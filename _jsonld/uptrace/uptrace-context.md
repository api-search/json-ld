---
api_specs:
- filename: uptrace-openapi.yml
  format: yaml
  label: Uptrace API
  slug: uptrace
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/openapi/uptrace-openapi.yml
class_count: 5
classes:
- Project
- Annotation
- Alert
- Dashboard
- Span
context_file: json-ld/uptrace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/json-ld/uptrace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uptrace from Uptrace.
layout: jsonld
name: Uptrace Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: uptrace
  uri: https://api.uptrace.dev/api/v1/
- prefix: otel
  uri: https://opentelemetry.io/docs/concepts/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: dsn
  type: string
- container: ''
  name: projectId
  type: integer
- container: set
  name: tags
  type: ''
- container: ''
  name: attrs
  type: '@json'
- container: ''
  name: time
  type: dateTime
- container: ''
  name: query
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: forDuration
  type: string
- container: ''
  name: condition
  type: string
- container: set
  name: notificationChannels
  type: ''
- container: ''
  name: traceId
  type: string
- container: ''
  name: spanId
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 19
provider_name: Uptrace
provider_slug: uptrace
slug: uptrace-context
source_filename: uptrace-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"uptrace\": \"https://api.uptrace.dev/api/v1/\",\n    \"otel\": \"https://opentelemetry.io/docs/concepts/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Project\": \"schema:SoftwareApplication\",\n    \"id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:integer\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"slug\": { \"@id\": \"schema:alternateName\", \"@type\": \"xsd:string\" },\n    \"dsn\": { \"@id\": \"uptrace:dsn\", \"@type\": \"xsd:string\" },\n\n    \"Annotation\": \"schema:Action\",\n    \"projectId\": { \"@id\": \"uptrace:projectId\", \"@type\": \"xsd:integer\" },\n    \"tags\": { \"@id\": \"schema:keywords\", \"@container\": \"@set\" },\n    \"attrs\": { \"@id\": \"uptrace:attrs\", \"@type\": \"@json\" },\n    \"time\": { \"@id\": \"schema:startTime\", \"@type\": \"xsd:dateTime\" },\n\n    \"Alert\": \"schema:Alert\"\
  ,\n    \"query\": { \"@id\": \"uptrace:query\", \"@type\": \"xsd:string\" },\n    \"state\": { \"@id\": \"uptrace:state\", \"@type\": \"xsd:string\" },\n    \"forDuration\": { \"@id\": \"uptrace:forDuration\", \"@type\": \"xsd:string\" },\n    \"condition\": { \"@id\": \"uptrace:condition\", \"@type\": \"xsd:string\" },\n    \"notificationChannels\": { \"@id\": \"uptrace:notificationChannels\", \"@container\": \"@set\" },\n\n    \"Dashboard\": \"schema:WebPage\",\n\n    \"Span\": \"schema:Action\",\n    \"traceId\": { \"@id\": \"otel:trace-id\", \"@type\": \"xsd:string\" },\n    \"spanId\": { \"@id\": \"otel:span-id\", \"@type\": \"xsd:string\" },\n    \"serviceName\": { \"@id\": \"schema:serviceType\", \"@type\": \"xsd:string\" },\n\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"\
  \ }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uptrace/refs/heads/main/json-ld/uptrace-context.jsonld
tags:
- APM
- Observability
- OpenTelemetry
- Distributed Tracing
- Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
