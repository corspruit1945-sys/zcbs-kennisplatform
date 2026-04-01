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
