---
class_count: 0
classes: []
context_file: json-ld/new-relic-log-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-log-context.jsonld
description: JSON-LD context defining the semantic vocabulary for New Relic Log from New Relic.
layout: jsonld
name: New Relic Log Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: LogDataObject
  type: ''
- container: ''
  name: CommonBlock
  type: ''
- container: ''
  name: LogRecord
  type: ''
- container: ''
  name: AcceptedResponse
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 5
provider_name: New Relic
provider_slug: new-relic
slug: new-relic-log-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"LogDataObject\": {\n      \"@id\": \"ns:LogDataObject\",\n      \"@context\": {\n        \"common\": {\n          \"@id\": \"ns:common\",\n          \"@type\": \"xsd:string\"\n        },\n        \"logs\": \"ns:logs\"\n      }\n    },\n    \"CommonBlock\": {\n      \"@id\": \"ns:CommonBlock\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"LogRecord\": {\n      \"@id\": \"ns:LogRecord\",\n      \"@context\": {\n        \"timestamp\": {\n          \"@id\": \"ns:timestamp\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"level\": {\n          \"@id\": \"ns:level\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"logtype\": {\n          \"@id\": \"ns:logtype\",\n          \"@type\": \"xsd:string\"\n        },\n        \"attributes\": \"ns:attributes\"\n      }\n    },\n    \"AcceptedResponse\": {\n      \"@id\": \"ns:AcceptedResponse\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"ns:requestId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"ns:ErrorResponse\",\n      \"@context\": {\n        \"requestId\": {\n          \"@id\": \"ns:requestId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/new-relic/refs/heads/main/json-ld/new-relic-log-context.jsonld
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
