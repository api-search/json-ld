---
class_count: 1
classes:
- BrowserInfo
context_file: json-ld/adyen-payments-browser-info-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-browser-info-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Browser Info from Adyen.
layout: jsonld
name: Adyen Payments Browser Info Context
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
  name: acceptHeader
  type: string
- container: ''
  name: colorDepth
  type: integer
- container: ''
  name: javaEnabled
  type: boolean
- container: ''
  name: javaScriptEnabled
  type: boolean
- container: ''
  name: language
  type: string
- container: ''
  name: screenHeight
  type: integer
- container: ''
  name: screenWidth
  type: integer
- container: ''
  name: timeZoneOffset
  type: integer
- container: ''
  name: userAgent
  type: string
property_count: 9
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-browser-info-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BrowserInfo\": \"adyen:BrowserInfo\",\n    \"acceptHeader\": {\n      \"@id\": \"adyen:acceptHeader\",\n      \"@type\": \"xsd:string\"\n    },\n    \"colorDepth\": {\n      \"@id\": \"adyen:colorDepth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"javaEnabled\": {\n      \"@id\": \"adyen:javaEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"javaScriptEnabled\": {\n      \"@id\": \"adyen:javaScriptEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"language\": {\n      \"@id\": \"adyen:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"screenHeight\": {\n      \"@id\": \"adyen:screenHeight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"screenWidth\": {\n      \"@id\": \"adyen:screenWidth\",\n \
  \     \"@type\": \"xsd:integer\"\n    },\n    \"timeZoneOffset\": {\n      \"@id\": \"adyen:timeZoneOffset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userAgent\": {\n      \"@id\": \"adyen:userAgent\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-browser-info-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
