---
api_specs:
- filename: sap-business-one-service-layer-openapi.yml
  format: yaml
  label: SAP Business One Service Layer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-business-one-service-layer-openapi.yml
- filename: sap-s4hana-cloud-business-partner-openapi.yml
  format: yaml
  label: SAP S/4HANA Cloud API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-s4hana-cloud-business-partner-openapi.yml
- filename: sap-event-mesh-asyncapi.yml
  format: yaml
  label: SAP Event Mesh API
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/asyncapi/sap-event-mesh-asyncapi.yml
- filename: sap-ai-core-openapi.yml
  format: yaml
  label: SAP AI Core API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/openapi/sap-ai-core-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sap-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/json-ld/sap-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sap from SAP.
layout: jsonld
name: Sap Context
namespaces:
- prefix: sap
  uri: https://api.sap.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: BusinessPartner
  type: ''
- container: ''
  name: Address
  type: ''
- container: ''
  name: SalesOrder
  type: ''
- container: ''
  name: SalesOrderItem
  type: ''
- container: ''
  name: PurchaseOrder
  type: ''
- container: ''
  name: Material
  type: ''
- container: ''
  name: JournalEntry
  type: ''
- container: ''
  name: Employee
  type: ''
property_count: 8
provider_name: SAP
provider_slug: sap
slug: sap-context
source_filename: sap-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sap\": \"https://api.sap.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"BusinessPartner\": {\n      \"@id\": \"sap:BusinessPartner\",\n      \"@context\": {\n        \"businessPartnerNumber\": \"sap:BusinessPartner\",\n        \"fullName\": \"schema:name\",\n        \"category\": \"sap:BusinessPartnerCategory\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"organizationName\": \"schema:legalName\",\n        \"language\": \"schema:inLanguage\",\n        \"industry\": \"sap:Industry\",\n        \"email\": \"schema:email\",\n        \"telephone\": \"schema:telephone\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:date\"\n        },\n        \"modifiedAt\": {\n          \"@id\": \"dcterms:modified\",\n \
  \         \"@type\": \"xsd:date\"\n        },\n        \"addresses\": {\n          \"@id\": \"schema:address\",\n          \"@container\": \"@set\"\n        },\n        \"roles\": {\n          \"@id\": \"sap:BusinessPartnerRole\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"country\": \"schema:addressCountry\",\n        \"region\": \"schema:addressRegion\",\n        \"city\": \"schema:addressLocality\",\n        \"postalCode\": \"schema:postalCode\",\n        \"street\": \"schema:streetAddress\",\n        \"houseNumber\": \"sap:HouseNumber\"\n      }\n    },\n\n    \"SalesOrder\": {\n      \"@id\": \"sap:SalesOrder\",\n      \"@context\": {\n        \"salesOrderNumber\": \"schema:orderNumber\",\n        \"orderType\": \"sap:SalesOrderType\",\n        \"customer\": {\n          \"@id\": \"schema:customer\",\n          \"@type\": \"@id\"\n        },\n        \"orderDate\"\
  : {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"deliveryDate\": {\n          \"@id\": \"sap:RequestedDeliveryDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": \"schema:totalPrice\",\n        \"currency\": \"schema:priceCurrency\",\n        \"items\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"SalesOrderItem\": {\n      \"@id\": \"sap:SalesOrderItem\",\n      \"@context\": {\n        \"itemNumber\": \"schema:position\",\n        \"material\": \"sap:Material\",\n        \"description\": \"schema:description\",\n        \"quantity\": \"schema:amount\",\n        \"unitOfMeasure\": \"schema:unitCode\",\n        \"netAmount\": \"schema:price\",\n        \"plant\": \"sap:Plant\"\n      }\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"sap:PurchaseOrder\",\n      \"@context\": {\n        \"purchaseOrderNumber\": \"schema:orderNumber\"\
  ,\n        \"orderType\": \"sap:PurchaseOrderType\",\n        \"supplier\": {\n          \"@id\": \"schema:seller\",\n          \"@type\": \"@id\"\n        },\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": \"schema:totalPrice\",\n        \"currency\": \"schema:priceCurrency\"\n      }\n    },\n\n    \"Material\": {\n      \"@id\": \"sap:Material\",\n      \"@context\": {\n        \"materialNumber\": \"schema:sku\",\n        \"description\": \"schema:name\",\n        \"materialType\": \"sap:MaterialType\",\n        \"baseUnit\": \"schema:unitCode\",\n        \"weight\": \"schema:weight\",\n        \"volume\": \"sap:Volume\"\n      }\n    },\n\n    \"JournalEntry\": {\n      \"@id\": \"sap:JournalEntry\",\n      \"@context\": {\n        \"documentNumber\": \"schema:identifier\",\n        \"referenceDate\": {\n          \"@id\": \"dcterms:date\",\n          \"@type\": \"xsd:date\"\n        },\n \
  \       \"postingDate\": {\n          \"@id\": \"sap:PostingDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"memo\": \"schema:description\",\n        \"lines\": {\n          \"@id\": \"sap:JournalEntryLine\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Employee\": {\n      \"@id\": \"sap:Employee\",\n      \"@context\": {\n        \"employeeId\": \"schema:identifier\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"department\": \"schema:department\",\n        \"hireDate\": {\n          \"@id\": \"sap:HireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"manager\": {\n          \"@id\": \"schema:colleague\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sap/refs/heads/main/json-ld/sap-context.jsonld
tags:
- AI
- BTP
- Business Applications
- Cloud
- Data Management
- Enterprise
- ERP
- Integration
- JSON-LD
- Linked Data
- Semantic Web
---
