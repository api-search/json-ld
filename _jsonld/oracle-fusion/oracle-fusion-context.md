---
api_specs:
- filename: api-rest-api.html
  format: yaml
  label: Oracle Fusion ERP REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/financials/22r3/farfa/api-rest-api.html
- filename: api-rest-api.html
  format: yaml
  label: Oracle Fusion HCM REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/human-resources/22r3/farws/api-rest-api.html
- filename: api-rest-api.html
  format: yaml
  label: Oracle Fusion SCM REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/supply-chain-management/22r3/fasrs/api-rest-api.html
- filename: rest-api.html
  format: yaml
  label: Oracle Fusion CX Sales and Fusion Service REST API
  slug: ''
  spec_type: OpenAPI
  url: https://docs.oracle.com/en/cloud/saas/cx-sales/rest-api.html
- filename: oracle-fusion-common-openapi.yml
  format: yaml
  label: Oracle Fusion Common Features REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/openapi/oracle-fusion-common-openapi.yml
- filename: oracle-fusion-project-management-openapi.yml
  format: yaml
  label: Oracle Fusion Project Management REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/openapi/oracle-fusion-project-management-openapi.yml
- filename: oracle-fusion-epm-openapi.yml
  format: yaml
  label: Oracle Fusion EPM REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/openapi/oracle-fusion-epm-openapi.yml
class_count: 0
classes: []
context_file: json-ld/oracle-fusion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/json-ld/oracle-fusion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Oracle Fusion from Oracle Fusion Cloud Applications.
layout: jsonld
name: Oracle Fusion Context
namespaces:
- prefix: orafusion
  uri: https://docs.oracle.com/schemas/oracle-fusion/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: Payment
  type: ''
- container: ''
  name: Worker
  type: ''
- container: ''
  name: Assignment
  type: ''
- container: ''
  name: SalesOrder
  type: ''
- container: ''
  name: PurchaseOrder
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Opportunity
  type: ''
- container: ''
  name: ServiceRequest
  type: ''
- container: ''
  name: ExpenseReport
  type: ''
- container: ''
  name: Item
  type: ''
