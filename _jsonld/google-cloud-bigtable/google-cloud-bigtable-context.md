---
api_specs:
- filename: cloud-bigtable-openapi.yml
  format: yaml
  label: Cloud Bigtable Admin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-bigtable/refs/heads/main/openapi/cloud-bigtable-openapi.yml
class_count: 16
classes:
- Instance
- Cluster
- Table
- ColumnFamily
- Backup
- name
- displayName
- description
- state
- type
- labels
- createTime
- location
- serveNodes
- defaultStorageType
- project
context_file: json-ld/google-cloud-bigtable-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-bigtable/refs/heads/main/json-ld/google-cloud-bigtable-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Bigtable from Google Cloud Bigtable.
layout: jsonld
name: Google Cloud Bigtable Context
namespaces:
- prefix: bigtable
  uri: https://cloud.google.com/bigtable/docs/reference/admin/rest/v2/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Bigtable
provider_slug: google-cloud-bigtable
slug: google-cloud-bigtable-context
source_filename: google-cloud-bigtable-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bigtable\": \"https://cloud.google.com/bigtable/docs/reference/admin/rest/v2/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Instance\": \"bigtable:projects.instances\",\n    \"Cluster\": \"bigtable:projects.instances.clusters\",\n    \"Table\": \"bigtable:projects.instances.tables\",\n    \"ColumnFamily\": \"bigtable:columnFamilies\",\n    \"Backup\": \"bigtable:projects.instances.clusters.backups\",\n    \"name\": \"schema:name\",\n    \"displayName\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n    \"state\": \"bigtable:state\",\n    \"type\": \"bigtable:instanceType\",\n    \"labels\": \"schema:keywords\",\n    \"createTime\": \"schema:dateCreated\",\n    \"location\": \"schema:location\",\n    \"serveNodes\": \"bigtable:serveNodes\",\n    \"defaultStorageType\": \"bigtable:defaultStorageType\",\n    \"project\": \"gcloud:project\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-bigtable/refs/heads/main/json-ld/google-cloud-bigtable-context.jsonld
tags:
- Bigtable
- Database
- Google Cloud
- NoSQL
- Wide Column
- JSON-LD
- Linked Data
- Semantic Web
---
