---
api_specs:
- filename: wegowise-openapi.yml
  format: yaml
  label: WegoWise API
  slug: wegowise
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/openapi/wegowise-openapi.yml
class_count: 0
classes: []
context_file: json-ld/wegowise-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/json-ld/wegowise-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wegowise from WegoWise.
layout: jsonld
name: Wegowise Context
namespaces:
- prefix: wegowise
  uri: https://www.wegowise.com/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: Building
  type: reference
- container: ''
  name: Meter
  type: reference
- container: ''
  name: RawDatapoint
  type: reference
- container: ''
  name: Development
  type: reference
- container: ''
  name: Apartment
  type: reference
- container: ''
  name: UtilityCompany
  type: reference
- container: ''
  name: id
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: gross_area
  type: decimal
- container: ''
  name: year_built
  type: integer
- container: ''
  name: number_of_units
  type: integer
- container: ''
  name: account_number
  type: string
- container: ''
  name: data_type
  type: string
- container: ''
  name: start_date
  type: date
- container: ''
  name: end_date
  type: date
- container: ''
  name: total_charge
  type: decimal
- container: ''
  name: kwh
  type: decimal
- container: ''
  name: btu
  type: decimal
- container: ''
  name: gallons
  type: decimal
- container: ''
  name: EnergyBenchmarking
  type: reference
property_count: 24
provider_name: WegoWise
provider_slug: wegowise
slug: wegowise-context
source_filename: wegowise-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"wegowise\": \"https://www.wegowise.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"Building\": {\n      \"@id\": \"schema:LodgingBusiness\",\n      \"@type\": \"@id\",\n      \"description\": \"A building tracked in WegoWise for energy benchmarking\"\n    },\n\n    \"Meter\": {\n      \"@id\": \"wegowise:Meter\",\n      \"@type\": \"@id\",\n      \"description\": \"A utility meter measuring energy or water consumption at a building\"\n    },\n\n    \"RawDatapoint\": {\n      \"@id\": \"wegowise:RawDatapoint\",\n      \"@type\": \"@id\",\n      \"description\": \"A raw utility usage reading for a billing period\"\n    },\n\n    \"Development\": {\n      \"@id\": \"schema:RealEstateListing\",\n      \"@type\": \"@id\",\n      \"description\": \"A development\
  \ grouping multiple buildings in a portfolio\"\n    },\n\n    \"Apartment\": {\n      \"@id\": \"schema:Accommodation\",\n      \"@type\": \"@id\",\n      \"description\": \"A residential apartment unit within a building\"\n    },\n\n    \"UtilityCompany\": {\n      \"@id\": \"schema:Organization\",\n      \"@type\": \"@id\",\n      \"description\": \"A utility company providing electric, gas, water, or other services\"\n    },\n\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"address\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"zip\": {\n      \"@id\": \"schema:postalCode\",\n      \"\
  @type\": \"xsd:string\"\n    },\n\n    \"gross_area\": {\n      \"@id\": \"schema:floorSize\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"year_built\": {\n      \"@id\": \"schema:yearBuilt\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"number_of_units\": {\n      \"@id\": \"wegowise:numberOfUnits\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"account_number\": {\n      \"@id\": \"schema:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"data_type\": {\n      \"@id\": \"wegowise:utilityType\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"start_date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"end_date\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"total_charge\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"kwh\": {\n      \"@id\": \"wegowise:kilowattHours\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"btu\": {\n\
  \      \"@id\": \"wegowise:btu\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"gallons\": {\n      \"@id\": \"wegowise:gallons\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"EnergyBenchmarking\": {\n      \"@id\": \"wegowise:EnergyBenchmarking\",\n      \"@type\": \"@id\",\n      \"description\": \"The process of measuring and comparing a building's energy performance\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wegowise/refs/heads/main/json-ld/wegowise-context.jsonld
tags:
- Benchmarking
- Building Energy
- Energy Efficiency
- Multifamily
- Property Management
- Utility Data
- JSON-LD
- Linked Data
- Semantic Web
---
