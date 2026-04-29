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
context_file: json-ld/servicenow-service-catalog-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-service-catalog-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Servicenow Service Catalog from ServiceNow.
layout: jsonld
name: Servicenow Service Catalog Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Catalog
  type: ''
- container: ''
  name: Category
  type: ''
- container: ''
  name: CatalogItem
  type: ''
- container: ''
  name: CatalogItemDetail
  type: ''
- container: ''
  name: CatalogVariable
  type: ''
- container: ''
  name: CartItemInput
  type: ''
- container: ''
  name: CartItem
  type: ''
- container: ''
  name: Cart
  type: ''
- container: ''
  name: OrderResult
  type: ''
- container: ''
  name: Error
  type: ''
property_count: 10
provider_name: ServiceNow
provider_slug: servicenow
slug: servicenow-service-catalog-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"Catalog\": {\n      \"@id\": \"ns:Catalog\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"has_categories\": {\n          \"@id\": \"ns:has_categories\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"has_items\": {\n          \"@id\": \"ns:has_items\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"Category\": {\n      \"@id\": \"ns:Category\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n    \
  \    \"title\": {\n          \"@id\": \"ns:title\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"full_description\": {\n          \"@id\": \"ns:full_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"subcategories\": \"ns:subcategories\"\n      }\n    },\n    \"CatalogItem\": {\n      \"@id\": \"ns:CatalogItem\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"ns:price\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"picture\": {\n          \"@id\": \"ns:picture\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"CatalogItemDetail\": {\n      \"@id\": \"ns:CatalogItemDetail\",\n      \"@context\": {\n        \"sys_id\": {\n          \"@id\": \"ns:sys_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"short_description\": {\n          \"@id\": \"ns:short_description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"ns:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"ns:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"price\": {\n          \"@id\": \"ns:price\",\n          \"@type\": \"xsd:string\"\n        },\n        \"picture\": {\n          \"@id\": \"ns:picture\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"mandatory_attachment\": {\n          \"@id\": \"ns:mandatory_attachment\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"request_method\": {\n          \"@id\": \"ns:request_method\",\n          \"@type\": \"xsd:string\"\n        },\n        \"variables\": \"ns:variables\"\n      }\n    },\n    \"CatalogVariable\": {\n      \"@id\": \"ns:CatalogVariable\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"ns:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"ns:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"ns:type\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mandatory\": {\n          \"@id\": \"ns:mandatory\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"default_value\": {\n          \"@id\": \"ns:default_value\",\n          \"@type\": \"xsd:string\"\n     \
  \   },\n        \"choices\": \"ns:choices\"\n      }\n    },\n    \"CartItemInput\": {\n      \"@id\": \"ns:CartItemInput\",\n      \"@context\": {\n        \"sysparm_quantity\": {\n          \"@id\": \"ns:sysparm_quantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"variables\": \"ns:variables\"\n      }\n    },\n    \"CartItem\": {\n      \"@id\": \"ns:CartItem\",\n      \"@context\": {\n        \"cart_item_id\": {\n          \"@id\": \"ns:cart_item_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"catalog_item_id\": {\n          \"@id\": \"ns:catalog_item_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"quantity\": {\n          \"@id\": \"ns:quantity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"subtotal\": {\n          \"@id\": \"ns:subtotal\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Cart\": {\n      \"@id\": \"ns:Cart\",\n      \"@context\": {\n        \"items\": \"ns:items\",\n \
  \       \"subtotal\": {\n          \"@id\": \"ns:subtotal\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"OrderResult\": {\n      \"@id\": \"ns:OrderResult\",\n      \"@context\": {\n        \"request_number\": {\n          \"@id\": \"ns:request_number\",\n          \"@type\": \"xsd:string\"\n        },\n        \"request_id\": {\n          \"@id\": \"ns:request_id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"table\": {\n          \"@id\": \"ns:table\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Error\": {\n      \"@id\": \"ns:Error\",\n      \"@context\": {\n        \"error\": \"ns:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/servicenow/refs/heads/main/json-ld/servicenow-service-catalog-context.jsonld
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
