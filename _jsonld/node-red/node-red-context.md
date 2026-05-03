---
api_specs:
- filename: node-red-admin-openapi.yml
  format: yaml
  label: Node-RED Admin API
  slug: node-red
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/node-red/refs/heads/main/openapi/node-red-admin-openapi.yml
class_count: 9
classes:
- Flow
- Node
- id
- type
- label
- name
- info
- wires
- env
context_file: json-ld/node-red-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/node-red/refs/heads/main/json-ld/node-red-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Node Red from Node-RED.
layout: jsonld
name: Node Red Context
namespaces:
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: Node-RED
provider_slug: node-red
slug: node-red-context
source_filename: node-red-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://nodered.org/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"Flow\": \"schema:CreativeWork\",\n    \"Node\": \"schema:SoftwareSourceCode\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"label\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"info\": \"schema:description\",\n    \"wires\": \"schema:isRelatedTo\",\n    \"env\": \"schema:hasPart\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/node-red/refs/heads/main/json-ld/node-red-context.jsonld
tags:
- Self-Hosted
- Workflow Automation
- Flow-Based Programming
- IoT
- JSON-LD
- Linked Data
- Semantic Web
---
