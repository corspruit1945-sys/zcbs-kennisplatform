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
