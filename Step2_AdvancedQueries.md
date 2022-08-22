# Filtering, faceting, and sorting from each dataset (as appropriate)
# Query 1

Index: `courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/courses-index/docs?api-version=2021-04-30-Preview&search=*&%24filter=rating_average%20gt%204.9`
Query String: `search=*&$filter=rating_average gt 4.9`

## Result

```json
{
  "@odata.context": "https://ai-enriched-training-catalog-search.search.windows.net/indexes('courses-index')/$metadata#docs(*)",
  "value": [
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "04092659-deab-43ad-ad0e-ef2992f0af29",
      "Timestamp": "2022-08-21T19:52:14.213Z",
      "Key": "ms-learn04092659-deab-43ad-ad0e-ef2992f0af29",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "administrator",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "11b92b3c-714a-481e-adda-f46285e2a090",
      "Timestamp": "2022-08-21T19:52:14.212Z",
      "Key": "ms-learn11b92b3c-714a-481e-adda-f46285e2a090",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "solution-architect",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "13f442b0-f1d1-4402-8c3e-13f0c8b6ce8d",
      "Timestamp": "2022-08-21T19:52:13.406Z",
      "Key": "ms-learn13f442b0-f1d1-4402-8c3e-13f0c8b6ce8d",
      "description": "Create an Azure Cognitive Search solution",
      "duration": 63,
      "instructor": "",
      "level": "intermediate",
      "product": "azure-cognitive-search",
      "rating_average": 4.91,
      "rating_count": 45,
      "role": "ai-engineer",
      "source": "MS Learn",
      "title": "Create an Azure Cognitive Search solution",
      "url": "https://docs.microsoft.com/en-us/learn/modules/create-azure-cognitive-search-solution/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Azure Cognitive Search solution"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "154ef75f-9956-45c9-8152-8e03cc1a2bba",
      "Timestamp": "2022-08-21T19:52:14.212Z",
      "Key": "ms-learn154ef75f-9956-45c9-8152-8e03cc1a2bba",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "technology-manager",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "1f8f9833-ee15-4ea5-9597-aa05fd895653",
      "Timestamp": "2022-08-21T19:52:14.214Z",
      "Key": "ms-learn1f8f9833-ee15-4ea5-9597-aa05fd895653",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "student",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "33538376-541c-4366-8290-a20873ee074d",
      "Timestamp": "2022-08-21T19:52:14.213Z",
      "Key": "ms-learn33538376-541c-4366-8290-a20873ee074d",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "administrator",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "4157d54e-86f5-4b5e-a94c-cb0ee392ee58",
      "Timestamp": "2022-08-21T19:52:14.211Z",
      "Key": "ms-learn4157d54e-86f5-4b5e-a94c-cb0ee392ee58",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "developer",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "6524b8f2-db34-4e39-8400-636d1d5cd9ff",
      "Timestamp": "2022-08-21T19:52:14.211Z",
      "Key": "ms-learn6524b8f2-db34-4e39-8400-636d1d5cd9ff",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "developer",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "683814dd-934d-4e72-a5fd-81a3c8037999",
      "Timestamp": "2022-08-21T19:52:13.406Z",
      "Key": "ms-learn683814dd-934d-4e72-a5fd-81a3c8037999",
      "description": "Create an Azure Cognitive Search solution",
      "duration": 63,
      "instructor": "",
      "level": "intermediate",
      "product": "azure-cognitive-search",
      "rating_average": 4.91,
      "rating_count": 45,
      "role": "developer",
      "source": "MS Learn",
      "title": "Create an Azure Cognitive Search solution",
      "url": "https://docs.microsoft.com/en-us/learn/modules/create-azure-cognitive-search-solution/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Azure Cognitive Search solution"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "821d3262-1d7a-4a63-9d28-d06f71b5ead9",
      "Timestamp": "2022-08-21T19:52:14.212Z",
      "Key": "ms-learn821d3262-1d7a-4a63-9d28-d06f71b5ead9",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "technology-manager",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "8e9bb2f6-e1af-43be-a4c5-7cd0e82ce275",
      "Timestamp": "2022-08-21T19:52:14.212Z",
      "Key": "ms-learn8e9bb2f6-e1af-43be-a4c5-7cd0e82ce275",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "devops-engineer",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "a7e5e71d-493b-47bd-8f71-983ec50ba877",
      "Timestamp": "2022-08-21T19:52:14.211Z",
      "Key": "ms-learna7e5e71d-493b-47bd-8f71-983ec50ba877",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "devops-engineer",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "cc436468-571e-41e5-aaf4-7563b7fd0a95",
      "Timestamp": "2022-08-21T19:52:14.213Z",
      "Key": "ms-learncc436468-571e-41e5-aaf4-7563b7fd0a95",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "github",
      "rating_average": 5,
      "rating_count": 8,
      "role": "student",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "e00a9b7f-cd37-41b1-87d3-d87018dcf606",
      "Timestamp": "2022-08-21T19:52:13.406Z",
      "Key": "ms-learne00a9b7f-cd37-41b1-87d3-d87018dcf606",
      "description": "Create an Azure Cognitive Search solution",
      "duration": 63,
      "instructor": "",
      "level": "intermediate",
      "product": "azure-cognitive-search",
      "rating_average": 4.91,
      "rating_count": 45,
      "role": "solution-architect",
      "source": "MS Learn",
      "title": "Create an Azure Cognitive Search solution",
      "url": "https://docs.microsoft.com/en-us/learn/modules/create-azure-cognitive-search-solution/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Azure Cognitive Search solution"
      ]
    },
    {
      "@search.score": 1,
      "PartitionKey": "ms-learn",
      "RowKey": "f6430b41-7899-4635-ba67-bbaf2076aed4",
      "Timestamp": "2022-08-21T19:52:14.212Z",
      "Key": "ms-learnf6430b41-7899-4635-ba67-bbaf2076aed4",
      "description": "In this module, we'll authenticate to GitHub, create a local Git repository, and push the repository to GitHub by using the Git tooling experience in Visual Studio 2019. We'll add and modify files, stage and commit changes, and then finally push to your remote.",
      "duration": 38,
      "instructor": "",
      "level": "beginner",
      "product": "vs",
      "rating_average": 5,
      "rating_count": 8,
      "role": "solution-architect",
      "source": "MS Learn",
      "title": "Get started with Git and GitHub in Visual Studio",
      "url": "https://docs.microsoft.com/en-us/learn/modules/visual-studio-github-push/?WT.mc_id=api_CatalogApi",
      "keyphrases": [
        "Git tooling experience",
        "local Git repository",
        "Visual Studio",
        "module",
        "GitHub",
        "files",
        "changes",
        "remote"
      ]
    }
  ]
}
```

# Query 2

Index: `courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-courses-index/docs?api-version=2021-04-30-Preview&search=%22gerald%20dominguez%22`
Query String: `search="gerald dominguez"`
## Result

```json
```

# Query 3

Index: `courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-courses-index/docs?api-version=2021-04-30-Preview&search=%22gerald%20dominguez%22`
Query String: `search="gerald dominguez"`

## Result

```json
```

# Query 4

Index: `courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-courses-index/docs?api-version=2021-04-30-Preview&search=%22gerald%20dominguez%22`
Query String: `search="gerald dominguez"`

## Result

```json
```

# Query 5

Index: `courses-index`
Request URL: `https://ai-enriched-training-catalog-search.search.windows.net/indexes/skillset-courses-index/docs?api-version=2021-04-30-Preview&search=%22gerald%20dominguez%22`
Query String: `search="gerald dominguez"`
## Result

```json
```