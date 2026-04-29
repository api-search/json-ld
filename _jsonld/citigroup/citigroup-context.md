---
class_count: 17
classes:
- Account
- Transaction
- Payment
- Customer
- Card
- Reward
- FXRate
- Branch
- Consent
- name
- iban
- bic
- currency
- amount
- balance
- createdAt
- valueDate
context_file: json-ld/citigroup-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/json-ld/citigroup-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Citigroup from Citigroup.
layout: jsonld
name: Citigroup Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: citi
  uri: https://developer.citi.com/vocab/
properties: []
property_count: 0
provider_name: Citigroup
provider_slug: citigroup
slug: citigroup-context
source_filename: citigroup-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.citi.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"citi\": \"https://developer.citi.com/vocab/\",\n    \"Account\": \"schema:BankAccount\",\n    \"Transaction\": \"schema:MoneyTransfer\",\n    \"Payment\": \"schema:PaymentService\",\n    \"Customer\": \"schema:Person\",\n    \"Card\": \"schema:PaymentCard\",\n    \"Reward\": \"citi:Reward\",\n    \"FXRate\": \"citi:FXRate\",\n    \"Branch\": \"schema:BankOrCreditUnion\",\n    \"Consent\": \"citi:Consent\",\n    \"name\": \"schema:name\",\n    \"iban\": \"schema:iban\",\n    \"bic\": \"schema:bic\",\n    \"currency\": \"schema:currency\",\n    \"amount\": \"schema:amount\",\n    \"balance\": \"citi:balance\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"valueDate\": \"citi:valueDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/citigroup/refs/heads/main/json-ld/citigroup-context.jsonld
tags:
- Banking
- Financial Services
- FX
- Open Banking
- Payments
- Treasury
- JSON-LD
- Linked Data
- Semantic Web
---
