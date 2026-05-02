---
api_specs:
- filename: jentic-api-openapi.yml
  format: yaml
  label: Jentic
  slug: jentic
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/jentic/refs/heads/main/openapi/jentic-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/jentic-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/jentic/refs/heads/main/json-ld/jentic-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Jentic from Jentic.
layout: jsonld
name: Jentic Context
namespaces:
- prefix: jentic
  uri: https://jentic.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Operation
  type: ''
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: Credential
  type: ''
- container: ''
  name: SearchResult
  type: ''
- container: ''
  name: ExecutionResult
  type: ''
property_count: 6
provider_name: Jentic
provider_slug: jentic
slug: jentic-context
source_filename: jentic-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"jentic\": \"https://jentic.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Agent\": {\n      \"@id\": \"jentic:Agent\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"apiKey\": \"jentic:apiKey\",\n        \"allowedApis\": {\n          \"@id\": \"jentic:allowedApis\",\n          \"@container\": \"@set\"\n        },\n        \"allowedWorkflows\": {\n          \"@id\": \"jentic:allowedWorkflows\",\n          \"@container\": \"@set\"\n        },\n        \"credentials\": {\n          \"@id\": \"jentic:credentials\",\n          \"@container\": \"@set\"\n        },\n        \"rateLimit\": \"jentic:rateLimit\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\"\
  : {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Operation\": {\n      \"@id\": \"jentic:Operation\",\n      \"@context\": {\n        \"uuid\": \"jentic:uuid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"operationType\": \"jentic:operationType\",\n        \"apiName\": \"jentic:apiName\",\n        \"method\": \"jentic:httpMethod\",\n        \"path\": {\n          \"@id\": \"jentic:path\",\n          \"@type\": \"@id\"\n        },\n        \"inputs\": \"jentic:inputs\",\n        \"authRequired\": \"jentic:authRequired\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Workflow\": {\n      \"@id\": \"jentic:Workflow\",\n      \"@context\": {\n        \"uuid\": \"jentic:uuid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"steps\"\
  : {\n          \"@id\": \"jentic:steps\",\n          \"@container\": \"@list\"\n        },\n        \"apiName\": \"jentic:apiName\"\n      }\n    },\n\n    \"Credential\": {\n      \"@id\": \"jentic:Credential\",\n      \"@context\": {\n        \"apiName\": \"jentic:apiName\",\n        \"credentialType\": \"jentic:credentialType\",\n        \"credentialId\": \"jentic:credentialId\",\n        \"status\": \"jentic:status\"\n      }\n    },\n\n    \"SearchResult\": {\n      \"@id\": \"jentic:SearchResult\",\n      \"@context\": {\n        \"uuid\": \"jentic:uuid\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"score\": \"jentic:relevanceScore\",\n        \"resultType\": \"jentic:resultType\",\n        \"apiName\": \"jentic:apiName\"\n      }\n    },\n\n    \"ExecutionResult\": {\n      \"@id\": \"jentic:ExecutionResult\",\n      \"@context\": {\n        \"executionId\": \"jentic:executionId\",\n        \"status\": \"jentic:executionStatus\"\
  ,\n        \"output\": \"jentic:output\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/jentic/refs/heads/main/json-ld/jentic-context.jsonld
tags:
- AI Agents
- Arazzo
- Integrations
- MCP
- OpenAPI
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
