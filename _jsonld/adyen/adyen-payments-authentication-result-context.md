---
class_count: 2
classes:
- AuthenticationResultRequest
- AuthenticationResultResponse
context_file: json-ld/adyen-payments-authentication-result-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-authentication-result-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Authentication Result from Adyen.
layout: jsonld
name: Adyen Payments Authentication Result Context
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
  name: merchantAccount
  type: string
- container: ''
  name: pspReference
  type: string
- container: ''
  name: threeDS1Result
  type: string
- container: ''
  name: threeDS2Result
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-authentication-result-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AuthenticationResultRequest\": \"adyen:AuthenticationResultRequest\",\n    \"AuthenticationResultResponse\": \"adyen:AuthenticationResultResponse\",\n    \"merchantAccount\": {\n      \"@id\": \"adyen:merchantAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pspReference\": {\n      \"@id\": \"adyen:pspReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS1Result\": {\n      \"@id\": \"adyen:threeDS1Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDS2Result\": {\n      \"@id\": \"adyen:threeDS2Result\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-authentication-result-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
