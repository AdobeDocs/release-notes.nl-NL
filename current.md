---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Sjabloon voor releaseopmerkingen bij Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: be2f2b5ad468ad63bfcb2fdd67d063203ac08654
workflow-type: tm+mt
source-wordcount: '4919'
ht-degree: 79%

---


# Adobe Experience Cloud-releaseopmerkingen - mei 2020

![Banner](/assets/experience-cloud-banner-3.png)

Deze pagina bevat nieuwe functies, correcties en belangrijke kennisgevingen in [!DNL Adobe Experience Cloud]. De releasedatums van de oplossing kunnen variëren. Controleer regelmatig op de nieuwste updates.

>[!NOTE]
>
>Meld u aan voor de [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases.

**Releasedatum: mei 2020**

Laatste update: **4 juni 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Bijgewerkt op 4 juni 2020**)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/nl-NL/target/using/release-notes/target-release-notes.html) (koppelingen naar de Help-pagina van Target)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/nl/primetime/user-guide.html) (koppelingen naar de Help-pagina van Primetime)

Hulp nodig? Ga naar [[!DNL Adobe Experience League]](https://experienceleague.adobe.com/#home) voor door Adobe geselecteerde cursussen, technische documentatie, snelle antwoorden, inzicht in de community en training onder leiding van instructeurs.

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Releasedatum: **21 mei 2020**

**Wat is er nieuw**

* Met uw Adobe ID kunt u lid worden van gebeurtenismeldingen met meer granulariteit, tot aan het aanbod van producten en invoegtoepassingen. Om u te helpen uw lidmaatschap sneller in te stellen wordt nu tijdens het proces voor zelfinschrijving een selectie van producten en aanbiedingen geadviseerd op basis van uw productrechten. Zo verkleint u het aantal e-mailberichten dat u ontvangt en krijgt u meer relevante meldingen in uw Postvak IN. Ga aan de slag op [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nieuwe en verbeterde functies die nu beschikbaar zijn**

| Functie | Beschrijving |
| -----------| ---------- |
| Verbeterde gebruikerservaring voor lidmaatschap en meldingen | <ul><li>[!DNL Marketo Engage] regionale locaties worden nu gefilterd op basis van de geselecteerde lijst met productaanbiedingen.</li><li>[!DNL Marketo Engage] e-mailmeldingen zijn relevant voor de regio, locatie en omgevingsvoorkeuren van de gebruiker.</li></ul> |
| Bevestiging van gebeurtenislidmaatschap | <ul><li>U kunt nu een e-mailbevestiging krijgen wanneer u een lidmaatschap hebt voor lopende updates van één gebeurtenis.</li></ul> |
| Verbeteringen van de algemene navigatiebruikbaarheid | <ul><li>Consistente gebruikerservaring met `Adobe.com` in het hoogste navigatiemenu.</li></ul> |

## ![Pictogram](/assets/ec_appicon_24.png) Experience Cloud-interface {#ecloud}

Algemene updates van de Experience Cloud-interface.

**Geïntegreerd productdomein**

Adobe heeft een update uitgevoerd van de domein- en interfaceheader om uw ervaring in alle Experience Cloud-applicaties te integreren en te verbeteren. Deze verbeteringen zijn ontworpen om uw ervaring op kleine maar belangrijke manieren te vereenvoudigen. Deze verbeteringen hebben geen invloed op uw huidige workflows.

Updates zijn:

* Nieuwe applicatie-URL&#39;s: `experience.adobe.com/<application name>`:
   * Uiteindelijk zal dit URL-patroon voor alle producten gelden. Kijk uit naar nieuwe URL&#39;s die gedurende deze maand van kracht worden.
   * Browserondersteuning: Tot de ondersteunde browsers behoren [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] en [!DNL Opera] (de nieuwste versies). **Opmerking:** Hoewel de Experience Cloud-interface deze browsers ondersteunt, wordt mogelijk niet elke browser door afzonderlijke applicaties ondersteund. ([Analytics](https://docs.adobe.com/content/help/nl-NL/analytics/admin/sys-reqs.html) biedt bijvoorbeeld geen ondersteuning voor [!DNL Opera] en [Target](https://docs.adobe.com/help/nl-NL/target/using/implement-target/before-implement/supported-browsers.html) biedt geen ondersteuning voor [!DNL Safari].)
   * (Alleen [!DNL Safari]) De domeinwijziging kan problemen met cookies veroorzaken in [!DNL Safari]. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Experience Cloud in dit nieuwe domein functioneren.
* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde producthulp: [!UICONTROL Experience League] is geïntegreerd in het product, zodat een zoekopdracht in de Help ook resultaten bevat van gemeenschapsforums en video-content. Deze wijziging vereenvoudigt de toegang tot meer content en helpt u optimaal te profiteren van Experience Cloud. Klik daarnaast op **[!UICONTROL Help]** > **[!UICONTROL Feedback]** om problemen te melden of uw ideeën te delen met Adobe.

De volgende applicaties gebruiken het nieuwe domein experience.adobe.com:

| App of service | Domein |
| -----------| ---------- |
| Startpagina van Experience Cloud | `experience.adobe.com/home` |
| Adobe Target | `experience.adobe.com/target` |
| Adobe Audience Manager | `experience.adobe.com/audience-manager` |
| Adobe Launch | `experience.adobe.com/launch` |
| Adobe Experience Platform | `experience.adobe.com/platform` |
| Klanttraject beheren | `experience.adobe.com/journeys` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign-besturingsdeelvenster | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places-service | `experience.adobe.com/places` |
| Softwaredistributie | `experience.adobe.com/downloads` |
| Admin-tool (bèta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board & Collections]**, een verouderd filter in de [!UICONTROL Marketing Cloud Assets]-kiezer, wordt uitgeschakeld.

## ![Pictogram](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Releaseopmerkingen voor de [!DNL Experience Platform,] inclusief [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] en beveiligingsbulletins.

### Interfaceverbeteringen

Bijgewerkt: **15 mei 2020**

[!DNL Adobe Experience Platform] brengt updates uit van het domein en de headerbalk vrij om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-applicaties. Updates zijn:

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikershulp, inclusief aanbevolen artikelen en contextrelevante documentatie in het menu Help.
* Mogelijkheid om feedback te geven over het Experience Platform en tickets te maken voor bestandsondersteuning.

Zie [Releaseopmerkingen bij Experience Platform](https://docs.adobe.com/content/help/nl-NL/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md) voor meer informatie.

### Klantkenmerken - nieuwe documentatie

Bijgewerkt: **15 mei 2020**

* [Ondersteuning van klantkenmerken voor CCPA](https://docs.adobe.com/content/help/nl-NL/core-services/interface/customer-attributes/ccpa.html) (California Consumer Privacy Act)
* [Ondersteuning van klantkenmerken voor GDPR](https://docs.adobe.com/content/help/nl-NL/core-services/interface/customer-attributes/gdpr.html) (General Data Protection Regulation)

### Journey Orchestration {#journey}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

* [Documentatie](https://docs.adobe.com/content/help/nl-NL/journeys/using/journey-orchestration-home.html)
* [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html)
* [Instructievideo&#39;s](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Aanvullende releasedata bij Experience Platform

* [Releaseopmerkingen bij Experience Platform Launch](https://docs.adobe.com/content/help/nl-NL/launch/using/intro/release-notes/current.html).
* [Releaseopmerkingen bij Experience Platform](https://docs.adobe.com/content/help/nl-NL/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md)
* [Beveiligingsbulletins en adviezen](https://helpx.adobe.com/nl/security.html) (Alle Adobe-producten)

## ![Pictogram](/assets/analytics.png) [!DNL Analytics] {#analytics}

Updated **June, 2020**

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Nieuwe functies in Media Analytics](#media-aa)
* [Adobe Analytics-oplossingen](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)
* [AppMeasurement](#appm)
* [Nieuwe tutorials voor Analytics](#tutorials-analytics)

### Nieuwe functies in Adobe Analytics {#aa-features}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html)- Doeldatum | Beschrijving |
| -----------| ---------- |-------|
| Attributie-IQ: Algorithmic Attribution | 18 juni 2020 | Het [!UICONTROL Algorithmic Attribution] model in de Werkruimte van de Analyse gebruikt statistische technieken om de optimale toewijzing van krediet voor geselecteerde metrisch dynamisch te bepalen. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attributie-IQ: Aangepaste terugzoekvensters | 18 juni 2020 | U kunt nu elk toewijzingsmodel configureren in [!UICONTROL Attribution IQ] om aanraakpunten op te nemen van maximaal 90 dagen vóór de rapportperiode. Dit zal de toewijzingsnauwkeurigheid voor gebeurtenissen die zich vroegtijdig in de verslagperiode voordoen, doorgaans verhogen door de verwerking van interacties die in de voorafgaande maand(en) hebben plaatsgevonden. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Projectrollen voor gedeelde werkruimteprojecten | 18 juni 2020 | Wanneer het delen van een project van de Werkruimte, kunt u ontvangers in één van drie projectrollen nu plaatsen, afhankelijk van de projectervaring u hen wilt hebben: Bewerken, dupliceren en weergeven. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Alleen-weergeven werkruimteprojecten | 18 juni 2020 | Werkruimteprojecten kunnen aan gebruikers worden gedeeld als &quot;Alleen kan bekijken&quot;. Wanneer een ontvanger van de Mening het gedeelde project opent, ontvangen zij een meer restrictieve projectervaring, zonder linkerspoorstaaf en beperkte interactie. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Mogelijkheid om werkruimteprojecten samen te bewerken | 18 juni 2020 | Ontvangers die aan de rol &quot;Kan uitgeven&quot;worden toegevoegd kunnen over een project bewaren dat aan hen is gedeeld. Dit geldt zowel voor beheerders als niet-beheerders. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Bijgewerkt leeg deelvenster in werkruimte | 18 juni 2020 | Het lege deelvenster in Workspace bevat nu deelvensters en visualisaties, zodat u een naadloze manier hebt om de analyseworkflow te kiezen die het beste voor u werkt. |
| Eerste-partijdomeinen beschikbaar in China RDC | 18 juni 2020 | Laat klanten met een `.cn` domein toe om een 1st-partijdomein voor gebruik binnen het Chinese vasteland aan te vragen. (Documentatie beschikbaar bij de aankoop van SKU &quot;China Performance Optimization&quot;.) |
| Deelvenster Snelle inzichten in werkruimte | 25 juni 2020 | De snelle Inzichten verstrekken begeleiding voor niet-analisten en nieuwe gebruikers van de Werkruimte van de Analyse om te leren hoe te om bedrijfsvragen snel en gemakkelijk te beantwoorden. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Analyses voor venster Doel in werkruimte | 25 juni 2020 | Met het deelvenster Analyse voor doel (A4T) kunt u uw Adobe Target-activiteiten en -ervaringen analyseren in de analysewerkruimte. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html)- Doeldatum | Beschrijving |
| -----------| ---------- |-----|
| Ondersteuning voor Anomaly Detection | 18 juni 2020 | Anomaly Detection biedt een statistische methode om te bepalen hoe een bepaalde metrische waarde is gewijzigd ten opzichte van eerdere gegevens. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Projectrollen voor gedeelde werkruimteprojecten | 18 juni 2020 | Wanneer het delen van een project van de Werkruimte, kunt u ontvangers in één van drie projectrollen nu plaatsen, afhankelijk van de projectervaring u hen wilt hebben: Bewerken, dupliceren en weergeven. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Alleen-weergeven werkruimteprojecten | 18 juni 2020 | Werkruimteprojecten kunnen aan gebruikers worden gedeeld als &quot;Alleen kan bekijken&quot;. Wanneer een ontvanger van de Mening het gedeelde project opent, ontvangen zij een meer restrictieve projectervaring, zonder linkerspoorstaaf en beperkte interactie. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Mogelijkheid om werkruimteprojecten samen te bewerken | 18 juni 2020 | Ontvangers die aan de rol &quot;Kan uitgeven&quot;worden toegevoegd kunnen over een project bewaren dat aan hen is gedeeld. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |

### Nieuwe functies in [!UICONTROL Media Analytics] {#media-aa}

Datum bijgewerkt: **29 mei 2020**

**Volgen van Player-status:** [!UICONTROL Media Analytics] klanten kunnen tijdens het afspelen viewerinteracties vastleggen met een standaardset oplossingsvariabelen voor volledig scherm, ondertiteling, dempen, beeld-in-beeld en scherpstelling. U kunt desgewenst ook aangepaste Player-statussen te maken. Variabelen voor het bijhouden van Player-statussen kunnen nu worden gerapporteerd in [!UICONTROL Analysis Workspace]. Voor deze functie is een van de volgende opties vereist:

* Media [!DNL JavaScript] SDK 3.0 of hoger
* Voor gebruik met de [!DNL Adobe Experience Platform] (AEP) SDK:
   * [!UICONTROL Media Analytics Extension] (voor web): [!UICONTROL Adobe Media Analytics] (3.x SDK) voor Audio &amp; Video v1.0 of hoger
   * [!UICONTROL Media Analytics Extension] (voor mobiele apparaten): [!UICONTROL Adobe Media Analytics for Audio] en Video v2.0 of hoger
* [!UICONTROL Media Collection]

Zie [Informatie over het bijhouden van Player-status](https://docs.adobe.com/content/help/nl-NL/media-analytics/using/player-state-tracking/player-state-overview.html).

### Adobe Analytics Fixes {#aa-fixes}

* Probleem verholpen waarbij segmenten met multibyte-zoekopdrachten naar bepaalde rapportsuites niets raakten. Ze komen nu overeen met de juiste tekenreeksen. AN-220043
* Correctie van een probleem met het itemfilter in Rapporten en Analyse werkt niet. AN-206132
* Oplossing voor een langzame reactietijd in de gebruikersinterface voor geplande projecten. AN-214837
* Probleem verholpen met het genereren van een fout in het datumbereik via Analytics Reporting API 2.0. AN-215087
* Probleem verholpen waarbij de instantie/het bezoek/de bezoeker niet in de noemer voor de tijdsperiodes werd geteld. Dit gebeurt wanneer een hit zonder waarde voor de dimensie (bijvoorbeeld Pagename) in dezelfde seconde wordt gevolgd. AN-211074
* Probleem verholpen waarbij gebruikers geen toegang kregen tot werkruimteprojecten die met hen werden gedeeld. AN-217561
* Correctie van probleem waarbij keys niet werden geclassificeerd door Classification Rule Builder. AN-221538
* Probleem verholpen waarbij het gebruik van de serveroproep geen gebruiksgegevens rapporteerde. AN-210452
* Problemen verholpen waarbij in AAM gegevens ontbraken in gepubliceerde segmenten van Adobe Analytics. AN-220208, AN-220659
* Probleem verholpen met rapporten waarin gegevens werden weergegeven, maar logboeken met gegevensinvoer waarin stond &quot;Geen gegevens in een opslagplaats&quot;. AN-220784, AN-220858
* Correctie van problemen waardoor ad-hocanalyse niet op het `experiencecloud.com` domein kon worden gestart. AN-219680, AN-221629
* Correctie van problemen met de hotkey &quot;Ctrl (of Command) + C&quot;. AN-221101, AN-221537
* Probleem verholpen met de actiepagina Activiteitenkaart. AN-222029, AN-221242
* Probleem verholpen waarbij het niet mogelijk was een aanraakpunt toe te voegen midden in een uitvalvisualisatie. AN-221648

#### Nog meer oplossingen in Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| Migratie naar uniform productdomein | Ingangsdatum: 28 mei 2020 | De migratie naar een uniform productdomein voor Adobe Analytics dat in januari 2020 is gestart, is op 28 mei 2020 voltooid. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Wanneer de volledige architectuurmigratie (binnenkort) is voltooid, stellen we u via de releaseopmerkingen op de hoogte en is deze whitelist-stap niet meer nodig. [Hier](https://helpx.adobe.com/nl/analytics/kb/adobe-ip-addresses.html) is een volledige lijst van geadviseerde IP adressen en domeinen die u zou moeten toestaan.<br>Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen. |
Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen.
|Nieuwe standaardlandingspagina voor Adobe Analytics|Ingangsdatum: 18 juni 2020|Op 18 juni 2020 verandert de standaard bestemmingspagina voor Adobe Analytics van Rapporten in Workspace. Deze wijziging vindt plaats voor alle gebruikers die nog geen aangepaste landingspagina hebben ingesteld.|
|Technologie van derden is toegestaan|12 maart 2020 (effectieve datum)|Adobe Analytics is begonnen met het benutten van technologieën van derden voor het beheer van de rollout van functies en ondersteuning in producten. De volgende URL&#39;s moeten worden toegevoegd aan alle benodigde netwerkfirewallallowlists om volledige toegang tot functies te garanderen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul>|
|Verbeterde overtolligheid voor de beschikbaarheid van de Werkruimte van de Analyse|21 mei, 2020|Om beschikbaarheid van de Werkruimte van de Analyse te verzekeren, voegen wij een secundaire CDN (het Netwerk van de Levering van de Inhoud) voor betere overtolligheid toe. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste whitelists voor de netwerkfirewall:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul>|
|Verandering in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace]|7 april 2020|In [!UICONTROL Analysis Workspace]maart 2020 hebben we de wisselwerking tussen de waarde _Geen_ en [!UICONTROL Entries/Exits]. Omdat u _Geen_ nu kunt in- en uitschakelen in [!UICONTROL Analysis Workspace], gebruiken we de waarde _Geen_ na openen en afsluiten, waar dit (voor eVars) vroeger werd toegepast vóór openen en afsluiten. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor eVars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] verschijnt de eerste hit als _Niet gespecificeerd_ voor de vermelding, maar in [!UICONTROL Analysis Workspace] verschijnt dit als de waarde voor de tweede hit.|
|EOL of **[!UICONTROL Dashboard Archive]**|March 27, 2020|The **[!UICONTROL View Archive]** setting under **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] will no longer be available as of October, 2020.|
|End of Life - Analytics Legacy APIs|9 januari 2020|In november 2020 zullen de volgende Analytics Legacy API services hun einde van de levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0.|
|San Jose FTP Broker Ending for London and Singapore|Juli 2020|Voor klanten in Londen en Singapore zullen we niet langer tussenhandel in gegevens tussen Londen of Singapore en het San Jose-datacenter [ftp.omniture.com](ftp://ftp.omniture.com/)ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul>|
|EOL van Ad Hoc Analysis|6 aug, 2018|Adobe kondigde aan dat het de bedoeling was om Ad Hoc Analysis te beëindigen. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/).|

### [!DNL AppMeasurement] {#appm}

Zie [AppMeasurement voor Javascript-releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/analytics/implementation/appmeasurement-updates.html). Versie 2.20.0 is uitgebracht op 5 maart 2020.

### Nieuwe tutorials voor Analytics {#tutorials-analytics}

| Inhoud | Beschrijving |
| -----------| ---------- |
| [Trainingstutorialsjabloon in Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/navigating-workspace-projects/training-tutorial-template-in-analysis-workspace.html) | In de [!UICONTROL Analysis Workspace] Trainingstutorials doorloopt u de gebruikelijke terminologie en stappen voor het opzetten van uw eerste project in [!UICONTROL Workspace]. |
| [Vergelijkingen van voorafgaande maanden en jaar toevoegen aan trends](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/calendar-and-date-ranges/adding-prior-month-and-year-comparisons-to-trends.html) | Leer hoe u aangepaste datumbereiken toepast om maandelijkse en jaarlijkse trendvergelijkingen te maken voor alle cijfers in [!UICONTROL Analysis Workspace]. |
| [Uitbreiding Donkere modus voor Analysis Workspace](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/dark-mode-extension-for-analysis-workspace.html) | Schakel de Reader Chrome-uitbreiding Donker in om Analysis Workspace donker te maken. |
| [Kleurenpipetextensie voor het definiëren van aangepaste paletten](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/customizing-the-ui/color-eyedropper-extension-for-defining-custom-palettes.html) | Leer hoe u de Chrome-extensie ColorPick EyeDropper Chrome gebruikt om eenvoudig de hexadecimale waarden te vinden die u nodig hebt voor een aangepast kleurenpalet in uw [!UICONTROL Workspace]-projecten. |

#### Bronnen voor Analytics Help

* [Adobe Analytics-tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-productdocumentatie](https://docs.adobe.com/content/help/nl-NL/analytics/landing/home.html)

## ![Pictogram](/assets/audience-manager.png) Audience Manager {#aam}

Nieuwe functies, correcties, documentatie en tutorials in Audience Manager.

### Gebruikersinterface-updates

Audience Manager brengt updates uit van het domein en de headerbalk om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-applicaties.

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikers-Help, inclusief aanbevolen artikelen en contextrelevante video&#39;s in het menu Help.
* Mogelijkheid om feedback te geven over het Experience Platform en tickets te maken voor bestandsondersteuning.
* Een nieuw, eenvoudiger URL-patroon. Werk uw bladwijzers bij naar de nieuwe URL: `experience.adobe.com/audience-manager`.

Deze updates zijn alleen beschikbaar voor gebruikers die zich aanmelden met Adobe ID. Raadpleeg [Experience Cloud-gebruikers en -producten beheren](https://docs.adobe.com/content/help/nl-NL/core-services/interface/manage-users-and-products/admin-getting-started.html) om naar een Adobe ID-aanmelding over te schakelen.

### Nieuwe functies en oplossingen in Adobe Audience Manager

| Functie | Beschrijving |
| -----------| ---------- |  
| [Bulkbeheertools (BAAAM)](https://docs.adobe.com/content/help/nl-NL/audience-manager/user-guide/reference/bulk-management-tools/bulk-management-intro.html#download) | We hebben een nieuw werkblad met bulkbeheertools geüpload: <br><br><ul><li>Hiermee kunt u de submappen in de hiërarchie van het kenmerk weergeven (AAM-51528)</li><li>Hiermee kunt u desgewenst cijfers terugzetten voor kenmerken die horen bij CRM-id&#39;s (cross-device-id&#39;s) (AAM-52135)</li><li>Lost een taalcoderingsprobleem op voor Koreaanse tekens (AAM-AAM-54006)</li></ul> |

**Oplossingen**

* Er is een probleem opgelost waardoor trendrapporten een time-out kregen bij mappen met een groot aantal kenmerken. (AAM-54457)
* Er is een probleem opgelost waardoor klanten de [!UICONTROL Expression builder] niet konden zien in de workflow voor het maken/bewerken van kenmerken. (AAM-54255)
* Er is een probleem opgelost waardoor foutberichten in de gebruikersinterface slechts voor een korte tijd werden weergegeven en verdwenen voordat klanten de kans kregen ze te lezen. Dit gebeurde bijvoorbeeld wanneer de gebruiker probeerde een segment te verwijderen dat aan een bestemming was toegewezen. (AAM-54031)
* Er is een probleem opgelost waardoor klanten die de [!UICONTROL Audience Marketplace] niet meer gebruikten, maandelijks e-mailfacturen kregen. (AAM-54602)
* Er is een probleem opgelost waardoor klanten die op bepaalde kenmerken van andere locaties in de gebruikersinterface klikten, verbroken koppelingen te zien kregen in plaats van de kenmerken. (AAM-54768)
* Er is een probleem opgelost waardoor in de modus voor het bewerken van kenmerkexpressies, wanneer op ENTER werd gedrukt, de pagina werd vernieuwd en de kenmerkexpressie verloren ging. (AAM-54210)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-47781, AAM-49075, AAM-49360, AAM-49361, AAM-49376, AAM-50432, AAM-52550, AAM-54660).

### Nieuwe Audience Manager-tutorials {#tutorials-aam}

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Inzicht in basisterminologie en -concepten in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-basic-terms-and-concepts-in-audience-manager.html) | In deze video worden enkele basistermen en -concepten besproken waarmee u in Audience Manager aan de slag kunt, zoals signalen, kenmerken, segmenten, enzovoort. |
| [Inzicht in de datastroom in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/understanding-the-data-flow-in-audience-manager.html) | Door deze video krijgt u meer inzicht in Adobe Audience Manager door een beschrijving van de datastroom naar, door en vanuit de applicatie. |
| [Audience Manager - Overzicht van een DMP](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-overview-of-a-dmp.html) | Krijg inzicht in de belangrijkste uitdagingen voor personalisatie via verschillende kanalen en in de manier waarop Adobe Audience Manager het klanttraject aanstuurt. Ontdek ook welke datatypen in Audience Manager kunnen worden opgenomen en welke ad-tech eco-systeempartners met Audience Manager zijn geïntegreerd. |
| [Gebruiksscenario&#39;s van Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/audience-manager-use-cases.html) | In deze video identificeren we vier gemeenschappelijke gebruiksscenario&#39;s van Audience Manager, en beschrijven we de best practices voor elk scenario. |
| [Inzicht in cijfers voor verschillende apparaten in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/profile-merge/understanding-cross-device-metrics-in-audience-manager.html) | In deze video bespreken we het verschil tussen apparaatprofielen en cross-device-apparaatprofielen en laten we zien waar de getallen in de gebruikersinterface overeenkomen met deze verschillende profieltypen. |
| [Voorspelbare doelgroepen in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/understanding-predictive-audiences.html) | In deze video bespreken we wat voorspelbare doelgroepen in Audience Manager zijn, leggen we uit hoe ze werken en geven we voorbeelden van het gebruik. |
| [Configureer en rapporteer over voorspelbare doelgroepen in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/algorithmic-models/configure-and-report-on-predictive-audiences.html) | In deze video doorlopen we de configuratie van voorspelbare doelgroepen in de interface van Audience Manager. We bekijken ook de rapporten die de resultaten van het model laten zien. |

## ![Pictogram](/assets/aem.png) Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### Productupdates

* **AEM als Cloud Service**

   * Verbeteringen en correcties in assetverwerking. Het dialoogvenster voor herverwerking van assets geeft de gebruiker meer controle, maakt het mogelijk een specifiek verwerkingsprofiel te selecteren, en om te bepalen of een naverwerkingsworkflow moet worden geactiveerd.
   * Prestatieverbeteringen in de assetopname in Dynamic Media.

### Zelfondersteuning

* **Service voor automatische conversie van formulieren - versie AFC-2020.03.1**

   Er is een nieuwe optie beschikbaar wanneer u de recentste connector installeert:

   **[!UICONTROL Auto-detect logical sections]**: u kunt de optie [!UICONTROL Auto-detect logical sections] gebruiken om deelvensters op paginaniveau neer te zetten (op paginanummer gebaseerde deelvensters) en alleen logische deelvensters te maken. Hierbij worden ook de velden die niet bij een sectie met een voorafgaande logische secties horen, en de velden van een logische sectie die verspreid zijn over twee aangrenzende pagina&#39;s, samengevoegd tot één logische sectie. Als bijvoorbeeld bepaalde velden van een logische sectie aan het einde van pagina 1 staan en andere aan het begin van pagina 2, worden al deze velden samengevoegd tot één logische sectie.

* **Niet-ondersteunde afbeeldingsindelingen in Dynamic Media**

   Informatie over de subtypen van bestandsindelingen van rasterafbeeldingen die niet worden ondersteund in [!UICONTROL Dynamic Media].

   Zie [Niet-ondersteunde indelingen van rasterafbeeldingen in Dynamische media](https://docs.adobe.com/content/help/nl-NL/experience-manager-65/assets/administer/assets-formats.html#unsupported-image-formats-dynamic-media).

* **Contentfragmenten**

   Informatie over [Ondersteuning voor contentfragmenten in de HTTP-API van AEM Assets](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/assets/admin/assets-api-content-fragments.html), samen met [Contentfragmenten aanpassen en uitbreiden](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-customizing.html) en [Onderdelen in Contentfragmenten configureren voor rendering](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/implementing/configuring-and-extending/content-fragments-configuring-components-rendering.html).

* **AEM Experience League-community**

   Maak verbinding met de [AEM Experience League-community](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community): stel vragen aan mede‘leerlingen’ en AEM-experts, blader door threads en deel uw tips en expertise!

* **AEM-nieuwsbrieven**

   De AEM-nieuwsbrief van [!UICONTROL Experience League] is ontworpen om u te helpen snel aan de slag te gaan met AEM, zodat u meteen waardevolle dingen kunt doen. Hier is de recentste nieuwsbrief:

   * [Volume 30](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.30.html): Experience Manager is nu beschikbaar als cloudservice.
   * [Lid worden](https://adobeeventsonline.com/AEM/2017/NL/Optin/) van de Experience Insider Newsletter.
   * Bekijk nieuwsbriefarchieven in de sectie [AEM-bronnen](https://helpx.adobe.com/nl/support/experience-manager/6-5.html) op de pagina Informatie en ondersteuning van Adobe Experience Manager 6.5.

### Nieuwe tutorials voor Experience Manager

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Lokale AEM-runtime instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/local-development-environment-set-up/aem-runtime.html) | Adobe Experience Manager (AEM) kan lokaal worden uitgevoerd met de [!UICONTROL AEM as a Cloud Service] SDK&#39;s [!UICONTROL Quickstart Jar]. Hierdoor kunnen ontwikkelaars aangepaste code, configuratie en content implementeren en testen voordat deze in bronbeheer worden doorgevoerd, en deze implementeren in een [!UICONTROL AEM as a Cloud Service]-omgeving. |
| [Aan de slag met AEM Assets](https://video.tv.adobe.com/v/33624?captions=dut) | Een introductievideo over aan de slag gaan met AEM Assets voor zakelijke gebruikers. |
| [Schema&#39;s voor metadatamappen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-folder-schemas.html) | Met schema&#39;s voor metadatamappen kunnen gebruikers metadata die aan assetmappen zijn gekoppeld, zelf beheren en controleren in plaats van via assets. |
| [Tags](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/tagging.html) | Tags zijn een integrale tool voor het beheer van assets in de maphiërarchie van assets. Het instellen van een tagtaxonomie is cruciaal om het voor gebruikers mogelijk te maken assets te ontdekken en te ordenen in AEM. |
| [Metadataprofielen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-profiles.html) | Met metadataprofielen kunnen standaardmetadata automatisch worden toegepast op assets in assetmappen. Dit verkleint de last van metadatabeheer voor AEM-gebruikers en vergroot de consistentie van metadata. |
| [Metadataschema&#39;s](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/configuring/metadata-schemas.html) | Metadataschema&#39;s definiëren de interface die metadata van assets in AEM beschikbaar maakt. In deze video wordt de combinatie van methoden voor het toepassen van assets besproken. |

### Aanvullende bronnen

* [Releaseopmerkingen bij AEM als Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)
* [AEM als Cloud Service-documentatie](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [AEM 6.4 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [AEM 6.3 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [AEM 6.2 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html)
* [Releaseopmerkingen bij AEM Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/nl-NL/dynamic-media-classic/using/home.html)
* [Releaseopmerkingen bij Dynamic Media](https://docs.adobe.com/content/help/nl-NL/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Releaseopmerkingen bij Livefyre](https://docs.adobe.com/content/help/nl-NL/livefyre/using/release-notes/c-rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Campaign Standard

* [Adobe Campaign Standard 20.3-release](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campaign-besturingsdeelvenster

| Functie | Beschrijving |
| -----------| ---------- |  
| Beheer van GPG-codes | Installeer en/of genereer GPG-codes op een marketinginstantie om data die vanuit Campaign worden verzonden, te coderen en inkomende data te ontcijferen. |
| Certificaatbeheer voor CNAME-subdomeinen | Met het besturingsdeelvenster kunt u nu de SSL-certificaten van uw subdomeinen vernieuwen die zijn gedelegeerd met de CNAME-methode. |

### Nieuwe zelfstudies voor Campaign

* Nieuwe tutorials voor Campaign Standard

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Besturingsdeelvenster - Google TXT-recordbeheer](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Leer hoe u verificatiedata van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Campaign-besturingsdeelvenster. |
| [Een workflow configureren en uitvoeren met de externe-API-activiteit](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Leer een extern REST-API-eindpunt op te roepen met de externe-API-activiteit. |
| [Aan de slag met pushmeldingen voor Android-tutorial](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | In deze zelfstudie worden de stappen beschreven die nodig zijn om pushmeldingen in te stellen met Campaign Standard en de Android-app. |

* Nieuwe tutorials voor Campaign Classic

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Beheer van big data op Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Krijg inzicht in het gebruik van de Snowflake-connector in Adobe Campaign Classic. |
| [Besturingsdeelvenster - Google TXT-recordbeheer](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Leer hoe u verificatiedata van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Campaign-besturingsdeelvenster. |

### Help-informatie en bronnen voor Campaign

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/campaign-standard-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/overview.html) - [Releaseplanning](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/campaign-classic-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/nl-NL/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/control-panel/using/release-notes.html)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

* [Nieuwe functies in Advertising Cloud DSP](#adcloud-dsp)
* [Nieuwe functies in Advertising Cloud Search](#adcloud-search)

### Nieuwe functies in Advertising Cloud DSP {#adcloud-dsp}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaigns Classic] en [!UICONTROL Campaigns Beta] | De IAS-meetinstellingen voor fraude en merkveiligheid, die u desgewenst voor elke campagne kunt configureren, bevatten nu opties voor metingen op VAST- en VPAID-inventory&#39;s. |
| [!UICONTROL Campaigns Beta] | De laadtijden van datavisualisatie en pagina&#39;s zijn verbeterd. |
|  | Op alle pagina&#39;s kunt u nu Excel-rapporten downloaden die zijn gebaseerd op de huidige filters en weergaven. |
|  | (In de release van 22 mei) Nieuwe cijfers omvatten cijfers voor alle datums, leveringen in het huidige interval, en datumspecifieke OTS. |
| [!UICONTROL Blacklists] | In het prognosesysteem wordt nu automatisch de zwarte lijst voor adverteerders- of accountniveau gebruikt. Gebruikers hoeven de zwarte lijst niet meer in de plaatsingsinstellingen te plakken. |
| [!UICONTROL Inventory Deals] | (Gesloten bèta) Met de nieuwe, vereenvoudigde vorm kunt u snel SSP-deals (zijplatform) opzetten, bewerken en corrigeren die niet beschikbaar in het Postvak IN van de Deal-id. |
|  | Wanneer u een pakket van programmatisch gegarandeerde deals in het Postvak IN van de Deal-id accepteert, krijgt u nu een bericht dat u een standaardplaatsing voor elk van de Deal-id&#39;s moet maken. |

### Nieuwe functies in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaigns] | (Google Ads-accounts; bètaservice) Vanaf eind mei kunt u met Advertising Cloud Search data voor uw Google Gmail-weergavecampagnes en uw Google Smart Shopping-campagnes synchroniseren met Google-conversies voor tracering en rapportage. Met deze service kunt u ook de campagne-instellingen en de reclamegroepsinstellingen voor uw bestaande campagnes bewerken vanuit de weergaven Campagnes en Advertentiegroepen. De service is optioneel. Zodra de service algemeen beschikbaar is, worden extra kosten in rekening gebracht.<br>Neem voor meer informatie over de service, waaronder het bètaprogramma en de toekomstige omvang, contact op met uw Adobe-accountmanager. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Voor de versienota&#39;s van Magento raadpleegt u:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo] {#marketo}

[!DNL Marketo Engage] is een volledige applicatie voor leadmanagement en B2B-marketeers die klantervaringen willen transformeren door betrokkenheid in elke fase van complexe kooptrajecten.

### Belangrijke Marketo Engage-updates

Zie [!DNL Marketo] [releaseopmerkingen](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) voor de recentste releasegegevens.

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
