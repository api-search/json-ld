---
api_specs:
- filename: spaceflight-news-api-openapi.yml
  format: yaml
  label: Spaceflight News API
  slug: spaceflight-news-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/openapi/spaceflight-news-api-openapi.yml
class_count: 14
classes:
- Article
- Blog
- Report
- Author
- id
- title
- news_site
- summary
- launch_id
- event_id
- provider
- name
- socials
- count
context_file: json-ld/spaceflight-news-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/json-ld/spaceflight-news-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spaceflight News Api from Spaceflight News API.
layout: jsonld
name: Spaceflight News Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: snapi
  uri: https://api.spaceflightnewsapi.net/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: authors
  type: schema:Person
- container: ''
  name: url
  type: reference
- container: ''
  name: image_url
  type: reference
- container: ''
  name: published_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: featured
  type: boolean
- container: ''
  name: launches
  type: ''
- container: ''
  name: events
  type: ''
- container: ''
  name: next
  type: reference
- container: ''
  name: previous
  type: reference
- container: ''
  name: results
  type: ''
property_count: 11
provider_name: Spaceflight News API
provider_slug: spaceflight-news-api
slug: spaceflight-news-api-context
source_filename: spaceflight-news-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"snapi\": \"https://api.spaceflightnewsapi.net/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Article\": \"schema:NewsArticle\",\n    \"Blog\": \"schema:BlogPosting\",\n    \"Report\": \"schema:Report\",\n    \"Author\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:headline\",\n    \"authors\": {\n      \"@id\": \"schema:author\",\n      \"@type\": \"schema:Person\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"news_site\": \"schema:publisher\",\n    \"summary\": \"schema:description\",\n    \"published_at\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n   \
  \ },\n    \"featured\": {\n      \"@id\": \"snapi:featured\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"launches\": {\n      \"@id\": \"snapi:relatedLaunch\"\n    },\n    \"events\": {\n      \"@id\": \"snapi:relatedEvent\"\n    },\n    \"launch_id\": \"snapi:launchId\",\n    \"event_id\": \"snapi:eventId\",\n    \"provider\": \"schema:provider\",\n    \"name\": \"schema:name\",\n    \"socials\": \"schema:sameAs\",\n\n    \"count\": \"snapi:totalCount\",\n    \"next\": {\n      \"@id\": \"schema:nextItem\",\n      \"@type\": \"@id\"\n    },\n    \"previous\": {\n      \"@id\": \"schema:previousItem\",\n      \"@type\": \"@id\"\n    },\n    \"results\": {\n      \"@id\": \"schema:itemListElement\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spaceflight-news-api/refs/heads/main/json-ld/spaceflight-news-api-context.jsonld
tags:
- News
- Space
- Spaceflight
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
