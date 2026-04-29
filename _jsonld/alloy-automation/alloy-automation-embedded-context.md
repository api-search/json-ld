---
class_count: 0
classes: []
context_file: json-ld/alloy-automation-embedded-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/json-ld/alloy-automation-embedded-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alloy Automation Embedded from Alloy Automation.
layout: jsonld
name: Alloy Automation Embedded Context
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
  name: fullName
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: token
  type: string
- container: ''
  name: integrationId
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
  name: installed
  type: boolean
- container: list
  name: integrations
  type: ''
- container: ''
  name: workflowId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: executedAt
  type: dateTime
- container: ''
  name: duration
  type: integer
- container: ''
  name: errorId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: occurredAt
  type: dateTime
- container: ''
  name: success
  type: boolean
- container: ''
  name: event
  type: string
- container: ''
  name: data
  type: ''
- container: ''
  name: error
  type: string
- container: ''
  name: version
  type: string
property_count: 23
provider_name: Alloy Automation
provider_slug: alloy-automation
slug: alloy-automation-embedded-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"alloy\": \"https://runalloy.com/vocab/\",\n    \"userId\": {\"@id\": \"alloy:userId\", \"@type\": \"xsd:string\"},\n    \"username\": {\"@id\": \"schema:identifier\", \"@type\": \"xsd:string\"},\n    \"fullName\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"createdAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"token\": {\"@id\": \"alloy:jwtToken\", \"@type\": \"xsd:string\"},\n    \"integrationId\": {\"@id\": \"alloy:integrationId\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"category\": {\"@id\": \"schema:category\", \"@type\": \"xsd:string\"},\n    \"iconUrl\": {\"@id\": \"schema:image\", \"@type\": \"@id\"},\n    \"installed\": {\"@id\": \"alloy:installed\", \"@type\": \"xsd:boolean\"},\n    \"integrations\": {\"@id\"\
  : \"alloy:integrations\", \"@container\": \"@list\"},\n    \"workflowId\": {\"@id\": \"alloy:workflowId\", \"@type\": \"xsd:string\"},\n    \"status\": {\"@id\": \"schema:status\", \"@type\": \"xsd:string\"},\n    \"executedAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"duration\": {\"@id\": \"alloy:durationMs\", \"@type\": \"xsd:integer\"},\n    \"errorId\": {\"@id\": \"alloy:errorId\", \"@type\": \"xsd:string\"},\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"occurredAt\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"success\": {\"@id\": \"alloy:success\", \"@type\": \"xsd:boolean\"},\n    \"event\": {\"@id\": \"alloy:eventName\", \"@type\": \"xsd:string\"},\n    \"data\": {\"@id\": \"alloy:data\"},\n    \"error\": {\"@id\": \"alloy:errorCode\", \"@type\": \"xsd:string\"},\n    \"version\": {\"@id\": \"schema:version\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alloy-automation/refs/heads/main/json-ld/alloy-automation-embedded-context.jsonld
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
