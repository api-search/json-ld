---
api_specs:
- filename: aligned-news-openapi.yml
  format: yaml
  label: Aligned News REST API
  slug: aligned-news-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/openapi/aligned-news-openapi.yml
class_count: 18
classes:
- AlignedNews
- name
- description
- url
- provider
- Story
- Signal
- Report
- Bundle
- Section
- id
- title
- summary
- body
- content
- Endpoint
- endpointURL
- endpointDescription
context_file: json-ld/aligned-news-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/json-ld/aligned-news-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aligned News from Aligned News.
layout: jsonld
name: Aligned News Context
namespaces:
- prefix: aln
  uri: https://alignednews.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: slug
  type: ''
- container: ''
  name: section
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: publishedAt
  type: dateTime
- container: ''
  name: badge
  type: ''
- container: ''
  name: analysis
  type: ''
- container: set
  name: relatedStories
  type: ''
- container: ''
  name: sourceUrl
  type: anyURI
- container: set
  name: stories
  type: ''
property_count: 9
provider_name: Aligned News
provider_slug: aligned-news
slug: aligned-news-context
source_filename: aligned-news-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aln\": \"https://alignednews.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlignedNews\": \"aln:AlignedNews\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"provider\": \"schema:provider\",\n\n    \"Story\": \"schema:NewsArticle\",\n    \"Signal\": \"aln:Signal\",\n    \"Report\": \"schema:Report\",\n    \"Bundle\": \"schema:Collection\",\n    \"Section\": \"aln:Section\",\n\n    \"id\": \"schema:identifier\",\n    \"title\": \"schema:headline\",\n    \"slug\": {\"@id\": \"aln:slug\"},\n    \"section\": {\"@id\": \"aln:section\"},\n    \"summary\": \"schema:abstract\",\n    \"body\": \"schema:articleBody\",\n    \"content\": \"schema:text\",\n    \"tags\": {\"@id\": \"schema:keywords\", \"@container\": \"@set\"},\n    \"publishedAt\": {\"\
  @id\": \"schema:datePublished\", \"@type\": \"xsd:dateTime\"},\n\n    \"badge\": {\"@id\": \"aln:badge\"},\n    \"analysis\": {\"@id\": \"aln:analysis\"},\n    \"relatedStories\": {\"@id\": \"aln:relatedStories\", \"@container\": \"@set\"},\n    \"sourceUrl\": {\"@id\": \"aln:sourceUrl\", \"@type\": \"xsd:anyURI\"},\n\n    \"stories\": {\"@id\": \"aln:stories\", \"@container\": \"@set\"},\n\n    \"Endpoint\": \"aln:Endpoint\",\n    \"endpointURL\": \"schema:endpointURL\",\n    \"endpointDescription\": \"schema:endpointDescription\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aligned-news/refs/heads/main/json-ld/aligned-news-context.jsonld
tags:
- AI
- News
- Intelligence
- MCP
- Signals
- JSON-LD
- Linked Data
- Semantic Web
---
