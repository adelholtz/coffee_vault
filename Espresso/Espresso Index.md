
```dataview
table origin as "Origin", taste as "Taste Profile", rating as "Rating", price_250 as "250g"
from "Espresso"
where category="espresso" or category="Espresso"
sort rating DESC
```
