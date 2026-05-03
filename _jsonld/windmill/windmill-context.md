---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Windmill API
  slug: windmill-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/windmill-labs/windmill/main/backend/windmill-api/openapi.yaml
class_count: 17
classes:
- Script
- Flow
- Job
- CompletedJob
- QueuedJob
- Schedule
- Workspace
- Resource
- Variable
- Worker
- Trigger
- App
- SoftwareApplication
- name
- description
- url
- version
context_file: json-ld/windmill-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/windmill/refs/heads/main/json-ld/windmill-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Windmill from Windmill.
layout: jsonld
name: Windmill Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: windmill
  uri: https://windmill.dev/vocab#
properties:
- container: ''
  name: path
  type: string
- container: ''
  name: workspaceId
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: jobStatus
  type: string
- container: ''
  name: durationMs
  type: integer
- container: ''
  name: scheduleExpression
  type: string
- container: ''
  name: isFlow
  type: boolean
- container: ''
  name: isSecret
  type: boolean
- container: ''
  name: resourceType
  type: string
- container: ''
  name: scriptPath
  type: string
- container: ''
  name: args
  type: '@json'
- container: ''
  name: result
  type: '@json'
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
property_count: 16
provider_name: Windmill
provider_slug: windmill
slug: windmill-context
source_filename: windmill-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"windmill\": \"https://windmill.dev/vocab#\",\n\n    \"Script\": \"windmill:Script\",\n    \"Flow\": \"windmill:Flow\",\n    \"Job\": \"windmill:Job\",\n    \"CompletedJob\": \"windmill:CompletedJob\",\n    \"QueuedJob\": \"windmill:QueuedJob\",\n    \"Schedule\": \"windmill:Schedule\",\n    \"Workspace\": \"windmill:Workspace\",\n    \"Resource\": \"windmill:Resource\",\n    \"Variable\": \"windmill:Variable\",\n    \"Worker\": \"windmill:Worker\",\n    \"Trigger\": \"windmill:Trigger\",\n    \"App\": \"windmill:App\",\n\n    \"path\": {\n      \"@id\": \"windmill:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workspaceId\": {\n      \"@id\": \"windmill:workspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"windmill:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\"\
  : {\n      \"@id\": \"windmill:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"windmill:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobStatus\": {\n      \"@id\": \"windmill:jobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"durationMs\": {\n      \"@id\": \"windmill:durationMs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scheduleExpression\": {\n      \"@id\": \"windmill:scheduleExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isFlow\": {\n      \"@id\": \"windmill:isFlow\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isSecret\": {\n      \"@id\": \"windmill:isSecret\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resourceType\": {\n      \"@id\": \"windmill:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scriptPath\": {\n      \"@id\": \"windmill:scriptPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"args\": {\n      \"@id\": \"windmill:args\",\n      \"@type\": \"@json\"\
  \n    },\n    \"result\": {\n      \"@id\": \"windmill:result\",\n      \"@type\": \"@json\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"windmill:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/windmill/refs/heads/main/json-ld/windmill-context.jsonld
tags:
- Automation
- Internal Tools
- Open Source
- ProCode API Composition
- Scripts
- Webhooks
- Workflow Engine
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
