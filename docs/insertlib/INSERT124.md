# INSERT124

## Titel
Linkblok : verwerking de voorvoegsels: 's- en 't (na INSERT111)

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Hoe kan ik linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Ik zoek een oplossing voor linkblok : verwerking de voorvoegsels: 's- en 't (na insert111)
Indien INSERT111 wordt gebruikt voor (onder meer) plaatsnamen en daarbij plaatsen voorkomen met voorvoegsels 's (zoals b


## Oplossing
Gebruik INSERT124

## Code
&INSERT124;

## Met parameters
&INSERT124 ("veldnr1; veldnr2; ...");

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT124 ("06; 23");

## Uitleg
Indien INSERT111 wordt gebruikt voor (onder meer) plaatsnamen en daarbij plaatsen voorkomen met voorvoegsels 's (zoals bij 's-Gravenhage) of voorvoegsel 't (zoals bij bijvoorbeeld 't Zand), worden deze niet goed in het getoonde linkblok alfabet ondergebracht (namelijk onder het teken ' i.p.v. onder een letter). 
Bij bijvoorbeeld de plaatsnaam 's-Gravenhage wordt met de INSERT124 genoemde plaats nu onder de letter G ondergebracht. 
Let op: 
&INSERT124 moet altijd na &INSERT111 worden aangeroepen (vanwege de juiste verwerking van de INSERT9 in beide subroutines). 
Zie #111: www.zcbs.nl/cgi-bin/insertlib.pl?i=124 
Niet alleen bij plaatsnamen is deze INSERT actief doch ook bijvoorbeeld bij velden als auteurs, familienamen, etc..

## Tags
linkblok : verwerking de voorvoegsels: 's- en 't (na insert111) linkblok
