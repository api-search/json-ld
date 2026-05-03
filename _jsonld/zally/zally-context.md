---
api_specs:
- filename: zally-api.yml
  format: yaml
  label: Zally API
  slug: zally-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/openapi/zally-api.yml
class_count: 10
classes:
- LintingRequest
- LintingResponse
- ReviewStatisticsResponse
- Rule
- SupportedRulesResponse
- Violation
- ViolationsCount
- title
- description
- url
context_file: json-ld/zally-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-ld/zally-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zally from Zally.
layout: jsonld
name: Zally Context
namespaces:
- prefix: zally
  uri: https://zally.example.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: apiDefinition
  type: string
- container: ''
  name: apiDefinitionString
  type: string
- container: ''
  name: apiDefinitionUrl
  type: string
- container: set
  name: ignoreRules
  type: string
- container: set
  name: violations
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: violationsCount
  type: reference
- container: ''
  name: totalReviews
  type: integer
- container: ''
  name: totalReviewsDeduplicated
  type: integer
- container: ''
  name: successfulReviews
  type: integer
- container: ''
  name: numberOfEndpoints
  type: integer
- container: ''
  name: mustViolations
  type: integer
- container: ''
  name: shouldViolations
  type: integer
- container: ''
  name: mayViolations
  type: integer
- container: ''
  name: hintViolations
  type: integer
- container: ''
  name: code
  type: string
- container: ''
  name: isActive
  type: boolean
- container: set
  name: paths
  type: string
- container: ''
  name: pointer
  type: string
- container: ''
  name: startLine
  type: integer
- container: ''
  name: endLine
  type: integer
- container: ''
  name: must
  type: integer
- container: ''
  name: should
  type: integer
- container: ''
  name: may
  type: integer
- container: ''
  name: could
  type: integer
- container: ''
  name: hint
  type: integer
- container: set
  name: supportedRules
  type: reference
- container: ''
  name: ruleLink
  type: string
- container: ''
  name: violationType
  type: reference
property_count: 29
provider_name: Zally
provider_slug: zally
slug: zally-context
source_filename: zally-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"zally\": \"https://zally.example.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LintingRequest\": \"zally:LintingRequest\",\n    \"LintingResponse\": \"zally:LintingResponse\",\n    \"ReviewStatisticsResponse\": \"zally:ReviewStatisticsResponse\",\n    \"Rule\": \"zally:Rule\",\n    \"SupportedRulesResponse\": \"zally:SupportedRulesResponse\",\n    \"Violation\": \"zally:Violation\",\n    \"ViolationsCount\": \"zally:ViolationsCount\",\n    \"apiDefinition\": {\n      \"@id\": \"zally:api_definition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiDefinitionString\": {\n      \"@id\": \"zally:api_definition_string\",\n      \"@type\": \"xsd:string\"\n    },\n    \"apiDefinitionUrl\": {\n      \"@id\": \"zally:api_definition_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ignoreRules\": {\n    \
  \  \"@id\": \"zally:ignore_rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"violations\": {\n      \"@id\": \"zally:violations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"message\": {\n      \"@id\": \"zally:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"violationsCount\": {\n      \"@id\": \"zally:violations_count\",\n      \"@type\": \"@id\"\n    },\n    \"totalReviews\": {\n      \"@id\": \"zally:total_reviews\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalReviewsDeduplicated\": {\n      \"@id\": \"zally:total_reviews_deduplicated\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"successfulReviews\": {\n      \"@id\": \"zally:successful_reviews\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfEndpoints\": {\n      \"@id\": \"zally:number_of_endpoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mustViolations\": {\n      \"@id\": \"zally:must_violations\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"shouldViolations\": {\n      \"@id\": \"zally:should_violations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mayViolations\": {\n      \"@id\": \"zally:may_violations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hintViolations\": {\n      \"@id\": \"zally:hint_violations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"code\": {\n      \"@id\": \"zally:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isActive\": {\n      \"@id\": \"zally:is_active\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paths\": {\n      \"@id\": \"zally:paths\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pointer\": {\n      \"@id\": \"zally:pointer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startLine\": {\n      \"@id\": \"zally:start_line\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endLine\"\
  : {\n      \"@id\": \"zally:end_line\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"must\": {\n      \"@id\": \"zally:must\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"should\": {\n      \"@id\": \"zally:should\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"may\": {\n      \"@id\": \"zally:may\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"could\": {\n      \"@id\": \"zally:could\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hint\": {\n      \"@id\": \"zally:hint\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"supportedRules\": {\n      \"@id\": \"zally:supported_rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ruleLink\": {\n      \"@id\": \"zally:rule_link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"violationType\": {\n      \"@id\": \"zally:violation_type\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zally/refs/heads/main/json-ld/zally-context.jsonld
tags:
- API Design
- API Linting
- API Quality
- Open Source
- OpenAPI
- Zalando
- JSON-LD
- Linked Data
- Semantic Web
---
