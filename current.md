---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Sjabloon voor releaseopmerkingen bij Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: a9f229b5766e90c4fef37d5c35f055856aa42f5a

---


# Releaseopmerkingen bij Adobe Experience Cloud - april 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nieuwe functies en oplossingen in [!DNL Adobe Experience Cloud].

>[!NOTE]
>
>Meld u aan voor de [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases. Nieuwe informatie die na de release wordt gepubliceerd, wordt gemarkeerd met de publicatiedatum.

**Releasedatum: april 2020**

Laatste update: 29 **april 2020**

(Specifieke versiedata kunnen variëren.)

* [Adobe-systeemstatus](#status)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) **(Bijgewerkt op 29 april)**
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (koppelingen naar de Help-pagina van Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (koppelingen naar de Help-pagina van Primetime)

Op zoek naar de Help-startpagina? Raadpleeg de [documentatie bij Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL De Status] van het Systeem van Adobe verstrekt gedetailleerde informatie, statusupdates, en e-mailberichten over de producten van de wolk van Adobe en de gebeurtenissen van de dienststroomonderbreking, en van het onderhoud. Ga naar [status.adobe.com](https://status.adobe.com/).

**Wat is er nieuw**

* Met uw Adobe ID kunt u lid worden van gebeurtenismeldingen met meer granulariteit, tot aan het aanbod van producten en invoegtoepassingen. Bovendien wordt in onze recentste versie nu een selectie van producten en services aanbevolen op basis van uw productrechten. Dit stroomlijnt het lidmaatschapsproces doordat er minder besluiten of kliks nodig zijn om lidmaatschappen tot stand te brengen, en het zorgt vooral voor meer relevante berichten in uw Postvak IN. Ga aan de slag op [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nieuwe en verbeterde functies die nu beschikbaar zijn**

| Functie | Beschrijving |
| -----------| ---------- |
| Gepersonaliseerde lidmaatschappen op basis van rechten | <ul><li>Vooraf geselecteerde abonnementsaanbevelingen op basis van de DX-rechten van de gebruiker.</li><li>Aanbevolen lidmaatschappen worden boven aan de productlijst gemarkeerd voor snelle visualisatie.</li><li>De ontvangen e-mailmeldingen zijn relevant voor de productrechten van de gebruiker.</li></ul> |
| Eenvoudiger beheer van lidmaatschappen | <ul><li>**[!UICONTROL Abonnementen]** beheren heeft een nieuwe gebruikerservaring om zowel product- als gebeurtenisabonnementen te beheren.</li><li>Nieuwe optie om product- en gebeurtenislidmaatschappen afzonderlijk weer te geven en te bewerken.</li><li>The **[!UICONTROL Delete]** option allows you to unsubscribe from a product or event subscription.</li><li>The one-click **[!UICONTROL Unsubscribe all]** option is available for the product subscriptions.</li><li>UX-ondersteuning is beschikbaar voor Web/Mobile/Tablet Surfaces en voor localisatie in 19 talen.</li></ul> |

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud-interface {#ecloud}

Nieuwe functies en oplossingen in de Experience Cloud-interface:

* Experience Cloud [!UICONTROL Feed] page was deprecated. (EXC-8505)
* De aanmeldingspagina van Experience Cloud is bijgewerkt met nieuwe brandingselementen. (EXC-10747)

Raadpleeg de [Experience Cloud-interface Help](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) voor productdocumentatie.

### Geïntegreerd productdomein

Adobe werkt aan een update van de domein- en interfaceheader om uw ervaring in alle Experience Cloud-applicaties te integreren en te verbeteren. Deze verbeteringen zijn ontworpen om uw ervaring op kleine maar belangrijke manieren te vereenvoudigen. Deze verbeteringen hebben geen invloed op uw huidige workflows.

Updates zijn:

* Nieuwe applicatie-URL&#39;s: `experience.adobe.com/<application name>`:
   * Uiteindelijk zal dit URL-patroon voor alle producten gelden. Kijk uit naar nieuwe URL&#39;s die gedurende deze maand van kracht worden.
   * Browserondersteuning: Tot de ondersteunde browsers behoren [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] en [!DNL Opera] (de nieuwste versies). **Opmerking:** Hoewel de Experience Cloud-interface deze browsers ondersteunt, wordt mogelijk niet elke browser door afzonderlijke applicaties ondersteund. ([Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) biedt bijvoorbeeld geen ondersteuning voor [!DNL Opera] en [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) biedt geen ondersteuning voor [!DNL Safari].)
   * (Alleen [!DNL Safari]) De domeinwijziging kan problemen met cookies veroorzaken in [!DNL Safari]. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Experience Cloud in dit nieuwe domein functioneren.
* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Improved product help: [!UICONTROL Experience League] is integrated into the product so that a help search also includes results from community forums and video content. Deze wijziging vereenvoudigt de toegang tot meer content en helpt u optimaal te profiteren van Experience Cloud. Additionally, click **[!UICONTROL Help]** > **[!UICONTROL Feedback]** to report issues or share your ideas with Adobe.

## ![Pictogram](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Opmerkingen bij de release [!DNL Experience Platform,] inclusief [!DNL Experience Platform Launch,] Reisorganisatie [!UICONTROL ,]Aanbiedingen [!UICONTROL ,]Personen [!UICONTROL ,]Plaatsen , Mobiele Services en beveiligingsbulletins.

### Journey Orchestration {#journey}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

* [Documentatie](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html)
* [Releaseopmerkingen](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html)
* [Instructievideo&#39;s](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobiele services en mobiele SDK&#39;s {#mobile}

Android 4.18.2 (3 april 2020):

* In App Messaging: For security reasons, [!UICONTROL WebViews] created by the SDK now set property `setAllowFileAccess` equal to _false_.

iOS 4.19.2 (24 maart 2020):

* Algemeen: oplossing voor lekken in [!DNL Target]-code.

Eenheid 4.19.0 (10 maart 2020):

* Updated [!UICONTROL Unity Plugin] to use versions 4.19.0 of iOS and 4.18.0 or [!DNL Android].
* Er is een nieuwe acquisitiemethode beschikbaar voor [!DNL Android] waardoor URL&#39;s die door referrer-API&#39;s van [!DNL Google Play] worden verstrekt, kunnen worden verwerkt.

### Aanvullende releasedata bij Experience Platform

* [Releaseopmerkingen bij Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html)
* [Releaseopmerkingen bij Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Beveiligingsbulletins en adviezen](https://helpx.adobe.com/nl/security.html) (Alle Adobe-producten)

## ![Pictogram](/assets/analytics.png) [!DNL Analytics] {#analytics}

>[!IMPORTANT]
>
>De Adobe Analytics-onderhoudsrelease van april is verplaatst naar 21 mei 2020. Zie [releaseopmerkingen van maart](c-legacy-releases/2020/03122020.md) voor de nieuwste releasedata van Analytics

* [Customer Journey Analytics](#cust-journey)
<!--* [New features in Adobe Analytics](#aa-features)-->
* [Belangrijke kennisgevingen voor Analytics-beheerders](#aa-notices) (bijgewerkt op 16 april 2020)
* [AppMeasurement](#appm)
* [Nieuwe tutorials voor Analytics](#tutorials-analytics)

### Customer Journey Analytics {#cust-journey}

| Functie | Beschrijving |
| -----------| ---------- |
| Data Workbench 6.74 (**update 29-4-2020**) | Update van TLS-certificaatparsering (Identity Management Service) in serverimplementatie. Deze update breidt het parseren uit van tekenreeksovereenkomst aan regelmatige uitdrukking, met inbegrip van de capaciteit om onderwerpalternatieve (San) certificaten te behandelen. See [Data Workbench release notes](https://docs.adobe.com/content/help/en/data-workbench/using/release-notes/release-notes.html) for more information. |
| [!UICONTROL Klantenreisanalyse]: Geautomatiseerde back-up van gegevensset | This new option lets you import all historical data for a connection in [!UICONTROL Customer Journey Analytics]. [Meer informatie](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-connections/create-connection.html) |

<!--### New features in Adobe Analytics {#aa-features}

| Feature    | Description  |
| -----------| ---------- |
|Analytics support for [!UICONTROL Experience Edge] |You can now forward data that was sent to [!UICONTROL Experience Edge] to Analytics.|
 |[!UICONTROL Workspace]: Automatically build Freeform Tables from a blank state|Previously, you could not drop components directly into a blank project or blank panel; you had to add a freeform table first. You can now drop components directly into a blank project or panel, and a freeform table will automatically be built for you in a recommended format. Additionally, improvements were made to how mixed component types (e.g. dimensions & metrics) are handled when dropped into a blank freeform table together.|

#### Analytics fixes

* Fixed an issue that caused missing Analytics segment data in Audience Manager. (AN-206221)
* Fixed an issue with [!UICONTROL Data Sources] processing showing the wrong dates. (AN-213604)
* Fixed an issue with classification files not getting uploaded to FTP properly. (AN-214102)
* Fixed an issue with the API method `Segments.Get` not returning a full response. (AN-206210)
* Fixed an issue where table line items were converted to special characters in [!DNL Workspace] PDF download. (AN-196153)
* Fixed an issue with Adobe Analytics API 1.4 call `visattrcustomeridcustomerattributes` not working properly. (AN-186873)
* Fixed an issue with data appearing in reports but missing from the [!UICONTROL Data Feed]. (AN-211923)
* Fixed an issue with being unable to copy [!UICONTROL Product Profile] permissions. (AN-211113)
* Fixed an issue where users with Federated IDs were not able to log in to Report Builder. (AN-207750)
* Fixed an issue with [!UICONTROL AdWords] data not showing in [!UICONTROL Advertising Analytics]. (AN-213249)
* Fixed an issue where classification data did not display in the trended view. (AN-212761)
* Fixed an issue that caused an incorrect published segment count in the [!UICONTROL Segment Manager]. (AN-213374)

#### Additional Analytics fixes

AN-212151; AN-214343; AN-215017; AN-115525; AN-123869; AN-101871; AN-152580; AN-160480; AN-199299; AN-209486; AN-212961; AN-211539; AN-213095; AN-212653; AN-211826; AN-206948; AN-208607; AN-204286; AN-214401; AN-212130; AN-211943; AN-212709; AN-212833; AN-211550; AN-212977; AN-213422; AN-213450; AN-214528; AN-213827; AN-214094; AN-214153; AN-214234; AN-214355; AN-214427; AN-214642; AN-214691; AN-214924; AN-215080; AN-215212 -->

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| De selectie Segment toegepast in datawarehouse is verwijderd | 16 april 2020 | Vanaf 16 april 2020 controleren wij niet meer of een segment is toegepast in een datawarehouseaanvraag vanuit de Segment Builder. Vroeger werd bij deze controle gezocht naar afzonderlijke segmenten die waren toegepast in datawarehouseaanvragen (niet naar meervoudige toegepaste segmenten), werd een waarschuwing geretourneerd als dit het geval was. Deze wijziging heeft geen invloed op de datawarehousecontrole op productcompatibiliteit voor segmenten. |
| Wijzigen in hoe [!UICONTROL items/uitgangen] worden berekend in [!UICONTROL werkruimte] | dinsdag 7 april 2020 | In [!UICONTROL Analysis Workspace], as of March 2020, we have changed how the _None_ value interacts with [!UICONTROL Entries/Exits]. Because you can now turn _Nones_ on and off in [!UICONTROL Analysis Workspace], we apply the _None_ value after the entry or exit, whereas (for eVars) it used to be applied before. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor Vars, maar de tweede hit wel. In [!UICONTROL Reports &amp; Analytics] it will show up as _Unspecified_ for the Entry, but in [!UICONTROL Analysis Workspace] it will show up as the value on the second hit. |
| EOL van instelling voor **[!UICONTROL conversieniveau]** | dinsdag 3 maart 2020 | De instelling Niet-functionerend [conversieniveau](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** wordt op 12 maart 2020 verwijderd uit de interface. |
| EOL van **[!UICONTROL dashboardarchief]** | vrijdag 27 maart 2020 | De instelling **[!UICONTROL Archief]** weergeven onder **[!UICONTROL Dashboards]** beheren in [!UICONTROL Reports &amp; Analytics] is niet meer beschikbaar vanaf oktober 2020. |
| Einde van ondersteuning voor TLS 1.1 | donderdag 3 oktober 2019 | Op 31 maart 2020 verwijdert Adobe Analytics de ondersteuning voor TLS 1.1. Deze wijziging is een onderdeel van onze voortdurende inspanningen om de hoogste veiligheidsnormen te handhaven en de veiligheid van klantdata te bevorderen. |
| Nieuw Adobe Analytics-domein | 18 dec. 2019 | Op 16 januari 2020 is Adobe Analytics begonnen met de verhuizing naar een nieuw domein - `https://experience.adobe.com/analytics.`<br>**Opmerking:** Deze wijziging geldt voor alle gebruikers die met hun Adobe ID of Enterprise ID toegang hebben tot Analytics.<ul><li>De domeinwijziging kan tijdens het laden van Analytics in Safari problemen met cookies veroorzaken. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Analytics in dit nieuwe Adobe Experience Cloud-domein functioneren. U kunt zonder problemen andere browsers gebruiken, omdat dit alleen voor [!DNL Safari]-gebruikers geldt.</li><li>The domain change may cause [!UICONTROL Activity Map] to stop working for some customers [in specific cases](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Einde van levensduur - Verouderde Analytics-API&#39;s | donderdag 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

### [!DNL AppMeasurement] {#appm}

Zie [AppMeasurement voor Javascript-releaseopmerkingen](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Versie 2.20.0 is uitgebracht op 5 maart 2020.

### Nieuwe tutorials voor Analytics {#tutorials-analytics}

| Inhoud | Beschrijving |
| -----------| ---------- |
| [Adobe Labs (technologische voorvertoningen) met Adobe Analytics](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/analytics-basics/adobe-labs-technology-previews.html) | Met Adobe Labs (technologische voorvertoningen) kunt u kennismaken met opkomende technologieën, waardevolle inzichten ontdekken en de ontwikkeling en prioriteiten van toekomstige [!DNL Analytics]-functies beïnvloeden. |
| [Verbeterde Experience Cloud Audience Publishing](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/integrations/experience-cloud/improved-experience-cloud-audience-publishing.html) | Er zijn verbeteringen aangebracht in de [!UICONTROL Cloud Audience Publishing]. U kunt nu doelgroepen (segmenten) publiceren en deze zes keer zo snel beschikbaar maken. Dit verkort de huidige latentietijd van 48 uur tot ongeveer 8 uur, en mogelijk nog sneller, afhankelijk van het verkeer en de segmentgrootte. |
| [Meerdere rapportsuites in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/using-panels/multiple-report-suites-in-analysis-workspace.html) | Multiple report suites can be analyzed in a single [!UICONTROL Workspace] project by selecting report suites at the panel level. Op deze manier kunt u een analyse van vensters naast elkaar uitvoeren voor verschillende datasets. |

Raadpleeg de [Adobe Analytics Help-startpagina](https://docs.adobe.com/content/help/en/analytics/landing/home.html) voor productdocumentatie.

## ![Pictogram](/assets/audience-manager.png) Audience Manager {#aam}

Nieuwe functies en oplossingen in Adobe Audience Manager:

| Functie | Beschrijving |
| -----------| ---------- |  
| [Voorspelend publiek](../features/algorithmic-models/predictive-audiences.md) | [!UICONTROL Met voorspellende doelgroepen] kunt u een onbekend publiek in real-time indelen in verschillende personen met behulp van geavanceerde technieken voor gegevenswetenschap. <br><br> In een marketingcontext is een persoon een publiekssegment dat wordt gedefinieerd door bezoekers, gebruikers of potentiële kopers en dat een specifieke reeks kenmerken deelt, zoals demografie, bruisende gewoonten, winkelgeschiedenis, enz.<br><br>[!UICONTROL De voorspellende modellen van het publiek] nemen dit concept een stap verder, door u toe te laten om de machine van de Manager van het Publiek te gebruiken om onbekend publiek in verschillende karakters te classificeren. <br><br>De Manager van de Publiek helpt u dit bereiken door de neiging van uw onbekend eerderepubliek voor een reeks bekende eerste-partijpubliek te berekenen. |
| Verbeteringen in aanvullende [!UICONTROL regels] voor het samenvoegen van profielen | [!UICONTROL De Regels] van de Fusie van het profiel geven de klanten van de Manager van de Publiek de capaciteit om, publiekssegmenten te bepalen te beheren en te activeren die op identiteit eerder dan apparaten worden gebaseerd. <br><br> Vanaf 29 april, zullen de klanten van de Manager van de Publiek de uitsplitsing van apparaat en dwars-apparaat bevolkingen van identiteitskaart voor eigenschap en segmenten binnen zowel individuele segmentatie als bulkrapportering in de UI van de Manager van de Publiek beter kunnen begrijpen. <br><br> Dit zal voor betere inzichten in identiteit binnen de Manager van het Publiek toestaan, die klanten een holistische mening over totale segmentbevolking door apparaat, persoon, en huishouden geven. De bulkexport van zowel apparaat- als apparaat-id&#39;s wordt ook bijgewerkt met deze verbeteringen.<br><br>  Specifieke updates omvatten de mogelijkheid om: <ul><li>rapporteren tegen [apparaat-id&#39;s](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) in de rapporten [Algemeen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/general-reports.html) en [Trend](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reporting/trend-reports.html) ;</li><li>Verbeter de [!UICONTROL Trait Selector] in de [Segment Builder](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/segments/segment-builder.html) om de populaties van trekvogels die van [CRM-id&#39;s](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html)zijn afgesneden, op te nemen;</li><li>Nauwkeurige export van [apparaatoverschrijdende id&#39;s](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html)maken;</li><li>Nauwkeurige export van [apparaat-id&#39;s](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) maken (moet geverifieerde kenmerken uitsluiten);</li><li>Retourneer correcte aantallen voor kenmerken verbonden aan [CRM IDs](https://docs.adobe.com/content/help/en/audience-manager/user-guide/reference/ids-in-aam.html) wanneer gevraagd gebruikend het hulpmiddel [BAAAM](https://docs.adobe.com/help/en/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html) .</li></ul> |
| [Belangrijkste problemen met klantenondersteuning](https://docs.adobe.com/content/help/en/audience-manager/user-guide/top-support-issues/support-issues-overview.html) | We hebben een nieuwe sectie toegevoegd aan onze documentatieportal, die antwoorden bevat op de meest gestelde vragen die ons team voor klantenondersteuning ontvangt. |

* Er is een probleem verholpen dat onjuiste rapportage veroorzaakte van [adresseerbare doelgroepen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html) voor segmenten die id&#39;s voor mobiele apparaten bevatten. Na deze update ziet u mogelijk een toename in uw [adresseerbare doelgroepen](https://docs.adobe.com/content/help/en/audience-manager/user-guide/features/addressable-audiences.html).
* Probleem verholpen waarbij de knoppen [!UICONTROL Testen] dupliceren en Toewijzingssjabloon [!UICONTROL dupliceren in] Audience Lab  niet werkten. (AAM-53388)
* Fixed an issue causing the [!UICONTROL Match Rate] and [!UICONTROL Segment Addressable Audiences] to be displayed as 0 when a destination is configured to export UUIDs. Het [!UICONTROL Tarief] van de Gelijke en [!UICONTROL Doelpubliek] van het Segment worden nu getoond als 100%. (AAM-51615)
* Er is een probleem verholpen waardoor namen van kenmerken die speciale tekens bevatten, tweemaal met HTML werden gecodeerd. (AAM-54001)
* Er is een probleem verholpen waardoor bepaalde gebruikers vanuit de [!DNL Audience Manager] gebruikersinterface niet konden overschakelen naar andere Adobe Experience Cloud-applicaties. (AAM-52917)
* Er is een probleem verholpen waardoor sommige gebruikers geen SHA256-databron konden maken voor op personen gebaseerde bestemmingen. (AAM-53525)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-48986, AAM-49009, AAM-48984, AAM-48939, AAM-48940, AAM-48964, AAM-49032, AAM-49360)

## ![Pictogram](/assets/aem.png) Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### Zelfondersteuning

* **AEM-nieuwsbrief**

   Zie de nieuwste [Adobe Experience Manager-nieuwsbrief](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html).

* **AEM als Cloud Service - Dynamic Media Cloud Service configureren**

   Er is een nieuwe optie beschikbaar wanneer u Dynamic Media Cloud Service configureert:

   **Selectieve publicatie** - Wanneer u deze optie selecteert, betekent dit dat assets automatisch worden gepubliceerd voor uitsluitend beveiligde voorvertoning en expliciet kunnen worden gepubliceerd naar AEM zonder dat ze naar DMS7 worden gepubliceerd voor aflevering in het publieke domein.

   Zie [Configuring Dynamic Media Cloud Service configureren](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/config-dm.html#configuring-dynamic-media-cloud-services).

* **Dynamic Media - Slimme beeldbewerking**

   Het volledige Help-onderwerp voor Slimme beeldbewerking is bijgewerkt met nieuwe informatie, waaronder voorbeelden van afbeeldingsassets die de toegevoegde Slimme beeldbewerking laten zien.

   Zie [Slimme beeldbewerking](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/imaging-faq.html).

* **Dynamic Media configureren - modus Scene7**

   A new Sync all content option is now available on the Dynamic Media Configuration page found in **[!UICONTROL Tools > Cloud Services]**.

   Zie [Een Dynamic Media-configuratie maken](https://docs.adobe.com/content/help/en/experience-manager-65/assets/dynamic/config-dms7.html#configuring-dynamic-media-cloud-services).

* **AEM Assets Brand Portal ondersteunt AEM Assets als Cloud Service**

   U kunt nu assets van AEM Assets als Cloud Service naar AEM Assets Brand Portal publiceren.

   Zie [AEM Assets met Brand Portal configureren](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/configure-aem-assets-with-brand-portal.html) en [Assets naar Brand Portal publiceren](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/brand-portal/publish-to-brand-portal.html).

* **Adobe Asset Link 2.0 uitgebracht**

   Adobe Asset Link 2.0 ondersteunt het werken met meerdere AEM-omgevingen en ondersteunt AEM als Cloud Service. AEM ondersteunt de behoefte van marketeers om automatische uitvoering van assetverwerkende workflows te configureren wanneer assets worden geüpload naar een map met behulp van Adobe Asset Link.

   Zie [Adobe Asset Link](https://helpx.adobe.com/nl/enterprise/using/adobe-asset-link.html).

### Nieuwe tutorials voor Experience Manager

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Local Dispatcher-tools instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/dispatcher-tools.html) | Learn about facilitating configuring, validating, and simulating [!UICONTROL Dispatcher] locally. |
| [Ontwikkeltools voor AEM Projects instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/development-tools.html) | Voor de ontwikkeling van Adobe Experience Manager (AEM) moet een minimale set ontwikkeltools worden geïnstalleerd en ingesteld op de ontwikkelcomputer. Deze tools ondersteunen de ontwikkeling en de opzet van AEM-projecten. |
| [Lokale AEM-runtime instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) can be run locally using the AEM as a Cloud Service SDK&#39;s [!UICONTROL QuickStart Jar]. Hierdoor kunnen ontwikkelaars aangepaste code, configuratie en content te implementeren en te testen voordat deze in bronbeheer worden doorgevoerd, en deze te implementeren in een AEM als Cloud Service-omgeving. |
| [Navigatie](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/authoring/navigation.html) | Verken de basisbeginselen voor navigatie van AEM Assets. |
| [Versies](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/collaboration/versions.html) | Ontdek hoe AEM assetversies maakt en onderhoudt. |
| [AEM - [!DNL Magento] Integratie die het Kader van de Integratie van de [!UICONTROL Handel gebruikt]](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/getting-started.html) | In deze video ziet u de instelling van de integratie tussen AEM en [!DNL Magento] wordt uitgevoerd. |
| [Inleiding tot de AEM Architecture Stack](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-architecture.html) | Het CIF Project-archetype maakt een minimaal Adobe Experience Manager (AEM) CIF-project als beginpunt voor klantprojecten die gebruikmaken van CIF Core Components. |
| [Inleiding tot OSGi](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-osgi.html) | Een inleiding tot OSGi, een dynamische modulaire architectuur voor Java-applicaties die de basis vormt voor Adobe Experience Manager. |
| [Inleiding tot de Java Content Repository (JCR)](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-jcr.html) | Een inleiding tot de [JCR (Java Content Repository) die door Adobe Experience Manager wordt gebruikt. |
| [Inleiding tot Sling](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-sling.html) | Een inleiding tot [!DNL Sling], een opensource RESTful-webframework dat deel uitmaakt van de onderliggende technologiestack van Adobe Experience Manager. |
| [Inleiding tot Author en Publish Tier](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-author-publish.html) | An introduction to the [!UICONTROL Author] and [!UICONTROL Publish] tiers as part of the architecture in Adobe Experience Manager. |
| [Inleiding tot Dispatcher](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/underlying-technology/introduction-dispatcher.html) | Een inleiding tot de mogelijkheden en de functies van de Dispatcher als deel van de AEM-architectuur. |
| [Inleiding tot Component Development](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/component-development.html) | Een overzicht van het ontwikkelen van componenten met Adobe Experience Manager Sites. Omvat een inleiding aan [!UICONTROL Dialogen], [!UICONTROL het Verdelen Modellen], [!UICONTROL Manuscripten]HTML, en [!UICONTROL cliënt-zijBibliotheken]. |
| [AEM Project-archetype](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/developing/aem-project-archetype.html) | Het AEM-project bevat alle code en configuraties voor een implementatie. The AEM [!UICONTROL Project Archetype] creates a minimal, best-practices-based Adobe Experience Manager project as a starting point for your own AEM projects. |
| [Inzicht in Core Components](https://docs.adobe.com/content/help/en/experience-manager-learn/sites/components/core-components-feature-video-understand.html) | AEM [!UICONTROL Core Components] are a standard set components to be used with Adobe Experience Manager. |
| [AEM QuickStart Jar gebruiken](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/developing/quickstart-jar.html) | Learn how to install and run a local instance of Adobe Experience Manager in just a few minutes with the [!UICONTROL AEM Quickstart jar]. |

### Aanvullende Help-bronnen

* [AEM as a Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [AEM 6.4 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [AEM 6.3 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [AEM 6.2 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Releaseopmerkingen bij Dynamic Media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Releaseopmerkingen bij Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Campaign Standard

* [Adobe Campaign Standard 20.2](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html)

### Nieuwe tutorials voor Campaign Standard {#tutorials-acs}

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Profielsubstitutie - E-mailberichten testen met behulp van specifieke profielen](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/communication-channels/email/profile-substitution.html) | Test uw e-mailberichten met de functie voor profielsubstitutie. |

### Aanvullende Help-bronnen voor Campaign

* Adobe Campaign Standard: [Documentatie](https://helpx.adobe.com/nl/support/campaign/standard.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) - [Instructievideo&#39;s](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) - [Releaseplanning](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentatie](https://helpx.adobe.com/nl/support/campaign/classic.html) - [Releaseopmerkingen](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Instructievideo&#39;s](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

<!-- ## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Advertising Cloud release notes. -->

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Voor de versienota&#39;s van Magento raadpleegt u:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] is een volledige applicatie voor leadmanagement en B2B-marketeers die klantervaringen willen transformeren door betrokkenheid in elke fase van complexe kooptrajecten.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo] [releaseopmerkingen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) voor meer informatie.

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
