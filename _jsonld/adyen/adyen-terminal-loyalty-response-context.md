---
class_count: 1
classes:
- LoyaltyResponse
context_file: json-ld/adyen-terminal-loyalty-response-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-response-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Loyalty Response from Adyen.
layout: jsonld
name: Adyen Terminal Loyalty Response Context
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
  name: Response
  type: string
- container: ''
  name: SaleData
  type: string
- container: ''
  name: POIData
  type: string
- container: set
  name: LoyaltyResult
  type: string
- container: set
  name: PaymentReceipt
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-loyalty-response-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LoyaltyResponse\": \"adyen:LoyaltyResponse\",\n    \"Response\": {\n      \"@id\": \"adyen:Response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"POIData\": {\n      \"@id\": \"adyen:POIData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoyaltyResult\": {\n      \"@id\": \"adyen:LoyaltyResult\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaymentReceipt\": {\n      \"@id\": \"adyen:PaymentReceipt\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-loyalty-response-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