property_count: 12
provider_name: Oracle Fusion Cloud Applications
provider_slug: oracle-fusion
slug: oracle-fusion-context
source_filename: oracle-fusion-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"orafusion\": \"https://docs.oracle.com/schemas/oracle-fusion/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Invoice\": {\n      \"@id\": \"orafusion:Invoice\",\n      \"@context\": {\n        \"invoiceNumber\": \"orafusion:invoiceNumber\",\n        \"invoiceAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"invoiceCurrencyCode\": \"schema:priceCurrency\",\n        \"invoiceDate\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:date\"\n        },\n        \"invoiceType\": \"orafusion:invoiceType\",\n        \"vendorName\": \"schema:name\",\n        \"businessUnit\": \"orafusion:businessUnit\",\n        \"description\": \"schema:description\",\n        \"paymentTerms\": \"orafusion:paymentTerms\",\n        \"dueDate\": {\n   \
  \       \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"approvalStatus\": \"orafusion:approvalStatus\",\n        \"paidAmount\": {\n          \"@id\": \"orafusion:paidAmount\",\n          \"@type\": \"xsd:decimal\"\n        }\n      }\n    },\n\n    \"Payment\": {\n      \"@id\": \"orafusion:Payment\",\n      \"@context\": {\n        \"paymentNumber\": \"orafusion:paymentNumber\",\n        \"paymentAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"paymentDate\": {\n          \"@id\": \"schema:paymentDueDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"paymentMethod\": \"schema:paymentMethod\",\n        \"vendorName\": \"schema:name\",\n        \"status\": \"orafusion:status\"\n      }\n    },\n\n    \"Worker\": {\n      \"@id\": \"orafusion:Worker\",\n      \"@context\": {\n        \"personNumber\": \"orafusion:personNumber\",\n        \"firstName\": \"schema:givenName\"\
  ,\n        \"lastName\": \"schema:familyName\",\n        \"displayName\": \"schema:name\",\n        \"dateOfBirth\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"workEmail\": \"schema:email\",\n        \"workPhoneNumber\": \"schema:telephone\",\n        \"hireDate\": {\n          \"@id\": \"orafusion:hireDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"workerType\": \"orafusion:workerType\"\n      }\n    },\n\n    \"Assignment\": {\n      \"@id\": \"orafusion:Assignment\",\n      \"@context\": {\n        \"assignmentNumber\": \"orafusion:assignmentNumber\",\n        \"businessUnitName\": \"orafusion:businessUnit\",\n        \"departmentName\": \"orafusion:department\",\n        \"jobName\": \"schema:jobTitle\",\n        \"positionName\": \"orafusion:position\",\n        \"locationName\": \"schema:workLocation\",\n        \"managerDisplayName\": \"orafusion:manager\",\n        \"assignmentStatus\": \"orafusion:status\"\
  ,\n        \"effectiveStartDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"SalesOrder\": {\n      \"@id\": \"orafusion:SalesOrder\",\n      \"@context\": {\n        \"orderNumber\": \"schema:orderNumber\",\n        \"orderType\": \"orafusion:orderType\",\n        \"customerName\": \"schema:name\",\n        \"businessUnit\": \"orafusion:businessUnit\",\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currencyCode\": \"schema:priceCurrency\",\n        \"status\": \"schema:orderStatus\"\n      }\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"orafusion:PurchaseOrder\",\n      \"@context\": {\n        \"orderNumber\": \"schema:orderNumber\",\n        \"supplierName\": \"schema:name\",\n        \"buyerName\": \"orafusion:buyer\"\
  ,\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currencyCode\": \"schema:priceCurrency\",\n        \"status\": \"schema:orderStatus\"\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"orafusion:Account\",\n      \"@context\": {\n        \"organizationName\": \"schema:name\",\n        \"industry\": \"schema:industry\",\n        \"annualRevenue\": {\n          \"@id\": \"orafusion:annualRevenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"numberOfEmployees\": {\n          \"@id\": \"schema:numberOfEmployees\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"phoneNumber\": \"schema:telephone\",\n        \"emailAddress\": \"schema:email\",\n        \"url\": \"schema:url\",\n        \"status\": \"orafusion:status\"\n      }\n    },\n\n    \"Contact\": {\n\
  \      \"@id\": \"orafusion:Contact\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"fullName\": \"schema:name\",\n        \"jobTitle\": \"schema:jobTitle\",\n        \"emailAddress\": \"schema:email\",\n        \"workPhoneNumber\": \"schema:telephone\",\n        \"accountName\": \"orafusion:accountName\"\n      }\n    },\n\n    \"Opportunity\": {\n      \"@id\": \"orafusion:Opportunity\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"accountName\": \"orafusion:accountName\",\n        \"ownerName\": \"orafusion:owner\",\n        \"salesStage\": \"orafusion:salesStage\",\n        \"winProbability\": {\n          \"@id\": \"orafusion:winProbability\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"revenue\": {\n          \"@id\": \"orafusion:revenue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"closeDate\": {\n          \"@id\": \"orafusion:closeDate\",\n\
  \          \"@type\": \"xsd:date\"\n        },\n        \"status\": \"orafusion:status\"\n      }\n    },\n\n    \"ServiceRequest\": {\n      \"@id\": \"orafusion:ServiceRequest\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"problemDescription\": \"schema:description\",\n        \"accountName\": \"orafusion:accountName\",\n        \"severity\": \"orafusion:severity\",\n        \"status\": \"orafusion:status\",\n        \"assigneeName\": \"orafusion:assignee\",\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolvedDate\": {\n          \"@id\": \"orafusion:resolvedDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ExpenseReport\": {\n      \"@id\": \"orafusion:ExpenseReport\",\n      \"@context\": {\n        \"purpose\": \"schema:description\",\n        \"personName\": \"schema:name\",\n        \"businessUnit\": \"orafusion:businessUnit\",\n  \
  \      \"totalAmount\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currencyCode\": \"schema:priceCurrency\",\n        \"approvalStatus\": \"orafusion:approvalStatus\",\n        \"submittedDate\": {\n          \"@id\": \"dcterms:dateSubmitted\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Item\": {\n      \"@id\": \"orafusion:Item\",\n      \"@context\": {\n        \"itemNumber\": \"schema:sku\",\n        \"itemDescription\": \"schema:description\",\n        \"itemType\": \"orafusion:itemType\",\n        \"unitOfMeasure\": \"orafusion:unitOfMeasure\",\n        \"listPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"itemStatus\": \"orafusion:status\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/oracle-fusion/refs/heads/main/json-ld/oracle-fusion-context.jsonld
tags:
- Cloud
- CX
- Enterprise
- EPM
- ERP
- HCM
- Project Management
- REST API
- SaaS
- SCM
- JSON-LD
- Linked Data
- Semantic Web
---
