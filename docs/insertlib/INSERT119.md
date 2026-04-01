# INSERT119

## Titel
Linkblok : samenvoegen 2 velden in linkblok

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : samenvoegen 2 velden in linkblok
Hoe kan ik linkblok : samenvoegen 2 velden in linkblok
Ik zoek een oplossing voor linkblok : samenvoegen 2 velden in linkblok
Twee velden in het linkblok worden samengevoegd tot een enkel veld. 
De INSERT119 kan maximaal 2 keer worden aangeroepen


## Oplossing
Gebruik INSERT119

## Code
&INSERT119;

## Met parameters
&INSERT119 (nr_1e_veld; nr_2e_veld; "nieuwe_veldnaam");

## Voorbeeld
require "misc/insertlib2.pm"; 
&INSERT119 (25,26, "Beroep verkoper/koper"); ## Linkblok : samenvoegen 2 velden 
&INSERT119 (24,22, "Achternaam koper/verkoper"); ## Linkblok : samenvoegen 2 velden 
&INSERT101; ## Linkblok : verwijder de losse (1) 
&INSERT111("Achternaam koper/verkoper"); ## Linkblok : uitklapbaar (verticaal) alfabet(ten)

## Uitleg
Twee velden in het linkblok worden samengevoegd tot een enkel veld. 
De INSERT119 kan maximaal 2 keer worden aangeroepen (dus samenvoegen van maximaal 2x2 velden. 
Voorbeeld: samenvoegen van een veld achternaam overledene en van partner en/of van beroep koper en verkoper 
Let op: 
Een INSERT101 aanroep mag nooit voor een INSERT119 plaatvinden. 
Na een INSERT119 kan bijvoorbeeld wel een INSERT111 opgenomen worden (uitklapbaar verticaal alfabet). 
De INSERT119 kent altijd 3 parameters: 2 getallen (veldnummers) en 1 tekststring tussen quotes (nieuwe veldnaam).

## Tags
linkblok : samenvoegen 2 velden in linkblok linkblok
