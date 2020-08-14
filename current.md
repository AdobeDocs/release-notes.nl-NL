---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Releaseopmerkingen bij Adobe Experience Cloud
doc-type: release notes
last-update: August 2020
author: mfrei
translation-type: tm+mt
source-git-commit: dc785dde4088570baa004f5296d134d16a503562
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Opmerkingen bij de release van Adobe Experience Cloud - augustus 2020

![Banner](/assets/experience-cloud-banner-3.png)

Deze pagina beschrijft nieuwe functies, correcties en belangrijke kennisgevingen in [!DNL Adobe Experience Cloud]. Ook worden nieuwe documentatie, trainingscursussen en videotutorials onder de aandacht gebracht om u te helpen optimaal te profiteren van Experience Cloud.

>[!NOTE]
>
>Meld u aan voor de [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases.

**Releasedatum: 13 augustus 2020**

De productreleasedatums kunnen variëren. Controleer regelmatig of er updates zijn.

Laatste update: **13 augustus 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) (Bijgewerkt op 13 augustus 2020) en [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/nl-NL/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/nl-NL/primetime/release-notes/home.html)

Hulp nodig? Bezoek [Adobe Experience League](https://experienceleague.adobe.com/#home) om te zoeken naar product- en technische documentatie, door Adobe georganiseerde cursussen, videotutorials, snelle antwoorden, communityinzichten en training onder leiding van instructeurs.

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Zie [21 mei 2020](c-legacy-releases/2020/05212020.md#status) voor de meest recente releasegegevens.

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud-interface {#ecloud}

Zie de [vorige versienota&#39;s](c-legacy-releases/2020/07162020.md#ecloud) van juli voor de recentste versieinformatie over de bijgewerkte interface en verenigd productdomein.

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release-opmerkingen voor [!DNL Experience Platform] en applicatieservices, waaronder [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], en beveiligingsbulletins.

Latest release date: **July 15, 2020**

Zie [Opmerkingen bij de release van Experience Platform](https://docs.adobe.com/content/help/nl-NL/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) voor de meest recente informatie over Experience Platform.

## ![Pictogram](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

### Nieuwe cursussen en tutorials voor Campaign

Nieuwe video&#39;s, tutorials of cursussen die in de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| ----------- | ---------- | ---------- |---------- |  
| 10 juli 2020 | [Dagboekevenementen aan Adobe Experience Platform melden](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/reporting-step-events-to-adobe-experience-platform.html) | Zelfstudie | Leer hoe de gebeurtenissen van de reisstap zijn en welke gegevensstappen automatisch op Experience Platform worden gecreeerd en hoe te om deze te onderzoeken. |

### Aanvullende bronnen voor Journey Orchestration

[Documentatie](https://docs.adobe.com/content/help/nl-NL/journeys/using/journey-orchestration-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html) - [Instructievideo&#39;s](https://docs.adobe.com/content/help/nl-NL/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Nieuwe functies in Media Analytics](#media-aa)
* [Oplossingen in Adobe Analytics](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)
* [AppMeasurement](#appm)

### Nieuwe functies in Adobe Analytics {#aa-features}

(Bijgewerkt op 13 augustus 2020)

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- |-------|
| [!UICONTROL Cross-Device Analytics]: Beschikbaarheid in EMEA en APAC | 31 augustus 2020 | [Cross-Device Analytics](https://docs.adobe.com/content/help/en/analytics/components/cda/overview.html) en een persoonlijke grafiek zijn beschikbaar voor klanten in EMEA en APAC. |
| Verbetering van het op het veld gebaseerde stitching in [!UICONTROL Cross-Device Analytics] (beschikbaar in Amerika en EMEA) | 31 augustus 2020 | Deze vereenvoudigde implementatie voor nieuwe [!UICONTROL Cross-Device Analytics] klanten geeft u de optie om vast te maken op basis van een gebruikers-id die is opgeslagen in een veld Analytics (prop of eVar) in plaats van apparaatgrafiek (co-op of private) te gebruiken. De verbetering schrapt het vereiste om ECID uit te voeren en schrapt het vereiste om identiteitskaart toe te passen synchroniseren voor doeleinden van CDA. (Voor bepaalde andere functies zijn ECID- en ID-synchronisatie nog steeds vereist.) |
| (Vroege aankondiging) Werkruimte: Download 50 kB items voor één dimensie | 17 september 2020 | U kunt 50.000 items downloaden voor één dimensie in een vrije-vormtabel, met toegepaste segmenten en filters. Hierdoor hebt u toegang tot meer dan 400 rijen gegevens buiten Analysis Workspace. |

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- |-----|
| [!UICONTROL Identity Map] optie voor persoon-id | 26 juni 2020 | [!UICONTROL Identity Map] is een structuur van kaartgegevens waarmee u sleutelwaardeparen kunt uploaden als onderdeel van het maken van een verbinding in [!UICONTROL Customer Journey Analytics]. De sleutels zijn identiteitsnaamruimten en de waarde is een structuur die de identiteitswaarde bevat. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics-platform/using/cja-connections/create-connection.html#use-identity-map-as-a-person-id) |

### Nieuwe functies in [!UICONTROL Media Analytics] {#media-aa}

Releasedatum: **16 juli 2020**

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- | ---------- |
| [Ondersteunde apparaten en platforms](https://docs.adobe.com/content/help/nl-NL/media-analytics/using/supported-devices.html) | 18 juni 2020 | De [!UICONTROL Media Launch Extension] met AEP SDK ondersteunt nu de volgende OTT-apparaten:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android-tv</li></ul> |
| [Player-status bijhouden](https://docs.adobe.com/content/help/nl-NL/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 mei 2020 | [!UICONTROL Media Analytics]-klanten kunnen tijdens het afspelen viewerinteracties vastleggen met een standaardset oplossingsvariabelen voor volledig scherm, ondertiteling, dempen, beeld-in-beeld en scherpstelling. U kunt desgewenst ook aangepaste Player-statussen te maken. [!UICONTROL Player State Tracking] variabelen zijn nu beschikbaar voor rapportage in [!UICONTROL Analysis Workspace]. Voor deze functie is een van de volgende opties vereist: <ul><li>Media [!DNL JavaScript] SDK 3.0 of hoger</li><li>Voor gebruik met de [!DNL Adobe Experience Platform] (AEP) SDK:</li><li>[!UICONTROL Media Analytics Extension] (voor web): [!UICONTROL Adobe Media Analytics] (3.x SDK) voor Audio &amp; Video v1.0 of hoger</li><li>[!UICONTROL Media Analytics Extension] (voor mobiele apparaten): [!UICONTROL Adobe Media Analytics for Audio] en Video v2.0 of hoger</li><li>[!UICONTROL Media Collection]</li></ul> |

### Oplossingen in Adobe Analytics {#aa-fixes}

* Probleem verholpen waarbij de rapportage-API geen bijgewerkte metrische waarden retourneerde. (AN-225617)
* Probleem verholpen waarbij gegevens niet konden worden geclassificeerd [!UICONTROL Classification Rules] voor [!UICONTROL Marketing Channel Details]. (AN-224832)
* Probleem verholpen waarbij een fout met _ontbrekende componenten_ werd veroorzaakt bij het maken van nieuwe projecten in een [!UICONTROL Virtual Report Suite].(AN-226808)
* Probleem verholpen waarbij een fout met _ontbrekende componenten_ werd veroorzaakt bij het beheren van een Virtual Report Suite. (AN-228257)
* Probleem verholpen waarbij het maken van nieuwe [!UICONTROL Reports & Analytics] doelen en kalendergebeurtenissen werd voorkomen. (AN-224872, AN-224890, AN-224914, AN-226661)
* Probleem verholpen waarbij ontbrekende activiteiten in het deelvenster A4T werden veroorzaakt in [!UICONTROL Workspace]. (AN-224606)
* Probleem verholpen met dubbele treffers in [!UICONTROL Data Feeds]. (AN-226308)
* Probleem verholpen waarbij berekende metriek met deelnemingskenmerk geen juiste waarden retourneerde. (AN-224642, AN-225190)
* Probleem verholpen waarbij segmentgegevens tussen [!DNL Analytics] en [!DNL Audience Manager] drie dagen werden gedeeld om in te verschijnen [!DNL Audience Manager].(AN-226649)
* Probleem verholpen waarbij de [!UICONTROL Analyze Further] koppeling niet kon worden gebruikt in e- [!UICONTROL Intelligent Alerts] mails. (AN-226823)
* Probleem verholpen waarbij het niet mogelijk was om segmenten te maken in een [!UICONTROL virtual report suite]. (AN-227039)
* Probleem verholpen waarbij intelligente waarschuwingen niet konden worden bewerkt. (AN-227162)

#### Nog meer oplossingen in Adobe Analytics

AN-219351; AN-220960; AN-223788; AN-224630; AN-224948; AN-225618; AN-226261; AN-226828; AN-226845; AN-226937; AN-226961; AN-227070; AN-227079; AN-227521; AN-227610; AN-228203; AN-228451; AN-228466; AN-228538

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| EOL van Adobe Data Connectors | 13 juli 2020 | Adobe [!UICONTROL Data Connectors] are powered by legacy technology that is no longer viable or supported. We hebben een nieuwe standaard in het [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud) dat moet worden gebruikt voor alle integraties waarvoor aanbod en ondersteuning gewenst is. De officiële einddatum moet nog worden vastgesteld, maar we verwachten dat deze in de komende 12-18 maanden zal liggen (medio 2021 tot eind 2021). [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/import/dataconnectors/data-connectors-eol.html) |
| Toewijzing rapportsuite aan IMS-org | Juli 2020 | De tool voor toewijzing van rapportsuites wordt in november 2020 gediscontinueerd. Met deze functie kunt u integratie mogelijk maken zoals het publiceren van Advertising Analytics- en Experience Cloud-segmenten in Adobe Analytics. Een rapportsuite moet worden toegewezen aan een IMS-org om deze en andere services in te schakelen. Nieuwere rapportsuites worden automatisch toegewezen bij het maken. Oudere rapportsuites moeten echter handmatig worden toegewezen aan een IMS-org. See [Map report suites to an organization](https://docs.adobe.com/content/help/nl-NL/core-services/interface/about-core-services/report-suite-mapping.html) in the Experience Cloud interface (Core Services) user guide to make sure all report suites belong to an IMS org. |
| Migratie naar uniform productdomein | Ingangsdatum: 28 mei 2020 | De migratie naar een uniform productdomein voor Adobe Analytics dat in januari 2020 is gestart, is op 28 mei 2020 voltooid. Hoewel Adobe Analytics probeert om alle `omniture.com`-domeinverwijzingen uit zijn architectuur te verwijderen, is het belangrijk om `omniture.com` als cookie van een derde partij op de allowlist te plaatsen. Wanneer de volledige architectuurmigratie (binnenkort) is voltooid, stellen we u via de releaseopmerkingen op de hoogte en is deze allowlist-stap niet meer nodig. [Hier](https://helpx.adobe.com/nl/analytics/kb/adobe-ip-addresses.html) vindt u de volledige lijst met aanbevolen IP-adressen en domeinen die u op de allowlist moet plaatsen.<br>Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen. |
| Nieuwe standaard landingspagina voor Adobe Analytics | Ingangsdatum: 18 juni 2020 | Op 18 juni 2020 verandert de standaard landingspagina voor Adobe Analytics van [!UICONTROL Reports] naar [!UICONTROL Workspace]. Deze wijziging vindt plaats voor alle gebruikers die nog geen aangepaste landingspagina hebben ingesteld. |
| Allowlist van technologieën van derden | 12 Maart 2020 (ingangsdatum) | Adobe Analytics is gestart met het gebruik van technologieën van derden voor doorlopend implementatiebeheer van functies en voor ondersteuning in het product. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste allowlists voor de netwerkfirewall om volledige toegang tot de functies te garanderen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Verbeterde redundantie voor de beschikbaarheid van [!UICONTROL Analysis Workspace] | 21 mei 2020 | Om de beschikbaarheid van [!UICONTROL Analysis Workspace] te verzekeren, voegen we een secundair CDN (Content Delivery Network) toe voor verbeterde redundantie. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste allowlists voor de netwerkfirewall:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Wijzigen in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace] | 7 april 2020 | Sinds maart 2020 is in [!UICONTROL Analysis Workspace] gewijzigd hoe de waarde _Geen_ communiceert met [!UICONTROL Entries/Exits]. Omdat u _Geen_ nu kunt in- en uitschakelen in [!UICONTROL Analysis Workspace], gebruiken we de waarde _Geen_ na openen en afsluiten, waar dit (voor eVars) vroeger werd toegepast vóór openen en afsluiten. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor eVars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] verschijnt de eerste hit als _Niet gespecificeerd_ voor de vermelding, maar in [!UICONTROL Analysis Workspace] verschijnt dit als de waarde voor de tweede hit. |
| EOL van **[!UICONTROL Dashboard Archive]** | 27 maart 2020 | De instelling **[!UICONTROL View Archive]** onder **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] zal vanaf oktober 2020 niet meer beschikbaar zijn. |
| EOL van Analytics Legacy API&#39;s | 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### AppMeasurement

Voor de meest recente updates over AppMeasurement-releases raadpleegt u [Releaseopmerkingen bij AppMeasurement voor JavaScript](https://docs.adobe.com/content/help/nl-NL/analytics/implementation/appmeasurement-updates.html).

#### Nieuwe cursussen en tutorials voor Analytics {#tutorials-analytics}

Nieuwe cursussen, videotutorials en artikelen in Analytics en Customer Journey Analytics.

| Gepubliceerd | Naam | Type | Beschrijving |
| ----------- | ----------- | ---------- | ---------- |  
| 30 juli 2020 | [Toegang tot rapportsuite beperken in de Admin Console](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/limit-report-suite-access-in-the-admin-console.html) | Zelfstudie | Leer hoe u de code gebruikt [!UICONTROL Admin Console] om ervoor te zorgen dat gebruikers alleen toegang hebben tot de rapportsuite(s) die nodig zijn voor hun rol. |
| 24 juli 2020 | [Beheerders toevoegen aan Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/administration/user-management/adding-an-administrator-to-adobe-analytics.html) | Zelfstudie | Leer hoe u een gebruiker als beheerder in de Adobe toevoegt [!UICONTROL Admin Console]. |
| 17 juli 2020 | [Deelvenster Snelle inzichten in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/quick-insights-panel-in-analysis-workspace.html) | Zelfstudie | Quick Insights biedt richtlijnen voor niet-analisten en nieuwe gebruikers van Analysis Workspace hoe ze zakelijke vragen snel en eenvoudig kunnen beantwoorden. |
| 17 juli 2020 | [Analyses voor doeldeelvenster (A4T) in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/target/analytics-for-target-a4t-panel-in-analysis-workspace.html) | Zelfstudie | The [!UICONTROL Analytics for Target] (A4T) panel lets you analyze your Adobe Target activities and experiences, with lift and confidence, in Analysis Workspace. |
| 6 juli 2020 | [Advertising Cloud-dashboards maken met Adobe Analytics](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-advertising-cloud-dashboards-with-adobe-analytics.html?lang=en#tutorials) | Zelfstudie | Technieken voor het creëren van een dashboard van Advertising Cloud voor levende campagnemonitoring. |
| 6 juli 2020 | [Aangepaste metingen voor analyse maken met Advertising Cloud-gegevens](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-custom-metrics-with-advertising-cloud-data.html?lang=en#tutorials) | Zelfstudie | Nuttige aangepaste maateenheden die u kunt maken wanneer u Advertising Cloud-gegevens gebruikt in Adobe Analytics. |
| 6 juli 2020 | [Analytische sitereisprofielen maken](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-site-journey-profiles.html?lang=en#tutorials) | Zelfstudie | Adobe Analytics gebruiken om robuuste herrichtingspools voor Advertising Cloud-hermarketing te maken. |
| 6 juli 2020 | [Analysesegmenten maken voor activering en rapportage](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/create-analytics-segments-for-activation-and-reporting.html?lang=en#tutorials) | Zelfstudie | Advertising Cloud-dimensies gebruiken om segmenten te maken voor een schonere rapportage en analyse. |
| 6 juli 2020 | [Een Campagneanalyse vóór de introductie van Adobe Analytics maken](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/integrations/ad-cloud/reporting-with-advertising-cloud-marketing-channels.html?lang=en#tutorials) | Zelfstudie | Hoe Adobe Analytics gebruiken om de basis te leggen voor een Advertising Cloud-mediacampagne. |
| 6 juli 2020 | [Delen van projecten in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/project-sharing-in-analysis-workspace.html?lang=en#tutorials) | Zelfstudie | Het delen van projecten is een manier om gegevens en inzichten van Analysis Workspace naar gebruikers in uw organisatie te democratiseren. U kunt ontvangers in één van drie projectrollen plaatsen, afhankelijk van de projectervaring u hen wilt hebben - geef uit, dupliceer en Mening. |
| 26 juni 2020 | [Aangepaste opzoekvensters in Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/custom-lookback-windows-in-attribution-iq.html?lang=en#tutorials) | Zelfstudie | Met aangepaste terugkijkvensters kunt u het toewijzingsvenster buiten het rapportagebereik uitbreiden (tot maximaal 90 dagen) en wordt de aanpassing toegepast op elke conversie in het rapportagebereik. |
| 26 juni 2020 | [Alleen-weergeven projecten in Analysis Workspace](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/view-only-projects-in-analysis-workspace.html?lang=en#tutorials) | Zelfstudie | Workspace projects can be shared to users as _Can view_ only. When a _View_ recipient opens the shared project, they receive a more restrictive project experience, with no left rail and limited interactions. |
| 26 juni 2020 | [Algorithmic Model in Attribution IQ](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/analysis-workspace/attribution-iq/algorithmic-model-in-attribution-iq.html?lang=en#tutorials) | Zelfstudie | Het [!UICONTROL Algorithmic Attribution]-model in Analysis Workspace maakt gebruik van statistische technieken om dynamisch de optimale allocatie van krediet voor de geselecteerde cijfers te bepalen. |

#### Bronnen voor Analytics Help

* [Adobe Analytics-tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-productdocumentatie](https://docs.adobe.com/content/help/nl-NL/analytics/landing/home.html)

## ![Pictogram](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nieuwe functies, correcties, documentatie en tutorials in Audience Manager.

Releasedatum: **13 augustus 2020**

### Nieuwe functies en oplossingen in Adobe Audience Manager

* U kunt [Mensen-Gebaseerde Doelen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-prerequisites.html) nu gebruiken aan doelgebruikers via [!DNL Google Customer Match]. Alvorens u kunt gebruiken [!UICONTROL People-Based Destinations] om uw segment van het eerste partijpubliek naar een [!DNL Google Customer Match] bestemming te verzenden, is het verplicht dat u aan hun lijst van gewenste personen [!DNL Google] toevoegt. Raadpleeg de [documentatie bij Op mensen gebaseerde doelen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-prerequisites.html) voor meer informatie. (PLAT-53962)
* [Voorspelend publiek](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/algorithmic-models/predictive-audiences/predictive-audiences.html) ondersteunt nu de selectie van een [!UICONTROL Profile Merge Rule] model tijdens het maken van het model. (AAM-55178)
* Begin- en einddatum van doeltoewijzing zijn nu zichtbaar op de pagina van elk segment. (AAM-40056)
* Probleem verholpen waarbij de waarde [!UICONTROL Device Type] van een eigenschap automatisch werd ingesteld [!UICONTROL Cross-Device] bij het maken van een nieuwe eigenschap. (AAM-55368)
* Probleem verholpen waarbij het bestand niet [!UICONTROL Audience Marketplace] zou worden geladen. (AAM-55549)
* U kunt segmenten van [!DNL Google] bestemmingen nu ongedaan maken wanneer de [!DNL Google UserList] parameter niet terugwinnbaar is. (AAM-42655)
* Probleem verholpen waarbij het toevoegen van meerdere segmenten aan een doel niet altijd correct zou werken. (AAM-55651)
* Probleem verholpen waarbij gebruikers die hun [!DNL Profile Merge Rules] limiet hadden verhoogd, de [!UICONTROL Add New Rule] knop niet zagen. (AAM-55700)
* Probleem verholpen waarbij de [!UICONTROL 30 Day Overlapped Unique Users] titel zou ontbreken in de [!UICONTROL Data Feed Report Metrics]. (AAM-55801)
* De metriek van het leven worden nu uitgesloten van de [!UICONTROL Destination] mening wanneer de bestemming wordt gevormd om [!DNL UUID]s uit te voeren. (AAM-54196)
* Probleem verholpen waarbij gebruikers [!DNL Tableau] rapporten niet konden weergeven. (AAM-55868)
* Probleem verholpen waarbij gebruikers een fout zouden ontvangen bij het maken van een nieuw [!UICONTROL Predictive Audiences] model. (AAM-55921)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-49062, AAM-49063, AAM-49365).

### Nieuwe Audience Manager-tutorials {#tutorials-aam}

| Gepubliceerd | Naam | Type | Beschrijving |
| ----------- | ----------- | ---------- | ---------- |
| 7 augustus 2020 | [Bespaar geld en optimaliseer de ervaring van klanten door advertenties aan converters te onderdrukken](https://experienceleague.adobe.com/?recommended=AudienceManager-A-1-2020.1) | Zelfstudie | In deze cursus, leer alle concepten van begin tot eind met het gebruiksgeval gaan om geld te besparen en de klantenervaring te optimaliseren door bestaande klanten uit uw bereikcampagnes te verwijderen. Dit omvat de bouw van eigenschappen en segmenten, toevoegend de juiste profielfusieregels, toevoegend segmenten aan bestemmingen, en zelfs het berekenen van ROI aangezien u dit gebruiksgeval gebruikt. |
| 7 augustus 2020 | [De regel voor het samenvoegen van profielen rechts kiezen](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/choosing-the-right-profile-merge-rule.html) | Zelfstudie | In deze video ziet u drie van de meest gebruikte gevallen voor [!UICONTROL Profile Merge Rules]en hoe u uw marketingactiviteiten kunt verbeteren. |
| 5 augustus 2020 | [Een segmenttaxonomie maken](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-a-segment-taxonomy.html) | Zelfstudie | Wanneer u een segment in Audience Manager creeert, slaat u hen in een op omslag-gebaseerde structuur, of een _taxonomie_ op. Leer enkele tips voor het maken en beheren van de segmenttaxonomie. |
| 4 augustus 2020 | [API-referenties ophalen in Adobe I/O](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/api/retrieve-api-credentials-in-adobe-io.html) | Zelfstudie | In plaats van contact op te nemen met Adobe Consulting of Customer Care voor referenties voor het gebruik van de REST API, kunt u gewoon naar `Adobe.io` de browser gaan en uw eigen gegevens ophalen of registreren. |
| 31 juli 2020 | [Recentie en frequentie gebruiken in segmenten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-recency-and-frequency-in-segments.html) | Zelfstudie | Gebruik [!UICONTROL Recency] en [!UICONTROL Frequency] om uw segmentparameters te geven van het aantal keren dat een bezoeker binnen een bepaalde periode voor een kenmerk in aanmerking moet komen. Ideaal voor de affiniteit van inhoud en voor het aftappen van frequenties, maar ook voor andere. |
| 22 juli 2020 | [De basisbeginselen van het maken van segmenten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/the-basics-of-creating-segments.html) | Zelfstudie | Doorloop de gebieden in UI om een segment in Audience Manager tot stand te brengen. |
| 22 juli 2020 | [Praktische segmentdefinitie en -ontwerp](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/practical-segment-definition-and-creation.html) | Zelfstudie | Deze video begeleidt u door een proces om uw segmenten te bepalen, en dan hen te breken door de eigenschappen en de signalen die u hen moet creëren. |
| 17 juli 2020 | [Advertenties aan converters onderdrukken](https://video.tv.adobe.com/v/36658?captions=dut) | Zelfstudie | Bespaar geld en optimaliseer de ervaring van klanten door advertenties aan converters te onderdrukken. |
| 15 juli 2020 | [Het meten van ROI in een Geval van het Gebruik van de Onderdrukking van de Klant](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/value-realization/measuring-roi-in-a-customer-suppression-use-case.html) | Zelfstudie | Leer om een paar formules te gebruiken om uw campagnekostenbesparingen te bepalen door advertenties aan bestaande klanten te onderdrukken. |
| 10 juli 2020 | [Een segment maken om advertenties aan klanten te onderdrukken](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/building-a-segment-to-suppress-ads-to-customers.html) | Zelfstudie | In deze video worden opties voor het maken van segmenten besproken, zodat degenen die al naar de status van de klant zijn geconverteerd, worden uitgesloten. |

## ![Pictogram](/assets/aem.png) Adobe Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### **Productintroducties**

* **AEM as a Cloud Service**

   Wat is nieuw op AEM als Cloud Service? Tot de aanbevolen hooglichten behoren:

   * AEM Commerce is nu beschikbaar op Cloud Service. Zie [Aan de slag met AEM Handel als Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/getting-started.html)
   * Connectors voor Adobe Target- en Adobe Analytics-verbeteringen zijn onder andere verbeterd gebruikersinterface, vervanging van de klassieke gebruikersinterface en integratie bij het starten van Adobe. Zie [Adobe Analytics](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-analytics.html) integreren en Adobe Target [integreren.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/integrations/integrating-adobe-target.html)
   * De dienst van de Compute van activa is een scalable en verlengbare dienst om activa te verwerken. De beheerders kunnen Experience Manager vormen om douanearbeider aan te halen die gebruikend de Dienst van de Berekening van Activa wordt gecreeerd. De ontwikkelaars kunnen de dienst gebruiken om gespecialiseerde douanearbeiders tot stand te brengen die aan complexe gebruiksgevallen behandelen. Deze webservice kan miniaturen genereren voor verschillende bestandstypen, afbeeldingen van hoge kwaliteit in de bestandsindelingen Adobe, video&#39;s coderen (in de toekomst), metagegevens extraheren, volledige tekst uitnemen als voorloper voor indexering en een element uitvoeren via alle beschikbare Sensei-services. Zie [Elementmicroservices en verwerkingsprofielen gebruiken.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/asset-microservices-configure-and-use.html)
   * [Asset Compute Service](https://docs.adobe.com/content/help/en/asset-compute/using/home.html) is beschikbaar voor uitbreiding om een aangepaste toepassing te maken. Het is een schaalbare en uitbreidbare service voor het verwerken van digitale elementen [!DNL Adobe Experience Cloud] . U kunt afbeeldingen, video, documenten en andere bestandsindelingen transformeren in verschillende uitvoeringen, zoals miniaturen, uitgenomen tekst en metagegevens, archieven en nog veel meer. Ontwikkelaars kunnen aangepaste toepassingen (ook wel aangepaste workers genoemd) maken voor het afhandelen van aangepaste gebruiksgevallen. Het wordt gebouwd gebruikend [Project Firefly](https://www.adobe.io/apis/experienceplatform/project-firefly/docs.html) en werkt in serverless [Adobe I/O Runtime](https://www.adobe.io/apis/experienceplatform/runtime.html).
   * Meerdere verbeteringen voor workflowmodellen en Dynamic Media in AEM als Cloud Service.
   * Release 2.11.0 van de [AEM Core Components](https://docs.adobe.com/content/help/nl-NL/experience-manager-core-components/using/introduction.html) is nu beschikbaar als onderdeel van AEM Sites, waaronder:
      * Introductie van een nieuwe [PDF Viewer-component.](https://aemcomponents.dev/content/core-components-examples/library/page-authoring/pdf-viewer.html)
      * Ondersteuning voor versnelde mobiele pagina&#39;s (AMP) van kerncomponenten. Het helpt klanten sneller ervaringen op te doen door de paginaovergang onmiddellijk te maken wanneer ze de site betreden vanuit een mobiel zoekresultaat van Google, wat de betrokkenheid van gebruikers en SEO verbetert. Zie [AMP-ondersteuning voor de Core Components.](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)
      * Compatibiliteit met versie 1.0.2 van de gegevenslaag [van de Cliënt van](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/developing/data-layer/overview.html)Adobe.
   * Meerdere verbeteringen in de gebruikersinterface van Cloud Manager.
   * De pijpleidingen van de Manager van de wolk steunen nu klant-vastgestelde variabelen en geheimen. Zie Variabelen [pipet.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/getting-access/creating-aem-application-project.html#pipeline-variables)
   * [Logs kan naar Splunk accounts](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/logging.html#splunk-logs)worden doorgestuurd, waardoor organisaties hun [!DNL Splunk] investering kunnen benutten.
   * U kunt [een statisch, specifiek uitgangIP adres](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/development-guidelines.html#dedicated-egress-ip-address) voor uitgaand die verkeer toewijzen in code Java wordt geprogrammeerd, die voor sommige integratie nuttig kan zijn.
   * [!UICONTROL Cloud Readiness Analyzer] v1.0.2 is uitgebracht. See detailed [Release Notes](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-2020-7-0.html#cloud-readiness-analyzer) for more information. Om met te beginnen, zie het [!UICONTROL Cloud Readiness Analyzer]Gebruiken van de Analysator [](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/cloud-readiness-analyzer/using-cloud-readiness-analyzer.html)van de Gereedheid van de Wolk.
   * Zie de [volledige versienota&#39;s voor AEM als Cloud Service.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html?mkt_tok=eyJpIjoiWm1SallqTmtOekF6WldZMCIsInQiOiJoTTZ3Qm9LNVRXc1lsbjExdlpNMGdQNFE2UGM5ejZob1EwZXlPZHp2MEZJa1BPTHhybHBYcUxFWTgwVjNFajlzYU1Fb1NoVXRwMTc3U2IrbHZKeTVSOG02MUErbWpIb1pjNU8zYkdTbW5MZHVIRUUyNk9vUU9SckdOeUJmbXlObSJ9)

### Zelfondersteuning

* **AEM Assets**

   * Meer tips voor het [oplossen van problemen toegevoegd](https://docs.adobe.com/content/help/en/experience-manager-desktop-app/using/troubleshoot.html) voor desktop-app van Experience Manager.

* **AEM Forms**

   * AEM Forms add-on pakketten zijn nu beschikbaar op [AEM Software Distribution](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?2_group.propertyvalues.property=.%2Fjcr%3Acontent%2Fmetadata%2Fdc%3Asolution&amp;2_group.propertyvalues.operation=equals&amp;2_group.propertyvalues.0_values=target-solution%3Aem%2Fforms&amp;orderby=%40jcr%3Acontent%2Fjcr%3AlastModified&amp;orderlayout=desc&amp;layout list&amp;p.offset=0&amp;p.limit=24). U vindt directe koppelingen voor pakketten van elke ondersteunde release in het [AEM Forms-releaseartikel](https://helpx.adobe.com/nl/aem-forms/kb/aem-forms-releases.html) .
   * Gebruik de [referentiesite](https://docs.adobe.com/content/help/en/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) om de end-to-end workflow van de Automated Forms Conversion-service te leren.
   * JavaDocs voor de versies van AEM [6.5.5.0](https://helpx.adobe.com/experience-manager/6-5/forms/javadocs/index.html) en AEM [6.4.8.1](https://helpx.adobe.com/experience-manager/6-4/forms/javadocs/index.html) zijn beschikbaar.
   * [Importeer vertrouwde certificaten](https://docs.adobe.com/content/help/en/experience-manager-65/forms/manage-administer-aem-forms/hardening-aem-forms-environment/hardening-aem-forms-jee-environment.html#configuring-ssl) naar JVM terwijl u een AEM Forms in de JEE-omgeving verhardt.
   * Verbeterde installatiedocumentatie voor [PDF Generator.](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/install-configure-document-services.html)

* **Kernonderdelen**

   Versie 2.11.0 van de Componenten van de kern introduceert steun voor AMP en is nu beschikbaar samen met [auteursdocumentatie](https://docs.adobe.com/content/help/nl-NL/experience-manager-core-components/using/introduction.html) en [ontwikkelaardetails en projectdownload beschikbaar op GitHub.](https://github.com/adobe/aem-core-wcm-components)

### **Community**

* **De meest recente AEM over Experience League**

   Dit is de officiële bron van de technische inhoud van Digital Experience die door Adobe wordt geproduceerd. Zie [hier de volledige lijst.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/qaq-p/373396)

### Nieuwe cursussen en tutorials voor Experience Manager

Nieuwe video&#39;s, tutorials of cursussen die in de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 7 augustus 2020 | [Aan de slag met beheer van meerdere sites voor zakelijke gebruikers](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites.msm) | Cursus | Leer hoe u een solide basis voor uw AEM Assets-implementatie kunt leggen door de kernproblemen te configureren, van het instellen van een basisarchitectuur voor inhoud en taxonomie tot het aanpassen van metagegevens en het verwerken van bedrijfsmiddelen. |
| 7 augustus 2020 | [AEM Assets voor beheerders configureren](https://experienceleague.adobe.com/?recommended=ExperienceManager-A-1-2020.1.assets) | Zelfstudie | Beschrijving |
| 19 juli 2020 | [Het gereedschap Inhoud overbrengen gebruiken](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/migration/content-transfer-tool.html) | Zelfstudie | Het [!UICONTROL Content Transfer] hulpmiddel is de geadviseerde manier om inhoud van een op-gebouw of AMS ontvangen versie van Experience Manager aan een [!UICONTROL AEM as a Cloud Service] milieu te migreren. |
| 21 juli 2020 | [Een actieve kopie maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-live-copy.html) | Zelfstudie | Begrijp hoe te om tot een [!UICONTROL Live Copy] voor uw plaats van een [!UICONTROL Blueprint] gebruikend de [!UICONTROL Create Live Copy] tovenaar te leiden. |
| 21 juli 2020 | [Live Copy Console](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-overview-console.html) | Zelfstudie | Leer hoe u overerving op een site kunt weergeven of beheren of uitrollingsbewerkingen kunt uitvoeren met de overzichtsconsole van Live kopie. |
| 21 juli 2020 | [Omzettingsprojecten](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Zelfstudie | Leer hoe u een vertaalproject voor uw [!UICONTROL Language Copy]project kunt maken, bewerken en beheren. |
| 21 juli 2020 | [Vertaaltaken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-translation-projects.html) | Zelfstudie | Leer hoe u een vertaaltaak toevoegt aan een bestaand vertaalproject. |
| 21 juli 2020 | [Taalkopie bijwerken met starten](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/updating-language-copy.html) | Zelfstudie | Leer hoe u wijzigingen in een toepassing kunt bijwerken, controleren en goedkeuren [!UICONTROL Language Copy] met behulp van Launches. |
| 21 juli 2020 | [Overzicht van beheer voor meerdere sites](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/language-copy-overview.html) | Zelfstudie | Bekijk een overzicht van hoe u een meertalige site kunt maken met [!UICONTROL Language Copy] de functie [!UICONTROL AEM Sites]. |
| 21 juli 2020 | [Live kopiëren en vervagen](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/live-copy-and-blueprint.html) | Zelfstudie | Begrijp de relatie tussen een [!UICONTROL Live Copy] en zijn [!UICONTROL Blueprint] in [!UICONTROL AEM Sites]. |
| 21 juli 2020 | [Overerving van live kopiëren op een pagina beheren](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-page-inheritance-live-copy.html) | Zelfstudie | Leer hoe u overerving tussen een [!UICONTROL Live Copy] en de [!UICONTROL Blueprint] bijbehorende overerving op paginaniveau beheert. |
| 21 juli 2020 | [Overerving van Live kopie beheren op een component](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Zelfstudie | Begrijp hoe te om overerving tussen een [!UICONTROL Live Copy] [!UICONTROL Blueprint] en zijn op een componentenniveau te beheren. |
| 21 juli 2020 | [Taalkopie maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/manage-component-inheritance-live-copy.html) | Zelfstudie | Beschrijving. |
| 21 juli 2020 | [Taalkopie maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-launguage-copy.html) | Zelfstudie | Ontdek hoe u een [!UICONTROL Language Copy] voor uw AEM site kunt maken met behulp van de [!UICONTROL Create Language Copy wizard]. |
| 21 juli 2020 | [Een meertalig vertaalproject maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-multinational-translational-project.html) | Zelfstudie | Leer hoe u een meertalig vertaalproject voor uw project kunt maken, bewerken en beheren [!UICONTROL Language Copy] vanuit AEM projectconsole. |
| 21 juli 2020 | [Een landsite maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-site.html) | Zelfstudie | Leer hoe u een landsite maakt op basis van een bestaande site [!UICONTROL Language Copies] met de [!UICONTROL Create Site] wizard. |
| 21 juli 2020 | [Een pagina Taalkopieën maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/create-new-page-language-copy.html) | Zelfstudie | Leer hoe u een pagina in een bestaande pagina maakt [!UICONTROL Language Copy]en vertaal de inhoud vervolgens naar een andere pagina [!UICONTROL Language Copy]. |
| 21 juli 2020 | [Taakstatus vertaling](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/multi-site-management/translation-job-status.html) | Zelfstudie | Begrijp de verschillende statussen verbonden aan een Vertaalbaan of een punt in de baan. |
| 21 juli 2020 | [Inleiding tot beheer van meerdere sites](https://video.tv.adobe.com/v/36686?captions=dut) | Zelfstudie | Introductie tot het Aan de slag met Beheer van meerdere sites voor zakelijke gebruikers cursus. |
| 21 juli 2020 | [Aangepaste formulierfragmenten maken](https://video.tv.adobe.com/v/37325?captions=dut) | Zelfstudie | Adaptieve formulieren bieden een handig mechanisme om slechts eenmaal een formuliersegment als een deelvenster of een groep velden te maken en deze in adaptieve formulieren opnieuw te gebruiken. Deze herbruikbare en standalone segmenten worden adaptieve formulierfragmenten genoemd. |
| 21 juli 2020 | [AEM Postvak IN](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/inbox-customization/introduction.html) | Zelfstudie | [!UICONTROL AEM Inbox] consolideert meldingen en taken van verschillende AEM, waaronder Forms-workflows. |
| 21 juli 2020 | [Fouten opsporen in lokale quickstart van AEM SDK met behulp van logbestanden](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Zelfstudie | De logboeken handelen als frontline voor het zuiveren AEM toepassingen, maar zijn afhankelijk van het adequate registreren in de opgestelde AEM toepassing. |
| 21 juli 2020 | [Introductie van SPA-editor](https://video.tv.adobe.com/v/37705?quality=12&learn=on&captions=dut) | Zelfstudie | Een cursusinleiding aan het Worden begonnen met AEM Redacteur van het KUUROORD voor ontwikkelaars. |
| 2020 | [Machtigingen basislijn](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/baseline-permissions.html) | Zelfstudie | Het beheren van gebruikerstoegang in de mappen met basiselementen is een essentieel aspect van het beheer en zorgt ervoor dat de processen correct worden ondersteund. |
| 21 juli 2020 | [Workflows automatisch starten](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/auto-start-workflows.html) | Zelfstudie | Workflows voor automatisch opstarten breiden de verwerking van bedrijfsmiddelen in AEM als Cloud Service uit door automatisch een aangepaste workflow aan te roepen bij het uploaden of opnieuw verwerken. |
| 21 juli 2020 | [Fouten opsporen in lokale quickstart van AEM SDK met behulp van logbestanden](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Zelfstudie | De logboeken handelen als frontline voor het zuiveren AEM toepassingen, maar zijn afhankelijk van het adequate registreren in de opgestelde AEM toepassing. |
| 21 juli 2020 | [Aangepaste formuliersjabloon maken](https://video.tv.adobe.com/v/37324?captions=dut) | Zelfstudie | Wanneer auteurs de sjabloon gebruiken om een adaptief formulier te maken, neemt het nieuwe formulier de structuur en componenten over die u in de sjabloon hebt opgegeven. |
| 21 juli 2020 | [Apache Sling Connection Pooled Data Source maken](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/prefill-fdm-db/create-form-data-model.html) | Zelfstudie | De eerste stap bij het maken van een formulier met RDBMS-ondersteuning is het configureren van Apache Sling Connection Pooled DataSource. |
| 21 juli 2020 | [Aangepaste formulieren vooraf invullen met behulp van het formuliergegevensmodel](https://video.tv.adobe.com/v/36387?captions=dut) | Zelfstudie | Inleiding tot het vooraf invullen van formulieren met behulp van het formuliergegevensmodel. |
| 21 juli 2020 | [Uw eerste adaptieve formulier maken](https://video.tv.adobe.com/v/37701?captions=dut) | Zelfstudie | Leer in deze video hoe u het eerste adaptieve formulier maakt. |

### Experience Manager-releasegegevens

Alle Experience Manager-releaseopmerkingen worden op de volgende pagina&#39;s bijgehouden:

* [Release-informatie bij AEM als Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/release-notes/home.html)
* [Releaseopmerkingen bij AEM Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Releaseopmerkingen bij de service Geautomatiseerde conversie van formulieren](https://docs.adobe.com/content/help/nl-NL/aem-forms-automated-conversion-service/using/release-notes.html)
* [Releaseopmerkingen bij AEM 6.5 Service Pack](https://docs.adobe.com/content/help/nl-NL/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
* [Releaseopmerkingen bij AEM 6.4 Cumulative Fix Pack](https://docs.adobe.com/content/help/nl-NL/experience-manager-64/release-notes/cfp-release-notes.html)
* [Releaseopmerkingen bij AEM Assets Dynamic Media](https://docs.adobe.com/content/help/nl-NL/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Releaseopmerkingen bij AEM Brand Portal](https://docs.adobe.com/content/help/nl-NL/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)
* [Releaseopmerkingen bij AEM-desktop-app](https://docs.adobe.com/content/help/nl-NL/experience-manager-desktop-app/using/release-notes.html)
* [Releaseopmerkingen bij AEM Dispatcher](https://docs.adobe.com/content/help/nl-NL/experience-manager-dispatcher/using/getting-started/release-notes.html)
* [Releaseopmerkingen bij Adobe Primetime](https://docs.adobe.com/content/help/nl-NL/primetime/release-notes/home.html)
* [Releaseopmerkingen bij Livefyre](https://docs.adobe.com/content/help/nl-NL/livefyre/using/release-notes/c-rn.html)

### Aanvullende Help-bronnen voor AEM

* [Gebruikershandleidingen voor AEM als Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [AEM 6.4 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [AEM 6.3 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [AEM 6.2 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/nl-NL/dynamic-media-classic/using/home.html)

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwe productversies

Releasegegevens voor Campaign Classic, Campaign Standard en Control Panel.

#### Campaign Classic

* 20.2.1 release - [Meer informatie](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Nieuwe cursussen en tutorials voor Campaign

Nieuwe video&#39;s, tutorials of cursussen die in de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| ----------- | ----------- | ---------- | ---------- |  
| 10 juli 2020 | [Configuratiescherm - GPG-sleutelbeheer - Gegevens ontsleutelen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/decrypting-data.html) | Campaign Classic | Leer hoe u een openbare sleutel maakt en deze kunt importeren en installeren in een Campaign-instantie voor het decoderen van binnenkomende data. |
| 10 juli 2020 | [Configuratiescherm - GPG-sleutelbeheer - Een GPG-sleutel gebruiken om gegevens te coderen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Classic | Leer hoe u data exporteert met een GPG-sleutel die is geïnstalleerd in het Configuratiescherm. |
| 10 juli 2020 | [Configuratiescherm - GPG-sleutels voor gegevenscodering genereren en installeren](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Classic | Leer hoe u een openbare/persoonlijke GPG-sleutelpaar genereert en de openbare sleutel in het Configuratiescherm installeert om gegevens te kunnen versleutelen voordat u deze vanuit uw instantie verzendt. |
| 21 juli 2020 | [Marketing-campagnes beheren](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/managing-marketing-campaigns.html) | Campaign Classic | Begrijp de belangrijkste concepten van Adobe Campaign die effectief helpen, kanaalmarketing campagnes plannen uitvoeren en meten. |
| 22 juli 2020 | [Een marketingplan, -programma&#39;s en -campagnes maken](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/creating-a-marketing-plan-programs-and-campaigns.html) | Campaign Classic | Leer hoe u een marketingplan, -programma en -campagne maakt, eigenschappen voor een campagne instelt en begrijpt hoe u de planning gebruikt. De video begeleidt u door een oefening die u kunt volgen. |
| 23 juli 2020 | [Profielen maken en beheren](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/profile-management/create-and-manage-profiles.html) | Campaign Classic | Begrijp het concept van profielen in Adobe Campaign Classic. Leer hoe u toegang krijgt tot profielgegevens, profielen kunt sorteren en filteren en profielen handmatig kunt maken en beheren. |
| 28 juli 2020 | [E-mails aanpassen met voorwaardelijke inhoud](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-create-a-multi-lingual-newsletter-using-conditional-content.html) | Campaign Classic | Leer hoe u voorwaardelijke inhoud aan een levering kunt toevoegen op het voorbeeld van een meertalige nieuwsbrief. |
| 28 juli 2020 | [E-mails aanpassen met velden voor personalisatie](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/email-channel/personalizing-emails-using-personalization-fields.html) | Campaign Classic | Leer hoe u een verpersoonlijkingsveld toevoegt aan de onderwerpregel en de inhoud van een e-maillevering. |
| 28 juli 2020 | [Doelprofielen in een workflow](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/getting-started/targeting-profiles-in-a-workflow.html) | Campaign Classic | Begrijp het gebruik van campagneworkflows en leer hoe u een workflow en doelprofielen maakt in een workflow met filtervoorwaarden. |
| 31 juli 2020 | [Een beschrijvend analyserapport genereren](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/reporting/generating-a-descriptive-analysis-report.html) | Campaign Classic | Leer hoe u een beschrijvend analyserapport kunt genereren. |
| 9 juli 2020 | [Configuratiescherm - GPG-sleutelbeheer - Een GPG-sleutel gebruiken om gegevens te coderen](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/using-a-gpg-key-to-encrypt-data.html) | Campaign Standard | Leer hoe u data exporteert met een GPG-sleutel die is geïnstalleerd in het Configuratiescherm. |
| 9 juli 2020 | [Configuratiescherm - GPG-sleutelbeheer - Gegevens ontsleutelen](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/decrypting-data.html) | Campaign Standard | Leer hoe u een openbare sleutel maakt en deze kunt importeren en installeren in een Campaign-instantie voor het decoderen van binnenkomende data. |
| 9 juli 2020 | [Configuratiescherm - GPG-sleutelbeheer - GPG-sleutels voor gegevenscodering genereren en installeren](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.html) | Campaign Standard | Leer hoe u een openbaar/persoonlijk sleutelpaar kunt genereren en installeren op een opgegeven Campaign-instantie voor de codering van uitgaande data. |

### Help-bronnen voor Help

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/campaign-standard-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/overview.html) - [Releaseplanning](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/campaign-classic-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/overview.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/nl-NL/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/control-panel/using/release-notes.html) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Releaseopmerkingen bij Adobe Advertising Cloud.

### Nieuwe functies in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

**8 augustus** release

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Portfolios] | Posielimieten op Portfolio-niveau zijn niet meer beschikbaar in portfolioinstellingen. Eerder gemaakte positielimieten zijn verwijderd. |
| [!UICONTROL Constraints] | Op positie gebaseerde beperkingen en beperkingsvoorwaarden worden niet meer ondersteund:<br/><ul><li>De meeste beperkingen van Pos en Max van Pos zijn niet meer beschikbaar en zijn verwijderd uit alle eerder gemaakte beperkingen van het Bod &amp; van de Positie en van het Aandeel van de Impressie.</li><li>Bestaande boden- en positiebeperkingen die plaatsingsbeperkingen bevatten, maar geen biedbeperkingen zijn gepauzeerd. Zij zijn nog beschikbaar in UI en in rapporten.</li><li>Bod- en positiebeperkingen zijn hernoemd tot biedingsbeperkingen.</li><li>Alle op positie-gebaseerde voorwaarden (gebruikend Gemiddelde Positie, Gewogen Gemiddelde Positie, of Laatste Bekende Pos metriek) in om het even welk type van beperking werden verwijderd.</li></ul><br/>**Opmerking:** Positiegegevens blijven ingevuld zolang deze beschikbaar zijn in de zoekmachines. Microsoft Ads zal in september 2020 met pensioen gaan. |  |
| [!UICONTROL Campaigns] | (Google Ads-campagnes) Advertising Cloud Search ondersteunt nu RSA&#39;s (responsieve zoekadvertenties) en biedt klanten deze mogelijkheid. Eerder, werden zij gesteund in alle advertentietypes behalve RSAs. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Voor de versienota&#39;s van Magento raadpleegt u:

* [Magento Commerce 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)
* [Magento Open Source 2.3.5](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-5-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

[!DNL Marketo Engage] is een volledige applicatie voor leadmanagement en B2B-marketeers die klantervaringen willen transformeren door betrokkenheid in elke fase van complexe kooptrajecten.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo] [releaseopmerkingen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+July+%2720) voor de recentste releasegegevens.

### Aanstaande functies

De volgende functies komen gedurende het komende kwartaal beschikbaar:

| Functie | Beschrijving |
|------|---------|
| [!DNL Bizible] | <ul><li>Nieuwe op accounts gebaseerde segmentatie</li><li>Dashboardspecifieke filters opslaan</li><li>Bizible-dashboards exporteren als PDF&#39;s</li></ul> |
| Sales Connect | Venster- en Opdrachtcentrum-updates/verbeteringen maken |

### Aankondigingen

**Marketo Engage-succescentrum:** Wordt gelanceerd in februari 2020. Het succescentrum is een helpcentrum in het product waarmee u productdocumenten en de community kunt doorzoeken, instructiehandleidingen kunt lanceren, toegang hebt tot opname van content, en meer. Opmerking: Deze functie wordt gelanceerd als bètaversie in ANZ en wordt later in het kwartaal uitgerold naar Noord-Amerika.

### Afgeschafte elementen

* **Assetparameter API &quot;_method&quot;:** Na september 2020 laten Asset API Endpoints `_method` geen queryparameters meer passeren in een POST-body om URI-lengterestricties te omzeilen.
* **Afschaffing van Internet Explorer-ondersteuning:** Vanaf de juli-release op 31 juli 2020 wordt de Marketo Engage-gebruikersinterface niet meer ondersteund in Internet Explorer.

Zie [Marketo-releaseopmerkingen](https://docs.marketo.com/x/CgA6Ag) voor cumulatieve en historische releaseopmerkingen.
