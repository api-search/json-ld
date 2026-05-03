---
api_specs:
- filename: starbucks-starbucks-api-openapi.yml
  format: yaml
  label: Starbucks API
  slug: starbucks-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/starbucks/refs/heads/main/openapi/starbucks-starbucks-api-openapi.yml
class_count: 32
classes:
- MenuItem
- Store
- LoyaltyAccount
- Order
- id
- name
- description
- imageUrl
- available
- categoryId
- address
- coordinates
- latitude
- longitude
- phone
- timezone
- hours
- amenities
- services
- mobileOrderingEnabled
- driveThru
- starBalance
- tier
- memberSince
- status
- storeId
- items
- subtotal
- total
- estimatedReadyAt
- loyaltyAccountId
- starsEarned
context_file: json-ld/starbucks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/starbucks/refs/heads/main/json-ld/starbucks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Starbucks from Starbucks.
layout: jsonld
name: Starbucks Context
namespaces:
- prefix: starbucks
  uri: https://api.starbucks.com/vocab#
properties:
- container: ''
  name: price
  type: Offer
- container: ''
  name: calories
  type: Integer
- container: list
  name: allergens
  type: ''
- container: list
  name: sizes
  type: ''
- container: list
  name: customizations
  type: ''
property_count: 5
provider_name: Starbucks
provider_slug: starbucks
slug: starbucks-context
source_filename: starbucks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"starbucks\": \"https://api.starbucks.com/vocab#\",\n    \"MenuItem\": \"FoodEstablishmentReservation\",\n    \"Store\": \"CafeOrCoffeeShop\",\n    \"LoyaltyAccount\": \"starbucks:LoyaltyAccount\",\n    \"Order\": \"Order\",\n    \"id\": \"@id\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"price\": {\n      \"@id\": \"offers\",\n      \"@type\": \"Offer\"\n    },\n    \"imageUrl\": \"image\",\n    \"available\": \"availability\",\n    \"calories\": {\n      \"@id\": \"starbucks:calories\",\n      \"@type\": \"Integer\"\n    },\n    \"allergens\": {\n      \"@id\": \"starbucks:allergens\",\n      \"@container\": \"@list\"\n    },\n    \"sizes\": {\n      \"@id\": \"starbucks:sizes\",\n      \"@container\": \"@list\"\n    },\n    \"customizations\": {\n      \"@id\": \"starbucks:customizations\",\n      \"@container\": \"@list\"\n    },\n    \"categoryId\": \"starbucks:category\",\n\
  \    \"address\": \"address\",\n    \"coordinates\": \"geo\",\n    \"latitude\": \"latitude\",\n    \"longitude\": \"longitude\",\n    \"phone\": \"telephone\",\n    \"timezone\": \"starbucks:timezone\",\n    \"hours\": \"openingHoursSpecification\",\n    \"amenities\": \"amenityFeature\",\n    \"services\": \"starbucks:services\",\n    \"mobileOrderingEnabled\": \"starbucks:mobileOrdering\",\n    \"driveThru\": \"starbucks:driveThru\",\n    \"starBalance\": \"starbucks:starBalance\",\n    \"tier\": \"starbucks:rewardsTier\",\n    \"memberSince\": \"startDate\",\n    \"status\": \"starbucks:accountStatus\",\n    \"storeId\": \"starbucks:storeReference\",\n    \"items\": \"orderedItem\",\n    \"subtotal\": \"price\",\n    \"total\": \"totalPrice\",\n    \"estimatedReadyAt\": \"starbucks:estimatedReadyAt\",\n    \"loyaltyAccountId\": \"starbucks:loyaltyAccount\",\n    \"starsEarned\": \"starbucks:starsEarned\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/starbucks/refs/heads/main/json-ld/starbucks-context.jsonld
tags:
- Coffee
- Food Service
- Loyalty
- Ordering
- Retail
- JSON-LD
- Linked Data
- Semantic Web
---
