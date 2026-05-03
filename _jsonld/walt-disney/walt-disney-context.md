---
api_specs:
- filename: walt-disney-disney-api-openapi.yml
  format: yaml
  label: Disney Characters API
  slug: disney-characters-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/openapi/walt-disney-disney-api-openapi.yml
class_count: 6
classes:
- Character
- Film
- TVShow
- VideoGame
- ParkAttraction
- _id
context_file: json-ld/walt-disney-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/json-ld/walt-disney-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Walt Disney from Walt Disney.
layout: jsonld
name: Walt Disney Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: disney
  uri: https://disneyapi.dev/#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: imageUrl
  type: reference
- container: set
  name: films
  type: ''
- container: set
  name: tvShows
  type: ''
- container: set
  name: videoGames
  type: ''
- container: set
  name: parkAttractions
  type: ''
- container: set
  name: allies
  type: ''
- container: set
  name: enemies
  type: ''
- container: ''
  name: alignment
  type: string
- container: ''
  name: sourceUrl
  type: reference
property_count: 11
provider_name: Walt Disney
provider_slug: walt-disney
slug: walt-disney-context
source_filename: walt-disney-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"disney\": \"https://disneyapi.dev/#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Character\": \"schema:Person\",\n    \"Film\": \"schema:Movie\",\n    \"TVShow\": \"schema:TVSeries\",\n    \"VideoGame\": \"schema:VideoGame\",\n    \"ParkAttraction\": \"schema:Attraction\",\n\n    \"_id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"imageUrl\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"films\": {\n      \"@id\": \"schema:subjectOf\",\n      \"@container\": \"@set\"\n    },\n    \"tvShows\": {\n      \"@id\": \"disney:tvShows\",\n      \"@container\": \"@set\"\n    },\n    \"videoGames\": {\n      \"@id\": \"disney:videoGames\",\n      \"@container\": \"@set\"\n    },\n    \"parkAttractions\"\
  : {\n      \"@id\": \"disney:parkAttractions\",\n      \"@container\": \"@set\"\n    },\n    \"allies\": {\n      \"@id\": \"schema:knows\",\n      \"@container\": \"@set\"\n    },\n    \"enemies\": {\n      \"@id\": \"disney:enemies\",\n      \"@container\": \"@set\"\n    },\n    \"alignment\": {\n      \"@id\": \"disney:alignment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceUrl\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/walt-disney/refs/heads/main/json-ld/walt-disney-context.jsonld
tags:
- Entertainment
- Media
- Streaming
- Parks
- Content
- JSON-LD
- Linked Data
- Semantic Web
---
