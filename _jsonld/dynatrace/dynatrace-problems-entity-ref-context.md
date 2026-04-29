---
class_count: 1
classes:
- EntityRef
context_file: json-ld/dynatrace-problems-entity-ref-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-entity-ref-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Dynatrace Problems Entity Ref from Dynatrace.
layout: jsonld
name: Dynatrace Problems Entity Ref Context
namespaces:
- prefix: dt
  uri: https://dt.dynatrace.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: entityId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: type
  type: string
property_count: 3
provider_name: Dynatrace
provider_slug: dynatrace
slug: dynatrace-problems-entity-ref-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"dt\": \"https://dt.dynatrace.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EntityRef\": \"dt:EntityRef\",\n    \"entityId\": {\n      \"@id\": \"dt:entityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dt:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/dynatrace/refs/heads/main/json-ld/dynatrace-problems-entity-ref-context.jsonld
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
