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
