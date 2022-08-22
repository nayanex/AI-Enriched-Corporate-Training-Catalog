Fork this repository to complete the Building an AI Enriched Corporate Training Catalog Project

![Step1_Architecture](Step1_Architecture.png)


ai-enriched-training-catalog-search
training6atalog5torage

Install **Azure Storage Explorer**

Cognitive Services
 - Cognitive Services



skillset-courses
skillset-library

Simple search on various search terms
Simple search using a phrase
Search using a Boolean operation on terms and / or phrases
Search using some of the Lucene capabilities such as fuzzy and proximity search or term boosting
Use a filter to limit results using different fields such as beds, baths, etc.
Add a facet to see how the facet results are returned

```
# Simple search with a term
search=flatlet

Simple search with a phrase
search="formal dining room"

# Boolean search (note the searchMode to make the negative Boolean work)
search="formal dining room" -flatlet&searchMode=all

# Fuzzy search
search="cul-de-sac"~&queryType=full

#Filter
search=*&$filter=baths eq 2 and beds eq 2

#Facet
search=*&facet=city

search=parks+water&$select=description
search=lake*&$select=description,city
search=*&$select=description, beds, baths&$filter=(beds gt 2 and baths gt 2)

search=*&$select=price,mortgage&$filter=mortgage eq "Conforming"
?search=*&$filter=category eq 'Starter Home'
```

https://training6atalog5torage.blob.core.windows.net/papers?sp=racwdli&st=2022-08-22T21:03:03Z&se=2022-08-26T05:03:03Z&spr=https&sv=2021-06-08&sr=c&sig=CWpHy37bihwKymdL%2FgnnMdq8u9zxU6BMjhBD3rgJ5Gk%3D