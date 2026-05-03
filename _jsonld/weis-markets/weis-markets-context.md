---
class_count: 6
classes:
- WeisMarkets
- WeisStore
- WeisProduct
- WeisRewardsProgram
- WeisVendor
- WeisPurchaseOrder
context_file: json-ld/weis-markets-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/weis-markets/refs/heads/main/json-ld/weis-markets-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Weis Markets from weis-markets.
layout: jsonld
name: Weis Markets Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: weis
  uri: https://www.weismarkets.com/vocab#
properties:
- container: ''
  name: storeId
  type: string
- container: ''
  name: storeNumber
  type: string
- container: ''
  name: storeName
  type: string
- container: ''
  name: storeAddress
  type: schema:PostalAddress
- container: ''
  name: storePhone
  type: string
- container: ''
  name: storeHours
  type: ''
- container: ''
  name: productId
  type: string
- container: ''
  name: productName
  type: string
- container: ''
  name: productBrand
  type: schema:Brand
- container: ''
  name: productCategory
  type: string
- container: ''
  name: productPrice
  type: decimal
- container: ''
  name: productUPC
  type: string
- container: ''
  name: memberId
  type: string
- container: ''
  name: memberPoints
  type: integer
- container: ''
  name: memberTier
  type: string
- container: ''
  name: vendorId
  type: string
- container: ''
  name: vendorName
  type: string
- container: ''
  name: vendorContact
  type: ''
- container: ''
  name: orderId
  type: string
- container: ''
  name: orderDate
  type: date
- container: ''
  name: orderStatus
  type: ''
- container: ''
  name: orderItems
  type: ''
- container: ''
  name: orderTotal
  type: decimal
property_count: 23
provider_name: weis-markets
provider_slug: weis-markets
slug: weis-markets-context
source_filename: weis-markets-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"weis\": \"https://www.weismarkets.com/vocab#\",\n\n    \"WeisMarkets\": \"schema:Organization\",\n    \"WeisStore\": \"schema:GroceryStore\",\n    \"WeisProduct\": \"schema:Product\",\n    \"WeisRewardsProgram\": \"schema:LoyaltyProgram\",\n    \"WeisVendor\": \"schema:Organization\",\n    \"WeisPurchaseOrder\": \"schema:Order\",\n\n    \"storeId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"storeNumber\": { \"@id\": \"weis:storeNumber\", \"@type\": \"xsd:string\" },\n    \"storeName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"storeAddress\": { \"@id\": \"schema:address\", \"@type\": \"schema:PostalAddress\" },\n    \"storePhone\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"storeHours\": { \"@id\": \"schema:openingHoursSpecification\" },\n\n    \"productId\"\
  : { \"@id\": \"schema:productID\", \"@type\": \"xsd:string\" },\n    \"productName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"productBrand\": { \"@id\": \"schema:brand\", \"@type\": \"schema:Brand\" },\n    \"productCategory\": { \"@id\": \"schema:category\", \"@type\": \"xsd:string\" },\n    \"productPrice\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"productUPC\": { \"@id\": \"schema:gtin12\", \"@type\": \"xsd:string\" },\n\n    \"memberId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"memberPoints\": { \"@id\": \"weis:rewardPoints\", \"@type\": \"xsd:integer\" },\n    \"memberTier\": { \"@id\": \"weis:memberTier\", \"@type\": \"xsd:string\" },\n\n    \"vendorId\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"vendorName\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"vendorContact\": { \"@id\": \"schema:contactPoint\" },\n\n    \"orderId\": { \"@id\": \"schema:orderNumber\"\
  , \"@type\": \"xsd:string\" },\n    \"orderDate\": { \"@id\": \"schema:orderDate\", \"@type\": \"xsd:date\" },\n    \"orderStatus\": { \"@id\": \"schema:orderStatus\" },\n    \"orderItems\": { \"@id\": \"schema:orderedItem\" },\n    \"orderTotal\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/weis-markets/refs/heads/main/json-ld/weis-markets-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
