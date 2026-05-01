---
api_specs:
- filename: batch-openapi.yml
  format: yaml
  label: Google Cloud Batch API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-batch/refs/heads/main/openapi/batch-openapi.yml
class_count: 9
classes:
- Job
- TaskGroup
- Task
- name
- description
- uid
- state
- priority
- machineType
context_file: json-ld/batch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-batch/refs/heads/main/json-ld/batch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Batch from Google Cloud Batch.
layout: jsonld
name: Batch Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: gcp
  uri: https://cloud.google.com/schema#
properties:
- container: ''
  name: taskCount
  type: string
- container: ''
  name: parallelism
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: updateTime
  type: dateTime
property_count: 4
provider_name: Google Cloud Batch
provider_slug: google-cloud-batch
slug: batch-context
source_filename: batch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://cloud.google.com/batch/schema#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"gcp\": \"https://cloud.google.com/schema#\",\n    \"Job\": \"gcp:BatchJob\",\n    \"TaskGroup\": \"gcp:BatchTaskGroup\",\n    \"Task\": \"gcp:BatchTask\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"uid\": \"schema:identifier\",\n    \"state\": \"gcp:state\",\n    \"priority\": \"gcp:priority\",\n    \"machineType\": \"gcp:machineType\",\n    \"taskCount\": {\n      \"@id\": \"gcp:taskCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parallelism\": {\n      \"@id\": \"gcp:parallelism\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"dcterms:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updateTime\": {\n      \"@id\": \"dcterms:modified\",\n      \"\
  @type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-batch/refs/heads/main/json-ld/batch-context.jsonld
tags:
- Batch Processing
- Compute
- Google Cloud
- HPC
- Jobs
- JSON-LD
- Linked Data
- Semantic Web
---
