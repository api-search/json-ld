---
class_count: 5
classes:
- MonitorCategoriesResponse
- MonitorMetricsResponse
- ReloadEntriesResponse
- ReloadEntry
- ReloadResponse
context_file: json-ld/bfe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/json-ld/bfe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bfe from BFE.
layout: jsonld
name: Bfe Context
namespaces:
- prefix: bfe
  uri: https://bfe-networks.net/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: categories
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: metrics
  type: string
- container: ''
  name: entries
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: message
  type: string
property_count: 7
provider_name: BFE
provider_slug: bfe
slug: bfe-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bfe\": \"https://bfe-networks.net/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MonitorCategoriesResponse\": \"bfe:MonitorCategoriesResponse\",\n    \"MonitorMetricsResponse\": \"bfe:MonitorMetricsResponse\",\n    \"ReloadEntriesResponse\": \"bfe:ReloadEntriesResponse\",\n    \"ReloadEntry\": \"bfe:ReloadEntry\",\n    \"ReloadResponse\": \"bfe:ReloadResponse\",\n    \"categories\": {\n      \"@id\": \"bfe:categories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"bfe:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"bfe:metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"bfe:entries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"bfe:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n     \
  \ \"@id\": \"bfe:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"message\": {\n      \"@id\": \"bfe:message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bfe/refs/heads/main/json-ld/bfe-context.jsonld
tags:
- Load Balancer
- Networking
- Open Source
- Traffic Management
- CNCF
- Baidu
- JSON-LD
- Linked Data
- Semantic Web
---
