---
class_count: 1
classes:
- ProblemDetails
context_file: json-ld/dynatrace-problems-problem-details-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-problem-details-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Problems Problem Details from Dynatrace.
layout: jsonld
name: Dynatrace Problems Problem Details Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: severityLevel
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startTime
  type: integer
- container: ''
  name: endTime
  type: integer
- container: set
  name: affectedEntities
  type: ''
property_count: 7
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-problems-problem-details-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ProblemDetails\": \"dt:ProblemDetails\",\n    \"id\": {\n      \"@id\": \"dt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dt:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityLevel\": {\n      \"@id\": \"dt:severityLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"dt:startTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"dt:endTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"affectedEntities\": {\n      \"@id\": \"dt:affectedEntities\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-problem-details-context.jsonld
tags:
- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
