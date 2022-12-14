Fork this repository to complete the Building an AI Enriched Corporate Training Catalog Project

![Step1_Architecture](Step1_Architecture.png)


Install **Azure Storage Explorer**


* Simple search on various search terms
* Simple search using a phrase
* Search using a Boolean operation on terms and / or phrases
* Search using some of the Lucene capabilities such as fuzzy and proximity search or term boosting
* Use a filter to limit results using different fields such as beds, baths, etc.
* Add a facet to see how the facet results are returned

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

# Filtering, faceting, and sorting from each dataset (as appropriate)

#  use the built-in Custom Entity Lookup skill to enrich the dataset.

# Storage Account Primary Endpoint

`https://training6atalog5torage.z6.web.core.windows.net/`