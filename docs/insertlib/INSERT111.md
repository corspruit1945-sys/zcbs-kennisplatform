# INSERT111

## Titel
Linkblok : uitklapbaar verticaal alfabet(ten)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : uitklapbaar verticaal alfabet(ten)
Hoe kan ik linkblok : uitklapbaar verticaal alfabet(ten)
Ik zoek een oplossing voor linkblok : uitklapbaar verticaal alfabet(ten)
Wanneer een lijst van een van de velden in het link blok (te) lang is, kan deze vervangen worden door een verticale 'alf


## Oplossing
Gebruik INSERT111

## Code
&INSERT111;

## Met parameters
&INSERT111 ("veld-a; veld-b; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT111("Familienaam; Auteur");

## Uitleg
Wanneer een lijst van een van de velden in het link blok (te) lang is, kan deze vervangen worden door een verticale 'alfabet'-lijst. 
Door op een letter te klikken worden alle waarden getoond die met de betreffende letter beginnen. 
Door nog een keer op de letter te klikken wordt de uitgeklapte lijst gesloten. 
Dat gebeurt eveneens als er een andere letter wordt aangeklikt. 
Via het argument van de INSERT-aanroep kan men 1 of meerdere velden opgeven. 
Zie ook #124: www.zcbs.nl/cgi-bin/insertlib.pl?i=124 
==> Let op: 
==> Als argument moet veldnaam worden gebruikt en geen veldnummer! 
==> De oorspronkelijke lijst (in $LINKBLOK) mag niet over meerdere kolommen zijn ingesteld!

## Tags
linkblok : uitklapbaar verticaal alfabet(ten) linkblok
