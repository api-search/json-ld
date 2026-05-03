---
api_specs:
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Payments API
  slug: visa-acceptance-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Invoicing API
  slug: visa-acceptance-invoicing
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
- filename: visa-acceptance-payments-openapi.yml
  format: yaml
  label: Visa Acceptance Pay by Link API
  slug: visa-acceptance-pay-by-link
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/openapi/visa-acceptance-payments-openapi.yml
class_count: 0
classes: []
context_file: json-ld/visa-acceptance-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/json-ld/visa-acceptance-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Visa Acceptance from Visa Acceptance.
layout: jsonld
name: Visa Acceptance Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: payment
  uri: https://developer.visaacceptance.com/vocab/payment/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/Accounting/CurrencyAmount/
properties:
- container: ''
  name: Payment
  type: reference
- container: ''
  name: Invoice
  type: reference
- container: ''
  name: PayByLink
  type: reference
- container: ''
  name: Authorization
  type: reference
- container: ''
  name: Capture
  type: reference
- container: ''
  name: Refund
  type: reference
- container: ''
  name: Void
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: submitTimeUtc
  type: http://www.w3.org/2001/XMLSchema#dateTime
- container: ''
  name: totalAmount
  type: ''
- container: ''
  name: currency
  type: ''
- container: ''
  name: approvalCode
  type: ''
- container: ''
  name: orderInformation
  type: ''
- container: ''
  name: paymentInformation
  type: ''
- container: ''
  name: billTo
  type: ''
- container: ''
  name: shipTo
  type: ''
- container: ''
  name: firstName
  type: ''
- container: ''
  name: lastName
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: phoneNumber
  type: ''
- container: ''
  name: dueDate
  type: http://www.w3.org/2001/XMLSchema#date
- container: ''
  name: invoiceUrl
  type: ''
- container: ''
  name: paymentLink
  type: ''
- container: ''
  name: expirationDate
  type: http://www.w3.org/2001/XMLSchema#dateTime
property_count: 25
provider_name: Visa Acceptance
provider_slug: visa-acceptance
slug: visa-acceptance-context
source_filename: visa-acceptance-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://developer.visaacceptance.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"payment\": \"https://developer.visaacceptance.com/vocab/payment/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/Accounting/CurrencyAmount/\",\n\n    \"Payment\": {\n      \"@id\": \"schema:PaymentService\",\n      \"@type\": \"@id\"\n    },\n    \"Invoice\": {\n      \"@id\": \"schema:Invoice\",\n      \"@type\": \"@id\"\n    },\n    \"PayByLink\": {\n      \"@id\": \"https://developer.visaacceptance.com/vocab/PayByLink\",\n      \"@type\": \"@id\"\n    },\n    \"Authorization\": {\n      \"@id\": \"https://developer.visaacceptance.com/vocab/Authorization\",\n      \"@type\": \"@id\"\n    },\n    \"Capture\": {\n      \"@id\": \"https://developer.visaacceptance.com/vocab/Capture\",\n      \"@type\": \"@id\"\n    },\n    \"Refund\": {\n      \"@id\": \"schema:RefundTypeEnumeration\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"Void\": {\n      \"@id\": \"https://developer.visaacceptance.com/vocab/Void\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\"\n    },\n    \"submitTimeUtc\": {\n      \"@id\": \"schema:datePosted\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n    },\n    \"totalAmount\": {\n      \"@id\": \"schema:totalPrice\"\n    },\n    \"currency\": {\n      \"@id\": \"schema:priceCurrency\"\n    },\n    \"approvalCode\": {\n      \"@id\": \"https://developer.visaacceptance.com/vocab/approvalCode\"\n    },\n    \"orderInformation\": {\n      \"@id\": \"schema:orderDetails\"\n    },\n    \"paymentInformation\": {\n      \"@id\": \"schema:paymentMethod\"\n    },\n    \"billTo\": {\n      \"@id\": \"schema:billingAddress\"\n    },\n    \"shipTo\": {\n      \"@id\": \"schema:deliveryAddress\"\n    },\n    \"firstName\": {\n      \"@id\": \"schema:givenName\"\n    },\n    \"lastName\"\
  : {\n      \"@id\": \"schema:familyName\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\"\n    },\n    \"phoneNumber\": {\n      \"@id\": \"schema:telephone\"\n    },\n    \"dueDate\": {\n      \"@id\": \"schema:paymentDueDate\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#date\"\n    },\n    \"invoiceUrl\": {\n      \"@id\": \"schema:url\"\n    },\n    \"paymentLink\": {\n      \"@id\": \"schema:url\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"http://www.w3.org/2001/XMLSchema#dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/visa-acceptance/refs/heads/main/json-ld/visa-acceptance-context.jsonld
tags:
- Payments
- E-Commerce
- Fintech
- Credit Cards
- Invoicing
- Payment Links
- Digital Wallets
- JSON-LD
- Linked Data
- Semantic Web
---
