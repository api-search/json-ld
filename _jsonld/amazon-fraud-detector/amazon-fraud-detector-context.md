---
api_specs:
- filename: amazon-fraud-detector-openapi.yml
  format: yaml
  label: Amazon Fraud Detector API
  slug: amazon-fraud-detector-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/openapi/amazon-fraud-detector-openapi.yml
class_count: 5
classes:
- Detector
- Model
- Rule
- EventType
- Tag
context_file: json-ld/amazon-fraud-detector-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/json-ld/amazon-fraud-detector-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Fraud Detector from Amazon Fraud Detector.
layout: jsonld
name: Amazon Fraud Detector Context
namespaces:
- prefix: fd
  uri: https://aws.amazon.com/fraud-detector/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: detectorId
  type: string
- container: ''
  name: modelId
  type: string
- container: ''
  name: modelType
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: outcomes
  type: ''
- container: ''
  name: eventTypeName
  type: string
- container: ''
  name: eventVariables
  type: ''
- container: ''
  name: labels
  type: ''
- container: ''
  name: arn
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: ''
  name: lastUpdatedTime
  type: dateTime
property_count: 12
provider_name: Amazon Fraud Detector
provider_slug: amazon-fraud-detector
slug: amazon-fraud-detector-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fd\": \"https://aws.amazon.com/fraud-detector/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Detector\": \"fd:Detector\",\n    \"Model\": \"fd:Model\",\n    \"Rule\": \"fd:Rule\",\n    \"EventType\": \"fd:EventType\",\n    \"Tag\": \"schema:PropertyValue\",\n    \"detectorId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelType\": {\n      \"@id\": \"fd:modelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expression\": {\n      \"@id\": \"fd:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outcomes\": {\n      \"@id\": \"fd:outcomes\"\n    },\n    \"eventTypeName\": {\n      \"@id\": \"fd:eventTypeName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"eventVariables\": {\n      \"@id\": \"fd:eventVariables\"\n    },\n    \"labels\": {\n      \"@id\": \"fd:labels\"\n    },\n    \"arn\": {\n      \"@id\": \"fd:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastUpdatedTime\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-fraud-detector/refs/heads/main/json-ld/amazon-fraud-detector-context.jsonld
tags:
- AWS
- Financial Services
- Fraud Detection
- Machine Learning
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
