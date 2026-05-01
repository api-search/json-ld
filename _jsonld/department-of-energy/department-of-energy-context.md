---
class_count: 0
classes: []
context_file: json-ld/department-of-energy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/json-ld/department-of-energy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Energy from Department of Energy.
layout: jsonld
name: Department Of Energy Context
namespaces:
- prefix: doe
  uri: https://www.energy.gov/
properties:
- container: ''
  name: Series
  type: ''
- container: ''
  name: Observation
  type: ''
- container: ''
  name: Publication
  type: ''
- container: ''
  name: Station
  type: ''
- container: ''
  name: Building
  type: ''
- container: ''
  name: Dataset
  type: ''
property_count: 6
provider_name: Department of Energy
provider_slug: department-of-energy
slug: department-of-energy-context
source_filename: department-of-energy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"doe\": \"https://www.energy.gov/\",\n    \"Series\": {\n      \"@id\": \"doe:eia/series\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"frequency\": \"https://schema.org/temporalCoverage\",\n        \"units\": \"https://schema.org/unitText\"\n      }\n    },\n    \"Observation\": {\n      \"@id\": \"doe:eia/observation\",\n      \"@context\": {\n        \"period\": \"https://schema.org/temporalCoverage\",\n        \"value\": \"https://schema.org/value\",\n        \"series\": \"https://schema.org/about\"\n      }\n    },\n    \"Publication\": {\n      \"@id\": \"https://schema.org/ScholarlyArticle\",\n      \"@context\": {\n        \"osti_id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n        \"authors\": \"https://schema.org/author\",\n        \"publicationDate\": \"https://schema.org/datePublished\"\
  ,\n        \"doi\": \"https://schema.org/sameAs\"\n      }\n    },\n    \"Station\": {\n      \"@id\": \"doe:nrel/station\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"fuelType\": \"https://schema.org/fuelType\",\n        \"address\": \"https://schema.org/address\",\n        \"latitude\": \"https://schema.org/latitude\",\n        \"longitude\": \"https://schema.org/longitude\"\n      }\n    },\n    \"Building\": {\n      \"@id\": \"doe:bpd/building\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"type\": \"https://schema.org/buildingType\",\n        \"vintage\": \"https://schema.org/yearBuilt\",\n        \"climateZone\": \"https://schema.org/climateContent\",\n        \"eui\": \"https://schema.org/value\"\n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\"\
  ,\n        \"title\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"publisher\": \"https://schema.org/publisher\",\n        \"license\": \"https://schema.org/license\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-energy/refs/heads/main/json-ld/department-of-energy-context.jsonld
tags:
- Buildings
- Electricity
- Energy
- Federal Government
- Open Data
- Renewables
- Research
- Solar
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---
