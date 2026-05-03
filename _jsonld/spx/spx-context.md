---
api_specs:
- filename: spx-graphics-control-api-openapi.yml
  format: yaml
  label: SPX Graphics Control API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spx/refs/heads/main/openapi/spx-graphics-control-api-openapi.yml
class_count: 20
classes:
- RundownItem
- Rundown
- Template
- TemplateField
- Extension
- Project
- id
- name
- description
- status
- field
- value
- out
- notes
- project
- rundown
- command
- extension
- function
- filename
context_file: json-ld/spx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spx/refs/heads/main/json-ld/spx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spx from SPX Graphics.
layout: jsonld
name: Spx Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spx
  uri: https://spxgraphics.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: template
  type: reference
- container: list
  name: fields
  type: ''
- container: ''
  name: playDelay
  type: integer
- container: set
  name: files
  type: ''
property_count: 4
provider_name: SPX Graphics
provider_slug: spx
slug: spx-context
source_filename: spx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spx\": \"https://spxgraphics.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"RundownItem\": \"spx:RundownItem\",\n    \"Rundown\": \"spx:Rundown\",\n    \"Template\": \"spx:Template\",\n    \"TemplateField\": \"spx:TemplateField\",\n    \"Extension\": \"spx:Extension\",\n    \"Project\": \"spx:Project\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"template\": {\n      \"@id\": \"spx:template\",\n      \"@type\": \"@id\"\n    },\n    \"status\": \"spx:playbackStatus\",\n    \"fields\": {\n      \"@id\": \"spx:hasField\",\n      \"@container\": \"@list\"\n    },\n    \"field\": \"spx:fieldName\",\n    \"value\": \"schema:value\",\n    \"out\": \"spx:outputTarget\",\n    \"playDelay\": {\n      \"@id\": \"spx:playDelay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notes\": \"schema:comment\"\
  ,\n    \"project\": \"spx:project\",\n    \"rundown\": \"spx:rundown\",\n    \"command\": \"spx:playbackCommand\",\n    \"extension\": \"spx:extension\",\n    \"function\": \"spx:function\",\n    \"filename\": \"schema:name\",\n    \"files\": {\n      \"@id\": \"spx:hasFile\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spx/refs/heads/main/json-ld/spx-context.jsonld
tags:
- Broadcast
- Graphics
- Live Production
- Media
- Streaming
- Video Production
- JSON-LD
- Linked Data
- Semantic Web
---
