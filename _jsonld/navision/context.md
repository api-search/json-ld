---
api_specs:
- filename: business-central-api-v2.yml
  format: yaml
  label: Business Central API v2.0
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/openapi/business-central-api-v2.yml
- filename: admin-center-api.yml
  format: yaml
  label: Business Central Administration Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/openapi/admin-center-api.yml
- filename: automation-api.yml
  format: yaml
  label: Business Central Automation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/openapi/automation-api.yml
class_count: 0
classes: []
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Microsoft Dynamics NAV.
layout: jsonld
name: context Context
namespaces:
- prefix: bc
  uri: https://api.businesscentral.dynamics.com/v2.0/schema/
- prefix: nav
  uri: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/resources/
- prefix: odata
  uri: http://www.odata.org/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Company
  type: ''
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Vendor
  type: ''
- container: ''
  name: Item
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
  name: Employee
  type: ''
- container: ''
  name: Environment
  type: ''
property_count: 9
provider_name: Microsoft Dynamics NAV
provider_slug: navision
slug: context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bc\": \"https://api.businesscentral.dynamics.com/v2.0/schema/\",\n    \"nav\": \"https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/resources/\",\n    \"odata\": \"http://www.odata.org/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Company\": {\n      \"@id\": \"bc:Company\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:companyId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:legalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"businessProfileId\": {\n          \"@id\": \"bc:businessProfileId\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Customer\": {\n      \"@id\": \"bc:Customer\",\n      \"@context\"\
  : {\n        \"id\": {\n          \"@id\": \"bc:customerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"bc:customerNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"bc:customerType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"addressLine1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"phoneNumber\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"balanceDue\": {\n          \"@id\": \"bc:balanceDue\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"creditLimit\": {\n          \"@id\": \"bc:creditLimit\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"taxLiable\": {\n          \"@id\": \"bc:taxLiable\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"taxRegistrationNumber\": {\n          \"@id\": \"schema:taxID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastModifiedDateTime\"\
  : {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Vendor\": {\n      \"@id\": \"bc:Vendor\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:vendorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"bc:vendorNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"addressLine1\": {\n          \"@id\": \"schema:streetAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"city\": {\n          \"@id\": \"schema:addressLocality\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"schema:addressRegion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"postalCode\": {\n          \"@id\": \"schema:postalCode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phoneNumber\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"website\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"taxRegistrationNumber\": {\n          \"@id\": \"schema:taxID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"balance\": {\n          \"@id\": \"bc:vendorBalance\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Item\": {\n      \"@id\": \"\
  bc:Item\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:itemId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"schema:sku\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"bc:itemType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"gtin\": {\n          \"@id\": \"schema:gtin\",\n          \"@type\": \"xsd:string\"\n        },\n        \"inventory\": {\n          \"@id\": \"bc:inventoryQuantity\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unitPrice\": {\n          \"@id\": \"schema:price\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"unitCost\": {\n          \"@id\": \"bc:unitCost\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"baseUnitOfMeasureCode\": {\n          \"@id\": \"bc:unitOfMeasure\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"itemCategoryCode\": {\n          \"@id\": \"schema:category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blocked\": {\n          \"@id\": \"bc:blocked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SalesOrder\": {\n      \"@id\": \"bc:SalesOrder\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:salesOrderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"customerId\": {\n          \"@id\": \"bc:customerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"customerName\": {\n\
  \          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalAmountExcludingTax\": {\n          \"@id\": \"bc:totalAmountExcludingTax\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalTaxAmount\": {\n          \"@id\": \"bc:totalTaxAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalAmountIncludingTax\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedDeliveryDate\": {\n          \"@id\": \"schema:deliveryDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"salesOrderLines\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@list\"\n        },\n        \"lastModifiedDateTime\"\
  : {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PurchaseOrder\": {\n      \"@id\": \"bc:PurchaseOrder\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:purchaseOrderId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"schema:orderNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"orderDate\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"vendorId\": {\n          \"@id\": \"bc:vendorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vendorName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"currencyCode\": {\n          \"@id\": \"schema:priceCurrency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalAmountExcludingTax\": {\n          \"@id\": \"bc:totalAmountExcludingTax\",\n          \"\
  @type\": \"xsd:decimal\"\n        },\n        \"totalTaxAmount\": {\n          \"@id\": \"bc:totalTaxAmount\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"totalAmountIncludingTax\": {\n          \"@id\": \"schema:totalPrice\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"status\": {\n          \"@id\": \"schema:orderStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"requestedReceiptDate\": {\n          \"@id\": \"bc:requestedReceiptDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"purchaseOrderLines\": {\n          \"@id\": \"schema:orderedItem\",\n          \"@container\": \"@list\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Account\": {\n      \"@id\": \"bc:Account\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:accountId\",\n          \"@type\": \"xsd:string\"\n       \
  \ },\n        \"number\": {\n          \"@id\": \"bc:accountNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"bc:accountCategory\",\n          \"@type\": \"xsd:string\"\n        },\n        \"accountType\": {\n          \"@id\": \"bc:accountType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"blocked\": {\n          \"@id\": \"bc:blocked\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"netChange\": {\n          \"@id\": \"bc:netChange\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Employee\": {\n      \"@id\": \"bc:Employee\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"bc:employeeId\",\n          \"@type\":\
  \ \"xsd:string\"\n        },\n        \"number\": {\n          \"@id\": \"bc:employeeNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"givenName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"surname\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobTitle\": {\n          \"@id\": \"schema:jobTitle\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phoneNumber\": {\n          \"@id\": \"schema:telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"employmentDate\": {\n          \"@id\": \"bc:employmentDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"status\": {\n          \"@id\": \"\
  bc:employeeStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"birthDate\": {\n          \"@id\": \"schema:birthDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Environment\": {\n      \"@id\": \"bc:Environment\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"friendlyName\": {\n          \"@id\": \"schema:alternateName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"bc:environmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"bc:environmentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"countryCode\": {\n          \"@id\": \"schema:addressCountry\",\n          \"@type\": \"xsd:string\"\n    \
  \    },\n        \"webClientLoginUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"webServiceUrl\": {\n          \"@id\": \"bc:webServiceUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/navision/refs/heads/main/json-ld/context.jsonld
tags:
- Business Management
- Dynamics NAV
- ERP
- Finance
- Inventory
- Microsoft
- Navision
- JSON-LD
- Linked Data
- Semantic Web
---
