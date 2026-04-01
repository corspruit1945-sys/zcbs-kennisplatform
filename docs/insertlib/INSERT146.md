# INSERT146

## Titel
Linkblok : uitklapbaar bij item/subitem

## Toepassing
Linkblok

## Probleem
Ik wil linkblok : uitklapbaar bij item/subitem
Hoe kan ik linkblok : uitklapbaar bij item/subitem
Ik zoek een oplossing voor linkblok : uitklapbaar bij item/subitem
Bij subrubrieken die bij een rubriek horen (en eveneens adressen bij plaatsnamen) worden alleen 
de rubrieken (dan wel p


## Oplossing
Gebruik INSERT146

## Code
&INSERT146;

## Met parameters
&INSERT146(1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT146;

## Uitleg
Bij subrubrieken die bij een rubriek horen (en eveneens adressen bij plaatsnamen) worden alleen 
de rubrieken (dan wel plaatsnamen) getoond in het linkblok. 
Door op een item te klikken verschijnen de bijbehorende subitems. 
Via een parameter kan een keuze worden gemaakt: 
- geen parameter of een 1 : INSERT werkt voor veld 03 en bijbehorende 04 
- parameter 2 : INSERT werkt voor veld 12 en bijbehorende 14 
- parameter 3 : INSERT werkt zowel op de combinatie 03/04 als 12/14 
Let wel dat bij de config $LINKBLOK het betreffende veld niet in meerdere kolommen is gesplitst! 
Zie ook het alternatief INSERTlib nr. 142 
Het gebruik van deze INSERT maakt het linkblok een stuk overzichtelijker.

## Tags
linkblok : uitklapbaar bij item/subitem linkblok
