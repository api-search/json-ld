---
class_count: 0
classes: []
context_file: json-ld/department-of-housing-and-urban-development-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/department-of-housing-and-urban-development/refs/heads/main/json-ld/department-of-housing-and-urban-development-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Department Of Housing And Urban Development from Department of Housing and Urban Development.
layout: jsonld
name: Department Of Housing And Urban Development Context
namespaces:
- prefix: hud
  uri: https://www.huduser.gov/
properties:
- container: ''
  name: FairMarketRent
  type: ''
- container: ''
  name: IncomeLimit
  type: ''
- container: ''
  name: MortgageLimit
  type: ''
- container: ''
  name: GeographicBoundary
  type: ''
- container: ''
  name: Dataset
  type: ''
property_count: 5
provider_name: Department of Housing and Urban Development
provider_slug: department-of-housing-and-urban-development
slug: department-of-housing-and-urban-development-context
source_filename: department-of-housing-and-urban-development-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"hud\": \"https://www.huduser.gov/\",\n    \"FairMarketRent\": {\n      \"@id\": \"hud:portal/datasets/fmr.html\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"geography\": \"https://schema.org/areaServed\",\n        \"efficiency\": \"https://schema.org/value\",\n        \"oneBedroom\": \"https://schema.org/value\",\n        \"twoBedroom\": \"https://schema.org/value\",\n        \"threeBedroom\": \"https://schema.org/value\",\n        \"fourBedroom\": \"https://schema.org/value\"\n      }\n    },\n    \"IncomeLimit\": {\n      \"@id\": \"hud:portal/datasets/il.html\",\n      \"@context\": {\n        \"year\": \"https://schema.org/datePublished\",\n        \"geography\": \"https://schema.org/areaServed\",\n        \"medianFamilyIncome\": \"https://schema.org/value\",\n        \"low\": \"https://schema.org/lowPrice\",\n        \"veryLow\": \"https://schema.org/lowPrice\"\
  ,\n        \"extremelyLow\": \"https://schema.org/lowPrice\"\n      }\n    },\n    \"MortgageLimit\": {\n      \"@id\": \"https://entp.hud.gov/idapp/html/hicostlook.cfm\",\n      \"@context\": {\n        \"state\": \"https://schema.org/addressRegion\",\n        \"county\": \"https://schema.org/addressLocality\",\n        \"msa\": \"https://schema.org/areaServed\",\n        \"fhaLimit\": \"https://schema.org/price\",\n        \"gseLimit\": \"https://schema.org/price\",\n        \"medianSalePrice\": \"https://schema.org/price\"\n      }\n    },\n    \"GeographicBoundary\": {\n      \"@id\": \"hud:hudgis\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"type\": \"https://schema.org/category\",\n        \"geometry\": \"https://schema.org/geo\"\n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"https://schema.org/Dataset\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"title\": \"https://schema.org/name\",\n    \
  \    \"description\": \"https://schema.org/description\",\n        \"publisher\": \"https://schema.org/publisher\",\n        \"license\": \"https://schema.org/license\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/department-of-housing-and-urban-development/refs/heads/main/json-ld/department-of-housing-and-urban-development-context.jsonld
tags:
- Affordable Housing
- Fair Market Rents
- Federal Government
- FHA
- GIS
- Housing
- HUD
- Income Limits
- Mortgage
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
