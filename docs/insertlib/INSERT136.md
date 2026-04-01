# INSERT136

## Titel
Linkblok : volgorde keuzes gelijk aan pull down menu

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : volgorde keuzes gelijk aan pull down menu
Hoe kan ik linkblok : volgorde keuzes gelijk aan pull down menu
Ik zoek een oplossing voor linkblok : volgorde keuzes gelijk aan pull down menu
Bij het linkblok op de homepage wordt per veld de getoonde items (met aantallen) gesorteerd weergegeven. 
Bij bepaalde v


## Oplossing
Gebruik INSERT136

## Code
&INSERT136;

## Met parameters
&INSERT136 (veldnr1,veldnr2,...);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT136 (3,18);

## Uitleg
Bij het linkblok op de homepage wordt per veld de getoonde items (met aantallen) gesorteerd weergegeven. 
Bij bepaalde velden is het beter om de belangrijkste items bovenaan te zetten en in dezelfde volgorde als in het pull down menu is opgegeven. 
Dat laatste wordt door deze INSERT gerealiseerd. 
Natuurlijk werkt deze INSERT alleen als er een pull down menu van het betreffende veld in de config file is opgenomen. 
Als argument kan een enkel veld worden opgegeven doch ook meerdere velden (gescheiden door een komma).

## Tags
linkblok : volgorde keuzes gelijk aan pull down menu linkblok
