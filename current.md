---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Sjabloon voor releaseopmerkingen bij Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 2cd60d72cfd5fa7d7ab0a17ba230162601f69b13
workflow-type: tm+mt
source-wordcount: '4584'
ht-degree: 32%

---


# Vroege toegang - Opmerkingen bij de release Adobe Experience Cloud - mei 2020

![Banner](/assets/experience-cloud-banner-3.png)

Deze pagina bevat nieuwe functies, correcties en belangrijke kennisgevingen in [!DNL Adobe Experience Cloud]. De de versiedata van de oplossing kunnen variëren. Kom regelmatig terug voor de nieuwste updates.

>[!IMPORTANT]
>
>Deze pagina bevat pre-releaseinhoud en kan vóór 21 mei 2020 worden gewijzigd. Nieuwe informatie die daarna wordt gepubliceerd, wordt genoteerd met de toegevoegde datum.

>[!NOTE]
>
>Meld u aan voor de [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases.

**Releasedatum: mei 2020**

Laatste update: **16 mei 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (koppelingen naar de Help-pagina van Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/nl/primetime/user-guide.html) (koppelingen naar de Help-pagina van Primetime)

Hebt u hulp nodig? Ga naar [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) voor cursussen, technische documentatie, snelle antwoorden, inzicht in de gebruikersgemeenschap en training onder leiding van instructeurs.

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Releasedatum: **21 mei 2020**

**Wat is er nieuw**

* Met uw Adobe ID kunt u lid worden van gebeurtenismeldingen met meer granulariteit, tot aan het aanbod van producten en invoegtoepassingen. Om u te helpen uw abonnement sneller in te stellen, raadt het proces voor zelfinschrijving nu een selectie van producten en aanbiedingen aan op basis van uw productrechten. Zo verkleint u het aantal e-mailberichten dat u ontvangt en levert u meer relevante meldingen in uw Postvak IN. Ga aan de slag op [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nieuwe en verbeterde functies die nu beschikbaar zijn**

| Functie | Beschrijving |
| -----------| ---------- |
| Verbeterde gebruikerservaring voor abonnementen en meldingen | <ul><li>[!DNL Marketo Engage] de regionale locaties worden nu gefilterd op basis van de geselecteerde lijst met productaanbiedingen .</li><li>[!DNL Marketo Engage] e-mailmeldingen zijn relevant voor de regio, locatie en omgeving van de gebruiker.</li></ul> |
| Bevestiging van abonnement op gebeurtenis | <ul><li>U kunt nu een e-mailbevestiging krijgen wanneer u zich abonneert op lopende updates voor één gebeurtenis.</li></ul> |
| Verbeteringen voor algemene bruikbaarheid van navigatie | <ul><li>Consistente gebruikerservaring met `Adobe.com` het navigatiemenu op het hoogste niveau.</li></ul> |

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud-interface {#ecloud}

Algemene updates van de Experience Cloud-interface.

**Geïntegreerd productdomein**

Adobe heeft de domein- en interfaceheader bijgewerkt om uw ervaring in alle Experience Cloud-toepassingen te verenigen en te verbeteren. Deze verbeteringen zijn ontworpen om uw ervaring op kleine maar belangrijke manieren te vereenvoudigen. Deze verbeteringen hebben geen invloed op uw huidige workflows.

Updates zijn:

* Nieuwe applicatie-URL&#39;s: `experience.adobe.com/<application name>`:
   * Uiteindelijk zal dit URL-patroon voor alle producten gelden. Kijk uit naar nieuwe URL&#39;s die gedurende deze maand van kracht worden.
   * Browserondersteuning: Tot de ondersteunde browsers behoren [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] en [!DNL Opera] (de nieuwste versies). **Opmerking:** Hoewel de Experience Cloud-interface deze browsers ondersteunt, wordt mogelijk niet elke browser door afzonderlijke applicaties ondersteund. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) biedt bijvoorbeeld geen ondersteuning voor [!DNL Opera] en [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) biedt geen ondersteuning voor [!DNL Safari].)
   * (Alleen [!DNL Safari]) De domeinwijziging kan problemen met cookies veroorzaken in [!DNL Safari]. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Experience Cloud in dit nieuwe domein functioneren.
* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde producthulp: [!UICONTROL Experience League] is geïntegreerd in het product, zodat een zoekopdracht in de Help ook resultaten bevat van gemeenschapsforums en video-content. Deze wijziging vereenvoudigt de toegang tot meer content en helpt u optimaal te profiteren van Experience Cloud. Klik daarnaast op **[!UICONTROL Help]** > **[!UICONTROL Feedback]** om problemen te melden of uw ideeën te delen met Adobe.

De volgende toepassingen gebruiken het nieuwe domein Experience.adobe.com:

| App of Service | Domein |
| -----------| ---------- |
| Introductiepagina van Experience Cloud | `experience.adobe.com/home` |
| Adobe-doel | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Reisbeheer | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Configuratiescherm Adobe-campagne | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Plaatsingsservice | `experience.adobe.com/places` |
| Softwaredistributie | `experience.adobe.com/downloads` |
| Admin Tool (bèta) | `experience.adobe.com/admin` |

## ![Pictogram](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Releaseopmerkingen voor de [!DNL Experience Platform,] inclusief [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] en beveiligingsbulletins.

### Interfaceverbeteringen

Bijgewerkt: **15 mei 2020**

[!DNL Adobe Experience Platform] Hiermee geeft u updates voor het domein en de headerbalk vrij om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-toepassingen. Updates zijn:

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikershulp, inclusief aanbevolen artikelen en contextrelevante documentatie in het menu Help.
* Mogelijkheid om feedback te geven over het Experience Platform en de tickets voor bestandsondersteuning.

See [Experience Platform release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) for more information.

### Klantkenmerken - nieuwe documentatie

Bijgewerkt: **15 mei 2020**

* [Customer Attributes support for CCPA](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Customer Attributes support for GDPR](https://docs.adobe.com/content/help/en/core-services/interface/customer-attributes/gdpr.html) (General Data Protection Regulation)

### Journey Orchestration {#journey}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

* [Documentatie](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Releaseopmerkingen](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [Instructievideo&#39;s](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Aanvullende releasedata bij Experience Platform

* [Releaseopmerkingen bij Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)
* [Releaseopmerkingen bij Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Beveiligingsbulletins en adviezen](https://helpx.adobe.com/nl/security.html) (Alle Adobe-producten)

## ![Pictogram](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nieuwe functies in de reisanalyse van klanten](#cust-journey)
* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Belangrijke kennisgevingen voor analysebeheerders](#aa-notices)
* [AppMeasurement](#appm)
* [Nieuwe tutorials voor Analytics](#tutorials-analytics)

### Nieuwe functies in de reisanalyse van klanten {#cust-journey}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: Wereldwijde beschikbaarheid | Maakt [!UICONTROL Customer Journey Analytics] beschikbaar voor klanten in EMEA en APAC. |
| [!UICONTROL Customer Journey Analytics]: Ondersteuning voor [!UICONTROL Adobe Experience Platform Sandboxes] | Staat u toe om specifiek te selecteren [!UICONTROL Adobe Experience Platform Sandboxes] om Verbindingen te bouwen CJA van. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

### Nieuwe functies in Adobe Analytics {#aa-features}

<!-- Bulk Ingest: Enables you to ingest batches of Analytics data. Useful for server-side and offline data. Learn more...
First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Functie | Beschrijving |
| -----------| ---------- |
| Analyseondersteuning voor [!UICONTROL Adobe Experience Platform Edge Network] | Hiermee kunt u één tag gebruiken om gegevens naar meerdere Adobe-oplossingen te verzenden, zoals Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile en Experience Cloud ID Service. [Meer informatie...](https://docs.adobe.com/content/help/en/experience-platform/edge/home.html) |
| [!UICONTROL Adobe Analytics dashboards] | [!UICONTROL Adobe Analytics dashboards] is een mobiele app waarmee gebruikers altijd en overal toegang hebben tot inzichten van Adobe Analytics. Deze app is bedoeld voor managers die onderweg toegang zoeken tot belangrijke metriek. Het maakt toegang mogelijk tot gekrulde, interactieve scorecards en is beschikbaar voor zowel de iOS- als Android-besturingssystemen. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace]: Automatisch samenstellen [!UICONTROL Freeform Tables] vanuit een leeg frame | Eerder kon u componenten niet direct in een leeg project of leeg paneel laten vallen; u moest een [!UICONTROL Freeform Table] eerste toevoegen. U kunt componenten nu rechtstreeks neerzetten in een leeg project of deelvenster en een [!UICONTROL Freeform Table] sjabloon wordt automatisch voor u gemaakt in een aanbevolen indeling. Bovendien, werden de verbeteringen aangebracht aan hoe de gemengde componenttypes (zoals afmetingen en metriek) wanneer gelaten vallen in een lege Lijst Freeform samen worden behandeld. |

#### Oplossingen voor Adobe Analytics

* Probleem verholpen waarbij ontbrekende [!DNL Analytics] segmentgegevens werden veroorzaakt in Audience Manager. (AN-206221)
* Probleem verholpen waarbij bij [!UICONTROL Data Sources] verwerking onjuiste datums werden weergegeven. (AN-213604)
* Probleem verholpen waarbij classificatiebestanden niet goed naar FTP werden geüpload. (AN-214102)
* Probleem verholpen waarbij de API-methode `Segments.Get` geen volledige reactie retourneerde. (AN-206210)
* Probleem verholpen waarbij tabelregelitems werden geconverteerd naar speciale tekens in [!DNL Workspace] PDF-download. (AN-196153)
* Probleem verholpen met aanroep van Adobe Analytics API 1.4 werkt `visattrcustomeridcustomerattributes` niet correct. (AN-186873)
* Probleem verholpen waarbij gegevens in rapporten werden weergegeven, maar niet in het [!UICONTROL Data Feed]bestand werden weergegeven. (AN-211923)
* Probleem verholpen waarbij [!UICONTROL Product Profile] machtigingen niet konden worden gekopieerd. (AN-21113)
* Probleem verholpen waarbij gebruikers met id&#39;s met federatie zich niet konden aanmelden bij [!UICONTROL Report Builder]. (AN-207750)
* Probleem verholpen waarbij [!UICONTROL AdWords] gegevens niet werden weergegeven [!UICONTROL Advertising Analytics]. (AN-213249)
* Probleem verholpen waarbij classificatiegegevens niet werden weergegeven in de trendweergave. (AN-212761)
* Probleem verholpen waarbij een onjuist aantal gepubliceerde segmenten in het [!UICONTROL Segment Manager]segment werd veroorzaakt. (AN-213374)
* Probleem verholpen met de **[!UICONTROL Show Upwards Trend As...]** optie in het deelvenster [!UICONTROL Calculated Metric Editor] - Het werkte niet bij het toepassen van filters. (AN-214223)
* Meerdere problemen met importeren en exporteren opgelost. [!UICONTROL Classification] (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Oplossing voor meerdere problemen met [!UICONTROL Classification Rule Builder]. (AN-213826, AN-213550, AN-213095)
* Opgeloste problemen met [!UICONTROL Data Sources] verwerking. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-21751, -217947, AN-219018, AN-214691, AN-218401)
* Oplossing voor problemen met FTP-connectiviteit. (AN-115525)
* Meerdere [!DNL Analytics] [!UICONTROL Data Feeds] problemen opgelost. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, -217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Oplossing voor problemen met [!UICONTROL Data Warehouse] aanvragen. (AN-181836)
* Correctie van problemen in gedownloade PDF- [!UICONTROL Workspace] projecten waarbij waarden werden geconverteerd naar speciale tekens. (AN-196153)
* Probleem verholpen waarbij [!UICONTROL Product Profile] machtigingen niet konden worden gekopieerd in [!UICONTROL Admin Console]. (AN-21113)
* Probleem verholpen waarbij tijdnotaties in berekende metriek werden afgebroken voor negatieve waarden. (AN-210900)
* Probleem verholpen waardoor gebruikers de gegevens voor statische rijen niet konden wijzigen. [!UICONTROL Attribution Model] (AN-207872)
* Probleem opgelost waarbij de [!UICONTROL Scheduled Report] builder vastliep in een status in de wachtrij. (AN-215317)
* Vaste de [!UICONTROL ExactTarget Data Connector]. (AN-210794)
* Opgeloste latentieproblemen in [!UICONTROL Bulk Ingestion API]. (AN-210165)
* Probleem verholpen waarbij gebruikers zich niet konden aanmelden [!UICONTROL Report Builder] met een federatieve id. (AN-207750)
* Probleem verholpen waarbij [!UICONTROL Advertising Analytics] gegevens niet konden worden [!DNL Google AdWords] weergegeven. (AN-213249)
* Probleem verholpen waardoor [!UICONTROL Workspace] [!UICONTROL Project Viewed] gebeurtenissen niet konden worden weergegeven in logboeken. (AN-214134)
* Probleem verholpen dat zich voordeed bij het wijzigen van het datumbereik in [!UICONTROL Workspace] en het selecteren **[!UICONTROL Apply to all panels]**. De datum is in sommige deelvensters niet gewijzigd. (AN-214944)
* Probleem verholpen waarbij waarschuwingen niet konden worden gemaakt of bewerkt. (AN-215920)
* Probleem verholpen waarbij voor alle dynamische datumbereiken onjuiste datums werden [!UICONTROL Workspace] weergegeven die te wijten waren aan de sporadisch overschakelende eerste dag van de week naar een zondag vanaf een maandag. (AN-218835)

#### Oplossingen voor aanvullende Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| Wijzigen in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace] | 7 april 2020 | Sinds maart 2020 is in [!UICONTROL Analysis Workspace] gewijzigd hoe de waarde _Geen_ communiceert met [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before entry or exit. Stel dat de eerste hit van een bezoek geen waarde heeft voor Vars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] the first hit will show as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| EOL van **[!UICONTROL Conversion Level]**-instelling | 3 maart 2020 | De niet-functionerende instelling [Conversieniveau](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** wordt op 12 maart 2020 uit de interface verwijderd. |
| EOL van **[!UICONTROL Dashboard Archive]** | 27 maart 2020 | De instelling **[!UICONTROL View Archive]** onder **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] zal vanaf oktober 2020 niet meer beschikbaar zijn. |
| Einde van ondersteuning voor TLS 1.1 | 3 oktober 2019 | Op 31 maart 2020 verwijdert Adobe Analytics de ondersteuning voor TLS 1.1. Deze wijziging is een onderdeel van onze voortdurende inspanningen om de hoogste veiligheidsnormen te handhaven en de veiligheid van klantdata te bevorderen. |
| Nieuw Adobe Analytics-domein | 18 dec. 2019 | Op 16 januari 2020 is Adobe Analytics begonnen met de verhuizing naar een nieuw domein - `https://experience.adobe.com/analytics.`<br>**Opmerking:** Deze wijziging geldt voor alle gebruikers die met hun Adobe ID of Enterprise ID toegang hebben tot Analytics.<ul><li>De domeinwijziging kan tijdens het laden van Analytics in Safari problemen met cookies veroorzaken. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Analytics in dit nieuwe Adobe Experience Cloud-domein functioneren. U kunt zonder problemen andere browsers gebruiken, omdat dit alleen voor [!DNL Safari]-gebruikers geldt.</li><li>De domeinwijziging kan ervoor zorgen dat [!UICONTROL Activity Map] voor bepaalde klanten [in specifieke gevallen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html) niet meer werkt.</li></ul> |
| Einde van levensduur - Verouderde Analytics-API&#39;s | 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Zie [AppMeasurement voor Javascript-releaseopmerkingen](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Versie 2.20.0 is uitgebracht op 5 maart 2020.

### Nieuwe tutorials voor Analytics {#tutorials-analytics}

| Inhoud | Beschrijving |
| -----------| ---------- |
| [Sjabloon voor zelfstudie training in de werkruimte Analyse](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | In de [!UICONTROL Analysis Workspace] zelfstudie Training worden algemene terminologie en stappen besproken voor het maken van uw eerste project in [!UICONTROL Workspace]. |
| [Vergelijkingen van voorafgaande maanden en jaar toevoegen aan trends](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Leer hoe u aangepaste datumbereiken toepast om maandelijkse en jaarlijkse trendvergelijkingen te maken voor elke metrische waarde in [!UICONTROL Analysis Workspace]. |
| [Extensie Donkere modus voor analysewerkruimte](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Schakel de extensie Donkere Reader Chrome in om de analysewerkruimte donker te maken. |
| [Kleurenpipetextensie voor het definiëren van aangepaste paletten](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Leer hoe u de extensie ColorPick EyeDropper Chrome gebruikt om eenvoudig de hexadecimale waarden te vinden die u nodig hebt voor een aangepast kleurenpalet in uw [!UICONTROL Workspace] projecten. |

#### Bronnen voor Analytics Help

* [Zelfstudies voor Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-productdocumentatie](https://docs.adobe.com/content/help/en/analytics/landing/home.html)

## ![Pictogram](/assets/audience-manager.png) Audience Manager {#aam}

Nieuwe functies, correcties, documentatie en zelfstudies in Audience Manager.

### Updates van gebruikersinterface

Audience Manager geeft updates voor het domein en de headerbalk uit om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-toepassingen.

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikershulp, inclusief aanbevolen artikelen en contextrelevante video&#39;s in het menu Help.
* Mogelijkheid om feedback te geven over het Experience Platform en de tickets voor bestandsondersteuning.
* Een nieuw, eenvoudiger URL-patroon. Werk uw bladwijzers bij naar de nieuwe URL: `experience.adobe.com/audience-manager`.

Deze updates zijn alleen beschikbaar voor gebruikers die zich aanmelden met een Adobe-id. Raadpleeg Gebruikers en producten [van de cloud](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-getting-started.html)beheren om over te schakelen op een Adobe-id.

### Nieuwe functies en oplossingen in Adobe Audience Manager

| Functie | Beschrijving |
| -----------| ---------- |  
| [Bulkbeheertools (BAAAM)](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | We hebben een nieuw werkblad met bulkbeheertools geüpload: <br><br><ul><li>Hiermee kunt u de submappen in de hiërarchie van het kenmerk weergeven (AAM-51528)</li><li>Haalt metriek terug wanneer ertoe aangezet voor eigenschappen verbonden aan CRM IDs (dwars-apparaat IDs) (AAM-52135)</li><li>Oplossing voor een taalcoderingsprobleem voor Koreaanse tekens (AAM-AAM-54006)</li></ul> |

**Oplossingen**

* Probleem verholpen waarbij trendrapporten de timing uitmaakten voor mappen met een groot aantal kenmerken. (AAM-54457)
* Probleem verholpen waarbij klanten de gegevens niet konden zien [!UICONTROL Expression builder] in de workflow voor het maken/bewerken van de taak. (AAM-54255)
* Probleem verholpen waarbij foutberichten in de gebruikersinterface slechts voor een korte tijd zouden worden weergegeven, die zouden verdwijnen voordat klanten de kans kregen ze te lezen. Dit kwam bijvoorbeeld voor wanneer het proberen om een segment te schrappen dat aan een bestemming in kaart werd gebracht. (AAM-54031)
* Probleem verholpen waarbij klanten die de e-mails [!UICONTROL Audience Marketplace] niet meer gebruiken maandelijks factureren. (AAM-54602)
* Probleem verholpen waarbij klanten die op bepaalde kenmerken van andere locaties in de gebruikersinterface klikken, verbroken koppelingen zouden zien in plaats van de kenmerken. (AAM-54768)
* Probleem verholpen waarbij in de modus voor het bewerken van de eigenschapuitdrukking door op ENTER te drukken de pagina zou worden vernieuwd en de standaardexpressie zou verloren gaan. (AAM-54210)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nieuwe zelfstudies voor Audience Manager {#tutorials-aam}

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Begrijpen van de BasisTermijnen en Concepten in de Manager van de Publiek](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | In deze video worden enkele basistermen en -concepten besproken die u in Audience Manager kunt starten, zoals signalen, kenmerken, segmenten, enzovoort. |
| [De gegevensstroom begrijpen in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Deze video helpt u Adobe Audience Manager te begrijpen door de gegevensstroom in, door en uit de toepassing te beschrijven. |
| [Audience Manager - Overzicht van een DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Begrijp de belangrijkste uitdagingen met dwars-kanaalpersonalisatie en hoe de Manager van de Publiek van Adobe de klantenreis drijft. Leer ook welke gegevenstypes in de Manager van het Publiek kunnen worden gecontroleerd en identificeer de ad-tech eco-systeempartners die met de Manager van het Publiek worden geïntegreerd. |
| [Gebruiksscenario&#39;s van Auditiebeheer](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | In deze video identificeren wij vier gemeenschappelijke het gebruiksgevallen van de Manager van de Publiek, en beschrijven de beste praktijken verbonden aan hen. |
| [Werken met apparaatmetingen in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | In deze video bespreken we het verschil tussen apparaatprofielen en apparaatprofielen en tonen we waar de getallen in de gebruikersinterface overeenkomen met deze verschillende profieltypen. |
| [Voorspelend publiek in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | In deze video bespreken we wat het voorspellende publiek van Audience Manager is, geven we details over hoe ze werken en wijzen we op gebruiksgevallen. |
| [Configureer en rapporteer op voorspellend publiek in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | In deze video lopen wij door de Predictive configuratie van het Publiek in de interface van de Manager van de Publiek. We zien ook de verslagen die de resultaten van het model laten zien. |

## ![Pictogram](/assets/aem.png) Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### Productupdates

* **AEM als Cloud Service**

   * Verbeteringen en correcties in de verwerking van bedrijfsmiddelen. Het dialoogvenster voor herverwerking van bedrijfsmiddelen geeft de gebruiker meer controle, maakt het mogelijk een specifiek verwerkingsprofiel te selecteren en of een workflow voor naverwerking moet worden geactiveerd.
   * Verbeteringen in de prestaties van dynamische media-elementen.

### Zelfondersteuning

* **Automated Forms Conversion Service - release AFC-2020.03.1**

   Een nieuwe optie is beschikbaar wanneer u de recentste schakelaar installeert:

   **[!UICONTROL Auto-detect logical sections]**: Met de [!UICONTROL Auto-detect logical sections] optie kunt u deelvensters op paginaniveau (op paginanummers gebaseerde deelvensters) neerzetten en alleen logische deelvensters maken. Ook worden de velden die niet tot een sectie met voorafgaande logische secties en velden van een logische sectie behoren die over twee aangrenzende pagina&#39;s zijn verspreid, in één logische sectie samengevoegd. Als sommige velden van een logische sectie zich bijvoorbeeld aan het einde van pagina 1 bevinden en sommige zich aan het begin van pagina 2 bevinden, worden al deze velden opgenomen in één logische sectie.

* **Niet-ondersteunde afbeeldingsindelingen in Dynamic Media**

   Informatie over de subtypen van bestandsindelingen voor rasterafbeeldingen waarin geen ondersteuning wordt geboden [!UICONTROL Dynamic Media].

   Zie [Niet-ondersteunde indelingen voor rasterafbeeldingen in Dynamische media](https://docs.adobe.com/content/help/en/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Inhoudsfragmenten**

   Informatie over de ondersteuning voor [inhoudsfragmenten in de HTTP-API](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html)van AEM Assets, samen met [het aanpassen en uitbreiden van inhoudsfragmenten](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html)en het configureren van [inhoudsfragmenten voor rendering](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League Community**

   Verbinden met de [AEM Experience League Community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): Stel vragen aan collega&#39;s en AEM-experts, blader door threads en deel uw tips en expertise!

* **AEM-nieuwsbrieven**

   De AEM-nieuwsbrief van [!UICONTROL Experience League] is ontworpen om u te helpen snel aan de slag te gaan met AEM, zodat u meteen aan de slag kunt. Hier is de meest recente nieuwsbrief:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager is nu beschikbaar als cloudservice.
   * [Abonneren](https://adobeeventsonline.com/AEM/2017/NL/Optin/) op de Experience Insider Newsletter.
   * Archiefbestanden voor nieuwsbrieven weergeven in de sectie met [AEM-bronnen](https://helpx.adobe.com/nl/support/experience-manager/6-5.html) op de pagina Leren en ondersteunen van Adobe Experience Manager 6.5.

### Nieuwe tutorials voor Experience Manager

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Lokale AEM-runtime instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) kan lokaal worden uitgevoerd met behulp van de [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. This allows developers to deploy to, and test custom code, configuration, and content prior to committing it to source control, and deploying it to a [!UICONTROL AEM as a Cloud Service] environment. |
| [Aan de slag met AEM Assets](https://video.tv.adobe.com/v/33624?captions=dut) | Een introductievideo over aan de slag gaan met AEM Assets voor zakelijke gebruikers. |
| [Metagegevensmappenschema&#39;s](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Met mappenschema&#39;s voor metagegevens kunnen gebruikers metagegevens die aan elementmappen zijn gekoppeld, zelf beheren en controleren in plaats van rechtstreeks op elementen. |
| [Tags](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Tags zijn een integraal hulpmiddel voor het beheer van elementen in de maphiërarchie van verschillende elementen. Het instellen van een tagtaxonomie is van essentieel belang om gebruikers in staat te stellen bedrijfsmiddelen in AEM te vinden en te organiseren. |
| [Metadataprofielen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Met metagegevensprofielen kunnen standaardmetagegevens automatisch worden toegepast op elementen in elementmappen. Hierdoor wordt het beheer van metagegevens voor AEM-gebruikers minder belast en wordt de consistentie van metagegevens verbeterd. |
| [Metagegevensschema&#39;s](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Metagegevensschema&#39;s definiëren de interface die metagegevens van elementen in AEM beschikbaar maakt. In deze video wordt de combinatie van methoden voor het toepassen van elementen besproken. |

### Aanvullende bronnen

* [Opmerkingen bij de release van AEM als Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM als documentatie van de Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [AEM 6.4 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [AEM 6.3 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [AEM 6.2 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://helpx.adobe.com/nl/experience-manager/cloud-manager/user-guide.html)
* [Opmerkingen bij de release van AEM Cloud Manager](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Releaseopmerkingen bij Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Releaseopmerkingen bij Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Campaign Standard

* [Adobe Campagne Standard 20.3-release](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campagne

| Functie | Beschrijving |
| -----------| ---------- |  
| Beheer van GPG-sleutels | Installeer en/of produceer GPG sleutels op een marketing instantie, om gegevens te coderen die van Campagne worden verzonden en inkomende gegevens te decrypteren. |
| Certificaatbeheer voor CNAME-subdomeinen | Het Controlebord staat u nu toe om de SSL certificaten van uw subdomeinen te vernieuwen die met de methode CNAME zijn afgevaardigd. |

### Nieuwe zelfstudies voor campagnes

* Nieuwe tutorials voor Campaign Standard

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Configuratiescherm - Google TXT-recordbeheer](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Leer hoe u verificatiegegevens van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Configuratiescherm van de Campagne. |
| [Een workflow configureren en uitvoeren met de externe API-activiteit](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Leer hoe te om een extern REST API eindpunt te roepen gebruikend de Externe API activiteit. |
| [Aan de slag met pushmeldingen voor Android-zelfstudie](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | In deze zelfstudie worden de stappen beschreven die nodig zijn om pushmeldingen in te stellen met Campagnestandaard en Android App. |

* Nieuwe lesbestanden over klassieke campagnes

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Groot gegevensbeheer op Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Begrijp hoe u de Snowflake-aansluiting kunt gebruiken in Adobe Campaign Classic. |
| [Configuratiescherm - Google TXT-recordbeheer](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Leer hoe u verificatiegegevens van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Configuratiescherm van de Campagne. |

### Bronnen voor hulp bij campagnes

* Adobe Campagnestandaard: [Help Center](https://docs.adobe.com/content/help/en/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) &#39;s - [Release-planning](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)&#39;s - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nieuwe functies in DSP voor Advertising Cloud](#adcloud-dsp)
* [Nieuwe functies in Cloud Search voor advertenties](#adcloud-search)

### Nieuwe functies in DSP voor Advertising Cloud {#adcloud-dsp}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] en [!UICONTROL Campaigns Beta] | De maatinstellingen van de IAS voor fraude en merkveiligheid, die u optioneel voor elke campagne kunt configureren, bevatten nu opties voor het meten van VAST- en VPAID-voorraden. |
| [!UICONTROL Campaigns Beta] | De gegevensvisualisatie en de laadtijden van de pagina zijn verbeterd. |
|  | Op alle pagina&#39;s kunt u nu Excel-rapporten downloaden die zijn gebaseerd op de huidige filters en weergaven. |
|  | (In versie van 22 mei) Nieuwe metriek omvat de metriek All-time, Huidige Levering van het Interval, Datum Specifieke OTS. |
| [!UICONTROL Blacklists] | In het systeem van voorspellingen wordt nu automatisch de zwarte lijst van adverteerders of accounts gebruikt. Gebruikers hoeven de zwarte lijst niet meer in de plaatsingsinstellingen te plakken. |
| [!UICONTROL Inventory Deals] | (Gesloten Bèta) Een nieuwe, vereenvoudigde vorm staat u toe om snel opstelling, uit te geven en problemen op te lossen zijplatform (SSPs) overeenkomsten die niet beschikbaar in identiteitskaart Inbox van de Overeenkomst zijn. |
|  | Wanneer u een pakket van programmatic gewaarborgde overeenkomsten in identiteitskaart Inbox van de Overeenkomst goedkeurt, wordt u nu gealarmeerd dat u een standaardplaatsing voor elk van deal IDs moet tot stand brengen. |

### Nieuwe functies in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaigns] | (Google Ads-accounts; bètaservice) Vanaf eind mei kunt u met Advertising Cloud Search gegevens voor uw Google Gmail-weergavecampagnes en uw Google Smart Shopping-campagnes synchroniseren met Google-conversies voor tracering en rapportage. Met deze service kunt u ook de instellingen voor de campagne en de groep voor uw bestaande campagnes bewerken vanuit de weergaven Campagnes en Advertentiegroepen. De service is optioneel. Wanneer de service algemeen beschikbaar is, worden extra kosten in rekening gebracht.<br>Neem voor meer informatie over de service, waaronder het bètaprogramma en het toekomstige bereik, contact op met uw accountmanager van Adobe. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Voor de versienota&#39;s van Magento raadpleegt u:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] is een volledige applicatie voor leadmanagement en B2B-marketeers die klantervaringen willen transformeren door betrokkenheid in elke fase van complexe kooptrajecten.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo] releaseopmerkingen [](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) voor de meest recente releasegegevens.

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
