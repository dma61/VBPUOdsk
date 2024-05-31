# Release notes 31 Mei 2024 

## Inleiding
--------------

De JSON-schema’s die horen bij de mei release van de VBPUO-standaard zijn inmiddels gepubliceerd op de GitHub omgeving. De bijbehorende nieuwe versie van de handleiding "20240527 Handleiding Standaard datauitwisseling VB-PUO Mei release" is gemaild en wordt binnenkort op de betreffende SIVI-Webpagina gepubliceerd. Schematische overzichten van de SPR-berichten en het Feedbackbericht zijn inmiddels gepubliceerd op de GitHub-WIKI onder “berichtenoverzicht”.

## Wijzigingen

In deze release zijn de onderstaande wijzigingen doorgevoerd. Voor gedetailleerde informatie verwijzen we naar de bijbehorende issues op de GitHub-pagina (het overzicht is te vinden op: ["mijlpaal" / "milestone" 202405](https://github.com/org/repo/milestone/202405)).

- **[Issue #31](https://github.com/org/repo/issues/31)**: De tabel AFDIDP is gekoppeld aan het attribuut PuvCode zodat alle bekende Nederlandse pensioenuitvoerders kunnen worden geselecteerd.
- **[Issue #49](https://github.com/org/repo/issues/49)**: De afdDefinitionName en afdDefinitionVersion zijn – handmatig – toegevoegd aan de JSON-schema’s als constanten.
- **[Issue #50](https://github.com/org/repo/issues/50) en [#54](https://github.com/org/repo/issues/54)**: Hoger maximum aantal occurrence (99999) voor pension.cohort en financialTransaction.payment.
- **[Issue #16](https://github.com/org/repo/issues/16)**: Toelichting op gebruik van applicationSendername. Binnen de kaders van VBPUO is dit gegeven uitsluitend beschikbaar in party.sender.
- **[Issue #52](https://github.com/org/repo/issues/52)**: Introductie feedbackbericht. Als gevolg daarvan wordt het error blok verwijderd uit de (14) reguliere berichten. De beschrijvingen van de gegevens in het feedbackbericht kunnen verschillen van die van de andere berichten.
- **[Issue #35](https://github.com/org/repo/issues/35)**: Toevoeging in de documentatie; bij het terugkoppelen over fouten wordt het betreffende onjuiste bericht NIET meegezonden.
- **[Issue #12](https://github.com/org/repo/issues/12)**: Toevoeging in de documentatie; als een niet-verplicht attribuut geen waarde heeft, moet het volledig worden weggelaten uit het JSON-bericht.

## Overige (documentatie) wijzigingen/toevoegingen

- Functioneel identieke berichten kunnen naar meerdere partijen moeten worden verzonden. Iedere partij ontvangt berichten altijd direct van de afzender!
- Een feedbackbericht verwijst altijd – in commonFunctional.originalMessageId – naar het bericht Id (commonTechnical.messageId) waar het een reactie op is.

## Vervolg

Komende tijd worden nog de voorbeeldberichten bijgewerkt, overzicht schema’s toegevoegd en worden de validaties bijgesteld en waar mogelijk omgezet naar JMESPath zodat ze aansluiten op AFD 2.0 standaard. Met de nu verwerkte aanpassingen zijn de openstaande issues met betrekking tot de SPR-berichten verwerkt.

Versie 1.08 van de OpenApi Specificatie is inmiddels gepubliceerd op de GitHub-omgeving. Deze specificatie is nog in ontwikkeling.

Referentie gegevens: 20240531 Json schema commit (mei release) / AOS 001.001 / "20240527 Handleiding Standaard datauitwisseling VB-PUO Mei release"

# Release notes May 31, 2024 (English version)

## Introduction
--------------

The JSON schemas related to the May release of the VBPUO standard have been published on the GitHub environment. The accompanying new version of the manual "20240527 Handleiding Standaard datauitwisseling VB-PUO Mei release" has been emailed and will soon be published on the relevant SIVI web page. Schematic overviews of the SPR messages and the Feedback message have been published on the GitHub WIKI under "berichtenoverzicht" (message overview).

## Changes

The following changes have been implemented in this release. For detailed information, please refer to the associated issues on the GitHub page (the overview can be found at: ["milestone" 202405](https://github.com/org/repo/milestone/202405)).

- **[Issue #31](https://github.com/org/repo/issues/31)**: The AFDIDP table is linked to the PuvCode attribute so that all known Dutch pension providers can be selected.
- **[Issue #49](https://github.com/org/repo/issues/49)**: The afdDefinitionName and afdDefinitionVersion have been manually added to the JSON schemas as constants.
- **[Issue #50](https://github.com/org/repo/issues/50) and [#54](https://github.com/org/repo/issues/54)**: Higher maximum number of occurrences (99999) for pension.cohort and financialTransaction.payment.
- **[Issue #16](https://github.com/org/repo/issues/16)**: Explanation on the use of applicationSendername. Within the framework of VBPUO, this data is only available in party.sender.
- **[Issue #52](https://github.com/org/repo/issues/52)**: Introduction feedback message. Consequently, the error block is removed from the (14) regular messages. The descriptions of the data in the feedback message may differ from those in the other messages.
- **[Issue #35](https://github.com/org/repo/issues/35)**: Addition in the documentation; when reporting errors, the erroneous message is NOT sent.
- **[Issue #12](https://github.com/org/repo/issues/12)**: Addition in the documentation; if a non-required attribute has no value, it must be completely omitted from the JSON message.

## Other (documentation) changes/additions

- Functionally identical messages may need to be sent to multiple parties. Each party always receives messages directly from the sender!
- A feedback message always refers – in commonFunctional.originalMessageId – to the message ID (commonTechnical.messageId) to which it is a response.

## Next Steps

In the coming period, the example messages will be updated, schema overviews will be added, and the validations will be adjusted and, where possible, converted to JMESPath to align with the AFD 2.0 standard. With the changes now implemented, the outstanding issues related to the SPR messages have been addressed.

Version 1.08 of the OpenApi Specification has been published on the GitHub environment. This specification is still under development.

Reference data: 20240531 Json schema commit (May release) / AOS 001.001 / "20240527 Handleiding Standaard datauitwisseling VB-PUO Mei release"
