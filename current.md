---
title: Opmerkingen bij de nieuwste release
description: Leer over de recentste versienota's, nieuwe eigenschappen, en nieuwe documentatie voor  [!DNL Experience Cloud] producten en de diensten. Zoek naar nieuwe Help en zelfstudies over [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: October 2021
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: e3a7e1b80d25a3b9625ca0ee31a07bae674eda6f
workflow-type: tm+mt
source-wordcount: '5113'
ht-degree: 10%

---

# Opmerkingen bij de release van Adobe Experience Cloud - oktober 2021

![Banner](assets/experience-cloud-banner-3.png)

[!DNL Experience Cloud] toepassingen en services worden maandelijks bijgewerkt. Deze pagina is uw centrale locatie voor het zoeken naar de meest recente release-updates, documentatie en zelfstudies voor [!DNL Experience Cloud] en [!DNL Experience Platform]. U kunt ook nieuwe documentatie vinden voor [!DNL Creative Cloud for enterprise] en [!DNL Document Cloud].

>[!NOTE]
>
>Abonneren op de maandelijkse [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om e-mailmeldingen over updates van deze pagina te ontvangen. Deze pagina wordt gedurende de hele maand onderhouden. Raadpleeg daarom regelmatig de updates voor de documentatie van Adobe-bedrijfsproducten en -Experiencen League.

Laatste update: **4 oktober 2021**

* [[!DNL Experience League] Live gebeurtenissen](#events)
* [[!DNL Experience Cloud Central Interface Components] &amp; Beheer](#ecloud)
* [Adobe [!UICONTROL System Status]](#status)
* [[!DNL Adobe Analytics]](#analytics)en [Customer Journey Analytics](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Target]](#target)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Document Cloud]](#doc-cloud)
* [[!DNL Creative Cloud for enterprise]](#creative-cloud)

Hulp nodig? Bezoek [Adobe Experience League](https://experienceleague.adobe.com/#home) om te zoeken naar product- en technische documentatie, door Adobe georganiseerde cursussen, videotutorials, snelle antwoorden, communityinzichten en training onder leiding van instructeurs.

## ![](/assets/experience-league.png) [!DNL Experience League] IconLive-gebeurtenissen {#events}

[!DNL Experience League] Live Events zijn gesprekken met Adobe-experts en speciale gasten die u helpen bij het aandragen van Adobe-technologie. Zie het volgende schema en doe mee met ons live of bekijk eerder opgenomen gebeurtenissen.

| Gebeurtenisdatum | Gebeurtenisnaam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 21 oktober 2021 | TBD | Live video, gebeurtenis | Nadere bijzonderheden. |
| 23 september 2021 | [Experttips om uw vakantiecampagnes te laten uitkomen](https://www.youtube.com/watch?v=bsU1lAv0xes) | Live video, gebeurtenis | Net zoals het nooit te vroeg is om uw vakantiewinkels te starten, is het nooit te vroeg om een welwillend succesvolle campagne voor het op de markt brengen van vakanties te beginnen. Met Adobe Campaign kunt u campagnes ontwerpen, plannen en uitvoeren die ervoor zorgen dat alle wensen van uw organisatie voor vakantie uitkomen.<br>Maar ken je alle tips voor het uitvoeren van campagnes die het jaar met een knal afmaken? Sluit zich aan bij Sandra voor een live gesprek met drie Adobe-experts die daar gezamenlijk deskundig in zijn. |
| 26 augustus 2021 | [Maak uw volgende segment van het publiek slimmer dan ooit](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-02.html?lang=en) | Gebeurtenisopname | Het succes van elke goede marketingcampagne hangt af van het feit dat u zich juist op uw doelgroep richt. Met de nieuwe Adobe Experience Platform [!UICONTROL Segment Builder] kunt u uw volgende publiekssegment bouwen gebruikend profielgegevens en op tijd-gebaseerd gebruikersgedrag over kanalen. Er is geen betere manier om ervoor te zorgen dat uw berichten de mensen bereiken die hen het meest moeten horen. |
| 29 juli 2021 | [Mijn drie favoriete Adobe Analytics-implementatietips](https://experienceleague.adobe.com/docs/experience-league-live-events/events/episodes/exl-live-episode-01.html?lang=en) | Gebeurtenisopname | U hebt hem op het podium gezien op de top. U hebt gehoord dat hij deskundig advies heeft gedeeld op Adobe Insider Tours. U hebt er misschien zelfs baat bij gehad om met hem samen te werken aan uw eigen Adobe Analytics-implementatie. Eric Matisoff brengt zijn drie favoriete Adobe Analytics implementatietips naar dit exclusieve Experience League Live discussie. |

{style=&quot;table-layout:auto&quot;}

Voor meer video&#39;s gaat u naar [Adobe Experience League Channel](https://www.youtube.com/channel/UCN-7ZEctit8Qu01BWeHQ0Fw) op YouTube.

## ![Pictogram](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components]  en beheer {#ecloud}

| Functie | Beschrijving |
| ------- | ------- |
| Unified Search | Met Unified Search kunt u nog steeds objecttypen toevoegen aan de zoekindex. In deze update wordt nu met algemene zoekopdrachten gezocht naar inhoud op het Experience League en naar de volgende Journey Optimizer-objecttypen: <ul><li>Gegevenssets</li><li>Doelen</li><li>Zoekopdrachten</li><li>Schema&#39;s</li><li>Segmenten</li><li>Bronnen</li><li>Aanbiedingen</li><li>Onderdelen</li><li>Berichten</li><li>Journeys</li></ul> |
| Goedkeuring van productgebruiksgegevens | Als u zich voor het eerst aanmeldt, wordt u gevraagd voorkeuren in te dienen voor de manier waarop Adobe u nuttige, gepersonaliseerde inhoud kan bieden, zoals zelfstudies, hulplijnen, snelle tips, aanbevelingen, leervideo&#39;s en meer, op basis van de gebruiksgegevens van uw Experience Cloud-product. Dit verzoek omvat ook een update van uw voorkeuren voor het verzamelen en gebruiken van deze gegevens op <https://experience.adobe.com/preferences>. |
| Navigatie Experience Cloud [!UICONTROL Triggers] | [Experience Cloud ](https://experienceleague.adobe.com/docs/core-services/interface/services/activation/triggers.html?lang=en) Triggersis beschikbaar voor directe navigatie van de toepassingsschakelaar in de kopbal voor provisioned gebruikers. |
| **Opmerking:** geplande update voor interfacenavigatie | In november 2021 wordt de navigatiefunctie _[!UICONTROL Go to Launch / Data Collection]_verwijderd uit <https://experience.adobe.com/implement>. |

{style=&quot;table-layout:auto&quot;}

**Meer Help-bronnen  [!DNL Experience Cloud Central UI Components] en beheer**

* Help voor beheer voor [Central Interface Components](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=en) en gebruikersbeheer
* Opmerkingen bij de Help en release voor [Plaatsen - Locatieservice](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=en)
* Help op [Personen - Klantenkenmerken en Audience Library](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Pictogram](/assets/adobe.png) [!DNL Adobe System Status] {#status}

[!DNL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval, verstoring en onderhoudsgebeurtenissen van Adobe-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

(Zoek de meest recente releasegegevens voor [!DNL Adobe System Status] in de releaseopmerkingen van [21 mei 2020](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/previous/2020/05212020.html?lang=en).)

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **7 oktober 2021**

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Oplossingen in Adobe Analytics](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)
* [Cursussen en zelfstudies voor analyse](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nieuwe functies in Adobe Analytics {#aa-features}

| Functie | Beschrijving | [Algemene beschikbaarheid](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Doeldatum |
| ----------- | ---------- | ------- |
| Visualisaties voor analytische dashboards | Analytics [!UICONTROL Dashboards] introduceert drie nieuwe visualisaties om leidinggevenden en besluitvormers een beter inzicht in hun gegevens te geven. Met de nieuwe [!UICONTROL Doughnut]-, [!UICONTROL Line]- en [!UICONTROL Horizontal]-staafdiagrammen kunt u gemakkelijker gegevens voor afzonderlijke dimensie-items zien, zonder dat u een gedetailleerde weergave hoeft te openen. (Koppeling naar documentatie) | 7 oktober 2021 |
| [!UICONTROL Media Playback Time Spent] | Met Adobe Streaming Media Playback [!UICONTROL Time Spent] beschikt u over een waardevol inzicht in de betrokkenheid van de kijker en kunnen mediaorganisaties diepgaandere, meer gedetailleerde inzichten afleiden met de betrokkenheid van gebruikers van elke minuut door middel van een geavanceerde tijdbestede analyse met de mogelijkheden voor het parseren van dagen. U kunt de hoeveelheid tijd waarnemen die het bekijken van uw media stromen op een specifiek punt in tijd besteedt. U kunt de afspeelduur splitsen op verschillende granulariteiten, zoals nieuwe granulariteiten van 5 minuten, 15 minuten en 30 minuten. [Meer informatie](https://experienceleague.adobe.com/docs/media-analytics/using/media-reports/media-workspace-panels/media-playback-time-spent.html?lang=en) | 18 oktober 2021 |
| Snel [!UICONTROL Segment Builder] | Staat bedrijfsgebruikers toe om basissegmenten in een vereenvoudigde, in-lijn projectwerkschema snel toe te passen. U hoeft niet naar [!UICONTROL Segment Builder] te gaan. [Meer informatie](https://experienceleague.adobe.com/docs/analytics/analyze/analysis-workspace/components/segments/quick-segments.html?lang=en) | 21 oktober 2021 |
| Verbeteringen in Analysis Workspace-linkerrasterzoekfunctie | Bij het zoeken naar het linkerspoor wordt 1) prioriteit gegeven aan exacte overeenkomsten boven brede overeenkomsten, en wordt niet alleen rekening gehouden met de actualiteit en relevantie van componenten. 2) Het markeert overeenkomende tekens om zoekresultaten begrijpelijker te maken. 3) Het is gemakkelijker om classificaties te vinden met betrekking tot een dimensie. 4) Tot slot steunt het vervanging (`*`) zoekend om specifieke componenten gemakkelijker te vinden die u nodig hebt. Opmerking: Het zoeken met jokertekens werkt nog niet op het niveau van dimensie-items. | 21 oktober 2021 |
| Analysis Workspace Donker thema | Donker thema is beschikbaar als weergaveoptie. | 21 oktober 2021 |

{style=&quot;table-layout:auto&quot;}

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | Beschrijving | [Algemene beschikbaarheid](https://experienceleague.adobe.com/docs/analytics/technotes/releases.html?lang=en) - Doeldatum |
| ----------- | ---------- | ----- |
| Report Builder-ondersteuning | Report Builder is een Microsoft® [!DNL Excel] toe:voegen-binnen die u toestaat om douanerapporten gemakkelijk tot stand te brengen uit te geven en te verfrissen gebruikend Customer Journey Analytics gegevens. Met Report Builder en Excel, kunt u eenvoudige maar flexibele belemmering-en-dalingsUI gebruiken om complexe gegevensverzoeken gemakkelijk te bouwen. Met Report Builder voor Customer Journey Analytics kunt u:<ul><li>Verwijs naar bestaande werkbladcellen om de perfecte rijvolgorde, datumbereik of filter te krijgen</li><li>Aangepaste datums maken met gebruik van kalender, celverwijzingen of wiskunde voor datums</li><li>Ontwerp uw lijsten en visualisaties met vertrouwde het formatteren van Excel hulpmiddelen</li><li>Beschikbaar op MacOS, Microsoft 365 voor het web en Microsoft Windows</li></ul> | 7 oktober 2021 |
| Visualisaties voor analytische dashboards | Analytics [!UICONTROL Dashboards] introduceert drie nieuwe visualisaties om leidinggevenden en besluitvormers een nog beter inzicht in hun gegevens te geven. De nieuwe donut-, lijn- en horizontale staafdiagrammen maken het allemaal gemakkelijker om gegevens voor afzonderlijke dimensie-items te zien, zonder dat u een gedetailleerde weergave hoeft te openen. (Koppeling naar documentatie) | 7 oktober 2021 |
| Customer Journey Analytics-auditlogs (alleen API) | Auditlogboeken vormen een belangrijk onderdeel van de naleving van de beveiliging en voor het controleren van gegevens en gebruikersacties. | 7 oktober 2021 |
| Snel [!UICONTROL Filter Builder] | Staat bedrijfsgebruikers toe om basissegmenten in een vereenvoudigde, in-lijn projectwerkschema snel toe te passen. U hoeft niet naar [!UICONTROL Filter Builder] te gaan. [Meer informatie](https://experienceleague.adobe.com/docs/analytics-platform/using/cja-components/cja-filters/quick-filters.html?lang=en) | 21 oktober 2021 |
| Verbeteringen in Analysis Workspace-linkerrasterzoekfunctie | Bij het zoeken naar het linkerspoor wordt 1) prioriteit gegeven aan exacte overeenkomsten boven brede overeenkomsten, en wordt niet alleen rekening gehouden met de actualiteit en relevantie van componenten. 2) Het markeert overeenkomende tekens om zoekresultaten begrijpelijker te maken. 3) Het is gemakkelijker om classificaties te vinden met betrekking tot een dimensie. 4) Tot slot steunt het vervanging (`*`) zoekend om specifieke componenten gemakkelijker te vinden die u nodig hebt. Opmerking: Het zoeken met jokertekens werkt nog niet op het niveau van dimensie-items. | 21 oktober 2021 |
| Analysis Workspace Donker thema | Donker thema is beschikbaar als weergaveoptie. | 21 oktober 2021 |

{style=&quot;table-layout:auto&quot;}

### Oplossingen in Adobe Analytics en CJA {#aa-fixes}

* Oplossing voor een fout met een gepland rapport in Customer Journey Analytics. (AN-271721)
* Correctie van problemen met [!UICONTROL Search Components] in [!UICONTROL Workspace] resulteerde niet in exacte overeenkomsten. (AN-253937; AN-271707)

#### Extra correcties in Adobe Analytics

AN-256136; AN-265420; AN-268455; AN-269768; AN-270276; AN-270287; AN-271601; AN-271969; AN-272056; AN-272111; AN-272457

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| ----------- | ---------- | ---------- |
| EOL voor drie Analytics API-services | 16 september 2021 | Op **28 oktober 2021** zullen de volgende Analytics Legacy API-services hun einddatum bereiken en worden afgesloten. Om het even welke huidige die integratie die gebruikend deze diensten wordt gebouwd houdt op het werken op die dag op.<ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>Adobe heeft een [Oudere API EOL FAQ](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) geleverd om uw vragen te helpen beantwoorden en hulp te bieden bij het volgen van uw stappen. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth-accounts kunnen migreren naar een [Adobe I/O](https://developer.adobe.com/console) Analytics-integratieaccount, die kan worden gebruikt voor toegang tot de API&#39;s voor 1.4 Analytics en 2.0 Analytics. |

{style=&quot;table-layout:auto&quot;}

### AppMeasurement {#appm}

Raadpleeg [AppMeasurement for JavaScript release notes](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en) voor de meest recente updates over AppMeasurement-releases (versie 2.22.2).

### Cursussen en zelfstudies voor analyse {#tutorials-analytics}

Nieuwste cursussen, zelfstudies en artikelen in [!DNL Analytics] en [!UICONTROL Customer Journey Analytics].

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Visualisaties gebruiken om uw gegevensartikelen te vertellen](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2021.1.visualizations) | Cursus | Wie wil de tafel na de tafel scoren om inzichten uit de gegevens te halen? Niet jij! In deze cursus, leer de grondbeginselen over visualisaties, met inbegrip van hoe te om hen aan een project toe te voegen, gegevens in hen te krijgen, en wat elke visualisatie u kan tonen. Leer hoe u de instellingen configureert om precies de benodigde gegevens op te halen. Lees ook wat tips en gebruiksgevallen om u te helpen visualisaties toe te passen op uw normale analyse. |

{style=&quot;table-layout:auto&quot;}

### Bronnen voor Analytics Help

* [Adobe Analytics-productdocumentatie en -Tutorials](https://experienceleague.adobe.com/docs/analytics.html)

## ![Pictogram](/assets/audience-manager.png) Audience Manager {#aam}

Nieuwe functies in Audience Manager - bijgewerkt **14 september 2021**:

| Functie | Beschrijving |
| ------- | ------- |
| Toestemming voor het verzamelen van gegevens voor mobiele id&#39;s | Toegevoegde ondersteuning voor toestemming voor gegevensverzameling voor mobiele id&#39;s. Om van deze update te kunnen profiteren, moeten klanten een upgrade uitvoeren naar [AEP Mobile SDK iOS Core 2.8.0](https://aep-sdks.gitbook.io/docs/foundation-extensions/mobile-core/mobile-core-release-notes#november-4-2020) of hoger. |

## ![Pictogram](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Bevat informatie over releaseupdates en nieuwe documentatie voor Experience Platform en [!UICONTROL Mobile SDK].

**29 september 2021**

| Functie | Beschrijving |
| ------- | ------- |
| [[!UICONTROL Data Landing Zone]](https://experienceleague.adobe.com/docs/experience-platform/sources/connectors/cloud-storage/data-landing-zone.html) | [!UICONTROL Data Landing Zone] is een  [!DNL Platform]provisioned  [!UICONTROL Azure Blob Store] die één veilige en tijdelijke opslag per zandbak toestaat om dossiers in Experience Platform te brengen. |
| Ondersteuning voor streamingbronnen voor [gegevensvoorbereiding](https://www.adobe.com/go/monitor-streaming-dataflows-en) | Streaming bronnen ondersteunen nu gegevensvoorbereiding, zodat u een JSON-bronschema kunt bieden om niet-XDM-compatibele brongegevens toe te wijzen aan een doel-XDM-schema. |
| [Niet-vervallende referenties](https://experienceleague.adobe.com/docs/experience-platform/query/ui/credentials.html) | Niet-vervallende referenties voor [!UICONTROL Query Service]-gebruikers maken duurdere verbindingen met externe clients mogelijk in plaats van de aanmeldingsgegevens elke 24 uur te vernieuwen. |
| [[!UICONTROL Destination SDK]](https://www.adobe.com/go/destination-sdk-overview-en) | Gebruik [!UICONTROL Destination SDK] om met [!DNL Platform] te integreren en aan de steeds groeiende bestemmingscatalogus bij te dragen. Toegang tot deze functie is alleen beschikbaar voor klanten die Experience Platforms activeren. |

Zie [Opmerkingen bij de release van het Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html) voor alle details.

### Zelfstudies en cursussen voor Experience Platforms {#tutorials-platform}

Nieuwste video&#39;s, zelfstudies of cursussen gepubliceerd voor Experience Platform en services.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [[!DNL Platform] Beheer](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-A-1-2021.1.admin) | Cursus | Leer over beleidsactiviteiten voor Experience Platform, met inbegrip van toestemming en zandbakbeheer. |

{style=&quot;table-layout:auto&quot;}

### Adobe Mobile SDK

Zie [Opmerkingen bij de release en logbestanden voor wijzigingen](https://aep-sdks.gitbook.io/docs/release-notes) voor de Adobe Experience Platform Mobile SDK&#39;s.

## ![](/assets/experience_platform_appicon_24.png) IconJourney Optimizer {#journey-opt}

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen vindt u in de [Opmerkingen bij de release van Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

### Zelfstudies en cursussen voor Journey Optimizer {#tutorials-ajo}

Nieuwste Journey Optimizer-zelfstudies:

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Gegevens configureren en beheren  [!DNL Journey Optimizer] voor gegevensengineers](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.2) | Cursus | Leer hoe u de gegevens die nodig zijn voor het beheer van reizen in Journey Optimizer kunt configureren en beheren. |
| Oktober 2021 | [Ga aan de slag  [!DNL Journey Optimizer] met Reisbeheerders en -managers](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-U-1-2021.1) | Cursus | Leer alles wat je moet weten om je eerste reis te maken. |
| Oktober 2021 | [ [!DNL Journey Optimizer] Configuratie voor beheerders van reizen](https://experienceleague.adobe.com/?recommended=JourneyOptimizer-A-1-2021.1) | Cursus | Begrijp de [!DNL Journey Optimizer] architectuur en de punten van integratie. Leer hoe u [!DNL Journey Optimizer] configureert. |

{style=&quot;table-layout:auto&quot;}

### Meer bronnen voor [!DNL Journey Optimizer]

[Help Center](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)  -  [Opmerkingen bij](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)  de release -  [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html)

## ![Pictogram](/assets/experience_platform_appicon_24.png) [!DNL Journey Orchestration] {#journey-orch}

Het Experience Platform van het gebruik om de reis van een klant bij schaal over ervaringskanalen te ordenen, door intelligent de behoeften van elk individu in echt te voorzien - tijd.

### Laatste [!DNL Journey Orchestration] productreleases

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen vindt u in de [[!DNL Journey Orchestration] Opmerkingen bij de release](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html).

#### Meer bronnen voor [!DNL Journey Orchestration]

[Help Center](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html)  - Opmerkingen bij de  [release](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html)  -  [Hoe kan ik-video](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=html?lang=nl) &#39;s -  [Meest recente documentatieupdates](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html)

## ![Beslissing ](/assets/experience_platform_appicon_24.png) IconOffer {#offer-decisioning}

[!UICONTROL Offer Decisioning] is een service die is geïntegreerd met Adobe Experience Platform. Gebruik [!UICONTROL Offer Decisioning] om uw klanten de beste aanbieding en ervaring op alle aanraakpunten op het juiste moment te bieden.

### Nieuwste productreleases in de Offer decisioning

Meer informatie over de recentste mogelijkheden, verbeteringen, en moeilijke situaties in [de Nota&#39;s van de Versie van de Offer decisioning](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html).

#### Meer bronnen voor [!UICONTROL Offer Decisioning]

[Help Center](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started/starting-offer-decisioning.html?lang=nl)  - Opmerkingen bij de  [release](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html)  -  [Hoe kan ik-video](https://experienceleague.adobe.com/docs/offer-decisioning-learn/tutorials/overview.html) &#39;s -  [Meest recente documentatieupdates](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html)

## ![Pictogram](/assets/aem.png) Experience Manager {#aem}

Adobe raadt aan de pagina [Updates en roadmaps](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html) van de release van de Experience Manager te bezoeken om actuele informatie over de release te blijven.

### Community

* [Adobe Developers Live](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)  | 4-5 oktober 2021, 7:00 PDT

   Adobe Developers Live brengt Adobe-ontwikkelaars en -ontwikkelaars met uiteenlopende achtergronden en een eigen functie met elkaar in contact om ongelofelijke end-to-end ervaringen te creëren. Deze tweedaagse conferentie biedt belangrijke updates voor ontwikkelaars, technische sessies en mogelijkheden voor gemeenschapsnetwerken.

   Adobe-productteams in Adobe Experience Cloud, Document Cloud en Creative Cloud laten de nieuwste technologische vooruitgang zien en ontwikkelaarsgereedschappen die het ontwerp, de workflows voor het maken van inhoud, documentservices en het beheer van klantervaringen in alle bedrijfstakken ondersteunen.

   Adobe heeft 20 Experience Managers geplande sessies. Spreid het woord uit!

   * [Volledige sessielijst](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/adobe-developers-live-october-2021-complete-session-list/m-p/423041#M120517)
   * [Gratis registratie - Aanmelden bij RSVP](https://developerevents.adobe.com/events/details/adobe-developer-events-developer-experience-presents-adobe-developers-live/?cid=Kautuk)
   * [Adobe Developers Live Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/registration-for-adobe-developers-live-is-now-open-october-4-5/td-p/422127)

### Nieuwe cursussen en tutorials voor Experience Manager {#tutorials-aem}

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Aan de slag met XML-documentatie](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.xmldocs) | Cursus | Leer hoe u inhoud maakt, ordent, ontwerpt en publiceert met XML-documentatie voor Adobe Experience Manager. |
| Oktober 2021 | [Creatieve workflows beheren  [!DNL Workfront] met Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.2.assets.essentials) | Cursus | Leer hoe Adobe [!DNL Workfront] en Experience Manager. |
| Oktober 2021 | [Aan de slag met AEM Assets Essentials](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2021.assets.essentials) | Cursus | Leer hoe AEM Assets Essentials het beheer van bedrijfsmiddelen kan stroomlijnen voor uw organisatie. |
| Oktober 2021 | [[!UICONTROL Content Transfer Tool]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/content-transfer-tool.html?lang=en) | Video | Leer hoe u met [!UICONTROL Content Transfer Tool] inhoud kunt migreren naar AEM als Cloud Service vanuit AEM 6.3+. |
| Oktober 2021 | [[!UICONTROL Bulk Import Service]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/content-migration/bulk-import-service.html?lang=en) | Video | Leer hoe AEM als Cloud Services [!UICONTROL Bulk Import Service] kan worden gebruikt om activa uit niet-AEM bronnen in te voeren. |
| Oktober 2021 | [Communicatie (uitvoerservice)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/communications.html?lang=en) | Video | Leer hoe AEM Forms als Cloud Service het communicatie gebruiksgeval steunt. |
| Oktober 2021 | [Digitale inschrijving](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/digital-enrollment.html?lang=en) | Video | Meer informatie over hoe AEM Forms als Cloud Service het gebruik van Digital Enrollment ondersteunt. |
| Oktober 2021 | [Gereedschappen  [!UICONTROL Cloud Acceleration Manager] gebruiken](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/using.html) | Video | Een doorloopprocedure voor het gebruik van [!UICONTROL Cloud Acceleration Manager]-gereedschappen. |
| Oktober 2021 | [Navigeren  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/navigating.html) | Video | Verken de navigatie-ervaring van [!UICONTROL Cloud Acceleration Manager] voor Experience Manager als Cloud Service. |
| Oktober 2021 | [[!UICONTROL Asset Workflow Migration] Gereedschap](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/asset-workflow-migration-tool.html) | Video | Leer hoe u met het gereedschap [!UICONTROL Asset Workflow Migration] uw bestaande AEM Assets Workflows kunt migreren naar AEM als Cloud Service. |
| Oktober 2021 | [[!UICONTROL Index Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/index-converter.html) | Video | Leer hoe [!UICONTROL Index Converter] automatisch bestaande AEM indexdefinities omzet om als Cloud Service compatibel te worden AEM. |
| Oktober 2021 | [[!UICONTROL Dispatcher Converter]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/dispatcher-converter.html) | Video | Leer hoe [!UICONTROL Dispatcher Converter] automatisch bestaande AEM Dispatcher configuraties bijwerken om als Cloud Service compatibel te worden AEM. |
| Oktober 2021 | [[!UICONTROL Code Repository Modernizer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-repository-modernizer.html) | Video | Leer hoe [!UICONTROL Core Repository Modernizer] automatisch bestaande AEM Gemaakt projecten om als Cloud Service compatibel AEM bij te werken. |
| Oktober 2021 | [[!UICONTROL Code Refactoring Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/code-refactoring-tools.html) | Video | Leer hoe de AEM [!UICONTROL Code Refactoring Tools] de conversie van bestaande AEM projecten automatiseren om als Cloud Service compatibel te worden AEM. |
| Oktober 2021 | [[!UICONTROL Content Transfer Tool]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/content-transfer-tool.html) | Video | Leer hoe u met [!UICONTROL Content Transfer Tool] inhoud efficiënt kunt verplaatsen van AEM 6.5 naar AEM als Cloud Service. |
| Oktober 2021 | [De uitvoeringsfasen van  [!UICONTROL Cloud Acceleration Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/implementation-phase.html) | Video | Bekijk en begrijp de belangrijkste implementatiefasen of ga naar AEM als Cloud Service met [!UICONTROL Cloud Acceleration Manager]. |
| Oktober 2021 | [Gereedheid en  [!UICONTROL Best Practice Analyzer]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/readiness-and-best-practice-analyzer.html) | Video | Leer hoe [!UICONTROL Best Practice Analyzer] u kan helpen zich voor te bereiden om zich van AEM op prem of de Beheerde Diensten van Adobe aan Experience Manager als Cloud Service te bewegen. |
| Oktober 2021 | [Inleiding tot Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/cloud-acceleration-manager/introduction.html) | Video | Leer hoe u [!UICONTROL Cloud Acceleration Manager] kunt helpen snel en gemakkelijk naar Experience Manager als Cloud Service te bewegen. |
| Oktober 2021 | [AEM Forms als Cloud Service - Verplaatsen naar AEM CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-forms/introduction.html?lang=en) | Video | Meer informatie over gebruiksgevallen en functies die door AEM Forms als Cloud Service worden ondersteund. |
| Oktober 2021 | [Problemen oplossen AEM als Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/troubleshooting.html?lang=en) | Video | Leer hoe te om de AEM SDK problemen op te lossen en te zuiveren, AEM als Cloud Service en, bouwt en proces opstelt. |
| Oktober 2021 | [AEM  [!UICONTROL Assets Microservices] - Naar AEM als Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/asset-compute-microservices.html?lang=en) | Video | Leer hoe u met AEM Assets als asset compute-microservices van een Cloud Service automatisch en efficiënt een uitvoering voor uw middelen kunt genereren en deze rol van de traditionele AEM-workflow kunt vervangen. |
| Oktober 2021 | [Zoeken en indexeren](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/search-and-indexing.html?lang=en) | Video | Leer over de AEM als indexen van het het onderzoek van de Cloud Service, hoe te om AEM 6 indexdefinities om te AEM als Cloud Service compatibel, en hoe te om indexen op te stellen aan AEM als Cloud Service. |
| Oktober 2021 | [[!UICONTROL Dispatcher]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/dispatcher.html?lang=en) | Video | Leer over AEM [!UICONTROL Dispatcher] voor AEM als Cloud Service, die zich op opmerkelijke veranderingen van [!UICONTROL Dispatcher] voor AEM 6, het [!UICONTROL Dispatcher] omzettingshulpmiddel concentreert en hoe te om de SDK van de Hulpmiddelen van de Verzender te gebruiken. |
| Oktober 2021 | [[!UICONTROL Cloud Manager]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/cloud-manager.html?lang=en) | Video | Leer meer over Cloud Manager voor AEM als Cloud Service en de verschillen met Cloud Manager voor AEM op Adobe Manager Services (AMS). |
| Oktober 2021 | [Onboarding van AEM as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/onboarding.html?lang=en) | Video | Leer over aan boord gaan om als Cloud Service te AEM die van de contractfase helemaal door vestiging de milieu&#39;s begint met [!UICONTROL Cloud Manager]. |
| Oktober 2021 | [Modernisering opslagplaats](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/repository-modernization.html?lang=en) | Video | Meer informatie over de modernisering van de opslagplaats, muteerbare en onveranderlijke inhoud, de pakketstructuur en het CLI-hulpmiddel voor de modernisering van de opslagplaats. |
| Oktober 2021 | [AEM [!UICONTROL Modernization Tools]](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/aem-modernization-tools.html?lang=en) | Video | Leer hoe AEM [!UICONTROL Modernization Tools] worden gebruikt om een bestaand AEM project en inhoud te bevorderen om als Cloud Service compatibel te worden AEM. |
| Oktober 2021 | [AEM-moderniseringstools](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/introduction.html?lang=en) | Video | Leer hoe te om anders over AEM als Cloud Service implementaties te denken. |
| Oktober 2021 | [Best Practice Analyzer en Cloud Acceleration Manager](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/migration/moving-to-aem-as-a-cloud-service/bpa-and-cam.html?lang=en) | Video | Leer hoe de Analysator van de Beste praktijken (BPA) en de Manager van de Versnelling van de Wolk (CAM) een aangepaste gids voor het migreren aan AEM als Cloud Service verstrekt. |
| Oktober 2021 | [Versiegeschiedenis onderhouden](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/versions.html) | Video | Leer hoe u met Adobe Workfront en Experience Manager [!UICONTROL Assets Essentials] versies van [!DNL Workfront] documenten en Assets Essentials-elementen kunt onderhouden. |
| Oktober 2021 | [Documenten en koppelingselementen verzenden](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/link-send.html?lang=en) | Video | Leer hoe u Workfront-documenten naar Assets Essentials verzendt en Assets Essentials-middelen koppelt aan Workfront. |
| Oktober 2021 | [De integratie configureren](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/configure.html?lang=en) | Video | Leer hoe u de integratie met Adobe Workfront en Assets Essentials configureert. |
| Oktober 2021 | [Wat is een digitale handtekening](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Meer informatie over digitale handtekeningen op basis van certificaten, die voldoen aan de strengste wettelijke voorschriften ter wereld en de hoogste mate van zekerheid bieden over de identiteit van een ondertekenaar. |
| Oktober 2021 | [Segment Builder in Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/components/segmentation/segment-builder-overview.html?lang=en#) | Video | U kunt uw gegevens in Adobe Analytics segmenteren en scheiden. Deze video doorloopt u [!UICONTROL Segment Builder] en geeft een basisoverzicht. |
| Oktober 2021 | [Metagegevens toewijzen](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/workfront/map-metadata.html?lang=en) | Video | Leer hoe u de toewijzing van metagegevens tussen Workfront-velden en Assets Essentials-eigenschappen configureert en hoe u Assets Essentials configureert om de toegewezen waarden weer te geven. |

{style=&quot;table-layout:auto&quot;}

### Experience Manager-releasegegevens {#aem-links}

De nota&#39;s van de versie en andere verbindingen van de versieinformatie voor Experience Manager zijn hier:

* Aanvullende informatie over[[!DNL Experience Manager as a Cloud Service] ](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?lang=en)
* [[!DNL Experience Manager as a Cloud Service] releasegegevens](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/release-notes/home.html?lang=en)
* Aanvullende informatie over[[!DNL Experience Manager Cloud Manager] ](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=en)
* [Releaseopmerkingen bij de service Geautomatiseerde conversie van formulieren](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=en)
* [Experience Manager 6.5 Opmerkingen bij de release Service Pack](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/service-pack/sp-release-notes.html?lang=en)
* [Experience Manager 6.4 Opmerkingen bij de release Cumulative Fix Pack](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=en)
* Aanvullende informatie over[[!DNL Experience Manager Assets Dynamic Media] ](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=en)
* Aanvullende informatie over[[!DNL Experience Manager Brand Portal] ](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=en)
* [Opmerkingen bij de release van Experience Manager-bureaublad](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=en)
* Aanvullende informatie over[[!DNL Experience Manager Dispatcher] ](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=en)
* [Releaseopmerkingen bij Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html)
* [Releaseopmerkingen bij Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html)

### Andere Help-bronnen voor Experience Manager

* [[!DNL Experience Manager as a Cloud Service] Hulplijnen](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/landing/home.html?lang=en)
* [Experience Manager 6.5 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=en)
* [Experience Manager 6.4 - Introductiepagina](https://experienceleague.adobe.com/docs/experience-manager-64.html)
* [Experience Manager 6.3 Introductie &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html)
* [Experience Manager 6.2 Thuis leren &amp; ondersteuning](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Oudere versies van de Documentatie van de Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [[!DNL Cloud Manager] Handboek](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=en)
* [[!DNL Dynamic Media Classic] Help Home](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=en)
* [Documentatie Experience Manager: Recente updates](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=en#aem-as-a-cloud-service)

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwste productreleases van campagne

Meer informatie over de nieuwste mogelijkheden, verbeteringen en oplossingen die worden vrijgegeven:

* [Opmerkingen bij de release Campagne v8](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html)
* [Opmerkingen bij de release Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html)
* [Opmerkingen bij de release Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html)

### Nieuwe [!UICONTROL Campaign] cursussen en zelfstudies {#tutorials-campaign}

Nieuwste zelfstudies en cursussen voor Adobe Campaign.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Geavanceerde campagnes bouwen met Adobe Campaign V8 voor zakelijke gebruikers](https://experienceleague.adobe.com/?recommended=Campaign-U-1.2021.1.v8) | Cursus | Leer hoe u geavanceerde marketingcampagnes configureert en uitvoert met Adobe Campaign V8. Leer over de eerste vereisten, bouw en vorm geavanceerde campagnes, leveringen, en beheer abonnementen. |
| Oktober 2021 | [SOAP API&#39;s gebruiken in workflows - Inleiding](https://experienceleague.adobe.com/docs/campaign-learn/use-soap-apis/introduction.html?lang=en) | Tutorial | Leer hoe u Adobe Campaign Soap API&#39;s kunt gebruiken en een geavanceerde leveringsworkflow kunt maken op basis van de gegevens die via de API zijn ontvangen. |
| Oktober 2021 | [Gebeurtenissen maken](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/create-events.html?lang=en) | Zelfstudie | Leer hoe te om een gebeurtenis te vormen, specificeer het het stromen eindpunt en de lading voor een gebeurtenis. |
| Oktober 2021 | [Gegevensbronnen configureren](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/journey-configuration/configure-data-sources.html?lang=en) | Zelfstudie | Begrijp wat een gegevensbron is en leer hoe te om Experience Platform en externe gegevensbronnen te vormen. |
| Oktober 2021 | [Hoofdletters/kleine letters gebruiken - Burgerberichten](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/create-journeys/use-case-burst-message.html?lang=en) | Zelfstudie | Begrijp de toepasselijke gebruiksscenario&#39;s voor burst-messaging. Leer hoe u een journey voor burst-berichten configureert en welke best practices u toe kunt passen. |

{style=&quot;table-layout:auto&quot;}

### Help-informatie en bronnen voor Campaign

* Adobe Campaign v8: [Help Center](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html) - [Implementatiehulplijnen](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html)
* Adobe Campaign Standard: [Campaign Standard-documentatie](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=nl) - [Release-notities](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html) - [Release-planning](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatiedetails](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Campaign Classic v7-documentatie](://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=nl) - [Opmerkingen bij de release](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html) - [Nieuwste documentatieupdates](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl) - [Releaseopmerkingen](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=en) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=nl) / [Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=nl)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Release-aantekeningen voor [!DNL Adobe Advertising Cloud].

* [Nieuwe functies in [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Nieuwe functies in [!DNL Advertising Cloud Search]](#adcloud-search)

### Nieuwe functies in [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Laatst bijgewerkt: **28 september 2021**

| Functie | Beschrijving |
| ------- | ----------- |
| Weergaven van Campagnebeheer | Een kolom &quot;[!UICONTROL Creation date]&quot; is nu beschikbaar in aangepaste kolomsets voor de weergaven [!UICONTROL Campaigns], [!UICONTROL Packages], [!UICONTROL Placements] en [!UICONTROL Ads]. U kunt de weergaven [!UICONTROL Placements] en [!UICONTROL Ads] ook filteren door [!UICONTROL Creation date]. |
| Door programmacode gegarandeerde deals | (8 September versie) U kunt [!UICONTROL Max Bid] voor de standaardplaatsing voor een programmatic gewaarborgde (PG) overeenkomst nu uitgeven. Omdat PG-deals echter altijd een vaste CPM hebben, dienen alleen internationale clients de [!UICONTROL Max Bid] te bewerken om rekening te houden met valutawisselkosten. |
|  | (8 september) Gebruikers met de machtiging &quot;[!DNL FreeWheel Programmatic Guaranteed]&quot; kunnen nu een advertentie verzenden naar [!DNL FreeWheel Programmatic Creative API] vanuit de weergave [!UICONTROL Ads] of de weergave [!UICONTROL Placements]. U kunt nog steeds een advertentie verzenden vanuit de weergave [!UICONTROL Deals]. |

{style=&quot;table-layout:auto&quot;}

### Nieuwe functies in [!DNL Advertising Cloud Search] {#adcloud-search}

Laatst bijgewerkt: **28 september 2021**

| Functie | Beschrijving |
| ------- | ----------- |
| Advertising Insights | Aanvullende inzichten zijn beschikbaar in de bètamodus. |

{style=&quot;table-layout:auto&quot;}

## ![Pictogram](/assets/magento.png) [!DNL Commerce]  (Magento) {#magento}

Raadpleeg de volgende koppelingen voor de release Adobe Commerce:

* [Adobe Handel en Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite voor Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

## ![Pictogram](/assets/target.png) [!DNL Target] {#target}

Laatst bijgewerkt: **3 augustus 2021**

Zie [[!DNL Target]  releaseopmerkingen](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=en) voor de recentste releasegegevens.

## ![Pictogram](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is een volledige toepassing voor het beheer van leads en B2B-marketers die de ervaringen van klanten willen transformeren door in elke fase van complexe inkoopritten mee te werken.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo Engage] [releaseschema](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=en) voor de meest recente informatie over de releaseschema en opmerkingen bij de release.

## ![Pictogram](/assets/workfront.png) [!DNL Workfront] {#workfront}

Adobe is een uniforme toepassing voor werkbeheer voor het delen van ideeën, het maken van inhoud, het beheren van complexe processen en het uitvoeren van hun beste werk.[!DNL Workfront]

Zie de pagina [[!DNL Workfront] releases](https://one.workfront.com/s/product-releases) voor een vervollediging van de meest recente informatie voor alle producten.

## ![](/assets/document-cloud-24.png) IconDocument Cloud {#doc-cloud}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Adobe Document Cloud.

### Cursussen en zelfstudies voor Documenten Cloud {#tutorials-doc-cloud}

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| Oktober 2021 | [Wat is een digitale handtekening?](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-signing/sign-with-a-digital-signature.html?lang=en) | Video | Leer hoe u digitale id&#39;s van over de hele wereld kunt gebruiken met Adobe Sign. |
| Oktober 2021 | [Aan de slag met Adobe Sign voor nieuwe afzenders](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/getting-started/getting-started-sending/new-sender.html) | Video | Als u Adobe Sign nog niet eerder hebt gebruikt, is deze zelfstudie een mooi beginpunt. Deze uitgebreide zelfstudie richt zich op alle basisbeginselen om u snel aan de slag te krijgen met Adobe Sign. |
| Oktober 2021 | [PDF-opmerkingen laden in InDesign](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/60-second/indesign.html) | Video | Leer in deze videozelfstudie van 60 seconden hoe u PDF-opmerkingen weer in InDesign laadt na een gedeelde Acrobat-revisie. Met deze digitale workflow kunt u revisies uitvoeren in de recordtijd. |
| Oktober 2021 | [Een digitale id ophalen van [!DNL Intesi Group]  (gekwalificeerd)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-qualified.html) | Video | Leer hoe u een gekwalificeerd digitaal ondertekeningscertificaat ophaalt bij [!DNL Intesi] Group. Als uw identiteit eenmaal is geregistreerd en geverifieerd, geeft [!DNL Intesi] Group u een digitale id weer waarmee een Adobe Sign-cloudhandtekening wordt toegepast. |
| Oktober 2021 | [Ondertekenen met [!DNL Intesi Group]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-sign.html) | Video | Leer hoe u uw digitale id voor Intesi Group gebruikt om uw identiteit te verifiëren en een externe digitale handtekening (cloudhandtekening) op een document te autoriseren. |
| Oktober 2021 | [Een digitale id ophalen van [!DNL Intesi Group]  (geavanceerd)](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/intesi/intesi-advanced.html) | Video | Leer hoe u een geavanceerd digitaal ondertekeningscertificaat kunt verkrijgen van Intesi Group. Zodra u bent geregistreerd en uw identiteit is geverifieerd, geeft Intesi Group u een digitale id weer waarmee u een Adobe Sign-cloudhandtekening kunt toepassen. |
| Oktober 2021 | [Ondertekenen met [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-sign.html) | Video | Leer hoe u uw [!DNL Digidentity] digitale id kunt gebruiken om uw identiteit te verifiëren en een externe digitale handtekening (cloudhandtekening) op een document te autoriseren. |
| Oktober 2021 | [Een digitale id ophalen van [!DNL Digidentity]](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/digital-id/digidentity/digidentity-reg.html) | Video | Leer hoe u een digitaal ondertekeningscertificaat ophaalt van [!DNL Digidentity]. Nadat uw identiteit is geregistreerd en geverifieerd, geeft [!DNL Digidentity] u een digitale id weer die wordt gebruikt om een Adobe Sign-cloudhandtekening toe te passen. |
| Oktober 2021 | [Verschillen tussen twee PDF&#39;s detecteren](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/compare.html) | Video | Maak nooit de fout om met de verkeerde versie van een bestand te werken. Snel en nauwkeurig de verschillen tussen twee PDF-bestanden detecteren om de workflows voor documentrevisie te verbeteren. |
| Oktober 2021 | [PDF-inhoud maken tijdens bladeren met Microsoft® Edge](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/edge.html) | Video | Leer hoe u webpagina&#39;s direct naar PDF kunt archiveren met de Adobe Acrobat-extensie voor Microsoft® Edge. Dit Windows-enige hulpmiddel is van onschatbare waarde voor onderzoeksprojecten en offline het bekijken van web-based informatie. |
| Oktober 2021 | [E-mailberichten en bijlagen converteren naar PDF in Outlook](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/integrations/outlook.html) | Video | Leer hoe u e-mailberichten en bijlagen in Outlook voor uw projecten kunt archiveren tot PDF. Leer professioneler en veiliger informatie te leveren door bijlagen automatisch te converteren naar PDF. Dit gereedschap is alleen beschikbaar voor Windows. |

{style=&quot;table-layout:auto&quot;}

Raadpleeg voor hulp bij Documenten Cloud:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html)
* [Adobe Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html)
* [Document Cloud - Meer informatie en ondersteuning](https://helpx.adobe.com/support/document-cloud.html)

## ![](/assets/creative-cloud-24.png) IconCreative Cloud voor ondernemingen {#creative-cloud}

Zie [Creative Cloud voor zelfstudies voor bedrijven](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=en) voor de meest recente zelfstudies.
