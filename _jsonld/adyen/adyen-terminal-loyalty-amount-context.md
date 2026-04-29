---
class_count: 1
classes:
- LoyaltyAmount
context_file: json-ld/adyen-terminal-loyalty-amount-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-amount-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Amount from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Amount Context
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
  name: LoyaltyUnit
  type: string
- container: ''
  name: Currency
  type: string
- container: ''
  name: AmountValue
  type: decimal
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-amount-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyAmount\": \"adyen:LoyaltyAmount\",\n    \"LoyaltyUnit\": {\n      \"@id\": \"adyen:LoyaltyUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Currency\": {\n      \"@id\": \"adyen:Currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AmountValue\": {\n      \"@id\": \"adyen:AmountValue\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-amount-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
