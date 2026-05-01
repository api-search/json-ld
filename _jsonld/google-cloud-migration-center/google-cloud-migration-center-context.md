---
api_specs:
- filename: migration-center-api-openapi.yml
  format: yaml
  label: Migration Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-migration-center/refs/heads/main/openapi/migration-center-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-migration-center-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-migration-center/refs/heads/main/json-ld/google-cloud-migration-center-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Migration Center from Google Cloud Migration Center.
layout: jsonld
name: Google Cloud Migration Center Context
namespaces:
- prefix: mc
  uri: https://cloud.google.com/migration-center/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: ImportJob
  type: ''
- container: ''
  name: PreferenceSet
  type: ''
property_count: 4
provider_name: Google Cloud Migration Center
provider_slug: google-cloud-migration-center
slug: google-cloud-migration-center-context
source_filename: google-cloud-migration-center-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mc\": \"https://cloud.google.com/migration-center/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Asset\": {\n      \"@id\": \"mc:Asset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"machineName\": \"mc:machineName\",\n        \"platform\": \"mc:platform\",\n        \"coreCount\": \"mc:coreCount\",\n        \"memoryMb\": \"mc:memoryMb\",\n        \"totalDiskSizeGb\": \"mc:totalDiskSizeGb\",\n        \"labels\": \"mc:labels\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Group\": {\n      \"@id\": \"mc:Group\",\n      \"@context\"\
  : {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"labels\": \"mc:labels\"\n      }\n    },\n\n    \"ImportJob\": {\n      \"@id\": \"mc:ImportJob\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"state\": \"mc:jobState\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updateTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PreferenceSet\": {\n      \"@id\": \"mc:PreferenceSet\",\n      \"@context\": {\n        \"displayName\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"targetProduct\"\
  : \"mc:targetProduct\",\n        \"commitmentPlan\": \"mc:commitmentPlan\",\n        \"createTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-migration-center/refs/heads/main/json-ld/google-cloud-migration-center-context.jsonld
tags:
- Assessment
- Cloud Migration
- Discovery
- Infrastructure
- Migration
- Planning
- JSON-LD
- Linked Data
- Semantic Web
---
