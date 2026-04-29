---
class_count: 7
classes:
- Tool
- ToolCall
- ToolResult
- MCPServer
- name
- description
- version
context_file: json-ld/agent-skills-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-ld/agent-skills-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agent Skills from Agent Skills.
layout: jsonld
name: Agent Skills Context
namespaces:
- prefix: ask
  uri: https://api-evangelist.github.io/agent-skills/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: type
  type: string
- container: ''
  name: inputSchema
  type: reference
- container: ''
  name: input
  type: reference
- container: ''
  name: strict
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: toolUseId
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: isError
  type: boolean
- container: ''
  name: transport
  type: string
- container: set
  name: tools
  type: reference
- container: set
  name: resources
  type: reference
- container: set
  name: prompts
  type: reference
- container: ''
  name: uri
  type: reference
- container: ''
  name: mimeType
  type: string
- container: set
  name: required
  type: string
- container: ''
  name: properties
  type: reference
property_count: 16
provider_name: Agent Skills
provider_slug: agent-skills
slug: agent-skills-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ask\": \"https://api-evangelist.github.io/agent-skills/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Tool\": \"ask:Tool\",\n    \"ToolCall\": \"ask:ToolCall\",\n    \"ToolResult\": \"ask:ToolResult\",\n    \"MCPServer\": \"ask:MCPServer\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n\n    \"type\": {\n      \"@id\": \"ask:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputSchema\": {\n      \"@id\": \"ask:input_schema\",\n      \"@type\": \"@id\"\n    },\n    \"input\": {\n      \"@id\": \"ask:input\",\n      \"@type\": \"@id\"\n    },\n    \"strict\": {\n      \"@id\": \"ask:strict\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"toolUseId\": {\n      \"@id\": \"ask:tool_use_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"ask:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isError\": {\n      \"@id\": \"ask:is_error\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"transport\": {\n      \"@id\": \"ask:transport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tools\": {\n      \"@id\": \"ask:tools\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"resources\": {\n      \"@id\": \"ask:resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"prompts\": {\n      \"@id\": \"ask:prompts\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"uri\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"mimeType\": {\n      \"@id\": \"ask:mime_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"ask:required\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"ask:properties\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agent-skills/refs/heads/main/json-ld/agent-skills-context.jsonld
tags:
- Agent Skills
- AI Agents
- Tool Use
- Function Calling
- MCP
- Agentic AI
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
