---
api_specs:
- filename: western-union-mass-payments-openapi.yml
  format: yaml
  label: Western Union Mass Payments API
  slug: mass-payments
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/openapi/western-union-mass-payments-openapi.yml
class_count: 0
classes: []
context_file: json-ld/western-union-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/json-ld/western-union-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Western Union from western-union.
layout: jsonld
name: Western Union Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: fibo
  uri: https://spec.edmcouncil.org/fibo/ontology/
- prefix: wu
  uri: https://developer.westernunion.com/ontology/
properties:
- container: ''
  name: Payment
  type: reference
- container: ''
  name: paymentId
  type: string
- container: ''
  name: paymentStatus
  type: string
- container: ''
  name: partnerReference
  type: string
- container: ''
  name: paymentReference
  type: string
- container: ''
  name: amount
  type: integer
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: settlementAmount
  type: integer
- container: ''
  name: settlementCurrency
  type: string
- container: ''
  name: purposeOfPayment
  type: string
- container: ''
  name: Batch
  type: reference
- container: ''
  name: batchId
  type: string
- container: ''
  name: batchReference
  type: string
- container: ''
  name: numberOfReceivedPayments
  type: integer
- container: ''
  name: numberOfAcceptedPayments
  type: integer
- container: ''
  name: Beneficiary
  type: reference
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: BankAccount
  type: reference
- container: ''
  name: accountNumber
  type: string
- container: ''
  name: bankCode
  type: string
- container: ''
  name: Quote
  type: reference
- container: ''
  name: fxRate
  type: double
- container: ''
  name: expirationIntervalInSec
  type: integer
- container: ''
  name: Address
  type: reference
- container: ''
  name: line1
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: countryCode
  type: string
property_count: 29
provider_name: western-union
provider_slug: western-union
slug: western-union-context
source_filename: western-union-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"fibo\": \"https://spec.edmcouncil.org/fibo/ontology/\",\n    \"wu\": \"https://developer.westernunion.com/ontology/\",\n\n    \"Payment\": {\n      \"@id\": \"schema:PayAction\",\n      \"@type\": \"@id\"\n    },\n    \"paymentId\": {\n      \"@id\": \"wu:paymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerReference\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentReference\": {\n      \"@id\": \"wu:paymentReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"schema:priceCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"settlementAmount\": {\n      \"@id\": \"wu:settlementAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"settlementCurrency\": {\n      \"@id\": \"wu:settlementCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purposeOfPayment\": {\n      \"@id\": \"wu:purposeOfPayment\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Batch\": {\n      \"@id\": \"wu:Batch\",\n      \"@type\": \"@id\"\n    },\n    \"batchId\": {\n      \"@id\": \"wu:batchId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"batchReference\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfReceivedPayments\": {\n      \"@id\": \"wu:numberOfReceivedPayments\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfAcceptedPayments\": {\n      \"@id\": \"wu:numberOfAcceptedPayments\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Beneficiary\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\": {\n   \
  \   \"@id\": \"schema:givenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"schema:familyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"BankAccount\": {\n      \"@id\": \"schema:BankAccount\",\n      \"@type\": \"@id\"\n    },\n    \"accountNumber\": {\n      \"@id\": \"schema:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankCode\": {\n      \"@id\": \"wu:bankCode\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"Quote\": {\n      \"@id\": \"schema:PriceSpecification\",\n      \"@type\": \"@id\"\n    },\n    \"fxRate\": {\n      \"@id\": \"wu:fxRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"expirationIntervalInSec\": {\n      \"@id\": \"wu:expirationInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"Address\": {\n      \"@id\": \"schema:PostalAddress\",\n      \"@type\": \"@id\"\n    },\n    \"line1\": {\n\
  \      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/western-union/refs/heads/main/json-ld/western-union-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
