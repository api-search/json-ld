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
class_count: 7
classes:
- ConstraintViolation
- EntityStub
- EventCollection
- EventIngestPayload
- EventIngestResultItem
- EventIngestResult
- Event
context_file: json-ld/dynatrace-events-api-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-events-api-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Events Api V2 from Dynatrace.
layout: jsonld
name: Dynatrace Events Api V2 Context
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
  name: entityId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: nextPageKey
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: set
  name: events
  type: ''
- container: ''
  name: eventType
  type: string
- container: ''
  name: timeout
  type: integer
- container: ''
  name: entitySelector
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: startTime
  type: integer
- container: ''
  name: endTime
  type: integer
- container: ''
  name: properties
  type: ''
- container: ''
  name: eventId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: reportCount
  type: integer
- container: set
  name: eventIngestResults
  type: ''
property_count: 22
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-events-api-v2-context
source_filename: dynatrace-events-api-v2-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ConstraintViolation\": \"dt:ConstraintViolation\",\n    \"path\": {\n      \"@id\": \"dt:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"dt:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameterLocation\": {\n      \"@id\": \"dt:parameterLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"dt:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityStub\": \"dt:EntityStub\",\n    \"entityId\": {\n      \"@id\": \"dt:entityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventCollection\": \"dt:EventCollection\"\
  ,\n    \"nextPageKey\": {\n      \"@id\": \"dt:nextPageKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"dt:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"dt:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"events\": {\n      \"@id\": \"dt:events\",\n      \"@container\": \"@set\"\n    },\n    \"EventIngestPayload\": \"dt:EventIngestPayload\",\n    \"eventType\": {\n      \"@id\": \"dt:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"dt:timeout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entitySelector\": {\n      \"@id\": \"dt:entitySelector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dt:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"dt:startTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"dt:endTime\",\n      \"@type\":\
  \ \"xsd:integer\"\n    },\n    \"properties\": {\n      \"@id\": \"dt:properties\"\n    },\n    \"EventIngestResultItem\": \"dt:EventIngestResultItem\",\n    \"eventId\": {\n      \"@id\": \"dt:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"dt:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventIngestResult\": \"dt:EventIngestResult\",\n    \"reportCount\": {\n      \"@id\": \"dt:reportCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"eventIngestResults\": {\n      \"@id\": \"dt:eventIngestResults\",\n      \"@container\": \"@set\"\n    },\n    \"Event\": \"dt:Event\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-events-api-v2-context.jsonld
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
