---
api_specs:
- filename: google-cloud-functions-openapi.yml
  format: yaml
  label: Google Cloud Functions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-functions/refs/heads/main/openapi/google-cloud-functions-openapi.yml
class_count: 8
classes:
- Function
- name
- description
- state
- url
- updateTime
- labels
- environment
context_file: json-ld/google-cloud-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-functions/refs/heads/main/json-ld/google-cloud-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Functions from Google Cloud Functions.
layout: jsonld
name: Google Cloud Functions Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/functions/docs/reference/rest/v2/projects.locations.functions#
properties:
- container: ''
  name: buildConfig
  type: ''
- container: ''
  name: serviceConfig
  type: ''
- container: ''
  name: eventTrigger
  type: ''
property_count: 3
provider_name: Google Cloud Functions
provider_slug: google-cloud-functions
slug: google-cloud-functions-context
source_filename: google-cloud-functions-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/functions/docs/reference/rest/v2/projects.locations.functions#\",\n    \"Function\": \"gcloud:Function\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"state\": \"schema:status\",\n    \"url\": \"schema:url\",\n    \"updateTime\": \"schema:dateModified\",\n    \"labels\": \"schema:keywords\",\n    \"environment\": \"schema:additionalType\",\n    \"buildConfig\": {\n      \"@id\": \"schema:SoftwareSourceCode\",\n      \"@context\": {\n        \"runtime\": \"schema:runtimePlatform\",\n        \"entryPoint\": \"schema:name\",\n        \"source\": \"schema:codeRepository\",\n        \"dockerRepository\": \"schema:url\"\n      }\n    },\n    \"serviceConfig\": {\n      \"@id\": \"schema:WebAPI\",\n      \"@context\": {\n        \"uri\": \"schema:url\",\n        \"timeoutSeconds\": \"schema:duration\",\n        \"availableMemory\": \"schema:memoryRequirements\"\
  ,\n        \"serviceAccountEmail\": \"schema:email\"\n      }\n    },\n    \"eventTrigger\": {\n      \"@id\": \"schema:Action\",\n      \"@context\": {\n        \"eventType\": \"schema:additionalType\",\n        \"pubsubTopic\": \"schema:name\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-functions/refs/heads/main/json-ld/google-cloud-functions-context.jsonld
tags:
- Event-Driven
- Functions
- Google Cloud
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
