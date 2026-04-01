# INSERT141

## Titel
Objectpagina : aanpassing volgorde velden en eventueel layout

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aanpassing volgorde velden en eventueel layout
Hoe kan ik objectpagina : aanpassing volgorde velden en eventueel layout
Ik zoek een oplossing voor objectpagina : aanpassing volgorde velden en eventueel layout
De volgorde van de velden op de objectpagina kunnen via deze INSERT eenvoudig worden aangepast. 
Dit moet wel apart voor


## Oplossing
Gebruik INSERT141

## Code
&INSERT141;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT141 ("2,blanco,25,5,7,blanco,28,8,11,9,6,26"); ## extern 
&INSERT141 ("15,blanco,31,17,16,30,12,13,blanco,20,10,blanco,21,27,19"); ## intern

## Uitleg
De volgorde van de velden op de objectpagina kunnen via deze INSERT eenvoudig worden aangepast. 
Dit moet wel apart voor de externe en voor de interne velden uitgevoerd worden. 
Indien zowel extern als intern de volgorde moeten worden aangepast, dan moet deze INSERT dus ook 2 keer worden aangeroepen! 
Let op dat: 
1. de INSERT-aanroep voor de **externe** velden altijd begint met: 2,blanco. 
2. de INSERT-aanroep voor de **interne** velden altijd veld 21 bevat. 
 
Bij de aanroep **kan** men eventueel een extra parameter "layout" toevoegen om groepen van velden van een kader te voorzien. 
Bij alleen deze parameter gelden default parameters: 
- de linker kolom met de veldnamen is 185px breed 
- de kleur van het kader is #ddd 
 
Deze default parameters zijn vanzelfsprekend aan te passen, bijvoorbeeld: 
 <samp>...,layout,390,#bbbbbb</samp> 
De tekst layout is vast. 
 
Deze aanvullende gegevens worden ingevuld in de INSERT141 parameterlijst van de **externe** velden. 
De extra parameters

## Tags
objectpagina : aanpassing volgorde velden en eventueel layout objectpagina
