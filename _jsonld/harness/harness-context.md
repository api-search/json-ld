---
class_count: 4
classes:
- Organization
- Project
- Pipeline
- PipelineExecution
context_file: json-ld/harness-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/json-ld/harness-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Harness from Harness.
layout: jsonld
name: Harness Context
namespaces:
- prefix: harness
  uri: https://harness.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: identifier
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: orgIdentifier
  type: string
- container: ''
  name: color
  type: string
- container: set
  name: tags
  type: ''
property_count: 7
provider_name: Harness
provider_slug: harness
slug: harness-context
source_filename: harness-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"harness\": \"https://harness.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Organization\": \"harness:Organization\",\n    \"Project\": \"harness:Project\",\n    \"Pipeline\": \"harness:Pipeline\",\n    \"PipelineExecution\": \"harness:PipelineExecution\",\n    \"identifier\": { \"@id\": \"harness:identifier\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"harness:status\", \"@type\": \"xsd:string\" },\n    \"orgIdentifier\": { \"@id\": \"harness:orgIdentifier\", \"@type\": \"xsd:string\" },\n    \"color\": { \"@id\": \"harness:color\", \"@type\": \"xsd:string\" },\n    \"tags\": { \"@id\": \"harness:tags\", \"@container\": \"@set\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/harness/refs/heads/main/json-ld/harness-context.jsonld
tags:
- DevOps
- GitOps
- Internal Developer Portal
- Lifecycle
- Software Delivery
- JSON-LD
- Linked Data
- Semantic Web
---
