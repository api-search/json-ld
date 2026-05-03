---
api_specs:
- filename: yaml-spec
  format: yaml
  label: USDA FoodData Central API
  slug: usda-fooddata-central-api
  spec_type: OpenAPI
  url: https://api.nal.usda.gov/fdc/v1/yaml-spec?api_key=DEMO_KEY
- filename: usda-nass-quickstats-openapi.yml
  format: yaml
  label: USDA NASS Quick Stats API
  slug: usda-nass-quickstats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nass-quickstats-openapi.yml
- filename: usda-ers-arms-openapi.yml
  format: yaml
  label: USDA ERS ARMS Data API
  slug: usda-ers-arms-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-ers-arms-openapi.yml
- filename: usda-nrcs-awdb-openapi.yml
  format: yaml
  label: USDA NRCS AWDB Water and Climate REST API
  slug: usda-nrcs-awdb-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/openapi/usda-nrcs-awdb-openapi.yml
class_count: 4
classes:
- FoodItem
- Nutrient
- AgriculturalStatistic
- GovernmentOrganization
context_file: json-ld/united-states-department-of-agriculture-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/json-ld/united-states-department-of-agriculture-context.jsonld
description: JSON-LD context defining the semantic vocabulary for United States Department Of Agriculture from United States Department of Agriculture.
layout: jsonld
name: United States Department Of Agriculture Context
namespaces:
- prefix: usda
  uri: https://fdc.nal.usda.gov/ontology/
- prefix: nass
  uri: https://quickstats.nass.usda.gov/ontology/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: agri
  uri: http://purl.org/agri/
properties:
- container: ''
  name: fdcId
  type: reference
- container: ''
  name: description
  type: ''
- container: ''
  name: dataType
  type: ''
- container: ''
  name: publicationDate
  type: schema:Date
- container: ''
  name: brandOwner
  type: ''
- container: ''
  name: foodCategory
  type: ''
- container: ''
  name: nutrientName
  type: ''
- container: ''
  name: nutrientNumber
  type: ''
- container: ''
  name: unitName
  type: ''
- container: ''
  name: value
  type: schema:Number
- container: ''
  name: commodity_desc
  type: ''
- container: ''
  name: year
  type: ''
- container: ''
  name: state_name
  type: ''
- container: ''
  name: Value
  type: ''
property_count: 14
provider_name: United States Department of Agriculture
provider_slug: united-states-department-of-agriculture
slug: united-states-department-of-agriculture-context
source_filename: united-states-department-of-agriculture-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"usda\": \"https://fdc.nal.usda.gov/ontology/\",\n    \"nass\": \"https://quickstats.nass.usda.gov/ontology/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"agri\": \"http://purl.org/agri/\",\n\n    \"FoodItem\": \"usda:FoodItem\",\n    \"Nutrient\": \"usda:Nutrient\",\n    \"AgriculturalStatistic\": \"nass:AgriculturalStatistic\",\n    \"GovernmentOrganization\": \"GovernmentOrganization\",\n\n    \"fdcId\": {\n      \"@id\": \"usda:fdcId\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"dataType\": {\n      \"@id\": \"usda:dataType\"\n    },\n    \"publicationDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"schema:Date\"\n    },\n    \"brandOwner\": {\n      \"@id\": \"schema:brand\"\n    },\n    \"foodCategory\": {\n      \"@id\": \"schema:category\"\n    },\n    \"nutrientName\": {\n      \"@id\": \"schema:name\"\
  \n    },\n    \"nutrientNumber\": {\n      \"@id\": \"usda:nutrientNumber\"\n    },\n    \"unitName\": {\n      \"@id\": \"schema:unitCode\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"schema:Number\"\n    },\n    \"commodity_desc\": {\n      \"@id\": \"agri:commodity\"\n    },\n    \"year\": {\n      \"@id\": \"schema:temporalCoverage\"\n    },\n    \"state_name\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"Value\": {\n      \"@id\": \"schema:value\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/united-states-department-of-agriculture/refs/heads/main/json-ld/united-states-department-of-agriculture-context.jsonld
tags:
- Federal Government
- Agriculture
- Food Safety
- Nutrition
- Rural Development
- Climate
- JSON-LD
- Linked Data
- Semantic Web
---
