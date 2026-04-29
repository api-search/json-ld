---
class_count: 3
classes:
- DataLake
- LogSource
- Subscriber
context_file: json-ld/amazon-security-lake-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-security-lake/refs/heads/main/json-ld/amazon-security-lake-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Security Lake from Amazon Security Lake.
layout: jsonld
name: Amazon Security Lake Context
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
  name: dataLakeArn
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: encryptionConfiguration
  type: string
- container: ''
  name: lifecycleConfiguration
  type: string
- container: ''
  name: s3BucketArn
  type: string
- container: ''
  name: sourceName
  type: string
- container: ''
  name: sourceVersion
  type: string
- container: ''
  name: sourceStatus
  type: string
- container: ''
  name: subscriberId
  type: string
- container: ''
  name: subscriberArn
  type: string
- container: ''
  name: subscriberName
  type: string
- container: ''
  name: subscriberDescription
  type: string
- container: ''
  name: subscriberStatus
  type: string
- container: set
  name: accessTypes
  type: string
- container: ''
  name: resourceShareArn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 18
provider_name: Amazon Security Lake
provider_slug: amazon-security-lake
slug: amazon-security-lake-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataLake\": \"aws:DataLake\",\n    \"dataLakeArn\": {\n      \"@id\": \"aws:dataLakeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"aws:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionConfiguration\": {\n      \"@id\": \"aws:encryptionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleConfiguration\": {\n      \"@id\": \"aws:lifecycleConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3BucketArn\": {\n      \"@id\": \"aws:s3BucketArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogSource\": \"aws:LogSource\",\n    \"sourceName\": {\n      \"@id\"\
  : \"aws:sourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceVersion\": {\n      \"@id\": \"aws:sourceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceStatus\": {\n      \"@id\": \"aws:sourceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subscriber\": \"aws:Subscriber\",\n    \"subscriberId\": {\n      \"@id\": \"aws:subscriberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriberArn\": {\n      \"@id\": \"aws:subscriberArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriberName\": {\n      \"@id\": \"aws:subscriberName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriberDescription\": {\n      \"@id\": \"aws:subscriberDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriberStatus\": {\n      \"@id\": \"aws:subscriberStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessTypes\": {\n      \"@id\": \"aws:accessTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"resourceShareArn\": {\n      \"@id\": \"aws:resourceShareArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"aws:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-security-lake/refs/heads/main/json-ld/amazon-security-lake-context.jsonld
tags:
- AWS
- Data Lake
- Security
- SIEM
- Threat Detection
- JSON-LD
- Linked Data
- Semantic Web
---
