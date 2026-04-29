---
class_count: 2
classes:
- CustomEvent
- SuccessResponse
context_file: json-ld/new-relic-event-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-event-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Event Api from New Relic.
layout: jsonld
name: New Relic Event Api Context
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
  name: eventType
  type: string
- container: ''
  name: timestamp
  type: integer
- container: ''
  name: success
  type: boolean
- container: ''
  name: uuid
  type: string
property_count: 4
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-event-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"nr\": \"https://docs.newrelic.com/docs/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomEvent\": \"nr:CustomEvent\",\n    \"eventType\": {\n      \"@id\": \"nr:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"nr:timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SuccessResponse\": \"nr:SuccessResponse\",\n    \"success\": {\n      \"@id\": \"nr:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"uuid\": {\n      \"@id\": \"nr:uuid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-event-api-context.jsonld
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
