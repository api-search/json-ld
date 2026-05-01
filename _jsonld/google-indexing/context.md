---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Indexing API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-indexing/refs/heads/main/openapi/openapi.yml
class_count: 13
classes:
- WebPage
- url
- dateModified
- datePublished
- Action
- UpdateAction
- DeleteAction
- actionStatus
- target
- startTime
- WebSite
- name
- description
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-indexing/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Indexing.
layout: jsonld
name: context Context
namespaces:
- prefix: indexing
  uri: https://indexing.googleapis.com/v3/
properties: []
property_count: 0
provider_name: Google Indexing
provider_slug: google-indexing
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"indexing\": \"https://indexing.googleapis.com/v3/\",\n    \"WebPage\": \"schema:WebPage\",\n    \"url\": \"schema:url\",\n    \"dateModified\": \"schema:dateModified\",\n    \"datePublished\": \"schema:datePublished\",\n    \"Action\": \"schema:Action\",\n    \"UpdateAction\": \"schema:UpdateAction\",\n    \"DeleteAction\": \"schema:DeleteAction\",\n    \"actionStatus\": \"schema:actionStatus\",\n    \"target\": \"schema:target\",\n    \"startTime\": \"schema:startTime\",\n    \"WebSite\": \"schema:WebSite\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-indexing/refs/heads/main/json-ld/context.jsonld
tags:
- Crawling
- Google
- Indexing
- Search
- SEO
- URLs
- JSON-LD
- Linked Data
- Semantic Web
---
