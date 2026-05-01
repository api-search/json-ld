---
api_specs:
- filename: bjs-ncvs-api-openapi.yml
  format: yaml
  label: BJS NCVS API
  slug: ncvs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/openapi/bjs-ncvs-api-openapi.yml
- filename: bjs-nibrs-api-openapi.yml
  format: yaml
  label: BJS NIBRS National Estimates API
  slug: nibrs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/openapi/bjs-nibrs-api-openapi.yml
class_count: 3
classes:
- Dataset
- Estimate
- Observation
context_file: json-ld/bjs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/json-ld/bjs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bjs from Bureau of Justice Statistics Data Analysis Tools.
layout: jsonld
name: Bjs Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bjs
  uri: https://schema.bjs.ojp.gov/
properties:
- container: ''
  name: year
  type: schema:Text
- container: ''
  name: estimate
  type: schema:Text
- container: ''
  name: standard_error
  type: schema:Text
- container: ''
  name: category
  type: schema:Text
- container: ''
  name: datasetId
  type: schema:Text
property_count: 5
provider_name: Bureau of Justice Statistics Data Analysis Tools
provider_slug: data-analysis-tools-bureau-of-justice-statistics
slug: bjs-context
source_filename: bjs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.bjs.ojp.gov/\",\n    \"schema\": \"https://schema.org/\",\n    \"bjs\": \"https://schema.bjs.ojp.gov/\",\n    \"Dataset\": \"schema:Dataset\",\n    \"Estimate\": \"bjs:Estimate\",\n    \"Observation\": \"schema:Observation\",\n    \"year\": {\"@id\": \"schema:temporalCoverage\", \"@type\": \"schema:Text\"},\n    \"estimate\": {\"@id\": \"schema:value\", \"@type\": \"schema:Text\"},\n    \"standard_error\": {\"@id\": \"bjs:standardError\", \"@type\": \"schema:Text\"},\n    \"category\": {\"@id\": \"schema:category\", \"@type\": \"schema:Text\"},\n    \"datasetId\": {\"@id\": \"schema:identifier\", \"@type\": \"schema:Text\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/data-analysis-tools-bureau-of-justice-statistics/refs/heads/main/json-ld/bjs-context.jsonld
tags:
- Crime Statistics
- Federal Government
- NCVS
- NIBRS
- Open Data
- SODA
- Statistics
- Victimization
- JSON-LD
- Linked Data
- Semantic Web
---
