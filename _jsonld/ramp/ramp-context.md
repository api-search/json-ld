---
api_specs:
- filename: ramp-developer-api-openapi.yml
  format: yaml
  label: Ramp Developer API
  slug: ramp-developer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/openapi/ramp-developer-api-openapi.yml
class_count: 20
classes:
- Transaction
- Card
- User
- Department
- Location
- Vendor
- Reimbursement
- Bill
- Statement
- id
- type
- name
- email
- amount
- currency_code
- merchant_name
- user_transaction_time
- first_name
- last_name
- role
context_file: json-ld/ramp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/json-ld/ramp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ramp from Ramp.
layout: jsonld
name: Ramp Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ramp
  uri: https://ramp.com/ns#
properties:
- container: ''
  name: department_id
  type: reference
- container: ''
  name: location_id
  type: reference
- container: ''
  name: card_id
  type: reference
- container: ''
  name: user_id
  type: reference
property_count: 4
provider_name: Ramp
provider_slug: ramp
slug: ramp-context
source_filename: ramp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ramp\": \"https://ramp.com/ns#\",\n    \"Transaction\": \"ramp:Transaction\",\n    \"Card\": \"ramp:Card\",\n    \"User\": \"ramp:User\",\n    \"Department\": \"ramp:Department\",\n    \"Location\": \"ramp:Location\",\n    \"Vendor\": \"ramp:Vendor\",\n    \"Reimbursement\": \"ramp:Reimbursement\",\n    \"Bill\": \"ramp:Bill\",\n    \"Statement\": \"ramp:Statement\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"amount\": \"schema:price\",\n    \"currency_code\": \"schema:priceCurrency\",\n    \"merchant_name\": \"schema:merchant\",\n    \"user_transaction_time\": \"schema:dateTime\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"role\": \"schema:roleName\",\n    \"department_id\": { \"@id\": \"ramp:department\", \"@type\": \"@id\" },\n    \"location_id\": { \"\
  @id\": \"ramp:location\", \"@type\": \"@id\" },\n    \"card_id\": { \"@id\": \"ramp:card\", \"@type\": \"@id\" },\n    \"user_id\": { \"@id\": \"ramp:user\", \"@type\": \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ramp/refs/heads/main/json-ld/ramp-context.jsonld
tags:
- Finance
- Spend Management
- Corporate Cards
- Expense Management
- Accounts Payable
- Bill Pay
- Accounting
- Reimbursements
- JSON-LD
- Linked Data
- Semantic Web
---
