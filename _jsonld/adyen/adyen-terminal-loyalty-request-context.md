---
class_count: 1
classes:
- LoyaltyRequest
context_file: json-ld/adyen-terminal-loyalty-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Request from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Request Context
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
  name: SaleData
  type: string
- container: ''
  name: LoyaltyTransaction
  type: string
- container: ''
  name: LoyaltyData
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyRequest\": \"adyen:LoyaltyRequest\",\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyTransaction\": {\n      \"@id\": \"adyen:LoyaltyTransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyData\": {\n      \"@id\": \"adyen:LoyaltyData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
