---
cssClasses: cards, cards-cover, cards-2-3, table-max
---

```dataview
table without id 
	("![](" + poster + ")") as Poster,
	file.link as Title,
	year as Year, 
	"by " + director as Director,
	"⭐ " + scoreImdb as "⭐ IMDB",
	rating
from #movies AND !"Templates"
where poster != null
```
