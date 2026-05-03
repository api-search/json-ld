---
api_specs:
- filename: smithery-openapi.json
  format: json
  label: Smithery Registry API
  slug: registry-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/openapi/smithery-openapi.json
class_count: 25
classes:
- Server
- Skill
- Connection
- Namespace
- qualifiedName
- displayName
- description
- iconUrl
- isVerified
- useCount
- namespace
- tools
- connections
- slug
- githubUrl
- tags
- releases
- releaseId
- createdAt
- updatedAt
- mcpVersion
- toolName
- inputSchema
- scopes
- token
context_file: json-ld/smithery-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/json-ld/smithery-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Smithery from Smithery.
layout: jsonld
name: Smithery Context
namespaces:
- prefix: smithery
  uri: https://api.smithery.ai/vocab#
properties: []
property_count: 0
provider_name: Smithery
provider_slug: smithery
slug: smithery-context
source_filename: smithery-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"smithery\": \"https://api.smithery.ai/vocab#\",\n    \"Server\": \"SoftwareApplication\",\n    \"Skill\": \"CreativeWork\",\n    \"Connection\": \"smithery:Connection\",\n    \"Namespace\": \"Organization\",\n    \"qualifiedName\": \"identifier\",\n    \"displayName\": \"name\",\n    \"description\": \"description\",\n    \"iconUrl\": \"image\",\n    \"isVerified\": \"smithery:isVerified\",\n    \"useCount\": \"interactionCount\",\n    \"namespace\": \"smithery:namespace\",\n    \"tools\": \"smithery:tools\",\n    \"connections\": \"smithery:connections\",\n    \"slug\": \"smithery:slug\",\n    \"githubUrl\": \"codeRepository\",\n    \"tags\": \"keywords\",\n    \"releases\": \"smithery:releases\",\n    \"releaseId\": \"smithery:releaseId\",\n    \"createdAt\": \"dateCreated\",\n    \"updatedAt\": \"dateModified\",\n    \"mcpVersion\": \"smithery:mcpVersion\",\n    \"toolName\": \"smithery:toolName\",\n \
  \   \"inputSchema\": \"smithery:inputSchema\",\n    \"scopes\": \"smithery:scopes\",\n    \"token\": \"smithery:token\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/smithery/refs/heads/main/json-ld/smithery-context.jsonld
tags:
- Artificial Intelligence
- Large Language Models
- MCP
- Model Context Protocol
- AI Agents
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
