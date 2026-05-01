---
api_specs:
- filename: dell-technologies-dell-api-openapi.yml
  format: yaml
  label: Dell Technologies API
  slug: dell-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dell-technologies/refs/heads/main/openapi/dell-technologies-dell-api-openapi.yml
class_count: 3
classes:
- Server
- Storage
- Service
context_file: json-ld/dell-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dell-technologies/refs/heads/main/json-ld/dell-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dell from Dell Technologies.
layout: jsonld
name: Dell Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dell
  uri: https://schema.dell.com/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: model
  type: schema:Text
- container: ''
  name: service_tag
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: version
  type: schema:Text
property_count: 6
provider_name: Dell Technologies
provider_slug: dell-technologies
slug: dell-context
source_filename: dell-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.dell.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"dell\": \"https://schema.dell.com/\",\n    \"Server\": \"dell:Server\",\n    \"Storage\": \"dell:Storage\",\n    \"Service\": \"schema:Service\",\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"model\": {\"@id\": \"schema:model\", \"@type\": \"schema:Text\"},\n    \"service_tag\": {\"@id\": \"dell:serviceTag\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"dell:status\", \"@type\": \"schema:Text\"},\n    \"version\": {\"@id\": \"schema:softwareVersion\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dell-technologies/refs/heads/main/json-ld/dell-context.jsonld
tags:
- Enterprise IT
- Infrastructure
- Servers
- Storage
- Cloud
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
