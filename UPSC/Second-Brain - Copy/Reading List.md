---
cssClasses:  cards
---

## Reading 
```dataview
Table ("![|100](" + cover_url + ")") as Cover, author as Author, total_page as "Pages", category as Category, Bar as Progress
From #book
where contains(status,"Reading")
```
---
---

## Completed
```dataview
Table ("![|100](" + cover_url + ")") as Cover, author as Author, total_page as "Pages", category as "Category", my_rate as "Rating"
From #book
where contains(status,"Completed")
```
---
---

## To Read
```dataview
Table ("![|100](" + cover_url + ")") as Cover, author as Author, total_page as "Pages", category as "Category"
From #book
where contains(status,"To Read")
```
---
---
## Unfinished
```dataview
Table ("![|100](" + cover_url + ")") as Cover, author as Author, total_page as "Pages", category as "Category"
From #book
where contains(status,"Unfinished")
```
---
---
- The network state
- The art of imposssible