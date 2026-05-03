---
api_specs:
- filename: relay-app-openapi.yml
  format: yaml
  label: Relay App Automation API
  slug: relay-app-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/openapi/relay-app-openapi.yml
class_count: 0
classes: []
context_file: json-ld/relay-app-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-ld/relay-app-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Relay App from Relay App.
layout: jsonld
name: Relay App Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: relay
  uri: https://relay.app/vocab/
properties:
- container: ''
  name: Workflow
  type: reference
- container: ''
  name: WorkflowRun
  type: reference
- container: ''
  name: WebhookTrigger
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: triggerType
  type: ''
- container: ''
  name: workflowId
  type: ''
- container: ''
  name: runId
  type: ''
- container: ''
  name: webhookId
  type: ''
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: error
  type: ''
- container: ''
  name: inputData
  type: ''
- container: set
  name: runs
  type: ''
- container: ''
  name: payload
  type: ''
- container: ''
  name: deduplicationKey
  type: ''
- container: ''
  name: comment
  type: ''
- container: ''
  name: inputs
  type: ''
property_count: 22
provider_name: Relay App
provider_slug: relay-app
slug: relay-app-context
source_filename: relay-app-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"relay\": \"https://relay.app/vocab/\",\n    \"Workflow\": {\n      \"@id\": \"relay:Workflow\",\n      \"@type\": \"@id\"\n    },\n    \"WorkflowRun\": {\n      \"@id\": \"relay:WorkflowRun\",\n      \"@type\": \"@id\"\n    },\n    \"WebhookTrigger\": {\n      \"@id\": \"relay:WebhookTrigger\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"status\": {\n      \"@id\": \"relay:status\"\n    },\n    \"triggerType\": {\n      \"@id\": \"relay:triggerType\"\n    },\n    \"workflowId\": {\n      \"@id\": \"relay:workflowId\"\n    },\n    \"runId\": {\n      \"@id\": \"relay:runId\"\n    },\n    \"webhookId\": {\n      \"@id\": \"relay:webhookId\"\n    },\n\
  \    \"startedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"error\": {\n      \"@id\": \"relay:errorMessage\"\n    },\n    \"inputData\": {\n      \"@id\": \"relay:inputData\"\n    },\n    \"runs\": {\n      \"@id\": \"relay:hasRun\",\n      \"@container\": \"@set\"\n    },\n    \"payload\": {\n      \"@id\": \"relay:webhookPayload\"\n    },\n    \"deduplicationKey\": {\n      \"@id\": \"relay:deduplicationKey\"\n    },\n    \"comment\": {\n      \"@id\": \"schema:comment\"\n    },\n    \"inputs\": {\n      \"@id\": \"relay:approvalInputs\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/relay-app/refs/heads/main/json-ld/relay-app-context.jsonld
tags:
- Automation
- Workflow
- Integration
- No-Code
- AI
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
