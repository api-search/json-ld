---
class_count: 17
classes:
- Ruleset
- Rule
- Report
- RuleResult
- description
- severity
- message
- given
- errors
- path
- startLine
- endLine
- generated
- version
- format
- totalErrors
- totalWarnings
context_file: json-ld/vacuum-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vacuum/refs/heads/main/json-ld/vacuum-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vacuum from Vacuum.
layout: jsonld
name: Vacuum Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dcat
  uri: https://www.w3.org/ns/dcat#
properties: []
property_count: 0
provider_name: Vacuum
provider_slug: vacuum
slug: vacuum-context
source_filename: vacuum-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://quobix.com/vacuum/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"dcat\": \"https://www.w3.org/ns/dcat#\",\n    \"Ruleset\": \"schema:CreativeWork\",\n    \"Rule\": \"schema:Action\",\n    \"Report\": \"schema:Report\",\n    \"RuleResult\": \"schema:ListItem\",\n    \"description\": \"schema:description\",\n    \"severity\": \"schema:additionalProperty\",\n    \"message\": \"schema:text\",\n    \"given\": \"schema:query\",\n    \"errors\": \"schema:error\",\n    \"path\": \"schema:identifier\",\n    \"startLine\": \"schema:startOffset\",\n    \"endLine\": \"schema:endOffset\",\n    \"generated\": \"schema:dateCreated\",\n    \"version\": \"schema:version\",\n    \"format\": \"schema:encodingFormat\",\n    \"totalErrors\": \"schema:errorCount\",\n    \"totalWarnings\": \"schema:warningCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vacuum/refs/heads/main/json-ld/vacuum-context.jsonld
tags:
- API Design
- Documentation
- Linting
- OpenAPI
- Spectral
- Developer Tools
- Go
- JSON-LD
- Linked Data
- Semantic Web
---
