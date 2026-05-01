---
api_specs:
- filename: storage-transfer-api-openapi.yml
  format: yaml
  label: Storage Transfer API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-cloud-transfer-service/refs/heads/main/openapi/storage-transfer-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/google-cloud-transfer-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-transfer-service/refs/heads/main/json-ld/google-cloud-transfer-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Cloud Transfer Service from Google Cloud Transfer Service.
layout: jsonld
name: Google Cloud Transfer Service Context
namespaces:
- prefix: sts
  uri: https://cloud.google.com/storage-transfer/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: TransferJob
  type: ''
- container: ''
  name: TransferOperation
  type: ''
- container: ''
  name: AgentPool
  type: ''
- container: ''
  name: GcsData
  type: ''
- container: ''
  name: AwsS3Data
  type: ''
property_count: 5
provider_name: Google Cloud Transfer Service
provider_slug: google-cloud-transfer-service
slug: google-cloud-transfer-service-context
source_filename: google-cloud-transfer-service-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sts\": \"https://cloud.google.com/storage-transfer/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"TransferJob\": {\n      \"@id\": \"sts:TransferJob\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"projectId\": \"sts:projectId\",\n        \"status\": \"sts:status\",\n        \"transferSpec\": \"sts:transferSpec\",\n        \"schedule\": \"sts:schedule\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModificationTime\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TransferOperation\": {\n      \"@id\": \"sts:TransferOperation\",\n      \"@context\": {\n        \"name\": \"schema:name\"\
  ,\n        \"projectId\": \"sts:projectId\",\n        \"status\": \"sts:operationStatus\",\n        \"startTime\": {\n          \"@id\": \"sts:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"sts:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"counters\": \"sts:transferCounters\"\n      }\n    },\n\n    \"AgentPool\": {\n      \"@id\": \"sts:AgentPool\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"displayName\": \"schema:alternateName\",\n        \"state\": \"sts:agentPoolState\",\n        \"bandwidthLimit\": \"sts:bandwidthLimit\"\n      }\n    },\n\n    \"GcsData\": {\n      \"@id\": \"sts:GcsData\",\n      \"@context\": {\n        \"bucketName\": \"sts:bucketName\",\n        \"path\": \"sts:path\"\n      }\n    },\n\n    \"AwsS3Data\": {\n      \"@id\": \"sts:AwsS3Data\",\n      \"@context\": {\n        \"bucketName\": \"sts:bucketName\",\n        \"path\": \"sts:path\",\n\
  \        \"roleArn\": \"sts:roleArn\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-cloud-transfer-service/refs/heads/main/json-ld/google-cloud-transfer-service-context.jsonld
tags:
- Azure
- Cloud Storage
- Data Transfer
- Migration
- S3
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
