---
api_specs:
- filename: restate-admin-api.yml
  format: yaml
  label: Restate Admin API
  slug: restate-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/openapi/restate-admin-api.yml
class_count: 32
classes:
- Deployment
- Service
- Handler
- Invocation
- Subscription
- VirtualObject
- RestateWorkflow
- deploymentId
- deploymentUri
- protocolType
- handlerType
- invocationId
- invocationTarget
- invocationStatus
- retryCount
- traceId
- durableExecution
- exactlyOnce
- journalEntry
- kafkaSource
- kafkaSink
- SoftwareApplication
- name
- description
- url
- version
- dateCreated
- dateModified
- Organization
- SoftwareSourceCode
- programmingLanguage
- codeRepository
context_file: json-ld/restate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/json-ld/restate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Restate from Restate.
layout: jsonld
name: Restate Context
namespaces:
- prefix: restate
  uri: https://restate.dev/vocab#
properties: []
property_count: 0
provider_name: Restate
provider_slug: restate
slug: restate-context
source_filename: restate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"restate\": \"https://restate.dev/vocab#\",\n    \"Deployment\": \"restate:Deployment\",\n    \"Service\": \"restate:Service\",\n    \"Handler\": \"restate:Handler\",\n    \"Invocation\": \"restate:Invocation\",\n    \"Subscription\": \"restate:Subscription\",\n    \"VirtualObject\": \"restate:VirtualObject\",\n    \"RestateWorkflow\": \"restate:Workflow\",\n    \"deploymentId\": \"restate:deploymentId\",\n    \"deploymentUri\": \"restate:deploymentUri\",\n    \"protocolType\": \"restate:protocolType\",\n    \"handlerType\": \"restate:handlerType\",\n    \"invocationId\": \"restate:invocationId\",\n    \"invocationTarget\": \"restate:invocationTarget\",\n    \"invocationStatus\": \"restate:invocationStatus\",\n    \"retryCount\": \"restate:retryCount\",\n    \"traceId\": \"restate:traceId\",\n    \"durableExecution\": \"restate:durableExecution\",\n    \"exactlyOnce\": \"restate:exactlyOnce\",\n    \"journalEntry\"\
  : \"restate:journalEntry\",\n    \"kafkaSource\": \"restate:kafkaSource\",\n    \"kafkaSink\": \"restate:kafkaSink\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"Organization\": \"schema:Organization\",\n    \"SoftwareSourceCode\": \"schema:SoftwareSourceCode\",\n    \"programmingLanguage\": \"schema:programmingLanguage\",\n    \"codeRepository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/restate/refs/heads/main/json-ld/restate-context.jsonld
tags:
- Durable Execution
- Workflows
- Microservices
- Orchestration
- Distributed Systems
- JSON-LD
- Linked Data
- Semantic Web
---
