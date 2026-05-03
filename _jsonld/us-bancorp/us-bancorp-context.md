---
api_specs:
- filename: us-bank-corporate-account-information-openapi.yml
  format: yaml
  label: US Bank Corporate Account Information API
  slug: us-bank-corporate-account-information
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-corporate-account-information-openapi.yml
- filename: us-bank-rtp-openapi.yml
  format: yaml
  label: US Bank RTP Real-Time Payments API
  slug: us-bank-rtp
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-rtp-openapi.yml
- filename: us-bank-ach-originations-openapi.yml
  format: yaml
  label: US Bank ACH Originations API
  slug: us-bank-ach-originations
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-ach-originations-openapi.yml
- filename: us-bank-positive-pay-openapi.yml
  format: yaml
  label: US Bank Positive Pay API
  slug: us-bank-positive-pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-positive-pay-openapi.yml
- filename: us-bank-push-to-card-openapi.yml
  format: yaml
  label: US Bank Push to Card API
  slug: us-bank-push-to-card
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/openapi/us-bank-push-to-card-openapi.yml
class_count: 30
classes:
- BankAccount
- DepositAccount
- Transaction
- Payment
- Organization
- FinancialProduct
- accountNumber
- accountType
- accountName
- currency
- status
- transactionId
- amount
- description
- transactionType
- referenceNumber
- bankReference
- availableBalance
- ledgerBalance
- collectedBalance
- routingNumber
- payerAccountNumber
- payeeAccountNumber
- payeeName
- remittanceInfo
- RTPPayment
- ACHPayment
- WireTransfer
- PushToCardPayment
- PositivePayException
context_file: json-ld/us-bancorp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-ld/us-bancorp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Bancorp from US Bancorp.
layout: jsonld
name: Us Bancorp Context
namespaces:
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: usb
  uri: https://www.usbank.com/vocab/
properties:
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: valueDate
  type: date
- container: ''
  name: balanceDate
  type: date
- container: ''
  name: USBancorp
  type: Organization
- container: ''
  name: USBank
  type: Organization
property_count: 5
provider_name: US Bancorp
provider_slug: us-bancorp
slug: us-bancorp-context
source_filename: us-bancorp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"usb\": \"https://www.usbank.com/vocab/\",\n\n    \"BankAccount\": \"usb:BankAccount\",\n    \"DepositAccount\": \"usb:DepositAccount\",\n    \"Transaction\": \"usb:Transaction\",\n    \"Payment\": \"PayAction\",\n    \"Organization\": \"Organization\",\n    \"FinancialProduct\": \"FinancialProduct\",\n\n    \"accountNumber\": \"usb:accountNumber\",\n    \"accountType\": \"usb:accountType\",\n    \"accountName\": \"name\",\n    \"currency\": \"usb:currency\",\n    \"status\": \"actionStatus\",\n\n    \"transactionId\": \"usb:transactionId\",\n    \"amount\": \"price\",\n    \"transactionDate\": {\n      \"@id\": \"usb:transactionDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"valueDate\": {\n      \"@id\": \"usb:valueDate\",\n      \"@type\"\
  : \"xsd:date\"\n    },\n    \"description\": \"description\",\n    \"transactionType\": \"usb:transactionType\",\n    \"referenceNumber\": \"usb:referenceNumber\",\n    \"bankReference\": \"usb:bankReference\",\n\n    \"availableBalance\": \"usb:availableBalance\",\n    \"ledgerBalance\": \"usb:ledgerBalance\",\n    \"collectedBalance\": \"usb:collectedBalance\",\n    \"balanceDate\": {\n      \"@id\": \"usb:balanceDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"routingNumber\": \"usb:routingNumber\",\n    \"payerAccountNumber\": \"usb:payerAccountNumber\",\n    \"payeeAccountNumber\": \"usb:payeeAccountNumber\",\n    \"payeeName\": \"usb:payeeName\",\n    \"remittanceInfo\": \"usb:remittanceInfo\",\n\n    \"RTPPayment\": \"usb:RTPPayment\",\n    \"ACHPayment\": \"usb:ACHPayment\",\n    \"WireTransfer\": \"usb:WireTransfer\",\n    \"PushToCardPayment\": \"usb:PushToCardPayment\",\n    \"PositivePayException\": \"usb:PositivePayException\",\n\n    \"USBancorp\": {\n      \"@id\"\
  : \"usb:USBancorp\",\n      \"@type\": \"Organization\"\n    },\n    \"USBank\": {\n      \"@id\": \"usb:USBank\",\n      \"@type\": \"Organization\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-bancorp/refs/heads/main/json-ld/us-bancorp-context.jsonld
tags:
- Banking
- Finance
- Fortune 500
- Corporate Banking
- Payments
- Open Banking
- Treasury Management
- Consumer Banking
- JSON-LD
- Linked Data
- Semantic Web
---
