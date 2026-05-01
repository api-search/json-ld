---
api_specs:
- filename: google-cloud-pubsub-openapi.yml
  format: yaml
  label: Google Cloud Pub/Sub API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-pubsub/refs/heads/main/openapi/google-cloud-pubsub-openapi.yml
class_count: 15
classes:
- Topic
- Subscription
- PubsubMessage
- name
- labels
- data
- messageId
- publishTime
- orderingKey
- topic
- pushEndpoint
- ackDeadlineSeconds
- filter
- messageRetentionDuration
- kmsKeyName
context_file: json-ld/google-cloud-pubsub-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-pubsub/refs/heads/main/json-ld/google-cloud-pubsub-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Pubsub from Google Cloud Pub/Sub.
layout: jsonld
name: Google Cloud Pubsub Context
namespaces:
- prefix: gcloud
  uri: https://cloud.google.com/pubsub/docs/reference/rest/v1/projects.topics#
properties:
- container: ''
  name: schemaSettings
  type: ''
property_count: 1
provider_name: Google Cloud Pub/Sub
provider_slug: google-cloud-pubsub
slug: google-cloud-pubsub-context
source_filename: google-cloud-pubsub-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"gcloud\": \"https://cloud.google.com/pubsub/docs/reference/rest/v1/projects.topics#\",\n    \"Topic\": \"gcloud:Topic\",\n    \"Subscription\": \"gcloud:Subscription\",\n    \"PubsubMessage\": \"gcloud:PubsubMessage\",\n    \"name\": \"schema:name\",\n    \"labels\": \"schema:keywords\",\n    \"data\": \"schema:text\",\n    \"messageId\": \"schema:identifier\",\n    \"publishTime\": \"schema:datePublished\",\n    \"orderingKey\": \"schema:position\",\n    \"topic\": \"schema:isPartOf\",\n    \"pushEndpoint\": \"schema:url\",\n    \"ackDeadlineSeconds\": \"schema:duration\",\n    \"filter\": \"schema:query\",\n    \"messageRetentionDuration\": \"schema:duration\",\n    \"kmsKeyName\": \"schema:identifier\",\n    \"schemaSettings\": {\n      \"@id\": \"schema:DataFeed\",\n      \"@context\": {\n        \"schema\": \"schema:name\",\n        \"encoding\": \"schema:encodingFormat\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-pubsub/refs/heads/main/json-ld/google-cloud-pubsub-context.jsonld
tags:
- Event-Driven
- Google Cloud
- Messaging
- Pub/Sub
- JSON-LD
- Linked Data
- Semantic Web
---
