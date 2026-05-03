---
class_count: 0
classes: []
context_file: json-ld/sally-beauty-holdings-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sally-beauty-holdings/refs/heads/main/json-ld/sally-beauty-holdings-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sally Beauty Holdings from Sally Beauty Holdings.
layout: jsonld
name: Sally Beauty Holdings Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sbh
  uri: https://api-evangelist.github.io/sally-beauty-holdings/vocab#
properties:
- container: ''
  name: Product
  type: ''
- container: ''
  name: Store
  type: ''
- container: ''
  name: Order
  type: ''
- container: ''
  name: SallyBeautySupply
  type: ''
- container: ''
  name: BeautySystemsGroup
  type: ''
property_count: 5
provider_name: Sally Beauty Holdings
provider_slug: sally-beauty-holdings
slug: sally-beauty-holdings-context
source_filename: sally-beauty-holdings-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sbh\": \"https://api-evangelist.github.io/sally-beauty-holdings/vocab#\",\n\n    \"Product\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"id\": \"schema:sku\",\n        \"name\": \"schema:name\",\n        \"brand\": \"schema:brand\",\n        \"description\": \"schema:description\",\n        \"category\": \"schema:category\",\n        \"subcategory\": \"schema:category\",\n        \"price\": \"schema:price\",\n        \"professional_price\": \"sbh:professionalPrice\",\n        \"currency\": \"schema:priceCurrency\",\n        \"upc\": {\n          \"@id\": \"schema:gtin12\",\n          \"@type\": \"xsd:string\"\n        },\n        \"images\": \"schema:image\",\n        \"available_online\": \"schema:availableDeliveryMethod\",\n        \"available_in_store\":\
  \ \"schema:availableAtOrFrom\",\n        \"professional_only\": \"sbh:professionalOnly\",\n        \"channel\": \"sbh:salesChannel\"\n      }\n    },\n\n    \"Store\": {\n      \"@id\": \"schema:Store\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"address\": \"schema:address\",\n        \"phone\": \"schema:telephone\",\n        \"hours\": \"schema:openingHours\",\n        \"channel\": \"sbh:storeChannel\"\n      }\n    },\n\n    \"Order\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"orderNumber\": \"schema:orderNumber\",\n        \"customer\": \"schema:customer\",\n        \"items\": \"schema:orderedItem\",\n        \"total\": \"schema:price\",\n        \"status\": \"schema:orderStatus\",\n        \"created_at\": {\n          \"@id\": \"schema:orderDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SallyBeautySupply\": {\n      \"@id\": \"schema:Organization\"\
  ,\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"type\": \"schema:additionalType\",\n        \"description\": \"schema:description\"\n      }\n    },\n\n    \"BeautySystemsGroup\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"description\": \"schema:description\",\n        \"professionalOnly\": \"sbh:professionalOnly\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sally-beauty-holdings/refs/heads/main/json-ld/sally-beauty-holdings-context.jsonld
tags:
- Beauty
- Retail
- Ecommerce
- Professional
- Consumer
- JSON-LD
- Linked Data
- Semantic Web
---
