# VBPUO-Bericht_3._Pensioenprojectie_(0001c) - Documentatie en Voorbeelden (v001.00)

Deze directory bevat de JSON Schema definitie, bijbehorende codelijsten, validatieregels en diverse voorbeeldbestanden voor het SIVI AOS bericht 'Bericht 3 Pensioenprojectie (0001c)', versie 001.00. De voorbeelden illustreren zowel een volledig bericht als de toepassing van chunking.

## Bestandsbeschrijving

Hieronder volgt een overzicht van de bestanden in deze directory:

*   **`VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c).json`**
    *   Het hoofd JSON Schema dat de structuur, datatypen en verplichte velden van het bericht definieert. Dit schema refereert naar het `afdCodelists`-bestand voor de definitie van specifieke codelijsten.

*   **`VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c)-afdCodelists.json`**
    *   JSON Schema bestand met definities voor de gebruikte codelijsten (bijv. `AFDIDP` voor pensioenuitvoerders, `AFDRES` voor reservetypes). Dit bestand wordt door het hoofdschema (`...0001c.json`) gerefereerd via `$ref`.

*   **`VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c)-validationRules.json`**
    *   Bevat aanvullende (business) validatieregels die verder gaan dan de structurele validatie van het JSON Schema. Dit kan bijvoorbeeld regels bevatten voor conditionele verplichtingen of complexere cross-field validaties.

*   **`Voorbeeldbereicht_3.json`**
    *   Een algemeen voorbeeld van een volledig, niet-gechunked `Bericht_3._Pensioenprojectie_(0001c)`. Dit kan gebruikt worden voor een basisvalidatie tegen het schema.

*   **`Voorbeeldbereicht_chunking-base-originalmsg.json`**
    *   Het volledige, geïntegreerde bericht (versie 001.00) waaruit de onderstaande chunk-voorbeelden zijn afgeleid. Dit dient als het 'bron'-bericht voor de chunking-demonstratie en bevat alle data (o.a. beide cohorten) in één bestand.

*   **`Voorbeeldbereicht_chunk_template.json`**
    *   Voorbeeld van de **eerste chunk (chunk 1 van 3)** in een gesplitst bericht.
    *   Deze chunk bevat de algemene structuur en metadata (commonFunctional, commonTechnical, party-informatie, pensionScheme-shell), maar nog geen specifieke cohortdata (de `pension`-array binnen `pensionScheme` is leeg).
    *   Het `chunking`-object is aanwezig en correct ingevuld (`chunkSequenceNumber: 1`, `totalNumberOfChunks: 3`).

*   **`Voorbeeldbereicht_chunk_2-cohortdata.json`**
    *   Voorbeeld van de **tweede chunk (chunk 2 van 3)**.
    *   Deze chunk levert de data voor het eerste cohort (`COHORT-001`) en herhaalt de omliggende structuur om individueel valideerbaar te zijn.
    *   Het `chunking`-object specificeert `chunkSequenceNumber: 2`.
    *   De `chunkFragmentPaths` verwijzen naar de relevante data-elementen in deze chunk.

*   **`Voorbeeldbereicht_chunk_3-cohortdata.json`**
    *   Voorbeeld van de **derde en laatste chunk (chunk 3 van 3)**.
    *   Deze chunk levert de data voor het tweede cohort (`COHORT-002`) en herhaalt de omliggende structuur.
    *   Het `chunking`-object specificeert `chunkSequenceNumber: 3`.
    *   De `chunkFragmentPaths` verwijzen naar de relevante data-elementen in deze chunk.

## Chunking Mechanisme

De chunking voorbeelden (`Voorbeeldbereicht_chunk_...json`) demonstreren hoe een groot bericht, zoals `Voorbeeldbereicht_chunking-base-originalmsg.json`, kan worden opgesplitst in kleinere, afzonderlijk te verwerken delen (chunks).

Belangrijke aspecten:
1.  **Elke chunk is individueel valideerbaar** tegen het hoofdschema (`VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c).json`). Dit wordt bereikt door de volledige omliggende berichtstructuur in elke chunk te herhalen.
2.  Het `chunking`-object binnen elke chunk bevat metadata:
    *   `currentChunkId`: Een unieke ID voor de specifieke chunk.
    *   `chunkSequenceNumber`: Het volgnummer van de chunk in de reeks.
    *   `totalNumberOfChunks`: Het totale aantal chunks waarin het originele bericht is opgesplitst.
    *   `chunkFragmentPaths`: Een array van JMESPath-expressies die verwijzen naar de specifieke data-elementen in *deze* chunk die nieuw zijn of de kern van de chunk-inhoud vormen. De ontvanger gebruikt deze paden om het bericht te reconstrueren.
3.  Het `messageId` (binnen `commonTechnical`) is identiek voor alle chunks die bij hetzelfde oorspronkelijke bericht horen.

## Validatie

Om de voorbeeldbestanden te valideren:
1.  Gebruik een JSON Schema validator.
2.  Voor de **chunk-voorbeelden** geldt dat elk individueel chunk-bestand moet valideren tegen `VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c).json`.
3.  Zorg ervoor dat de validator het `VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c)-afdCodelists.json` bestand kan vinden en gebruiken om de `$ref` verwijzingen naar codelijsten correct op te lossen. Dit kan vaak door de bestanden in dezelfde directory te plaatsen of de resolver van de validator correct te configureren.
4.  De `VBPUO-001.00-Bericht_3._Pensioenprojectie_(0001c)-validationRules.json` bevat aanvullende regels die mogelijk een specifieke tool of engine vereisen (bijv. een custom validator of een engine die Schematron-achtige regels op JSON kan toepassen).

## Structuur van het Bericht

Het bericht `Bericht_3 Pensioenprojectie (0001c)` is ontworpen voor het uitwisselen van pensioenprojectiegegevens. Kernonderdelen zijn:
*   `commonFunctional`: Algemene functionele metadata over het bericht.
*   `commonTechnical`: Algemene technische metadata, inclusief partij-informatie (zender, ontvanger).
*   `party`: Bevat de `partyPensionProvider` (pensioenuitvoerder).
    *   `pensionScheme`: Details over de pensioenregeling.
        *   `financialInformation`: Financiële rapportageperiode.
        *   `financialTransaction`: Financiële transacties op regelingniveau.
        *   `pension`: Een array van `pensionCohort` objecten, die elk de projectiedata voor een specifiek cohort bevatten, inclusief eventuele `financialTransaction` objecten specifiek voor dat cohort.
*   `chunking` (optioneel): Aanwezig indien het bericht een chunk is van een groter geheel.
*   `document` (optioneel): Voor eventuele bijlagen.

---
Dit README-bestand dient als startpunt. Afhankelijk van de gebruikte validatietools of specifieke workflows kunnen verdere details of instructies worden toegevoegd.