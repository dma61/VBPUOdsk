# Release notes 10 april 2024 (April 2024)

## Inleiding
--------------

De nieuwe JSON-schemas zijn in middels beschikbaar. De naamgeving van de berichten is aangepast zodat deze beter aansluit op de AFD-2.0 onderhouds werkwijze. Daarbij zijn ook de spaties in berichtnamen en bestandsnamen vervangen door "_". De wijzigingshistorie is gehandhaafd.

## Overzicht van wijzigingen

De volgende wijzigingen zijn doorgevoerd in het kader van de ["mijlpaal" / "milestone" 202404](https://github.com/dma61/VBPUOdsk/issues?q=is:issue%20milestone:%22202404%20release%22%20). Voor gedetailleerde informatie verwijzen we naar de bijbehorende issues op de GitHub-pagina.

- **[Issue #11](https://github.com/dma61/VBPUOdsk/issues/11):** De veldlengte van `afdDefinitionName` is vergroot naar 80 posities om te voldoen aan de behoefte voor meer posities.
  
- **[Issues #14](https://github.com/dma61/VBPUOdsk/issues/14), [#21](https://github.com/dma61/VBPUOdsk/issues/21), [#33](https://github.com/dma61/VBPUOdsk/issues/33):** De velden `refKeys` en `messageID` zijn nu verplicht en beperkt tot 70 posities. Ze vertegenwoordigen de entiteitidentificatie in de tijd. Dat brengt met zich mee dat bijvoorbeeld de combinatie van een (functionele) schemanaam en de refKey op een pensioenschema mag niet veranderen. Bij cosmetische hernoemingen / naamswijzigingen in "partij", "schema", "cohort" enzovoort kan de bestaande refKey worden gehandhaafd. Als er echter sprake is van een inhoudelijke wijziging van bijvoorbeeld een schema dient een nieuwe refKey te worden gebruikt. P.m. als er geen functionele behoefte is aan een refKey, kan de refkey worden ingevuld met de waarde van bijvoorbeeld de RSIN, de beschrijving, enzovoort.

  
- **[Issue #18](https://github.com/dma61/VBPUOdsk/issues/18):** Het `resending`-attribuut is vervangen door het al bestaande `function`-attribuut met waarde 54.

- **[Issue #39](https://github.com/dma61/VBPUOdsk/issues/39):** Verplicht stellen van `pensionschemeName & description` vergemakkelijkt de controle op aansluiting van opeenvolgende berichten.

- **[Issues #32](https://github.com/dma61/VBPUOdsk/issues/32), [#34](https://github.com/dma61/VBPUOdsk/issues/34):**  De lengte beperkingen voor een aantal attributen zijn verwijderd op basis van AFD 2.0 richtlijnen. Er is geen veldlengte meer gespecificeerd voor booleans, decimale getallen (numbers), integers, datums en strings met een code- of optielijst.

- **[Issue #38](https://github.com/dma61/VBPUOdsk/issues/38):** Het attribuut `PuvCode` is toegevoegd aan `party.pensionprovider`. In de AFD 2.0 release van mei wordt aan deze code AFD 2.0 tabel AFDIDP gekoppeld met de unieke codes van pensioenuitvoerders. De code is verplicht omdat de party.pensionprovider altijd een NL pensioenuitvoerder is. Door de introductie van de `PuvCode` heeft de RefKey geen functie meer voor deze entiteit en vervalt.

- **[Issue #31](https://github.com/dma61/VBPUOdsk/issues/31):** Ter illustratie zijn enkele `puvCode`-codes opgenomen, vooruitlopend op de operationele status per mei 2024.

- **[Issue #35](https://github.com/dma61/VBPUOdsk/issues/35):** Gebruiksinstructies voor de errorsectie binnen de JSON-schema's zijn verduidelijkt. Het is niet nodig om het initiële bericht met de errormessage mee te sturen.(FAQ/WIKI item)

- **[Issue #29](https://github.com/dma61/VBPUOdsk/issues/29):** De lengte van "error omschrijving" is gewijzigd naar 300 posities.

- **[Issue #26](https://github.com/dma61/VBPUOdsk/issues/26):** Het maximale aantal cohorten is verhoogd naar 999.

- **[Issue #30](https://github.com/dma61/VBPUOdsk/issues/30):** Inhoudelijke errorcodes zijn uitgebreid, met verwijdering van code 10. Uit het JSON-schema is verwijderd: code 10 (functionele fout). Code 10 wordt vervangen door de errorcodes: 12 (Inhoudelijke fout), 13 (Volgorderlijke fout) en 14 (Data zender en ontvanger matchen niet). Deze zijn toegevoegd aan ADNFTM en de JSON-schema's.

- **[Issue #12](https://github.com/dma61/VBPUOdsk/issues/14):** Aanbevolen wordt om lege waarden in optionele attributen te vermijden.

- **[Issue #9](https://github.com/dma61/VBPUOdsk/issues/9):** Entiteiten binnen SIVI AFS zijn altijd gedefinieerd als een array, ook als deze maar één object bevatten, of maar één soort entityType (zoals pensionProvider onder party).

- **[Issue #8](https://github.com/dma61/VBPUOdsk/issues/8):** Voor pensioenprojecties is bericht 3, 0001c uitgebreid om toekomstige uitkeringsstromen efficiënter mee te kunnen geven.

- **[Issue #6](https://github.com/dma61/VBPUOdsk/issues/6):** Er zijn diverse attributen toegevoegd om de herkenbaarheid van de cohorten te verbeteren.

- **[Issue #44](https://github.com/dma61/VBPUOdsk/issues/44):** De codelijsten `DOCFLNM` en `DOCEXT` zijn verwijderd. `fileName` en `fileExtension` zijn nu vrij formaat stringvelden. In het JSON-schema is de fileExtention beperkt tot: pdf, csv, txt.

- **Voortschrijdend inzicht:** `messageVersion` (commonTechnical) is vervangen door `afdDefinitionVersion` (commonFunctional), wat beter voldoet aan het beoogde doel.

- **[Issue #3](https://github.com/dma61/VBPUOdsk/issues/3):** Alle datumgerelateerde attributen zijn gestandaardiseerd als "date".

- **[Issue #2](https://github.com/dma61/VBPUOdsk/issues/2):** Alle RSIN-nummers zijn nu van het type string.

- **[Issues #4](https://github.com/dma61/VBPUOdsk/issues/4), [#7](https://github.com/dma61/VBPUOdsk/issues/7):** De kardinaliteit van cohorten in de SPR-berichten is aangepast voor verschillende berichttypen. Pension.cohort is verplicht voor bericht 1 (0001a) en optioneel voor bericht 2 (0001b), 3 (0001c) en 2 (00002).

- **[Issues #5](https://github.com/dma61/VBPUOdsk/issues/5), [#10](https://github.com/dma61/VBPUOdsk/issues/10), [#13](https://github.com/dma61/VBPUOdsk/issues/13), [#19](https://github.com/dma61/VBPUOdsk/issues/19):** Aanpassingen in de contactgegevens zijn doorgevoerd.

- **Aantal mogelijke ontvangers:** Aantal mogelijke ontvangers is gewijzigd naar 1. Een bericht heeft 1 ontvanger.

- **Berichten aan LDI-partijen:** Berichten kunnen naast de genoemde partijen ook worden gestuurd naar zogenoemde LDI-partijen. Partijen ontvangen berichten steeds direct van de verzender. 

## Documentatie van bericht 2 "Cashflow" (0001b)

Naast bovengenoemde wijzigingen is de tekst over prospectieve en retrospectieve benaderingen aangepast in de documentatie van bericht 2 "Cashflow" (0001b).




------------------


