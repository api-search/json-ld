---
api_specs:
- filename: pantry-openapi.yml
  format: yaml
  label: Pantry API
  slug: pantry
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/pantry/refs/heads/main/openapi/pantry-openapi.yml
class_count: 8
classes:
- name
- description
- contactEmail
- Pantry
- Basket
- ttl
- percentFull
- notifications
context_file: json-ld/pantry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/pantry/refs/heads/main/json-ld/pantry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Pantry from Pantry.
layout: jsonld
name: Pantry Context
namespaces:
- prefix: pantry
  uri: https://getpantry.cloud/#
properties:
- container: set
  name: baskets
  type: ''
property_count: 1
provider_name: Pantry
provider_slug: pantry
slug: pantry-context
source_filename: pantry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"pantry\": \"https://getpantry.cloud/#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"contactEmail\": \"schema:email\",\n    \"Pantry\": \"pantry:Pantry\",\n    \"Basket\": \"pantry:Basket\",\n    \"baskets\": {\n      \"@id\": \"pantry:basket\",\n      \"@container\": \"@set\"\n    },\n    \"ttl\": \"pantry:ttl\",\n    \"percentFull\": \"pantry:percentFull\",\n    \"notifications\": \"pantry:notifications\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/pantry/refs/heads/main/json-ld/pantry-context.jsonld
tags:
- Data Storage
- Developer Tools
- JSON
- JSON-LD
- Linked Data
- Semantic Web
---
