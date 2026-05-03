---
api_specs:
- filename: whmcs-openapi.yml
  format: yaml
  label: WHMCS API
  slug: whmcs
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/whmcs/main/openapi/whmcs-openapi.yml
class_count: 12
classes:
- name
- description
- url
- email
- telephone
- Organization
- Person
- PostalAddress
- Invoice
- Order
- Product
- SoftwareApplication
context_file: json-ld/whmcs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/whmcs/refs/heads/main/json-ld/whmcs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Whmcs from WHMCS.
layout: jsonld
name: Whmcs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: whmcs
  uri: https://www.whmcs.com/
properties:
- container: ''
  name: client
  type: reference
- container: ''
  name: clientId
  type: integer
- container: ''
  name: clientStatus
  type: string
- container: ''
  name: credit
  type: decimal
- container: ''
  name: invoice
  type: reference
- container: ''
  name: invoiceId
  type: integer
- container: ''
  name: invoiceStatus
  type: string
- container: ''
  name: dueDate
  type: date
- container: ''
  name: datePaid
  type: date
- container: ''
  name: total
  type: decimal
- container: ''
  name: balance
  type: decimal
- container: ''
  name: order
  type: reference
- container: ''
  name: orderId
  type: integer
- container: ''
  name: orderStatus
  type: string
- container: ''
  name: paymentMethod
  type: string
- container: ''
  name: ticket
  type: reference
- container: ''
  name: ticketId
  type: integer
- container: ''
  name: ticketStatus
  type: string
- container: ''
  name: ticketPriority
  type: string
- container: ''
  name: department
  type: reference
- container: ''
  name: domain
  type: string
- container: ''
  name: service
  type: reference
- container: ''
  name: product
  type: reference
property_count: 23
provider_name: WHMCS
provider_slug: whmcs
slug: whmcs-context
source_filename: whmcs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"whmcs\": \"https://www.whmcs.com/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"email\": \"schema:email\",\n    \"telephone\": \"schema:telephone\",\n    \"Organization\": \"schema:Organization\",\n    \"Person\": \"schema:Person\",\n    \"PostalAddress\": \"schema:PostalAddress\",\n    \"Invoice\": \"schema:Invoice\",\n    \"Order\": \"schema:Order\",\n    \"Product\": \"schema:Product\",\n    \"SoftwareApplication\": \"schema:SoftwareApplication\",\n    \"client\": {\n      \"@id\": \"whmcs:client\",\n      \"@type\": \"@id\"\n    },\n    \"clientId\": {\n      \"@id\": \"whmcs:clientId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"clientStatus\": {\n      \"@id\": \"whmcs:clientStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credit\": {\n \
  \     \"@id\": \"whmcs:credit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"invoice\": {\n      \"@id\": \"whmcs:invoice\",\n      \"@type\": \"@id\"\n    },\n    \"invoiceId\": {\n      \"@id\": \"whmcs:invoiceId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"invoiceStatus\": {\n      \"@id\": \"whmcs:invoiceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"datePaid\": {\n      \"@id\": \"whmcs:datePaid\",\n      \"@type\": \"xsd:date\"\n    },\n    \"total\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"balance\": {\n      \"@id\": \"whmcs:balance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"order\": {\n      \"@id\": \"whmcs:order\",\n      \"@type\": \"@id\"\n    },\n    \"orderId\": {\n      \"@id\": \"whmcs:orderId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"whmcs:orderStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethod\": {\n      \"@id\": \"schema:paymentMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticket\": {\n      \"@id\": \"whmcs:ticket\",\n      \"@type\": \"@id\"\n    },\n    \"ticketId\": {\n      \"@id\": \"whmcs:ticketId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ticketStatus\": {\n      \"@id\": \"whmcs:ticketStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ticketPriority\": {\n      \"@id\": \"whmcs:ticketPriority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"department\": {\n      \"@id\": \"whmcs:department\",\n      \"@type\": \"@id\"\n    },\n    \"domain\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"whmcs:service\",\n      \"@type\": \"@id\"\n    },\n    \"product\": {\n      \"@id\": \"whmcs:product\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/whmcs/refs/heads/main/json-ld/whmcs-context.jsonld
tags:
- Web Hosting
- Billing Automation
- Client Management
- Domain Management
- Support Tickets
- Provisioning
- JSON-LD
- Linked Data
- Semantic Web
---
