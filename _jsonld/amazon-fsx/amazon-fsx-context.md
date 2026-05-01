---
api_specs:
- filename: amazon-fsx-openapi.yml
  format: yaml
  label: Amazon FSx API
  slug: amazon-fsx-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fsx/refs/heads/main/openapi/amazon-fsx-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-fsx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-fsx/refs/heads/main/json-ld/amazon-fsx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Fsx from Amazon FSx.
layout: jsonld
name: Amazon Fsx Context
namespaces:
- prefix: fsx
  uri: https://docs.aws.amazon.com/fsx/latest/APIReference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: FileSystem
  type: ''
- container: ''
  name: Backup
  type: ''
property_count: 2
provider_name: Amazon FSx
provider_slug: amazon-fsx
slug: amazon-fsx-context
source_filename: amazon-fsx-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fsx\": \"https://docs.aws.amazon.com/fsx/latest/APIReference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"FileSystem\": {\n      \"@id\": \"fsx:FileSystem\",\n      \"@context\": {\n        \"fileSystemId\": \"fsx:fileSystemId\",\n        \"fileSystemType\": \"fsx:fileSystemType\",\n        \"lifecycle\": \"fsx:lifecycle\",\n        \"storageCapacity\": \"fsx:storageCapacity\",\n        \"storageType\": \"fsx:storageType\",\n        \"vpcId\": \"fsx:vpcId\",\n        \"subnetIds\": {\n          \"@id\": \"fsx:subnetIds\",\n          \"@container\": \"@list\"\n        },\n        \"dnsName\": \"fsx:dnsName\",\n        \"creationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"fsx:tags\",\n          \"@container\": \"@set\"\
  \n        }\n      }\n    },\n\n    \"Backup\": {\n      \"@id\": \"fsx:Backup\",\n      \"@context\": {\n        \"backupId\": \"fsx:backupId\",\n        \"lifecycle\": \"fsx:lifecycle\",\n        \"type\": \"fsx:backupType\",\n        \"fileSystem\": \"fsx:fileSystem\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-fsx/refs/heads/main/json-ld/amazon-fsx-context.jsonld
tags:
- File Systems
- Lustre
- NetApp
- OpenZFS
- Storage
- Windows
- JSON-LD
- Linked Data
- Semantic Web
---
