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
