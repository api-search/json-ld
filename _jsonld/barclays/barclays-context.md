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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"barclays\": \"https://developer.barclays.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/FND/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": {\n      \"@id\": \"barclays:Account\",\n      \"@type\": \"@id\"\n    },\n    \"Transaction\": {\n      \"@id\": \"barclays:Transaction\",\n      \"@type\": \"@id\"\n    },\n    \"Payment\": {\n      \"@id\": \"barclays:Payment\",\n      \"@type\": \"@id\"\n    },\n    \"Consent\": {\n      \"@id\": \"barclays:Consent\",\n      \"@type\": \"@id\"\n    },\n    \"PaymentConsent\": {\n      \"@id\": \"barclays:PaymentConsent\",\n      \"@type\": \"@id\"\n    },\n    \"AccountConsent\": {\n      \"@id\": \"barclays:AccountConsent\",\n      \"@type\": \"@id\"\n    },\n    \"FundsConfirmation\": {\n      \"@id\": \"barclays:FundsConfirmation\",\n      \"@type\": \"@id\"\n    },\n    \"accountId\"\
  : {\n      \"@id\": \"barclays:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balance\": {\n      \"@id\": \"barclays:balance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": {\n      \"@id\": \"barclays:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"barclays:amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transactionId\": {\n      \"@id\": \"barclays:transactionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creditorAccount\": {\n      \"@id\": \"barclays:creditorAccount\",\n      \"@type\": \"@id\"\n    },\n    \"debtorAccount\": {\n      \"@id\": \"barclays:debtorAccount\",\n      \"@type\": \"@id\"\n    },\n    \"fundsAvailable\": {\n      \"@id\": \"barclays:fundsAvailable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"consentId\": {\n      \"@id\": \"barclays:consentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"barclays:status\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/barclays/refs/heads/main/json-ld/barclays-context.jsonld
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
