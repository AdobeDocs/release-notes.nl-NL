---
title: Releaseopmerkingen bij Adobe Experience Cloud
description: Sjabloon voor releaseopmerkingen bij Experience Cloud
doc-type: release notes
last-update: May 2020
author: mfrei
translation-type: tm+mt
source-git-commit: 9ca2b181b020052ec1f2cc968e9c2cf1bdfa7fdc
workflow-type: tm+mt
source-wordcount: '5149'
ht-degree: 85%

---


# Opmerkingen bij de release Adobe Experience Cloud - mei 2020

![Banner](/assets/experience-cloud-banner-3.png)

Deze pagina bevat nieuwe functies, correcties en belangrijke kennisgevingen in [!DNL Adobe Experience Cloud]. De releasedatums van de oplossing kunnen variëren. Controleer regelmatig op de nieuwste updates.

>[!NOTE]
>
>Meld u aan voor de [[!DNL Adobe Priority Product Update]](https://www.adobe.com/subscription/priority-product-update.html) om via e-mail op de hoogte te worden gebracht van komende releases.

**Releasedatum: mei 2020**

Laatste update: **2 juni 2020**

* [Adobe-systeemstatus](#status)
* [Experience Cloud-interface](#ecloud)
* [Experience Platform](#platform)
* [!DNL Analytics](#analytics) (**Bijgewerkt op 2 juni 2020**)
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

Release date: **May 21, 2020**

**Wat is er nieuw**

* Met uw Adobe ID kunt u lid worden van gebeurtenismeldingen met meer granulariteit, tot aan het aanbod van producten en invoegtoepassingen. Om u te helpen uw lidmaatschap sneller in te stellen wordt nu tijdens het proces voor zelfinschrijving een selectie van producten en aanbiedingen geadviseerd op basis van uw productrechten. Zo verkleint u het aantal e-mailberichten dat u ontvangt en krijgt u meer relevante meldingen in uw Postvak IN. Ga aan de slag op [status.adobe.com/subscriptions](https://status.adobe.com/proactive-notifications/subscriptions/edit).

**Nieuwe en verbeterde functies die nu beschikbaar zijn**

| Functie | Beschrijving |
| -----------| ---------- |
| Verbeterde gebruikerservaring voor lidmaatschap en meldingen | <ul><li>[!DNL Marketo Engage] regionale locaties worden nu gefilterd op basis van de geselecteerde lijst met productaanbiedingen.</li><li>[!DNL Marketo Engage] e-mailmeldingen zijn relevant voor de regio, locatie en omgeving van de gebruiker.</li></ul> |
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
>**[!UICONTROL Board & Collections]**, een verouderd filter in de [!UICONTROL Marketing Cloud Assets] kiezer, wordt uitgeschakeld.

## ![Pictogram](/assets/experience_platform_appicon_24.png) Experience Platform {#platform}

Releaseopmerkingen voor de [!DNL Experience Platform,] inclusief [!DNL Experience Platform Launch,] [!UICONTROL Journey Orchestration], [!UICONTROL Offers], [!UICONTROL People], [!UICONTROL Places], [!UICONTROL Mobile Services] en beveiligingsbulletins.

### Interfaceverbeteringen

Bijgewerkt: **15 mei 2020**

[!DNL Adobe Experience Platform] brengt updates uit van het domein en de headerbalk vrij om uw ervaring te verbeteren en te verenigen met andere Experience Cloud-applicaties. Updates zijn:

* Eenvoudiger overschakelen tussen uw organisaties of op een andere applicatie.
* Verbeterde gebruikershulp, inclusief aanbevolen artikelen en contextrelevante documentatie in het menu Help.
* Mogelijkheid om feedback te geven over het Experience Platform en tickets te maken voor bestandsondersteuning.

Zie [Releaseopmerkingen bij Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md) voor meer informatie.

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
* [Releaseopmerkingen bij Experience Platform](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes.md)
* [Beveiligingsbulletins en adviezen](https://helpx.adobe.com/nl/security.html) (Alle Adobe-producten)

## ![Pictogram](/assets/analytics.png) [!DNL Analytics] {#analytics}

* [Nieuwe functies in Customer Journey Analytics](#cust-journey)
* [Nieuwe functies in Adobe Analytics](#aa-features) (**Bijgewerkt op 2 juni 2020**)
* [Nieuwe functies in Media Analytics](#media-aa) (**bijgewerkt op 29 mei 2020**)
* [Belangrijke kennisgevingen voor analysebeheerders](#aa-notices) (1 juni 2020 **bijgewerkt**)
* [Oplossingen voor](#aa-fixes) Adobe Analytics (**bijgewerkt tot 21 mei 2020**)
* [AppMeasurement](#appm)
* [Nieuwe tutorials voor Analytics](#tutorials-analytics)

### Nieuwe functies in Customer Journey Analytics {#cust-journey}

| Functie | Beschrijving |
| -----------| ---------- |
| [!UICONTROL Customer Journey Analytics]: wereldwijde beschikbaarheid | Maakt [!UICONTROL Customer Journey Analytics] beschikbaar voor klanten in EMEA en APAC. |
| [!UICONTROL Customer Journey Analytics]: ondersteuning voor [!UICONTROL Adobe Experience Platform Sandboxes] | Hiermee kunt u specifieke [!UICONTROL Adobe Experience Platform Sandboxes] selecteren om CJA-verbindingen te maken. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics-platform/using/cja-connections/create-connection.html) |

### Nieuwe functies in Adobe Analytics {#aa-features}

<!--First-Party Domains Available in China RDC: Enables customers with a cn domain to request a 1st-party domain for use inside of Mainland China. Learn more... -->

| Functie | [Algemene beschikbaarheidsdatum doel](https://docs.adobe.com/content/help/en/analytics/landing/an-releases.html) | Beschrijving |
| -----------| ------------ | ---------- |
| API voor het invoegen van bulkgegevens | 31 mei 2020 | Hiermee kunt u eenvoudig en onafhankelijk batches met analysegegevens invoeren. Nuttig voor server-kant en off-line gegevens. [Meer informatie...](https://www.adobe.io/apis/experiencecloud/analytics/docs.html#!AdobeDocs/analytics-2.0-apis/master/bdia.md) |
| Analytics-ondersteuning voor [!UICONTROL Adobe Experience Platform Edge Network] | 31 mei 2020 | Hiermee kunt u één tag gebruiken om data te verzenden naar meerdere Adobe-oplossingen zoals Adobe Analytics, Adobe Target, Adobe Audience Manager, Adobe Experience Platform Data Lake, Unified Profile en Experience Cloud ID Service. [Meer informatie...](https://docs.adobe.com/content/help/en/experience-platform/edge/solutions/analytics/analytics-overview.html) |
| [!UICONTROL Adobe Analytics dashboards] | 21 mei 2020 | [!UICONTROL Adobe Analytics dashboards] is een mobiele app waarmee gebruikers altijd en overal toegang hebben tot inzichten van Adobe Analytics. Deze app is bedoeld voor managers die onderweg toegang willen tot belangrijke cijfers. Hiermee is toegang mogelijk tot geselecteerde, interactieve scorecards en de app is beschikbaar voor zowel iOS- als Android-besturingssystemen. [Meer informatie...](https://docs.adobe.com/content/help/nl-NL/analytics/analyze/mobapp/home.html) |
| [!UICONTROL Workspace]: automatisch [!UICONTROL Freeform Tables] samenstellen vanuit een lege status | [21 mei 2020] | Vroeger konden onderdelen niet rechtstreeks in een leeg project of leeg venster paneel worden neergezet; u moest eerst een [!UICONTROL Freeform Table] toevoegen. Nu kunt u onderdelen rechtstreeks neerzetten in een leeg project of deelvenster en wordt er automatisch een [!UICONTROL Freeform Table] voor u gemaakt in een aanbevolen indeling. Bovendien zijn er verbeteringen toegevoegd in de manier waarop gemengde onderdeeltypen (zoals dimensies en cijfers) wanneer deze samen in een lege vrije-vormtabel worden neergezet. |
| [!UICONTROL Adobe Analytics Package] toegevoegd aan [!UICONTROL Feature Access Level] pagina | 21 mei 2020 | U kunt nu bekijken aan welke [!UICONTROL Adobe Analytics Package] (SKU) uw bedrijf recht heeft op **[!UICONTROL Admin]** > **[!UICONTROL Company Settings]** > **[!UICONTROL Feature Access Level]**. |
| Toegankelijkheidsverbeteringen | 21 mei 2020 | Het Adobe Analytics-team heeft verschillende toegankelijkheidsverbeteringen doorgevoerd in de analysewerkruimte, waaronder verbeterde toetsenbordnavigatie, kleurcontrast en ondersteuning voor schermlezers. [Meer informatie...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/workspace-faq/aw-accessibility.html) |

#### Nieuwe functies in [!UICONTROL Media Analytics] {#media-aa}

Datum bijgewerkt: **29 mei 2020**

**Volgen van spelerstatus:** [!UICONTROL Media Analytics] klanten kunnen tijdens het afspelen viewerinteractie vastleggen met een standaardset oplossingsvariabelen voor volledig scherm, ondertiteling, dempen, beeld-in-beeld en scherpgesteld. U hebt ook de flexibiliteit om aangepaste spelerstatussen te maken. Variabelen voor het bijhouden van Player-statussen kunnen nu worden gerapporteerd in [!UICONTROL Analysis Workspace]. Voor deze functie is een van de volgende opties vereist:

* Media [!DNL JavaScript] SDK 3.0 of hoger
* Voor gebruik met de [!DNL Adobe Experience Platform] (AEP) SDK:
   * [!UICONTROL Media Analytics Extension] (voor web): [!UICONTROL Adobe Media Analytics] (3.x SDK) voor audio en video v1.0 of hoger
   * [!UICONTROL Media Analytics Extension] (voor mobiele apparaten): [!UICONTROL Adobe Media Analytics for Audio] en Video v2.0 of hoger
* [!UICONTROL Media Collection]

Zie [Informatie over het bijhouden](https://docs.adobe.com/content/help/en/media-analytics/using/player-state-tracking/player-state-overview.html)van spelerstatussen.

#### Adobe Analytics-oplossingen {#aa-fixes}

* Adobe heeft de [!UICONTROL Time Spent] maatstaf zodanig gewijzigd dat deze nooit &quot;Niet opgegeven&quot; in de berekening opneemt. Dit betekent dat, ongeacht of de UI zegt om &quot;Niet gespecificeerd&quot;te omvatten, wij een speciale uitzondering maken om &quot;Ongespecificeerd&quot;altijd in de [!UICONTROL Time Spent] berekening uit te sluiten. Daarom zelfs als u een rapport vormde dat [!UICONTROL Time Spent] metrisch bevat om &quot;Niet gespecificeerd&quot;te omvatten, zal het altijd 0 tijd terugkeren die voor het &quot;Niet gespecificeerde&quot;lijnpunt wordt doorgebracht. Merk op dat dit historische rapporten in Rapporten &amp; Analytics evenals de Rapporterende API v1.4 kan veranderen. (AN-197958)
* Probleem verholpen waarbij Instance/bezoek/bezoeker niet in de noemer voor de [!UICONTROL Time Spent] meetgegevens werd meegeteld.  Dit gebeurt wanneer een hit zonder waarde voor de dimensie (bijvoorbeeld [!UICONTROL Pagename]) in dezelfde seconde wordt gevolgd. (AN-211074)
* Er is een probleem opgelost waardoor [!DNL Analytics]-segmentdata ontbraken in Audience Manager. (AN-206221)
* Er is een probleem opgelost waardoor bij [!UICONTROL Data Sources]-verwerking verkeerde datums werden weergegeven. (AN-213604)
* Er is een probleem opgelost waardoor classificatiebestanden niet goed naar de FTP werden geüpload. (AN-214102)
* Er is een probleem opgelost waardoor de API-methode `Segments.Get` geen volledige reactie retourneerde. (AN-206210)
* Er is een probleem opgelost waardoor tabelregelitems werden geconverteerd naar speciale tekens in een [!DNL Workspace]-PDF-download. (AN-196153)
* Er is een probleem opgelost waardoor de Adobe Analytics API 1.4-call `visattrcustomeridcustomerattributes` niet goed werkte. (AN-186873)
* Er is een probleem opgelost waardoor data in rapporten werden weergegeven, maar niet in de [!UICONTROL Data Feed]. (AN-211923)
* Er is een probleem opgelost waardoor [!UICONTROL Product Profile]-rechten niet konden worden gekopieerd. (AN-211113)
* Er is een probleem opgelost waardoor gebruikers met Federated ID&#39;s zich niet konden aanmelden bij [!UICONTROL Report Builder]. (AN-207750)
* Er is een probleem opgelost waardoor [!UICONTROL AdWords]-data niet werden weergegeven in [!UICONTROL Advertising Analytics]. (AN-213249)
* Er is een probleem opgelost waardoor classificatiedata niet werden weergegeven in de trendweergave. (AN-212761)
* Er is een probleem opgelost dat een onjuist aantal gepubliceerde segmenten in [!UICONTROL Segment Manager] veroorzaakte. (AN-213374)
* Er is een probleem opgelost met de optie **[!UICONTROL Show Upwards Trend As...]** in het deelvenster [!UICONTROL Calculated Metric Editor] - het werkte niet bij het toepassen van filters. (AN-214223)
* Er zijn meerdere problemen opgelost met het importeren en exporteren van [!UICONTROL Classification]. (AN-213488, AN-215309, AN-216345, AN-215307, AN-216671)
* Er zijn meerdere problemen opgelost met [!UICONTROL Classification Rule Builder]. (AN-213826, AN-213550, AN-213095)
* Er zijn problemen opgelost met [!UICONTROL Data Sources]-verwerking. (AN-218083, AN-213604, AN-214102, AN-215485, AN-215339, AN-212911, AN-217551, AN-217947, AN-219018, AN-214691, AN-218401)
* Er zijn problemen opgelost met FTP-verbindingsproblemen. (AN-115525)
* Er zijn meerdere problemen opgelost met [!DNL Analytics] [!UICONTROL Data Feeds]. (AN-176769, AN-160480, AN-211923, AN-204286, AN-212977, AN-214528, AN-215080, AN-217784, AN-219093, AN-218817, AN-217798, AN-218267, AN-218382)
* Er zijn problemen opgelost met [!UICONTROL Data Warehouse]-aanvragen. (AN-181836)
* Er zijn problemen opgelost met als PDF-gedownloade [!UICONTROL Workspace]-projecten waarbij waarden werden geconverteerd naar speciale tekens. (AN-196153)
* Er is een probleem opgelost waardoor [!UICONTROL Product Profile]-rechten niet konden worden gekopieerd in [!UICONTROL Admin Console]. (AN-211113)
* Er is een probleem opgelost waardoor tijdnotaties in berekende cijfers werden verstoord bij negatieve waarden. (AN-210900)
* Er is een probleem opgelost waardoor gebruikers het [!UICONTROL Attribution Model] van de cijfers van statische rijen niet konden wijzigen. (AN-207872)
* Er is een probleem opgelost waardoor de [!UICONTROL Scheduled Report]-builder vastliep in een wachtrijstatus. (AN-215317)
* [!UICONTROL ExactTarget Data Connector] probleem is gecorrigeerd. (AN-210794)
* Er zijn problemen met latentie opgelost in [!UICONTROL Bulk Ingestion API]. (AN-210165)
* Er is een probleem opgelost waardoor gebruikers zich niet konden aanmelden bij [!UICONTROL Report Builder] met een Federated ID. (AN-207750)
* Er is een probleem opgelost in [!UICONTROL Advertising Analytics] waardoor [!DNL Google AdWords]-data niet konden worden weergegeven. (AN-213249)
* Er is een probleem opgelost waardoor gebeurtenissen van [!UICONTROL Workspace] [!UICONTROL Project Viewed] niet konden worden weergegeven in logboeken. (AN-214134)
* Er is een probleem opgelost dat zich voordeed wanneer het datumbereik in [!UICONTROL Workspace] werd gewijzigd en **[!UICONTROL Apply to all panels]** werd geselecteerd. De datum werd in sommige deelvensters niet gewijzigd. (AN-214944)
* Er is een probleem opgelost waardoor waarschuwingen niet konden worden gemaakt of bewerkt. (AN-215920)
* Er is een probleem opgelost waardoor voor alle dynamische datumbereiken in [!UICONTROL Workspace] onjuiste datums werden weergegeven doordat de eerste dag van de week af en toe wisselde tussen zondag en maandag. (AN-218835)

#### Nog meer oplossingen in Adobe Analytics

AN-101871, AN-115525; AN-123869; AN-152580; AN-160480; AN-178128; AN-186907; AN-199299; AN-201342; AN-201397; AN-204286; AN-204518; AN-206045; AN-206948; AN-208607; AN-209486; AN-210743; AN-211550; AN-211539; AN-211826; AN-211943; AN-212130; AN-212151; AN-212653; AN-212673; AN-212709; AN-212833; AN-212961; AN-212977; AN-213095; AN-213422; AN-213450; AN-213490; AN-213752; AN-213827; AN-214094; AN-214153; AN-214214; AN-214234; AN-214253;  AN-214255; AN-214343; AN-214355; AN-214401; AN-214427; AN-214528; AN-214642; AN-214691; AN-214772; AN-214793; AN-214924; AN-215017; AN-215080; AN-215212; AN-215312; AN-215377; AN-215402; AN-215545; AN-215905; AN-215963; AN-216447; AN-216676; AN-216880; AN-216999; AN-217245; AN-218450; AN-218899; AN-219487; AN-219677

### Belangrijke berichten voor [!DNL Analytics]-beheerders {#aa-notices}

| Bericht | Toegevoegd of bijgewerkt op | Beschrijving |
| -----------| ---------- | ---------- |
| Migratie naar één productdomein | Ingangsdatum: 28 mei 2020 | De migratie naar een uniform productdomein voor Adobe Analytics, dat in januari 2020 is gestart, is op 28 mei 2020 voltooid. Hoewel Adobe Analytics werkt om alle `omniture.com` domeinverwijzingen uit zijn architectuur te verwijderen, is het belangrijk om `omniture.com` als derdekoekjes te whitelist. Wanneer de volledige architectuurmigratie (binnenkort) is voltooid, stellen we u via de releaseopmerkingen op de hoogte en deze whitelist-stap is dan niet meer nodig. [Hier](https://helpx.adobe.com/analytics/kb/adobe-ip-addresses.html) is een volledige lijst van geadviseerde IP adressen en domeinen die u zou moeten whitelist.<br>Als uw organisatie cookies van derden blokkeert, neemt u contact op met de klantenservice om uw toegang tot Adobe Analytics te herstellen. |
| Nieuwe standaardlandingspagina voor Adobe Analytics | Ingangsdatum: 18 juni 2020 | Op 18 juni 2020 verandert de standaard bestemmingspagina voor Adobe Analytics van [!UICONTROL Reports] naar [!UICONTROL Workspace]. Deze wijziging vindt plaats voor alle gebruikers die nog geen aangepaste bestemmingspagina hebben ingesteld. |
| Technologie-whitelist van derden | (Ingangsdatum: 12 maart 2020 | Adobe Analytics is begonnen technologieën van derden te gebruiken voor functionaliteit-implementatiebeheer en ondersteuning in producten. De volgende URL&#39;s moeten worden toegevoegd aan de whitelisten van de netwerkfirewall om volledige toegang tot de functies te garanderen:<ul><li>Verzicht: https://esp.aptrinsic.com</li><li>Donkerder starten: https://app.launchdarkly.com</li></ul> |
| Verbeterde redundantie voor beschikbaarheid van analysewerkruimte | 21 mei 2020 | Om beschikbaarheid van de Werkruimte van de Analyse te verzekeren, voegen wij een secundaire CDN (het Netwerk van de Levering van de Inhoud) voor betere overtolligheid toe. De volgende URL&#39;s moeten worden toegevoegd aan de vereiste whitelists van de netwerkfirewall:<ul><li>https://aaui-879784980514.s3.us-east-2.amazonaws</li><li>https://d30ln29764hddd.cloudfront.net</li><li>https://awaascicdprodva7.blob.core.windows.net</li><li>https://aauicdnva7.azureedge.net</li></ul> |
| Wijzigen in hoe [!UICONTROL Entries/Exits] wordt berekend in [!UICONTROL Workspace] | 7 april 2020 | Sinds maart 2020 is in [!UICONTROL Analysis Workspace] gewijzigd hoe de waarde _Geen_ communiceert met [!UICONTROL Entries/Exits]. Omdat u _Geen_ nu kunt in- en uitschakelen in [!UICONTROL Analysis Workspace], gebruiken we de waarde _Geen_ na openen en afsluiten, waar dit (voor eVars) vroeger werd toegepast vóór openen en afsluiten. Stel bijvoorbeeld dat de eerste hit van een bezoek geen waarde heeft voor eVars, maar de tweede hit wel. In [!UICONTROL Reports & Analytics] verschijnt de eerste hit als _Niet gespecificeerd_ voor de vermelding, maar in [!UICONTROL Analysis Workspace] verschijnt dit als de waarde voor de tweede hit. |
| EOL van **[!UICONTROL Conversion Level]**-instelling | 3 maart 2020 | De niet-functionerende instelling [Conversieniveau](https://docs.adobe.com/content/help/nl-NL/analytics/admin/admin-tools/general-acct-settings-admin.html) in **[!UICONTROL Admin Tools]** > **[!UICONTROL Report Suites]** > **[!UICONTROL General Account Settings]** wordt op 12 maart 2020 uit de interface verwijderd. |
| EOL van **[!UICONTROL Dashboard Archive]** | 27 maart 2020 | De instelling **[!UICONTROL View Archive]** onder **[!UICONTROL Manage Dashboards]** in [!UICONTROL Reports & Analytics] zal vanaf oktober 2020 niet meer beschikbaar zijn. |
| Einde van ondersteuning voor TLS 1.1 | 3 oktober 2019 | Op 31 maart 2020 verwijdert Adobe Analytics de ondersteuning voor TLS 1.1. Deze wijziging is een onderdeel van onze voortdurende inspanningen om de hoogste veiligheidsnormen te handhaven en de veiligheid van klantdata te bevorderen. |
| Nieuw Adobe Analytics-domein | 18 dec. 2019 | Op 16 januari 2020 is Adobe Analytics begonnen met de verhuizing naar een nieuw domein - `https://experience.adobe.com/analytics.`<br>**Opmerking:** Deze wijziging geldt voor alle gebruikers die met hun Adobe ID of Enterprise ID toegang hebben tot Analytics.<ul><li>De domeinwijziging kan tijdens het laden van Analytics in Safari problemen met cookies veroorzaken. Als u de optie _Cross-site tracking voorkomen_ in de privacyvoorkeuren van [!DNL Safari] uitschakelt, worden cookies in alle domeinen (en alle cross-site-ervaringen) ingeschakeld en kan Analytics in dit nieuwe Adobe Experience Cloud-domein functioneren. U kunt zonder problemen andere browsers gebruiken, omdat dit alleen voor [!DNL Safari]-gebruikers geldt.</li><li>De domeinwijziging kan ervoor zorgen dat [!UICONTROL Activity Map] voor bepaalde klanten [in specifieke gevallen](https://docs.adobe.com/content/help/nl-NL/analytics/analyze/activity-map/activity-map.html) niet meer werkt.</li></ul> |
| Einde van levensduur - Verouderde Analytics-API&#39;s | 9 januari 2020 | In november 2020 zullen de volgende verouderder Analytics-API-services het eind van hun levensduur bereiken en worden afgesloten. De huidige integraties die met deze services zijn gemaakt, werken niet meer. <ul><li>1.3 API&#39;s voor Analytics</li><li>1.4 API&#39;s voor SOAP Analytics</li><li>Verouderde OAuth-verificatie (OAuth en JWT)</li></ul>We hebben gezorgd voor een [Verouderde API EOL - Veelgestelde vragen](https://github.com/AdobeDocs/analytics-1.4-apis/blob/master/docs/APIEOL.md?mv=email) om uw vragen te beantwoorden en richtlijnen te geven voor het vervolg. API-integraties die van deze services gebruikmaken, kunnen migreren naar de [1.4 Analytics REST-API&#39;s](https://github.com/AdobeDocs/analytics-1.4-apis?mv=email) of de [Analytics 2.0-API&#39;s](https://github.com/AdobeDocs/analytics-2.0-apis?mv=email). Verouderde OAuth-accounts kunnen migreren naar een [Adobe IO](https://console.adobe.io/home?mv=email) Analytics-integratieaccount dat kan worden gebruikt voor toegang tot de API&#39;s van Analytics 1.4 en Analytics 2.0. |
| San Jose FTP Broker eindigt voor Londen en Singapore | Juli 2020 | Voor klanten in Londen en Singapore zullen we de datatussenhandel tussen Londen of Singapore en het datacenter in San Jose [ftp.omniture.com](ftp://ftp.omniture.com/) niet meer ondersteunen.<br/><ul><li>Voor Londen gebruikt u [ftp3.omniture.com](ftp://ftp3.omniture.com/)</li><li>Voor Singapore gebruikt u [ftp4.omniture.com](ftp://ftp4.omniture.com/)</li></ul> |
| EOL van Ad Hoc Analysis | 6 aug. 2018 | Adobe heeft aangekondigd dat Ad Hoc Analysis zal worden beëindigd. De einddatum wordt gedeeld zodra deze beschikbaar is. Ga voor meer informatie naar [Discover Workspace](https://spark.adobe.com/page/S9Bhp66VJ2fEn/). |

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
* [Gebruikershandleiding voor Cloud Manager](https://helpx.adobe.com/nl/experience-manager/cloud-manager/user-guide.html)
* [Releaseopmerkingen bij AEM Cloud Manager](https://docs.adobe.com/content/help/nl-NL/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)
* [Oudere versies van AEM-documentatie](https://helpx.adobe.com/nl/experience-manager/aem-previous-versions.html)
* [Dynamic Media Classic Help-startpagina](https://docs.adobe.com/content/help/nl-NL/dynamic-media-classic/using/home.html)
* [Releaseopmerkingen bij Dynamic Media](https://docs.adobe.com/content/help/nl-NL/dynamic-media-developer-resources/release-notes/s7rn2017.html)
* [Releaseopmerkingen bij Livefyre](https://docs.adobe.com/content/help/nl-NL/livefyre/using/release-notes/c-rn.html)

## ![Pictogram](/assets/campaign.png) [!DNL Campaign] {#ac}

Adobe Campaign biedt een intuïtieve, geautomatiseerde manier om één-op-één berichten af te leveren via online en offline marketingkanalen. U kunt nu anticiperen op wat uw klanten willen met behulp van ervaringen die worden bepaald door hun gewoonten en voorkeuren.

### Campaign Standard

* [Adobe Campagne Standard 20.3-release](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html)

### Campaign Classic

* [Adobe Campaign Classic 20.1.3](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/latest-release.html#release-20-1-3-build-9124)
* [Adobe Campaign Classic 19.1.4](https://docs.adobe.com/content/help/nl-NL/campaign-classic/using/release-notes/previous-releases/release--19-1.html#release-19-1-4-build-9032)

### Campagne

| Functie | Beschrijving |
| -----------| ---------- |  
| Beheer van GPG-codes | Installeer en/of genereer GPG-codes op een marketinginstantie om data die vanuit Campaign worden verzonden, te coderen en inkomende data te ontcijferen. |
| Certificaatbeheer voor CNAME-subdomeinen | Met het besturingsdeelvenster kunt u nu de SSL-certificaten van uw subdomeinen vernieuwen die zijn gedelegeerd met de CNAME-methode. |

### Nieuwe zelfstudies voor campagnes

* Nieuwe tutorials voor Campaign Standard

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Besturingsdeelvenster - Google TXT-recordbeheer](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/administrating/control-panel/google-txt-record-management.html) | Leer hoe u verificatiedata van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Campaign-besturingsdeelvenster. |
| [Een workflow configureren en uitvoeren met de externe-API-activiteit](https://docs.adobe.com/content/help/en/campaign-standard-learn/tutorials/managing-processes-and-data/data-management-activities/external-api-activity.html) | Leer een extern REST-API-eindpunt op te roepen met de externe-API-activiteit. |
| [Aan de slag met pushmeldingen voor Android-tutorial](https://docs.adobe.com/content/help/en/campaign-standard-learn/getting-started-with-push-notifications-android/introduction.html) | In deze zelfstudie worden de stappen beschreven die nodig zijn om pushmeldingen in te stellen met Campagnestandaard en Android App. |

* Nieuwe tutorials voor Campaign Classic

| Inhoud | Beschrijving |
| -----------| ---------- |  
| [Beheer van big data op Snowflake](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/fda/big-data-segmentation-on-snowflake.html) | Krijg inzicht in het gebruik van de Snowflake-connector in Adobe Campaign Classic. |
| [Besturingsdeelvenster - Google TXT-recordbeheer](https://docs.adobe.com/content/help/en/campaign-classic-learn/tutorials/administrating/control-panel-acc/google-txt-record-management.html) | Leer hoe u verificatiedata van de Google TXT-site toevoegt aan al uw subdomeinen die worden gebruikt om e-mails naar GMAIL-adressen te verzenden via het Campaign-besturingsdeelvenster. |

### Bronnen voor hulp bij campagnes

* Adobe Campagnestandaard: [Help Center](https://docs.adobe.com/content/help/en/campaign-standard/using/campaign-standard-home.html) - [Release Notes](https://docs.adobe.com/content/help/nl-NL/campaign-standard/using/release-notes/release-notes.html) - [Hoe kan ik-video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-standard-tutorials/overview.html) &#39;s - [Release-planning](https://docs.adobe.com/content/help/en/campaign-standard/using/release-notes/release-planning.html) - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/en/campaign-standard/using/documentation-updates.html)
* Adobe Campaign Classic: [Help Center](https://docs.adobe.com/content/help/en/campaign-classic/using/campaign-classic-home.html) - [Release Notes](https://docs.adobe.com/content/help/en/campaign-classic/using/release-notes/latest-release.html) - [Hoe kan ik-video](https://docs.adobe.com/content/help/en/campaign-learn/campaign-classic-tutorials/overview.html)&#39;s - [Nieuwste documentatieupdates](https://docs.adobe.com/content/help/en/campaign-classic/using/documentation-updates.html)
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
