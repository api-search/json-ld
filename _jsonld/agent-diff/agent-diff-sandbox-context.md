---
class_count: 6
classes:
- DiffEntry
- Sandbox
- createdAt
- SandboxCreateRequest
- DiffList
- SandboxList
context_file: json-ld/agent-diff-sandbox-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agent-diff/refs/heads/main/json-ld/agent-diff-sandbox-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agent Diff Sandbox from Agent Diff.
layout: jsonld
name: Agent Diff Sandbox Context
namespaces:
- prefix: agent-diff
  uri: https://agent-diff.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: sandboxId
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: set
  name: changes
  type: reference
- container: ''
  name: api
  type: string
- container: ''
  name: scenario
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: baseUrl
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: seedData
  type: reference
- container: ''
  name: ttl
  type: integer
- container: set
  name: diffs
  type: string
- container: ''
  name: total
  type: integer
- container: set
  name: sandboxes
  type: string
property_count: 15
provider_name: Agent Diff
provider_slug: agent-diff
slug: agent-diff-sandbox-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"agent-diff\": \"https://agent-diff.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DiffEntry\": \"agent-diff:DiffEntry\",\n    \"id\": {\n      \"@id\": \"agent-diff:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sandboxId\": {\n      \"@id\": \"agent-diff:sandbox_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"agent-diff:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"agent-diff:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"changes\": {\n      \"@id\": \"agent-diff:changes\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Sandbox\": \"agent-diff:Sandbox\",\n    \"api\": {\n      \"@id\": \"agent-diff:api\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scenario\": {\n  \
  \    \"@id\": \"agent-diff:scenario\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"agent-diff:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"agent-diff:base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"expiresAt\": {\n      \"@id\": \"agent-diff:expires_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"SandboxCreateRequest\": \"agent-diff:SandboxCreateRequest\",\n    \"seedData\": {\n      \"@id\": \"agent-diff:seed_data\",\n      \"@type\": \"@id\"\n    },\n    \"ttl\": {\n      \"@id\": \"agent-diff:ttl\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"DiffList\": \"agent-diff:DiffList\",\n    \"diffs\": {\n      \"@id\": \"agent-diff:diffs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"agent-diff:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SandboxList\": \"agent-diff:SandboxList\"\
  ,\n    \"sandboxes\": {\n      \"@id\": \"agent-diff:sandboxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agent-diff/refs/heads/main/json-ld/agent-diff-sandbox-context.jsonld
tags:
- API Testing
- AI Agents
- Sandboxing
- API Diffing
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
