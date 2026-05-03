---
api_specs:
- filename: shutterstock-openapi.yml
  format: yaml
  label: Shutterstock API
  slug: shutterstock-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/openapi/shutterstock-openapi.yml
class_count: 14
classes:
- Image
- Video
- Audio
- Contributor
- Collection
- id
- description
- name
- url
- keywords
- categories
- duration
- width
- height
context_file: json-ld/shutterstock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/json-ld/shutterstock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shutterstock from Shutterstock.
layout: jsonld
name: Shutterstock Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: shutterstock
  uri: https://api.shutterstock.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: cc
  uri: https://creativecommons.org/ns#
properties:
- container: ''
  name: image_type
  type: '@vocab'
- container: ''
  name: media_type
  type: '@vocab'
- container: ''
  name: is_editorial
  type: boolean
- container: ''
  name: is_adult
  type: boolean
- container: ''
  name: is_illustration
  type: boolean
- container: ''
  name: added_date
  type: date
- container: ''
  name: contributor
  type: ''
- container: ''
  name: assets
  type: ''
- container: list
  name: releases
  type: ''
- container: ''
  name: has_model_release
  type: boolean
- container: ''
  name: has_property_release
  type: boolean
- container: ''
  name: license
  type: reference
- container: ''
  name: aspect
  type: decimal
- container: ''
  name: subscription_id
  type: string
- container: ''
  name: format
  type: ''
- container: ''
  name: file_size
  type: ''
- container: ''
  name: total_count
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: per_page
  type: integer
- container: ''
  name: search_id
  type: string
property_count: 20
provider_name: Shutterstock
provider_slug: shutterstock
slug: shutterstock-context
source_filename: shutterstock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"shutterstock\": \"https://api.shutterstock.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"cc\": \"https://creativecommons.org/ns#\",\n\n    \"Image\": \"schema:ImageObject\",\n    \"Video\": \"schema:VideoObject\",\n    \"Audio\": \"schema:AudioObject\",\n    \"Contributor\": \"schema:Person\",\n    \"Collection\": \"schema:Collection\",\n\n    \"id\": \"@id\",\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"keywords\": \"schema:keywords\",\n    \"categories\": \"schema:about\",\n    \"duration\": \"schema:duration\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n\n    \"image_type\": {\n      \"@id\": \"shutterstock:imageType\",\n      \"@type\": \"@vocab\"\n    },\n    \"media_type\": {\n      \"@id\": \"shutterstock:mediaType\",\n      \"@type\": \"@vocab\"\n  \
  \  },\n    \"is_editorial\": {\n      \"@id\": \"shutterstock:isEditorial\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_adult\": {\n      \"@id\": \"shutterstock:isAdult\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_illustration\": {\n      \"@id\": \"shutterstock:isIllustration\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"added_date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"contributor\": {\n      \"@id\": \"schema:creator\"\n    },\n    \"assets\": {\n      \"@id\": \"shutterstock:assets\"\n    },\n    \"releases\": {\n      \"@id\": \"shutterstock:releases\",\n      \"@container\": \"@list\"\n    },\n    \"has_model_release\": {\n      \"@id\": \"shutterstock:hasModelRelease\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"has_property_release\": {\n      \"@id\": \"shutterstock:hasPropertyRelease\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"license\": {\n      \"@id\": \"cc:license\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"aspect\": {\n      \"@id\": \"shutterstock:aspectRatio\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"subscription_id\": {\n      \"@id\": \"shutterstock:subscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"schema:encodingFormat\"\n    },\n    \"file_size\": {\n      \"@id\": \"schema:contentSize\"\n    },\n    \"total_count\": {\n      \"@id\": \"shutterstock:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"shutterstock:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"per_page\": {\n      \"@id\": \"shutterstock:perPage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"search_id\": {\n      \"@id\": \"shutterstock:searchId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shutterstock/refs/heads/main/json-ld/shutterstock-context.jsonld
tags:
- Images
- Media
- Photos
- Stock Images
- Videos
- Audio
- Licensing
- Creative Content
- JSON-LD
- Linked Data
- Semantic Web
---
