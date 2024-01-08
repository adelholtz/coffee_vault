
```dataview
table origin as "Origin", taste as "Taste Profile", rating as "Rating", brew_method as "Brew Sytle", price_250 as "250g"
from "Coffee"
where category="coffee" or category="Coffee" or category="Filterkaffee"
sort rating DESC
```
