---
api_specs:
- filename: google-cloud-run-openapi.yml
  format: yaml
  label: Google Cloud Run Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-run/refs/heads/main/openapi/google-cloud-run-openapi.yml
class_count: 17
classes:
- Service
- Revision
- Job
- name
- description
- uid
- uri
- createTime
- updateTime
- deleteTime
- labels
- annotations
- ingress
- launchStage
- creator
- lastModifier
- latestReadyRevision
context_file: json-ld/google-cloud-run-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-run/refs/heads/main/json-ld/google-cloud-run-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Run from Google Cloud Run.
layout: jsonld
name: Google Cloud Run Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/run/docs/reference/rest/v2/projects.locations.services#
properties:
- container: ''
  name: template
  type: ''
- container: ''
  name: traffic
  type: ''
property_count: 2
provider_name: Google Cloud Run
provider_slug: google-cloud-run
slug: google-cloud-run-context
source_filename: google-cloud-run-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/run/docs/reference/rest/v2/projects.locations.services#\",\n    \"Service\": \"gcloud:Service\",\n    \"Revision\": \"gcloud:Revision\",\n    \"Job\": \"gcloud:Job\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"uid\": \"schema:identifier\",\n    \"uri\": \"schema:url\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"deleteTime\": \"schema:expires\",\n    \"labels\": \"schema:keywords\",\n    \"annotations\": \"schema:additionalProperty\",\n    \"ingress\": \"schema:accessMode\",\n    \"launchStage\": \"schema:creativeWorkStatus\",\n    \"creator\": \"schema:creator\",\n    \"lastModifier\": \"schema:editor\",\n    \"latestReadyRevision\": \"schema:version\",\n    \"template\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"serviceAccount\": \"\
  schema:email\",\n        \"timeout\": \"schema:duration\",\n        \"containers\": {\n          \"@id\": \"schema:SoftwareApplication\",\n          \"@context\": {\n            \"image\": \"schema:url\",\n            \"name\": \"schema:name\",\n            \"command\": \"schema:executableLibraryName\"\n          }\n        }\n      }\n    },\n    \"traffic\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"revision\": \"schema:version\",\n        \"percent\": \"schema:value\",\n        \"tag\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-run/refs/heads/main/json-ld/google-cloud-run-context.jsonld
tags:
- Cloud Run
- Containers
- Google Cloud
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
