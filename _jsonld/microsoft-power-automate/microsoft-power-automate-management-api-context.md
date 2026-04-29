---
api_specs:
- filename: microsoft-power-automate-management-api.yaml
  format: yaml
  label: Power Automate Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-automate/refs/heads/main/openapi/microsoft-power-automate-management-api.yaml
class_count: 6
classes:
- Flow
- Environment
- FlowRun
- Connector
- Connection
- FlowPermission
context_file: json-ld/microsoft-power-automate-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-automate/refs/heads/main/json-ld/microsoft-power-automate-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Power Automate Management Api from Microsoft Power Automate.
layout: jsonld
name: Microsoft Power Automate Management Api Context
namespaces:
- prefix: mpa
  uri: https://api.flow.microsoft.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: lastModifiedTime
  type: dateTime
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: environmentSku
  type: string
- container: ''
  name: isDefault
  type: boolean
- container: ''
  name: flowTriggerUri
  type: reference
- container: ''
  name: iconUri
  type: reference
- container: ''
  name: tier
  type: string
- container: ''
  name: isCustomApi
  type: boolean
- container: ''
  name: email
  type: string
property_count: 17
provider_name: Microsoft Power Automate
provider_slug: microsoft-power-automate
slug: microsoft-power-automate-management-api-context
source_filename: microsoft-power-automate-management-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mpa\": \"https://api.flow.microsoft.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Flow\": \"mpa:Flow\",\n    \"Environment\": \"mpa:Environment\",\n    \"FlowRun\": \"mpa:FlowRun\",\n    \"Connector\": \"mpa:Connector\",\n    \"Connection\": \"mpa:Connection\",\n    \"FlowPermission\": \"mpa:FlowPermission\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"mpa:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"mpa:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTime\"\
  : {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startTime\": {\n      \"@id\": \"mpa:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"mpa:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"mpa:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"mpa:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentSku\": {\n      \"@id\": \"mpa:environmentSku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDefault\": {\n      \"@id\": \"mpa:isDefault\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"flowTriggerUri\": {\n      \"@id\": \"mpa:flowTriggerUri\",\n      \"@type\": \"@id\"\n    },\n    \"iconUri\": {\n      \"@id\": \"mpa:iconUri\",\n      \"@type\": \"@id\"\n    },\n    \"tier\": {\n      \"@id\": \"mpa:tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCustomApi\": {\n      \"@id\": \"mpa:isCustomApi\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-power-automate/refs/heads/main/json-ld/microsoft-power-automate-management-api-context.jsonld
tags:
- Automation
- Business Process
- Integration
- Low-Code
- Microsoft
- Power Platform
- RPA
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
