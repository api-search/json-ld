---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Custom Search JSON API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-custom-search/refs/heads/main/openapi/openapi.yml
class_count: 14
classes:
- SearchResultsPage
- SearchAction
- query
- result
- WebPage
- name
- url
- description
- image
- thumbnailUrl
- datePublished
- ItemList
- numberOfItems
- itemListElement
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-custom-search/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Custom Search.
layout: jsonld
name: context Context
namespaces:
- prefix: cse
  uri: https://customsearch.googleapis.com/customsearch/v1/
properties: []
property_count: 0
provider_name: Google Custom Search
provider_slug: google-custom-search
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cse\": \"https://customsearch.googleapis.com/customsearch/v1/\",\n    \"SearchResultsPage\": \"schema:SearchResultsPage\",\n    \"SearchAction\": \"schema:SearchAction\",\n    \"query\": \"schema:query\",\n    \"result\": \"schema:result\",\n    \"WebPage\": \"schema:WebPage\",\n    \"name\": \"schema:name\",\n    \"url\": \"schema:url\",\n    \"description\": \"schema:description\",\n    \"image\": \"schema:image\",\n    \"thumbnailUrl\": \"schema:thumbnailUrl\",\n    \"datePublished\": \"schema:datePublished\",\n    \"ItemList\": \"schema:ItemList\",\n    \"numberOfItems\": \"schema:numberOfItems\",\n    \"itemListElement\": \"schema:itemListElement\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-custom-search/refs/heads/main/json-ld/context.jsonld
tags:
- Custom Search
- Google
- Image Search
- Search
- Web Search
- JSON-LD
- Linked Data
- Semantic Web
---
