---
api_specs:
- filename: new-relic-openapi.yml
  format: yaml
  label: New Relic REST API v2
  slug: new-relic-rest-api-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-openapi.yml
- filename: new-relic-metric-api-openapi.yml
  format: yaml
  label: New Relic Metric API
  slug: new-relic-metric-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-metric-api-openapi.yml
- filename: new-relic-event-api-openapi.yml
  format: yaml
  label: New Relic Event API
  slug: new-relic-event-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-event-api-openapi.yml
- filename: new-relic-log-api-openapi.yml
  format: yaml
  label: New Relic Log API
  slug: new-relic-log-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-log-api-openapi.yml
- filename: new-relic-trace-api-openapi.yml
  format: yaml
  label: New Relic Trace API
  slug: new-relic-trace-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/openapi/new-relic-trace-api-openapi.yml
class_count: 6
classes:
- MetricDataObject
- CommonBlock
- MetricDataPoint
- name
- SummaryValue
- AcceptedResponse
context_file: json-ld/new-relic-metric-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-metric-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Metric Api from New Relic.
layout: jsonld
name: New Relic Metric Api Context
namespaces:
- prefix: nr
  uri: https://docs.newrelic.com/docs/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: common
  type: string
- container: set
  name: metrics
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: interval.ms
  type: integer
- container: ''
  name: attributes
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: count
  type: decimal
- container: ''
  name: sum
  type: decimal
- container: ''
  name: min
  type: decimal
- container: ''
  name: max
  type: decimal
- container: ''
  name: requestId
  type: string
property_count: 12
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-metric-api-context
source_filename: new-relic-metric-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nr\": \"https://docs.newrelic.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MetricDataObject\": \"nr:MetricDataObject\",\n    \"common\": {\n      \"@id\": \"nr:common\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metrics\": {\n      \"@id\": \"nr:metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommonBlock\": \"nr:CommonBlock\",\n    \"timestamp\": {\n      \"@id\": \"nr:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"interval.ms\": {\n      \"@id\": \"nr:interval.ms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attributes\": {\n      \"@id\": \"nr:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"MetricDataPoint\": \"nr:MetricDataPoint\",\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"nr:type\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"nr:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SummaryValue\": \"nr:SummaryValue\",\n    \"count\": {\n      \"@id\": \"nr:count\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"sum\": {\n      \"@id\": \"nr:sum\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"min\": {\n      \"@id\": \"nr:min\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"max\": {\n      \"@id\": \"nr:max\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"AcceptedResponse\": \"nr:AcceptedResponse\",\n    \"requestId\": {\n      \"@id\": \"nr:requestId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-metric-api-context.jsonld
tags:
- Analysis
- Analytics
- APM
- DevOps
- Infrastructure
- Monitoring
- Observability
- Performance
- Platform
- JSON-LD
- Linked Data
- Semantic Web
---
