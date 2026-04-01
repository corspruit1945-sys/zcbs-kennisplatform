# INSERT148

## Titel
Objectpagina : Aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Hoe kan ik objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Ik zoek een oplossing voor objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record
Indien men een record heeft met carrousel afbeeldingen kan men bij het kiezen van een bepaalde carrouselafbeelding zowel


## Oplossing
Gebruik INSERT148

## Code
&INSERT148;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT148;

## Uitleg
Indien men een record heeft met carrousel afbeeldingen kan men bij het kiezen van een bepaalde carrouselafbeelding zowel onder de afbeelding een variabele titel plaatsen als ook bij de beschrijving een (aanvullende) variabele tekst. 
Om dat te bereiken dient men in het bijzonderhedenveld (bij het edit scherm) het volgende op te nemen: 
Eventuele algemene beschrijving, 
< CAR > 
De 1e regel :Titel 1e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 1e carrousel afbeelding 
< CAR > 
De 1e regel :Titel 2e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 2e carrousel afbeelding 
< CAR > 
De 1e regel :Titel 3e carrousel afbeelding 
De 2e en eventueel volgende regels: beschrijving 3e carrousel afbeelding 
< CAR > 
etc 
< /CAR > 
Eventuele aanvullende algemene beschrijving. 
Bij een carrousel afbeelding mag eventueel beschrijving of titel+beschrijving weg worden gelaten. 
Het aantal < CAR > tags hoort overeen te komen met het aantal carrousel afbeeldingen. 
De set van < CAR >-tags dient afgesloten te worden met < /CAR >-tag 
Let op: 
Deze INSERT dient voor een eventueel gebruikte INSERT141 geplaatst te worden.

## Tags
objectpagina : aparte teksten titel+beschrijving bij elke carrousel afbeelding van een record objectpagina
