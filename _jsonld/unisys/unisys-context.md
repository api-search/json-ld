---
api_specs:
- filename: unisys-stealth-ecoapi-openapi.yaml
  format: yaml
  label: Unisys Stealth EcoAPI
  slug: unisys-stealth-ecoapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/openapi/unisys-stealth-ecoapi-openapi.yaml
class_count: 0
classes: []
context_file: json-ld/unisys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Unisys from Unisys.
layout: jsonld
name: Unisys Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: unisys
  uri: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld#
properties:
- container: ''
  name: StealthRole
  type: schema:Role
- container: ''
  name: IsolationRequest
  type: schema:Action
- container: ''
  name: UnisolationRequest
  type: schema:Action
- container: ''
  name: ActionResponse
  type: schema:ActionStatusType
- container: ''
  name: roleId
  type: string
- container: ''
  name: roleName
  type: string
- container: ''
  name: endpoint
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: timestamp
  type: dateTime
property_count: 11
provider_name: Unisys
provider_slug: unisys
slug: unisys-context
source_filename: unisys-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"unisys\": \"https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld#\",\n\n    \"StealthRole\": {\n      \"@id\": \"unisys:StealthRole\",\n      \"@type\": \"schema:Role\"\n    },\n    \"IsolationRequest\": {\n      \"@id\": \"unisys:IsolationRequest\",\n      \"@type\": \"schema:Action\"\n    },\n    \"UnisolationRequest\": {\n      \"@id\": \"unisys:UnisolationRequest\",\n      \"@type\": \"schema:Action\"\n    },\n    \"ActionResponse\": {\n      \"@id\": \"unisys:ActionResponse\",\n      \"@type\": \"schema:ActionStatusType\"\n    },\n\n    \"roleId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpoint\": {\n      \"@id\": \"schema:location\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"schema:agent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:actionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/unisys/refs/heads/main/json-ld/unisys-context.jsonld
tags:
- Security
- Zero Trust
- Network Security
- IT Services
- Cybersecurity
- Enterprise Technology
- JSON-LD
- Linked Data
- Semantic Web
---
