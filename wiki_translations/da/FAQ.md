---
title: FAQ
---
{% start_liquid main_title %}

General Questions

{% end_liquid %}

{% start_liquid qa %}

Hvad er SuperTuxKart?

SuperTuxKart er et 3D open-source kart racerspil. Det går efter, at det skal være sjovt for spillere uanset niveau ved hjælp af gaveæsker med tilfældigt indhold, nitro, drifting og mere.
Fokus er ikke på realisme.

STK har multiplayertilstand, lokal multiplayertilstand, enkeltspillertilstand mod AI'er både med tilpassede løb og en fortællertilstand til at låse op for nye karts og baner. Det indeholder også Grand Prix, hvor målet er at få flest point over mange løb.

De 21 baner vil lede dig ind i forskellige miljøer. Fra strandene på solfyldte øer til underjordiske dybder i en gammel mine, fra Candela City's gader til fredfyldte veje på landet, fra et rumskib til bjergene. Du har meget at udforske og opdage.

Spillet indeholder også yderligere spiltilstande ud over normale løb: Tidskørsel, følg lederen, fodbold, erobre flaget og to typer kamptilstand.

[Find mere her](Discover)!

{% end_liquid %}

{% start_liquid qa %}

Hvem står bag SuperTuxKart?

Se vores [Team](Team)-side for at få oplysninger om folkene bag SuperTuxKart!

{% end_liquid %}

{% start_liquid qa %}

Hvad er hardwarekravene?

**GPU**

GPU'en er normalt begrænsningen for STK's ydeevne. Kort, der opfylder minimumskravene, har OpenGL-understøttelse til at køre spillet, men kræver lav opløsning og lav grafik for at spille flydende. Kort, der opfylder eller overstiger de anbefalede krav, kan køre STK's mest krævende bane ved 60 FPS/1080p med den moderne renderingspipeline på grafik 4.

* **Anbefalet**: NVIDIA GeForce GTX 950, AMD Radeon RX 460 eller bedre. Mindst 1 GB VRAM (videohukommelse).
* **Minimum**: NVIDIA GeForce 470 GTX, AMD Radeon 6870 HD series card eller Intel HD Graphics 4000. Mindst 512 MB VRAM (videohukommelse).

**CPU**

CPU-performance kan være flaskehalsen afhængig af grafikkort og grafikindstillinger,. Især ved online gaming der er mere CPU-krævende. God CPU-performance hjælper med til at sikre høj framerate og endnu mere vigtigt flydende grafik uden hak. STK har først og fremmest gavn af høj enkelttrådsperformance.

* **Anbefalet**: Core i5-2400 enkelttrådsperformance eller bedre. Det omfatter AMD Ryzen desktop CPU'er, de fleste Intel desktop CPU'er efter 2012 og nyere middel- til høj-ydelse mobile CPU'er.
* **Minimum**: Alle Intel eller AMD CPU'er med to kerne. Meget gamle modeller og lavfrekvens mobile CPU'er kan have det svært. Specielt ved online gaming.

**Andre forudsætninger**

* Mindst 1 GB fri hukommelse
* 700 MB diskplads

**Valgfrit**

* (Hvis du foretrækker at spille med et joystick.) Et joystick med mindst 6 knapper.

{% end_liquid %}

{% start_liquid qa %}

Min computer er for gammel til at køre SuperTuxKart. Hvad skal jeg gøre?

Du kan prøve, om det fungerer for dig. STK kan falde tilbage til en rendering, der kun bruger OpenGL 2.1 / GLES2 / DirectX 9, der burge fungere på de fleste enheder. Men det har ingen moderne renderingsstyring.

{% end_liquid %}

{% start_liquid qa %}

Hvad er SuperTuxKarts historie?

