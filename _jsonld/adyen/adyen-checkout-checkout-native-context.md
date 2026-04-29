---
class_count: 2
classes:
- CheckoutNativeRedirectAction
- url
context_file: json-ld/adyen-checkout-checkout-native-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-native-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Checkout Native from Adyen.
layout: jsonld
name: Adyen Checkout Checkout Native Context
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
  name: data
  type: reference
- container: ''
  name: method
  type: string
- container: ''
  name: nativeRedirectData
  type: string
- container: ''
  name: paymentMethodType
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-checkout-native-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckoutNativeRedirectAction\": \"adyen:CheckoutNativeRedirectAction\",\n    \"data\": {\n      \"@id\": \"adyen:data\",\n      \"@type\": \"@id\"\n    },\n    \"method\": {\n      \"@id\": \"adyen:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nativeRedirectData\": {\n      \"@id\": \"adyen:nativeRedirectData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodType\": {\n      \"@id\": \"adyen:paymentMethodType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-native-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
