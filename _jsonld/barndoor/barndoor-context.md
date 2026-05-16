---
api_specs:
- filename: barndoor-openapi.yml
  format: yaml
  label: Barndoor Platform API
  slug: platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/openapi/barndoor-openapi.yml
class_count: 3
classes:
- name
- description
- url
context_file: json-ld/barndoor-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/json-ld/barndoor-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Barndoor from Barndoor.
layout: jsonld
name: Barndoor Context
namespaces:
- prefix: barndoor
  uri: https://barndoor.ai/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AIAgent
  type: reference
- container: ''
  name: MCPServer
  type: reference
- container: ''
  name: AccessPolicy
  type: reference
- container: ''
  name: ToolCall
  type: reference
- container: ''
  name: AuditEntry
  type: reference
- container: ''
  name: Connection
  type: reference
- container: ''
  name: agentId
  type: string
- container: ''
  name: mcpServerId
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: allowed
  type: boolean
- container: ''
  name: toolName
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: userId
  type: string
- container: ''
  name: organizationId
  type: string
property_count: 14
provider_name: Barndoor
provider_slug: barndoor
slug: barndoor-context
source_filename: barndoor-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"barndoor\": \"https://barndoor.ai/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AIAgent\": {\n      \"@id\": \"barndoor:AIAgent\",\n      \"@type\": \"@id\"\n    },\n    \"MCPServer\": {\n      \"@id\": \"barndoor:MCPServer\",\n      \"@type\": \"@id\"\n    },\n    \"AccessPolicy\": {\n      \"@id\": \"barndoor:AccessPolicy\",\n      \"@type\": \"@id\"\n    },\n    \"ToolCall\": {\n      \"@id\": \"barndoor:ToolCall\",\n      \"@type\": \"@id\"\n    },\n    \"AuditEntry\": {\n      \"@id\": \"barndoor:AuditEntry\",\n      \"@type\": \"@id\"\n    },\n    \"Connection\": {\n      \"@id\": \"barndoor:Connection\",\n      \"@type\": \"@id\"\n    },\n    \"agentId\": {\n      \"@id\": \"barndoor:agentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mcpServerId\": {\n      \"@id\": \"barndoor:mcpServerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\"\
  : {\n      \"@id\": \"barndoor:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allowed\": {\n      \"@id\": \"barndoor:allowed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"toolName\": {\n      \"@id\": \"barndoor:toolName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"barndoor:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"userId\": {\n      \"@id\": \"barndoor:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationId\": {\n      \"@id\": \"barndoor:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/barndoor/refs/heads/main/json-ld/barndoor-context.jsonld
tags:
- AI Agents
- AI Governance
- Agentic AI
- MCP
- Model Context Protocol
- Policy Enforcement
- OAuth
- Identity
- Security
- Audit
- Control Plane
- JSON-LD
- Linked Data
- Semantic Web
---
