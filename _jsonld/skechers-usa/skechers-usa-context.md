---
class_count: 41
classes:
- Product
- Order
- Customer
- LoyaltyAccount
- Store
- id
- name
- description
- styleNumber
- category
- collection
- technology
- gender
- colors
- sizes
- pricing
- regularPrice
- salePrice
- currency
- images
- rating
- url
- features
- materials
- orderId
- status
- shippingAddress
- trackingNumber
- totalAmount
- customerId
- email
- firstName
- lastName
- loyaltyAccount
- points
- tier
- storeId
- storeType
- phone
- hours
- coordinates
context_file: json-ld/skechers-usa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/skechers-usa/refs/heads/main/json-ld/skechers-usa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Skechers Usa from Skechers U.S.A..
layout: jsonld
name: Skechers Usa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: skechers
  uri: https://www.skechers.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: orderDate
  type: dateTime
property_count: 1
provider_name: Skechers U.S.A.
provider_slug: skechers-usa
slug: skechers-usa-context
source_filename: skechers-usa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"skechers\": \"https://www.skechers.com/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"Order\": \"schema:Order\",\n    \"Customer\": \"schema:Person\",\n    \"LoyaltyAccount\": \"schema:LoyaltyProgram\",\n    \"Store\": \"schema:LocalBusiness\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"styleNumber\": \"skechers:styleNumber\",\n    \"category\": \"schema:category\",\n    \"collection\": \"skechers:collection\",\n    \"technology\": \"skechers:technology\",\n    \"gender\": \"schema:audience\",\n    \"colors\": \"schema:color\",\n    \"sizes\": \"schema:size\",\n    \"pricing\": \"schema:offers\",\n    \"regularPrice\": \"schema:price\",\n    \"salePrice\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"images\": \"schema:image\",\n    \"\
  rating\": \"schema:aggregateRating\",\n    \"url\": \"schema:url\",\n    \"features\": \"schema:description\",\n    \"materials\": \"schema:material\",\n\n    \"orderId\": \"schema:orderNumber\",\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:orderStatus\",\n    \"shippingAddress\": \"schema:deliveryAddress\",\n    \"trackingNumber\": \"skechers:trackingNumber\",\n    \"totalAmount\": \"schema:totalPrice\",\n\n    \"customerId\": \"schema:identifier\",\n    \"email\": \"schema:email\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"loyaltyAccount\": \"skechers:loyaltyAccount\",\n    \"points\": \"skechers:loyaltyPoints\",\n    \"tier\": \"skechers:membershipTier\",\n\n    \"storeId\": \"schema:identifier\",\n    \"storeType\": \"schema:additionalType\",\n    \"phone\": \"schema:telephone\",\n    \"hours\": \"schema:openingHoursSpecification\",\n    \"coordinates\"\
  : \"schema:geo\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/skechers-usa/refs/heads/main/json-ld/skechers-usa-context.jsonld
tags:
- Footwear
- Retail
- E-Commerce
- Fortune 500
- Direct-to-Consumer
- Lifestyle
- JSON-LD
- Linked Data
- Semantic Web
---
