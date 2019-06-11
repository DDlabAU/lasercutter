
# https://forms.gle/C63LCHBYJXiDDpAr6

# Brug af lasercutteren i prototyperummet
Der er en række ting, man skal være opmærksom på ved brug af lasercutteren og dem kan du læse om lige her.  
For at få adgang til lasercutteren, skal du kontakte en ansat i DDlab, enten i åbningstiden eller på mail, og arrangere et kort introduktionskursus.
Det er kun tilladt at bruge lasercutteren til studierelevante aktiviteter. Skal du producere til egen virksomhed eller projekter ud over studiet, bedes du i stedet gøre brug af faciliteterne på [godsbanen](http://godsbanen.dk/muligheder/godsbanens-aabne-vaerksteder/lasercutter/).

## Inden du går i gang

Inden du går i gang er her et par ting, der er smart at huske på:
- Du kan booke tid på [lasercutterkalenderen](https://teamup.com/ksaoksap5dd29vbcdu). Når du har booket tid, har du førsteret til lasercutteren og du er i din gode ret til at bede andre brugere om at afslutte deres projekter, så du kan komme til.
- Når du skærer i acryl, så vent med at tage beskyttelsesfilmen af så længe som muligt. Så bliver det pænere når du skærer, og dit materiale bliver ikke så nemt ridset.
- Hvis du vil undgå røgmærker på dit træ, så tape overfladen med malertape, inden du cutter.  

*Hvis du gør dig egne erfaringer eller har tips, så giv dem meget gerne videre til medstuderende og DD Lab*

## Når du laver din fil i Illustrator

Inden du gør i gang, så hent skabelonen til Illustrator [her](https://github.com/DDlabAU/Laser-Cutter-Things/blob/master/VLS_6.60_Illustrator_Template.ait?raw=true). Den er sat op med de rigtige mål (450 mm. x 800 mm.) og farvepaletten er gjort klar til lasercutteren. Åbn den i Illustrator.

Husk at dine streger/stroke skal sættes til 0,02 mm. Lasercutteren ser bort fra streger der er over 0,025 mm. så derfor er det vigtigt at huske dette. Husk at det er 0,02 *mm* og ikke *pt.* som er Illustrators standard. Illustrator ændrer automatisk til noget a la 0,0567 pt. og det er fint.

Det kan være svært at se så tynd en streg på skærmen, så tegn evt. med en tykkere streg og ændr når du er klar til at lasercutte. Du kan vælge alle ting med samme karakteristika (farve + stregytkkelse) ved at gå til Select —> Same —> Appearance i Illustrators menu. 

Stregfarven for de ting du skal skære skal være “RGB rød” hvilket du vælger ved at klikke på den lille pil til venstre for ‘Stroke’-teksten i menubaren øverst til venstre. Den er allerede kodet ind i femte række med mærkaten ‘Through cut’. Ved siden af den er den sorte farve. Den angiver du som fyld/fill på det område du vil have graveret.

Hvis du ønsker at ‘vektorgravere’ skal du vælge ‘Blue’ samme sted. Det kan betale sig at vektorgravere hvis du har tynde streger som f.eks. på et landkort.

Når du har sikret dig at din stregtykkelse er 0,02mm. der hvor du vil skære er RGB rød (altså 255,0,0), der hvor du vil gravere er RGB sort (altså 0,0,0) og der hvor du vil vektorgravere er RGB blå (altså 0,0,255) kan du gemme din fil på en USB stick der kan læses af Windows, tage dit materiale under armen og gå over i Chomsky.

Hvis du vil være sikker på at din fil kan læses ordentligt af lasercutteren, kan du, på din egen maskine, hente en [driver](https://www.ulsinc.com/support/software-downloads) til windows og tjekke efter. Under  `"Download Drivers for VLS, PLS and ILS Platforms"` vælger du `UCP Installer` og downloader og installerer driveren. Du kan nu 'printe' til lasercutteren fra illustrator, hvorefter kontrolpanelet til lasercutteren vil komme frem og du kan se hvordan den læser din fil.


## Når du skal lasercutte og færdes i prototyperummet

Der er en masse enten dyrt eller farligt udstyr i prototyperummet, så opfør dig forsigtigt derinde. ~~Linsen på lasercutteren renses med linserens eller isopropylalkohol og en linserenseklud/linsepapir~~ Det er DD Lab der vedligeholder maskinen og renser linsen. Den koster 10.000 kr. og hvis den går i stykker kan andre ikke bruge lasercutteren, så derfor er det vigtigt at kontakte en DDlab medarbejder hvis der er problemer med laseren (så som at den ikke skærer igennem materialet på den rigtige indstilling). DD Lab kan kontaktes på ddlabau@gmail.com eller i personligt i lab'ets åbningstid.
Det er ikke tilladt at lasercutte i klorholdige materialer, metal eller glas. Hvis du er i tvivl om noget, så spørg i DD Lab, eller spørg google.

Både BOFA Udsugningen (den store sorte der står ved siden af lasercutteren), udsugning til linsen (den under lasercutteren) og loft-udsugningen, skal ALTID være tændt, når der lasercuttes. Også selvom du bare graverer.  
Hvis der, mod forventning, skulle gå ild i dit materiale, så forsøges ilden først slukket med spraydåsen med kølespray, der står ved lasercutteren, og, hvis det ikke er muligt, så med ildslukkeren.  
Lasercutteren stopper automatisk, når du åbner den. For at genoptage det igangværende projekt trykkes på pauseknappen på lasercutteren. Hvis du trykker på start i stedet vil opgaven starte forfra.

Du har ansvaret for tingene, når du er i rummet som kørekorthavende, så lad være med at lukke andre ind. Der står sandsynligvis nogle materialerester i rummet, dem kan man frit bruge, men brug også lige din sunde fornuft og spørg eller hold fingrene væk, hvis der er noget der ligner et igangværende projekt. Det er OK at låne en skydelære eller lignende kortvarigt, men husk altid at lægge tingene tilbage med det samme.

Når du har indlæst til Illustratorfil på PCen ved lasercutteren og dobbelttjekket dine stregtykkelser og farver, skal du følge punkterne på træpladen på opslagstavlen for at lykkes med dit projekt på en fornuftig og sikker måde.

## Vil du skære en kasse?

Hvis du skal bruge en kasse til din elektronik eller på anden måde i forbindelse til dit projekt, så kan du bruge en online service til at generere tegningerne, inden du retter til i Illustrator eller Inkscape. Vi har to favoritter her på DD Lab, som du kan prøve:

- [Boxmaker](http://boxmaker.connectionlab.org/)
- [Makercase](http://www.makercase.com/)

Når du efterfølgende eksporterer din PDF eller SVG-fil skal du åbne i Illustrator eller Inkscape og rette til.

Husk på at der er tale om gratis værktøjer der er under udvikling. Tjek derfor altid at målene er som forventet i forhold til din materialetykkelse, inden du skærer dem.

[Ansøg om adgang til lasercutteren](https://goo.gl/forms/SlW60lH60ulgC40k1)

[Manual til lasercutteren](http://www.engraversnetwork.com/files/VLS_Platform_User_Guide.pdf)
