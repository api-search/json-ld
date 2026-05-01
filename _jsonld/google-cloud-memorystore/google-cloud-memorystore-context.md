---
api_specs:
- filename: cloud-memorystore-openapi.yml
  format: yaml
  label: Memorystore for Redis API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-memorystore/refs/heads/main/openapi/cloud-memorystore-openapi.yml
class_count: 18
classes:
- Instance
- Operation
- name
- displayName
- description
- state
- tier
- memorySizeGb
- redisVersion
- host
- port
- locationId
- labels
- createTime
- authorizedNetwork
- connectMode
- replicaCount
- project
context_file: json-ld/google-cloud-memorystore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-memorystore/refs/heads/main/json-ld/google-cloud-memorystore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Memorystore from Google Cloud Memorystore.
layout: jsonld
name: Google Cloud Memorystore Context
namespaces:
- prefix: redis
  uri: https://cloud.google.com/memorystore/docs/redis/reference/rest/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Memorystore
provider_slug: google-cloud-memorystore
slug: google-cloud-memorystore-context
source_filename: google-cloud-memorystore-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"redis\": \"https://cloud.google.com/memorystore/docs/redis/reference/rest/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Instance\": \"redis:projects.locations.instances\",\n    \"Operation\": \"redis:projects.locations.operations\",\n    \"name\": \"schema:name\",\n    \"displayName\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n    \"state\": \"redis:state\",\n    \"tier\": \"redis:tier\",\n    \"memorySizeGb\": \"redis:memorySizeGb\",\n    \"redisVersion\": \"redis:redisVersion\",\n    \"host\": \"schema:url\",\n    \"port\": \"redis:port\",\n    \"locationId\": \"schema:location\",\n    \"labels\": \"schema:keywords\",\n    \"createTime\": \"schema:dateCreated\",\n    \"authorizedNetwork\": \"redis:authorizedNetwork\",\n    \"connectMode\": \"redis:connectMode\",\n    \"replicaCount\": \"redis:replicaCount\",\n    \"project\": \"gcloud:project\"\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-memorystore/refs/heads/main/json-ld/google-cloud-memorystore-context.jsonld
tags:
- Cache
- Google Cloud
- In-Memory
- Memcached
- Redis
- JSON-LD
- Linked Data
- Semantic Web
---
