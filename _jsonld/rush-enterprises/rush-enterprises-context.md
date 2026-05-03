---
class_count: 0
classes: []
context_file: json-ld/rush-enterprises-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rush-enterprises/refs/heads/main/json-ld/rush-enterprises-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rush Enterprises from Rush Enterprises.
layout: jsonld
name: Rush Enterprises Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rush
  uri: https://www.rushtruckcenters.com/vocab/
properties:
- container: ''
  name: CommercialVehicle
  type: reference
- container: ''
  name: vehicleId
  type: schema:Text
- container: ''
  name: vin
  type: schema:Text
- container: ''
  name: make
  type: schema:Text
- container: ''
  name: model
  type: schema:Text
- container: ''
  name: year
  type: schema:Integer
- container: ''
  name: mileage
  type: schema:QuantitativeValue
- container: ''
  name: price
  type: schema:Number
- container: ''
  name: ServiceEvent
  type: reference
- container: ''
  name: serviceType
  type: schema:Text
- container: ''
  name: status
  type: schema:Text
- container: ''
  name: scheduledDate
  type: schema:DateTime
- container: ''
  name: completedDate
  type: schema:DateTime
- container: list
  name: faultCodes
  type: ''
- container: ''
  name: Location
  type: reference
- container: ''
  name: name
  type: schema:Text
- container: ''
  name: address
  type: schema:Text
- container: ''
  name: city
  type: schema:Text
- container: ''
  name: state
  type: schema:Text
property_count: 19
provider_name: Rush Enterprises
provider_slug: rush-enterprises
slug: rush-enterprises-context
source_filename: rush-enterprises-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rush\": \"https://www.rushtruckcenters.com/vocab/\",\n    \"CommercialVehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@type\": \"@id\"\n    },\n    \"vehicleId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"schema:Text\"\n    },\n    \"vin\": {\n      \"@id\": \"schema:vehicleIdentificationNumber\",\n      \"@type\": \"schema:Text\"\n    },\n    \"make\": {\n      \"@id\": \"schema:vehicleMake\",\n      \"@type\": \"schema:Text\"\n    },\n    \"model\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"schema:Text\"\n    },\n    \"year\": {\n      \"@id\": \"schema:modelDate\",\n      \"@type\": \"schema:Integer\"\n    },\n    \"mileage\": {\n      \"@id\": \"schema:mileageFromOdometer\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"price\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"ServiceEvent\"\
  : {\n      \"@id\": \"rush:ServiceEvent\",\n      \"@type\": \"@id\"\n    },\n    \"serviceType\": {\n      \"@id\": \"rush:serviceType\",\n      \"@type\": \"schema:Text\"\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"schema:Text\"\n    },\n    \"scheduledDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completedDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"faultCodes\": {\n      \"@id\": \"rush:faultCodes\",\n      \"@container\": \"@list\"\n    },\n    \"Location\": {\n      \"@id\": \"schema:AutoRepair\",\n      \"@type\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"schema:Text\"\n    },\n    \"address\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"schema:Text\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"schema:Text\"\n    },\n    \"state\"\
  : {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"schema:Text\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rush-enterprises/refs/heads/main/json-ld/rush-enterprises-context.jsonld
tags:
- Commercial Vehicles
- Fleet Management
- Telematics
- Truck Dealerships
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
