---
class_count: 1
classes:
- Avs
context_file: json-ld/adyen-checkout-avs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-avs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Avs from Adyen.
layout: jsonld
name: Adyen Checkout Avs Context
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
  name: addressEditable
  type: boolean
- container: ''
  name: enabled
  type: string
property_count: 2
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-avs-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Avs\": \"adyen:Avs\",\n    \"addressEditable\": {\n      \"@id\": \"adyen:addressEditable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enabled\": {\n      \"@id\": \"adyen:enabled\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-avs-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
