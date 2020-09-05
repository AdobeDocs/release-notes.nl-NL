---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Releaseopmerkingen bij Adobe Experience Cloud
doc-type: release notes
last-update: September 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 2bda04891fdfe3a57208f4f6accf7ac0d5c49432
workflow-type: tm+mt
source-wordcount: '6392'
ht-degree: 39%

---


# Vroege toegang - Opmerkingen bij de release van Adobe Experience Cloud - september 2020

![Banner](/assets/experience-cloud-banner-3.png)

Deze pagina beschrijft nieuwe functies, correcties en belangrijke kennisgevingen in [!DNL Adobe Experience Cloud]. Ook worden nieuwe documentatie, trainingscursussen en videotutorials onder de aandacht gebracht om u te helpen optimaal te profiteren van Experience Cloud.

>[!IMPORTANT]
>
>Deze pagina bevat pre-releasecontent en kan vóór de geplande release worden gewijzigd.

>[!NOTE]
>
>Meld u aan voor de [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases.

**Releasedatum: 10 september 2020**

De productreleasedatums kunnen variëren. Controleer regelmatig of er updates zijn.

Laatste update: **4 september 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics)  en [Customer Journey Analytics](#cust-journey)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/nl-NL/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://docs.adobe.com/content/help/nl-NL/primetime/release-notes/home.html)

Hulp nodig? Bezoek [Adobe Experience League](https://experienceleague.adobe.com/#home) om te zoeken naar product- en technische documentatie, door Adobe georganiseerde cursussen, videotutorials, snelle antwoorden, communityinzichten en training onder leiding van instructeurs.

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Zie [Adobe System Status - 21 mei 2020](https://docs-stg.corp.adobe.com/content/help/en/release-notes/experience-cloud/previous/2020/05212020.html#status) voor de recentste releaseinformatie.

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud-interface {#ecloud}

Zie [Cumulatieve releaseopmerkingen](https://docs.adobe.com/content/help/en/core-services/interface/release-notes/release-notes.html) voor de meest recente releasegegevens voor de Experience Cloud-interface (klantkenmerken, publiek, gebruikers- en productbeheer).

## ![Pictogram](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Release-opmerkingen voor [!DNL Experience Platform] en applicatieservices, waaronder [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], en beveiligingsbulletins.

Releasedatum: **12 augustus 2020**

Updates voor bestaande functies in Adobe Experience Platform:

* [Werkruimte voor gegevenswetenschap](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#dsw)
* [Doelen](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#destinations)
* [Bronnen](https://docs.adobe.com/content/help/en/experience-platform/release-notes/latest.html#sources)

Zie [Opmerkingen bij de release van Experience Platform](https://docs.adobe.com/content/help/nl-NL/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) voor de meest recente informatie over Experience Platform.

### Zelfstudies en cursussen over Experience Platform en diensten

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Experience Platform en services.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 17 augustus 2020 | [Fouten opsporen in een opstartimplementatie](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | Video | Een inleiding aan sommige gemeenschappelijke hulpmiddelen en technieken om een implementatie van de Lancering te zuiveren. Leer hoe te om de de ontwikkelaarsconsole van browser en de Debugger van het Experience Platform uitbreiding te gebruiken om zeer belangrijke aspecten van een implementatie van de Lancering te identificeren en problemen op te lossen. |
| 17 augustus 2020 | [Configuratie van Cloud Service starten maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | Video | Leer hoe te om een nieuwe configuratie van de Cloud Services van de Lancering tot stand te brengen. De configuratie van de Cloud Service van de Lancering kan dan op een bestaande Plaats worden toegepast en de bibliotheken van de Lancering kunnen worden waargenomen ladend in zowel auteur als Publish milieu&#39;s. |
| 17 augustus 2020 | [AEM verbinden met Starten met Adobe I/O](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | Video | Leer hoe u een IMS-configuratie maakt met Adobe I/O om AEM te verifiëren met de opstartAPI. Zodra deze integratie is geïnstalleerd, kan AEM via de API voor starten communiceren om toegang te krijgen tot de eigenschappen van Launch. |
| 17 augustus 2020 | [Goedkeuringsbeheer - Google IAB TCF 2.0-ondersteuning](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-iab-transparency-and-consent-framework-2.html) | Video | In deze video ziet u hoe Adobe Real-time Customer Data Platform ervoor zorgt dat merken de toestemming van de consument respecteren wanneer ze digitale eigenschappen gebruiken. Door de steun van IAB&#39;s Transparency &amp; Consent Framework 2.0, krijgen merken meer flexibiliteit over hoe ze met consumenten kunnen omgaan en krijgen ze meer controle over hun toestemming om dat te doen. |
| 17 augustus 2020 | [Google Customer Match](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/integrate-with-google-customer-match.html) | Video | In deze video wordt getoond hoe Adobe&#39;s Real-Time CDP en de klantenservice van Google brandmerken kunnen helpen om met hun klanten op de bezittingen en bediende eigendommen van Google samen te werken met het bedrijfsdoel hun outreachecampagnes te verbeteren. |
| 17 augustus 2020 | [Cursusstart voor Aan de slag met Adobe Experience Platform for Data Engineers](https://video.tv.adobe.com/v/39478?captions=dut) | Video | Een inleidende video voor de cursus [Aan de slag met Adobe Experience Platform for Data Engineers](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) . |
| 17 augustus 2020 | [Aan de slag met Adobe Experience Platform for Data Engineers](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.2) | Cursus | Leer hoe u belangrijke gegevensengineeringtaken in Adobe Experience Platform kunt uitvoeren. In deze cursus op inleidend niveau worden video&#39;s en handoefeningen gebruikt om u te helpen batchgegevens in te voeren, streaminggegevens in te voeren met Web SDK, query&#39;s uit te voeren en nog veel meer. |
| 17 augustus 2020 | [Cursusintroductie tot Aan de slag met Adobe Experience Platform for Data Architects](https://video.tv.adobe.com/v/39477?captions=dut) | Video | Deze video geeft u een overzicht van de cursus [Aan de slag met Adobe Experience Platform for Data Architects](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) . |
| 17 augustus 2020 | [Aan de slag met Adobe Experience Platform for Data Architects](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-D-1-2020.1) | Video | Leer hoe u belangrijke taken voor gegevensarchitect in Adobe Experience Platform kunt uitvoeren.  Deze cursus op inleidend niveau gebruikt video&#39;s en handoefeningen om u te beginnen gegevens in XDM schema te modelleren, etiketterend identiteiten om gegevens in de Profielen van de Klant in real time te binden, creërend segmenten en meer. |

## ![Pictogram](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

### Nieuwe productversies

* August release - [Read more](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#august-release)

### [!UICONTROL Journey Orchestration] cursussen en zelfstudies

Nieuwe video&#39;s, zelfstudies en cursussen gepubliceerd voor [!UICONTROL Journey Orchestration].

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 10 augustus 2020 | [Segmentkwalificatiegebeurtenissen gebruiken](https://docs.adobe.com/content/help/en/journey-orchestration-learn/tutorials/using-segment-qualification-events.html) | Video | This video gives you a brief introduction on how to create a journey with a [!UICONTROL Segment Qualification] event as entry or exit point. |

### Aanvullende bronnen voor Journey Orchestration

[Documentatie](https://docs.adobe.com/content/help/nl-NL/journeys/using/journey-orchestration-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html) - [Instructievideo&#39;s](https://docs.adobe.com/content/help/nl-NL/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html)

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Nieuwe functies in Media Analytics](#media-aa)
* [Oplossingen in Adobe Analytics](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)
* [Cursussen en zelfstudies voor analyse](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nieuwe functies in Adobe Analytics {#aa-features}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| ----------- | ---------- | ------- |
| [!UICONTROL Cross-Device Analytics]: beschikbaarheid in EMEA en APAC | 31 augustus 2020 | [Apparaatanalyse](https://docs.adobe.com/content/help/nl-NL/analytics/components/cda/overview.html) en persoonlijke grafiek zijn beschikbaar voor klanten in EMEA en in APAC. |
| Verbetering van het stitching op basis van velden in [!UICONTROL Cross-Device Analytics] (wereldwijd beschikbaar) | 31 augustus 2020 | Deze vereenvoudigde implementatie voor nieuwe [!UICONTROL Cross-Device Analytics]-klanten geeft u de optie om gegevens te koppelen op basis van een gebruikers-id die is opgeslagen in een Analytics-veld (prop of eVar) in plaats van een (coöperatieve of persoonlijke) apparaatgrafiek te gebruiken. Dankzij de verbetering is het niet langer nodig om ECID te implementeren of id-synchronisatie toe te passen voor CDA-doeleinden. (Voor bepaalde andere functies zijn ECID en id-synchronisatie nog steeds vereist.) |
| China Data Collection, Fase 2 | 1 september 2020 | Uitgebreide ondersteuning voor First-Party SSL. |
| Nieuwe datumbereiken in Workspace | 10 september 2020 | We voegen vijf nieuwe datumbereiken toe, zodat u kunt kiezen uit datumbereiken die geen gegevens van vandaag voor een gedeeltelijke dag bevatten: Laatste 7 volledige dagen, Laatste 14 volledige dagen, Laatste 30 volledige dagen, Laatste 60 volledige dagen, Laatste 90 volledige dagen |
| Werkruimte: Download 50 kB items voor één dimensie | 17 september 2020 | U kunt 50.000 items downloaden voor één dimensie in een vrije-vormtabel, met toegepaste segmenten en filters. Hierdoor hebt u toegang tot meer dan de 400 rijen gegevens buiten Analysis Workspace. |
| Werkruimte: Verbeteringen op gebied van [!UICONTROL Line] visualisatie | 17 september 2020 | <ul><li>U kunt de x-as en de y-as van elke [!UICONTROL Line] visualisatie weergeven of verbergen. Dit kan vooral handig zijn wanneer uw [!UICONTROL Line] visualisaties compacter zijn.</li><li>U kunt een minimum- en maximumwaardelabel bedekken op elke [!UICONTROL Line] visualisatie om de pieken en dalen snel in een metrische kleur te markeren.</li><li>U kunt verschillende regressietendensen lijnen op om het even welke [!UICONTROL Line] visualisatie bedekken om de trend in de gegevens gemakkelijker te zien. De opties omvatten [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] en [!UICONTROL Quadratic].</li></ul> [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/line.html) |

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| ----------- | ---------- | ----- |
| Wijzigingen in machtigingen voor Customer Journey Analytics | 9 september 2020 | CJA behandelt niet meer alle gebruikers als beheerders. Alleen gebruikers die zijn aangewezen als productbeheerders in de [Adobe Admin Console](https://docs.adobe.com/content/help/nl-NL/core-services/interface/manage-users-and-products/admin-getting-started.html) kunnen de volgende handelingen uitvoeren:<ul><li>Maken/bijwerken/verwijderen [!UICONTROL Connections] of [!UICONTROL Data Views]</li><li>Werk/schrappingsprojecten, filters, of calc metriek die door andere gebruikers werden gecreeerd</li><li>Een Workspace-project delen met alle gebruikers</li></ul> |
| Ondersteuning voor [!UICONTROL Anomaly Detection] | 10 september 2020 | [!UICONTROL Anomaly Detection] laat je zien welke statistische fluctuaties belangrijk zijn en welke niet. Deze functie wordt nu ondersteund in [!UICONTROL Customer Journey Analytics]. |
| Nieuwe datumbereiken in Workspace | 10 september 2020 | We voegen vijf nieuwe datumbereiken toe, zodat u kunt kiezen uit datumbereiken die geen gegevens van vandaag voor een gedeeltelijke dag bevatten: [!UICONTROL Last 7 full days], [!UICONTROL Last 14 full days], [!UICONTROL Last 30 full days], [!UICONTROL Last 60 full days], [!UICONTROL Last 90 full days] |
| Werkruimte: Verbeteringen op gebied van [!UICONTROL Line] visualisatie | 17 september 2020 | <ul><li>U kunt de x-as en de y-as van elke [!UICONTROL Line] visualisatie weergeven of verbergen. Dit kan vooral handig zijn wanneer uw [!UICONTROL Line] visualisaties compacter zijn.</li><li>U kunt een minimum- en maximumwaardelabel bedekken op elke [!UICONTROL Line] visualisatie om de pieken en dalen snel in een metrische kleur te markeren.</li><li>U kunt verschillende regressietendensen lijnen op om het even welke [!UICONTROL Line] visualisatie bedekken om de trend in de gegevens gemakkelijker te zien. De opties omvatten [!UICONTROL Linear], [!UICONTROL Logarithmic], [!UICONTROL Exponential], [!UICONTROL Power] en [!UICONTROL Quadratic].</li></ul> [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/visualizations/line.html) |

### Nieuwe functies in [!UICONTROL Media Analytics] {#media-aa}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| ----------- | ---------- | ---------- |
| Deelvenster [!UICONTROL Media Concurrent Viewer] in [!UICONTROL Workspace] | 17 september 2020 | In [!UICONTROL Media Concurrent Viewers] het deelvenster kunt u zien waar de piekgelijktijdige uitvoering heeft plaatsgevonden of waar een vervolgkeuzelijst heeft plaatsgevonden. Het biedt waardevolle inzichten in de kwaliteit van de betrokkenheid van de inhoud en viewer en helpt bij het oplossen van problemen of het plannen van volumes/schaal. [Meer informatie...](https://docs.adobe.com/content/help/en/media-analytics/using/media-reports/media-workspace-panels/media-concurrent-viewers.html) |

### Oplossingen in Adobe Analytics {#aa-fixes}

* Probleem verholpen waarbij het filteren van [!UICONTROL Workspace] kolommen met de &quot;niet-opgegeven&quot; dimensie werd voorkomen. (AN-222393)
* Oplossing voor een probleem met een time-out voor de verbinding dat niet kon worden [!UICONTROL Scheduled Projects] geleverd. (AN-223916)
* Probleem verholpen waarbij [!UICONTROL Visit] segmenten [!UICONTROL virtual report suites] niet goed werkten. (AN-225719)
* Probleem met de Chrome-browserversie in Adobe Report Builder verholpen. (AN-226718)
* Probleem verholpen met gekrulde waarden [!UICONTROL virtual report suites] die in de vrijwillige VUT-regeling nog steeds konden worden uitgesplitst naar afmetingen/maatstaven. (AN-228035)
* Probleem verholpen waarbij de zoekfunctie in de [!UICONTROL Segment Manager] nit goed werkte. (AN-226954)
* Probleem verholpen met time-outfouten tijdens het delen van projecten [!UICONTROL Workspace] met meer dan een of twee gebruikers. (AN-229443)
* Probleem verholpen met een API-aanvraag die een fout met een systeemfout veroorzaakte. (AN-229537)
* Probleem opgelost waarbij hoofdwaarden niet werden geclassificeerd. [!UICONTROL Classification Rule Builder] (AN-229786, AN-230300, AN-230563)
* Probleem verholpen waarbij bepaalde gegevens niet werden gerapporteerd door de [!UICONTROL Data Insertion] API. (AN-230587)
* Probleem verholpen waarbij het [!UICONTROL Data Warehouse] verzoek een bestand met de basisnaam niet kon ophalen en verifiëren. (AN-230642)
* ([!UICONTROL Customer Journey Analytics]) Oplossing voor een probleem met machtigingen voor het delen van projecten in CJA. (AN-226592)

#### Nog meer oplossingen in Adobe Analytics

AN-215683; AN-216894; AN-226370; AN-227138; AN-227154; AN-227328; AN-227486; AN-227672; AN-228264; AN-228960; AN-229031; AN-229274; AN-229319; AN-229353; AN-229537; AN-229610; AN-229975; AN-230008; AN-230015; AN-230347; AN-230468; AN-230473; AN-231326; AN-231329; AN-231345; AN-231509; AN-231795; AN-231901

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| ----------- | ---------- | ---------- |
| Migratie van `omniture.com` naar `adobe.com`-domein | 21 augustus 2020 | Op 13 augustus 2020 is de front-end architectuur van Adobe Analytics gemigreerd van `omniture.com|http://omniture.com/` naar het `adobe.com|http://adobe.com/`-domein. Deze wijziging verhelpt problemen met cookies van derden die optraden na de aanvankelijke productdomeinwijziging van 28 mei 2020. As a result of this update, the browser may prompt users to trust the new an `.adobe.com|http://an.adobe.com/` or `experience.adobe.com|http://experience.adobe.com/` domain. |
| Update over compatibiliteit met Ad Hoc Analysis Java 8 | 21 augustus 2020 | Ad Hoc Analysis is momenteel niet compatibel met Java 8-versies 1.8.0_261+. Om ervoor te zorgen dat uw toegang tot deze tool niet wordt beëindigd voordat de [einddatum](https://spark.adobe.com/page/S9Bhp66VJ2fEn/) is bereikt, raden we u aan een Java 8-versie te gebruiken die ouder is dan 1.8.0_261. |
| EOL van Adobe Data Connectors | 13 juli 2020 | Adobe [!UICONTROL Data Connectors] worden mogelijk gemaakt door verouderde technologie die niet meer werkbaar is of ondersteund wordt. We hebben een nieuwe standaard in het [Adobe Exchange Partner Program](https://partners.adobe.com/exchangeprogram/experiencecloud) dat moet worden gebruikt voor alle integraties waarvoor aanbod en ondersteuning gewenst is. De officiële einddatum moet nog worden vastgesteld, maar we verwachten dat deze in de komende 12-18 maanden zal liggen (medio 2021 tot eind 2021). [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/import/dataconnectors/data-connectors-eol.html) |
| Toewijzing rapportsuite aan IMS-org | Juli 2020 | De tool voor toewijzing van rapportsuites wordt in november 2020 gediscontinueerd. Met deze functie kunt u integratie mogelijk maken zoals het publiceren van Advertising Analytics- en Experience Cloud-segmenten in Adobe Analytics. Een rapportsuite moet worden toegewezen aan een IMS-org om deze en andere services in te schakelen. Nieuwere rapportsuites worden automatisch toegewezen bij het maken. Oudere rapportsuites moeten echter handmatig worden toegewezen aan een IMS-org. Zie [Rapportsuites aan een organisatie toewijzen](https://docs.adobe.com/content/help/nl-NL/core-services/interface/about-core-services/report-suite-mapping.html) in de gebruikershandleiding Experience Cloud-interface (kernservices) om ervoor te zorgen dat alle rapportsuites bij een IMS-org horen. |
| Migratie naar uniform productdomein | Ingangsdatum: 28 mei 2020 | De migratie naar een uniform productdomein voor Adobe Analytics dat in januari 2020 is gestart, is op 28 mei 2020 voltooid. Hoewel Adobe Analytics probeert om alle `omniture.com`-domeinverwijzingen uit zijn architectuur te verwijderen, is het belangrijk om `omniture.com` als cookie van een derde partij op de allowlist te plaatsen. Wanneer de volledige architectuurmigratie (binnenkort) is voltooid, stellen we u via de releaseopmerkingen op de hoogte en is deze allowlist-stap niet meer nodig. [Hier](https://helpx.adobe.com/nl/analytics/kb/adobe-ip-addresses.html) vindt u de volledige lijst met aanbevolen IP-adressen en domeinen die u op de allowlist moet plaatsen.<br>Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen. |
| Nieuwe standaard landingspagina voor Adobe Analytics | Ingangsdatum: 18 juni 2020 | Op 18 juni 2020 verandert de standaard landingspagina voor Adobe Analytics van [!UICONTROL Reports] naar [!UICONTROL Workspace]. Deze wijziging vindt plaats voor alle gebruikers die nog geen aangepaste landingspagina hebben ingesteld. |
| Allowlist van technologieën van derden | 12 Maart 2020 (ingangsdatum) | Adobe Analytics is gestart met het gebruik van technologieën van derden voor doorlopend implementatiebeheer van functies en voor ondersteuning in het product. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste allowlists voor de netwerkfirewall om volledige toegang tot de functies te garanderen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Verbeterde redundantie voor de beschikbaarheid van [!UICONTROL Analysis Workspace] | 21 mei 2020 | Om de beschikbaarheid van [!UICONTROL Analysis Workspace] te verzekeren, voegen we een secundair CDN (Content Delivery Network) toe voor verbeterde redundantie. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste allowlists voor de netwerkfirewall:<ul><li>`https://aaui-879784980514.s3.us-east-2.amazonaws`</li><li>`https://d30ln29764hddd.cloudfront.net`</li><li>`https://awaascicdprodva7.blob.core.windows.net`</li><li>`https://aauicdnva7.azureedge.net`</li></ul> |
| Wijzigen in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace] | 7 april 2020 | Sinds maart 2020 is in [!UICONTROL Analysis Workspace] gewijzigd hoe de waarde _Geen_ communiceert met [!UICONTROL Entries/Exits]. Omdat u _Geen_ nu kunt in- en uitschakelen in [!UICONTROL Analysis Workspace], gebruiken we de waarde _Geen_ na openen en afsluiten, waar dit (voor eVars) vroeger werd toegepast vóór openen en afsluiten. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor eVars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] verschijnt de eerste hit als _Niet gespecificeerd_ voor de vermelding, maar in [!UICONTROL Analysis Workspace] verschijnt dit als de waarde voor de tweede hit. |
| EOL van **[!UICONTROL Dashboard Archive]** | 27 maart 2020 | De instelling **[!UICONTROL View Archive]** onder **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] zal vanaf oktober 2020 niet meer beschikbaar zijn. |
| EOL van Analytics Legacy API&#39;s | 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### AppMeasurement {#appm}

Voor de meest recente updates over AppMeasurement-releases raadpleegt u [Releaseopmerkingen bij AppMeasurement voor JavaScript](https://docs.adobe.com/content/help/nl-NL/analytics/implementation/appmeasurement-updates.html).

### Analytics courses and tutorials {#tutorials-analytics}

Nieuwe cursussen, zelfstudies en artikelen in [!DNL Analytics] en [!UICONTROL Customer Journey Analytics].

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 30 augustus 2020 | [Opslaan, delen en samenwerken aan projecten in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/curate-and-share-projects/saving-sharing-and-collaborating-on-projects-in-analysis-workspace.html) | Video | Leer in [!UICONTROL Analysis Workspace]hoe u tekstuitleg aan een tabel kunt toevoegen, een directe koppeling voor uw project kunt maken en deze kunt delen. |
| 28 augustus 2020 | [Introductie van cursus - Toewijzing van waarde aan Digital Touch-points op de reis van de klant](https://video.tv.adobe.com/v/39380?captions=dut) | Video | In deze inleidende video leert u de vereisten en cursusinhoud voor de [waarde toewijzen aan Digital Touch-punten in de cursus Reis](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) van de Klant. |
| 28 augustus 2020 | [Waarde toewijzen aan Digital Touch-punten op de reis van de klant](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.2) | Cursus | Krijg uw bezoekers van de site te kennen door te begrijpen wat hen naar uw site heeft gebracht, hoe u kredieten voor conversie op uw site kunt toewijzen aan verschillende kanalen en zelfs te begrijpen hoe andere items op uw site worden geconverteerd. Deze cursus leert u de belangrijkste visualisaties die deze analyse tonen, en ook hoe te om attributiemodellen in uw analyse toe [!UICONTROL Attribution IQ] te wijzen. |
| 21 augustus 2020 | [Analyse op verschillende tabbladen gebruiken om de elementaire marketingtoewijzing in Analysis Workspace te verkennen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/attribution-iq/using-cross-tab-analysis-to-explore-basic-marketing-attribution-in-analysis-workspace.html) | Video | Er zijn vele manieren u uw attributiemethodologie aan het volgende niveau met Adobe Analytics kunt nemen. In deze video benadrukken we hoe u diepgaande inzichten kunt afleiden uit het [!UICONTROL Marketing Channels] rapport met behulp van een analyse op verschillende tabbladen in [!UICONTROL Workspace]. |
| 21 augustus 2020 | [Klikken met rechtermuisknop voor efficiëntie van werkruimte](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/right-click-for-workspace-efficiency.html) | Video | Meer weten over al onze favoriete Analysis Workspace-rechtsklikken en hoe u ze kunt gebruiken. Van de Lijsten van de Vrije Vorm tot de Visualisaties van de Uitval, zal het met de rechtermuisknop aanklikken u efficiënter en bekwaam in Werkruimte maken. |

### Bronnen voor Analytics Help

* [Adobe Analytics-tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-productdocumentatie](https://docs.adobe.com/content/help/nl-NL/analytics/landing/home.html)

## ![Pictogram](/assets/audience-manager.png) Adobe Audience Manager {#aam}

Nieuwe functies, correcties, documentatie en tutorials in Audience Manager.

Releasedatum: **20 september 2020**

### Nieuwe functies en oplossingen in Adobe Audience Manager

* Probleem verholpen waarbij een testsegmentpopulatie niet beschikbaar was onder [!UICONTROL Audience Lab] [!UICONTROL Aggregate Reporting]. (AAM-54553)
* Probleem verholpen waarbij segmenten die algoritmische modellen van derden gebruiken, niet werden weergegeven in de [!UICONTROL Segment Usage] weergave in [!UICONTROL Audience Marketplace]. (AAM-54595)
* Probleem verholpen waarbij sommige gebruikers fouten ondervonden bij het verwijderen van gegevensbronnen, ook al werden geen kenmerken of segmenten toegewezen aan de gegevensbronnen. (AAM-55609)
* Probleem verholpen waarbij segmenten niet werden weergegeven in het rapport van de bezoekerserprofiel. (AAM-55780)
* Probleem verholpen op de pagina in de lijst Doelen, waarbij na selectie **[!UICONTROL Lifetime]** in het **[!UICONTROL Look Back Window for Metrics]** filter een lege pagina zou worden geretourneerd. (AAM-49732)
* Probleem verholpen in het dashboard traits waarbij de metriek bij het filteren van **[!UICONTROL All Traits]** naar een filter (**[!UICONTROL Rule-based]**, **[!UICONTROL Onboarded]** enz.) zou worden bijgewerkt, maar de naam en id van de eigenschap niet. (AAM-55823)
* Probleem verholpen waarbij segmenten die aan Facebook zijn toegewezen niet zouden worden bijgewerkt omdat een ontbrekend [!UICONTROL People-based destinations]`traitAlias` veld in een API-aanroep ontbreekt. (AAM-55952)
* Probleem verholpen waarbij de grafiek niet vernieuwde tijdens het schakelen tussen kenmerken en segmenten (AAM-54736). [!UICONTROL Trend Reports]
* Probleem verholpen [!UICONTROL Look-alike Modeling] waarbij het drukken op het **[!UICONTROL Pause]** besturingselement het model niet zou onderbreken, maar juist zou sluiten. (AAM-56121)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-48950, AAM-48957, AAM-49022, AAM-49026, AAM-49044, AAM-49069, AAM-4970,-5599, 5990).

### Audience Manager courses and tutorials {#tutorials-aam}

Nieuwe video&#39;s, zelfstudies of cursussen gepubliceerd voor Audience Manager.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 17 augustus 2020 | [Segmenten Audience Manager toewijzen aan bestemmingen](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/mapping-audience-manager-segments-to-destinations.html) | Video | Leer over de verschillende soorten bestemmingen in Audience Manager en de details van het in kaart brengen van segmenten aan elk bestemmingstype. |
| 14 augustus 2020 | [Het beste uit de Regels van de Fusie van het Profiel krijgen - Tips, Strijken en Strategieën](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/customer-tips-getting-the-most-out-of-profile-merge-rules.html) | Artikel | Varun Kalra, consultant voor meerdere oplossingen in [!DNL Accordant]de VS, geeft tips voor het kiezen en gebruiken van [!UICONTROL Profile Merge Rules]. |
| 14 augustus 2020 | [Aanbevolen praktijken voor treinen en segmenten](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/customer-tips-traits-and-segments-best-practices.html) | Artikel | Matt Vittorioso, Senior Marketing Specialist bij [!DNL Ally Financial], geeft tips over het beheren van eigenschappen. |
| 12 augustus 2020 | [De Google-klant afstemmen op een op mensen gebaseerde bestemming en configureren](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-google-customer-match-pbd.html) | Video | In deze video wordt u door de details en het gebruiksgeval van de Google Customer Match geleid [!UICONTROL People-Based Destination]en wordt een doorloop gemaakt voor het maken van een segment en het toewijzen ervan aan een doel. Het toont ook het publiek dat in de Google Ad Console landt. |
| 13 augustus 2020 | [Cursusintroductie - Segment voor doelgroepen maken en strategieën](https://video.tv.adobe.com/v/39091?captions=dut) | Video | In deze video leert u wat u wacht binnen de cursus Aanmaak en strategieën van het segment Audience. |
| 13 augustus 2020 | [Codeweergave gebruiken bij het bouwen van segmenten ](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/using-code-view-when-building-segments.html) | Video | Leer hoe u de codeweergave kunt gebruiken om segmenten te definiëren, zodat u complexe combinaties van kenmerken kunt maken, inclusief het gebruik van recentie en frequentie. |
| 21 augustus 2020 | [Creatie en strategieën van het segment &quot;Audience&quot;](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.2) | Cursus | In deze cursus leert u segmenten van A tot Z. Leer hoe te om hen tot stand te brengen, hen te beheren, en hen te activeren aan bestemmingspartners. Bekijk enkele handige gebruiksgevallen en krijg zelfs tips en trucs van klanten. |

## ![Pictogram](/assets/aem.png) Adobe Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### Productupdates

* **AEM 6.5.6.0** AEM 6.5, Service Pack 6 (6.5.6.0 vrijgegeven op 3 september 2020) is een belangrijke update die nieuwe eigenschappen, zeer belangrijke klantenverhogingen, betere prestaties, stabiliteit, en veiligheid omvat, die sinds de algemene beschikbaarheid van AEM 6.5, April 2019 wordt vrijgegeven.
   * [Releaseopmerkingen](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Te leveren items voor release van AEM Forms](https://helpx.adobe.com/nl/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.2** AEM 6.4, Service Pack 8, Cumulative Fix Pack 2 (6.4.8.2 vrijgegeven op 3 september 2020) is een belangrijke update die verscheidene interne en klantenmoeilijke situaties omvat sinds de algemene beschikbaarheid van AEM 6.4, Service Pack 8 (6.4.8.0), Maart 2020.
   * [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Te leveren items voor release van AEM Forms](https://helpx.adobe.com/nl/aem-forms/kb/aem-forms-releases.html)

### Productreleases

* **[!UICONTROL AEM as a Cloud Service]**

   Wat is er nieuw aan [!UICONTROL AEM as a Cloud Service]? Aanbevolen highlights zijn onder andere:

   * Mogelijkheid om pagina&#39;s en subpagina&#39;s (paginastructuren) [!UICONTROL AEM as a Cloud Service] te [herstellen naar een eerdere versie](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/features/page-versions.html#reinstating-versions).
   * Videotranscodering wordt nu ondersteund door middel van asset micro-services, met een nieuwe [!UICONTROL Video] sectie in het [!UICONTROL Processing Profiles] scherm die de configuratie van videobitsnelheid en -afmetingen ondersteunt (uitvoerindeling is MP4 met H.264-codec). Zie Video-elementen [beheren voor meer informatie.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/manage/manage-video-assets.html#transcode-video) Voor meer transcoderingsopties en [!UICONTROL Dynamic Media] invoegtoepassing voor het afleveren van video kan worden gebruikt.
   * Dankzij een nieuwe ervaring voor het downloaden van bedrijfsmiddelen,
      * Asynchrone download voor grote downloads zodat de gebruikers niet hoeven te wachten.
      * Een nieuwe modulaire API voor uitbreidbaarheid voor ontwikkelaars.
   * U kunt de CDN-cache (Content Delivery Network) nu rechtstreeks van [!UICONTROL Dynamic Media] binnen [!UICONTROL AEM as a Cloud Service] (in tegenstelling tot het gebruiken van [!UICONTROL Dynamic Media Classic]) ongeldig maken om ervoor te zorgen dat de nieuwste elementen binnen minuten in plaats van uren worden aangeboden. Zie De CDN-cache [ongeldig maken met behulp van Dynamic Media.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)
   * Verbeterde toegankelijkheidsondersteuning wordt toegevoegd aan besturingselementen voor gebruikersinterfaces, navigatie, bladeren en zoekervaring in Elementen.
   * AEM Desktop app 2.0.3 is nu beschikbaar, waardoor de compatibiliteit met AEM 6.5, Service Pack 5 (AEM 6.5.5) en het bijwerken van de compatibiliteitslijst voor client-besturingssystemen wordt verbeterd (Windows 7- en MacOS-versies voor 10.14 worden verwijderd).
   * [!UICONTROL Product Console] Deze functie is nu beschikbaar in AEM [!UICONTROL Commerce as a Cloud Service]. Dit staat marketers en auteurs in AEM toe om categorieën en producten te bekijken en te navigeren die in de handelsholding worden opgeslagen. Steun voor eigenschappen voor categorieën en producten in de [!UICONTROL Product Console] eveneens verstrekte informatie.
   * [!UICONTROL Product] en [!UICONTROL Category Pickers] verbeterd zodat marketers hun product via SKU kunnen selecteren of een categorie als categorie-id kunnen selecteren.
   * [!UICONTROL Content Audit] is een functie ingeschakeld [!UICONTROL Cloud Manager Sites Production Pipelines]. De [!UICONTROL Production Pipeline] configuratie voor programma&#39;s met [!UICONTROL Sites] nu een derde genoemd lusje omvat **[!UICONTROL Content Audit]**. Wanneer een productiepijpleiding in werking wordt gesteld, zal een nieuwe [!UICONTROL Content Audit] stap in de pijpleiding na douane functionele het testen worden opgenomen die de plaats tegen een aantal dimensies met inbegrip van prestaties, SEO (de Optimalisering van de Motor van het Onderzoek), toegankelijkheid, beste praktijken en PWA (Progressieve App van het Web) zal evalueren.
Zie Testen op [inhoudscontrole.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/using-cloud-manager/test-results/content-audit-testing.html)
   * Nieuw gemaakte omgevingen in [!UICONTROL Assets] programma&#39;s worden nu automatisch geconfigureerd met [!UICONTROL Smart Content Services].
   * Gesamberde omgevingen kunnen worden gedehiberneerd van de **[!UICONTROL Overview]** pagina van Cloud Manager.
   * Mogelijkheid om ervaringscontroles uit te voeren op pagina&#39;s, aangedreven door [!DNL Google Lighthouse]. Als onderdeel van [!UICONTROL Cloud Manager] pijpleiding, kunnen tot 25 pagina&#39;s tegen ervaring KPIs worden gecontroleerd en worden bevestigd, en de scores worden getoond in [!UICONTROL Cloud Manager] UI.
   * See the [AEM as a Cloud Service release notes.](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

* **Experience Manager[!UICONTROL Desktop App]2.0.3.2**

   Deze kleine release omvatte het volgende:
   * Probleem verholpen waarbij bureaubladtoepassing versie 2.0.2 voor Windows niet werkte met AEM 6.5.5-exemplaar.
   * De ondersteunde OS-platforms worden bijgewerkt naar Win 10 met het nieuwste servicepack en Mac OS 10.14 of hoger.
   * Zie de opmerkingen bij de [release.](https://docs.adobe.com/content/help/nl-NL/experience-manager-desktop-app/using/release-notes.html)

* **AEM[!UICONTROL Assets Brand Portal]**

   Deze release bevatte het volgende:
   * Een documentviewer voor een verbeterde PDF-weergave.
   * Verbeteringen in de configuratie en ervaring van downloadmiddelen.
   * Oplossingen voor kritieke productproblemen.
   * Zie de opmerkingen bij de [release.](https://docs.adobe.com/content/help/nl-NL/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### **Zelfondersteuning**

* **Nieuwe gereedschappen voor[!UICONTROL AEM as a Cloud Service Transitions]**

   * De insteekmodule AIO-CLI wordt vrijgegeven om code refactoring hulpmiddelen te verenigen om ontwikkelaars toe te laten om code refactoring hulpmiddelen van één plaats aan te halen en uit te voeren. Zie het middel GitHub [ao-cli-plugin-aem-wolk-dienst-migratie](https://github.com/adobe/aio-cli-plugin-aem-cloud-service-migration) voor meer details.
   * [!UICONTROL AEM Dispatcher Converter] uitgebreid om omzettingen van configuraties On-premise en Adobe in AEM als Cloud Service compatibele configuraties van de Ontvanger te steunen. [!UICONTROL Managed Services Dispatcher] Zie het middel GitHub [AEM de Convertor](https://github.com/adobe/aem-cloud-service-source-migration/tree/master/packages/dispatcher-converter) van de Verzender van de Cloud Service voor meer details.
   * AEM Dispatcher Converter herschreven in node.js en geïntegreerd met AIO-CLI plug-in.

* **CDN-validatie in[!UICONTROL Dynamic Media]**

   U kunt nu een aanvraag vanuit de toepassing verzenden [!UICONTROL Dynamic Media] om de CDN-cache binnen enkele minuten te laten verlopen. Deze functie is handig wanneer u elementen bijwerkt en u wilt dat deze wijzigingen direct op uw website van kracht worden.

   Zie De CDN-cache [ongeldig maken als [!UICONTROL Dynamic Media]volgt.](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/invalidate-cdn-cache-dynamic-media.html)

* **In- en uittijden voor het publiceren van pagina&#39;s**

   Wanneer u pagina&#39;s publiceert met de functie [Aan en Uit-tijd](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/page-properties.html#basic), raadpleegt u het tabblad Standaard van Pagina-eigenschappen en kunt u Automatische replicatie [nu](https://docs.adobe.com/help/en/experience-manager-cloud-service/operations/replication.html#on-and-off-times-trigger-configuration)vooraf configureren.

* **[!UICONTROL Core Components]**

   [!UICONTROL Core Components] versie 2.11.0 introduceert steun voor AMP en is nu beschikbaar samen met [auteursdocumentatie](https://docs.adobe.com/content/help/nl-NL/experience-manager-core-components/using/introduction.html) en [ontwikkelaardetails en projectdownload beschikbaar op GitHub.](https://github.com/adobe/aem-core-wcm-components)

* **[!UICONTROL Forms]**

   * Bijgewerkte [](https://docs.adobe.com/content/help/nl-NL/experience-manager-65/forms/getting-started/aem-forms-reference-collaterals/forms-gov-reference-site-user-demo.html) Gov en We.Finance verwijzingsplaatsen zijn beschikbaar. U kunt deze verwijzingsplaatsen gebruiken om werkschema&#39;s van begin tot eind te leren om vormen voor overheid en financiële toppen tot stand te brengen en te leveren.
   * Er is een [voorbeeldimplementatie beschikbaar van Opslaan als concept-SPI](https://docs.adobe.com/content/help/en/experience-manager-65/forms/interactive-communications/prepare-send-interactive-communication.html#sample-ccrDocumentInstance-spi) . U kunt het voorbeeld gebruiken om de [!UICONTROL Save as a Draft] eigenschap voor uw uit te voeren [!UICONTROL Interactive Communications Agent UI]. Het helpt agenten in het bewaren van en het terugwinnen van concepten om Interactieve Communicatie generatie te versnellen.
   * De instructie om de installatie van Visuele C++ redistributables [te](https://docs.adobe.com/content/help/en/experience-manager-65/forms/install-aem-forms/osgi-installation/installing-configuring-aem-forms-osgi.html#automatic-installation-visual-studio-redistributables) installeren en te bevestigen terwijl het installeren van [!UICONTROL AEM Forms] toe:voegen-op pakket is beschikbaar. Dit helpt fouten met betrekking tot Visuele C++ redistributables installatie en configuratie verminderen.
   * [Adobe Sign configureren met documentatie voor adaptieve formulieren](https://docs.adobe.com/content/help/en/experience-manager-65/forms/adaptive-forms-advanced-authoring/adobe-sign-integration-adaptive-forms.html) wordt grondig getest en vernieuwd. Het bevat nu aanvullende instructies voor het probleemloos configureren van Adobe Sign met adaptieve formulieren.
   * (Alleen[!UICONTROL AEM Forms] in JEE) Er is documentatie beschikbaar om een [Invite External Users Handler voor de service](https://docs.adobe.com/content/help/en/experience-manager-65/forms/developer-reference/programming-aem-forms-jee/developing-spis-aem-forms/creating-invite-external-users-handler.html) Rights Management te maken.

### **Community**

* **De meest recente AEM-content over Experience League**

   Dit is de officiële bron van technische Digital Experience-content die door Adobe is geproduceerd. Klik [hier](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/list-of-latest-adobe-experience-manager-content-on-experience/m-p/377452#M27156) om de volledige lijst te zien.

### Nieuwe cursussen en tutorials voor Experience Manager

Nieuwe video&#39;s, zelfstudies en cursussen die de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Type | Beschrijving |
| -----------| ---------- | ---------- | ---------- |
| 31 augustus 2020 | [XDP-sjablonen configureren voor gebruik van AEM Forms- en Adobe Sign-integratie](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/using-xdp-templates-with-adobe-sign.html) | Video | Gebruik bestaande XDP-sjablonen met integratie [!UICONTROL AEM Forms] en Ondertekenen. |
| 17 augustus 2020 | [Geconverteerd adaptief formulier controleren en configureren](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-converted-adaptive-form.html) | Video | Configureer het adaptieve formulier dat met de service voor geautomatiseerde formulieren is gemaakt, zodat u de integratie met Adobe Sign kunt gebruiken. Wijzig de deelvenstertitels en wijzig de rangschikking van bepaalde velden naar wens. |
| 25 augustus 2020 | [Adaptief formulier configureren voor 2 ondertekenaars](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/forms-and-sign/configure-adaptive-form-for-two-signers.html) | Video | Vorm veelvoudige ondertekenaars en specificeer de orde (opeenvolgend of parallel) gebruikend de Adaptieve interface van Forms. |
| 17 augustus 2020 | [Toegang tot AEM configureren](https://video.tv.adobe.com/v/39230?captions=dut) | Video | Onderzoek hoe de gebruikers voor authentiek verklaren gebruikend Adobe IMS aan [!UICONTROL AEM as a Cloud Service], en hoe de Gebruikers van Adobe IMS, [!UICONTROL User Groups]en [!UICONTROL Product Profiles] worden gebruikt om toegang tot AEM en zijn eigenschappen en functionaliteit te controleren. |
| 17 augustus 2020 | [Toegang tot AEM doorlopen configureren](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/walk-through.html) | Video | Een verkorte looppas-niettemin het vormen gebruikers van Adobe IMS, [!UICONTROL User Groups], en [!UICONTROL Product Profiles] in Adobe [!UICONTROL Admin Console]. Leer ook hoe u deze Adobe IMS-abstracties kunt gebruiken [!UICONTROL AEM Author] om specifieke op groepen gebaseerde machtigingen te definiëren en te beheren. |
| 17 augustus 2020 | [AEM gebruikers, groepen en machtigingen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/aem-users-groups-and-permissions.html) | Video | Adobe Experience Manager bouwt voort op Adobe IMS gebruikers, [!UICONTROL User Groups], en [!UICONTROL Product Profiles] om klantgerichte toegang tot AEM te verlenen. Leer hoe u AEM groepen en machtigingen definieert en hoe ze samenwerken met de abstracties van Adobe IMS om naadloze en aanpasbare toegang tot AEM te bieden. |
| 17 augustus 2020 | [Fouten opsporen in een opstartimplementatie](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/debug-launch-implementation.html) | Video | Een inleiding aan sommige gemeenschappelijke hulpmiddelen en technieken om een implementatie van de Lancering te zuiveren. Leer hoe te om de browser ontwikkelaarsconsole en de [!UICONTROL Experience Platform Debugger] uitbreiding te gebruiken om zeer belangrijke aspecten van een Experience Platform Launch implementatie te identificeren en problemen op te lossen. |
| 17 augustus 2020 | [Configuratie van Cloud Service starten maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-cloud-service.html) | Video | Leer hoe te om een nieuwe configuratie van de Cloud Services van het Experience Platform Launch tot stand te brengen. De configuratie van de Cloud Service van de Lancering kan dan op een bestaande Plaats worden toegepast en de bibliotheken van de Lancering kunnen worden waargenomen ladend in zowel auteur als Publish milieu&#39;s. |
| 17 augustus 2020 | [AEM verbinden met Starten met Adobe I/O](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/connect-aem-launch-adobe-io.html) | Video | Leer hoe u een IMS-configuratie maakt met Adobe I/O om AEM te verifiëren met de Experience Platform Launch-API. Zodra deze integratie is geïnstalleerd, kan AEM via de API voor starten communiceren om toegang te krijgen tot de eigenschappen van Launch. |
| 17 augustus 2020 | [Een opstarteigenschap maken](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/create-launch-property.html) | Video | Leer hoe te om een bezit van de Lancering met de kale-minimumconfiguratie te creëren nodig aan opstelling de rest van de integratie. Gebruikers krijgen een introductie in de gebruikersinterface van Launch en leren meer over extensies, regels en publicatieworkflows. |
| 17 augustus 2020 | [Experience Platform Launch en AEM integreren](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/integrations/experience-platform-launch/overview.html) | Video | Experience Platform Launch is het platform voor tagbeheer van de volgende generatie en de beste manier om Adobe Analytics, Audience Manager [!DNL Target]en nog veel meer oplossingen te implementeren. Bekijk een overzicht van Experience Platform Launch en de aanbevolen integratie met Adobe Experience Manager. |
| 17 augustus 2020 | [AEM Assets voor beheerders configureren](https://video.tv.adobe.com/v/37647?captions=dut) | Video | In deze video kunnen beheerders meer leren over het configureren [!UICONTROL AEM Assets]. |
| 12 augustus 2020 | [Lokale ontwikkeling met AEM als Cloud Service SDK](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/commerce/develop.html) | Video | Leer hoe u een lokale ontwikkelomgeving voor [!UICONTROL AEM Commerce] en de [!UICONTROL AEM as a Cloud Service] SDK instelt. |
| 17 augustus 2020 | [Aangepaste formulieren vooraf invullen met behulp van het formuliergegevensmodel](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.1.forms) | Cursus | U kunt de velden van een adaptief formulier vooraf invullen met bestaande gegevens. Leer in deze cursus de velden vooraf in te vullen met het aanvraagkenmerk van het formuliergegevensmodel. |
| 17 augustus 2020 | [Adobe IMS-productprofielen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-product-profiles.html) | Video | Met Adobe IMS-productprofielen kunnen gebruikers zich aanmelden bij een AEM-auteurservice en een basislijn voor toegang bieden, afhankelijk van het productprofiel waaraan ze zijn toegevoegd. |
| 17 augustus 2020 | [Adobe IMS-gebruikersgroepen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-user-groups.html) | Video | Adobe IMS gebruikersgroepen vestigen logische reeksen gebruikers die aan AEM worden blootgesteld, waar zij kunnen worden leveraged om toestemmingen aan AEM gebruikers te bepalen. |
| 17 augustus 2020 | [Adobe IMS-gebruikers](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/accessing/adobe-ims-users.html) | Video | Leer over welke Adobe IMS gebruikers zijn, en hoe zij in Admin Console worden betreden en worden beheerd, en hoe zij aan login aan AEM als Cloud Service kunnen worden gebruikt. |
| 17 augustus 2020 | [Aan de slag met HTML5 Forms voor ontwikkelaars](https://experienceleague.adobe.com/?recommended=ExperienceManager-D-1-2020.forms) | Cursus | HTML5-formulieren bieden rendering van XFA-formuliersjablonen in HTML5-indeling. Met deze functie wordt de weergave mogelijk van formulieren op mobiele apparaten en desktopbrowsers waarop XFA-gebaseerde PDF niet wordt ondersteund. |

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

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwe productversies

Releasegegevens voor Campaign Classic, Campaign Standard en Control Panel.

#### Campaign Classic

* Release 20.2.2 - [meer informatie](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html#release-20-2-2-build-9180)

### Nieuwe cursussen en tutorials voor Campaign

Nieuwe video&#39;s, tutorials of cursussen die in de afgelopen maand zijn gepubliceerd.

| Gepubliceerd | Naam | Oplossing | Beschrijving |
| ----------- | ----------- | ---------- | ---------- |
| 10 augustus 2020 | [Doelen verfijnen door queryresultaten te combineren](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-combining-query-results.html) | Campaign Classic | Leer hoe te om uw doel te verfijnen door vraagresultaten in een werkschema te combineren gebruikend de doorsnede of de vakbondsactiviteiten. |
| 10 augustus 2020 | [De activiteit van de updatelijst gebruiken om een lijst met een werkschema tot stand te brengen](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/using-the-update-list-activity.html) | Campaign Classic | Begrijp het concept lijsten in Adobe Campaign Classic en leer hoe te om een lijst tot stand te brengen gebruikend de activiteit van de updatelijst in een werkschema. |
| 20 augustus 2020 | [Doelen verfijnen door queryresultaten uit te sluiten](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/automating-with-workflows/refining-targets-by-excluding-query-results.html) | Campaign Classic | Leer hoe u uw doel kunt verfijnen door een standaarduitsluiting toe te passen op een workflow. U leert ook hoe u vooraf gedefinieerde filters maakt en hoe u problemen ondervindt bij het opnemen van uw workflow. |
| 25 augustus 2020 | [Direct-mailleveringen maken](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | Begrijp hoe direct mail in Adobe Campaign werkt en leer hoe te om een direct-maillevering tot stand te brengen, te formatteren en uit te voeren. |  | 25 augustus 2020 | [Direct-maillevering maken](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/sending-messages/direct-mail/creating-direct-mail-deliveries.html) | Campaign Classic | Begrijp hoe direct mail in Adobe Campaign werkt en leer hoe te om een direct-maillevering tot stand te brengen, te formatteren en uit te voeren. |

### Help-bronnen voor Help

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/campaign-standard-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/overview.html) - [Releaseplanning](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/campaign-classic-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/overview.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/nl-NL/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/control-panel/using/release-notes.html) - Video&#39;s met stapsgewijze instructies voor [Campaign Standard](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/nl-NL/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Releaseopmerkingen bij Adobe Advertising Cloud.

* [Nieuwe functies in Advertising Cloud DSP](#adcloud-dsp)
* [Nieuwe functies in Advertising Cloud Search](#adcloud-search)

### Nieuwe functies in [!UICONTROL Advertising Cloud DSP] {#adcloud-dsp}

| Functie | Beschrijving |
| -----------| ---------- |
| Interactieve pre-roll uitgebreid met VAST-inventory | Elke interactieve pre-roll-plaatsing en -advertentie ondersteunt nu zowel VPAID- als VAST-inventory. **Opmerking:** Als uw primaire KPI de weergavemogelijkheid is, blijft u afzonderlijke VPAID- en VAST-plaatsingen en -advertenties maken, omdat zichtbare indrukkingen niet beschikbaar zijn voor VAST-advertenties. |

### Nieuwe functies in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

Release van **8 augustus**

| Functie | Beschrijving |
| ----------- | ---------- |
| [!UICONTROL Portfolios] | Positielimieten op portfolioniveau zijn niet meer beschikbaar in portfolioinstellingen. Eerder gemaakte positielimieten zijn verwijderd. |
| [!UICONTROL Constraints] | Op positie gebaseerde restricties en restrictievoorwaarden worden niet meer ondersteund: <br/> <ul><li>[!UICONTROL Min Pos] en [!UICONTROL Max Pos] beperkingen niet meer beschikbaar zijn en zijn verwijderd uit alle eerder gemaakte [!UICONTROL Bid & Position] beperkingen en [!UICONTROL Impression Share] beperkingen.</li><li>Existing [!UICONTROL Bid & Position] constraints that included position constraints but no bid constraints were paused. Zij zijn nog beschikbaar in de UI en in rapporten.</li><li>[!UICONTROL Bid & Position] de namen van de beperkingen werden gewijzigd in [!UICONTROL Bid] beperkingen .</li><li>Alle op positie-gebaseerde voorwaarden (het gebruiken [!UICONTROL Average Position], [!UICONTROL Weighted Average Position], of [!UICONTROL Last Known Pos] metriek) in om het even welk type van beperking werden verwijderd.</li></ul> <br/> **Opmerking:** Positiegegevens worden nog steeds ingevuld zolang deze beschikbaar zijn in de zoekmachines. Positie is met ingang van september 2020 niet langer beschikbaar in Microsoft Ads. |
| [!UICONTROL Campaigns] | (Google Ads-campagnes) Advertising Cloud Search ondersteunt nu advertentie-aanpassers in RSA&#39;s (responsieve zoekadvertenties). Voorheen werden deze ondersteund in alle advertentietypen behalve RSA&#39;s. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

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
| ------ | --------- |
| [!DNL Bizible] | <ul><li>Nieuwe op accounts gebaseerde segmentatie</li><li>Dashboardspecifieke filters opslaan</li><li>Bizible-dashboards exporteren als PDF&#39;s</li></ul> |
| Sales Connect | Venster- en Opdrachtcentrum-updates/verbeteringen maken |

### Afgeschafte elementen

* **Assetparameter API &quot;_method&quot;:** Na september 2020 laten Asset API Endpoints `_method` geen queryparameters meer passeren in een POST-body om URI-lengterestricties te omzeilen.
* **Afschaffing van Internet Explorer-ondersteuning:** Vanaf de juli-release op 31 juli 2020 wordt de Marketo Engage-gebruikersinterface niet meer ondersteund in Internet Explorer.

Zie [Marketo-releaseopmerkingen](https://docs.marketo.com/x/CgA6Ag) voor cumulatieve en historische releaseopmerkingen.
