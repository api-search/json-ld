---
api_specs:
- filename: grapes-knowledge-base-openapi.yml
  format: yaml
  label: Grapes API
  slug: grapes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/grapes-knowledge-base/refs/heads/main/openapi/grapes-knowledge-base-openapi.yml
class_count: 9
classes:
- Project
- Agent
- Dataset
- id
- name
- description
- format
- configuration
- _links
context_file: json-ld/grapes-knowledge-base-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/grapes-knowledge-base/refs/heads/main/json-ld/grapes-knowledge-base-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Grapes Knowledge Base from Grapes Knowledge Base.
layout: jsonld
name: Grapes Knowledge Base Context
namespaces:
- prefix: grapes
  uri: https://raw.githubusercontent.com/api-evangelist/grapes-knowledge-base/refs/heads/main/json-ld/grapes-knowledge-base-context.jsonld#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
property_count: 2
provider_name: Grapes Knowledge Base
provider_slug: grapes-knowledge-base
slug: grapes-knowledge-base-context
source_filename: grapes-knowledge-base-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"grapes\": \"https://raw.githubusercontent.com/api-evangelist/grapes-knowledge-base/refs/heads/main/json-ld/grapes-knowledge-base-context.jsonld#\",\n    \"Project\": \"schema:Project\",\n    \"Agent\": \"grapes:Agent\",\n    \"Dataset\": \"schema:Dataset\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"format\": \"grapes:format\",\n    \"configuration\": \"grapes:configuration\",\n    \"_links\": \"grapes:links\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/grapes-knowledge-base/refs/heads/main/json-ld/grapes-knowledge-base-context.jsonld
tags:
- Knowledge Management
- Knowledge Base
- Data Management
- Automation
- HATEOAS
- JSON-LD
- Linked Data
- Semantic Web
---
