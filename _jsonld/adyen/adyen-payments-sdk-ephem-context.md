---
class_count: 1
classes:
- SDKEphemPubKey
context_file: json-ld/adyen-payments-sdk-ephem-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-sdk-ephem-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Payments Sdk Ephem from Adyen.
layout: jsonld
name: Adyen Payments Sdk Ephem Context
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
  name: crv
  type: string
- container: ''
  name: kty
  type: string
- container: ''
  name: x
  type: string
- container: ''
  name: y
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-payments-sdk-ephem-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SDKEphemPubKey\": \"adyen:SDKEphemPubKey\",\n    \"crv\": {\n      \"@id\": \"adyen:crv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kty\": {\n      \"@id\": \"adyen:kty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"x\": {\n      \"@id\": \"adyen:x\",\n      \"@type\": \"xsd:string\"\n    },\n    \"y\": {\n      \"@id\": \"adyen:y\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-payments-sdk-ephem-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
