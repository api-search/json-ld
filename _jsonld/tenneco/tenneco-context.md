---
class_count: 6
classes:
- AutoPartsStore
- Product
- Organization
- name
- description
- url
context_file: json-ld/tenneco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tenneco/refs/heads/main/json-ld/tenneco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tenneco from Tenneco.
layout: jsonld
name: Tenneco Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tenneco
  uri: https://www.tenneco.com/#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AutoPart
  type: reference
- container: ''
  name: VehicleFitment
  type: reference
- container: ''
  name: AftermarketBrand
  type: reference
- container: ''
  name: partNumber
  type: string
- container: ''
  name: brand
  type: reference
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: vehicleMake
  type: string
- container: ''
  name: vehicleModel
  type: string
- container: ''
  name: vehicleYear
  type: integer
- container: ''
  name: category
  type: '@vocab'
property_count: 10
provider_name: Tenneco
provider_slug: tenneco
slug: tenneco-context
source_filename: tenneco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tenneco\": \"https://www.tenneco.com/#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"AutoPart\": {\n      \"@id\": \"tenneco:AutoPart\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An automotive component or part\"\n    },\n    \"VehicleFitment\": {\n      \"@id\": \"tenneco:VehicleFitment\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"Vehicle application fitment data for a part\"\n    },\n    \"AftermarketBrand\": {\n      \"@id\": \"tenneco:AftermarketBrand\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"An aftermarket automotive brand under the DRiV portfolio\"\n    },\n\n    \"AutoPartsStore\": \"schema:AutoPartsStore\",\n    \"Product\": \"schema:Product\",\n    \"Organization\": \"schema:Organization\",\n\n    \"name\": \"\
  schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"partNumber\": {\n      \"@id\": \"schema:productID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brand\": {\n      \"@id\": \"schema:brand\",\n      \"@type\": \"@id\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"vehicleMake\": {\n      \"@id\": \"schema:vehicleConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicleModel\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vehicleYear\": {\n      \"@id\": \"schema:vehicleModelDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"category\": {\n      \"@id\": \"tenneco:productCategory\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"Clean Air\": \"tenneco:CleanAir\",\n        \"Powertrain\": \"tenneco:Powertrain\",\n        \"Ride Performance\": \"tenneco:RidePerformance\",\n        \"Aftermarket\"\
  : \"tenneco:Aftermarket\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tenneco/refs/heads/main/json-ld/tenneco-context.jsonld
tags:
- Aftermarket
- Automotive
- Emissions Control
- Manufacturing
- Powertrain
- Ride Performance
- JSON-LD
- Linked Data
- Semantic Web
---
