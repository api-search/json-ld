---
class_count: 10
classes:
- Restaurant
- Brand
- MenuItem
- MenuSection
- Menu
- LoyaltyProgram
- LoyaltyMember
- DigitalOrder
- OrderItem
- DeliveryAddress
context_file: json-ld/yum-china-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/yum-china/refs/heads/main/json-ld/yum-china-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Yum China from Yum China.
layout: jsonld
name: Yum China Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: yumc
  uri: https://www.yumchina.com/vocab/
properties:
- container: ''
  name: YumChina
  type: reference
- container: ''
  name: superApp
  type: reference
- container: ''
  name: superBrain
  type: reference
- container: ''
  name: membershipCount
  type: ''
- container: ''
  name: loyaltyPoints
  type: ''
- container: ''
  name: digitalSalesPercentage
  type: ''
- container: ''
  name: aiOrderingAssistant
  type: reference
- container: ''
  name: restaurantCount
  type: ''
- container: ''
  name: brandName
  type: ''
- container: ''
  name: menuItemName
  type: ''
- container: ''
  name: menuItemDescription
  type: ''
- container: ''
  name: menuItemPrice
  type: ''
- container: ''
  name: calories
  type: ''
- container: ''
  name: restaurantAddress
  type: schema:PostalAddress
- container: ''
  name: restaurantHours
  type: ''
- container: ''
  name: orderStatus
  type: ''
- container: ''
  name: estimatedDeliveryTime
  type: ''
- container: ''
  name: city
  type: ''
- container: ''
  name: province
  type: ''
- container: ''
  name: latitude
  type: ''
- container: ''
  name: longitude
  type: ''
property_count: 21
provider_name: Yum China
provider_slug: yum-china
slug: yum-china-context
source_filename: yum-china-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"yumc\": \"https://www.yumchina.com/vocab/\",\n\n    \"YumChina\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\"\n    },\n    \"Restaurant\": \"schema:FoodEstablishment\",\n    \"Brand\": \"schema:Brand\",\n    \"MenuItem\": \"schema:MenuItem\",\n    \"MenuSection\": \"schema:MenuSection\",\n    \"Menu\": \"schema:Menu\",\n    \"LoyaltyProgram\": \"schema:ProgramMembership\",\n    \"LoyaltyMember\": \"schema:Person\",\n    \"DigitalOrder\": \"schema:Order\",\n    \"OrderItem\": \"schema:OrderItem\",\n    \"DeliveryAddress\": \"schema:PostalAddress\",\n\n    \"superApp\": {\n      \"@id\": \"yumc:superApp\",\n      \"@type\": \"@id\"\n    },\n    \"superBrain\": {\n      \"@id\": \"yumc:superBrain\",\n      \"@type\": \"@id\"\n    },\n    \"membershipCount\": {\n      \"@id\": \"yumc:membershipCount\"\n    },\n    \"loyaltyPoints\": {\n      \"@id\": \"yumc:loyaltyPoints\"\
  \n    },\n    \"digitalSalesPercentage\": {\n      \"@id\": \"yumc:digitalSalesPercentage\"\n    },\n    \"aiOrderingAssistant\": {\n      \"@id\": \"yumc:aiOrderingAssistant\",\n      \"@type\": \"@id\"\n    },\n    \"restaurantCount\": {\n      \"@id\": \"yumc:restaurantCount\"\n    },\n    \"brandName\": {\n      \"@id\": \"schema:brand\"\n    },\n    \"menuItemName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"menuItemDescription\": {\n      \"@id\": \"schema:description\"\n    },\n    \"menuItemPrice\": {\n      \"@id\": \"schema:price\"\n    },\n    \"calories\": {\n      \"@id\": \"schema:calories\"\n    },\n    \"restaurantAddress\": {\n      \"@id\": \"schema:address\",\n      \"@type\": \"schema:PostalAddress\"\n    },\n    \"restaurantHours\": {\n      \"@id\": \"schema:openingHoursSpecification\"\n    },\n    \"orderStatus\": {\n      \"@id\": \"schema:orderStatus\"\n    },\n    \"estimatedDeliveryTime\": {\n      \"@id\": \"schema:expectedArrivalFrom\"\n    },\n    \"\
  city\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"province\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/yum-china/refs/heads/main/json-ld/yum-china-context.jsonld
tags:
- Restaurants
- Fast Food
- Quick Service Restaurant
- Digital Ordering
- Loyalty
- China
- Food Technology
- JSON-LD
- Linked Data
- Semantic Web
---
