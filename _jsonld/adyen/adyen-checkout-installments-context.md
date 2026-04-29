---
class_count: 1
classes:
- Installments
context_file: json-ld/adyen-checkout-installments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-installments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Installments from Adyen.
layout: jsonld
name: Adyen Checkout Installments Context
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
  name: plan
  type: string
- container: ''
  name: value
  type: integer
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-installments-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Installments\": \"adyen:Installments\",\n    \"plan\": {\n      \"@id\": \"adyen:plan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"adyen:value\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-installments-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
