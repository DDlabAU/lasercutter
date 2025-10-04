# Brug af Lasercutteren i DD Lab
Der er en række ting, man skal være opmærksom på ved brug af lasercutteren og dem kan du læse om lige her.  

For at få adgang til lasercutteren, skal du kontakte en ansat i DDLab, enten i åbningstiden eller på mail, og arrangere et kort introduktionskursus.

Det er kun tilladt at bruge lasercutteren til studierelevante aktiviteter. Skal du producere til egen virksomhed eller projekter ud over studiet, bedes du i stedet gøre brug af faciliteterne på [godsbanen](http://godsbanen.dk/godsbanens-aabne-vaerksteder/laser//).

## Indhold

- [Inden du går i gang](#inden-du-går-i-gang) ❗️❗️❗️
  - [Indstil Lightburn på din egen PC](#indstil-lightburn-på-din-egen-pc)
- [Materialer](#materialer) 🪵
- [Når du laver din fil](#når-du-laver-din-fil)
  - [Tegn din fil direkte i Lightburn](#tegn-din-fil-direkte-i-lightburn)
  - [Tegn din fil i et andet program](#tegn-din-fil-i-et-andet-program)
  - [Indstil farver (layers)](#indstil-farver-layers)
  - [Indstil skæreindstillinger](#indstil-skæreindstillinger)
- [Når du skal skære](#når-du-skal-skære) 🧯
- [Vedligeholdelse af maskinen](#vedligeholdelse-af-maskinen) 🛠️
- [Nyttige Links + Guides](#nyttige-links--guides) 
   - [Guides](#guides) 🤓



## Inden du går i gang

Inden du går i gang, er her et par ting, der er smarte at huske på:  

- Lasercutteren har et effektivt skæreområde på 700x500mm. Der er plads til materialer op til 710x510mm. Er dit materiale større end dette, skal du have skåret det til inden. Brug evt. savene i grovlab'et. 
- Det er ikke muligt at reservere lasercutteren. Vær derfor ude i god tid når du skal skære, da maskinen kan være meget travl i perioder.  
- Når du skærer i akryl, så vent med at tage beskyttelsesfilmen af så længe som muligt, medmindre du skal gravere (se under [indstil skæreindstillinger](https://github.com/DDlabAU/lasercutter#indstil-skæreindstillinger)). Så bliver det pænere når du skærer og dit materiale bliver ikke så nemt ridset.
- Hvis du vil undgå røgmærker på dit træ, så tape overfladen med malertape, inden du skærer.  

*Hvis du gør dig egne erfaringer eller har tips, så giv dem meget gerne videre til medstuderende og DD Lab*
<br>
<br>
<br>
<br>
<br>

#### Indstil Lightburn på din egen PC

[Lightburns officielle guide](https://docs.lightburnsoftware.com/Guides/Migration.html)

For at have den mest optimale version af Lightburn, kan du installere en sammenfattet profil med alle vores instillinger (Kræver version 1.6 eller nyere) :
[LightBurn Indstillinger](https://github.com/DDlabAU/lasercutter/blob/master/Laser%20Profile%20Export.lbzip)
Denne profil inkluderer bl.a. _material library_, som består af forskellige skæreindstillinger til alle tilladte materialer. 

**Guide**
- Gem filen "Laser Profile Export.lbzip" på din PC. 
- Åbn Lightburn  
- Tryk på _File_ / _Filer_ → _Bundles_ → _Import Bundle_ og vælg filen. 
- Marker alle komponenter og tryk _Import_. 
<br>
<br>
<br>

Hent også labbets Lightburn-profil med indstillingerne 



## Materialer
Det er kun tilladt at lasercutte materialer købt på [DDLabs webshop](ddlab.au.dk/webshop). 
Det er ikke noget lab'et tjener penge på, men er en måde for os at være sikre på, at der ikke bliver skåret i farlige materialer.

Som udgangspunkt sælges der træ og akryl. Har du et ønske om at skære andre materialer, skal du kontakte en ansat i åbningstiden eller på vores mail (ddlabau@gmail.com) hvor vi vil undersøge om det kan lade sig gøre.

Du betaler for materialerne på webshoppen og afhenter i lab'ets åbningstid. Du får tilsendt en kvittering på mail, som du skal kunne fremvises, hvis du bliver spurgt af en ansat.

Skal du købe en større mængde materialer på én gang så kom gerne forbi lab'et inden du betaler. Webshoppens beholdning er ikke altid 100% korrekt og på den måde kan vi være helt sikre på, at vi har alle de ønskede materialer inden du betaler.

Du finder webshoppen her: [ddlab.au.dk/webshop](http://ddlab.au.dk/webshop/)
<br>
<br>
<br>
<br>
<br>




## Når du laver din fil

Det eneste krav til filer der skal skæres er at de kan åbnes af programmet Lightburn. Når du skal lave din fil, har du flere muligheder i forhold til hvilke programmer du kan bruge.
<br>
<br>
<br>

#### Tegn din fil direkte i lightburn

Der er installeret lightburn på computeren ved lasercutteren. Som udgangspunkt skal den kun bruges til at 'kommunikere' med lasercutteren og til mindre rettelser og justeringer af design. Der forventes at man har gjort designet klar hjemmefra - dvs. tegn den på din egen pc.  
Du kan hente en _[prøve-version af lightburn](https://lightburnsoftware.com/pages/trial-version-try-before-you-buy)_ og tegne din fil hjemmefra. Hvis din prøve-periode er udløbbet, kan du kontakte en ansat i labbet for at få adgang til en licens.

<br>
<br>
<br>

#### Tegn din fil i et andet program  
En anden mulighed er at tegne filen i et andet program, som f.eks. Illustrator eller Inkscape, og importere den til lightburn.

Der er ikke nogen krav til hverken bestemte stregtykkelser eller farver i filen du skal importere. Alt det indstilles efter den er blevet importeret til lightburn.

Når du eksporterer din fil, skal du sørge for at gøre det til et af følgende filformat som lightburn kan importere:
* .ai - Adobe Illustrator
* .pdf - Adobe Portable Document Format
* .dxf - Drawing Exchange Format
* .svg - Scalable Vector Graphics
* .hpgl / .plt - Plotter vector graphics

<br>
<br>
<br>

#### Indstil farver (layers)

**Man kan ikke indgravere i forskellige farver! - farver = layers**

Når du er færdig med at tegne og har importeret din fil til lightburn, skal du indstille farverne på dit cut.

Farver i lightburn er en måde at adskille forskellige elementer (bl.a. visuelt) og fungerer lidt ligesom lag i photoshop eller illustrator. Når en form bliver givet sin egen farve, har man mulighed for at arbejde med den form adskilt fra de andre og give den unikke skære- eller indgraveringsindstillinger. Giver du den samme farve til flere former vil de pågældende former ligge under samme lag og dele indstillinger. 

Den farve der ligger øverst i oversigten af alle dine lag/farver (`Cuts/Layers`) er den der bliver skåret/graveret **først** og herefter er det den næste under, osv. 
Ønsker du at ændre på rækkefølgen kan du trække i farverne i listen af dine farver/lag.

Hvor mange farver du er nødt til at bruge afhænger helt af hvad du gerne vil skære. Har du et simpelt cut, hvor alle formerne skal skæres på samme måde, kan du nøjes med at bruge en enkelt farve til det hele.

Skal du derimod både gravere og skære dit materiale i samme omgang, er du nødt til at bruge én farve til de former du vil skære og en anden farve til de former du vil gravere. Her er det selvfølgeligt også muligt at bruge forskellige farver til at gravere specifikke former lysere eller mørkere.

Du indstiller farven på en form ved at markere formen og derefter klikke på en farve i bunden af vinduet. Når du har gjort det, vil du se din farve dukke op som et lag ude i højre side af vinduet.
<br>
<br>
<br>

#### Indstil skæreindstillinger

Når du har givet din fil de nødvendige farver skal du sørge for at alle farverne/lagene har den korrekte skæreindstilling. Hvad den er, vil afhænge af hvilket materiale du arbejder på, tykkelsen på materialet og hvilket type cut du gerne vil lave (gennemskæring eller gravering).

DDLab vedligeholder en samling af skæreindstillinger du kan bruge som udgangspunkt for dine egne indstillinger. På grund af slid af maskinen og små forskelle på materialerne der skæres, kan vi ikke garantere at indstillingerne skærer helt perfekt. Du bør derfor altid lave et mindre test-cut i dit materiale og derudfra justere indstillingerne så du opnår dit ønskede resultat.

Du finder indstillingerne nederst i højre side af vinduet under fanen `Library`. De er inddelt først i materialer, så i tykkelser. Graveringsindstillinger vil være under `Engrave` under det pågældende materiale. Der findes to niveauer af gravering, `Engrave normal` og `Engrave light`, alt efter hvor dybt/tydeligt du vil gravere i dit materiale. Der findes tre niveauer af gravering af linjer `Engrave Dark`, `Engrave normal` og `Engrave light`.

Hvis `Library`-fanen er forsvundet, kan du genaktivere den ved øverst i vinduet at trykke på `Window` og derefter sætte et flueben ud foran `Library`.

Du anvender skæreindstillingerne ved at markere den farve/det lag du vil indstille, så markerer du den ønskede indstilling og trykker på knappen `Assign to layer`.

Hvis du skal gravere i akryl kan du med fordel lægge siden uden film opad da filmen ellers vil smelte lidt ned i graveringen, især ved gravering med indstillingen `Engrave normal`. På billedet kan det ses hvordan graveringen vil se ud i de forskellige indstillinger og med/uden filmsiden opad. 

![](engraveAcrylic.png)
*Du kan også finde disse prøveskæringer i labbet ved siden af lasercutteren.*

Hvis du skal gravere en eller flere linjer kan du bruge `Engrave line` indstillingerne under `Engrave` for de forskellige materialer (lige nu er der kun graverings indstillinger for linje for finer). Herunder kan du se hvordan gravering vil se ud i de  forskellige indstillinger vi har.

<img src="fill_new.jpg">

*Du kan også finde disse prøveskæringer i labbet ved siden af lasercutteren.*
<br>
<br>
<br>
<br>
<br>
## Når du skal skære

- Du MÅ ikke forlade rummet mens maskinen er i gang (i labbets bemandingstid skal du informere den ansatte, hvis du skal forlade maskinen)
- Du MÅ ikke skære medbragt materiale uden at have spurgt om vurdering og tilladelse.
- Du MÅ ikke justere på laser-styrken for cut og engrave. Brug de tilpassede pre-sets. 

I rummet hvor lasercutteren står er der flere dyre og farlige maskiner. Opfør dig derfor forsigtigt og med respekt for maskinerne.

Når du skærer skal udsugningen (Fans & Air Pump) **ALTID** være tændt. 

Du skal kun aktivere knapperne på selve maskinen, og du skal altså **ikke** indstille noget på den hvide boks til udsugningen i hjørnet af rummet. 

Udsugningen tændes på knappen **Fans** som altid skal tændes for, sammen med de andre knapper. Tjek altid at der lyser en grøn diode ud fra *Drift* på udsugningen på væggen efter du har tændt for **Fans**. Hvis den mod forventning ikke skulle lyse - kontakt en ansat. 

Hvis der, mod forventning, skulle gå ild i dit materiale, stopper du først maskinen ved at trykke på den store røde nødstop-knap, så forsøger du først at slukke ilden med spraydåsen med kølespray, der står ved lasercutteren, og, hvis det ikke er muligt, så med ildslukkeren. Se også sikkerhedsinstruktionerne over maskinen. 
<br>
<br>
<br>
<br>
<br>
## Vedligeholdelse af maskinen
Det er kun DDLab-ansatte der må foretage vedligeholdelse af maskinen. Du bør derfor tage kontakt til en ansat, hvis du oplever problemer når du skal skære. Det kan du gøre personligt i lab'ets åbningstid eller på mail til ddlabau@gmail.com
<br>
<br>
<br>
<br>
<br>
## Nyttige Links + Guides

Hvis du skal bruge en kasse til din elektronik eller i forbindelse med dit projekt, så kan du bruge en online service til at generere tegningerne, så du ikke selv behøver at lave dem fra bunden. Du kan så efterfølgende rette tegningerne til i f.eks. Illustratur, Inkscape eller Lightburn. Vi har to favoritter som du kan prøve:

- [Boxes.py](https://www.festi.info/boxes.py/)
- [Makercase](http://www.makercase.com/)
- [Living Hinges generator](https://pomocnik.rs/hng.html)

Husk på at der er tale om gratis værktøjer der er under udvikling. Tjek derfor altid at målene er som forventet i forhold til din materialetykkelse, inden du skærer dem. 
<br>
<br>
<br>
<br>
<br>
### Guides

[Trace Image med kamera](https://docs.google.com/presentation/d/1d29kRin2b5o1rduTOiAI4QecXiaNsfKvVj5YhygZm_Y/edit?usp=sharing)

En kort guide til hurtigt og effektivt at overføre håndtegnede designs ind i Lightburn vha. kameraet inde i lasercutteren. 

[Billedindgravering](https://docs.google.com/presentation/d/1jXhuIf8osP3unIowRO8HyUHixzTv9yZjyoUBdMxu2tM/edit?usp=sharing)

En lille guide til indstilling af billeder vha. "Adjust Image" funktion, der gør det muligt at indgravere detaljerede billeder og fotoer. 

[Ting alle med lasercutter kørekort SKAL vide](https://docs.google.com/document/d/194hD3mJoMfGWuLNzh1YbXGY8i5Xl2ATHYWU0qgb8bRE/edit?usp=sharing)

Guldkorn for alle - et must for dem der har været igennem et kørekort-kursus. 



<!-- ===== Bottom Fire (transparent background) ===== -->
<div class="fireband" aria-hidden="true">
  <svg class="fire-svg" viewBox="0 0 1000 300" preserveAspectRatio="none">
    <defs>
      <!-- Soft vertical fade so tips don't crop at the top of the band -->
      <linearGradient id="fadeMask" x1="0" y1="1" x2="0" y2="0">
        <stop offset="0%" stop-color="white"/>
        <stop offset="70%" stop-color="white"/>
        <stop offset="100%" stop-color="black"/>
      </linearGradient>
      <mask id="softCut">
        <rect width="100%" height="100%" fill="url(#fadeMask)"/>
      </mask>

      <!-- Flame color ramps (warm core + outer glow) -->
      <linearGradient id="flameGrad1" x1="0" y1="1" x2="0" y2="0">
        <stop offset="0%"   stop-color="rgba(255,120,0,0.00)"/>
        <stop offset="30%"  stop-color="rgba(255,120,0,0.55)"/>
        <stop offset="55%"  stop-color="rgba(255,160,0,0.85)"/>
        <stop offset="85%"  stop-color="rgba(255,220,120,0.95)"/>
        <stop offset="100%" stop-color="rgba(255,255,220,0.00)"/>
      </linearGradient>
      <linearGradient id="flameGrad2" x1="0" y1="1" x2="0" y2="0">
        <stop offset="0%"   stop-color="rgba(255,80,0,0.00)"/>
        <stop offset="35%"  stop-color="rgba(255,80,0,0.35)"/>
        <stop offset="60%"  stop-color="rgba(255,120,0,0.65)"/>
        <stop offset="90%"  stop-color="rgba(255,240,200,0.85)"/>
        <stop offset="100%" stop-color="rgba(255,255,255,0.00)"/>
      </linearGradient>
      <radialGradient id="embersGrad" cx="50%" cy="90%" r="70%">
        <stop offset="0%"   stop-color="rgba(255,180,0,0.35)"/>
        <stop offset="60%"  stop-color="rgba(255,120,0,0.10)"/>
        <stop offset="100%" stop-color="rgba(255,80,0,0.00)"/>
      </radialGradient>

      <!-- Wavy displacement fields (animated turbulence) -->
      <filter id="wobble1" x="-50%" y="-200%" width="200%" height="400%">
        <feTurbulence type="fractalNoise" baseFrequency="0.015 0.25" numOctaves="3" seed="7" result="turb">
          <animate attributeName="baseFrequency" dur="6s" values="0.015 0.25; 0.020 0.30; 0.012 0.22; 0.015 0.25" repeatCount="indefinite"/>
        </feTurbulence>
        <feDisplacementMap in="SourceGraphic" in2="turb" scale="45" xChannelSelector="R" yChannelSelector="G"/>
      </filter>

      <filter id="wobble2" x="-50%" y="-200%" width="200%" height="400%">
        <feTurbulence type="fractalNoise" baseFrequency="0.02 0.35" numOctaves="4" seed="23" result="turb2">
          <animate attributeName="baseFrequency" dur="4.5s" values="0.02 0.35; 0.028 0.45; 0.016 0.28; 0.02 0.35" repeatCount="indefinite"/>
        </feTurbulence>
        <feDisplacementMap in="SourceGraphic" in2="turb2" scale="30" xChannelSelector="G" yChannelSelector="B"/>
      </filter>

      <!-- Gentle vertical shimmer for heat -->
      <filter id="heatShimmer" x="-50%" y="-200%" width="200%" height="400%">
        <feTurbulence type="fractalNoise" baseFrequency="0.003 0.6" numOctaves="2" seed="99" result="noise">
          <animate attributeName="baseFrequency" dur="7s" values="0.003 0.6; 0.004 0.7; 0.0025 0.5; 0.003 0.6" repeatCount="indefinite"/>
        </feTurbulence>
        <feDisplacementMap in="SourceGraphic" in2="noise" scale="10" xChannelSelector="R" yChannelSelector="G"/>
      </filter>
    </defs>

    <!-- Emissive bed/glow -->
    <rect x="0" y="120" width="1000" height="180" fill="url(#embersGrad)" opacity="0.7" mask="url(#softCut)"/>

    <!-- Core flame body (two layers for depth) -->
    <g mask="url(#softCut)">
      <rect x="-50" y="30" width="1100" height="260" fill="url(#flameGrad1)" filter="url(#wobble1)"/>
      <rect x="-50" y="10" width="1100" height="260" fill="url(#flameGrad2)" filter="url(#wobble2)"/>
    </g>

    <!-- Subtle rising heat haze over everything -->
    <g filter="url(#heatShimmer)" opacity="0.6" mask="url(#softCut)">
      <rect x="-50" y="0" width="1100" height="300" fill="transparent"/>
    </g>
  </svg>
</div>

<style>
  /* Position the fire band at the bottom, fully transparent behind content */
  .fireband {
    position: fixed; /* stick to bottom of viewport; change to absolute inside a container if you prefer */
    left: 0;
    right: 0;
    bottom: 0;
    height: 28vh;            /* overall fire height */
    pointer-events: none;    /* let clicks pass through */
    z-index: 0;              /* keep behind other content unless you raise it */
    background: transparent; /* ensure page background shows through */
    /* Safe margin: keeps flame tips away from the top edge of this band to avoid cropping */
    --flame-safe-top: 6vh;   /* tweak this to increase/decrease headroom */
    padding-top: var(--flame-safe-top);
    /* Optional: add side padding if your layout has gutters */
    padding-left: 0;
    padding-right: 0;
  }

  .fire-svg {
    display: block;
    width: 100%;
    height: 100%;
  }

</style>
<!-- ===== /Bottom Fire ===== -->

