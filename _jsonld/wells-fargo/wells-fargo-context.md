---
api_specs:
- filename: wells-fargo-gateway-api-openapi.yml
  format: yaml
  label: Wells Fargo Gateway API
  slug: gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-gateway-api-openapi.yml
- filename: wells-fargo-account-transactions-api-openapi.yml
  format: yaml
  label: Wells Fargo Account Transactions API
  slug: account-transactions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-account-transactions-api-openapi.yml
- filename: wells-fargo-ach-payments-api-openapi.yml
  format: yaml
  label: Wells Fargo ACH Payments API
  slug: ach-payments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/openapi/wells-fargo-ach-payments-api-openapi.yml
class_count: 6
classes:
- WellsFargoAccount
- WellsFargoPayment
- WellsFargoTransaction
- WellsFargoACHPayment
- WellsFargoWireTransfer
- WellsFargoCustomer
context_file: json-ld/wells-fargo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/json-ld/wells-fargo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wells Fargo from wells-fargo.
layout: jsonld
name: Wells Fargo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wf
  uri: https://developer.wellsfargo.com/vocab#
properties:
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: ledgerBalance
  type: decimal
- container: ''
  name: availableBalance
  type: decimal
- container: ''
  name: intradayPosition
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: transactionId
  type: string
- container: ''
  name: transactionType
  type: string
- container: ''
  name: debitCreditIndicator
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionDate
  type: date
- container: ''
  name: postingDate
  type: date
- container: ''
  name: transactionStatus
  type: string
- container: ''
  name: counterpartyName
  type: string
- container: ''
  name: referenceNumber
  type: string
- container: ''
  name: paymentId
  type: string
- container: ''
  name: paymentStatus
  type: string
- container: ''
  name: debitAccountId
  type: string
- container: ''
  name: creditAccountNumber
  type: string
- container: ''
  name: creditRoutingNumber
  type: string
- container: ''
  name: transactionCode
  type: string
- container: ''
  name: receiverName
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: settlementDate
  type: date
- container: ''
  name: traceNumber
  type: string
- container: ''
  name: sameDayAch
  type: boolean
property_count: 28
provider_name: wells-fargo
provider_slug: wells-fargo
slug: wells-fargo-context
source_filename: wells-fargo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wf\": \"https://developer.wellsfargo.com/vocab#\",\n\n    \"WellsFargoAccount\": \"schema:BankAccount\",\n    \"WellsFargoPayment\": \"schema:PayAction\",\n    \"WellsFargoTransaction\": \"schema:TransferAction\",\n    \"WellsFargoACHPayment\": \"schema:MoneyTransfer\",\n    \"WellsFargoWireTransfer\": \"schema:MoneyTransfer\",\n    \"WellsFargoCustomer\": \"schema:Organization\",\n\n    \"accountId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"accountNumber\": { \"@id\": \"wf:accountNumber\", \"@type\": \"xsd:string\" },\n    \"accountType\": { \"@id\": \"wf:accountType\", \"@type\": \"xsd:string\" },\n    \"accountName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"ledgerBalance\": { \"@id\": \"wf:ledgerBalance\", \"@type\"\
  : \"xsd:decimal\" },\n    \"availableBalance\": { \"@id\": \"wf:availableBalance\", \"@type\": \"xsd:decimal\" },\n    \"intradayPosition\": { \"@id\": \"wf:intradayPosition\", \"@type\": \"xsd:decimal\" },\n    \"currency\": { \"@id\": \"schema:currency\", \"@type\": \"xsd:string\" },\n\n    \"transactionId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"transactionType\": { \"@id\": \"wf:transactionType\", \"@type\": \"xsd:string\" },\n    \"debitCreditIndicator\": { \"@id\": \"wf:debitCreditIndicator\", \"@type\": \"xsd:string\" },\n    \"amount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"transactionDate\": { \"@id\": \"schema:startTime\", \"@type\": \"xsd:date\" },\n    \"postingDate\": { \"@id\": \"wf:postingDate\", \"@type\": \"xsd:date\" },\n    \"transactionStatus\": { \"@id\": \"wf:transactionStatus\", \"@type\": \"xsd:string\" },\n    \"counterpartyName\": { \"@id\": \"schema:recipient\", \"@type\": \"xsd:string\" },\n    \"referenceNumber\"\
  : { \"@id\": \"schema:orderNumber\", \"@type\": \"xsd:string\" },\n\n    \"paymentId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"paymentStatus\": { \"@id\": \"wf:paymentStatus\", \"@type\": \"xsd:string\" },\n    \"debitAccountId\": { \"@id\": \"schema:fromLocation\", \"@type\": \"xsd:string\" },\n    \"creditAccountNumber\": { \"@id\": \"schema:toLocation\", \"@type\": \"xsd:string\" },\n    \"creditRoutingNumber\": { \"@id\": \"wf:routingNumber\", \"@type\": \"xsd:string\" },\n    \"transactionCode\": { \"@id\": \"wf:nachaTransactionCode\", \"@type\": \"xsd:string\" },\n    \"receiverName\": { \"@id\": \"schema:recipient\", \"@type\": \"xsd:string\" },\n    \"effectiveDate\": { \"@id\": \"schema:scheduledTime\", \"@type\": \"xsd:date\" },\n    \"settlementDate\": { \"@id\": \"wf:settlementDate\", \"@type\": \"xsd:date\" },\n    \"traceNumber\": { \"@id\": \"wf:traceNumber\", \"@type\": \"xsd:string\" },\n    \"sameDayAch\": { \"@id\": \"wf:sameDayAch\", \"\
  @type\": \"xsd:boolean\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wells-fargo/refs/heads/main/json-ld/wells-fargo-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
