---
api_specs:
- filename: census-data-api-openapi.yml
  format: yaml
  label: Census Data API
  slug: census-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/openapi/census-data-api-openapi.yml
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/united-states-census-bureau-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/json-ld/united-states-census-bureau-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Census Bureau from United States Census Bureau.
layout: jsonld
name: United States Census Bureau Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: dct
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sdmx
  uri: http://purl.org/linked-data/sdmx/2009/dimension#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: skos
  uri: http://www.w3.org/2004/02/skos/core#
- prefix: census
  uri: https://api.census.gov/vocab#
- prefix: tiger
  uri: https://tigerweb.geo.census.gov/vocab#
properties:
- container: ''
  name: CensusDataset
  type: reference
- container: ''
  name: StatisticalVariable
  type: reference
- container: ''
  name: CensusGeography
  type: reference
- container: ''
  name: CensusTract
  type: reference
- container: ''
  name: BlockGroup
  type: reference
- container: ''
  name: FIPS
  type: ''
- container: ''
  name: populationEstimate
  type: integer
- container: ''
  name: medianHouseholdIncome
  type: decimal
- container: ''
  name: medianHomeValue
  type: decimal
- container: ''
  name: vintage
  type: ''
- container: ''
  name: surveyYear
  type: integer
- container: ''
  name: geoLevel
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: county
  type: ''
- container: ''
  name: tract
  type: ''
- container: ''
  name: blockGroup
  type: ''
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: matchedAddress
  type: ''
- container: ''
  name: coordinates
  type: reference
- container: ''
  name: publisher
  type: reference
property_count: 21
provider_name: United States Census Bureau
provider_slug: united-states-census-bureau
slug: united-states-census-bureau-context
source_filename: united-states-census-bureau-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sdmx\": \"http://purl.org/linked-data/sdmx/2009/dimension#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"skos\": \"http://www.w3.org/2004/02/skos/core#\",\n    \"census\": \"https://api.census.gov/vocab#\",\n    \"tiger\": \"https://tigerweb.geo.census.gov/vocab#\",\n\n    \"CensusDataset\": {\n      \"@id\": \"schema:Dataset\",\n      \"@type\": \"@id\"\n    },\n    \"StatisticalVariable\": {\n      \"@id\": \"census:StatisticalVariable\",\n      \"@type\": \"@id\"\n    },\n    \"CensusGeography\": {\n      \"@id\": \"census:CensusGeography\",\n      \"@type\": \"@id\"\n    },\n    \"CensusTract\": {\n      \"@id\": \"census:Tract\",\n      \"@type\": \"@id\"\n    },\n    \"BlockGroup\": {\n      \"@id\": \"census:BlockGroup\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"FIPS\": {\n      \"@id\": \"census:FIPSCode\"\n    },\n    \"populationEstimate\": {\n      \"@id\": \"census:populationEstimate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"medianHouseholdIncome\": {\n      \"@id\": \"census:medianHouseholdIncome\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"medianHomeValue\": {\n      \"@id\": \"census:medianHomeValue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"vintage\": {\n      \"@id\": \"census:vintage\"\n    },\n    \"surveyYear\": {\n      \"@id\": \"census:surveyYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"geoLevel\": {\n      \"@id\": \"census:geographyLevel\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"county\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"tract\": {\n      \"@id\": \"census:censusTract\"\n    },\n    \"blockGroup\": {\n      \"@id\": \"census:blockGroup\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\"\
  : \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"matchedAddress\": {\n      \"@id\": \"schema:address\"\n    },\n    \"coordinates\": {\n      \"@id\": \"geo:hasGeometry\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"publisher\": {\n      \"@id\": \"schema:publisher\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-census-bureau/refs/heads/main/json-ld/united-states-census-bureau-context.jsonld
tags:
- Demographics
- Federal Government
- Open Data
- Statistics
- Economics
- Population
- JSON-LD
- Linked Data
- Semantic Web
---
