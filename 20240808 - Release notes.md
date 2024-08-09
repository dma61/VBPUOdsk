# Release notes Juli 2024 

## Inleiding
--------------

De JSON-schema’s die horen bij de Juli release van de VBPUO-standaard zijn inmiddels gepubliceerd op de GitHub omgeving. De bijbehorende nieuwe versie van de handleiding "20240809 Handleiding Standaard datauitwisseling VB-PUO Juli release" is gemaild en wordt binnenkort op de betreffende SIVI-Webpagina gepubliceerd. 

## Wijzigingen

In deze release zijn de onderstaande wijzigingen doorgevoerd. Voor gedetailleerde informatie verwijzen we naar de bijbehorende issues op de GitHub-pagina (het overzicht is te vinden op: ["mijlpaal" / "milestone" 202407](https://github.com/dma61/VBPUOdsk/milestone/4).

- **[Issue #62](https://github.com/org/repo/issues/62)**: RSIN nummer op 9 posities gesteld conform beschrijving: https://www.sdu.nl/content/rsin-doet-intrede.
- **[Issue #56](https://github.com/org/repo/issues/56)**: In bericht 2 (cashflow) zijn - en blijven - bedragen en datums onverplicht. Het is aan partijen om te bepalen welke combinaties van bedrag/datum zij (functioneel) verplichten. De documentatie is aangepast.
- **[Issue #42](https://github.com/org/repo/issues/42)**: Aan (FPR) bericht bericht 13. Waarde-informatie beleggingspool (00555b) zijn de attributen marketValueAmount, preliminaryUnitValueAmount en numberOfUnits toegevoegd.

- ** OAS directory is hernoemd: "(in ontwikkeling") is verwijderd
- ** Omschrijving "afdDefinitionVersion" is gewijzigd van: "Versie van de standaard" in "Versie van het JSON schema" 

pm ook de voorbeeldberichten zijn bijgewerkt.

## Overige (documentatie) wijzigingen/toevoegingen

- Aan hoofdstuk 7 is de paragraaf: 7.4.2 API-implementatie en back-up toegevoegd.
- De hoofdstukken over "Governance" en "Wijzigingsprocedure" zijn verwijderd. 

## Vervolg

Komende tijd worden nog de voorbeeldberichten toegevoegd en overzicht schema’s toegevoegd. 

## Versies OAS en JSON schemas in GitHub release 2024_07, | Tag v1.1.0
Open API specificatie 1.08 maakt deel uit van deze versie
JSON-schemas berichten 1 t/m 14 (AOS) 001.02 (afdDefinitionVersion)
JSON-schema VBPUO_Feedback_Message (AOS) 001.00 (afdDefinitionVersion)

Referentie gegevens: 20240809 Json schema commit (juli release) / AOS 001.02 - Model base 20240808 0907 / OAS 1.08 / "20240809 Handleiding Standaard datauitwisseling VB-PUO Juli release"
GitHub releases en releasenotes: https://github.com/dma61/VBPUOdsk/releases 

# Release Notes July 2024 (English version)

## Introduction
--------------

The JSON schemas associated with the July release of the VBPUO standard have now been published on the GitHub environment. The corresponding new version of the manual "20240809 Handleiding Standaard datauitwisseling VB-PUO Juli release" has been emailed and will soon be published on the relevant SIVI webpage.

## Changes

The following changes have been implemented in this release. For detailed information, please refer to the related issues on the GitHub page (the overview can be found at: ["milestone" 202407](https://github.com/dma61/VBPUOdsk/milestone/4)).

- **[Issue #62](https://github.com/org/repo/issues/62)**: RSIN number formatted to 9 positions as described here: https://www.sdu.nl/content/rsin-doet-intrede.
- **[Issue #56](https://github.com/org/repo/issues/56)**: In message 2 (cashflow), amounts and dates are - and will remain - optional. It is up to the parties to decide which combinations of amount/date they (functionally) require. The documentation has been updated.
- **[Issue #42](https://github.com/org/repo/issues/42)**: In (FPR) message 13, value information for investment pool (00555b), the attributes marketValueAmount, preliminaryUnitValueAmount, and numberOfUnits have been added.

- ** OAS directory has been renamed: "in development" has been removed.
- ** Description of "afdDefinitionVersion" has been changed from: "Version of the standard" to "Version of the JSON schema".

Sample messages have also been updated.

## Other (documentation) changes/additions

- A new paragraph: 7.4.2 API Implementation and Backup has been added to Chapter 7.
- The chapters on "Governance" and "Wijzigingsprocedure" have been removed.

## Next Steps

In the coming period, the sample messages and schema overview will be added.

## Versions of OAS and JSON Schemas in GitHub Release 2024_07, | Tag v1.1.0
Open API specification 1.08 is part of this version.
JSON schemas messages 1 to 14 (AOS) 001.02 (afdDefinitionVersion)
JSON schema VBPUO_Feedback_Message (AOS) 001.00 (afdDefinitionVersion)

Reference data: 20240809 JSON schema commit (July release) / AOS 001.02 - Model base 20240808 0907 / OAS 1.08 / "20240809 Guide for Standard Data Exchange VB-PUO July Release"
GitHub releases en releasenotes: https://github.com/dma61/VBPUOdsk/releases