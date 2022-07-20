---
title: Opmerkingen bij de nieuwste release
description: Meer informatie over de nieuwste opmerkingen bij de release, nieuwe functies en nieuwe documentatie voor [!DNL Experience Cloud] producten en diensten. Nieuwe Help en zelfstudies vinden over [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], en [!DNL Document Cloud].
doc-type: release notes
last-update: July 2022
author: mfrei
mini-toc-levels: 2
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: d5e56e4a6877d4930a43407d0d149c3e224a8346
workflow-type: tm+mt
source-wordcount: '5519'
ht-degree: 10%

---

# Opmerkingen bij de release van Adobe Experience Cloud - juli 2022

![Banner](assets/experience-cloud-banner-3.png)

Als Ervaar, begint uw weg aan succes met [Experience League](https://experienceleague.adobe.com/?lang=en#home). Zoek naar een uitgebreide &#39;Hoe kan ik&#39;-documentatiebibliotheek, zelfgeleide zelfstudies, &#39;Hoe kan ik&#39;-video&#39;s en cursussen voor alle niveaus en rollen, een online gemeenschap van peers en een expert support wanneer u deze nodig hebt.

>[!NOTE]
>
>Als u maandelijks een bericht wilt ontvangen over updates van deze pagina, meldt u zich aan bij de [Adobe Priority-productupdate](https://www.adobe.com/subscription/priority-product-update.html). Vaak terugkijken om boven op wat er op het Experience League gebeurt te blijven.

Laatste update: **18 juli 2022**

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

Gebeurtenissen van het Experience League zijn een uitstekende plaats om te leren, interactie aan te gaan en antwoorden van productdeskundigen bij Adobe te krijgen! Zie [Gebeurtenissen](https://experienceleague.adobe.com/events/?lang=en) inzake Experience League dat voor juli 2022 moet worden bijgewerkt.

Bijgewerkt **17 juli 2022**

| Gebeurtenis | Type | Beschrijving |
| -----------|---------- | ----|
| [Vraag het de experts: DataStreams en voorinstelling van gegevens](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) | Experience League LIVE | In deze laatste van drie sessies met betrekking tot gegevensverzameling voor de Adobe Experience Cloud zullen onze experts een diepgaandere analyse geven van de geavanceerde mogelijkheden van Adobe om gegevens te verzamelen, waaronder functies zoals data prep voor gegevensverzameling. Aan het einde van deze sessie zullen de deelnemers vertrouwen hebben in de nieuwste en krachtigste functies voor het verzamelen van gegevens uit digitale ervaringen <br>**Datum:** 21 juli @ 9.00 uur PDT - [Details](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-07-21-22.html?lang=en) |

{style=&quot;table-layout:auto&quot;}

Zie [Gebeurtenissen](https://experienceleague.adobe.com/events/?lang=en) over Experience League om op de hoogte te blijven van komende gebeurtenissen en eerdere episodes.

## ![Pictogram](/assets/system-status.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval, verstoring en onderhoudsgebeurtenissen van Adobe-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Voor de recentste versieinformatie, zie de Status van het Systeem van Adobe [releaseopmerkingen](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2022/02162022.html?lang=en#status).

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud - centrale interfacecomponenten &amp; beheer {#ecloud}

Experience Cloud [centrale UI-componenten](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) bevat functies die beschikbaar zijn op de homepage en de permanente productkoptekst. Deze functies zijn onder andere instellingen voor gebruikersprofielen, voorkeuren en zoekopdrachten. U kunt ook hulp vinden bij gebruikers- en productbeheer, klantkenmerken en Experience Cloud-soorten publiek.

### Provisioning-update

>[!IMPORTANT]
>
>Controleer de volgende kennisgeving met betrekking tot Experience Cloud-provisioning.

Adobe werkt zijn levering bij om alle klanten van de Experience Cloud toegang tot stichtingsmogelijkheden te verlenen die interoperabiliteit tussen sommige producten van Experience Cloud helpen. Gebruikers krijgen Adobe Experience Platform als nieuwe machtiging toegevoegd aan hun Experience Cloud-organisaties, met [!UICONTROL Data Collection] als inbegrepen dienst.

Adobe Experience Platform [!UICONTROL Data Collection] include [tags](https://experienceleague.adobe.com/docs/tags.html?lang=en) voor vereenvoudigd beheer van universele tags en biedt een vertrouwde, robuuste en complete, streaminggegevensinfrastructuur. Tags vereenvoudigen het verzamelen van gegevens door de klant en stroomlijnen de levering van ervaringen.

Met deze update kunnen beheerders wijzigingen of toevoegingen aan de Admin Console zien:

1. De Adobe Experience Platform-productkaart in de Admin Console bevat:

   * Plaatsen
   * Betrouwbaarheid
   * Naamruimte van identiteit
   * Sandboxen
   * Experience Data Model
   * Schema&#39;s
   * DataStreams
   * Bezoekers-id

   Voor organisaties die momenteel geen Experience Platform gebruiken, ziet u nu de _Adobe Experience Platform_ in de Admin Console, met inbegrip van de hierboven vermelde mogelijkheden.

   Voor organisaties die momenteel Experience Platform gebruiken, _Plaatsen_ wordt nu geconsolideerd in de kaart van het Experience Platform.

1. Adobe Experience Platform Data Collection (voorheen, Launch) en Privacy zullen als afzonderlijke productkaarten van de andere mogelijkheden van het Experience Platform blijven verschijnen.

Ga voor meer informatie over de nieuwe mogelijkheden naar de pagina&#39;s op het Experience League:

* [Gegevensverzameling](https://experienceleague.adobe.com/docs/analytics/analyze/reports-analytics/reporting-interface/overview-data-collection.html)
* [Plaatsen](https://experienceleague.adobe.com/docs/places/using/home.html?lang=nl)
* [Betrouwbaarheid](https://experienceleague.adobe.com/docs/platform-learn/implement-mobile-sdk/app-implementation/assurance.html%3Flang%3Dde)
* [Naamruimte van identiteit](https://experienceleague.adobe.com/docs/experience-platform/identity/home.html?lang=en)
* [Sandboxen](https://experienceleague.adobe.com/docs/experience-platform/sandbox/home.html?lang=en)
* [Experience Data Model](https://experienceleague.adobe.com/docs/experience-platform/xdm/home.html?lang=nl)
* [Schema&#39;s](https://experienceleague.adobe.com/docs/experience-platform/xdm/schema/composition.html)
* [DataStreams](https://experienceleague.adobe.com/docs/experience-platform/edge/datastreams/overview.html?lang=en)
* [Bezoekers-id](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services.html?lang=en#section_3C9F6DF37C654D939625BB4D485E4354)
* [Privacy](https://experienceleague.adobe.com/docs/experience-platform/privacy/home.html?lang=en)

Geen: **11 juli 2022**

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

Geplande release: **27 juli 2022**

* [Releaseopmerkingen bij Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html)

### Nieuw [!DNL Experience Platform] zelfstudies en cursussen {#tutorials-platform}

Nieuwe videozelfstudies, artikelen en cursussen gepubliceerd voor [!DNL Experience Platform].

| Gepubliceerd | Naam | Type | Beschrijving | Toepassing |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juli 2022 | [Gebeurtenis controleren door:sturen](https://experienceleague.adobe.com/docs/platform-learn/data-collection/event-forwarding/monitor.html) | Video | Leer hoe te om gebeurtenis te controleren die in de interface van de Inzameling van Gegevens door:sturen. | Gegevensverzameling |
| Juli 2022 | [Gegevens bijhouden](https://experienceleague.adobe.com/docs/platform-learn/tutorials/monitoring/monitoring-dashboard.html) | Video | Leer hoe u gegevens die in Adobe Experience Platform worden ingevoerd, kunt bijhouden en volgen met het dashboard voor bewaking. | Gegevensverzameling |
| Juli 2022 | [Voorbeeldgegevens importeren naar Adobe Experience Platform](https://experienceleague.adobe.com/docs/platform-learn/tutorials/import-sample-data.html) | Artikel | Leer hoe u een Experience Platform-sandboxomgeving instelt met voorbeeldgegevens. Met behulp van een Postman-verzameling kunt u veldgroepen, schema&#39;s, gegevenssets maken en vervolgens voorbeeldgegevens importeren in Experience Platform. | Experience Platform |
| Juli 2022 | [Segmentovereenkomst die gegevens ontvangt](https://experienceleague.adobe.com/docs/platform-learn/tutorials/segments/segment-match-receiving-data.html) | Video | Met de Overeenkomst van het Segment, kunnen de gegevens aan u door uw strategische partners worden gedeeld. In deze video leert u hoe u de gegevens kunt goedkeuren en ontvangen en waar u deze kunt zien en toevoegen aan uw eigen segmenten. | Experience Platform - Segmenten |
| Juli 2022 | [Vraag het de experts: Real-Time CDP-verbindingen](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-06-23-22.html?lang=en) | Experience League LIVE-video | In deze tweede van drie livestreamsessies met betrekking tot gegevensverzameling bieden onze favoriete experts een uitgebreid overzicht van Adobe RTCDP [!UICONTROL Connections], waarbij klanten gebeurtenissen naar niet-Adobe-doelen kunnen doorsturen met behulp van een server-side tagbeheersysteem. | Gegevensverzameling |

{style=&quot;table-layout:auto&quot;}

### [!DNL Adobe Mobile] SDK

Zie [Opmerkingen bij de release en logbestanden wijzigen](https://aep-sdks.gitbook.io/docs/release-notes) voor de Adobe Experience Platform Mobile SDK&#39;s.

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Volgende release: **20 juli 2022**

Laatste update: **13 juli 2022**

* Adobe Analytics [releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en)
* Adobe Analytics [productdocumentatie en zelfstudies](https://experienceleague.adobe.com/docs/analytics.html)

### AppMeasurement {#appm}

Releaseversie: **2.22.4.**

* [AppMeasurement voor JavaScript-releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### Nieuw [!DNL Analytics] zelfstudies en cursussen {#tutorials-analytics}

Nieuwe videozelfstudies, artikelen en cursussen gepubliceerd voor Adobe Analytics.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [2022 Stroomverbeteringen](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/analyzing-customer-journeys/flow-improvements.html) | Video | Meer informatie over enkele van de grote verbeteringen in de [!UICONTROL Flow] visualisatie. De verbeteringen omvatten het laten u het begin of het eind van de weg vormen u in geinteresseerd bent, het filtreren van een kolom om een specifiek punt, en pre-configureerbare geavanceerde montages te omvatten of uit te sluiten. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/analytics.png) [!DNL Customer Journey Analytics] {#cja}

Laatste update: **12 juli 2022**

* Customer Journey Analytics [releaseopmerkingen](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)
* Customer Journey Analytics [productdocumentatie en zelfstudies](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### Nieuwe zelfstudies en cursussen voor Customer Journey Analytics {#tutorials-cja}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor CJA.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [Het volgende en vorige deelvenster met items configureren](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/panels/configure-next-previous-item-panel.html) | Video | Leer hoe u het deelvenster Volgende en Vorige item configureert in [!DNL Customer Journey Analytics]. Dit deelvenster genereert tabellen en visualisaties om het volgende of vorige item voor een specifieke waarde van de dimensie te identificeren. |
| Juli 2022 | [Een aantekening maken](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/annotations/create-an-annotation.html?lang=en) | Video | Leer een aantekening te maken in uw [!DNL Customer Journey Analytics] projecten wanneer gebeurtenissen zoals het lanceren van de campagne, gegevenskwesties, en vakantie voorkomen. Deze functie informeert uw gebruikers over metrische variaties op deze datums of datumbereiken. |
| Juli 2022 | [Een snel filter maken](https://experienceleague.adobe.com/docs/customer-journey-analytics-learn/tutorials/components/filters/create-a-quick-filter.html) | Video | Snelle filters rechtstreeks in uw [!DNL Customer Journey Analytics] projecten uitvoert en de complexiteit van de volledige filterbuilder omzeilt. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/analytics.png) [!DNL Streaming Media Analytics] {#sma}

Laatste update: **23 maart 2022**

* [!DNL Streaming Media Analytics] [releaseopmerkingen](https://experienceleague.adobe.com/docs/media-analytics/using/additional-resources/release-notes.html?lang=en)
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

### Video over productupdates

* [Video over het overzicht van de release van juni 2022](https://video.tv.adobe.com/v/344308/?quality=12) voor een samenvatting van de release van 2022.6.

Video&#39;s over oudere productupdates:

* [Video over het overzicht van de release van mei 2022](https://video.tv.adobe.com/v/343321/?quality=12) voor een overzicht van de functies die in de release van 2022.5.0 (mei 2022) zijn toegevoegd.
* [Video over het overzicht van de release van april 2022](https://video.tv.adobe.com/v/342612?quality=12)
* [Video over het overzicht van de release van maart 2022](https://video.tv.adobe.com/v/341465)
* [Video over Overzicht release januari 2022](https://video.tv.adobe.com/v/340120)
* [Video over het overzicht van de release van december 2021](https://video.tv.adobe.com/v/339278)
* [Video over het overzicht van de release van oktober 2021](https://video.tv.adobe.com/v/338253)
* [Video over het overzicht van de release van september 2021](https://video.tv.adobe.com/v/337381)

### Experience Manager [!DNL Sites] als [!DNL Cloud Service]

Nieuwe functies in [!DNL Sites]:

* A [nieuwe gebruikersinterface](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/administering/content-fragments/content-fragments-console.html?lang=en) is nu beschikbaar voor beheerders van inhoud en auteurs van inhoud om efficiënt te beheren (acties zoals publiceren, ongedaan maken, kopiëren en verplaatsen), te zoeken/filteren en inhoudsfragmenten te maken voor gebruik in hoofdletters.

* De nieuwe [Component Inhoudsopgave](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/components/tableofcontents.html?lang=en) werkt niet alleen met de [!UICONTROL Core Components] maar met alle componenten wordt de inhoudsopgave automatisch op de inhoudspagina&#39;s weergegeven. En omdat de server-kant deze rendert en volledig in cache wordt geplaatst door de verzender, is het ook efficiënt om te laden.

### Experience Manager [!DNL Assets] als [!DNL Cloud Service]

Nieuwe functies in [!DNL Assets]:

* Experience Manager [!DNL Assets] Gebruikt momenteel Adobe Sensei AI-mogelijkheden [onderscheid maken tussen kleuren in een afbeelding en deze als tags automatisch toepassen bij opname](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/color-tag-images.html?lang=en). Deze tags maken een verbeterde zoekervaring mogelijk op basis van de compositie van de afbeeldingskleur. U kunt het aantal kleuren binnen een bereik van 1 tot 40 configureren dat aan een afbeelding is gelabeld, zodat u later kunt zoeken naar afbeeldingen op basis van die kleuren.

### Experience Manager Forms as a Cloud Service

Nieuwe functies in [!DNL Forms]:

* [Integreren [!UICONTROL Adaptive Forms] met Microsoft® Power Automate](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/forms-microsoft-power-automate-integration.html?lang=en): U kunt nu een adaptief formulier configureren om bij verzending een Microsoft® Power Automate Cloud Flow uit te voeren. Met het geconfigureerde adaptieve formulier worden vastgelegde gegevens, bijlagen en het document met records naar Power Automate Cloud Flow verzonden voor verwerking. Het helpt u om een aangepaste ervaring op het gebied van gegevensvastlegging op te bouwen en tegelijk de kracht van Microsoft® Power Automate te benutten om bedrijfslogics rond vastgelegde gegevens te bouwen en de workflows van klanten te automatiseren.

**Wizard voor het maken van een adaptief formulier:** U kunt een gebruiksvriendelijke wizard gebruiken om snel de auteur te ontwerpen [!UICONTROL Adaptive Forms]. De wizard biedt een snelle tabnavigatie waarmee u eenvoudig vooraf geconfigureerde sjablonen, stijlen, velden en verzendopties kunt selecteren om een adaptief formulier te maken.

### Experience Manager as a Cloud Service Stichting

Nieuwe functies:

Zoals vermeld in de de versienota&#39;s van Mei (2022.5.0), werd de &quot;Add boom&quot;optie onder het lusje van de Distribute van het scherm van het beheer van de replicatieagent verwijderd. Pakketten met een boomstructuur met inhoud moeten worden gerepliceerd met Publicatie beheren of de workflow van de inhoudsstructuur publiceren.

### [!DNL Cloud Manager]

Nieuwe functies:

* [!DNL Cloud Manager] gebruikers hebben nu toegang tot nuttige videozelfstudies via de [!UICONTROL Welcome] op de landingspagina op elk gewenst moment.

* De popover op de [Inhoud herstellen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/operations/backup.html?lang=en) tabblad van de pagina met omgevingsdetails bevat nu een handige lijst met it-opdrachten waarmee de gebruiker wijzigingen lokaal kan bekijken.

### Nieuwe cursussen en tutorials voor Experience Manager {#tutorials-aem}

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving | Toepassingen |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juli 2022 | [Haal alles uit het workflowbeheer voor bedrijven](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/workflow.html?lang=en) | Video | Leer de voordelen van het gebruik van workflows voor uw middelenbeheer en hoe u deze snel kunt maken. | AEM - Experience Workflow Management |
| Juli 2022 | [Ervaring zonder grenzen bieden met Adobe Experience Manager](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/headless.html?lang=en) | Video | Meer informatie over beheer van headless Experience met de nieuwste Experience Manager [!UICONTROL Content Fragment] verbeteringen en de nieuwe GraphQL API voor het leveren van inhoud zonder kop. | Experience Manager [!DNL Sites] |
| Juli 2022 | [Metagegevens laten werken voor uw bedrijf in Adobe Experience Manager Assets](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/metadata.html?lang=en) | Video | Leer hoe u optimaal kunt profiteren van uw metagegevens in AEM Assets door de werklast te verminderen en elementen van tags te voorzien en uw middelen doorzoekbaar te maken. | Experience Manager [!DNL Assets] |
| Juli 2022 | [iOS-app](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/ios-swiftui-app.html) | Video | Voorbeeldtoepassingen zijn een geweldige manier om de mogelijkheden zonder kop van Adobe Experience Manager te verkennen. In deze iOS-toepassing wordt getoond hoe u inhoud kunt zoeken met AEM [!UICONTROL GraphQL APIs] het gebruiken van persisted vragen. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Juli 2022 | [Android™-toepassing](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/example-apps/android-app.html) | Video | Deze Android™-toepassing laat zien hoe u query&#39;s uitvoert op inhoud met de [!UICONTROL GraphQL APIs] AEM. | Experience Manager [!DNL Assets], [!DNL Sites] |
| Juli 2022 | [OSGi configureren voor Adobe Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/deploying/configuring-osgi.html?lang=en) | Video | Leer hoe u OSGI voor AEM CS configureert. Bijvoorbeeld, leer over beheer van bundels OSGi en het beheren van de configuratiemontages voor componenten OSGi door configuratiedossiers die deel van een AEM codeproject uitmaken. | AEM as a Cloud Service |
| Juli 2022 | [Eigenschappen van formuliergegevensmodel overschrijven](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/adaptive-forms/override-fdm-values.html?lang=en) | Video | Leer hoe u eigenschappen van het formuliergegevensmodel kunt overschrijven, zodat u gemakkelijker één formuliergegevensmodel kunt testen op verschillende eindpunten. | AEM [!DNL Forms] |

{style=&quot;table-layout:auto&quot;}

### Experience Manager-releasegegevens

Alle Experience Manager-releaseopmerkingen worden op de volgende pagina&#39;s bijgehouden:

* [Informatie over as a Cloud Service release van Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=en)
* [Opmerkingen bij de release Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/release-notes/current.html?lang=en)
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
* [Gebruikershandleiding voor Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/content/introduction.html?lang=en)
* [Experience Manager 6.5 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 - Introductiepagina](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 Thuis leren &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Oudere versies van de Documentatie van de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Dynamic Media Classic Help-startpagina](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Documentatie Experience Manager: Recente updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Pictogram](/assets/ec_appicon_24.png) Adobe [!DNL Experience Manager Guides] {#xml-doc}

[!DNL Experience Manager Guides] is een toepassing die op AEM wordt opgesteld. Het is een krachtige oplossing voor componentcontentbeheer op bedrijfsniveau (CCMS) die native DITA-ondersteuning in Adobe Experience Manager mogelijk maakt en AEM in staat stelt om op DITA gebaseerde content creation en delivery af te handelen.

Meer informatie over [[!DNL Experience Manager Guides]](https://www.adobe.com/products/xml-documentation-for-experience-manager/features.html).

### Aanvullende bronnen

* [[!DNL Experience Manager Guides]](https://experienceleague.adobe.com/docs/experience-manager-guides-learn/videos/overview.html?lang=en) - zelfstudies over Experience League
* [[!DNL Experience Manager Guides] Meer informatie en ondersteuning](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - productdocumentatie

## ![Pictogram](/assets/ec_appicon_24.png) [!DNL Adobe Commerce] {#commerce}

Raadpleeg de volgende koppelingen voor Adobe Commerce-releaseopmerkingen:

* [Opmerkingen bij de release Adobe Commerce en Magento Open Source 2.4.x](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Opmerkingen bij de release Cloud Suite](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Nieuwe Adobe Commerce-zelfstudies en documentatie {#tutorials-commerce}

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [Aan de slag met Adobe Commerce - handleiding](https://experienceleague.adobe.com/docs/commerce-admin/start/guide-overview.html) | Productdocumentatie | Een hulplijn die is bedoeld voor handelaren en systeembeheerders die nieuw zijn voor Adobe Commerce en Magento Open Source. Bekijk vanuit hun perspectief een overzicht van het platform en enkele gedetailleerde informatie over de basisfuncties die een functionele winkel mogelijk maken. |
| Juli 2022 | [Gebruikershandleiding voor Page Builder](https://experienceleague.adobe.com/docs/commerce-admin/page-builder/guide-overview.html) | Productdocumentatie | Leer over de eigenschappen van de Bouwer van de Pagina, met inbegrip van een driedelige analyse voor het bouwen van basisinhoudcomponenten. Deze handleiding is bedoeld voor beheerders. Hierbij wordt uitgegaan van een basiskennis van de basisconfiguratie en -functionaliteit van Adobe Commerce. |
| Juli 2022 | [B2B voor Adobe Commerce Guide](https://experienceleague.adobe.com/docs/commerce-admin/b2b/guide-overview.html) | Beheerdershandleiding | Krijg gedetailleerde informatie over het installeren van en het toelaten van deze module, met inbegrip van configuratie en beheer van zijn eigenschappen. |
| Juli 2022 | [B2B voor Adobe Commerce - zelfstudies](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/b2b/company-accounts.html?lang=en) | Video (meerdere) | Meer informatie over de [!UICONTROL Companies] pagina in Adobe Commerce. U kunt uw bedrijfsrekeningen beheren en om het even welke hangende verzoeken om goedkeuring verschijnen bij de bovenkant van de lijst. |
| Juli 2022 | [Het gereedschap Kwaliteitspatch gebruiken](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/quality-patch-tool.html) | Video | Meer informatie over de [!UICONTROL Quality Patch Tool], een opdrachtregelprogramma dat garant staat voor hoogwaardige patches voor Adobe Commerce en Magento Open Source. |
| Juli 2022 | [Het dashboard Analyse voor de hele site](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/tools/site-wide-analysis-tool.html) | Video | Leer over het hulpmiddel van de Analyse van de Plaats-brede. Deze functie is een proactief hulpprogramma voor zelfbediening en een centrale opslagplaats met gedetailleerde systeeminzichten en aanbevelingen voor de beveiliging en de werking van uw Adobe Commerce-installatie. |
| Juli 2022 | [Betalingsservices gebruiken](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/admin/payment-services.html) | Video | Leren gebruiken [!UICONTROL Payment Services] om operationele overheadkosten te verminderen, verhoging opbrengst. |
| Juli 2022 | [Status van bestelling beheren](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/orders/order-status.html) | Video | Leer hoe u de status van een bestelling en de bijbehorende details kunt controleren en hoe u, indien nodig, de status van een bestelling kunt wijzigen. |
| Juli 2022 | [Marketingtools](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/marketing/catalog-price-rules.html?lang=en) | Video (meerdere) | Meer informatie over het maken van een prijsregel voor catalogi, regels voor winkelprijzen, het beheren van gerelateerde productregels, live zoeken en meer. |
| Juli 2022 | [Innovaties in inhoudpersonalisatie die bedrijfswaarde leveren](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/content-and-commerce/2022/content-perosonalization.html?lang=en) | Video | Bekijk de presentaties van de Bouwer van de Vaardigheid en leer over recente innovaties in de oplossing van de Inhoud van de Adobe die u helpen inhoud het schrijven democratiseren, omni-channel levering maken een breeze, en schaal verpersoonlijking. |
| Juli 2022 | [Catalogusbeheer](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/catalog/seo-url-rewrites.html) | Video&#39;s | Meer informatie over catalogusbeheer in Adobe Commerce. een categorie maken, producten in een categorie beheren, voorraad beheren en nog veel meer. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/target.png) [!DNL Adobe Target] {#target}

Laatst bijgewerkt: **30 juni 2022**

* Voor informatie over de release raadpleegt u [Adobe Target prerelease](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en)
* Zie voor actuele informatie [Opmerkingen bij de release van Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

### Nieuwe cursussen en zelfstudies voor Adobe Target {#tutorials-target}

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [Soorten publiek maken](https://experienceleague.adobe.com/docs/target-learn/tutorials/audiences/create-audiences.html) | Video | Leer aangepaste soorten publiek te maken en op te slaan in [!DNL Target] om te gebruiken in uw activiteiten. |
| Juli 2022 | [Personaliseren en automatiseren met Adobe Target](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/data-and-insights/2022/personalize.html?lang=en) | Video | Leer de basisconcepten van het automatiseren en optimaliseren van Adobe Target-mogelijkheden met behulp van [!UICONTROL Auto Target] en [!UICONTROL Auto Personalizations]. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwste productreleases van campagne

* [release Campagne v7.3](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)
* [Release van juni van het bedieningspaneel](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en)
* [zelfstudies en cursussen](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html#tutorials-campaign) over Experience League

### Nieuw [!DNL Campaign] zelfstudies en cursussen {#tutorials-campaign}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Adobe Campaign.

| Gepubliceerd | Naam | Type | Beschrijving | Toepassingen |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juli 2022 | [Configuratiescherm voor hybride hostingmodellen](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/control-panel-for-hybrid-hosting-models.html) | Video | Leer hoe u het configuratiescherm inschakelt voor hybride hostingmodellen van Adobe Campaign, toegang krijgt tot het configuratiescherm en belangrijke functies ontgrendelt. | Configuratiescherm  |
| Juli 2022 | [Doorvoereenheid en latentie bewaken](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-throughputs-and-latency.html?lang=nl) | Video | Leer hoe te om levering door-output en transactionele berichtlatentie van uw campagneexemplaar te controleren. | Configuratiescherm  |
| Juli 2022 | [Workflows controleren om het gebruik van bronnen te optimaliseren](https://experienceleague.adobe.com/docs/control-panel-learn/control-panel/performance-monitoring/monitor-workflows.html?lang=nl) | Video | Leer hoe u het tijdelijke opslaggebruik van uw workflows kunt controleren en waar u workflowinstellingen kunt configureren om database- of workflowproblemen voor uw exemplaar te voorkomen. | Configuratiescherm  |
| Juli 2022 | [Gegevensmodellen ontwikkelen en aanpassen in Adobe Campaign Classic](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/data-models.html?lang=en) | Video (de gebeurtenissen van de Bouwer van de Vaardigheid) | Sluit u aan bij deze sessie met onze trainer Campagne om te leren hoe u een gegevensschema kunt ontwikkelen binnen een gegevensmodel in Campaign Classic. | Campaign Classic v7 |
| Juli 2022 | [Aanbevolen werkwijzen en strategieën voor de prestaties](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/deliverability-best-practices.html) | Video | Leer hoe u de ontelbare uren voor de planning en productie van uw e-mailcampagnes tot een minimum kunt beperken. | Campaign Classic v7 |
| Juli 2022 | [Je crosschannel marketing verhogen met Adobe Campaign Classic](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/cross-channel.html?lang=en) | Video | Kijk naar deze diepgaande webinar die zich richt op workflows, automatisering, personalisatie en metingen voor Adobe Campaign Classic-klanten. | Campaign Classic v7 |
| Juli 2022 | [Tijd bespaart tips van een pro!](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/tips.html?lang=en) | Video | Start je nieuwe jaar met tips en trucs van een Adobe Campaign pro! Leer efficiënter te zijn met het maken en lanceren van campagnes en hoe u zinvollere en meer op maat gemaakte ervaringen over meerdere kanalen kunt bieden. | Campaign Classic v7 |
| Juli 2022 | [Adobe Campaign-integratie met een marketingecosysteem](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/integrations.html?lang=en) | Video | Meer informatie over Adobe Campaign-integratie met een marketingecosysteem. Kanaaloverschrijdende marketingoplossingen zoals Adobe Campaign mogen niet los worden gezien van andere technologieën of teams. Laat ongelijksoortige systemen een volledig inzicht in een klant niet verhinderen en verstoren dwars-kanaalstrategieën. | Campaign Classic v7 |
| Juli 2022 | [Adobe Campaign Standard Customer Spotlight - Microsoft](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/microsoft.html?lang=en) | Video | Horen van het marketingteam van Microsoft® om te delen hoe ze Adobe Campaign Standard gebruiken, hun architectuur en leidende principes, en beste praktijken. | Campaign Standard |
| Juli 2022 | [Adobe Campaign Customer Spotlight - Center Parcs](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/center-parcs.html?lang=en) | Video | Horen Adobe Campaign-klanten delen hoe ze uitdagingen het hoofd kunnen bieden, zich aanpassen aan de nieuwe norm, efficiënter worden met het beheren van campagnes en een betekenisvolle waarde creëren via Adobe Campaign. | Campaign Classic v7 |
| Juli 2022 | [Adobe Campaign Classic V7 versus V8](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/classic-v7-vs-v8.html?lang=en) | Video | Lees de nieuwste productupdates en begrijp de verschillen tussen V7 en V8 van onze productmanagers. | Campaign Classic v7, campagne v8 |
| Juli 2022 | [Keynote - trends en innovatie op het gebied van reizen van klanten over B2B en B2C](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/keynote.html?lang=en) | Video | Leer over de recentste tendensen in het Beheer van de Reis van de Klant over B2B en B2C. Zie de meest recente innovaties in belangrijke reistoepassingen en de bredere Adobe Experience Cloud en het Platform. | Marketo, Campaign Classic v7, Campagne v8 |
| Juli 2022 | [Toptips en trucs voor Adobe Campaign Standard](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/tips-and-tricks.html?lang=en) | Video | Sluit u aan bij uw Adobe Campaign Standard-exemplaar en ontdek de beste praktijken voor het aanwijzen, personaliseren en op de markt brengen van vermoeidheid voor een beter gebruik van ACS. | Campaign Standard |
| Juli 2022 | [Team, vaardigheden, en organisatorisch ontwerp dat wordt vereist om kanaalmarketing te steunen](https://experienceleague.adobe.com/docs/adobe-campaign-insider-events/events/team-skills-org-design.html) | Video | Leer hoe je je kunt engageren, waar en wanneer je wilt. Leer het belang van een marketingorganisatie die planning, uitvoering en meting ondersteunt. | Campaign Classic v7, campagne v8, Campaign Standard |

{style=&quot;table-layout:auto&quot;}

### Help-informatie en bronnen voor Campaign

* Adobe Campaign v8: [Documentatie](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign/campaign-v8/new/whats-new.html) - [Implementatiehulplijnen](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard Documentatie](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=nl) - [Release-planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7-documentatie](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=nl) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl) - [Releaseopmerkingen](https://experienceleague.adobe.com/docs/control-panel/using/release-notes/release-notes.html?lang=en) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=nl) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=nl)

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Met Journey Optimizer, kunt u geplande omnichannel campagnes en één-aan-één momenten voor miljoenen klanten van één enkele toepassing-en de volledige reis wordt geoptimaliseerd met intelligente besluiten en inzichten.

### Nieuwste Journey Optimizer-productreleases

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen in de [Opmerkingen bij de release van Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=en).

### Nieuwe zelfstudies en cursussen voor Journey Optimizer {#tutorials-ajo}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Adobe Journey Optimizer.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [Regels voor berichtfrequentie configureren](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/channel-configuration/configure-frequency-rules.html) | Video | Leer hoe u frequentieregels maakt, activeert, test en rapporteert. Begrijp hoe u kunt bepalen welke frequentieregels voor een bericht worden overgenomen. |
| Juli 2022 | [Sms-berichten configureren, opstellen en leveren](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/configure-author-and-deliver-sms-messages.html) | Video | Leer hoe u sms-berichten configureert, opstelt en opneemt in uw klantjourneys. |
| Juli 2022 | [Ondersteuning van binnenkomende zoektermen voor sms](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-messages/inbound-keyword-support-for-sms.html) | Video | Begrijp hoe ondersteuning voor native binnenkomende zoektermen (start, stop, unstop) voor sms werkt. |

{style=&quot;table-layout:auto&quot;}

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

### Nieuwe zelfstudies en cursussen voor Marketo {#tutorials-marketo}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Adobe Marketo.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Juli 2022 | [B2B-ervaringen met Marketo Engage en Adobe Experience Cloud](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-experiences.html?lang=en) | Video | Krijg een analyse van de integratie tussen de toepassing van Marketo Engage en van Adobe Experience Cloud, en welke pijnpunten zullen worden opgelost. | Marketo Engage |
| Juli 2022 | [Beter samen - Adobe Marketo Engage en Real-Time CDP](https://experienceleague.adobe.com/docs/skill-builder-events/skill-builder/customer-journeys/2022/b2b-campaigns.html?lang=en) | Video | Leer hoe u B2B-campagnes kunt ordenen met Marketo Engage en RT-CDP (B2B-editie) en wat zijn de meest gebruikte gevallen en voordelen die zijn ontgrendeld. | Marketo, Real-time Customer Data Platform |

{style=&quot;table-layout:auto&quot;}

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

Laatst bijgewerkt: **14 juli 2022**

| Functie | Beschrijving |
| ------- | ----------- |
| Aangepaste rapporten | (31 mei vrijgave; bètafunctie) Advertising Cloud DSP kan nu eerste-partijsegmenten opnemen die bestaan uit geverifieerde signalen die zijn gemaakt in een CDP (Customer Data Platform). |
| [!UICONTROL Inventory] | (29 juni) De nieuwe [!UICONTROL Inventory] > [!UICONTROL Deals] de weergave beschikt over dezelfde mogelijkheden voor gegevensaanpassing als de [!UICONTROL Campaigns] weergaven, waaronder aanvullende filters, kolomaanpassing en de optie om aangepaste weergaven, kolomsortering en een weergave voor gegevensvisualisatie (grafiek) op te slaan. U kunt een bevelmenu in elke rij openen door de ellipsen (...) na de overeenkomstennaam te klikken. |
| [!UICONTROL Inventory Inspector] | (29 juni) De [!UICONTROL Inventory] tabblad van de plaatsing [!UICONTROL Inspector] omvat nu aanpasbare gegevensvisualisatiekaarten en uitgebreide prestatiesmetriek, zoals [!UICONTROL Viewability Rate], [!UICONTROL Clicks], en [!UICONTROL Yesterday’s CPM]. |

{style=&quot;table-layout:auto&quot;}

### Nieuwe functies in [!DNL Advertising Cloud Search] {#adcloud-search}

Laatst bijgewerkt: **14 juli 2022**

| Functie | Beschrijving |
| ------- | ----------- |
| [!UICONTROL Insights] | (Release 11 juni) De analyse van het verlies van het Aandeel van de Impressie is nu opnieuw beschikbaar als bètaeigenschap. |
| [!DNL Advanced Campaign Management] | (20 juni) ([!DNL Google Ads] en [!DNL Microsoft Advertising] campagnes) U kunt nu dynamische responsieve onderzoek en variaties tot stand brengen gebruikend een onderzoeksmotor-specifieke advertentiesjabloon, gebaseerd op de inhoud van uw inventaris, van [!UICONTROL Campaigns] > [!UICONTROL Advanced (ACM)]. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Nieuwe zelfstudies en cursussen voor Adobe Document Cloud.

| Gepubliceerd | Naam | Type | Beschrijving | Toepassing |
| -----------| ---------- | ---------- | ---------- |---------- |
| Juli 2022 | [De rol fiatteur gebruiken](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/add-an-approver.html?lang=en) | Video (bijgewerkt) | Leer hoe u een document verzendt via een goedkeuringsproces. | Adobe Sign |
| Juli 2022 | [Een webformulier instellen](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/webform.html) | Video (bijgewerkt) | Leer hoe u een document maakt dat elektronisch rechtstreeks op uw website kan worden ondertekend. | Adobe Sign |
| Juli 2022 | [De rol van de gedelegeerde gebruiken](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/advanced-tasks/advanced-tasks-sending/delegate-signature.html?lang=en) | Video (bijgewerkt) | Beschrijving | Adobe Sign |
| Juli 2022 | [Een document elektronisch ondertekenen](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/electronically-sign-a-document.html?lang=en) | Video (bijgewerkt) | Leer hoe eenvoudig het is om een document te ondertekenen dat u met Acrobat Sign wordt gestuurd. | Adobe Sign |
| Juli 2022 | [Aan de slag voor Acrobat Sign-beheerders](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/up-and-running-admin.html?lang=en) | Video (bijgewerkt) | Leer de zeven belangrijkste gebieden waarop beheerders zich moeten richten om snel in Acrobat Sign aan de slag te gaan. | Adobe Sign |
| Juli 2022 | [Send for Signature in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/send-for-signature-with-outlook.html?lang=en#) | Video (bijgewerkt) | Leer hoe u documentworkflows stroomlijnt door een document ter ondertekening rechtstreeks in Microsoft® Outlook te verzenden. | Adobe Sign |
| Juli 2022 | [Opvullen en ondertekenen in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/integrations/microsoft/fill-and-sign-doc-microsoft-outlook.html?lang=en) | Video (bijgewerkt) | Leer hoe u documentworkflows stroomlijnt door een formulier rechtstreeks in Microsoft Outlook in te vullen en te ondertekenen. | Adobe Sign |
| Juli 2022 | [Groepen maken en beheren](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/admin-set-up/getting-started-admin/create-and-manage-groups.html?lang=en) | Video (bijgewerkt) | Leer hoe u groepen maakt, gebruikers toevoegt aan groepen en groepsinstellingen bewerkt. | Adobe Sign |
| Juli 2022 | [Ondertekening delegeren aan iemand anders](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/delegate-signing.html?lang=en) | Video (bijgewerkt) | Leer hoe u het ondertekenen van een document aan iemand anders kunt delegeren. | Adobe Sign |

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
