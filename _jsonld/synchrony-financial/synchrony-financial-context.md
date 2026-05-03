---
api_specs:
- filename: synchrony-financial-credit-authorization-openapi.yml
  format: yaml
  label: Synchrony Credit Authorization API
  slug: credit-authorization
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/openapi/synchrony-financial-credit-authorization-openapi.yml
- filename: synchrony-financial-quickscreen-apply-openapi.yml
  format: yaml
  label: Synchrony Quickscreen Apply API
  slug: quickscreen-apply
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/openapi/synchrony-financial-quickscreen-apply-openapi.yml
class_count: 24
classes:
- Transaction
- CreditApplication
- PreapprovalOffer
- transactionId
- authorizationCode
- merchantId
- accountNumber
- transactionStatus
- transactionType
- channel
- merchantOrderId
- applicationId
- creditLimit
- offerId
- preapprovalDecision
- firstName
- lastName
- email
- phone
- street
- city
- state
- zipCode
- country
context_file: json-ld/synchrony-financial-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/json-ld/synchrony-financial-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Synchrony Financial from Synchrony Financial.
layout: jsonld
name: Synchrony Financial Context
namespaces:
- prefix: syf
  uri: https://developer.syf.com/vocab/
properties:
- container: ''
  name: amount
  type: schema:Number
- container: ''
  name: timestamp
  type: schema:DateTime
property_count: 2
provider_name: Synchrony Financial
provider_slug: synchrony-financial
slug: synchrony-financial-context
source_filename: synchrony-financial-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"syf\": \"https://developer.syf.com/vocab/\",\n    \"Transaction\": \"syf:Transaction\",\n    \"CreditApplication\": \"syf:CreditApplication\",\n    \"PreapprovalOffer\": \"syf:PreapprovalOffer\",\n    \"transactionId\": \"syf:transactionId\",\n    \"authorizationCode\": \"syf:authorizationCode\",\n    \"merchantId\": \"syf:merchantId\",\n    \"accountNumber\": \"syf:accountNumber\",\n    \"transactionStatus\": \"syf:transactionStatus\",\n    \"transactionType\": \"syf:transactionType\",\n    \"channel\": \"syf:channel\",\n    \"merchantOrderId\": \"syf:merchantOrderId\",\n    \"applicationId\": \"syf:applicationId\",\n    \"creditLimit\": \"syf:creditLimit\",\n    \"offerId\": \"syf:offerId\",\n    \"preapprovalDecision\": \"syf:preapprovalDecision\",\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"schema:DateTime\"\n    },\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:email\",\n    \"phone\": \"schema:telephone\",\n    \"street\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\",\n    \"country\": \"schema:addressCountry\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/synchrony-financial/refs/heads/main/json-ld/synchrony-financial-context.jsonld
tags:
- Financial Services
- Credit
- Payments
- Consumer Finance
- Retail Finance
- JSON-LD
- Linked Data
- Semantic Web
---
