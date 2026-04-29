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
context_file: json-ld/new-relic-trace-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-trace-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Trace from New Relic.
layout: jsonld
name: New Relic Trace Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: SpanBatch
  type: ''
- container: ''
  name: CommonBlock
  type: ''
- container: ''
  name: Span
  type: ''
- container: ''
  name: ZipkinSpan
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
slug: new-relic-trace-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"SpanBatch\": {\n      \"@id\": \"ns:SpanBatch\",\n      \"@context\": {\n        \"common\": {\n          \"@id\": \"ns:common\",\n          \"@type\": \"xsd:string\"\n        },\n        \"spans\": \"ns:spans\"\n      }\n    },\n    \"CommonBlock\": {\n      \"@id\": \"ns:CommonBlock\",\n      \"@context\": {\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"Span\": {\n      \"@id\": \"ns:Span\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"trace.id\": {\n          \"@id\": \"ns:trace.id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"ZipkinSpan\"\
  : {\n      \"@id\": \"ns:ZipkinSpan\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"ns:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"traceId\": {\n          \"@id\": \"ns:traceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentId\": {\n          \"@id\": \"ns:parentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"duration\": {\n          \"@id\": \"ns:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"kind\": {\n          \"@id\": \"ns:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"localEndpoint\": \"ns:localEndpoint\",\n        \"remoteEndpoint\": \"ns:remoteEndpoint\",\n        \"tags\": \"ns:tags\",\n        \"annotations\": \"ns:annotations\"\n      }\n\
  \    },\n    \"AcceptedResponse\": {\n      \"@id\": \"ns:AcceptedResponse\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"ns:requestId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"ns:requestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-trace-context.jsonld
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
