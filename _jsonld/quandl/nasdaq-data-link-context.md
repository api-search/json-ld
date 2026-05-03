---
api_specs:
- filename: nasdaq-data-link-timeseries-openapi.yml
  format: yaml
  label: Nasdaq Data Link REST API (Time-Series)
  slug: nasdaq-data-link-timeseries-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/openapi/nasdaq-data-link-timeseries-openapi.yml
class_count: 0
classes: []
context_file: json-ld/nasdaq-data-link-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/json-ld/nasdaq-data-link-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nasdaq Data Link from Quandl (Nasdaq Data Link).
layout: jsonld
name: Nasdaq Data Link Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ndl
  uri: https://data.nasdaq.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcat
  uri: http://www.w3.org/ns/dcat#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Dataset
  type: reference
- container: ''
  name: id
  type: integer
- container: ''
  name: dataset_code
  type: ''
- container: ''
  name: database_code
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: refreshed_at
  type: dateTime
- container: ''
  name: newest_available_date
  type: date
- container: ''
  name: oldest_available_date
  type: date
- container: ''
  name: column_names
  type: ''
- container: ''
  name: frequency
  type: ''
- container: ''
  name: premium
  type: boolean
- container: ''
  name: Database
  type: reference
- container: ''
  name: database_code_catalog
  type: ''
- container: ''
  name: datasets_count
  type: integer
- container: ''
  name: DataPoint
  type: reference
- container: ''
  name: date
  type: date
- container: ''
  name: value
  type: decimal
- container: ''
  name: DatatableRow
  type: reference
property_count: 19
provider_name: Quandl (Nasdaq Data Link)
provider_slug: quandl
slug: nasdaq-data-link-context
source_filename: nasdaq-data-link-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ndl\": \"https://data.nasdaq.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcat\": \"http://www.w3.org/ns/dcat#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Dataset\": {\n      \"@id\": \"dcat:Dataset\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataset_code\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"database_code\": {\n      \"@id\": \"ndl:databaseCode\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"description\": {\n      \"@id\": \"dcterms:description\"\n    },\n    \"refreshed_at\": {\n      \"@id\": \"dcterms:modified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"newest_available_date\": {\n      \"@id\": \"dcterms:temporal\",\n      \"@type\": \"xsd:date\"\n    },\n    \"oldest_available_date\"\
  : {\n      \"@id\": \"dcat:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"column_names\": {\n      \"@id\": \"dcat:column\"\n    },\n    \"frequency\": {\n      \"@id\": \"dcterms:accrualPeriodicity\"\n    },\n    \"premium\": {\n      \"@id\": \"ndl:premium\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"Database\": {\n      \"@id\": \"dcat:Catalog\",\n      \"@type\": \"@id\"\n    },\n    \"database_code_catalog\": {\n      \"@id\": \"dcterms:identifier\"\n    },\n    \"datasets_count\": {\n      \"@id\": \"dcat:dataset\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"DataPoint\": {\n      \"@id\": \"schema:Observation\",\n      \"@type\": \"@id\"\n    },\n    \"date\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"DatatableRow\": {\n      \"@id\": \"schema:PropertyValue\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/quandl/refs/heads/main/json-ld/nasdaq-data-link-context.jsonld
tags:
- Finance
- Market Data
- Economic Data
- Time Series
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
