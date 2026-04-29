---
class_count: 0
classes: []
context_file: json-ld/dynatrace-events-v2-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-events-v2-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Events V2 from Dynatrace.
layout: jsonld
name: Dynatrace Events V2 Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: EventIngestPayload
  type: ''
- container: ''
  name: EventIngestResult
  type: ''
- container: ''
  name: EventIngestResultItem
  type: ''
- container: ''
  name: Event
  type: ''
- container: ''
  name: EventCollection
  type: ''
- container: ''
  name: EntityStub
  type: ''
- container: ''
  name: ErrorEnvelope
  type: ''
- container: ''
  name: Error
  type: ''
- container: ''
  name: ConstraintViolation
  type: ''
property_count: 9
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-events-v2-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"EventIngestPayload\": {\n      \"@id\": \"ns:EventIngestPayload\",\n      \"@context\": {\n        \"eventType\": {\n          \"@id\": \"ns:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeout\": {\n          \"@id\": \"ns:timeout\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"entitySelector\": {\n          \"@id\": \"ns:entitySelector\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"ns:startTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endTime\": {\n          \"@id\": \"ns:endTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"properties\": \"ns:properties\"\n      }\n    },\n    \"EventIngestResult\"\
  : {\n      \"@id\": \"ns:EventIngestResult\",\n      \"@context\": {\n        \"reportCount\": {\n          \"@id\": \"ns:reportCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventIngestResults\": \"ns:eventIngestResults\"\n      }\n    },\n    \"EventIngestResultItem\": {\n      \"@id\": \"ns:EventIngestResultItem\",\n      \"@context\": {\n        \"eventId\": {\n          \"@id\": \"ns:eventId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Event\": {\n      \"@id\": \"ns:Event\",\n      \"@context\": {\n        \"eventId\": {\n          \"@id\": \"ns:eventId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"eventType\": {\n          \"@id\": \"ns:eventType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n  \
  \      \"startTime\": {\n          \"@id\": \"ns:startTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"endTime\": {\n          \"@id\": \"ns:endTime\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"entityId\": {\n          \"@id\": \"ns:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"properties\": \"ns:properties\",\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"EventCollection\": {\n      \"@id\": \"ns:EventCollection\",\n      \"@context\": {\n        \"nextPageKey\": {\n          \"@id\": \"ns:nextPageKey\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalCount\": {\n          \"@id\": \"ns:totalCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"pageSize\": {\n          \"@id\": \"ns:pageSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"events\": \"ns:events\"\n      }\n    },\n    \"EntityStub\"\
  : {\n      \"@id\": \"ns:EntityStub\",\n      \"@context\": {\n        \"entityId\": {\n          \"@id\": \"ns:entityId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ErrorEnvelope\": {\n      \"@id\": \"ns:ErrorEnvelope\",\n      \"@context\": {\n        \"error\": {\n          \"@id\": \"ns:error\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"code\": {\n          \"@id\": \"ns:code\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"constraintViolations\": \"ns:constraintViolations\"\n      }\n    },\n    \"ConstraintViolation\": {\n\
  \      \"@id\": \"ns:ConstraintViolation\",\n      \"@context\": {\n        \"path\": {\n          \"@id\": \"ns:path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"message\": {\n          \"@id\": \"ns:message\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameterLocation\": {\n          \"@id\": \"ns:parameterLocation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-events-v2-context.jsonld
tags:
- AI Operations
- Analytics
- APM
- Application Performance Monitoring
- Application Security
- Automation
- Cloud Monitoring
- Digital Experience Management
- Intelligence
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
