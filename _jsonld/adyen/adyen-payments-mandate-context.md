---
class_count: 1
classes:
- Mandate
context_file: json-ld/adyen-payments-mandate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-mandate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Mandate from Adyen.
layout: jsonld
name: Adyen Payments Mandate Context
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
  name: amount
  type: string
- container: ''
  name: amountRule
  type: string
- container: ''
  name: billingAttemptsRule
  type: string
- container: ''
  name: billingDay
  type: string
- container: ''
  name: endsAt
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: remarks
  type: string
- container: ''
  name: startsAt
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-mandate-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Mandate\": \"adyen:Mandate\",\n    \"amount\": {\n      \"@id\": \"adyen:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amountRule\": {\n      \"@id\": \"adyen:amountRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingAttemptsRule\": {\n      \"@id\": \"adyen:billingAttemptsRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingDay\": {\n      \"@id\": \"adyen:billingDay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endsAt\": {\n      \"@id\": \"adyen:endsAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"adyen:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remarks\": {\n      \"@id\": \"adyen:remarks\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"startsAt\": {\n      \"@id\": \"adyen:startsAt\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-mandate-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
