---
api_specs:
- filename: tempo-openapi.yml
  format: yaml
  label: Tempo HTTP API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/openapi/tempo-openapi.yml
class_count: 7
classes:
- name
- description
- url
- SoftwareApplication
- Tags
- Documentation
- Repository
context_file: json-ld/tempo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/json-ld/tempo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tempo from Tempo.
layout: jsonld
name: Tempo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: otel
  uri: https://opentelemetry.io/otel/
- prefix: tempo
  uri: https://grafana.com/oss/tempo/
properties:
- container: ''
  name: trace
  type: reference
- container: ''
  name: span
  type: reference
- container: ''
  name: traceId
  type: schema:Text
- container: ''
  name: spanId
  type: schema:Text
- container: ''
  name: parentSpanId
  type: schema:Text
- container: ''
  name: operationName
  type: schema:Text
- container: ''
  name: startTime
  type: schema:DateTime
- container: ''
  name: endTime
  type: schema:DateTime
- container: ''
  name: duration
  type: schema:Duration
- container: ''
  name: serviceName
  type: schema:Text
- container: ''
  name: spanKind
  type: schema:Text
- container: ''
  name: statusCode
  type: schema:Text
- container: ''
  name: attributes
  type: reference
- container: ''
  name: resource
  type: reference
property_count: 14
provider_name: Tempo
provider_slug: tempo
slug: tempo-context
source_filename: tempo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"otel\": \"https://opentelemetry.io/otel/\",\n    \"tempo\": \"https://grafana.com/oss/tempo/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"trace\": {\n      \"@id\": \"otel:trace\",\n      \"@type\": \"@id\"\n    },\n    \"span\": {\n      \"@id\": \"otel:span\",\n      \"@type\": \"@id\"\n    },\n    \"traceId\": {\n      \"@id\": \"otel:traceId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"spanId\": {\n      \"@id\": \"otel:spanId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"parentSpanId\": {\n      \"@id\": \"otel:parentSpanId\",\n      \"@type\": \"schema:Text\"\n    },\n    \"operationName\": {\n      \"@id\": \"otel:operationName\",\n      \"@type\": \"schema:Text\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startTime\"\
  ,\n      \"@type\": \"schema:DateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"schema:Duration\"\n    },\n    \"serviceName\": {\n      \"@id\": \"otel:serviceName\",\n      \"@type\": \"schema:Text\"\n    },\n    \"spanKind\": {\n      \"@id\": \"otel:spanKind\",\n      \"@type\": \"schema:Text\"\n    },\n    \"statusCode\": {\n      \"@id\": \"otel:statusCode\",\n      \"@type\": \"schema:Text\"\n    },\n    \"attributes\": {\n      \"@id\": \"otel:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"resource\": {\n      \"@id\": \"otel:resource\",\n      \"@type\": \"@id\"\n    },\n    \"Tags\": \"schema:keywords\",\n    \"Documentation\": \"schema:documentation\",\n    \"Repository\": \"schema:codeRepository\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tempo/refs/heads/main/json-ld/tempo-context.jsonld
tags:
- Distributed Tracing
- Observability
- OpenTelemetry
- Grafana
- Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
