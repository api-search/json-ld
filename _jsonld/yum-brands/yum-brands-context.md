---
class_count: 12
classes:
- Restaurant
- Brand
- FranchiseLocation
- MenuItem
- MenuSection
- Menu
- LoyaltyProgram
- LoyaltyPoints
- DigitalOrder
- OrderItem
- DeliveryAddress
- Payment
context_file: json-ld/yum-brands-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/yum-brands/refs/heads/main/json-ld/yum-brands-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Yum Brands from Yum Brands.
layout: jsonld
name: Yum Brands Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: yum
  uri: https://www.yum.com/vocab/
properties:
- container: ''
  name: YumBrands
  type: reference
- container: ''
  name: bytePlatform
  type: reference
- container: ''
  name: digitalTransaction
  type: ''
- container: ''
  name: loyaltyPoints
  type: ''
- container: ''
  name: franchiseId
  type: ''
- container: ''
  name: restaurantBrand
  type: ''
- container: ''
  name: kitchenDisplaySystem
  type: reference
- container: ''
  name: menuItemPrice
  type: ''
- container: ''
  name: menuItemName
  type: ''
- container: ''
  name: menuItemDescription
  type: ''
- container: ''
  name: calories
  type: ''
- container: ''
  name: restaurantAddress
  type: schema:PostalAddress
- container: ''
  name: restaurantHours
  type: schema:OpeningHoursSpecification
- container: ''
  name: orderStatus
  type: ''
- container: ''
  name: estimatedDeliveryTime
  type: ''
- container: ''
  name: country
  type: ''
- container: ''
  name: postalCode
  type: ''
- container: ''
  name: latitude
  type: ''
- container: ''
  name: longitude
  type: ''
property_count: 19
provider_name: Yum Brands
provider_slug: yum-brands
slug: yum-brands-context
source_filename: yum-brands-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"yum\": \"https://www.yum.com/vocab/\",\n\n    \"YumBrands\": {\n      \"@id\": \"schema:FoodEstablishmentReservation\",\n      \"@type\": \"@id\"\n    },\n    \"Restaurant\": \"schema:FoodEstablishment\",\n    \"Brand\": \"schema:Brand\",\n    \"FranchiseLocation\": \"schema:LocalBusiness\",\n    \"MenuItem\": \"schema:MenuItem\",\n    \"MenuSection\": \"schema:MenuSection\",\n    \"Menu\": \"schema:Menu\",\n    \"LoyaltyProgram\": \"schema:ProgramMembership\",\n    \"LoyaltyPoints\": \"schema:MonetaryAmount\",\n    \"DigitalOrder\": \"schema:Order\",\n    \"OrderItem\": \"schema:OrderItem\",\n    \"DeliveryAddress\": \"schema:PostalAddress\",\n    \"Payment\": \"schema:PaymentMethod\",\n\n    \"bytePlatform\": {\n      \"@id\": \"yum:bytePlatform\",\n      \"@type\": \"@id\"\n    },\n    \"digitalTransaction\": {\n      \"@id\": \"yum:digitalTransaction\"\n    },\n    \"loyaltyPoints\"\
  : {\n      \"@id\": \"yum:loyaltyPoints\"\n    },\n    \"franchiseId\": {\n      \"@id\": \"yum:franchiseId\"\n    },\n    \"restaurantBrand\": {\n      \"@id\": \"yum:restaurantBrand\"\n    },\n    \"kitchenDisplaySystem\": {\n      \"@id\": \"yum:kitchenDisplaySystem\",\n      \"@type\": \"@id\"\n    },\n    \"menuItemPrice\": {\n      \"@id\": \"schema:price\"\n    },\n    \"menuItemName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"menuItemDescription\": {\n      \"@id\": \"schema:description\"\n    },\n    \"calories\": {\n      \"@id\": \"schema:calories\"\n    },\n    \"restaurantAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"restaurantHours\": {\n      \"@id\": \"schema:openingHoursSpecification\",\n      \"@type\": \"schema:OpeningHoursSpecification\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\"\n    },\n    \"estimatedDeliveryTime\": {\n      \"@id\": \"schema:expectedArrivalFrom\"\n \
  \   },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"postalCode\": {\n      \"@id\": \"schema:postalCode\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/yum-brands/refs/heads/main/json-ld/yum-brands-context.jsonld
tags:
- Restaurants
- Fast Food
- Quick Service Restaurant
- Digital Ordering
- Loyalty
- Food Technology
- JSON-LD
- Linked Data
- Semantic Web
---
