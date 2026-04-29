---
class_count: 1
classes:
- StockData
context_file: json-ld/adyen-legal-entity-stock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-stock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Legal Entity Stock from Adyen.
layout: jsonld
name: Adyen Legal Entity Stock Context
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
  name: marketIdentifier
  type: string
- container: ''
  name: stockNumber
  type: string
- container: ''
  name: tickerSymbol
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-legal-entity-stock-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"StockData\": \"adyen:StockData\",\n    \"marketIdentifier\": {\n      \"@id\": \"adyen:marketIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stockNumber\": {\n      \"@id\": \"adyen:stockNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tickerSymbol\": {\n      \"@id\": \"adyen:tickerSymbol\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-legal-entity-stock-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
