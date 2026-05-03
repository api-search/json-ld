---
api_specs:
- filename: bls-public-data-api-openapi.yaml
  format: yaml
  label: BLS Public Data API
  slug: bls-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/openapi/bls-public-data-api-openapi.yaml
class_count: 13
classes:
- Calculations
- DataPoint
- Footnote
- MultipleSeriesRequest
- PeriodCalculations
- PopularSeriesResponse
- SeriesCatalog
- SeriesData
- SeriesResponse
- SeriesResults
- SurveyMetadataResponse
- Survey
- SurveysResponse
context_file: json-ld/bls-public-data-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-ld/bls-public-data-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Bls Public Data Api from U.S. Bureau of Labor Statistics.
layout: jsonld
name: Bls Public Data Api Context
namespaces:
- prefix: bls
  uri: https://api.bls.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: netChanges
  type: string
- container: ''
  name: pctChanges
  type: string
- container: ''
  name: year
  type: string
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
  type: string
- container: ''
  name: latest
  type: string
- container: ''
  name: calculations
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: text
  type: string
- container: set
  name: seriesid
  type: string
- container: ''
  name: startyear
  type: string
- container: ''
  name: endyear
  type: string
- container: ''
  name: registrationkey
  type: string
- container: ''
  name: catalog
  type: boolean
- container: ''
  name: annualaverage
  type: boolean
- container: ''
  name: aspects
  type: boolean
- container: ''
  name: status
  type: string
- container: ''
  name: responseTime
  type: integer
- container: set
  name: message
  type: string
- container: ''
  name: Results
  type: string
- container: set
  name: series
  type: string
- container: ''
  name: seriesID
  type: string
- container: ''
  name: seriesId
  type: string
- container: ''
  name: seasonality
  type: string
- container: ''
  name: seriesTitle
  type: string
- container: ''
  name: measureDataType
  type: string
- container: ''
  name: commerceIndustry
  type: string
- container: ''
  name: occupation
  type: string
- container: ''
  name: surveyName
  type: string
- container: ''
  name: surveyAbbreviation
  type: string
- container: set
  name: data
  type: string
- container: set
  name: survey
  type: string
- container: ''
  name: surveyTitle
  type: string
- container: ''
  name: surveyDescription
  type: string
property_count: 36
provider_name: U.S. Bureau of Labor Statistics
provider_slug: u-s-bureau-of-labor-statistics
slug: bls-public-data-api-context
source_filename: bls-public-data-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bls\": \"https://api.bls.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Calculations\": \"bls:Calculations\",\n    \"DataPoint\": \"bls:DataPoint\",\n    \"Footnote\": \"bls:Footnote\",\n    \"MultipleSeriesRequest\": \"bls:MultipleSeriesRequest\",\n    \"PeriodCalculations\": \"bls:PeriodCalculations\",\n    \"PopularSeriesResponse\": \"bls:PopularSeriesResponse\",\n    \"SeriesCatalog\": \"bls:SeriesCatalog\",\n    \"SeriesData\": \"bls:SeriesData\",\n    \"SeriesResponse\": \"bls:SeriesResponse\",\n    \"SeriesResults\": \"bls:SeriesResults\",\n    \"SurveyMetadataResponse\": \"bls:SurveyMetadataResponse\",\n    \"Survey\": \"bls:Survey\",\n    \"SurveysResponse\": \"bls:SurveysResponse\",\n    \"netChanges\": {\n      \"@id\": \"bls:net_changes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pctChanges\"\
  : {\n      \"@id\": \"bls:pct_changes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"bls:year\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"bls:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodName\": {\n      \"@id\": \"bls:periodName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"bls:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"footnotes\": {\n      \"@id\": \"bls:footnotes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latest\": {\n      \"@id\": \"bls:latest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"calculations\": {\n      \"@id\": \"bls:calculations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"bls:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"bls:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesid\": {\n      \"@id\": \"bls:seriesid\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startyear\": {\n      \"@id\": \"bls:startyear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endyear\": {\n      \"@id\": \"bls:endyear\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registrationkey\": {\n      \"@id\": \"bls:registrationkey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"catalog\": {\n      \"@id\": \"bls:catalog\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"annualaverage\": {\n      \"@id\": \"bls:annualaverage\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"aspects\": {\n      \"@id\": \"bls:aspects\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"status\": {\n      \"@id\": \"bls:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseTime\": {\n      \"@id\": \"bls:responseTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"message\": {\n      \"@id\": \"bls:message\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Results\": {\n      \"@id\": \"bls:Results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"series\": {\n      \"@id\": \"bls:series\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesID\": {\n      \"@id\": \"bls:seriesID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesId\": {\n      \"@id\": \"bls:series_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seasonality\": {\n      \"@id\": \"bls:seasonality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesTitle\": {\n      \"@id\": \"bls:series_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"measureDataType\": {\n      \"@id\": \"bls:measure_data_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commerceIndustry\": {\n      \"@id\": \"bls:commerce_industry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"occupation\": {\n      \"@id\": \"bls:occupation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyName\": {\n      \"@id\": \"bls:survey_name\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyAbbreviation\": {\n      \"@id\": \"bls:survey_abbreviation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"bls:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"survey\": {\n      \"@id\": \"bls:survey\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyTitle\": {\n      \"@id\": \"bls:survey_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"surveyDescription\": {\n      \"@id\": \"bls:survey_description\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-bureau-of-labor-statistics/refs/heads/main/json-ld/bls-public-data-api-context.jsonld
tags:
- Federal Government
- Labor
- Statistics
- Employment
- Economic Data
- JSON-LD
- Linked Data
- Semantic Web
---
