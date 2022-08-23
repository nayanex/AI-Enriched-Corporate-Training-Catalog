# Filtering, faceting, and sorting from each dataset (as appropriate)

# Query 1

* Index: `courses-index`

* Request URL: ``

* Query String: `search=*&$filter=rating_average gt 4.9`

## Result

```json
```

# Query 2

* Index: `courses-index`

* Request URL: ``

* Query String: `search=*&facet=role`

## Result

```json
```

# Query 3

* Index: `courses-index`

* Request URL: ``

* Query String: `search=*&$filter=rating_average gt 4.9&$orderby=rating_count`

## Result

```json
```

# Query 4

* Index: `library-index`

* Request URL: ``

* Query String: `search=decision-making+HR&$select=content`

## Result

```json
```

# Query 5

* Index: `library-index`

* Request URL: ``

* Query String: `search=decision-making+HR&$select=people`
## Result

```json

```