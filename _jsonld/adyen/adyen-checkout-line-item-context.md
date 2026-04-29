---
class_count: 2
classes:
- LineItem
- description
context_file: json-ld/adyen-checkout-line-item-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-line-item-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Checkout Line Item from Adyen.
layout: jsonld
name: Adyen Checkout Line Item Context
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
  name: amountExcludingTax
  type: integer
- container: ''
  name: amountIncludingTax
  type: integer
- container: ''
  name: brand
  type: string
- container: ''
  name: color
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: imageUrl
  type: string
- container: ''
  name: itemCategory
  type: string
- container: ''
  name: manufacturer
  type: string
- container: ''
  name: productUrl
  type: string
- container: ''
  name: quantity
  type: integer
- container: ''
  name: receiverEmail
  type: string
- container: ''
  name: size
  type: string
- container: ''
  name: sku
  type: string
- container: ''
  name: taxAmount
  type: integer
- container: ''
  name: taxPercentage
  type: integer
- container: ''
  name: upc
  type: string
property_count: 16
provider_name: Adyen
provider_slug: adyen
slug: adyen-checkout-line-item-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LineItem\": \"adyen:LineItem\",\n    \"amountExcludingTax\": {\n      \"@id\": \"adyen:amountExcludingTax\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"amountIncludingTax\": {\n      \"@id\": \"adyen:amountIncludingTax\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"brand\": {\n      \"@id\": \"adyen:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"color\": {\n      \"@id\": \"adyen:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adyen:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageUrl\": {\n      \"@id\": \"adyen:imageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemCategory\": {\n      \"@id\": \"adyen:itemCategory\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"adyen:manufacturer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"productUrl\": {\n      \"@id\": \"adyen:productUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quantity\": {\n      \"@id\": \"adyen:quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"receiverEmail\": {\n      \"@id\": \"adyen:receiverEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"adyen:size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sku\": {\n      \"@id\": \"adyen:sku\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taxAmount\": {\n      \"@id\": \"adyen:taxAmount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"taxPercentage\": {\n      \"@id\": \"adyen:taxPercentage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"upc\": {\n      \"@id\": \"adyen:upc\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-checkout-line-item-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
