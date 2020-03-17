---
title: Opmerkingen bij de release Adobe Experience Cloud
description: Opmerkingen bij de release Sjabloon voor Experience Cloud
doc-type: release notes
last-update: March 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 01f2d4ae03be92da8d5d6feb1900cd4901a1b142

---


# Opmerkingen bij de release Adobe Experience Cloud - maart 2020

![Banner](/assets/experience-cloud-banner-3.png)

Nieuwe functies en oplossingen in het deelvenster [!DNL Adobe Experience Cloud].

>[!IMPORTANT]
>Deze pagina bevat inhoud die vóór de release beschikbaar is en kan worden gewijzigd voordat de geplande release wordt uitgebracht.

>[!NOTE]
>Meld u aan voor de [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases. Nieuwe informatie die na de release wordt gepubliceerd, wordt gemarkeerd met de publicatiedatum.

**Releasedatum: maart 2020**

Laatste update: 11 maart 2020

* [Adobe-systeemstatus](#status)
* [Ervaar de interface van de Wolk en de kerndiensten](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) - Releasedatum: 12 **maart 2020**
* [Auditiebeheer](#aam)
* [Experience Manager](#aem)
* [!DNL Campaign](#ac)
* [!DNL Target](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html) (koppelingen naar Help bij oplossing)
* [!DNL Advertising Cloud](#adcloud)
* [!DNL Magento](#magento)
* [!DNL Marketo](#marketo)
* [!DNL Primetime](https://helpx.adobe.com/primetime/user-guide.html) (koppelingen naar Help bij oplossing)
* [Nieuwe documentatie en zelfstudies](#selfhelp)

Op zoek naar hulp thuis? Raadpleeg de documentatie bij [Adobe Experience Cloud](https://docs.adobe.com/content/help/en/experience-cloud/user-guides/home.html).

(De specifieke data van de productversie kunnen variëren.)

## ![Pictogram](/assets/adobe.png) Adobe-systeemstatus {#status}

[!UICONTROL De Status] van het Systeem van Adobe verstrekt gedetailleerde informatie, statusupdates, en e-mailberichten over de producten van de wolk van Adobe en de gebeurtenissen van de dienststroomonderbreking, en van het onderhoud. Ga naar [status.adobe.com](https://status.adobe.com/).

**Nieuwe functies**

* Met uw Adobe-id kunt u zich met meer granulariteit abonneren op gebeurtenismeldingen, tot aan het productaanbod en het invoegniveau. Kies voor deze nieuwe mogelijkheid in producten van de Experience Cloud, waar het proces voor zelfinschrijving subaanbiedingen weergeeft voor de producten en services waarop u zich wilt abonneren. Deze verbetering zou het aantal meldingen dat u ontvangt aanzienlijk moeten verminderen en de meldingen relevanter moeten maken voor de producten en functies die u gebruikt.  Ga aan de slag op [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nieuwe en verbeterde functies die vandaag beschikbaar zijn**

| Functie | Beschrijving |
| -----------| ---------- |
| Persoonlijk abonnement op subaanbiedingen van producten | <ul><li>Zelfinschrijving per product of invoegtoepassingen voor producten uit de Experience Cloud.</li><li>Ontvangen gebeurtenismeldingen zijn relevant voor uw voorkeuren voor producten en productaanbiedingen.</li></ul> |
| Persoonlijke ervaring op basis van gebruikersvoorkeuren | <ul><li>Tijdzonevoorkeur gebaseerd op browser het plaatsen wordt gebruikt in e-mailberichten.</li><li>E-mailbevestiging verzonden bij abonnement/abonnement met alle geselecteerde voorkeuren.</li></ul> |
| Betere levering van gebeurtenisberichten | <ul><li>Gebeurtenisgeschiedenis gesorteerd op basis van chronologische gebeurtenisupdates.</li><li>Tijdstempel van gebeurtenisresolutie toegevoegd aan belangrijke/kleine afgesloten problemen.</li></ul> |

## ![Icon](/assets/experience-cloud.png) Experience Cloud-interface en kernservices {#ecloud}

Nieuwe functies en oplossingen in de Experience Cloud-interface, waaronder beheer en kernservices (klantkenmerken, publiek, triggers, cookies, enzovoort).

| Functie | Releasedatum | Beschrijving |
| ----|----|---- |
| Beheer - Gebruikersgegevens weergeven | 26 februari 2020 | Beheerders kunnen een sorteerbare en filterbare lijst met alle Experience Cloud-gebruikers en hun gegevens weergeven in het nieuwe Admin Tool. De details van de gebruiker omvatten de het producttoegang van een gebruiker, rollen, en laatste betreden informatie. Zie [Experience Cloud Admin Tool](https://docs.adobe.com/content/help/en/core-services/interface/manage-users-and-products/admin-tool-experience-cloud.html) voor meer informatie. |

### Geïntegreerd productdomein

Adobe werkt de domein- en interfaceheader bij om uw ervaring in alle Experience Cloud-toepassingen te verenigen en te verbeteren. Deze verbeteringen zijn ontworpen om uw ervaring op kleine maar belangrijke manieren te vereenvoudigen. Deze verbeteringen hebben geen invloed op uw huidige workflows.

Updates zijn:

* Nieuwe oplossing-URL&#39;s: `experience.adobe.com/<application name>`:
   * Uiteindelijk zullen alle producten dit patroon URL goedkeuren. Nieuwe URL&#39;s worden de hele maand van kracht.
   * Browserondersteuning: Tot de ondersteunde browsers behoren [!DNL Microsoft Edge], [!DNL Google Chrome], [!DNL Firefox], [!DNL Safari]en [!DNL Opera] (de nieuwste versies). **Opmerking:** Hoewel de interface Experience Cloud deze browsers ondersteunt, wordt mogelijk niet elke browser ondersteund door afzonderlijke oplossingen. ( [Analytics](https://docs.adobe.com/content/help/en/analytics/admin/sys-reqs.html) biedt bijvoorbeeld geen ondersteuning [!DNL Opera]en [Target](https://docs.adobe.com/help/en/target/using/implement-target/before-implement/supported-browsers.html) biedt geen ondersteuning voor [!DNL Safari].)
   * ([!DNL Safari] Alleen) De domeinwijziging kan problemen met cookies veroorzaken in [!DNL Safari]. Als u de selectie van _Zoeken_ tussen verschillende sites in de [!DNL Safari] privacyvoorkeuren opheft, worden cookies in verschillende domeinen (en alle ervaringen die op andere sites worden gegenereerd) ingeschakeld en werkt Experience Cloud op dit nieuwe domein.
* Eenvoudiger overschakelen tussen uw organisaties of op een andere toepassing.
* Verbeterde producthulp: De [!UICONTROL Experience League] is geïntegreerd in het product, zodat een zoekopdracht in de Help ook resultaten bevat van gemeenschapsforums en video-inhoud. Deze wijziging vereenvoudigt de toegang tot meer inhoud en helpt u optimaal te profiteren van Experience Cloud. Klik bovendien op **[!UICONTROL Help]** > **[!UICONTROL Feedback]** om problemen te melden of uw ideeën te delen met Adobe.
* Verbeterde meldingen: Het vervolgkeuzemenu [!UICONTROL Meldingen] heeft nu twee tabbladen: een voor uw eigen productmeldingen en een voor algemene productaankondigingen.

**Opmerking:** De pagina [!UICONTROL Feed] is in januari 2020 vervangen. Zoek naar een bericht over afgekeurde producten.

Raadpleeg [Experience Cloud](https://docs.adobe.com/content/help/en/core-services/interface/experience-cloud.html) Help voor productdocumentatie.

## ![Icon](/assets/platform.png) Experience Platform {#platform}

Opmerkingen bij de release voor het [!UICONTROL Experience Platform,] [!UICONTROL Experience Platform Launch,] [!UICONTROL Identity Service,] Journey Orchestration, Mobile Services en beveiligingsbulletins.

* [Opmerkingen bij de release Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Introductie van Experience Platform](#launch)
* [Reisorkest](#journey)
* [Mobiele services en mobiele SDK&#39;s](#mobile)
* [Beveiligingsbulletins en -adviezen](https://helpx.adobe.com/security.html) (alle Adobe-producten)

### Introductie van Experience Platform {#launch}

Zie [Experience Platform Launch](https://docs.adobe.com/content/help/en/launch/using/intro/release-notes/current.html) voor opmerkingen over releases en productdocumentatie.

### Reisorkest {#journey}

Met behulp van het Adobe Experience Platform kunt u individuele reizen van klanten op schaal en via verschillende ervaringskanalen ordenen door op intelligente wijze in real-time te anticiperen op de behoeften van elk individu, waar zijn reis deze ook brengt.

Release Q1 is gepubliceerd. [Meer informatie](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html#q1-release---march-2020)

#### Aanvullende middelen voor Reisorchestratie

[Documentatie](https://docs.adobe.com/content/help/en/journeys/using/journey-orchestration-home.html) - [Release-aantekeningen](https://docs.adobe.com/content/help/en/journeys/using/release-notes/release-notes.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/en/platform-learn/tutorials/journey-orchestration/introduction.html)

### Mobiele services en mobiele SDK&#39;s {#mobile}

**iOS v4.19.1**

* Algemeen - Resolved een potentiële neerstorting wanneer de [!UICONTROL Swift] aantallen in contextgegevens voor spoorvraag inbegrepen zijn.
* [!DNL Target] - [!DNL Target] Sessie-id wordt nu toegevoegd als een parameter voor contextgegevens `a.target.sessionId` in de interne hit [!UICONTROL Analytics-for-Target] die naar Adobe Analytics wordt verzonden.

**Android v4.18.1**

* [!DNL Target] - De sessie-id wordt nu toegevoegd als een contextgegevensparameter &quot;a.target.sessionId&quot; in de interne [!DNL Target] actie Analytics-for-Target  die naar Adobe Analytics wordt verzonden.

## ![Pictogram](/assets/analytics.png) [!DNL Analytics]{#analytics}

Releasedatum: 12 **maart 2020**

Nieuwe functies en oplossingen in Adobe Analytics:

* [Nieuwe functies, verbeteringen en correcties in Adobe Analytics](#aa-features)
* [Belangrijke kennisgevingen voor analysebeheerders](#aa-notices)
* [AppMeasurement](#appm)

Raadpleeg de Help Home [voor](https://docs.adobe.com/content/help/en/analytics/landing/home.html)Adobe Analytics voor productdocumentatie.

### Nieuwe functies, verbeteringen en correcties in Adobe Analytics {#aa-features}

* **Meerdere rapportsuites in de[!UICONTROL analysewerkruimte ]**: U kunt gegevens van veelvoudige rapportreeksen in één enkel project van de Werkruimte[!UICONTROL van de]Analyse nu brengen om in zij aan zij panelen te bekijken.[Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/multiple-report-suites.html)
* **Geniet van optimalisatie** voor publiek in cloud: Met deze functie kunt u binnen 8 uur segmenten publiceren naar de Experience Cloud (in plaats van de voorgaande 48-uurs verwerkingstijd). [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-publish.html)
* **Analyse van werkruimte - sjabloon** voor zelfstudie: Dit nieuwe standaardmalplaatje begeleidt u door gemeenschappelijke terminologie en stappen voor het bouwen van uw eerste analyse in Werkruimte. Het is beschikbaar als standaardmalplaatje in [!UICONTROL Nieuw Project] modaal en vervangt het steekproefproject dat vandaag voor nieuwe gebruikers bestaat die geen andere projecten in hun lijst hebben.

#### Oplossingen

* Probleem opgelost in [!UICONTROL Rapporten en Analyses] dat het downloaden van `.xls` rapporten verhinderde. Deze kwestie betrof klanten die andere valuta dan de Amerikaanse dollar en de euro gebruikten. (AN-206541, AN-204008)
* De introductie van een nieuwe shell verholpen verschillende klantproblemen met betrekking tot het overschakelen van Experience Cloud-organisaties.(AN-200844, AN-186920)
* Probleem verholpen waarbij een uitsplitsing naar de _niet-gespecificeerde_ lijnpost (of sommige andere posten in de rapportagelijn) zonder _Niet-gespecificeerd (Geen)_ op te nemen in de zoekfilters van de uitsplitsing geen resultaten in de uitsplitsing zou opleveren.
* Probleem verholpen die zich voordeed bij het gebruik van een geclassificeerde dimensie, en de metrische totalen bij het in- of uitgaan niet overeenkwamen met het totaal van de posten in een uitsplitsing.
* Probleem verholpen waarbij de eerste aanraak- en laatste aanraakmodellen in Attribution IQ de creditering voor sommige regelitems in sommige niet-lege dimensies niet correct berekenden.
* Probleem verholpen waarbij het opsplitsen van een datumdimensie naar een andere datumdimensie onjuiste resultaten zou opleveren.
* Probleem verholpen waarbij de meetgegevens voor in- of uitstappen soms onjuist zouden worden geteld wanneer deze werden toegepast op &quot;Niet gespecificeerd&quot; in een rapport met een gerubriceerde dimensie.

### Belangrijke kennisgevingen voor [!DNL Analytics] beheerders {#aa-notices}

| Kennisgeving | Datum toegevoegd of bijgewerkt | Beschrijving |
| -----------| ---------- | ---------- |
| EOL van instelling voor **[!UICONTROL conversieniveau]** | 3 maart 2020 | De instelling voor het niet-functionerende [conversieniveau](https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Admin Tools]>[!UICONTROL Report Suites]>[!UICONTROL General Account Settings]** wordt op 12 maart 2020 verwijderd uit de gebruikersinterface. |
| EOL van **[!UICONTROL dashboardarchief]** | 3 maart 2020 | De instelling **[!UICONTROL Archief]** weergeven onder **[!UICONTROL Dashboards]** beheren in [!UICONTROL Reports &amp; Analytics] is vanaf 12 maart 2020 niet meer beschikbaar. |
| Einde van ondersteuning voor TLS 1.1 | 3 oktober 2019 | Op 31 maart 2020 verwijdert Adobe Analytics de ondersteuning voor TLS 1.1. Deze verandering maakt deel uit van onze voortdurende inspanningen om de hoogste veiligheidsnormen te handhaven en de veiligheid van klantengegevens te bevorderen. |
| Nieuw Adobe Analytics-domein | 18 dec. 2019 | Op 16 januari 2020 is Adobe Analytics naar een nieuw domein gegaan - `https://experience.adobe.com/analytics.`<br>**Opmerking:**Deze wijziging geldt voor alle gebruikers die toegang hebben tot Analytics met hun Adobe-id of Enterprise-id.<ul><li>De domeinwijziging kan tijdens het laden van Analytics in Safari cookies veroorzaken. Als u de selectie van _Zoeken_ tussen verschillende sites voorkomen in de [!DNL Safari] privacyvoorkeuren opheft, worden cookies in verschillende domeinen ingeschakeld (en alle ervaringen die op andere sites beschikbaar zijn) en kan Analytics werken op dit nieuwe Adobe Experience Cloud-domein. U kunt andere browsers zonder problemen gebruiken, omdat dit alleen voor [!DNL Safari] gebruikers geldt.</li><li>De domeinwijziging kan ertoe leiden dat [!UICONTROL Activiteitenkaart] niet langer werkt voor bepaalde klanten [in specifieke gevallen](https://docs.adobe.com/content/help/en/analytics/analyze/activity-map/activity-map.html).</li></ul> |
| Einde van levensduur - Verouderde API&#39;s voor analyse | 9 januari 2020 | In november 2020, zullen de volgende Analytics Legacy API diensten hun eind-van-leven bereiken en zullen sluiten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor analyse</li><li>1.4 API&#39;s voor SOAP-analyse</li><li>Oudere OAuth-verificatie (OAuth en JWT)</li></ul>We hebben een [verouderde API EOL-veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) beschikbaar gesteld die u helpen uw vragen te beantwoorden en aanwijzingen te geven voor het verdere verloop. API-integratie die van deze services gebruik maakt, kan migreren naar de [1.4 Analytics REST API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [2.0 Analytics API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Legacy OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount, dat kan worden gebruikt voor toegang tot de API&#39;s voor 1.4 Analytics en 2.0 Analytics. |
| San Jose FTP Broker Ending voor Londen en Singapore | juli 2020 | Voor klanten in Londen en Singapore zullen we niet langer de tussenhandel in gegevens tussen Londen of Singapore en het San Jose datacenter [ftp.omniture.com](ftp://ftp.omniture.com/)steunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Gebruik voor Singapore [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |

### [!DNL AppMeasurement] {#appm}

Zie [AppMeasurement voor Javascript-releaseopmerkingen](https://docs.adobe.com/content/help/en/analytics/implementation/appmeasurement-updates.html). Versie 2.20.0 is uitgebracht op 5 maart 2020.

## ![Pictogrambeheer](/assets/audience-manager.png){#aam}

Nieuwe functies en updates voor Audience Manager:

### Oplossingen en verbeteringen {#aam-fixes-and-improvements}

* Probleem verholpen waarbij klanten de segmentnaam niet konden bijwerken vanwege een ontbrekende RBAC-machtiging [!UICONTROL VIEW_ALL_DESTINATIONS]. De toestemming [!UICONTROL VIEW_ALL_DESTINATIONS] zou niet moeten worden vereist om een segment bij te werken. Voor meer informatie over toestemmingen RBAC, zie [Beleid (Controles RBAC)](https://docs.adobe.com/help/en/audience-manager/user-guide/features/administration/administration-overview.html#wild-card-permissions). (AM-52760)
* Oplossing voor een bug in [Data Explorer](https://docs.adobe.com/help/en/audience-manager/user-guide/features/data-explorer/data-explorer-overview.html) waarbij sommige klanten geen inhoud konden zien in de basisinformatiesectie en operatoren in de expressiebouwer bij het maken van kenmerken die zijn gebaseerd op [!UICONTROL Data Explorer] -signalen. (AM-53130)
* Probleem verholpen waarbij sommige klanten de interface [!UICONTROL Audience Marketplace] niet konden laden. (AM-52070)
* Probleem verholpen in de [!UICONTROL Segmenten-API] , waarbij de interface vanwege bepaalde segmenten zonder beschrijving vastliep wanneer gebruikers probeerden toegang te krijgen tot die segmenten en gebruikers buiten die pagina moesten navigeren. (AM-53071)
* Meerdere toegankelijkheidsverbeteringen door de interface. (AAM-48952, AAM-48969, AAM-48979, AAM-48993, AAM-49048, AAM-49057, AAM-49058, AAM-493) 92)

## ![Icon](/assets/aem.png) Experience Manager {#aem}

Nieuwe functies, oplossingen en updates in Adobe Experience Manager (AEM). Adobe raadt klanten met on-premise implementaties aan de nieuwste patches te implementeren om een hogere stabiliteit, beveiliging en prestaties te garanderen.

### Productupdates

* **AEM 6.5.4.0** AEM 6.5, Service Pack 4.0 (6.5.4.0 die 5 Maart, 2020) wordt vrijgegeven is een belangrijke update die nieuwe eigenschappen, zeer belangrijke klantenverhogingen, betere prestaties, stabiliteit, en veiligheid omvat, sinds de algemene beschikbaarheid van AEM 6.5, April 2019.
   * [Nieuw in Adobe Experience Manager 6.5, Service Pack 4](https://docs.adobe.com/content/help/en/experience-manager-65/release-notes/service-pack/new-features-latest-service-pack.html)
   * [Opmerkingen bij de release](https://helpx.adobe.com/experience-manager/6-5/release-notes/sp-release-notes.html)
   * [Te leveren items voor release van AEM Forms](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.4.8.0**

   AEM 6.4, Service Pack 8.0 (6.4.8.0 vrijgegeven 5 maart 2020) is een belangrijke update die zeer belangrijke klantenmoeilijke situaties omvat die sinds de algemene beschikbaarheid van AEM 6.4, April 2018 worden vrijgegeven.
   * [Opmerkingen bij de release](https://helpx.adobe.com/experience-manager/6-4/release-notes/sp-release-notes.html)
   * [AEM Forms GVB-releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM 6.3.3.8**

   AEM 6.3, Service Pack 3, Cumulative Fix Pack 8 (6.3.3.8 uitgebracht 5 maart 2019) is een belangrijke update die zeer belangrijke klantenmoeilijke situaties omvat die sinds de algemene beschikbaarheid van AEM 6.3, April 2017 worden vrijgegeven.
   * [Opmerkingen bij de release](https://helpx.adobe.com/experience-manager/release-notes--aem-6-3-cumulative-fix-pack.html)
   * [AEM Forms GVB-releases](https://helpx.adobe.com/aem-forms/kb/aem-forms-releases.html)

* **AEM Assets Brand Portal**

   AEM Assets Brand Portal 6.4, Service Pack 6 (6.4.6 uitgebracht op 5 maart 2020) wijzigt de manier waarop AEM Assets wordt geconfigureerd met [!UICONTROL Brand Portal.] Daarnaast bevat de release andere verbeteringen en foutoplossingen.
   * [Opmerkingen bij de release](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html)

### Zelfhulp

* **AEM als cloudservice - Op rollen gebaseerde machtigingen**

   Cloud Manager heeft vooraf geconfigureerde rollen met de juiste machtigingen. Elk van de rollen heeft specifieke toestemmingen, pre-gevormde taken, of toestemmingen, verbonden aan elke rol. In het Help-onderwerp Op [rol gebaseerde machtigingen](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/onboarding/what-is-required/role-based-permissions.html) worden de beschikbare functies en de rollen aangegeven die ze kunnen uitvoeren.

* **AEM als cloudservice - Dispatcher**

   De secties [Dispatcher en CDN](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#dispatcher-cdn) en [Expliciet de geheim voorgeheugen van de Verzender](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/implementing/dispatcher/overview.html#explicit-invalidation) werden bijgewerkt om de opties te verduidelijken die beschikbaar zijn en hoe zij werken.

* **AEM-middelen configureren met Brand Portal**

   AEM Assets wordt nu geconfigureerd met [!UICONTROL Brand Portal] via Adobe I/O, dat een IMS token aanschaft voor toestemming van de Perkortaalgebruiker. Eerder, werd het gevormd in Klassieke interface door middel van de [!UICONTROL Oudere Gateway OAuth.]
Zie AEM-middelen [configureren met Brand Portal](https://docs.adobe.com/content/help/en/experience-manager-brand-portal/using/publish/configure-aem-assets-with-brand-portal.html).

* **AEM als cloudservice - Smart Crop in Dynamic Media**

   Een nieuwe optie is beschikbaar in AEM als de Dienst van de Wolk wanneer u met Slim Uitsnijden in de Dynamische component van Media werkt:

   **Hoogte-breedteverhouding** inschakelen - Selecteer deze optie als u wilt dat Dynamic Media een slimme uitsnijdvertoning kiest die het beste overeenkomt met de hoogte-breedteverhouding van de oorspronkelijke afbeelding.
Zie [Wanneer u werkt met Slim uitsnijden](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/assets/dynamicmedia/adding-dynamic-media-assets-to-pages.html#when-working-with-smart-crop).

### Gemeenschap

* **Webinars van AEM Skill Builder**

   * AEM-sites: vanaf 17 maart 2020 worden de bouwstenen van het ontwerpen van inhoud en de fundamentele concepten en bewerkingen van AEM-sites geleerd. [Nu](https://aemskillbuilder-sites.experienceleague.adobeevents.com/register)registreren.
   * AEM Assets - Vanaf 19 maart 2020 wordt uw expertise op het gebied van beheer van digitale middelen geoptimaliseerd, plus de basisbeginselen van het merkportaal, [!UICONTROL Dynamic Media,] [!UICONTROL Asset Link,] enzovoort. [Nu](https://aemskillbuilder-assets.experienceleague.adobeevents.com/register)registreren.

### Aanvullende bronnen

* [AEM als cloudservice](https://docs.adobe.com/content/help/en/experience-manager-cloud-service/landing/home.html)
* [AEM 6.5 - Introductie van &amp; ondersteuning](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [AEM 6.4 Introductie van leer &amp; ondersteuning](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [AEM 6.3 Introductie van de leer &amp; Steun](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [AEM 6.2 Introductiepagina voor informatie en ondersteuning](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Gebruikershandleiding voor Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help Home](https://docs.adobe.com/content/help/en/dynamic-media-classic/using/home.html)
* [Opmerkingen bij de release van dynamische media](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Opmerkingen bij de release Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Campaign]{#ac}

De Campagne van Adobe verstrekt een intuïtieve, geautomatiseerde manier om één-op-één berichten over online en off-line marketing kanalen te leveren. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Campaign Classic

* [Campagne Classic 19.1.4-update](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Aanvullende bronnen

* Adobe Campagnestandaard: [Documentatie](https://helpx.adobe.com/support/campaign/standard.html) - de Nota&#39;s [van de](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-notes.html) Versie - [hoe te video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) &#39;s - de Planning van de [Versie](https://helpx.adobe.com/campaign/kb/acs-release-planning.html)
* Adobe Campaign Classic: [Documentatie](https://helpx.adobe.com/support/campaign/classic.html) - [Release-aantekeningen](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Hoe kan ik-video&#39;s](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)
* Configuratiescherm Adobe-campagne: [Documentatie](https://docs.adobe.com/content/help/en/control-panel/using/control-panel-home.html) - Opmerkingen bij de [release](https://docs.adobe.com/content/help/en/control-panel/using/release-notes.html)

## ![Icon](/assets/advertising-cloud.png) Advertising Cloud {#adcloud}

Bijgewerkt op 10 februari 2020, voor release 8 februari:

| Weergave | Functie |
|------|---------|
| [!UICONTROL Portfolio&#39;s] | U kunt nu campagnes van het Netwerk van de Vertoning van Japan (YDN) aan portefeuilles toevoegen om de campagnebegrotingen en ad groep-vlakke biedingen te optimaliseren. [!DNL Yahoo!] Hetzelfde bod geldt voor alle advertenties in een advertentiegroep. De gegevens voor de campagnes van het Netwerk van de Vertoning van Japan zijn inbegrepen in de simulaties voor de portefeuille. |
| [!UICONTROL Zoeken] > [!UICONTROL Opsommingstekens] | U kunt nu met behulp van bulksbladen Google responsieve zoekadvertenties (RSA&#39;s) maken, bewerken en verwijderen. Eerder was de steun beschikbaar slechts door de standaardinterface van het campagnebeheer bij **[!UICONTROL Onderzoek]** > **[!UICONTROL Campagnes]** |
| [!UICONTROL Zoeken] > [!UICONTROL Campagnes, Rapporten] | De belangrijkste cijfers voor Google Ads `Impr. (Abs. Top) %` en `Impr. (Top) %` zijn nu beschikbaar in alle basisrapporten en campagnebeheerweergaven op entiteitniveau, behalve in die voor winkelproductgroepen, in de rapporten [!UICONTROL Campagne Daily Impression Share] en [!UICONTROL Keyword Daily Impression Share] , en in de labels en beperkingsweergaven. |

## ![Pictogram](/assets/magento.png) [!DNL Magento]{#magento}

Voor de versienota&#39;s van Magento, zie:

* [Magento Commerce 2.3.4](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-commerce.html)
* [Open Bron 2.3.4 van Magento](https://devdocs.magento.com/guides/v2.3/release-notes/release-notes-2-3-4-open-source.html)

## ![Pictogram](/assets/marketo.png) [!DNL Marketo]{#marketo}

[!DNL Marketo Engage] is een volledige oplossing voor het beheer van leads en B2B-marketers die de ervaringen van klanten willen transformeren door in elke fase van complexe inkoopritten te gaan werken.

### Core Marketo Engineering-updates

Releasedatum: 21 februari 2020

* **Microsoft Dynamics _Change Owner in Microsoft_Flow Action:** Wijzig een lead of contactpersoon rechtstreeks vanuit Marketo Engage.
* **Verbeteringen aan API-aanroepen:**
   * Gebruikersbeheer-API&#39;s
   * Aangepast objectschema-API&#39;s
   * Regels voor omleiding van bestemmingspagina&#39;s
* **Caching van formulierdescriptor:** Verbeteringen in bestemmingspagina&#39;s en -formulieren.

Zie de [!DNL Marketo] opmerkingen bij de release van [februari 2020](https://docs.marketo.com/display/public/DOCS/Release+Notes%3A+Feb+%2720) voor meer informatie.

### Opkomende functies

De volgende functies worden gedurende het hele kwartaal beschikbaar gesteld:

| Functie | Beschrijving |
|------|---------|
| [!DNL Bizible] | <ul><li>Nieuwe op een account gebaseerde segmentatie</li><li>Specifieke dashboardfilters opslaan</li><li>Bizible dashboards exporteren als PDF&#39;s</li></ul> |
| Verkoop Connect | Updates/verbeteringen voor Venster- en Command Center samenstellen |

### Aankondigingen

**Marketo Engage Success Center:** Starten in februari 2020. Het Succescentrum is een centrum van de hulp binnen-product dat u toelaat om de Docs van het Product en de Gemeenschap te zoeken, te lanceren hoe te gidsen, toegang tot adoptie inhoud, en meer. Opmerking: Deze functie wordt gestart als een bètaversie in ANZ en wordt later in het kwartaal uitgezonden naar Noord-Amerika.

### Afwijkingen

* **Parameter &quot;_methode&quot; van de element-API:** Na September 2020, zullen de Eindpunten van activa API niet meer &quot;_method&quot;goedkeuren om de Parameters van de Vraag in een POST lichaam over te gaan om de lengtebeperkingen van URI te omzeilen.
* **Ondersteuning voor Internet Explorer-veroudering:** Vanaf de release van 31 juli 2020 wordt de gebruikersinterface Marketo Engage niet meer ondersteund in Internet Explorer.

Voor cumulatieve en historische versienota&#39;s, zie [Marketo versie nota](https://docs.marketo.com/x/CgA6Ag).

## ![Pictogram](/assets/experience-cloud.png) Nieuwe documentatie en zelfstudies {#selfhelp}

Nieuwe en recente zelfhulpartikelen en video&#39;s. <!--`https://jira.corp.adobe.com/secure/Dashboard.jspa?selectPageId=60327`-->

| Oplossing | Inhoud | Beschrijving |
|----------| -----------| ---------- |  
| [!UICONTROL AEM Commerce] | Video - Meerdere categorieën en productpagina&#39;s [maken](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/04-style-cif-component.md) | Leer hoe te om een minimaal CIF-project van de Manager van de Ervaring van Adobe (AEM) tot stand te brengen als uitgangspunt voor klantenprojecten gebruikend de Componenten van de Kern CIF. Pas thema en CSS het stileren op componenten toe en inspecteer een nieuw project AEM CIF, dat door archetype wordt geproduceerd. Leer ook hoe CSS en JavaScript die door de belangrijkste componenten van CIF worden gebruikt worden georganiseerd. |
| [!UICONTROL AEM-formulieren] | Artikel - [Verifiëren voor AEM-auteur met OKTA](https://docs.adobe.com/content/help/en/experience-manager-learn/forms/single-sign-on-with-okta.html) | Leer hoe u uw app configureert op de OKTA-portal en over de instellingen die u doorgaans gebruikt voor het registreren van nieuwe toepassingen. |
| [!UICONTROL AEM Commerce] | Zelfstudie - [CIF Core-componenten aanpassen](https://www.adobe.io/apis/experiencecloud/commerce-integration-framework/tutorials.html#!AdobeDocs/commerce-cif-documentation/master/tutorials/05-customize-cif-components.md) | Bekijk verscheidene verschillende uitbreidingspunten die door de Componenten van de Kern van CIF en AEM in het algemeen worden verstrekt. De Componenten van de Kern van CIF verstrekt een standaardreeks componenten van de Handel die kunnen worden gebruikt om een project te versnellen dat de Oplossingen van de Manager van de Ervaring van Adobe (AEM) en van Magento integreert. |
| [!DNL Adobe Campaign] - Bestemmingen van het publiek | Video - [Create an audience...](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/creating-audiences-using-segment-builder.html) | Maak een publiek in Campagnestandaard met de Adobe [!UICONTROL Experience Platform Segment Builder]. U hebt rechtstreeks toegang tot deze functie in Adobe Campagne Standard via de modules [!UICONTROL Soorten publiek] . |
| [!DNL Adobe Campaign] - Bestemmingen van het publiek | Video - [Adobe Experience Platform-soorten activeren in een marketingworkflow](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/activating-aep-audiences.html) | Leer hoe te om de Audience [!UICONTROL van de Vraag van de] Diensten van Gegevens binnen een werkschema te activeren door de activiteit van het [!UICONTROL Leespubliek] te gebruiken. |
| [!DNL Adobe Campaign] | Lesbestand - [pushmelding met Android](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/getting-started-push-notifications/getting-started-with-push-notifications-android.html) | Verzend gepersonaliseerde en gesegmenteerde pushmeldingen naar mobiele iOS- en Android-apparaten. Deze zelfstudie begeleidt u door de stappen die nodig zijn voor het verzenden van pushmeldingen vanuit Adobe Campaign en het ontvangen van deze meldingen in uw Android-app. |
| [!DNL Adobe Campaign] | Video - [Een pushmelding maken](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/communication-channels/mobile/push/creating-a-push-notification.html) | Maak een pushmelding in Adobe Campaign Standard. U kunt persoonlijke en gesegmenteerde pushmeldingen verzenden naar mobiele apparaten met iOS en Android. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Controleer de status van een gegevensinvoertaak](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/checking-status-of-data-ingestion-jobs.html) | Leer hoe u de status van een gegevensinnametaak kunt controleren en of de gegevens vanuit Adobe Campaign Standard zijn opgenomen in het Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - Gegevenstoewijzing [wijzigen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/modifying-data-mapping.html) | Leer hoe u de status kunt controleren en de gegevenstoewijzing kunt wijzigen. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Kaarten, ervaringsgebeurtenissen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-experience-events.html) | Leer hoe u Experience Events in het Adobe Experience Platform in kaart brengt. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - Aangepaste bronnen [toewijzen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-custom-resources.html) | Leer hoe u verschillende gegevenstypen kunt toewijzen tussen Adobe Campaign Standard en Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Inzicht in de gegevensconnector van het Adobe Experience Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/understanding-the-adobe-experience-platform-data-connector.html) | Leer hoe u uw gegevens op het Adobe Experience Platform beschikbaar kunt maken door XTK-gegevens (gegevens die in Campaign worden opgenomen) toe te wijzen aan de XDM-gegevens (Experience Data Model) op het Adobe Experience Platform. |
| [!DNL Adobe Campaign] - AEP Data Connector | Video - [Gegevens van zaadtabel toewijzen](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/administrating/adobe-experience-platform-data-connector/mapping-seed-table-data.html) | Leer hoe u uw zaadgegevens/testprofielen met het Platform van de Ervaring van Adobe in kaart brengt. |
| [!DNL Adobe Campaign]- Bestemmingen van het publiek | Video - [Wijzig de doeldimensie van een levering voor een publiek Platform](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/changing-targeting-dimension.html) | Leer hoe u de doeldimensie van een levering voor een platformpubliek wijzigt buiten de tabel met het primaire profiel in Adobe Campagnestandaard. |
| [!DNL Adobe Campaign] | Video - [Groot gegevensbeheer op Snowflake](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Gebruik de Snowflake-connector in Adobe Campaign Classic. |
| [!DNL Adobe Campaign] - Bestemmingen van het publiek | Artikel - [Doelstellingen van de doelgroep (BETA) - Overzicht](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/profiles-and-audiences/audience-destinations/audience-destinations-overview.html) | Leer hoe u gecentraliseerde en geconsolideerde profielgegevens van het Adobe Experience Platform kunt gebruiken voor marketingcampagnes in Adobe Campagne Standard. |
| [!DNL Adobe Target] - Mobile SDK | Zelfstudie - [Een persoonlijk tintje toevoegen aan apps met Adobe Target](https://docs.adobe.com/content/help/en/target-learn/mobile-sdk-v4-android/overview.html) | Implementeer Adobe Target in uw eigen Android-app. Valideer de installatie van de SDK van de Mobiele Diensten en voer [!DNL Target] verzoeken zoals pre-haalt inhoud uit, het blokkeren van verzoeken, en meer. |
| Adobe Analytics | Video - [Adobe Summit 2019 - Supersessie](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-high-tech.html) | Bekijk gekrulde clips van de high-tech &#39;super sessie&#39; op Top 2019. |
| Adobe Analytics | Video - [Inleiding tot Berekende Metriek in de Analyse van de Reis van de Klant](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/introduction-to-calculated-metrics-in-customer-journey-analytics.html) | Doorloop de grondbeginselen van het creëren van [!UICONTROL Berekende Metriek] in de Analyse [!UICONTROL van de Reis van de]Klant. |
| Adobe Analytics | Video - [Adobe Summit 2019 - Supersessie](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-travel.html) | Bekijk gekrulde clips van de reis- en gastsessie op topconferentie 2019. |
| Adobe Analytics | Video - [Adobe Summit 2019 - Supersessie](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-summit-2019-super-session-retail.html) | Zie gekrulde clips van de handelssessie op Top 2019. |
| Adobe Analytics | Video - [Gebruiksscenario voor klant: Accentgroep investeert in de ervaring van de klant om verkoop te stimuleren](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/accent-group-invests-in-customer-experience-to-drive-sales.html) | Kijk hoe de Accent Group de Adobe Experience Cloud gebruikt om vloeiende digitale ervaringen te maken. |
| Adobe Analytics | Video - [Gebruiksscenario voor klant: ServiceNow krijgt de juiste inzichten om met vooruitzichten te verbinden](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/servicenow-gets-the-right-insights-to-connect-with-prospects.html) | Ontdek hoe u via de marketingkanalen actiefgegevens kunt [!DNL ServiceNow] ophalen en het rendement van de investering in betaalde zoekopdrachten kunt verhogen met Adobe Advertising Cloud en Adobe Analytics. |
| Adobe Analytics | Video - [Adobe Analytics - Het is meer dan gegevens die de Klantintelligentie heeft](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-analytics-customer-intelligence.html) | Leer meer over gegevensgestuurde marketing en hoe u uw analysemogelijkheden kunt aanpassen van gegevens tot inzichten tot actie. |
| Adobe Analytics | Video - [Adobe Sensei en Adobe Analytics - Extended Version](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/adobe-sensei-and-adobe-analytics.html) | Belangrijke functies weergeven in Adobe Analytics met Adobe-functionaliteit [!DNL Sensei,] , zoals [!UICONTROL Anomaly Detection,] [!UICONTROL Contribution Analysis,] [!UICONTROL Intelligent Alerts,] [!UICONTROL Clustering,]  [!UICONTROL Segment IQ,enPropensity Modeling.] |
| Adobe Analytics | Video - [Hoe kan de werkruimte van de Analyse van Adobe uw zaken veranderen](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/how-adobe-analysis-workspace-can-change-your-business.html) | Leer hoe u ad hoc analyse, flexibele analyse, cohortanalyse, en reserveanalyse kunt uitvoeren gebruikend de Werkruimte [!UICONTROL van de]Analyse. U kunt de analyse het werkmilieu met iedereen in uw bedrijf ook delen, en zijn belemmering en dalingsfunctie staat iedereen toe om de gegevens gemakkelijk te analyseren en inzicht snel te krijgen. |
| Adobe Analytics | Video - [Gebruiksscenario voor klant: Het thuisdepot vernieuwt met Customer Experience Management](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/intro-to-analytics/what-can-aa-do-for-me/the-home-depot-innovates-with-customer-experience-management.html) | Leer hoe u met Adobe-oplossingen loyaliteit en klanttevredenheid over uw merk kunt creëren dankzij een gepersonaliseerde, aangepaste boodschapervaring. [!DNL Home Depot] |
| Adobe Analytics | Presentatie - [Klantenreisanalyse begrijpen](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/understanding-customer-journey-analytics.html) | Leer hoe de Analyse van de Reis van de [!UICONTROL Klant van Adobe, een toepassingsdienst die op], wordt voortgebouwd de Werkruimte [!DNL Adobe Experience Platform]van de  Analyse in het Platform van de Ervaring brengt. Deze functie maakt multikanaalanalyse van al uw [!DNL Adobe Experience Platform] gegevenssets mogelijk. |
| Adobe Analytics | Video - [Kanaalkenmerk in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/cross-channel-attribution-in-customer-journey-analytics.html) | Leer hoe u visualisaties kunt gebruiken om attributie (krediet geven) over kanalen in de Analyse van de Reis van de [!UICONTROL Klant te tonen]. |
| Adobe Analytics | Artikel - [Klantentips voor het vervolgen van uw Adobe Analytics Learning-reis](https://docs.adobe.com/content/help/en/analytics-learn/tutorials/analysis-workspace/tips-and-tricks/customer-tips-for-continuing-your-adobe-analytics-learning-journey.html) | Neem contact op met drie Adobe-klanten die tips en trucs voor u hebben over hoe u de beste resultaten kunt behalen uit Adobe Analytics. |
| Adobe Analytics | Video - Kanaaloverschrijdende [visualisaties maken in CJA](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/creating-cross-channel-visualizations-in-customer-journey-analytics.html) | Ontdek hoe u met [!UICONTROL Klantenreisanalyse] visualisaties kunt maken die gegevens uit meerdere gegevenssets op meerdere kanalen bevatten, waaronder het samenvoegen van de gegevens per bezoeker. |
| Adobe Analytics | Video - Uw berekende cijfers [verplaatsen van Adobe Analytics naar Customer Journey Analytics](https://docs.adobe.com/content/help/en/platform-learn/tutorials/cja/moving-your-calculated-metrics-from-adobe-analytics-to-customer-journey-analytics.html) | Zoek tips voor het opnieuw maken van uw [!UICONTROLCberekende Metriek] voor Analyse van de Reis van de [!UICONTROL Klant]. |
