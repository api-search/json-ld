---
api_specs:
- filename: debbie-platform-api-openapi.yml
  format: yaml
  label: Debbie Platform API
  slug: debbie-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/openapi/debbie-platform-api-openapi.yml
- filename: debbie-client-api-openapi.yml
  format: yaml
  label: Debbie Client API
  slug: debbie-client-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/openapi/debbie-client-api-openapi.yml
class_count: 5
classes:
- Case
- Customer
- Creditor
- Voucher
- Payment
context_file: json-ld/debbie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/json-ld/debbie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Debbie from Debbie Collect.
layout: jsonld
name: Debbie Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: debbie
  uri: https://schema.debbiecollect.com/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: email
  type: schema:Text
- container: ''
  name: phone
  type: schema:Text
- container: ''
  name: principal_amount
  type: schema:Number
- container: ''
  name: outstanding_amount
  type: schema:Number
- container: ''
  name: currency
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: due_date
  type: schema:Date
- container: ''
  name: reference_id
  type: schema:Text
property_count: 10
provider_name: Debbie Collect
provider_slug: debbie-collect
slug: debbie-context
source_filename: debbie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.debbiecollect.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"debbie\": \"https://schema.debbiecollect.com/\",\n    \"Case\": \"debbie:Case\",\n    \"Customer\": \"schema:Person\",\n    \"Creditor\": \"schema:Organization\",\n    \"Voucher\": \"debbie:Voucher\",\n    \"Payment\": \"schema:PaymentMethod\",\n    \"id\": {\"@id\": \"schema:identifier\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"schema:Text\"},\n    \"email\": {\"@id\": \"schema:email\", \"@type\": \"schema:Text\"},\n    \"phone\": {\"@id\": \"schema:telephone\", \"@type\": \"schema:Text\"},\n    \"principal_amount\": {\"@id\": \"debbie:principalAmount\", \"@type\": \"schema:Number\"},\n    \"outstanding_amount\": {\"@id\": \"debbie:outstandingAmount\", \"@type\": \"schema:Number\"},\n    \"currency\": {\"@id\": \"schema:priceCurrency\", \"@type\": \"schema:Text\"},\n    \"status\": {\"@id\": \"debbie:status\"\
  , \"@type\": \"schema:Text\"},\n    \"due_date\": {\"@id\": \"schema:dueDate\", \"@type\": \"schema:Date\"},\n    \"reference_id\": {\"@id\": \"debbie:referenceId\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/debbie-collect/refs/heads/main/json-ld/debbie-context.jsonld
tags:
- Accounts Receivable
- Collections
- Debt Collection
- FinTech
- Payments
- SaaS
- JSON-LD
- Linked Data
- Semantic Web
---
