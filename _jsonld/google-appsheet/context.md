---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google AppSheet API
  slug: google-appsheet
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-appsheet/refs/heads/main/openapi/openapi.yml
class_count: 11
classes:
- SoftwareApplication
- name
- description
- Action
- actionStatus
- target
- result
- object
- DataFeed
- dataFeedElement
- Dataset
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-appsheet/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google AppSheet.
layout: jsonld
name: context Context
namespaces:
- prefix: appsheet
  uri: https://api.appsheet.com/api/v2/
properties: []
property_count: 0
provider_name: Google AppSheet
provider_slug: google-appsheet
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"appsheet\": \"https://api.appsheet.com/api/v2/\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"Action\": \"schema:Action\",\n    \"actionStatus\": \"schema:actionStatus\",\n    \"target\": \"schema:target\",\n    \"result\": \"schema:result\",\n    \"object\": \"schema:object\",\n    \"DataFeed\": \"schema:DataFeed\",\n    \"dataFeedElement\": \"schema:dataFeedElement\",\n    \"Dataset\": \"schema:Dataset\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-appsheet/refs/heads/main/json-ld/context.jsonld
tags:
- Applications
- Data
- Google
- Low-Code
- No-Code
- Tables
- JSON-LD
- Linked Data
- Semantic Web
---
