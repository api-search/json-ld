---
api_specs:
- filename: the-news-api-openapi.yml
  format: yaml
  label: The News API
  slug: the-news-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/openapi/the-news-api-openapi.yml
class_count: 20
classes:
- Article
- Source
- uuid
- title
- description
- snippet
- language
- source
- locale
- keywords
- categories
- relevance_score
- similar
- source_id
- domain
- meta
- found
- returned
- limit
- page
context_file: json-ld/the-news-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/json-ld/the-news-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The News Api from The News API.
layout: jsonld
name: The News Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: news
  uri: https://www.thenewsapi.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: image_url
  type: reference
- container: ''
  name: published_at
  type: dateTime
property_count: 3
provider_name: The News API
provider_slug: the-news-api
slug: the-news-api-context
source_filename: the-news-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"news\": \"https://www.thenewsapi.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Article\": \"schema:NewsArticle\",\n    \"Source\": \"schema:NewsMediaOrganization\",\n\n    \"uuid\": \"schema:identifier\",\n    \"title\": \"schema:headline\",\n    \"description\": \"schema:description\",\n    \"snippet\": \"schema:abstract\",\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"image_url\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"language\": \"schema:inLanguage\",\n    \"published_at\": { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\" },\n    \"source\": \"schema:publisher\",\n    \"locale\": \"schema:countryOfOrigin\",\n    \"keywords\": \"schema:keywords\",\n    \"categories\": \"schema:articleSection\",\n    \"relevance_score\": \"news:relevanceScore\",\n    \"similar\": \"schema:mentions\",\n\n\
  \    \"source_id\": \"schema:identifier\",\n    \"domain\": \"schema:url\",\n\n    \"meta\": \"news:meta\",\n    \"found\": \"news:totalResults\",\n    \"returned\": \"news:returnedResults\",\n    \"limit\": \"news:pageSize\",\n    \"page\": \"news:pageNumber\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-news-api/refs/heads/main/json-ld/the-news-api-context.jsonld
tags:
- Articles
- Headlines
- News
- Media
- Search
- International
- JSON-LD
- Linked Data
- Semantic Web
---
