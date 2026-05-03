---
api_specs:
- filename: volkswagen-okapi-openapi.yml
  format: yaml
  label: Volkswagen OKAPI - Open Konfigurator API
  slug: volkswagen-okapi
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/volkswagen/refs/heads/main/openapi/volkswagen-okapi-openapi.yml
class_count: 25
classes:
- configId
- typeId
- selectedOptions
- buildable
- wltp
- fuelConsumption
- co2Emissions
- energyEfficiencyClass
- Car
- Vehicle
- Offer
- Product
- Organization
- name
- description
- identifier
- price
- priceCurrency
- url
- brand
- model
- manufacturer
- countryOfOrigin
- fuelType
- emissionsCO2
context_file: json-ld/volkswagen-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/volkswagen/refs/heads/main/json-ld/volkswagen-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Volkswagen from Volkswagen.
layout: jsonld
name: Volkswagen Context
namespaces:
- prefix: vw
  uri: https://productdata.volkswagenag.com/ns/
- prefix: okapi
  uri: https://productdata.volkswagenag.com/v3/
properties: []
property_count: 0
provider_name: Volkswagen
provider_slug: volkswagen
slug: volkswagen-context
source_filename: volkswagen-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vw\": \"https://productdata.volkswagenag.com/ns/\",\n    \"okapi\": \"https://productdata.volkswagenag.com/v3/\",\n    \"configId\": \"vw:configId\",\n    \"typeId\": \"vw:typeId\",\n    \"selectedOptions\": \"vw:selectedOptions\",\n    \"buildable\": \"vw:buildable\",\n    \"wltp\": \"vw:WltpData\",\n    \"fuelConsumption\": \"vw:fuelConsumption\",\n    \"co2Emissions\": \"vw:co2Emissions\",\n    \"energyEfficiencyClass\": \"vw:energyEfficiencyClass\",\n    \"Car\": \"schema:Car\",\n    \"Vehicle\": \"schema:Vehicle\",\n    \"Offer\": \"schema:Offer\",\n    \"Product\": \"schema:Product\",\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"identifier\": \"schema:identifier\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\",\n    \"url\": \"schema:url\",\n    \"brand\": \"schema:brand\",\n\
  \    \"model\": \"schema:model\",\n    \"manufacturer\": \"schema:manufacturer\",\n    \"countryOfOrigin\": \"schema:countryOfOrigin\",\n    \"fuelType\": \"schema:fuelType\",\n    \"emissionsCO2\": \"schema:emissionsCO2\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/volkswagen/refs/heads/main/json-ld/volkswagen-context.jsonld
tags:
- Automobiles
- Cars
- Vehicles
- Automotive
- Vehicle Configuration
- JSON-LD
- Linked Data
- Semantic Web
---
