---
api_specs:
- filename: stacker-openapi.yml
  format: yaml
  label: Stacker API
  slug: stacker-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/openapi/stacker-openapi.yml
class_count: 10
classes:
- sid
- object_sid
- record_sid
- stack_id
- account_id
- field_api_name
- name
- description
- created
- modified
context_file: json-ld/stacker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/json-ld/stacker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stacker from Stacker.
layout: jsonld
name: Stacker Context
namespaces:
- prefix: stacker
  uri: https://api.go.stackerhq.com/schema/
properties:
- container: ''
  name: StackObject
  type: reference
- container: ''
  name: Record
  type: reference
- container: ''
  name: Account
  type: reference
property_count: 3
provider_name: Stacker
provider_slug: stacker
slug: stacker-context
source_filename: stacker-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"stacker\": \"https://api.go.stackerhq.com/schema/\",\n    \"sid\": \"stacker:systemIdentifier\",\n    \"object_sid\": \"stacker:objectIdentifier\",\n    \"record_sid\": \"stacker:recordIdentifier\",\n    \"stack_id\": \"stacker:stackIdentifier\",\n    \"account_id\": \"stacker:accountIdentifier\",\n    \"field_api_name\": \"stacker:fieldApiName\",\n    \"StackObject\": {\n      \"@id\": \"stacker:Object\",\n      \"@type\": \"@id\"\n    },\n    \"Record\": {\n      \"@id\": \"stacker:Record\",\n      \"@type\": \"@id\"\n    },\n    \"Account\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": \"schema:dateCreated\",\n    \"modified\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stacker/refs/heads/main/json-ld/stacker-context.jsonld
tags:
- Application Development
- Low-Code
- No-Code
- Portals
- Workflow Automation
- JSON-LD
- Linked Data
- Semantic Web
---
