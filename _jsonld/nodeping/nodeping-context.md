---
api_specs:
- filename: nodeping-openapi.yml
  format: yaml
  label: NodePing API
  slug: nodeping
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nodeping/refs/heads/main/openapi/nodeping-openapi.yml
class_count: 13
classes:
- Check
- Contact
- ContactGroup
- Schedule
- Result
- _id
- type
- label
- target
- description
- tags
- created
- modified
context_file: json-ld/nodeping-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nodeping/refs/heads/main/json-ld/nodeping-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nodeping from NodePing.
layout: jsonld
name: Nodeping Context
namespaces:
- prefix: schema
  uri: https://schema.org/
properties: []
property_count: 0
provider_name: NodePing
provider_slug: nodeping
slug: nodeping-context
source_filename: nodeping-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://nodeping.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"Check\": \"schema:Action\",\n    \"Contact\": \"schema:Person\",\n    \"ContactGroup\": \"schema:Organization\",\n    \"Schedule\": \"schema:Schedule\",\n    \"Result\": \"schema:Observation\",\n    \"_id\": \"@id\",\n    \"type\": \"@type\",\n    \"label\": \"schema:name\",\n    \"target\": \"schema:url\",\n    \"description\": \"schema:description\",\n    \"tags\": \"schema:keywords\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nodeping/refs/heads/main/json-ld/nodeping-context.jsonld
tags:
- Monitoring
- Uptime
- Notifications
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
