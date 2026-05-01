---
class_count: 0
classes: []
context_file: json-ld/amazon-s3-glacier-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/json-ld/amazon-s3-glacier-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon S3 Glacier from Amazon S3 Glacier.
layout: jsonld
name: Amazon S3 Glacier Context
namespaces:
- prefix: glacier
  uri: https://docs.aws.amazon.com/amazonglacier/latest/dev/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: iam
  uri: https://docs.aws.amazon.com/IAM/latest/UserGuide/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: Vault
  type: ''
- container: ''
  name: Archive
  type: ''
- container: ''
  name: Job
  type: ''
property_count: 3
provider_name: Amazon S3 Glacier
provider_slug: amazon-s3-glacier
slug: amazon-s3-glacier-context
source_filename: amazon-s3-glacier-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"glacier\": \"https://docs.aws.amazon.com/amazonglacier/latest/dev/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"iam\": \"https://docs.aws.amazon.com/IAM/latest/UserGuide/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"schema\": \"https://schema.org/\",\n\n    \"Vault\": {\n      \"@id\": \"glacier:api-vault-get.html\",\n      \"@context\": {\n        \"VaultARN\": {\n          \"@id\": \"aws:arn\",\n          \"@type\": \"@id\"\n        },\n        \"VaultName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastInventoryDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"NumberOfArchives\"\
  : {\n          \"@id\": \"glacier:NumberOfArchives\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"SizeInBytes\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"Archive\": {\n      \"@id\": \"glacier:api-archive-post.html\",\n      \"@context\": {\n        \"ArchiveId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ArchiveDescription\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:long\"\n        },\n        \"SHA256TreeHash\": {\n          \"@id\": \"glacier:SHA256TreeHash\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"glacier:api-initiate-job-post.html\"\
  ,\n      \"@context\": {\n        \"JobId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"JobDescription\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Action\": {\n          \"@id\": \"glacier:JobAction\",\n          \"@type\": \"xsd:string\"\n        },\n        \"StatusCode\": {\n          \"@id\": \"glacier:JobStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"CreationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"CompletionDate\": {\n          \"@id\": \"glacier:CompletionDate\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/json-ld/amazon-s3-glacier-context.jsonld
tags:
- Archive
- Backup
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
