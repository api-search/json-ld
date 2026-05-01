---
class_count: 1
classes:
- Amazon S3 Glacier Vault
context_file: json-ld/amazon-s3-glacier-vault-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/json-ld/amazon-s3-glacier-vault-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon S3 Glacier Vault from Amazon S3 Glacier.
layout: jsonld
name: Amazon S3 Glacier Vault Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: VaultARN
  type: string
- container: ''
  name: VaultName
  type: string
- container: ''
  name: CreationDate
  type: dateTime
- container: ''
  name: LastInventoryDate
  type: dateTime
- container: ''
  name: NumberOfArchives
  type: integer
- container: ''
  name: SizeInBytes
  type: integer
- container: ''
  name: VaultAccessPolicy
  type: string
- container: ''
  name: VaultNotificationConfig
  type: string
- container: ''
  name: Tags
  type: string
property_count: 9
provider_name: Amazon S3 Glacier
provider_slug: amazon-s3-glacier
slug: amazon-s3-glacier-vault-context
source_filename: amazon-s3-glacier-vault-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amazon S3 Glacier Vault\": \"aws:Amazon S3 Glacier Vault\",\n    \"VaultARN\": {\n      \"@id\": \"aws:VaultARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VaultName\": {\n      \"@id\": \"aws:VaultName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"aws:CreationDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastInventoryDate\": {\n      \"@id\": \"aws:LastInventoryDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"NumberOfArchives\": {\n      \"@id\": \"aws:NumberOfArchives\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"SizeInBytes\": {\n      \"@id\": \"aws:SizeInBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"VaultAccessPolicy\": {\n      \"@id\": \"aws:VaultAccessPolicy\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"VaultNotificationConfig\": {\n      \"@id\": \"aws:VaultNotificationConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-s3-glacier/refs/heads/main/json-ld/amazon-s3-glacier-vault-context.jsonld
tags:
- Archive
- Backup
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
