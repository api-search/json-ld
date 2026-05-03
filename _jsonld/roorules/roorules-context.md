---
class_count: 0
classes: []
context_file: json-ld/roorules-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roorules/refs/heads/main/json-ld/roorules-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roorules from .Roorules.
layout: jsonld
name: Roorules Context
namespaces:
- prefix: roorules
  uri: https://roocode.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: RooCode
  type: ''
- container: ''
  name: RooruleFile
  type: ''
- container: ''
  name: Mode
  type: ''
- container: ''
  name: ApiConfigurationProfile
  type: ''
- container: ''
  name: McpServer
  type: ''
- container: ''
  name: Provider
  type: ''
property_count: 6
provider_name: .Roorules
provider_slug: roorules
slug: roorules-context
source_filename: roorules-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roorules\": \"https://roocode.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"RooCode\": {\n      \"@id\": \"roorules:RooCode\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"version\": { \"@id\": \"schema:version\" },\n        \"url\": { \"@id\": \"schema:url\" },\n        \"license\": { \"@id\": \"dcterms:license\" },\n        \"programmingLanguage\": { \"@id\": \"schema:programmingLanguage\" }\n      }\n    },\n\n    \"RooruleFile\": {\n      \"@id\": \"roorules:RooruleFile\",\n      \"@context\": {\n        \"projectPath\": { \"@id\": \"roorules:projectPath\" },\n        \"rules\": { \"@id\": \"roorules:rules\" },\n        \"conventions\": { \"@id\": \"roorules:conventions\" },\n        \"guidelines\": {\
  \ \"@id\": \"roorules:guidelines\" }\n      }\n    },\n\n    \"Mode\": {\n      \"@id\": \"roorules:Mode\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"systemPrompt\": { \"@id\": \"roorules:systemPrompt\" },\n        \"allowedTools\": { \"@id\": \"roorules:allowedTools\" },\n        \"model\": { \"@id\": \"roorules:model\" }\n      }\n    },\n\n    \"ApiConfigurationProfile\": {\n      \"@id\": \"roorules:ApiConfigurationProfile\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"provider\": { \"@id\": \"roorules:provider\" },\n        \"model\": { \"@id\": \"roorules:model\" },\n        \"apiKey\": { \"@id\": \"roorules:apiKey\" }\n      }\n    },\n\n    \"McpServer\": {\n      \"@id\": \"roorules:McpServer\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n      \
  \  \"transport\": { \"@id\": \"roorules:transport\" },\n        \"tools\": { \"@id\": \"roorules:tools\" }\n      }\n    },\n\n    \"Provider\": {\n      \"@id\": \"roorules:Provider\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"baseUrl\": { \"@id\": \"schema:url\" },\n        \"models\": { \"@id\": \"roorules:models\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roorules/refs/heads/main/json-ld/roorules-context.jsonld
tags:
- AI Agents
- AI Copilot
- Coding Assistant
- Coding Standards
- Developer Workflow
- LLM
- MCP
- Roo Code
- VS Code
- JSON-LD
- Linked Data
- Semantic Web
---
