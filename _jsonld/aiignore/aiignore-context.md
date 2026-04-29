---
class_count: 4
classes:
- AIIgnoreRule
- AIIgnoreConfig
- ExclusionPattern
- AIToolCompatibility
context_file: json-ld/aiignore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aiignore/refs/heads/main/json-ld/aiignore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aiignore from .AIIgnore.
layout: jsonld
name: Aiignore Context
namespaces:
- prefix: aiignore
  uri: https://aiignore.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: pattern
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: negated
  type: boolean
- container: ''
  name: scope
  type: string
- container: ''
  name: tool
  type: string
- container: set
  name: rules
  type: reference
- container: set
  name: patterns
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: rationale
  type: string
- container: ''
  name: toolName
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: documentationUrl
  type: reference
property_count: 12
provider_name: .AIIgnore
provider_slug: aiignore
slug: aiignore-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aiignore\": \"https://aiignore.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AIIgnoreRule\": \"aiignore:AIIgnoreRule\",\n    \"AIIgnoreConfig\": \"aiignore:AIIgnoreConfig\",\n    \"ExclusionPattern\": \"aiignore:ExclusionPattern\",\n    \"AIToolCompatibility\": \"aiignore:AIToolCompatibility\",\n    \"pattern\": {\n      \"@id\": \"aiignore:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"negated\": {\n      \"@id\": \"aiignore:negated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"scope\": {\n      \"@id\": \"aiignore:scope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tool\": {\n      \"@id\": \"aiignore:tool\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"aiignore:rules\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"patterns\": {\n      \"@id\": \"aiignore:patterns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"aiignore:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rationale\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toolName\": {\n      \"@id\": \"aiignore:tool_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"aiignore:file_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentationUrl\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aiignore/refs/heads/main/json-ld/aiignore-context.jsonld
tags:
- AI Agents
- Configuration
- Developer Workflow
- Security
- Privacy
- Developer Tools
- LLM
- Secrets Management
- JSON-LD
- Linked Data
- Semantic Web
---
