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
