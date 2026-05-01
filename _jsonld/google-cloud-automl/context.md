---
api_specs:
- filename: openapi.yml
  format: yaml
  label: Google Cloud AutoML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-automl/refs/heads/main/openapi/openapi.yml
class_count: 12
classes:
- AutoMLModel
- dataset
- model
- displayName
- datasetId
- deploymentState
- payload
- prediction
- score
- name
- description
- url
context_file: json-ld/context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-automl/refs/heads/main/json-ld/context.jsonld
description: JSON-LD context defining the semantic vocabulary for context from Google Cloud AutoML.
layout: jsonld
name: context Context
namespaces:
- prefix: gcp
  uri: https://cloud.google.com/automl#
properties: []
property_count: 0
provider_name: Google Cloud AutoML
provider_slug: google-cloud-automl
slug: context
source_filename: context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcp\": \"https://cloud.google.com/automl#\",\n    \"AutoMLModel\": \"gcp:AutoMLModel\",\n    \"dataset\": \"gcp:dataset\",\n    \"model\": \"gcp:model\",\n    \"displayName\": \"gcp:displayName\",\n    \"datasetId\": \"gcp:datasetId\",\n    \"deploymentState\": \"gcp:deploymentState\",\n    \"payload\": \"gcp:payload\",\n    \"prediction\": \"gcp:prediction\",\n    \"score\": \"gcp:score\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-automl/refs/heads/main/json-ld/context.jsonld
tags:
- AutoML
- Custom Models
- Google Cloud
- Machine Learning
- Training
- JSON-LD
- Linked Data
- Semantic Web
---
