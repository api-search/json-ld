---
class_count: 33
classes:
- FuelOrder
- FuelProduct
- Terminal
- EnergySupplier
- order_id
- status
- order_date
- delivery_date
- customer
- account_id
- delivery_location
- street
- city
- state
- zip
- country
- product
- quantity
- amount
- unit
- pricing
- price_per_unit
- currency
- total_amount
- terminal
- driver_notes
- heating_oil
- diesel
- ultra_low_sulfur_diesel
- gasoline
- kerosene
- biofuel
- bunker_fuel
context_file: json-ld/sprague-resources-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sprague-resources/refs/heads/main/json-ld/sprague-resources-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sprague Resources from Sprague Resources.
layout: jsonld
name: Sprague Resources Context
namespaces:
- prefix: sprague
  uri: https://spragueenergy.com/vocab#
- prefix: energy
  uri: https://schema.org/EnergyConsumptionDetails
properties:
- container: ''
  name: SpraguePORT
  type: reference
- container: ''
  name: NaturalGas
  type: reference
- container: ''
  name: Electricity
  type: reference
property_count: 3
provider_name: Sprague Resources
provider_slug: sprague-resources
slug: sprague-resources-context
source_filename: sprague-resources-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sprague\": \"https://spragueenergy.com/vocab#\",\n    \"energy\": \"https://schema.org/EnergyConsumptionDetails\",\n    \"FuelOrder\": \"sprague:FuelOrder\",\n    \"FuelProduct\": \"sprague:FuelProduct\",\n    \"Terminal\": \"sprague:Terminal\",\n    \"EnergySupplier\": \"Organization\",\n    \"order_id\": \"orderNumber\",\n    \"status\": \"orderStatus\",\n    \"order_date\": \"orderDate\",\n    \"delivery_date\": \"expectedArrivalFrom\",\n    \"customer\": \"customer\",\n    \"account_id\": \"identifier\",\n    \"delivery_location\": \"deliveryAddress\",\n    \"street\": \"streetAddress\",\n    \"city\": \"addressLocality\",\n    \"state\": \"addressRegion\",\n    \"zip\": \"postalCode\",\n    \"country\": \"addressCountry\",\n    \"product\": \"orderedItem\",\n    \"quantity\": \"orderQuantity\",\n    \"amount\": \"value\",\n    \"unit\": \"unitText\",\n    \"pricing\": \"priceSpecification\",\n    \"\
  price_per_unit\": \"price\",\n    \"currency\": \"priceCurrency\",\n    \"total_amount\": \"totalPrice\",\n    \"terminal\": \"seller\",\n    \"driver_notes\": \"disambiguatingDescription\",\n    \"heating_oil\": \"sprague:HeatingOil\",\n    \"diesel\": \"sprague:Diesel\",\n    \"ultra_low_sulfur_diesel\": \"sprague:UltraLowSulfurDiesel\",\n    \"gasoline\": \"sprague:Gasoline\",\n    \"kerosene\": \"sprague:Kerosene\",\n    \"biofuel\": \"sprague:Biofuel\",\n    \"bunker_fuel\": \"sprague:BunkerFuel\",\n    \"SpraguePORT\": {\n      \"@id\": \"sprague:SpraguePORT\",\n      \"@type\": \"@id\"\n    },\n    \"NaturalGas\": {\n      \"@id\": \"sprague:NaturalGas\",\n      \"@type\": \"@id\"\n    },\n    \"Electricity\": {\n      \"@id\": \"sprague:Electricity\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sprague-resources/refs/heads/main/json-ld/sprague-resources-context.jsonld
tags:
- Energy
- Petroleum
- Natural Gas
- Fuel Distribution
- Materials Handling
- Northeast
- JSON-LD
- Linked Data
- Semantic Web
---
