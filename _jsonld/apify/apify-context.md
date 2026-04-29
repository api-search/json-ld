---
api_specs:
- filename: apify-api.yaml
  format: yaml
  label: Apify API
  slug: apify-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/openapi/apify-api.yaml
class_count: 7
classes:
- Actor
- Run
- Dataset
- KeyValueStore
- name
- description
- title
context_file: json-ld/apify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/json-ld/apify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apify from Apify.
layout: jsonld
name: Apify Context
namespaces:
- prefix: apify
  uri: https://apify.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: finishedAt
  type: dateTime
- container: ''
  name: itemCount
  type: integer
property_count: 6
provider_name: Apify
provider_slug: apify
slug: apify-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"apify\": \"https://apify.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Actor\": \"apify:Actor\",\n    \"Run\": \"apify:Run\",\n    \"Dataset\": \"apify:Dataset\",\n    \"KeyValueStore\": \"apify:KeyValueStore\",\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"username\": {\n      \"@id\": \"apify:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": \"schema:name\",\n    \"status\": {\n      \"@id\": \"apify:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"finishedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\
  \    \"itemCount\": {\n      \"@id\": \"apify:itemCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apify/refs/heads/main/json-ld/apify-context.jsonld
tags:
- Actors
- Browser Automation
- Crawling
- Data Aggregation
- Data Extraction
- Web Automation
- Web Scraping
- JSON-LD
- Linked Data
- Semantic Web
---
