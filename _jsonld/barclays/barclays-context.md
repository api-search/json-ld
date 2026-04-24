---
class_count: 2
classes:
- name
- description
context_file: json-ld/barclays-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/json-ld/barclays-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Barclays from Barclays.
layout: jsonld
name: Barclays Context
namespaces:
- prefix: barclays
  uri: https://developer.barclays.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/FND/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Account
  type: reference
- container: ''
  name: Transaction
  type: reference
- container: ''
  name: Payment
  type: reference
- container: ''
  name: Consent
  type: reference
- container: ''
  name: PaymentConsent
  type: reference
- container: ''
  name: AccountConsent
  type: reference
- container: ''
  name: FundsConfirmation
  type: reference
- container: ''
  name: accountId
  type: string
- container: ''
  name: balance
  type: decimal
- container: ''
  name: currency
  type: string
- container: ''
  name: amount
  type: decimal
- container: ''
  name: transactionId
  type: string
- container: ''
  name: creditorAccount
  type: reference
- container: ''
  name: debtorAccount
  type: reference
- container: ''
  name: fundsAvailable
  type: boolean
- container: ''
  name: consentId
  type: string
- container: ''
  name: status
  type: string
property_count: 17
provider_name: Barclays
provider_slug: barclays
slug: barclays-context
tags:
- Banking
- Credit Cards
- Finance
- Open Banking
- Payments
- PSD2
- UK Banking
- JSON-LD
- Linked Data
- Semantic Web
---
