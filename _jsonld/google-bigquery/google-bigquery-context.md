---
api_specs:
- filename: bigquery-api-openapi.yml
  format: yaml
  label: BigQuery API
  slug: bigquery
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/openapi/bigquery-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-bigquery-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/json-ld/google-bigquery-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Bigquery from Google BigQuery.
layout: jsonld
name: Google Bigquery Context
namespaces:
- prefix: bq
  uri: https://cloud.google.com/bigquery/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: Table
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Model
  type: ''
- container: ''
  name: Routine
  type: ''
property_count: 5
provider_name: Google BigQuery
provider_slug: google-bigquery
slug: google-bigquery-context
source_filename: google-bigquery-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bq\": \"https://cloud.google.com/bigquery/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Dataset\": {\n      \"@id\": \"bq:Dataset\",\n      \"@context\": {\n        \"datasetId\": \"bq:datasetId\",\n        \"projectId\": \"bq:projectId\",\n        \"friendlyName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"location\": \"schema:location\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"bq:labels\",\n        \"selfLink\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Table\": {\n      \"@id\": \"bq:Table\"\
  ,\n      \"@context\": {\n        \"tableId\": \"bq:tableId\",\n        \"datasetId\": \"bq:datasetId\",\n        \"projectId\": \"bq:projectId\",\n        \"friendlyName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"type\": \"bq:tableType\",\n        \"numRows\": \"bq:numRows\",\n        \"numBytes\": \"bq:numBytes\",\n        \"schema\": \"bq:tableSchema\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"expirationTime\": {\n          \"@id\": \"bq:expirationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"bq:labels\"\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"bq:Job\",\n      \"@context\": {\n        \"jobId\": \"bq:jobId\",\n        \"projectId\": \"bq:projectId\",\n        \"location\": \"schema:location\",\n        \"state\": \"bq:jobState\",\n        \"configuration\": \"bq:jobConfiguration\",\n        \"status\": \"bq:jobStatus\"\
  ,\n        \"statistics\": \"bq:jobStatistics\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Model\": {\n      \"@id\": \"bq:Model\",\n      \"@context\": {\n        \"modelId\": \"bq:modelId\",\n        \"datasetId\": \"bq:datasetId\",\n        \"projectId\": \"bq:projectId\",\n        \"modelType\": \"bq:modelType\",\n        \"friendlyName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"labels\": \"bq:labels\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Routine\": {\n      \"@id\": \"bq:Routine\",\n      \"@context\": {\n        \"routineId\": \"bq:routineId\",\n        \"datasetId\": \"bq:datasetId\",\n        \"projectId\": \"bq:projectId\",\n        \"routineType\": \"bq:routineType\",\n        \"language\": \"schema:programmingLanguage\",\n    \
  \    \"description\": \"schema:description\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-bigquery/refs/heads/main/json-ld/google-bigquery-context.jsonld
tags:
- Analytics
- Big Data
- Cloud
- Data Warehouse
- Serverless
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
