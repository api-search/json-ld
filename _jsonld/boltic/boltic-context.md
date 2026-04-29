---
api_specs:
- filename: boltic-gateway-api-openapi.yml
  format: yaml
  label: Boltic Gateway API
  slug: gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-gateway-api-openapi.yml
- filename: boltic-workflow-api-openapi.yml
  format: yaml
  label: Boltic Workflow API
  slug: workflow-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-workflow-api-openapi.yml
- filename: boltic-tables-api-openapi.yml
  format: yaml
  label: Boltic Tables API
  slug: tables-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-tables-api-openapi.yml
- filename: boltic-pipes-api-openapi.yml
  format: yaml
  label: Boltic Pipes API
  slug: pipes-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-pipes-api-openapi.yml
- filename: boltic-streams-api-openapi.yml
  format: yaml
  label: Boltic Streams API
  slug: streams-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/openapi/boltic-streams-api-openapi.yml
class_count: 36
classes:
- id
- type
- Workflow
- Table
- Pipe
- Route
- StreamEvent
- Service
- Plugin
- Consumer
- Execution
- SyncRun
- StreamSource
- name
- description
- status
- trigger
- nodes
- columns
- source
- destination
- schedule
- paths
- methods
- tags
- email
- userId
- anonymousId
- executionCount
- rowsSynced
- rowCount
- duration
- config
- properties
- frequency
- cronExpression
context_file: json-ld/boltic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/json-ld/boltic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Boltic from Boltic.
layout: jsonld
name: Boltic Context
namespaces:
- prefix: boltic
  uri: https://www.boltic.io/ns/
properties:
- container: ''
  name: createdAt
  type: schema:DateTime
- container: ''
  name: updatedAt
  type: schema:DateTime
- container: ''
  name: serviceId
  type: reference
- container: ''
  name: workflowId
  type: reference
- container: ''
  name: pipeId
  type: reference
- container: ''
  name: sourceId
  type: reference
- container: ''
  name: integrationId
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: timestamp
  type: schema:DateTime
property_count: 9
provider_name: Boltic
provider_slug: boltic
slug: boltic-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"boltic\": \"https://www.boltic.io/ns/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Workflow\": \"boltic:Workflow\",\n    \"Table\": \"boltic:Table\",\n    \"Pipe\": \"boltic:Pipe\",\n    \"Route\": \"boltic:Route\",\n    \"StreamEvent\": \"boltic:StreamEvent\",\n    \"Service\": \"boltic:Service\",\n    \"Plugin\": \"boltic:Plugin\",\n    \"Consumer\": \"boltic:Consumer\",\n    \"Execution\": \"boltic:Execution\",\n    \"SyncRun\": \"boltic:SyncRun\",\n    \"StreamSource\": \"boltic:StreamSource\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"boltic:status\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"trigger\": \"boltic:trigger\",\n    \"nodes\": \"boltic:nodes\"\
  ,\n    \"columns\": \"boltic:columns\",\n    \"source\": \"boltic:source\",\n    \"destination\": \"boltic:destination\",\n    \"schedule\": \"boltic:schedule\",\n    \"paths\": \"boltic:paths\",\n    \"methods\": \"boltic:methods\",\n    \"serviceId\": {\n      \"@id\": \"boltic:serviceId\",\n      \"@type\": \"@id\"\n    },\n    \"workflowId\": {\n      \"@id\": \"boltic:workflowId\",\n      \"@type\": \"@id\"\n    },\n    \"pipeId\": {\n      \"@id\": \"boltic:pipeId\",\n      \"@type\": \"@id\"\n    },\n    \"sourceId\": {\n      \"@id\": \"boltic:sourceId\",\n      \"@type\": \"@id\"\n    },\n    \"integrationId\": {\n      \"@id\": \"boltic:integrationId\",\n      \"@type\": \"@id\"\n    },\n    \"tags\": \"schema:keywords\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"email\": \"schema:email\",\n    \"userId\": \"boltic:userId\",\n    \"anonymousId\": \"boltic:anonymousId\",\n    \"timestamp\": {\n      \"@id\": \"boltic:timestamp\",\n\
  \      \"@type\": \"schema:DateTime\"\n    },\n    \"executionCount\": \"boltic:executionCount\",\n    \"rowsSynced\": \"boltic:rowsSynced\",\n    \"rowCount\": \"boltic:rowCount\",\n    \"duration\": \"boltic:duration\",\n    \"config\": \"boltic:config\",\n    \"properties\": \"boltic:properties\",\n    \"frequency\": \"boltic:frequency\",\n    \"cronExpression\": \"boltic:cronExpression\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/boltic/refs/heads/main/json-ld/boltic-context.jsonld
tags:
- Automation
- DataSync
- Gateways
- NoCode
- Streaming
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
