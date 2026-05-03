---
api_specs:
- filename: zdnet-rss.yml
  format: yaml
  label: ZDNet RSS Feed
  slug: rss
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/openapi/zdnet-rss.yml
class_count: 3
classes:
- RssFeed
- RssItem
- description
context_file: json-ld/zdnet-rss-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-ld/zdnet-rss-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zdnet Rss from ZDNet.
layout: jsonld
name: Zdnet Rss Context
namespaces:
- prefix: zdnet
  uri: https://zdnet.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: title
  type: string
- container: ''
  name: link
  type: string
- container: ''
  name: language
  type: string
- container: set
  name: items
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: pubDate
  type: dateTime
- container: set
  name: category
  type: string
- container: ''
  name: guid
  type: string
property_count: 8
provider_name: ZDNet
provider_slug: zdnet
slug: zdnet-rss-context
source_filename: zdnet-rss-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zdnet\": \"https://zdnet.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RssFeed\": \"zdnet:RssFeed\",\n    \"RssItem\": \"zdnet:RssItem\",\n    \"title\": {\n      \"@id\": \"zdnet:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"zdnet:link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"language\": {\n      \"@id\": \"zdnet:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"zdnet:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"zdnet:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pubDate\": {\n      \"@id\": \"zdnet:pubDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"category\": {\n      \"@id\"\
  : \"zdnet:category\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guid\": {\n      \"@id\": \"zdnet:guid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zdnet/refs/heads/main/json-ld/zdnet-rss-context.jsonld
tags:
- Enterprise IT
- Media
- Technology News
- JSON-LD
- Linked Data
- Semantic Web
---
