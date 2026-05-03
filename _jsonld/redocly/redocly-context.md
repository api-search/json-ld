---
class_count: 0
classes: []
context_file: json-ld/redocly-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/json-ld/redocly-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Redocly from Redocly.
layout: jsonld
name: Redocly Context
namespaces:
- prefix: redocly
  uri: https://redocly.com/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: RedoclyConfig
  type: ''
- container: ''
  name: ApiDefinition
  type: ''
- container: ''
  name: LintResult
  type: ''
- container: ''
  name: LintProblem
  type: ''
property_count: 4
provider_name: Redocly
provider_slug: redocly
slug: redocly-context
source_filename: redocly-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"redocly\": \"https://redocly.com/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"RedoclyConfig\": {\n      \"@id\": \"redocly:Configuration\",\n      \"@context\": {\n        \"apis\": {\n          \"@id\": \"redocly:apis\",\n          \"@container\": \"@index\"\n        },\n        \"extends\": \"redocly:extends\",\n        \"rules\": {\n          \"@id\": \"redocly:rules\",\n          \"@container\": \"@index\"\n        },\n        \"plugins\": {\n          \"@id\": \"redocly:plugins\",\n          \"@container\": \"@set\"\n        },\n        \"theme\": \"redocly:theme\"\n      }\n    },\n\n    \"ApiDefinition\": {\n      \"@id\": \"redocly:ApiDefinition\",\n      \"@context\": {\n        \"root\": {\n          \"@id\": \"redocly:rootFile\",\n          \"@type\": \"xsd:string\"\n        },\n        \"extends\"\
  : \"redocly:extends\",\n        \"rules\": {\n          \"@id\": \"redocly:rules\",\n          \"@container\": \"@index\"\n        },\n        \"labels\": {\n          \"@id\": \"redocly:labels\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"LintResult\": {\n      \"@id\": \"redocly:LintResult\",\n      \"@context\": {\n        \"totals\": \"redocly:totals\",\n        \"problems\": {\n          \"@id\": \"redocly:problems\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"LintProblem\": {\n      \"@id\": \"redocly:LintProblem\",\n      \"@context\": {\n        \"message\": \"schema:description\",\n        \"severity\": \"redocly:severity\",\n        \"ruleId\": \"redocly:ruleId\",\n        \"location\": {\n          \"@id\": \"redocly:location\",\n          \"@container\": \"@set\"\n        },\n        \"suggest\": {\n          \"@id\": \"redocly:suggest\",\n          \"@container\": \"@set\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/redocly/refs/heads/main/json-ld/redocly-context.jsonld
tags:
- API Catalog
- API Documentation
- Developer Portal
- Governance
- Linting
- OpenAPI
- JSON-LD
- Linked Data
- Semantic Web
---
