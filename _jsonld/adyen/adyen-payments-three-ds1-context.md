---
class_count: 1
classes:
- ThreeDS1Result
context_file: json-ld/adyen-payments-three-ds1-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-three-ds1-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Three Ds1 from Adyen.
layout: jsonld
name: Adyen Payments Three Ds1 Context
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
  name: cavv
  type: string
- container: ''
  name: cavvAlgorithm
  type: string
- container: ''
  name: eci
  type: string
- container: ''
  name: threeDAuthenticatedResponse
  type: string
- container: ''
  name: threeDOfferedResponse
  type: string
- container: ''
  name: xid
  type: string
property_count: 6
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-three-ds1-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ThreeDS1Result\": \"adyen:ThreeDS1Result\",\n    \"cavv\": {\n      \"@id\": \"adyen:cavv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cavvAlgorithm\": {\n      \"@id\": \"adyen:cavvAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eci\": {\n      \"@id\": \"adyen:eci\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDAuthenticatedResponse\": {\n      \"@id\": \"adyen:threeDAuthenticatedResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threeDOfferedResponse\": {\n      \"@id\": \"adyen:threeDOfferedResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xid\": {\n      \"@id\": \"adyen:xid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-three-ds1-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
