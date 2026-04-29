---
class_count: 0
classes: []
context_file: json-ld/servicenow-table-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-table-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Table from ServiceNow.
layout: jsonld
name: Servicenow Table Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Record
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 2
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-table-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Record\": {\n      \"@id\": \"ns:Record\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_on\": {\n          \"@id\": \"ns:sys_created_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_by\": {\n          \"@id\": \"ns:sys_created_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"ns:sys_updated_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_by\": {\n          \"@id\": \"ns:sys_updated_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_mod_count\": {\n          \"@id\": \"ns:sys_mod_count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sys_tags\": {\n          \"@id\": \"ns:sys_tags\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_class_name\": {\n          \"@id\": \"ns:sys_class_name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-table-context.jsonld
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
