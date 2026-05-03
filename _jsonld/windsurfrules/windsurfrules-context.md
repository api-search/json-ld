---
api_specs:
- filename: windsurf-enterprise-openapi.yml
  format: yaml
  label: Windsurf Enterprise API
  slug: windsurf-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/openapi/windsurf-enterprise-openapi.yml
class_count: 12
classes:
- WindsurfRules
- CascadeAgent
- CompletionAnalytics
- UserAnalytics
- CascadeAnalytics
- ServiceKey
- UsageConfig
- SoftwareApplication
- name
- description
- url
- version
context_file: json-ld/windsurfrules-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/json-ld/windsurfrules-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Windsurfrules from Windsurf.
layout: jsonld
name: Windsurfrules Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: windsurf
  uri: https://windsurf.com/vocab#
properties:
- container: ''
  name: serviceKey
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: completionsShown
  type: integer
- container: ''
  name: completionsAccepted
  type: integer
- container: ''
  name: acceptanceRate
  type: decimal
- container: ''
  name: linesSaved
  type: integer
- container: ''
  name: cascadeLines
  type: integer
- container: ''
  name: totalCredits
  type: integer
- container: ''
  name: usedCredits
  type: integer
- container: ''
  name: remainingCredits
  type: integer
- container: ''
  name: dataSource
  type: string
- container: ''
  name: rulesFile
  type: string
- container: ''
  name: activationMode
  type: string
property_count: 13
provider_name: Windsurf
provider_slug: windsurfrules
slug: windsurfrules-context
source_filename: windsurfrules-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"windsurf\": \"https://windsurf.com/vocab#\",\n\n    \"WindsurfRules\": \"windsurf:WindsurfRules\",\n    \"CascadeAgent\": \"windsurf:CascadeAgent\",\n    \"CompletionAnalytics\": \"windsurf:CompletionAnalytics\",\n    \"UserAnalytics\": \"windsurf:UserAnalytics\",\n    \"CascadeAnalytics\": \"windsurf:CascadeAnalytics\",\n    \"ServiceKey\": \"windsurf:ServiceKey\",\n    \"UsageConfig\": \"windsurf:UsageConfig\",\n\n    \"serviceKey\": {\n      \"@id\": \"windsurf:serviceKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"windsurf:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completionsShown\": {\n      \"@id\": \"windsurf:completionsShown\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"completionsAccepted\": {\n      \"@id\": \"windsurf:completionsAccepted\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"acceptanceRate\": {\n      \"@id\": \"windsurf:acceptanceRate\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"linesSaved\": {\n      \"@id\": \"windsurf:linesSaved\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cascadeLines\": {\n      \"@id\": \"windsurf:cascadeLines\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalCredits\": {\n      \"@id\": \"windsurf:totalCredits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usedCredits\": {\n      \"@id\": \"windsurf:usedCredits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"remainingCredits\": {\n      \"@id\": \"windsurf:remainingCredits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataSource\": {\n      \"@id\": \"windsurf:dataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rulesFile\": {\n      \"@id\": \"windsurf:rulesFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activationMode\": {\n      \"@id\": \"windsurf:activationMode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"version\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/windsurfrules/refs/heads/main/json-ld/windsurfrules-context.jsonld
tags:
- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- IDE
- Windsurf
- JSON-LD
- Linked Data
- Semantic Web
---
