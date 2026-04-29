---
class_count: 1
classes:
- PaymentToken
context_file: json-ld/adyen-terminal-payment-token-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-token-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Payment Token from Adyen.
layout: jsonld
name: Adyen Terminal Payment Token Context
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
  name: TokenRequestedType
  type: string
- container: ''
  name: TokenValue
  type: string
- container: ''
  name: ExpiryDateTime
  type: dateTime
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-payment-token-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PaymentToken\": \"adyen:PaymentToken\",\n    \"TokenRequestedType\": {\n      \"@id\": \"adyen:TokenRequestedType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TokenValue\": {\n      \"@id\": \"adyen:TokenValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiryDateTime\": {\n      \"@id\": \"adyen:ExpiryDateTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-payment-token-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