Først var der [TuxKart](http://tuxkart.sourceforge.net). Der blev arbejdet med det ca. april 2000 til marts 2004. Det blev i juni 2004 'Månedens spil'-projekt i [Linux Game Tome](https://web.archive.org/web/20040915081722/http://www.happypenguin.org/) besluttede at forbedre TuxKart. Det blev udført mellem juni og december 2004. (De fleste links til det gamle forum sider er døde. Arkiv kan nås her: [[1]](https://web.archive.org/web/20041109144934/http://www.happypenguin.org/forums/viewtopic.php?t=1407) [[2]](https://web.archive.org/web/20120607000453/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=15&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[3]](https://web.archive.org/web/20120606235857/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=30&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[4]](https://web.archive.org/web/20120607000143/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=45&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[5]](https://web.archive.org/web/20120607000320/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=60&sid=e3789fa7035b89cbfc1ab2aa6366033c) [[6]](https://web.archive.org/web/20120606235853/http://www.happypenguin.org/forums/viewtopic.php?t=1407&postdays=0&postorder=asc&start=75&sid=e3789fa7035b89cbfc1ab2aa6366033c). Projektet endte desværre pga. store uenigheder, og det blev besluttet at bevare den nuværende tilstand som "SuperTuxKart". Mens nogle grafiske forbedringer blev udført, var kodebasen meget ustabil og i praksis uspillelig. Ingen arbejdede på (Super)TuxKart i adskillige år.

I 2006 genoptog Joerg Henrichs (kendt som "Hiker") SuperTuxKart. Rettede udestående fejl og performanceproblemer uden at involvere den oprindelige spildesigner eller 'Månedens spil'-projektet. Med hjælp fra"Coz" var den første udgave af STK klar i september 2006.

I maj 2007 blev version 0.3 frigivet. Den tilføjede highscorelister, en ny bane (Island), tidsbomber, MacOSX-understøttelse og OpenAL-understøttelse.

Februar 2008 blev version 0.4 frigivet. Denne version brugte kuglefysik til at forbedre kollisionshåndtering. "Auria" kom til og begyndte at forbedre baner (Shifting Sands, Lighthouse).

Version 0.5 blev frigivet maj 2008. Den havde mange forbedrede baner, oplåselige udfordringer, følg lederen spiltilstand og flere oversættelser (OS sprogdetektor og tilpasning til nærmeste oversættelse).

Version 0.6 blev frigivet 22. januar 2009. Den havde væsentligt forbedret gameplay, bedre fysik med Nitro og udskridning. Lyden var også forbedret, mere interessant musik var tilføjet og mange baner og karts var tilføjet. Den havde også første udgave af specialmultiplayerarena for 3-ramt kamp og nye enheder/powerups.

Version 0.7 blev frigivet 20. december 2010. Den havde adskillige bemærkelsesværdige forbedringer som: Ny 3D-renderingsmaskine, Irrlicht, en ny GUI, nye kart- og baneanimationer, nye baner, karts og enheder/powerups og understøttelse af genveje/alternative veje. Versionerne 0.7.1, 0.7.2 og 0.7.3 blev frigivet kort efter med flere forbedringer.

Version 0.8 blev frigivet december 2012 med tilføjelse af historiemodus, nye udfordringer, forbedret AI og udskridning, omvendt tilstand, nye baner og musik. Menuerne blev også forbedret. Den blev fulgt op af 0.8.1, der tilføjede og opdaterede baner, tilføjede fodbold og æggejagt tilstande og andre grafiske og gameplay udvidelser.

I 2015 frigav vi version 0.9. En banebrydende udgave drevet af en helt ny spillemaskine kaldet Antarctica, der tilføjede avancerede grafiske funktioner, som før ville have været umulige. Disse funktioner inkluderer dynamisk belysning, instansrendering (der muliggør en stor forøgelse af vegetation) og meget mere. 0.9 blev fulgt af tre punktfrigivelser, der tilføjede yderligere funktioner og nye baner.

I april 2019 frigav vi version 1.0 for første gang nu med understøttelse af online multiplayer. Udover denne vigtige funktion var der nye og opdaterede baner, tilføjelse af SuperTux udfordringer i historiemodus, mange afbalancerende justeringer og mange flere forbedringer og rettelser.

Derefter meddelte Hiker sit valg om at trække sig tilbage fra projektet efter at have styret det i 13 år. Auria trådte også af fra hendes rolle som med-bestyrer, men fortsatte med at være involveret i projektet.

Projektlederskabet blev overført til Benau, en større kode bidragsyder siden 2017 og Alayan, en større bidragsyder til 1.0. Deveee, en vigtig bidragsyder i adskillige år, som var ansvarlig for Androidversionen, forblev i teamet.

Januar 2020 blev version 1.1 frigivet. Gameplay var uændret, da alle 1.x-versioner er kompatible. De større ændringer var forbedret net-kode og større UI-forbedringer specielt i store opløsninger sammenholdt med mange fejlrettelser og udvidelser.

August 2020 blev version 1.2 frigivet. Med forbedret gamepad-understøttelse via SDL2, der understøtter hotplug og gamepad-tilpasninger.

September 2021 blev den nyeste version 1.3 frigivet. Den indehold opdateringer for mange officielle karts.

For flere detaljer, se venligst [changelog](https://github.com/supertuxkart/stk-code/blob/master/CHANGELOG.md),  [blog posts](https://blog.supertuxkart.net) eller listen med rettede fejl på STK's GitHub.

{% end_liquid %}

{% start_liquid qa %}

Er SuperTuxKart en Mario Kart-klon?

Nej! Mario Kart-serien er det bedst kendte racerkart-spil, men der har været mange andre.

Ældre udgaver af STK forsøgte at efterabe Mario Kart, men det har ikke været tilfældet i meget lang tid. Vi ser af og til på det for at få inspiration, som vi gør det med andre kartspil. Men det er alt.

Udover de mange signifikante forskelle i gameplay udvikler SuperTuxKart sig på sin egen måde, og vi prøver ikke at tilpasse det tættere mod Mario Kart.

{% end_liquid %}

{% start_liquid qa %}

Jeg vil gerne hjælpe! Hvad kan jeg gøre?

Prøv først at se på [Hjælp med](Community)-siden. Den bør have al information, du behøver, til at gå i gang med kodning, modellering, design eller hvad du har lyst til at gøre.

Før du starter, bør du kontakte udviklerne og kunstnerne gennem [IRC](https://web.libera.chat/?channels=#supertuxkart), [Telegram-kanal](https://t.me/STKInternational) eller [forum](https://forum.freegamedev.net/viewforum.php?f=16) og sig os, hvad du vil opnå. Det forbedrer dine chancer for accept af dit bidrag gevaldigt.

{% end_liquid %}

{% start_liquid main_title %}

Spørgsmål til gameplay

{% end_liquid %}

{% start_liquid qa %}

AI'en (computer karten) skød bagud - hvordan kan jeg gøre det?

De fleste ting (bowlingkugler, kager, svuppere) kan bruges bagud. Bare skyd dem afsted, mens du ser bagud.

{% end_liquid %}

{% start_liquid qa %}

Snyder AI'en?

Nej!

Hastighedsgrænser og hastighedsforøgelser er de samme for alle karts, AI eller menneskelig. På lavere sværhedsgrader sænker AI'en  måske også farten med vilje. Powerup-sandsynligheder i gavepakker er identiske. Der er mindre forskelle i, hvor hurtigt karts kan styre fra en retning til en anden, men det giver ingen meningsfuld fordel til AI'en, og det er heller ikke meningen.

AI'en kan af og til have superhurtige reflekser, når den bruger powerups, men hvis et menneske trykker på højre knap på rette tid, kan han opnå samme resultat. Der er også råderum til at overgå den.

Hvis det er en kamp at slå AI'en fokusér på at forbedre din kørsel, så du undgår sammenstød så meget som muligt ved høje hastigheder. Lær at bruge udskridning. På højere sværhedsgrader er udskridning essentielt for at kunne slå AI'en.

{% end_liquid %}

{% start_liquid qa %}

Kan jeg spille STK på internettet?

Ja! Efter at have oprettet en online konto i spillet og forbundet dig til den, sælg "Online"-knappen i hovedmenuen. Dernæst "Global networking" for at tilgå netværksgameplay over internettet. Du kan være vært for din egen server, som andre kan spille på eller tilslutte dig fællesskabets servere. For at få den bedste oplevelse er en stabil forbindelse og hurtig ping til serveren vigtige størrelser.

{% end_liquid %}

{% start_liquid qa %}

Hvorfor virker nogle tastaturtaster ikke, når de trykkes ned samtidigt?

Når du spiller med dit tastatur får du måske problemer, når flere taster samtidigt trykkes ind. F.eks. at prøve nitro samtidig med at give gas og dreje. I den slags situationer kan det være, at nogle tastetryk ikke registreres. Det er ikke en fejl i SuperTuxKart, men en fysisk begrænsning på dit tastatur. De fleste tastaturer kan kun håndtere et vist antal samtidige tastetryk. (For mere detaljeret information se venligst [her] (https://www.sjbaker.org/wiki/index.php?title=Keyboards_Are_Evil)). Løsningen er at bruge en dedikeret spille-inputenhed. (Gamepad, gaming tastatur). Eller optimér tastekombinationer for at finde taster, som dit tastatur kan registrere simultant.

{% end_liquid %}

{% start_liquid qa %}

Jeg har mærkelige input-problemer

Det kan omfatte, at karten altid trækker til venstre eller tilfældigt bremser eller en anden mærkværdighed, hvor spillet ser ud til at tro, at du trykker en tast ned, når du ikke gør det. Hvis det sker så prøv at gå til indstillinger på inputskærmen og check om du har gamepads der. Prøv at slå alle gamepads fra undtagen den enhed, du bruger. Af og til kommer falsk input fra gamepads eller lignende enheder, som OS ser som en gamepad.

{% end_liquid %}

{% start_liquid qa %}

Pludselig fik jeg en stor rød cirkel på skærmen. Hvad er det?

Hvis der er en pingvin i midten af cirklen, har nogen skudt en svupper i ansigtet på dig. Du kan gøre det ved andre ved at skyde svupperen bagud. (Se FAQ om at skyde ting bagud.)

{% end_liquid %}

{% start_liquid qa %}

Kan jeg bruge min Wii remote med STK?

Ja! Se [Wiimote](Wiimote)-siden for detaljer.

{% end_liquid %}

{% start_liquid main_title %}

Tekniske spørgsmål

{% end_liquid %}

{% start_liquid qa %}

Jeg fandt en fejl. Hvordan skal jeg kontakte dig?

Se først på [STK bug tracker](https://github.com/supertuxkart/stk-code/issues) og åbn et nyt problem, hvis det ikke er indrapporteret.

{% end_liquid %}

{% start_liquid qa %}

Hvor er opsætningen gemt?

* I **Windows**: er det i `%APPDATA%/supertuxkart/config-0.10`. (Du kan skrive det ind i Explorer, og det vil tage dig derhen.)
* I **Linux**: er det enten i `$XDG_CONFIG_HOME/supertuxkart/config-0.10` (første valg), `~/.config/supertuxkart/config-0.10` (andet valg) eller i `~/.supertuxkart/config-0.10` (tredje valg).
* I **macOS**: er det i `~/Library/Application Support/supertuxkart/config-0.10`. Bemærk at folderen måske er skjult.

Du kan også se output på terminalen for at se, om der er en note om, hvor  konfigurationsfiler er lagret. Eller du kan søge efter en fil kaldet "config.xml".

{% end_liquid %}

{% start_liquid qa %}

Git-versionen vil ikke kompilere. Hvad skal jeg gøre?

Det sker af og til. Udviklerne bør være klar over det, og det bør blive fikset hurtigt. Hvis [GitHub aktioner](https://github.com/supertuxkart/stk-code/actions) siger, at den nuværende Git-version kompilerer, mens det ikke fungerer for dig, er der sandsynligvis noget galt med din kompileropsætning. (Check om du har alle afhængigheder, udfør CMake igen, ...)

{% end_liquid %}

{% start_liquid qa %}

Hvordan låser jeg alle baner op?

Den tiltænkte måde er fortælletilstand i spillet, hvor du klarer alle udfordringer.

Men hvis du vil låse alt op uden at spille fortælletilstand, kan du også snyde ved at redigere en config-fil. Åbn folderen nævnt ovenfor i spørgsmålet "Hvor lagrer STK brugeropsætningsfilen?". Derfra kan folderen "config-0.10" åbnes og derefter filen "players.xml". Erstat alle forekomster af "ingen" med "svær" (eller "nem" eller "medium" som indikator for det højeste niveau du har løst en udfordring).

{% end_liquid %}
