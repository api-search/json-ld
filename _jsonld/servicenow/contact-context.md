---
api_specs:
- filename: servicenow-table-api-openapi.yml
  format: yaml
  label: ServiceNow Table API
  slug: servicenow-table-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-table-api-openapi.yml
- filename: servicenow-aggregate-api-openapi.yml
  format: yaml
  label: ServiceNow Aggregate API
  slug: servicenow-aggregate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-aggregate-api-openapi.yml
- filename: servicenow-attachment-api-openapi.yml
  format: yaml
  label: ServiceNow Attachment API
  slug: servicenow-attachment-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-attachment-api-openapi.yml
- filename: servicenow-import-set-api-openapi.yml
  format: yaml
  label: ServiceNow Import Set API
  slug: servicenow-import-set-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-import-set-api-openapi.yml
- filename: servicenow-change-management-api-openapi.yml
  format: yaml
  label: ServiceNow Change Management API
  slug: servicenow-change-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-change-management-api-openapi.yml
- filename: servicenow-service-catalog-api-openapi.yml
  format: yaml
  label: ServiceNow Service Catalog API
  slug: servicenow-service-catalog-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-service-catalog-api-openapi.yml
- filename: servicenow-cmdb-instance-api-openapi.yml
  format: yaml
  label: ServiceNow CMDB Instance API
  slug: servicenow-cmdb-instance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/servicenow-cmdb-instance-api-openapi.yml
- filename: contact-api-openapi.yaml
  format: yaml
  label: ServiceNow Contact API
  slug: servicenow-contact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/contact-api-openapi.yaml
- filename: trouble-ticket-openapi.yaml
  format: yaml
  label: ServiceNow Trouble Ticket Open API
  slug: servicenow-trouble-ticket-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/openapi/trouble-ticket-openapi.yaml
- filename: servicenow-events-asyncapi.yml
  format: yaml
  label: ServiceNow Event Management Topic Open API
  slug: servicenow-event-management-topic-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/asyncapi/servicenow-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/contact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/contact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Contact from ServiceNow.
layout: jsonld
name: Contact Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Contact
  type: ''
