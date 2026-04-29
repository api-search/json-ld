---
class_count: 1
classes:
- ForexQuote
context_file: json-ld/adyen-payments-forex-quote-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-forex-quote-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Forex Quote from Adyen.
layout: jsonld
name: Adyen Payments Forex Quote Context
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
  name: account
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: baseAmount
  type: string
- container: ''
  name: basePoints
  type: integer
- container: ''
  name: buy
  type: string
- container: ''
  name: interbank
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: sell
  type: string
- container: ''
  name: signature
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: validTill
  type: dateTime
property_count: 12
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-forex-quote-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ForexQuote\": \"adyen:ForexQuote\",\n    \"account\": {\n      \"@id\": \"adyen:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"adyen:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseAmount\": {\n      \"@id\": \"adyen:baseAmount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basePoints\": {\n      \"@id\": \"adyen:basePoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"buy\": {\n      \"@id\": \"adyen:buy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interbank\": {\n      \"@id\": \"adyen:interbank\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"adyen:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sell\"\
  : {\n      \"@id\": \"adyen:sell\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signature\": {\n      \"@id\": \"adyen:signature\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"adyen:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validTill\": {\n      \"@id\": \"adyen:validTill\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-forex-quote-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
