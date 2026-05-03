---
class_count: 25
classes:
- FoodserviceOrder
- FoodserviceProduct
- OrderLineItem
- FoodServiceProvider
- DistributionCenter
- id
- type
- orderId
- customerId
- status
- items
- itemNumber
- gtin
- description
- brand
- packSize
- ingredients
- allergens
- calories
- servingSize
- countryOfOrigin
- isActive
- quantityOrdered
- unitPrice
- unitOfMeasure
context_file: json-ld/us-foods-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-foods/refs/heads/main/json-ld/us-foods-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Foods from US Foods.
layout: jsonld
name: Us Foods Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: usf
  uri: https://www.usfoods.com/ns/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: images
  type: reference
- container: ''
  name: Organization
  type: ''
property_count: 4
provider_name: US Foods
provider_slug: us-foods
slug: us-foods-context
source_filename: us-foods-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"usf\": \"https://www.usfoods.com/ns/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FoodserviceOrder\": \"schema:Order\",\n    \"FoodserviceProduct\": \"schema:Product\",\n    \"OrderLineItem\": \"schema:OrderItem\",\n    \"FoodServiceProvider\": \"schema:FoodService\",\n    \"DistributionCenter\": \"schema:Warehouse\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"orderId\": \"schema:orderNumber\",\n    \"customerId\": \"schema:customer\",\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"deliveryDate\": {\n      \"@id\": \"schema:expectedArrivalUntil\",\n      \"@type\": \"xsd:date\"\n    },\n    \"status\": \"schema:orderStatus\",\n    \"items\": \"schema:orderedItem\",\n\n    \"itemNumber\": \"gs1:gtin\",\n    \"gtin\": \"gs1:gtin\",\n    \"description\"\
  : \"schema:description\",\n    \"brand\": \"schema:brand\",\n    \"packSize\": \"gs1:packagingType\",\n    \"ingredients\": \"schema:ingredients\",\n    \"allergens\": \"schema:hasAllergen\",\n    \"calories\": \"schema:calories\",\n    \"servingSize\": \"schema:servingSize\",\n    \"countryOfOrigin\": \"schema:countryOfOrigin\",\n    \"isActive\": \"schema:discontinued\",\n    \"images\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n\n    \"quantityOrdered\": \"schema:orderQuantity\",\n    \"unitPrice\": \"schema:price\",\n    \"unitOfMeasure\": \"schema:unitCode\",\n\n    \"Organization\": {\n      \"@id\": \"schema:Corporation\",\n      \"name\": \"US Foods\",\n      \"url\": \"https://www.usfoods.com\",\n      \"sameAs\": [\n        \"https://www.wikidata.org/wiki/Q7884960\",\n        \"https://www.dnb.com/business-directory/company-profiles.us_foods_holding_corp.html\"\n      ]\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-foods/refs/heads/main/json-ld/us-foods-context.jsonld
tags:
- Food Service
- Fortune 500
- Distribution
- Supply Chain
- eCommerce
- JSON-LD
- Linked Data
- Semantic Web
---
