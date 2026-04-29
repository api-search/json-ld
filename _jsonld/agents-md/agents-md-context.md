---
class_count: 1
classes:
- AgentsMdFile
context_file: json-ld/agents-md-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/json-ld/agents-md-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Agents Md from AGENTS.md.
layout: jsonld
name: Agents Md Context
namespaces:
- prefix: amd
  uri: https://agents.md/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: filename
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: project_name
  type: string
- container: ''
  name: description
  type: string
- container: set
  name: build_commands
  type: reference
- container: set
  name: test_commands
  type: reference
- container: set
  name: lint_commands
  type: reference
- container: set
  name: coding_standards
  type: string
- container: set
  name: security_notes
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: command
  type: string
- container: ''
  name: created
  type: date
- container: ''
  name: modified
  type: date
property_count: 13
provider_name: AGENTS.md
provider_slug: agents-md
slug: agents-md-context
source_filename: agents-md-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amd\": \"https://agents.md/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"AgentsMdFile\": \"amd:AgentsMdFile\",\n\n    \"filename\": {\n      \"@id\": \"amd:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"amd:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"project_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"build_commands\": {\n      \"@id\": \"amd:build_commands\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"test_commands\": {\n      \"@id\": \"amd:test_commands\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"lint_commands\": {\n      \"@id\": \"\
  amd:lint_commands\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"coding_standards\": {\n      \"@id\": \"amd:coding_standards\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"security_notes\": {\n      \"@id\": \"amd:security_notes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"amd:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/agents-md/refs/heads/main/json-ld/agents-md-context.jsonld
tags:
- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- Open Standard
- Documentation
- JSON-LD
- Linked Data
- Semantic Web
---
