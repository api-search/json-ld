---
class_count: 1
classes:
- AdditionalData3DSecure
context_file: json-ld/adyen-checkout-additional-data3-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-additional-data3-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Additional Data3 from Adyen.
layout: jsonld
name: Adyen Checkout Additional Data3 Context
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
  name: allow3DS2
  type: string
- container: ''
  name: challengeWindowSize
  type: string
- container: ''
  name: executeThreeD
  type: string
- container: ''
  name: mpiImplementationType
  type: string
- container: ''
  name: scaExemption
  type: string
- container: ''
  name: threeDSVersion
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-additional-data3-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AdditionalData3DSecure\": \"adyen:AdditionalData3DSecure\",\n    \"allow3DS2\": {\n      \"@id\": \"adyen:allow3DS2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"challengeWindowSize\": {\n      \"@id\": \"adyen:challengeWindowSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executeThreeD\": {\n      \"@id\": \"adyen:executeThreeD\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mpiImplementationType\": {\n      \"@id\": \"adyen:mpiImplementationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scaExemption\": {\n      \"@id\": \"adyen:scaExemption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDSVersion\": {\n      \"@id\": \"adyen:threeDSVersion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-additional-data3-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
