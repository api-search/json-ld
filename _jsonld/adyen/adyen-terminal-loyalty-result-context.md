---
class_count: 1
classes:
- LoyaltyResult
context_file: json-ld/adyen-terminal-loyalty-result-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-result-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Result from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Result Context
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
  name: LoyaltyAccount
  type: string
- container: ''
  name: CurrentBalance
  type: decimal
- container: ''
  name: LoyaltyAmount
  type: string
- container: ''
  name: LoyaltyAcquirerData
  type: string
- container: ''
  name: Rebates
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-result-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyResult\": \"adyen:LoyaltyResult\",\n    \"LoyaltyAccount\": {\n      \"@id\": \"adyen:LoyaltyAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentBalance\": {\n      \"@id\": \"adyen:CurrentBalance\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"LoyaltyAmount\": {\n      \"@id\": \"adyen:LoyaltyAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyAcquirerData\": {\n      \"@id\": \"adyen:LoyaltyAcquirerData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rebates\": {\n      \"@id\": \"adyen:Rebates\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-result-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
