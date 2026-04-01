# INSERT117

## Titel
Linkblok : afwijkend (ongelijk aan 14) adresveld

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : afwijkend (ongelijk aan 14) adresveld
Hoe kan ik linkblok : afwijkend (ongelijk aan 14) adresveld
Ik zoek een oplossing voor linkblok : afwijkend (ongelijk aan 14) adresveld
Een adresveld bestaat veelal uit 2 delen: de straatnaam en het huisnummer. 
Als gezocht wordt op een adres via het linkb


## Oplossing
Gebruik INSERT117

## Code
&INSERT117;

## Met parameters
&INSERT117 ("veldnummer");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT117("24");

## Uitleg
Een adresveld bestaat veelal uit 2 delen: de straatnaam en het huisnummer. 
Als gezocht wordt op een adres via het linkblok wordt alleen exact gezocht op de straatnaam zelf, dus zonder het huisnummer. 
Binnen ZCBS wordt hier rekening mee gehouden zolang veld14 het adres bevat 
Indien het adres in een ander veld staat, moet echter van deze INSERT gebruik worden gemaakt om er voor te zorgen dat er geen exacte match wordt gevonden met het adres doch alleen met de straatnaam.

## Tags
linkblok : afwijkend (ongelijk aan 14) adresveld linkblok
