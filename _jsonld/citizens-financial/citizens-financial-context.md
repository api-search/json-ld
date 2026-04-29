---
class_count: 14
classes:
- Organization
- API
- Account
- Transaction
- ATM
- Merchant
- Loan
- name
- description
- category
- balance
- transactionType
- createdAt
- updatedAt
context_file: json-ld/citizens-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/json-ld/citizens-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Citizens Financial from Citizens Financial.
layout: jsonld
name: Citizens Financial Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: cf
  uri: https://developer.citizensbank.com/vocab/
properties: []
property_count: 0
provider_name: Citizens Financial
provider_slug: citizens-financial
slug: citizens-financial-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://apievangelist.com/vocab/citizens-financial/\",\n    \"schema\": \"https://schema.org/\",\n    \"cf\": \"https://developer.citizensbank.com/vocab/\",\n    \"Organization\": \"schema:BankOrCreditUnion\",\n    \"API\": \"schema:WebAPI\",\n    \"Account\": \"cf:DepositAccount\",\n    \"Transaction\": \"cf:BankTransaction\",\n    \"ATM\": \"schema:AutomatedTeller\",\n    \"Merchant\": \"schema:Organization\",\n    \"Loan\": \"schema:LoanOrCredit\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"category\": \"schema:category\",\n    \"balance\": \"cf:accountBalance\",\n    \"transactionType\": \"cf:transactionType\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/citizens-financial/refs/heads/main/json-ld/citizens-financial-context.jsonld
tags:
- Accounts
- ATMs
- Banking
- Open Banking
- Payments
- Point of Sale
- Transactions
- JSON-LD
- Linked Data
- Semantic Web
---
