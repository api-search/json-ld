---
class_count: 1
classes:
- ReceiptOptions
context_file: json-ld/adyen-management-receipt-options-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-receipt-options-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Receipt Options from Adyen.
layout: jsonld
name: Adyen Management Receipt Options Context
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
  name: logo
  type: string
- container: ''
  name: promptBeforePrinting
  type: boolean
- container: ''
  name: qrCodeData
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-receipt-options-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ReceiptOptions\": \"adyen:ReceiptOptions\",\n    \"logo\": {\n      \"@id\": \"adyen:logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"promptBeforePrinting\": {\n      \"@id\": \"adyen:promptBeforePrinting\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"qrCodeData\": {\n      \"@id\": \"adyen:qrCodeData\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-receipt-options-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
