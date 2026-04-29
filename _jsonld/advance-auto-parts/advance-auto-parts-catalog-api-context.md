---
class_count: 34
classes:
- YearList
- years
- Make
- MakeList
- makes
- id
- name
- VehicleModel
- ModelList
- models
- Product
- partNumber
- brand
- description
- available
- categoryId
- ProductList
- products
- total
- StoreInventory
- storeId
- storeName
- quantity
- InventoryResult
- stores
- Store
- address
- phone
- hours
- distance
- StoreList
- ErrorResponse
- code
- message
context_file: json-ld/advance-auto-parts-catalog-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/json-ld/advance-auto-parts-catalog-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Advance Auto Parts Catalog Api from Advance Auto Parts.
layout: jsonld
name: Advance Auto Parts Catalog Api Context
namespaces:
- prefix: aap
  uri: https://api.advanceautoparts.com/v1/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: price
  type: decimal
property_count: 1
provider_name: Advance Auto Parts
provider_slug: advance-auto-parts
slug: advance-auto-parts-catalog-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aap\": \"https://api.advanceautoparts.com/v1/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"YearList\": \"aap:YearList\",\n    \"years\": \"aap:years\",\n    \"Make\": \"aap:Make\",\n    \"MakeList\": \"aap:MakeList\",\n    \"makes\": \"aap:makes\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"VehicleModel\": \"aap:VehicleModel\",\n    \"ModelList\": \"aap:ModelList\",\n    \"models\": \"aap:models\",\n    \"Product\": \"aap:Product\",\n    \"partNumber\": \"aap:partNumber\",\n    \"brand\": \"schema:brand\",\n    \"description\": \"schema:description\",\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"available\": \"schema:availability\",\n    \"categoryId\": \"aap:categoryId\",\n    \"ProductList\": \"aap:ProductList\",\n    \"products\": \"aap:products\",\n    \"total\": \"aap:total\",\n \
  \   \"StoreInventory\": \"aap:StoreInventory\",\n    \"storeId\": \"aap:storeId\",\n    \"storeName\": \"aap:storeName\",\n    \"quantity\": \"aap:quantity\",\n    \"InventoryResult\": \"aap:InventoryResult\",\n    \"stores\": \"aap:stores\",\n    \"Store\": \"schema:AutoPartsStore\",\n    \"address\": \"schema:address\",\n    \"phone\": \"schema:telephone\",\n    \"hours\": \"schema:openingHours\",\n    \"distance\": \"aap:distance\",\n    \"StoreList\": \"aap:StoreList\",\n    \"ErrorResponse\": \"aap:ErrorResponse\",\n    \"code\": \"aap:errorCode\",\n    \"message\": \"schema:description\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/advance-auto-parts/refs/heads/main/json-ld/advance-auto-parts-catalog-api-context.jsonld
tags:
- Automotive
- E-Commerce
- Parts Catalog
- Retail
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
