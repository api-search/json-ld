---
api_specs:
- filename: datadog-apm-api.yml
  format: yaml
  label: Datadog APM API
  slug: datadog-apm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/datadog-apm/refs/heads/main/openapi/datadog-apm-api.yml
class_count: 0
classes: []
context_file: json-ld/datadog-apm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/datadog-apm/refs/heads/main/json-ld/datadog-apm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Datadog Apm from Datadog APM.
layout: jsonld
name: Datadog Apm Context
namespaces:
- prefix: datadog
  uri: https://docs.datadoghq.com/api/latest/
properties:
- container: ''
  name: Trace
  type: ''
- container: ''
  name: Span
  type: ''
- container: ''
  name: Service
  type: ''
- container: ''
  name: ServiceDefinition
  type: ''
- container: ''
  name: SLO
  type: ''
property_count: 5
provider_name: Datadog APM
provider_slug: datadog-apm
slug: datadog-apm-context
source_filename: datadog-apm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"datadog\": \"https://docs.datadoghq.com/api/latest/\",\n    \"Trace\": {\n      \"@id\": \"datadog:tracing\",\n      \"@context\": {\n        \"trace_id\": \"https://schema.org/identifier\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"resource\": \"https://schema.org/about\",\n        \"duration\": \"https://schema.org/duration\",\n        \"start\": \"https://schema.org/startTime\",\n        \"end\": \"https://schema.org/endTime\",\n        \"spans\": \"https://schema.org/hasPart\",\n        \"tags\": \"https://schema.org/keywords\"\n      }\n    },\n    \"Span\": {\n      \"@id\": \"datadog:tracing\",\n      \"@context\": {\n        \"span_id\": \"https://schema.org/identifier\",\n        \"trace_id\": \"https://schema.org/isPartOf\",\n        \"parent_id\": \"https://schema.org/parent\",\n        \"service\": \"https://schema.org/serviceType\",\n        \"name\": \"https://schema.org/name\"\
  ,\n        \"resource\": \"https://schema.org/about\",\n        \"start\": \"https://schema.org/startTime\",\n        \"duration\": \"https://schema.org/duration\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"error\": \"https://schema.org/status\",\n        \"meta\": \"https://schema.org/additionalProperty\"\n      }\n    },\n    \"Service\": {\n      \"@id\": \"datadog:service_definition\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"env\": \"https://schema.org/applicationCategory\",\n        \"tags\": \"https://schema.org/keywords\"\n      }\n    },\n    \"ServiceDefinition\": {\n      \"@id\": \"datadog:service_definition\",\n      \"@context\": {\n        \"schema_version\": \"https://schema.org/schemaVersion\",\n        \"dd_service\": \"https://schema.org/identifier\",\n        \"team\": \"https://schema.org/sourceOrganization\",\n        \"contacts\": \"https://schema.org/contactPoint\"\
  ,\n        \"links\": \"https://schema.org/sameAs\",\n        \"tags\": \"https://schema.org/keywords\"\n      }\n    },\n    \"SLO\": {\n      \"@id\": \"datadog:service_level_objectives\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"type\": \"https://schema.org/additionalType\",\n        \"thresholds\": \"https://schema.org/MonetaryAmount\",\n        \"target\": \"https://schema.org/value\",\n        \"warning\": \"https://schema.org/value\",\n        \"timeframe\": \"https://schema.org/duration\",\n        \"tags\": \"https://schema.org/keywords\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/datadog-apm/refs/heads/main/json-ld/datadog-apm-context.jsonld
tags:
- APM
- Distributed Tracing
- Microservices
- Observability
- Performance Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
