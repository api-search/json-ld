---
api_specs:
- filename: dynatrace-metrics-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Metrics API v2
  slug: dynatrace-metrics-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-metrics-api-v2-openapi.yml
- filename: dynatrace-log-monitoring-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Log Monitoring API v2
  slug: dynatrace-log-monitoring-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-log-monitoring-api-v2-openapi.yml
- filename: dynatrace-account-management-api-openapi.yml
  format: yaml
  label: Dynatrace Account Management API
  slug: dynatrace-account-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-account-management-api-openapi.yml
- filename: dynatrace-events-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Events API v2
  slug: dynatrace-events-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-events-api-v2-openapi.yml
- filename: dynatrace-problems-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Problems API v2
  slug: dynatrace-problems-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-problems-api-v2-openapi.yml
- filename: dynatrace-entities-api-v2-openapi.yml
  format: yaml
  label: Dynatrace Entities API v2
  slug: dynatrace-entities-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/openapi/dynatrace-entities-api-v2-openapi.yml
class_count: 0
classes: []
context_file: json-ld/dynatrace-log-monitoring-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-log-monitoring-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Log Monitoring V2 from Dynatrace.
layout: jsonld
name: Dynatrace Log Monitoring V2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: LogIngestRecord
  type: ''
- container: ''
  name: LogRecord
  type: ''
- container: ''
  name: LogRecordSearchResult
  type: ''
- container: ''
  name: LogAggregateResult
  type: ''
- container: ''
  name: LogAggregateGroup
  type: ''
- container: ''
  name: LogExportResult
  type: ''
- container: ''
  name: ErrorEnvelope
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ConstraintViolation
  type: ''
property_count: 9
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-log-monitoring-v2-context
source_filename: dynatrace-log-monitoring-v2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"LogIngestRecord\": {\n      \"@id\": \"ns:LogIngestRecord\",\n      \"@context\": {\n        \"content\": {\n          \"@id\": \"ns:content\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"ns:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:string\"\n        },\n        \"log.source\": {\n          \"@id\": \"ns:log.source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dt.entity.host\": {\n          \"@id\": \"ns:dt.entity.host\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"LogRecord\": {\n      \"@id\": \"ns:LogRecord\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"content\": {\n          \"@id\": \"ns:content\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"ns:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"log.source\": {\n          \"@id\": \"ns:log.source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dt.entity.host\": {\n          \"@id\": \"ns:dt.entity.host\",\n          \"@type\": \"xsd:string\"\n        },\n        \"additionalFields\": \"ns:additionalFields\"\n      }\n    },\n    \"LogRecordSearchResult\": {\n      \"@id\": \"ns:LogRecordSearchResult\",\n      \"@context\": {\n        \"nextSliceKey\": {\n          \"@id\": \"ns:nextSliceKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\"\n      }\n    },\n    \"LogAggregateResult\": {\n      \"@id\": \"ns:LogAggregateResult\",\n      \"@context\": {\n        \"results\": \"ns:results\"\n      }\n    },\n    \"LogAggregateGroup\": {\n\
  \      \"@id\": \"ns:LogAggregateGroup\",\n      \"@context\": {\n        \"groupByFields\": \"ns:groupByFields\",\n        \"count\": {\n          \"@id\": \"ns:count\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"LogExportResult\": {\n      \"@id\": \"ns:LogExportResult\",\n      \"@context\": {\n        \"nextSliceKey\": {\n          \"@id\": \"ns:nextSliceKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"results\": \"ns:results\"\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n     \
  \   \"constraintViolations\": \"ns:constraintViolations\"\n      }\n    },\n    \"ConstraintViolation\": {\n      \"@id\": \"ns:ConstraintViolation\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameterLocation\": {\n          \"@id\": \"ns:parameterLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-log-monitoring-v2-context.jsonld
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
