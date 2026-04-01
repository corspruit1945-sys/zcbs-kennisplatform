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
