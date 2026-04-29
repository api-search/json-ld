---
class_count: 0
classes: []
context_file: json-ld/servicenow-aggregate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-aggregate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Aggregate from ServiceNow.
layout: jsonld
name: Servicenow Aggregate Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: AggregateResult
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 2
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-aggregate-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"AggregateResult\": {\n      \"@id\": \"ns:AggregateResult\",\n      \"@context\": {\n        \"stats\": \"ns:stats\",\n        \"group_by\": \"ns:group_by\"\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-aggregate-context.jsonld
tags:
- Automation
- Cloud Services
- Digital Workflows
- Enterprise Platform
- IT Service Management
- ITSM
- Processes
- T1
- Workflow Automation
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
