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
