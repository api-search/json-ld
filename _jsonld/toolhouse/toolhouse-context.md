---
api_specs:
- filename: toolhouse-openapi-original.yml
  format: yaml
  label: Toolhouse Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/openapi/toolhouse-openapi-original.yml
class_count: 0
classes: []
context_file: json-ld/toolhouse-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/json-ld/toolhouse-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Toolhouse from Toolhouse.
layout: jsonld
name: Toolhouse Context
namespaces:
- prefix: toolhouse
  uri: https://toolhouse.ai/ns/
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
  name: AgentRun
  type: ''
- container: ''
  name: Tool
  type: ''
- container: ''
  name: ToolExecution
  type: ''
- container: ''
  name: Bundle
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: ApiKey
  type: ''
- container: ''
  name: UserProfile
  type: ''
- container: ''
  name: KeyValueEntry
  type: ''
- container: ''
  name: McpServer
  type: ''
property_count: 10
provider_name: Toolhouse
provider_slug: toolhouse
slug: toolhouse-context
source_filename: toolhouse-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"toolhouse\": \"https://toolhouse.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Agent\": {\n      \"@id\": \"toolhouse:Agent\",\n      \"@context\": {\n        \"agentId\": \"toolhouse:agentId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"slug\": \"toolhouse:slug\",\n        \"model\": \"toolhouse:model\",\n        \"systemPrompt\": \"toolhouse:systemPrompt\",\n        \"tools\": {\n          \"@id\": \"toolhouse:tools\",\n          \"@container\": \"@set\"\n        },\n        \"bundles\": {\n          \"@id\": \"toolhouse:bundles\",\n          \"@container\": \"@set\"\n        },\n        \"files\": {\n          \"@id\": \"toolhouse:files\",\n          \"@container\": \"@set\"\n        },\n        \"schedules\": {\n          \"@id\": \"toolhouse:schedules\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"isPublic\": \"toolhouse:isPublic\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AgentRun\": {\n      \"@id\": \"toolhouse:AgentRun\",\n      \"@context\": {\n        \"runId\": \"toolhouse:runId\",\n        \"agentId\": \"toolhouse:agentId\",\n        \"status\": \"toolhouse:executionStatus\",\n        \"logs\": {\n          \"@id\": \"toolhouse:logs\",\n          \"@container\": \"@list\"\n        },\n        \"mcpServerLogs\": {\n          \"@id\": \"toolhouse:mcpServerLogs\",\n          \"@container\": \"@list\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Tool\": {\n      \"@id\": \"toolhouse:Tool\"\
  ,\n      \"@context\": {\n        \"toolId\": \"toolhouse:toolId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"toolName\": \"toolhouse:toolName\",\n        \"category\": \"schema:category\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"inputs\": \"toolhouse:inputs\",\n        \"outputs\": \"toolhouse:outputs\"\n      }\n    },\n\n    \"ToolExecution\": {\n      \"@id\": \"toolhouse:ToolExecution\",\n      \"@context\": {\n        \"executionId\": \"toolhouse:executionId\",\n        \"toolName\": \"toolhouse:toolName\",\n        \"status\": \"toolhouse:executionStatus\",\n        \"result\": \"toolhouse:result\",\n        \"creditsUsed\": \"toolhouse:creditsUsed\",\n        \"executedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Bundle\": {\n      \"@id\": \"toolhouse:Bundle\",\n \
  \     \"@context\": {\n        \"bundleId\": \"toolhouse:bundleId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"tools\": {\n          \"@id\": \"toolhouse:tools\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"toolhouse:Schedule\",\n      \"@context\": {\n        \"scheduleId\": \"toolhouse:scheduleId\",\n        \"agentId\": \"toolhouse:agentId\",\n        \"cronExpression\": \"toolhouse:cronExpression\",\n        \"isActive\": \"toolhouse:isActive\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiKey\": {\n      \"@id\": \"toolhouse:ApiKey\",\n      \"@context\": {\n        \"apiKeyId\": \"toolhouse:apiKeyId\",\n        \"name\": \"schema:name\",\n        \"isDefault\": \"toolhouse:isDefault\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\"\
  : \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"UserProfile\": {\n      \"@id\": \"toolhouse:UserProfile\",\n      \"@context\": {\n        \"userId\": \"toolhouse:userId\",\n        \"email\": \"schema:email\",\n        \"credits\": \"toolhouse:credits\",\n        \"tier\": \"toolhouse:tier\",\n        \"billing\": \"toolhouse:billing\"\n      }\n    },\n\n    \"KeyValueEntry\": {\n      \"@id\": \"toolhouse:KeyValueEntry\",\n      \"@context\": {\n        \"key\": \"toolhouse:key\",\n        \"value\": \"toolhouse:value\"\n      }\n    },\n\n    \"McpServer\": {\n      \"@id\": \"toolhouse:McpServer\",\n      \"@context\": {\n        \"serverId\": \"toolhouse:serverId\",\n        \"name\": \"schema:name\",\n        \"connections\": {\n          \"@id\": \"toolhouse:connections\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/toolhouse/refs/heads/main/json-ld/toolhouse-context.jsonld
tags:
- Agent Infrastructure
- AI Agents
- Backend as a Service
- Tools
- JSON-LD
- Linked Data
- Semantic Web
---
