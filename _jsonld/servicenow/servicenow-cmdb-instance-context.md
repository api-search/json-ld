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
context_file: json-ld/servicenow-cmdb-instance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-cmdb-instance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Cmdb Instance from ServiceNow.
layout: jsonld
name: Servicenow Cmdb Instance Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: CmdbInstanceSummary
  type: ''
- container: ''
  name: CmdbInstance
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 3
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-cmdb-instance-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"CmdbInstanceSummary\": {\n      \"@id\": \"ns:CmdbInstanceSummary\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CmdbInstance\": {\n      \"@id\": \"ns:CmdbInstance\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_class_name\": {\n          \"@id\": \"ns:sys_class_name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n    \
  \    },\n        \"subcategory\": {\n          \"@id\": \"ns:subcategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operational_status\": {\n          \"@id\": \"ns:operational_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"install_status\": {\n          \"@id\": \"ns:install_status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serial_number\": {\n          \"@id\": \"ns:serial_number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"asset_tag\": {\n          \"@id\": \"ns:asset_tag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ip_address\": {\n          \"@id\": \"ns:ip_address\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mac_address\": {\n          \"@id\": \"ns:mac_address\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dns_domain\": {\n          \"@id\": \"ns:dns_domain\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fqdn\": {\n          \"@id\"\
  : \"ns:fqdn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"os\": {\n          \"@id\": \"ns:os\",\n          \"@type\": \"xsd:string\"\n        },\n        \"os_version\": {\n          \"@id\": \"ns:os_version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"manufacturer\": {\n          \"@id\": \"ns:manufacturer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"model_id\": {\n          \"@id\": \"ns:model_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"location\": {\n          \"@id\": \"ns:location\",\n          \"@type\": \"xsd:string\"\n        },\n        \"department\": {\n          \"@id\": \"ns:department\",\n          \"@type\": \"xsd:string\"\n        },\n        \"company\": {\n          \"@id\": \"ns:company\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assigned_to\": {\n          \"@id\": \"ns:assigned_to\",\n          \"@type\": \"xsd:string\"\n        },\n        \"managed_by\": {\n          \"\
  @id\": \"ns:managed_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"owned_by\": {\n          \"@id\": \"ns:owned_by\",\n          \"@type\": \"xsd:string\"\n        },\n        \"support_group\": {\n          \"@id\": \"ns:support_group\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_created_on\": {\n          \"@id\": \"ns:sys_created_on\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sys_updated_on\": {\n          \"@id\": \"ns:sys_updated_on\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-cmdb-instance-context.jsonld
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
