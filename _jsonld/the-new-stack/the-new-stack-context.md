---
class_count: 1
classes:
- title
context_file: json-ld/the-new-stack-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-new-stack/refs/heads/main/json-ld/the-new-stack-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The New Stack from The New Stack.
layout: jsonld
name: The New Stack Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rss
  uri: https://thenewstack.io/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: NewsArticle
  type: ''
- container: ''
  name: BlogPosting
  type: ''
- container: ''
  name: NewsMediaOrganization
  type: ''
- container: ''
  name: Podcast
  type: ''
- container: ''
  name: PodcastEpisode
  type: ''
- container: ''
  name: TheNewStack
  type: ''
- container: ''
  name: link
  type: reference
- container: ''
  name: pubDate
  type: dateTime
- container: ''
  name: author
  type: ''
- container: set
  name: categories
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: content
  type: ''
- container: ''
  name: guid
  type: ''
- container: ''
  name: channel
  type: ''
- container: ''
  name: feed
  type: ''
- container: set
  name: item
  type: ''
- container: set
  name: topics
  type: ''
property_count: 17
provider_name: The New Stack
provider_slug: the-new-stack
slug: the-new-stack-context
source_filename: the-new-stack-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rss\": \"https://thenewstack.io/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"NewsArticle\": {\n      \"@id\": \"schema:NewsArticle\"\n    },\n    \"BlogPosting\": {\n      \"@id\": \"schema:BlogPosting\"\n    },\n    \"NewsMediaOrganization\": {\n      \"@id\": \"schema:NewsMediaOrganization\"\n    },\n    \"Podcast\": {\n      \"@id\": \"schema:PodcastSeries\"\n    },\n    \"PodcastEpisode\": {\n      \"@id\": \"schema:PodcastEpisode\"\n    },\n\n    \"TheNewStack\": {\n      \"@id\": \"schema:NewsMediaOrganization\",\n      \"schema:name\": \"The New Stack\",\n      \"schema:url\": \"https://thenewstack.io\",\n      \"schema:sameAs\": [\n        \"https://x.com/thenewstack\",\n        \"https://www.linkedin.com/company/the-new-stack\"\n      ]\n    },\n\n    \"title\": \"schema:headline\",\n    \"link\": {\n  \
  \    \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"pubDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"author\": {\n      \"@id\": \"schema:author\"\n    },\n    \"categories\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@set\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"content\": {\n      \"@id\": \"schema:articleBody\"\n    },\n    \"guid\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n\n    \"channel\": {\n      \"@id\": \"schema:WebSite\"\n    },\n    \"feed\": {\n      \"@id\": \"schema:DataFeed\"\n    },\n    \"item\": {\n      \"@id\": \"schema:dataFeedElement\",\n      \"@container\": \"@set\"\n    },\n\n    \"topics\": {\n      \"@id\": \"schema:about\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-new-stack/refs/heads/main/json-ld/the-new-stack-context.jsonld
tags:
- Cloud Native
- DevOps
- Media
- Technology News
- JSON-LD
- Linked Data
- Semantic Web
---
