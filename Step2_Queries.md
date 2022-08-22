# Query 1

## Query

Index: `skillset-courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-courses-index/docs?api-version=2021-04-30-Preview&search=%22gerald%20dominguez%22`
Query String: `search="gerald dominguez"`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('skillset-courses-index')/$metadata#docs(*)",
  "value": [
    {
      "@search.score": 0.32096615,
      "PartitionKey": "company-moodle",
      "RowKey": "17b1eedc-0e96-4e5b-8199-83a484388efe",
      "Timestamp": "2022-08-21T19:52:15.617Z",
      "description": "Learn our internal best practices for using the O365 suite including email signatures, file storage and other issues",
      "duration": 2,
      "instructor": "Gerald Dominguez",
      "level": "beginner",
      "product": "O365",
      "rating_average": 4.6,
      "rating_count": 510,
      "role": "all",
      "source": "Company Moodle",
      "title": "O365",
      "url": "https://www.example.com/course10",
      "keyphrases": [
        "internal best practices",
        "O365 suite",
        "email signatures",
        "file storage",
        "other issues"
      ]
    },
    {
      "@search.score": 0.32096615,
      "PartitionKey": "company-moodle",
      "RowKey": "c014cf36-2a83-4ded-bfe5-d62f405ba970",
      "Timestamp": "2022-08-21T19:52:15.617Z",
      "description": "This course will teach you best practices for communicating with your team while working remotely",
      "duration": 1,
      "instructor": "Gerald Dominguez",
      "level": "beginner",
      "product": "NA",
      "rating_average": 4.7,
      "rating_count": 325,
      "role": "all",
      "source": "Company Moodle",
      "title": "Remote work",
      "url": "https://www.example.com/course11",
      "keyphrases": [
        "best practices",
        "course",
        "team"
      ]
    }
  ]
}
```

# Query 2

## Query

Index: `skillset-courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-library-index/docs?api-version=2021-04-30-Preview&search=*`
Query String: `search=*`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('skillset-library-index')/$metadata#docs(*)",
  "value": []
}
```