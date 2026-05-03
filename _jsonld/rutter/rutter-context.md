---
api_specs:
- filename: rutter-unified-api-openapi.yml
  format: yaml
  label: Rutter Unified API
  slug: unified-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/openapi/rutter-unified-api-openapi.yml
class_count: 1
classes:
- id
context_file: json-ld/rutter-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-ld/rutter-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rutter from Rutter.
layout: jsonld
name: Rutter Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rutter
  uri: https://www.rutter.com/vocab/
properties:
- container: ''
  name: Connection
  type: reference
- container: ''
  name: platform
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: created_at
  type: schema:DateTime
- container: ''
  name: updated_at
  type: schema:DateTime
- container: ''
  name: Invoice
  type: reference
- container: ''
  name: customer_id
  type: reference
- container: ''
  name: amount_due
  type: schema:MonetaryAmount
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: due_date
  type: schema:Date
- container: list
  name: line_items
  type: ''
- container: ''
  name: Order
  type: reference
- container: ''
  name: total_price
  type: schema:Number
- container: ''
  name: Product
  type: reference
- container: ''
  name: title
  type: schema:Text
- container: ''
  name: description
  type: schema:Text
- container: ''
  name: price
  type: schema:Number
- container: ''
  name: Customer
  type: reference
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: email
  type: schema:Text
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: balance
  type: schema:Number
- container: ''
  name: access_token
  type: schema:Text
- container: ''
  name: next_cursor
  type: schema:Text
property_count: 24
provider_name: Rutter
provider_slug: rutter
slug: rutter-context
source_filename: rutter-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rutter\": \"https://www.rutter.com/vocab/\",\n    \"Connection\": {\n      \"@id\": \"rutter:Connection\",\n      \"@type\": \"@id\"\n    },\n    \"id\": \"@id\",\n    \"platform\": {\n      \"@id\": \"rutter:platform\",\n      \"@type\": \"schema:Text\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"schema:Text\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"Invoice\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"@id\"\n    },\n    \"customer_id\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"@id\"\n    },\n    \"amount_due\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"schema:MonetaryAmount\"\n    },\n    \"currency\"\
  : {\n      \"@id\": \"schema:currency\",\n      \"@type\": \"schema:Text\"\n    },\n    \"due_date\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"schema:Date\"\n    },\n    \"line_items\": {\n      \"@id\": \"schema:itemListElement\",\n      \"@container\": \"@list\"\n    },\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@type\": \"@id\"\n    },\n    \"total_price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"schema:Text\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"Customer\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\
  ,\n      \"@type\": \"schema:Text\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"schema:Text\"\n    },\n    \"BankAccount\": {\n      \"@id\": \"schema:BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"balance\": {\n      \"@id\": \"schema:amount\",\n      \"@type\": \"schema:Number\"\n    },\n    \"access_token\": {\n      \"@id\": \"rutter:accessToken\",\n      \"@type\": \"schema:Text\"\n    },\n    \"next_cursor\": {\n      \"@id\": \"rutter:nextCursor\",\n      \"@type\": \"schema:Text\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rutter/refs/heads/main/json-ld/rutter-context.jsonld
tags:
- Accounting
- B2B
- Commerce
- Financial Data
- Payments
- Unified API
- JSON-LD
- Linked Data
- Semantic Web
---
