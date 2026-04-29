---
class_count: 2
classes:
- CapitalGrantInfo
- CapitalGrant
context_file: json-ld/adyen-transfers-capital-grant-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-capital-grant-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Capital Grant from Adyen.
layout: jsonld
name: Adyen Transfers Capital Grant Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: counterparty
  type: string
- container: ''
  name: grantAccountId
  type: string
- container: ''
  name: grantOfferId
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: balances
  type: string
- container: ''
  name: fee
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: repayment
  type: string
- container: ''
  name: status
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-capital-grant-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CapitalGrantInfo\": \"adyen:CapitalGrantInfo\",\n    \"CapitalGrant\": \"adyen:CapitalGrant\",\n    \"counterparty\": {\n      \"@id\": \"adyen:counterparty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grantAccountId\": {\n      \"@id\": \"adyen:grantAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grantOfferId\": {\n      \"@id\": \"adyen:grantOfferId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"balances\": {\n      \"@id\": \"adyen:balances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fee\": {\n      \"@id\": \"adyen:fee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"repayment\": {\n      \"@id\": \"adyen:repayment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-capital-grant-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
