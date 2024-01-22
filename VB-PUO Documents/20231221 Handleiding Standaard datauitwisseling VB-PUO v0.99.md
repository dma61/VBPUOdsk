![](RackMultipart20231222-1-avhyj4_html_58eca520b5f6d772.png)

![Shape1](RackMultipart20231222-1-avhyj4_html_3742ca558ba74c9d.gif)

![Shape2](RackMultipart20231222-1-avhyj4_html_45a4bc9e499ef5ae.gif)

## Standaard voor uitwisseling data tussen Vermogensbeheer en Pensioenuitvoering

![](RackMultipart20231222-1-avhyj4_html_d139616a39860196.png)

**Inhoud**

[1Inleiding 4](#_Toc154127502)

[1.1Context 4](#_Toc154127503)

[1.2Doel 4](#_Toc154127504)

[1.3Doelgroep 4](#_Toc154127505)

[1.4Opzet 5](#_Toc154127506)

[1.5Links 6](#_Toc154127507)

[1.6Bron afbeelding op titelpagina 6](#_Toc154127508)

[2Uitgangspunten 7](#_Toc154127509)

[2.1Aanleiding 7](#_Toc154127510)

[2.2Buiten scope 7](#_Toc154127511)

[2.3Uitgangspunten gegevensuitwisseling 8](#_Toc154127512)

[2.4Verduidelijking uitgangspunten gegevensuitwisseling 8](#_Toc154127513)

[2.5Deelnemer communicatie 9](#_Toc154127514)

[2.6Techniek 9](#_Toc154127515)

[2.7Governance en beheer 10](#_Toc154127516)

[3Processen & informatiestromen – Solidaire Premieregeling 11](#_Toc154127517)

[3.1Inleiding 11](#_Toc154127518)

[3.2Informatiestroom Fiduciair Manager en Beleggingsadministrateur 12](#_Toc154127519)

[3.2.1Informatiestroom 1a, vermogen 12](#_Toc154127520)

[3.2.2Informatiestroom 1b, in- en uitstroom ("Cashflow") 13](#_Toc154127521)

[3.2.3Informatiestroom 1c, geprojecteerde uitkeringen ("Pensioenprojectie") 14](#_Toc154127522)

[3.2.4Informatiestroom 2, Informatiebehoefte pensioenuitvoeringsorganisatie ("Rendementsinformatie") 14](#_Toc154127523)

[4Processen & informatiestromen – Flexibele Premieregeling 16](#_Toc154127524)

[4.1Inleiding 16](#_Toc154127525)

[4.2Model 1 eenvoudiger, direct ordermodel 16](#_Toc154127526)

[4.3Model 2 uitgebreider, gelaagd ordermodel 18](#_Toc154127527)

[4.4Informatiestroom model 1 (1a en 1b) 20](#_Toc154127528)

[4.4.1Informatiestroom van Pensioenuitvoeringsorganisatie naar Brokers/Transfer Agents/Order Desks 1a 22](#_Toc154127529)

[4.4.2Informatiestroom van brokers/transfer agents/order desks naar pensioenuitvoeringsorganisatie 1b 22](#_Toc154127530)

[4.5Informatiestroom model 2 22](#_Toc154127531)

[4.5.1Informatiebehoefte administrateur cohortenpools en beleggingspools 25](#_Toc154127532)

[4.5.2Reconciliatie administrateur van cohortenpools en beleggingspools, fiduciair manager en beleggingsadministrateur 26](#_Toc154127533)

[4.5.3Informatie aansturen beleggingspools 26](#_Toc154127534)

[4.5.4Rebalancing cohortenpools 27](#_Toc154127535)

[4.5.5Doorgeven waardes per beleggingspool en per cohortenpool 27](#_Toc154127536)

[4.5.6Betaalinstructies onttrekkingen 28](#_Toc154127537)

[5Aanpak/opzet gegevensstandaard 29](#_Toc154127538)

[5.1Maak beschrijvingen van de processen en informatiestromen 29](#_Toc154127539)

[5.2Stel een lijst op met entiteiten en bijbehorende attributen 29](#_Toc154127540)

[5.3Bepaal de basisstructuur van de berichten 30](#_Toc154127541)

[5.4Geef aan welke berichten nodig zijn. 30](#_Toc154127542)

[5.5Maak een kruistabel tussen de basisstructuur en de berichten. 30](#_Toc154127543)

[5.6Relatie met SIVI AFS 31](#_Toc154127544)

[6Functionele specificaties 32](#_Toc154127545)

[6.1Datadictionary 32](#_Toc154127546)

[6.2Entiteiten en entiteitstypen 33](#_Toc154127547)

[6.3Attributen in entiteiten.entiteitstypen 34](#_Toc154127548)

[6.4Berichten 42](#_Toc154127549)

[6.4.1Basisbericht 48](#_Toc154127550)

[6.4.2Berichtstructuur 1. Vermogen (0001a) 49](#_Toc154127551)

[6.4.3Berichtstructuur 2. Cashflow (0001b) 50](#_Toc154127552)

[6.4.4Berichtstructuur 3. Pensioenprojectie (0001c) 51](#_Toc154127553)

[6.4.5Berichtstructuur 4. Rendementsinformatie (00002) 51](#_Toc154127554)

[6.4.6Berichtstructuur 5. Orderopdracht (00541) 52](#_Toc154127555)

[6.4.7Berichtstructuur 6. Ordersettlement (00542) 52](#_Toc154127556)

[6.4.8Berichtstructuur 7. Mutatiesaldi (00551) 53](#_Toc154127557)

[6.4.9Berichtstructuur 8. Reconciliatie-informatie (00552a) 53](#_Toc154127558)

[6.4.10Berichtstructuur 9. PUO-reconciliatie-informatie (00552b) 54](#_Toc154127559)

[6.4.11Berichtstructuur 10. Stuurinformatiebeleggingspools (00553) 54](#_Toc154127560)

[6.4.12Berichtstructuur 11. Rebalancinginformatie (00554) 55](#_Toc154127561)

[6.4.13Berichtstructuur 12. Waarde-informatie cohortenpool (00555a) 55](#_Toc154127562)

[6.4.14Berichtstructuur 13. Waarde-informatie beleggingspool (00555b) 56](#_Toc154127563)

[6.4.15Berichtstructuur 14. Betaalinformatie (00556) 56](#_Toc154127564)

[6.5Kruisreferentie Attributen & berichten 57](#_Toc154127565)

[7Technische specificaties 64](#_Toc154127566)

[7.1Berichten & regelingen 64](#_Toc154127567)

[7.2Validaties 64](#_Toc154127568)

[7.3JSON 64](#_Toc154127569)

[8Governance en beheer 65](#_Toc154127570)

[8.1Inleiding 65](#_Toc154127571)

[8.2Visie beheerorganisatie 65](#_Toc154127572)

[8.3Taken beheerorganisatie 65](#_Toc154127573)

[8.4Inrichting beheerorganisatie 66](#_Toc154127574)

[8.5Klankbordgroep 66](#_Toc154127575)

[8.6Contactgegevens SIVI 66](#_Toc154127576)

[9Wijzigingsprocedure 67](#_Toc154127577)

[9.1Intake 67](#_Toc154127578)

[9.2Besluitvorming 67](#_Toc154127579)

[9.3Verwerken 67](#_Toc154127580)

[9.4Communicatie 67](#_Toc154127581)

[10Bijlagen 68](#_Toc154127582)

[10.1Begrippenlijst/Afkortingenlijst Vermogensbeheer & Pensioenuitvoering 68](#_Toc154127583)

[10.2Begrippenlijst gegevensuitwisseling op basis van standaarden 74](#_Toc154127584)

[10.3Proces flow & data-uitwisseling FPR 77](#_Toc154127585)

[10.4Huishoudelijk Reglement Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering 80](#_Toc154127586)

[10.4.1Inleiding 80](#_Toc154127587)

[10.4.2Begrippenlijst 80](#_Toc154127588)

[10.4.3Samenstelling 80](#_Toc154127589)

[10.4.4Wijzigingen samenstelling 81](#_Toc154127590)

[10.4.5Vergaderingen 81](#_Toc154127591)

[10.4.6Taken 83](#_Toc154127592)

[10.4.7Besluitvorming 83](#_Toc154127593)

[10.4.8Overig 84](#_Toc154127594)

[10.5Onderdelen Standaard Vermogensbeheer Pensioenuitvoering 84](#_Toc154127595)

[10.6Vertaaltabel van functionele attributen naar AFD2.0 attributen. 87](#_Toc154127596)

#

# 1Inleiding

**In deze inleiding bespreken we de context, het doel en de doelgroep van deze handleiding. Tevens presenteren we (vrij uitgebreid) de opzet van de handleiding.**

## 1.1Context

**Eindrapport**

Begin september 2023 verscheen het eindrapport ''[Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380).

Met de invoering/uitvoering van de Wet Toekomst Pensioenen (Wtp) is strakkere aansluiting tussen fondsvermogen en collectieve administratie van persoonlijke pensioenvermogens noodzakelijk. Daarmee neemt de frequentie van de noodzakelijke informatie-uitwisseling toe. In de huidige praktijk regelen pensioenuitvoerders en vermogensbeheerpartijen onderling de informatie-uitwisseling. Door de intensivering van de informatie-uitwisseling is standaardisatie van de informatie-uitwisseling gewenst.

Het genoemde eindrapport beschrijft de voor de uitwisseling benodigde functionele gegevens, de informatiestromen en de, daarvan medeafhankelijke, deelnemercommunicatie.

De gegevens en informatiestromen zijn uitgewerkt voor zowel de solidaire premieregeling als de flexibele premieregeling.

Het eindrapport is gebaseerd op bijdragen van diverse organisaties, waaronder APG, AZL, Caceis, Capgemini, H&C, Van Lanschot Kempen IM, MN, Pensioenfederatie, SIVI en TKP. Middels een consultatieronde zijn onder andere nog diverse andere uitvoeringsorganisaties, fiduciairs, custodians en pensioenfondsen betrokken. Deze consultatieronde is afgerond en de input daaruit is verwerkt.

**Vervolg**

Het eindrapport vertaalt SIVI naar een gegevensstandaard gebaseerd op AFD 2.0 uit SVI AFS. Bij deze gegevensstandaard hoort een basisbericht waar we 14 berichten van afleiden. De berichten worden uitgewisseld via beveiligde bestandsuitwisseling dan wel Webservices (API's).

**Governance en beheer**

De standaard vertegenwoordigt een gezamenlijk belang van pensioenuitvoering en vermogensbeheer waarvoor het bestuurlijk en het inhoudelijk beheer moet worden belegd. Na introductie van de standaard ontstaan nieuwe wensen die al dan niet in de standaard zullen moeten worden opgenomen.

Afgesproken is dat:

- Het eigenaarschap van de standaard bij de Pensioenfederatie berust.
- Inhoudelijk en bestuurlijk beheer rond de standaard vorm zal worden gegeven.
- De standaard beheerd wordt door beheerorganisatie SIVI.
- Een klankboordgroep zal worden ingesteld ter ondersteuning van het beheer (bemensing vanuit pensioenuitvoering en vermogensbeheer).

## 1.2Doel

Deze handleiding vormt een toelichting op de standaard voor datauitwisseling tussen vermogensbeheer en pensioenuitvoering. De handleiding geeft:

- Analisten en ontwikkelaars een handvat om de standaard te (laten) implementeren;
- Betrokkenen inzicht in het beheer van de standaard.

## 1.3Doelgroep

Deze handleiding is bestemd voor consultants, analisten en ontwikkelaars die betrokken zijn bij de implementatie van de standaard voor datauitwisseling tussen vermogensbeheer- en pensioenuitvoeringspartijen.

## 1.4Opzet

| **Hoofdstuk** | **Inhoud** |
| --- | --- |
| **1** | **Inleiding** In deze inleiding bespreken we de context, het doel en de doelgroep van deze handleiding. Tevens presenteren we (vrij uitgebreid) de opzet van de handleiding.
 |
| --- | --- |
| **2** | **Uitgangspunten** In dit hoofdstuk bespreken we de belangrijkste uitgangspunten bij de ontwikkeling, opzet en besturing van de standaard. Dit is vooral gebaseerd op **[Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380).**
 |
| **3** | **Processen & informatiestromen – Solidaire premieregeling** De processen & informatiestromen staan uitvoering beschreven in het rapport ''**[Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380):**Hoofdstuk 4: Solidaire premieregeling.
 |
| **4** | **Processen & informatiestromen – Flexibele premieregeling** De processen & informatiestromen staan uitvoering beschreven in het rapport ''**[Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380):**Hoofdstuk 5: Flexibele premieregeling.
 |
| **5** | **Aanpak/opzet gegevensstandaard** In dit hoofdstuk leggen we uit hoe we komen tot specificaties van de berichten.Stappen om te komen tot de functionele specificaties van de berichten:
- Maak beschrijvingen van de processen en informatiestromen.
- Stel een lijst op met entiteiten en bijbehorende attributen.
- Bepaal de basisstructuur van de berichten.
- Geef aan welke berichten nodig zijn.
- Maak een kruistabel tussen de basisstructuur en de berichten.

De relatie met SIVI AFS leggen we uit. De bouwstenen uit SIVI AFS (AFD 2.0) gebruiken we om tot technische specificaties te komen.
 |
| **6** | **Functionele specificaties** In dit hoofdstuk volgen de functionele specificaties:
- Datadictionary;
- Basisbericht;
- Kruisreferentie basisbericht & berichten.

 |
| **7** | **Technische specificaties** De technische gegevensspecificaties komen beschikbaar op basis van AFD 2.0 uit SIVI AFS. In dit hoofdstuk kan de lezer kennisnemen van een toelichting.
 |
| **8** | **Governance en beheer** Governance gaat over het optimaal inrichten van de organisatie van de community rond de standaard. Duidelijk moet zijn wie beslist wat uitgevoerd wordt met betrekking tot standaarden, en wie beslist hoe dit wordt uitgevoerd.
Dit hoofdstuk gaat voorts in op de beheersmatige processen rondom de standaarden. Het omvat alle activiteiten gericht op het aanpassen, uitbreiden, doorontwikkelen, beschikbaar stellen en houden van een (set van) berichten die steeds past bij de actuele behoefte van de belanghebbenden.
 |
| **9** | **Wijzigingsprocedure** Wijzigingen op de standaard raakt meerdere belanghebbenden. In de procedure van wijziging zijn hierom de belangen van alle deelnemende partijen vertegenwoordigd. Verzoeken en voorstellen voor wijzigingen zullen volgens onderstaande procedure worden behandeld. Een wijziging wordt afgehandeld via een viertal stappen:
1. Intake;
2. Besluitvorming;
3. Verwerken;
4. Communicatie.

 |
| 10 | **Bijlagen** In de bijlagen treft u de:
- Begrippenlijst/Afkortingenlijst Vermogensbeheer & Pensioenuitvoering;
- Begrippenlijst gegevensuitwisseling op basis van standaarden;
- Huishoudelijk reglement Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering.
Onderdelen Standaard Vermogensbeheer Pensioenuitvoering.
 |

## 1.5Links

Deze handleiding bevat links, veelal bronvermeldingen. Deze zijn **blauw** gekleurd. Door op de link te klikken komt de lezer bij de desbetreffende webpagina of het desbetreffende rapport/artikel.

## 1.6Bron afbeelding op titelpagina

[https://www.flaticon.com/free-icon/data-exchange\_4995192](https://www.flaticon.com/free-icon/data-exchange_4995192)

# 2Uitgangspunten

**In dit hoofdstuk bespreken we de belangrijkste uitgangspunten bij de ontwikkeling, opzet en besturing van de standaard. Dit is vooral gebaseerd op** **[Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380).**

## 2.1Aanleiding

Pensioenuitvoeringsorganisaties hebben regelmatig informatie nodig van fiduciair managers en/of beleggingsadministrateurs (vermogensbeheer) om de deelnemersadministratie van pensioenregelingen correct uit te kunnen voeren. Anderzijds hebben fiduciair managers (en vermogensbeheerders) informatie nodig om de middelen voor verschillende pensioenuitvoerders te kunnen beleggen binnen de kaders van het afgesproken beleggingsbeleid. De benodigde gegevensuitwisseling tussen pensioenuitvoeringsorganisaties, fiduciair managers en beleggingsadministrateurs (en vermogensbeheerders) is naar verwachting in alle gevallen zeer vergelijkbaar.

Met de invoering van de Wtp zal de informatiebehoefte wijzigen en zal de frequentie waarin informatie-uitwisseling gewenst is toenemen. De informatiebehoefte voor de pensioenuitvoeringsorganisaties, fiduciair managers en beleggingsadministrateurs ten behoeve van de dienstverlening aan pensioenuitvoerders komt in de basis sterk overeen. Eventuele verschillen in de informatie-uitwisseling zullen met name afhankelijk zijn van het type regeling dat wordt uitgevoerd.

In de opbouwfase van de flexibele premieregeling (FPR) zal de informatiebehoefte grotendeels overeenkomen met die van de huidige 'defined contribution' regelingen, mogelijk aangevuld met gegevens over risicodelingsreserve. Wat betreft de uitwisseling van gegevens tijdens de collectieve uitkeringsfase, zal deze in veel opzichten vergelijkbaar zijn met de uitkeringsfase van de solidaire premieregeling.

Voor de solidaire premieregeling (SPR) zal een geheel nieuwe datastroom moeten worden opgezet, zowel voor de opbouw-, als de uitkeringsfase. Er zal een strakkere aansluiting moeten zijn tussen het fondsvermogen dat door de fiduciair manager wordt belegd en de collectieve administratie van persoonlijke pensioenvermogens door de pensioenuitvoeringsorganisatie.

## 2.2Buiten scope

Buiten scope van de uitwerking van de informatie-uitwisseling vallen:

- De standaard voorziet in de noodzakelijke informatie-uitwisseling, de gegevensbehoefte, tussen pensioenuitvoeringsorganisaties en vermogensbeheerpartijen op de verschillende procesmomenten. De standaard voorziet in de gegevensbehoefte voor zowel Solidaire Premieregeling (SPR) als Flexibele Premieregeling (FPR). De exacte invulling van de gegevensuitwisseling tussen partijen wordt bepaald door contractuele afspraken tussen de samenwerkende pensioenuitvoerder en zijn vermogensbeheerpartners. Deze contractuele afspraken met betrekking tot het totale proces rondom vermogensbeheer vallen expliciet buiten de scope van de standaard.
- Processen die al lopen en in de basis niet veranderen, zoals de reconciliatie van de beleggingsadministratie tussen de fiduciair manager en de beleggingsadministrateur/asset service provider.
- Informatie die niet hoeft te worden uitgewisseld omdat deze slechts door één partij in de keten wordt gebruikt.
- Informatie met betrekking tot beleggingsbeleid, bescherming en toedelingsregels en cohortsamenstelling. Deze informatie wordt door de pensioenuitvoerder met betrokken partijen gedeeld via diverse beleidsdocumenten, zoals het strategisch beleggingsbeleid, het jaarplan beleggingen en beleggingsrichtlijnen.
- Informatie-uitwisseling tussen pensioendeelnemer, pensioenuitvoerder en/of pensioenuitvoeringsorganisatie.
- Toedeling van rendementen aan deelnemers.

- Informatie over kosten:
  - Vooralsnog is er geen uitgekristalliseerd en eenduidig proces in samenwerkingsketens om te komen tot de kostentoedeling (en tevens de communicatie over kosten). De ervaringen tot dusverre lijken aan te geven dat dit lastig is te standaardiseren. Verschillende partijen maken verschillende afwegingen ten aanzien van verwerking, fijnmazigheid, feitelijk/begroot, treffen voorziening, tijdigheid, rolverdeling in de aanlevering van verschillende onderdelen etc.
  - Verwacht wordt dat bestaande processen om de DNB-jaarstaat J402 samen te stellen de basis blijven vormen voor de informatie-uitwisseling over kosten, voor zowel de SPR als de FPR
- Inzicht in/ doorzicht naar de daadwerkelijke beleggingen meestal aangeduid met "Lookthrough" informatie. Ad hoc verzoeken om aanvullende informatie bij beleggingsadministrateur/asset service provider of fiduciair manager kunnen nodig zijn maar vallen niet onder reguliere gegevensuitwisseling in de context van de uitwisseling zoals beschreven in deze handleiding.
- Eventuele specifieke Informatie-uitwisseling benodigd voor een premie-uitkeringsovereenkomst zoals aangeboden door verzekeraars.
- Niet elk proces binnen de pensioenuitvoering leidt tot noodzakelijke acties binnen vermogensbeheer. De gevolgen van processen die wel tot vermogensbeheeracties leiden moeten echter wel op periodieke basis worden uitgewisseld. De periodiciteit van de uitwisseling van de daarmee samenhangende berichten is flexibel invulbaar tussen partijen. Ook de wijze waarop partijen samenwerken, de rolverdeling of governance, maakt geen onderdeel uit van de standaard.

## 2.3Uitgangspunten gegevensuitwisseling

Om de gegevensuitwisseling zo praktisch mogelijk vorm te geven gelden de navolgende uitgangspunten:

- De gegevensstandaard is bruikbaar voor elke (governance)verdeling tussen pensioenuitvoering en vermogensbeheer.
- Pensioenuitvoeringsorganisaties hebben in het algemeen per pensioenuitvoerder een voorkeur voor één partij die hen van de benodigde informatie voorziet ten aanzien van de ontwikkeling van de beleggingen.
- Indien de asset service provider een onafhankelijke rol vervult als leidende beleggingsadministrateur en/of de uitvoering van beleid toetst, dan ontvangt deze dezelfde informatie als de fiduciair manager om onafhankelijk te kunnen rapporteren aan pensioenfondsen over het gevolgde en gerealiseerde beleggingsbeleid in relatie tot de doelstellingen.
- De fiduciair manager rol ontvangt de benodigde informatie om het collectieve vermogen conform de kaders van het beleggingsbeleid te beleggen, rekening houdend met in- en uitstroom (door premies, uitkeringen en waardeoverdrachten) en geprognosticeerde uitkeringen.
- De pensioenuitvoeringsorganisatie geeft de deelnemer inzicht in de ontwikkeling van voor de pensioenuitkering bestemd vermogen (SPR) en/of voor pensioen bestemd kapitaal (FPR) inclusief de toedeling van rendementen en verwachte uitkeringen.

## 2.4Verduidelijking uitgangspunten gegevensuitwisseling

Bij de inhoudelijke consultatieronde in mei/juni 2023 kwamen enkele kwesties regelmatig terug die niet tot aanpassingen in het inhoudelijk deel van het [rapport](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380) leidde maar wel verduidelijkt moesten worden om misverstanden te voorkomen.

- **Gegevensmodel** : Het gegevensmodel bevat slechts de gegevens die nodig zijn om de benodigde informatie rond het beleggen van pensioengelden te kunnen verzenden en/of te ontvangen en informatie rondom gerealiseerde beleggingsresultaten te kunnen delen.
- **Rollen (niet voorschrijvend)**: Ter ondersteuning van de uitwerking van het gegevensmodel wordt gegevensuitwisseling tussen diverse partijen in de keten beschreven. Om het begrip van het gegevensmodel te ondersteunen is hierbij zowel voor de SPR als voor de FPR een rolverdeling geschetst in de keten waarbij het governance model voorziet in bepaalde functiescheidingen. In een alternatieve inrichting kunnen rollen door eenzelfde partij worden uitgevoerd, zo kan de fiduciair manager ook de leidende beleggingsadministratie voeren en kan de rol van de administrateur cohorten- en beleggingspools in de FPR ook door de pensioenuitvoeringsorganisatie of door de beleggingsadministrateur worden uitgevoerd. Het is niet de bedoeling van deze handleiding om de vorm van samenwerking tussen partijen en daarmee het governance model voor te schrijven.
- **Periodiciteit:** Bij de beschrijving van een aantal processen is aangegeven dat deze naar verwachting maandelijkse periodiciteit kennen. Deze periodiciteit wordt niet voorgeschreven. De genoemde uitwisselingsmomenten en periodes zijn voorbeelden die in de afspraken tussen partijen anders kunnen worden ingevuld.
- **Procesbeschrijving** : Voor de FPR is het mogelijk om uit te gaan van al bestaande processen (inclusief -indicatieve- tijdslijnen en rolverdeling) voor (collectieve) individuele DC-regelingen. Voor de SPR is dit nog niet het geval.
- **Kosten** : De informatie-uitwisseling over kosten valt buiten de scope van deze standaard. Vooralsnog gaan we er van uit dat wordt voortgebouwd op bestaande processen die ook de basis vormen voor bijvoorbeeld de J402 DNB-jaarstaat..
- **Begrip Vermogensbeheer** : Als in deze handleiding het begrip "vermogensbeheer" wordt gebruikt, dan wordt daarmee gedoeld op de partijen: fiduciair manager, beleggingsadministrateur/asset service provider en custodian. Bij "pensioenuitvoering" gaat het om de combinatie van de wettelijke pensioenuitvoerder en de pensioenuitvoeringsorganisaties die voor hen de administratie voeren.
- **Taal** : Dit rapport is opgesteld voor de gegevensuitwisseling tussen pensioenuitvoeringsorganisaties en vermogensbeheerders binnen de Nederlandse WTP-context. Het rapport en de standaard worden in de Nederlandse taal opgeleverd. De namen van de gebruikte variabelen in de standaards zijn overigens wel in het Engels gesteld zodat het begrippenapparaat ook voor niet Nederlandstaligen die wel thuis zijn in vermogensbeheer begrijpelijk is.
-

## 2.5Deelnemer communicatie

Zie hoofdstuk 6 in het eerdere in de inleiding genoemde [eindrapport](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380).

## 2.6Techniek

Rond gebruik en technische invulling van de gegevensstandaard zijn een aantal principes geformuleerd:

- De gegevensuitwisseling is "duurzaam" dus niet gekoppeld aan technologische trends (of hypes).
- De documentatie is duidelijk en transparant.
- De gegevensset kan in overleg met de betrokken partijen worden bijgesteld.
- Er wordt zoveel mogelijk gebruik gemaakt van open technische standaarden (bijvoorbeeld REST, JSON, SOAP, ODATA, OAuth).

Voor de technische invulling van het berichtenverkeer is het volgende afgesproken:

- Gegevensuitwisseling: RESTful Web services of bestandsuitwisseling.
- Gegevensformaat: JSON.
- Voor het gegevensformaat conformeren we ons binnen deze standaard aan AFD 2.0. Dat heeft onder andere consequenties voor de naamgeving van de attributen en entiteiten.

- AFD 2.0 definieert het gegevenstype van een attribuut, **maar beperkt de tekenreekslengte of het aantal decimalen niet**. Als een leverancier extra restricties wil toepassen. Een eventuele beperking van het aantal posities kan tussen partijen onderling worden afgesproken. Zie [https://www.manula.com/manuals/sivi/sivi-all-finance-standard/1/en/topic/data-types-and-formats](https://www.manula.com/manuals/sivi/sivi-all-finance-standard/1/en/topic/data-types-and-formats)

- Berichten verwerking is asynchroon. De frequentie van de informatie-uitwisseling is periodiek (bijvoorbeeld maandelijks) en de verwerking door de ontvanger in principe op dagbasis; synchroon (realtime) is niet nodig.
- Bericht initiatief ligt bij de verzender van de informatie, deze brengt (pushed) het bericht naar de ontvanger.
- Service venster: advies is kantoortijden. Partijen kunnen hierover onderling eigen afspraken maken.
- Beveiligingsaspecten:

  - Tijdens het transport van informatie wordt er gebruik gemaakt van two-way authentication (mutual-TLS).
  - Authenticatie van de verzender bij de ontvangende server is vereist.
  - De gegevens dienen gegarandeerd ongewijzigd aan te komen bij de ontvanger (zijn onweerlegbaar). Ze zijn daarom digitaal ondertekend.

Afspraken over de onderstaande aspecten worden uitgewerkt en behandeld binnen de kaders van de governancestructuur rond de standaard.

- De complete – technische – gegevensstandaard en de verschillende daarop gebaseerde berichten.
- Maximale omvang (aantallen en/of bestandsomvang) van het bericht.
- Granulariteit van het berichtenverkeer.

- Een lagere granulariteit geeft aan dat er -op een zeker niveau- minder details worden uitgewisseld.

- Verwerkingstijd van ontvangen berichten.
- Berichtterugkoppeling: response berichten (ontvangstbevestiging en correct of foutmelding – inhoudelijk en technisch - of waarschuwing). Hiervoor moeten de regels worden beschreven.
- Responsetijd (server).

**Transactievolume**

Het verwachtte transactievolume is laag.

## 2.7Governance en beheer

- Het gebruik van de standaard vormt onderdeel van de individuele overeenkomsten tussen pensioenuitvoerders en vermogensbeheerpartijen. Partijen gebruiken de standaard conform de afspraken die gelden voor de standaard.
- De standaard is eigendom van de Pensioenfederatie. Het beheer zal worden ondergebracht bij SIVI. De standaard wordt beheerd op zowel bestuurlijk als inhoudelijk niveau. De operationele invulling van deze bestuurlijke- en inhoudelijke governance moet nog worden geaccordeerd. Ondersteuning door een expertgroep bestaande uit vermogensbeheerpartijen en pensioenuitvoerders ligt daarbij in de lijn van de verwachting.

##

# 3Processen & informatiestromen – Solidaire Premieregeling

**De processen & informatiestromen staan uitvoering beschreven in**  **het rapport ''**** [Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380):**

**Hoofdstuk 4: Solidaire premieregeling.**

## 3.1Inleiding

Deze paragraaf beschrijft de noodzakelijke informatie-uitwisseling tussen betrokken partijen die nodig is om op een robuuste wijze invulling te geven aan de uitvoering van de solidaire premieregeling

# 1
.

In Figuur 1 hieronder wordt de informatie-uitwisseling tussen de betrokken partijen schematisch weergegeven. De beleggingsadministrateur voorziet de pensioenuitvoeringsorganisatie onafhankelijk van de fiduciair manager van informatie en kan tevens een toetsende rol vervullen. Indien daar niet voor wordt gekozen en de fiduciair ook de leidende beleggingsadministratie voert zal informatiestroom 2 van de fiduciair manager naar de pensioenuitvoeringsorganisatie lopen.

![](RackMultipart20231222-1-avhyj4_html_ecfa6d97e7d17a1a.gif)

**Figuur 1 - Scope informatie-uitwisseling SPR**

Hieronder worden de rollen van de diverse partijen in het schema nader toegelicht:

- De pensioenuitvoeringsorganisatie heeft de verantwoordelijkheid om conform de door de pensioenuitvoerder vastgestelde toedelingsregels rendementen toe te delen naar de persoonlijke pensioenvermogens van deelnemers (eventueel via een collectieve uitkeringsfase) de solidariteitsreserve, het eventuele compensatiedepot en mogelijke andere reserves.
 Op basis van deze persoonlijke pensioenvermogens worden, conform de uitgangspunten van de pensioenuitvoerder, uitkeringen bepaald en geprojecteerd.
 De pensioenvermogens en geprojecteerde uitkeringen worden naar cohorten, aan de fiduciair manager en/of de beleggingsadministrateur geleverd. De pensioenuitvoeringsorganisatie verwerkt premies, uitkeringen en mutaties in het deelnemersbestand en verzorgt de deelnemerscommunicatie.
- De fiduciair manager ondersteunt de pensioenuitvoerder bij de totstandkoming van het integrale beleggingsbeleid, draagt zorg voor de uitvoering van dit beleggingsbeleid en stuurt daarbij de operationele vermogensbeheerders aan. De fiduciair manager zal ook een (schaduw) beleggingsadministratie voeren. Bij grote pensioenuitvoerders zonder fiduciair manager is de pensioenuitvoerder zelf verantwoordelijk voor het aansturen van zowel interne als externe vermogensbeheerders.
- De operationele vermogensbeheerders beheren onderdelen van de portefeuille en worden daarbij aangestuurd door de fiduciair manager. Het is mogelijk dat (voor onderdelen) de fiduciair manager en de operationeel vermogensbeheerder tot dezelfde organisatie behoren.
- De beleggingsadministrateur/asset service provider (doorgaans aanvullende dienstverlening van de custodian) verzorgt de onafhankelijke beleggingsadministratie voor de pensioenuitvoerder. De beleggingsadministrateur berekent het totale rendement van de beleggingen en (indien nodig) het rendement van verschillende beleggings(sub)portefeuilles en levert dit aan de pensioenuitvoeringsorganisatie. Zoals hierboven aangegeven kan de fiduciair manager ook de leidende beleggingsadministratie voeren. De beleggingsadministratie wordt gevoed vanuit de afwikkeling van mutaties in de portefeuille, uitgevoerd door de operationele vermogensbeheerders. Met de fiduciair manager wordt indien gewenst deze administratie gereconcilieerd. De beleggingsadministrateur draagt ook vaak zorg voor het opstellen van toezichthoudersrapportages of onderdelen hiervan.

**Informatiestromen SPR**

De informatiestromen voor SPR-producten tussen de fiduciair manager, de beleggingsadministrateur en de pensioenuitvoeringsorganisatie zijn:

- Informatie van de pensioenuitvoeringsorganisatie over vermogens- en geprojecteerde af te dekken kasstromen (eventueel per cohort) om de fiduciair manager en beleggingsadministrateur in staat te stellen hun rollen te vervullen.
- Informatie van de beleggingsadministrateur of fiduciair manager over rendementen die de pensioenuitvoerder nodig heeft om te komen tot een juiste toedeling aan de deelnemers.

Deze informatiestromen worden hieronder nader uitgewerkt.

## 3.2Informatiestroom Fiduciair Manager en Beleggingsadministrateur

Informatiestroom van pensioenuitvoeringsorganisatie naar fiduciair manager en beleggingsadministrateur/asset service provider (stroom 1 in Figuur 1)

De informatiestroom van de pensioenuitvoeringsorganisatie naar fiduciair/beleggingsadministrateur (stroom 1) kan worden opgedeeld in informatiestroom 1a (vermogen), informatiestroom 1b (in- en uitstroom) en informatiestroom 1c (geprojecteerde uitkeringen).

### 3.2.1Informatiestroom 1a, vermogen

Op periodieke (naar verwachting maandelijkse) basis ontvangt de fiduciair manager over een pensioenuitvoerder (Pensionfund ID
# 2
) per regeling (Pension scheme ID i) het totale pensioenvermogen (Capital i) bij aanvang van de periode (Capital date i).

Naast de informatie op totaalniveau kan de fiduciair ook per (leeftijds
# 3
-) cohort (Cohort ID i,k) het pensioenvermogen (Cohort capital i,k) ontvangen. Zo kan bijvoorbeeld voor het leeftijdscohort 25-29 jaar het totaal van de persoonlijke pensioenvermogens bij aanvang worden ontvangen.

Met de cohortinformatie kan de fiduciair manager desgewenst een totaalberekening maken en de aansluiting bij de geleverde informatie op totaal/collectief niveau toetsen aan het beleid van het fonds. Dit is nuttig voor een robuuste overdracht en audittrail afhankelijk van afspraken die partijen maken. Conform het beleid van de pensioenuitvoerder kan bij (grote) afwijkingen herbalancering wenselijk zijn
# 4
. Deze informatie kan behalve aan de fiduciair manager desgewenst ook worden verstrekt aan de beleggingsadministrateur/asset service provider om deze ook in staat te stellen toetsings- en rapportage-activiteiten uit te voeren met behulp van de leidende beleggingsadministratie.

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name 6.4.2Berichtstructuur 1. Vermogen (0001a)

### 3.2.2Informatiestroom 1b, in- en uitstroom ("Cashflow")

Op periodieke (naar verwachting maandelijkse) basis ontvangt de fiduciair manager over een pensioenuitvoerder (Pensionfund ID) per regeling (Pension scheme ID i) de instroom (Contribution i) in de periode (op de Contribution date i) en de uitstroom of als gesaldeerde cashflow (Net contribution/withdrawal i in de periode (op de Net contribution/withdrawal date i).

Naast de informatie op totaalniveau kan de fiduciair ook per (leeftijds -) cohort (Cohort ID i,k) de instroom (Cohort contribution i,k) en uitstroom (Cohort withdrawal i,k) of als gesaldeerde cashflow (Net contribution/withdrawal i,k) over de periode (Start date PUO admin tot End date PUO admin) worden ontvangen.

De in- en uitstroom bevat naast premies, waardeoverdrachten en uitkeringen ook de verschuivingen over cohorten als daar sprake van is. Een cohort kan ook een geboortejaar zijn. Een voorbeeld is het persoonlijke pensioenvermogen van deelnemers die van cohort 25-29 jaar naar cohort 30-34 jaar verschuiven. Ook het 'cohort' solidariteitsreserve, het 'cohort' compensatiedepot en mogelijk andere reserves zullen hierbij betrokken worden.

Met de cohortinformatie kan de fiduciair manager desgewenst een totaalberekening maken en de aansluiting bij de geleverde informatie op totaal/collectief niveau toetsen aan het beleid van het fonds. Dit is nuttig voor een robuuste overdracht en audittrail afhankelijk van afspraken die partijen maken. Deze informatie kan behalve aan de fiduciair manager desgewenst ook worden verstrekt aan de beleggingsadministrateur/asset service provider om ook deze in staat te stellen toetsings- en rapportage-activiteiten uit te voeren met behulp van de leidende beleggingsadministratie.

De fiduciair manager draagt zorg voor de belegging van instroom of het vrijmaken van middelen om uitstroom te financieren. Afhankelijk van de voorkeur van de pensioenuitvoerder en werkwijze van de pensioenuitvoeringsorganisatie zal dit reactief of prospectief zijn.

In de reactieve werkwijze acteert de fiduciair manager in de komende periode op de ontvangen instroom of uitstroom die correspondeert met mutaties over de afgelopen (gegevens-)periode.

Bij de prospectieve werkwijze acteert de fiduciair manager in de komende periode op de instroom of uitstroom op basis van een ontvangen prognose over de komende (gegevens-) periode. Strikt genomen hoeft de fiduciair manager niet geïnformeerd te worden op welke periode de gegevens betrekking hebben aangezien beleggingen immers nooit met terugwerkende kracht uitgevoerd kunnen worden. Voor de audittrail kan het wenselijk zijn om de periode wel vast te leggen in de informatie-uitwisseling. Instroom en uitstroom kunnen separaat worden aangeleverd of als gesaldeerde cashflow. Bij separate aanlevering dienen ook de inflow en outflow datum te worden gevuld, bij een gesaldeerde aanlevering is dat alleen de cashflow datum.

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name 6.4.3Berichtstructuur 2. Cashflow (0001b).

### 3.2.3Informatiestroom 1c, geprojecteerde uitkeringen ("Pensioenprojectie")

Op periodieke (verwachting is maandelijkse) basis (Projection date) ontvangt de fiduciair manager van een pensioenuitvoerder (Pensionfund ID) per regeling (Pension scheme ID i) en per (leeftijds-)cohort (Cohort ID i,j) de geprojecteerde uitkeringen (Cohort expected pension payment i,j,k) op basis van de opgebouwde vermogens naar toekomstige periodes (Expected pension payment date i,k).

Bijvoorbeeld voor het cohort 25-29-jarigen betreft dit (voornamelijk) het projecteerde ouderdomspensioen over 39 jaar (uitgaande van de reglementaire pensioenleeftijd). In de informatiestroom per 31 december 2022 wordt de eerste (uitkerings)kasstroom voor dit cohort dan in 2061 verwacht. Deze informatie is belangrijk voor de fiduciair manager om (aansturing van) de beschermingsportefeuille in te richten en de beoogde beschermingsrendementen te genereren. De gewenste bescherming per leeftijdscohort (bijvoorbeeld 25% voor 25-29 jaar en 100% vanaf 70-jaar) is bepalend voor de af te dekken rentegevoeligheid. Het volstaat niet langer om alleen een projectie van uitkeringen te baseren op de gehele populatie in een pensioenregeling omdat het renterisico niet langer door de complete deelnemerspopulatie wordt gedeeld. Desgewenst kunnen ook het 'cohort' solidariteitsreserve, eventueel het 'cohort' compensatiedepot en mogelijk andere reserves beschermingsrendement toebedeeld krijgen. Dan zal voor deze cohorten een (fictief) kasstroomprofiel moeten worden opgesteld. Naast de individuele geprojecteerde uitkeringen per cohort (inclusief de reserves) kan ook een totale geprojecteerde uitkering over de hele populatie worden aangeleverd (Total expected pension payment i,k). Dit is gelijk aan de som van de geprojecteerde uitkeringen over alle cohorten per toekomstige periode (Expected pension payment date i,k).

Tenslotte bevat de gegevensuitwisseling de af te dekken kasstromen per regeling (Hedged expected pension payment i,k) per toekomstige periode. Dit is gelijk aan de som van de gewogen geprojecteerde uitkeringen per cohort. De wegingsfactor is gelijk aan het percentage bescherming per cohort. Bijvoorbeeld: de bescherming van het cohort 25-29 jaar is 25% en de bescherming van het cohort vanaf 70-jaar is 100%. De geprojecteerde uitkeringen van het cohort 25-29 jaar worden met 25% vermenigvuldigd en opgeteld bij de volledige geprojecteerde uitkeringen van het cohort vanaf 70-jaar vermenigvuldigd met 100%. Op deze manier ontstaat een profiel van de af te dekken kasstromen. Deze uitwisseling vermijdt misverstanden ten aanzien van af te dekken kasstromen en kan desgewenst een toets in het proces introduceren.

Functionele uitwerking naar bericht: zie hoofdstuk 6.met name 6.4.4Berichtstructuur 3. Pensioenprojectie (0001c)

### 3.2.4Informatiestroom 2, Informatiebehoefte pensioenuitvoeringsorganisatie ("Rendementsinformatie")

**Informatiestroom van beleggingsadministrateur/asset service provider naar de pensioenuitvoeringsorganisatie (stroom 2 uit Figuur 1) in de SPR.**

De pensioenuitvoeringsorganisatie heeft voor het uitvoeren van de solidaire premieregeling periodiek (naar verwachting maandelijks) informatie nodig over het behaalde rendement.

Periodiek ontvangt de pensioenuitvoeringsorganisatie over de periode (die loopt van Start date investment report tot End date investment report) voor een pensioenuitvoerder (Pensionfund ID) per regeling (Pension scheme ID i) en per portefeuille (Portfolio ID n) de waarde aan het begin van de periode (Total Market Value start i,n), de waarde aan het einde van de periode (Total Market Value end i,n) en het rendement in portefeuille valuta en (eventueel) uitgedrukt als percentage (Return rate i,n). De pensioenuitvoeringsorganisatie draagt zorg voor de toedeling van rendementen naar deelnemers op basis van portefeuillerendementen. Optioneel kunnen ook per cohort in de regeling (Cohort ID i, k) pensioenvermogen (Cohort Capital i, k), beschermingsrendement (Cohort return protection i, k) en overrendement (Cohort return excess i, k) worden gedeeld met de pensioenuitvoeringsorganisatie. Of deze optionele elementen worden uitgewisseld hangt af van de overeengekomen rollen en verantwoordelijkheden tussen de samenwerkende partijen. Daarbij is het uitgangspunt dat de pensioenuitvoeringsorganisatie de verantwoordelijkheid heeft om conform de door de pensioenuitvoerder vastgestelde toedelingsregels rendementen toe te delen naar de persoonlijke pensioenvermogens van deelnemers, de solidariteitsreserve, een eventueel compensatiedepot en mogelijk andere reserves.

De beleggingsadministrateur/asset service provider verstrekt de daartoe benodigde informatie aan de pensioenuitvoeringsorganisatie en baseert zich daarbij op de onafhankelijke beleggingsadministratie. In een alternatief governance model kan de fiduciair manager deze informatie aan de pensioenuitvoeringsorganisatie verstrekken.

Indien de solidaire premieregeling is ingericht met **indirect (theoretisch) beschermingsrendement** dan volstaat in principe informatie over het totale rendement. De toedeling van beschermingsrendement is dan namelijk niet afhankelijk van gerealiseerd rendement. Het door de pensioenuitvoeringsorganisatie toe te delen overrendement kan de pensioenuitvoeringsorganisatie berekenen op basis van het totale rendement verminderd met het toegedeelde indirect (theoretische) beschermingsrendement.

Wanneer de solidaire premieregeling het toe te delen beschermingsrendement baseert op het **direct (feitelijk) behaalde rendement** dan moet de pensioenuitvoeringsorganisatie beschikken over een onderverdeling van het behaalde rendement. De beleggingsadministrateur/asset service provider dient dan het rendement aan te leveren voor subportefeuilles (en optioneel naar cohorten), waarbij in ieder geval een onderscheid gemaakt wordt tussen de beschermingsportefeuille en de overrendementsportefeuille. Afhankelijk van de wijze waarop feitelijk beschermingsrendement wordt toebedeeld naar individuele deelnemers kan een verdere uitsplitsing van de beschermingsportefeuille naar subportefeuilles wenselijk zijn.

Een (verdere) uitsplitsing van portefeuilles kan bovendien wenselijk zijn ten behoeve van communicatie over behaalde rendementen naar deelnemers, reconciliatiedoeleinden en eventuele wettelijke verplichtingen. Dit is afhankelijk van de door de pensioenuitvoerder gewenste opzet.

De informatie-uitwisseling ten behoeve van de solidaire regeling gebaseerd op het direct (feitelijk) behaalde rendement kan tevens gebruikt worden voor een uitwisseling bij een specifieke uitvoeringsvariant van de flexibele premieregeling. Deze keuze zal met name gemaakt worden door partijen die voor de flexibele premieregeling een vergelijkbare wijze van toedeling van rendementen hanteren als bij de solidaire premieregeling die uitgaat van feitelijke rendementen. Voor elk cohort wordt dan aan de pensioenuitvoeringsorganisatie een feitelijk beschermingsrendement en overrendement geleverd als bedrag en optioneel als percentage.

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name 6.4.5Berichtstructuur 4. Rendementsinformatie (00002)

# 4Processen & informatiestromen – Flexibele Premieregeling

**De processen & informatiestromen staan uitvoering beschreven in**  **het rapport ''**** [Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380):**

**Hoofdstuk 5: Flexibele premieregeling.**

## 4.1Inleiding

Dit hoofdstuk beschrijft de noodzakelijke informatie-uitwisseling tussen betrokken partijen die nodig is om op een robuuste wijze invulling te geven aan de uitvoering van de Flexibele premieregeling. Op basis van de uitgangspunten en de scope is de benodigde gegevensset vastgesteld.

In de aansturing van het proces van de flexibele premieregeling kan onderscheid gemaakt worden tussen twee modellen voor het "orderen" van beleggingen die in de operationele samenwerking tussen pensioenuitvoering en vermogensbeheer worden toegepast:

- Model 1, een eenvoudiger, direct ordermodel en een
- Model 2, een uitgebreider, gelaagd ordermodel.

Er is ook een model denkbaar waarbij voor de FPR-gegevensuitwisseling het SPR gegevensmodel gebruikt kan worden. In dit model is FPR ingericht vergelijkbaar met SPR-feitelijk waarbij alleen meerdere risicoprofielen per cohort ondersteund worden.

## 4.2Model 1 eenvoudiger, direct ordermodel

In dit model (zie Figuur 2) bestaan de beleggingen (onderste laag uit Figuur 2) alleen uit direct via een platform verhandelbare, beleggingsfondsen. Dit betreffen handelsplatformen (bijvoorbeeld AllFunds, Fundsettle etc.) waar beleggingsfondsen direct kunnen worden verhandeld. Dit model wordt in de bestaande praktijk vooral toegepast voor Individuele DC-regelingen. Het direct order model kan door de pensioenuitvoeringsorganisatie zelf uitgevoerd worden.

![](RackMultipart20231222-1-avhyj4_html_26042cf4330abd2.gif) **Figuur 2 – Schematische weergave directe ordermodel**

De pensioenuitvoeringsorganisatie vertaalt bij toepassing van dit model mutaties op deelnemersniveau naar benodigde (gesaldeerde) transacties in de beleggingsfondsen van operationele vermogensbeheerders en laat deze uitvoeren via een handelsplatform.Een dergelijke opzet kan ook gezamenlijk met de asset service provider/custodian worden geïmplementeerd waarbij de pensioenuitvoeringsorganisatie mutaties op deelnemersniveau vertaalt naar gesaldeerde mutaties en de asset service provider/custodian zorgdraagt voor de uitvoering van de transacties in beleggingsfondsen via een handelsplatform zie Figuur 6 - Model 1b: de pensioenuitvoeringsorganisatie geeft beleggingsopdrachten aan een tussenpartij (order platform: custodian, fiduciair). Bij de samenstelling van de orders wordt rekening gehouden met aspecten zoals de minimale orderomvang per beleggingsproduct, de settlement cyclus en de bijbehorende financiële stromen.

In het direct ordermodel wordt de pensioenuitvoerder in de regel door de fiduciair manager ondersteund ten aanzien van de inrichting van de lifecycle(s) en de samenstelling daarvan (selectie en monitoring van onderliggende beleggingen). Specifieke aandacht verdient het proces van wijzigingen in de samenstelling van de beleggingen (vervanging van beleggingsfondsen). Dergelijke wijzigingen resulteren in transitie-activiteiten bij de pensioenadministrateur en/of asset service provider/custodian. Specifieker omgeschreven; als een beleggingsproduct (dat kan bijvoorbeeld een beleggingsfonds maar ook een virtuele pool of een mandaat zijn) wordt vervangen, verwijderd of toegevoegd dan zal de pensioenuitvoeringsorganisatie dit aanpassen en verwerken. Als _in_ een beleggingsproduct aanpassingen worden doorgevoerd dan is dat voor de pensioenuitvoeringsorganisatie niet relevant en raakt dit enkel de aanbieder van het product.

In het direct ordermodel bestaat een cohortenpool uit een groep deelnemers die op basis van het lifecycle principe (minder beleggings- en renterisico naarmate de pensioeningang/einddatum beleggingshorizon nadert) een gelijke beleggingsverdeling kennen. Een cohortenpool kan gebruikt worden om deelnemersgroepen te onderscheiden. Dit kan op basis van tijd (leeftijd, periode tot pensioen etc.) zijn maar ook op basis van een kenmerk als bv. actief, slaper, arbeidsongeschikt etc. Het aantal pools is in de basis onbeperkt. Er worden zoveel pools gemaakt als nodig om de juiste deelnemersgroepen te kunnen onderscheiden die een eigen beleggingsmix nodig hebben. Hieronder volgt een eenvoudig voorbeeld met indeling in drie lifecycles op basis van geboortejaren en de vastgestelde verdeling over aandelen en obligaties. De administratie van de cohortenpool is optioneel en kan bij de pensioenuitvoeringsorganisatie, de beleggingsadministrateur/asset service provider of elders liggen. De verdeling van de gewichten (percentages) wordt veelal door de fiduciair manager gemaakt.

Een cohortenpool is een administratieve groepering die bestaat uit een groep deelnemers die op basis van het bijvoorbeeld het lifecycle principe een gelijke beleggingsverdeling kennen.

|   | **Lifecycle defensief** | **Lifecycle neutraal** | **Lifecycle offensief** |
| --- | --- | --- | --- |
| **Cohortenpool** | % Aandelen | % Obligaties | % Aandelen | % Obligaties | % Aandelen | % Obligaties |
| Geboortejaar 1987 | 90 | 10 | 95 | 5 | 100 | 0 |
| Geboortejaar 1986 | 88 | 12 | 94 | 6 | 98 | 2 |
| Geboortejaar 1985 | 86 | 14 | 93 | 7 | 96 | 4 |
| Geboortejaar 1984 | 85 | 15 | 91 | 9 | 94 | 6 |
| Geboortejaar 1983 | 84 | 16 | 89 | 11 | 92 | 8 |
| Geboortejaar 1982 | 83 | 17 | 87 | 13 | 90 | 10 |
| Geboortejaar 1981 | 82 | 18 | 85 | 15 | 88 | 12 |
| Geboortejaar 1980 | 81 | 19 | 84 | 16 | 86 | 14 |
| Geboortejaar 1979 | 80 | 20 | 82 | 18 | 84 | 16 |

**Figuur 3 - Voorbeeld cohortenpools en lifecycles**

Het voorbeeld in Figuur 3 laat zien hoe geboortejaren en daarmee leeftijden invloed kunnen hebben op de verdeling van beleggingen binnen lifecycles.

Als een deelnemer een jaar ouder wordt, dan wordt een zogenaamde leeftijdsrebalance doorgevoerd. Elke deelnemer wordt in een volgende cohortenpool wordt geplaatst.

Daarbij wordt de beleggingsmix van de deelnemer aangepast naar die van het nieuwe cohort. In het voorbeeld hierboven (Figuur) wordt ongeacht het gekozen risicoprofiel het aandeel aandelen afgebouwd en het aandeel obligaties opgebouwd. Dit leidt dus tot concrete aan- en verkooporders richting de productaanbieders.

Een andere vorm van rebalancing is de doelgewichtenrebalancing. Deze kan worden uitgevoerd wanneer de werkelijke verdeling van beleggingen buiten vooraf vastgestelde bandbreedtes valt als gevolg van koersontwikkelingen. Ook deze vorm van rebalancing leidt tot aan- en verkooporders.

Een groep (cohort) deelnemers kan op verschillende manieren worden samengesteld. Over het algemeen spelen daarbij 3 aspecten een rol:

- Leeftijd.
- Status.
- Beleggingsprofiel.

Voor het leeftijdsaspect kan bijvoorbeeld gebruik gemaakt worden van:

- Leeftijd.
- Periode tot pensioeningang/einddatum beleggingshorizon.
- Geboortejaar/maand.

Voor de status kan onderscheid worden gemaakt in:

- Opbouwend versus uitkerend.
- Actief/Slaper/Arbeidsongeschikt (AO)/Uitkerend/etc.

Salderen (ook wel "netten") van de beleggingen vindt plaats over de cohortenpools conform de instructies voor de beleggingentransacties. In het direct ordermodel vindt dat plaats "in de spaghetti" (zie Figuur 2: Schematische weergave direct ordermodel) tussen de cohortenpools en de beleggingen. De risicodelingsreserve wordt gezien als een aparte cohortenpool die conform een eigen beleggingsbeleid in beleggingsproducten belegt.

## 4.3Model 2 uitgebreider, gelaagd ordermodel

In het "Uitgebreidere, gelaagde model" (Figuur 4) kunnen de beleggingen ook bestaan uit niet dagelijks verhandelbare en/of niet via een platform) verhandelbare (illiquide) fondsen of uit beleggingsmandaten. Dit model wordt al toegepast voor grotere Collectieve Individuele DC (CIDC) regelingen.

**F ![](RackMultipart20231222-1-avhyj4_html_e659904408e5771.png) iguur-4 - Schematische weergave gelaagd ordermodel**

**In dit model:**

- Participeren deelnemers in cohortenpools conform de gekozen lifecycle en gekozen samenstelling van cohorten. De cohortenpools participeren vervolgens in beleggingspools. Deze beleggingspools kunnen bestaan uit uiteenlopende onderliggende beleggingen (liquide, illiquide, fondsen en mandaten). De cohortenpools participeren in beleggingspools al naar gelang de strategische verdeling binnen de cohortenpools
# 5
. Om de toedeling naar deelnemers robuust en traceerbaar vorm te geven worden voor de verschillende (gelaagde) pools units uitgegeven en unitwaardes uitgerekend. Het vermogen van de deelnemer is daardoor exact terug te voeren naar het pro rata deel van de onderliggende beleggingen. De laag met cohortenpools is overigens optioneel en kan de inrichting van het beleggingsbeleid en/of de beoogde functiescheiding reflecteren. Indien deze laag ontbreekt dat dient de pensioenuitvoeringsorganisatie per deelnemer te administreren welke participaties in de verschillende beleggingspools worden aangehouden. In het eenvoudigere FPR Direct Order-model zijn de cohortenpools en/of beleggingspools niet nodig.
 De beleggingen zijn dan dagelijks verhandelbaar en de koersen zijn ook dagelijks beschikbaar. Als eenvoudig voorbeeld voor een cohortenpool geldt eveneens Figuur 3 waarbij "% Aandelen" en "% Obligaties" dan vervangen wordt door bijvoorbeeld "% Zakelijke waarden", "% Vastrentend beleggingen, korte looptijden","% Vastrentende beleggingen, lange looptijden", etc.
- Kan de allocatie van de rendementen door de pensioenuitvoeringsorganisatie of de administrateur van de cohortenpools en beleggingspools worden gedaan:
  - Heeft de pensioenuitvoeringsorganisatie de verantwoordelijkheid om conform de door de pensioenuitvoerder vastgestelde allocatieregels rendementen expliciet toe te delen naar: de persoonlijke pensioenvermogens van deelnemers, de risicodelingsreserve, een eventueel compensatiedepot en mogelijk andere reserves. Daartoe verwerkt de pensioenuitvoeringsorganisatie mutaties in het deelnemersbestand en de allocatie van persoonlijke pensioenvermogens naar cohortenpools. Bij de samenstelling van de cohortenpools wordt rekening gehouden met de lifecycle die de deelnemer gekozen heeft (offensief, neutraal, defensief etc.). Ook wordt rekening gehouden met ingelegde premie en mogelijke verrekeningen zoals met de risicodelingsreserve. Op basis van deze persoonlijke pensioenvermogens worden, conform de uitgangspunten van de pensioenuitvoerder, uitkeringen geprojecteerd. Daarnaast verzorgt de pensioenuitvoeringsorganisatie de deelnemerscommunicatie.
  - Verwerkt de administrateur van cohortenpools en beleggingspools de allocatie en administratie van cohortenpools zoals aangeleverd door de pensioenuitvoeringsorganisatie. Daarnaast verzorgt hij de allocatie naar beleggingspools (bijvoorbeeld zakelijke waarden, vastrentende waarden). Hiervoor worden zowel voor de cohortenpools als de beleggingspools unitwaarden berekend en het aantal units geadministreerd. In het geval van cohortenpools spreken we hierbij van participatiewaardes, bij beleggingspools van unitwaardes. Hierbij worden premies, onttrekkingen en herbalanceringen meegenomen. Deze rol kan eventueel ook uitgevoerd worden door een pensioenuitvoeringsorganisatie of door een beleggingsadministrateur/asset service provider. De participatiewaardes en het aantal participaties van de cohortenpools vormen de basis voor de pensioenuitvoeringsorganisatie om vermogen expliciet aan deelnemers toe te delen. De administrateur van cohortenpools en beleggingspools ontvangt maandelijks de posities uit de leidende administratie van de beleggingsadministrateur van de beleggingspools, aangevuld met de posities uit de (schaduw) administratie van de fiduciair manager. Deze posities worden gereconcilieerd met de posities in de eigen administratie van de administrateur van cohortenpools en beleggingspools.
- Kan sprake zijn van een dubbele cohortenadministratie. De eerste ligt bij de pensioenuitvoeringsorganisatie en betreft de deelnemer- & cohortenadministratie. De tweede ligt bij "een administrateur", dat kan de pensioenuitvoeringsorganisatie, een andere gespecialiseerde partij of de beleggingsadministrateur/asset service provider zijn. In deze tweede rol wordt de relatie tussen de cohortenpools en de beleggingspools gelegd. Deze laatste administratie kan ook wel middenadministratie genoemd worden en is optioneel. Als deze niet van toepassing is dan administreert de pensioenuitvoeringsorganisatie op deelnemersniveau in welke beleggingspools de deelnemer belegt en geeft de pensioenuitvoeringsorganisatie de benodigde informatie rechtstreeks door aan de fiduciair manager.
- Ondersteunt de fiduciair manager de pensioenuitvoerder bij de totstandkoming van het integrale beleggingsbeleid. Hij draagt zorg voor de uitvoering van dit beleggingsbeleid en stuurt daarbij (operationele) vermogensbeheerders aan. De fiduciair manager zal ook een (schaduw) beleggingsadministratie voeren.
- Beheren de vermogensbeheerders onderdelen van de portefeuille. Zij worden daarbij aangestuurd door de fiduciair manager. Het is mogelijk dat (voor onderdelen) de fiduciair manager en de operationeel vermogensbeheerder tot dezelfde organisatie behoren.
- Verzorgt de beleggingsadministrateur/asset service provider (doorgaans aanvullende dienstverlening van de custodian) de onafhankelijke beleggingsadministratie van de beleggingspools voor de pensioenuitvoerder. Deze administratie wordt gevoed vanuit de afwikkeling van mutaties in de portefeuille van de beleggingspool, uitgevoerd door de operationele vermogensbeheerders die worden geïnstrueerd door de fiduciair manager. Deze beleggingsadministratie wordt gereconcilieerd met de (schaduw)administratie van de fiduciair manager.

In het proces voor "Model 2 uitgebreider, gelaagd ordermodel" wordt onderscheid gemaakt tussen een opbouwfase (links van de stippellijn in Figuur 4) en een uitkeringsfase (rechts in Figuur 4).

Voor zover de uitkeringsfase volledig is ondergebracht bij een verzekeraar is de gegevensuitwisseling out-of-scope van deze uitwerking van gegevensuitwisseling. In dat geval krijgt de verzekeraar het kapitaal van de deelnemer overgemaakt middels een uitgaande waardeoverdracht vanuit de pensioenuitvoeringsorganisatie en wordt daarmee een pensioenuitkering aangekocht bij de verzekeraar.

De uitkeringsfase die door een pensioenuitvoeringsorganisatie wordt uitgevoerd is in-scope. In de uitkeringsfase hebben deelnemers de keuze uit doorbeleggen (met een variabele pensioenuitkering) of voor een vaste pensioenuitkering. Bij een variabele uitkering kan het pensioenfonds kiezen voor een model met een individuele uitkeringsfase of een collectieve uitkeringsfase.

Bij een individuele uitkeringsfase kan de gegevensuitwisseling voor de doorbeleggen variant op dezelfde wijze worden ingericht als voor de opbouwfase (waarbij op hogere leeftijd bijvoorbeeld meer wordt belegd in kortere vastrentende waarden).

Bij een collectieve uitkeringsfase (alle gepensioneerden in één cohort), zowel bij vaste als variabele uitkeringen, is aansluiting van de rentegevoeligheid van de beleggingen (in een matchingportefeuille) bij de collectieve rentegevoeligheid van geprojecteerde uitkeringen van belang. Het is mogelijk dat de opbouwfase in model 1 (direct order model) plaatsvindt en de uitkeringsfase middels model 2 (uitgebreider order model). Tevens is het mogelijk dat er gekozen kan worden om individueel door te beleggen in de uitkeringsfase en later te switchen naar een collectieve uitkeringsfase. Deze switch heeft geen impact op de datavelden en/of gegevensuitwisseling tussen partijen.

Voor de uitkeringsfase (die uitgevoerd wordt door een pensioenuitvoerder) zal de fiduciair manager de (aansturing van een) matchingsportefeuille inrichten. Voor de benodigde gegevensuitwisseling stuurt de pensioenuitvoeringsorganisatie op periodieke (verwachting is maandelijkse) basis per regeling de geprojecteerde af te dekken uitkeringen per cohortpool naar de fiduciair manager. De gegevensuitwisseling zal daarvoor conform de gegevensuitwisseling 1b uit de SPR worden opgezet.

## 4.4Informatiestroom model 1 (1a en 1b)

De informatie-uitwisseling voor model 1 kan worden uitgesplitst naar een variant 1a waarin de pensioenuitvoeringsorganisatie zelf belegt en een variant 1b waarin de pensioenuitvoeringsorganisatie belegt via een order platform. Strikt genomen is er vanuit de pensioenuitvoeringsorganisatie bezien geen onderscheid tussen beide varianten maar voor de helderheid worden beide varianten apart uitgelegd. Een en ander wordt schematisch en vereenvoudigd weergegeven in Figuur 5 respectievelijk Figuur 6_._ Via een broker zou een pensioenuitvoeringsorganisatie bijvoorbeeld ETF's kunnen verhandelen namens het pensioenfonds als deze onderdeel zijn van de afgesproken beleggingsmix.

![](RackMultipart20231222-1-avhyj4_html_701e87d2c8b2091e.gif)

**Figuur 5 - Model 1a: de pensioenuitvoeringsorganisatie belegt direct bij diverse marktpartijen**

De gegevensuitwisseling, in Figuur 5 aangeduid met "scope", vindt in dit model plaats tussen de pensioenuitvoeringsorganisatie enerzijds en de diverse type marktpartijen anderzijds.

![](RackMultipart20231222-1-avhyj4_html_c1e9b52e0cb6d549.gif)

**Figuur 6 - Model 1b: de pensioenuitvoeringsorganisatie geeft beleggingsopdrachten aan een tussenpartij (order platform: custodian, fiduciair)**

Gegevensuitwisseling (scope) uit Figuur 6 vindt uitsluitend plaats tussen pensioenuitvoeringsorganisatie en order platform.

### 4.4.1Informatiestroom van Pensioenuitvoeringsorganisatie naar Brokers/Transfer Agents/Order Desks 1a

De informatiestroom is de minimale set aan gegevens die benodigd is om een order te kunnen sturen aan een order verwerkende partij. Tevens kan er een switch mee worden uitgevoerd. De pensioenuitvoeringsorganisatie stuurt orders in op het hoogste niveau van het beleggingsfonds. De aanbieder van het fonds voert zelf de ordering uit in de onderliggende beleggingen. Dat kan onder andere genoteerde en illiquide beleggingen betreffen.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.6.

### 4.4.2Informatiestroom van brokers/transfer agents/order desks naar pensioenuitvoeringsorganisatie 1b

Vanuit de order verwerkende partij komen de settlementgegevens van de order terug naar de pensioenuitvoeringsorganisatie.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.7.

## 4.5Informatiestroom model 2

De informatie-uitwisseling van model 2 (uitgebreider, gelaagd ordermodel) kan schematisch vereenvoudig als volgt worden weergegeven.

![](RackMultipart20231222-1-avhyj4_html_f76406ef2ac51bde.gif) **Figuur** _ **7** _ **- Model 2: de pensioenuitvoeringsorganisatie laat beleggen**

De gegevensuitwisseling, in Figuur 7 aangeduid met "scope" leidt tot de uitwisseling van diverse informatiestromen. De gestandaardiseerde gegevensuitwisseling die binnen de scope vallen zijn worden in onderstaande procesflow figuren aangegeven met rode pijlen de gegevens nodig voor die verschillende informatiestromen/processen wordt in de paragrafen daarna uitgewerkt. Let op: De tijdaanduidingen in onderstaande figuren zijn indicatief en kunnen per pensioenuitvoerder anders worden ingevuld. Dit document gaat slechts over de informatiestromen.

De informatiestroom van model 2 heeft diverse stappen – zie de (stap)nummers hieronder in een 2-tal proces flow schema's (de figuren 8 en 9)

# 6
.

![](RackMultipart20231222-1-avhyj4_html_fc6f2b9749e5dca.gif)

**Figuur 8 - Proces flow & datauitwisseling FPR (1)**

**Toelichting bij Figuur 8: Proces flow & datauitwisseling FPR (1) - standaard**

Het weergegeven proces heeft als uitgangspunt één administrateur van zowel cohortenpools als beleggingspools. Deze administrateur verzorgt de koppeling van ontvangen geaggregeerde gegevens over deelnemers (via cohortenpools) naar de beleggingen (via beleggingspools).

In stap 5 naar stap 10 levert de pensioenuitvoeringsorganisatie de mutaties in aantal participaties per cohort (op cohortniveau, dus niet voor onderliggende deelnemers) aan de administrateur cohortenpools (rekening houdend met premiestortingen en onttrekkingen).

Deze administrateur stelt op basis van de gereconcilieerde administratie van de beleggingspools (stap 8) de voorlopige participatiewaarde per participatie vast (stap 9).

Door de aangeleverde mutaties in aantallen participaties per cohort (stap 5) te combineren met de berekende voorlopige participatiewaarde en de herbalanceringsregels (ofwel de norm-allocaties per cohort naar beleggingspools) worden de benodigde transacties in beleggingspools berekend die per cohort gedaan moeten worden.

Door deze transacties voor alle cohorten te combineren (en daarmee te salderen, wanneer tegengesteld) resulteert per beleggingspool één instructie in euro die aan de fiduciair manager wordt gecommuniceerd. De fiduciair manager voert voor deze bedragen transacties uit in de beleggingspools (stap 11).

Deze transacties vloeien via SWIFT naar de beleggingsadministrateur/asset service provider (stap 15).

De administrateur beleggingspools berekent de definitieve unitwaarden voor de beleggingspools op basis van de administratie die met de beleggingsadministrateur/asset service provider wordt gereconcilieerd (stap 16).

De unitwaarden voor de beleggingspools, de posities die cohortenpools in de beleggingspools houden en het aantal participaties vormen de basis om de participatiewaarde voor cohortenpools te bereken (stap 17).

Deze worden met de pensioenuitvoeringsorganisatie gedeeld (stap 18) zodat de waarde voor individuele deelnemers kan worden vastgesteld.

**Toelichting bij Figuur 8 – Proces flow & datauitwisseling FPR(1) – variant 1**

(Variant pensioenuitvoeringsorganisatie heeft ook de rol van administrateur cohortenpools)

Het is mogelijk dat de beschreven rollen van administrateur cohorten en beleggingspools anders zijn toebedeeld. De pensioenuitvoeringsorganisatie kan de rol van administrateur cohortenpools vervullen. In dat geval zullen de stappen 9 en 10 geheel naar de pensioenuitvoeringsorganisatie verschuiven.

In stap 8 zal de administrateur beleggingspools dan aan de pensioenuitvoeringsorganisatie voorlopige unitwaardes voor de beleggingspools door moeten geven. Deze zijn nodig voor de pensioenuitvoeringsorganisatie om de participatiewaarden van cohortenpools in stap 9 te bepalen.

Doordat de stappen uit elkaar worden getrokken is een additionele informatie-uitwisseling tussen deze partijen noodzakelijk. Dit geldt ook voor de definitieve waardebepaling. De administrateur beleggingspools blijft de definitieve unitwaarde voor beleggingspools berekenen (stap 16) maar moet deze communiceren met de pensioenuitvoeringsorganisatie omdat deze de participatiewaarden voor cohortenpools berekent (stap 17). Bij de uitwerking van de stappen 8 en 16 in de paragrafen hierna wordt hieraan expliciet aandacht aan geschonken.

**Toelichting bij Figuur 8 – Proces flow & datauitwisseling FPR(1) - variant 2** (Variant pensioenuitvoeringsorganisatie heeft ook de rol van administrateur cohortenpools & beleggingsadministrateur/asset service provider de rol van administrateur beleggingspools)

Daarnaast is mogelijk dat de beleggingsadministrateur/asset service provider de rol van administrateur beleggingspools vervult en de pensioenuitvoeringsorganisatie de rol van administrateur cohortenpools.

De beleggingsadministrateur/asset service provider treedt dan in de plaats voor de administrateur beleggingspools.

**Toelichting bij Figuur 8 – Proces flow & datauitwisseling FPR(1) -variant 3**
(Variant beleggingsadministrateur/asset service provider rol van administrateur cohortenpools en de rol van administrateur beleggingspools)

Ten slotte is het ook mogelijk dat de beleggingsadministrateur/asset service provider zowel de beschreven rol van administrateur cohortenpools als van administrateur beleggingspools vervult. Bij deze rolverdeling verandert er niets aan het beschreven proces, behalve dat overal beleggingsadministrateur/asset service provider gelezen moet worden voor administrateur cohortenpools en beleggingspools staat. Een aantal informatiestromen vinden dan plaats binnen deze partij.

![](RackMultipart20231222-1-avhyj4_html_afc02851f676c798.png)

**Figuur 9 - Proces flow & datauitwisseling FPR (2)**

**Toelichting bij Figuur 9 Proces flow & datauitwisseling FPR (2)**

Het weergegeven proces gaat uit van een administrateur van cohortenpools en beleggingspools. Indien de pensioenuitvoeringsorganisatie de rol van administrateur van cohortenpools vervult dan zullen de stappen 19, 20 en 22 verschuiven naar de pensioenuitvoeringsorganisatie terwijl stap 27 komt te vervallen.

### 4.5.1Informatiebehoefte administrateur cohortenpools en beleggingspools

**Informatiestroom van pensioenuitvoeringsorganisatie naar administrateur van cohortenpools en beleggingspools in de FPR (5**  **-\>**** 10 in schema) op T-4:**

![](RackMultipart20231222-1-avhyj4_html_c1b78607b7f61ddc.png)De eerste (naar verwachting maandelijkse) informatiestroom van de pensioenuitvoeringsorganisatie naar de administrateur van cohortenpools en beleggingspools (stroom van 5 naar 10 in de Figuur x) betreft gesaldeerde mutaties, zijnde aankoop, verkoop en switches op totaalniveau per cohortenpool welke worden doorgegeven aan de administrateur cohortenpools en beleggingspools. Deze administrateur kan hiermee de in- of uitstroom voor beleggingspools berekenen en daarmee de fiduciair manager instrueren.

Indien de pensioenuitvoeringsorganisatie de rol van administrateur cohortenpools vervult dan zal stap 10 daar ook plaatsvinden.

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.8.

### 4.5.2Reconciliatie administrateur van cohortenpools en beleggingspools, fiduciair manager en beleggingsadministrateur

![](RackMultipart20231222-1-avhyj4_html_4cc50e34ea2293ed.png)**Informatiestroom tussen administrateur van cohortenpools en beleggingspools, Fiduciair manager en beleggingsadministrateur (6**  **-\>** **7 -\> 8 in schema) op T-4:**

De administrateur cohortenpools en beleggingspools ontvangt maandelijks de posities uit de leidende administratie van de beleggingsadministrateur van de beleggingspools, mogelijk aangevuld uit de (schaduw) administratie van de fiduciair manager. Deze posities worden gereconcilieerd
# 7
 met de posities in de eigen administratie van de administrateur van cohortenpools en beleggingspools

4.5.2.a Reconciliatie administrateur van cohortenpools en beleggingspools, fiduciair manager en beleggingsadministrateur

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.9

4.5.2 b additionele informatie als de pensioenuitvoeringsorganisatie (ook) de rol van administrateur van cohortenpools vervuld.

Indien de pensioenuitvoeringsorganisatie de rol van administrateur cohortenpools vervult dan is een additionele informatie-uitwisseling nodig van de administrateur beleggingspools naar de pensioenuitvoeringsorganisatie over de voorlopige unitwaarden van de beleggingspools. Deze is in de onderstaande tabel weergegeven. Door ook het aantal uitgegeven units per beleggingspool te delen wordt de pensioenuitvoeringsorganisatie in staat gesteld om de aansluiting bij het aantal gehouden units in de beleggingspools door alle cohortenpools te reconciliëren.

Functionele uitwerking naar bericht: zie hoofdstuk 6 met name Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.10

### 4.5.3Informatie aansturen beleggingspools

**Informatiestroom tussen Administrateur van cohortenpools en beleggingspools en Fiduciair manager (10**  **-\>** **11 in schema) op T-4:**

![](RackMultipart20231222-1-avhyj4_html_ec46d7a7ab80ee3e.png)De administrateur van cohortenpools en beleggingspools berekent de Participatiewaarden van Actieve Leeftijdsgroepen en combineert deze waarden met de opgegeven mutaties om de casheffecten op de beleggingspools te schatten. De administrateur cohortenpools en beleggingspools verstuurt de casheffecten op de beleggingspool (met onderbouwing) naar de fiduciair in het volgende format.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.11.

### 4.5.4Rebalancing cohortenpools

![](RackMultipart20231222-1-avhyj4_html_ec4c0c1978f178ef.png)**Informatiestroom tussen Administrateur van cohortenpools en beleggingspools en Fiduciair manager (20**  **-\>** **21 in schema) op T+3:**

De administrateur van cohortenpools en beleggingspools herbalanceert de relevante leeftijdsgroepen om op basis van de unitwaarden van de beleggingspools van tijdstip T conform het normbeleid belegd te zijn voor alle cohorten.

De administrateur van cohortenpools en beleggingspools verstuurt alle maandultimo transacties in de cohortenpools en beleggingspools in het afgesproken format naar de fiduciair manager.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.12.

### 4.5.5Doorgeven waardes per beleggingspool en per cohortenpool

**I ![](RackMultipart20231222-1-avhyj4_html_dffb31965ac8ab9a.png) nformatiestroom tussen beleggingsadministrateur, administrateur van cohortenpools en beleggingspools, fiduciair manager en pensioenuitvoeringsorganisatie (15 -\> 16 -\> 17 -\> 18 in schema) op T+3**

De administrateur van cohortenpools en beleggingspools berekent de unitwaarde per unit in de beleggingspool en de participatiewaarde per participatie in de cohortenpool.

De administrateur van cohortenpools en beleggingspools geeft de (participatie)waarden van de cohortenpools door aan de pensioenuitvoeringsorganisatie en aan de fiduciair.

Indien de pensioenuitvoeringsorganisatie de rol van de administrateur cohortenpools vervult dan zal deze de unitwaarden van de beleggingspools ontvangen van de administrateur beleggingspools maar zelf zorgdragen voor de berekening van de participatiewaarden van de cohortenpools. De fiduciair manager zal deze dan ook ontvangen van de pensioenuitvoeringsorganisatie.

4.5.5.a Fiduciair ontvangt van de pensioenuitvoeringsorganisatie (pensioenuitvoeringsorganisatie administreert cohortenpools)

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.13.

4.5.5.b De administrateur van cohortenpools en beleggingspools geeft (daarnaast) de (unit)waarden, de administratieve koers, van beleggingspools door.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.14.

### 4.5.6Betaalinstructies onttrekkingen

**Informatiestroom tussen administrateur van cohortenpools en beleggingspools en fiduciair manager (22**  **-\>** **23 in schema), begin van de maand, in het schema op T+5:**

![](RackMultipart20231222-1-avhyj4_html_d9911630be07feec.png)

De administrateur van cohortenpools en beleggingspools verstuurt de betaalinstructie voor onttrekkingen naar de fiduciair manager.

Functionele uitwerking naar bericht: zie hoofdstuk 6 en met name 6.4.15

# 5Aanpak/opzet gegevensstandaard

**In dit hoofdstuk leggen we uit hoe we komen tot specificaties van de berichten.**

**Stappen om te komen tot de functionele specificaties van de berichten:**

1. **Maak beschrijvingen van de processen en informatiestromen.**
2. **Stel een lijst op met entiteiten en bijbehorende attributen.**
3. **Bepaal de basisstructuur van de berichten.**
4. **Geef aan welke berichten nodig zijn.**
5. **Maak een kruistabel tussen de basisstructuur en de berichten.**

**De relatie met SIVI AFS leggen we uit. De bouwstenen uit SIVI AFS (AFD 2.0) gebruiken we om tot technische specificaties te komen.**

## 5.1Maak beschrijvingen van de processen en informatiestromen

Om de koppelvlakken inclusief berichtuitwisseling tussen partijen in de keten(s) te kunnen standaardiseren maken we beschrijvingen van de verschillende ketenprocessen zoals die plaatsvinden, inclusief op hoofdlijnen de gewenste functionaliteit bij de ketenactoren. Tevens geven we aan welke informatiestromen aan de orde zijn. Gevisualiseerde afbeeldingen van de informatiestromen tussen partijen zijn hierbij een hulpmiddel.

**De processen & informatiestromen staan uitvoering beschreven in**  **het rapport ''**** [Resultaten onderzoek: Standaard voor datauitwisseling pensioenuitvoering & vermogensbeheer partijen''](https://www.pensioenfederatie.nl/cms/streambin.aspx?documentid=18380):**

**Hoofdstuk 4: Solidaire premieregeling.**

**Hoofdstuk 5: Flexibele premieregeling.**

Zie ook hoofdstuk 3 van deze handleiding.

## 5.2Stel een lijst op met entiteiten en bijbehorende attributen

Maak definities van entiteiten en attributen. Maak waar mogelijk gebruik van codelijsten, waarbij de voorkeur uitgaat naar bestaande codelijsten. Geef ook de vereiste verbanden tussen de gegevenselementen aan. Iedere entiteit en ieder attribuut krijgt op technisch niveau ook een label. De labels worden met bijbehorende waarden opgenomen in een bericht. Een computer kan hierdoor de gegevens uit het bericht automatisch verwerken. In Figuur 10 zijn de bouwstenen van een gegevensmodel opgenomen.

![](RackMultipart20231222-1-avhyj4_html_afbc844e4a26c01a.gif)

**Figuur 10 – Bouwstenen gegevensmodel**

## 5.3Bepaal de basisstructuur van de berichten

Maak tevens de opbouw van de berichten duidelijk, bijvoorbeeld:

Entiteit A V

Entiteit B\* V, 1… 999

Entiteit C V, 1

Entiteit D F, 1

Entiteit A komt 1 keer verplicht voor.

Entiteit B komt minimaal 1 keer voor en maximaal 999 keer.

Entiteit C is genest onder entiteit B en komt verplicht 1 keer voor.

Entiteit D is genest onder entiteit B en komt maximaal 1 keer voor.

## 5.4Geef aan welke berichten nodig zijn.

Stel op basis van de beschrijvingen van de processen en informatiestromen vast welke berichten nodig zijn.

## 5.5Maak een kruistabel tussen de basisstructuur en de berichten.

Geef per bericht in de tabel aan welke entiteiten/attributen van toepassing. Geef hierbij het aantal herhalingen (entiteiten) aan en geef ook aan welke attributen verplicht gevuld moeten worden. Het is tevens mogelijk selecties uit codelijsten te maken, dat wil zeggen aan te geven welke codewaarden van toepassing zijn.

Onderstaande Figuur 11 geeft aan hoe we vanuit een verzameling entiteiten/attributen meerdere basisstructuren opstellen en hoe we van iedere basisstructuur meerdere functionele berichten kunnen afleiden. Tenslotte leveren we technische berichtspecificaties. Figuur 11 licht een en ander toe.

![](RackMultipart20231222-1-avhyj4_html_1eb38fd35c3563e5.gif)

**Figuur 11 - Van entiteiten naar basisstructuur naar functionele berichten naar technische berichtdefinities**

## 5.6Relatie met SIVI AFS

Het Engelstalige AFD 2.0 is onderdeel van de SIVI All Finance Standaard. Via [AFD 2.0 Online Raadplegen](https://www.sivi.org/standaarden/sivi-all-finance-standaard/afd-online-2-0/) kun je online zoeken op alle entiteiten, attributen en codelijsten. Aanvullend vind je ook een overzicht van AFD 2.0 in XLS-formaat. Pensioen is tot op zekere hoogte al in AFD 2.0 aanwezig. Dit heeft onder andere te maken met de mapping die SIVI ontwikkelde voor het [Ockto Datamodel](https://www.sivi.org/actueel/persbericht-sivi-en-ockto-brengen-registratie-klantdata-stap-verder/). Ockto heeft een koppeling met pensioenregister. Gebruik van JSON is een uitgangspunt bij AFD 2.0.

AFD 2.0 bevat bouwstenen die we gebruiken bij het specificeren van de entiteiten en attributen ten behoeve van de standaard voor datauitwisseling tussen vermogensbeheer en pensioenuitvoering. Hierbij geven we aan welke AFD 2.0 bouwstenen we gebruiken en welke bouwstenen ontbreken. Deze laatste kan SIVI dan aan AFD 2.0 toevoegen. Naast entiteiten/attributen kan het daarbij ook gaan om codelijsten.

# 6Functionele specificaties

**In dit hoofdstuk volgen de functionele specificaties:**

- **Datadictionary;**
- **Basisbericht;**
- **Kruisreferentie basisbericht & berichten.**

## 6.1Datadictionary

De datadictionary geeft een overzicht van alle gebruikte entiteiten en entiteittypen die worden gebruikt binnen deze standaard.

Pm de _ **rood vet italic** _gemarkeerde berichten zijn t.b.v. de deze standaard nieuw toegevoegd aan AFD 2.0. De overige entiteiten en gegevens zijn bestaande AFD 2.0 entiteiten en gegevens.

| **Entity.entitytype** |
| --- |
| commonTechnical.default |
| party.sender |
| party.contact |
| party.receiver |
| commonFunctional.default |
| party.pensionProvider |
| _ **pension.scheme** _ |
| _ **financialInformation.reportingPeriod** _ |
| _ **financialTransaction.payment** _ |
| _ **party.creditor** _ |
| _ **capital.default** _ |
| _ **financialTransaction.cashflow** _ |
| _ **pension.cohort** _ |
| _ **pension.cohortPool** _ |
| _ **investment.pool** _ |
| _ **investment.portfolio** _ |
| _ **investment.investmentDetails** _ |
| _ **financialTransaction.trade** _ |
| error.default |
| document.default |

## 6.2Entiteiten en entiteitstypen

![](RackMultipart20231222-1-avhyj4_html_92dca21913e032a4.png)

In deze paragraaf zijn de diverse entiteiten en de attributen binnen die entiteiten beschreven.

Hieronder volgt een toelichting op de entiteiten. Deze informatie is ontleend aan AFD 2.0 wat via deze [link](https://www.sivi.org/standaarden/sivi-all-finance-standaard/afd-online-2-0/) kan worden geraadpleegd.

Let op: het entiteittype is verplicht.

| Entiteit.entiteittype | Toelichting |
| --- | --- |
| commonTechnical.default | Deze entiteit bevat technische details over het verzenden en opslaan van berichten. Het vormt als het ware de basis voor de technische aspecten binnen het berichtensysteem. |
| --- | --- |
| party.sender | De entiteit "party.sender" verwijst naar de afzender van het bericht. |
| party.contact | De entiteit "party.contact" vertegenwoordigt een contactpersoon binnen een juridische entiteit. Deze contactpersonen kunnen worden benaderd voor verdere informatie over het bericht. |
| party.receiver | Deze entiteit vertegenwoordigt de ontvanger van het bericht. |
| commonFunctional | Binnen deze entiteit bevindt zich domeinspecifieke informatie over de inhoud van het bericht. Het geeft context en betekenis aan de functioneledetails in het bericht. |
| party.pensioenProvider | Deze entiteit staat voor een pensioenuitvoerder, Een pensioenuitvoerder is een pensioenfonds, verzekeraar of premiepensioeninstelling (PPI) waar pensioen wordt opgebouwd voor de werknemer door de werkgever. |
| pension.scheme | Deze entiteit is bevat gegevens op het niveau van de pensioenregeling of het pensioenplan of -schema. |
| financialInformation.reportingPeriod | Deze entiteit heeft betrekking op rapportageperiodes, tijdsintervallen waarvoor wordt gerapporteerd en andere generieke datums. |
| financialTransaction.payment | Deze combinatie van entiteit en entiteittype gegevens over een betaling. |
| party.creditor | Deze entiteit vertegenwoordigt de crediteur; de ontvanger van de betalingen, binnen het ecosysteem waarin de berichten worden uitgewisseld. |
| financialTransaction.cashflow | Deze entiteit behandelt financiële transacties met betrekking tot pensioenen, specifiek gericht op kasstromen. |
| pension.cohort | Deze entiteit bevat informatie over specifieke doelgroepen binnen het pensioenschema. |
| pension.cohortPool | De gepoolde (verzamelde) combinatie van beleggingspools voor een cohort.) Bij FPR wordt óf individueel belegd (via trades in investments) of wordt gezamenlijk belegd in investmentpools via cohortPools. In deze entiteit worden de gegevens over het pensioenvermogen en de in- en uitstroom voor een gepoolde (verzamelde) combinatie van beleggingen (beleggingspools) voor een cohort vastgelegd.In een cohortpool wordt belegd voor een groep deelnemers die op basis van de mate van risico een gelijke beleggingsverdeling kennen. |
| investment.pool | Deze entiteit (beleggingspool) vertegenwoordigt de collecties van uiteenlopende onderliggende beleggingen (liquide, illiquide, fondsen en mandaten). |
| investment.portfolio | Deze entiteit heeft betrekking op beleggingsportefeuilles, die het totaal beheerde vermogen (of een deelvermogen) binnen het collectief weergeven. |
| investment.investmentdetails | Deze entiteit beschrijft individuele beleggingen van een pensioenuitvoerder in aandelen of beleggingsfondsen. |
| financialTransaction.trade | Deze entiteit heeft betrekking op handelsactiviteiten binnen het pensioenschema. |
| error | In het geval van fouten in het systeem wordt deze entiteit gebruikt om foutmeldingen te genereren en aan te geven wat er precies mis is gegaan. |
| document | Deze entiteit is bedoeld voor het toevoegen van eventuele bijlagen aan berichten. |

## 6.3Attributen in entiteiten.entiteitstypen

Hierna worden de attributen per combinatie van entiteit en entiteitstype beschreven.

De beschrijving bevat naast de attribuutnaam een definitie van het attribuut, het datatype van het attribuut, de beoogde maximale lengte van het gegeven en een verwijzing naar een eventuele codelijst.

De attribuutnamen wijken af van de naamgeving in het consultatiedocument; ze zijn nu – mede – vormgegeven op basis van de AFD 2.0 conventies. In de bijlage is een vertaaltabel opgenomen: _Vertaaltabel van functionele attributen naar AFD2.0 attributen.(10.6)._

| **commonTechnical.default** |
| --- |
| The commonTechnical entity covers all information about sending or storing the message. This is typically technical information. (NL: Bericht Algemeen) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| messageId | Unieke berichtidentificatie | string | 22 |   |
| messageVersion | Versie van de standaard | string | 10 | ADNVER |
| creationDateTime | Aanmaakdatum en tijd Date | timestamp | 24 |   |
| _ **testMessage** _ | Indicatie testbericht | boolean | 1 | Logical Unit |

| **party.sender** |
| --- |
| Sender. (NL: Partij Zender) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| rsinNumber | Governmental identification number for legal entities and associations (RSIN) | integer | 8 |   |
| organizationName | Organisatie naam van de afzender | string | 60 |   |
| applicationSenderName | Naam van de applicatie die het bericht heeft aangemaakt | string | 60 |   |

| **party.contact** |
| --- |
| A natural person who can be contacted within a legal person for further information. (NL: Partij Contactpersoon) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| surname | Achternaam | string | 60 |   |
| firstName | Voornaam | string | 30 |   |
| prefixes | Tussenvoegsel | string | 10 |   |
| initials | Voorletters | string | 10 |   |
| titlesPrefix | Voorvoegsel | string | 10 |   |
| gender | Geslacht | string | 3 | ADNGES |
| fullName | Volledige naam | string | 90 |   |

| **party.receiver** |
| --- |
| Receiver. (NL: Partij Ontvanger) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| rsinNumber | Governmental identification number for legal entities and associations (RSIN) | string | 8 |   |
| organizationName | Naam van de ontvanger(s) (organisatie(s)) | string | 60 |   |

| **commonFunctional.default** |
| --- |
| The commonFunctional entity covers all information about the content of the message. This is typically domain-specific information. (NL: Bericht Algemeen) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| function | Message function code. (NL: Code waarmee de functie van het bericht wordt aangegeven.) | string | 2 | ADNFUN |
| resending | commonFunctional.default. Retransmit previously sent message. (Only at the express request of the receiver). (NL: herzending van een eerder verzonden bericht op uitdrukkelijk verzoek van de ontvanger.) | boolean | 1 |   |
| afdDefinitionName | Soort bericht | string | 5 |   |
| _ **originalMessageId** _ | Het oorspronkelijke messageId van het bericht dat wordt vervangen door dit bericht | string | 22 |   |

| **party.pensionProvider** |
| --- |
| Information on pensionprovider Level (NL: Pensioenuitvoerder: Pensioenfonds, Pensioenverzekeraar, PPI, APF) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID van het pensioenuitvoerder (PUV-code) / Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| rsinNumber | Governmental identification number for legal entities and associations (RSIN) | integer | 8 |   |
| organizationName | Naam van de pensioenuitvoerder | string | 60 |   |

| **2.7 pension.scheme** |
 |
 |
 |
 |
| --- | --- | --- | --- | --- |
| **pension.scheme** |
| Data on pension scheme level |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID van de pensioenregeling / (Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.)) | string | 70 |   |
| _ **pensionschemeName** _ | Naam van de pensioenregeling | string | 30 |   |
| _ **StartAmount** _ | Totaal pensioenvermogen per begindatum | decimal | 13 |   |
| _ **expectedPensionPaymentDate** _ | Pensioenuitkeringsmoment (eventueel per regeling) | date | 10 |   |
| totalExpectedPensionPaymentAmount | Totaal geprojecteerde uitkeringen over alle cohorten | decimal | 13 |   |
| hedgedExpectedPensionPaymentAmount | Af te dekken kasstromen per periode | decimal | 13 |   |
| tradingPortfolioId | Portefeuille ID van de custodian (bewaren en beheren van financiële activa) | decimal | 10 |   |

| _ **financialInformation.reportingPeriod** _ |
| --- |
| Reportingperiod Information |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| _ **startDate** _ | Begindatum van de gegevensperiode waarop de aanlevering vanuit de PUO wordt gebaseerd | date | 10 |   |
| endDate | Einddatum van de gegevensperiode waarop de aanlevering vanuit de PUO wordt gebaseerd
Einddatum van de gegevensperiode waarover rendement wordt gerapporteerd | date | 10 |   |
| _ **mutationValuationDate** _ | Datum verwerking mutaties per leeftijdsgroep | date | 10 |   |
| _ **projectionDate** _ | Datum van de projectie van pensioenuitkeringen | date | 10 |   |
| _ **instructionDate** _ | Instructiedatum (datum van de bestelling verzonden door de PUO) | date | 10 |   |
| _ **unitValueEstimationDate** _ | Geeft de datum aan waarop de voorlopige unitwaarde (belegginspool) is bepaald | date | 10 |   |
| _ **participationValuationDate** _ | Prijsdatum participatiewaarde (cohortpool) | date | 10 |   |
| _ **positionDate** _ | De datum waarop de posities in de beleggingsadministratie zijn vastgesteld | date | 10 |   |

| _ **financialTransaction.payment** _ |
| --- |
| Information about payments. (NL: Betaalinformatie) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| amount | Bedrag in valuta | decimal | 10 |   |
| currencyType | Valuta | string | 10 | ISOVAL |
| collectionAccountIban | IBAN-nummer van debet rekening | string | 10 |   |
| description | Omschrijving van de transactie (betaling) | string | 30 |   |

| _ **party.creditor** _ |
| --- |
| The party that has a claim. (NL: Partij Crediteur) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| collectionAccountIban | IBAN-nummer van credit rekening per regeling | string | 10 |   |
| _ **collectionAccountInNameOf** _ | Naam van de tegenpartij per regeling | string | 10 |   |
| collectionAccountBic | Business Identifier Code (BIC) per regeling | string | 10 |   |
| _ **collectionAccountBicCorrespondent** _ | BIC-correspondent per regeling | string | 10 |   |

| _ **financialTransaction.cashflow** _ |
| --- |
| The sum of contributions and withdrawals on all cohorts |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| _ **contributionAmount** _ | Som van inleg | decimal | 13 |   |
| _ **contributionDate** _ | Datum van ontvangst van de inleg | decimal | 10 |   |
| _ **withdrawalAmount** _ | Som van de uitstroom | decimal | 13 |   |
| _ **withdrawalDate** _ | Datum waarop (uiterlijk) de liquiditeiten ten behoeve van de onttrekking zijn vrijgemaakt | decimal | 10 |   |
| _ **netAmount** _ | Som van inleg en onttrekkingen per regeling (net). Een negatief bedrag is een (netto) withdrawal. / Verschil tussen inleg en onttrekking. Een negatief bedrag is een (netto) onttrekking.) | decimal | 13 |   |
| _ **netDate** _ | Datum waarop gesaldeerde instroom en uitstroom wordt gefaciliteerd / Datum waarop het saldo van inleg en onttrekking is bepaald | decimal | 10 |   |

| _ **pension.cohort** _ |
| --- |
| Information on cohort (pension target audience) level |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID van het cohort | string | 70 |   |
| description | Beschrijving van het cohort | string | 30 |   |
| _ **startAmount** _ | Pensioenvermogen van het cohort per begindatum | decimal | 13 |   |
| _ **netAmount** _ | Som van inleg en onttrekkingen per cohort. Een negatief bedrag is een (netto) onttrekking.) | decimal | 13 |   |
| _ **contributionAmount** _ | Instroom te beleggen door de fiduciair manager | decimal | 13 |   |
| _ **withdrawalAmount** _ | Uitstroom te beleggen door de fiduciair manager | decimal | 13 |   |
| _ **expectedPensionPaymentAmount** _ | (Geprojecteerde) uitkering | decimal | 13 |   |
| _ **protectionReturnPercentage** _ | Het behaalde beschermingsrendement in percentage over gegevensperiode per regeling en per cohort | decimal | 10 |   |
| _ **excessReturnPercentage** _ | Het behaalde overrendement in percentage over gegevensperiode per regeling en per cohort | decimal | 10 |   |
| _ **protectionReturnAmount** _ | Het behaalde beschermingsrendement in valuta van de regeling over gegevensperiode per regeling en per cohort | decimal | 13 |   |
| _ **excessReturnAmount** _ | Het behaalde overrendement in valuta van de regeling over gegevensperiode per regeling en per cohort | decimal | 13 |   |

| _ **pension.cohortPool** _ |
| --- |
| De gepoolde (verzamelde) combinatie van beleggingen (beleggingspools) voor een cohort |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID van de cohortpool | string | 70 |   |
| _ **cohortRef** _ | Geeft aan op welk cohort in de regeling de cohortpool-gegevens betrekking hebben | string | 70 |   |
| description | Beschrijving | string | 30 |   |
| currencyType | Valuta van de cohortgegevens | string | 10 | ISO 4217 |
| _ **inflowPremiumAmount** _ | Premie-inleg per cohortpool per regeling | decimal | 13 |   |
| _ **inflowRebalanceAmount** _ | Geldbedrag van rebalance transacties per cohortpool per regeling | decimal | 13 |   |
| _ **numberOfNewParticipations** _ | Nieuwe uit te geven participaties in cohortpool per regeling (instroom) | decimal | 13 |   |
| _ **numberOfParticipations** _ | Aantal uitstaande units (participaties) in de Cohortpool | decimal | 13 |   |
| _ **numberOFRebalanceParticipations** _ | Rebalance participaties per cohortpool per regeling (bij overgang van een cohortpool naar een ander cohort) | decimal | 13 |   |
| _ **participationsSummedValueAmount** _ | Waarde per cohortpool (som participatiewaarde) per participationValuationDate | date | 13 |   |

| _ **investment.Pool** _ |
| --- |
| Beleggingspool / beleggingsportefeuille |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID van de beleggingspool per regeling | string | 70 |   |
| description | Beschrijving | string | 30 |   |
| _ **marketValueAmount** _ | _ **Marktwaarde per portefeuille per regeling in currencyType** _ | _ **decimal** _ | _ **13** _ |   |
| _ **unitsSummedValueAmount** _ | _**Waarde per beleggingspool(unitwaarde)**_ | _ **decimal** _ | _ **13** _ |   |
| _ **marketValueAmount** _ | _ **Marktwaarde in 'financialTransaction.cashflow.withdrawalAmount'** _ | _ **decimal** _ | _ **13** _ |   |
| _ **preliminaryMarketValueAmount** _ | _ **Voorlopige Marktwaarde per portefeuille per regeling in currencyType van de pool** _ | _ **decimal** _ | _ **13** _ |   |
| _ **preliminaryUnitValueAmount** _ | _ **Voorlopige unitwaarde in currencyType van de pool** _ | _ **decimal** _ | _ **13** _ |   |
| _ **numberOfUnits** _ | _ **Aantal units uitgegeven voor de beleggingspool,** _ | _ **decimal** _ | _ **13** _ |   |
| _ **currencyType** _ | _ **Valuta van de pool** _ | _ **string** _ | _ **10** _ | ISO 4217 |
| dummyCashId | ID voor dummy cash instrument per beleggingspool per regeling per cohort(pool) | decimal | 10 |   |
| buySellId | Aan- verkoopindicator; ID voor aan-/verkoop per beleggingspool per regeling per cohort | string | 10 | sell, buy |
| _ **tradeQuantity** _ | _**Aantal te verhandelen stukken (units) van de transactie**_ | _ **decimal** _ | _ **13** _ |   |
| _ **unitPrice** _ | _**Unitwaarde (/prijs) per beleggingspool per regeling per cohort**_ | _ **decimal** _ | _ **10** _ |   |
| _ **currencyExchangeRate** _ | _ **FX rate per beleggingspool per regeling per cohort** _ | _ **integer** _ | _ **10** _ |   |
| _ **tradeValueAmount** _ | _**Waarde transactie per beleggingspool per regeling (gesommeerd over cohorten)**_ | _ **integer** _ | _ **13** _ |   |

| _ **investment.portfolio** _ |
| --- |
| Beleggingsportefeuille |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | ID Beleggingsportefeuille / Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| _ **portfolioID** _ | ID Beleggingsportefeuille | string | 10 |   |
| description | Beschrijving | string | 30 |   |
| _ **startAmount** _ | De waarde van de Total Market Value aan het begin van de gegevensperiode | decimal | 13 |   |
| _ **netAmount** _ | Som van inleg en onttrekkingen per regeling (net). Een negatief bedrag is een (netto) withdrawal | decimal | 13 |   |
| _ **endAmount** _ | De waarde van de Total Market Value aan het eind van de gegevensperiode. Per regeling en beleggingsportefeuille | decimal | 13 |   |
| _ **returnPercentage** _ | Het behaalde rendement in percentage over gegevensperiode per regeling en per beleggingsportefeuille | decimal | 10 |   |
| _ **returnAmount** _ | Het behaalde rendement in valuta van de regeling over gegevensperiode per regeling en per beleggingsportefeuille | decimal | 13 |   |

| _ **investment.investmentDetails** _ |
| --- |
| Een belegging in zowel liquide (makkelijk verhandelbare) als illiquide (beperkt verhandelbare) fondsen of groepen (pools) daarvan. |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | Identifier (bijvoorbeeld ISIN of interne code) | string | 70 |   |
| description | De naam van de belegging / de officiële naam van het fonds / van het instrument | string | 30 |   |
| _ **currencyType** _ | Valuta van het instrument | string | 10 | ISO 4217 |
| _ **numberOfHoldings** _ | Aantal holdings per instrument per regeling per beleggingsportefeuille | decimal | 13 |   |
| _ **localPrice** _ | Prijs per instrument in originele valuta per regeling per beleggingsportefeuille | decimal | 10 |   |
| _ **localValueAmount** _ | Totale marktwaarde in originele valuta per instrument per regeling per beleggingsportefeuille[1] | decimal | 13 |   |
| _ **result** _ | Ongerealiseerd resultaat per instrument per regeling per beleggingsportefeuille | decimal | 10 |   |
| _ **accruedInterest** _ | Opgelopen rente per instrument per regeling per beleggingsportefeuille | decimal | 10 |   |
| _ **poolPercentage** _ | Gewicht in de portefeuille per instrument per regeling per beleggingsportefeuille[2] | decimal | 10 |   |
| _ **currencyExchangeRate** _ | FX rates per instrument per regeling per beleggingsportefeuille / koers per positionDate | decimal | 10 |   |

| _ **financialTransaction.trade** _ |
| --- |
| Handelen/ orderen; Kopen en verkopen |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| _ **tradeDate** _ | Gewenste handelsdatum | date | 10 |   |
| _ **investmentOrderSettlementDate** _ | Datum waarop de volledige cyclus van de beleggingsorder afgewikkeld moet zijn. | date | 10 |   |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| _ **adjustmentIndicator** _ | Aangepaste trade instructie | boolean | 1 |   |
| _ **buySellId** _ | Aan- verkoop- switchindicator | integer | 3 | sell, buy, switch |
| _ **tradeAmount** _ | Bedrag van de aankoop in de valuta waarin de belegging luidt | decimal | 13 |   |
| _ **tradeQuantity** _ | Aantal te verhandelen stukken (units) van de transactie | decimal | 13 |   |
| _ **tradePrice** _ | Aankoopprijs / koers | decimal | 13 |   |
| _ **switchType** _ | Type switch; one-day of sequential | decimal | 3 | sequential, one-day |
| _ **counterparty** _ | Transfer Agent; de partij die de aankoop/verkoop verricht | string |   |   |
| _ **broker** _ | Effectenmakelaar die beleggingsorders uitvoert namens klanten op de markt | string |   |   |
| _ **interest** _ | Bedrag aan van toepassing zijnde rente | decimal | 13 |   |
| _ **commissionAmount** _ | Vergoeding voor het uitvoeren van de transactie | decimal | 13 |   |
| _ **clearingBroker** _ | Effectenmakelaar verantwoordelijk administratieve en financiële afwikkeling van de transactie | string |   |   |

| **error.default** |
| --- |
| Error message. (NL: Foutmelding) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Codelijst** |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| errorCode | Error code type. (NL: Soort foutmelding code.) | string | 2 | ADNFTM |
| errorCodeExplanation | Explanation of the error message. (NL: Toelichting op de soort foutmelding.) | string | 60 |   |

| **document.default** |
| --- |
| Information about an attachment/document. (NL: Bijlage) |
| **Attribuutnaam** | **Definitie** | **datatype** | **lengte** | **Optional** |
| refKey | Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) | string | 70 |   |
| fileName | Name of the file under which the attachment can be saved. (NL: Naam van het bestand waaronder de bijlage kan worden opgeslagen.) | string | 60 | DOCFLNM |
| fileExtension | Extension of the file under which the attachment can be saved. For example "pdf", "doc", etc. (NL: Extensienaam van het bestand waaronder de bijlage kan worden opgeslagen. Bijvoorbeeld "PDF", "DOC", etc.) | string | 10 | DOCEXT |

## 6.4Berichten

Het basisbericht wordt hierna uitgewerkt naar een 14-tal specifieke berichten.

Onderstaande Figuur 12 geeft een overzicht van die berichten en tussen welke rollen ze worden uitgewisseld:

| **Berichtnaam** | **Soort** | **PUO** | **FM** | **BA** | **ACB** | **BR** |
| --- | --- | --- | --- | --- | --- | --- |
| **1. Vermogen (0001a)** | SPR | van | naar |   |   |   |
| **2. Cashflow (0001b)** | SPR | van | naar |   |   |   |
| **3. Pensioenprojectie (0001c)** | SPR | van | naar |   |   |   |
| **4. Rendementsinformatie (00002)** | SPR | naar |   | van |   |   |
| **5. Orderopdracht (00541)** | FPR | van |   |   |   | naar |
| **6. Ordersettlement (00542)** | FPR | naar |   |   |   | van |
| **7. Mutatiesaldi (00551)** | FPR | van |   |   | naar |   |
| **8. Reconciliatie-informatie (00552a)** | FPR |   | van | van | naar |   |
| **9. PUO-reconciliatie-informatie (00552b)** | FPR | van |   |   | naar |   |
| **10. Stuurinformatiebeleggingspools (00553)** | FPR |   | naar |   | van |   |
| **11. Rebalancinginformatie (00554)** | FPR |   | naar |   | van |   |
| **12. Waarde-informatie cohortenpool (00555a)** | FPR | van | naar |   | van |   |
| **13. Waarde-informatie beleggingspool (00555b)** | FPR | naar | naar |   | van |   |
| **14. Betaalinformatie (00556)** | FPR |   | naar |   | van |   |

**Figuur-12 – Overzicht berichten tussen zenders en ontvangers**

**Legenda**

- Pensioenuitvoeringsorganisaties (PUO)
- Fiduciair managers (FM)
- Beleggingsadministrateurs / Asset service provider (BA)
- Administrateurs cohorten- en beleggingspools (ACB)
- Brokers / Transfer agents (BR)

In onderstaande tabel de berichtsoorten en de betekenis. Tussen haakjes de verwijzing naar het eindrapport.

PMT = pensionMessageType in AFD 2.0 (aangegeven zijn de omschrijvingen van de berichttypes).

| **Soort** | **Berichtsoort** | **PMT** | **Omschrijving** |
| --- | --- | --- | --- |
| **SPR** | 1a
(4.2.1.1)

 | Vermogen | **Van  Naar** Van pensioenuitvoeringsorganisatie naar fiduciair manager en beleggingsadministrateur/ asset service provider.
Op periodieke (naar verwachting maandelijkse) basis ontvangt de fiduciair manager over een pensioenuitvoerder per regeling het totale pensioenvermogen bij aanvang van de periode.
Naast de informatie op totaalniveau kan de fiduciair ook per cohort het pensioenvermogen ontvangen. Zo kan bijvoorbeeld voor het leeftijdscohort 25-29 jaar het totaal van de persoonlijke pensioenvermogens bij aanvang worden ontvangen.
Met de cohortinformatie kan de fiduciair manager desgewenst een totaalberekening maken en de aansluiting bij de geleverde informatie op totaal/collectief niveau toetsen aan het beleid van het fonds. Dit is nuttig voor een robuuste overdracht en audittrail afhankelijk van afspraken die partijen maken. Conform het beleid van de pensioenuitvoerder kan bij (grote) afwijkingen herbalancering wenselijk zijn. Deze informatie kan behalve aan de fiduciair manager desgewenst ook worden verstrekt aan de beleggingsadministrateur/asset service provider om deze ook in staat te stellen toetsings- en rapportage-activiteiten uit te voeren met behulp van de leidende beleggingsadministratie.
 |
| --- | --- | --- | --- |
| **SPR** | 1b (4.2.1.3)
 | Cashflow | Instroom en uitstroom
**Van  Naar** Van pensioenuitvoeringsorganisatie naar fiduciair manager en beleggingsadministrateur/ asset service provider.
Op periodieke (naar verwachting maandelijkse) basis ontvangt de fiduciair manager over een pensioenuitvoerder per regeling de instroom in de periode en de uitstroom. Naast op totaalniveau kan ook per cohort instroom en uitstroom aangeleverd worden.
De in- en uitstroom bevat naast premies, waardeoverdrachten en uitkeringen ook de verschuivingen over cohorten als daar sprake van is. Een cohort kan ook een geboortejaar zijn. Ook het 'cohort' solidariteitsreserve, het 'cohort' compensatiedepot en mogelijk andere reserves zullen hierbij betrokken worden.
Met de cohortinformatie kan de fiduciair manager desgewenst een totaalberekening maken en de aansluiting bij de geleverde informatie op totaal/collectief niveau toetsen aan het beleid van het fonds. Dit is nuttig voor een robuuste overdracht en audittrail afhankelijk van afspraken die partijen maken. Deze informatie kan behalve aan de fiduciair manager desgewenst ook worden verstrekt aan de beleggingsadministrateur/asset service provider om ook deze in staat te stellen toetsings- en rapportage-activiteiten uit te voeren met behulp van de leidende beleggingsadministratie.
 |
| **SPR** | 1c (4.2.1.3)
 | Pensioenprojectie | Geprojecteerde uitkeringen
**Van  Naar** Van pensioenuitvoeringsorganisatie naar fiduciair manager en beleggingsadministrateur/ asset service provider.
Op periodieke (verwachting is maandelijkse) basis ontvangt de fiduciair manager van een pensioenuitvoerder per regeling en per cohort de geprojecteerde uitkeringen op basis van de opgebouwde vermogens naar toekomstige periodes.
Tevens bevat de gegevensuitwisseling de af te dekken kasstromen per regeling per toekomstige periode. Dit is gelijk aan de som van de gewogen geprojecteerde uitkeringen per cohort. De wegingsfactor is gelijk aan het percentage bescherming per cohort. Op deze manier ontstaat een profiel van de af te dekken kasstromen. Deze uitwisseling vermijdt misverstanden ten aanzien van af te dekken kasstromen en kan desgewenst een toets in het proces introduceren.

 |
| **SPR** | 2(4.2.2.)
 | Rendementsinformatie | Informatiebehoefte pensioenuitvoeringsorganisatie
**Van  Naar** Informatiestroom van beleggingsadministrateur/asset service provider naar de pensioenuitvoeringsorganisatie.
De pensioenuitvoeringsorganisatie heeft voor het uitvoeren van de solidaire premieregeling periodiek (naar verwachting maandelijks) informatie nodig over het behaalde rendement.
Periodiek ontvangt de pensioenuitvoeringsorganisatie over de periode voor een pensioenuitvoerder per regeling en per portefeuille de waarde aan het begin van de periode, de waarde aan het einde van de periode en het rendement in portefeuille valuta en (eventueel) uitgedrukt als percentage. De pensioenuitvoeringsorganisatie draagt zorg voor de toedeling van rendementen naar deelnemers op basis van portefeuillerendementen. Optioneel kunnen ook per cohort in de regeling pensioenvermogen, beschermingsrendement en overrendement worden gedeeld met de pensioenuitvoeringsorganisatie. Of deze optionele elementen worden uitgewisseld hangt af van de overeengekomen rollen en verantwoordelijkheden tussen de samenwerkende partijen.
Daarbij is het uitgangspunt dat de pensioenuitvoeringsorganisatie de verantwoordelijkheid heeft om conform de door de pensioenuitvoerder vastgestelde toedelingsregels rendementen toe te delen naar de persoonlijke pensioenvermogens van deelnemers, de solidariteitsreserve, een eventueel compensatiedepot en mogelijk andere reserves.
 |
| **FPR** | 541 (5.4.1.) | Orderopdracht | Direct order (pensioenuitvoeringsorganisatie belegt zelf)
**Van  Naar** Informatiestroom van pensioenuitvoeringsorganisatie naar Brokers/Transfer Agents/Order Desks.
Dit is de minimale set aan gegevens die benodigd is om een order te kunnen sturen aan een order verwerkende partij. Tevens kan er een switch mee worden uitgevoerd.De pensioenuitvoeringsorganisatie stuurt orders in op het hoogste niveau van het beleggingsfonds. De aanbieder van het fonds voert zelf de ordering uit in de onderliggende beleggingen. Dat kan onder andere genoteerde en illiquide beleggingen betreffen.
 |
| **FPR** | 542(5.4.2.)
 | Ordersettlement | Direct order (pensioenuitvoeringsorganisatie belegt via een order platform)
**Van  Naar** Van brokers/transfer agents/order desks naar pensioenuitvoeringsorganisatie.
Vanuit de order verwerkende partij komen de settlementgegevens van de order terug naar de pensioenuitvoeringsorganisatie.
 |
| **FPR** | 551 (5.5.1) | Mutatiesaldi | Informatiebehoefte administrateur cohortenpools en beleggingspools
**Van  Naar** Van pensioenuitvoeringsorganisatie naar administrateur van cohortenpools en beleggingspools.
De eerste (naar verwachting maandelijkse) informatiestroom van de pensioenuitvoeringsorganisatie naar de administrateur van cohortenpools en beleggingspools betreft gesaldeerde mutaties, zijnde aankoop, verkoop en switches op totaalniveau per cohortenpool welke worden doorgegeven aan de administrateur cohortenpools en beleggingspools. Deze administrateur kan hiermee de in- of uitstroom voor beleggingspools berekenen en daarmee de fiduciair manager instrueren.
 |
| **FPR** | 52a(5.5.2) | Reconciliatie-informatie | Reconciliatie administrateur van cohortenpools en beleggingspools, fiduciair manager en beleggingsadministrateur.
**Van  Naar** Informatiestroom tussen administrateur van cohortenpools en beleggingspools, fiduciair manager en beleggingsadministrateur.
De administrateur cohortenpools en beleggingspools ontvangt maandelijks de posities uit de leidende administratie van de beleggingsadministrateur van de beleggingspools, mogelijk aangevuld uit de (schaduw) administratie van de fiduciair manager. Deze posities worden gereconcilieerd met de posities in de eigen administratie van de administrateur van cohortenpools en beleggingspools.
 |
| **FPR** | 52b(5.5.2) | PUO-reconciliatie-informatie | Additionele informatie als de pensioenuitvoeringsorganisatie (ook) de rol van administrateur van cohortenpools vervuld.
**Van  Naar** Administrateur beleggingspools naar de pensioenuitvoeringsorganisatie.
Indien de pensioenuitvoeringsorganisatie de rol van administrateur cohortenpools vervult dan is een additionele informatie-uitwisseling nodig van de administrateur beleggingspools naar de pensioenuitvoeringsorganisatie over de voorlopige unitwaarden van de beleggingspools. Deze is in de onderstaande tabel weergegeven. Door ook het aantal uitgegeven units per beleggingspool te delen wordt de pensioenuitvoeringsorganisatie in staat gesteld om de aansluiting bij het aantal gehouden units in de beleggingspools door alle cohortenpools te reconciliëren.
 |
| **FPR** | 553 (5.5.3) | Stuurinformatiebeleggingspools | Informatie aansturen beleggingspools
**Van  Naar** Van Administrateur van cohortenpools en beleggingspools naar fiduciair manager.
De administrateur van cohortenpools en beleggingspools berekent de participatiewaarden van actieve leeftijdsgroepen en combineert deze waarden met de opgegeven mutaties om de casheffecten op de beleggingspools te schatten. De administrateur cohortenpools en beleggingspools verstuurt de casheffecten op de beleggingspool (met onderbouwing) naar de fiduciair in het volgende format.
 |
| **FPR** | 554(5.5.4) | Rebalancinginformatie | Rebalancing cohortenpools
**Van  Naar** Informatiestroom tussen administrateur van cohortenpools en beleggingspools en fiduciair manager.
De administrateur van cohortenpools en beleggingspools herbalanceert de relevante leeftijdsgroepen om op basis van de unitwaarden van de beleggingspools van tijdstip T conform het normbeleid belegd te zijn voor alle cohorten.
De administrateur van cohortenpools en beleggingspools verstuurt alle maandultimo transacties in de cohortenpools en beleggingspools in het afgesproken format naar de fiduciair manager.
 |
| **FPR** | 55a(5.5.5) | Waarde-informatie cohortenpool | Doorgeven waardes per beleggingspool en per cohortenpool(Fiduciair ontvangt van de pensioenuitvoeringsorganisatie)
**Van  Naar** Fiduciair ontvangt van de pensioenuitvoeringsorganisatie (pensioenuitvoeringsorganisatie administreert cohortenpools)
De administrateur van cohortenpools en beleggingspools berekent de unitwaarde per unit in de beleggingspool en de participatiewaarde per participatie in de cohortenpool.
Indien de pensioenuitvoeringsorganisatie de rol van de administrateur cohortenpools vervult dan zal deze de unitwaarden van de beleggingspools ontvangen van de administrateur beleggingspools maar zelf zorgdragen voor de berekening van de participatiewaarden van de cohortenpools. De fiduciair manager zal deze dan ook ontvangen van de pensioenuitvoeringsorganisatie.
De administrateur van cohortenpools en beleggingspools geeft daarnaast de gesommeerde (unit)waarden van beleggingspools door aan partijen.
 |
| **FPR** | 55b(5.5.5) | Waarde-informatie Beleggingspool | Doorgeven waardes per beleggingspool en per cohortenpool
**Van  Naar** Informatiestroom tussen beleggingsadministrateur, administrateur van cohortenpools en beleggingspools, fiduciair manager en pensioenuitvoeringsorganisatie.De administrateur van cohortenpools en beleggingspools berekent de unitwaarde per unit in de beleggingspool en de participatiewaarde per participatie in de cohortenpool.De administrateur van cohortenpools en beleggingspools geeft de (participatie)waarden van de cohortenpools door aan de pensioenuitvoeringsorganisatie en aan de fiduciair.
 |
| **FPR** | 556(5.5.6) | Betaalinformatie | Betaalinstructies onttrekkingen
**Van  Naar** Informatiestroom tussen administrateur van cohortenpools en beleggingspools en fiduciair manager, begin van de maand.
De administrateur van cohortenpools en beleggingspools verstuurt de betaalinstructie voor onttrekkingen naar de fiduciair manager.
 |

### 6.4.1Basisbericht

De basisstructuur voor berichten (transactie) toont de hiërarchische verbanden tussen verschillende entiteiten in het gegevensmodel. De entiteiten en entiteitstypen vormen een samenhangende hiërarchie. Per definitie is het nodig om in uit te wisselen berichten een hiërarchie aan te brengen en de structuur van de transactie vormt hiervoor de basis. De structuur geeft onder meer aan welke onderliggende entiteit bij welke bovenliggende entiteit hoort.

In de kolom "Kardinaliteit" wordt weergegeven hoe vaak die entiteit dan minimaal en maximaal kan voorkomen.Met R (verplicht) of O (optioneel) wordt onder Kardinaliteit aangegeven of een entity.entitytype moet of mag voorkomen. Binnen het basisbericht zijn alle entiteiten optioneel gelaten.

Uit onderstaande tabel valt bijvoorbeeld af te leiden dat:

1. Per party.sender meerdere party.contact mogelijk


2. Per party.pensionProvider
  1. maximaal 1 financialInformation.reportingPeriod voorkomt en mogelijk
  2. meerdere pension.scheme's

| **Entity.entitytype** | **Kardinaliteit** |
| --- | --- |
| commonTechnical.default | 1..1, O |
| party.sender | 1..1, O |
| party.contact | 0..\*, O |
| party.receiver | 1..1, O |
| commonFunctional.default | 1..1, O |
| party.pensionProvider | 1..1, O |
| _ **pension.scheme** _ | 1..\*, O |
| _ **financialInformation.reportingPeriod** _ | 1..1, O |
| _ **financialTransaction.payment** _ | 1..\*, O |
| _ **party.creditor** _ | 1..\*, O |
| _ **financialTransaction.cashflow** _ | 1..1, O |
| _ **pension.cohort** _ | 1..\*, O |
| _ **pension.cohortPool** _ | 1..1, O |
| _ **investment.pool** _ | 1..\*, O |
| _ **investment.pool** _ | 1..\*, O |
| _ **investment.investmentDetails** _ | 1..\*, O |
| _ **investment.portfolio** _ | 1..1, O |
| _ **investment.investmentDetails** _ | 1..1, O |
| _ **financialTransaction.trade** _ | 1..\*, O |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

NB.in de technische implementatie is het aantal herhalingen (\*) begrenst. Zie het overzicht hieronder:

| **Entity.entitytype** | **Maximumaantal
 iteraties** |
| --- | --- |
| party.contact | 9 |
| party.receiver | 9 |
| pension.scheme | 999 |
| pension.cohort | 99 |
| pension.cohortPool | 99 |
| investment.pool | 99 |
| investment.portfolio | 99 |
| investment.investmentDetails | 999 |
| financialTransaction.trade | 99 |
| error.default | 99 |
| document.default | 99 |

### 6.4.2Berichtstructuur 1. Vermogen (0001a)

Zie ook 3.2.1.

| **Berichtstructuur 1. Vermogen (0001a)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohort** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.3Berichtstructuur 2. Cashflow (0001b)

Zie ook 3.2.2

| **Berichtstructuur 2. Cashflow (0001b)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **financialTransaction.cashflow** _ | 1..\*, R |
| _ **pension.cohort** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.4Berichtstructuur 3. Pensioenprojectie (0001c)

Zie ook 3.2.3.

| **Berichtstructuur 3. Pensioenprojectie (0001c)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohort** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.5Berichtstructuur 4. Rendementsinformatie (00002)

Zie ook 3.2.4.

| **Berichtstructuur 4. Rendementsinformatie (00002)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohort** _ | 1..\*, O |
| _ **investment.portfolio** _ | 1..1, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

.

### 6.4.6Berichtstructuur 5. Orderopdracht (00541)

Zie ook 4.2 & 4.4.1

| **Berichtstructuur 5. Orderopdracht (00541)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **investment.investmentDetails** _ | 1..\*, R |
| _ **financialTransaction.trade** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.7Berichtstructuur 6. Ordersettlement (00542)

Zie ook 4.2 & 4.4.2.

| **Berichtstructuur 6. Ordersettlement (00542)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **investment.investmentDetails** _ | 1..\*, R |
| _ **financialTransaction.trade** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.8Berichtstructuur 7. Mutatiesaldi (00551)

Zie ook 4.3 & 4.5.1.

| **Berichtstructuur 7. Mutatiesaldi (00551)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohortPool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.9Berichtstructuur 8. Reconciliatie-informatie (00552a)

Zie ook 4.3 & 4.5.2

| **Berichtstructuur 8. Reconciliatie-informatie (00552a)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **investment.pool** _ | 1..\*, R |
| _ **investment.investmentDetails** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.10Berichtstructuur 9. PUO-reconciliatie-informatie (00552b)

Zie ook 4.3 & 4.5.2

| **Berichtstructuur 9. PUO-reconciliatie-informatie (00552b)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **investment.pool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.11Berichtstructuur 10. Stuurinformatiebeleggingspools (00553)

Zie ook 4.3 & 4.5.3.

| **Berichtstructuur 10. Stuurinformatiebeleggingspools (00553)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohortPool** _ | 1..\*, R |
| _ **investment.pool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.12Berichtstructuur 11. Rebalancinginformatie (00554)

Zie ook 4.3 & 4.5.4.

| **Berichtstructuur 11. Rebalancinginformatie (00554)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohortPool** _ | 1..\*, R |
| _ **investment.pool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.13Berichtstructuur 12. Waarde-informatie cohortenpool (00555a)

Zie ook 4.3 & 4.5.5.

| **Berichtstructuur 12. Waarde-informatie cohortenpool (00555a)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **pension.cohortPool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.14Berichtstructuur 13. Waarde-informatie beleggingspool (00555b)

Zie ook 4.3 & 4.5.5.

| **Berichtstructuur 13. Waarde-informatie beleggingspool (00555b)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **investment.pool** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

### 6.4.15Berichtstructuur 14. Betaalinformatie (00556)

Zie ook 4.3 & 4.5.1.

| **Berichtstructuur 14. Betaalinformatie (00556)** |
| --- |
| **Entity** | **Kardinaliteit** |
| commonTechnical.default | 1..1, R |
| party.sender | 1..1, R |
| party.contact | 0..\*, O |
| party.receiver | 1..1, R |
| commonFunctional.default | 1..1, R |
| party.pensionProvider | 1..1, R |
| _ **pension.scheme** _ | 1..\*, R |
| _ **financialInformation.reportingPeriod** _ | 1..1, R |
| _ **financialTransaction.payment** _ | 1..\*, R |
| _ **party.creditor** _ | 1..\*, R |
| error.default | 0..\*, O |
| document.default | 0..\*, O |

## 6.5Kruisreferentie Attributen & berichten

Dit overzicht toont welke attributen binnen een bepaald bericht verplicht (R) of optioneel (O) of niet van toepassing ( ) zijn.

| Berichten =\>


 Entities.entitytypes & Attributes | **Bericht 1. Vermogen (0001a)** | **Bericht 2. Cashflow (0001b)** | **Bericht 3. Pensioenprojectie (0001c)** | **Bericht 4. Rendementsinformatie (00002)** | **Bericht 5. Orderopdracht (00541)** | **Bericht 6. Ordersettlement (00542)** | **Bericht 7. Mutatiesaldi (00551)** | **Bericht 8. Reconciliatie-informatie (0552a)** | **Bericht 9. PUO-reconciliatie-informatie (0552b)** | **Bericht 10. Stuurinformatiebeleggingspools (00553)** | **Bericht 11. Rebalancinginformatie (00554)** | **Bericht 12. Waarde-informatie cohortenpool (0555a)** | **Bericht 13. Waarde-informatie beleggingspool (0555b)** | **Bericht 14. Betaalinformatie (00556)** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| commonTechnical.default |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| messageId | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| messageVersion | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| creationDateTime | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| testMessage | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| party.sender |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| rsinNumber | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| organizationName | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| applicationSenderName | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| party.contact |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| surname | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| firstName | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| prefixes | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| initials | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| titlesPrefix | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| gender | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| fullName | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| party.receiver |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| rsinNumber | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| organizationName | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| commonFunctional.default |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| function | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| resending | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| afdDefinitionName | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| originalMessageId | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| party.pensionProvider |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| rsinNumber | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| organizationName | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| pension.scheme |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| pensionschemeName | O | O | O | O | O | O | O | O | O | O | O | O | O | O |
| StartAmount | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| expectedPensionPaymentDate |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| totalExpectedPensionPaymentAmount |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| hedgedExpectedPensionPaymentAmount |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| tradingPortfolioId |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| financialInformation.reportingPeriod |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| startDate | R | R |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| endDate |
 | R |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| mutationValuationDate |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
| tradeDate |
 |
 |
 |
 |
 |
 | R |
 |
 | R | R |
 |
 |
 |
| investmentOrderSettlementDate |
 |
 |
 |
 |
 | R |
 |
 |
 | R | R |
 |
 |
 |
| projectionDate |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| instructionDate |
 |
 |
 |
 | R | O |
 |
 |
 |
 |
 |
 |
 |
 |
| unitValueEstimationDate |
 |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
| participationValuationDate |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
| valueDate |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| positionDate |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| financialTransaction.payment |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| amount |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| currencyType |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| collectionAccountIban |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| description |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| party.creditor |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| collectionAccountIban |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| collectionAccountInNameOf |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| collectionAccountBic |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
| collectionAccountBicCorrespondent |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | O |
| financialTransaction.cashflow |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| contributionAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| contributionDate |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| withdrawalAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| withdrawalDate |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| netAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| netDate |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| pension.cohort |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | R | R | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| description | O | O | O | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| startAmount | R |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| netAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| contributionAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| withdrawalAmount |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| expectedPensionPaymentAmount |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| protectionReturnPercentage |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| excessReturnPercentage |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| protectionReturnAmount |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| excessReturnAmount |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| pension.cohortPool |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 |
 |
 | R |
 |
 | R | R | R |
 |
 |
| cohortRef |
 |
 |
 |
 |
 |
 | O |
 |
 | O | O | O |
 |
 |
| description |
 |
 |
 |
 |
 |
 | O |
 |
 | O | O | O |
 |
 |
| currencyType |
 |
 |
 |
 |
 |
 | R |
 |
 | R | R | R |
 |
 |
| inflowPremiumAmount |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
| inflowRebalanceAmount |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
| numberOfNewParticipations |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
| numberOfParticipations |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | O |
 |
 |
| numberOFRebalanceParticipations |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
| participationsSummedValueAmount |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 | R |
 |
 |
| investment.pool |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 | R |
 |
| description |
 |
 |
 |
 |
 |
 |
 | O | O |
 |
 |
 | O |
 |
| marketValueAmount |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| unitsSummedValueAmount |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
 |
| preliminaryMarketValueAmount |
 |
 |
 |
 |
 |
 |
 |
 | O |
 |
 |
 |
 |
 |
| preliminaryUnitValueAmount |
 |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
| numberOfUnits |
 |
 |
 |
 |
 |
 |
 |
 | O |
 |
 |
 |
 |
 |
| currencyType |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 | R |
 |
| investment.pool |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| description |
 |
 |
 |
 |
 |
 |
 |
 |
 | O | O |
 |
 |
 |
| dummyCashId |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| buySellId |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| tradeQuantity |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| unitPrice |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| currencyExchangeRate |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| tradeValueAmount |
 |
 |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
| currencyType |
 |
 |
 |
 |
 |
 |
 |
 |
 | R | R |
 |
 |
 |
| investment.portfolio |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| description |
 |
 |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| startAmount |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| netAmount |
 |
 |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| endAmount |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| returnPercentage |
 |
 |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| returnAmount |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| investment.investmentDetails |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| description |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| currencyType |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| investment.investmentDetails |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| description |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| currencyType |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| numberOfHoldings |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| localPrice |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| localValueAmount |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| result |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| accruedInterest |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| poolPercentage |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| currencyExchangeRate |
 |
 |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
| financialTransaction.trade |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| tradeDate |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| adjustmentIndicator |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| buySellId |
 |
 |
 |
 | R | R |
 |
 |
 |
 |
 |
 |
 |
 |
| tradeAmount |
 |
 |
 |
 | O | R |
 |
 |
 |
 |
 |
 |
 |
 |
| tradeQuantity |
 |
 |
 |
 | O | R |
 |
 |
 |
 |
 |
 |
 |
 |
| tradePrice |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| switchType |
 |
 |
 |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| financialInformationRef |
 |
 |
 |
 | O |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| counterparty |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| broker |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| interest |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| commissionAmount |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| clearingBroker |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| clearingbrokerCashAccount |
 |
 |
 |
 |
 | R |
 |
 |
 |
 |
 |
 |
 |
 |
| error.default |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| errorCode | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| errorCodeExplanation | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| document.default |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
 |
| refKey | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| fileName | R | R | R | R | R | R | R | R | R | R | R | R | R | R |
| fileExtension | R | R | R | R | R | R | R | R | R | R | R | R | R | R |

# 7Technische specificaties

**De technische gegevensspecificaties komen beschikbaar op basis van AFD 2.0 uit SIVI AFS. In dit hoofdstuk kan de lezer kennisnemen van een toelichting.**

## 7.1Berichten & regelingen

Ieder bericht kan over meerdere regelingen (pension.scheme) gaan. Wel gaat het steeds om 1 party.pensioenprovider. De verzending is per bericht en dat bericht bevat dus 1 pension.provider en 1 of meer pension.scheme's

## 7.2Validaties

De volgende validatieregels kunnen met de technische specificaties uitgevoerd worden:

- Controle of de berichtstructuur correct is;

- Klopt het gegevenstype (onder meer getallen, strings);
- Controle op minimale en maximale waarden;
- Validatie van de veldlengte;
- Controle of verplichte entiteiten en verplichte attributen aanwezig zijn;
- Controle op het aantal herhalingen van entiteiten;
- Is sprake van toepassing van toegestane codes uit codelijsten.

PM verbandscontroles (validatie regels op de tussen verschillende gegevens) zijn nog in ontwikkeling. Zie ook de JSON-schema's en bijlage 10.5.

## 7.3JSON

1.
2. Het SIVI AFS team volgt voor AFD 2.0 in combinatie met JSON onderstaande specificaties (ontleend aan [Forum Standaardisatie](https://www.forumstandaardisatie.nl/open-standaarden/json)):
3.

| **Betreft** | **Omschrijving** |
| --- | --- |
| **Volledige naam** | JavaScript Object Notation |
| --- | --- |
| **Versie** | RFC8259, december 2017 |
| **Specificatiedocument** | [Specificatiedocument JSON](https://tools.ietf.org/html/rfc8259) |
| **Beheerorganisatie** | Internet Engineering Task Force [https://datatracker.ietf.org/doc/html/rfc7159](https://datatracker.ietf.org/doc/html/rfc7159) |
| **Functioneel toepassingsgebied** | Objectnotatie voor het uitwisselen van datastructuren. Bijvoorbeeld in webapplicaties die asynchroon gegevens ophalen van de webserver. |
| **Typering** | Uitwisselen van datastructuren |
| **Nut** | JSON (JavaScript Object Notation) is een deelverzameling van de programmeertaal JavaScript.  De eenvoud van JSON heeft geleid tot een grote populariteit ervan, met name als een 'light' alternatief voor XML. |
| **Werking** | JavaScript Object Notation (JSON) een formaat om net zoals XML gegevens op te slaan en te versturen. JavaScript is de programmeertaal waarvan de basis syntax beschrijving is afgeleid voor gebruik in JSON. JSON wordt gebruikt voor het uitwisselen van datastructuren, met name in webapplicaties die asynchroon gegevens ophalen van de webserver. De standaard is met name gericht op efficiënt programmeren en kent een compacte notatie bijvoorbeeld: { "naam": Jan, "geboren": 1983 } |
| **Hulpmiddelen** | Verschillende online JSON validators en hulpmiddelen zijn te vinden, ook voor de verschillende programmeerplatformen. Meer informatie over de standaard is ook te vinden via [publicaties van ECMA International](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-404.pdf) |

# 8Governance en beheer

**Governance gaat over het optimaal inrichten van de organisatie van de community rond de standaard. Duidelijk moet zijn wie beslist wat uitgevoerd wordt met betrekking tot standaarden, en wie beslist hoe dit wordt uitgevoerd.**

**Dit hoofdstuk gaat voorts in op de beheersmatige processen rondom de standaarden. Het omvat alle activiteiten gericht op het aanpassen, uitbreiden, doorontwikkelen, beschikbaar stellen en houden van een (set van) berichten die steeds past bij de actuele behoefte van de belanghebbenden.**

## 8.1Inleiding

Onderstaande Figuur 13 geeft een overzicht van de onderkende beheersmatige processen rondom de standaarden. Hierover maken we afspraken.

![](RackMultipart20231222-1-avhyj4_html_3a128dc78d51eafd.gif) **Figuur 13 – Beheersmatige processen rond standaarden**

## 8.2Visie beheerorganisatie

De beheerorganisatie streeft naar een stabiele standaard die goed en eenduidig bruikbaar is voor alle relevante partijen.

## 8.3Taken beheerorganisatie

De beheerorganisatie heeft als taak het up to date houden en verbeteren van de standaard en alle bijbehorende documentatie, inclusief de bijbehorende communicatie naar relevante partijen.

Hieronder volgt een niet limitatief overzicht van verantwoordelijkheden:

- Faciliteren van vergaderingen, afspraken en dergelijke.
- Standaard over het voetlicht brengen.
- In ontvangst nemen, analyseren en verder opvolgen van wijzigingsverzoeken ten behoeve van alle documentatie.
- Wijzigingen afstemmen met de Klankbordgroep.
- Nieuwe versies van de documentatie maken.
- Communiceren en publiek beschikbaar stellen van goedgekeurde documentatie.

De beheerorganisatie behandelt wijzigingsvoorstellen op basis van de impact:

- Aanpassingen met lichte impact worden beoordeeld door de beheerorganisatie. Het gaat hierbij bijvoorbeeld om herstel van bepaalde onjuistheden.
- Aanpassingen met middelgrote impact worden beoordeeld door de Klankbordgroep. Het gaat hierbij bijvoorbeeld om nieuwe spelregel voor het aanmaken/vullen van de berichten, toevoegen van attributen aan de standaard of het toevoegen van codewaarde aan codelijst. Na voorbereiding , eventueel in een werkgroep, neemt de Klankbordgroep een beslissing over het wijzigingsverzoek.
- Aanpassingen met zware impact worden beoordeeld op stuurgroepniveau. Het gaat hierbij bijvoorbeeld om wijzigingen in de structuur van de standaard.

## 8.4Inrichting beheerorganisatie

Het beheer wordt uitgevoerd door Stichting SIVI. De beheerorganisatie bereidt besluitvorming voor en biedt deze aan en rapporteert aan de Pensioenfederatie via de Stuurgroep Digitale Standaardisatie en Ontwikkeling (DSO). Tevens rapporteren we aan de Stuurgroep van het Gezamenlijk Domein (GZD).

In de stuurgroep DSO zijn de Pensioenfederatie en 7 pensioenuitvoeringsorganisaties vertegenwoordigd. In de stuurgroep GZD nemen deel: de Pensioenfederatie, 2 pensioenuitvoeringsorganisaties, 1 verzekeraar, het Verbond van Verzekeraars en de voorzitter van het SIVI bestuur.

## 8.5Klankbordgroep

Voor de uitvoering van de verantwoordelijkheden en de besluitvorming rond de wijzigingsverzoeken. werkt de beheerorganisatie samen met de Klankbordgroep. Deze Klankbordgroep bestaat uit vertegenwoordigers van vermogensbeheerders, pensioenuitvoeringsorganisaties en SWO's.

Leden van de Klankbordgroep worden benoemd conform het desbetreffende Huishoudelijk Reglement Klankbordgroep.

## 8.6Contactgegevens SIVI

| **Betreft** | **Inhoud** |
| --- | --- |
| **Straatadres** | Pythagoraslaan 101 |
| **Postcode** | 3584 BA |
| **Plaats** | Utrecht |
| **Telefoon** | 030 698 80 90 |
| **E-Mail** | [vb-puo@sivi.org](mailto:Inbox%20VB-PUO%20-%20VB-PUO%20%3Cb2f38b85.sivi.org@emea.teams.ms%3E?subject=VBPUO-Reactie%20/%20Vraag) |
| **Website** | www.sivi.org |

# 9Wijzigingsprocedure

**Wijzigingen op de standaard raakt meerdere belanghebbenden. In de procedure van wijziging zijn hierom de belangen van alle deelnemende partijen vertegenwoordigd. Verzoeken en voorstellen voor wijzigingen zullen volgens onderstaande procedure worden behandeld.**

**Een wijziging wordt afgehandeld via een viertal stappen:**

1. **Intake;**
2. **Besluitvorming;**
3. **Verwerken;**
4. **Communicatie.**

## 9.1Intake

De volgende partijen kunnen wijzigingen initiëren:

- Vermogensbeheerders;
- Pensioenuitvoeringsorganisaties;
- Pensioenuitvoerders;
- Leveranciers die de standaard implementeren.

Verzoeken tot wijziging kunnen, voorzien van motivatie, via een nader te bepalen e-mailadres aangeleverd worden bij de beheerorganisatie van de standaard.

Ontvangen wijzigingsverzoeken worden in eerste instantie beoordeeld door de beheerorganisatie van de standaard. Voor het bepalen van de impact vindt een onderzoek plaats naar de consequenties van de wijziging voor hiervoor genoemde partijen. Het resultaat van deze beoordeling wordt teruggekoppeld met de aanvrager.

Mede op basis van de impact wordt door de beheerorganisatie een advies opgesteld over de verzochte wijziging. Het wijzigingsverzoek wordt voorzien van advies voorgelegd aan de Klankbordgroep.

Het bespreken van de voorgestelde wijzigingen kent geen vaste volgorde.

## 9.2Besluitvorming

De Klankbordgroep komt eenmaal per kwartaal bij elkaar. Dit gebeurt op uitnodiging van de beheerorganisatie. Aan het begin van een jaar wordt een kalender opgesteld voor deze bijeenkomsten.

Aangeleverde wijzigingsverzoeken worden in de eerstvolgende bijeenkomst van de Klankbordgroep geagendeerd. Naast het bespreken van de inhoudelijke wijziging worden tevens afspraken over de implementatie gemaakt.

## 9.3Verwerken

Na formeel akkoord van de Klankbordgroep wordt de wijziging in een nieuwe versie van de handleiding en de bijbehorende standaard opgenomen. Wijzigingen ten opzichte van de voorgaande versie van de documentatie worden duidelijk herkenbaar beschreven. Ook wordt expliciet aangegeven op welk moment deze wijziging ingaat.

Vooralsnog wordt ervan uit gegaan dat er per jaar maximaal één nieuwe versie van de standaard gepubliceerd wordt.

## 9.4Communicatie

Nadat de wijziging goedgekeurd en verwerkt is, vindt communicatie plaats richting de:

- Vermogensbeheerders;
- Pensioenuitvoeringsorganisaties;
- Pensioenuitvoerders;
- Leveranciers die de standaard implementeren.

Deze communicatie bestaat uit:

- E-mail aan de genoemde partijen over de gewijzigde versie van de standaard;
- Publiceren van de gewijzigde handleiding via de website van SIVI.

# 10Bijlagen

**In de bijlagen treft u de:**

- **Begrippenlijst/Afkortingenlijst Vermogensbeheer & Pensioenuitvoering;**
- **Begrippenlijst gegevensuitwisseling op basis van standaarden;**
- **Huishoudelijk reglement Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering;**
- **Onderdelen Standaard Vermogensbeheer Pensioenuitvoering.**

## 10.1Begrippenlijst/Afkortingenlijst Vermogensbeheer & Pensioenuitvoering

| **Begrip** | **Afkorting** | **Omschrijving** |
| --- | --- | --- |
| **Afdekkingspercentage, beschermingspercentage** |
 | De mate waarin de rentegevoeligheid van op basis van persoonlijke vermogens geprognosticeerde uitkeringen wordt afgedekt.
 |
| --- | --- | --- |
| **Algemeen Pensioenfonds** | APF | Algemeen Pensioenfonds (APF): Een APF is een pensioenuitvoerder die verschillende pensioenregelingen van verschillende werkgevers en bedrijfstakken kan bundelen in één administratie.
 |
| **Asset service provider** |
 | Zie: Beleggingsadministrateur.
 |
| **Bank Identifier Code** | BIC | Bank Identifier Code. bijvoorbeeld van ABN: ABNANL2A
 |
| **BIC Correspondent** |
 | Een BIC correspondent is de BIC-code van een correspondentbank;een bank die diensten verleent aan andere banken.
 |
| **Beleggingsadministrateur** |
 | Een onafhankelijke partij die de beleggingsadministratie voert voor de pensioenuitvoerder. Dit is een dienst die veelal door de custodian wordt verzorgd.
 |
| **Beleggingen methode** |
 | Berekening van het beschermingsrendement vindt, buiten het domein van de pensioenuitvoeringsorganisatie plaats op basis van de werkelijke renterisico afdekking.
 |
| **Beleggingsinstructie** |
 | Beleggingsorder.
 |
| **Beleggingsorder** |
 | Een opdracht tot het aankopen van bepaalde beleggingen.
 |
| **Beleggingspool** |
 | Een beleggingspool is een verzameling van beleggingen in verschillende fondsen of mandaten die een gemeenschappelijk kenmerk delen. Een voorbeeld hiervan is de 'zakelijke waarden beleggingspool', waarin wordt belegd in meerdere zakelijke waarden fondsen en/of mandaten. Beleggingspools zijn bedoeld om de beleggingen van een groep investeerders te bundelen en te beheren. Ze bieden investeerders de mogelijkheid om te diversifiëren en risico's te spreiden door te investeren in verschillende activa.
 |
| **Beschermingsportefeuille** | | Specifiek deel van de beleggingsportefeuille aangehouden met als doel om (voornamelijk) het beschermingsrendement te genereren. Bij de SPR kan dit een operationeel onderdeel zijn van de totale portefeuille waarmee de renteafdekking wordt vormgegeven. Bij het gebruik van feitelijk beschermingsrendement zal het een of meerdere afgescheiden portefeuilles zijn.
 |
| **Beschermingsrendement** |
 | De vermogensbijschrijving die ervoor zorgt dat de, uit het opgebouwde pensioenvermogen te financieren, toekomstige pensioenuitkeringen en lopende pensioenuitkeringen nominaal stabiel blijven voor de mate waarin deze worden beschermd, dat wordt gefinancierd vanuit het totaal behaalde rendement en looptijdafhankelijk wordt toebedeeld aan de vermogens op basis van marktwaardering, waarbij toedelingsregels worden gehanteerd. Toedelingsregels SPR worden vastgesteld: ofwel op basis van wijziging van de rentetermijnstructuur, die de toezichthouder beschikbaar stelt (RTS) ofwel rechtstreeks uit het rendement van de daarvoor bestemde beleggingen. (Beleggingen methode)
 Zie ook: Beleggingen methode en Rentetermijnstructuur methode.
 |
| **Book of records** |
 | Een aanduiding voor boekhoudkundige administraties binnen vermogensbeheer. Binnen de kaders van dit rapport gaat het om: ABOR = Accounting Book of Records (hoofdadministratie, volgens accounting regels), IBOR = Investment Book of Records (vaak schaduwadministratie).
 |
| **Cohorten** | | De term verwijst naar doelgroepen. Deze kunnen op allerlei wijze worden samengesteld. Leeftijdsdoelgroepen maar ook op bijvoorbeeld deelnemer, slaper, gepensioneerd, arbeidsongeschikt en/of soort dienstverband kan gedifferentieerd worden Een cohort kan de basis zijn waarop een pensioenuitvoerder deelnemers aan een passende herbalanceringssystematiek koppelt.
 |
| **Cohortenpool/ Cohortpool** |
 | Een cohortenpool bevat de verzameling van alle beleggingen (beleggingspools) voor 1 cohort. Oftewel de gepoolde (verzamelde) combinatie van beleggingen (beleggingspools) voor een cohort.
 |
| **Custodians** | | Bewaarder van het beheerde vermogen van een pensioenuitvoerder. Bepaalt onafhankelijk de waardering en het rendement van de holdings en beleggingsportefeuilles/pools.
 |
| **Direct (feitelijk)beschermingsrendement** |
 | Rendement dat gegenereerd wordt met een of meerdere directe beschermingsportefeuilles voor renterisico. Hierbij zijn er twee opties: Met één beschermingsportefeuille: de beschrijving per deelnemer vindt plaats op basis van het theoretisch beschermingsrendement waarbij het resultaat 'geschaald' wordt naar het resultaat van de beschermingsportefeuille.
 Voorbeeld: indien het totale theoretische beschermingsrendement 1000 zou zijn maar het feitelijk beschermingsrendement maar 900, dan krijgt iedere deelnemer 90% van het theoretisch beschermingsrendement bijgeschreven.
 Met meerdere beschermingsportefeuilles: per leeftijdscohort geldt een allocatie naar de beschermingsportefeuilles (eventueel inclusief inflatie-instrumenten).
 |
| **Fiduciair manager** | | Een fiduciair manager draagt zorg voor de integrale aansturing van het vermogensbeheer waarbij het (strategisch) beleggingsbeleid van het fonds in brede zin wordt geïmplementeerd. Daarbij kunnen vervolgens uiteenlopende, onderliggende vermogensbeheerders worden aangestuurd. De fiduciair manager zal ook een (schaduw) beleggingsadministratie voeren.
 |
| **Flexibele premieregeling** | FPR | Premieovereenkomst waarbij de premie individueel wordt belegd en waarbij het kapitaal voortvloeiend uit de premie vanaf de pensioendatum wordt aangewend voor financiering van een variabele uitkering of voor de aankoop van een vastgestelde uitkering.
 |
| **Foreign Exchange Rate** | FX-rate | Wisselkoers Een investment currency waarde van 1,1 USD bij een investment-pool currency waarde van 1 leidt tot een waarde in euro van 1/1,1 = € 0,9090
 |
| **Geprojecteerde pensioenuitkeringen** |
 | De verwachte variabele uitkeringen in een solidaire premieovereenkomst van een pensioenuitvoerder op basis van het opgebouwde voor pensioen bestemde vermogen. De hoogte van de verwachte variabele uitkering wordt bepaald door het inrekenen van een projectierendement op het voor pensioen bestemde vermogen Dit kan hoger of lager zijn dan de risicovrije rente. De precieze invulling van geprojecteerde uitkeringen is een partijen/governance afspraak.
 |
| **Identifier** |
 | Een sleutel gegeven dat een beleggingsinstrument uniek identificeert bijvoorbeeld [ISIN](https://en.wikipedia.org/wiki/International_Securities_Identification_Number) of [SEDOL](https://en.wikipedia.org/wiki/SEDOL).
 |
| **Instruction Date** |
 | Datum van de verzending van de beleggingsorder/beleggingsinstructie door de pensioenuitvoeringsorganisatie. |
| [**International Securities Identification Number**](https://en.wikipedia.org/wiki/International_Securities_Identification_Number) | ISIN | Een codenummer voor een "effect" bestaande uit een landencode en een uniek National Security Number (NSIN). ISIN is het acroniem van International Securities Identification Number. ISIN codes worden alleen gebruikt voor beursgenoteerde genoteerde beleggingsfondsen. In de pensioenvermogensbeheerpraktijk wordt veelal gewerkt met administratieve pools die GEEN ISIN hebben. Voor zulke pools is wel een unieke identifier nodig.
 |
| **DNB-jaarstaat kosten vermogensbeheer** | J402 | Kosten vermogensbeheer uitgesplitst naar verschillende (beleggings)categorieën. De jaarstaat omvat alle vermogensbeheerkosten zowel de gefactureerde kosten als kosten die worden ingehouden op de behaalde bruto rendementen. Per beleggingscategorie worden beheervergoedingen, prestatieafhankelijke vergoedingen en transactiekosten gerapporteerd.
 |
| **Leidende beleggingsadministratie** |
 | Beleggingsadministratie die voor de pensioenuitvoeringsorganisatie en de pensioenuitvoerder de basis is voor (mutaties in) het persoonlijk voor pensioenuitkering bestemd vermogen (SPR), voor pensioen bestemd kapitaal (FPR) en voor de rapportage aan de toezichthouder.
 |
| **Lifecycle** |
 | Het doel van beleggen volgens een lifecycle is om de grote schommelingen in de kapitaalopbouw te verminderen bij het naderen van de beleggingshorizon. Om dit te bereiken, delen pensioenuitvoerders deelnemers op in deelpopulaties op basis van de resterende tijd tot de pensioendatum. Naarmate de pensioendatum en beleggingshorizon dichterbij komen, wordt het beleggings- en renterisico voor deze deelpopulaties afgebouwd. Zo wordt ervoor gezorgd dat het beleggingsbeleid past bij de levensfase waarin de deelnemer zich bevindt.
 |
| **Local valuta / Local price** |
 | Prijs van het beleggingsinstrument in diens originele valuta.
 |
| **Lookthrough** |
 | Met dit begrip wordt gedoeld op het "doorzicht" naar daadwerkelijke beleggingen. Afhankelijk van het type product en de beleggingssamenstelling is dit "doorzicht" eenvoudig dan wel moeilijk of tegen forse kosten te realiseren. Bij SPR producten is de beleggingsmix op individueel niveau niet te bepalen. Bij FPR-producten kunnen de beleggingen in sommige gevallen direct aan een beursgenoteerd fonds worden gelinkt.
 |
| **Net asset value** | NAV | Zie: Total Market Value.
 |
| **Netten** |
 | Het samenvoegen (salderen/consolideren) of optellen van beleggingsorders in hetzelfde beleggingsproduct.
 |
| **Order date** |
 | Instruction Date
 |
| **Overrendement** |
 | Het saldo van het totaal behaalde rendement op de beleggingen, de ontwikkeling van de levensverwachting en het sterfteresultaat en het toebedeelde beschermingsrendement op basis van de toedelingsregels.
 |
| **Pensioenfonds** |
 | Instellingen die pensioenregelingen beheren en uitvoeren ten behoeve van werknemers die bij een specifiek bedrijf of bedrijfstak werken.
 |
| **Pensioenuitvoerder** |
 | In Nederland worden verschillende partijen gedefinieerd als "pensioenuitvoerder" volgens de Pensioenwet. In 2023 gaat/ging het om: Pensioenfondsen, Pensioenverzekeraars, Premiepensioeninstellingen (PPI's) en Algemeen Pensioenfonds (APF).
 |
| **Pensioenregeling** |
 | Een pensioenregeling volgens de Pensioenwet is een overeenkomst (of toezegging) tussen een werkgever en een werknemer waarin is vastgelegd welke pensioenuitkeringen worden toegezegd en onder welke voorwaarden.
 |
| **Pensioenreglement** |
 | De door de pensioenuitvoerder opgestelde regeling waarin de rechten en plichten van de deelnemer en de pensioenuitvoerder zijn beschreven.
 |
| Pensioen **uitvoeringsorganisatie** | PUO/PA | Administrateur van pensioenregelingen.

 |
| **Pensioenverzekeraar** |
 | Verzekeringsmaatschappijen die individuele en collectieve pensioenverzekeringen aanbieden en de pensioenregelingen beheren en uitvoeren. |
| **Portfolio** |
 | Een beleggingsportefeuille, oftewel een geheel van aandelen en andere effecten. |
| **Premiepensioeninstelling** | PPI | Financiële instellingen die individuele premieovereenkomsten aanbieden, waarbij de hoogte van het pensioen afhangt van de premie-inleg en het rendement daarop. |
| **Premie-uitkeringsovereenkomst** | | Premieovereenkomst uitgevoerd door een verzekeraar waarbij de premie individueel wordt belegd, waarbij de premie of het kapitaal voortvloeiend uit de premie in de laatste 15 jaar voor de pensioengerechtigde leeftijd kan worden aangewend voor aankoop van een vastgestelde uitkering vanaf de pensioendatum en waarbij het resterend kapitaal vanaf de pensioendatum wordt aangewend voor financiering van een variabele uitkering of voor de aankoop van een vastgestelde uitkering.
 |
| **Projectierendement** | | Het ingerekende toekomstig rendement voor de vaststelling van variabele uitkeringen.
 |
| **Rebalancen** | | Het periodiek of op verzoek in evenwicht brengen van een beleggingsportefeuille met de doelgewichten binnen deze portefeuille, na in- of uitstroom in de betreffende portefeuille (externe aanleiding) of doordat binnen de portefeuille sprake is ongewenste afwijkingen van normbeleid door marktbewegingen.
 |
| **Reconciliatie** | | Het proces waarbij vergeleken wordt of de (totalen) van registraties van stukken tussen de verschillende partijen (bijvoorbeeld vermogensbeheerder en custodian) in overeenstemming zijn en zo nee het oplossen van verschillen.
 |
| **Rentetermijnstructuur methode** | RTS | Bij de RTS-methode vindt de berekening van het SPR beschermingsrendement plaats op basis van de wijziging van de RTS in de schaduw-VPV. De schaduw VPV is de VPV van de schaduw-aanspraken op basis van het aanwezige kapitaal.
 |
| **Solidariteitsreserve** |
 | Een collectieve vermogensreserve waarmee in een solidaire premieovereenkomst financiële mee- of tegenvallers met toekomstige opbouw kunnen worden gedeeld.
 |
| **Risicodelingsreserve** | | Een collectieve vermogensreserve waarmee in een flexibele premieovereenkomst financiële mee- of tegenvallers met toekomstige opbouw kunnen worden gedeeld.
 |
| **Settlement date** |
 | Datum waarop de volledige cyclus van de beleggingsorder vanaf de trade date - afgewikkeld is. Elk (beleggings)product heeft z'n eigen settlement duur variërend van T+1 tot T+4 (T = trade date) |
| **Solidaire premieregeling** | SPR | Premieregeling waarbij de premie collectief wordt belegd, de resultaten in ieder geval naar leeftijdscohorten worden toebedeeld en waarbij het voor pensioenuitkering bestemd vermogen gedurende de uitkeringsfase wordt aangewend voor financiering van een variabele uitkering. Voor de cohorten moet door de pensioenuitvoerders worden voorzien in toedelingsbeleid naar de individuen/deelnemers die van een cohort deel uitmaken.
 |
| **Toedelingsbeleid / Toedelingsregels** | | De wijze waarop de pensioenuitvoerder het rendement toebedeeld aan de (groepen / cohorten en vanuit die groepen naar individuele) deelnemers.
 |
| **Total market value**
 |
 | De nettowaarde van een belegging. Bij de FPR gaat het om de waarde van een aandeel of andere participatievorm in het totale kapitaal. Bij de SPR wordt door de beleggingsadministrateur de waarde (NAV) van het totale kapitaal van de (collectieve) belegging doorgegeven aan de pensioenuitvoeringsorganisatie.
 |
| **Trade date** |
 | Datum waarop de pensioenuitvoeringsorganisatie de order voor een pensioenregeling (scheme) uitgevoerd wil hebben.
 |
| **Indirect (theoretisch beschermingsrendement)** |
 | Bescherming voor het renterisico in de solidaire premieregeling door gebruik te maken van een rentetermijnstructuur, bedoeld in artikel 2, tweede lid, van het Besluit financieel toetsingskader pensioenfondsen.
 |
| **Transfer agent** |
 | Registrar; degene die de participaties bijhoudt. Vooral van belang bij dagelijks verhandelbare stukken (bij FPR) Een transferagent is een trustmaatschappij, bank of soortgelijke instelling die is aangewezen om de financiële gegevens van een belegger bij te houden en het rekeningsaldo van elke belegger bij te houden. Voorbeelden zijn: Fundsettle, Allfunds en BBH).
 |
| **Valuation date** |
 | Datum van de waardebepaling van de cohortenpool gebruikt bij het doorgeven van de waarde van (pool)unit binnen deze pool.
 |
| **Value date** |
 | Valuta datum. Een datum binnen een opdracht tot het doen van een betaling.
 |
| **Vermogensbeheerder** | VB | Uitgever van financiële producten (structured products) verantwoordelijk voor het actief en/of passief portefeuillemanagement.
 |
| **Voorziening pensioenverplichtingen** | VPV | Het benodigde kapitaal wat nodig is om aan de huidige en toekomstige pensioenverplichtingen te kunnen voldoen.
 |

## 10.2Begrippenlijst gegevensuitwisseling op basis van standaarden

| **Begrip** | **Betekenis** |
| --- | --- |
| **API** | Een application programming interface (API) is een gestructureerd en gedocumenteerd koppelvlak voor communicatie tussen applicaties. Voor steeds meer organisaties vormen API's (bibliotheek met webservices) de sleutelrol in het aanbieden van transacties, het distribueren van content of het ontsluiten van een workflow tussen schakels in de keten.
 |
| --- | --- |
| **Attribuut** | Een uniek kenmerk of gegeven van een entiteit. |
| **Begrijpelijkheid gegeven**
 | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)De mate waarin gegevens eenvoudig gelezen en geïnterpreteerd kunnen worden door gebruikers.
 |
| **Bericht** | Een bericht beschrijft de interface tussen twee geautomatiseerde toepassingen die berichten uitwisselen.
 |
| **Berichtschema** | Een bericht-/productdefinitie in schemavorm.
 |
| **Berichtstructuur** | Op basis van de bouwstenendoos met entiteiten, attributen etc. worden een of meer hiërarchische structuren gespecificeerd. In deze structuur worden de relaties tussen de entiteiten aangegeven.
 |
| **Consistentie gegevens**
 | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)De mate waarin gegevens vrij van tegenspraak zijn en samenhang vertonen met andere gegevens.
 |
| **CSV-bestand** | Een gegevensbestand waarvan de waarden door een leesteken worden gescheiden (in de regel een komma of puntkomma) als specificatie voor tabelbestanden. De waarden kunnen in een rekenblad¬ of een databaseprogramma worden ingelezen en vervolgens op een beeldscherm als tabel worden gepresenteerd.
 |
| **Data Exchange** | Data Exchange is de techniek waarbij de data van verschillende geautomatiseerde toepassingen op geautomatiseerde wijze met elkaar uitwisselbaar zijn op basis van gemaakte afspraken over onder andere standaarden.
 |
| **Data Governance** | Een systeem dat interoperabiliteitscomponenten (standaarden en beleidsregels) toepast om het acceptabele gebruik en de hoge kwaliteit van gegevens binnen een specifiek ecosysteem te garanderen. Beheert de beschikbaarheid, bruikbaarheid, consistentie, integriteit en beveiliging van de gebruikte gegevens.
 |
| **Entiteit** | Dit is 'iets wat een bestaan heeft'. Dus iets dat er toe doet, dat men kan duiden, kan benoemen en waarde heeft. Bijvoorbeeld een persoon is een entiteit en kan beschreven worden met attributen zoals voornaam, familienaam of [BSN](https://nl.wikipedia.org/wiki/Burgerservicenummer)-nummer (uniek persoonsgebonden nummer).
 |
| **Gegeven** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)Weergave van een feit, begrip of aanwijzing, geschikt voor overdracht, interpretatie of verwerking door een persoon of apparaat.
 |
| **Gegevensgroep (entiteit)** | Groep van gegevenselementen die logisch bij elkaar hoort.
 |
| **Gegevenskwaliteit of Datakwaliteit** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online) De mate waarin een geheel van eigenschappen en kenmerken van één of meer gegevens voldoet aan eisen. Het streven is dat gegevenskwaliteit "fit-for-purpose" is; dat deze aansluit bij het gebruik. Kwaliteit heeft betrekking op de mate waarin wordt voldaan aan verwachtingen.
 |
| **Gegevensoverdraagbaarheid** | Dataportabiliteit. De mogelijkheid om gegevens gemakkelijk te verplaatsen tussen interoperabele toepassingen en domeinen.
 |
| **Interoperabiliteit** | I[nteroperabiliteit](https://www.noraonline.nl/wiki/Interoperabiliteit) is het vermogen van organisaties (en hun processen en systemen) om effectief en efficiënt informatie te delen met hun omgeving.
In het [European Interoperability Framework](https://joinup.ec.europa.eu/collection/nifo-national-interoperability-framework-observatory/european-interoperability-framework-detail) worden drie vormen van interoperabiliteit onderscheiden:
1. Technische interoperabiliteit – Om systemen te kunnen koppelen, moeten er afspraken worden gemaakt over interfaces, standaarden en protocollen voor communicatie, berichtenformaten, gegevensintegratie, beveiliging, beschikbaarheid, etc.
2. Semantische interoperabiliteit – De informatie die partijen uitwisselen, moet wederzijds begrijpelijk zijn. Context en betekenis van gegevens moet eenduidig zijn vastgelegd.
3. Organisatorische interoperabiliteit – Om gezamenlijke diensten te kunnen leveren, moeten organisaties op elkaar zijn afgestemd in termen van hun businessdoelen, verdeling van verantwoordelijkheden en uitwisselingsprocessen.

 |
| **Koppelvlak** | Het geheel van gemeenschappelijke afspraken dat de uitwisseling van gegevens tussen digitale systemen mogelijk maakt.
 |
| **Kwaliteitseis of norm** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online) Een norm waaraan gegevens moeten voldoen. Een kwaliteitseis wordt in veel gevallen uitgedrukt in een getal zoals een percentage.
 |
| **Metadata** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online) Metagegevens. Data over data. Metadata zijn data die de karakteristieken van andere data beschrijven. Het bewaren bij of koppelen van metadata aan de data waarop ze betrekking hebben, heeft als voordeel dat de data makkelijker gevonden kunnen worden.
 |
| **Metagegevens** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)Gegevens die context, inhoud, structuur en vorm van informatie en het beheer ervan door de tijd heen beschrijven.
 |
| **Onweerlegbaarheid gegeven** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)Begrip dat gebruikt wordt bij elektronische berichtuitwisseling en dat inhoudt dat de zender van een bericht niet kan ontkennen een bepaald bericht te hebben verstuurd en dat de ontvanger van een bericht niet kan ontkennen het bericht van de zender in de oorspronkelijke staat te hebben ontvangen. |
| **Plausibiliteit gegeven** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)De mate waarin gegevens worden beschouwd als waar en geloofwaardig door gebruikers.
 |
| **Precisie gegeven** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)De mate waarin gegevens exact of onderscheidend genoeg zijn.
 |
| **Semantiek** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online) Leer van de betekenis van woorden en woordgroepen.
 |
| **Standaard** | Dit zijn afspraken over informatie of over een proces, dit kan zowel op het niveau van semantische als technische standaarden. Veelal worden de afspraken vastgelegd in documenten met erkende status. Standaarden worden onderhouden vanuit standaardisatie organisaties zoals het NEN en aanbevolen of verplicht gesteld door bijvoorbeeld [Bureau Forum Standaardisatie.](https://forumstandaardisatie.nl/node/229)

 |
| **Straight Through Processing (STP)**
 | STP is de elektronische verwerking van processen waarbij de elkaar opvolgende administratieve handelingen plaatsvinden met zo min mogelijk menselijke tussenkomst.
 |
| **Transparantie** | Bron: [SSI Speelveldanalyse](https://open.overheid.nl/repository/ronl-9fa0e23a-0b04-442a-917b-36bce29403a8/1/pdf/eindrapport-nederlandse-self-sovereign-identity-ecosysteem-ssi.pdf), Innopay & TNO, 1 oktober 2021 De mate waarin personen, groepen en organisaties zicht hebben op welke gegevens die op henzelf betrekking hebben voor welk doel gebruikt worden.
 |
| **Validiteit gegevens** | Bron: [NORA](https://www.noraonline.nl/wiki/NORA_online)De mate waarin gegevens voldoen aan de verwachte structuur en opslagvorm.
 |

## 10.3P ![](RackMultipart20231222-1-avhyj4_html_f07e1c2c5a686d86.png) roces flow & data-uitwisseling FPR

![](RackMultipart20231222-1-avhyj4_html_a9ad496a63299634.png)

## 10.4Huishoudelijk Reglement Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering

### 10.4.1Inleiding

Dit Huishoudelijk Reglement geeft uitleg over de overlegstructuur van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering heeft een informeel karakter, omdat alle betrokken een gemeenschappelijk belang hebben, namelijk een goed werkende standaard.

Dit document biedt handvaten zodat de betrokken partijen van elkaar weten wat ze in deze samenwerking kunnen verwachten. Het Huishoudelijk Reglement bevat naast toelatingscriteria en taken, een weergave van de meer operationele werkafspraken over de vergaderingen, de verdeling van de werkzaamheden, de besluitvorming in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering en de verhouding tot de Stuurgroep DSO en de Stuurgroep GZD.

### 10.4.2Begrippenlijst

Standaard Vermogensbeheer Pensioenuitvoering

De Standaard Vermogensbeheer Pensioenuitvoeringis een standaard voor het uitwisselen van data tussen vermogensbeheer en pensioenuitvoering. De intellectueel eigendomsrechten van de liggen bij de Pensioenfederatie. De standaard staat beschreven in verschillende functionele en technische documenten.

Stuurgroep DSO

De Stuurgroep Digitale Standaardisatie en Ontwikkeling bestaat uit vertegenwoordigers van pensioenuitvoeringsorganisaties en een waarnemer vanuit de Pensioenfederatie. De stuurgroep DSO is opdrachtgever richting SIVI.

Stuurgroep GZD

De Stuurgroep Gezamenlijk Domein bestaat uit vertegenwoordigers van de stuurgroep DSO, het SIVI Bestuur, de Pensioenfederatie en het Verbond van Verzekeraars. De stuurgroep GZD is opdrachtgever richting SIVI.

Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering bestaat uit vertegenwoordigers van pensioenuitvoeringsorganisaties, vermogensbeheerders en leveranciers. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering wordt gefaciliteerd door SIVI.

Pensioenuitvoeringsorganisatie

Een pensioenuitvoeringsorganisatie voert in opdracht van een of meerdere pensioenfondsen een aantal werkzaamheden uit. Bijvoorbeeld de administratie van de pensioenaanspraken, de communicatie met de deelnemers, het verzorgen van de uitbetaling van pensioenen, etc.

Leverancier

Een bedrijf dat ontwikkelaar is van software voor de datauitwisseling tussen vermogensbeheer en pensioenuitvoering.

SIVI

Stichting die de Standaard Vermogensbeheer Pensioenuitvoering beheert in opdracht van de Pensioenfederatie.

### 10.4.3Samenstelling

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering bestaat uit vertegenwoordigers van pensioenuitvoeringsorganisaties, vermogensbeheerders en leveranciers. De samenstelling van de groep draagt bij aan overleg dat informeel van toon is, dat evenwichtig verdeeld is en materiedeskundig. Een aantal uitgangspunten helpt hierbij.

1. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering bestaat uit vertegenwoordigers van organisaties die de gegevensuitwisseling tussen vermogensbeheer en pensioenuitvoering implementeren, of daartoe de intentie hebben.
2. De genoemde vertegenwoordigers in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering hebben een vaste vertegenwoordiger.
3. Van de vertegenwoordigers van leveranciers wordt verwacht dat zij handelen in het belang van alle leveranciers, inclusief die partijen die niet vertegenwoordigd zijn in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering;
4. Behoudens SIVI, wordt iedere organisatie vertegenwoordigd door één persoon. Daarbij is het de doelstelling dat sprake is van een vaste vertegenwoordiging, ten behoeve van het borgen van de continuïteit en kennis;
5. Een lid van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering kan zich laten vervangen door een collega uit de organisatie namens wie hij/zij in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering afgevaardigd is;
6. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering wordt voorgezeten door een vaste voorzitter. De vaste voorzitter kan bij afwezigheid vervangen worden door een vicevoorzitter. SIVI levert de voorzitter en vicevoorzitter.
7. SIVI levert ook een secretaris voor de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering en kan zich in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering laten bijstaan door een raadgevende deskundige.
8. De vertegenwoordiger van een pensioenuitvoeringsorganisatie, vermogensbeheerder of leverancier wordt benoemd door de directeur van SIVI. Een afwijzing van een voorgedragen kandidaat is met redenen omkleed.
9. Elk lid van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering belooft geheimhouding ten aanzien van concurrentiële informatie en heeft:

- Ervaring met toepassing van en/of bedrijfsprocessen rond de datauitwisseling tussen vermogensbeheer en pensioenuitvoering;
- Ervaring met de inzet van ICT binnen bedrijfsprocessen;
- Ervaring met analyse en inhoudelijk inzicht in bedrijfsprocessen en koppelvlakken tussen processen en organisaties in de pensioensector;
- Bereidheid om samen te werken en kennis te delen;
- Bereidheid om te adviseren vanuit een collectief belang.

1. Het maximaal aantal pensioenuitvoeringsorganisaties, vermogensbeheerders en leveranciers in de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering is respectievelijk 7, 7 en 5.

### 10.4.4Wijzigingen samenstelling

1. Een nieuw lid wordt voorgedragen door zijn organisatie.
2. Een vertegenwoordiger van wie het lidmaatschap aan de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering eindigt, stelt hiervan de secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering in kennis.
3. Voor leden die bij hun benoeming zijn voorgedragen door hun organisatie eindigt het lidmaatschap bij beëindiging van de werkzaamheden voor de organisatie. Het lid stelt de secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering hiervan zo spoedig in kennis. De organisatie kan tevens een nieuw lid voordragen.
4. Lidmaatschap van een vertegenwoordiger aan de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering eindigt tevens op verzoek van de organisatie. De organisatie dient dit verzoek in bij de secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering. De organisatie kan tevens een nieuw lid voordragen.

### 10.4.5Vergaderingen

Frequentie

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering vergadert minimaal 2 maal per jaar en verder zo vaak als nodig wordt geacht door SIVI of door de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering.

Voorbereiding

      1. De secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering stelt de conceptagenda op en legt deze uiterlijk twee weken voor de vergaderdatum ter goedkeuring voor aan de voorzitter van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering.
      2. Na goedkeuring door de voorzitter van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering stuurt de secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering - uiterlijk een week voor de vergaderdatum - de agenda en bijbehorende vergaderstukken naar de leden van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering.

Vergadering

1. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering vergadert onder leiding van de voorzitter of de vicevoorzitter van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering.
2. De secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering maakt een verslag op van de vergadering en stuurt deze uiterlijk één week na de vergadering in concept naar de leden. De leden hebben dan gelegenheid om aanvullingen/correcties door te geven, gedurende de bij het verzoek vermelde termijn. In het verslag wordt opgenomen welke leden aanwezig en afwezig zijn.
3. De secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering stuurt het verslag met de agendastukken van de eerstvolgende vergadering aan de leden mee. Een verslag wordt op de eerstvolgende vergadering ter goedkeuring voorgelegd.
4. Tot de goedkeuring van het verslag is de inhoud van het verslag vertrouwelijk.

Afwezigheid

Een lid dat niet aanwezig kan zijn bij een vergadering van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering, stelt de secretaris hiervan zo spoedig mogelijk in kennis. Bij deze kennisgeving wordt ook aangegeven of en door wie het lid vervangen zal worden.

Werkgroepen

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering kan specialistische vraagstukken laten behandelen/voorbereiden door een hiervoor tijdelijk ingerichte werkgroep. De notulen van deze werkgroep overleggen zijn vertrouwelijk.

### 10.4.6Taken

SIVI behandelt wijzigingsvoorstellen op basis van de impact:

- Aanpassingen met lichte impact worden beoordeeld door uitvoeringsorgaan SIVI. Het gaat hierbij bijvoorbeeld om herstel van bepaalde onjuistheden of de vulling van het regelingenoverzicht. In deze gevallen kan SIVI kiezen voor afstemming per e-mail.
- Aanpassingen met middelgrote impact worden beoordeeld door de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering. Het gaat hierbij bijvoorbeeld om nieuwe spelregel voor het aanmaken/vullen van berichten, toevoegen attributen aan berichten, of het toevoegen van codewaarden aan codelijsten.
- Aanpassingen met zware impact worden beoordeeld door de Stuurgroep DSO en Stuurgroep GZD. Het gaat hierbij bijvoorbeeld om wijzigingen in de structuur van de standaard.

Gevraagd en ongevraagd advies

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering geeft SIVI gevraagd en ongevraagd advies met betrekking tot het werkgebied van de Standaard Vermogensbeheer Pensioenuitvoering.

Voor gevraagd advies gelden de volgende uitgangspunten:

1. De Stuurgroep DSO, Stuurgroep GZD en de uitvoeringsorganisatie SIVI kunnen de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering verzoeken hen van advies te dienen.
2. Het adviesverzoek wordt gericht aan de secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering en bevat in ieder geval:
  1. De aard en de aanleiding voor het verzoek;
  2. Een beschrijving van het verzoek.
3. De secretaris plaatst het verzoek om advies op de agenda van de eerstvolgende vergadering, mits de agendastukken voor die vergadering nog niet zijn verstuurd. In dat geval agendeert de secretaris het verzoek voor de daaropvolgende vergadering.
4. Tijdens de vergadering kan de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering ten aanzien van het verzoek:
  1. een advies formuleren;
  2. besluiten dat de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering geen advies kan uitbrengen, omdat de kwestie niet tot haar competentie behoort;
  3. besluiten dat de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering bij gebrek aan voldoende informatie geen advies kan uitbrengen, en de verzoeker vragen dit te herstellen. In dat geval geeft de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering zo specifiek mogelijk aan welke informatie ontbreekt;
  4. besluiten dat de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering nog geen advies kan uitbrengen, omdat zij meer tijd nodig heeft om tot een advies te komen. In dat geval geeft de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering aan wanneer zij denkt met een advies te kunnen komen.
5. De secretaris van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering stelt het antwoord op het verzoek na de vergadering op schrift en legt dit ter goedkeuring voor aan de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering. Zij geven binnen de gestelde termijn na ontvangst van het concept hun reactie hierop.
6. Van de uitkomst van de behandeling van een verzoek om advies wordt de Stuurgroep DSO, Stuurgroep GZD en SIVI in kennis gesteld.

Voor gevraagd advies gelden de volgende uitgangspunten:

1. De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering kan besluiten de Stuurgroep DSO, Stuurgroep GZD of SIVI ongevraagd van advies te dienen. In dat geval stelt de secretaris na de vergadering het advies op schrift en legt dit ter goedkeuring voor aan de leden.
2. De leden van de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering, geven binnen de gestelde termijn na ontvangst van het concept hun reactie hierop.

### 10.4.7Besluitvorming

De Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering heeft een besluitvormende rol en een adviserende rol. Daar waar de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering besluiten neemt over wijzigingsverzoeken of besluiten neemt over adviezen worden deze in beginsel tijdens de vergadering genomen. Hierbij wordt gestreefd naar gemeenschappelijke overeenstemming. Wordt geen consensus bereikt, dan stelt SIVI de Stuurgroep DSO en stuurgroep GZD in staat een besluit te nemen.

### 10.4.8Overig

**Communicatie**

Schriftelijke communicatie vindt zo veel mogelijk plaats per e-mail.

**Onkosten**

Deelname aan de Klankbordgroep Standaard Vermogensbeheer Pensioenuitvoering is onbezoldigd. Reis-, verblijfkosten en overige onkosten worden gedragen door de vertegenwoordigde organisatie.

**Wijziging**

1. Dit huishoudelijk reglement is goedgekeurd door de Stuurgroep DSO en Stuurgroep GZD.
2. Wijzigingen in het huishoudelijk reglement worden door de Stuurgroep DSO en stuurgroep GZD goedgekeurd.

## 10.5Onderdelen Standaard Vermogensbeheer Pensioenuitvoering

In onderstaande Figuur 14 staat aangeven wat SIVI gaat vastleggen voor de Standaard Vermogensbeheer Pensioenuitvoering. Daarna volgt in de tabel een toelichting op de onderdelen.

![](RackMultipart20231222-1-avhyj4_html_2f46e6b16b8f2dba.gif)

**Figuur 14 - Onderdelen van de standaard in samenhang**

| **Nr.** | **Onderdeel standaard** | **Toelichting** |
| --- | --- | --- |
| **1** | **Uitgangspunten** | De belangrijkste uitgangspunten bij de ontwikkeling, opzet en besturing van de standaard.
 |
| --- | --- | --- |
| **2** | **Procesbeschrijvingen** | Procesbeschrijvingen zijn gestructureerde beschrijvingen die de stappen, activiteiten en betrokken elementen van de specifieke ketenprocessen en informatiestromen in detail uitleggen. We gebruiken deze beschrijvingen om een duidelijk begrip te verschaffen van hoe de processen werken en welke informatiestromen aan de orde zijn. In dit geval is vooral het onderscheid tussen flexibele en solidaire premieregeling relevant.
 |
| **3** | **Governance** | Governance gaat over het optimaal inrichten van de organisatie van de community rond de standaard. Duidelijk moet zijn wie beslist over wat uitgevoerd wordt met betrekking tot standaarden, en wie beslist hoe dit wordt uitgevoerd. Onderdeel is het huishoudelijk reglement van de klankbordgroep en de eventuele tijdelijke werkgroepen.
 |
| **4** | **Organisatie beheer** | Beheer gaat in op de beheersmatige processen rondom de standaarden. Het omvat alle activiteiten gericht op het aanpassen, uitbreiden, doorontwikkelen, beschikbaar stellen en houden van een (set van) berichten die steeds past bij de actuele behoefte van de belanghebbenden.
 |
| **5** | **Wijzigingsprocedure** | Wijzigingen op de standaard raakt meerdere belanghebbenden. In de procedure van wijziging zijn hierom de belangen van alle deelnemende partijen vertegenwoordigd. Verzoeken en voorstellen voor wijzigingen zullen een afgesproken procedure worden behandeld.
 |
| **6** | **Gegevensspecificaties** | In de gegevensspecificaties is de betekenis van de gegevenselementen beschreven en zijn de onderlinge verbanden beschreven. Gegevenselementen zijn entiteiten, attributen en codelijsten.
In de gegevensspecificaties is de afbeelding naar AFD 2.0 opgenomen. Hierdoor is duidelijk wat ontbreekt. Voor de ontbrekende elementen is een voorzet gedaan in AFD 2.0 termen.
 |
| **7** | **Basisstructuur berichten** | Basisbericht met de basisstructuur voor een set berichten. In de basisstructuur staat een opsomming van de entiteiten/attributen en de bijbehorende hiërarchische structuur. De beschrijving van dit basisbericht kan gebruikt worden om een baseline te maken.
 |
| **8** | **Kruistabel basisstructuur en berichten** | Een kruistabel tussen de basisstructuur en de berichten.Per bericht is in de tabel aangegeven welke entiteiten/attributen van toepassing zijn. Hierbij is het aantal herhalingen (entiteiten) aangegeven en ook welke attributen verplicht gevuld moeten worden. Het is tevens mogelijk selecties uit codelijsten te maken, dat wil zeggen aan te geven welke codewaarden van toepassing zijn.
 |
| **9** | **Berichtspecificaties** | De specificaties zijn gebaseerd op de gegevensspecificaties. In deze berichtspecificatie wordt dit vertaald naar een hiërarchische berichtstructuur. Onderdeel van de set berichtspecificaties is het responsebericht. Dit moeten we nog opstellen.
Ieder bericht kent een algemene sectie waarin onder meer staat aangegeven wie de zender/ontvanger is van het bericht.
 |
| **10** | **Berichtcontroles** | Een specificatie van alle controles op de berichten, bijvoorbeeld verbandcontroles. Het is een optie deze controles in machine leesbare vorm uit te leveren, maar in eerste instantie is dit niet noodzakelijk.
 |
| **11** | **Uitbreiding AFD 2.0** | Uitbreiding van AFD 2.0 met gevraagde gegevenselementen. AFD 2.0 kan op verzoek van belanghebbenden maandelijks uitgebreid worden.
 |
| **12** | **Baseline** | Dit is het basisbericht dat in AOS wordt geïmporteerd. Daarna kunnen AFD-definities gemaakt worden.
 |
| **13** | **Schema's** | JSON-Schema of XML-Schema per bericht/basisstructuur. Onder meer om berichten te kunnen valideren. AOS levert JSON-schema's op basis van AFD 2.0 berichten en AFD-definities.
 |
| **14** | **Handleiding events** | Voorbeelden van het afhandelen van specifieke situaties. De situaties laten zien hoe de standaard toegepast moet worden.Voorbeeldberichten zijn onderdeel van de handleiding events.
 |
| **15** | **Koppelvlakspecificaties** | Bij geautomatiseerde koppelingen tussen gedistribueerde systemen (machine-‐machine) is sprake van een interface waarmee communicatie mogelijk wordt gemaakt. Zo'n interface wordt een koppelvlak genoemd. De beschrijving van een koppelvlak noemen we koppelvlakspecificaties.Voorbeelden:
- Webservices
- File transfer
- Aanlevering via portaal

Onderdeel van de koppelvlakspecificaties kunnen instructies zijn over de (data)beveiliging.
Opmerking: koppelvlakspecificaties hebben Duco/Gerhard niet toegezegd. Als hier vraag naar ontstaat, dan pakken we dat op.
 |
| **16** | **Testvoorzieningen** | Voorzieningen om de ontwikkelaars te ondersteunen bij het implementeren van de berichten/koppelvlakspecificaties.Onderdeel kan een generieke set zijn met testgegevens.
 |
| **17** | **Rekenvoorschriften** | Instructies om berekeningen uit te voeren. De berekeningen zijn van toepassing voor gegevenselementen in de berichten.
 |

**Berichtcontroles**

Op dit moment wordt voor berichtcontroles (verbandscontroles) **in plaats van Xpath** gebruik gemaakt van berichten [pseudocode](https://oer-studentresources.gesci.org/wp-content/courses/Computer/CS-F3-Algorithms/examples.html) die in principe vrij makkelijk [is om te zetten](https://pseudoeditor.com/app/) in welke programmeertaal dan ook. Voorbeeld:

BEGIN

    FOR EACH pensionScheme IN bericht4.party.pension

        FOR EACH investmentPortfolio IN pensionScheme.investment

            calculatedEndAmount = investmentPortfolio.startAmount + investmentPortfolio.returnAmount + investmentPortfolio.netAmount

            IF calculatedEndAmount != investmentPortfolio.endAmount THEN

                PRINT 'FT4001'

            END IF

        END FOR

    END FOR

END

Waarbij FT4001 = 'In investment portfolio '' + investmentPortfolio.refKey + '', de som van 'startAmount', 'returnAmount' en 'netAmount' (Netto som van inleg en onttrekkingen) moet gelijk zijn aan 'endAmount

**JSON-schema's**

De JSON-schema's zijn in principe zelfverklarend, maar enige toelichting kan nuttig zijn omdat deze schema's ook in JSON-technologie zijn opgesplitst. Dit betekent dat naast de verwachte entiteiten en entiteittypen zoals 'party' en 'pension.scheme', er ook wordt gesproken over bepaalde sleutelelementen zoals "Definitions", "Type", "Properties", "AdditionalProperties" en "Required". Deze eigenschappen en specificaties die van toepassing zijn op bijvoorbeeld 'commonFunctional', zijn niet allemaal gegroepeerd rond 'commonFunctional', maar zijn verspreid over het JSON-schema. Het belangrijkste om op te merken is dat deze verspreiding niet willekeurig is, maar volgt uit de verschillende typen eigenschappen.

## 10.6Vertaaltabel van functionele attributen naar AFD2.0 attributen.

In het consultatierapport werden op diverse plaatsen andere attribuutnamen gebruikt dan in het uiteindelijke AFD 2.0 model. Hieronder een overzicht van de functionele attribuutnamen en de uiteindelijke AFD 2.0 gegevensnamen.

| **Attribuutnaam Functioneel** | **AFD 2.0 entity.entitytype** | **AFD 2.0 attribuutnaam** | **Omschrijving** |
| --- | --- | --- | --- |
| Transfer ID | commonTechnical.default | messageId | Unieke berichtidentificatie |
| --- | --- | --- | --- |
| Pensionfund ID | party.pensionProvider | refKey | ID van het pensioenuitvoerder (PUV-code) / Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) |
| Pension scheme ID i | pension.scheme | refKey | ID van de pensioenregeling / (Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.)) |
| Capital i | pension.scheme | StartAmount | Totaal pensioenvermogen per begindatum |
| Expected pension payment Date i, k | pension.scheme | expectedPensionPaymentDate | Pensioenuitkeringsmoment (eventueel per regeling) |
| Total expected pension payment i,k | pension.scheme | totalExpectedPensionPaymentAmount | Totaal geprojecteerde uitkeringen over alle cohorten |
| Hedged expected pension payment i,k | pension.scheme | hedgedExpectedPensionPaymentAmount | Af te dekken kasstromen per periode |
| Portfolio | pension.scheme | tradingPortfolioId | Portefeuille ID van de custodian (bewaren en beheren van financiële activa) |
| Capital date i / Start date PUO admin / Start date Investment Report | financialInformation.reportingPeriod | startDate | Begindatum van de gegevensperiode waarop de aanlevering vanuit de PUO wordt gebaseerd |
| End date PUO admin | financialInformation.reportingPeriod | endDate | Einddatum van de gegevensperiode waarop de aanlevering vanuit de PUO wordt gebaseerd |
| Mutations date | financialInformation.reportingPeriod | mutationValuationDate | Datum verwerking mutaties per leeftijdsgroep |
| End date​ Investment Report | financialInformation.reportingPeriod | endDate | Einddatum van de gegevensperiode waarover rendement wordt gerapporteerd |
| Settlement date | financialInformation.reportingPeriodn | investmentOrderSettlementDate | Datum waarop de volledige cyclus van de beleggingsorder afgewikkeld moet zijn |
| Projection date | financialInformation.reportingPeriod | projectionDate | Datum van de projectie van pensioenuitkeringen |
| instruction date | financialInformation.reportingPeriod | instructionDate | Instructiedatum (datum van de bestelling verzonden door de PUO) |
| Estimation date | financialInformation.reportingPeriod | unitValueEstimationDate | Geeft de datum aan waarop de voorlopige unitwaarde (belegginspool) is bepaald |
| Valuation date | financialInformation.reportingPeriod | participationValuationDate | Prijsdatum participatiewaarde (cohortpool) |
| value date | financialInformation.reportingPeriodn | valueDate | Currency date. (NL: Valutadatum) |
| Date | financialInformation.reportingPeriod | positionDate | De datum waarop de posities in de beleggingsadministratie zijn vastgesteld |
| Value | financialTransaction.payment | amount | Bedrag in valuta |
| currency i | financialTransaction.payment | currencyType | Valuta |
| IBAN debet i | financialTransaction.payment | collectionAccountIban | IBAN-nummer van debet rekening |
| Description i | financialTransaction.payment | description | Omschrijving van de transactie (betaling) |
| IBAN credit i | party.creditor | collectionAccountIban | IBAN-nummer van credit rekening per regeling |
| Counterparty i | party.creditor | collectionAccountInNameOf | Naam van de tegenpartij per regeling |
| BIC i | party.creditor | collectionAccountBic | Business Identifier Code (BIC) per regeling |
| BIC-correspondent i | party.creditor | collectionAccountBicCorrespondent | BIC-correspondent per regeling |
| Contribution i | financialTransaction.cashflow | contributionAmount | Som van inleg |
| Contribution date i | financialTransaction.cashflow | contributionDate | Datum van ontvangst van de inleg |
| Withdrawal i | financialTransaction.cashflow | withdrawalAmount | Som van de uitstroom |
| Withdrawal date i | financialTransaction.cashflow | withdrawalDate | Datum waarop (uiterlijk) de liquiditeiten ten behoeve van de onttrekking zijn vrijgemaakt |
| Net contribution/withdrawal i | financialTransaction.cashflow | netAmount | Som van inleg en onttrekkingen per regeling (net). Een negatief bedrag is een (netto) withdrawal. / Verschil tussen inleg en onttrekking. Een negatief bedrag is een (netto) onttrekking.) |
| Net contribution/withdrawal
 date i | financialTransaction.cashflow | netDate | Datum waarop gesaldeerde instroom en uitstroom wordt gefaciliteerd / Datum waarop het saldo van inleg en onttrekking is bepaald |
| Cohort ID i, k | pension.cohort | refKey | ID van het cohort |
| Cohort Capital i,k | pension.cohort | startAmount | Pensioenvermogen van het cohort per begindatum |
| Net contribution/withdrawal I,k | pension.cohort | netAmount | Som van inleg en onttrekkingen per cohort. Een negatief bedrag is een (netto) onttrekking.) |
| Cohort contribution i,k | pension.cohort | contributionAmount | Instroom te beleggen door de fiduciair manager |
| Cohort withdrawal i,k | pension.cohort | withdrawalAmount | Uitstroom te beleggen door de fiduciair manager |
| Cohort expected pension payment i,j,k | pension.cohort | expectedPensionPaymentAmount | (Geprojecteerde) uitkering |
| Cohort return rate protection i,k | pension.cohort | protectionReturnPercentage | Het behaalde beschermingsrendement in percentage over gegevensperiode per regeling en per cohort |
| Cohort return rate excess i,k | pension.cohort | excessReturnPercentage | Het behaalde overrendement in percentage over gegevensperiode per regeling en per cohort |
| Cohort return protection i,k | pension.cohort | protectionReturnAmount | Het behaalde beschermingsrendement in valuta van de regeling over gegevensperiode per regeling en per cohort |
| Cohort return excess i,k | pension.cohort | excessReturnAmount | Het behaalde overrendement in valuta van de regeling over gegevensperiode per regeling en per cohort |
| Cohort ID i, k | pension.cohortPool | cohortRef | Geeft aan op welk cohort in de regeling de cohortpool-gegevens betrekking hebben |
| Cohort Inflow i-k (1) | pension.cohortPool | inflowPremiumAmount | Premie-inleg per cohortpool per regeling |
| Cohort Inflow i-k (2) | pension.cohortPool | inflowRebalanceAmount | Geldbedrag van rebalance transacties per cohortpool per regeling |
| Cohort withdrawal i,k | pension.cohortPool | numberOfNewParticipations | Nieuwe uit te geven participaties in cohortpool per regeling (instroom) |
| Number of units, i,k | pension.cohortPool | numberOfParticipations | Aantal uitstaande units (participaties) in de Cohortpool |
| Cohort rebalance i,k | pension.cohortPool | numberOFRebalanceParticipations | Rebalance participaties per cohortpool per regeling (bij overgang van een cohortpool naar een ander cohort) |
| Cohort Capital i,k / Cohort value i, k | pension.cohortPool | participationsSummedValueAmount | Waarde per cohortpool (som participatiewaarde) per participationValuationDate |
| Pool ID i,j | investment.pool | refKey | ID van de beleggingspool per regeling |
| Market value portfolio | investment.pool | marketValueAmount | Marktwaarde per portefeuille per regeling in currencyType |
| Pool value i, k | investment.pool | unitsSummedValueAmount | Waarde per beleggingspool(unitwaarde) |
| Preliminary market value i, k | investment.pool | preliminaryMarketValueAmount | Voorlopige Marktwaarde per portefeuille per regeling in currencyType van de pool |
| Preliminary pool value i, k | investment.pool | preliminaryUnitValueAmount | Voorlopige unitwaarde in currencyType van de pool |
| number of units investment pool i,k | investment.pool | numberOfUnits | Aantal units uitgegeven voor de beleggingspool, |
| currency i,j | investment.pool | currencyType | Valuta van de pool |
| Pool ID i,j | investment.pool | refKey | ID van de beleggingspool per regeling |
| Transaction description i,j, k /Description | investment.pool | description | Beschrijving |
| Dummy cash ID | investment.pool | dummyCashId | ID voor dummy cash instrument per beleggingspool per regeling per cohort(pool) |
| Sell buy ID i,j, k | investment.pool | buySellId | Aan- verkoopindicator; ID voor aan-/verkoop per beleggingspool per regeling per cohort |
| Amount i,j, k | investment.pool | tradeQuantity | Aantal te verhandelen stukken (units) van de transactie |
| Unit value i,j, k | investment.pool | unitPrice | Unitwaarde (/prijs) per beleggingspool per regeling per cohort |
| FX rate i,j, k | investment.pool | currencyExchangeRate | FX rate per beleggingspool per regeling per cohort |
| Value i,k | investment.pool | tradeValueAmount | Waarde transactie per beleggingspool per regeling (gesommeerd over cohorten) |
| currency i,j | investment.pool | currencyType | Valuta van de pool |
| portfolio ID i,n | investment.portfolio | refKey | ID Beleggingsportefeuille / Unique reference key assigned to an entity. (NL: Entiteitsreferentie is een unieke referentie sleutel die aan een entiteit wordt toegekend.) |
| Total Market Value start I,n | investment.portfolio | startAmount | De waarde van de Total Market Value aan het begin van de gegevensperiode |
| Net contribution/withdrawal I, n | investment.portfolio | netAmount | Som van inleg en onttrekkingen per regeling (net). Een negatief bedrag is een (netto) withdrawal |
| Total Market Value end I,n | investment.portfolio | endAmount | De waarde van de Total Market Value aan het eind van de gegevensperiode. Per regeling en beleggingsportefeuille |
| Return rate i,n​ | investment.portfolio | returnPercentage | Het behaalde rendement in percentage over gegevensperiode per regeling en per beleggingsportefeuille |
| Return i,n​ | investment.portfolio | returnAmount | Het behaalde rendement in valuta van de regeling over gegevensperiode per regeling en per beleggingsportefeuille |
| Identifier | investment.investmentDetails | refKey | Identifier (bijvoorbeeld ISIN of interne code) |
| Fund Name i | investment.investmentDetails | description | De naam van de belegging / de officiële naam van het fonds / van het instrument |
| Local Price i,j, k | investment.investmentDetails | currencyType | Valuta van het instrument |
| Identifier | investment.investmentDetails | refKey | Identifier (bijvoorbeeld ISIN of interne code) |
| Fund Name i | investment.investmentDetails | description | De naam van de belegging / de officiële naam van het fonds / van het instrument |
| Local Price i,j, k | investment.investmentDetails | currencyType | Valuta van het instrument |
| Total holdings i,j, k | investment.investmentDetails | numberOfHoldings | Aantal holdings per instrument per regeling per beleggingsportefeuille |
| Local Price i,j, k | investment.investmentDetails | localPrice | Prijs per instrument in originele valuta per regeling per beleggingsportefeuille |
| Local Value instrument i,j, k | investment.investmentDetails | localValueAmount | Totale marktwaarde in originele valuta per instrument per regeling per beleggingsportefeuille[1] |
| Result i,j, k[1] | investment.investmentDetails | result | Ongerealiseerd resultaat per instrument per regeling per beleggingsportefeuille |
| Accrued Interest i,j, k | investment.investmentDetails | accruedInterest | Opgelopen rente per instrument per regeling per beleggingsportefeuille |
| Portfolio weight i,j, k | investment.investmentDetails | poolPercentage | Gewicht in de portefeuille per instrument per regeling per beleggingsportefeuille[2] |
| FX rate i,j, k | investment.investmentDetails | currencyExchangeRate | FX rates per instrument per regeling per beleggingsportefeuille / koers per positionDate |
| Trade date / Transaction date | financialTransaction.trade | tradeDate | Gewenste handelsdatum |
| Adj Trade i, j | financialTransaction.trade | adjustmentIndicator | Aangepaste trade instructie |
| Buy/Sell i,j | financialTransaction.trade | buySellId | Aan- verkoop- switchindicator |
| Amount | financialTransaction.trade | tradeAmount | Bedrag van de aankoop in de valuta waarin de belegging luidt |
| Amount | financialTransaction.trade | tradeAmount | Bedrag van de aankoop in de valuta waarin de belegging luidt |
| Quantity | financialTransaction.trade | tradeQuantity | Aantal te verhandelen stukken (units) van de transactie |
| Quantity | financialTransaction.trade | tradeQuantity | Aantal te verhandelen stukken (units) van de transactie |
| Price i,j | financialTransaction.trade | tradePrice | Aankoopprijs / koers |
| Switch type | financialTransaction.trade | switchType | Type switch; one-day of sequential |
| Counterparty i,j | financialTransaction.trade | counterparty | Transfer Agent; de partij die de aankoop/verkoop verricht |
| Broker i,j | financialTransaction.trade | broker | Effectenmakelaar die beleggingsorders uitvoert namens klanten op de markt |
| Interest i,j | financialTransaction.trade | interest | Bedrag aan van toepassing zijnde rente |
| Commission i, j | financialTransaction.trade | commissionAmount | Vergoeding voor het uitvoeren van de transactie |
| Clearing broker i,j | financialTransaction.trade | clearingBroker | Effectenmakelaar verantwoordelijk administratieve en financiële afwikkeling van de transactie |
| Cash account i,j | financialTransaction.trade | clearingbrokerCashAccount | Geldrekening (IBAN) bij de clearingbroker op naam van de Pensioenuitvoerder |

[1](#sdfootnote1anc) LET OP: het SPR gegevensmodel, wat feitelijk een decompositiemodel is, kan ook voor de gegevensuitwisseling van FPR worden gebruikt. Dit ligt voor de hand als de uitvoering van een FPR-regeling niet unitised is maar ook is terug te voeren op rendementsdecompositie.

[2](#sdfootnote2anc) (Pensionfund ID) en de andere attribuutnamen volgen de functionele attribuutnaamgeving uit het consultatierapport. De AFD 2.0 technische benaming is anders. In de bijlage 10.6 is een vertaaltabel opgenomen.

[3](#sdfootnote3anc) Cohorten kunnen ook gebaseerd zijn op een ander uitgangspunt zoals bijvoorbeeld geboortejaren, status (Actief/Slaper/Arbeidsongeschikt/Uitkerend), maar ook reserves zoals de solidariteitsreserve (deze kunnen volgens de Memorie van Toelichting als apart leeftijdscohort worden gezien)

[4](#sdfootnote4anc) Bijvoorbeeld als de afwijking tussen de portefeuille en de beoogde collectieve blootstelling naar overrendement te groot wordt.

[5](#sdfootnote5anc) Bijvoorbeeld kan binnen cohortenpool A de (strategische) verdeling van de beleggingen 30% beleggingspool I en 70% beleggingspool II zijn. Bij cohortenpool B kan verdeling 40 : 60 zijn.

[6](#sdfootnote6anc)In bijlage 10.3 "Proces flow & data-uitwisseling FPR" zijn de proces flow schema's in een groter formaat opgenomen.

[7](#sdfootnote7anc) Reconciliatie tussen fiduciair manager en de beleggingsadministrateur is niet in scope voor de gegevensuitwisseling maar de reconciliatie tussen administrateur cohortenpools en beleggingspools, de fiduciair manager en de beleggingsadministrateur is in scope voor de gegevensuitwisseling.