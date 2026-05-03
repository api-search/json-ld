---
api_specs:
- filename: bls-public-data-api-openapi.yml
  format: yaml
  label: BLS Public Data API
  slug: bls-public-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yml
class_count: 3
classes:
- Dataset
- Distribution
- GovernmentOrganization
context_file: json-ld/us-bureau-of-labor-statistics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/json-ld/us-bureau-of-labor-statistics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Us Bureau Of Labor Statistics from US Bureau of Labor Statistics.
layout: jsonld
name: Us Bureau Of Labor Statistics Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: bls
  uri: https://www.bls.gov/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcat
  uri: https://www.w3.org/ns/dcat#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: BLSTimeSeries
  type: reference
- container: ''
  name: BLSSurvey
  type: reference
- container: ''
  name: BLSDataPoint
  type: reference
- container: ''
  name: seriesID
  type: string
- container: ''
  name: seriesTitle
  type: string
- container: ''
  name: surveyName
  type: string
- container: ''
  name: surveyAbbreviation
  type: string
- container: ''
  name: seasonality
  type: string
- container: ''
  name: measureDataType
  type: string
- container: ''
  name: area
  type: string
- container: ''
  name: year
  type: gYear
- container: ''
  name: period
  type: string
- container: ''
  name: periodName
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: footnotes
  type: ''
- container: ''
  name: footnoteCode
  type: string
- container: ''
  name: footnoteText
  type: string
- container: ''
  name: calculations
  type: ''
- container: ''
  name: netChanges
  type: ''
- container: ''
  name: pctChanges
  type: ''
- container: ''
  name: beginYear
  type: gYear
- container: ''
  name: endYear
  type: gYear
- container: ''
  name: status
  type: string
- container: ''
  name: responseTime
  type: integer
- container: ''
  name: Results
  type: ''
- container: ''
  name: publisher
  type: reference
- container: ''
  name: description
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: issued
  type: date
- container: ''
  name: modified
  type: date
property_count: 30
provider_name: US Bureau of Labor Statistics
provider_slug: us-bureau-of-labor-statistics
slug: us-bureau-of-labor-statistics-context
source_filename: us-bureau-of-labor-statistics-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"bls\": \"https://www.bls.gov/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcat\": \"https://www.w3.org/ns/dcat#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"BLSTimeSeries\": {\n      \"@id\": \"bls:data/TimeSeries\",\n      \"@type\": \"@id\"\n    },\n    \"BLSSurvey\": {\n      \"@id\": \"bls:survey/Survey\",\n      \"@type\": \"@id\"\n    },\n    \"BLSDataPoint\": {\n      \"@id\": \"bls:data/DataPoint\",\n      \"@type\": \"@id\"\n    },\n\n    \"seriesID\": {\n      \"@id\": \"bls:data/seriesID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesTitle\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyName\": {\n      \"@id\": \"bls:survey/surveyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyAbbreviation\": {\n      \"@id\": \"bls:survey/abbreviation\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"seasonality\": {\n      \"@id\": \"bls:data/seasonallyAdjusted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"measureDataType\": {\n      \"@id\": \"bls:data/measureType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"area\": {\n      \"@id\": \"schema:areaServed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"schema:temporalCoverage\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"period\": {\n      \"@id\": \"bls:data/period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodName\": {\n      \"@id\": \"bls:data/periodName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footnotes\": {\n      \"@id\": \"bls:data/footnotes\",\n      \"@container\": \"@set\"\n    },\n    \"footnoteCode\": {\n      \"@id\": \"bls:data/footnoteCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footnoteText\": {\n      \"@id\": \"bls:data/footnoteText\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"calculations\": {\n      \"@id\": \"bls:data/calculations\"\n    },\n    \"netChanges\": {\n      \"@id\": \"bls:data/netChanges\"\n    },\n    \"pctChanges\": {\n      \"@id\": \"bls:data/percentChanges\"\n    },\n    \"beginYear\": {\n      \"@id\": \"dcat:startDate\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"endYear\": {\n      \"@id\": \"dcat:endDate\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"status\": {\n      \"@id\": \"bls:api/status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseTime\": {\n      \"@id\": \"bls:api/responseTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Results\": {\n      \"@id\": \"bls:api/Results\"\n    },\n\n    \"Dataset\": \"dcat:Dataset\",\n    \"Distribution\": \"dcat:Distribution\",\n    \"GovernmentOrganization\": \"schema:GovernmentOrganization\",\n    \"publisher\": {\n      \"@id\": \"dct:publisher\",\n      \"@type\": \"@id\"\n    },\n    \"description\": {\n      \"\
  @id\": \"dct:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"dct:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issued\": {\n      \"@id\": \"dct:issued\",\n      \"@type\": \"xsd:date\"\n    },\n    \"modified\": {\n      \"@id\": \"dct:modified\",\n      \"@type\": \"xsd:date\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/us-bureau-of-labor-statistics/refs/heads/main/json-ld/us-bureau-of-labor-statistics-context.jsonld
tags:
- Federal Government
- Labor Statistics
- Economic Data
- Open Data
- JSON-LD
- Linked Data
- Semantic Web
---
