---
api_specs:
- filename: grounded-tools-docs-mcp-server-openapi.yml
  format: yaml
  label: Grounded.tools
  slug: grounded-tools
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grounded-tools/refs/heads/main/openapi/grounded-tools-docs-mcp-server-openapi.yml
class_count: 0
classes: []
context_file: json-ld/grounded-tools-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/grounded-tools/refs/heads/main/json-ld/grounded-tools-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Grounded Tools from Grounded.tools.
layout: jsonld
name: Grounded Tools Context
namespaces:
- prefix: grounded
  uri: https://grounded.tools/
properties:
- container: ''
  name: Library
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: SearchResult
  type: ''
property_count: 4
provider_name: Grounded.tools
provider_slug: grounded-tools
slug: grounded-tools-context
source_filename: grounded-tools-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"grounded\": \"https://grounded.tools/\",\n    \"Library\": {\n      \"@id\": \"grounded:library\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"versions\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"Version\": {\n      \"@id\": \"grounded:version\",\n      \"@context\": {\n        \"version\": \"https://schema.org/softwareVersion\",\n        \"documentCount\": \"https://schema.org/numberOfItems\",\n        \"uniqueUrlCount\": \"https://schema.org/numberOfItems\",\n        \"indexedAt\": \"https://schema.org/dateCreated\",\n        \"status\": \"https://schema.org/status\",\n        \"sourceUrl\": \"https://schema.org/url\"\n      }\n    },\n    \"Job\": {\n      \"@id\": \"grounded:job\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"library\": \"https://schema.org/name\",\n        \"version\": \"https://schema.org/softwareVersion\"\
  ,\n        \"status\": \"https://schema.org/status\",\n        \"createdAt\": \"https://schema.org/dateCreated\",\n        \"startedAt\": \"https://schema.org/startTime\",\n        \"finishedAt\": \"https://schema.org/endTime\",\n        \"error\": \"https://schema.org/error\",\n        \"progress\": \"https://schema.org/MonitorAction\"\n      }\n    },\n    \"SearchResult\": {\n      \"@id\": \"grounded:search-result\",\n      \"@context\": {\n        \"url\": \"https://schema.org/url\",\n        \"content\": \"https://schema.org/text\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/grounded-tools/refs/heads/main/json-ld/grounded-tools-context.jsonld
tags:
- Developer Tools
- Developers
- Documentation
- Experience
- JSON-LD
- Linked Data
- Semantic Web
---
