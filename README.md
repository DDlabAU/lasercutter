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


<div id="pixel-fire" aria-hidden="true"></div>
<style>
  #pixel-fire {
    position: fixed;
    left: 0; right: 0; bottom: -20;
    height: 220px;           /* fire band height on screen */
    pointer-events: none;    /* don’t block clicks */
    z-index: 9999;
    mix-blend-mode: normal;  /* change to 'screen' to glow on dark pages */
  }
  #pixel-fire canvas {
    width: 100%;
    height: 100%;
    image-rendering: pixelated;   /* keep the chunky look */
    image-rendering: crisp-edges;
    display: block;
  }

  /* Respect reduced-motion */
  @media (prefers-reduced-motion: reduce) {
    #pixel-fire { display: none; }
  }
</style>
<script>
(function () {
  const container = document.getElementById('pixel-fire');
  if (!container) return;

  const canvas = document.createElement('canvas');
  const ctx = canvas.getContext('2d', { willReadFrequently: true });
  container.appendChild(canvas);

  // Tunables
  const pixelSize = 4;            // larger = chunkier pixels
  const maxIntensity = 36;        // palette size (more = smoother gradient)
  const cooling = 2;              // 0..3; bigger = faster decay
  const wind = 1;                 // -2..2; negative = drift left, positive = right
  const fpsCap = 60;              // simple FPS cap

  let W = 0, H = 0, gridW = 0, gridH = 0, fire = [], palette = [];

  function makePalette() {
    palette = [];
    for (let i = 0; i <= maxIntensity; i++) {
      const t = i / maxIntensity;
      // warm gradient: black -> deep red -> orange -> yellow -> white
      const r = Math.min(255, Math.floor(255 * t));
      const g = Math.min(255, Math.floor(170 * Math.pow(t, 1.2)));
      const b = Math.min(255, Math.floor(30  * Math.pow(t, 2.0)));
      palette.push([r, g, b, 255]);
    }
  }

  function resize() {
    W = container.clientWidth;
    H = container.clientHeight;
    gridW = Math.max(64, Math.floor(W / pixelSize));
    gridH = Math.max(32, Math.floor(H / pixelSize));
    canvas.width  = gridW;     // 1 canvas pixel = 1 fire cell (scaled via CSS)
    canvas.height = gridH;
    fire = new Array(gridW * gridH).fill(0);
    // Set bottom row as heat source
    for (let x = 0; x < gridW; x++) fire[(gridH - 1) * gridW + x] = maxIntensity;
  }

  function idx(x, y) { return y * gridW + x; }

const topMargin = 4; // how many pixel cells of clear space at the top

function step() {
  // propagate from y=0..gridH-2, but leave margin at the top
  for (let y = topMargin; y < gridH - 1; y++) {
    for (let x = 0; x < gridW; x++) {
      const below = idx(x, y + 1);
      const decay = (Math.random() * (cooling + 1)) | 0;
      let newI = fire[below] - decay;
      if (newI < 0) newI = 0;

      const drift = (((Math.random() * 3) | 0) - 1) + wind;
      const nx = (x + drift + gridW) % gridW;
      fire[idx(nx, y)] = newI;
    }
  }

  // reheat the bottom row as usual
  for (let x = 0; x < gridW; x++) {
    fire[idx(x, gridH - 1)] =
      Math.max(0, Math.min(maxIntensity, maxIntensity - ((Math.random() * 3) | 0)));
  }
}


  function draw() {
    const img = ctx.getImageData(0, 0, gridW, gridH);
    const data = img.data;
    for (let i = 0; i < fire.length; i++) {
      const c = palette[fire[i]];
      const off = i * 4;
if (fire[i] === 0) {
  data[off + 3] = 0; // fully transparent when “no fire”
} else {
  data[off]     = c[0];
  data[off + 1] = c[1];
  data[off + 2] = c[2];
  data[off + 3] = 255; // fully opaque flame pixel
}

    }
    ctx.putImageData(img, 0, 0);
  }

  // Basic rAF loop with fps cap
  let last = 0;
  function loop(ts) {
    if (ts - last > 1000 / fpsCap) {
      step();
      draw();
      last = ts;
    }
    requestAnimationFrame(loop);
  }

  // Init
  makePalette();
  resize();
  requestAnimationFrame(loop);

  // Debounced resize
  let rAF = null;
  window.addEventListener('resize', () => {
    if (rAF) cancelAnimationFrame(rAF);
    rAF = requestAnimationFrame(() => {
      resize();
    });
  });
})();
</script>
