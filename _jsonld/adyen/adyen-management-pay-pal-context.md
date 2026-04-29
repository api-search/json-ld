---
class_count: 1
classes:
- PayPalInfo
context_file: json-ld/adyen-management-pay-pal-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-pay-pal-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Pay Pal from Adyen.
layout: jsonld
name: Adyen Management Pay Pal Context
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
  name: directCapture
  type: boolean
- container: ''
  name: payerId
  type: string
- container: ''
  name: subject
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-pay-pal-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayPalInfo\": \"adyen:PayPalInfo\",\n    \"directCapture\": {\n      \"@id\": \"adyen:directCapture\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"payerId\": {\n      \"@id\": \"adyen:payerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"adyen:subject\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-pay-pal-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
