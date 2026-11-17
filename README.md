# Handleiding Lap (Nederlands)

> Onofficiële Nederlandstalige handleiding voor [Lap](https://github.com/julyx10/lap), de gratis, lokale fotobeheerder voor Windows, macOS en Linux. Geschreven door [Mc5](https://github.com/OPGERUIMD97), maker van de Nederlandse vertaling van Lap. Deze handleiding is geen onderdeel van het Lap-project zelf.
>
> 📄 **[Download deze handleiding als PDF](Handleiding-Lap-NL.pdf)** (A4, om te printen of te delen)
>
> Lap downloaden: [nieuwste release](https://github.com/julyx10/lap/releases/latest) · Vragen of fouten in Lap: [issues van Lap](https://github.com/julyx10/lap/issues)

## Inhoud

1. [Eerste stappen](#1-eerste-stappen)
2. [Foto's later toevoegen](#2-fotos-later-toevoegen)
3. [Bladeren en bekijken](#3-bladeren-en-bekijken)
4. [Ordenen](#4-ordenen)
5. [Zoeken en personen](#5-zoeken-en-personen)
6. [Duplicaten en vergelijkbare foto's](#6-duplicaten-en-vergelijkbare-fotos)
7. [Bewerken en externe apps](#7-bewerken-en-externe-apps)
8. [Bibliotheekgegevens en back-ups](#8-bibliotheekgegevens-en-back-ups)
9. [Problemen oplossen en veelgestelde vragen](#9-problemen-oplossen-en-veelgestelde-vragen)

---

Lap is een gratis fotobeheerder die rechtstreeks met je eigen mappen werkt: je foto's blijven waar ze staan en alles draait op je eigen computer. Dit stappenplan volgt de volgorde waarin je Lap leert kennen, van het eerste album tot back-ups en veelgestelde vragen.

Bijgewerkt voor **Lap 0.4.0**. Sinds versie 0.3.3 is Lap ook in het Nederlands beschikbaar; deze handleiding gebruikt de Nederlandse namen van knoppen en menu's, met de Engelse naam tussen haakjes voor wie Lap in het Engels gebruikt.

**Windows, macOS en Linux.** Lap werkt op alle drie hetzelfde. Toetscombinaties staan in deze handleiding met **Ctrl**; op een Mac gebruik je daarvoor **⌘** (Command). Waar een toets op de Mac anders is, staat dat erbij. *Rechtsklik* betekent op een Mac: Control-klik of met twee vingers klikken. Met *bestandsbeheerder* bedoelen we Verkenner (Windows), Finder (macOS) of de bestandsbeheerder van je Linux-systeem.

## 1. Eerste stappen

In Lap is een **album** gewoon een map op je computer, externe schijf of NAS. Lap kopieert en verplaatst niets; het houdt die map alleen bij.

### Taal kiezen

Bij de eerste start kiest Lap automatisch de taal van je computer; staat die op Nederlands, dan start Lap meteen in het Nederlands. Een andere taal kies je op het welkomstscherm, of later via **Instellingen → Algemeen → Taal en regio** (*Settings → General → Language & region*). Daar stel je ook de **Datum- en tijdnotatie** in: **Systeem volgen** (standaard, volgt de regio-instelling van je computer, op Windows ook je eigen datumnotatie) of **App-taal volgen**.

### Licht of donker

Bij **Instellingen → Algemeen → Weergave → Kleurmodus** kies je **Licht**, **Donker** of **Systeem volgen**. Met *Systeem volgen* wisselt Lap vanzelf mee met de licht- of donkerstand van je computer.

### Na een update naar 0.4.0

Lap zet je bibliotheek bij de eerste start automatisch om. Bestaande albums lezen daarna één keer de metadata van je bestanden opnieuw in, om de nieuwe velden te vullen (titel, maker, copyright en dergelijke). Dat gebeurt op de achtergrond; je kunt gewoon doorwerken.

### Je eerste album toevoegen

1. Klik op het welkomstscherm op **Nieuw album** (*New album*), of open **Albums** in de zijbalk en klik op **+**.
2. Klik bij **Map** (*Folder*) en kies de map met je foto's en video's. Submappen gaan automatisch mee.
3. Geef het album eventueel een naam en beschrijving.
4. Wil je iets overslaan? Gebruik in hetzelfde venster **Bestandstypen uitsluiten**, **Kleine afbeeldingen uitsluiten** of **Mappen uitsluiten** (*Exclude file types / small images / folders*). Het scanvoorbeeld laat zien hoeveel bestanden meedoen.
5. Klik op **OK**.

Sneller: sleep een map vanuit je bestandsbeheerder naar **Albums** in de zijbalk en laat los op **Sleep een map om deze toe te voegen**. Lap vraagt je die map nog één keer te kiezen (**Map selecteren: …**) en voegt hem daarna toe.

Later aanpassen: klik met rechts op het album en kies **Album bewerken…** (*Edit album…*). Met **Opslaan en bijwerken** (*Save & Update*) worden de wijzigingen doorgevoerd.

Albums mogen elkaar niet overlappen. Heb je `Afbeeldingen` als album, dan kun je `Afbeeldingen/2024` niet los toevoegen; die map bekijk je binnen het bestaande album.

### Lap laten scannen

Na het toevoegen scant Lap het album op de achtergrond, in drie stappen: bestanden zoeken, miniaturen maken en zoeken voorbereiden. Alles gebeurt op je eigen computer. Lap leest daarbij ook de metadata die al in je bestanden of in XMP-sidecars staat, zoals sterren, tags en beschrijvingen uit een ander fotoprogramma (zie hoofdstuk 8).

- Je kunt meteen beginnen met bladeren. De eerste scan van een groot album kan even duren; daarna verwerkt Lap alleen wijzigingen.
- Pauzeren of hervatten: klik met rechts op het album en kies **Scannen pauzeren** of **Album scannen** (*Pause scanning / Scan album*).
- Werd Lap tijdens een scan afgesloten, dan vraagt Lap bij de volgende start of je wilt **Doorgaan**. Blijft één bestand problemen geven, kies dan **Dit bestand overslaan en doorgaan**.

### De zijbalk

| Onderdeel | Wat je ziet |
| --- | --- |
| **Bibliotheek** (*Library*) | Alle bestanden, Op deze dag, favorieten, beoordelingen, schiften, onderwerpen |
| **Albums** | Je albums met hun echte mappenstructuur |
| **Slimme albums** (*Smart albums*) | Opgeslagen weergaven op basis van regels |
| **Zoeken** (*Search*) | Zoeken op tekst en beschrijving |
| **Kalender** (*Calendar*) | Foto's per jaar, maand en dag |
| **Tags** | Je tags, als boom met subtags |
| **Personen** (*People*) | Herkende gezichten, alleen als gezichtsherkenning aanstaat |
| **Locaties** (*Locations*) | Foto's per plaats |
| **Camera's** (*Cameras*) | Foto's per camera en objectief |

Bovenaan de zijbalk staat de naam van je **bibliotheek**, met het aantal bestanden erin. Klik erop om te wisselen of om **Bibliotheken beheren…** te openen. De meeste mensen hebben er maar één nodig.

## 2. Foto's later toevoegen

Een **nieuw album** heb je alleen nodig voor foto's op een compleet nieuwe plek. In alle andere gevallen voeg je ze toe aan een album dat je al hebt, op een van deze manieren.

### A. In een map zetten die al bij een album hoort

Kopieer of bewaar de bestanden met je bestandsbeheerder (Verkenner, Finder of de bestandsbeheerder van Linux) of een andere app in die map. Lap ziet ze vanzelf:

- bij het opstarten controleert Lap alle albummappen op wijzigingen;
- zodra je die map opent onder **Albums**, wordt hij opnieuw gecontroleerd.

Wil je ze meteen zien? Klik in de werkbalk op **Vernieuwen** (*Refresh*), of klik met rechts op het album en kies **Album scannen**. Een **nieuwe submap** die je buiten Lap hebt gemaakt, verschijnt na rechtsklikken op de bovenliggende map → **Mappen vernieuwen** (*Refresh folders*). Dat controleert nu ook de bestanden direct in die map, dus ook een bestand dat je onder dezelfde naam hebt overschreven.

Lap herkent ook RAW+JPEG/HEIC-paren, Live Photos en XMP-sidecars die bij een foto horen, VOB-video's (van dvd's) en Affinity-bestanden (`.af`, `.afphoto`, `.afdesign`, `.afpub`), waarvan je een voorbeeld ziet.

### B. Slepen of plakken in Lap

1. Open **Albums** en kies het album of de map waar de foto's heen moeten.
2. Sleep de bestanden vanuit je bestandsbeheerder naar het venster van Lap en laat los zodra **Laat bestanden los om te importeren** verschijnt.

Lap kopieert de bestanden naar die map. Plakken kan ook: kopieer bestanden in je bestandsbeheerder en plak ze met **Ctrl+V** in de gekozen map. Een afbeelding op het klembord, zoals een schermafbeelding, wordt als nieuw bestand bewaard.

Liever kiezen dan slepen? Klik met rechts op een map onder **Albums** en kies **Bestanden importeren…** (*Import Files…*). Selecteer de bestanden; Lap kopieert ze naar die map en houdt rekening met de uitsluitingen van het album.

### C. Importeren van camera of geheugenkaart, gesorteerd op datum

1. Klik met rechts op het album en kies **Map importeren…** (*Import folder…*).
2. Kies de **Bron** (*Source*), bijvoorbeeld je SD-kaart, en de **Bestemming** (*Destination*) binnen het album.
3. Kies een **Mapindeling** (*Folder layout*): per dag (`JJJJ/JJJJ-MM-DD`), per maand, per jaar, of **Mapstructuur behouden** om de mappen van de bron over te nemen.
4. Klik op **Importeren**.

Lap kopieert de bestanden met hun originele naam en slaat bestanden over waarvan de inhoud al in de bestemming staat. RAW-paren en XMP-sidecars gaan samen mee. De originelen op de bron blijven onaangeroerd.

### D. Foto's op een nieuwe plek

Staan de foto's in een map die nog bij geen enkel album hoort, bijvoorbeeld op een nieuwe schijf? Voeg die map dan toe als **Nieuw album** (zie hoofdstuk 1).

## 3. Bladeren en bekijken

### Het raster met miniaturen

In de werkbalk boven de miniaturen kun je:

- **filteren** op bestandstype: **Alle**, **Afbeeldingen**, **Alleen RAW** of **Video's** (één keuze tegelijk; de aantallen in de zijbalk en de albumomslagen veranderen er niet door). In hetzelfde menu zet je **Alleen favorieten** aan;
- **groeperen** op map, dag, maand, jaar, beoordeling, locatie, camera, objectief, bestandstype of schiftstatus;
- **sorteren** op opnamedatum, aanmaakdatum, wijzigingsdatum, naam, grootte, afmetingen, duur, willekeurig of **Toegevoegd** (de volgorde waarin bestanden aan Lap zijn toegevoegd);
- de **Selectie** openen (zie Selecteren hieronder);
- **Duplicaten** en vergelijkbare foto's zoeken (hoofdstuk 6);
- de **Kaart** tonen;
- **Info** tonen of verbergen voor het infopaneel rechts.

Miniaturen maak je groter of kleiner met **=** en **-**. Stijl, schaling en labels onder de miniaturen stel je in via **Instellingen → Indeling** (*Layout*). Grote bibliotheken bladeren sinds 0.4.0 een stuk sneller: Lap laadt eerst de miniaturen die in beeld zijn.

Toont een map onder **Albums** geen bestanden terwijl er wel submappen met foto's zijn? Open dan het **⋯**-menu bovenaan **Albums** in de zijbalk en zet **Bestanden uit submappen tonen** aan (*Show files from subfolders*). In hetzelfde menu stel je de **Mapvolgorde** in.

Tags, Locaties en Camera's hebben een eigen zoekveld in de zijbalk, en je kunt de resultaten direct in de weergave sorteren.

### Selecteren

- Klik op een miniatuur; met **Ctrl** of **Shift** erbij selecteer je er meer. Lap gaat dan vanzelf in de selectiemodus.
- **Ctrl+A** selecteert alles, **Ctrl+D** niets, **Ctrl+I** keert de selectie om.
- In de selectiemodus staat rechtsboven een balkje met het aantal geselecteerde bestanden (bijvoorbeeld *12 geselecteerd*). Klik erop voor het **Selectie**-paneel, met bulkacties: favoriet, taggen, beoordelen, in een collectie zetten, verplaatsen, kopiëren, verwijderen of een collage maken. De statusbalk onderaan toont het aantal items en de totale grootte.
- Je kunt de selectiemodus ook starten met de knop **Selectie** in de werkbalk. Stoppen doe je met het kruisje in het balkje (**Selectiemodus beëindigen**) of met **Esc**.
- Een RAW+JPEG/HEIC-paar of een Live Photo telt als één item, ook bij selecteren, slepen, kopiëren en verwijderen.

### Bestanden naar buiten slepen

Sleep miniaturen uit het raster of de viewer naar je bestandsbeheerder, je bureaublad of een andere app (bijvoorbeeld een e-mail). Lap geeft dan de echte bestanden mee, tot 1000 tegelijk. Bij een album op een losgekoppelde schijf, of bij bestanden die alleen online in de cloud staan, kan dat niet, omdat de originelen nodig zijn.

Alleen het pad nodig, bijvoorbeeld om in een ander programma te plakken? Druk op **Ctrl+Shift+C** (Mac: **⌥⌘C**) of gebruik het knopje **Bestandspad kopiëren** in het infopaneel.

### Foto's en video's bekijken

1. Dubbelklik op een miniatuur, of selecteer hem en druk op **spatie** voor de snelle weergave. Nog eens **spatie** sluit hem weer.
2. Met **←** en **→** ga je naar het vorige of volgende bestand, met **Esc** sluit je.
3. Zoom met **=** en **-** of het muiswiel; **Z** wisselt tussen passend in venster en ware grootte.
4. Bij een video pauzeert of hervat **spatie** het afspelen.
5. Start een diavoorstelling met de knop **Diavoorstelling** in de werkbalk van de viewer. Interval en overgang staan bij **Instellingen → Viewer**.
6. **F11** (Mac: **⌃⌘F**) schakelt volledig scherm in of uit. Ook dan zie je labels met de belangrijkste gegevens, zoals sterren en favoriet.

Houd **Ctrl** of **Shift** ingedrukt tijdens het dubbelklikken om een apart venster te openen. Live Photos en Motion Photos hebben een label *LIVE* of *MOTION* en spelen hun beweging af. Als je de muis boven een knop houdt, zie je ook de sneltoets ervan.

**Scherpstelpunt bekijken:** bij veel camera's kan de viewer laten zien waar de autofocus lag. Klik in de werkbalk op **AF-gebieden tonen** of druk op **Alt+A** (Mac: **⌥A**). Heeft de foto geen bruikbare AF-gegevens, dan meldt Lap dat.

**Foto's naast elkaar vergelijken:** selecteer twee tot vier foto's, klik met rechts en kies **Vergelijken** (*Compare*). Met **Zoomen en verschuiven koppelen** zoom je in alle foto's op dezelfde plek in.

### Het infopaneel

Druk op **I** om het infopaneel (**Informatie**) te tonen of te verbergen. Het is ingedeeld in blokken, zoals **Organisatie** (sterren, tags, titel, beschrijving, maker, copyright), **Bestand**, **Opname** (camera, objectief en **Belichting**), **Locatie** en **Overige informatie** (de oorspronkelijke metadata uit het bestand). Klik op een camera, objectief of plaats om alle foto's te zien die dat delen.

- Bepaal zelf wat je ziet via **Velden aanpassen**: kies bij **Zichtbare velden** voor **Standaard**, **Alles tonen** of **Aangepast**, en zet eventueel **Lege velden automatisch verbergen** aan.
- Druk op **M** (of klik op **Metadata bewerken**) om titel, koptekst, beschrijving, maker en copyright in te vullen. Zie hoofdstuk 4.
- Bij een video klik je op **Miniatuur wijzigen** om een ander beeld uit de video als miniatuur te gebruiken; klik nog eens voor het volgende beeld.

### Kaart

1. Klik in de werkbalk op **Kaart** (*Map*). De kaart toont de foto's en video's met locatie uit de huidige weergave, inclusief je filters.
2. Klik op een groep om de foto's van die plek te bekijken.
3. Wissel tussen **Standaard**, **Satelliet** en **Hittekaart**.

De kaart zelf wordt van internet geladen; je foto's worden niet geüpload. Locaties uit foto's van vivo- en andere MediaTek-telefoons staan sinds 0.4.0 ook goed op de kaart.

### Scherpte controleren

Zet **Instellingen → Viewer → Scherpteraster in de navigator** aan. De navigator (het kleine overzichtsbeeld in de viewer) markeert dan de scherpe delen van de foto, handig om bij een serie te kiezen welke foto het scherpst is.

### RAW-foto's

Lap kan van een RAW-bestand het **ingesloten voorbeeld** van de camera tonen (snel) of de RAW zelf **renderen** (nauwkeuriger). De instellingen staan bij **Instellingen → RAW**:

| Instelling | Keuzes |
| --- | --- |
| **RAW-paren groeperen** | Toont bij elkaar horende RAW- en JPEG/HEIC-bestanden (en Live Photos) als één item |
| **Standaardweergave voor paren** | De RAW of de **JPEG / HEIC** |
| **Standaardvoorbeeldbron** | **Ingesloten voorbeeld**, **RAW renderen** of **Automatisch oplichten** (gerenderd en lichter gemaakt); ontbreekt de ene, dan gebruikt Lap de andere |

In de viewer wissel je per foto van voorbeeldmodus via het RAW-label of met **Alt+R** (Mac: **⌥R**), of toon je de gekoppelde JPEG/HEIC. Bij inzoomen rendert Lap de RAW op volle resolutie.

Met **RAW-paren groeperen** aan gedraagt een paar zich overal als één foto: bij bladeren, selecteren, importeren, slepen, kopiëren en bij duplicaten. Bij verwijderen kies je wat er weg moet (zie hoofdstuk 4).

### Handige sneltoetsen

Alle sneltoetsen staan in **Instellingen → Sneltoetsen** (*Shortcuts*). Sinds 0.4.0 werken ze op de letter die op de toets staat, dus ook op een AZERTY-, Dvorak- of Colemak-toetsenbord. Een aantal sneltoetsen is in 0.4.0 veranderd; die zijn in de tabel **vet** gezet.

| Actie | Toets | Op een Mac |
| --- | --- | --- |
| Snelle weergave openen / sluiten | Spatie of Enter / Esc | Spatie / Esc |
| Vorige / volgende | ← / → | |
| **Ware grootte / passend in venster** | **Z** | |
| **Video pauzeren / hervatten** | **Spatie** | |
| Info tonen | I | |
| Favoriet | F | |
| Sterren geven / wissen | 1 – 5 / 0 | |
| Gekozen / afgewezen / niet bekeken | P / X / U | |
| **Hetzelfde en meteen naar de volgende foto** | **Shift + F, 0 – 5, P, X of U** | |
| Tags / collecties | T / B | |
| **Metadata bewerken (titel, beschrijving…)** | **M** | |
| **Foto bewerken** | **Ctrl+E** | **⌘E** |
| Verwante foto's zoeken | S | |
| **Openen in externe app** | **Ctrl+Shift+E** | **⇧⌘E** |
| Naam wijzigen (bij meerdere: batch hernoemen) | F2 | Enter |
| **Verplaatsen binnen bibliotheek** | **Ctrl+Shift+M** | **⇧⌘M** |
| **Bestandspad kopiëren** | **Ctrl+Shift+C** | **⌥⌘C** |
| Naar prullenbak | Delete | ⌘⌫ |
| **Definitief verwijderen** | **Shift+Delete** | **⌘⌥⌫** |
| **AF-gebieden tonen / verbergen** | **Alt+A** | **⌥A** |
| **RAW-voorbeeldmodus wisselen** | **Alt+R** | **⌥R** |
| **Volledig scherm** | **F11** | **⌃⌘F** |
| Alles selecteren | Ctrl+A | ⌘A |
| Zijbalk tonen / verbergen | Ctrl+B | ⌘B |
| Zoeken | Ctrl+/ | ⌘/ |
| Instellingen | Ctrl+, | ⌘, |

Let op bij oude gewoontes: **C** (opmerking) bestaat niet meer, gebruik **M** voor de beschrijving. **Shift+P** start geen diavoorstelling meer, maar markeert een foto als gekozen en gaat naar de volgende; de diavoorstelling start je met de knop **Diavoorstelling** in de viewer. **E** opent de editor niet meer; dat is nu **Ctrl+E**.

## 4. Ordenen

Alles in dit hoofdstuk — favorieten, sterren, schiften, tags, beschrijvingen, collecties en slimme albums — bewaart Lap in zijn eigen bibliotheek. Favorieten, sterren, schiftmarkeringen, tags en beschrijvingen kun je daarnaast zelf naar XMP-sidecars schrijven, zodat andere programma's ze ook zien (zie hoofdstuk 7 en 8).

### Favorieten en sterren

- Druk op **F** om een foto favoriet te maken, nog eens om dat ongedaan te maken.
- Druk op **1** tot **5** voor sterren, **0** om de beoordeling te wissen.

Dat werkt in het raster, in de viewer en op een selectie. Houd je **Shift** ingedrukt (bijvoorbeeld **Shift+F** of **Shift+4**), dan springt Lap daarna meteen naar de volgende foto. Je vindt ze terug onder **Bibliotheek** in de zijbalk.

### Schiften: kiezen of afwijzen

Hiermee ga je snel door een fotoserie en bepaal je wat je bewaart.

1. Open de eerste foto met **spatie**.
2. Druk per foto op **P** (gekozen), **X** (afgewezen) of **U** (niet bekeken) en daarna op **→**. Sneller: **Shift+P**, **Shift+X** of **Shift+U** markeert en gaat meteen door naar de volgende.
3. Open daarna **Bibliotheek → Schiften** (*Culling*) voor alle **Gekozen** of **Afgewezen** foto's.
4. Afgewezen foto's weggooien: open **Afgewezen**, selecteer alles met **Ctrl+A** en druk op **Delete** (Mac: **⌘⌫**).

### Tags

1. Selecteer een of meer bestanden en druk op **T** (of rechtsklik → **Tags…**).
2. Vink bestaande tags aan of typ een nieuwe naam. Met **Alleen geselecteerde tags tonen** zie je in een lange lijst alleen wat al is aangevinkt.
3. Bekijk je tags onder **Tags** in de zijbalk.

Sinds 0.4.0 staan tags in een **boom** in plaats van in groepen. Een tag kan subtags hebben, bijvoorbeeld *Familie → Opa en oma* of *Vakanties → 2025 → Frankrijk*.

- In het tagvenster (**T**) verschijnen knopjes als je de muis boven een tag houdt: **Nieuwe subtag** maakt een tag eronder, **Wijzig naam** past de naam direct in de lijst aan. Tagnamen mogen geen `,` `;` of `|` bevatten.
- Sleep in de zijbalk een tag om hem van volgorde te wisselen of onder een andere tag te hangen; zijn subtags gaan mee. Sleep hem naar **Hoofdniveau** om hem weer bovenaan de boom te zetten.
- Zoeken en tellen gebeurt inclusief subtags: klik je op *Vakanties*, dan zie je ook de foto's met *Frankrijk*.
- **Verwijderen** van een tag verwijdert ook zijn subtags. Je foto's blijven bestaan, en een verwijderde tag komt niet terug als je een album opnieuw scant.

Hiërarchische trefwoorden uit een ander programma, zoals digiKam, neemt Lap als boom over, zonder dubbele tags.

### Beschrijving, titel en andere metadata

Wat vroeger *opmerking* heette, heet nu **Beschrijving**. Je vult hem in via rechtsklik → **Beschrijving…**. Beschrijvingen zijn doorzoekbaar.

Meer velden tegelijk invullen? Druk op **M** of klik in het infopaneel op **Metadata bewerken**. Je kunt dan **Titel**, **Koptekst**, **Beschrijving**, **Maker** (één per regel) en **Copyright** invullen. Welke velden je ziet, bepaal je met **Velden aanpassen** onder **Organisatie** in het infopaneel.

Deze gegevens staan eerst alleen in Lap. Wil je ze in de bestanden zelf hebben, gebruik dan **Metadata opslaan in XMP** (hoofdstuk 7).

### Collecties

Een collectie is een zelfgekozen set bestanden van overal uit je bibliotheek, bijvoorbeeld voor een fotoboek. Er wordt niets gekopieerd of verplaatst.

1. Open onderaan de zijbalk **Collecties** en klik op **Nieuwe collectie**.
2. Sleep bestanden op de collectie, of selecteer ze en druk op **B**.
3. Klik op een collectie om hem te bekijken. **Uit collectie halen** haalt het bestand alleen uit de collectie; het bestand zelf blijft bestaan.

### Slimme albums

Een slim album is een opgeslagen zoekopdracht die zichzelf bijwerkt, bijvoorbeeld *5 sterren, dit jaar gemaakt, met GPS*.

1. Open **Slimme albums** in de zijbalk en klik op **+** (**Nieuw slim album**).
2. Geef een naam en kies of bestanden aan **Alle regels** of **Een van de regels** moeten voldoen.
3. Voeg regels toe met **Regel toevoegen**: **Mapnaam**, **Bestandsnaam**, bestandstype, beoordeling, favoriet, schiften, datums, grootte, afmetingen, oriëntatie, GPS, tag, persoon, album, collectie, camera, objectief of locatie. Bij lange lijsten (tags, personen, camera's, objectieven…) typ je in het vak **Filteren…** om snel de juiste waarde te vinden.
4. Stel eventueel **Groeperen**, **Sorteren** en **Volgorde** in en sla op.

### Bestanden hernoemen, verplaatsen en verwijderen

Doe dit in Lap in plaats van in je bestandsbeheerder. Lap werkt dan meteen zijn catalogus bij, houdt tags en beoordelingen aan het bestand gekoppeld en houdt bij elkaar horende bestanden samen, zoals Live Photo-video's, RAW+JPEG-paren en XMP-sidecars.

| Actie | Hoe |
| --- | --- |
| Naam wijzigen | **F2** (Mac: **Enter**), of rechtsklik → **Wijzig naam** |
| Meerdere bestanden tegelijk hernoemen | selecteer ze en druk op **F2** (Mac: **Enter**): zie *Batch hernoemen* hieronder |
| Verplaatsen binnen je bibliotheek | **Ctrl+Shift+M** (Mac: **⇧⌘M**), of rechtsklik → **Verplaatsen / kopiëren → Verplaatsen binnen bibliotheek…** |
| Verplaatsen of kopiëren naar een map buiten je bibliotheek | rechtsklik → **Verplaatsen / kopiëren → Verplaatsen naar map…** of **Kopiëren naar map…** |
| Nieuwe map | rechtsklik op een map onder **Albums** → **Nieuwe map** |
| Naar de prullenbak | **Delete** (Mac: **⌘⌫**) |
| Definitief verwijderen | **Shift+Delete** (Mac: **⌘⌥⌫**); Lap vraagt altijd eerst om bevestiging |

**Batch hernoemen:** typ bij **Naam** een nieuwe naam, kies bij **Begin bij** het eerste nummer en bij **Cijfers** hoeveel cijfers het nummer krijgt (bijvoorbeeld `001`), of **Geen nullen**. Het **Voorbeeld** toont per bestand de **Huidige naam** en de **Nieuwe naam**; de eerste 100 worden getoond, maar alle geselecteerde bestanden worden hernoemd.

**Verwijderen van een RAW-paar:** Lap vraagt welke bestanden van het paar weg moeten: **Beide bestanden**, **Alleen RAW** of **Alleen JPEG / HEIC**.

Wat de **Delete**-toets standaard doet, stel je in bij **Instellingen → Geavanceerd → Bestanden verwijderen → Bij het verwijderen van bestanden**: **Naar prullenbak** (één bestand gaat dan zonder vraag naar de prullenbak) of **Definitief verwijderen** (altijd met bevestiging). Lap onthoudt die keuze. Kan een bestand niet naar de prullenbak, bijvoorbeeld op een netwerkschijf zonder prullenbak, dan vraagt Lap of het definitief verwijderd mag worden.

Een **album verwijderen** (rechtsklik → **Verwijderen**) haalt het alleen uit Lap. De map en de bestanden blijven gewoon op je schijf staan. **Map verwijderen** verwijdert wel de map met alle bestanden en submappen erin; Lap controleert vlak voor het verwijderen nog eens of het om de juiste map gaat, en weigert een albummap zelf of de map waarin je bibliotheek staat.

## 5. Zoeken en personen

Alle zoekfuncties draaien op je eigen computer; er gaat niets naar een online dienst.

### Zoeken door te beschrijven

1. Open **Zoeken** in de zijbalk, of druk op **Ctrl+/**.
2. Typ wat je zoekt, bijvoorbeeld `dog on the beach` of `red car`.
3. Lap toont **Visuele overeenkomsten** (foto's die op je beschrijving lijken) en **Tekstovereenkomsten** (bestandsnamen, beschrijvingen en metadata zoals maker, copyright en software met je woorden).

Zoeken op beschrijving werkt pas als een album klaar is met *Zoeken voorbereiden*. Te veel of te weinig resultaten? Pas **Instellingen → Zoeken → Zoekovereenkomst** aan: *Strikt* geeft minder maar betere treffers, *Ruim* geeft er meer.

### Zoeken in het Nederlands

Het standaardmodel begrijpt **alleen Engels**. Zo zoek je in het Nederlands of een van de 50+ andere talen:

1. Open **Instellingen → Zoeken** (*Settings → Search*).
2. Kies bij **Kies model** voor **Meertalig** (*Multilingual*).
3. Bevestig de download; dat is eenmalig een paar honderd megabyte. Valt je verbinding weg of sluit je Lap, dan gaat de download later verder waar hij gebleven was.
4. Start Lap opnieuw zodra het model klaar is.

### Zoeken op tags

Klik onder **Tags** in de zijbalk op een tag om de foto's te zien. Een tag met subtags toont ook de foto's van alle subtags, en het getal erachter telt die mee. Met het zoekveld boven de lijst (**Tags zoeken**) vind je een tag snel terug; houd de muis boven een lange tagnaam om het hele pad te zien.

### Verwante foto's zoeken

Selecteer een foto en druk op **S** (of rechtsklik → **Verwante foto's zoeken**) voor foto's die erop lijken: dezelfde plek, een serie of bewerkte versies.

### Personen (gezichtsherkenning)

Gezichtsherkenning staat **standaard uit** en is nog in bèta.

1. Open **Instellingen → Zoeken** en zet onder **Personen zoeken** de optie **Gezichtsherkenning inschakelen** aan (*People search → Enable face recognition*). **Personen** verschijnt nu in de zijbalk.
2. Open **Personen**, klik bovenaan op het **⋯**-menu en kies **Gezichten indexeren** (*Index faces*). Bij grote bibliotheken duurt dat even; je kunt gewoon doorwerken.
3. Klik op een persoon om zijn of haar foto's te zien. Via het **⋯**-menu bij een persoon geef je een naam.

Worden verschillende mensen samengevoegd, of één persoon over meerdere groepen verdeeld? Pas dan **Groeperingsdrempel** aan onder **Personen zoeken** en begin opnieuw met **Index resetten** en daarna **Gezichten indexeren**.

### Mappen uitsluiten van zoeken

Klik met rechts op een map onder **Albums** en kies **Uitsluiten van zoeken**, bijvoorbeeld voor een map met schermafbeeldingen. Met **Opnemen in zoeken** draai je dat terug. Ook in grote bibliotheken werkt dat sinds 0.4.0 snel.

## 6. Duplicaten en vergelijkbare foto's

Lap vindt twee soorten dubbelen: **duplicaten** zijn exact dezelfde bestanden, ook met een andere naam of in een andere map; **vergelijkbare afbeeldingen** lijken op elkaar, zoals een serie snel achter elkaar genomen foto's.

Lap zoekt altijd in de huidige weergave. Open **Bibliotheek → Alle bestanden** om je hele bibliotheek te controleren, of één album, map of collectie voor alleen dat deel. Heb je bestanden geselecteerd, dan wordt alleen de selectie gecontroleerd. Bestanden die alleen online in de cloud staan, slaat Lap over; dat aantal staat in de resultaten.

### Bewaarregels instellen

Met **Bewaarregels** bepaal je vooraf welke kopie Lap automatisch op **Behouden** zet. Je opent ze in het duplicatenpaneel. De regels gelden in alle vensters van Lap en worden in deze **Prioriteitsvolgorde** toegepast:

| Regel | Keuzes |
| --- | --- |
| **Voorkeursmappen** | Klik op **Map toevoegen** voor mappen waarin je de originelen wilt houden. Submappen tellen mee; wat hoger in de lijst staat, gaat voor. Versleep mappen om de volgorde te wijzigen. |
| **Voorkeursformaat** (alleen vergelijkbare afbeeldingen) | **RAW eerst**, **JPEG / HEIC eerst** of **Negeren** |
| **Voorkeursgrootte** (alleen vergelijkbare afbeeldingen) | **Hoogste resolutie**, **Laagste resolutie**, **Grootste bestandsgrootte**, **Kleinste bestandsgrootte** of **Negeren** |
| **Voorkeursdatum** | **Oudste aanmaakdatum**, **Nieuwste aanmaakdatum**, **Oudste wijzigingsdatum** of **Nieuwste wijzigingsdatum** |

De twee helften van een RAW+JPEG-paar worden nooit als elkaars duplicaat behandeld.

### Duplicaten opruimen

1. Open de weergave en klik in de werkbalk op **Duplicaten**.
2. Blijf op het tabblad **Duplicaten** en wacht tot de scan klaar is. Je ziet de duplicaatsets en hoeveel ruimte **vrij te maken** is.
3. Klik op een set. In elke set is één bestand gemarkeerd als **Behouden** (het slotje), volgens je bewaarregels.
4. Liever een andere kopie? Klik op het slotje bij dat bestand. Met **Vergelijken** zie je de kopieën naast elkaar.
5. Opruimen: **Selectie verwijderen** verwijdert de geselecteerde kopieën in deze set; **Alles naar de prullenmand verplaatsen** doet dat in alle sets tegelijk voor elke kopie die niet op *Behouden* staat.

De bestanden gaan naar de prullenbak van je computer, dus je kunt ze nog terugzetten. Heb je bij **Instellingen → Geavanceerd** gekozen voor definitief verwijderen, dan heet de knop **Alles verwijderen** en gaan de bestanden niet naar de prullenbak.

### Vergelijkbare foto's bekijken

1. Open het tabblad **Vergelijkbare afbeeldingen** en klik op **Analyseren**. Bij veel foto's kan dat enkele minuten duren.
2. Loop de **Vergelijkbare sets** door. Lap heeft volgens je bewaarregels al een foto op *Behouden* gezet; pas dat zo nodig aan met het slotje, selecteer de rest en klik op **Selectie verwijderen**.

Hoe sterk foto's moeten lijken om in dezelfde set te komen, stel je in via **Instellingen → Zoeken → Vergelijkbare foto's → Strengheid groeperen**. Voor het kiezen van de beste foto's uit een serie is schiften met **P** en **X** (hoofdstuk 4) vaak sneller.

## 7. Bewerken en externe apps

### Snel bewerken in Lap

Lap heeft een eenvoudige editor voor snelle correcties; voor zwaarder werk gebruik je je eigen fotoprogramma.

1. Selecteer één foto en druk op **Ctrl+E** (Mac: **⌘E**), of rechtsklik → **Bewerken…**.
2. Op het tabblad **Algemeen** kun je **Bijsnijden** (vrij of met een beeldverhouding), rechtzetten met **Hoek** (een liniaal voor elke gewenste hoek, die naar 0° terugspringt en met de pijltjestoetsen fijn bij te stellen is), **Linksom** / **Rechtsom draaien**, **Horizontaal** / **Verticaal spiegelen** en **Formaat wijzigen**.
3. Op het tabblad **Aanpassen** kies je een voorinstelling (zoals *Levendig*, *Warm* of *Zwart-wit*) of stel je helderheid, contrast, verzadiging, tint en vervaging zelf in. Met **Origineel bekijken** vergelijk je met het origineel.
4. Klik op **Opslaan** en kies **Origineel bestand overschrijven** of **Opslaan als nieuw bestand**, met een nieuwe naam, formaat (JPEG, PNG of WEBP) en kwaliteit.

Overschrijven kan niet ongedaan worden gemaakt. Twijfel je, sla dan op als nieuw bestand. **Weergave draaien** (**R** / **Shift+R**) draait de foto alleen op het scherm, niet het bestand zelf.

### Openen in een ander programma

1. Kies bij **Instellingen → Geavanceerd → Externe apps** een programma voor **Foto openen in** en **Video openen in**. Via **Externe apps beheren** voeg je er meer toe en kies je een standaard.
2. Selecteer een of meer bestanden en druk op **Ctrl+Shift+E** (Mac: **⇧⌘E**), of rechtsklik → **Openen in externe app…**.

Worden miniatuur of gegevens niet bijgewerkt nadat je een bestand in een ander programma hebt bewerkt? Klik er met rechts op en kies **Bestandsinfo vernieuwen**. Dat werkt ook voor meerdere geselecteerde bestanden tegelijk.

### Metadata opslaan in XMP

Lap kan je favorieten, sterren, schiftmarkeringen, tags en de velden uit **Metadata bewerken** (titel, koptekst, beschrijving, maker, copyright) in een **XMP-sidecar** schrijven: een klein `.xmp`-bestand naast de foto. Andere fotoprogramma's die XMP-sidecars lezen, zien die gegevens dan ook.

1. Selecteer een of meer bestanden.
2. Klik met rechts en kies **Metadata opslaan in XMP**.

Lap past alleen zijn eigen gegevens aan en laat de rest van een bestaande sidecar ongemoeid. De fotobestanden zelf worden niet gewijzigd. Hernoem, verplaats, kopieer of verwijder je een bestand in Lap, dan gaat de sidecar mee.

### Collage maken

Maak van een selectie foto's één afbeelding om te delen of af te drukken.

1. Selecteer minstens twee foto's, klik met rechts en kies **Collage maken** (*Create collage*). De collage opent in een eigen venster.
2. Kies bij **Indeling** een stijl: **Kaartweergave**, **Tegelweergave**, **Uitgevulde weergave** (mozaïek), **Metselweergave** of **Vrije collage** (een stapel foto's zoals in Picasa). In een vrije collage kun je foto's verslepen, draaien, groter of kleiner maken en naar voren halen; **Willekeurige collage** schudt de indeling.
3. Stel bij **Pagina** het **Formaat** in (A4, 10 × 15 cm, **Scherm 16:9** of **Vierkant**) en de **Oriëntatie**.
4. Kies bij **Stijl** de **Achtergrond**, **Tussenruimte**, **Rand** en eventueel **Schaduwen tekenen** of **Willekeurig draaien**.
5. Klik op **Afdrukken** of **Opslaan als**. Lap maakt de collage op volle resolutie uit de originele foto's.

Je instellingen worden onthouden voor de volgende collage.

## 8. Bibliotheekgegevens en back-ups

Je foto's en video's blijven altijd gewone bestanden in hun eigen mappen. Daarnaast houdt Lap een **bibliotheek** bij: een lokale database met alles wat Lap over je bestanden weet.

| Staat in het fotobestand (of de XMP-sidecar) | Staat in de bibliotheek van Lap |
| --- | --- |
| De foto of video zelf | Favorieten, sterren, gekozen en afgewezen |
| EXIF-gegevens: opnamedatum, camera, objectief, GPS, oriëntatie | Tags, beschrijvingen, titels en andere metadata |
| Bewerkingen die je in de editor hebt **opgeslagen** | Collecties en slimme albums |
| Wat je met **Metadata opslaan in XMP** hebt weggeschreven | Gezichten, zoekgegevens en miniaturen |

### Metadata van andere programma's

Lap leest bij elke scan en vernieuwing de metadata die al in je bestanden zit (EXIF en IPTC) en in XMP-sidecars ernaast: favorieten, sterren, tags, schiftmarkeringen, GPS, opnamedatum, titel, koptekst, beschrijving, maker en copyright. Staat iets zowel in het bestand als in de sidecar, dan wint de sidecar. Wat je zelf in Lap hebt aangepast, blijft behouden.

Dit staat standaard aan. Je zet het uit bij **Instellingen → Metagegevens → Metagegevens importeren → Uit EXIF, IPTC en XMP**.

Dat betekent:

- Wat je in Lap verandert, staat eerst alleen in de bibliotheek van Lap. Andere programma's zien het pas nadat je **Metadata opslaan in XMP** hebt gebruikt (hoofdstuk 7). Doe dat ook als je foto's naar een andere computer meeneemt.
- Hernoem of verplaats je bestanden **buiten** Lap, dan herkent Lap ze mogelijk niet als dezelfde bestanden en kunnen tags of sterren verloren gaan, tenzij ze ook in een XMP-sidecar staan. Doe dit dus in Lap (hoofdstuk 4).
- Lap verwijderen of de bibliotheek wissen verwijdert nooit je foto's.

### Back-up maken

1. Open **Instellingen → Geavanceerd** en klik onder **Onderhoud bibliotheekgegevens** op **Back-up**.
2. Kies de bibliotheken en bewaar het ZIP-bestand, bijvoorbeeld op je back-upschijf of NAS.

Terugzetten gaat via **Terugzetten** op dezelfde plek. Bibliotheken met een bestaande naam worden hernoemd; bestaande gegevens worden niet overschreven.

Extra zekerheid: schrijf je tags, sterren en beschrijvingen met **Metadata opslaan in XMP** naar sidecars (hoofdstuk 7). Die gaan mee in de gewone back-up van je fotomappen en zijn ook zonder Lap te lezen.

### Opslaglocatie wijzigen

Standaard bewaart Lap zijn bibliotheek in de gewone app-gegevensmap van je systeem. Een andere plek kiezen:

1. Klik bij **Instellingen → Geavanceerd** onder **Gegevenslocatie wijzigen** op **Wijzigen**.
2. Kies een map, bij voorkeur op een **lokale** schijf voor de beste snelheid.

Met **Standaardlocatie herstellen** zet je het terug. Tijdens het indexeren van een album of gezichten kan de locatie niet worden gewijzigd.

Lap verplaatst de gegevens veilig: kunnen sommige oude bestanden niet worden verwijderd, dan meldt Lap welke dat zijn, zodat je ze zelf kunt opruimen.

### Miniaturencache verplaatsen

De miniaturen kunnen veel ruimte innemen. Je kunt ze naar een andere schijf verplaatsen, los van de bibliotheek:

1. Klik bij **Instellingen → Geavanceerd → Miniaturencache** naast **Cachelocatie wijzigen** op de knop en kies een map.
2. Klik op **Starten**. Lap verplaatst de miniaturen van alle bibliotheken; de nieuwe plek wordt pas gebruikt als dat gelukt is. Breek je het af, dan blijft alles bij het oude.

Is die schijf later niet aangesloten, dan meldt Lap dat. Je kunt dan doorgaan met **Doorgaan en opnieuw maken**: Lap maakt de miniaturen zo nodig op de nieuwe plek opnieuw, en je foto's en bibliotheekgegevens blijven ongewijzigd. Op dezelfde plek kies je bij **Resolutie van miniaturen wijzigen** voor **Laag (256 px)**, **Standaard (512 px)** of **Hoog (1024 px)**.

### Meerdere bibliotheken

Extra bibliotheken zijn handig voor volledig gescheiden verzamelingen, zoals *Familie* en *Werk*, elk met eigen albums, tags en instellingen. Klik op de bibliotheeknaam bovenaan de zijbalk om te wisselen, of kies **Bibliotheken beheren…** om ze toe te voegen, te hernoemen, te verbergen of te verwijderen. Een bibliotheek verwijderen wist de database (albums, tags, sterren), maar nooit je foto's.

In **Bibliotheken beheren** zie je per bibliotheek hoeveel ruimte de miniaturencache inneemt; met **Ongebruikte cache opschonen** maak je die ruimte vrij.

### Externe schijven en NAS

- Koppel de schijf of netwerkmap eerst (op Windows met een stationsletter, op macOS onder `/Volumes`, op Linux meestal onder `/media` of `/mnt`) en voeg de map daarna toe als album.
- Is de schijf niet aangesloten, dan blijft het album zichtbaar met een waarschuwingsteken. Je kunt gewoon blijven bladeren door de opgeslagen miniaturen en gegevens, ook in **Alle bestanden**. Acties die het originele bestand nodig hebben (zoals bewerken en naar buiten slepen) zijn uitgeschakeld tot je de schijf weer aansluit.
- Gebruik steeds dezelfde koppeling of stationsletter. Lap bewaart volledige paden en kan de bestanden anders niet vinden.
- Scannen over het netwerk is trager dan lokaal, vooral de eerste keer.
- Sluit je de schijf weer aan, dan pakt Lap het album vanzelf weer op.

### Bestanden in iCloud of OneDrive

Mappen die met iCloud Drive (macOS) of OneDrive (*Bestanden op aanvraag*) worden gesynchroniseerd, kun je gewoon als album toevoegen. Bestanden die alleen online staan, neemt Lap op zonder ze te downloaden; ze krijgen het label **Alleen online beschikbaar**. Lap downloadt ze nooit vanzelf. Acties die het originele bestand nodig hebben, zoals openen op volle grootte, bewerken en naar buiten slepen, werken pas als het bestand op je computer staat: download het daarvoor in je cloud-app (bijvoorbeeld met *Altijd op dit apparaat bewaren*).

## 9. Problemen oplossen en veelgestelde vragen

Deze vragen komen uit de [GitHub-issues](https://github.com/julyx10/lap/issues) en van gebruikers.

### Foto's en albums

**Ik heb foto's toegevoegd, maar ze verschijnen niet.** Klik op **Vernieuwen** of kies met rechts op het album **Album scannen**. Voor een nieuwe submap: rechtsklik op de bovenliggende map → **Mappen vernieuwen**. Zie hoofdstuk 2.

**Moet ik voor nieuwe foto's steeds een nieuw album maken?** Nee, alleen voor foto's op een compleet nieuwe plek. Zie hoofdstuk 2 voor de andere manieren.

**Ik kan een map niet als album toevoegen.** Albums mogen elkaar niet overlappen. Bekijk de map binnen het album waar hij al in zit.

**Een map toont geen bestanden, maar heeft wel submappen met foto's.** Zet **Bestanden uit submappen tonen** aan in het **⋯**-menu bovenaan **Albums** in de zijbalk.

**Bestanden die ik buiten Lap (in mijn bestandsbeheerder) heb hernoemd of verwijderd, staan nog in Lap.** Kies **Mappen vernieuwen** op de bovenliggende map of **Album scannen**. Voorkom het door dit in Lap te doen.

**De scan is onderbroken.** Kies bij de volgende start **Doorgaan**. Blijft één bestand vastlopen, kies dan **Dit bestand overslaan en doorgaan**.

**Mijn album op een externe schijf of NAS is niet bereikbaar.** Je kunt gewoon blijven bladeren door de opgeslagen miniaturen. Voor bewerken, slepen en andere acties met het origineel koppel je de schijf opnieuw, met dezelfde stationsletter of koppeling. Zie hoofdstuk 8.

**Kan ik foto's gebruiken die alleen online in iCloud of OneDrive staan?** Ja, sinds 0.4.0 toont Lap ze met het label **Alleen online beschikbaar**, zonder ze te downloaden. Om ze te openen, te bewerken of te slepen moet je ze eerst in je cloud-app downloaden. Bij het zoeken naar duplicaten slaat Lap ze over. Zie hoofdstuk 8.

**Kan ik Lap vanaf een USB-stick op verschillende computers gebruiken?** Nog niet. Lap bewaart volledige paden, dus een bibliotheek verhuist niet mee naar een andere computer of stationsletter.

**Datums staan in een andere notatie dan ik verwacht.** Lap volgt standaard de regio-instelling van je computer. Op Windows volgt Lap sinds 0.4.0 ook je eigen datumnotatie uit de regio-instellingen. Kies bij **Instellingen → Algemeen → Datum- en tijdnotatie** voor **App-taal volgen** als je de notatie van de gekozen taal wilt.

**Mijn RAW-foto's zien er donkerder of anders uit dan in de camera.** Kies bij **Instellingen → RAW** een andere **Standaardvoorbeeldbron**: het **Ingesloten voorbeeld** lijkt het meest op de camera, **Automatisch oplichten** maakt een gerenderde RAW lichter. In de viewer wissel je per foto via het RAW-label of met **Alt+R** (Mac: **⌥R**).

**Ik wil alleen de JPEG van een RAW-paar weggooien.** Druk op **Delete** en kies **Alleen JPEG / HEIC**. Zie hoofdstuk 4.

**Sneltoetsen doen niets of iets anders op mijn AZERTY-toetsenbord.** Werk bij naar 0.4.0: sneltoetsen volgen nu de letter op de toets. Let op: een paar sneltoetsen zijn veranderd, zoals **Ctrl+E** voor bewerken en **Z** voor zoomen (zie de tabel in hoofdstuk 3).

### Zoeken en personen

**Zoeken in het Nederlands geeft rare of geen resultaten.** Het standaardmodel begrijpt alleen Engels. Kies **Meertalig** bij **Instellingen → Zoeken → Kies model** en start Lap opnieuw.

**Het downloaden van het meertalige model mislukt.** Start de download opnieuw; sinds 0.4.0 gaat hij verder waar hij gebleven was, ook na een herstart van Lap.

**Ik zie geen Personen in de zijbalk.** Gezichtsherkenning staat standaard uit. Zet hem aan bij **Instellingen → Zoeken → Personen zoeken** en kies daarna **Gezichten indexeren**.

**Zoeken op beschrijving vindt mijn nieuwste foto's niet.** Wacht tot de scan klaar is met *Zoeken voorbereiden*.

### Tags en gegevens

**Andere programma's zien mijn tags en sterren niet.** Die staan in de bibliotheek van Lap. Selecteer de foto's en kies rechtsklik → **Metadata opslaan in XMP**. Zie hoofdstuk 7.

**Mijn tags en sterren uit een ander programma verschijnen niet in Lap.** Controleer of **Instellingen → Metagegevens → Uit EXIF, IPTC en XMP** aanstaat en kies **Album scannen**. Na een update naar 0.4.0 leest Lap alle bestanden één keer opnieuw in; dat kan bij een grote bibliotheek even duren.

**Waar zijn mijn taggroepen gebleven?** Sinds 0.4.0 staan tags in een boom met subtags. Zie hoofdstuk 4.

**Waar is de opmerking (C) gebleven?** Die heet nu **Beschrijving**: rechtsklik → **Beschrijving…** of **M** voor **Metadata bewerken**.

**Ik heb een eigen opslaglocatie gekozen, maar de oude map bestaat nog.** Sinds versie 0.3.3 meldt Lap na het verplaatsen welke oude bestanden niet konden worden verwijderd. Controleer eerst of Lap goed werkt met de nieuwe locatie en maak een back-up. Verwijder de genoemde oude bestanden pas daarna, met Lap afgesloten.

### Installatie

**Hoe zet ik Lap in het Nederlands?** Sinds 0.4.0 start Lap de eerste keer vanzelf in de taal van je computer. Anders: **Settings → General → Language & region → Select language → Nederlands**.

**Windows SmartScreen blokkeert de installatie.** De Windows-installer is nog niet ondertekend. Kies **Meer informatie → Toch uitvoeren**, of **Toch behouden** als de browser de download blokkeert.

**Windows zet na elke update een snelkoppeling op het bureaublad.** Dat is een bekende beperking van de installer; verwijder de snelkoppeling gewoon.

**Hoe werk ik de AppImage-versie bij?** Download de nieuwe AppImage van de [releasepagina](https://github.com/julyx10/lap/releases/latest) in plaats van de ingebouwde updater te gebruiken. Wie AppImageUpdate of AppImageLauncher gebruikt, kan daarmee ook alleen de wijzigingen downloaden.

**Video's spelen niet af op Linux.** Installeer de GStreamer-plug-ins: `sudo apt install gstreamer1.0-libav gstreamer1.0-plugins-good`.

**Een videoformaat wordt niet ondersteund.** Stel een externe speler in bij **Instellingen → Geavanceerd → Externe apps** en open de video met **Ctrl+Shift+E** (Mac: **⇧⌘E**).

### Kom je er niet uit?

Zoek in de [bestaande issues](https://github.com/julyx10/lap/issues) of maak een nieuwe aan (in het Engels). Vermeld je besturingssysteem, je Lap-versie (**Instellingen → Over**) en de stappen om het probleem na te doen.

---

## Licentie

© 2026 Mc5. Deze handleiding valt onder de licentie [Creative Commons Naamsvermelding 4.0 Internationaal (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.nl). Je mag de tekst delen en bewerken, ook voor commerciële doeleinden, zolang je Mc5 als maker vermeldt, naar deze licentie linkt en aangeeft of je iets hebt veranderd.

Lap zelf is een project van [julyx10](https://github.com/julyx10/lap) en valt onder een eigen licentie (GPL-3.0-or-later).
