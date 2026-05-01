---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Content API for Shopping
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-shopping/refs/heads/main/openapi/openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-shopping.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-shopping/refs/heads/main/json-ld/google-shopping.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Shopping from Google Content API for Shopping.
layout: jsonld
name: Google Shopping Context
namespaces:
- prefix: gshopping
  uri: https://developers.google.com/shopping-content/reference/rest/v2.1/
- prefix: Product
  uri: https://schema.org/Product
- prefix: Offer
  uri: https://schema.org/Offer
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: offerId
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: link
  type: reference
- container: ''
  name: imageLink
  type: reference
- container: ''
  name: price
  type: string
- container: ''
  name: priceCurrency
  type: string
- container: ''
  name: brand
  type: string
- container: ''
  name: gtin
  type: string
- container: ''
  name: availability
  type: string
- container: ''
  name: condition
  type: string
property_count: 11
provider_name: Google Content API for Shopping
provider_slug: google-shopping
slug: google-shopping
source_filename: google-shopping.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gshopping\": \"https://developers.google.com/shopping-content/reference/rest/v2.1/\",\n    \"Product\": \"https://schema.org/Product\",\n    \"Offer\": \"https://schema.org/Offer\",\n    \"offerId\": {\n      \"@id\": \"gshopping:offerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"https://schema.org/name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"https://schema.org/description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"https://schema.org/url\",\n      \"@type\": \"@id\"\n    },\n    \"imageLink\": {\n      \"@id\": \"https://schema.org/image\",\n      \"@type\": \"@id\"\n    },\n    \"price\": {\n      \"@id\": \"https://schema.org/price\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priceCurrency\": {\n      \"@id\": \"https://schema.org/priceCurrency\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"brand\": {\n      \"@id\": \"https://schema.org/brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gtin\": {\n      \"@id\": \"https://schema.org/gtin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availability\": {\n      \"@id\": \"https://schema.org/availability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"https://schema.org/itemCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-shopping/refs/heads/main/json-ld/google-shopping.jsonld
tags:
- E-Commerce
- Google Shopping
- Merchant Center
- Product Listings
- Retail
- Shopping
- JSON-LD
- Linked Data
- Semantic Web
---
