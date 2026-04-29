---
class_count: 1
classes:
- ReversalRequest
context_file: json-ld/adyen-terminal-reversal-request-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-reversal-request-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Reversal Request from Adyen.
layout: jsonld
name: Adyen Terminal Reversal Request Context
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
  name: OriginalPOITransaction
  type: string
- container: ''
  name: ReversedAmount
  type: decimal
- container: ''
  name: ReversalReason
  type: string
- container: ''
  name: CustomerOrder
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-reversal-request-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReversalRequest\": \"adyen:ReversalRequest\",\n    \"SaleData\": {\n      \"@id\": \"adyen:SaleData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginalPOITransaction\": {\n      \"@id\": \"adyen:OriginalPOITransaction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReversedAmount\": {\n      \"@id\": \"adyen:ReversedAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ReversalReason\": {\n      \"@id\": \"adyen:ReversalReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerOrder\": {\n      \"@id\": \"adyen:CustomerOrder\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-reversal-request-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
