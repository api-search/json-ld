---
api_specs:
- filename: amdocs-connectx-openapi.yml
  format: yaml
  label: Amdocs connectX BSS API
  slug: amdocs-connectx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/openapi/amdocs-connectx-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amdocs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amdocs from Amdocs.
layout: jsonld
name: Amdocs Context
namespaces:
- prefix: amdocs
  uri: https://devportal.amdocs-dbs.com/api/
- prefix: schema
  uri: https://schema.org/
- prefix: tmf
  uri: https://tmforum.org/schemas/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Customer
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Invoice
  type: ''
- container: ''
  name: Product
  type: ''
- container: ''
  name: Address
  type: ''
property_count: 5
provider_name: Amdocs
provider_slug: amdocs
slug: amdocs-context
source_filename: amdocs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amdocs\": \"https://devportal.amdocs-dbs.com/api/\",\n    \"schema\": \"https://schema.org/\",\n    \"tmf\": \"https://tmforum.org/schemas/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"customerId\": {\"@id\": \"amdocs:customerId\", \"@type\": \"xsd:string\"},\n        \"customerType\": {\"@id\": \"amdocs:customerType\"},\n        \"status\": {\"@id\": \"amdocs:accountStatus\"},\n        \"accountNumber\": {\"@id\": \"amdocs:accountNumber\"},\n        \"firstName\": {\"@id\": \"schema:givenName\"},\n        \"lastName\": {\"@id\": \"schema:familyName\"},\n        \"companyName\": {\"@id\": \"schema:legalName\"},\n        \"email\": {\"@id\": \"schema:email\"},\n        \"phone\": {\"@id\": \"schema:telephone\"},\n        \"address\": {\"@id\": \"schema:address\"},\n        \"subscriptions\": {\"@id\": \"amdocs:subscription\"\
  , \"@container\": \"@set\"}\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"schema:Service\",\n      \"@context\": {\n        \"subscriptionId\": {\"@id\": \"amdocs:subscriptionId\"},\n        \"productId\": {\"@id\": \"amdocs:productId\"},\n        \"productName\": {\"@id\": \"schema:name\"},\n        \"status\": {\"@id\": \"amdocs:subscriptionStatus\"},\n        \"startDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n        \"endDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n        \"monthlyCharge\": {\"@id\": \"schema:price\", \"@type\": \"xsd:decimal\"},\n        \"currency\": {\"@id\": \"schema:priceCurrency\"}\n      }\n    },\n\n    \"Invoice\": {\n      \"@id\": \"schema:Invoice\",\n      \"@context\": {\n        \"invoiceId\": {\"@id\": \"amdocs:invoiceId\"},\n        \"invoiceNumber\": {\"@id\": \"schema:identifier\"},\n        \"customerId\": {\"@id\": \"schema:customer\"},\n        \"status\": {\"@id\": \"schema:paymentStatus\"\
  },\n        \"invoiceDate\": {\"@id\": \"schema:dateIssued\", \"@type\": \"xsd:date\"},\n        \"dueDate\": {\"@id\": \"schema:paymentDueDate\", \"@type\": \"xsd:date\"},\n        \"totalAmount\": {\"@id\": \"schema:totalPrice\"},\n        \"taxAmount\": {\"@id\": \"schema:taxTotal\"},\n        \"currency\": {\"@id\": \"schema:priceCurrency\"}\n      }\n    },\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"productId\": {\"@id\": \"schema:productID\"},\n        \"productName\": {\"@id\": \"schema:name\"},\n        \"productType\": {\"@id\": \"schema:category\"},\n        \"description\": {\"@id\": \"schema:description\"},\n        \"monthlyPrice\": {\"@id\": \"schema:price\"},\n        \"currency\": {\"@id\": \"schema:priceCurrency\"},\n        \"features\": {\"@id\": \"schema:additionalProperty\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@context\": {\n        \"street\"\
  : {\"@id\": \"schema:streetAddress\"},\n        \"city\": {\"@id\": \"schema:addressLocality\"},\n        \"state\": {\"@id\": \"schema:addressRegion\"},\n        \"postalCode\": {\"@id\": \"schema:postalCode\"},\n        \"country\": {\"@id\": \"schema:addressCountry\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-context.jsonld
tags:
- Telecom
- BSS
- OSS
- Billing
- Customer Management
- MVNO
- 5G
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
