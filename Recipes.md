```dataview
table without id file.link as Recipe, type as Type, author as Author, ingredients as Ingredients, rating as Rating
from #recipes
where !contains(file.name,"Template")
sort created desc
```