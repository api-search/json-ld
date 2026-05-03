---
api_specs:
- filename: swift-swiftref-api-openapi.yml
  format: yaml
  label: SwiftRef API
  slug: swiftref-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/openapi/swift-swiftref-api-openapi.yml
class_count: 19
classes:
- BIC
- IBAN
- LEI
- NationalId
- Transaction
- PaymentInstruction
- id
- bic
- iban
- lei
- institutionName
- city
- address
- status
- currencyCode
- legalName
- registrationStatus
- uetr
- nationalId
context_file: json-ld/swift-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/json-ld/swift-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Swift from SWIFT.
layout: jsonld
name: Swift Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: swift
  uri: https://www.swift.com/vocab#
- prefix: gleif
  uri: https://www.gleif.org/ontology/Base/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: countryCode
  type: schema:Country
property_count: 1
provider_name: SWIFT
provider_slug: swift
slug: swift-context
source_filename: swift-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"swift\": \"https://www.swift.com/vocab#\",\n    \"gleif\": \"https://www.gleif.org/ontology/Base/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"BIC\": \"swift:BankIdentifierCode\",\n    \"IBAN\": \"swift:InternationalBankAccountNumber\",\n    \"LEI\": \"gleif:LegalEntityIdentifier\",\n    \"NationalId\": \"swift:NationalClearingCode\",\n    \"Transaction\": \"swift:FinancialTransaction\",\n    \"PaymentInstruction\": \"swift:PaymentInstruction\",\n\n    \"id\": \"@id\",\n    \"bic\": \"swift:bic\",\n    \"iban\": \"swift:iban\",\n    \"lei\": \"gleif:lei\",\n    \"institutionName\": \"schema:name\",\n    \"countryCode\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"schema:Country\"\n    },\n    \"city\": \"schema:addressLocality\",\n    \"address\": \"schema:streetAddress\",\n    \"status\": \"schema:additionalType\",\n    \"currencyCode\": \"\
  schema:priceCurrency\",\n    \"legalName\": \"schema:legalName\",\n    \"registrationStatus\": \"gleif:EntityStatus\",\n    \"uetr\": \"swift:UniqueEndToEndTransactionReference\",\n    \"nationalId\": \"swift:nationalClearingCode\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/swift/refs/heads/main/json-ld/swift-context.jsonld
tags:
- Banking
- Cross-Border Payments
- Financial Messaging
- Financial Services
- GPI
- ISO 20022
- Payments
- JSON-LD
- Linked Data
- Semantic Web
---
