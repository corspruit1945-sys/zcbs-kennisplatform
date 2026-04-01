# INSERT143

## Titel
Homepage : verwissel geboren/overleden daterings-zoekveld

## Toepassing
Homepage

## Probleem
Ik wil homepage : verwissel geboren/overleden daterings-zoekveld
Hoe kan ik homepage : verwissel geboren/overleden daterings-zoekveld
Ik zoek een oplossing voor homepage : verwissel geboren/overleden daterings-zoekveld
Bij zoeken in een veld kan een aanvullende selectie worden gemaakt via het extra dateringsveld. 
De naam van dat veld ka


## Oplossing
Gebruik INSERT143

## Code
&INSERT143;

## Met parameters
&INSERT143 ("datumveld");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT143(23);

## Uitleg
Bij zoeken in een veld kan een aanvullende selectie worden gemaakt via het extra dateringsveld. 
De naam van dat veld kan zijn: 
- Periode/jaar als de opgegeven naam van het dateringsveld Datum, Datering of Periode is. 
- In andere gevallen de opgegeven naam van het dateringsveld (veld 08). 
Bij onder meer bidprentjes en grafmonumenten zijn er veelal 2 velden met een datum inhoud, veld 08 en een ander veld 
Via deze INSERT kan nu gefilterd worden op 1 van deze 2 velden. 
Door als parameter (veldnummer 2e dateringsveld) een negatieve waarde op te geven worden de twee getoonde keuzes verwisseld.

## Tags
homepage : verwissel geboren/overleden daterings-zoekveld homepage
