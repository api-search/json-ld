---
class_count: 2
classes:
- CheckoutDelegatedAuthenticationAction
- url
context_file: json-ld/adyen-checkout-checkout-delegated-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-delegated-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Checkout Delegated from Adyen.
layout: jsonld
name: Adyen Checkout Checkout Delegated Context
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
  name: authorisationToken
  type: string
- container: ''
  name: paymentData
  type: string
- container: ''
  name: paymentMethodType
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: type
  type: string
property_count: 5
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-checkout-delegated-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CheckoutDelegatedAuthenticationAction\": \"adyen:CheckoutDelegatedAuthenticationAction\",\n    \"authorisationToken\": {\n      \"@id\": \"adyen:authorisationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentData\": {\n      \"@id\": \"adyen:paymentData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paymentMethodType\": {\n      \"@id\": \"adyen:paymentMethodType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"adyen:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"adyen:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-checkout-delegated-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
