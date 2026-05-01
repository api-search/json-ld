---
api_specs:
- filename: cloud-build-api-openapi.yml
  format: yaml
  label: Cloud Build API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-build/refs/heads/main/openapi/cloud-build-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-build-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-build/refs/heads/main/json-ld/google-cloud-build-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Build from Google Cloud Build.
layout: jsonld
name: Google Cloud Build Context
namespaces:
- prefix: cb
  uri: https://cloud.google.com/build/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Build
  type: ''
- container: ''
  name: BuildStep
  type: ''
- container: ''
  name: BuildTrigger
  type: ''
- container: ''
  name: WorkerPool
  type: ''
property_count: 4
provider_name: Google Cloud Build
provider_slug: google-cloud-build
slug: google-cloud-build-context
source_filename: google-cloud-build-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cb\": \"https://cloud.google.com/build/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Build\": {\n      \"@id\": \"cb:Build\",\n      \"@context\": {\n        \"id\": \"cb:buildId\",\n        \"projectId\": \"cb:projectId\",\n        \"status\": \"cb:buildStatus\",\n        \"source\": \"cb:source\",\n        \"steps\": \"cb:steps\",\n        \"images\": \"cb:images\",\n        \"timeout\": \"cb:timeout\",\n        \"substitutions\": \"cb:substitutions\",\n        \"tags\": \"cb:tags\",\n        \"logUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startTime\": {\n          \"@id\": \"cb:startTime\",\n          \"@type\": \"xsd:dateTime\"\n      \
  \  },\n        \"finishTime\": {\n          \"@id\": \"cb:finishTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"BuildStep\": {\n      \"@id\": \"cb:BuildStep\",\n      \"@context\": {\n        \"name\": \"cb:stepImage\",\n        \"args\": \"cb:args\",\n        \"dir\": \"cb:workingDir\",\n        \"id\": \"cb:stepId\",\n        \"waitFor\": \"cb:waitFor\",\n        \"entrypoint\": \"cb:entrypoint\",\n        \"env\": \"cb:env\"\n      }\n    },\n\n    \"BuildTrigger\": {\n      \"@id\": \"cb:BuildTrigger\",\n      \"@context\": {\n        \"id\": \"cb:triggerId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"disabled\": \"cb:disabled\",\n        \"filename\": \"cb:filename\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"WorkerPool\": {\n      \"@id\": \"cb:WorkerPool\",\n      \"@context\": {\n      \
  \  \"name\": \"cb:workerPoolName\",\n        \"displayName\": \"schema:name\",\n        \"state\": \"cb:workerPoolState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-build/refs/heads/main/json-ld/google-cloud-build-context.jsonld
tags:
- Build Automation
- CI/CD
- Container Build
- Continuous Delivery
- Continuous Integration
- DevOps
- JSON-LD
- Linked Data
- Semantic Web
---
