---
api_specs:
- filename: google-cloud-data-fusion-openapi.yml
  format: yaml
  label: Google Cloud Data Fusion API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-fusion/refs/heads/main/openapi/google-cloud-data-fusion-openapi.yml
class_count: 14
classes:
- Instance
- name
- description
- displayName
- type
- state
- version
- createTime
- updateTime
- serviceEndpoint
- apiEndpoint
- zone
- labels
- privateInstance
context_file: json-ld/google-cloud-data-fusion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-fusion/refs/heads/main/json-ld/google-cloud-data-fusion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Data Fusion from Google Cloud Data Fusion.
layout: jsonld
name: Google Cloud Data Fusion Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/data-fusion/docs/reference/rest/v1/projects.locations.instances#
properties:
- container: ''
  name: networkConfig
  type: ''
property_count: 1
provider_name: Google Cloud Data Fusion
provider_slug: google-cloud-data-fusion
slug: google-cloud-data-fusion-context
source_filename: google-cloud-data-fusion-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/data-fusion/docs/reference/rest/v1/projects.locations.instances#\",\n    \"Instance\": \"gcloud:Instance\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"displayName\": \"schema:alternateName\",\n    \"type\": \"schema:additionalType\",\n    \"state\": \"schema:status\",\n    \"version\": \"schema:softwareVersion\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"serviceEndpoint\": \"schema:url\",\n    \"apiEndpoint\": \"schema:EntryPoint\",\n    \"zone\": \"schema:locationCreated\",\n    \"labels\": \"schema:keywords\",\n    \"privateInstance\": \"schema:isAccessibleForFree\",\n    \"networkConfig\": {\n      \"@id\": \"schema:NetworkConfiguration\",\n      \"@context\": {\n        \"network\": \"schema:name\",\n        \"ipAllocation\": \"schema:identifier\"\n      }\n    }\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-data-fusion/refs/heads/main/json-ld/google-cloud-data-fusion-context.jsonld
tags:
- Data Integration
- Data Pipelines
- ETL
- Google Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
