---
api_specs:
- filename: zluri-api-openapi.yml
  format: yaml
  label: Zluri
  slug: zluri
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/openapi/zluri-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/zluri-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/json-ld/zluri-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zluri from Zluri.
layout: jsonld
name: Zluri Context
namespaces:
- prefix: zluri
  uri: https://api-ext.zluri.com/v2/
properties:
- container: ''
  name: Instance
  type: ''
- container: ''
  name: Sync
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: SnapshotDataUpload
  type: ''
- container: ''
  name: FactDataUpload
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: Contract
  type: ''
- container: ''
  name: Transaction
  type: ''
property_count: 9
provider_name: Zluri
provider_slug: zluri
slug: zluri-context
source_filename: zluri-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"zluri\": \"https://api-ext.zluri.com/v2/\",\n    \"Instance\": {\n      \"@id\": \"zluri:Instance\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"status\": \"schema:status\",\n        \"notification_emails\": \"schema:email\",\n        \"created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\"\n      }\n    },\n    \"Sync\": {\n      \"@id\": \"zluri:Sync\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"instance_id\": \"schema:isPartOf\",\n        \"status\": \"schema:status\",\n        \"created_at\": \"schema:dateCreated\",\n        \"finished_at\": \"schema:endDate\"\n      }\n    },\n    \"Webhook\": {\n      \"@id\": \"zluri:Webhook\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"url\": \"schema:url\",\n        \"events\": \"schema:about\",\n        \"status\": \"schema:status\",\n        \"\
  created_at\": \"schema:dateCreated\",\n        \"updated_at\": \"schema:dateModified\"\n      }\n    },\n    \"SnapshotDataUpload\": {\n      \"@id\": \"zluri:SnapshotDataUpload\",\n      \"@context\": {\n        \"entity\": \"schema:additionalType\",\n        \"page\": \"schema:position\",\n        \"data\": \"schema:dataset\"\n      }\n    },\n    \"FactDataUpload\": {\n      \"@id\": \"zluri:FactDataUpload\",\n      \"@context\": {\n        \"entity\": \"schema:additionalType\",\n        \"page\": \"schema:position\",\n        \"data\": \"schema:dataset\"\n      }\n    },\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"email\": \"schema:email\",\n        \"name\": \"schema:name\",\n        \"status\": \"schema:status\"\n      }\n    },\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"schema:status\"\n      }\n    },\n    \"Contract\": {\n   \
  \   \"@id\": \"schema:Service\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"status\": \"schema:status\"\n      }\n    },\n    \"Transaction\": {\n      \"@id\": \"schema:PayAction\",\n      \"@context\": {\n        \"amount\": \"schema:price\",\n        \"date\": \"schema:startTime\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zluri/refs/heads/main/json-ld/zluri-context.jsonld
tags:
- Access Management
- SaaS Management
- JSON-LD
- Linked Data
- Semantic Web
---
