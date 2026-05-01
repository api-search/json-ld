---
api_specs:
- filename: cloud-storage-openapi.yml
  format: yaml
  label: Cloud Storage JSON API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-storage/refs/heads/main/openapi/cloud-storage-openapi.yml
class_count: 19
classes:
- Bucket
- Object
- BucketAccessControl
- ObjectAccessControl
- name
- description
- dateCreated
- dateModified
- contentType
- contentSize
- location
- storageClass
- selfLink
- labels
- encryption
- versioning
- lifecycle
- project
- iamConfiguration
context_file: json-ld/google-cloud-storage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-storage/refs/heads/main/json-ld/google-cloud-storage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Storage from Google Cloud Storage.
layout: jsonld
name: Google Cloud Storage Context
namespaces:
- prefix: gcs
  uri: https://cloud.google.com/storage/docs/json_api/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Storage
provider_slug: google-cloud-storage
slug: google-cloud-storage-context
source_filename: google-cloud-storage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcs\": \"https://cloud.google.com/storage/docs/json_api/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Bucket\": \"gcs:buckets\",\n    \"Object\": \"gcs:objects\",\n    \"BucketAccessControl\": \"gcs:bucketAccessControls\",\n    \"ObjectAccessControl\": \"gcs:objectAccessControls\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"contentType\": \"schema:encodingFormat\",\n    \"contentSize\": \"schema:contentSize\",\n    \"location\": \"schema:location\",\n    \"storageClass\": \"gcs:storageClass\",\n    \"selfLink\": \"schema:url\",\n    \"labels\": \"schema:keywords\",\n    \"encryption\": \"gcs:encryption\",\n    \"versioning\": \"gcs:versioning\",\n    \"lifecycle\": \"gcs:lifecycle\",\n    \"project\": \"gcloud:project\",\n    \"iamConfiguration\": \"\
  gcs:iamConfiguration\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-storage/refs/heads/main/json-ld/google-cloud-storage-context.jsonld
tags:
- Buckets
- Cloud
- Google Cloud
- Objects
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
