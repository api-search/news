---
name: NPR
description: >-
  National Public Radio (NPR) APIs. The APIs support station finding,
  authentication, user management and listening.
image: https://dev.npr.org/NPRLogo_BlackOutline.png
url: https://raw.githubusercontent.com/apis-json/artisanal/main/apis/npr.yml
created: 2023/11/1
modified: 2023/11/1
specificationVersion: '0.16'
tags: []
apis:
  - name: Listening
    description: Audio recommendations tailored to a user's preferences.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=listening
    baseURL: https://listening.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=listening
      - type: OpenAPI
        url: https://listening.api.npr.org/v2/swagger.json
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://listening.api.npr.org/v2/swagger.json-openapi-search.yml
    aid: npr:listening
  - name: Station
    description: NPR Station information.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=station
    baseURL: https://station.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=station
      - type: Swagger
        url: https://station.api.npr.org/v3/swagger.json
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays: []
    aid: npr:station
  - name: Identity
    description: User management API.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=identity
    baseURL: https://identity.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=identity
      - type: Swagger
        url: https://identity.api.npr.org/v2/swagger.json
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays: []
    aid: npr:identity
  - name: Authorization
    description: API Authorization.
    image: https://dev.npr.org/NPRLogo_BlackOutline.png
    humanURL: https://dev.npr.org/?urls.primaryName=authorization
    baseURL: https://authorization.api.npr.org
    tags: []
    properties:
      - type: Documentation
        url: https://dev.npr.org/?urls.primaryName=authorization
      - type: OpenAPI
        url: https://authorization.api.npr.org/v2/swagger.json
    contact:
      - FN: ''
        url: ''
        email: ''
    overlays:
      - type: APIs.io Search
        url: >-
          overlays/https://authorization.api.npr.org/v2/swagger.json-openapi-search.yml
    aid: npr:authorization
maintainers:
  - FN: Steven Willmott
    url: http://timewarp.com
    email: steve@timewarp.io
overlays:
  - type: APIs.io Search
    url: overlays/apis-io-search.yml
  - type: API Evangelist Ratings
    url: overlays/apis-io-search.yml
aid: npr
---