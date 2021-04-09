---
title: Opmerkingen bij de nieuwste release
description: Meer informatie over de nieuwste opmerkingen bij de release, nieuwe functies en nieuwe documentatie voor Experience Cloud-producten en -services. Zoek naar nieuwe hulp en zelfstudies over Experience Cloud, Creative Cloud voor Onderneming, en Document Cloud.
doc-type: release notes
last-update: March 2021
author: mfrei
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
translation-type: tm+mt
source-git-commit: c2746e2d0b558ce60d6af679cf29110d238426ad
workflow-type: tm+mt
source-wordcount: '7704'
ht-degree: 15%

---

# Opmerkingen bij de release van Adobe Experience Cloud - maart 2021

![Banner](/assets/experience-cloud-banner-3.png)

Experience Cloud oplossingen en services worden maandelijks bijgewerkt. Deze pagina is uw centrale locatie voor het zoeken naar de meest recente release-updates, documentatie en zelfstudies voor [!DNL Experience Cloud] producten en services. U kunt ook nieuwe documentatie vinden voor [!DNL Creative Cloud for Enterprise] en [!DNL Document Cloud].

>[!NOTE]
>
>Abonneren op de maandelijkse [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om e-mailmeldingen over updates van deze pagina te ontvangen. Deze pagina wordt gedurende de hele maand onderhouden en bevat mogelijk inhoud die vóór een releasedatum kan worden gewijzigd. Controleer regelmatig of er updates beschikbaar zijn voor Adobe Enterprise-producten en Experience League-documentatie.

Laatste update: **6 april 2021**

* [Digital Experience Blueprints](#blueprints)  (nieuwe implementatiedocumentatie)
* [Adobe-systeemstatus](#status)
* [Experience Cloud UI-componenten, -services en -beheer](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [offer decisioning](#offer-decisioning)
* [Analytics](#analytics) **(bijgewerkt op 6 april 2021)** en  [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [[!DNL Target]](#target)
* [[!DNL Magento]](#magento)
* [[!DNL Marketo Engage]](#marketo)
* [Document Cloud](#doc-cloud)
* [Creative Cloud Enterprise](#creative-cloud)

Hulp nodig? Bezoek [Adobe Experience League](https://experienceleague.adobe.com/#home) om te zoeken naar product- en technische documentatie, door Adobe georganiseerde cursussen, videotutorials, snelle antwoorden, communityinzichten en training onder leiding van instructeurs.

## ![](/assets/adobe.png) IconDigital Experience Blueprints  {#blueprints}

Digitale Ervaring blauwdrukken zijn herhaalbare implementaties om strategie aan te pakken en gevestigde bedrijfsproblemen op te lossen. De blauwdrukken versnellen tijd-aan-waarde en verstrekken een snelle weg aan succes.

| Gepubliceerd | Beschrijving |
| -----------| ---------- |
| [Digitale beleving blauwdrukken](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html) | Overzicht van [!UICONTROL Digital Blueprints]. Elke blauwdruk biedt een reeks artefacten die het bedrijfsprobleem van de hoge waarde, architectuur, implementatiestappen, technische overwegingen, en verbindingen aan de relevante documentatie verklaren. |
| [Audience Activation vervagen](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/audience-activation/overview.html) | Met deze activering waarbij de gebruikers eerst worden geactiveerd, kunnen merken de interactie van klanten via meerdere kanalen verbinden om een gecentraliseerd publiek te leveren dat op alle kanalen kan worden geactiveerd. |
| [Vervaging van de Hub voor klantactiviteiten](https://experienceleague.adobe.com/docs/blueprints-learn/architecture//customer-activity-hub/overview.html) | Leer hoe externe toepassingen tot [!UICONTROL Real-time Customer Profile] van Adobe Experience Platform kunnen toegang hebben. |
| [Customer Journey Analytics vervagen](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journey-analytics/overview.html) | Leer hoe de merken klantengegevens en gedrag van diverse interactiekanalen en bronnen kunnen verenigen om een op reis-gebaseerde mening van alle klanteninteractie tot stand te brengen. |
| [Aangepaste gegevenswetenschap voor blauwdruk van profielverrijking](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-science/overview.html) | Leer hoe de gegevens in Adobe Experience Platform door [!UICONTROL Data Science Workspace] worden gebruikt om modellen op te leiden, te implementeren en te scoren om inzichten in het leren van machines te bieden. |
| [Voorbereiding van gegevens en vervagingsblauwdruk](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-ingestion/overview.html) | Leer hoe te om brongegevens aan het [!UICONTROL Experience Data Model] (XDM) schema in kaart te brengen. Deze blauwdruk omvat ook het uitvoeren van transformaties op gegevens, met inbegrip van datum het formatteren, gebied het splitsen, aaneenschakeling, en omzettingen, evenals het aansluiten van, het samenvoegen van, en het opnieuw sluiten van verslagen. |
| [Blauwdruk voor Enterprise Data Exploration &amp; Reporting](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/data-exploration/overview.html) | Met de [!UICONTROL Query Service] van het Experience Platform kunnen SQL-query&#39;s op de gegevens worden uitgevoerd. Leer hoe [!UICONTROL Data Science Workspace] gegevensexploratie, gegevenswetenschap en werklasten voor machinaal leren uitvoert op de gegevens. |
| [Blauwdruk voor berichtenorchestratie meerdere kanalen](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/multi-channel-message-orchestration/overview.html) | Leer hoe merken proactief kunnen communiceren met hun klanten via kanalen zoals e-mail, SMS en mobiele waarschuwingen. |
| [Blauwdruk voor gegevensverzameling op de server](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/server-side-enterprise-data-collection/overview.html) | Leer hoe de gegevens die met het Web van Adobe Experience Platform en Mobiele SDKs worden verzameld van Experience Platform [!UICONTROL Edge Network] aan een gewenste bestemming kunnen door:sturen. |
| [Web &amp; mobiele verfijning](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/web-personalization/overview.html) | Leer hoe te om publiekssegmentatie in veelvoudige toepassingen te gebruiken om klantenervaringen te personaliseren en te optimaliseren. U kunt klantengedrag, demografie, loyaliteitsniveau, en vroegere transacties gebruiken om lay-outs, vraag-aan-actie, en inhoud te personaliseren. |

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

De meest recente updates van de Status van het Systeem van Adobe worden gevonden bij [Status van het Systeem van Adobe - 21 Mei, 2020](https://docs.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status).

## ![](/assets/ec_appicon_24.png) IconExperience Cloud UI Components, Services en Administration  {#ecloud}

| Functie | Beschrijving |
| -----------| ---------- |
| Unified Search | Het verenigde Onderzoek, dat momenteel voor Experience Platform beschikbaar is, steunt nu onderzoek op Bronnen en Doelen voor de gebruikers van het Experience Platform. Deze eigenschap laat u toe om Segmenten, Datasets, Schema&#39;s, Bronnen en Doelen te zoeken. |

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Bevat releaseupdategegevens voor Experience Platform en Experience Platform Launch.

* [Releaseopmerkingen bij Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html). (Bijgewerkt op 24 februari 2021)
* [Releaseopmerkingen bij Experience Platform Launch](https://experienceleague.adobe.com/docs/launch/using/release-notes/current.html). (Bijgewerkt op 18 februari 2021)

### Zelfstudies en cursussen voor Experience Platforms

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Experience Platform en services.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| maart 2021 | [Monitoringdashboard](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/monitoring-dashboard.html) | Video | Leer hoe u gegevens die in Adobe Experience Platform worden ingevoerd, kunt bijhouden en volgen met behulp van het Monitoring Dashboard. Dit controledashboard verstrekt een top-down mening van brongegevensverwerking door gegevens meer aan de Diensten van het Profiel en van de Identiteit op de bron, dataflow, en dataflow looppas niveaus, met actionable advisories op een geschikte manier. |
| maart 2021 | [Gegevens streamen met behulp van Bronverbindingen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-source-connector.html) | Video | Deze video laat zien hoe gegevens in real-time kunnen worden gestreamd van een bron voor cloudopslag naar Platform en hoe de gegevens in real-time kunnen worden gebruikt voor de betrokkenheid van klanten. |
| 5 maart 2021 | [Gegevensinname voor gegevensengineers](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1.dataingestion) | Cursus | Hoe te om gegevens van Veelvoudige Bronnen in Adobe Experience Platform, en meer te brengen. |
| maart 2021 | [De Azure Blob-bestemming configureren](https://experienceleague.adobe.com/docs/platform-learn/tutorials/destinations/configure-the-azure-blob-destination.html?lang=en#destinations) | Video | Leer hoe u door de stappen kunt lopen die nodig zijn voor het instellen en configureren en Azure Blob Storage-bestemming in [!UICONTROL Real-time Customer Data Platform] (Real-time CDP). |
| 5 maart 2021 | [Aan de slag met Offer decisioning voor markeertekens](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1.offerdecisioning) | Cursus | Meer informatie over de [!UICONTROL Offer Decisioning] toepassingsservice die op Adobe Experience Platform is gebouwd. Deze cursus wordt ontworpen voor marketers die opbrengst, klantenervaring en loyaliteit willen drijven door de beste aanbiedingen aan hun klanten te leveren. |
| 5 maart 2021 | [Streaming van gegevensinvoer via API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/streaming-ingestion-http-api.html) | Video | Deze video laat zien hoe gegevens in real-time naar Adobe Experience Platform kunnen worden gestreamd met behulp van het HTTP API-eindpunt. |
| 5 maart 2021 | [Gegevensinname controleren met API](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/data-monitoring.html?lang=en#data-ingestion) | Video | Leer hoe u gegevens kunt bijhouden en bijhouden die in Adobe Experience Platform worden ingevoerd met de gebruikersinterface en API van het Platform. |
| 5 maart 2021 | [Gegevens uit databases samenvoegen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/ingest-data-from-databases.html?lang=en#sources) | Video | Deze video loopt door hoe te om een partijenlijst van gegevens van een gegevensbestandbron in het Profiel van de Klant in real time van Adobe Experience Platform uit te voeren en het meer van Gegevens van de Ervaring, op een naadloze en scalable manier. |
| 5 maart 2021 | [Gegevens van Amazon S3 verzamelen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-amazon-s3.html) | Video | In deze video ziet u hoe u eenvoudig en op een naadloze en schaalbare manier gecomprimeerde gegevens van cloudopslagservices kunt opslaan in het Real-Time Customer Profile (realtime profiel van de klant) en in het datumpomeer van Adobe Experience Platform. |
| 5 maart 2021 | [Ingest-gegevens van Salesforce CRM](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-salesforce-crm.html) | Video | In deze video ziet u hoe u eenvoudig en op een naadloze en schaalbare manier ingesloten gegevens van CRM-bronnen in het Real-Time Customer Profile (realtime profiel van de klant) en in het datumpomeer van Adobe Experience Platform kunt plaatsen. |
| 5 maart 2021 | [Gegevens van Adobe Analytics verzamelen](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/ingest-data-from-adobe-analytics.html) | Video | Met de Adobe Analytics Source-aansluiting kunt u gegevens eenvoudig streamen van Adobe Analytics naar het Real-time Customer Profile (Real-time profiel van de klant) en het Experience Data Lake (Engelstalig), op een naadloze en schaalbare manier. |
| 5 maart 2021 | [Bronconnectors](https://experienceleague.adobe.com/docs/platform-learn/tutorials/sources/overview.html?lang=en#sources) | Video | Deze video geeft een overzicht van Bronnen, of Bron schakelaars, in Experience Platform. |
| 5 maart 2021 | [Details exportpostman Adobe IO-console](https://experienceleague.adobe.com/docs/platform-learn/tutorials/apis/postman.html) | Video | Leer hoe u Experience Platform-API&#39;s kunt verifiëren en openen. |
| 5 maart 2021 | [Gegevensinname](https://experienceleague.adobe.com/docs/platform-learn/tutorials/data-ingestion/understanding-data-ingestion.html#data-ingestion) | Video | Leer over de mogelijkheden van de gegevensopname van Experience Platform die u uw gegevens in één open en scalable platform laten samenbrengen om klantenprofielen in real time te beheren. |

## ![Pictogram](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Gebruik Adobe Experience Platform om de reis van een klant op schaal over ervaringskanalen te ordenen, door intelligent op de behoeften van elk individu in real time te anticiperen.

### Laatste productreleases

Release van februari 2021 - Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen in de [Opmerkingen bij de release van Journey Orchestration](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html).

### Nieuwe cursussen en tutorials voor Journey Orchestration

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 16 maart 2021 | [Profielactie bijwerken](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/building-a-journey/update-profile-action.html?lang=en#building-a-journey) | Video | Leer hoe u een bestaand Experience Platform-profiel kunt bijwerken met informatie die afkomstig is van een gebeurtenis, een gegevensbron of een specifieke waarde. |

### Meer bronnen voor Journey Orchestration

[Documentatie](https://docs.adobe.com/content/help/nl-NL/journeys/using/journey-orchestration-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Instructievideo&#39;s](https://docs.adobe.com/content/help/nl-NL/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Beslissing ](/assets/experience_platform_appicon_24.png) IconOffer  {#offer-decisioning}

[!UICONTROL Offer Decisioning] is een toepassingsservice die is geïntegreerd met Adobe Experience Platform. Gebruik [!UICONTROL Offer Decisioning] om uw klanten de beste aanbieding en ervaring op alle aanraakpunten op het juiste moment te bieden.

### Laatste productreleases

Release van februari 2021 - ontdek meer over de recentste mogelijkheden in [de Nota&#39;s van de Versie van de Offer decisioning](https://experienceleague.adobe.com/docs/offer-decisioning/using/new/release-notes.html?lang=en#new).

### Meer bronnen voor Offer decisioning

[Documentatie](https://experienceleague.adobe.com/docs/offer-decisioning/using/offer-decisioning-home.html?lang=en)  -  [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html?lang=en)

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **25 maart 2021**

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Oplossingen in Adobe Analytics](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)  **(bijgewerkt op 6 april 2021)**
* [AppMeasurement](#appm)

### Nieuwe functies in Adobe Analytics {#aa-features}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| ----------- | ---------- | ------- |
| API-updates voor gegevensherstel | 25 maart 2021 | De API voor gegevensherstel ondersteunt nu standaardvariabelen zoals [!UICONTROL Page] en [!UICONTROL IP address], mobiele en videovariabelen en de aangepaste [!UICONTROL props] en [!UICONTROL eVars].  Waarden binnen variabelen kunnen worden verwijderd of nieuwe waarden kunnen worden ingesteld. De API biedt nu ook filters voor URL&#39;s, querytekenreeksen bij borden en meer. |
| Analysis Workspace: [!UICONTROL Components] > [!UICONTROL User preferences] | 25 maart 2021 | Met de pagina [!UICONTROL Components] > [!UICONTROL User preferences] kunt u [!UICONTROL Analysis Workspace]-instellingen en de bijbehorende componenten voor uw gebruiker beheren. [!UICONTROL User preferences] van toepassing op alle nieuwe projecten en panels. <br>**Opmerking:** de volgende instellingen zijn verplaatst naar de  [!UICONTROL User preferences] pagina:<ul><li>Rapportinstellingen: Scheidingsteken voor duizendtallen (nu _Getalnotatie_)</li><li>Rapportinstellingen: CSV-scheidingsteken</li><li>Werkruimteprojecten: Help > Tips inschakelen</li><li>Werkruimteprojecten: Leeg deelvenster _Nieuwe projecten starten met dit deelvenster_, optie</li></ul> |
| Analysis Workspace: [!UICONTROL Histogram Smart Bucket Prediction] | 25 maart 2021 | [!UICONTROL Histogram Smart Bucket Prediction] biedt hulp bij histogrammen met hoge cardinaliteit door automatisch de juiste breedte en het juiste aantal emmers voor de gegevensspread te identificeren. Voor metingen met lage cardinaliteit gedraagt de visualisatie zich op dezelfde manier als voorheen. |
| [!UICONTROL Usage Log] API | 25 maart 2021 | Dit is een nieuwe v2.0 Analytics-API die via programmacode toegang mogelijk maakt tot dezelfde logbestandgegevens die beschikbaar zijn onder **[!UICONTROL Admin]** > **[!UICONTROL Log]** > **[!UICONTROL Usage and Access Log]**. Aanvullende details over verificatie, schema en voorbeeldreactie zijn [hier](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/usage-logs.md) beschikbaar. |
| Ondersteuning voor analytische dashboards voor aangepaste datumbereiken | 22 april 2021 | Scorecard-makers kunnen aangepaste datumbereiken maken en toepassen op mobiele scorecardprojecten. Maker kan kiezen uit de vertrouwde werkruimte en mobiele datumbereiken of een aangepast datumbereik maken. [Meer informatie](https://experienceleague.adobe.com/docs/analytics/analyze/mobapp/curator.html#mobapp). |

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| ----------- | ---------- | ----- |
| Ondersteuning voor [!UICONTROL Adobe Analytics dashboards] | 25 maart 2021 | [!UICONTROL Customer Journey Analytics] (CJA) ondersteunt nu de  [!UICONTROL Adobe Analytics dashboards Scorecard Builder] en de mobiele app. Hierdoor kunnen managers en zakelijke gebruikers hun kanaalspecifieke PKI&#39;s op basis van CJA-gegevens bekijken met dezelfde app die ze mogelijk al gebruiken voor Adobe Analytics. |
| Analysis Workspace: **[!UICONTROL Components]** > **[!UICONTROL User preferences]** | 25 maart 2021 | Met de pagina [!UICONTROL Components] > [!UICONTROL User preferences] kunt u [!UICONTROL Analysis Workspace]-instellingen en de bijbehorende componenten voor uw gebruiker beheren. [!UICONTROL User preferences] van toepassing op alle nieuwe projecten en panels. <br>**Opmerking:** de volgende instellingen zijn verplaatst naar de  [!UICONTROL User preferences] pagina:<ul><li>Werkruimteprojecten: Help > Tips inschakelen</li><li>Werkruimteprojecten: Leeg deelvenster _Nieuwe projecten starten met dit deelvenster_, optie</li></ul> |
| Analysis Workspace: [!UICONTROL Histogram Smart Bucket Prediction] | 25 maart 2021 | [!UICONTROL Histogram Smart Bucket Prediction] biedt hulp bij histogrammen met hoge cardinaliteit door automatisch de juiste breedte en het juiste aantal emmers voor de gegevensspread te identificeren. Voor metingen met lage cardinaliteit gedraagt de visualisatie zich op dezelfde manier als voorheen. |
| Ondersteuning voor analytische dashboards op Customer Journey Analytics | 25 maart 2021 | De app Analytics-dashboards ondersteunt nu Customer Journey Analytics. Gebruikers met Customer Journey Analytics kunnen KPI&#39;s weergeven op basis van gegevens die in Adobe Experience Platform worden ingevoerd in de app Analytics-dashboards. Met Customer Journey Analytics kunt u meerdere gegevensbronnen combineren voor een echte multikanaalweergave van de klantervaring. Met de app Analytics-dashboards kunt u altijd en overal een actuele, holistische weergave van uw bedrijf bekijken. [Meer informatie](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-dashboards/curator.html?lang=en#cja-dashboards). |

### Oplossingen in Adobe Analytics {#aa-fixes}

* Probleem verholpen waarbij deze nieuwe eigenaar na het bewerken en opslaan van de nieuwe eigenaar van een segment niet werd weerspiegeld in de gebruikersinterface van het segment. (AN-234502; AN-250970; AN-250286)
* Probleem verholpen waarbij een App-rapportsuite zowel primaire serveraanroepen als mobiele primaire serveraanroepen verbruikte. (AN-244029)
* Probleem verholpen met trage reactietijd van de gebruikersinterface bij het openen van [!UICONTROL Workspace]-projecten. (AN-242553)
* Probleem verholpen waarbij u zich niet kon aanmelden bij [!UICONTROL Report Builder] na upgrade naar de meest recente versie. (AN-248825)
* Gebruikersmachtigingen voor gebruikers die geen beheerder zijn, zijn nu opgelost. Een gebruiker moet toestemming hebben zolang deze maar is toegevoegd aan ten minste een van de profielen in [!UICONTROL Admin Console]. Als u gebruikers toevoegt aan profielen, hoeft u alleen maar machtigingen toe te voegen aan de profielen waarop ze al recht hebben. U mag ook niets verwijderen uit andere productprofielen. (AN-242723)
* Probleem met taalcodering verholpen met [!UICONTROL Data Feeds]. (AN-249862)
* Probleem verholpen waarbij gebruikers geen toegang hadden tot gedeelde [!UICONTROL Workspace]-projecten. (AN-247814)
* Probleem verholpen waarbij [!UICONTROL Alert Previews] niet overeenkwam met het aantal getriggerde [!UICONTROL Alerts]. (AN-249392; AN-250804)

#### Nog meer oplossingen in Adobe Analytics

AN-206099; AN-237460; AN-241803; AN-243735; AN-244081; AN-244615; AN-244687; AN-246832; AN-247227; AN-248237; AN-248478; AN-248852; AN-249115; AN-249140; AN-249216; AN-249275; AN-249538; AN-249963; AN-250034; AN-250270; AN-250320; AN-250338; AN-250377; AN-250378; AN-250557; AN-250609; AN-250614; AN-250615; AN-250885; AN-251088; AN-251137; AN-251190; AN-251192; AN-251193; AN-251301; AN-251496; AN-251545; AN-251734; AN-251735; AN-251744; AN-251816; AN-251982; AN-251972; AN-252051; AN-252073; AN-252105; AN-252409; AN-252640

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| ----------- | ---------- | ---------- |
| Aanmeldingsupdate voor [!UICONTROL Report Builder] | 9 april 2021 | Op 14 januari 2021 zijn tijdens de [!UICONTROL Report Builder]-aanmeldupdates afhankelijkheden van oudere technologieën verwijderd en is het aanmeldingsproces uitgelijnd met Experience Cloud. Experience Cloud gebruikt uw Enterprise ID (e-mail en wachtwoord). Om ononderbroken toegang tot [!UICONTROL Report Builder] te verzekeren, update [!UICONTROL Report Builder] toe:voegen-binnen aan versie 5.6.47 of later tegen 22 juli 2021. Report Builder versie 5.6.47 en hoger ondersteunt alleen het aanmelden bij de Experience Cloud en ondersteunt geen Single Sign-On. |
| De Diervoed van gegevens en IP van de Data Warehouse de Veranderingen van het Adres | 6 april 2021 | Vanaf 17 juni, zal het de leveringssysteem van de Diervoeders van Gegevens en van de Data Warehouse binnen onze gegevenscentra worden verplaatst, en daarom kan een verandering van externe IP adressen veroorzaken zichtbaar aan u.  U zou moeten bevestigen dat alle IP CIDR blokken voor het gegevenscentrum waar uw rapporten en het voer worden gedownload aanwezig zijn in om het even welke firewalls, voor om het even welke bestemmingssystemen die u controleert. [Hier is een volledige lijst van IP waaiers van het Adres in de lijsten van gewenste personen](https://https://experienceleague.adobe.com/docs/analytics/technotes/ip-addresses.html#data-collection-and-ftp-ip-address-blocks) van uw firewall te plaatsen. |
| Kennisgeving van aanstaande wijzigingen in het menu Analytics | 24 maart 2021 | Op 22 april 2021 werken we de vervolgkeuzemenu&#39;s **[!UICONTROL Components]**, **[!UICONTROL Tools]** en **[!UICONTROL Admin]** bij om de prestaties enigszins te verbeteren. Al deze pagina&#39;s zijn nog steeds beschikbaar via de koppelingen **[!UICONTROL All Components]**, **[!UICONTROL All Tools]** en **[!UICONTROL All Admin]**. Ze worden gewoon verwijderd uit het vervolgkeuzemenu. Hier zijn de menu-items die uit het vervolgkeuzemenu worden verwijderd en op de respectievelijke koppelingspagina worden geplaatst:<br><br> [!UICONTROL Components]<ul><li>[!UICONTROL Bookmarks]</li><li>[!UICONTROL Dashboards]</li><li>[!UICONTROL Targets]</li><li>[!UICONTROL Calendar Events]</li><li>[!UICONTROL Scheduled Reports]</li><li>[!UICONTROL Report Settings]</li></ul>[!UICONTROL Tools]<ul><li>[!UICONTROL Recommendations Classic]</li><li>[!UICONTROL Search & Promote]</li></ul>[!UICONTROL Admin]<ul><li>[!UICONTROL User Management]</li><li>[!UICONTROL Classification Importer]</li><li>[!UICONTROL Classification Rule Builder]</li><li>[!UICONTROL Data Sources]</li><li>[!UICONTROL Data Connectors]</li><li>[!UICONTROL Company Settings]</li><li>[!UICONTROL Logs]</li><li>[!UICONTROL Dynamic Tag Management]</li><li>[!UICONTROL Code Manager]</li><li>[!UICONTROL Exclude by IP]</li><li>[!UICONTROL Traffic Management]</li></ul> |
| [!UICONTROL Same-as-SiteCatalyst VISTA Processing] = ON | 17 maart 2021 | Op 17 juni 2021 worden alle rapportsuites bijgewerkt zodat [!UICONTROL Same-as-SiteCatalyst VISTA Processing] is ingesteld op ON. Deze wijziging is van invloed op de rapportage van [!UICONTROL Data Warehouse] door de gegevens te verwerken in overeenstemming met de verwerkingsregels. Neem voor vragen of verduidelijking contact op met de klantenservice van Adobe. |
| EOL van [!UICONTROL Full Processing] [!UICONTROL Data Sources] | 10 maart 2021 | Adobe is van plan [!UICONTROL Full Processing] [!UICONTROL Data Sources] in de toekomst af te schaffen. Vanaf 25 maart 2021 kan er geen nieuwe invoer van dit type meer worden gecreëerd. Gebruik [Bulk Data Insertion API](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) om dit type gegevens te importeren. [Meer informatie](https://experienceleague.adobe.com/docs/analytics/import/data-sources/data-types-and-categories/datasrc-fullproc-eol.html) |
| Opties voor bestemmingspagina&#39;s voor rapporten en analyses | 19 februari 2021 | Op 25 maart 2021 worden de opties voor het instellen van nieuwe Dashboards &amp; Analytics of andere inhoud als de Adobe Analytics-landingspagina verwijderd. Als u eerder een pagina Rapporten &amp; Analytics als uw aangepaste landingspagina plaatst, zal het blijven werken tot uw landingspagina in [!UICONTROL User Preferences] wordt gewijzigd. |
| EOL van Ad Hoc Analysis | Januari 2021 | [!UICONTROL Ad Hoc Analysis] op 1 maart 2021 zijn einddatum heeft bereikt. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |
| Einde van levensduur voor drie API-analysemogelijkheden | 6 januari 2021 | Op 30 april 2021 zijn de volgende API-services van Analytics Legacy gepland om hun einddatum te bereiken en worden ze afgesloten. De huidige integratie die met deze services wordt gebouwd, werkt niet meer op die dag.<ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>Wij hebben een [Oudere API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) geleverd om u te helpen uw vragen beantwoorden en richtlijnen te geven over hoe te te werk te gaan. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=emailAantal) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| EOL van Adobe Data Connectors | 13 juli 2020 | Adobe [!UICONTROL Data Connectors] worden mogelijk gemaakt door verouderde technologie die niet meer werkbaar is of ondersteund wordt. Een nieuwe norm is beschikbaar in [het Programma van de Partner van de Uitwisseling van de Adobe](https://partners.adobe.com/exchangeprogram/experiencecloud). U kunt die standaard gebruiken om integratie te blijven aanbieden en ondersteunen. De officiële einddatum is 1 augustus 2021. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/import/dataconnectors/data-connectors-eol.html) |

### AppMeasurement {#appm}

Voor de meest recente updates over AppMeasurement-releases raadpleegt u [Releaseopmerkingen bij AppMeasurement voor JavaScript](https://docs.adobe.com/content/help/nl-NL/analytics/implementation/appmeasurement-updates.html).

### Bronnen voor Analytics Help

* [Adobe Analytics-productdocumentatie en -Tutorials](https://experienceleague.corp.adobe.com/docs/analytics.html)

## ![Pictogram](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Oplossingen en verbeteringen in de Audience Manager.

### Oplossingen en verbeteringen {#aam-fixes-and-improvements}

* Probleem verholpen in het [Statusrapport aan boord](https://experienceleague.adobe.com/docs/audience-manager/user-guide/reporting/onboarding-status-report.html). In deze kwestie was er een discrepantie tussen de records in het rapport en die in het bestand dat door een partner aan boord werd geüpload. (AAM-57415)
* Probleem verholpen waarbij een fout is opgetreden bij de onjuiste validatie van gedupliceerde segmenttoewijzing voor **[!UICONTROL People-Based Destinations]**. (AAM-56631)
* Probleem verholpen waarbij sommige gebruikers de toegang tot **[!UICONTROL Audience Reports]** werd geblokkeerd. (AAM-57412)
* Er is een [!UICONTROL Remote Code Execution]-kwetsbaarheid in patches geplaatst die door aanvallers kan worden gebruikt om toegang te krijgen tot vertrouwelijke gegevens. (AAM-57495)

### Cursussen en zelfstudies voor Audience Managers {#tutorials-aam}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Audience Manager.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 19 maart 2021 | [Het begrip van Gegevensbeheer in Real-time CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-data-gov-for-aam-users.html) | Video | Meer informatie over de functionaliteit voor gegevensbeheer in [!UICONTROL Real-time Customer Data Platform]. |
| 19 maart 2021 | [Een overzicht van twee percepties - merken versus consumenten](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/brands-vs-consumers.html) | Video | In dit webinar maakt Adobe de kennis en gereedheid van adverteerders en uitgevers bekend voor een kokloze toekomst, de gevolgen voor hun gebruiksgevallen en hun perceptie van het bredere ecosysteem. |
| 5 maart 2021 | [10 overwegingen voor Verantwoordelijk beheer van klantgegevens](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/ten-considerations-for-responsible-customer-data-management.html) | Gebeurtenis | Horen van Adobe en Scotiabank Digital over belangrijke overwegingen voor verantwoord gegevensbeheer. |
| 19 maart 2021 | [De toekomst van gegevensbeheer en de veranderende omgeving](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/industry/the-future-of-data-management-and-the-changing-environment.html) | Gebeurtenis | In dit webinar, zie hoe Adobe en 451 Onderzoek over de toekomst van technologie en gegevens denken om het nieuwe marketing milieu te richten en beginnen uw zaken voor de toekomst van gegevensbeheer voor te bereiden. |
| 21 maart 2021 | [Het begrip Schema&#39;s en XDM in Echte - tijd CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html?lang=en#other-integrations) | Video | Aangezien u zich van Audience Manager aan het Platform van de Gegevens van de Klant in real time (CDP in real time) beweegt, zult u een paar nieuwe concepten en praktijken ontmoeten. Schemas en XDM vallen in die categorie. In deze video worden deze concepten uitgelegd. |
| 17 maart 2021 | [Het begrip Signalen in Echt - tijd CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-signals-for-aam-users.html) | Video | Deze video wordt bedoeld voor de gebruikers van de Audience Manager die zich aan het Platform van Gegevens in real time van de Klant (CDP in real time) bewegen, en bespreekt hoe de signalen (zeer belangrijke paren) die u in Audience Manager gebruikt om eigenschappen te bouwen in Platform worden gebruikt. |
| 12 maart 2021 | [Het begrip Schema&#39;s en XDM in Echte - tijd CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-schemas-xdm-for-aam-users.html) | Video | Aangezien u zich van Audience Manager aan het Platform van de Gegevens van de Klant in real time (CDP in real time) beweegt, zult u een paar nieuwe concepten en praktijken ontmoeten. Schemas en XDM vallen in die categorie. In deze video worden deze concepten uitgelegd. |
| 12 maart 2021 | [Begrijpen van de Ingestie van de Gegevens van het Web in Real-time CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-web-ingestion-for-aam-users.html) | Video | Leer de concepten betreffende het brengen van websitegegevens in het Platform van de Gegevens van de Klant in real time (in real time CDP), en omvat een aanraking op hoog niveau op waar de Verbinding van de Gegevens van de Audience Manager past, evenals hoe de gegevens zich van de website direct door Web SDK in Real-time CDP kunnen bewegen. |
| 3 maart 2021 | [Begrijpen van Segmenten in real time CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-segments-for-aam-users.html?lang=en#other-integrations) | Video | Leer de verschillen in segmenten en segmentverwezenlijking tussen Audience Manager en in real time CDP. |
| 3 maart 2021 | [Begrijpen de Tanden in Echt - tijd CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-traits-for-aam-users.html?lang=en#other-integrations) | Video | Leer de eigenschappen in Audience Manager en wat het equivalent in real time CDP is. |
| 3 maart 2021 | [Begrijpen van de Ingestie van Gegevens van 1st-Partij in Echt - tijd CDP voor de Gebruikers van de Audience Manager](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/other-integrations/integrating-with-rtcdp/rtcdp-1pd-ingestion-for-aam-users.html?lang=en#other-integrations) | Video | Leer over 1st-partij off-line gegevensopname in het Platform van de Gegevens van de Klant in real time (CDP in real time). Leer over sommige van de belangrijkste verschillen tussen de twee producten betreffende gegevensopname en toont hoe de Verbinding van Gegevens van de Audience Manager als stophiaat kan worden gebruikt tot de processen over naar CDP in real time zijn verplaatst. |
| 1 maart 2021 | [Commercialiseer uw Eigen publiek door op Audience Marketplace aan te bieden](https://experienceleague.adobe.com/docs/audience-manager-learn/tutorials/audience-marketplace/selling-data/commercialize-owned-audiences-on-marketplace.html?lang=en#audience-marketplace) | Video | Leer hoe u uw gegevens instelt als persoonlijke of openbare gegevensinvoer op de Audience Marketplace, waardoor u een gegevensaanbieder van gegevens van derden of derden bent. |
| maart 2021 | [Gegevensactivering maken en beheren in Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.4) | Cursus | In deze cursus, leer allen over het activeren van uw publiek, bijvoorbeeld, die publieksgegevens naar bestemmingspartners verzenden om de ervaring voor uw eind aan te passen - gebruikers. Leer de grondbeginselen van bestemmingen, hoe te om de juiste bestemming te kiezen, en hoe te om publieksgegevens voor te bereiden en te verzenden naar sociale netwerkbestemmingen die op mensen, niet koekjes worden gebaseerd. |
| maart 2021 | [Geavanceerde vaardigheden Audience Managers](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.5) | Cursus | Zodra u de grondbeginselen van Audience Manager hebt beheerst, neem deze cursus om over het nemen van uw Beheer van het Publiek aan het volgende niveau te leren. Leer hoe te om AI met algoritmische modellen te gebruiken, hoe te om de Regels van de Fusie van het Profiel te gebruiken om uw klanten als mensen in plaats van apparaten te begrijpen, en andere grote onderwerpen om het gebruik van DMP uit te breiden. |

## ![Pictogram](/assets/aem.png) Adobe Experience Manager {#aem}

Nieuwe functies, correcties en updates in Experience Manager. Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

>[!NOTE]
>
>Adobe raadt aan de pagina [Experience Manager-releaseupdates en roadmap](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) te bezoeken om actuele informatie over de release te blijven.

### Productreleases

* **AEM 6.5.8.0**
AEM 6.5, Service Pack 8 (6.5.8.0 vrijgegeven 11 maart 2021) is een belangrijke update die nieuwe eigenschappen, zeer belangrijke klantenverhogingen, betere prestaties, stabiliteit, en veiligheid omvat, vrijgegeven sinds de algemene beschikbaarheid van AEM 6.5, April 2019.
   * [Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en#service-pack)
   * [Te leveren items voor release van AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **AEM 6.4.8.4**
AEM 6.4, Service Pack 8, Cumulatief Fix Pack 4 (6.4.8.4 vrijgegeven 25 februari, 2021) is een belangrijke update die verscheidene interne en klantenmoeilijke situaties omvat sinds de algemene beschikbaarheid van AEM 6.4, Service Pack 8 (6.4.8.0), Maart 2020.
   * [Aanvullende informatie](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
   * [Te leveren items voor release van AEM Forms](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/forms-updates/aem-forms-releases.html#forms-updates)

* **Adobe Experience Manager as a Cloud Service**

   Wat is nieuw op Experience Manager als Cloud Service?

   * **Sites Experience Managers als Cloud Service**

      * [De RemotePage-component](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/remote-page.html?lang=en): Extra ondersteuning voor het weergeven en bewerken van externe SPA in Experience Manager met.
      * [Een externe SPA bewerken in de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/developing/hybrid/editing-external-spa.html?lang=en): Mogelijkheid toegevoegd om een zelfstandige toepassing van één pagina te uploaden naar een instantie van een Experience Manager, bewerkbare gedeelten van inhoud toe te voegen en het schrijven van inhoud in te schakelen.
   * **Elementen Experience Managers als Cloud Service**

      * De Middelen van de Experience Manager als Cloud Service hebben recht om een pre-gevormde instantie van het Portaal van het Merk te hebben. De gebruiker van de Manager van de Wolk kan het Portaal van het Merk op de Middelen van de Experience Manager als Cloud Service activeren. Zie [Brand Portal activeren met Brand Portal](https://experienceleague.corp.adobe.com/docs/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html).
      * Bedrijven kunnen nu elementen aanschaffen met behulp van Brand Portal. De functie voor het aanschaffen van bedrijfsmiddelen gebruikt Brand Portal om klanten te helpen bij het aanschaffen van bedrijfsmiddelen voor nieuwe marketingcampagnes, foto&#39;s en projecten. Zie [Overzicht van Asset Sourcing](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/asset-sourcing-in-brand-portal/brand-portal-asset-sourcing.html?lang=en) in de Handleiding voor het Brand Portal.
      * In het gebruiksrapport van het Brand Portal worden nu alleen de actieve gebruikers weergegeven. De inactieve gebruikers worden nu niet weergegeven. Actieve gebruikers zijn de gebruikers van wie de account is toegewezen aan een productprofiel in de Admin Console. Zie [Werken met rapporten](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/admin-tools/brand-portal-reports.html?lang=en) in de Poortgids van het Merk.
      * In Brand Portal is een nieuwe downloadinstelling geïntroduceerd waarmee u voor elk element een aparte map kunt maken wanneer u mappen, verzamelingen en dergelijke downloadt. Zie [Asset Download](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/download/brand-portal-download-assets.html?lang=en) in **Elementen downloaden van Brand Portal** in de Handleiding voor het Brand Portal.
   * **Experience Manager Forms als Cloud Service**

      AEM Forms heeft veel organisaties geholpen om in de loop der jaren geweldige ervaring op het gebied van instapweigering en inschrijving te bieden. Deze ervaringen hebben organisaties geholpen bij het omzetten van leads naar verkoop, het verwerken van vastgelegde klantgegevens, het leveren van responsieve ervaringen op basis van het profiel van het publiek en nog veel meer. AEM Forms is nu beschikbaar als cloudservice.

      U kunt AEM Forms gebruiken als Cloud Service om digitale formulieren te maken, formulieren te verbinden met bestaande gegevensbronnen, formulieren te integreren met Adobe Sign om e-handtekeningen toe te voegen aan formulieren, Document of Record (DoR) te genereren om ingediende formulieren als PDF-bestanden te archiveren. De service kan uw bestaande PDF forms ook converteren naar digitale formulieren. Naast de standaard AEM Forms-functies biedt de service verschillende mogelijkheden in de cloud, zoals automatisch schalen, geen downtime voor upgrades en ontwikkelomgeving in de cloud. Lees [dit blogbericht](https://blog.adobe.com/en/publish/2021/03/11/experience-manager-forms-as-a-cloud-service.html) voor meer informatie over de mogelijkheden en functies van AEM Forms als Cloud Service.

      U kunt een demo afspelen bij uw Adobe-medewerker of u aanmelden voor de service.


   * **Experience Manager Commerce als Cloud Service**

      * Product Experience Management: Verrijk de pagina&#39;s van de productcatalogus individueel met de Fragmenten van de Ervaring.
      * De uitgebreide eigenschappen van de productconsole om verbonden Middelen en de Fragmenten van de Ervaring te tonen, met inbegrip van actie om snel aan de bijbehorende inhoud te navigeren.
      * Uitgebrachte CIF Venia Reference Site - 2021.02.24 met de nieuwste versie van CIF Core Components 1.8.0. Zie [CIF Venia Reference Site 2021.02.24](https://github.com/adobe/aem-cif-guides-venia/releases/tag/venia-2021.02.24) voor meer informatie.
      * Uitgebrachte versie CIF Core Components versie 1.8.0. Zie [CIF Core Components 1.8.0](https://github.com/adobe/aem-core-cif-components/releases/tag/core-cif-components-reactor-1.8.0) voor meer informatie.
   * **Cloud Manager**

      * Klanten met omgevingen die reeds bestaande aangepaste domeinnaamconfiguraties voor [IP-Lijsten van gewenste personen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/ip-allow-lists/check-ip-allow-list-status.html?lang=en#pre-existing-cdn), [SSL-certificaten](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/manage-ssl-certificates/check-status-ssl-certificate.html?lang=en#pre-existing-cdn) en [Aangepaste domeinnamen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/custom-domain-names/check-domain-name-status.html?lang=en#pre-existing-cdn) hebben, zien nu een bericht over hun bestaande configuraties. Ze kunnen ook zelf dienen via de gebruikersinterface.
      * Gebruikers met de vereiste machtigingen kunnen nu een programma bewerken, zodat zij het volgende op een zelfbedieningsmanier kunnen doen:
         * Voeg de oplossing van Plaatsen aan een bestaand programma met Activa toe of omgekeerd.
         * Sites of middelen verwijderen uit een bestaand programma met zowel Sites als Middelen.
         * Voeg tweede, ongebruikte oplossingsrechten toe aan een bestaand programma of aan een nieuw programma.
      * **AEM Push** Updatelabel wordt nu weergegeven voor zowel  *Pipeline* Execution als  ** Activiteitsschermen.
      * Als een milieu gehiberneerd is, maar er ook een Experience Manager beschikbare update is, neemt **Gesamberneerde** status belangrijkheid over **Update beschikbaar**.
      * Gebruikers kunnen hun rollen van de Manager van de Wolk nu zien door **Rollen van de Manager van de Wolk van de Mening te selecteren** na het navigeren aan het pictogram van het Profiel van de Gebruiker (hoogste recht) van Verenigde Shell.
      * Het label **Goedkeuringsaanvraag** is voor meer duidelijkheid opnieuw gelabeld aan **Productiegoedkeuring**.
      * Het **Version**-label is opnieuw gelabeld aan **Git Tag** in het uitvoeringsscherm van de productiepijplijn.
      * De labels die het gedrag bepalen wanneer belangrijke metriek niet aan de bepaalde drempel voldoet, zijn opnieuw geëtiketteerd om op hun ware gedrag te wijzen: **Onmiddellijk annuleren** en **Direct goedkeuren**.
      * De lijsten van de klasse en van de methodevervanging zijn bijgewerkt gebaseerd op versie `2021.3.4997.20210303T022849Z-210225` van de Experience Manager Cloud Service SDK.
      * De productiepijplijn van de Manager van de wolk omvat nu [het Testen van de Douane UI](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/functional-testing.html?lang=en#custom-ui-testing) vermogen.




### **Community**

* **Adobe Developers Live 2021 | Volledige lijst met sessies**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-2021-complete-session-list/m-p/394595#M27875) Hier volgt een geaggregeerde lijst van alle sessies van Experience Managers die plaatsvinden op  **Adobe Developers Live**.

* **Top van Adobe in 2021 | Volledige lijst met sessie-Experience Managers**

   [](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-summit-2021-complete-aem-session-list/td-p/398344) Hieronder volgt een geaggregeerde lijst van alle vergaderingen van de Experience Manager die plaatsvinden op de top van  **Adobe 2021**.

### Experience Manager-releasegegevens

Alle Experience Manager-releaseopmerkingen worden op de volgende pagina&#39;s bijgehouden:

* [Updates van de release van Experience Managers en roadmap](https://docs.adobe.com/content/help/en/experience-manager-release-information/aem-release-updates/home.html)
* [Experience Manager als informatie over de release van een Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/release-notes/home.html)
* [Opmerkingen bij de release Experience Manager Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Releaseopmerkingen bij de service Geautomatiseerde conversie van formulieren](https://docs.adobe.com/content/help/nl-NL/aem-forms-automated-conversion-service/using/release-notes.html)
* [Experience Manager 6.5 Opmerkingen bij de release Service Pack](https://docs.adobe.com/content/help/nl-NL/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Experience Manager 6.4 Opmerkingen bij de release Cumulative Fix Pack](https://docs.adobe.com/content/help/nl-NL/experience-manager-64/release-notes/cfp-release-notes.html)
* [Opmerkingen bij de release Experience ManagerAssets Dynamic Media](https://docs.adobe.com/content/help/nl-NL/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Opmerkingen bij de release van Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Opmerkingen bij de release van Experience Manager-bureaublad](https://docs.adobe.com/content/help/nl-NL/experience-manager-desktop-app/using/release-notes.html)
* [Opmerkingen bij de release Experience Manager Dispatcher](https://docs.adobe.com/content/help/nl-NL/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Releaseopmerkingen bij Livefyre](https://docs.adobe.com/content/help/nl-NL/livefyre/using/release-notes/c-rn.html)

### Cursussen en zelfstudies voor Experience Managers

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Maart 2021 | [Inhoud leveren op Experience Manager Cloud Service](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/content/feb2021/content-delivery.html#content) | Gebeurtenis | Adobe Experience Manager als Cloud Service beschikt over een krachtige, vooraf geconfigureerde architectuur voor de levering van inhoud. Toon hoe te om het beste van geoptimaliseerde configuraties van de inhoudslevering te maken |
| Maart 2021 | [Helpx-artikel migreren naar soorten Forms en Documenten](https://experienceleague.adobe.com/docs/experience-manager-learn/forms/document-services/pdf-forms-and-documents.html?lang=en#document-services) | Artikel | Een artikel waarin de verschillende typen PDF forms en documenten worden uitgelegd. |
| Maart 2021 | [Implementatie van productie met een AEM-publicatie-omgeving](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-with-aem-headless/graphql/production-deployment.html#graphql) | Tutorial | Stel een lokale omgeving in om inhoud te simuleren die wordt verspreid van een instantie Auteur naar een instantie Publish. Genereer een productiebuild van een React-app die is geconfigureerd om inhoud te verbruiken vanuit de AEM-publicatieomgeving met behulp van de GraphQL-API&#39;s. Langs de manier, zult u leren hoe te om milieuvariabelen effectief te gebruiken en hoe te om de configuraties van AEM CORS bij te werken. |
| Maart 2021 | [Beheer van inhoud zonder hoofd met GraphQL API&#39;s](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.headless) | Cursus | Ontdek hoe u de GraphQL-API&#39;s en headless-functies van AEM kunt gebruiken om ervaringen die in een externe app zijn opgedoken, kracht bij te zetten. |
| Maart 2021 | [Starten - Functievideo](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/launches.html) | Video | Starten in AEM Sites bieden een manier om inhoud voor websites te maken, te ontwerpen en te reviseren voor toekomstige release. Tijdens de lancering van de lancering kan de productiewebsite blijven evolueren en dag in dag veranderen zoals het normaal zou doen. |
| Maart 2021 | [LinRelate- en niet-gerelateerde elementen - Feature VideoText](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/authoring/relate-unrelate.html) | Video | Leer hoe u relaties tussen elementen in AEM tot stand brengt en beheert. |
| Maart 2021 | [Verifiëren voor AEM als Cloud Service van een externe toepassing](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.aemcs) | Cursus | Leer hoe een externe toepassing de Tokens van de Toegang van de Lokale Ontwikkeling en de Referenties van de Dienst kan gebruiken programmatically om als Cloud Service over HTTP voor authentiek te verklaren te AEM. |
| Maart 2021 | [Meerdere formulieren invullen en ondertekenen in een hypotheektoepassing](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.7.forms) | Cursus | Onderteken een pakket documenten naadloos met behulp van de integratie met AEM Forms en Ondertekenen. De gegevens die in het formulier zijn ingevoerd, kunnen worden gebruikt om volgende formulieren vooraf in te vullen in het pakket. |
| Maart 2021 | [Versionering/Tijdverdraaiing in AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/page-authoring/timewarp-feature-video-use.html) | Video | Timewarp is een eigenschap van Adobe Experience Manager Sites die auteurs een snelle manier verstrekt om de staat van een pagina op specifieke tijd in het verleden te herzien. |
| Maart 2021 | [Foundation - workflowbeheer](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-workflow-management.html?lang=en#workflow) | Video | Deze video gebruikt de Modellen van het Werkschema om deze reeks mogelijkheden aan te tonen, nochtans zijn zij ook van toepassing op AEM Lancers. |
| Maart 2021 | [Ervaar fragmentblokken](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/building-blocks.html) | Video | Bouwstenen zijn een onderdeel van Experience Fragments. Bouwstenen laten inhoudsauteurs toe om componenten over verschillende variaties van de Fragmenten van de Ervaring opnieuw te gebruiken. |
| Maart 2021 | [Workflow-editor](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/workflow/use-the-workflow-editor.html?lang=en#workflow) | Video | De workflow maakt bedrijfsprocesbeheer in Experience Manager mogelijk en wordt gebruikt voor automatische verwerking van inhoud en voor het vergemakkelijken van governance en processen waarvoor menselijke besluitvorming vereist is. |
| Maart 2021 | [Gesloten gebruikersgroepen in AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/closed-user-groups.html) | Video | Gesloten gebruikersgroepen (CUG&#39;s) is een functie die wordt gebruikt om de toegang tot inhoud te beperken tot een bepaalde groep gebruikers op een gepubliceerde site. In deze video ziet u hoe groepen van gebruikers met gesloten deuren kunnen worden gebruikt met Adobe Experience Manager Assets om de toegang tot een specifieke map met middelen te beperken. |
| Maart 2021 | [Rapporten](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/advanced/asset-reports.html) | Video | Leer hoe AEM Assets een rapportagekader op bedrijfsniveau biedt dat schaalt voor grote opslagplaatsen via een intuïtieve gebruikerservaring. |
| Maart 2021 | [Slimme tags voor afbeeldingen met AEM Assets](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/image-smart-tags.html) | Video | Slimme tags voor afbeeldingen vergroten AEM zoekmogelijkheden door automatisch en intelligent metagegevenstags toe te voegen aan afbeeldingselementen op basis van de inhoud van de afbeelding. |
| Maart 2021 | [Metagegevens trapsgewijs, zichtbaarheid](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/metadata/cascade-metadata-feature-video-use.html) | Video | Meer informatie over nieuwe dynamische regels voor veldvereisten, zichtbaarheid en contextafhankelijke keuzes. In de video worden ook de stappen beschreven die een beheerder nodig heeft om deze regels toe te passen op een aangepast metagegevensschema. |
| Maart 2021 | [Projectstramienen](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/projects/use-project-masters.html?lang=en#delete-project-masters) | Video | Het schrappen van een master project resulteert in onbruikbaar afgeleide projecten. |
| Maart 2021 | [Pagina-eigenschappen aanpassen](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/developing/page-properties-technical-video-develop.html) | Video | Maak een technische video over hoe u de pagina-eigenschappen het beste kunt uitbreiden en aanpassen. |
| Maart 2021 | [Inhoudsfragmenten omzetten](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/content-fragments/content-fragments-translation-feature-video-use.html) | Video | Leer hoe u Content Fragments kunt lokaliseren en vertalen met Adobe Experience Manager. Elementen met gemengde media die aan een inhoudsfragment zijn gekoppeld, kunnen ook worden geëxtraheerd en vertaald. |
| Maart 2021 | [Ervaringsfragmenten](https://experienceleague.adobe.com/docs/experience-manager-learn/sites/experience-fragments/experience-fragments-feature-video-use.html) | Video | Leer hoe de Fragmenten van de Ervaring inhoudsauteurs toelaat om inhoud over kanalen, met inbegrip van de pagina&#39;s van Plaatsen en derdesystemen opnieuw te gebruiken. |
| Maart 2021 | [Verbeterde zoekfunctie](https://experienceleague.adobe.com/docs/experience-manager-learn/assets/search-and-discovery/search-boost.html) | Video | Meer weten over Zoekopdrachten? |

### Overige Help-bronnen voor Experience Manager

* [Experience Managers als hulplijnen voor Cloud Servicen](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/landing/home.html)
* [Experience Manager 6.5 Introductie &amp; ondersteuning](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [Experience Manager 6.4 - Introductiepagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [Experience Manager 6.3 Introductie &amp; ondersteuning](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [Experience Manager 6.2 Thuis leren &amp; ondersteuning](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Oudere versies van de Documentatie van de Experience Manager](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/nl-NL/dynamic-media-classic/using/home.html)

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Laatste productreleases

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen die worden vrijgegeven:

* [Opmerkingen bij de release Campaign Standard](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html)
* [Opmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) bij de release Campaign Classic.

>[!IMPORTANT]
>
>Meer informatie over [vereiste configuratie-updates](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/acc-config-updates.html?lang=en) voor Adobe Campaign Classic.

### Nieuwe cursussen en tutorials voor Campaign

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Oplossing | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 23 februari 2021 | [Leverbaarheid - Metriek voor leverbaarheid](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/metrics-overview.html) | Campaign Classic/Standaard | Leer over zeer belangrijke leverbaarheidsmetriek om te controleren en hoe te om hen te gebruiken om een reputatiekwestie te identificeren. |
| 23 februari 2021 | [Leverbaarheid - Stortingen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bounces.html) | Campaign Classic/Standaard | Meer informatie over de verschillende typen bounces. |
| 23 februari 2021 | [Leverbaarheid - Klachten](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/complaints.html) | Campaign Classic/Standaard | Lees meer over klachten die worden geregistreerd wanneer een gebruiker aangeeft dat een e-mail ongewenst of onverwacht is. |
| 23 februari 2021 | [Leverbaarheid - Spam-overvullingen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/spam-traps.html) | Campaign Classic/Standaard | Meer informatie over de verschillende typen bounces. |
| 23 februari 2021 | [Aflevering - Opsomming en blokkering](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/metrics-for-deliverability/bulking-and-blocking.html) | Campaign Classic/Standaard | Leer waarom ISP’s berichten in een map met ongewenste e-mail plaatsen of e-mails blokkeren. |
| 23 februari 2021 | [Leverbaarheid - Overgangsproces - Infrastructuur](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/infrastructure.html) | Campaign Classic/Standaard | Leer wat nodig is om een e-mailinfrastructuur correct te bouwen. |
| 23 februari 2021 | [Leverbaarheid — Betrokkenheid](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/engagement.html) | Campaign Classic/Standaard | Meer informatie over de verschillende soorten betrokkenheid en waarom betrokkenheid van belang is voor de te leveren prestaties. |
| 23 februari 2021 | [Leverbaarheid - Overgangsproces: Doelcriteria](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/targeting-criteria.html) | Campaign Classic/Standaard | Leer hoe u een positieve reputatie van de get-go kunt opbouwen om vertrouwen op te bouwen voordat u gaat rollen in uw minder betrokken publiek. |
| 23 februari 2021 | [Leverbaarheid - Overgangsproces - ISP-specifieke overwegingen tijdens IP het opwarmen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/isp-specific-considerations-during-ip-warming.html) | Campaign Classic/Standaard | Leer over de verschillende regels en de manieren ISP leveranciers om hun verkeer te bekijken |
| 24 februari 2021 | [Leverbaarheid - Eerste indrukken - inleiding](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/introduction.html) | Campaign Classic/Standaard | Leer hoe u zich kunt instellen voor het uitvoeren van een succesvol e-mailprogramma door een goede eerste indruk te maken op die gebieden. |
| 24 februari 2021 | [Leverbaarheid - Overgangsproces: Volume](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/volume.html) | Campaign Classic/Standaard | Begrijp hoe het verzenden van volume de leverbaarheid van uw e-mailcampagnes beïnvloedt. |
| 24 februari 2021 | [Leverbaarheid - Eerste indrukken - Verzameling van adressen en groei van lijsten](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/address-collection-and-list-growth.html) | Campaign Classic/Standaard | Leer wat de beste bronnen voor nieuwe e-mailadressen zijn, hoe te om hoge gegevenskwaliteit te verzekeren, en aanpassing aan wettelijke richtlijnen te verzekeren. |
| 25 februari 2021 | [Leverbaarheid - Eerste indrukken - Welkomstbericht](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/first-impressions/welcome-emails.html) | Campaign Classic/Standaard | Leer wat de belangrijkste elementen van uw welkomststrategie moeten zijn. |
| 25 februari 2021 | [Leverbaarheid - Overgangsproces: E-mailplatforms schakelen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/transition-process/switching-email-platforms.html) | Campaign Classic/Standaard | Leer hoe u probleemloos kunt overschakelen tussen e-mailplatforms. |
| 26 februari 2021 | [Leverbaarheid - Tips en trucs voor optimale prestaties](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/content-best-practices-for-optimal-delivery.html) | Campaign Classic/Standaard | Tips voor het optimaliseren van de inhoud van uw e-mail voor de leveringsbaarheid. |
| 26 februari 2021 | [Leverbaarheid - blijvend karakter van afzender](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/sender-permanence.html) | Campaign Classic/Standaard | Leer waarom het belangrijk is om een verenigbaar verzendend volume te vestigen. |
| 26 februari 2021 | [Leverbaarheid - Doorlopende controle](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/ongoing-monitoring.html) | Campaign Classic/Standaard | Weet op welke problemen u moet letten wanneer u uw leveringen controleert. |
| 26 februari 2021 | [Leverbaarheid - In de praktijk brengen](https://experienceleague.adobe.com/docs/deliverability-learn/deliverability-best-practice-guide/putting-it-in-practice.html) | Campaign Classic/Standaard | Vier sleutelpijlers voor succes. |
| 10 maart 2021 | [Aanbevolen werkwijzen voor de levering van leiders, zakelijke gebruikers en beheerders](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.deliverability) | Campaign Classic | Leer de belangrijkste termen, concepten en benaderingen van leverbaarheid zodat u over de juiste kennis beschikt om van uw marketingprogramma een succes te maken. |

### Help-bronnen voor Help

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/campaign-standard-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/overview.html) - [Releaseplanning](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/campaign-classic-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/overview.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/nl-NL/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/control-panel/using/release-notes.html) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Releaseopmerkingen bij Adobe Advertising Cloud.

* [Nieuwe functies in Advertising Cloud DSP](#adcloud-dsp)
* [Nieuwe functies in Advertising Cloud Search](#adcloud-search)

### Nieuwe functies in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Laatst bijgewerkt: **28 oktober 2020**

| Functie | Beschrijving |
| -----------| ---------- |
| Nieuwe Help | (28 oktober) De oudere Help is vervangen door bijgewerkte pagina&#39;s, die beschikbaar zijn via de koppeling Help in het DSP hoofdmenu en die ook altijd beschikbaar zijn via [https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html](https://experienceleague.adobe.com/docs/advertising-cloud/dsp/home.html) |
| Campagnes | (28 oktober) De vorige Campagne Bètweergaven zijn nu de standaardcameraweergaven, voor snellere inzichten, vereenvoudigde workflows en aangepaste weergaven. |
| Privévoorraad | (15 oktober versie) Alle gebruikers kunnen de details van dealID nu opstelling en uitgeven gebruikend een nieuwe vorm van overeenkomstidentiteitskaart, die een vereenvoudigde versie van de erfenis [!UICONTROL Smart Ad Serving] vorm is. Als u nieuwe deal-id-details wilt instellen, gaat u naar **[!UICONTROL Inventory > Deals]**, klikt u op **[!UICONTROL Create]** en vervolgens op **[!UICONTROL Deal ID Beta]**. |
| Prognose van plaatsing | (15 oktober) Voor plaatsingen met plaatsing-vlakke het passen, omvat [!UICONTROL Forecast] sectie van de plaatsingsmontages een nieuwe [!UICONTROL Estimated Maximums] sectie, die wijst op hoeveel meer capaciteit met de huidige het richten configuratie beschikbaar is. |

### Nieuwe functies in [!DNL Advertising Cloud Search] {#adcloud-search}

Laatst bijgewerkt: **29 maart 2022, voor release 27 maart**

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Search Campaigns]<br> Rapporten | (Microsoft Ads-campagnes) Biedingsondersteuning is nu beschikbaar voor de uitgebreide eCPC-biedstrategie (cost per click) van Microsoft. Dit is de standaardbiedstrategie voor advertenties van Microsoft. U kunt nu een campagne-niveau [!UICONTROL Bid Strategy] voor uw campagnes specificeren. U kunt onder andere [!UICONTROL Manual CPC] en [!UICONTROL Enhanced CPC] kiezen. U kunt [!UICONTROL Enhanced CPC] met onderzoek, bestaande dynamische onderzoeksadvertentie, en het winkelen campagnes gebruiken.<br>Wanneer u een campagne met eCPC toevoegt aan een geoptimaliseerde Advertising Cloud-portfolio, optimaliseert Advertising Cloud de basisbiedingen en — wanneer de optie &#39;De budgetlimieten voor campagnes automatisch aanpassen&#39; is ingeschakeld — het campagnebudget. Microsoft past alle correcties voor biedingen toe en kan de door Advertising Cloud gegenereerde biedingen wijzigen op het moment dat de gebruikersquery wordt uitgevoerd op basis van gegevens en inzichten van eigendomsrechten.<br>De  [!UICONTROL Bid Strategy] aangepaste kolom is beschikbaar in de  [!UICONTROL Campaigns] weergave en in rapporten. |
| [!UICONTROL Search Campaigns]<br> [!UICONTROL Bulksheets] | (Reclamecampagnes van Microsoft) Voor uitgevouwen tekstadvertenties is nu ondersteuning beschikbaar voor een optionele derde kopregel ([!UICONTROL Ad Title 3]) en een optionele tweede beschrijving ([!UICONTROL Description 2]). Ondersteuning is beschikbaar in de weergave [!UICONTROL Ads] en in [!UICONTROL Bulksheets]. |
| [!UICONTROL Advertising Insights] | Er zijn twee nieuwe [!UICONTROL Advertising Insights] beschikbaar:<ul><li>[!UICONTROL Delayed Revenue]: Hiermee wordt de omzettingsvertraging (de tijd die is verstreken tussen een SEM-klik en een daaropvolgende conversie) van een portefeuille gemeten en worden eventuele verschillen in gewogen opbrengsten, ROI en modelnauwkeurigheid wegens de vertraging weergegeven.</li><li>[!UICONTROL Query Cross Matching]: Zoekt instanties van onderzoeksvragen die Google aan meer dan één sleutelwoord aanpaste en verstrekt suggesties voor waar te om verkeer te leiden.</li></ul> |

### Zelfstudies en cursussen voor Advertising Cloud

Bijgewerkt: **23 februari 2021**

| Zelfstudie | Beschrijving |
| -----------| ---------- |
| [Inleiding tot werkruimte en rapportage](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/analytics/analytics-analysis-workspace-a4adc.html) | Leer hoe u Advertising Cloud-gegevens kunt gebruiken om visuele rapporten te maken in Adobe Analytics Analysis Workspace. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Zie Magento Commerce en Open Source [releaseopmerkingen](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html) voor de meest recente releasegegevens.

## ![Pictogram](/assets/target.png)[!DNL Target] {#target}

Zie [[!DNL Target]  releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/target/using/release-notes/target-release-notes.html) voor de recentste releasegegevens.

## ![Pictogram](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is een volledige toepassing voor het beheer van leads en B2B-marketers die de ervaringen van klanten willen transformeren door in elke fase van complexe inkoopritten mee te werken.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo Engage] [releaseopmerkingen](https://docs.marketo.com/display/public/DOCS/Release+Notes) voor de recentste releasegegevens.

### Aanstaande functies

De volgende functies komen gedurende het komende kwartaal beschikbaar:

| Functie | Beschrijving |
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nieuwe op accounts gebaseerde segmentatie</li><li>Dashboardspecifieke filters opslaan</li><li>Bizible-dashboards exporteren als PDF&#39;s</li></ul> |
| Sales Connect | Venster- en Opdrachtcentrum-updates/verbeteringen maken |

### Afgeschafte elementen

* **Assetparameter API &quot;_method&quot;:** Na september 2020 laten Asset API Endpoints `_method` geen queryparameters meer passeren in een POST-body om URI-lengterestricties te omzeilen.
* **Afschaffing van Internet Explorer-ondersteuning:** Vanaf de juli-release op 31 juli 2020 wordt de Marketo Engage-gebruikersinterface niet meer ondersteund in Internet Explorer.

## ![](/assets/document-cloud-24.png) IconDocument Cloud  {#doc-cloud}

Raadpleeg voor hulp bij Documenten Cloud:

* [Adobe Acrobat Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign Learning Hub](https://experienceleague.corp.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud - Meer informatie en ondersteuning](https://helpx.adobe.com/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloud Enterprise  {#creative-cloud}

Nieuwe zelfstudies voor Creative Cloud Enterprise.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| maart 2021 | [Licentie voor benoemde gebruikers begrijpen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/nameduserlicensing.html) | Artikel | Meer informatie over het belang van licentie voor benoemde gebruikers. |
| 5 maart 2021 | [Verlopen serienummer](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/cceserial.html) | Video | Leer de stappen die nodig zijn om ervoor te zorgen dat uw eindgebruikers toegang hebben tot hun Adobe-apps en -services. |
| maart 2021 | [Landing implementeren en beheren - Asset ondersteunen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/deploy/overview-deploy.html) | Video | Leer hoe Creative Cloud for Enterprise aangepaste implementaties en flexibele licentiemogelijkheden ondersteunt, en het werkt met andere Adobe-producten voor bedrijven. |
| 5 maart 2021 | [De kleuren in een Adobe Stock Vector-illustratie aanpassen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/customizecolors.html) | Video | Voeg Pools toe aan elk project met een prachtige illustratie. Vind de perfecte vector in Adobe Stock, en pas dan de kleuren aan het palet van uw project aan gebruikend Adobe Illustrator. |
| 5 maart 2021 | [Een Adobe Stock-presentatiesjabloon aanpassen om er professioneel en toch opvallend uit te zien](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/presentationtemplate.html) | Video | Maak in een paar minuten een mooie gestileerde presentatie met afbeeldingen en sjablonen van Adobe Stock en enkele gebruiksvriendelijke speciale effecten. |
| 5 maart 2021 | [Een animatie voor het laadscherm aanpassen met Adobe Stock en XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/loadingscreen.html) | Video | Pas vectorillustraties vanuit Adobe Stock aan om een animatie voor het koelen van een scherm voor een mobiele app te maken. |
| 5 maart 2021 | [realistische fotosamenstellingen maken met Adobe Stock-afbeeldingen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/realisticcomposite.html) | Video | Breng twee fantastische Adobe Stock-foto&#39;s samen om mensen op uw sociale posts te zetten. |
| 5 maart 2021 | [In een oogwenk inspirerende stemmingsborden maken met Adobe Stock](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/moodboard.html) | Video | Creeer een kaart van de projectomstemming om informatie, ideeën, beelden, en kleurenpaletten aan teams/cliënten door te geven. |
| 5 maart 2021 | [Samenhangende merkbeelden maken met prachtige verlopen en Adobe Stock-middelen](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/brandgradients.html) | Video | Breng animatie in uw nieuwsbrief grafiek met editable vectoren voor Adobe Stock. |
| 5 maart 2021 | [Animaties maken voor e-mail met Adobe Stock en Photoshop](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/animationemail.html) | Video | Laat je e-mails in staat stellen animaties op te heffen met Adobe Stock en Photoshop. |
| 5 maart 2021 | [Een interactieve toeristische foto maken met Adobe Stock en XD](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/stockoverview/stocktutorials/interactivetourismphoto.html) | Video | Maak snel een interactieve foto in uw websiteprototype met Adobe Stock en XD. |
