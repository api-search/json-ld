---
class_count: 12
classes:
- id
- type
- name
- description
- category
- baseURL
- authentication
- plans
- tags
- monthlyRequests
- pricePerMonth
- headerName
context_file: json-ld/apilayer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/json-ld/apilayer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apilayer from APILayer.
layout: jsonld
name: Apilayer Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: apilayer
  uri: https://apilayer.com/vocab/
properties:
- container: ''
  name: documentationURL
  type: reference
property_count: 1
provider_name: APILayer
provider_slug: apilayer
slug: apilayer-context
source_filename: apilayer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"apilayer\": \"https://apilayer.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": \"apilayer:category\",\n    \"baseURL\": \"schema:url\",\n    \"documentationURL\": {\n      \"@id\": \"schema:documentation\",\n      \"@type\": \"@id\"\n    },\n    \"authentication\": \"apilayer:authentication\",\n    \"plans\": \"apilayer:plans\",\n    \"tags\": \"schema:keywords\",\n    \"monthlyRequests\": \"apilayer:monthlyRequests\",\n    \"pricePerMonth\": \"schema:price\",\n    \"headerName\": \"apilayer:headerName\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apilayer/refs/heads/main/json-ld/apilayer-context.jsonld
tags:
- API Catalog
- API Discovery
- API Marketplace
- Developer Tools
- SaaS APIs
- JSON-LD
- Linked Data
- Semantic Web
---
