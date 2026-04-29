---
class_count: 8
classes:
- role
- content
- model
- id
- created
- name
- status
- version
context_file: json-ld/bifrost-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/json-ld/bifrost-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bifrost from Bifrost.
layout: jsonld
name: Bifrost Context
namespaces:
- prefix: bf
  uri: https://www.getbifrost.ai/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: messages
  type: string
- container: ''
  name: temperature
  type: decimal
- container: ''
  name: max_tokens
  type: integer
- container: ''
  name: stream
  type: boolean
- container: ''
  name: top_p
  type: decimal
- container: ''
  name: n
  type: integer
- container: ''
  name: index
  type: integer
- container: ''
  name: message
  type: string
- container: ''
  name: finish_reason
  type: string
- container: ''
  name: prompt_tokens
  type: integer
- container: ''
  name: completion_tokens
  type: integer
- container: ''
  name: total_tokens
  type: integer
- container: ''
  name: object
  type: string
- container: ''
  name: choices
  type: string
- container: ''
  name: usage
  type: string
- container: ''
  name: providers
  type: string
property_count: 16
provider_name: Bifrost
provider_slug: bifrost
slug: bifrost-context
source_filename: bifrost-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bf\": \"https://www.getbifrost.ai/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"role\": \"schema:roleName\",\n    \"content\": \"schema:text\",\n    \"model\": \"schema:model\",\n    \"messages\": {\n      \"@id\": \"bf:messages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"temperature\": {\n      \"@id\": \"bf:temperature\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"max_tokens\": {\n      \"@id\": \"bf:max_tokens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stream\": {\n      \"@id\": \"bf:stream\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"top_p\": {\n      \"@id\": \"bf:top_p\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"n\": {\n      \"@id\": \"bf:n\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"index\": {\n      \"@id\": \"bf:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"bf:message\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"finish_reason\": {\n      \"@id\": \"bf:finish_reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prompt_tokens\": {\n      \"@id\": \"bf:prompt_tokens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"completion_tokens\": {\n      \"@id\": \"bf:completion_tokens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total_tokens\": {\n      \"@id\": \"bf:total_tokens\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": \"schema:identifier\",\n    \"object\": {\n      \"@id\": \"bf:object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": \"schema:dateCreated\",\n    \"choices\": {\n      \"@id\": \"bf:choices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usage\": {\n      \"@id\": \"bf:usage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"status\": \"schema:status\",\n    \"version\": \"schema:version\",\n    \"providers\": {\n      \"@id\": \"bf:providers\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/bifrost/refs/heads/main/json-ld/bifrost-context.jsonld
tags:
- AI Gateway
- LLM
- Load Balancing
- Open Source
- OpenAI Compatible
- MCP
- JSON-LD
- Linked Data
- Semantic Web
---
