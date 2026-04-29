---
class_count: 1
classes:
- Configuration
context_file: json-ld/adyen-checkout-configuration-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-configuration-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Configuration from Adyen.
layout: jsonld
name: Adyen Checkout Configuration Context
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
  name: avs
  type: string
- container: ''
  name: cardHolderName
  type: string
- container: ''
  name: installments
  type: string
- container: ''
  name: shopperInput
  type: string
property_count: 4
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-configuration-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Configuration\": \"adyen:Configuration\",\n    \"avs\": {\n      \"@id\": \"adyen:avs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardHolderName\": {\n      \"@id\": \"adyen:cardHolderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"installments\": {\n      \"@id\": \"adyen:installments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shopperInput\": {\n      \"@id\": \"adyen:shopperInput\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-configuration-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
