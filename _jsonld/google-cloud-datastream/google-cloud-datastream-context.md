---
api_specs:
- filename: google-cloud-datastream-openapi.yml
  format: yaml
  label: Google Cloud Datastream API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-datastream/refs/heads/main/openapi/google-cloud-datastream-openapi.yml
class_count: 13
classes:
- Stream
- ConnectionProfile
- name
- displayName
- description
- state
- createTime
- updateTime
- labels
- hostname
- port
- username
- database
context_file: json-ld/google-cloud-datastream-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-datastream/refs/heads/main/json-ld/google-cloud-datastream-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Datastream from Google Cloud Datastream.
layout: jsonld
name: Google Cloud Datastream Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/datastream/docs/reference/rest/v1/projects.locations.streams#
properties:
- container: ''
  name: sourceConfig
  type: ''
- container: ''
  name: destinationConfig
  type: ''
property_count: 2
provider_name: Google Cloud Datastream
provider_slug: google-cloud-datastream
slug: google-cloud-datastream-context
source_filename: google-cloud-datastream-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/datastream/docs/reference/rest/v1/projects.locations.streams#\",\n    \"Stream\": \"gcloud:Stream\",\n    \"ConnectionProfile\": \"gcloud:ConnectionProfile\",\n    \"name\": \"schema:name\",\n    \"displayName\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n    \"state\": \"schema:status\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"labels\": \"schema:keywords\",\n    \"sourceConfig\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"sourceConnectionProfile\": \"schema:url\"\n      }\n    },\n    \"destinationConfig\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"destinationConnectionProfile\": \"schema:url\"\n      }\n    },\n    \"hostname\": \"schema:url\",\n    \"port\": \"schema:identifier\",\n    \"username\": \"schema:name\",\n \
  \   \"database\": \"schema:name\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-datastream/refs/heads/main/json-ld/google-cloud-datastream-context.jsonld
tags:
- Change Data Capture
- Data Replication
- Google Cloud
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
