---
title: Opmerkingen bij de nieuwste release
description: Meer informatie over de nieuwste opmerkingen bij de release, nieuwe functies en nieuwe documentatie voor [!DNL Experience Cloud] producten en diensten. Nieuwe Help en zelfstudies vinden over [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], en [!DNL Document Cloud].
doc-type: release notes
last-update: June 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: fbe6dd6b917a94fa8c26f832f373584becd6796a
workflow-type: tm+mt
source-wordcount: '4684'
ht-degree: 8%

---

# Adobe Experience Cloud-releaseopmerkingen - juni 2022

![Banner](assets/experience-cloud-banner-3.png)

Als Ervaar, begint uw weg aan succes met [Experience League](https://experienceleague.adobe.com/?lang=en#home). Zoek naar een uitgebreide &#39;Hoe kan ik&#39;-documentatiebibliotheek, zelfgeleide zelfstudies, &#39;Hoe kan ik&#39;-video&#39;s en cursussen voor alle niveaus en rollen, een online gemeenschap van peers en een expert support wanneer u deze nodig hebt.

>[!NOTE]
>
>Als u maandelijks een bericht wilt ontvangen over updates van deze pagina, meldt u zich aan bij de [Adobe Priority-productupdate](https://www.adobe.com/subscription/priority-product-update.html). Vaak terugkijken om boven op wat er op het Experience League gebeurt te blijven.

Laatste update: **12 juni 2022**

* [[!DNL Experience League] events](#events)
* [[!DNL Adobe System Status]](#status)
* [Experience Cloud - centrale interfacecomponenten &amp; beheer](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cja)
* [[!DNL Streaming Media Analytics]](#sma)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Experience Manager Guides]](#xml-doc)
* [[!DNL Adobe Commerce]](#commerce)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprints - zelfstudies](#blueprints)

Hulp nodig? Bezoek [Experience League](https://experienceleague.adobe.com/#home) voor product en technische documentatie, cursussen met Adobe-cursus, videozelfstudies, snelle antwoorden, inzicht in de gemeenschap en training onder leiding van instructeurs.

## ![Pictogram](/assets/experience-league.png) [!DNL Experience League] gebeurtenissen {#events}

[Gebeurtenissen van Experience League](https://experienceleague.adobe.com/events/?lang=en) zijn een geweldige plek om te leren, te interageren en antwoorden te krijgen van productexperts bij Adobe!

Bijgewerkt op **10 juni 2022**

| Gebeurtenis | Type | Beschrijving |
| -----------|---------- | ----|
| Adobe Campaign, Journey Optimizer - [De uitdaging voor meerdere kanalen: Personalisatie op schaal](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) | Virtuele gebeurtenis | Hoort van Sheryl Kingstone, Research Director op 451 Research, over het bijhouden van het tempo van de verandering, het gebruiken van marketing technologie als kritieke enabler, en het worden van meer gegeven-gedreven. We gaan ook terug op belangrijke sessies en tips en trucs die tijdens Adobe Summit 2022 worden gedeeld, waar u van experts hoort hoe u personalisatie via verschillende kanalen kunt stimuleren.<br>**Datum:** 14 juni - [Details en registratie](https://adobe-campaign-cross-channel.dxfieldmarketing.adobeevents.com/) |
| [Onder de kap zoeken - Cloud Manager 2022](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) | AEM Gems - Virtuele gebeurtenis | Ontdek de nieuwe functies die vorig jaar zijn gepubliceerd, een update van de ontwikkelingen achter de schermen en kijk uit naar de rest van 2022. <br>**Datum:** 15 juni -[Details en registratie](https://aem-augs.adobe.com/events/details/adobe-experience-manager-aem-learning-chapter-presents-aem-gems-looking-under-the-hood-cloud-manager-2022/) |
| [Hoe te om Vertrouwen te bouwen en Gevolgen mee te delen om Uw Digitale Strategie te schrapen](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) | Stramienen rondetafel | Sluit u aan bij ons voor een exclusieve en intieme conversatie, waar we manieren bespreken om de impact van uw digitale strategie effectief te communiceren. <br>**Datum:** 21 juni - [Details en registratie](https://mastersroundtablemay2022.experienceleague.adobeevents.com/) |
| [Experience Makers Live](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) | Video- en virtuele gebeurtenissen | Game-veranderende klantervaringen en digitale transformaties met kaak zijn wat de Adobe Experience Maker Awards van 2022 vieren. <br>Deelnemen aan de gala voor Amerika, Japan, India, Australië en Nieuw-Zeeland op **22 juni**<br> Meld u aan voor Europa, het Midden-Oosten en Afrika op **23 juni** <br> [Details en registratie](https://business.adobe.com/events/experience-makers-live/experience-makers-award-winners.html?sdid=JQVGW4SX&amp;mv=email&amp;mv2=sponsored) |
| [Vraag het de experts - Real-Time CDP Connections](https://www.youtube.com/watch?v=hVwtxDYvzw4) | Experience League LIVE | Onze favoriete Adobe-experts zullen een uitgebreid overzicht geven van het product Adobe Connections, waar klanten gebeurtenissen kunnen doorsturen naar elke bestemming met behulp van een server-side tagbeheersysteem.<br>**Datum:** 23 juni om 9.00 uur - [Details](https://www.youtube.com/watch?v=hVwtxDYvzw4) |
| [Vraag het de experts: De grondbeginselen van Web SDK](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-05-26-22.html) | Experience League LIVE | Tips en trucs voor het verzamelen van gegevens. <br>[Gebeurtenissen plannen en verleden](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=en) |
| [De Uitwisseling van de Vaardigheid](https://experienceleague.adobe.com/docs/skill-exchange-events/events/overview.html?lang=en) | Opgenomen sessies | Bezoek de Uitwisseling van de Vaardigheid om onze globale reeks virtuele klanten het leren gebeurtenissen te bekijken, die zich op het divers in de oplossingen van Adobe Experience Cloud concentreren. |
| [Experience Makers Government Forum](https://adobegovforum.govexec.com/agenda/) | Video op aanvraag | Het 13e jaarlijkse AEMGF op 10 mei was een succes, met een combinatie van virtuele en persoonlijke deelnemers. Vergaderingen voor beheer en brainstormsessies die zijn toegespitst op het thema van _Digitale ervaringen die mensen op de eerste plaats zetten_. Meest gebruikte sessies _Manhunters: Hoe we Pablo Escobar hebben afgenomen_, _De toekomst van CX_, en _De gouden eeuw van de creativiteit en de moderne werkplek_. |
| [Adobe [!DNL Developers Live]: Handel](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2022/feb2022/overview.html?lang=en) | Video&#39;s op aanvraag | _Adobe Developers Live: Handel 2022_ ontwikkelaars en ervaringsontwikkelaars met verschillende achtergronden en een speciaal doel samenbrengen - om ongelooflijke end-to-end ervaringen te creëren. Deze virtuele conferentie van één dag kenmerkt belangrijke updates van de Handel en van de Ontwikkelaar Open Bron, technische zittingen, van het communautaire voorzien van een netwerkkansen en meer. |
| [Marketo Skill Exchange](https://experienceleague.adobe.com/docs/skill-exchange-events/events/marketo/aug2021/marketo-roadmap.html?lang=en) | Video&#39;s op aanvraag | Lees meer over het belang van je Marketo-routekaart en hoe je slechte planning kunt voorkomen. Vraag advies over het ontsluiten van het potentieel van Aangepaste velden voor programmaleden, tips en trucs voor Marketo Engage en nog veel meer in de [!DNL Marketo] Skill Exchange vanaf augustus 2021, nu op Experience League. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval, verstoring en onderhoudsgebeurtenissen van Adobe-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Voor de recentste versieinformatie, zie de Status van het Systeem van Adobe [releaseopmerkingen](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud - centrale interfacecomponenten &amp; beheer {#ecloud}

Experience Cloud [centrale UI-componenten](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) bevat functies die beschikbaar zijn op de homepage en de permanente productkoptekst. Deze functies zijn onder andere instellingen voor gebruikersprofielen, voorkeuren en zoekopdrachten. U kunt ook hulp vinden bij gebruikers- en productbeheer, klantkenmerken en Experience Cloud-soorten publiek.

Geplande release: **11 juli 2022**

| Functie | Beschrijving |
| ------- | ------- |
| Unified Home - Quick Access-widget | **Navigeren sneller:** U kunt uw thuiservaring nu verder aanpassen en bepalen welke toepassingen binnen handbereik zijn. Met de nieuwe functie voor vastzetten kunt u selecteren welke toepassingen op de voorgrond en in het midden van uw [!UICONTROL Quick Access]. <br>**Blijf op de hoogte met slim vastzetten:** Uw nieuwe toepassingen zijn nu gemakkelijker te vinden. Nieuw toegewezen toepassingen weergeven als _Nieuw_ badge en automatisch vastzetten op [!UICONTROL Quick Access]. |

{style=&quot;table-layout:auto&quot;}

**Meer Help-bronnen op [!DNL Experience Cloud Central UI Components] &amp; Beheer**

* [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) voor Experience Cloud Central UI-componenten
* [Gebruiker- en productbeheer](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) voor Experience Cloud (toediening)
* Plaatsingsservice [releaseopmerkingen](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Productdocumentatie voor [Personen - Klantkenmerken en Audience Library](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)
* [Unified Search voor objecten en entiteiten](https://experienceleague.adobe.com/docs/core-services/interface/services/search-experience-cloud.html?lang=en)

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe [!DNL Experience Platform] {#platform}

Laatste releasegegevens en nieuwe documentatie voor [!DNL Experience Platform] en [!UICONTROL Mobile SDK]:

Geplande release: **22 juni 2022**

* [Releaseopmerkingen bij Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)

### Nieuw [!DNL Experience Platform] zelfstudies en cursussen {#tutorials-platform}

Nieuwe videozelfstudies, artikelen en cursussen gepubliceerd voor [!DNL Experience Platform].

| Gepubliceerd | Naam | Type | Beschrijving | Toepassing |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juni 2022 | [Aan de slag met Real-time CDP voor beheerders](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2022.1.rtcdp) | Cursus | Ontvang een inleiding aan de admin taken u moet doen om te beginnen met [!DNL Real-time Customer Data Platform]. Leer over gebruikersbeheer en hoe te opstellingsverbindingen met andere partners en systemen. | [!DNL Real-time CDP] |
| Juni 2022 | [Het succes van de segmentactivering volgen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-the-success-of-segment-activation.html?lang=en) | Video | Leer twee belangrijke manieren om de stroom van uw segmenten uit aan bestemmingen te controleren. Wanneer het verzenden van segmentprofielen naar uw activeringspartners, is het noodzakelijk om informatie betreffende het succes van deze gegevensoverdracht te zien, vooral zodat kunt u problemen bevestigen. | [!DNL Real-time CDP] |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Zie [Opmerkingen bij de release en logbestanden wijzigen](https://aep-sdks.gitbook.io/docs/release-notes) voor de Adobe Experience Platform Mobile SDK&#39;s.

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Volgende release: **15 juni 2022**

Laatste update: **8 juni 2022**

* Adobe Analytics [releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en)
* Adobe Analytics [productdocumentatie en zelfstudies](https://experienceleague.adobe.com/docs/analytics.html)

### AppMeasurement {#appm}

Releaseversie: **2.22.4.**

* [AppMeasurement voor JavaScript-releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### Nieuw [!DNL Analytics] zelfstudies en cursussen {#tutorials-analytics}

Nieuwe videozelfstudies, artikelen en cursussen gepubliceerd voor Adobe Analytics.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juni 2022 | [Adobe Analytics-gegevens exporteren en democratiseren](https://experienceleague.adobe.com/docs/courses/using/analytics-a-1-2022-1-democratizing.html?lang=en) | Cursus | Leer meer over de functies in Adobe Analytics die u ondersteunen bij het democratiseren van uw digitale gegevens. De democratisering van gegevens is het proces om knelpunten weg te nemen en zeer belangrijke mensen in uw organisatie toe te laten om met gegevens comfortabel te werken zodat zij gegevens-geïnformeerde besluiten kunnen nemen. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Laatste update: **19 mei 2022**

* Customer Journey Analytics [releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)
* Customer Journey Analytics [productdocumentatie en zelfstudies](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### Nieuwe zelfstudies en cursussen voor Customer Journey Analytics {#tutorials-cja}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor CJA.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juni 2022 | [Dimension in gegevensweergaven binden](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/binding-dimensions-in-data-views.html?lang=en) | Video | Leer over het binden van dimensies. Deze functie biedt u de mogelijkheid om één dimensie te gebruiken en deze aan een andere dimensie te koppelen voor een verfijnde persistentietoewijzing. |
| Juni 2022 | [Customer Journey Analytics-landingspagina](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/cja-basics/customer-journey-analytics-landing-page.html) | Video | De landingspagina voor Customer Journey Analytics is voorzien van een standaardweergave van uw projecten en mobiele scorecards en een leergedeelte om u te helpen effectiever aan de slag te gaan. |
| Juni 2022 | [Adobe Analytics-gegevens samenstellen, toewijzen en transformeren](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-prep/ingest-map-and-transform-adobe-analytics-data.html) | Video | Meer informatie over het gebruik van functies voor gegevensvoorvertoningen voor [!DNL Analytics] gegevens, met inbegrip van gegevensmanipulatiefuncties. U kunt bijvoorbeeld analytische variabelen toewijzen aan nieuwe aangepaste velden en transformaties en berekeningen uitvoeren. |
| Juni 2022 | [Componentinstellingen voor subtekenreeksen configureren](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/data-views/configure-substring-component-settings.html) | Video | Leer om koordmanipulatiemethodes te gebruiken om het gewenste gedeelte van afmetingswaarden in rapporten van de Customer Journey Analytics te verkrijgen. Na toepassing vindt de gegevenstransformatie met terugwerkende kracht en onmiddellijk plaats. |
| Juni 2022 | [Een mobiele scorecard maken](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/create-scorecard.html) | Video | Leer hoe u dashboards kunt configureren en presenteren voor uitvoerende gebruikers. |
| Juni 2022 | [Verbindingen maken en bewerken](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/connections/cja-connections-creation-and-edit-experience.html) | Video | Leer hoe te om het rollen venster van het gegevensbehoud toe te laten, om backfill gegevens toe te laten en te verzoeken die op gebeurtenissen timestamp worden gebaseerd, en bestaande gegevens door dataset in te voeren. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Laatste update: **23 maart 2022**

* [!DNL Streaming Media Analytics][Aanvullende informatie voor ](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en)
* [!DNL Streaming Media Analytics] [productdocumentatie en zelfstudies](https://experienceleague.adobe.com/docs/media-analytics/using/media-overview.html?lang=en)

## ![Pictogram](/assets/audience-manager.png) Audience Manager {#aam}

Oplossingen en verbeteringen in de Audience Manager:

| Verbetering | Beschrijving |
| -----------| ---------- |  
| Validator voor doelgegevensbronnen van andere ondernemingen | Audience Manager heeft een verbetering van de [batchgegevens aan boord](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/batch-data-transfer-overview.html?lang=en). Om toevallig dossier en gegevens te verhinderen in doelgegevensbronnen die door andere partners worden bezeten, heeft de Audience Manager een kaartvereiste tussen partner identiteitskaart (PID) en de gegevensbronnen (DPID) toegevoegd die door andere partners worden bezeten. <ul><li>Zie ook de __DPID_TARGET_DATA_OWNER_ veld in [Amazon S3-vereisten voor naam en bestandsgrootte voor binnenkomende gegevensbestanden](https://experienceleague.adobe.com/docs/audience-manager/user-guide/implementation-integration-guides/sending-audience-data/batch-data-transfer-process/inbound-s3-filenames.html?lang=en#name-elements).</li><li>Adobe-interne consultants en de klantenservice moeten [Toegang aan boord beheren voor gegevens van een tweede partij](https://experienceleague.adobe.com/docs/audience-manager-admin/admin-guide/companies/admin-manage-onboarding-access.html?lang=en) voor informatie over de nieuwe toewijzing moeten verbeteringen worden aangebracht en moet worden aangegeven hoe een nieuwe toewijzing moet worden aangevraagd</li><li>Het is _niet_ vereist om een afbeelding aan te vragen voor bestaande relaties voor het delen van gegevens. De toewijzing is ook _niet_ vereist wanneer het aan boord gaan van gegevens in doelgegevensbronnen die tot uw PID behoren.</li></ul> |

{style=&quot;table-layout:auto&quot;}

Voor hulpmiddelen voor zelfhulp raadpleegt u [Documentatie en zelfstudies voor Audience Managers](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) op Experience League.

## ![Pictogram](/assets/aem.png) Adobe Experience Manager {#aem}

Nieuwe functies, correcties en updates in Experience Manager. Adobe raadt klanten met On-Premise-implementaties aan de nieuwste patches te implementeren om een hogere stabiliteit, beveiliging en prestaties te garanderen.

Adobe raadt u aan de [Updates van de release van Experience Managers en routekaarten](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) pagina om actueel te blijven bij releasegegevens.

### Productupdates Experience Manager

* **Experience Manager as a Cloud Service**

   Kijk naar de [Video over het overzicht van de release van mei 2022](https://video.tv.adobe.com/v/343321/?quality=12) voor een overzicht van de functies die in de release van 2022.5.0 (mei 2022) zijn toegevoegd. <!-- Beginning with the video this month, Adobe has enabled localized closed captioning in French (FR), German (DE) and Japanese (JP). -->

   * [Video over het overzicht van de release van april 2022](https://video.tv.adobe.com/v/342612?quality=12)
   * [Video over het overzicht van de release van maart 2022](https://video.tv.adobe.com/v/341465).
   * [Video over Overzicht release januari 2022](https://video.tv.adobe.com/v/340120).
   * [Video over het overzicht van de release van december 2021](https://video.tv.adobe.com/v/339278).
   * [Video over het overzicht van de release van oktober 2021](https://video.tv.adobe.com/v/338253).
   * [Video over het overzicht van de release van september 2021](https://video.tv.adobe.com/v/337381).

* **Experience Manager Sites as a Cloud Service**

   _Nieuwe functie in prereleasekanaal_

   * Verschillende GraphQL-functies.
   * A [nieuwe console](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/headless/content-fragments/content-fragment-console.html?lang=en) geoptimaliseerd voor headless gebruik van inhoudsfragmenten.

* **Experience Manager Assets as a Cloud Service**

   _Nieuwe functies_

   * [Dynamic Media Smart Imaging ondersteunt nu de AVIF-bestandsindeling](https://medium.com/adobetech/one-solution-fits-all-smart-imaging-with-aem-dynamic-media-be690b62df9f) - verder verbeteren van Google Core Web Vital (Grootste inhoudelijke verf), waarbij AVIF een extra reductie van 20% biedt ten opzichte van WebP. In totaal kan AVIF tot 41% reductie van gemiddelde grootte bieden in vergelijking met JPEG (in sommige afbeeldingen zelfs tot 76%).
   * Experience Manager Assets Brand Portal voert nu elke 12 uur automatische taken uit om alle Brand Portal-middelen te verwijderen die naar Experience Manager worden gepubliceerd. U hoeft daarom de middelen in de map Contribution niet handmatig te verwijderen om de mapgrootte onder de drempelwaarde te houden. Zie [Nieuw in Experience Manager Assets Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/whats-new.html?lang=en).

   _Nieuwe functie in prereleasekanaal_

   * Experience Manager Assets gebruikt tot nu toe Adobe Sensei AI-mogelijkheden [onderscheid maken tussen kleuren in een afbeelding en verschillen automatisch toepassen als tags bij inname](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en). Deze tags maken een verbeterde zoekervaring mogelijk op basis van de compositie van de afbeeldingskleur. U kunt het aantal kleuren binnen een bereik van 1 tot 40 configureren dat aan een afbeelding is gelabeld, zodat u later kunt zoeken naar afbeeldingen op basis van die kleuren.


* **Experience Manager Forms as a Cloud Service**

   _Nieuwe functies in prereleasekanaal_

   * **Adaptieve Forms integreren met Microsoft® Power Automate** - U kunt nu een adaptief formulier configureren om bij verzending een Microsoft® Power Automate Cloud Flow uit te voeren. Met het geconfigureerde adaptieve formulier worden vastgelegde gegevens, bijlagen en het document met records naar Power Automate Cloud Flow verzonden voor verwerking. Het helpt u om een aangepaste ervaring op het gebied van gegevensvastlegging op te bouwen en tegelijk de kracht van Microsoft® Power Automate te benutten om bedrijfslogics rond vastgelegde gegevens te bouwen en de workflows van klanten te automatiseren.
   * **Wizard voor het maken van een adaptief formulier** - U kunt een gebruiksvriendelijke wizard gebruiken om Adaptive Forms snel te ontwerpen. De wizard biedt een snelle tabnavigatie waarmee u eenvoudig vooraf geconfigureerde sjablonen, stijlen, velden en verzendopties kunt selecteren om een adaptief formulier te maken.

* **Experience Manager as a Cloud Service Stichting**

   _Nieuwe functies_

   * De **[!UICONTROL Add tree]** optie onder het beheerscherm van de replicatieagent **[!UICONTROL Distribute]** tabblad, dat eerder als afgekeurd werd aangekondigd, wordt verwijderd op 20 juni 2022 of kort daarna. Pakketten met een boomstructuur van inhoud moeten in plaats daarvan worden gerepliceerd met [Publicatie beheren](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) of de [Workflow Inhoudsstructuur publiceren](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow).
   * Het gebruik van de API voor beheer van replicatieagent voor het distribueren van inhoudspakketten groter dan 10 MB (knooppunten met eigenschappen, exclusief binaire getallen) is afgekeurd en wordt afgedwongen op 12 september 2022 of kort daarna. In plaats daarvan, [Publicatie beheren](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#manage-publication) of de [Workflow Inhoudsstructuur publiceren](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/replication.html?lang=en#publish-content-tree-workflow) moeten worden gebruikt om deze grote inhoudspakketten te repliceren. In juli 2022 wordt een waarschuwingsbericht weergegeven in het beheerscherm van de replicatieagent **[!UICONTROL Distribute]** tab. Het lijkt als u probeert om deze grote inhoudspakketten en ook in het foutenlogboek van de Experience Manager te herhalen wanneer de replicatie API wordt gebruikt om deze grote inhoudspakketten te herhalen. In september worden waarschuwingen vervangen door fouten. Adobe raadt u aan uw processen dienovereenkomstig aan te passen.

   _Nieuwe functie in prereleasekanaal_

   * as a Cloud Service Experience Manager is nu geïntegreerd met Verenigde Shell om de gebruikerservaring te verbeteren en het met alle andere toepassingen van Experience Cloud te verenigen. Zie [Experience Manager as a Cloud Service op Verenigde Shell](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/overview/aem-cloud-service-on-unified-shell.html?lang=en) voor meer informatie .


* **Experience Manager as a Cloud Service Stichting Veiligheid**

   * **Afschrijving van TLS 1.0 en TLS 1.1** - Vanaf 30 juni 2022 is voor as a Cloud Service Experience Manager een veiligere netwerkcommunicatie en gegevensuitwisseling met gebruikerssystemen vereist. Experience Manager zal uitsluitend TLS (de Veiligheid van de Laag van het Vervoer) 1.2 protocol gebruiken. TLS 1.0 en 1.1 worden afgekeurd.

      Als u TLS 1.0 of TLS 1.1 blijft gebruiken, kan de toegang tot as a Cloud Service Experience Manager verloren gaan.

### Community

* Afspelen [Video over update van Experience Manager as a Cloud Service 2022.5.0-release](https://adobe.ly/3NDPR8Y) dat geldt voor wat er is vrijgelaten . (10 minuten)
* GEM&#39;s Webinar - _Onder de kap kijken: Cloud Manager 2022_
   * Woensdag 15 juni 2022
   * 08:00 Pacific Time; 17:00 Midden-Europese Tijd; 20:30 India Standard Time
   * [Hier registreren](https://adobe.ly/3t4jfgp).
   * [Discussielijn](https://adobe.ly/3O0rdzd).

### Nieuwe cursussen en tutorials voor Experience Manager {#tutorials-aem}

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving | Toepassingen |
| -----------| ---------- | ---------- | ---------- | ------|
| Juni 2022 | [[!DNL Forms] Poortonderdelen](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/forms-portal-components.html?lang=en) | Video | Leer hoe u kunt inschakelen [!DNL AEM Forms] [!UICONTROL Portal] in Forms Cloud Service. | AEM Forms CS |
| Juni 2022 | [Integreer AEM en CIF kader om een rijke en immersive e-commerce ervaring te bouwen](https://experienceleague.adobe.com/docs/experience-manager-gems-events/gems/gems2022/aem-and-cif-framework-integration.html?lang=en) | Video | Begrijp hoe het kader van CIF van Adobe kan worden gebruikt om een verenigbare, tevreden-rijke en diepgaande handelservaring te bouwen. | AEM en CIF-framework |
| Juni 2022 | [SAML 2.0-verificatie](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/authentication/saml-2-0.html) | Video | Leer hoe u eindgebruikers (niet AEM auteurs) instelt en verifieert voor een compatibele IDP voor SAML 2.0 van uw keuze. | AEM CS |
| Juni 2022 | [Contextbewuste cloudconfiguraties](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/context-aware-fdm.html?lang=en) | Video | Leer hoe u contextbewuste cloudconfiguraties definieert in AEM Forms op Cloud Service. | AEM Forms |

{style=&quot;table-layout:auto&quot;}

### Experience Manager-releasegegevens

Alle Experience Manager-releaseopmerkingen worden op de volgende pagina&#39;s bijgehouden:

* [Informatie over as a Cloud Service release van Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Opmerkingen bij de release Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Releaseopmerkingen bij de service Geautomatiseerde conversie van formulieren](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Opmerkingen bij de release Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=en)
* [Experience Manager 6.4 Opmerkingen bij de release Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* [Opmerkingen bij de release Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* [Opmerkingen bij de release Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Opmerkingen bij de release van Experience Manager-bureaublad](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* [Opmerkingen bij de release Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Releaseopmerkingen bij Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Releaseopmerkingen bij Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### Overige Help-bronnen voor Experience Manager

* [Handleidingen voor Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=en)
* [Gebruikershandleiding voor Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [Experience Manager 6.5 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 - Introductiepagina](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 Thuis leren &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Oudere versies van de Documentatie van de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic Help-startpagina](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Documentatie Experience Manager: Recente updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Pictogram](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] (voorheen, [!DNL XML Documentation for Experience Manager]) is een toepassing die op AEM wordt geïmplementeerd. Het is een krachtige oplossing voor componentcontentbeheer op bedrijfsniveau (CCMS) die native DITA-ondersteuning in Adobe Experience Manager mogelijk maakt en AEM in staat stelt om op DITA gebaseerde content creation en delivery af te handelen.

Meer informatie over [[!DNL Experience Manager Guides]](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html).

### Aanvullende bronnen

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=en) - zelfstudies over Experience League
* [[!DNL Experience Manager Guides] Meer informatie en ondersteuning](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - productdocumentatie

## ![Pictogram](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Raadpleeg de volgende koppelingen voor Adobe Commerce-releaseopmerkingen:

* [Opmerkingen bij de release Adobe Commerce en Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Opmerkingen bij de release Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nieuwe Adobe Commerce-zelfstudies en documentatie {#tutorials-commerce}

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juni 2022 | [Aan de slag met MBI](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/getting-started.html?lang=en) | Video | Leer rechtstreeks over de kernfunctionaliteit van MBI van het team van het Product van de Handel met een diepe duik in pre-gevormde dashboards en beschikbare aanpassingsopties. |
| Juni 2022 | [Gegevenssets beheren in MBI](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/manage-data-sets.html?lang=en) | Video | Of u nu beschikt over de krachtige functies van MBI Data Warehouse Manager, rechtstreeks bij het Adobe Commerce Product-team. Ga verder dan het samenstellen van basisrapporten en leer hoe u meer kunt doen met uw gegevens. |
| Juni 2022 | [Uw MBI-Data Warehouse optimaliseren](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/optimize-data-warehouse.html?lang=en) | Video | Leer hoe te om lijst en kolomsync montages te beheren, boor neer in het schema van een lijst, en creeer berekende kolommen in rapporten te gebruiken. |
| Juni 2022 | [Gereedheid voor feestdagen met MBI](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/holiday-readiness.html?lang=en) | Video | Leer veelgebruikte seizoensanalyses, gebruik gevallen en methoden om deze aan te pakken met behulp van belangrijke MBI-functies. |
| Juni 2022 | [MBI - Vraag het een expert](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/mbi/webinars/ask-expert.html?lang=en) | Video | In dit tweedelige webinar, leer wat de klanten over Business Intelligence zeggen. Leer bedrijfstransformatie door Business Intelligence, SQL optimalisering gebruikend gemeenschappelijke lijstuitdrukkingen, en veel meer. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/target.png) [!DNL Adobe Target] {#target}

Laatst bijgewerkt: **7 juni 2022**

* Voor informatie over de release raadpleegt u [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en)
* Zie voor actuele informatie [Opmerkingen bij de release van Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

### Nieuwe cursussen en zelfstudies voor Adobe Target {#tutorials-target}

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juni 2022 | [linktext](https://experienceleague.adobe.com/?recommended=Target-D-1-2021.1) | Cursus | Leer hoe u Adobe Target op uw website kunt implementeren. Beginnend met administratieve onderwerpen, met inbegrip van vereisten en gebruikerstoestemmingen, behandelt de cursus dan implementatiemethodes, overwegingen, en beste praktijken. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwste productreleases van campagne

* Nieuw [Release van campagne v8.3](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/release-notes.html)
* Nieuw [release van Campaign Standard 22.2](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)
* Nieuw [Het bedieningspaneel kan worden losgelaten](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en#may-2022)
* Nieuw [zelfstudies en cursussen](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) over Experience League

### Nieuw [!DNL Campaign] zelfstudies en cursussen {#tutorials-campaign}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Adobe Campaign.

| Gepubliceerd | Naam | Type | Beschrijving | Toepassing |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juni 2022 | [Een leveringssjabloon maken](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/sending-messages/using-delivery-templates/configure-a-delivery-template.html) | Video | Leer hoe u een sjabloon voor een ad-hoclevering configureert. | Campaign v8 |
| Juni 2022 | [Herhalende en doorlopende e-mailleveringen maken](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/process-management/recurring-deliveries.html) | Video | Leer hoe te om een terugkomende levering en een planneractiviteit te vormen. | Campagne v8 |
| Juni 2022 | [Verrijkingsactiviteiten configureren](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/enrichment-activity.html) | Video | Leer hoe u een verrijkingsactiviteit kunt configureren op basis van het leveringslogboek. | Campagne v8 |
| Juni 2022 | [Inleiding tot SMS](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/introduction-to-sms.html) | Video | Ontdek wat SMS is, de rol van de SMS-serviceprovider, hoe Adobe Campaign verbinding maakt met de serviceprovider. Begrijp welke informatie door de dienstverlener wordt doorgegeven en welke technische nota&#39;s beschikbaar zijn. | Campagne v8, Campaign Standard, Campaign Classic v7 |
| Juni 2022 | [Een SMS-account instellen voor een standaard SMPP-provider](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/set-up-account-for-standard-smpp-provider.html?lang=en) | Video | Leer hoe u een SMPP-account instelt bij Adobe Campaign, hoe u de resultaten van de SMS-levering analyseert en de SR-verwerking aanpast aan de specificaties van uw SMPP-provider. | Campagne v8, Campaign Classic v7 |
| Juni 2022 | [Pas de SMS-aansluiting aan op uw SMPP-provider](https://experienceleague.adobe.com/docs/campaign-learn/set-up-sms-for-adobe-campaign/adapt-sms-connector-to-smpp-provider.html) | Video | Leer hoe u de SMS-connector aanpast aan uw SMPP-provider. Pas uw SMS-instellingen aan om verbindingsgrenzen af te handelen, stel de maximale doorvoer, het verzendende venster en codering in met TLS. | Campagne v8, Campaign Classic v7, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Help-informatie en bronnen voor Campaign

* Adobe Campaign v8: [Documentatie](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Implementatiehulplijnen](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard Documentatie](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=nl) - [Release-planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7-documentatie](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=nl) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl) - [Releaseopmerkingen](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=nl) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=nl)

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Met Journey Optimizer, kunt u geplande omnichannel campagnes en één-aan-één momenten voor miljoenen klanten van één enkele toepassing-en de volledige reis wordt geoptimaliseerd met intelligente besluiten en inzichten.

### Nieuwste Journey Optimizer-productreleases

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen in de [Opmerkingen bij de release van Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

### Meer bronnen voor [!DNL Journey Optimizer]

* [Journey Optimizer-documentatie](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html) - [Geen rotaties](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)
* [Beslissingsbeheerdocumentatie](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management/introduction-to-decision-management.html) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Pictogram](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Het Experience Platform van het gebruik om de reis van een klant bij schaal over ervaringskanalen te ordenen, door intelligent de behoeften van elk individu in echt te voorzien - tijd.

### Laatste [!DNL Journey Orchestration] productreleases

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen in de [[!DNL Journey Orchestration] releaseopmerkingen](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html).

#### Meer bronnen voor [!DNL Journey Orchestration]

* [Journey Orchestration-documentatie](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=html?lang=nl) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![Pictogram](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

[!DNL Marketo Engage] is een volledige toepassing voor het beheer van leads en B2B-marketers die de ervaringen van klanten willen transformeren door in elke fase van complexe inkoopritten mee te werken.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo Engage] [releaseplanning](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) voor de recentste informatie van het versieschema en versienota&#39;s.

## ![Pictogram](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

Adobe [!DNL Workfront] is een uniforme toepassing voor werkbeheer voor het delen van ideeën, het maken van inhoud, het beheren van complexe processen en het uitvoeren van hun beste werk.

Zie de [[!DNL Workfront] lozingen](https://one.workfront.com/s/product-releases) pagina voor een afronding van de meest recente informatie voor alle producten.

## ![Pictogram](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Opmerkingen bij de release voor [!DNL Adobe Advertising Cloud].

<!-- * [New features across [!DNL Advertising Cloud]](#adcloud-all) -->
* [Nieuwe functies in [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nieuwe functies in [!DNL Advertising Cloud Search]](#adcloud-search)
<!-- * [New [!DNL Advertising Cloud] tutorials](#tutorials-ad-cloud) -->

<!--
### New features across [!DNL Advertising Cloud] {#adcloud-all}

Last updated: **October 27, 2021**

| Feature | Description |
| ------- | ----------- |
| Analytics for Advertising Cloud | If your organization wants to switch from using the legacy Adobe Analytics `visitorAPI.js` library to the Adobe Experience Platform library (`alloy.js`) for data collection, you must make changes to enable ID stitching. See [Using the [!DNL Last Event Service] JavaScript Library with Adobe Experience Platform [!DNL Web SDK]](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html). |

-->

### Nieuwe functies in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Laatst bijgewerkt: **8 juni 2022** voor 31 mei

| Functie | Beschrijving |
| ------- | ----------- |
| Aangepaste rapporten | (Beta eigenschap) Advertising Cloud DSP kan nu eerste-partijsegmenten die van voor authentiek verklaarde signalen worden samengesteld binnen een platform van klantengegevens (CDP) worden opgenomen. |

{style=&quot;table-layout:auto&quot;}

### Nieuwe functies in [!DNL Advertising Cloud Search] {#adcloud-search}

Laatst bijgewerkt: **8 juni 2022** voor 11 juni

| Functie | Beschrijving |
| ------- | ----------- |
| [!UICONTROL Insights] | De analyse voor het delen van indrukken is nu weer beschikbaar als bètafunctie. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nieuwe zelfstudies en cursussen voor Adobe Document Cloud.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juni 2022 | [De rol van de gedelegeerde gebruiken](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | Video | Leer om de delegatorrol te gebruiken om een document naar een intermediair te verzenden die dan het document voor handtekening kan leiden. |
| Juni 2022 | [Meldingen voor gebeurtenissen en waarschuwingen configureren](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/set-up-shared-events-and-alert.html?lang=en) | Video | Meer informatie over gedeelde gebeurtenissen en waarschuwingsinstellingen die u kunt configureren in Acrobat Sign. Waarschuwingen zijn acties die niet binnen een bepaalde tijd hebben plaatsgevonden en gebeurtenissen zijn acties die hebben plaatsgevonden. |
| Juni 2022 | [Geavanceerd account delen](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/advanced-tasks-admins/advanced-account-sharing.html?lang=en) | Video | Leer hoe u geavanceerde mogelijkheden voor het delen van accounts instelt, zodat beheerders en gebruikers hun machtigingen voor verzenden, wijzigen en weergeven kunnen delegeren. |

{style=&quot;table-layout:auto&quot;}

Raadpleeg voor hulp bij Documenten Cloud:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud - Meer informatie en ondersteuning](https://helpx.adobe.com/support/document-cloud.html)

## ![Pictogram](/assets/creative-cloud-24.png) Adobe Creative Cloud for enterprise {#creative-cloud}

Zie [Creative Cloud voor zelfstudies voor bedrijven](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) voor de meest recente zelfstudies.

## ![Pictogram](/assets/experience-league.png) Beheer van klantgegevens - Voices {#voices}

[Klantengegevensbeheerstemmen](https://experienceleague.adobe.com/docs/customer-data-management-voices-events/events/overview.html?lang=en) is uw bestemming als technisch en marketing van klantengegevensbeheer leider en specialist. Deze verzameling zelfstudies is uw one-stop-shop om van uw collega&#39;s te horen, geïnspireerd te raken en te leren over de ontwikkelingen in MarTech. Geen registratie vereist, klik en bekijk eenvoudig.

## ![Pictogram](/assets/experience-league.png) Digitale beleving blauwdrukken {#blueprints}

[Digitale beleving blauwdrukken](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) zijn herhaalbare implementaties die u strategie laten behandelen en snel gevestigde bedrijfsproblemen oplossen. Elke blauwdruk verstrekt een reeks artefacten die het high-value bedrijfsprobleem, architectuur, implementatiestappen, technische overwegingen, en verbindingen aan de relevante documentatie verklaren.

[Boven](#events)
