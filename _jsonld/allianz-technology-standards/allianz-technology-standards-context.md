---
class_count: 8
classes:
- StandardList
- WebhookGuideline
- StandardRule
- ComplianceCheckRequest
- ComplianceViolation
- Standard
- ComplianceResult
- PaginationGuideline
context_file: json-ld/allianz-technology-standards-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/allianz-technology-standards/refs/heads/main/json-ld/allianz-technology-standards-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Allianz Technology Standards from Allianz Technology Standards.
layout: jsonld
name: Allianz Technology Standards Context
namespaces:
- prefix: allianz
  uri: https://standards.allianz.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: total
  type: integer
- container: set
  name: items
  type: string
- container: ''
  name: guidelineId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: string
- container: set
  name: notificationTypes
  type: string
- container: set
  name: securityRequirements
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: openapiUrl
  type: reference
- container: set
  name: standardIds
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: standardId
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: rules
  type: string
- container: ''
  name: checkId
  type: string
- container: ''
  name: passed
  type: integer
- container: ''
  name: failed
  type: integer
- container: ''
  name: warnings
  type: integer
- container: set
  name: violations
  type: string
- container: set
  name: parameters
  type: string
- container: set
  name: responseHeaders
  type: string
property_count: 24
provider_name: Allianz Technology Standards
provider_slug: allianz-technology-standards
slug: allianz-technology-standards-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"allianz\": \"https://standards.allianz.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StandardList\": \"allianz:StandardList\",\n    \"WebhookGuideline\": \"allianz:WebhookGuideline\",\n    \"StandardRule\": \"allianz:StandardRule\",\n    \"ComplianceCheckRequest\": \"allianz:ComplianceCheckRequest\",\n    \"ComplianceViolation\": \"allianz:ComplianceViolation\",\n    \"Standard\": \"allianz:Standard\",\n    \"ComplianceResult\": \"allianz:ComplianceResult\",\n    \"PaginationGuideline\": \"allianz:PaginationGuideline\",\n    \"total\": {\n      \"@id\": \"allianz:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"items\": {\n      \"@id\": \"allianz:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guidelineId\": {\n      \"@id\": \"allianz:guideline_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\"\
  : {\n      \"@id\": \"allianz:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"allianz:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationTypes\": {\n      \"@id\": \"allianz:notification_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityRequirements\": {\n      \"@id\": \"allianz:security_requirements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"allianz:rule_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"allianz:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"allianz:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"openapiUrl\": {\n      \"@id\": \"allianz:openapi_url\",\n      \"@type\": \"@id\"\n    },\n    \"standardIds\": {\n      \"@id\": \"allianz:standard_ids\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"allianz:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"standardId\": {\n      \"@id\": \"allianz:standard_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"allianz:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"allianz:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"allianz:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkId\": {\n      \"@id\": \"allianz:check_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passed\": {\n      \"@id\": \"allianz:passed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failed\": {\n      \"@id\": \"allianz:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"warnings\": {\n      \"@id\": \"allianz:warnings\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"violations\": {\n      \"@id\": \"allianz:violations\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"allianz:parameters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseHeaders\": {\n      \"@id\": \"allianz:response_headers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/allianz-technology-standards/refs/heads/main/json-ld/allianz-technology-standards-context.jsonld
tags:
- Best Practices
- Enterprise Architecture
- Guidelines
- Software Development
- Technology Standards
- API Design
- OpenAPI
- JSON-LD
- Linked Data
- Semantic Web
---
