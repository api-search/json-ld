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
class_count: 0
classes: []
context_file: json-ld/new-relic-metric-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-metric-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Metric from New Relic.
layout: jsonld
name: New Relic Metric Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: MetricDataObject
  type: ''
- container: ''
  name: CommonBlock
  type: ''
- container: ''
  name: MetricDataPoint
  type: ''
- container: ''
  name: SummaryValue
  type: ''
- container: ''
  name: AcceptedResponse
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 6
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-metric-context
source_filename: new-relic-metric-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"MetricDataObject\": {\n      \"@id\": \"ns:MetricDataObject\",\n      \"@context\": {\n        \"common\": {\n          \"@id\": \"ns:common\",\n          \"@type\": \"xsd:string\"\n        },\n        \"metrics\": \"ns:metrics\"\n      }\n    },\n    \"CommonBlock\": {\n      \"@id\": \"ns:CommonBlock\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"interval.ms\": {\n          \"@id\": \"ns:interval.ms\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"MetricDataPoint\": {\n      \"@id\": \"ns:MetricDataPoint\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n  \
  \        \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"value\": {\n          \"@id\": \"ns:value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"interval.ms\": {\n          \"@id\": \"ns:interval.ms\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"SummaryValue\": {\n      \"@id\": \"ns:SummaryValue\",\n      \"@context\": {\n        \"count\": {\n          \"@id\": \"ns:count\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"sum\": {\n          \"@id\": \"ns:sum\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"min\": {\n          \"@id\": \"ns:min\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"max\": {\n          \"@id\": \"ns:max\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n    \"AcceptedResponse\"\
  : {\n      \"@id\": \"ns:AcceptedResponse\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"ns:requestId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"error\": \"ns:error\",\n        \"failures\": \"ns:failures\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-metric-context.jsonld
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
