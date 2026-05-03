---
api_specs:
- filename: tinybird-openapi.yml
  format: yaml
  label: Tinybird API
  slug: tinybird
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/openapi/tinybird-openapi.yml
class_count: 35
classes:
- DataSource
- Pipe
- PipeNode
- Token
- Job
- Organization
- Workspace
- EnvVar
- id
- name
- description
- schema_def
- cluster
- row_count
- disk_bytes
- replicated
- ttl_expression
- tags
- nodes
- sql
- pipe_type
- endpoint
- token
- scopes
- scope_type
- resource
- filter
- job_kind
- status
- progress
- error
- region
- baseUri
- format
- query
context_file: json-ld/tinybird-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-ld/tinybird-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tinybird from Tinybird.
layout: jsonld
name: Tinybird Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tinybird
  uri: https://www.tinybird.co/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 2
provider_name: Tinybird
provider_slug: tinybird
slug: tinybird-context
source_filename: tinybird-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tinybird\": \"https://www.tinybird.co/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"DataSource\": \"tinybird:DataSource\",\n    \"Pipe\": \"tinybird:Pipe\",\n    \"PipeNode\": \"tinybird:PipeNode\",\n    \"Token\": \"tinybird:Token\",\n    \"Job\": \"tinybird:Job\",\n    \"Organization\": \"schema:Organization\",\n    \"Workspace\": \"tinybird:Workspace\",\n    \"EnvVar\": \"tinybird:EnvironmentVariable\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"schema_def\": \"tinybird:schemaDefinition\",\n    \"cluster\": \"tinybird:cluster\",\n    \"row_count\": \"tinybird:rowCount\",\n    \"\
  disk_bytes\": \"tinybird:diskBytes\",\n    \"replicated\": \"tinybird:replicated\",\n    \"ttl_expression\": \"tinybird:ttlExpression\",\n    \"tags\": \"schema:keywords\",\n\n    \"nodes\": \"tinybird:hasNode\",\n    \"sql\": \"tinybird:sqlQuery\",\n    \"pipe_type\": \"tinybird:pipeType\",\n    \"endpoint\": \"schema:url\",\n\n    \"token\": \"tinybird:tokenValue\",\n    \"scopes\": \"tinybird:hasScope\",\n    \"scope_type\": \"tinybird:scopeType\",\n    \"resource\": \"tinybird:scopeResource\",\n    \"filter\": \"tinybird:rowFilter\",\n\n    \"job_kind\": \"tinybird:jobKind\",\n    \"status\": \"tinybird:jobStatus\",\n    \"progress\": \"tinybird:jobProgress\",\n    \"error\": \"schema:error\",\n\n    \"region\": \"schema:areaServed\",\n    \"baseUri\": \"schema:url\",\n    \"format\": \"schema:encodingFormat\",\n    \"query\": \"tinybird:sqlStatement\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tinybird/refs/heads/main/json-ld/tinybird-context.jsonld
tags:
- Analytics
- Data
- Real-Time
- SQL
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
