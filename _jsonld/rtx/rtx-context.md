---
api_specs:
- filename: rtx-eagle-api-openapi.yml
  format: yaml
  label: RTX EAGLE API
  slug: eagle-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rtx/refs/heads/main/openapi/rtx-eagle-api-openapi.yml
class_count: 4
classes:
- DataSource
- AnalyticsJob
- Report
- id
context_file: json-ld/rtx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rtx/refs/heads/main/json-ld/rtx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rtx from RTX.
layout: jsonld
name: Rtx Context
namespaces:
- prefix: rtx
  uri: https://www.rtx.com/vocab/eagle/
- prefix: schema
  uri: https://schema.org/
- prefix: mil
  uri: https://www.dodmil.mil/vocab/
properties:
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: type
  type: schema:Text
- container: ''
  name: program
  type: schema:Text
- container: ''
  name: classification
  type: schema:Text
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: completedAt
  type: schema:DateTime
property_count: 8
provider_name: RTX
provider_slug: rtx
slug: rtx-context
source_filename: rtx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rtx\": \"https://www.rtx.com/vocab/eagle/\",\n    \"schema\": \"https://schema.org/\",\n    \"mil\": \"https://www.dodmil.mil/vocab/\",\n\n    \"DataSource\": \"rtx:DataSource\",\n    \"AnalyticsJob\": \"rtx:AnalyticsJob\",\n    \"Report\": \"rtx:Report\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"status\": {\n      \"@id\": \"rtx:operationalStatus\",\n      \"@type\": \"schema:Text\"\n    },\n    \"type\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"schema:Text\"\n    },\n    \"program\": {\n      \"@id\": \"rtx:defenseProgram\",\n      \"@type\": \"schema:Text\"\n    },\n    \"classification\": {\n      \"@id\": \"mil:classificationLevel\",\n      \"@type\": \"schema:Text\"\n    },\n    \"createdAt\": {\n      \"@id\"\
  : \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rtx/refs/heads/main/json-ld/rtx-context.jsonld
tags:
- Defense
- Aerospace
- Government
- Logistics
- Intelligence
- Military
- JSON-LD
- Linked Data
- Semantic Web
---
