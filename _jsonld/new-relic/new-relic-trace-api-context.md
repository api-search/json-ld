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
- SpanBatch
- CommonBlock
- Span
- ZipkinSpan
- name
- AcceptedResponse
context_file: json-ld/new-relic-trace-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-trace-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Trace Api from New Relic.
layout: jsonld
name: New Relic Trace Api Context
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
  name: spans
  type: string
- container: ''
  name: attributes
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: trace.id
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: traceId
  type: string
- container: ''
  name: parentId
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: kind
  type: string
- container: ''
  name: localEndpoint
  type: reference
- container: ''
  name: remoteEndpoint
  type: reference
- container: ''
  name: tags
  type: reference
- container: set
  name: annotations
  type: string
- container: ''
  name: requestId
  type: string
property_count: 15
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-trace-api-context
source_filename: new-relic-trace-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nr\": \"https://docs.newrelic.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SpanBatch\": \"nr:SpanBatch\",\n    \"common\": {\n      \"@id\": \"nr:common\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spans\": {\n      \"@id\": \"nr:spans\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommonBlock\": \"nr:CommonBlock\",\n    \"attributes\": {\n      \"@id\": \"nr:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"Span\": \"nr:Span\",\n    \"id\": {\n      \"@id\": \"nr:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trace.id\": {\n      \"@id\": \"nr:trace.id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"nr:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ZipkinSpan\": \"nr:ZipkinSpan\",\n    \"traceId\"\
  : {\n      \"@id\": \"nr:traceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentId\": {\n      \"@id\": \"nr:parentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"duration\": {\n      \"@id\": \"nr:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"kind\": {\n      \"@id\": \"nr:kind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localEndpoint\": {\n      \"@id\": \"nr:localEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"remoteEndpoint\": {\n      \"@id\": \"nr:remoteEndpoint\",\n      \"@type\": \"@id\"\n    },\n    \"tags\": {\n      \"@id\": \"nr:tags\",\n      \"@type\": \"@id\"\n    },\n    \"annotations\": {\n      \"@id\": \"nr:annotations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcceptedResponse\": \"nr:AcceptedResponse\",\n    \"requestId\": {\n      \"@id\": \"nr:requestId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-trace-api-context.jsonld
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
