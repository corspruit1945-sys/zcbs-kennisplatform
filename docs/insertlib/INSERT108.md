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
