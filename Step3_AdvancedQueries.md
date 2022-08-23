# Filtering, faceting, and sorting from each dataset (as appropriate)

# Query 1

* Index: `courses-index`

* Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/courses-index/docs?api-version=2021-04-30-Preview&search=Eileen%20Diaz&%24select=instructor%2Cinstructor_entities`

* Query String: `search=Eileen%20Diaz&%24select=instructor%2Cinstructor_entities`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('courses-index')/$metadata#docs(*)",
  "value": [
    {
      "@search.score": 0.95620304,
      "instructor": "Eileen Diaz",
      "instructor_entities": [
        {
          "name": "Eileen Diaz",
          "description": "Eileen is our Senior Security Engineer responsible for application and service security. She has been with the company for 9 years and enjoys writing Sci-Fi in her spare time.",
          "matches": [
            {
              "text": "Eileen Diaz",
              "offset": 0,
              "length": 11,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 0.95620304,
      "instructor": "Eileen Diaz",
      "instructor_entities": [
        {
          "name": "Eileen Diaz",
          "description": "Eileen is our Senior Security Engineer responsible for application and service security. She has been with the company for 9 years and enjoys writing Sci-Fi in her spare time.",
          "matches": [
            {
              "text": "Eileen Diaz",
              "offset": 0,
              "length": 11,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 0.95620304,
      "instructor": "Eileen Diaz",
      "instructor_entities": [
        {
          "name": "Eileen Diaz",
          "description": "Eileen is our Senior Security Engineer responsible for application and service security. She has been with the company for 9 years and enjoys writing Sci-Fi in her spare time.",
          "matches": [
            {
              "text": "Eileen Diaz",
              "offset": 0,
              "length": 11,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 0.95620304,
      "instructor": "Eileen Diaz",
      "instructor_entities": [
        {
          "name": "Eileen Diaz",
          "description": "Eileen is our Senior Security Engineer responsible for application and service security. She has been with the company for 9 years and enjoys writing Sci-Fi in her spare time.",
          "matches": [
            {
              "text": "Eileen Diaz",
              "offset": 0,
              "length": 11,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 0.95620304,
      "instructor": "Eileen Diaz",
      "instructor_entities": [
        {
          "name": "Eileen Diaz",
          "description": "Eileen is our Senior Security Engineer responsible for application and service security. She has been with the company for 9 years and enjoys writing Sci-Fi in her spare time.",
          "matches": [
            {
              "text": "Eileen Diaz",
              "offset": 0,
              "length": 11,
              "matchDistance": 0
            }
          ]
        }
      ]
    }
  ]
}
```

# Query 2

* Index: `courses-index`

* Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/courses-index/docs?api-version=2021-04-30-Preview&search=*&%24select=source%2Crating_count%20%2Cinstructor%2Cinstructor_entities&facet=source&%24filter=rating_count%20ge%20500`

* Query String: `search=*&%24select=source%2Crating_count%20%2Cinstructor%2Cinstructor_entities&facet=source&%24filter=rating_count%20ge%20500`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('courses-index')/$metadata#docs(*)",
  "@search.facets": {
    "source": [
      {
        "count": 391,
        "value": "MS Learn"
      },
      {
        "count": 4,
        "value": "Company Moodle"
      }
    ]
  },
  "value": [
    {
      "@search.score": 1,
      "instructor": "Gerald Dominguez",
      "rating_count": 510,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Gerald Dominguez",
          "description": "Gerald is a Junior IT Administrator and has been with the company for 1 year. Gerald played NCAA soccer and is a part-time soccer coach on weekends. ",
          "matches": [
            {
              "text": "Gerald Dominguez",
              "offset": 0,
              "length": 16,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 550,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 540,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 525,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 3301,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 758,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 2779,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1855,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1425,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 604,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 721,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 10997,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 3395,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 800,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1136,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1283,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1425,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 714,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 2061,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 788,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1706,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 717,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 736,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1614,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1868,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 703,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 756,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1868,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1029,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 581,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1744,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 800,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1998,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 544,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 702,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 504,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 7797,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 3395,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 714,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 3395,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1614,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1614,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1706,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1004,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 956,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 604,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1855,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 1512,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 2061,
      "source": "MS Learn",
      "instructor_entities": []
    },
    {
      "@search.score": 1,
      "instructor": "",
      "rating_count": 604,
      "source": "MS Learn",
      "instructor_entities": []
    }
  ],
  "@odata.nextLink": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('courses-index')/docs?api-version=2021-04-30-Preview&search=%2A&$select=source%2Crating_count%20%2Cinstructor%2Cinstructor_entities&facet=source&$filter=rating_count%20ge%20500&$skip=50"
}
```

