---
api_specs:
- filename: fumadocs-search-openapi.yml
  format: yaml
  label: Fumadocs Search API
  slug: search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/openapi/fumadocs-search-openapi.yml
- filename: fumadocs-openapi-proxy-openapi.yml
  format: yaml
  label: Fumadocs OpenAPI Proxy API
  slug: openapi-proxy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/openapi/fumadocs-openapi-proxy-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fumadocs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/json-ld/fumadocs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fumadocs from Fumadocs.
layout: jsonld
name: Fumadocs Context
namespaces:
- prefix: fumadocs
  uri: https://fumadocs.dev/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DocumentationSite
  type: ''
- container: ''
  name: PageTree
  type: ''
- container: ''
  name: Page
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Separator
  type: ''
- container: ''
  name: SearchResult
  type: ''
- container: ''
  name: Meta
  type: ''
property_count: 7
provider_name: Fumadocs
provider_slug: fumadocs
slug: fumadocs-context
source_filename: fumadocs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fumadocs\": \"https://fumadocs.dev/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DocumentationSite\": {\n      \"@id\": \"fumadocs:DocumentationSite\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"baseUrl\": {\n          \"@id\": \"fumadocs:baseUrl\",\n          \"@type\": \"@id\"\n        },\n        \"pageTree\": {\n          \"@id\": \"fumadocs:pageTree\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PageTree\": {\n      \"@id\": \"fumadocs:PageTree\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"children\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n  \
  \      },\n        \"fallback\": {\n          \"@id\": \"fumadocs:fallback\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Page\": {\n      \"@id\": \"fumadocs:Page\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"icon\": \"schema:image\",\n        \"type\": \"schema:additionalType\",\n        \"external\": \"fumadocs:external\"\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"fumadocs:Folder\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"icon\": \"schema:image\",\n        \"root\": \"fumadocs:root\",\n        \"defaultOpen\": \"fumadocs:defaultOpen\",\n        \"collapsible\": \"fumadocs:collapsible\",\n        \"children\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        },\n\
  \        \"index\": {\n          \"@id\": \"fumadocs:indexPage\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Separator\": {\n      \"@id\": \"fumadocs:Separator\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"icon\": \"schema:image\"\n      }\n    },\n\n    \"SearchResult\": {\n      \"@id\": \"fumadocs:SearchResult\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"type\": \"schema:additionalType\",\n        \"content\": \"schema:text\",\n        \"breadcrumbs\": {\n          \"@id\": \"fumadocs:breadcrumbs\",\n          \"@container\": \"@list\"\n        }\n      }\n    },\n\n    \"Meta\": {\n      \"@id\": \"fumadocs:Meta\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"pages\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\"\
  : \"@list\"\n        },\n        \"root\": \"fumadocs:root\",\n        \"defaultOpen\": \"fumadocs:defaultOpen\",\n        \"collapsible\": \"fumadocs:collapsible\",\n        \"icon\": \"schema:image\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fumadocs/refs/heads/main/json-ld/fumadocs-context.jsonld
tags:
- Documentation
- Framework
- Next.js
- React
- JSON-LD
- Linked Data
- Semantic Web
---
