# INSERT101

## Titel
Linkblok : verwijder de losse (1)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : verwijder de losse (1)
Hoe kan ik linkblok : verwijder de losse (1)
Ik zoek een oplossing voor linkblok : verwijder de losse (1)
In het linkblok op de homepage worden de waarden van de velden die slechts een keer voorkomen niet meer getoond met een 


## Oplossing
Gebruik INSERT101

## Code
&INSERT101;

## Met parameters
&INSERT101;

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT101;

## Uitleg
In het linkblok op de homepage worden de waarden van de velden die slechts een keer voorkomen niet meer getoond met een (1).

## Tags
linkblok : verwijder de losse (1) linkblok


---

# INSERT102

## Titel
Homepage : tijdelijk uitschakelen mutaties

## Toepassing
Homepage

## Probleem
Ik wil homepage : tijdelijk uitschakelen mutaties
Hoe kan ik homepage : tijdelijk uitschakelen mutaties
Ik zoek een oplossing voor homepage : tijdelijk uitschakelen mutaties
De mogelijkheid van muteren kan tijdelijk worden uitgeschakeld. Onder meer de edit mogelijkheiden worden daarbij uitgeschakeld.

Let op:
Alleen mutaties worden geblokkeerd, de beeldbank blijft zichtbaar voor bezoekers.


## Oplossing
Gebruik INSERT102

## Code
&INSERT102;

## Met parameters
&INSERT102("Tekst");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT102 ("==== UITVOEREN VAN MUTATIES IS TIJDELIJK NIET MOGELIJK ====");

## Uitleg
De mogelijkheid van muteren kan tijdelijk worden uitgeschakeld. Onder meer de edit mogelijkheiden worden daarbij uitgeschakeld. 
Bovenaan de homepage wordt daarbij de volgende default tekst geplaatst: 
   ==== UITVOEREN VAN MUTATIES IS TIJDELIJK NIET MOGELIJK ==== 
Deze tekst is via het argument van de INSERT-aanroep aan te passen.

## Tags
homepage : tijdelijk uitschakelen mutaties homepage


---

# INSERT103

## Titel
Zoekresultaat : kaders rond list items

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : kaders rond list items
Hoe kan ik zoekresultaat : kaders rond list items
Ik zoek een oplossing voor zoekresultaat : kaders rond list items
Een kader met de default kleur grijs, wordt geplaatst rond de records bij de lijst-weergave in de zoekresultaten pagina.


## Oplossing
Gebruik INSERT103

## Code
&INSERT103;

## Met parameters
&INSERT103 ("#RGB-waarde");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT103;

## Uitleg
Een kader met de default kleur grijs, wordt geplaatst rond de records bij de lijst-weergave in de zoekresultaten pagina. 
De kleur van het kader is via een RGB-waarde in het argument van de INSERT-aanroep aan te passen. 
 
