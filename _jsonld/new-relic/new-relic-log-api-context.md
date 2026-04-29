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
class_count: 4
classes:
- LogDataObject
- CommonBlock
- LogRecord
- AcceptedResponse
context_file: json-ld/new-relic-log-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-log-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Log Api from New Relic.
layout: jsonld
name: New Relic Log Api Context
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
  name: logs
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: attributes
  type: reference
- container: ''
  name: message
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: logtype
  type: string
- container: ''
  name: requestId
  type: string
property_count: 8
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-log-api-context
source_filename: new-relic-log-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nr\": \"https://docs.newrelic.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LogDataObject\": \"nr:LogDataObject\",\n    \"common\": {\n      \"@id\": \"nr:common\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logs\": {\n      \"@id\": \"nr:logs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommonBlock\": \"nr:CommonBlock\",\n    \"timestamp\": {\n      \"@id\": \"nr:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attributes\": {\n      \"@id\": \"nr:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"LogRecord\": \"nr:LogRecord\",\n    \"message\": {\n      \"@id\": \"nr:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"nr:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logtype\": {\n      \"@id\"\
  : \"nr:logtype\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AcceptedResponse\": \"nr:AcceptedResponse\",\n    \"requestId\": {\n      \"@id\": \"nr:requestId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-log-api-context.jsonld
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
