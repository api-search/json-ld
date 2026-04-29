---
class_count: 0
classes: []
context_file: json-ld/servicenow-change-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-change-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Change Management from ServiceNow.
layout: jsonld
name: Servicenow Change Management Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: ChangeRequest
  type: ''
- container: ''
  name: ChangeRequestInput
  type: ''
- container: ''
  name: ChangeTask
  type: ''
- container: ''
  name: ChangeTaskInput
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 5
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-change-management-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ChangeRequest\": {\n      \"@id\": \"ns:ChangeRequest\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"ns:number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"ns:priority\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"risk\": {\n          \"@id\": \"ns:risk\",\n          \"@type\": \"xsd:string\"\n        },\n        \"impact\": {\n          \"@id\": \"ns:impact\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"ns:assigned_to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignment_group\": {\n          \"@id\": \"ns:assignment_group\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requested_by\": {\n          \"@id\": \"ns:requested_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_date\": {\n          \"@id\": \"ns:start_date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"end_date\": {\n          \"@id\": \"ns:end_date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cmdb_ci\": {\n          \"@id\": \"ns:cmdb_ci\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"close_code\": {\n          \"@id\": \"ns:close_code\",\n          \"@type\": \"xsd:string\"\n        },\n        \"close_notes\": {\n          \"@id\": \"ns:close_notes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"approval\": {\n          \"@id\": \"ns:approval\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_on\": {\n          \"@id\": \"ns:sys_created_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"ns:sys_updated_on\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ChangeRequestInput\": {\n      \"@id\": \"ns:ChangeRequestInput\",\n      \"@context\": {\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\":\
  \ {\n          \"@id\": \"ns:priority\",\n          \"@type\": \"xsd:string\"\n        },\n        \"risk\": {\n          \"@id\": \"ns:risk\",\n          \"@type\": \"xsd:string\"\n        },\n        \"impact\": {\n          \"@id\": \"ns:impact\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"ns:assigned_to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignment_group\": {\n          \"@id\": \"ns:assignment_group\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requested_by\": {\n          \"@id\": \"ns:requested_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"start_date\": {\n          \"@id\": \"ns:start_date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"end_date\": {\n          \"@id\": \"ns:end_date\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"cmdb_ci\": {\n          \"@id\": \"ns:cmdb_ci\",\n          \"@type\": \"xsd:string\"\n        },\n        \"justification\": {\n          \"@id\": \"ns:justification\",\n          \"@type\": \"xsd:string\"\n        },\n        \"implementation_plan\": {\n          \"@id\": \"ns:implementation_plan\",\n          \"@type\": \"xsd:string\"\n        },\n        \"backout_plan\": {\n          \"@id\": \"ns:backout_plan\",\n          \"@type\": \"xsd:string\"\n        },\n        \"test_plan\": {\n          \"@id\": \"ns:test_plan\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ChangeTask\": {\n      \"@id\": \"ns:ChangeTask\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"ns:number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"ns:assigned_to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"change_request\": {\n          \"@id\": \"ns:change_request\",\n          \"@type\": \"xsd:string\"\n        },\n        \"planned_start_date\": {\n          \"@id\": \"ns:planned_start_date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"planned_end_date\": {\n          \"@id\": \"ns:planned_end_date\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ChangeTaskInput\": {\n      \"@id\": \"ns:ChangeTaskInput\",\n      \"@context\": {\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n      \
  \  \"assigned_to\": {\n          \"@id\": \"ns:assigned_to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignment_group\": {\n          \"@id\": \"ns:assignment_group\",\n          \"@type\": \"xsd:string\"\n        },\n        \"planned_start_date\": {\n          \"@id\": \"ns:planned_start_date\",\n          \"@type\": \"xsd:string\"\n        },\n        \"planned_end_date\": {\n          \"@id\": \"ns:planned_end_date\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-change-management-context.jsonld
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
