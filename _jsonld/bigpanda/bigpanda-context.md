---
class_count: 6
classes:
- status
- description
- timestamp
- name
- id
- user
context_file: json-ld/bigpanda-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/json-ld/bigpanda-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bigpanda from BigPanda.
layout: jsonld
name: Bigpanda Context
namespaces:
- prefix: bp
  uri: https://docs.bigpanda.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: app_key
  type: string
- container: ''
  name: host
  type: string
- container: ''
  name: check
  type: string
- container: ''
  name: _id
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: environments
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: alerts_count
  type: integer
- container: ''
  name: started_at
  type: integer
- container: ''
  name: incidents
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: end
  type: integer
- container: ''
  name: active
  type: boolean
- container: ''
  name: maintenance_plans
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: hosts
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: logs
  type: string
property_count: 19
provider_name: BigPanda
provider_slug: bigpanda
slug: bigpanda-context
source_filename: bigpanda-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bp\": \"https://docs.bigpanda.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"app_key\": {\n      \"@id\": \"bp:app_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": \"schema:status\",\n    \"host\": {\n      \"@id\": \"bp:host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"check\": {\n      \"@id\": \"bp:check\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"timestamp\": \"schema:dateCreated\",\n    \"_id\": {\n      \"@id\": \"bp:_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"condition\": {\n      \"@id\": \"bp:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": \"schema:identifier\",\n    \"environments\": {\n      \"@id\": \"bp:environments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"bp:severity\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"alerts_count\": {\n      \"@id\": \"bp:alerts_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"started_at\": {\n      \"@id\": \"bp:started_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"incidents\": {\n      \"@id\": \"bp:incidents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"bp:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"end\": {\n      \"@id\": \"bp:end\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"active\": {\n      \"@id\": \"bp:active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"maintenance_plans\": {\n      \"@id\": \"bp:maintenance_plans\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"bp:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"bp:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hosts\": {\n      \"@id\": \"bp:hosts\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"user\": \"schema:person\",\n    \"action\": {\n      \"@id\": \"bp:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logs\": {\n      \"@id\": \"bp:logs\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bigpanda/refs/heads/main/json-ld/bigpanda-context.jsonld
tags:
- Incidents
- Monitoring
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