# Query 3

* Index: `courses-index`

* Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/courses-index/docs?api-version=2021-04-30-Preview&search=M*%20&searchFields=instructor&%24select=source%2Crating_count%20%2Cinstructor%2Cinstructor_entities&facet=source&%24filter=rating_count%20ge%20500`

* Query String: `search=M*%20&searchFields=instructor&%24select=source%2Crating_count%20%2Cinstructor%2Cinstructor_entities&facet=source&%24filter=rating_count%20ge%20500`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('courses-index')/$metadata#docs(*)",
  "@search.facets": {
    "source": [
      {
        "count": 3,
        "value": "Company Moodle"
      }
    ]
  },
  "value": [
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 550,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 540,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    },
    {
      "@search.score": 1,
      "instructor": "Mike Montoya",
      "rating_count": 525,
      "source": "Company Moodle",
      "instructor_entities": [
        {
          "name": "Mike Montoya",
          "description": "Mike  is our HR trainer responsible for helping employees be successful in their careers at our company.  He has been with us for 3 years. Mike is an amateur chef and enjoys outdoor live music events.",
          "matches": [
            {
              "text": "Mike Montoya",
              "offset": 0,
              "length": 12,
              "matchDistance": 0
            }
          ]
        }
      ]
    }
  ]
}
```

# Query 4

* Index: `library-index`

* Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/library-index/docs?api-version=2021-04-30-Preview&search=*&searchFields=publication_name&%24select=doi%2Cpublisher%2Cpublication_name%2Cpublication_date`

* Query String: `searchFields=publication_name&%24select=doi%2Cpublisher%2Cpublication_name%2Cpublication_date`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('library-index')/$metadata#docs(*)",
  "value": [
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "EURASIP Journal on Image and Video Processing",
      "publisher": "Springer",
      "publication_date": "2018-11-27",
      "doi": "10.1186/s13640-018-0373-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Business Research",
      "publisher": "Springer",
      "publication_date": "2020-11-01",
      "doi": "10.1007/s40685-020-00134-w"
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "SpringerPlus",
      "publisher": "Springer",
      "publication_date": "2015-12-01",
      "doi": "10.1186/s40064-015-1515-4"
    },
    {
      "@search.score": 1,
      "publication_name": "Complex Adaptive Systems Modeling",
      "publisher": "Springer",
      "publication_date": "2016-02-03",
      "doi": "10.1186/s40294-016-0016-9"
    },
    {
      "@search.score": 1,
      "publication_name": "EURASIP Journal on Image and Video Processing",
      "publisher": "Springer",
      "publication_date": "2021-01-14",
      "doi": "10.1186/s13640-020-00545-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Human-centric Computing and Information Sciences",
      "publisher": "Springer",
      "publication_date": "2018-05-09",
      "doi": "10.1186/s13673-018-0135-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Human-centric Computing and Information Sciences",
      "publisher": "Springer",
      "publication_date": "2019-05-01",
      "doi": "10.1186/s13673-019-0177-6"
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Trust Management",
      "publisher": "Springer",
      "publication_date": "2015-09-07",
      "doi": "10.1186/s40493-015-0019-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2018-09-22",
      "doi": "10.1186/s40537-018-0141-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-02-28",
      "doi": "10.1186/s40537-019-0184-5"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-06-06",
      "doi": "10.1186/s40537-019-0210-7"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-10-31",
      "doi": "10.1186/s40537-019-0258-4"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2020-02-28",
      "doi": "10.1186/s40537-020-00292-y"
    },
    {
      "@search.score": 1,
      "publication_name": "Brain Informatics",
      "publisher": "Springer",
      "publication_date": "2015-09-01",
      "doi": "10.1007/s40708-015-0017-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Brain Informatics",
      "publisher": "Springer",
      "publication_date": "2020-09-21",
      "doi": "10.1186/s40708-020-00109-x"
    },
    {
      "@search.score": 1,
      "publication_name": "Applied Network Science",
      "publisher": "Springer",
      "publication_date": "2020-11-16",
      "doi": "10.1007/s41109-020-00330-x"
    }
  ]
}
```

