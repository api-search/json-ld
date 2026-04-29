---
class_count: 0
classes: []
context_file: json-ld/carsxe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/carsxe/refs/heads/main/json-ld/carsxe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Carsxe from CarsXE.
layout: jsonld
name: Carsxe Context
namespaces:
- prefix: carsxe
  uri: https://carsxe.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: LicensePlate
  type: ''
- container: ''
  name: MarketValue
  type: ''
- container: ''
  name: VehicleHistoryRecord
  type: ''
- container: ''
  name: SafetyRecall
  type: ''
- container: ''
  name: VehicleImage
  type: ''
- container: ''
  name: OBDCode
  type: ''
- container: ''
  name: OCRResult
  type: ''
property_count: 8
provider_name: CarsXE
provider_slug: carsxe
slug: carsxe-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"carsxe\": \"https://carsxe.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Vehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@context\": {\n        \"vin\": {\n          \"@id\": \"schema:vehicleIdentificationNumber\",\n          \"@type\": \"xsd:string\"\n        },\n        \"year\": {\n          \"@id\": \"schema:vehicleModelDate\",\n          \"@type\": \"xsd:gYear\"\n        },\n        \"make\": \"schema:brand\",\n        \"model\": \"schema:model\",\n        \"trim\": \"carsxe:trim\",\n        \"engine\": \"carsxe:engine\",\n        \"drivetrain\": \"carsxe:drivetrain\",\n        \"bodyStyle\": \"schema:bodyType\",\n        \"fuelType\": \"schema:fuelType\"\n      }\n    },\n\n    \"LicensePlate\": {\n      \"@id\": \"carsxe:LicensePlate\",\n      \"@context\": {\n        \"plate\": {\n          \"@id\": \"carsxe:plate\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"state\": \"schema:addressRegion\",\n        \"country\": \"schema:addressCountry\"\n      }\n    },\n\n    \"MarketValue\": {\n      \"@id\": \"carsxe:MarketValue\",\n      \"@context\": {\n        \"retail\": {\n          \"@id\": \"carsxe:retail\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"wholesale\": {\n          \"@id\": \"carsxe:wholesale\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"tradeIn\": {\n          \"@id\": \"carsxe:tradeIn\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"currency\": \"schema:priceCurrency\",\n        \"asOf\": {\n          \"@id\": \"carsxe:asOf\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"VehicleHistoryRecord\": {\n      \"@id\": \"carsxe:VehicleHistoryRecord\",\n      \"@context\": {\n        \"eventType\": \"carsxe:eventType\",\n        \"eventDate\": {\n          \"@id\": \"schema:dateRecorded\",\n          \"@type\": \"xsd:date\"\
  \n        },\n        \"odometer\": {\n          \"@id\": \"carsxe:odometer\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"titleState\": \"carsxe:titleState\",\n        \"source\": \"schema:provider\"\n      }\n    },\n\n    \"SafetyRecall\": {\n      \"@id\": \"schema:ProductRecall\",\n      \"@context\": {\n        \"campaignId\": \"schema:identifier\",\n        \"summary\": \"schema:description\",\n        \"remedy\": \"carsxe:remedy\",\n        \"issuedAt\": {\n          \"@id\": \"carsxe:issuedAt\",\n          \"@type\": \"xsd:date\"\n        }\n      }\n    },\n\n    \"VehicleImage\": {\n      \"@id\": \"schema:ImageObject\",\n      \"@context\": {\n        \"url\": \"schema:contentUrl\",\n        \"color\": \"carsxe:color\",\n        \"transparentBackground\": {\n          \"@id\": \"carsxe:transparentBackground\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"OBDCode\": {\n      \"@id\": \"carsxe:OBDCode\",\n      \"@context\": {\n\
  \        \"code\": \"carsxe:code\",\n        \"description\": \"schema:description\",\n        \"system\": \"carsxe:system\"\n      }\n    },\n\n    \"OCRResult\": {\n      \"@id\": \"carsxe:OCRResult\",\n      \"@context\": {\n        \"text\": {\n          \"@id\": \"carsxe:text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"confidence\": {\n          \"@id\": \"carsxe:confidence\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"imageUrl\": \"schema:contentUrl\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/carsxe/refs/heads/main/json-ld/carsxe-context.jsonld
tags:
- Automotive
- Vehicles
- VIN
- Vehicle Data
- License Plate
- OCR
- Automobiles
- JSON-LD
- Linked Data
- Semantic Web
---
