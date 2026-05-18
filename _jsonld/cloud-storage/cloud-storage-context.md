---
class_count: 0
classes: []
context_file: json-ld/cloud-storage-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage/refs/heads/main/json-ld/cloud-storage-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cloud Storage from Cloud Storage.
layout: jsonld
name: Cloud Storage Context
namespaces:
- prefix: cs
  uri: https://apievangelist.com/topics/cloud-storage/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Bucket
  type: ''
- container: ''
  name: Object
  type: ''
- container: ''
  name: MultipartUpload
  type: ''
- container: ''
  name: FileSystem
  type: ''
- container: ''
  name: Volume
  type: ''
- container: ''
  name: Snapshot
  type: ''
- container: ''
  name: LifecycleRule
  type: ''
property_count: 7
provider_name: Cloud Storage
provider_slug: cloud-storage
slug: cloud-storage-context
source_filename: cloud-storage-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cs\": \"https://apievangelist.com/topics/cloud-storage/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Bucket\": {\n      \"@id\": \"cs:Bucket\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"provider\": \"schema:provider\",\n        \"region\": \"cs:region\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"versioning\": \"cs:versioning\",\n        \"encryption\": \"cs:encryption\",\n        \"publicAccess\": \"cs:public_access\"\n      }\n    },\n\n    \"Object\": {\n      \"@id\": \"cs:Object\",\n      \"@context\": {\n        \"key\": \"cs:key\",\n        \"size\": \"schema:contentSize\",\n        \"etag\": \"cs:etag\",\n        \"contentType\": \"schema:encodingFormat\",\n        \"storageClass\": \"cs:storage_class\"\
  ,\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"MultipartUpload\": {\n      \"@id\": \"cs:MultipartUpload\",\n      \"@context\": {\n        \"uploadId\": \"cs:upload_id\",\n        \"key\": \"cs:key\",\n        \"initiatedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"parts\": {\n          \"@id\": \"cs:parts\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"FileSystem\": {\n      \"@id\": \"cs:FileSystem\",\n      \"@context\": {\n        \"id\": \"cs:id\",\n        \"name\": \"schema:name\",\n        \"performanceMode\": \"cs:performance_mode\",\n        \"throughputMode\": \"cs:throughput_mode\",\n        \"provisionedThroughputInMibps\": \"cs:provisioned_throughput\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n\
  \    },\n\n    \"Volume\": {\n      \"@id\": \"cs:Volume\",\n      \"@context\": {\n        \"id\": \"cs:id\",\n        \"size\": \"schema:contentSize\",\n        \"type\": \"cs:volume_type\",\n        \"iops\": \"cs:iops\",\n        \"throughput\": \"cs:throughput\",\n        \"encrypted\": \"cs:encrypted\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Snapshot\": {\n      \"@id\": \"cs:Snapshot\",\n      \"@context\": {\n        \"id\": \"cs:id\",\n        \"volumeId\": \"cs:volume_id\",\n        \"size\": \"schema:contentSize\",\n        \"state\": \"cs:state\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"LifecycleRule\": {\n      \"@id\": \"cs:LifecycleRule\",\n      \"@context\": {\n        \"id\": \"cs:id\",\n        \"filter\": \"cs:filter\",\n        \"transitions\": {\n          \"@id\"\
  : \"cs:transitions\",\n          \"@container\": \"@set\"\n        },\n        \"expirationDays\": \"cs:expiration_days\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cloud-storage/refs/heads/main/json-ld/cloud-storage-context.jsonld
tags:
- Block Storage
- Cloud
- Cloud Storage
- File Storage
- Object Storage
- S3 Compatible
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
