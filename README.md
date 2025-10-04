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



<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Bottom Fire</title>
<style>
  :root{
    /* Tweak this to add "headroom" above the flames so they don't crop */
    --fire-top-margin: 56px;      /* margin inside the fire strip */
    --fire-height: 240px;         /* overall strip height */
    --flame-count: 70;            /* visual density */
    --ember-count: 45;
    --bg: #0b0f1a;
  }

  /* Page baseline */
  html, body {
    height: 100%;
    margin: 0;
    background: radial-gradient(1200px 600px at 50% 100%, #151d2b 0 35%, var(--bg) 75%);
    color: #e6ecff;
    font-family: system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, "Helvetica Neue", Arial, "Noto Sans", "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  }

  main{
    min-height: 100%;
    display: grid;
    place-items: center;
    padding-bottom: var(--fire-height); /* keep content above the fire */
    box-sizing: border-box;
    text-align: center;
  }

  /* The fire strip sticks to the bottom and provides internal top "margin" */
  .fire-strip{
    position: fixed;
    left: 0;
    right: 0;
    bottom: 0;
    height: var(--fire-height);
    padding-top: var(--fire-top-margin); /* <- headroom to avoid cropping */
    overflow: visible;                   /* allow tall flames to breathe */
    pointer-events: none;                /* don't block clicks on page */
    /* subtle heat glow behind flames */
    background:
      radial-gradient(60% 120% at 50% 100%,
        rgba(255,120,40,.18) 0%,
        rgba(200,40,0,.07) 50%,
        rgba(0,0,0,0) 70%)
      0 0 / 100% 100% no-repeat;
  }

  /* Ground / charcoal at the base */
  .bed{
    position: absolute;
    left: 0; right: 0; bottom: 0;
    height: 44px;
    background:
      radial-gradient(80px 30px at 10% 50%, rgba(250,180,60,.7), transparent 70%),
      radial-gradient(120px 40px at 45% 40%, rgba(255,140,40,.5), transparent 70%),
      radial-gradient(100px 34px at 80% 60%, rgba(255,210,120,.45), transparent 70%),
      linear-gradient(#2a1a14, #100a08 70%);
    filter: blur(0.3px) contrast(1.05);
    box-shadow: 0 -4px 24px rgba(255,120,40,.25) inset;
  }

  /* Container for animated pieces */
  .flames, .embers{
    position: absolute;
    left: 0; right: 0;
    bottom: 44px; /* sit on the bed */
    height: calc(100% - 44px - var(--fire-top-margin));
    overflow: visible;
  }

  /* Individual flame */
  .flame{
    position: absolute;
    bottom: 0;
    width: 36px;
    height: 110px;
    transform-origin: 50% 100%;
    /* layered radial gradients to suggest a hot core and cooler shell */
    background:
      radial-gradient(ellipse at 50% 75%, #fff7b0 0 18%, rgba(255,230,120,.9) 18% 30%, transparent 31%),
      radial-gradient(ellipse at 50% 85%, #ffd37a 0 35%, #ff9a3a 36% 56%, #ff5a00 57% 75%, transparent 76%);
    border-radius: 50% 50% 45% 45% / 70% 70% 30% 30%;
    mix-blend-mode: screen;
    filter: blur(0.15px) saturate(1.15);
    opacity: .92;
    animation:
      rise var(--rise, 2.6s) linear infinite,
      sway var(--sway, 1.9s) ease-in-out infinite alternate,
      flicker var(--flicker, 120ms) steps(2,end) infinite;
  }

  /* Tiny hot sparks */
  .ember{
    position: absolute;
    bottom: 10px;
    width: 3px; height: 3px;
    border-radius: 50%;
    background: radial-gradient(circle at 50% 50%, #ffebb0 0 35%, #ffcd55 36% 60%, rgba(255,120,0,.8) 61% 100%);
    box-shadow:
      0 0 8px rgba(255,160,60,.75),
      0 0 14px rgba(255,120,40,.45);
    opacity: .85;
    animation:
      ember-rise var(--e-rise, 2.8s) linear infinite,
      ember-drift var(--e-drift, 2.2s) ease-in-out infinite alternate,
      ember-fade var(--e-fade, 2.8s) ease-in infinite;
    mix-blend-mode: screen;
  }

  /* Keyframes */
  @keyframes rise{
    0%   { transform: translateY(0) scaleY(1) scaleX(1); opacity: .95; }
    70%  { opacity: .9; }
    100% { transform: translateY(-105%) scaleY(1.3) scaleX(.85); opacity: 0; }
  }
  @keyframes sway{
    from { transform: translateY(var(--ty,0)) translateX(-8px) scaleY(1.1) rotate(-2.5deg); }
    to   { transform: translateY(var(--ty,0)) translateX(8px)  scaleY(1.05) rotate(2.5deg); }
  }
  @keyframes flicker{
    50% { filter: blur(0.35px) brightness(1.05); }
  }

  @keyframes ember-rise{
    0%   { transform: translateY(0) scale(1); }
    100% { transform: translateY(-140%) scale(0.9); }
  }
  @keyframes ember-drift{
    from { transform: translateX(-18px); }
    to   { transform: translateX(22px); }
  }
  @keyframes ember-fade{
    0%   { opacity: .95; }
    80%  { opacity: .55; }
    100% { opacity: 0; }
  }

  /* Nice little performance bump */
  .flame, .ember { will-change: transform, opacity, filter; }

  /* Optional: responsive tuning */
  @media (max-width: 640px){
    :root{
      --fire-height: 200px;
      --fire-top-margin: 44px;
    }
    .flame{ width: 28px; height: 92px; }
  }
</style>
</head>
<body>
  <main>
    <div>
      <h1>Bottom Fire Demo</h1>
      <p>Replace this content with your page. The fire stays at the bottom.</p>
    </div>
  </main>

  <div class="fire-strip" aria-hidden="true">
    <div class="flames" id="flames"></div>
    <div class="embers" id="embers"></div>
    <div class="bed"></div>
  </div>

<script>
  // Plain, tiny helper to populate flames/embers with variety
  (function makeFire(){
    const flames = document.getElementById('flames');
    const embers = document.getElementById('embers');
    const W = window.innerWidth;

    const FLAMES = 70;   // matches --flame-count
    const EMBERS = 45;   // matches --ember-count

    for(let i=0;i<FLAMES;i++){
      const f = document.createElement('span');
      f.className = 'flame';

      // Distribute across width with a little clustering
      const x = (i/(FLAMES-1)) * (W + 80) - 40 + (Math.random()*60 - 30);
      const delay = -(Math.random()*2.6).toFixed(2) + 's';
      const rise  = (2.2 + Math.random()*1.2).toFixed(2) + 's';
      const sway  = (1.6 + Math.random()*1.2).toFixed(2) + 's';
      const flick = (80 + Math.random()*120|0) + 'ms';
      const h    = 90 + Math.random()*70;      // flame height
      const w    = 26 + Math.random()*22;      // flame width
      const o    = 0.75 + Math.random()*0.25;  // opacity variation

      f.style.left = x + 'px';
      f.style.height = h + 'px';
      f.style.width  = w + 'px';
      f.style.opacity = o.toFixed(2);
      f.style.setProperty('--rise', rise);
      f.style.setProperty('--sway', sway);
      f.style.setProperty('--flicker', flick);
      f.style.animationDelay = delay;

      flames.appendChild(f);
    }

    for(let i=0;i<EMBERS;i++){
      const e = document.createElement('i');
      e.className = 'ember';
      const x = Math.random()*W;
      const delay = -(Math.random()*2.8).toFixed(2) + 's';
      const rise  = (2.2 + Math.random()*1.6).toFixed(2) + 's';
      const drift = (1.6 + Math.random()*1.6).toFixed(2) + 's';

      e.style.left = x + 'px';
      e.style.setProperty('--e-rise', rise);
      e.style.setProperty('--e-drift', drift);
      e.style.setProperty('--e-fade', rise);
      e.style.animationDelay = delay;

      embers.appendChild(e);
    }

    // Keep distribution sane on resize (simple approach)
    window.addEventListener('resize', () => {
      flames.innerHTML = '';
      embers.innerHTML = '';
      makeFire();
    }, { once: true });
  })();
</script>
</body>
</html>
