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
