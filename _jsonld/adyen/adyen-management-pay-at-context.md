---
class_count: 1
classes:
- PayAtTable
context_file: json-ld/adyen-management-pay-at-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-pay-at-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Pay At from Adyen.
layout: jsonld
name: Adyen Management Pay At Context
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
  name: authenticationMethod
  type: string
- container: ''
  name: enablePayAtTable
  type: boolean
- container: ''
  name: paymentInstrument
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-pay-at-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PayAtTable\": \"adyen:PayAtTable\",\n    \"authenticationMethod\": {\n      \"@id\": \"adyen:authenticationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enablePayAtTable\": {\n      \"@id\": \"adyen:enablePayAtTable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"paymentInstrument\": {\n      \"@id\": \"adyen:paymentInstrument\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-pay-at-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
