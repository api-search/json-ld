---
class_count: 16
classes:
- Product
- sku
- name
- description
- url
- category
- price
- amount
- currency
- formatted
- ProductImage
- images
- altText
- color
- orderId
- orderStatus
context_file: json-ld/tiffany-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tiffany/refs/heads/main/json-ld/tiffany-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tiffany from Tiffany & Co..
layout: jsonld
name: Tiffany Context
namespaces:
- prefix: tiffany
  uri: https://www.tiffany.com/ontology/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: subcategory
  type: ''
- container: ''
  name: collection
  type: ''
- container: ''
  name: availability
  type: '@vocab'
- container: ''
  name: Gemstone
  type: reference
- container: ''
  name: gemstones
  type: ''
- container: ''
  name: carats
  type: decimal
- container: ''
  name: clarity
  type: ''
- container: ''
  name: cut
  type: ''
- container: ''
  name: Metal
  type: reference
- container: ''
  name: metals
  type: ''
- container: ''
  name: karat
  type: ''
- container: ''
  name: materials
  type: ''
- container: ''
  name: sizes
  type: ''
- container: ''
  name: giftable
  type: boolean
- container: ''
  name: engravable
  type: boolean
- container: ''
  name: occasion
  type: ''
- container: ''
  name: CorporateGiftOrder
  type: reference
- container: ''
  name: orderDate
  type: date
- container: ''
  name: deliveryDate
  type: date
property_count: 19
provider_name: Tiffany & Co.
provider_slug: tiffany
slug: tiffany-context
source_filename: tiffany-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tiffany\": \"https://www.tiffany.com/ontology/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n\n    \"Product\": \"Product\",\n    \"sku\": \"sku\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"url\": \"url\",\n    \"category\": \"category\",\n    \"subcategory\": {\n      \"@id\": \"tiffany:subcategory\"\n    },\n    \"collection\": {\n      \"@id\": \"tiffany:collection\"\n    },\n\n    \"price\": \"offers\",\n    \"amount\": \"price\",\n    \"currency\": \"priceCurrency\",\n    \"formatted\": \"tiffany:formattedPrice\",\n    \"availability\": {\n      \"@id\": \"availability\",\n      \"@type\": \"@vocab\"\n    },\n\n    \"ProductImage\": \"ImageObject\",\n    \"images\": \"image\",\n    \"altText\": \"alternateName\",\n\n    \"Gemstone\": {\n      \"@id\": \"tiffany:Gemstone\",\n      \"@type\": \"@id\"\n    },\n    \"gemstones\": {\n      \"@id\": \"tiffany:gemstones\"\n  \
  \  },\n    \"carats\": {\n      \"@id\": \"tiffany:carats\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"color\": \"color\",\n    \"clarity\": {\n      \"@id\": \"tiffany:clarity\"\n    },\n    \"cut\": {\n      \"@id\": \"tiffany:cut\"\n    },\n\n    \"Metal\": {\n      \"@id\": \"tiffany:Metal\",\n      \"@type\": \"@id\"\n    },\n    \"metals\": {\n      \"@id\": \"tiffany:metals\"\n    },\n    \"karat\": {\n      \"@id\": \"tiffany:karat\"\n    },\n\n    \"materials\": {\n      \"@id\": \"tiffany:materials\"\n    },\n    \"sizes\": {\n      \"@id\": \"tiffany:sizes\"\n    },\n    \"giftable\": {\n      \"@id\": \"tiffany:giftable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"engravable\": {\n      \"@id\": \"tiffany:engravable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"occasion\": {\n      \"@id\": \"tiffany:occasion\"\n    },\n\n    \"CorporateGiftOrder\": {\n      \"@id\": \"tiffany:CorporateGiftOrder\",\n      \"@type\": \"@id\"\n    },\n    \"orderId\": \"@id\"\
  ,\n    \"orderDate\": {\n      \"@id\": \"orderDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"tiffany:deliveryDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"orderStatus\": \"orderStatus\",\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tiffany/refs/heads/main/json-ld/tiffany-context.jsonld
tags:
- Corporate Gifting
- E-Commerce
- Jewelry
- Luxury Retail
- Watches
- JSON-LD
- Linked Data
- Semantic Web
---
