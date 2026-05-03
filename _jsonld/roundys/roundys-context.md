---
api_specs:
- filename: Kroger-API-Spec-23c0b0b34f55c3d32d60fcb23de33a86.yaml
  format: yaml
  label: Kroger Product Catalog API
  slug: kroger-product-catalog-api
  spec_type: OpenAPI
  url: https://developer.kroger.com/assets/files/Kroger-API-Spec-23c0b0b34f55c3d32d60fcb23de33a86.yaml
class_count: 0
classes: []
context_file: json-ld/roundys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roundys/refs/heads/main/json-ld/roundys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roundys from Roundy's.
layout: jsonld
name: Roundys Context
namespaces:
- prefix: roundys
  uri: https://www.roundys.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Roundys
  type: schema:Organization
- container: ''
  name: GroceryStore
  type: ''
- container: ''
  name: GroceryProduct
  type: ''
- container: ''
  name: LoyaltyProgram
  type: ''
- container: ''
  name: ShoppingCart
  type: ''
property_count: 5
provider_name: Roundy's
provider_slug: roundys
slug: roundys-context
source_filename: roundys-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roundys\": \"https://www.roundys.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Roundys\": {\n      \"@id\": \"roundys:Roundys\",\n      \"@type\": \"schema:Organization\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"parentOrganization\": { \"@id\": \"schema:parentOrganization\" },\n        \"foundingDate\": { \"@id\": \"schema:foundingDate\" },\n        \"location\": { \"@id\": \"schema:location\" },\n        \"numberOfLocations\": { \"@id\": \"roundys:numberOfLocations\" }\n      }\n    },\n\n    \"GroceryStore\": {\n      \"@id\": \"schema:GroceryOrSupermarket\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"banner\": { \"@id\": \"roundys:banner\" },\n        \"storeNumber\"\
  : { \"@id\": \"roundys:storeNumber\" },\n        \"address\": { \"@id\": \"schema:address\" },\n        \"geo\": { \"@id\": \"schema:geo\" },\n        \"openingHours\": { \"@id\": \"schema:openingHours\" },\n        \"telephone\": { \"@id\": \"schema:telephone\" },\n        \"departments\": { \"@id\": \"roundys:departments\" },\n        \"services\": { \"@id\": \"schema:availableService\" }\n      }\n    },\n\n    \"GroceryProduct\": {\n      \"@id\": \"schema:Product\",\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"description\": { \"@id\": \"schema:description\" },\n        \"brand\": { \"@id\": \"schema:brand\" },\n        \"upc\": { \"@id\": \"gs1:gtin\" },\n        \"category\": { \"@id\": \"schema:category\" },\n        \"price\": { \"@id\": \"schema:price\" },\n        \"priceCurrency\": { \"@id\": \"schema:priceCurrency\" },\n        \"image\": { \"@id\": \"schema:image\" }\n      }\n    },\n\n    \"LoyaltyProgram\": {\n      \"@id\": \"schema:LoyaltyProgram\"\
  ,\n      \"@context\": {\n        \"name\": { \"@id\": \"schema:name\" },\n        \"memberOf\": { \"@id\": \"schema:memberOf\" },\n        \"cardNumber\": { \"@id\": \"roundys:cardNumber\" },\n        \"points\": { \"@id\": \"roundys:loyaltyPoints\" },\n        \"fuelPoints\": { \"@id\": \"roundys:fuelPoints\" }\n      }\n    },\n\n    \"ShoppingCart\": {\n      \"@id\": \"schema:Cart\",\n      \"@context\": {\n        \"items\": { \"@id\": \"schema:itemListElement\" },\n        \"totalPrice\": { \"@id\": \"schema:totalPrice\" },\n        \"storeId\": { \"@id\": \"roundys:storeId\" }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roundys/refs/heads/main/json-ld/roundys-context.jsonld
tags:
- Grocery
- Kroger
- Midwest
- Retail
- Supermarket
- Wisconsin
- JSON-LD
- Linked Data
- Semantic Web
---
