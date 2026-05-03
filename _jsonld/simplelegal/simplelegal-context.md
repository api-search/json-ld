---
api_specs:
- filename: simplelegal-openapi.yml
  format: yaml
  label: SimpleLegal API
  slug: simplelegal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/simplelegal/refs/heads/main/openapi/simplelegal-openapi.yml
class_count: 39
classes:
- LegalMatter
- LegalInvoice
- LegalVendor
- LegalUser
- CostCode
- Payment
- InvoiceLineItem
- id
- name
- description
- status
- matterNumber
- practiceArea
- client
- leadAttorney
- outsideCounsel
- budget
- actualSpend
- accruals
- invoiceNumber
- matterId
- vendorId
- currency
- totalAmount
- approvedAmount
- lineItems
- taskCode
- activityCode
- timekeeper
- hours
- rate
- amount
- vendorType
- diversityInfo
- contactEmail
- contactName
- userRole
- department
- email
context_file: json-ld/simplelegal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/simplelegal/refs/heads/main/json-ld/simplelegal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Simplelegal from SimpleLegal.
layout: jsonld
name: Simplelegal Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: lkif
  uri: http://www.estrellaproject.org/lkif-core/lkif-core.owl#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: simplelegal
  uri: https://simplelegal.com/vocab/
properties:
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: invoiceDate
  type: date
- container: ''
  name: dueDate
  type: date
property_count: 4
provider_name: SimpleLegal
provider_slug: simplelegal
slug: simplelegal-context
source_filename: simplelegal-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"lkif\": \"http://www.estrellaproject.org/lkif-core/lkif-core.owl#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"simplelegal\": \"https://simplelegal.com/vocab/\",\n\n    \"LegalMatter\": \"simplelegal:LegalMatter\",\n    \"LegalInvoice\": \"simplelegal:LegalInvoice\",\n    \"LegalVendor\": \"simplelegal:LegalVendor\",\n    \"LegalUser\": \"simplelegal:LegalUser\",\n    \"CostCode\": \"simplelegal:CostCode\",\n    \"Payment\": \"schema:Payment\",\n    \"InvoiceLineItem\": \"simplelegal:InvoiceLineItem\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"simplelegal:status\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"matterNumber\"\
  : \"simplelegal:matterNumber\",\n    \"practiceArea\": \"simplelegal:practiceArea\",\n    \"client\": \"schema:customer\",\n    \"leadAttorney\": \"simplelegal:leadAttorney\",\n    \"outsideCounsel\": \"simplelegal:outsideCounsel\",\n    \"budget\": \"simplelegal:budget\",\n    \"actualSpend\": \"simplelegal:actualSpend\",\n    \"accruals\": \"simplelegal:accruals\",\n\n    \"invoiceNumber\": \"schema:identifier\",\n    \"matterId\": \"simplelegal:matterReference\",\n    \"vendorId\": \"schema:seller\",\n    \"invoiceDate\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"currency\": \"schema:currency\",\n    \"totalAmount\": \"schema:totalPaymentDue\",\n    \"approvedAmount\": \"simplelegal:approvedAmount\",\n    \"lineItems\": \"simplelegal:lineItems\",\n\n    \"taskCode\": \"simplelegal:taskCode\",\n    \"activityCode\": \"simplelegal:activityCode\"\
  ,\n    \"timekeeper\": \"simplelegal:timekeeper\",\n    \"hours\": \"simplelegal:hoursWorked\",\n    \"rate\": \"schema:price\",\n    \"amount\": \"schema:amount\",\n\n    \"vendorType\": \"simplelegal:vendorType\",\n    \"diversityInfo\": \"simplelegal:diversityInfo\",\n    \"contactEmail\": \"schema:email\",\n    \"contactName\": \"schema:contactPoint\",\n\n    \"userRole\": \"simplelegal:userRole\",\n    \"department\": \"schema:department\",\n    \"email\": \"schema:email\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/simplelegal/refs/heads/main/json-ld/simplelegal-context.jsonld
tags:
- eBilling
- Enterprise Legal Management
- Legal Operations
- Legal Spend Management
- Matter Management
- Vendor Management
- JSON-LD
- Linked Data
- Semantic Web
---