# Query 5

* Index: `library-index`

* Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/library-index/docs?api-version=2021-04-30-Preview&search=*&%24select=doi%2Cpublisher%2Cpublication_name%2Cpublication_date`

* Query String: `search=*&%24select=doi%2Cpublisher%2Cpublication_name%2Cpublication_date`
## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('library-index')/$metadata#docs(*)",
  "value": [
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "EURASIP Journal on Image and Video Processing",
      "publisher": "Springer",
      "publication_date": "2018-11-27",
      "doi": "10.1186/s13640-018-0373-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Business Research",
      "publisher": "Springer",
      "publication_date": "2020-11-01",
      "doi": "10.1007/s40685-020-00134-w"
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "SpringerPlus",
      "publisher": "Springer",
      "publication_date": "2015-12-01",
      "doi": "10.1186/s40064-015-1515-4"
    },
    {
      "@search.score": 1,
      "publication_name": "Complex Adaptive Systems Modeling",
      "publisher": "Springer",
      "publication_date": "2016-02-03",
      "doi": "10.1186/s40294-016-0016-9"
    },
    {
      "@search.score": 1,
      "publication_name": "EURASIP Journal on Image and Video Processing",
      "publisher": "Springer",
      "publication_date": "2021-01-14",
      "doi": "10.1186/s13640-020-00545-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Human-centric Computing and Information Sciences",
      "publisher": "Springer",
      "publication_date": "2018-05-09",
      "doi": "10.1186/s13673-018-0135-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Human-centric Computing and Information Sciences",
      "publisher": "Springer",
      "publication_date": "2019-05-01",
      "doi": "10.1186/s13673-019-0177-6"
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "",
      "publisher": "",
      "publication_date": "",
      "doi": ""
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Trust Management",
      "publisher": "Springer",
      "publication_date": "2015-09-07",
      "doi": "10.1186/s40493-015-0019-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2018-09-22",
      "doi": "10.1186/s40537-018-0141-8"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-02-28",
      "doi": "10.1186/s40537-019-0184-5"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-06-06",
      "doi": "10.1186/s40537-019-0210-7"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2019-10-31",
      "doi": "10.1186/s40537-019-0258-4"
    },
    {
      "@search.score": 1,
      "publication_name": "Journal of Big Data",
      "publisher": "Springer",
      "publication_date": "2020-02-28",
      "doi": "10.1186/s40537-020-00292-y"
    },
    {
      "@search.score": 1,
      "publication_name": "Brain Informatics",
      "publisher": "Springer",
      "publication_date": "2015-09-01",
      "doi": "10.1007/s40708-015-0017-z"
    },
    {
      "@search.score": 1,
      "publication_name": "Brain Informatics",
      "publisher": "Springer",
      "publication_date": "2020-09-21",
      "doi": "10.1186/s40708-020-00109-x"
    },
    {
      "@search.score": 1,
      "publication_name": "Applied Network Science",
      "publisher": "Springer",
      "publication_date": "2020-11-16",
      "doi": "10.1007/s41109-020-00330-x"
    }
  ]
}
```