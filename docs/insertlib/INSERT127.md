# INSERT127

## Titel
Objectpagina : aanpassen linkerkant reactieformulier

## Toepassing
Objectpagina

## Probleem
Ik wil objectpagina : aanpassen linkerkant reactieformulier
Hoe kan ik objectpagina : aanpassen linkerkant reactieformulier
Ik zoek een oplossing voor objectpagina : aanpassen linkerkant reactieformulier
De standaard recordgegevens aan de linker kant van een reactieformulier kunnen worden vervangen door een eigen keuze van


## Oplossing
Gebruik INSERT127

## Code
&INSERT127;

## Met parameters
n.v.t.

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT127 ("20, 0, 11,28,9, 00, 4,3,24");

## Uitleg
De standaard recordgegevens aan de linker kant van een reactieformulier kunnen worden vervangen door een eigen keuze van velden. 
Het veld met het databasenummer kan niet vervangen worden. 
De eigen gekozen velden worden onder het veld met het databasenummer geplaatst. 
Opgegeven moet worden de veldnummers (de nul voor de velden beneden de 10 mag worden weggelaten. 
De volgorde van de velden wordt bepaald door de opgegeven veldnummers bij de aanroep van INSERT127. 
Door het opgeven van veldnummer 0 of 00 wordt een blanco regel geplaatst.

## Tags
objectpagina : aanpassen linkerkant reactieformulier objectpagina
