---
class_count: 18
classes:
- Account
- Transaction
- Statement
- Branch
- ATM
- Customer
- Loan
- Installment
- Merchant
- name
- address
- latitude
- longitude
- balance
- currency
- amount
- createdAt
- valueDate
context_file: json-ld/citizens-financial-group-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial-group/refs/heads/main/json-ld/citizens-financial-group-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Citizens Financial Group from Citizens Financial Group.
layout: jsonld
name: Citizens Financial Group Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fdx
  uri: https://financialdataexchange.org/vocab/
properties: []
property_count: 0
provider_name: Citizens Financial Group
provider_slug: citizens-financial-group
slug: citizens-financial-group-context
source_filename: citizens-financial-group-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.citizensbank.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"fdx\": \"https://financialdataexchange.org/vocab/\",\n    \"Account\": \"schema:BankAccount\",\n    \"Transaction\": \"schema:MoneyTransfer\",\n    \"Statement\": \"schema:DigitalDocument\",\n    \"Branch\": \"schema:BankOrCreditUnion\",\n    \"ATM\": \"schema:AutomatedTeller\",\n    \"Customer\": \"schema:Person\",\n    \"Loan\": \"schema:LoanOrCredit\",\n    \"Installment\": \"fdx:Installment\",\n    \"Merchant\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"address\": \"schema:address\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"balance\": \"fdx:balance\",\n    \"currency\": \"schema:currency\",\n    \"amount\": \"schema:amount\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"valueDate\": \"fdx:valueDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial-group/refs/heads/main/json-ld/citizens-financial-group-context.jsonld
tags:
- Banking
- Buy Now Pay Later
- Financial Services
- FDX
- Locator
- Open Banking
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
