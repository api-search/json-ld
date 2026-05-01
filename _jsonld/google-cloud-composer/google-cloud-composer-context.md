---
api_specs:
- filename: google-cloud-composer-openapi.yml
  format: yaml
  label: Google Cloud Composer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-composer/refs/heads/main/openapi/google-cloud-composer-openapi.yml
class_count: 8
classes:
- Environment
- name
- description
- state
- uuid
- createTime
- updateTime
- labels
context_file: json-ld/google-cloud-composer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-composer/refs/heads/main/json-ld/google-cloud-composer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Composer from Google Cloud Composer.
layout: jsonld
name: Google Cloud Composer Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/composer/docs/reference/rest/v1/projects.locations.environments#
properties:
- container: ''
  name: config
  type: ''
property_count: 1
provider_name: Google Cloud Composer
provider_slug: google-cloud-composer
slug: google-cloud-composer-context
source_filename: google-cloud-composer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/composer/docs/reference/rest/v1/projects.locations.environments#\",\n    \"Environment\": \"gcloud:Environment\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": \"schema:status\",\n    \"uuid\": \"schema:identifier\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"labels\": \"schema:keywords\",\n    \"config\": {\n      \"@id\": \"schema:Configuration\",\n      \"@context\": {\n        \"gkeCluster\": \"schema:identifier\",\n        \"dagGcsPrefix\": \"schema:url\",\n        \"nodeCount\": \"schema:numberOfItems\",\n        \"airflowUri\": \"schema:url\",\n        \"environmentSize\": \"schema:size\",\n        \"softwareConfig\": {\n          \"@id\": \"schema:SoftwareApplication\",\n          \"@context\": {\n            \"imageVersion\": \"schema:softwareVersion\",\n   \
  \         \"pythonVersion\": \"schema:programmingLanguage\"\n          }\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-composer/refs/heads/main/json-ld/google-cloud-composer-context.jsonld
tags:
- Apache Airflow
- Data Pipelines
- Google Cloud
- Workflow Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
