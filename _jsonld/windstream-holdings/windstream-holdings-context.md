---
api_specs:
- filename: windstream-voice-openapi.yml
  format: yaml
  label: Windstream Enterprise Voice API
  slug: windstream-voice-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-voice-openapi.yml
- filename: windstream-contact-center-openapi.yml
  format: yaml
  label: Windstream Enterprise Contact Center Services API
  slug: windstream-contact-center-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-contact-center-openapi.yml
class_count: 14
classes:
- Call
- Extension
- AutoAttendant
- Tenant
- Agent
- Queue
- User
- Role
- Organization
- name
- description
- url
- telephone
- email
context_file: json-ld/windstream-holdings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/json-ld/windstream-holdings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Windstream Holdings from Windstream Holdings.
layout: jsonld
name: Windstream Holdings Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: windstream
  uri: https://windstreamenterprise.com/vocab#
- prefix: telecom
  uri: https://www.itu.int/vocab#
properties:
- container: ''
  name: callId
  type: string
- container: ''
  name: callingNumber
  type: string
- container: ''
  name: calledNumber
  type: string
- container: ''
  name: callState
  type: string
- container: ''
  name: callDuration
  type: integer
- container: ''
  name: extensionNumber
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: agentState
  type: string
- container: ''
  name: queueLength
  type: integer
- container: ''
  name: agentsAvailable
  type: integer
- container: ''
  name: menuOption
  type: reference
- container: ''
  name: dtmfDigit
  type: string
- container: ''
  name: greeting
  type: string
property_count: 13
provider_name: Windstream Holdings
provider_slug: windstream-holdings
slug: windstream-holdings-context
source_filename: windstream-holdings-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"windstream\": \"https://windstreamenterprise.com/vocab#\",\n    \"telecom\": \"https://www.itu.int/vocab#\",\n\n    \"Call\": \"windstream:Call\",\n    \"Extension\": \"windstream:Extension\",\n    \"AutoAttendant\": \"windstream:AutoAttendant\",\n    \"Tenant\": \"windstream:Tenant\",\n    \"Agent\": \"windstream:Agent\",\n    \"Queue\": \"windstream:Queue\",\n    \"User\": \"windstream:User\",\n    \"Role\": \"windstream:Role\",\n\n    \"callId\": {\n      \"@id\": \"windstream:callId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callingNumber\": {\n      \"@id\": \"windstream:callingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"calledNumber\": {\n      \"@id\": \"windstream:calledNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"callState\": {\n      \"@id\": \"windstream:callState\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"callDuration\": {\n      \"@id\": \"windstream:callDuration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"extensionNumber\": {\n      \"@id\": \"windstream:extensionNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"windstream:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentState\": {\n      \"@id\": \"windstream:agentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueLength\": {\n      \"@id\": \"windstream:queueLength\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"agentsAvailable\": {\n      \"@id\": \"windstream:agentsAvailable\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"menuOption\": {\n      \"@id\": \"windstream:menuOption\",\n      \"@type\": \"@id\"\n    },\n    \"dtmfDigit\": {\n      \"@id\": \"windstream:dtmfDigit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"greeting\": {\n      \"@id\": \"windstream:greeting\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"telephone\": \"schema:telephone\",\n    \"email\": \"schema:email\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/json-ld/windstream-holdings-context.jsonld
tags:
- Broadband
- Contact Center
- Managed Services
- Network Communications
- SD-WAN
- Telecom
- UCaaS
- Unified Communications
- JSON-LD
- Linked Data
- Semantic Web
---
