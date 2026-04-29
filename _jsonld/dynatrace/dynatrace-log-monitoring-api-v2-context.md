---
class_count: 7
classes:
- ConstraintViolation
- LogAggregateGroup
- LogAggregateResult
- LogExportResult
- LogIngestRecord
- LogRecord
- LogRecordSearchResult
context_file: json-ld/dynatrace-log-monitoring-api-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-log-monitoring-api-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Log Monitoring Api V2 from Dynatrace.
layout: jsonld
name: Dynatrace Log Monitoring Api V2 Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: path
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: parameterLocation
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: groupByFields
  type: ''
- container: ''
  name: count
  type: integer
- container: set
  name: results
  type: ''
- container: ''
  name: nextSliceKey
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: log.source
  type: string
- container: ''
  name: dt.entity.host
  type: string
- container: ''
  name: additionalFields
  type: ''
property_count: 14
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-log-monitoring-api-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConstraintViolation\": \"dt:ConstraintViolation\",\n    \"path\": {\n      \"@id\": \"dt:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"dt:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterLocation\": {\n      \"@id\": \"dt:parameterLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"dt:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogAggregateGroup\": \"dt:LogAggregateGroup\",\n    \"groupByFields\": {\n      \"@id\": \"dt:groupByFields\"\n    },\n    \"count\": {\n      \"@id\": \"dt:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"LogAggregateResult\": \"dt:LogAggregateResult\",\n    \"results\": {\n      \"@id\": \"dt:results\",\n      \"@container\": \"@set\"\
  \n    },\n    \"LogExportResult\": \"dt:LogExportResult\",\n    \"nextSliceKey\": {\n      \"@id\": \"dt:nextSliceKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogIngestRecord\": \"dt:LogIngestRecord\",\n    \"content\": {\n      \"@id\": \"dt:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"dt:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"dt:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"log.source\": {\n      \"@id\": \"dt:log.source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dt.entity.host\": {\n      \"@id\": \"dt:dt.entity.host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogRecord\": \"dt:LogRecord\",\n    \"additionalFields\": {\n      \"@id\": \"dt:additionalFields\"\n    },\n    \"LogRecordSearchResult\": \"dt:LogRecordSearchResult\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-log-monitoring-api-v2-context.jsonld
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
