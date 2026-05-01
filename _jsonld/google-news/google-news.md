---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google News RSS API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/openapi/openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-news.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-ld/google-news.jsonld
description: JSON-LD context defining the semantic vocabulary for Google News from Google News RSS.
layout: jsonld
name: Google News Context
namespaces:
- prefix: gnews
  uri: https://news.google.com/rss#
- prefix: NewsArticle
  uri: https://schema.org/NewsArticle
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: headline
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: datePublished
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: publisher
  type: reference
- container: ''
  name: topic
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: language
  type: string
property_count: 8
provider_name: Google News RSS
provider_slug: google-news
slug: google-news
source_filename: google-news.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gnews\": \"https://news.google.com/rss#\",\n    \"NewsArticle\": \"https://schema.org/NewsArticle\",\n    \"headline\": {\n      \"@id\": \"https://schema.org/headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"https://schema.org/url\",\n      \"@type\": \"@id\"\n    },\n    \"datePublished\": {\n      \"@id\": \"https://schema.org/datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"https://schema.org/description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\": \"https://schema.org/publisher\",\n      \"@type\": \"@id\"\n    },\n    \"topic\": {\n      \"@id\": \"gnews:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"gnews:geo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"gnews:hl\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-news/refs/heads/main/json-ld/google-news.jsonld
tags:
- Aggregation
- Google News
- Headlines
- Media
- News
- RSS
- JSON-LD
- Linked Data
- Semantic Web
---
