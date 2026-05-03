---
api_specs:
- filename: veryfi-ocr-openapi.yml
  format: yaml
  label: Veryfi OCR API
  slug: ocr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/openapi/veryfi-ocr-openapi.yml
class_count: 9
classes:
- Document
- BankStatement
- Invoice
- Receipt
- W2Form
- W9Form
- Check
- LineItem
- Vendor
context_file: json-ld/veryfi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/json-ld/veryfi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Veryfi from Veryfi.
layout: jsonld
name: Veryfi Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: veryfi
  uri: https://www.veryfi.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: external_id
  type: string
- container: ''
  name: document_type
  type: string
- container: ''
  name: vendor
  type: reference
- container: ''
  name: date
  type: string
- container: ''
  name: due_date
  type: string
- container: ''
  name: invoice_number
  type: string
- container: ''
  name: total
  type: decimal
- container: ''
  name: subtotal
  type: decimal
- container: ''
  name: tax
  type: decimal
- container: ''
  name: tip
  type: decimal
- container: ''
  name: currency_code
  type: string
- container: list
  name: line_items
  type: ''
- container: ''
  name: description
  type: string
- container: ''
  name: quantity
  type: decimal
- container: ''
  name: price
  type: decimal
- container: list
  name: tags
  type: ''
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: account_number
  type: string
- container: ''
  name: routing_number
  type: string
- container: ''
  name: bank_name
  type: string
- container: ''
  name: opening_balance
  type: decimal
- container: ''
  name: closing_balance
  type: decimal
- container: list
  name: transactions
  type: ''
- container: ''
  name: wages
  type: decimal
- container: ''
  name: federal_tax_withheld
  type: decimal
- container: ''
  name: tin
  type: string
property_count: 28
provider_name: Veryfi
provider_slug: veryfi
slug: veryfi-context
source_filename: veryfi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"veryfi\": \"https://www.veryfi.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Document\": \"schema:CreativeWork\",\n    \"BankStatement\": \"schema:FinancialProduct\",\n    \"Invoice\": \"schema:Invoice\",\n    \"Receipt\": \"schema:Receipt\",\n    \"W2Form\": \"veryfi:W2Form\",\n    \"W9Form\": \"veryfi:W9Form\",\n    \"Check\": \"schema:PaymentCard\",\n    \"LineItem\": \"schema:OrderItem\",\n    \"Vendor\": \"schema:Organization\",\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"external_id\": {\n      \"@id\": \"veryfi:externalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"document_type\": {\n      \"@id\": \"veryfi:documentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"schema:seller\",\n   \
  \   \"@type\": \"@id\"\n    },\n    \"date\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:string\"\n    },\n    \"due_date\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invoice_number\": {\n      \"@id\": \"schema:confirmationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"subtotal\": {\n      \"@id\": \"veryfi:subtotal\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tax\": {\n      \"@id\": \"veryfi:taxAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tip\": {\n      \"@id\": \"veryfi:tipAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency_code\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line_items\": {\n      \"@id\": \"schema:orderedItem\",\n      \"@container\": \"@list\"\n    },\n    \"description\": {\n      \"@id\": \"\
  schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:orderQuantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tags\": {\n      \"@id\": \"schema:keywords\",\n      \"@container\": \"@list\"\n    },\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"account_number\": {\n      \"@id\": \"veryfi:accountNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routing_number\": {\n      \"@id\": \"veryfi:routingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bank_name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"opening_balance\": {\n      \"@id\": \"veryfi:openingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"\
  closing_balance\": {\n      \"@id\": \"veryfi:closingBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactions\": {\n      \"@id\": \"schema:accountId\",\n      \"@container\": \"@list\"\n    },\n    \"wages\": {\n      \"@id\": \"veryfi:wages\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"federal_tax_withheld\": {\n      \"@id\": \"veryfi:federalTaxWithheld\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"tin\": {\n      \"@id\": \"veryfi:taxpayerIdentificationNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/veryfi/refs/heads/main/json-ld/veryfi-context.jsonld
tags:
- AI
- Document Processing
- Finance
- Invoices
- OCR
- Receipts
- Tax Forms
- JSON-LD
- Linked Data
- Semantic Web
---
