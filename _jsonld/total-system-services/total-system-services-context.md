---
api_specs:
- filename: tsys-payment-gateway-openapi.yml
  format: yaml
  label: TSYS Payment Gateway
  slug: tsys-payment-gateway
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/openapi/tsys-payment-gateway-openapi.yml
- filename: tsys-issuing-openapi.yml
  format: yaml
  label: TSYS Issuing Platform
  slug: tsys-issuing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/openapi/tsys-issuing-openapi.yml
class_count: 45
classes:
- Transaction
- id
- merchantId
- orderId
- status
- amount
- settledAmount
- currency
- cardType
- lastFour
- authorizationCode
- batchId
- createdAt
- settledAt
- Account
- programId
- cardholder
- availableBalance
- creditLimit
- Card
- accountId
- type
- network
- expirationDate
- issuedAt
- activatedAt
- Cardholder
- firstName
- lastName
- email
- phone
- dateOfBirth
- address
- SpendingControls
- dailyLimit
- monthlyLimit
- transactionLimit
- internationalEnabled
- onlineEnabled
- atmEnabled
- Dispute
- transactionId
- reason
- filedAt
- resolvedAt
context_file: json-ld/total-system-services-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/json-ld/total-system-services-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Total System Services from Total System Services.
layout: jsonld
name: Total System Services Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tsys
  uri: https://api.tsys.com/vocab#
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Total System Services
provider_slug: total-system-services
slug: total-system-services-context
source_filename: total-system-services-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tsys\": \"https://api.tsys.com/vocab#\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Transaction\": \"schema:PayAction\",\n    \"id\": \"@id\",\n    \"merchantId\": \"tsys:merchantId\",\n    \"orderId\": \"schema:orderNumber\",\n    \"status\": \"tsys:transactionStatus\",\n    \"amount\": \"schema:totalPrice\",\n    \"settledAmount\": \"tsys:settledAmount\",\n    \"currency\": \"schema:priceCurrency\",\n    \"cardType\": \"tsys:cardNetwork\",\n    \"lastFour\": \"tsys:maskedCardNumber\",\n    \"authorizationCode\": \"schema:confirmationNumber\",\n    \"batchId\": \"tsys:settlementBatch\",\n    \"createdAt\": \"schema:startTime\",\n    \"settledAt\": \"tsys:settlementDate\",\n\n    \"Account\": \"schema:FinancialProduct\",\n    \"programId\": \"tsys:cardProgramId\",\n    \"cardholder\": \"schema:customer\"\
  ,\n    \"availableBalance\": \"tsys:availableBalance\",\n    \"creditLimit\": \"tsys:creditLimit\",\n\n    \"Card\": \"tsys:PaymentCard\",\n    \"accountId\": \"tsys:relatedAccount\",\n    \"type\": \"tsys:cardDeliveryMethod\",\n    \"network\": \"tsys:cardNetwork\",\n    \"expirationDate\": \"tsys:cardExpiry\",\n    \"issuedAt\": \"schema:dateIssued\",\n    \"activatedAt\": \"tsys:activationDate\",\n\n    \"Cardholder\": \"schema:Person\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"dateOfBirth\": \"schema:birthDate\",\n    \"address\": \"schema:address\",\n\n    \"SpendingControls\": \"tsys:SpendingControls\",\n    \"dailyLimit\": \"tsys:dailySpendingLimit\",\n    \"monthlyLimit\": \"tsys:monthlySpendingLimit\",\n    \"transactionLimit\": \"tsys:perTransactionLimit\",\n    \"internationalEnabled\": \"tsys:internationalTransactionsEnabled\",\n    \"onlineEnabled\": \"\
  tsys:onlineTransactionsEnabled\",\n    \"atmEnabled\": \"tsys:atmWithdrawalsEnabled\",\n\n    \"Dispute\": \"tsys:PaymentDispute\",\n    \"transactionId\": \"tsys:disputedTransaction\",\n    \"reason\": \"tsys:disputeReason\",\n    \"filedAt\": \"tsys:disputeFiledDate\",\n    \"resolvedAt\": \"tsys:disputeResolvedDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/total-system-services/refs/heads/main/json-ld/total-system-services-context.jsonld
tags:
- Payments
- Payment Processing
- Card Issuing
- Merchant Services
- Fintech
- Financial Services
- JSON-LD
- Linked Data
- Semantic Web
---
