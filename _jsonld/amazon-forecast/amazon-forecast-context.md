---
api_specs:
- filename: amazon-forecast-openapi.yml
  format: yaml
  label: Amazon Forecast API
  slug: amazon-forecast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/openapi/amazon-forecast-openapi.yml
class_count: 5
classes:
- Dataset
- Predictor
- Forecast
- DatasetGroup
- Tag
context_file: json-ld/amazon-forecast-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/json-ld/amazon-forecast-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Forecast from Amazon Forecast.
layout: jsonld
name: Amazon Forecast Context
namespaces:
- prefix: forecast
  uri: https://aws.amazon.com/forecast/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: DatasetArn
  type: string
- container: ''
  name: DatasetName
  type: string
- container: ''
  name: Domain
  type: string
- container: ''
  name: DatasetType
  type: string
- container: ''
  name: DataFrequency
  type: string
- container: ''
  name: PredictorArn
  type: string
- container: ''
  name: PredictorName
  type: string
- container: ''
  name: ForecastHorizon
  type: integer
- container: ''
  name: ForecastArn
  type: string
- container: ''
  name: ForecastName
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: CreationTime
  type: dateTime
- container: ''
  name: LastModificationTime
  type: dateTime
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
property_count: 15
provider_name: Amazon Forecast
provider_slug: amazon-forecast
slug: amazon-forecast-context
source_filename: amazon-forecast-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"forecast\": \"https://aws.amazon.com/forecast/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Dataset\": \"forecast:Dataset\",\n    \"Predictor\": \"forecast:Predictor\",\n    \"Forecast\": \"forecast:Forecast\",\n    \"DatasetGroup\": \"forecast:DatasetGroup\",\n    \"Tag\": \"schema:PropertyValue\",\n    \"DatasetArn\": {\n      \"@id\": \"forecast:datasetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Domain\": {\n      \"@id\": \"forecast:domain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetType\": {\n      \"@id\": \"forecast:datasetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataFrequency\": {\n      \"@id\": \"forecast:dataFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredictorArn\": {\n      \"@id\": \"forecast:predictorArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"PredictorName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForecastHorizon\": {\n      \"@id\": \"forecast:forecastHorizon\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ForecastArn\": {\n      \"@id\": \"forecast:forecastArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForecastName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"forecast:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModificationTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Key\": {\n      \"@id\": \"schema:propertyID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"schema:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-forecast/refs/heads/main/json-ld/amazon-forecast-context.jsonld
tags:
- AWS
- Forecasting
- Machine Learning
- Predictive Analytics
- Time Series
- JSON-LD
- Linked Data
- Semantic Web
---
