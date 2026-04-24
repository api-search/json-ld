---
class_count: 0
classes: []
context_file: json-ld/bancontact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/bancontact/refs/heads/main/json-ld/bancontact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bancontact from Bancontact.
layout: jsonld
name: Bancontact Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: bancontact
  uri: https://www.bancontact.com/vocab/
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
  name: description
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: QRCode
  type: reference
- container: ''
  name: qrContent
  type: string
- container: ''
  name: deeplink
  type: anyURI
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
  name: Refund
  type: reference
- container: ''
  name: refundId
  type: string
- container: ''
  name: refundAmount
  type: decimal
- container: ''
  name: originalPaymentId
  type: string
property_count: 18
provider_name: Bancontact
provider_slug: bancontact
slug: bancontact-context
tags:
- Banking
- Belgium
- Debit Cards
- E-Commerce
- Fintech
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
