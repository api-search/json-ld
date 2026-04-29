---
class_count: 1
classes:
- CurrencyConversion
context_file: json-ld/adyen-terminal-currency-conversion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-currency-conversion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Terminal Currency Conversion from Adyen.
layout: jsonld
name: Adyen Terminal Currency Conversion Context
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
  name: CustomerApprovedFlag
  type: boolean
- container: ''
  name: ConvertedAmount
  type: string
- container: ''
  name: Rate
  type: string
- container: ''
  name: Markup
  type: string
- container: ''
  name: Commission
  type: decimal
- container: ''
  name: Declaration
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-terminal-currency-conversion-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CurrencyConversion\": \"adyen:CurrencyConversion\",\n    \"CustomerApprovedFlag\": {\n      \"@id\": \"adyen:CustomerApprovedFlag\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ConvertedAmount\": {\n      \"@id\": \"adyen:ConvertedAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rate\": {\n      \"@id\": \"adyen:Rate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Markup\": {\n      \"@id\": \"adyen:Markup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Commission\": {\n      \"@id\": \"adyen:Commission\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Declaration\": {\n      \"@id\": \"adyen:Declaration\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-terminal-currency-conversion-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
