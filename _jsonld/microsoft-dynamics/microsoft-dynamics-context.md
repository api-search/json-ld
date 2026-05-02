---
api_specs:
- filename: microsoft-dynamics-business-central-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Business Central API
  slug: business-central-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-business-central-openapi.yml
- filename: microsoft-dynamics-dataverse-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Dataverse Web API
  slug: dataverse-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-dataverse-openapi.yml
- filename: microsoft-dynamics-finance-operations-openapi.yml
  format: yaml
  label: Microsoft Dynamics 365 Finance & Operations Data API
  slug: finance-operations-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/openapi/microsoft-dynamics-finance-operations-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-dynamics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/json-ld/microsoft-dynamics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Dynamics from Microsoft Dynamics.
layout: jsonld
name: Microsoft Dynamics Context
namespaces:
- prefix: dynamics
  uri: https://learn.microsoft.com/en-us/dynamics365/
- prefix: bc
  uri: https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/
- prefix: dataverse
  uri: https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/
- prefix: fo
  uri: https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/
properties:
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
  name: SalesInvoice
  type: ''
- container: ''
  name: Employee
  type: ''
- container: ''
  name: Account
  type: ''
- container: ''
  name: Contact
  type: ''
- container: ''
  name: Lead
  type: ''
- container: ''
  name: Opportunity
  type: ''
property_count: 10
provider_name: Microsoft Dynamics
provider_slug: microsoft-dynamics
slug: microsoft-dynamics-context
source_filename: microsoft-dynamics-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"dynamics\": \"https://learn.microsoft.com/en-us/dynamics365/\",\n    \"bc\": \"https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/\",\n    \"dataverse\": \"https://learn.microsoft.com/en-us/power-apps/developer/data-platform/webapi/reference/\",\n    \"fo\": \"https://learn.microsoft.com/en-us/dynamics365/fin-ops-core/dev-itpro/data-entities/\",\n    \"Customer\": {\n      \"@id\": \"bc:api/dynamics_customer_get\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"number\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"addressLine1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\
  ,\n        \"website\": \"schema:url\"\n      }\n    },\n    \"Vendor\": {\n      \"@id\": \"bc:api/dynamics_vendor_get\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"number\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"addressLine1\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"postalCode\": \"schema:postalCode\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n    \"Item\": {\n      \"@id\": \"bc:api/dynamics_item_get\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"number\": \"schema:identifier\",\n        \"unitPrice\": \"schema:price\",\n        \"gtin\": \"schema:gtin\"\n      }\n    },\n    \"SalesOrder\": {\n      \"@id\": \"bc:api/dynamics_salesorder_get\",\n      \"@context\": {\n   \
  \     \"id\": \"@id\",\n        \"number\": \"schema:orderNumber\",\n        \"orderDate\": \"schema:orderDate\",\n        \"customerName\": \"schema:customer\",\n        \"totalAmountIncludingTax\": \"schema:totalPrice\",\n        \"currencyCode\": \"schema:priceCurrency\"\n      }\n    },\n    \"SalesInvoice\": {\n      \"@id\": \"bc:api/dynamics_salesinvoice_get\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"number\": \"schema:identifier\",\n        \"invoiceDate\": \"schema:paymentDueDate\",\n        \"customerName\": \"schema:customer\",\n        \"totalAmountIncludingTax\": \"schema:totalPaymentDue\",\n        \"currencyCode\": \"schema:priceCurrency\"\n      }\n    },\n    \"Employee\": {\n      \"@id\": \"bc:api/dynamics_employee_get\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"schema:name\",\n        \"givenName\": \"schema:givenName\",\n        \"surname\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n      \
  \  \"jobTitle\": \"schema:jobTitle\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"birthDate\": \"schema:birthDate\"\n      }\n    },\n    \"Account\": {\n      \"@id\": \"dataverse:account\",\n      \"@context\": {\n        \"accountid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"accountnumber\": \"schema:identifier\",\n        \"telephone1\": \"schema:telephone\",\n        \"emailaddress1\": \"schema:email\",\n        \"websiteurl\": \"schema:url\",\n        \"address1_line1\": \"schema:streetAddress\",\n        \"address1_city\": \"schema:addressLocality\",\n        \"address1_stateorprovince\": \"schema:addressRegion\",\n        \"address1_postalcode\": \"schema:postalCode\",\n        \"address1_country\": \"schema:addressCountry\",\n        \"numberofemployees\": \"schema:numberOfEmployees\"\n      }\n    },\n    \"Contact\": {\n      \"@id\": \"dataverse:contact\",\n      \"@context\": {\n        \"contactid\": \"@id\",\n        \"firstname\": \"schema:givenName\"\
  ,\n        \"lastname\": \"schema:familyName\",\n        \"fullname\": \"schema:name\",\n        \"jobtitle\": \"schema:jobTitle\",\n        \"emailaddress1\": \"schema:email\",\n        \"telephone1\": \"schema:telephone\",\n        \"mobilephone\": \"schema:telephone\",\n        \"birthdate\": \"schema:birthDate\"\n      }\n    },\n    \"Lead\": {\n      \"@id\": \"dataverse:lead\",\n      \"@context\": {\n        \"leadid\": \"@id\",\n        \"subject\": \"schema:name\",\n        \"firstname\": \"schema:givenName\",\n        \"lastname\": \"schema:familyName\",\n        \"companyname\": \"schema:worksFor\",\n        \"emailaddress1\": \"schema:email\",\n        \"telephone1\": \"schema:telephone\",\n        \"jobtitle\": \"schema:jobTitle\"\n      }\n    },\n    \"Opportunity\": {\n      \"@id\": \"dataverse:opportunity\",\n      \"@context\": {\n        \"opportunityid\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"estimatedvalue\"\
  : \"schema:price\",\n        \"estimatedclosedate\": \"schema:validThrough\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-dynamics/refs/heads/main/json-ld/microsoft-dynamics-context.jsonld
tags:
- CRM
- ERP
- Microsoft Dynamics
- JSON-LD
- Linked Data
- Semantic Web
---
