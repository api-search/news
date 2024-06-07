---
name: The New York Times
description: >-
  The official developer area for accessing The New York Times archive, article
  search, books, most popular, reviews, semantic, times tags, times wire, and
  top stories APis.
image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
url: >-
  https://raw.githubusercontent.com/apis-json/artisanal/main/apisnew-york-times.yml
created: 2023/10/6
modified: 2023/10/6
specificationVersion: '0.16'
tags: []
apis:
  - name: Archive API
    description: >-
      The Archive API returns an array of NYT articles for a given month, going
      back to 1851. Its response fields are the same as the Article Search API.
      The Archive API is very useful if you want to build your own database of
      NYT article metadata. You simply pass the API the year and month and it
      returns a JSON object with all articles for t
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/archive-product/1/overview
    baseURL: https://api.nytimes.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/archive-product/1/overview
      - type: OpenAPI
        url: https://api.apis.guru/v2/specs/nytimes.com/archive/1.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/archive/1.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:archive-api
  - name: Article Search API
    description: >-
      Use the Article Search API to look up articles by keyword. You can refine
      your search using filters and facets.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/articlesearch-product/1/overview
    baseURL: https://api.nytimes.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/articlesearch-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/article_search/1.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/article_search/1.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:article-search-api
  - name: Books API
    description: >-
      The Books API provides information about book reviews and The New York
      Times Best Sellers lists.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/books-product/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/books-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/books_api/3.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/books_api/3.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:books-api
  - name: Most Popular
    description: >-
      Provides services for getting the most popular articles on NYTimes.com
      based on emails, shares, or views.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/most-popular-product/1/overview
    baseURL: https://api.nytimes.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/most-popular-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/most_popular_api/2.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/most_popular_api/2.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:most-popular
  - name: Movie Reviews API
    description: >-
      As an alternative, use the Article Search API to get New York Times movie
      reviews using the following filter query.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/movie-reviews-api/1/overview
    baseURL: >-
      https://api.apis.guru/v2/specs/nytimes.com/movie_reviews/2.0.0/openapi.yaml
    tags: []
    properties:
      - type: Documentation
        url: https://example.com/documentation
      - type: OpenAPI
        url: http://example.com/openapi.json
    overlays:
      - type: APIs.io Search
        url: overlays/http://example.com/openapi.json-openapi-search.yml
    aid: the-new-york-times:movie-reviews-api
  - name: Semantic API
    description: >-
      The Semantic API complements the Articles API. With the Semantic API, you
      get access to the long list of people, places, organizations and other
      locations, entities and descriptors that make up the controlled vocabulary
      used as metadata by The New York Times (sometimes referred to as Times
      Tags and used for Times Topics pages.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/semantic-api-product/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/semantic-api-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/semantic_api/2.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/semantic_api/2.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:semantic-api
  - name: TimesTags API
    description: >-
      With the TimesTags API, you can mine the riches of the New York Times tag
      set. The TimesTags service matches your query to the controlled
      vocabularies that fuel NYTimes.com metadata. You supply a string of
      characters, and the service returns a ranked list of suggested terms.
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/timestags-product/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/timestags-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/times_tags/1.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/times_tags/1.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:timestags-api
  - name: Times Newswire API
    description: >-
      With the Times Newswire API, you can get links and metadata for Times'
      articles as soon as they are published on NYTimes.com. The Times Newswire
      API provides an up-to-the-minute stream of published articles. You can
      filter results by source (all, nyt, inyt) and section (arts, business,
      ...).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/timeswire-product/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/timeswire-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/timeswire/3.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/timeswire/3.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:times-newswire-api
  - name: Top Stories
    description: >-
      The Top Stories API returns an array of articles currently on the
      specified section (arts, business, ...).
    image: https://kinlane-productions2.s3.amazonaws.com/apis-json/apis-json-logo.jpg
    humanURL: https://developer.nytimes.com/docs/top-stories-product/1/overview
    baseURL: https://api.example.com
    tags: []
    properties:
      - type: Documentation
        url: https://developer.nytimes.com/docs/top-stories-product/1/overview
      - type: OpenAPI
        url: >-
          https://api.apis.guru/v2/specs/nytimes.com/top_stories/2.0.0/openapi.yaml
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://api.apis.guru/v2/specs/nytimes.com/top_stories/2.0.0/openapi.yaml-openapi-search.yml
    aid: the-new-york-times:top-stories
common:
  - type: Getting Started
    url: https://developer.nytimes.com/get-started
  - type: Signup
    url: https://developer.nytimes.com/accounts/create
  - type: Login
    url: https://developer.nytimes.com/accounts/login
  - type: TermsOfService
    url: https://developer.nytimes.com/terms
maintainers:
  - FN: API Evangelist
    url: https://apievangelist.com
    email: info@apievangelist.com
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: the-new-york-times
---