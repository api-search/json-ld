---
api_specs:
- filename: fis-payments-openapi.yml
  format: yaml
  label: FIS Payments API
  slug: fis-payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fis/refs/heads/main/openapi/fis-payments-openapi.yml
class_count: 12
classes:
- paymentId
- currency
- paymentMethod
- status
- remittanceInfo
- accountNumber
- accountHolderName
- bankName
- accountType
- routingNumber
- swiftCode
- iban
context_file: json-ld/fis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fis/refs/heads/main/json-ld/fis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fis from FIS Global.
layout: jsonld
name: Fis Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: pay
  uri: https://w3c-ccg.github.io/payment-handler-api/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Payment
  type: reference
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: FinancialInstitution
  type: reference
- container: ''
  name: amount
  type: decimal
- container: ''
  name: executionDate
  type: date
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: debtorAccount
  type: reference
- container: ''
  name: creditorAccount
  type: reference
property_count: 10
provider_name: FIS Global
provider_slug: fis
slug: fis-context
source_filename: fis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"pay\": \"https://w3c-ccg.github.io/payment-handler-api/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"Payment\": {\n      \"@id\": \"schema:PayAction\",\n      \"@type\": \"@id\"\n    },\n    \"BankAccount\": {\n      \"@id\": \"schema:BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"FinancialInstitution\": {\n      \"@id\": \"schema:BankOrCreditUnion\",\n      \"@type\": \"@id\"\n    },\n\n    \"paymentId\": \"schema:identifier\",\n    \"amount\": {\n      \"@id\": \"schema:totalPaymentDue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:currency\",\n    \"paymentMethod\": \"schema:paymentMethod\",\n    \"status\": \"schema:orderStatus\",\n    \"remittanceInfo\": \"schema:description\",\n    \"executionDate\": {\n      \"\
  @id\": \"schema:scheduledTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"debtorAccount\": {\n      \"@id\": \"fibo:FBC/FunctionalEntities/FinancialServicesEntities/Debtor\",\n      \"@type\": \"@id\"\n    },\n    \"creditorAccount\": {\n      \"@id\": \"fibo:FBC/FunctionalEntities/FinancialServicesEntities/Creditor\",\n      \"@type\": \"@id\"\n    },\n\n    \"accountNumber\": \"schema:accountId\",\n    \"accountHolderName\": \"schema:name\",\n    \"bankName\": \"schema:legalName\",\n    \"accountType\": \"schema:bankAccountType\",\n    \"routingNumber\": \"schema:identifier\",\n    \"swiftCode\": \"schema:identifier\",\n    \"iban\": \"schema:identifier\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fis/refs/heads/main/json-ld/fis-context.jsonld
tags:
- Banking
- Core Banking
- Financial Services
- Payments
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
