---
api_specs:
- filename: cloud-spanner-openapi.yml
  format: yaml
  label: Cloud Spanner API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-spanner/refs/heads/main/openapi/cloud-spanner-openapi.yml
class_count: 16
classes:
- Instance
- Database
- Session
- Backup
- name
- displayName
- description
- state
- config
- nodeCount
- processingUnits
- labels
- createTime
- updateTime
- databaseDialect
- project
context_file: json-ld/google-cloud-spanner-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-spanner/refs/heads/main/json-ld/google-cloud-spanner-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Spanner from Google Cloud Spanner.
layout: jsonld
name: Google Cloud Spanner Context
namespaces:
- prefix: spanner
  uri: https://cloud.google.com/spanner/docs/reference/rest/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Spanner
provider_slug: google-cloud-spanner
slug: google-cloud-spanner-context
source_filename: google-cloud-spanner-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spanner\": \"https://cloud.google.com/spanner/docs/reference/rest/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Instance\": \"spanner:projects.instances\",\n    \"Database\": \"spanner:projects.instances.databases\",\n    \"Session\": \"spanner:projects.instances.databases.sessions\",\n    \"Backup\": \"spanner:projects.instances.backups\",\n    \"name\": \"schema:name\",\n    \"displayName\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n    \"state\": \"spanner:state\",\n    \"config\": \"spanner:instanceConfig\",\n    \"nodeCount\": \"spanner:nodeCount\",\n    \"processingUnits\": \"spanner:processingUnits\",\n    \"labels\": \"schema:keywords\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"databaseDialect\": \"spanner:databaseDialect\",\n    \"project\": \"gcloud:project\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-spanner/refs/heads/main/json-ld/google-cloud-spanner-context.jsonld
tags:
- Database
- Distributed
- Google Cloud
- Relational
- SQL
- JSON-LD
- Linked Data
- Semantic Web
---
