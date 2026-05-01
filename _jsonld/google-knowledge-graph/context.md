---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Knowledge Graph Search API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-knowledge-graph/refs/heads/main/openapi/openapi.yml
class_count: 14
classes:
- Thing
- Person
- Place
- Organization
- name
- description
- url
- image
- sameAs
- detailedDescription
- identifier
- ItemList
- itemListElement
- resultScore
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-knowledge-graph/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Knowledge Graph Search.
layout: jsonld
name: context Context
namespaces:
- prefix: kg
  uri: https://kgsearch.googleapis.com/v1/
properties: []
property_count: 0
provider_name: Google Knowledge Graph Search
provider_slug: google-knowledge-graph
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"kg\": \"https://kgsearch.googleapis.com/v1/\",\n    \"Thing\": \"schema:Thing\",\n    \"Person\": \"schema:Person\",\n    \"Place\": \"schema:Place\",\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"image\": \"schema:image\",\n    \"sameAs\": \"schema:sameAs\",\n    \"detailedDescription\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"ItemList\": \"schema:ItemList\",\n    \"itemListElement\": \"schema:itemListElement\",\n    \"resultScore\": \"kg:resultScore\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-knowledge-graph/refs/heads/main/json-ld/context.jsonld
tags:
- Entities
- Google
- Knowledge Graph
- Linked Data
- Schema.org
- Semantic Search
- JSON-LD
- Linked Data
- Semantic Web
---
