---
class_count: 0
classes: []
context_file: json-ld/bancomat-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bancomat/refs/heads/main/json-ld/bancomat-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bancomat from Bancomat.
layout: jsonld
name: Bancomat Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bancomat
  uri: https://bancomat.it/vocab/
properties:
- container: ''
  name: Payment
  type: reference
- container: ''
  name: paymentId
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: Merchant
  type: reference
- container: ''
  name: merchantId
  type: string
- container: ''
  name: merchantName
  type: string
- container: ''
  name: QRCode
  type: reference
- container: ''
  name: qrContent
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: iban
  type: string
- container: ''
  name: phoneNumber
  type: string
property_count: 15
provider_name: Bancomat
provider_slug: bancomat
slug: bancomat-context
tags:
- ATM
- Banking
- Financial Services
- Italy
- Mobile Payments
- Payments
- Debit Cards
- JSON-LD
- Linked Data
- Semantic Web
---
