# INSERT147

## Titel
Homepage : toon laatst geplaatste objecten op internet

## Toepassing
Homepage

## Probleem
Ik wil homepage : toon laatst geplaatste objecten op internet
Hoe kan ik homepage : toon laatst geplaatste objecten op internet
Ik zoek een oplossing voor homepage : toon laatst geplaatste objecten op internet
Standaard wordt op de beeldbank homepage de volgende regels getoond, intern bijvoorbeeld: 
- <code>Of toon de nieuwe dat


## Oplossing
Gebruik INSERT147

## Code
&INSERT147;

## Met parameters
&INSERT147 (1);

## Voorbeeld
require "misc/insertlib.pm"; 
&INSERT147;

## Uitleg
Standaard wordt op de beeldbank homepage de volgende regels getoond, intern bijvoorbeeld: 
- <code>Of toon de nieuwe databaserecords op internet van laatste : half jaar (9) ... jaar (13)</code> 
- <code>Of toon de nieuwe databaserecords op intranet van : 13-01-2024 (4x) ... 08-11-2024 (4x) ... 02-03-2025 (9x)</code> 
en bij externe bezoekers alleen de eerste regel 
 
Met INSERT147 wordt standaard getoond intern een extra een regel: 
- <code>Of toon de laatst geplaatste objecten op internet van : 05-03-2025 (9x)</code> 
Dus expliciet de laatste volledige datum (+aantal). 
 
Deze INSERT kent ook een parameter: 
- 1 : analoog de default zonder parameter: toon alleen de laatste beschikbaarstelling 
- 2 : toon de laatste 2 beschikbaarstellings datums 
- 3 : toon de laatste 3 beschikbaarstellings datums 
Zie ook de voorbeelden 
 
<CAR> 
1 : webpagina intern zonder gebruikmaking van &INSERT147 
<CAR> 
2 : webpagina extern zonder gebruikmaking van &INSERT147 
<CAR> 
3 : webpagina intern met gebruikmaking van &INSERT147 of INSERT147(1) 
<CAR> 
4 : webpagina extern met gebruikmaking van &INSERT147 of INSERT147(1) 
<CAR> 
5 : webpagina extern met gebruikmaking van &INSERT147(2); 
<CAR> 
6 : webpagina extern met gebruikmaking van &INSERT147(3); 
</CAR>

## Tags
homepage : toon laatst geplaatste objecten op internet homepage
