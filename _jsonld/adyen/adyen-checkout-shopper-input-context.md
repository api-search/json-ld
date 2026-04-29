---
class_count: 1
classes:
- ShopperInput
context_file: json-ld/adyen-checkout-shopper-input-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-shopper-input-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Shopper Input from Adyen.
layout: jsonld
name: Adyen Checkout Shopper Input Context
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
  name: billingAddress
  type: string
- container: ''
  name: deliveryAddress
  type: string
- container: ''
  name: personalDetails
  type: string
property_count: 3
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-shopper-input-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ShopperInput\": \"adyen:ShopperInput\",\n    \"billingAddress\": {\n      \"@id\": \"adyen:billingAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryAddress\": {\n      \"@id\": \"adyen:deliveryAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"personalDetails\": {\n      \"@id\": \"adyen:personalDetails\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-shopper-input-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
