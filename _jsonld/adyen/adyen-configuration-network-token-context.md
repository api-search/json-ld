---
class_count: 1
classes:
- NetworkToken
context_file: json-ld/adyen-configuration-network-token-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-network-token-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Configuration Network Token from Adyen.
layout: jsonld
name: Adyen Configuration Network Token Context
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
  name: brandVariant
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: device
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: paymentInstrumentId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tokenLastFour
  type: string
- container: ''
  name: type
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-configuration-network-token-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"NetworkToken\": \"adyen:NetworkToken\",\n    \"brandVariant\": {\n      \"@id\": \"adyen:brandVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"adyen:creationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"device\": {\n      \"@id\": \"adyen:device\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentInstrumentId\": {\n      \"@id\": \"adyen:paymentInstrumentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenLastFour\": {\n      \"@id\": \"adyen:tokenLastFour\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-configuration-network-token-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