Zie ook de video %%nr 122(https://www.zcbs.nl/cgi-bin/insertlib.pl?ident=122)

## Tags
zoekresultaat : kaders rond list items zoekresultaat


---

# INSERT104

## Titel
Zoekresultaat : kaders rond gallery items

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : kaders rond gallery items
Hoe kan ik zoekresultaat : kaders rond gallery items
Ik zoek een oplossing voor zoekresultaat : kaders rond gallery items
Een kader met de default kleur grijs, wordt geplaatst rond de records bij de gallery-weergave in de zoekresultaten pagin


## Oplossing
Gebruik INSERT104

## Code
&INSERT104;

## Met parameters
&INSERT104 ("#555555");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT104;

## Uitleg
Een kader met de default kleur grijs, wordt geplaatst rond de records bij de gallery-weergave in de zoekresultaten pagina. 
De kleur van het kader is via een RGB-waarde in het argument van de INSERT-aanroep aan te passen.

## Tags
zoekresultaat : kaders rond gallery items zoekresultaat


---

# INSERT105

## Titel
Overzicht database : dateringsveld(en) van oud naar recent gesorteerd

## Toepassing
Overzicht

## Probleem
Ik wil overzicht database : dateringsveld(en) van oud naar recent gesorteerd
Hoe kan ik overzicht database : dateringsveld(en) van oud naar recent gesorteerd
Ik zoek een oplossing voor overzicht database : dateringsveld(en) van oud naar recent gesorteerd
Standaard wordt de datums op de 1e (en volgend) cijfer gesorteerd weergegeven. 
Via deze INSERT wordt nu chronologisch g


## Oplossing
Gebruik INSERT105

## Code
&INSERT105;

## Met parameters
&INSERT105 ("veld-nr1; veld-nr2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT105;

## Uitleg
Standaard wordt de datums op de 1e (en volgend) cijfer gesorteerd weergegeven. 
Via deze INSERT wordt nu chronologisch gesorteerd (oudste datum bovenaan, recentste onderaan). 
Default (zonder argument) wordt alleen veld-08 behandeld.

## Tags
overzicht database : dateringsveld(en) van oud naar recent gesorteerd overzicht


---

# INSERT106

## Titel
E-mail : afzenderadres reactieformulier is van de echte afzender

## Toepassing
E-mail

## Probleem
Ik wil e-mail : afzenderadres reactieformulier is van de echte afzender
Hoe kan ik e-mail : afzenderadres reactieformulier is van de echte afzender
Ik zoek een oplossing voor e-mail : afzenderadres reactieformulier is van de echte afzender
Bij de e-mail die de systeembeheerder ontvangt wordt het default e-mail afzender adres vervangen door het e-mail adres w


## Oplossing
Gebruik INSERT106

## Code
&INSERT106;

## Met parameters
&INSERT106;

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT106;

## Uitleg
Bij de e-mail die de systeembeheerder ontvangt wordt het default e-mail afzender adres vervangen door het e-mail adres wat de reactiegever heeft opgegeven.

## Tags
e-mail : afzenderadres reactieformulier is van de echte afzender e-mail


---

# INSERT107

## Titel
Zoekresultaat : plak subveld aan veld (i.v.m. zoeken)

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : plak subveld aan veld (i.v.m. zoeken)
Hoe kan ik zoekresultaat : plak subveld aan veld (i.v.m. zoeken)
Ik zoek een oplossing voor zoekresultaat : plak subveld aan veld (i.v.m. zoeken)
Een subveld is in de database gescheiden met een |-teken in het betreffende veld. 
Bijvoorbeeld: Straat|Huisnummer of Ac


## Oplossing
Gebruik INSERT107

## Code
&INSERT107;

## Met parameters
&INSERT107 ("straat|huisnummer;-achternaam|voornaam");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT107 ("07;-24");

## Uitleg
Een subveld is in de database gescheiden met een |-teken in het betreffende veld. 
Bijvoorbeeld: Straat|Huisnummer of Achternaam|Voornaam. 
Zoeken op de combinatie van beiden geeft zodoende problemen (lees: geen resultaat). 
Via deze INSERT wordt bij het inlezen van de database het |-teken vervangen door een spatie en (bij een opgegeven negatief veld) eerst het subveld met het veld verwisseld.

## Tags
zoekresultaat : plak subveld aan veld (i.v.m. zoeken) zoekresultaat


---

# INSERT108

## Titel
Zoekresultaat : gebruik large i.p.v. small afbeeldingen voor thumbnails

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : gebruik large i.p.v. small afbeeldingen voor thumbnails
Hoe kan ik zoekresultaat : gebruik large i.p.v. small afbeeldingen voor thumbnails
Ik zoek een oplossing voor zoekresultaat : gebruik large i.p.v. small afbeeldingen voor thumbnails
Door voor de thumbnails, de large afbeeldingen te gebruiken (maar dan natuurlijk door ZCBS automatisch verkleint), kan d


## Oplossing
Gebruik INSERT108

## Code
&INSERT108;

## Met parameters
&INSERT108 (max. hoogte dan wel breedte);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT108 (250); ## max. hoogte dan wel breedte: 250px (default) oftewel &INSERT (250);

## Uitleg
Door voor de thumbnails, de large afbeeldingen te gebruiken (maar dan natuurlijk door ZCBS automatisch verkleint), kan de webserver map small overbodig gemaakt worden. 
Hiermee wordt het aantal bestanden op de webserver sterk verkleint vooral bij databases met zeer veel records (> 100.000 stuks). 
Bij sommige hostingproviders geldt een beperking van het aantal bestanden op de webserver; bij bijvoorbeeld hosting2go maximaal 500.000 (ionodes). 
Default krijgt de thumbnail een maximale afmeting van 250px (hoogte dan wel breedte). 
Via een parameter in de INSERT108 aanroep kan echter een andere waarde opgegeven worden.

## Tags
zoekresultaat : gebruik large i.p.v. small afbeeldingen voor thumbnails zoekresultaat


---

# INSERT109

## Titel
Objectpagina : alleen PDF's laatste jaren vrij op internet

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : alleen pdf's laatste jaren vrij op internet
Hoe kan ik objectpagina : alleen pdf's laatste jaren vrij op internet
Ik zoek een oplossing voor objectpagina : alleen pdf's laatste jaren vrij op internet
Deze INSERT kan gebruikt worden als van een tijdschrift de PDF's van de laatste jaren integraal vrijgegeven worden voor 


## Oplossing
Gebruik INSERT109

## Code
&INSERT109;

## Met parameters
&INSERT109 ("/tijdschrift/pdf", 4,0);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT109 ("/zhb/pdf",4);

## Uitleg
Deze INSERT kan gebruikt worden als van een tijdschrift de PDF's van de laatste jaren integraal vrijgegeven worden voor plaatsing op internet. 
Bij de aanroep moet worden opgegeven: 
1. de locatie van de PDF bestanden 
2. het aantal jaren van vrijgave (default geldt 4) 
3. de eerste postite van het jaartal van het betreffende tijdschrift in het recordnummer (default 0 = aan het begin). 
Het jaartal in het recordnummer dient 4 cijfers te bevatten.

## Tags
objectpagina : alleen pdf's laatste jaren vrij op internet objectpagina


---

# INSERT110

## Titel
Zoekresultaat : toon aantal carrousel afbeeldingen

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : toon aantal carrousel afbeeldingen
Hoe kan ik zoekresultaat : toon aantal carrousel afbeeldingen
Ik zoek een oplossing voor zoekresultaat : toon aantal carrousel afbeeldingen
Het aantal carrousel (+ de originele) afbeeldingen wordt getoond bij lijst en gallery weergave. 
Opgegeven kan eventueel


## Oplossing
Gebruik INSERT110

## Code
&INSERT110;

## Met parameters
&INSERT110 (1/2, "getoonde tekst", "styling tekst");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT110; 
&INSERT110 (1,"xxx afbeeldingen", "color:black;font-size:14px;"); 
&INSERT110 (2,"record bevat xxx images", "color:red;background:white;font-size:19px;font-weight:bold"); 
&INSERT110 (2,"record bevat xxx images", "color:red;background:white;font-size:19px;font-weight:bold");

## Uitleg
Het aantal carrousel (+ de originele) afbeeldingen wordt getoond bij lijst en gallery weergave. 
Opgegeven kan eventueel worden: 
- de locatie boven (=1) of onder (=2) de afbeelding 
- tekst die toegevoegd moet worden (aantal images moet worden aangegeven met: xxx) 
- de styling van de tekst (in CSS-formaat, bijvoorbeeld grootte en kleur van de tekst)

## Tags
zoekresultaat : toon aantal carrousel afbeeldingen zoekresultaat


---

# INSERT111

## Titel
Linkblok : uitklapbaar verticaal alfabet(ten)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : uitklapbaar verticaal alfabet(ten)
Hoe kan ik linkblok : uitklapbaar verticaal alfabet(ten)
Ik zoek een oplossing voor linkblok : uitklapbaar verticaal alfabet(ten)
Wanneer een lijst van een van de velden in het link blok (te) lang is, kan deze vervangen worden door een verticale 'alf


## Oplossing
Gebruik INSERT111

## Code
&INSERT111;

## Met parameters
&INSERT111 ("veld-a; veld-b; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT111("Familienaam; Auteur");

## Uitleg
Wanneer een lijst van een van de velden in het link blok (te) lang is, kan deze vervangen worden door een verticale 'alfabet'-lijst. 
Door op een letter te klikken worden alle waarden getoond die met de betreffende letter beginnen. 
Door nog een keer op de letter te klikken wordt de uitgeklapte lijst gesloten. 
Dat gebeurt eveneens als er een andere letter wordt aangeklikt. 
Via het argument van de INSERT-aanroep kan men 1 of meerdere velden opgeven. 
Zie ook #124: www.zcbs.nl/cgi-bin/insertlib.pl?i=124 
==> Let op: 
==> Als argument moet veldnaam worden gebruikt en geen veldnummer! 
==> De oorspronkelijke lijst (in $LINKBLOK) mag niet over meerdere kolommen zijn ingesteld!

## Tags
linkblok : uitklapbaar verticaal alfabet(ten) linkblok


---

# INSERT112

## Titel
Webpagina personen.html : uitklapbaar alfabet verticaal

## Toepassing
Lijst personen

## Probleem
Ik wil webpagina personen.html : uitklapbaar alfabet verticaal
Hoe kan ik webpagina personen.html : uitklapbaar alfabet verticaal
Ik zoek een oplossing voor webpagina personen.html : uitklapbaar alfabet verticaal
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt op de objectpa


## Oplossing
Gebruik INSERT112

## Code
&INSERT112;

## Met parameters
&INSERT112;

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT112;

## Uitleg
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt op de objectpagina zowel een persoonsnaam in het beschrijvingsveld (veld06) of in een ander veld, cursief getoond indien deze tussen bushaken (bijvoorbeeld, [Jansen, J.]) is geplaatst. Daarnaast wordt er een bestand aangemaakt (na het geven van het systeemcommand UPDATE_PERSONEN) op webserverlocatie: <code>[public_html]/[beeldbank]/misc/personen.html</code> bevattende alle (tussen de bushaken geplaatste) persoonsnamen. 
Standaard is dat een lange verticale rij met alle namen van A t/m Z. 
Via een toepassing uit de INSERT-bibliotheek kan dat omgezet worden in een uitklapbare rij voor de (begin)letters A t/m Z. 
Let op: Het uitklapbare alfabet wordt pas getoond na het systeemcommando: <code>UPDATE_DATABASE</code> (hetgeen natuurlijk na aanpassingen in de records opnieuw opgegeven moet worden).

## Tags
webpagina personen.html : uitklapbaar alfabet verticaal lijst personen


---

# INSERT113

## Titel
Webpagina personen.html : uitklapbaar alfabet horizontaal

## Toepassing
Lijst personen

## Probleem
Ik wil webpagina personen.html : uitklapbaar alfabet horizontaal
Hoe kan ik webpagina personen.html : uitklapbaar alfabet horizontaal
Ik zoek een oplossing voor webpagina personen.html : uitklapbaar alfabet horizontaal
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt op de objectpa


## Oplossing
Gebruik INSERT113

## Code
&INSERT113;

## Met parameters
&INSERT113 (1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT113;

## Uitleg
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt op de objectpagina zowel een persoonsnaam in het beschrijvingsveld (veld06) of in een ander veld, cursief getoond indien deze tussen rechte haken (bijvoorbeeld, [Jansen, J.]) is geplaatst. Daarnaast wordt er een bestand aangemaakt (na het geven van het systeemcommand UPDATE_PERSONEN) op webserverlocatie: 
<code>[public_html]/[beeldbank]/misc/personen.html</code> bevattende alle (tussen de rechte haken geplaatste) persoonsnamen. 
Standaard is dat een lange verticale rij met alle namen van A t/m Z. 
 
Via een toepassing uit de INSERT-bibliotheek kan dat omgezet worden in een uitklapbare rij voor de (begin)letters A t/m Z. 
Let op: Het uitklapbare alfabet wordt pas getoond na het systeemcommando: <code>UPDATE_DATABASE</code> (hetgeen natuurlijk na aanpassingen in de records opnieuw opgegeven moet worden). 
 
Door het opgeven van de parameter met waarde 1 wordt de keuze [A-Z] (dus alle persoonsnamen) weggelaten. 
Alleen de rij met de lossen alfabet letters wordt getoond. 
Bij (zeer) veel persoonsnamen scheelt dat de helft in grootte van de webpagina! 
<CAR> 
het resultaat van &INSERT113; 
<CAR>zonder het gebruik van de INSERT113 (een hele lange lijst van A t/m Z) 
<CAR>met INSERT113 bij aanklikken letter I 
<CAR>de zelf aan te brengen link op de homepage van de beeldbank 
</CAR>

## Tags
webpagina personen.html : uitklapbaar alfabet horizontaal lijst personen


---

# INSERT114

## Titel
Linkblok : plaats/adressen vooraan lijst positioneren

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : plaats/adressen vooraan lijst positioneren
Hoe kan ik linkblok : plaats/adressen vooraan lijst positioneren
Ik zoek een oplossing voor linkblok : plaats/adressen vooraan lijst positioneren
Bij de opsomming in het linkblok van het veld 'Plaats-Straat', worden de Plaatsen in alfabetische volgorde getoond. 
Met


## Oplossing
Gebruik INSERT114

## Code
&INSERT114;

## Met parameters
&INSERT114 ("plaats-1; plaats-2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT114 ("Burgerbrug; Callantsoog; Oudesluis; ...");

## Uitleg
Bij de opsomming in het linkblok van het veld 'Plaats-Straat', worden de Plaatsen in alfabetische volgorde getoond. 
Met deze keuze uit de INSERT-bibliotheek kan men bepaalde plaatsen in een eigen volgorde aan het begin van de lijst plaatsen.

## Tags
linkblok : plaats/adressen vooraan lijst positioneren linkblok


---

# INSERT115

## Titel
Linkblok : plaats/adressen achteraan lijst positioneren

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : plaats/adressen achteraan lijst positioneren
Hoe kan ik linkblok : plaats/adressen achteraan lijst positioneren
Ik zoek een oplossing voor linkblok : plaats/adressen achteraan lijst positioneren
Bij de opsomming in het linkblok van het veld 'Plaats-Straat', worden de Plaatsen in alfabetische volgorde getoond. 
Met


## Oplossing
Gebruik INSERT115

## Code
&INSERT115;

## Met parameters
&INSERT115 ("plaats-1; plaats-2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT115 ("Hilversum; Amsterdam; Alkmaar");

## Uitleg
Bij de opsomming in het linkblok van het veld 'Plaats-Straat', worden de Plaatsen in alfabetische volgorde getoond. 
Met deze keuze uit de INSERT-bibliotheek kan men bepaalde plaatsen in een eigen volgorde aan het eind van de lijst plaatsen.

## Tags
linkblok : plaats/adressen achteraan lijst positioneren linkblok


---

# INSERT116

## Titel
Linkblok : splits een veld in extra kolom(men)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : splits een veld in extra kolom(men)
Hoe kan ik linkblok : splits een veld in extra kolom(men)
Ik zoek een oplossing voor linkblok : splits een veld in extra kolom(men)
Kolommen in het linkblok binnen een veld, worden automatisch ingedeeld indien men meer dan 1 kolom heeft opgegeven...


## Oplossing
Gebruik INSERT116

## Code
&INSERT116;

## Met parameters
&INSERT116 ("veldwaarde-1; veldwaarde-2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT116 ("Julianastraat; Toniesplein ");

## Uitleg
Kolommen in het linkblok binnen een veld, worden automatisch ingedeeld indien men meer dan 1 kolom heeft opgegeven...

## Tags
linkblok : splits een veld in extra kolom(men) linkblok


---

# INSERT117

## Titel
Linkblok : afwijkend (ongelijk aan 14) adresveld

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : afwijkend (ongelijk aan 14) adresveld
Hoe kan ik linkblok : afwijkend (ongelijk aan 14) adresveld
Ik zoek een oplossing voor linkblok : afwijkend (ongelijk aan 14) adresveld
Een adresveld bestaat veelal uit 2 delen: de straatnaam en het huisnummer. 
Als gezocht wordt op een adres via het linkb


## Oplossing
Gebruik INSERT117

## Code
&INSERT117;

## Met parameters
&INSERT117 ("veldnummer");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT117("24");

## Uitleg
Een adresveld bestaat veelal uit 2 delen: de straatnaam en het huisnummer. 
Als gezocht wordt op een adres via het linkblok wordt alleen exact gezocht op de straatnaam zelf, dus zonder het huisnummer. 
Binnen ZCBS wordt hier rekening mee gehouden zolang veld14 het adres bevat 
Indien het adres in een ander veld staat, moet echter van deze INSERT gebruik worden gemaakt om er voor te zorgen dat er geen exacte match wordt gevonden met het adres doch alleen met de straatnaam.

## Tags
linkblok : afwijkend (ongelijk aan 14) adresveld linkblok


---

# INSERT118

## Titel
Zoekresultaat : volgorde afhankelijk aantal OCR-regels

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : volgorde afhankelijk aantal ocr-regels
Hoe kan ik zoekresultaat : volgorde afhankelijk aantal ocr-regels
Ik zoek een oplossing voor zoekresultaat : volgorde afhankelijk aantal ocr-regels
Bij onder meer tijdschriften beeldbanken wordt ook gezocht op de OCR-tekst binnen het betreffende tijdschrift/artikel/pa


## Oplossing
Gebruik INSERT118

## Code
&INSERT118;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT118;

## Uitleg
Bij onder meer tijdschriften beeldbanken wordt ook gezocht op de OCR-tekst binnen het betreffende tijdschrift/artikel/pagina. Zinnen, bevattende de tekst die als zoekopdracht is opgegeven, worden als resultaat getoond. 
Default wordt bij het zoekresultaat op recordnummer gesorteerd welke meestal bestaat uit jaar-maand combinatie waardoor het recentste uitgave als eerste verschijnt. 
Met deze INSERT wordt nu het tijdschrift/artikel/pagina met de meeste zinnen die de zoekopdracht-tekst bevatten (veelal het belangrijkste resultaat) eerst getoond.

## Tags
zoekresultaat : volgorde afhankelijk aantal ocr-regels zoekresultaat


---

# INSERT119

## Titel
Linkblok : samenvoegen 2 velden in linkblok

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : samenvoegen 2 velden in linkblok
Hoe kan ik linkblok : samenvoegen 2 velden in linkblok
Ik zoek een oplossing voor linkblok : samenvoegen 2 velden in linkblok
Twee velden in het linkblok worden samengevoegd tot een enkel veld. 
De INSERT119 kan maximaal 2 keer worden aangeroepen


## Oplossing
Gebruik INSERT119

## Code
&INSERT119;

## Met parameters
&INSERT119 (nr_1e_veld; nr_2e_veld; "nieuwe_veldnaam");

## Voorbeeld
require "misc/insertlib2.pm"; 
&INSERT119 (25,26, "Beroep verkoper/koper"); ## Linkblok : samenvoegen 2 velden 
&INSERT119 (24,22, "Achternaam koper/verkoper"); ## Linkblok : samenvoegen 2 velden 
&INSERT101; ## Linkblok : verwijder de losse (1) 
&INSERT111("Achternaam koper/verkoper"); ## Linkblok : uitklapbaar (verticaal) alfabet(ten)

## Uitleg
Twee velden in het linkblok worden samengevoegd tot een enkel veld. 
De INSERT119 kan maximaal 2 keer worden aangeroepen (dus samenvoegen van maximaal 2x2 velden. 
Voorbeeld: samenvoegen van een veld achternaam overledene en van partner en/of van beroep koper en verkoper 
Let op: 
Een INSERT101 aanroep mag nooit voor een INSERT119 plaatvinden. 
Na een INSERT119 kan bijvoorbeeld wel een INSERT111 opgenomen worden (uitklapbaar verticaal alfabet). 
De INSERT119 kent altijd 3 parameters: 2 getallen (veldnummers) en 1 tekststring tussen quotes (nieuwe veldnaam).

## Tags
linkblok : samenvoegen 2 velden in linkblok linkblok


---

# INSERT120

## Titel
Zoekresultaat : bijlagen tonen in lijst zoekresultaat

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : bijlagen tonen in lijst zoekresultaat
Hoe kan ik zoekresultaat : bijlagen tonen in lijst zoekresultaat
Ik zoek een oplossing voor zoekresultaat : bijlagen tonen in lijst zoekresultaat
Toon ook de eventueel aanwezige bijlagen van een record bij de lijstweergave van het zoekresultaat


## Oplossing
Gebruik INSERT120

## Code
&INSERT120;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT120;

## Uitleg
Toon ook de eventueel aanwezige bijlagen van een record bij de lijstweergave van het zoekresultaat

## Tags
zoekresultaat : bijlagen tonen in lijst zoekresultaat zoekresultaat


---

# INSERT121

## Titel
Alle webpagina's : XML-dump/export objecten-, foto- of boeken-beeldbank i.p.v. een webpagina

## Toepassing
Alle webpagina's

## Probleem
Ik wil alle webpagina's : xml-dump/export objecten-, foto- of boeken-beeldbank i.p.v. een webpagina
Hoe kan ik alle webpagina's : xml-dump/export objecten-, foto- of boeken-beeldbank i.p.v. een webpagina
Ik zoek een oplossing voor alle webpagina's : xml-dump/export objecten-, foto- of boeken-beeldbank i.p.v. een webpagina
Genereer, i.p.v. een webpagina met zoekresultaten, XML-output t.b.v. interactieve schermen (o.a. Vidinexus en Onwijs). N


## Oplossing
Gebruik INSERT121

## Code
&INSERT121;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT121;

## Uitleg
Genereer, i.p.v. een webpagina met zoekresultaten, XML-output t.b.v. interactieve schermen (o.a. Vidinexus en Onwijs). Natuurlijk alleen van records die zijn vrijgegeven. Niet alle externe velden worden geëxporteerd. 
In het zoekveld van de foto-beeldbank wordt opgegeven bijvoorbeeld: 
    XML zoekopdracht 
Als alleen XML wordt opgegeven worden alle records van de betreffende foto-database in XML getoond. 
Deze INSERT wordt in principe alleen door computersystemen (van b.v. Vidinexus en Onwijs) gegeven en niet door een (fysieke) beeldbankbezoeker.

## Tags
alle webpagina's : xml-dump/export objecten-, foto- of boeken-beeldbank i.p.v. een webpagina alle webpagina's


---

# INSERT122

## Titel
Zoekresultaat : pas achtergrondskleur aan afh. status record

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : pas achtergrondskleur aan afh. status record
Hoe kan ik zoekresultaat : pas achtergrondskleur aan afh. status record
Ik zoek een oplossing voor zoekresultaat : pas achtergrondskleur aan afh. status record
Toon via een kleur zowel in galerij als lijst omgeving aan of een record: 
1. niet op internet is geplaatst 
2. nog niet


## Oplossing
Gebruik INSERT122

## Code
&INSERT122;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT122 (1, "green"); ## niet op internet 
&INSERT122 (2, "red"); ## niet beschreven

## Uitleg
Toon via een kleur zowel in galerij als lijst omgeving aan of een record: 
1. niet op internet is geplaatst 
2. nog niet beschreven is 
3. copyright op de afbeelding rust (toon alleen de metadata aan externe bezoekers) 
De aanroep kent 2 parameters: 
- de keuze 1,2,3 
- de kleur van de achtergrond (galerij) of border (lijst) 
Bij kleur kan gekozen worden uit namen als: red, green, blue, etc. 
Daarnaast kan de kleur heximaal opgegeven worden, bijvoorbeeld : #ffff00 
Voor een uitgebreid overzicht kleurkeuzes zie: www.w3schools.com/cssref/css_colors.php 
Let op: De 2e parameter (kleur) moet altijd tussen quotes worden opgegeven. 
Meerdere aanroepen van INSERT122 zijn toegestaan (zie het voorbeeld).

## Tags
zoekresultaat : pas achtergrondskleur aan afh. status record zoekresultaat


---

# INSERT123

## Titel
Objectpagina : toon leeftijd uit geboorte/overlijdensdatum

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : toon leeftijd uit geboorte/overlijdensdatum
Hoe kan ik objectpagina : toon leeftijd uit geboorte/overlijdensdatum
Ik zoek een oplossing voor objectpagina : toon leeftijd uit geboorte/overlijdensdatum
Bij onder meer een bidprentjesbeeldbank wordt uit de geboorte- en overlijdensdatum, de leeftijd van de betreffende perso


## Oplossing
Gebruik INSERT123

## Code
&INSERT123;

## Met parameters
&INSERT123 ("veldnr_geboortedatum", "veldnr_overlijdensdatum", "veldnr_plaatsing");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT123 ("08", "22", "08");

## Uitleg
Bij onder meer een bidprentjesbeeldbank wordt uit de geboorte- en overlijdensdatum, de leeftijd van de betreffende persoon berekend en geplaatst onder een opgegeven veld. 
De geboorte- en overlijdensdatum mag opgegeven zijn zowel in het formaat dd-mm-jjjj als jjjj-mm-dd. 
Bij een ander formaat of bij ontbrekende gegevens (ook bij bijvoorbeeld "ca.") wordt de leeftijd niet uitgerekend.

## Tags
objectpagina : toon leeftijd uit geboorte/overlijdensdatum objectpagina


---

# INSERT124

## Titel
Linkblok : verwerking de voorvoegsels: 's- en 't (na INSERT111)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Hoe kan ik linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Ik zoek een oplossing voor linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Indien INSERT111 wordt gebruikt voor (onder meer) plaatsnamen en daarbij plaatsen voorkomen met voorvoegsels 's (zoals b


## Oplossing
Gebruik INSERT124

## Code
&INSERT124;

## Met parameters
&INSERT124 ("veldnr1; veldnr2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT124 ("06; 23");

## Uitleg
Indien INSERT111 wordt gebruikt voor (onder meer) plaatsnamen en daarbij plaatsen voorkomen met voorvoegsels 's (zoals bij 's-Gravenhage) of voorvoegsel 't (zoals bij bijvoorbeeld 't Zand), worden deze niet goed in het getoonde linkblok alfabet ondergebracht (namelijk onder het teken ' i.p.v. onder een letter). 
Bij bijvoorbeeld de plaatsnaam 's-Gravenhage wordt met de INSERT124 genoemde plaats nu onder de letter G ondergebracht. 
Let op: 
&INSERT124 moet altijd na &INSERT111 worden aangeroepen (vanwege de juiste verwerking van de INSERT9 in beide subroutines). 
Zie #111: www.zcbs.nl/cgi-bin/insertlib.pl?i=124 
Niet alleen bij plaatsnamen is deze INSERT actief doch ook bijvoorbeeld bij velden als auteurs, familienamen, etc..

## Tags
linkblok : verwerking de voorvoegsels: 's- en 't (na insert111) linkblok


---

# INSERT125

## Titel
Zoekresultaat : aanpassing locatie button 'Lijst weergave'

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : aanpassing locatie button 'lijst weergave'
Hoe kan ik zoekresultaat : aanpassing locatie button 'lijst weergave'
Ik zoek een oplossing voor zoekresultaat : aanpassing locatie button 'lijst weergave'
Met deze INSERT uit de INSERT-bibliotheek kan men de 'Lijst weergave' button direct boven en onder het zoekresultaat, al


## Oplossing
Gebruik INSERT125

## Code
&INSERT125;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT125;

## Uitleg
Met deze INSERT uit de INSERT-bibliotheek kan men de 'Lijst weergave' button direct boven en onder het zoekresultaat, alsmede de tekst 'Klik op object...', exact in lijn brengen met de linker kantlijn van de getoonde afbeeldingen.

## Tags
zoekresultaat : aanpassing locatie button 'lijst weergave' zoekresultaat


---

# INSERT126

## Titel
Homepage : button 'Zoek via de index'

## Toepassing
Homepage

## Probleem
Ik wil homepage : button 'zoek via de index'
Hoe kan ik homepage : button 'zoek via de index'
Ik zoek een oplossing voor homepage : button 'zoek via de index'
Een button met de tekst 'Zoek via de index' wordt geplaatst op de homepage welke een link bevat direct naar het linkblok


## Oplossing
Gebruik INSERT126

## Code
&INSERT126;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT126;

## Uitleg
Een button met de tekst 'Zoek via de index' wordt geplaatst op de homepage welke een link bevat direct naar het linkblok onderaan de homepage.

## Tags
homepage : button 'zoek via de index' homepage


---

# INSERT127

## Titel
Objectpagina : aanpassen linkerkant reactieformulier

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aanpassen linkerkant reactieformulier
Hoe kan ik objectpagina : aanpassen linkerkant reactieformulier
Ik zoek een oplossing voor objectpagina : aanpassen linkerkant reactieformulier
De standaard recordgegevens aan de linker kant van een reactieformulier kunnen worden vervangen door een eigen keuze van


## Oplossing
Gebruik INSERT127

## Code
&INSERT127;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT127 ("20, 0, 11,28,9, 00, 4,3,24");

## Uitleg
De standaard recordgegevens aan de linker kant van een reactieformulier kunnen worden vervangen door een eigen keuze van velden. 
Het veld met het databasenummer kan niet vervangen worden. 
De eigen gekozen velden worden onder het veld met het databasenummer geplaatst. 
Opgegeven moet worden de veldnummers (de nul voor de velden beneden de 10 mag worden weggelaten. 
De volgorde van de velden wordt bepaald door de opgegeven veldnummers bij de aanroep van INSERT127. 
Door het opgeven van veldnummer 0 of 00 wordt een blanco regel geplaatst.

## Tags
objectpagina : aanpassen linkerkant reactieformulier objectpagina


---

# INSERT128

## Titel
Webpagina personen.html : aanmaak lijst persoonsnamen zonder input van de vierkante haken

## Toepassing
Lijst personen

## Probleem
Ik wil webpagina personen.html : aanmaak lijst persoonsnamen zonder input van de vierkante haken
Hoe kan ik webpagina personen.html : aanmaak lijst persoonsnamen zonder input van de vierkante haken
Ik zoek een oplossing voor webpagina personen.html : aanmaak lijst persoonsnamen zonder input van de vierkante haken
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt er een bestand


## Oplossing
Gebruik INSERT128

## Code
&INSERT128;

## Met parameters
&INSERT128 ("veld_achternaam, veld_voornaam, optionele_parameter");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT128 ("6,22");

## Uitleg
Via de config file variabele: <code>$PERSONEN = 1;</code> of <code>$PERSONEN = [veldnummer];</code> wordt er een bestand aangemaakt (na het geven van het systeemcommand UPDATE_PERSONEN) op webserverlocatie: <code>[public_html]/[beeldbank]/misc/personen.html</code> bevattende alle tussen [ en ] geplaatste) persoonsnamen. 
Dat wordt toegepast bij fotobeeldbanken. 
Echter dat kan ook bij onder meer beeldbanken met bidprentjes, grafmonumenten, familieberichten en bevolkingsregisters worden toegepast. 
Via deze INSERT uit de INSERT-bibliotheek wordt, indien een veld alleen de achternaam en een ander veld alleen de voornaam bevat, deze samengevoegd en intern tijdelijk van de haken [ en ] voorzien bij het geven van het systeemcommand UPDATE_PERSONEN waardoor in dat geval op de webserver ook een bestand <code>[public_html]/[beeldbank]/misc/personen.html</code> wordt aangemaakt. 
Als de derde parameter 1 is, dan parameter wordt er geen [A-Z] range getoond

## Tags
webpagina personen.html : aanmaak lijst persoonsnamen zonder input van de vierkante haken lijst personen


---

# INSERT129

## Titel
Webpagina inloggen : volledige database in gemeenschapsruimte

## Toepassing
Alle webpagina's

## Probleem
Ik wil webpagina inloggen : volledige database in gemeenschapsruimte
Hoe kan ik webpagina inloggen : volledige database in gemeenschapsruimte
Ik zoek een oplossing voor webpagina inloggen : volledige database in gemeenschapsruimte
Met deze INSERT kan in een gemeenschapsruimte van de instelling (met <ROUTER> in de permissiefile), zowel alle externe a


## Oplossing
Gebruik INSERT129

## Code
&INSERT129;

## Met parameters
&INSERT129 ("IP-adres; de te tonen tekst bij inlogkeuze");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT129 ("86.87.213.122; De gehele ZM Niestadt beeldbank");

## Uitleg
Met deze INSERT kan in een gemeenschapsruimte van de instelling (met <ROUTER> in de permissiefile), zowel alle externe als interne records worden getoond. Tevens zijn de 100% afbeeldingen daarbij ook beschikbaar. 
Met de 1e parameter van de INSERT wordt het IP-adres van de gemeenschapsruimte opgegeven. 
De standaard keuzemogelijkheid: 
 o Internet (geen wachtwoord nodig) 
wordt vervangen door een eigen gekozen tekst (2e parameter)

## Tags
webpagina inloggen : volledige database in gemeenschapsruimte alle webpagina's


---

# INSERT130

## Titel
Alle webpagina's : eenvoudige en smalle webpagina voor smartphones

## Toepassing
Alle webpagina's

## Probleem
Ik wil alle webpagina's : eenvoudige en smalle webpagina voor smartphones
Hoe kan ik alle webpagina's : eenvoudige en smalle webpagina voor smartphones
Ik zoek een oplossing voor alle webpagina's : eenvoudige en smalle webpagina voor smartphones
Via deze INSERT wordt de webpagina op smartphones zo goed als mogelijk getoond. 
De inhoud en de layout van de webpagina


## Oplossing
Gebruik INSERT130

## Code
&INSERT130;

## Met parameters
&INSERT130 ("L");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT130;

## Uitleg
Via deze INSERT wordt de webpagina op smartphones zo goed als mogelijk getoond. 
De inhoud en de layout van de webpagina verandert alleen bij kleine schermbreedte resolutie t/m 450 px. 
Dus niet zoals bij vele webtoepassingen bij een kleinere vensterbreedte! 
Het is dus apparaat afhankelijk en niet toepassingswindow afhankelijk. 
Bij gebruik van deze INSERT en gebruik van kleine schermen worden enkele onderdelen van de webpagina weggelaten die veelal niet zinvol zijn voor de bediening van de beeldbank op een smartphone. 
Het is in principe alleen bedoeld voor beeldbank-bezoekers. Vanzelfsprekend niet voor beeldbank-beheerders! 
Deze INSERT is uit te testen op een groot scherm (PC of laptop) via de SPECiale zoekopdracht: SPEC17. 
Men kan daarbij het venster versmallen en zien hoe de webpagina op een smartphone wordt getoond. 
<img style="padding: 10px 0px 6px 20px;" src="/insertlib/large/130-sub.jpg" height="300"> 
Op de afbeelding de homepage van een ZCBS-beeldbank op een PC met hoge resolutie.

## Tags
alle webpagina's : eenvoudige en smalle webpagina voor smartphones alle webpagina's


---

# INSERT131

## Titel
Objectpagina : MULTI_TEKST plaatsen in database

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : multi_tekst plaatsen in database
Hoe kan ik objectpagina : multi_tekst plaatsen in database
Ik zoek een oplossing voor objectpagina : multi_tekst plaatsen in database



## Oplossing
Gebruik INSERT131

## Code
&INSERT131;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT131;

## Uitleg


## Tags
objectpagina : multi_tekst plaatsen in database objectpagina


---

# INSERT132

## Titel
Objectpagina : aanpassen grootte afbeelding in PDFjs viewer

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aanpassen grootte afbeelding in pdfjs viewer
Hoe kan ik objectpagina : aanpassen grootte afbeelding in pdfjs viewer
Ik zoek een oplossing voor objectpagina : aanpassen grootte afbeelding in pdfjs viewer
De default waarde van het getoonde PDFviewer scherm is 500px hoogte bij 700px breedte. 
Bij bepaalde documentenbanken ka


## Oplossing
Gebruik INSERT132

## Code
&INSERT132;

## Met parameters
&INSERT132 ("hoogte, breedte");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT132 ("600, 1100");

## Uitleg
De default waarde van het getoonde PDFviewer scherm is 500px hoogte bij 700px breedte. 
Bij bepaalde documentenbanken kan een aangepaste grootte het document beter tot zijn recht laten komen. 
Met deze INSERT kan men een aangepaste hoogte en breedte opgeven. 
Natuurlijk kan de website bezoeker ook zelf via de rechteronderhoek van het PDFviewer scherm de grootte aanpassen.

## Tags
objectpagina : aanpassen grootte afbeelding in pdfjs viewer objectpagina


---

# INSERT133

## Titel
Formulierpagina : standplaats V15 meerdere velden

## Toepassing
Formulierpagina

## Probleem
Ik wil formulierpagina : standplaats v15 meerdere velden
Hoe kan ik formulierpagina : standplaats v15 meerdere velden
Ik zoek een oplossing voor formulierpagina : standplaats v15 meerdere velden
VELD15 (Vaste Standplaats) in de objecten- en documentenbank is standaard een enkelvoudig veld. 
Met deze INSERT kan VEL


## Oplossing
Gebruik INSERT133

## Code
&INSERT133;

## Met parameters
&INSERT133 ("veldnaam1=keuzes; veldnaam2=keuzes;...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT133 ("Gang= A..K; Kamer= 1..10; Stelling= 1,2,4, 6, 8; Plank= onder,boven, midden ; Lade= a1,a2,=a3,b6,d8 ; Verpakking= 10; Alternatieve locatie= 20");

## Uitleg
VELD15 (Vaste Standplaats) in de objecten- en documentenbank is standaard een enkelvoudig veld. 
Met deze INSERT kan VELD15 in meerdere subvelden worden verdeeld, bijvoorbeeld die van Ruimte, Stelling, Plank, etc.. 
Voor elk veld wordt opgegeven (gescheiden met een = teken): veldnaam en uittrekmenuwaarden 
Meerdere velden gescheiden met een ; teken. 
Het aantal veldnaam-veldwaarden combinaties is in principe onbeperkt. 
Uittrekmenu waarden kan een range zijn, bijvoorbeeld 1..10 of een lijst van waarden gescheiden met een , teken. 
Is de veldwaarde een enkel getal dan betreft het geen keuzemenu doch de lengte van het invulveld

## Tags
formulierpagina : standplaats v15 meerdere velden formulierpagina


---

# INSERT134

## Titel
Objectpagina : hyperlink i.p.v. direct tonen Google Maps/Streetview

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : hyperlink i.p.v. direct tonen google maps/streetview
Hoe kan ik objectpagina : hyperlink i.p.v. direct tonen google maps/streetview
Ik zoek een oplossing voor objectpagina : hyperlink i.p.v. direct tonen google maps/streetview
Indien Google coördinaten aanwezig zijn, dan wel, indien zowel plaats als volledig adres opgegeven zijn, wordt in princi


## Oplossing
Gebruik INSERT134

## Code
&INSERT134;

## Met parameters
&INSERT134 ("veldnr_plaats, veldnr_adres, veldnr_google_maps, te_tonen_tekst");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT134;

## Uitleg
Indien Google coördinaten aanwezig zijn, dan wel, indien zowel plaats als volledig adres opgegeven zijn, wordt in principe een Google Maps getoond eventueel inclusief Streetview. 
Daar bij (zeer) veel gebruik van deze mogelijkheid men de gebruikerslimiet van de Google API kan overschrijden, kan via deze INSERT ook een zgn. "tussenpagina" worden aangemaakt waar i.p.v. de Google Maps zelf, alleen een (tekst)link wordt getoond waarmee de gebruiker door daarop eventueel te klikken, dezelfde objectpagina kan oproepen maar dan met de getoonde Google Maps. 
Default (zonder opgegeven parameters) wordt bij deze INSERT uitgegaan van: 
- veldnr_plaats = 12, 
- veldnr_adres = 14, 
- veldnr_google_maps = 25 en 
- te tonen tekst: "Klik hier om Google Maps zichtbaar te maken". 
Oftewel de default parameters: "12, 14, 25, Klik hier om Google Maps zichtbaar te maken". 
Overigens, i.p.v. de parameterscheiding met komma mag ook spatie of ; worden gebruikt. 
Statisch plaatje i.p.v. tekstregel: 
Vanaf de versie van december 2024 is er ook een mogelijkheid om i.p.v. de tekstregel een statisch plaatje toe te voegen. Deze plaatjes worden opgehaald uit de folder "google" die staat in dezelfde map als "large"en "small" (/[beeldbank]/google/) 
Plaatjes kunnen 831 pixels breed en 309 pixels hoog zijn en zullen soms een oude versie van de google map en streetview tonen. Het vullen van deze google-map moet de instelling zelf regelen. 
Op het ZCBS-forum staat een thread met de naam "google-folder vullen tbv Insert134" met daarin meer uitleg over hoe men die plaatjes maakt en genoemde map vult.

## Tags
objectpagina : hyperlink i.p.v. direct tonen google maps/streetview objectpagina


---

# INSERT135

## Titel
Homepage : plaatsing knop "Hulp bij zoeken"

## Toepassing
Homepage

## Probleem
Ik wil homepage : plaatsing knop "hulp bij zoeken"
Hoe kan ik homepage : plaatsing knop "hulp bij zoeken"
Ik zoek een oplossing voor homepage : plaatsing knop "hulp bij zoeken"
Op de homepage wordt een button geplaatst. 
Deze gaat naar een 'standaard' help pagina m.b.t. de belangrijkste homepage 


## Oplossing
Gebruik INSERT135

## Code
&INSERT135;

## Met parameters
&INSERT135 (1,"< details >","< p >\n");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT135;

## Uitleg
Op de homepage wordt een button geplaatst. 
Deze gaat naar een 'standaard' help pagina m.b.t. de belangrijkste homepage zoekmogelijkheden. 
De betreffende html-pagina is geplaatst op www.zcbs.nl/zoekhulp/index.html 
Een bijbehorende .zip file om (om een en ander geheel naar eigen wensen aan te passen) is beschikbaar op: www.zcbs.nl/zoekhulp/zoeken.zip 
 
Bij deze INSERT kan ook 3 parameters worden opgegeven om de knop een andere locatie op de homepage te geven (zie afbeelding 2 en 3) 
De 2e parameter geeft een stukje code van de homepage aan waar de knop daar voor (1e parameter is 1) of daar achter (1e parameter is 2) geplaatst moet worden. 
Met de 3e parameter kan tussen de knop en de code van parameter 2 eventueel eigen aanvullende code (veelal een < p > of een < br >) worden geplaatst.

## Tags
homepage : plaatsing knop "hulp bij zoeken" homepage


---

# INSERT136

## Titel
Linkblok : volgorde keuzes gelijk aan pull down menu

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : volgorde keuzes gelijk aan pull down menu
Hoe kan ik linkblok : volgorde keuzes gelijk aan pull down menu
Ik zoek een oplossing voor linkblok : volgorde keuzes gelijk aan pull down menu
Bij het linkblok op de homepage wordt per veld de getoonde items (met aantallen) gesorteerd weergegeven. 
Bij bepaalde v


## Oplossing
Gebruik INSERT136

## Code
&INSERT136;

## Met parameters
&INSERT136 (veldnr1,veldnr2,...);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT136 (3,18);

## Uitleg
Bij het linkblok op de homepage wordt per veld de getoonde items (met aantallen) gesorteerd weergegeven. 
Bij bepaalde velden is het beter om de belangrijkste items bovenaan te zetten en in dezelfde volgorde als in het pull down menu is opgegeven. 
Dat laatste wordt door deze INSERT gerealiseerd. 
Natuurlijk werkt deze INSERT alleen als er een pull down menu van het betreffende veld in de config file is opgenomen. 
Als argument kan een enkel veld worden opgegeven doch ook meerdere velden (gescheiden door een komma).

## Tags
linkblok : volgorde keuzes gelijk aan pull down menu linkblok


---

# INSERT137

## Titel
Homepage : zoeken met uitsluitsel(s)

## Toepassing
Homepage

## Probleem
Ik wil homepage : zoeken met uitsluitsel(s)
Hoe kan ik homepage : zoeken met uitsluitsel(s)
Ik zoek een oplossing voor homepage : zoeken met uitsluitsel(s)
Een opgegeven zoekwoord voorafgaand met een - teken wordt uitgesloten van de zoekopdracht. 
Bijvoorbeeld de zoekopdracht


## Oplossing
Gebruik INSERT137

## Code
&INSERT137;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT137;

## Uitleg
Een opgegeven zoekwoord voorafgaand met een - teken wordt uitgesloten van de zoekopdracht. 
Bijvoorbeeld de zoekopdracht: schagerbrug - sloot 
zoekt in het dorp Schagerbrug naar alle records waarin het woord sloot <em.niet voorkomt. 
Meerdere uitsluitsels zijn moegelijk, bijvoorbeeld de zoekopdracht: 
 -schagerbrug -oudesluis -petten -burgerbrug 
zoekt in de gehele beeldbank doch alleen waar de 4 genoemde zoekwoorden niet voorkomen. 
Uitsluitsels zijn handig ook bij bevoorbeeld: beheerderspagina, item E: Toon de laatste mutaties. 
Door een (bijvoorbeeld eigen) achternaam (voorafgaand met een minteken) op te geven, worden alle laatste mutaties getoond minus die van de opgegeven achternaam!

## Tags
homepage : zoeken met uitsluitsel(s) homepage


---

# INSERT138

## Titel
Homepage : simpel en alleen edt mogelijk

## Toepassing
Homepage

## Probleem
Ik wil homepage : simpel en alleen edt mogelijk
Hoe kan ik homepage : simpel en alleen edt mogelijk
Ik zoek een oplossing voor homepage : simpel en alleen edt mogelijk
Voor de groep van eenvoudige databeheerders die alleen metadata moeten aanpassen of aanvullen, kan het handig zijn om de


## Oplossing
Gebruik INSERT138

## Code
&INSERT138;

## Met parameters
&INSERT138 ("Be Ginner; Sta Giair; Vrij Willig");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT138 ("Be Ginner; Sta Giair; Vrij Willig");

## Uitleg
Voor de groep van eenvoudige databeheerders die alleen metadata moeten aanpassen of aanvullen, kan het handig zijn om de homepage van de beeldbank zo eenvoudig als mogelijk te presenteren

## Tags
homepage : simpel en alleen edt mogelijk homepage


---

# INSERT139

## Titel
Zoekresultaat : eigen systeem-zoekwoord : COPYRIGHT

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : eigen systeem-zoekwoord : copyright
Hoe kan ik zoekresultaat : eigen systeem-zoekwoord : copyright
Ik zoek een oplossing voor zoekresultaat : eigen systeem-zoekwoord : copyright
Zorgt voor het systeem-zoekwoord COPYRIGHT waarmee alle records worden getoond die op internet zijn vrijgegeven doch waa


## Oplossing
Gebruik INSERT139

## Code
&INSERT139;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT139;

## Uitleg
Zorgt voor het systeem-zoekwoord COPYRIGHT waarmee alle records worden getoond die op internet zijn vrijgegeven doch waarvan de afbeelding niet mag worden getoond. 
Zie ook de config variabele: $IMAGE_COPYRIGHT. 
Met gelijksoorige INSERT code (zie de listing) kunnen gemakkelijk andere bepaalde (eigen/locale) systeem-zoekwoorden worden gemaakt.

## Tags
zoekresultaat : eigen systeem-zoekwoord : copyright zoekresultaat


---

# INSERT140

## Titel
Reactieformulier : vereenvoudiging invulformulier

## Toepassing
Reactieformulier

## Probleem
Ik wil reactieformulier : vereenvoudiging invulformulier
Hoe kan ik reactieformulier : vereenvoudiging invulformulier
Ik zoek een oplossing voor reactieformulier : vereenvoudiging invulformulier
Bij het reactieformulier websitebezoeker worden de niet verplichte invulvelden verwijderd


## Oplossing
Gebruik INSERT140

## Code
&INSERT140;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT140;

## Uitleg
Bij het reactieformulier websitebezoeker worden de niet verplichte invulvelden verwijderd

## Tags
reactieformulier : vereenvoudiging invulformulier reactieformulier


---

# INSERT141

## Titel
Objectpagina : aanpassing volgorde velden en eventueel layout

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aanpassing volgorde velden en eventueel layout
Hoe kan ik objectpagina : aanpassing volgorde velden en eventueel layout
Ik zoek een oplossing voor objectpagina : aanpassing volgorde velden en eventueel layout
De volgorde van de velden op de objectpagina kunnen via deze INSERT eenvoudig worden aangepast. 
Dit moet wel apart voor


## Oplossing
Gebruik INSERT141

## Code
&INSERT141;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT141 ("2,blanco,25,5,7,blanco,28,8,11,9,6,26"); ## extern 
&INSERT141 ("15,blanco,31,17,16,30,12,13,blanco,20,10,blanco,21,27,19"); ## intern

## Uitleg
De volgorde van de velden op de objectpagina kunnen via deze INSERT eenvoudig worden aangepast. 
Dit moet wel apart voor de externe en voor de interne velden uitgevoerd worden. 
Indien zowel extern als intern de volgorde moeten worden aangepast, dan moet deze INSERT dus ook 2 keer worden aangeroepen! 
Let op dat: 
1. de INSERT-aanroep voor de **externe** velden altijd begint met: 2,blanco. 
2. de INSERT-aanroep voor de **interne** velden altijd veld 21 bevat. 
 
Bij de aanroep **kan** men eventueel een extra parameter "layout" toevoegen om groepen van velden van een kader te voorzien. 
Bij alleen deze parameter gelden default parameters: 
- de linker kolom met de veldnamen is 185px breed 
- de kleur van het kader is #ddd 
 
Deze default parameters zijn vanzelfsprekend aan te passen, bijvoorbeeld: 
 <samp>...,layout,390,#bbbbbb</samp> 
De tekst layout is vast. 
 
Deze aanvullende gegevens worden ingevuld in de INSERT141 parameterlijst van de **externe** velden. 
De extra parameters

## Tags
objectpagina : aanpassing volgorde velden en eventueel layout objectpagina


---

# INSERT142

## Titel
Linkblok : layout subrubriek uitklapbaar bij rubriek/subrubriek

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : layout subrubriek uitklapbaar bij rubriek/subrubriek
Hoe kan ik linkblok : layout subrubriek uitklapbaar bij rubriek/subrubriek
Ik zoek een oplossing voor linkblok : layout subrubriek uitklapbaar bij rubriek/subrubriek
I.p.v. de subrubrieken die bij een rubriek horen wordt een uitklapbare lijst getoond welke te openen is door te klikken 


## Oplossing
Gebruik INSERT142

## Code
&INSERT142;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT142;

## Uitleg
I.p.v. de subrubrieken die bij een rubriek horen wordt een uitklapbare lijst getoond welke te openen is door te klikken op de tekst: Toon de subrubrieken. 
Dat geldt alleen voor de rubrieken waar ook subrubrieken bij horen. 
Voor de duidelijkheid zijn daarnaast de rubrieken gescheiden met een extra blanco regel. 
Zie ook het alternatief INSERTlib nr. 146 
Aanvulling: 
De tekst 'Toon de rubrieken' kan met een parameter (1) aangepast worden. 
I.p.v. 'de rubrieken', wordt de naam van de rubrieken getoond.

## Tags
linkblok : layout subrubriek uitklapbaar bij rubriek/subrubriek linkblok


---

# INSERT143

## Titel
Homepage : verwissel geboren/overleden daterings-zoekveld

## Toepassing
Homepage

## Probleem
Ik wil homepage : verwissel geboren/overleden daterings-zoekveld
Hoe kan ik homepage : verwissel geboren/overleden daterings-zoekveld
Ik zoek een oplossing voor homepage : verwissel geboren/overleden daterings-zoekveld
Bij zoeken in een veld kan een aanvullende selectie worden gemaakt via het extra dateringsveld. 
De naam van dat veld ka


## Oplossing
Gebruik INSERT143

## Code
&INSERT143;

## Met parameters
&INSERT143 ("datumveld");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT143(23);

## Uitleg
Bij zoeken in een veld kan een aanvullende selectie worden gemaakt via het extra dateringsveld. 
De naam van dat veld kan zijn: 
- Periode/jaar als de opgegeven naam van het dateringsveld Datum, Datering of Periode is. 
- In andere gevallen de opgegeven naam van het dateringsveld (veld 08). 
Bij onder meer bidprentjes en grafmonumenten zijn er veelal 2 velden met een datum inhoud, veld 08 en een ander veld 
Via deze INSERT kan nu gefilterd worden op 1 van deze 2 velden. 
Door als parameter (veldnummer 2e dateringsveld) een negatieve waarde op te geven worden de twee getoonde keuzes verwisseld.

## Tags
homepage : verwissel geboren/overleden daterings-zoekveld homepage


---

# INSERT144

## Titel
Homepage : knop beperkt/uitgebreid zoekmogelijkheid

## Toepassing
Homepage

## Probleem
Ik wil homepage : knop beperkt/uitgebreid zoekmogelijkheid
Hoe kan ik homepage : knop beperkt/uitgebreid zoekmogelijkheid
Ik zoek een oplossing voor homepage : knop beperkt/uitgebreid zoekmogelijkheid
De uitgebreide zoekopties op de homepage van de beeldbank kan via een pijltje/link of button worden opgeroepen. 
Default


## Oplossing
Gebruik INSERT144

## Code
&INSERT144;

## Met parameters
&INSERT144 (1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT144; 
&INSERT144 (1);

## Uitleg
De uitgebreide zoekopties op de homepage van de beeldbank kan via een pijltje/link of button worden opgeroepen. 
Default wordt een pijltje getoond 
Als een parameter 1 wordt opgegeven wordt i.p.v. het pijltje een button getoond 
De getoonde tekst (in beide gevallen) kan eventueel nog aangepast worden door na deze INSERT144 een INSERT9 op te nemen.

## Tags
homepage : knop beperkt/uitgebreid zoekmogelijkheid homepage


---

# INSERT145

## Titel
Diversen : Voornaam Achternaam naar Achternaam, Voornaam

## Toepassing
Alle webpagina's

## Probleem
Ik wil diversen : voornaam achternaam naar achternaam, voornaam
Hoe kan ik diversen : voornaam achternaam naar achternaam, voornaam
Ik zoek een oplossing voor diversen : voornaam achternaam naar achternaam, voornaam
Maakt een database aan waarbij voor een veld waarin alleen persoonsnamen voorkomen, de Voornaam Achternaam combinatie wo


## Oplossing
Gebruik INSERT145

## Code
&INSERT145;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT145;

## Uitleg
Maakt een database aan waarbij voor een veld waarin alleen persoonsnamen voorkomen, de Voornaam Achternaam combinatie wordt omgezet naar Achternaam, Voornaam (voor zover het mogelijk is). 
Zie ook het laatste gedeelte van de webinar presentatie op: www.zcbs.nl/cgi-bin/documentatie.pl?i=239 
Om het proces te starten dient het volgende systeem(zoekwoord)commando gegeven te worden ACHTERNAAM 
Met direct daarachter het veldnummer met de persoonsnamen. 
Bijvoorbeeld voor het auteursveld: ACHTERNAAM7 
 
De te volgen werkwijze is als volgt: 
Stap A: 
1. Plaats &INSERT145 in de config 
2. Zorg dat bij meerdere namen deze gescheiden zijn met een punt-komma 
Stap B: 
1. Geef systeemzoekwoord: ACHTERNAAM7 (indien veld7 de persoonsnamen bevat) 
      Het output bestand op de webserver personen_out.txt bevat nu alle aanpassingen 
2. Verwijder in dit bestand de regels die de **juiste** omzetting bevatten. 
2. Rename: personen_out.txt naar personen_in.txt (zie ook de informatie aan het begin van dit bestand). 
4. Geef opnieuw systeemzoekwoord: ACHTERNAAM7 
Stap C: 
1. Controleer of alle omzettingen nu goed zijn 
2. Vergelijk goed de aangemaakte database met de oorspronkelijke 
      Maak eventueel van de aangemaakte database, een test-database [beeldbank]2.txt 
3. Indien oke, vervang dan [beeldbank]_new.txt door [beeldbank].txt

## Tags
diversen : voornaam achternaam naar achternaam, voornaam alle webpagina's


---

# INSERT146

## Titel
Linkblok : uitklapbaar bij item/subitem

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : uitklapbaar bij item/subitem
Hoe kan ik linkblok : uitklapbaar bij item/subitem
Ik zoek een oplossing voor linkblok : uitklapbaar bij item/subitem
Bij subrubrieken die bij een rubriek horen (en eveneens adressen bij plaatsnamen) worden alleen 
de rubrieken (dan wel p


## Oplossing
Gebruik INSERT146

## Code
&INSERT146;

## Met parameters
&INSERT146(1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT146;

## Uitleg
Bij subrubrieken die bij een rubriek horen (en eveneens adressen bij plaatsnamen) worden alleen 
de rubrieken (dan wel plaatsnamen) getoond in het linkblok. 
Door op een item te klikken verschijnen de bijbehorende subitems. 
Via een parameter kan een keuze worden gemaakt: 
- geen parameter of een 1 : INSERT werkt voor veld 03 en bijbehorende 04 
- parameter 2 : INSERT werkt voor veld 12 en bijbehorende 14 
- parameter 3 : INSERT werkt zowel op de combinatie 03/04 als 12/14 
Let wel dat bij de config $LINKBLOK het betreffende veld niet in meerdere kolommen is gesplitst! 
Zie ook het alternatief INSERTlib nr. 142 
Het gebruik van deze INSERT maakt het linkblok een stuk overzichtelijker.

## Tags
linkblok : uitklapbaar bij item/subitem linkblok


---

# INSERT147

## Titel
Homepage : toon laatst geplaatste objecten op internet

## Toepassing
Homepage

## Probleem
Ik wil homepage : toon laatst geplaatste objecten op internet
Hoe kan ik homepage : toon laatst geplaatste objecten op internet
Ik zoek een oplossing voor homepage : toon laatst geplaatste objecten op internet
Standaard wordt op de beeldbank homepage de volgende regels getoond, intern bijvoorbeeld: 
- <code>Of toon de nieuwe dat


## Oplossing
Gebruik INSERT147

## Code
&INSERT147;

## Met parameters
&INSERT147 (1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT147;

## Uitleg
Standaard wordt op de beeldbank homepage de volgende regels getoond, intern bijvoorbeeld: 
- <code>Of toon de nieuwe databaserecords op internet van laatste : half jaar (9) ... jaar (13)</code> 
- <code>Of toon de nieuwe databaserecords op intranet van : 13-01-2024 (4x) ... 08-11-2024 (4x) ... 02-03-2025 (9x)</code> 
en bij externe bezoekers alleen de eerste regel 
 
Met INSERT147 wordt standaard getoond intern een extra een regel: 
- <code>Of toon de laatst geplaatste objecten op internet van : 05-03-2025 (9x)</code> 
Dus expliciet de laatste volledige datum (+aantal). 
 
Deze INSERT kent ook een parameter: 
- 1 : analoog de default zonder parameter: toon alleen de laatste beschikbaarstelling 
- 2 : toon de laatste 2 beschikbaarstellings datums 
- 3 : toon de laatste 3 beschikbaarstellings datums 
Zie ook de voorbeelden 
 
<CAR> 
1 : webpagina intern zonder gebruikmaking van &INSERT147 
<CAR> 
2 : webpagina extern zonder gebruikmaking van &INSERT147 
<CAR> 
3 : webpagina intern met gebruikmaking van &INSERT147 of INSERT147(1) 
<CAR> 
4 : webpagina extern met gebruikmaking van &INSERT147 of INSERT147(1) 
<CAR> 
5 : webpagina extern met gebruikmaking van &INSERT147(2); 
<CAR> 
6 : webpagina extern met gebruikmaking van &INSERT147(3); 
</CAR>

## Tags
homepage : toon laatst geplaatste objecten op internet homepage


---

# INSERT148

## Titel
Objectpagina : Aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Hoe kan ik objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Ik zoek een oplossing voor objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Indien men een record heeft met carrousel afbeeldingen kan men bij het kiezen van een bepaalde carrouselafbeelding zowel


## Oplossing
Gebruik INSERT148

## Code
&INSERT148;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT148;

## Uitleg
Indien men een record heeft met carrousel afbeeldingen kan men bij het kiezen van een bepaalde carrouselafbeelding zowel onder de afbeelding een variabele titel plaatsen als ook bij de beschrijving een (aanvullende) variabele tekst. 
Om dat te bereiken dient men in het bijzonderhedenveld (bij het edit scherm) het volgende op te nemen: 
Eventuele algemene beschrijving, 
< CAR > 
De 1e regel :Titel 1e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 1e carrousel afbeelding 
< CAR > 
De 1e regel :Titel 2e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 2e carrousel afbeelding 
< CAR > 
De 1e regel :Titel 3e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 3e carrousel afbeelding 
< CAR > 
etc 
< /CAR > 
Eventuele aanvullende algemene beschrijving. 
Bij een carrousel afbeelding mag eventueel beschrijving of titel+beschrijving weg worden gelaten. 
Het aantal < CAR > tags hoort overeen te komen met het aantal carrousel afbeeldingen. 
De set van < CAR >-tags dient afgesloten te worden met < /CAR >-tag 
Let op: 
Deze INSERT dient voor een eventueel gebruikte INSERT141 geplaatst te worden.

## Tags
objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record objectpagina


---

# INSERT149

## Titel
Webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]

## Toepassing
Lijst personen

## Probleem
Ik wil webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Hoe kan ik webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Ik zoek een oplossing voor webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Standaard kan slechts in 1 veld de namen van personen verzameld worden door deze tussen vierkante haken te plaatsen. 
In


## Oplossing
Gebruik INSERT149

## Code
&INSERT149;

## Met parameters
&INSERT149 (verzamelveld,veld_met_namen_1,veld_met_namen_2);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT149 (25,5,6);

## Uitleg
Standaard kan slechts in 1 veld de namen van personen verzameld worden door deze tussen vierkante haken te plaatsen. 
In de config file dient dit geactiveerd te worden via de opdracht $PERSONEN = ...; 
Met deze INSERT kan dat uitgebreid worden met 2 velden. 
Daartoe moet er wel een vrij veld beschikbaar zijn. 
De aanroep van INSERT149 kent daarop 3 parameters waarvan de eerste het vrije "verzamel"-veld is en de volgende 2 de betreffende 2 velden met namen tussen de vierkante haken.

## Tags
webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam] lijst personen


---

# INSERT150

## Titel
Zoekresultaat : toevoegen sorteerknop

## Toepassing
Zoekresultaat

## Probleem
Ik wil zoekresultaat : toevoegen sorteerknop
Hoe kan ik zoekresultaat : toevoegen sorteerknop
Ik zoek een oplossing voor zoekresultaat : toevoegen sorteerknop
Bij de zoekresultatenpagina, verkregen via een zoekopdracht of via een link van het linkblok, wordt een knop getoond waa


## Oplossing
Gebruik INSERT150

## Code
&INSERT150;

## Met parameters
&INSERT150 ("veldnummers");

## Voorbeeld
&INSERT150 ("2,8,3,15,5,9,3,29");

## Uitleg
Bij de zoekresultatenpagina, verkregen via een zoekopdracht of via een link van het linkblok, wordt een knop getoond waar men een andere sorteeroptie kan kiezen van hetzelfde zoekopdracht resultaat. 
Opgegeven wordt als argument van de INSERT de externe en/of interne velden die men in het pull down menu getoond wilt hebben.

## Tags
zoekresultaat : toevoegen sorteerknop zoekresultaat


---

# INSERT190

## Titel
Alle webpagina's : UTF-8 code naar ANSI

## Toepassing
Alle webpagina's

## Probleem
Ik wil alle webpagina's : utf-8 code naar ansi
Hoe kan ik alle webpagina's : utf-8 code naar ansi
Ik zoek een oplossing voor alle webpagina's : utf-8 code naar ansi
Diakritische tekens in UTF-8 worden omgezet in voor ZCBS goed te tonen ANSI tekens.


## Oplossing
Gebruik INSERT190

## Code
&INSERT190;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT190;

## Uitleg
Diakritische tekens in UTF-8 worden omgezet in voor ZCBS goed te tonen ANSI tekens.

## Tags
alle webpagina's : utf-8 code naar ansi alle webpagina's


---

# INSERT191

## Titel
Alle webpagina's : vertaalt ZCBS-output naar Engels

## Toepassing
Alle webpagina's

## Probleem
Ik wil alle webpagina's : vertaalt zcbs-output naar engels
Hoe kan ik alle webpagina's : vertaalt zcbs-output naar engels
Ik zoek een oplossing voor alle webpagina's : vertaalt zcbs-output naar engels
Vertaalt alle door het ZCBS-programma (objecten.pl) gebruikte woorden in het Engels. 
Deze INSERT werd voorheen (2016) t


## Oplossing
Gebruik INSERT191

## Code
&INSERT191;

## Met parameters
&INSERT191;

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT191;

## Uitleg
Vertaalt alle door het ZCBS-programma (objecten.pl) gebruikte woorden in het Engels. 
Deze INSERT werd voorheen (2016) toegepast bij het TRANSLATE commando en is een voorloper van alle INSERT's (zie de Tech.Doc. 8.13.1). 
De database zelf en de instellingen in het config bestand moeten natuurlijk zelf in het Engels worden aangeboden.

## Tags
alle webpagina's : vertaalt zcbs-output naar engels alle webpagina's


---

