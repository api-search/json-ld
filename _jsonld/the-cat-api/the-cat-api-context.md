---
api_specs:
- filename: the-cat-api-openapi.yml
  format: yaml
  label: The Cat API
  slug: the-cat-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-cat-api/refs/heads/main/openapi/the-cat-api-openapi.yml
class_count: 3
classes:
- id
- name
- description
context_file: json-ld/the-cat-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-cat-api/refs/heads/main/json-ld/the-cat-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Cat Api from The Cat API.
layout: jsonld
name: The Cat Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: catapi
  uri: https://api.thecatapi.com/v1/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Image
  type: ''
- container: ''
  name: url
  type: reference
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: Breed
  type: ''
- container: ''
  name: origin
  type: ''
- container: ''
  name: temperament
  type: ''
- container: ''
  name: life_span
  type: ''
- container: ''
  name: wikipedia_url
  type: reference
- container: ''
  name: intelligence
  type: integer
- container: ''
  name: affection_level
  type: integer
- container: ''
  name: energy_level
  type: integer
- container: ''
  name: Favourite
  type: ''
- container: ''
  name: image_id
  type: ''
- container: ''
  name: sub_id
  type: ''
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: Vote
  type: ''
- container: ''
  name: value
  type: integer
- container: ''
  name: Category
  type: ''
- container: set
  name: breeds
  type: ''
- container: set
  name: categories
  type: ''
property_count: 21
provider_name: The Cat API
provider_slug: the-cat-api
slug: the-cat-api-context
source_filename: the-cat-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"catapi\": \"https://api.thecatapi.com/v1/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Image\": {\n      \"@id\": \"schema:ImageObject\"\n    },\n    \"id\": \"@id\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"width\": {\n      \"@id\": \"schema:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"schema:height\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Breed\": {\n      \"@id\": \"catapi:Breed\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"origin\": {\n      \"@id\": \"schema:countryOfOrigin\"\n    },\n    \"temperament\": {\n      \"@id\": \"catapi:temperament\"\n    },\n    \"life_span\": {\n      \"@id\": \"catapi:lifeSpan\"\n    },\n    \"wikipedia_url\": {\n      \"@id\"\
  : \"schema:sameAs\",\n      \"@type\": \"@id\"\n    },\n    \"intelligence\": {\n      \"@id\": \"catapi:intelligence\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"affection_level\": {\n      \"@id\": \"catapi:affectionLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"energy_level\": {\n      \"@id\": \"catapi:energyLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Favourite\": {\n      \"@id\": \"catapi:Favourite\"\n    },\n    \"image_id\": {\n      \"@id\": \"catapi:imageId\"\n    },\n    \"sub_id\": {\n      \"@id\": \"catapi:subId\"\n    },\n    \"created_at\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Vote\": {\n      \"@id\": \"catapi:Vote\"\n    },\n    \"value\": {\n      \"@id\": \"schema:ratingValue\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Category\": {\n      \"@id\": \"schema:DefinedTerm\"\n    },\n    \"breeds\": {\n      \"@id\": \"catapi:breeds\",\n      \"@container\": \"@set\"\n    },\n\
  \    \"categories\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-cat-api/refs/heads/main/json-ld/the-cat-api-context.jsonld
tags:
- Animals
- Cats
- Images
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
