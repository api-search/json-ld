---
class_count: 18
classes:
- CustomerList
- Subscription
- SubscriptionList
- Product
- description
- InvoiceList
- Pagination
- InvoiceLineItem
- CustomerRequest
- email
- SubscriptionRequest
- Address
- Customer
- createdAt
- updatedAt
- CustomerUpdate
- Invoice
- ProductList
context_file: json-ld/amdocs-connectx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-connectx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amdocs Connectx from Amdocs.
layout: jsonld
name: Amdocs Connectx Context
namespaces:
- prefix: amdocs
  uri: https://amdocs.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: data
  type: string
- container: ''
  name: pagination
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: customerId
  type: string
- container: ''
  name: productId
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: monthlyCharge
  type: decimal
- container: ''
  name: currency
  type: string
- container: set
  name: addons
  type: string
- container: ''
  name: productType
  type: string
- container: ''
  name: monthlyPrice
  type: decimal
- container: set
  name: features
  type: string
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: totalPages
  type: integer
- container: ''
  name: totalItems
  type: integer
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: unitPrice
  type: decimal
- container: ''
  name: amount
  type: decimal
- container: ''
  name: customerType
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: phone
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: street
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: billingAddress
  type: string
- container: ''
  name: invoiceId
  type: string
- container: ''
  name: invoiceNumber
  type: string
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: taxAmount
  type: decimal
- container: set
  name: lineItems
  type: string
property_count: 42
provider_name: Amdocs
provider_slug: amdocs
slug: amdocs-connectx-context
source_filename: amdocs-connectx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amdocs\": \"https://amdocs.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomerList\": \"amdocs:CustomerList\",\n    \"data\": {\n      \"@id\": \"amdocs:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagination\": {\n      \"@id\": \"amdocs:pagination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subscription\": \"amdocs:Subscription\",\n    \"subscriptionId\": {\n      \"@id\": \"amdocs:subscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customerId\": {\n      \"@id\": \"amdocs:customerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productId\": {\n      \"@id\": \"amdocs:productId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productName\": {\n      \"@id\": \"amdocs:productName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  status\": {\n      \"@id\": \"amdocs:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"amdocs:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"amdocs:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"monthlyCharge\": {\n      \"@id\": \"amdocs:monthlyCharge\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"amdocs:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addons\": {\n      \"@id\": \"amdocs:addons\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionList\": \"amdocs:SubscriptionList\",\n    \"Product\": \"amdocs:Product\",\n    \"productType\": {\n      \"@id\": \"amdocs:productType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"monthlyPrice\": {\n      \"@id\": \"amdocs:monthlyPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"features\": {\n     \
  \ \"@id\": \"amdocs:features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvoiceList\": \"amdocs:InvoiceList\",\n    \"Pagination\": \"amdocs:Pagination\",\n    \"page\": {\n      \"@id\": \"amdocs:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"amdocs:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPages\": {\n      \"@id\": \"amdocs:totalPages\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalItems\": {\n      \"@id\": \"amdocs:totalItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"InvoiceLineItem\": \"amdocs:InvoiceLineItem\",\n    \"quantity\": {\n      \"@id\": \"amdocs:quantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"unitPrice\": {\n      \"@id\": \"amdocs:unitPrice\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"amount\": {\n      \"@id\": \"amdocs:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"CustomerRequest\": \"amdocs:CustomerRequest\"\
  ,\n    \"customerType\": {\n      \"@id\": \"amdocs:customerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"amdocs:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"amdocs:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyName\": {\n      \"@id\": \"amdocs:companyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"phone\": {\n      \"@id\": \"amdocs:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"amdocs:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionRequest\": \"amdocs:SubscriptionRequest\",\n    \"Address\": \"amdocs:Address\",\n    \"street\": {\n      \"@id\": \"amdocs:street\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"amdocs:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amdocs:state\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"postalCode\": {\n      \"@id\": \"amdocs:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"amdocs:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Customer\": \"amdocs:Customer\",\n    \"accountNumber\": {\n      \"@id\": \"amdocs:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAddress\": {\n      \"@id\": \"amdocs:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"CustomerUpdate\": \"amdocs:CustomerUpdate\",\n    \"Invoice\": \"amdocs:Invoice\",\n    \"invoiceId\": {\n      \"@id\": \"amdocs:invoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceNumber\": {\n      \"@id\": \"amdocs:invoiceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoiceDate\": {\n      \"@id\": \"amdocs:invoiceDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dueDate\": {\n      \"@id\": \"\
  amdocs:dueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"amdocs:totalAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"taxAmount\": {\n      \"@id\": \"amdocs:taxAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lineItems\": {\n      \"@id\": \"amdocs:lineItems\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductList\": \"amdocs:ProductList\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amdocs/refs/heads/main/json-ld/amdocs-connectx-context.jsonld
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
