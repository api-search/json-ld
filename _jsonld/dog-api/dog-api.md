---
api_specs:
- filename: dog-api.yml
  format: yaml
  label: Dog API
  slug: dog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dog-api/refs/heads/main/openapi/dog-api.yml
class_count: 5
classes:
- name
- description
- url
- provider
- category
context_file: json-ld/dog-api.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dog-api/refs/heads/main/json-ld/dog-api.jsonld
description: JSON-LD context defining the semantic vocabulary for Dog Api from Dog API.
layout: jsonld
name: Dog Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Dog API
provider_slug: dog-api
slug: dog-api
source_filename: dog-api.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"schema\": \"https://schema.org/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n    \"category\": \"schema:category\"\n  },\n  \"@type\": \"schema:WebAPI\",\n  \"name\": \"Dog API\",\n  \"description\": \"Open-source REST API serving over 20,000 dog images across 120+ breeds.\",\n  \"url\": \"https://dog.ceo/dog-api/\",\n  \"category\": [\"Animals\", \"Open Data\", \"Images\"],\n  \"provider\": {\n    \"@type\": \"schema:Organization\",\n    \"name\": \"dog.ceo\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dog-api/refs/heads/main/json-ld/dog-api.jsonld
tags:
- Dogs
- Images
- Open Data
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
