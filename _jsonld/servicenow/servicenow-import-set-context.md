---
class_count: 0
classes: []
context_file: json-ld/servicenow-import-set-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-import-set-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Import Set from ServiceNow.
layout: jsonld
name: Servicenow Import Set Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ImportSetResult
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 2
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-import-set-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ImportSetResult\": {\n      \"@id\": \"ns:ImportSetResult\",\n      \"@context\": {\n        \"transform_map\": {\n          \"@id\": \"ns:transform_map\",\n          \"@type\": \"xsd:string\"\n        },\n        \"table\": {\n          \"@id\": \"ns:table\",\n          \"@type\": \"xsd:string\"\n        },\n        \"display_name\": {\n          \"@id\": \"ns:display_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"display_value\": {\n          \"@id\": \"ns:display_value\",\n          \"@type\": \"xsd:string\"\n        },\n        \"record_link\": {\n          \"@id\": \"ns:record_link\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"ns:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status_message\": {\n          \"@id\": \"ns:status_message\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"target_sys_id\": {\n          \"@id\": \"ns:target_sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"import_set\": {\n          \"@id\": \"ns:import_set\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-import-set-context.jsonld
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
