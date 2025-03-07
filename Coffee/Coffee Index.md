---
tags:
  - gakundu
  - coffee
  - chemex
name: Gakundu
roaster: Rehorik
category: Filterkaffee
link: https://www.rehorik.de/produkt/filterkaffee-gakundu/
price_250: 8,90€
type: 100% Arabica
origin: Kenia
taste: Cranberry, Hagebutte
rating: 8
brew_method: Chemex
date_added: 18.08.23
---

## Zubereitung

### Chemex 
* 250ml / 16g: 
	* Bloom: 30 Sekunden 40-50g Wasser
	* Durchlaufzeit: 2:30
*  300ml / 20g: 
	* Bloom: 30 Sekunden -> Rest langsam aufgießen 
	* Durchlaufzeit: 3:00

### v60
* 250ml / 15g: 
	* Bloom: 30 Sekunden 30-40g Wasser
	* Aufgusszyklen: 100g -140g - 180g - 250g
	* Durchlaufzeit: 2:30
## Zubereitung

### Chemex 
* 250ml / 16g: 
	* Bloom: 30 Sekunden 40-50g Wasser
	* Durchlaufzeit: 2:30
*  300ml / 20g: 
	* Bloom: 30 Sekunden -> Rest langsam aufgießen 
	* Durchlaufzeit: 3:00

### v60
* 250ml / 15g: 
	* Bloom: 30 Sekunden 30-40g Wasser
	* Aufgusszyklen: 100g -140g - 180g - 250g
	* Durchlaufzeit: 2:30
```dataview
table origin as "Origin", taste as "Taste Profile", rating as "Rating", brew_method as "Brew Sytle", price_250 as "250g"
from "Coffee"
where category="coffee" or category="Coffee" or category="Filterkaffee"
sort rating DESC
```
