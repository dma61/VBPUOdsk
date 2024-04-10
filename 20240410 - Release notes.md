# Release notes 10 april 2024 (April 2024)

## Inleiding
--------------

## Overzicht van wijzigingen

De volgende wijzigingen zijn doorgevoerd in het kader van de ["mijlpaal" / "milestone" 202404](https://github.com/dma61/VBPUOdsk/issues?q=is:issue%20milestone:%22202404%20release%22%20). Voor gedetailleerde informatie verwijzen we naar de bijbehorende issues op de GitHub-pagina.

- **[Issue #11](https://github.com/dma61/VBPUOdsk/issues/11):** De veldlengte van `afdDefinitionName` is vergroot naar 80 posities om te voldoen aan de behoefte voor meer posities.
  
- **[Issues #14, #21, #33](https://github.com/dma61/VBPUOdsk/issues/14):** De velden `refKeys` en `messageID` zijn nu verplicht en beperkt tot 70 posities om consistente entiteitidentificatie over tijd te waarborgen.
  
- **[Issue #18](https://github.com/dma61/VBPUOdsk/issues/18):** Het `resending`-attribuut is vervangen door een "function"-attribuut met waarde 54.

- **[Issue #39](https://github.com/dma61/VBPUOdsk/issues/39):** Verplicht stellen van `pensionschemeName & description` vergemakkelijkt de controle op aansluiting van opeenvolgende berichten.

- **[Issues #32, #34](https://github.com/dma61/VBPUOdsk/issues/32):** Lengtebeperkingen in attributen zijn verwijderd, in lijn met AFD 2.0 richtlijnen.

- **[Issue #38](https://github.com/dma61/VBPUOdsk/issues/38):** Het attribuut `PuvCode` is toegevoegd aan `party.pensionprovider`, waarmee de refKey voor deze entiteit vervalt.

- **[Issue #31](https://github.com/dma61/VBPUOdsk/issues/31):** Ter illustratie zijn enkele `puvCode`-codes opgenomen, vooruitlopend op de operationele status per mei 2024.

- **[Issue #35](https://github.com/dma61/VBPUOdsk/issues/35):** Gebruiksinstructies voor de errorsectie binnen de JSON-schema's zijn verduidelijkt.

- **[Issue #29](https://github.com/dma61/VBPUOdsk/issues/29):** De lengte van "error omschrijving" is gewijzigd naar 300 posities.

- **[Issue #26](https://github.com/dma61/VBPUOdsk/issues/26):** Het maximale aantal cohorten is verhoogd naar 999.

- **[Issue #30](https://github.com/dma61/VBPUOdsk/issues/30):** Inhoudelijke errorcodes zijn uitgebreid, met verwijdering van code 10.

- **[Issue #12](https://github.com/dma61/VBPUOdsk/issues/14):** Aanbevolen wordt om lege waarden in optionele attributen te vermijden.

- **[Issue #9](https://github.com/dma61/VBPUOdsk/issues/9):** Entiteiten binnen SIVI AFS zijn altijd gedefinieerd als een array.

- **[Issue #8](https://github.com/dma61/VBPUOdsk/issues/8):** Voor pensioenprojecties is bericht 3, 0001c uitgebreid om toekomstige uitkeringsstromen efficiënter mee te kunnen geven.

- **[Issue #6](https://github.com/dma61/VBPUOdsk/issues/6):** Er zijn diverse attributen toegevoegd om de herkenbaarheid van de cohorten te verbeteren.

- **[Issue #44](https://github.com/dma61/VBPUOdsk/issues/44):** De attributen `DOCFLNM` en `DOCEXT` zijn aangepast. `fileName` en `fileExtension` zijn nu vrij formaat stringvelden, afgestemd met AFD 2.0 richtlijnen.

- **Voortschrijdend inzicht:** `messageVersion` (commonTechnical) is vervangen door `afdDefinitionVersion` (commonFunctional), wat beter voldoet aan het beoogde doel.

- **[Issue #3](https://github.com/dma61/VBPUOdsk/issues/3):** Alle datumgerelateerde attributen zijn gestandaardiseerd als "date".

- **[Issue #2](https://github.com/dma61/VBPUOdsk/issues/2):** Alle RSIN-nummers zijn nu van het type string.

- **[Issues #4, #7](https://github.com/dma61/VBPUOdsk/issues/14):** De kardinaliteit van cohorten in de SPR-berichten is aangepast voor verschillende berichttypen.

- **[Issues #5, #10, #13, #19](https://github.com/dma61/VBPUOdsk/issues/19):** Aanpassingen in de contactgegevens zijn doorgevoerd.

- **Aantal mogelijke ontvangers:** Het is gewijzigd dat een bericht nu slechts één ontvanger heeft.

- **Berichten aan LDI-partijen:** Het is nu mogelijk dat berichten, naast de genoemde partijen, ook naar zogenaamde LDI-partijen gestuurd kunnen worden. Partijen ontvangen berichten direct van de verzender.

## Documentatie van bericht 2 "Cashflow" (0001b)

Naast bovengenoemde wijzigingen is de tekst over prospectieve en retrospectieve benaderingen aangepast in de documentatie van bericht 2 "Cashflow" (0001b), wat de duidelijkheid ten goede komt.




------------------


