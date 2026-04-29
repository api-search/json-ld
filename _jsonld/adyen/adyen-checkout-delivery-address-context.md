---
class_count: 1
classes:
- DeliveryAddress
context_file: json-ld/adyen-checkout-delivery-address-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-delivery-address-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Delivery Address from Adyen.
layout: jsonld
name: Adyen Checkout Delivery Address Context
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
  name: city
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: houseNumberOrName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: stateOrProvince
  type: string
- container: ''
  name: street
  type: string
property_count: 8
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-delivery-address-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeliveryAddress\": \"adyen:DeliveryAddress\",\n    \"city\": {\n      \"@id\": \"adyen:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"adyen:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"adyen:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"houseNumberOrName\": {\n      \"@id\": \"adyen:houseNumberOrName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"adyen:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"adyen:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateOrProvince\": {\n      \"@id\": \"adyen:stateOrProvince\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"street\": {\n      \"@id\": \"adyen:street\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-delivery-address-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
