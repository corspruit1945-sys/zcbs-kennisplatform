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