- container: ''
  name: ContactCreate
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 3
provider_name: ServiceNow
provider_slug: servicenow
slug: contact-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Contact\": {\n      \"@id\": \"ns:Contact\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"first_name\": {\n          \"@id\": \"ns:first_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"middle_name\": {\n          \"@id\": \"ns:middle_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_name\": {\n          \"@id\": \"ns:last_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"user_name\": {\n          \"@id\": \"ns:user_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"phone\": {\n          \"@id\": \"ns:phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mobile_phone\": {\n          \"@id\": \"ns:mobile_phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"home_phone\": {\n          \"@id\": \"ns:home_phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employee_number\": {\n          \"@id\": \"ns:employee_number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"company\": {\n          \"@id\": \"ns:company\",\n          \"@type\": \"xsd:string\"\n        },\n        \"account\": {\n          \"@id\": \"ns:account\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"ns:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manager\": {\n          \"@id\": \"ns:manager\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"building\": {\n          \"@id\": \"ns:building\",\n          \"@type\": \"xsd:string\"\n        },\n        \"street\": {\n          \"@id\": \"ns:street\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"ns:city\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zip\": {\n          \"@id\": \"ns:zip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"ns:country\",\n          \"@type\": \"xsd:string\"\n        },\n        \"active\": {\n          \"@id\": \"ns:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"vip\": {\n          \"@id\": \"ns:vip\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"locked_out\": {\n  \
  \        \"@id\": \"ns:locked_out\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"web_service_access_only\": {\n          \"@id\": \"ns:web_service_access_only\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"internal_integration_user\": {\n          \"@id\": \"ns:internal_integration_user\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enable_multifactor_authn\": {\n          \"@id\": \"ns:enable_multifactor_authn\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"geolocation_tracked\": {\n          \"@id\": \"ns:geolocation_tracked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"notification\": {\n          \"@id\": \"ns:notification\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"calendar_integration\": {\n          \"@id\": \"ns:calendar_integration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"failed_attempts\": {\n          \"@id\": \"ns:failed_attempts\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"latitude\": {\n          \"@id\": \"ns:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"ns:longitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"time_zone\": {\n          \"@id\": \"ns:time_zone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"date_format\": {\n          \"@id\": \"ns:date_format\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time_format\": {\n          \"@id\": \"ns:time_format\",\n          \"@type\": \"xsd:string\"\n        },\n        \"preferred_language\": {\n          \"@id\": \"ns:preferred_language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"gender\": {\n          \"@id\": \"ns:gender\",\n          \"@type\": \"xsd:string\"\n        },\n        \"photo\": {\n          \"@id\": \"ns:photo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"introduction\": {\n          \"@id\": \"ns:introduction\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"ns:source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"roles\": {\n          \"@id\": \"ns:roles\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cost_center\": {\n          \"@id\": \"ns:cost_center\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schedule\": {\n          \"@id\": \"ns:schedule\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time_sheet_policy\": {\n          \"@id\": \"ns:time_sheet_policy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"default_perspective\": {\n          \"@id\": \"ns:default_perspective\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ldap_server\": {\n          \"@id\": \"ns:ldap_server\",\n          \"@type\": \"xsd:string\"\n        },\n        \"agent_status\": {\n          \"@id\": \"ns:agent_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  on_schedule\": {\n          \"@id\": \"ns:on_schedule\",\n          \"@type\": \"xsd:string\"\n        },\n        \"edu_status\": {\n          \"@id\": \"ns:edu_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_login\": {\n          \"@id\": \"ns:last_login\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_login_time\": {\n          \"@id\": \"ns:last_login_time\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_login_device\": {\n          \"@id\": \"ns:last_login_device\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_position_update\": {\n          \"@id\": \"ns:last_position_update\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_class_name\": {\n          \"@id\": \"ns:sys_class_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_by\": {\n          \"@id\": \"ns:sys_created_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_on\":\
  \ {\n          \"@id\": \"ns:sys_created_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_by\": {\n          \"@id\": \"ns:sys_updated_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"ns:sys_updated_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_mod_count\": {\n          \"@id\": \"ns:sys_mod_count\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"sys_domain\": {\n          \"@id\": \"ns:sys_domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_domain_path\": {\n          \"@id\": \"ns:sys_domain_path\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_tags\": {\n          \"@id\": \"ns:sys_tags\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"ContactCreate\": {\n      \"@id\": \"ns:ContactCreate\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"first_name\": {\n          \"@id\": \"ns:first_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"middle_name\": {\n          \"@id\": \"ns:middle_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_name\": {\n          \"@id\": \"ns:last_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"user_name\": {\n          \"@id\": \"ns:user_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"ns:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phone\": {\n          \"@id\": \"ns:phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mobile_phone\": {\n          \"@id\": \"ns:mobile_phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"home_phone\": {\n          \"@id\": \"ns:home_phone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"employee_number\": {\n          \"@id\": \"ns:employee_number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"company\": {\n          \"@id\": \"ns:company\",\n          \"@type\": \"xsd:string\"\n        },\n        \"account\": {\n          \"@id\": \"ns:account\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"ns:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manager\": {\n          \"@id\": \"ns:manager\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"building\": {\n          \"@id\": \"ns:building\",\n          \"@type\": \"xsd:string\"\n        },\n        \"street\": {\n          \"@id\": \"ns:street\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"ns:city\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"zip\": {\n          \"@id\": \"ns:zip\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"ns:country\",\n          \"@type\": \"xsd:string\"\n        },\n        \"active\": {\n          \"@id\": \"ns:active\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"vip\": {\n          \"@id\": \"ns:vip\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"locked_out\": {\n          \"@id\": \"ns:locked_out\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"web_service_access_only\": {\n          \"@id\": \"ns:web_service_access_only\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"internal_integration_user\": {\n          \"@id\": \"ns:internal_integration_user\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enable_multifactor_authn\": {\n          \"@id\"\
  : \"ns:enable_multifactor_authn\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"geolocation_tracked\": {\n          \"@id\": \"ns:geolocation_tracked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"notification\": {\n          \"@id\": \"ns:notification\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"calendar_integration\": {\n          \"@id\": \"ns:calendar_integration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"failed_attempts\": {\n          \"@id\": \"ns:failed_attempts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"latitude\": {\n          \"@id\": \"ns:latitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"longitude\": {\n          \"@id\": \"ns:longitude\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"time_zone\": {\n          \"@id\": \"ns:time_zone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"date_format\": {\n          \"@id\": \"ns:date_format\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"time_format\": {\n          \"@id\": \"ns:time_format\",\n          \"@type\": \"xsd:string\"\n        },\n        \"preferred_language\": {\n          \"@id\": \"ns:preferred_language\",\n          \"@type\": \"xsd:string\"\n        },\n        \"gender\": {\n          \"@id\": \"ns:gender\",\n          \"@type\": \"xsd:string\"\n        },\n        \"photo\": {\n          \"@id\": \"ns:photo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"introduction\": {\n          \"@id\": \"ns:introduction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"source\": {\n          \"@id\": \"ns:source\",\n          \"@type\": \"xsd:string\"\n        },\n        \"roles\": {\n          \"@id\": \"ns:roles\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cost_center\": {\n          \"@id\": \"ns:cost_center\",\n          \"@type\": \"xsd:string\"\n        },\n        \"schedule\": {\n          \"@id\"\
  : \"ns:schedule\",\n          \"@type\": \"xsd:string\"\n        },\n        \"time_sheet_policy\": {\n          \"@id\": \"ns:time_sheet_policy\",\n          \"@type\": \"xsd:string\"\n        },\n        \"default_perspective\": {\n          \"@id\": \"ns:default_perspective\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ldap_server\": {\n          \"@id\": \"ns:ldap_server\",\n          \"@type\": \"xsd:string\"\n        },\n        \"agent_status\": {\n          \"@id\": \"ns:agent_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"on_schedule\": {\n          \"@id\": \"ns:on_schedule\",\n          \"@type\": \"xsd:string\"\n        },\n        \"edu_status\": {\n          \"@id\": \"ns:edu_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_login_time\": {\n          \"@id\": \"ns:last_login_time\",\n          \"@type\": \"xsd:string\"\n        },\n        \"last_login_device\": {\n          \"@id\": \"ns:last_login_device\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"social_channel\": {\n          \"@id\": \"ns:social_channel\",\n          \"@type\": \"xsd:string\"\n        },\n        \"social_handle\": {\n          \"@id\": \"ns:social_handle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"social_handle_url\": {\n          \"@id\": \"ns:social_handle_url\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/contact-context.jsonld
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
