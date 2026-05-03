---
api_specs:
- filename: apispec
  format: yaml
  label: USDA FoodData Central API
  slug: fooddata-central-api
  spec_type: OpenAPI
  url: https://fdc.nal.usda.gov/portal-data/external/apispec
- filename: usda-ars-ag-data-commons-openapi.yml
  format: yaml
  label: USDA Ag Data Commons CKAN API
  slug: ag-data-commons-ckan-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/openapi/usda-ars-ag-data-commons-openapi.yml
class_count: 3
classes:
- FoodItem
- FoodNutrient
- AgriculturalDataset
context_file: json-ld/usda-agricultural-research-service-ars--context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/json-ld/usda-agricultural-research-service-ars--context.jsonld
description: JSON-LD context defining the semantic vocabulary for Usda Agricultural Research Service Ars from USDA Agricultural Research Service (ARS).
layout: jsonld
name: Usda Agricultural Research Service Ars Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: food
  uri: https://fdc.nal.usda.gov/vocab/
- prefix: agri
  uri: https://aims.fao.org/aos/agrovoc/
properties:
- container: ''
  name: fdcId
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: dataType
  type: string
- container: ''
  name: publishedDate
  type: date
- container: ''
  name: foodCategory
  type: string
- container: ''
  name: brandOwner
  type: string
- container: ''
  name: ingredients
  type: string
- container: ''
  name: servingSize
  type: decimal
- container: set
  name: foodNutrients
  type: ''
- container: ''
  name: nutrientName
  type: string
- container: ''
  name: unitName
  type: string
- container: ''
  name: value
  type: decimal
- container: ''
  name: title
  type: string
- container: ''
  name: notes
  type: string
- container: ''
  name: author
  type: string
- container: set
  name: tags
  type: ''
- container: ''
  name: license_title
  type: string
property_count: 17
provider_name: USDA Agricultural Research Service (ARS)
provider_slug: usda-agricultural-research-service-ars-
slug: usda-agricultural-research-service-ars--context
source_filename: usda-agricultural-research-service-ars--context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"food\": \"https://fdc.nal.usda.gov/vocab/\",\n    \"agri\": \"https://aims.fao.org/aos/agrovoc/\",\n\n    \"FoodItem\": \"schema:NutritionInformation\",\n    \"FoodNutrient\": \"schema:PropertyValue\",\n    \"AgriculturalDataset\": \"schema:Dataset\",\n\n    \"fdcId\": {\n      \"@id\": \"food:fdcId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataType\": {\n      \"@id\": \"food:dataType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publishedDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"foodCategory\": {\n      \"@id\": \"food:foodCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"brandOwner\": {\n      \"\
  @id\": \"schema:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingredients\": {\n      \"@id\": \"food:ingredients\",\n      \"@type\": \"xsd:string\"\n    },\n    \"servingSize\": {\n      \"@id\": \"schema:servingSize\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"foodNutrients\": {\n      \"@id\": \"schema:nutrition\",\n      \"@container\": \"@set\"\n    },\n    \"nutrientName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unitName\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"title\": {\n      \"@id\": \"dcterms:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notes\": {\n      \"@id\": \"dcterms:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"dcterms:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"\
  dcterms:subject\",\n      \"@container\": \"@set\"\n    },\n    \"license_title\": {\n      \"@id\": \"dcterms:license\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/usda-agricultural-research-service-ars-/refs/heads/main/json-ld/usda-agricultural-research-service-ars--context.jsonld
tags:
- Federal Government
- Agriculture
- Food Safety
- Nutrition
- Open Data
- Research
- JSON-LD
- Linked Data
- Semantic Web
---
