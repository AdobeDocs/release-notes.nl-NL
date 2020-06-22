---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Opmerkingen bij de release Adobe Experience Cloud
doc-type: release notes
last-update: June 2020
author: mfrei
translation-type: tm+mt
source-git-commit: a88748f592df569028641cd53d563e3b6c1d1201
workflow-type: tm+mt
source-wordcount: '6520'
ht-degree: 32%

---


# Opmerkingen bij de release Adobe Experience Cloud - juni 2020

![Banner](/assets/experience-cloud-banner-3.png)

This page describes new features, fixes, and important notices in [!DNL Adobe Experience Cloud]. Ook worden nieuwe documentatie, trainingscursussen en videozelfstudies gemarkeerd om u te helpen optimaal te profiteren van Experience Cloud.

>[!NOTE]
>
>Subscribe to the [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) to be notified via email about upcoming releases.

**Releasedatum: 18 juni 2020**

De releasedatums van het product kunnen variëren. Controleer regelmatig of er updates zijn.

Laatste update: **18 juni 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [Journey Orchestration](#journey-orch)
* [Analytics](#analytics) (en [Customer Journey Analytics](#cust-journey))
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [Campagne](#ac)
* [Advertising Cloud](#adcloud)
* [!DNL Target](https://docs.adobe.com/content/help/nl-NL/target/using/release-notes/target-release-notes.html)
* [!DNL Magento](#magento)
* [!DNL Marketo Engage](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/nl/primetime/user-guide.html) (koppelingen naar de Help-pagina van Primetime)

Hulp nodig? Bezoek de [Adobe Experience League](https://experienceleague.adobe.com/#home) om product- en technische documentatie, cursussen met Adobe-cursus, videozelfstudies, snelle antwoorden, inzicht in de gebruikersgemeenschap en training onder leiding van instructeurs te zoeken.

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL Adobe System Status] biedt gedetailleerde informatie, statusupdates en e-mailmeldingen over uitval-, onderbrekings- en onderhoudsgebeurtenissen van Adobe Cloud-producten en -services. Ga naar [status.adobe.com](https://status.adobe.com/).

Uitgegeven: **21 mei 2020**

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
   * Browserondersteuning: Tot de ondersteunde browsers behoren [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari] en [!DNL Opera] (de nieuwste versies). **Opmerking:** Hoewel de interface van Experience Cloud deze browsers steunt, zouden de individuele toepassingen niet elke browser kunnen steunen. ([Analytics](https://docs.adobe.com/content/help/nl-NL/analytics/admin/sys-reqs.html) biedt bijvoorbeeld geen ondersteuning voor [!DNL Opera] en [Target](https://docs.adobe.com/help/nl-NL/target/using/implement-target/before-implement/supported-browsers.html) biedt geen ondersteuning voor [!DNL Safari].)
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
| Adobe Analytics | `experience.adobe.com/analytics` |
| Customer Journey Analytics | `experience.adobe.com/platform/analytics` |
| Adobe Campaign-besturingsdeelvenster | `experience.adobe.com/controlpanel` |
| Cloud Manager | `experience.adobe.com/cloud-manager` |
| Places Service | `experience.adobe.com/places` |
| Softwaredistributie | `experience.adobe.com/downloads` |
| Admin-tool (bèta) | `experience.adobe.com/admin` |

>[!NOTE]
>
>**[!UICONTROL Board & Collections]**, een verouderd filter in de [!UICONTROL Marketing Cloud Assets]-kiezer, wordt uitgeschakeld.

## ![Adobe Experience Platform pictogram](/assets/experience_platform_appicon_24.png) {#platform}

Release notes for the [!DNL Experience Platform] and application services, including [!DNL Experience Platform Launch,] [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services], and security bulletins.

Releasedatum: **10 juni 2020**

[!DNL Adobe Experience Platform] bevat de volgende nieuwe functies:

* **Werkruimte voor gegevenswetenschap:** De [!DNL JupyterLab Launcher] laptop is nu voorzien van een [!DNL Python] startfunctie voor realtime leren van machines (Alpha).
* **Segmentatie:** Er is een datumveld voor de datum van een verjaardag toegevoegd, waarmee gebruikers datums zonder het jaar kunnen evalueren.
* **Bronnen:** Nieuwe bronschakelaars voor [!DNL Apache HDFS] en [!DNL Couchbase].

Zie Opmerkingen bij de release van [Experience Platforms voor meer informatie over deze functies](https://docs.adobe.com/content/help/nl-NL/experience-platform/release-notes/latest.html#!end-user/markdown/release-notes/release-notes.md).

### Aanvullende releasedata bij Experience Platform

* [Releaseopmerkingen bij Experience Platform Launch](https://docs.adobe.com/content/help/nl-NL/launch/using/intro/release-notes/current.html)
* [Beveiligingsbulletins en adviezen](https://helpx.adobe.com/nl/security.html) (Alle Adobe-producten)

### Nieuwe cursussen en zelfstudies voor Experience Platforms {#tutorials-plat}

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |
| [Inleiding tot Adobe Experience Platform](https://experienceleague.adobe.com/?recommended=ExperiencePlatform-U-1-2020.1) | Cursus | Leer hoe Adobe Experience Platform u de juiste ervaring biedt door uw gegevens om te zetten in robuuste realtime klantprofielen en door AI aangedreven inzichten die u in elk kanaal kunt activeren. Deze cursus op introductieniveau geeft u een overzicht van de mogelijkheden van Experience Platforms, gebruiksscenario&#39;s, relatie met Adobe Experience Cloud, basisarchitectuur, interface en projectrollen. |
| [Inleiding tot Web SDK en Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/introduction-to-web-sdk-and-edge-network.html) | Videozelfstudie | Een overzicht van Adobe Experience Platform SDK en het Netwerk van de Rand. Experience Platform Web SDK is een JavaScript-bibliotheek aan de clientzijde waarmee klanten één JavaScript-bibliotheek, één type baken, één gegevensstroom, één gegevensstroom en een bestemming aan de serverzijde kunnen gebruiken om gegevens naar alle Adobe-toepassingen en naar andere bestemmingen te verzenden. |
| [Demo van Web SDK en Edge Network](https://docs.adobe.com/content/help/en/platform-learn/tutorials/data-ingestion/web-sdk/demo-of-web-sdk-and-edge-network.html) | Videozelfstudie | Bekijk de SDK van het Web van het Adobe Experience Platform en het Netwerk van de Rand in actie, met één enkele vraag aan Adobe die gegevens naar Experience Platform, Analytics, Audience Manager en Target verzendt. |
| [Demo van Platform van realtime klantgegevens](https://docs.adobe.com/content/help/en/platform-learn/tutorials/rtcdp/demo.html) | Videozelfstudie | Leer hoe CDP in real time wordt gebruikt om gegevens uit veelvoudige bronnen te verzamelen. U kunt die gegevens in één enkel real-time klantenprofiel samenvoegen, en die gegevens activeren om gepersonaliseerde klantenervaringen tot stand te brengen. |

## ![Icon](/assets/experience_platform_appicon_24.png) Journey Orchestration {#journey-orch}

Met behulp van het Adobe Experience Platform kunt u individuele customer journeys op schaal orkestreren via verschillende ervaringskanalen ordenen door intelligent en in real time te anticiperen op wat ieder individu nodig heeft, waar de reis ook heen gaat.

### Laatste release

Zie Opmerkingen bij de release van [Journey Orchestration voor de meest recente release-updates](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html)

### Nieuwe cursussen en zelfstudies voor Journey Orchestration {#jo-tutorials}

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |
| [Aan de slag met Journey Orchestration voor beheerders](https://experienceleague.adobe.com/?recommended=JourneyOrchestration-A-1-2020.2) | Cursus | Leer hoe u Journey Orchestration configureert en gebruikt. Deze cursus behandelt de belangrijkste concepten, en de configuratiestappen die worden vereist om de orchestratie van een reis toe te laten. Leer hoe u uw georkestreerde reizen kunt maken, publiceren en analyseren. |
| [Aan de slag met Journey Orchestration voor zakelijke gebruikers](https://experienceleague.corp.adobe.com/?recommended=JourneyOrchestration-U-1-2020.1) | Cursus | Leer hoe u Journey Orchestration configureert en gebruikt. Deze cursus behandelt de belangrijkste concepten. U leert hoe u uw georkestreerde reizen kunt maken, publiceren, rapporteren en analyseren. |

### Aanvullende bronnen voor Journey Orchestration

[Documentatie](https://docs.adobe.com/content/help/nl-NL/journeys/using/journey-orchestration-home.html) - [Release-aantekeningen](https://docs.adobe.com/content/help/nl-NL/journeys/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

## ![Pictogram](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Releasedatum: **18 juni 2020**

* [Nieuwe functies in Adobe Analytics](#aa-features)
* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Nieuwe functies in Media Analytics](#media-aa)
* [Oplossingen in Adobe Analytics](#aa-fixes)
* [Belangrijke berichten voor Analytics-beheerders](#aa-notices)
* [Nieuwe cursussen en zelfstudies voor Adobe Analytics](#tutorials-analytics)
* [AppMeasurement](#appm)

### Nieuwe functies in Adobe Analytics {#aa-features}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- |-------|
| Attributie-IQ: Algorithmic Attribution | 18 Juni 2020 | Het [!UICONTROL Algorithmic Attribution] model in Analysis Workspace gebruikt statistische technieken om dynamisch de optimale allocatie van het krediet voor de geselecteerde maatstaf te bepalen. Beschikbaar voor Adobe Analytics Ultimate-klanten. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/algorithmic.html) |
| Attributie-IQ: Aangepaste terugzoekvensters | 18 Juni 2020 | U kunt nu elk toewijzingsmodel configureren in [!UICONTROL Attribution IQ] om aanraakpunten op te nemen van maximaal 90 dagen vóór de rapportperiode. Dit zal de toewijzingsnauwkeurigheid voor gebeurtenissen die zich vroegtijdig in de verslagperiode voordoen, doorgaans verhogen door de verwerking van interacties die in de voorafgaande maand(en) hebben plaatsgevonden. Beschikbaar voor Adobe Analytics Foundation, Select, Premium, Premium, Premium Attribution, Premium Complete en Ultimate-klanten. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/panels/attribution/attribution.html#lookback-windows) |
| Projectrollen voor gedeelde werkruimteprojecten | 18 Juni 2020 | Wanneer het delen van een project van de Werkruimte, kunt u ontvangers in één van drie projectrollen nu plaatsen, afhankelijk van de projectervaring u hen wilt hebben: Bewerken, dupliceren en weergeven. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Alleen-weergeven werkruimteprojecten | 18 Juni 2020 | Werkruimteprojecten kunnen aan gebruikers worden gedeeld als &quot;Alleen kan bekijken&quot;. Wanneer een ontvanger van de Mening het gedeelde project opent, ontvangen zij een meer restrictieve projectervaring, zonder linkerspoorstaaf en beperkte interactie. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/view-only-projects.html) |
| Mogelijkheid om werkruimteprojecten samen te bewerken | 18 Juni 2020 | Ontvangers die aan de rol &quot;Kan uitgeven&quot;worden toegevoegd kunnen over een project bewaren dat aan hen is gedeeld. Dit geldt zowel voor beheerders als niet-beheerders. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/curate-share/share-projects.html) |
| Bijgewerkt leeg deelvenster in werkruimte | 18 Juni 2020 | Het lege deelvenster in Workspace bevat nu deelvensters en visualisaties, zodat u een naadloze manier hebt om de analyseworkflow te kiezen die het beste voor u werkt. |
| Eerste-partijdomeinen beschikbaar in China RDC | 18 Juni 2020 | Laat klanten met een `.cn` domein toe om een 1st-partijdomein voor gebruik binnen het Chinese vasteland aan te vragen. (Documentatie beschikbaar bij de aankoop van SKU &quot;China Performance Optimization&quot;.) |
| Deelvenster Snelle inzichten in werkruimte | 25 Juni 2020 | Quick Insights biedt hulp aan niet-analisten en nieuwe gebruikers van Analysis Workspace om te leren hoe zakelijke vragen snel en eenvoudig te beantwoorden. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/analyze/analysis-workspace/panels/quickinsight.html) |
| Deelvenster Analytics for Target in Workspace | 25 Juni 2020 | Met het deelvenster Analytics for Target (A4T) kunt u uw Adobe Target-activiteiten en -ervaringen in Analysis Workspace met een optillen en vertrouwen analyseren. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/analyze/analysis-workspace/panels/a4t-panel.html) |
| [!UICONTROL About Workspace] page | Juni 18,2020 | De [!UICONTROL About Workspace] pagina bevat informatie over uw Analysis Workspace-omgeving, over uw Adobe Analytics-beheerders (als u ondersteuning nodig hebt) en een manier om feedback in het product te geven. U vindt deze onder **[!UICONTROL Workspace]** > **[!UICONTROL Help]** > **[!UICONTROL About Workspace]**. |

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- |-----|
| Ondersteuning voor objectarrays | 18 Juni 2020 | CJA-klanten kunnen nu de afmetingen en metriek rapporteren die in Object-arrays worden weergegeven binnen hun schema&#39;s voor de gegevensset van Adobe Experience Platforms. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-usecases/object-arrays.html) |
| Attribution IQ: [!UICONTROL Algorithmic Attribution] | 18 Juni 2020 | Het [!UICONTROL Algorithmic Attribution] model in [!UICONTROL Analysis Workspace] gebruik van statistische technieken om dynamisch de optimale allocatie van krediet voor de geselecteerde maatstaf te bepalen. Beschikbaar voor Adobe Analytics Ultimate-klanten. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/algorithmic.html) |
| Attributie-IQ: Aangepaste terugzoekvensters | 18 Juni 2020 | U kunt nu elk attributiemodel configureren in [!UICONTROL Attribution IQ] om aanraakpunten op te nemen van maximaal 90 dagen vóór de rapportperiode. Dit zal de toewijzingsnauwkeurigheid voor gebeurtenissen die zich vroegtijdig in de verslagperiode voordoen, doorgaans verhogen door de verwerking van interacties die in de voorafgaande maand(en) hebben plaatsgevonden. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/attribution/models.html) |
| ondersteuning voor [!UICONTROL Anomaly Detection] | 18 Juni 2020 | [!UICONTROL Anomaly Detection] verschaft een statistische methode om te bepalen hoe een bepaalde meting is gewijzigd ten opzichte van eerdere gegevens. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/virtual-analyst/anomaly-detection/anomaly-detection.html) |
| Projectrollen voor gedeelde [!UICONTROL Workspace] projecten | 18 Juni 2020 | Wanneer het delen van een [!UICONTROL Workspace] project, kunt u ontvangers in één van drie projectrollen nu plaatsen, afhankelijk van de projectervaring u hen wilt hebben: Bewerken, dupliceren en weergeven. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Alleen-weergeven [!UICONTROL Workspace] projecten | 18 Juni 2020 | [!UICONTROL Workspace] projecten kunnen _[!UICONTROL Can View]_alleen aan gebruikers worden gedeeld. Wanneer een ontvanger van de Mening het gedeelde project opent, ontvangen zij een meer restrictieve projectervaring zonder linkerspoorstaaf en beperkte interactie.[Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/view-only-projects.html) |
| Mogelijkheid om projecten te [!UICONTROL Workspace] bewerken | 18 Juni 2020 | Ontvangers die aan de _[!UICONTROL Can Edit]_rol zijn toegevoegd, kunnen een project opslaan dat aan hen is gedeeld.[Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/curate-share/share-projects.html) |
| Deelvenster Snelle inzichten in [!UICONTROL Workspace] | 25 Juni 2020 | Quick Insights provides guidance for non-analysts and new users of [!UICONTROL Analysis Workspace] to learn how to answer business questions quickly and easily. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics-platform/using/cja-workspace/panels/quickinsight.html) |
| [!UICONTROL About Workspace] page | Juni 18,2020 | De [!UICONTROL About Workspace] pagina bevat informatie over uw Analysis Workspace-omgeving, over uw Adobe Analytics-beheerders (als u ondersteuning nodig hebt) en een manier om feedback in het product te geven. U vindt deze onder **[!UICONTROL Workspace]** > **[!UICONTROL Help]** > **[!UICONTROL About Workspace]**. |

### Nieuwe functies in [!UICONTROL Media Analytics] {#media-aa}

Datum bijgewerkt: **18 juni 2020**

| Functie | [Algemene beschikbaarheid](https://docs.adobe.com/content/help/nl-NL/analytics/landing/an-releases.html) - Doeldatum | Beschrijving |
| -----------| ---------- | ---------- |
| [Ondersteunde apparaten en platforms](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 Juni 2020 | De extensie Media Launch met AEP SDK ondersteunt nu de volgende OTT-apparaten:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android-tv</li></ul> |  | [Ondersteunde apparaten en platforms](https://docs.adobe.com/content/help/en/media-analytics/using/supported-devices.html) | 18 Juni 2020 | De extensie Media Launch met AEP SDK ondersteunt nu de volgende OTT-apparaten:<ul><li>Apple TV (tvOS)</li><li>Fire TV (Fire OS)</li><li>Android-tv</li></ul> |
| [Player-status bijhouden](https://docs.adobe.com/content/help/nl-NL/media-analytics/using/player-state-tracking/player-state-overview.html) | 29 Mei 2020 | [!UICONTROL Media Analytics] klanten kunnen tijdens het afspelen viewerinteractie vastleggen met een standaardset oplossingsvariabelen voor volledig scherm, ondertiteling, dempen, beeld-in-beeld en scherpgesteld. U kunt desgewenst ook aangepaste Player-statussen te maken. Variabelen voor het bijhouden van Player-statussen kunnen nu worden gerapporteerd in [!UICONTROL Analysis Workspace]. Voor deze functie is een van de volgende opties vereist: <ul><li>Media [!DNL JavaScript] SDK 3.0 of hoger</li><li>Voor gebruik met de [!DNL Adobe Experience Platform] (AEP) SDK:</li><li>[!UICONTROL Media Analytics Extension] (voor web): [!UICONTROL Adobe Media Analytics] (3.x SDK) voor Audio &amp; Video v1.0 of hoger</li><li>[!UICONTROL Media Analytics Extension] (voor mobiele apparaten): [!UICONTROL Adobe Media Analytics for Audio] en Video v2.0 of hoger</li><li>[!UICONTROL Media Collection]</li></ul> |

### Oplossingen in Adobe Analytics {#aa-fixes}

* Probleem verholpen waarbij segmenten met multibyte-zoekopdrachten naar bepaalde rapportsuites niets raakten. Ze komen nu overeen met de juiste tekenreeksen. (AN-220043)
* Probleem verholpen waarbij de functie [!UICONTROL Item Filter] in [!UICONTROL Reports & Analytics] niet werkte. (AN-206132)
* Oplossing voor een trage reactietijd in de [!UICONTROL Scheduled Projects] interface. (AN-214837)
* Probleem verholpen waarbij een fout in het datumbereik werd gegenereerd met de Analytics Reporting API 2.0. (AN-215087)
* Fixed a case in which the instance/visit/visitor wasn&#39;t being counted in the denominator for the [!UICONTROL Time Spent] metrics. Dit gebeurt wanneer een hit zonder waarde voor de dimensie (bijvoorbeeld Pagename) in dezelfde seconde wordt gevolgd. (AN-211074)
* Probleem verholpen waarbij gebruikers geen toegang konden krijgen tot met hen gedeelde [!UICONTROL Workspace] projecten. (AN-217561)
* Probleem opgelost waarbij sleutels niet door werden geclassificeerd. [!UICONTROL Classification Rule Builder] (AN-221538)
* Probleem verholpen waarbij [!UICONTROL Server Call Usage] geen gebruiksgegevens werden gerapporteerd. (AN-210452)
* Problemen verholpen waarbij gegevens in de Audience Manager ontbraken in gepubliceerde Adobe Analytics-segmenten. (AN-220208, AN-220659)
* Probleem verholpen met rapporten waarin gegevens werden weergegeven, maar [!UICONTROL Data Feeds] logboeken waarin stond &quot;Geen Data warehouse-gegevens&quot;. (AN-220784, AN-220858)
* Correctie van problemen die het opstarten van [!UICONTROL Ad Hoc Analysis] het `experiencecloud.com` domein hebben verhinderd. (AN-219680, AN-221629)
* Correctie van problemen met de hotkey &quot;Ctrl (of Command) + C&quot;. (AN-221101, AN-221537)
* Probleem verholpen met de pagina [!UICONTROL Activity Map] Enablement. (AN-222029, AN-221242)
* Probleem verholpen waarbij een aanraakpunt niet midden in een [!UICONTROL Fallout] visualisatie kon worden toegevoegd. (AN-221648)

#### Nog meer oplossingen in Adobe Analytics

AN-218269; AN-218455; AN-218492; AN-219888; AN-220447; AN-220546; AN-220788; AN-220866; AN-221165; AN-221545; AN-221712; AN-221832; AN-221853; AN-222000; AN-222505; AN-222559

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| Migratie naar uniform productdomein | Ingangsdatum: 28 mei 2020 | De migratie naar een uniform productdomein voor Adobe Analytics dat in januari 2020 is gestart, is op 28 mei 2020 voltooid. While Adobe Analytics works to remove all `omniture.com` domain references from its architecture, it is important to allowlist `omniture.com` as a third-party cookie. Wanneer de volledige architectuurmigratie (binnenkort) is voltooid, stellen we u via de releaseopmerkingen op de hoogte en deze allowlist-stap is dan niet meer nodig. [Hier](https://helpx.adobe.com/nl/analytics/kb/adobe-ip-addresses.html) is een volledige lijst van geadviseerde IP adressen en domeinen die u zou moeten toestaan.<br>Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen. |
| Nieuwe standaard landingspagina voor Adobe Analytics | Ingangsdatum: 18 juni 2020 | Op 18 juni 2020 verandert de standaard landingspagina voor Adobe Analytics van [!UICONTROL Reports] naar [!UICONTROL Workspace]. Deze wijziging vindt plaats voor alle gebruikers die nog geen aangepaste landingspagina hebben ingesteld. |
| Technologie van derden is toegestaan | 12 Maart 2020 (ingangsdatum) | Adobe Analytics is gestart met het gebruik van technologieën van derden voor doorlopend implementatiebeheer van functies en voor ondersteuning in het product. De volgende URL&#39;s moeten worden toegevoegd aan alle benodigde netwerkfirewallallowlists om volledige toegang tot functies te garanderen:<ul><li>Gainsight: https://esp.aptrinsic.com</li><li>LaunchDarkly: https://app.launchdarkly.com</li></ul> |
| Improved redundancy for [!UICONTROL Analysis Workspace] availability | 21 Mei 2020 | In order to ensure availability of [!UICONTROL Analysis Workspace], we are adding a secondary CDN (Content Delivery Network) for improved redundancy. De volgende URL&#39;s moeten worden toegevoegd aan alle benodigde lijsten met netwerkfirewalls:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Wijzigen in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace] | 7 april 2020 | Sinds maart 2020 is in [!UICONTROL Analysis Workspace] gewijzigd hoe de waarde _Geen_ communiceert met [!UICONTROL Entries/Exits]. Omdat u _Geen_ nu kunt in- en uitschakelen in [!UICONTROL Analysis Workspace], gebruiken we de waarde _Geen_ na openen en afsluiten, waar dit (voor eVars) vroeger werd toegepast vóór openen en afsluiten. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor eVars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] verschijnt de eerste hit als _Niet gespecificeerd_ voor de vermelding, maar in [!UICONTROL Analysis Workspace] verschijnt dit als de waarde voor de tweede hit. |
| EOL van **[!UICONTROL Dashboard Archive]** | 27 maart 2020 | De instelling **[!UICONTROL View Archive]** onder **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] zal vanaf oktober 2020 niet meer beschikbaar zijn. |
| Einde van levensduur - Verouderde Analytics-API&#39;s | 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

#### Nieuwe cursussen en zelfstudies voor Analytics {#tutorials-analytics}

Nieuwe cursussen, zelfstudievideo&#39;s en artikelen in Analytics en Customer Journey Analytics.

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |
| [Aan de slag met Customer Journey Analytics for Users](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-U-1-2020.1) | Cursus | In deze cursus leert u hoe u Customer Journey Analytics (CJA) kunt gebruiken om gegevens uit vele verschillende gegevensbronnen te analyseren. U leert de verschillen tussen Adobe Analytics en Customer Journey Analytics en hoe de gegevens worden verwerkt in CJA. Na het volgen van deze cursus, zou u kanaalvisualisaties voor meer inzicht in uw klanten moeten kunnen tot stand brengen en aanpassen. |
| [Aan de slag met Customer Journey Analytics voor beheerders](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-A-1-2020.1) | Cursus | Leer hoe te vormen en te gebruiken [!UICONTROL Journey Orchestration]. Deze cursus behandelt de belangrijkste concepten en de configuratiestappen die worden vereist om de orchestratie van een Reizen toe te laten. U leert hoe u uw georkestreerde reizen kunt maken, publiceren en analyseren. |
| [Aan de slag met Customer Journey Analytics for Data Engineers](https://experienceleague.adobe.com/?recommended=CustomerJourneyAnalytics-D-1-2020.1) | Cursus | In deze cursus leert u meer over de gegevens die in Customer Journey Analytics worden ingevoerd en over de invloed ervan op de rapporten voor de analist. Deze cursus bouwt voort op uw algemene kennis van het Adobe Experience Platform. |
| [Aan de slag met Customer Journey Analytics voor beheerders](https://video.tv.adobe.com/v/34349?captions=dut) | Videozelfstudie | Een inleidende video naar Customer Journey Analytics for Administrator. |
| [Analytics-implementatie met instructies](https://experienceleague.adobe.com/?recommended=Analytics-D-1-2019.1) | Cursus | In deze cursus leert u hoe u Adobe Analytics kunt gaan implementeren, inzicht kunt krijgen in Analytics-concepten, een abonnement kunt maken en Adobe Analytics kunt implementeren met behulp van Experience Platform Launch. |
| [Adobe Analytics Grondbeginselen voor leiders](https://experienceleague.adobe.com/?recommended=Analytics-L-1-2020.1) | Cursus | In deze cursus leert u meer over de basisprincipes van Analytics en hoe Analysis Workspace uw bedrijf kan veranderen. Leer hoe u inzichten met Adobe Sensei kunt ontdekken, klantengetuigenissen kunt horen, en hoogtepunten van industriedeskundigen op Top 2019 kunt bekijken. |
| [Aan de slag met Analysis Workspace](https://experienceleague.adobe.com/?recommended=Analytics-U-1-2020.1.workspace) | Cursus | Leer hoe je aan de slag kunt met Analysis Workspace. Bouw uw eerste project, leer hoe te om datumwaaiers te bepalen, segmenten toe te passen, en deel en aan projecten samen te werken. |
| [Adobe Analytics-dashboards Scorecard Builder](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-scorecard-builder.html) | Videozelfstudie | In deze video leert u hoe u kunt maken en delen [!UICONTROL Scorecards] in [!UICONTROL Analysis Workspace] om te worden weergegeven op Adobe Analytics-dashboards (mobiele app). |
| [Ervaring met Adobe Analytics-dashboards in de app](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/additional-tools/analytics-dashboards/adobe-analytics-dashboards-in-app-experience.html) | Videozelfstudie | In deze video leert u hoe u Adobe Analytics-dashboards (mobiele app) kunt gebruiken voor toegang tot en weergave van [!UICONTROL Scorecards] gemaakte of met u gedeelde dashboards. |

#### Bronnen voor Analytics Help

* [Adobe Analytics-tutorials](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/overview.html)
* [Adobe Analytics-productdocumentatie](https://docs.adobe.com/content/help/nl-NL/analytics/landing/home.html)

## ![Adobe Audience Manager pictogram](/assets/audience-manager.png) {#aam}

Nieuwe functies, correcties, documentatie en tutorials in Audience Manager.

Updated **June 10, 2020**

### Gebruikersinterface-updates

Audience Manager brengt updates uit van het domein en de headerbalk om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-applicaties.

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikers-Help, inclusief aanbevolen artikelen en contextrelevante video&#39;s in het menu Help.
* Mogelijkheid om feedback te geven over Experience Platform- en bestandsondersteuningstickets.
* Een nieuw, eenvoudiger URL-patroon. Werk uw bladwijzers bij naar de nieuwe URL: `experience.adobe.com/audience-manager`.

Deze updates zijn alleen beschikbaar voor gebruikers die zich aanmelden met Adobe ID. Raadpleeg [Experience Cloud-gebruikers en -producten beheren](https://docs.adobe.com/content/help/nl-NL/core-services/interface/manage-users-and-products/admin-getting-started.html) om naar een Adobe ID-aanmelding over te schakelen.

### Nieuwe functies en oplossingen in Adobe Audience Manager

| Functie | Beschrijving |
| -----------| ---------- |  
| [Audience Manager-plug-in voor IAB TCF v2.0 ](https://docs.adobe.com/content/help/en/audience-manager/user-guide/overview/data-privacy/consent-management/aam-iab-plugin.html) | Aangezien Adobe zich blijft richten op &#39;Privacy door Ontwerp&#39;, werken we de plug-in Audience Manager voor IAB TCF bij naar IAB Transparency &amp; Consent Framework (TCF) versie 2.0, die op 10 juni 2020 van start gaat. Klanten die de plug-in Audience Manager voor IAB TCF hebben geïmplementeerd, moeten vóór 15 augustus 2020 een upgrade naar versie 2.0 uitvoeren om de functie te kunnen blijven gebruiken. Na 15 augustus 2020 wordt versie 1.1 vervangen en niet meer ondersteund. |

**Oplossingen**

* Bijgewerkt om de wettelijke vereisten in specifieke geografische gebieden [!UICONTROL Audience Marketplace Terms & Conditions] weer te geven. (AAM-54518)
* Probleem verholpen waarbij een fout van 404 zou optreden als u de [!UICONTROL Traits] pagina benadert via bladwijzers. (AAM-54768)
* Probleem verholpen waarbij de API voor doelupdate tijdens het ophalen uit was. [!UICONTROL Algorithmic Models] (AAM-54342)
* Gebruikers kunnen nu een model zien voor een nauwkeurigheidsindicator voor de classificatie [!UICONTROL Smart Personas]. (AAM-54847)
* Probleem verholpen waarbij door op Enter te drukken nadat een standaardexpressie was toegevoegd, de expressie zou worden verwijderd in plaats van opgeslagen. (AAM-54210)
* Oplossing voor een probleem waarbij aanroepen naar de GET-methode van de [!UICONTROL Traits] API zouden mislukken voor gebruikers die niet over de machtiging VIEW_MODELS beschikten. (AAM-53104)
* Probleem verholpen waarbij gebruikers [!UICONTROL Algorithmic Models] de inhoud niet konden verwijderen [!UICONTROL Folder Traits]. (AAM-50192)
* Lange trace-expressies lopen nu over meerdere regels. (AAM-54972)
* Probleem verholpen waarbij gebruikers met alleen-lezen machtigingen de [!UICONTROL Create New] knop op de pagina&#39;s met algoritmische modellen konden zien. (AAM-54889)
* Probleem verholpen waarbij de laadindicator voor het laden [!UICONTROL General] en [!UICONTROL Trend] rapporten bleef draaien nadat het downloaden van CSV was voltooid. (AAM-54571)
* Probleem verholpen waarbij gebruikers geen bulkkenmerken konden toevoegen aan segmenten in de [!UICONTROL Segment Builder]app. (AAM-55033)
* Meerdere toegankelijkheidsverbeteringen in de interface. (AAM-47269, AAM-48966, AAM-48976, AAM-49369, AAM-49023, AAM-49042).

### Nieuwe cursussen en zelfstudies voor Audience Managers {#tutorials-aam}

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |  
| [Inleiding tot Audience Manager](https://experienceleague.adobe.com/?recommended=AudienceManager-U-1-2020.1) | Cursus | Deze cursus leert u de grondbeginselen van Audience Manager en de problemen die u kunt oplossen. Leer over gemeenschappelijke gebruiksgevallen en zeer belangrijke Audience Manager termijnen en concepten. |
| [Inleiding tot Identiteit in Audience Manager](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/intro-to-audience-manager/introduction-to-identity-in-audience-manager.html) | Videozelfstudie | Leer hoe Adobe Audience Manager identiteiten beheert, inclusief interne profielen en samenvoegen van profielen en id-synchronisatie met partners. |
| [Het begrip van en het Vormen van LinkedIn op mensen-Gebaseerde Bestemming](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/data-activation/people-based-destinations/understanding-and-configuring-the-linkedin-pbd.html) | Cursus | Deze video begeleidt u door de concepten en de stappen om een op mensen-Gebaseerde Bestemming aan LinkedIn tot stand te brengen. Het bouwt op de extra video&#39;s en de documentatie betreffende Op mensen-Gebaseerde Doelen voort. |
| [Op regels gebaseerde treits maken](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/build-and-manage-audiences/traits-and-segments/creating-rule-based-traits.html) | Videozelfstudie | Leer hoe te om [!UICONTROL Trait Builder] in de interface van de Audience Manager te gebruiken om een op regel-gebaseerd bezit tot stand te brengen, dat u toestaat om activiteit in real time in de profielen van de Audience Manager te vangen. |
| [Het toelaten van de Plug-in van de Audience Manager voor IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#enabling-iab-tcf) | Videozelfstudie | Leer hoe te om de Plug-in van de Audience Manager voor IAB TCF toe te laten. U kunt deze plug-in eenvoudig inschakelen als u Adobe Experience Platform starten gebruikt. |
| [Demo van de insteekmodule Audience Manager voor IAB TCF 2.0](https://docs.adobe.com/content/help/en/audience-manager-learn/tutorials/setup-and-admin/data-governance-and-privacy/iab-tcf-support.html#demo) | Videozelfstudie | In deze video ziet u hoe cookies en bakens van Experience Cloud ID Service en oplossingen worden beïnvloed door de keuzeselecties van de IAB-gebruiker. |

## ![Adobe Experience Manager pictogram](/assets/aem.png) {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe adviseert klanten met implementaties op locatie om de nieuwste patches te implementeren om een grotere stabiliteit, beveiliging en prestaties te garanderen.

### Productupdates

* **AEM 6.5.5.0**

   AEM 6.5, Service Pack 5 (6.5.5.0 uitgebracht op 4 juni 2020) is een belangrijke update die nieuwe eigenschappen, belangrijkste klant-gevraagde verhogingen, en prestaties, stabiliteit, veiligheidsverbeteringen omvat, die sinds de algemene beschikbaarheid van AEM 6.5 in April 2019 wordt vrijgegeven.

   * [Release-opmerkingen](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/sp-release-notes.html)
   * [Te leveren items voor release van AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.1**

   AEM 6.4, Service Pack 8, Cumulative Fix Pack (6.4.8.1 uitgebracht Juni 04, 2020) is een belangrijke update die verscheidene interne en klantenmoeilijke situaties omvat sinds de algemene beschikbaarheid van AEM 6.4, Service Pack 8 (6.4.8.0) in Maart 2020.

   * [Release-opmerkingen](https://docs.adobe.com/content/help/en/experience-manager-64/release-notes/cfp-release-notes.html)
   * [Te leveren items voor release van AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

### Zelfondersteuning

* **AEM als Cloud Service**

   Wat is er nieuw op AEM als Cloud Service?

   Tot de hooglichten behoren:

   * AEM Sites Commerce Integration Framework.
   * Verbeterde slimme tags en nieuwe functies in de training met instructies voor de gebruikersinterface.
   * Ondersteuning voor Adobe Asset Link voor Adobe XD.
   * AEM Assets Dynamic Media 3D-ondersteuning.
   * De nieuwe verbeteringen van de Zelfbediening verminderen gebiedsdelen van Adobe voor zandbakverrichtingen.
      * Dankzij de verbeterde ondersteuning voor zelfstandige sandboxen in Cloud Manager kunnen gemachtigde gebruikers alle omgevingen in een sandbox verwijderen en credits ontvangen.
      * Auto-Sluimerzandbakmilieu&#39;s &quot;hibernaten&quot;sandboxen na een periode van inactiviteit automatisch. Klanten kunnen actief &quot;dehibernatie&quot; activeren.
   * Overgangstools voor ondersteuning van cloudversnelling
   Met het doel om tijd en kosten aan overgang van op-gebouw aan Cloud Service te verminderen, werden twee overgangshulpmiddelen gelanceerd deze maand. Deze hulpmiddelen worden ontworpen om sommige zeer belangrijke taken tijdens overgangsproces te automatiseren en vandaar de algemene inspanning te verminderen. .

   1. [Met het gereedschap](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html) Inhoud overbrengen (beschikbaar op SD) stroomlijnt u de activiteit van de inhoudsoverdracht en maakt u deze schaalbaar. Met een gebruikersvriendelijke UI, is het hulpmiddel zelfbediening voor bestaande klanten en partners (on-prem/AMS) die aan AEM als Cloud Service overgaan.
   1. [AMS Dispatcher Converter](https://github.com/adobe/aem-cloud-service-dispatcher-converter) (Open-source)-hulpprogramma voor het automatiseren van de conversie van AMS Dispatcher-configuraties naar Cloud Service Dispatcher-configuraties.
   [Opmerkingen bij de release voor AEM als Cloud Service 2020.6.0](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/release-notes/release-notes/release-notes-current.html)

   Overgang:

   https://github.com/adobe/aem-cloud-service-dispatcher-converter

   https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/using-content-transfer-tool.html

* **Kernonderdelen**

   De Componenten van de kern 2.9.0 introduceert integratie met de Laag [van Gegevens van de Cliënt van](https://github.com/adobe/adobe-client-data-layer) Adobe en een nieuwe Component van de Bar van de Voortgang en is nu beschikbaar samen met [auteursdocumentatie](https://docs.adobe.com/content/help/en/experience-manager-core-components/using/introduction.html) en [ontwikkelaardetails en projectdownload beschikbaar op GitHub](https://github.com/adobe/aem-core-wcm-components).

* **Overstappen naar AEM as a Cloud Service**

   [Als u als Cloud Service](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/home.html) naar AEM gaat, wordt de aanbevolen overgang beschreven voor een bestaande AEM-klant die naar Cloud Service gaat. Het doel van deze documentatie is klanten van informatie, begeleiding en beste praktijken te voorzien om hen te helpen zich op deze overgang voorbereiden en deze reis gestructureerd en voorspelbaar te maken.

   Een van de gereedschappen voor cloudovergang - Content Transfer Tool is uitgebracht. [Het Content Transfer Tool](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/cloud-migration/content-transfer-tool/overview-content-transfer-tool.html) is ontwikkeld door Adobe en kan worden gebruikt om bestaande inhoud van een AEM-broninstantie (on-premise of AMS) naar de AEM Cloud Service-doelinstantie te verplaatsen.

   Één van de Hulpmiddelen van de Refactoring van de Code - AEM Dispatcher Converter werd vrijgegeven. [AEM Dispatcher Converter](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/moving/refactoring-tools/dispatcher-transformation-utility-tools.html) is een hulpmiddel om bestaande AEM Dispatcher-configuraties in AEM om te zetten als Cloud Service Dispatcher-configuraties en is beschikbaar.

* **Toegankelijkheid en de WCAG 2.1-richtsnoeren**

   Updates met betrekking tot de richtsnoeren van WCAG 2.1:

   * [Adobe Experience Manager as a Cloud Service en de Web Accessibility Guidelines](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/web-accessibility.html)
   * [Snelgids voor WCAG 2.1](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/accessibility/quick-guide-wcag.html)
   * [Toegankelijke content maken (WCAG 2.1-compatibiliteit)](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)

* **AEM-nieuwsbrieven**

   De nieuwsbrief van AEM door de Liga van de Ervaring wordt ontworpen om u te helpen om met AEM aan snelheid te komen zodat u kunt beginnen waarde meteen realiseren. Hier is de recentste nieuwsbrief:

   * [Volume 31](https://expleague.azureedge.net/assets/aem/Experience-Insider-vol.31.html): Experience Manager is nu beschikbaar als cloudservice.
   * [Lid worden](https://adobeeventsonline.com/AEM/2017/NL/Optin/) van de Experience Insider Newsletter.
   * Bekijk nieuwsbriefarchieven in de sectie [AEM-bronnen](https://helpx.adobe.com/nl/support/experience-manager/6-5.html) op de pagina Informatie en ondersteuning van Adobe Experience Manager 6.5.

### **Gemeenschap**

* **AEM Community Discussie**

   Nu kun je alle AEM aankondigingen bekijken en interessante verwijzingen naar interne en externe bloggers op één plaats. Zie het gedeelte [Discussie van de AEM-gemeenschap.](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/bd-p/adobe-experience-manager-discussions)

### Nieuwe cursussen en zelfstudies voor Experience Manager

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |
| [Aan de slag met Adobe Asset Link voor zakelijke gebruikers](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.asset.link) | Cursus | In deze cursus leert u hoe u de functies en mogelijkheden van Adobe Asset Link kunt gebruiken om uw creatieve ontwerp te voeden met inhoud die is opgeslagen in Adobe Experience Manager Assets. De cursus omvat alles, van hoe u de koppeling met Adobe-middelen kunt starten, elementaire middelenbewerkingen, opties voor zoeken en bladeren, en hoe u efficiënt kunt samenwerken met andere gebruikers. |
| [Aan de slag met AEM Assets voor zakelijke gebruikers](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.assets) | Cursus | Leer hoe u aan de slag kunt met AEM Assets voor zakelijke gebruikers. Verken de grondbeginselen van AEM Assets, samenwerkingsfuncties, zoeken, elementen ordenen en elementen en hun uitvoeringen downloaden. |
| [Aan de slag met AEM Sites voor zakelijke gebruikers](https://experienceleague.adobe.com/?recommended=ExperienceManager-U-1-2020.1.sites) | Cursus | Leer hoe u de kernfuncties en -mogelijkheden van AEM Sites kunt gebruiken om de webpagina&#39;s van uw organisatie te beheren. De cursus behandelt alles, van een inleiding tot AEM Sites, basisconcepten van creatie, geavanceerde ontwerpfuncties en mogelijkheden voor paginabeheer. |
| [AEM-projectstructuur](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/developing/aem-project-content-package-structure.html) | Artikel | Beschrijft de veranderingen die aan Adobe Experience Manager GeMaven projecten worden vereist zodat zij Cloud Service compatibel met AEM zijn. |
| [Verkoopmodellen](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#sling-models) | Videozelfstudie | Leer over het zuiveren AEM als lokale quickstart van Cloud Service SDK gebruikend de het Webconsole van Modellen van de Verschuiving. |
| [AEM-webconsolecomponenten](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/osgi-web-consoles.html#components) | Videozelfstudie | Leer over het zuiveren AEM als lokale quickstart van Cloud Service SDK gebruikend de het Webconsole van Componenten. |
| [Fouten opsporen in lokale QuickStart van AEM SDK met behulp van logbestanden](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/logs.html) | Videozelfstudie | Meer informatie over foutopsporing in AEM als lokale quickstart van een Cloud Service SDK met de Bundles-webconsole. |
| [Foutopsporing op afstand van de AEM als lokale quickstart van de Cloud Service SDK](https://docs.adobe.com/content/help/en/experience-manager-learn/cloud-service/debugging/debugging-aem-sdk-local-quickstart/remote-debugging.html) | Videozelfstudie | Leer over verre het zuiveren van Java van uw winde, die u toestaat om door levende code uitvoering in AEM te stappen om de nauwkeurige uitvoeringsstroom te begrijpen. |
| [Slimme tag instellen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/metadata/smart-tags-technical-video-setup.html) | Videozelfstudie | Stapsgewijze instructies voor de integratie van Adobe Experience Manager (AEM) met de Smart Content Service met behulp van Adobe I/O. |
| [Batch genereren van documenten](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/interactive-communications/batch-generation-interactive-communications.html) | Artikel | Leer over het gebruiken van de Band API om veelvoudige interactieve mededelingen van een malplaatje te produceren. |
| [Kanaaldocument afdrukken maken in AEM Forms](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/ic-print-channel-tutorial/introduction.html) | Artikel | Leer de stappen die nodig zijn om een interactieve communicatie voor het afdrukkanaal te maken. |
| [Adobe-elementkoppeling openen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/launch-adobe-asset-link.html) | Videozelfstudie | Leer meer over het benaderen van inhoud die is opgeslagen in Adobe Experience Manager Assets (AEM Assets) zonder de Creative Cloud-bureaubladtoepassingen te verlaten waarmee u vertrouwd bent. |
| [Overzicht van het deelvenster Koppeling voor elementen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/panel-overview.html) | Videozelfstudie | Met Adobe Asset Link kunnen creatieve gebruikers door middelen bladeren, zoeken, uitchecken en inchecken die in AEM Assets zijn opgeslagen via het deelvenster in de app in InDesign, Photoshop en Illustrator. Maak kennis met de gebruikersinterface en mogelijkheden van het deelvenster Adobe Asset Link. |
| [Zoeken in middelen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/asset-search.html) | Videozelfstudie | Creatieve gebruikers kunnen zoeken naar elementen die in AEM Assets zijn opgeslagen met behulp van trefwoorden of een zoekopdracht uitvoeren onder een bepaalde locatie. |
| [Bestandsversie en opmerkingen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/file-versioning-and-comments.html) | Videozelfstudie | Via het deelvenster Koppeling met Adobe-middelen hebt u vanuit het deelvenster toegang tot bestandsgegevens voor elementen in AEM Assets, zoals miniaturen, standaardmetagegevens en versies. |
| [Uitchecken van inchecken](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/check-in-check-out.html) | Videozelfstudie | Met Adobe Asset kunt u AEM Assets rechtstreeks uitchecken vanuit de creatieve app waarmee u werkt. U kunt dan direct beginnen met het maken van bewerkingen. |
| [Alleen voor uitvoering bij plaatsing voor AEM Assets](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/for-placement-only.html) | Videozelfstudie | Ontdek hoe u een FPO-uitvoering (For Placement Only) voor AEM-elementen kunt maken en gebruiken. |
| [Kopie plaatsen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/place-copy.html) | Videozelfstudie | Leer hoe u elementen van AEM Assets kunt gebruiken met de bewerking Kopie plaatsen. |
| [Downloaden en uploaden](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/download-and-upload.html) | Videozelfstudie | Leer hoe u elementbestanden kunt downloaden van en uploaden naar AEM Assets via het deelvenster Koppeling voor middelen. |
| [Bestanden en verzamelingen](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/adobe-asset-link/files-and-collections.html) | Videozelfstudie | Leer hoe u bestanden en verzamelingen van AEM Assets snel en gemakkelijk kunt openen vanuit het deelvenster Koppeling voor bedrijfsmiddelen. |
| [Downloaden](https://docs.adobe.com/content/help/en/experience-manager-learn/assets/sharing/download.html) | Videozelfstudie | Leer hoe u elementen en de bijbehorende uitvoeringen naar uw lokale computer downloadt voor gebruik en delen. |

### Aanvullende bronnen

* [AEM als Cloud Service](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-5.html)
* [AEM 6.4 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-4.html)
* [AEM 6.3 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-3.html)
* [AEM 6.2 Informatie en ondersteuning Support-startpagina](https://helpx.adobe.com/nl/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://helpx.adobe.com/nl/experience-manager/cloud-manager/user-guide.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/nl-NL/dynamic-media-classic/using/home.html)
* [Releaseopmerkingen bij Dynamic Media](https://docs.adobe.com/content/help/en/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Releaseopmerkingen bij Livefyre](https://docs.adobe.com/content/help/en/livefyre/using/release-notes/c-rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Nieuwe productreleases

[Adobe Campaign Classic versie](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) 20.2 bevat:

* _Ondersteuning voor Emoticon_ - _Azure Synapse FDA Connector_ - _Nieuwe privacyregels_
* Configuratiescherm: [Actieve profielcontrole](https://docs.adobe.com/content/help/en/control-panel/using/performance-monitoring/active-profiles-monitoring.html)

### Nieuwe cursussen en zelfstudies voor campagnes

| Inhoud | Inhoudstype | Beschrijving |
| -----------| ---------- | ---------- |  
| [Aan de slag met Adobe Campaign Standard for Business Users](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Cursus | Leer hoe te om de interface te navigeren, met leveringen te werken, en ontvankelijke gegevens tot stand te brengen en te beheren. |
| [De Adobe Campaign-client installeren en instellen](https://experienceleague.adobe.com/?recommended=Campaign-U-1-2020.1.standard) | Video | Leer hoe u de Adobe Campaign Client Console downloadt en installeert, uw verbindingen maakt en beheert met meerdere omgevingen en de toegang tot de Adobe Campaign Client Console verifieert |

### Help-bronnen

* Adobe Campaign Standard: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/campaign-standard-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/nl-NL/campaign-standard-learn/tutorials/overview.html) - [Releaseplanning](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/campaign-classic-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/documentation-updates.html)
* Adobe Campaign - Configuratiescherm: [Documentatie](https://docs.adobe.com/content/help/nl-NL/control-panel/using/control-panel-home.html) - [Releaseopmerkingen](https://docs.adobe.com/content/help/nl-NL/control-panel/using/release-notes.html) - Hoe kan ik-video&#39;s voor [Campaign Standard](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/control-panel-overview.html) / [Campaign Classic](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/control-panel-overview.html)

## ![Pictogram](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Updated **June 3, 2020**

* [Nieuwe functies in Advertising Cloud DSP](#adcloud-dsp)
* [Nieuwe functies in Advertising Cloud Search](#adcloud-search)

### Nieuwe functies in Advertising Cloud DSP {#adcloud-dsp}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaign] Home | (Release van 3 juni) Er zijn nieuwe maatstaven voor het afstemmen op campagnemeniveau beschikbaar op basis van het beschikbare campagnebudget en de verstreken tijd. |
| Placement Forecasting | (Release 3 juni) Voor CTV- en videokoppelingen met optimalisatie op plaatsingsniveau bevat de plaatsingsinstellingen nu een voorspelling voor meerdere advertentiedengten (15 sec en 30 sec). Zij omvatten ook prognoses voor zowel de VAST- als de VPAID-inventaris. |
| CPA/ROAS optimaliseren | (release van 20 mei) Campagnebeheerders hoeven geen nieuwe plaatsingen in pakketten meer te beperken om overbesteding van de begroting te voorkomen. Plaatsen krijgen nu een dynamische begrotingstoewijzing op basis van hun CPM- of CPA/ROAS-prestaties. |

### Nieuwe functies in [!UICONTROL Advertising Cloud Search] {#adcloud-search}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Campaigns] | In Microsoft Advertising (voorheen Bing Ads) worden de gemiddelde positiewaarden na 30 september 2020 afgekeurd. Ter voorbereiding hiervan, vanaf 11 juli, zullen op positie-gebaseerde beperkingen worden genegeerd en op positie-gebaseerde voorwaarden in om het even welk type van beperking zullen ook genegeerd worden. |
| [!UICONTROL Advertising Insights] | (Release van 13 juni) De volgende inzichten zijn verwijderd:<br/><br/><ul><li>Publiek Target Performance (de nieuwere versie)</li><li>Historische prestaties (de nieuwere versie)</li><li>Type overeenkomst (de nieuwere versie)</li><li>Settings Audit (de nieuwere versie)</li><li>Vooraf geplaatst portfolio (verouderd)</li></ul><br/>De resterende inzichten zijn oudere versies en het label _Verouderd_ is uit de namen verwijderd. Bovendien zijn de modi Live/Bewerken verwijderd. |

## ![Pictogram](/assets/magento.png) [!DNL Magento] {#magento}

Voor de versienota&#39;s van Magento raadpleegt u:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Magento Open Source 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo Engage] {#marketo}

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
