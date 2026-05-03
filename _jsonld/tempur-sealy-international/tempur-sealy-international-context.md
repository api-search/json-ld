---
class_count: 6
classes:
- name
- description
- url
- Product
- Tags
- Documentation
context_file: json-ld/tempur-sealy-international-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tempur-sealy-international/refs/heads/main/json-ld/tempur-sealy-international-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tempur Sealy International from Tempur Sealy International.
layout: jsonld
name: Tempur Sealy International Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: tsi
  uri: https://api-evangelist.com/topics/tempur-sealy-international/
properties:
- container: ''
  name: Mattress
  type: schema:Product
- container: ''
  name: productId
  type: schema:Text
- container: ''
  name: brand
  type: schema:Brand
- container: ''
  name: category
  type: schema:Text
- container: ''
  name: firmness
  type: schema:Text
- container: ''
  name: size
  type: schema:Text
- container: ''
  name: price
  type: schema:Offer
- container: ''
  name: msrp
  type: schema:Number
- container: ''
  name: availability
  type: schema:ItemAvailability
- container: ''
  name: materials
  type: schema:Text
- container: ''
  name: warranty
  type: schema:WarrantyPromise
- container: ''
  name: certifications
  type: schema:Text
property_count: 12
provider_name: Tempur Sealy International
provider_slug: tempur-sealy-international
slug: tempur-sealy-international-context
source_filename: tempur-sealy-international-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"tsi\": \"https://api-evangelist.com/topics/tempur-sealy-international/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"Product\": \"schema:Product\",\n    \"Mattress\": {\n      \"@id\": \"tsi:Mattress\",\n      \"@type\": \"schema:Product\"\n    },\n    \"productId\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"schema:Text\"\n    },\n    \"brand\": {\n      \"@id\": \"schema:brand\",\n      \"@type\": \"schema:Brand\"\n    },\n    \"category\": {\n      \"@id\": \"schema:category\",\n      \"@type\": \"schema:Text\"\n    },\n    \"firmness\": {\n      \"@id\": \"tsi:firmness\",\n      \"@type\": \"schema:Text\"\n    },\n    \"size\": {\n      \"@id\": \"tsi:mattressSize\",\n      \"@type\": \"schema:Text\"\n    },\n    \"price\": {\n      \"@id\": \"schema:offers\"\
  ,\n      \"@type\": \"schema:Offer\"\n    },\n    \"msrp\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"availability\": {\n      \"@id\": \"schema:availability\",\n      \"@type\": \"schema:ItemAvailability\"\n    },\n    \"materials\": {\n      \"@id\": \"schema:material\",\n      \"@type\": \"schema:Text\"\n    },\n    \"warranty\": {\n      \"@id\": \"schema:warranty\",\n      \"@type\": \"schema:WarrantyPromise\"\n    },\n    \"certifications\": {\n      \"@id\": \"tsi:certification\",\n      \"@type\": \"schema:Text\"\n    },\n    \"Tags\": \"schema:keywords\",\n    \"Documentation\": \"schema:documentation\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tempur-sealy-international/refs/heads/main/json-ld/tempur-sealy-international-context.jsonld
tags:
- Bedding
- Manufacturing
- E-Commerce
- Retail
- Fortune 500
- Consumer Goods
- JSON-LD
- Linked Data
- Semantic Web
---
