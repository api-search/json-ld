---
class_count: 1
classes:
- Dynatrace Problem
context_file: json-ld/dynatrace-dynatrace-problem-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-dynatrace-problem-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Dynatrace Problem from Dynatrace.
layout: jsonld
name: Dynatrace Dynatrace Problem Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: problemId
  type: string
- container: ''
  name: displayId
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
- container: set
  name: impactedEntities
  type: ''
- container: ''
  name: rootCauseEntity
  type: string
- container: set
  name: managementZones
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: evidenceDetails
  type: ''
- container: ''
  name: comments
  type: ''
property_count: 14
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-dynatrace-problem-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Dynatrace Problem\": \"dt:Dynatrace Problem\",\n    \"problemId\": {\n      \"@id\": \"dt:problemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayId\": {\n      \"@id\": \"dt:displayId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dt:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityLevel\": {\n      \"@id\": \"dt:severityLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"dt:startTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"dt:endTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"affectedEntities\": {\n      \"@id\": \"dt:affectedEntities\",\n\
  \      \"@container\": \"@set\"\n    },\n    \"impactedEntities\": {\n      \"@id\": \"dt:impactedEntities\",\n      \"@container\": \"@set\"\n    },\n    \"rootCauseEntity\": {\n      \"@id\": \"dt:rootCauseEntity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managementZones\": {\n      \"@id\": \"dt:managementZones\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"dt:tags\",\n      \"@container\": \"@set\"\n    },\n    \"evidenceDetails\": {\n      \"@id\": \"dt:evidenceDetails\"\n    },\n    \"comments\": {\n      \"@id\": \"dt:comments\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-dynatrace-problem-context.jsonld
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
