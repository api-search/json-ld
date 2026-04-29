---
class_count: 1
classes:
- Repayment
context_file: json-ld/adyen-transfers-repayment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-repayment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Transfers Repayment from Adyen.
layout: jsonld
name: Adyen Transfers Repayment Context
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
  name: basisPoints
  type: integer
- container: ''
  name: term
  type: string
- container: ''
  name: threshold
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-transfers-repayment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Repayment\": \"adyen:Repayment\",\n    \"basisPoints\": {\n      \"@id\": \"adyen:basisPoints\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"term\": {\n      \"@id\": \"adyen:term\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threshold\": {\n      \"@id\": \"adyen:threshold\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-transfers-repayment-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
