---
class_count: 0
classes: []
context_file: json-ld/cloud-storage-and-data-acquisition-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage-and-data-acquisition/refs/heads/main/json-ld/cloud-storage-and-data-acquisition-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloud Storage And Data Acquisition from Cloud Storage and Data Acquisition.
layout: jsonld
name: Cloud Storage And Data Acquisition Context
namespaces:
- prefix: csda
  uri: https://apievangelist.com/topics/cloud-storage-and-data-acquisition/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: DataSource
  type: ''
- container: ''
  name: IngestionJob
  type: ''
- container: ''
  name: StorageBucket
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: TransferTask
  type: ''
property_count: 5
provider_name: Cloud Storage and Data Acquisition
provider_slug: cloud-storage-and-data-acquisition
slug: cloud-storage-and-data-acquisition-context
source_filename: cloud-storage-and-data-acquisition-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"csda\": \"https://apievangelist.com/topics/cloud-storage-and-data-acquisition/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"DataSource\": {\n      \"@id\": \"csda:DataSource\",\n      \"@context\": {\n        \"id\": \"csda:id\",\n        \"name\": \"schema:name\",\n        \"type\": \"csda:source_type\",\n        \"owner\": \"schema:provider\",\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"IngestionJob\": {\n      \"@id\": \"csda:IngestionJob\",\n      \"@context\": {\n        \"id\": \"csda:id\",\n        \"source\": \"csda:source\",\n        \"destination\": \"csda:destination\",\n        \"schedule\": \"schema:schedule\",\n        \"status\": \"csda:status\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n    \
  \      \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"StorageBucket\": {\n      \"@id\": \"csda:StorageBucket\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"provider\": \"schema:provider\",\n        \"region\": \"csda:region\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Dataset\": {\n      \"@id\": \"csda:Dataset\",\n      \"@context\": {\n        \"id\": \"csda:id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"format\": \"schema:encodingFormat\",\n        \"size\": \"schema:contentSize\",\n        \"license\": \"schema:license\"\n      }\n    },\n\n    \"TransferTask\": {\n      \"@id\": \"csda:TransferTask\",\n      \"@context\": {\n        \"id\": \"csda:id\",\n        \"source\": \"csda:source\",\n        \"destination\": \"csda:destination\",\n        \"bytesTransferred\": \"csda:bytes_transferred\"\
  ,\n        \"status\": \"csda:status\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage-and-data-acquisition/refs/heads/main/json-ld/cloud-storage-and-data-acquisition-context.jsonld
tags:
- Bulk Transfer
- Change Data Capture
- Cloud Storage
- Data Acquisition
- Data Ingestion
- Data Lake
- ETL
- Object Storage
- Pipelines
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
