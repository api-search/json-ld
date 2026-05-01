---
api_specs:
- filename: cloud-firestore-openapi.yml
  format: yaml
  label: Cloud Firestore API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-firestore/refs/heads/main/openapi/cloud-firestore-openapi.yml
class_count: 18
classes:
- Document
- Database
- Index
- Collection
- name
- description
- fields
- createTime
- updateTime
- locationId
- type
- concurrencyMode
- stringValue
- integerValue
- booleanValue
- geoPointValue
- timestampValue
- project
context_file: json-ld/google-cloud-firestore-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-firestore/refs/heads/main/json-ld/google-cloud-firestore-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Firestore from Google Cloud Firestore.
layout: jsonld
name: Google Cloud Firestore Context
namespaces:
- prefix: firestore
  uri: https://cloud.google.com/firestore/docs/reference/rest/v1/
- prefix: gcloud
  uri: https://cloud.google.com/apis/
properties: []
property_count: 0
provider_name: Google Cloud Firestore
provider_slug: google-cloud-firestore
slug: google-cloud-firestore-context
source_filename: google-cloud-firestore-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"firestore\": \"https://cloud.google.com/firestore/docs/reference/rest/v1/\",\n    \"gcloud\": \"https://cloud.google.com/apis/\",\n    \"Document\": \"firestore:projects.databases.documents\",\n    \"Database\": \"firestore:projects.databases\",\n    \"Index\": \"firestore:projects.databases.collectionGroups.indexes\",\n    \"Collection\": \"firestore:collection\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"fields\": \"firestore:fields\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"locationId\": \"schema:location\",\n    \"type\": \"firestore:databaseType\",\n    \"concurrencyMode\": \"firestore:concurrencyMode\",\n    \"stringValue\": \"schema:Text\",\n    \"integerValue\": \"schema:Integer\",\n    \"booleanValue\": \"schema:Boolean\",\n    \"geoPointValue\": \"schema:GeoCoordinates\",\n    \"timestampValue\"\
  : \"schema:DateTime\",\n    \"project\": \"gcloud:project\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-firestore/refs/heads/main/json-ld/google-cloud-firestore-context.jsonld
tags:
- Database
- Documents
- Google Cloud
- NoSQL
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
