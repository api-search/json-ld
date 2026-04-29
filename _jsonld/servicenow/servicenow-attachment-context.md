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
context_file: json-ld/servicenow-attachment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-attachment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Attachment from ServiceNow.
layout: jsonld
name: Servicenow Attachment Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Attachment
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 2
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-attachment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Attachment\": {\n      \"@id\": \"ns:Attachment\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"file_name\": {\n          \"@id\": \"ns:file_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"table_name\": {\n          \"@id\": \"ns:table_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"table_sys_id\": {\n          \"@id\": \"ns:table_sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"content_type\": {\n          \"@id\": \"ns:content_type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size_bytes\": {\n          \"@id\": \"ns:size_bytes\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"size_compressed\": {\n          \"@id\": \"ns:size_compressed\",\n\
  \          \"@type\": \"xsd:integer\"\n        },\n        \"download_link\": {\n          \"@id\": \"ns:download_link\",\n          \"@type\": \"xsd:string\"\n        },\n        \"image_height\": {\n          \"@id\": \"ns:image_height\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"image_width\": {\n          \"@id\": \"ns:image_width\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hash\": {\n          \"@id\": \"ns:hash\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"ns:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_on\": {\n          \"@id\": \"ns:sys_created_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_by\": {\n          \"@id\": \"ns:sys_created_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"ns:sys_updated_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_by\"\
  : {\n          \"@id\": \"ns:sys_updated_by\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-attachment-context.jsonld
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
