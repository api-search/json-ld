---
api_specs:
- filename: thermal-power-openapi.yml
  format: yaml
  label: Thermal Power API
  slug: thermal-power
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/openapi/thermal-power-openapi.yml
class_count: 0
classes: []
context_file: json-ld/thermal-power-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/json-ld/thermal-power-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thermal Power from Thermal Power.
layout: jsonld
name: Thermal Power Context
namespaces:
- prefix: eia
  uri: https://www.eia.gov/opendata/
- prefix: energy
  uri: https://dbpedia.org/ontology/
properties:
- container: ''
  name: PowerPlant
  type: ''
- container: ''
  name: ElectricPowerRecord
  type: ''
- container: ''
  name: RTORecord
  type: ''
property_count: 3
provider_name: Thermal Power
provider_slug: thermal-power
slug: thermal-power-context
source_filename: thermal-power-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"eia\": \"https://www.eia.gov/opendata/\",\n    \"energy\": \"https://dbpedia.org/ontology/\",\n    \"PowerPlant\": {\n      \"@id\": \"energy:PowerStation\",\n      \"@context\": {\n        \"plantCode\": \"https://schema.org/identifier\",\n        \"plantName\": \"https://schema.org/name\",\n        \"state\": \"https://schema.org/addressRegion\",\n        \"capacityMW\": {\n          \"@id\": \"energy:installedCapacity\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"generation\": {\n          \"@id\": \"energy:netElectricity\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"fuelType\": {\n          \"@id\": \"energy:usingFuel\",\n          \"@type\": \"@id\"\n        },\n        \"heatRate\": {\n          \"@id\": \"eia:heatRate\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"heatContent\"\
  : {\n          \"@id\": \"eia:heatContent\",\n          \"@type\": \"https://schema.org/QuantitativeValue\"\n        },\n        \"primeMover\": {\n          \"@id\": \"eia:primeMoverCode\"\n        }\n      }\n    },\n    \"ElectricPowerRecord\": {\n      \"@id\": \"eia:electricPowerOperationalData\",\n      \"@context\": {\n        \"period\": \"https://schema.org/temporal\",\n        \"location\": \"https://schema.org/addressRegion\",\n        \"fueltypeid\": \"energy:usingFuel\",\n        \"generation\": \"energy:netElectricity\",\n        \"sectorid\": \"eia:sectorId\",\n        \"sectorDescription\": \"https://schema.org/description\"\n      }\n    },\n    \"RTORecord\": {\n      \"@id\": \"eia:rtoFuelTypeData\",\n      \"@context\": {\n        \"period\": \"https://schema.org/temporal\",\n        \"respondent\": \"https://schema.org/identifier\",\n        \"respondent-name\": \"https://schema.org/name\",\n        \"fueltype\": \"energy:usingFuel\",\n        \"value\": \"energy:netElectricity\"\
  \n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thermal-power/refs/heads/main/json-ld/thermal-power-context.jsonld
tags:
- Energy
- Thermal Power
- Power Generation
- Electricity
- Coal
- Natural Gas
- Nuclear
- JSON-LD
- Linked Data
- Semantic Web
---
