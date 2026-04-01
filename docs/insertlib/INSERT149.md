# INSERT149

## Titel
Webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]

## Toepassing
Lijst personen

## Probleem
Ik wil webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Hoe kan ik webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Ik zoek een oplossing voor webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam]
Standaard kan slechts in 1 veld de namen van personen verzameld worden door deze tussen vierkante haken te plaatsen. 
In


## Oplossing
Gebruik INSERT149

## Code
&INSERT149;

## Met parameters
&INSERT149 (verzamelveld,veld_met_namen_1,veld_met_namen_2);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT149 (25,5,6);

## Uitleg
Standaard kan slechts in 1 veld de namen van personen verzameld worden door deze tussen vierkante haken te plaatsen. 
In de config file dient dit geactiveerd te worden via de opdracht $PERSONEN = ...; 
Met deze INSERT kan dat uitgebreid worden met 2 velden. 
Daartoe moet er wel een vrij veld beschikbaar zijn. 
De aanroep van INSERT149 kent daarop 3 parameters waarvan de eerste het vrije "verzamel"-veld is en de volgende 2 de betreffende 2 velden met namen tussen de vierkante haken.

## Tags
webpagina personen.html : twee velden t.b.v. lijst met [persoonsnaam] lijst personen
