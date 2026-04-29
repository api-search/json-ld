---
api_specs:
- filename: cflow-openapi.yml
  format: yaml
  label: Cflow Workflow API
  slug: cflow
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/openapi/cflow-openapi.yml
class_count: 3
classes:
- name
- description
- email
context_file: json-ld/cflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/json-ld/cflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cflow from Cflow.
layout: jsonld
name: Cflow Context
namespaces:
- prefix: cflow
  uri: https://us.cflowapps.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: workflowId
  type: string
- container: ''
  name: stageId
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: currentStage
  type: string
- container: ''
  name: submittedBy
  type: string
- container: ''
  name: fields
  type: '@json'
- container: ''
  name: stages
  type: '@json'
- container: ''
  name: reviewers
  type: '@json'
- container: ''
  name: order
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: permissions
  type: '@json'
- container: ''
  name: username
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 15
provider_name: Cflow
provider_slug: cflow
slug: cflow-context
source_filename: cflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"cflow\": \"https://us.cflowapps.com/\",\n    \"workflowId\": {\n      \"@id\": \"cflow:workflowId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stageId\": {\n      \"@id\": \"cflow:stageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"cflow:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentStage\": {\n      \"@id\": \"cflow:currentStage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedBy\": {\n      \"@id\": \"cflow:submittedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fields\": {\n      \"@id\": \"cflow:fields\",\n      \"@type\": \"@json\"\n    },\n    \"stages\": {\n      \"@id\": \"cflow:stages\",\n      \"@type\": \"@json\"\n    },\n    \"reviewers\": {\n      \"@id\": \"cflow:reviewers\",\n      \"@type\": \"@json\"\n    },\n    \"order\": {\n      \"@id\": \"cflow:order\",\n      \"@type\": \"xsd:integer\"\n    },\n  \
  \  \"status\": {\n      \"@id\": \"cflow:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"cflow:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"cflow:permissions\",\n      \"@type\": \"@json\"\n    },\n    \"username\": {\n      \"@id\": \"cflow:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"cflow:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"cflow:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"email\": \"schema:email\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cflow/refs/heads/main/json-ld/cflow-context.jsonld
tags:
- Automations
- Business Process Automation
- Integrations
- No-Code
- Platform
- Protocols
- Rules
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
