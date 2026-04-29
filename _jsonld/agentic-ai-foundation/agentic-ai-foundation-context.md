---
class_count: 5
classes:
- MCPTool
- MCPResource
- name
- description
- version
context_file: json-ld/agentic-ai-foundation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/json-ld/agentic-ai-foundation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agentic Ai Foundation from Agentic AI Foundation.
layout: jsonld
name: Agentic Ai Foundation Context
namespaces:
- prefix: aaif
  uri: https://aaif.foundation/schema/
- prefix: mcp
  uri: https://modelcontextprotocol.io/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: uri
  type: reference
- container: ''
  name: mimeType
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: inputSchema
  type: reference
- container: ''
  name: annotations
  type: reference
- container: ''
  name: readOnly
  type: boolean
- container: ''
  name: destructive
  type: boolean
property_count: 7
provider_name: Agentic AI Foundation
provider_slug: agentic-ai-foundation
slug: agentic-ai-foundation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aaif\": \"https://aaif.foundation/schema/\",\n    \"mcp\": \"https://modelcontextprotocol.io/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"MCPTool\": \"mcp:Tool\",\n    \"MCPResource\": \"mcp:Resource\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n\n    \"uri\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"mimeType\": {\n      \"@id\": \"schema:encodingFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"inputSchema\": {\n      \"@id\": \"mcp:input_schema\",\n      \"@type\": \"@id\"\n    },\n    \"annotations\": {\n      \"@id\": \"mcp:annotations\",\n      \"@type\": \"@id\"\n    },\n    \"readOnly\"\
  : {\n      \"@id\": \"mcp:read_only\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"destructive\": {\n      \"@id\": \"mcp:destructive\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agentic-ai-foundation/refs/heads/main/json-ld/agentic-ai-foundation-context.jsonld
tags:
- AI Agents
- Linux Foundation
- Open Source
- Standards
- MCP
- Agentic AI
- Interoperability
- JSON-LD
- Linked Data
- Semantic Web
---
