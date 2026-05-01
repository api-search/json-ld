---
api_specs:
- filename: Looker.4.0.oas.json
  format: json
  label: Looker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/looker-open-source/sdk-codegen/main/spec/Looker.4.0.oas.json
- filename: rest
  format: yaml
  label: Looker (Google Cloud core) API
  slug: ''
  spec_type: OpenAPI
  url: https://looker.googleapis.com/$discovery/rest?version=v1
class_count: 16
classes:
- User
- Look
- Dashboard
- Query
- id
- name
- title
- description
- first_name
- last_name
- email
- url
- is_disabled
- role_ids
- query_id
- public
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-looker/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Looker.
layout: jsonld
name: context Context
namespaces:
- prefix: looker
  uri: https://cloud.google.com/looker/docs/reference/looker-api/latest/
properties: []
property_count: 0
provider_name: Google Looker
provider_slug: google-looker
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"looker\": \"https://cloud.google.com/looker/docs/reference/looker-api/latest/\",\n    \"User\": \"schema:Person\",\n    \"Look\": \"schema:CreativeWork\",\n    \"Dashboard\": \"schema:CreativeWork\",\n    \"Query\": \"schema:Action\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"url\": \"schema:url\",\n    \"is_disabled\": \"looker:isDisabled\",\n    \"role_ids\": \"looker:roleIds\",\n    \"query_id\": \"looker:queryId\",\n    \"public\": \"looker:public\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-looker/refs/heads/main/json-ld/context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
