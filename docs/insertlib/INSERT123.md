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
