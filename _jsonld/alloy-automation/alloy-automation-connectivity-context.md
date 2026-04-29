---
api_specs:
- filename: alloy-automation-embedded.yaml
  format: yaml
  label: Alloy Automation Embedded API
  slug: embedded-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/openapi/alloy-automation-embedded.yaml
- filename: alloy-automation-connectivity.yaml
  format: yaml
  label: Alloy Automation Connectivity API
  slug: connectivity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/openapi/alloy-automation-connectivity.yaml
class_count: 0
classes: []
context_file: json-ld/alloy-automation-connectivity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/json-ld/alloy-automation-connectivity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alloy Automation Connectivity from Alloy Automation.
layout: jsonld
name: Alloy Automation Connectivity Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: alloy
  uri: https://runalloy.com/vocab/
properties:
- container: ''
  name: userId
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: token
  type: string
- container: ''
  name: connectorId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: iconUrl
  type: reference
- container: ''
  name: actionCount
  type: integer
- container: list
  name: connectors
  type: ''
- container: ''
  name: resourceId
  type: string
- container: ''
  name: description
  type: string
- container: list
  name: actions
  type: ''
- container: ''
  name: actionId
  type: string
- container: list
  name: parameters
  type: ''
- container: ''
  name: credentialId
  type: string
- container: ''
  name: authType
  type: string
- container: list
  name: requiredFields
  type: ''
- container: ''
  name: success
  type: boolean
- container: ''
  name: data
  type: ''
- container: ''
  name: error
  type: string
- container: ''
  name: message
  type: string
property_count: 22
provider_name: Alloy Automation
provider_slug: alloy-automation
slug: alloy-automation-connectivity-context
source_filename: alloy-automation-connectivity-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"alloy\": \"https://runalloy.com/vocab/\",\n    \"userId\": {\"@id\": \"alloy:userId\", \"@type\": \"xsd:string\"},\n    \"username\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"token\": {\"@id\": \"alloy:jwtToken\", \"@type\": \"xsd:string\"},\n    \"connectorId\": {\"@id\": \"alloy:connectorId\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"category\": {\"@id\": \"schema:category\", \"@type\": \"xsd:string\"},\n    \"iconUrl\": {\"@id\": \"schema:image\", \"@type\": \"@id\"},\n    \"actionCount\": {\"@id\": \"alloy:actionCount\", \"@type\": \"xsd:integer\"},\n    \"connectors\": {\"@id\": \"alloy:connectors\", \"@container\": \"@list\"},\n    \"resourceId\": {\"\
  @id\": \"alloy:resourceId\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"actions\": {\"@id\": \"alloy:actions\", \"@container\": \"@list\"},\n    \"actionId\": {\"@id\": \"alloy:actionId\", \"@type\": \"xsd:string\"},\n    \"parameters\": {\"@id\": \"alloy:parameters\", \"@container\": \"@list\"},\n    \"credentialId\": {\"@id\": \"alloy:credentialId\", \"@type\": \"xsd:string\"},\n    \"authType\": {\"@id\": \"alloy:authType\", \"@type\": \"xsd:string\"},\n    \"requiredFields\": {\"@id\": \"alloy:requiredFields\", \"@container\": \"@list\"},\n    \"success\": {\"@id\": \"alloy:success\", \"@type\": \"xsd:boolean\"},\n    \"data\": {\"@id\": \"alloy:data\"},\n    \"error\": {\"@id\": \"alloy:errorCode\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/json-ld/alloy-automation-connectivity-context.jsonld
tags:
- Automation
- Embedded Integrations
- Integrations
- iPaaS
- Unified API
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
