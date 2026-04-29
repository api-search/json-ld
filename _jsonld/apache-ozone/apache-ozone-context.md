---
api_specs:
- filename: apache-ozone-s3-api.yaml
  format: yaml
  label: Apache Ozone
  slug: apache-ozone
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/openapi/apache-ozone-s3-api.yaml
class_count: 5
classes:
- ListAllMyBucketsResult
- Owner
- Bucket
- ListObjectsResult
- Object
context_file: json-ld/apache-ozone-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/json-ld/apache-ozone-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Apache Ozone from Apache Ozone.
layout: jsonld
name: Apache Ozone Context
namespaces:
- prefix: ozon
  uri: https://ozone.apache.org/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: owner
  type: string
- container: set
  name: buckets
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: name
  type: schema:name
- container: ''
  name: creationDate
  type: string
- container: ''
  name: storageClass
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: maxKeys
  type: integer
- container: ''
  name: isTruncated
  type: boolean
- container: ''
  name: nextContinuationToken
  type: string
- container: set
  name: contents
  type: ''
- container: ''
  name: key
  type: string
- container: ''
  name: lastModified
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: size
  type: integer
property_count: 16
provider_name: Apache Ozone
provider_slug: apache-ozone
slug: apache-ozone-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ozon\": \"https://ozone.apache.org/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListAllMyBucketsResult\": \"ozon:ListAllMyBucketsResult\",\n    \"Owner\": \"ozon:Owner\",\n    \"Bucket\": \"ozon:Bucket\",\n    \"ListObjectsResult\": \"ozon:ListObjectsResult\",\n    \"Object\": \"ozon:Object\",\n    \"owner\": {\n      \"@id\": \"ozon:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buckets\": {\n      \"@id\": \"ozon:buckets\",\n      \"@container\": \"@set\"\n    },\n    \"id\": {\n      \"@id\": \"ozon:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"ozon:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"ozon:name\",\n      \"@type\": \"schema:name\"\n    },\n    \"creationDate\": {\n      \"@id\": \"ozon:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"storageClass\": {\n      \"@id\": \"ozon:storageClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"ozon:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxKeys\": {\n      \"@id\": \"ozon:maxKeys\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"isTruncated\": {\n      \"@id\": \"ozon:isTruncated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"nextContinuationToken\": {\n      \"@id\": \"ozon:nextContinuationToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contents\": {\n      \"@id\": \"ozon:contents\",\n      \"@container\": \"@set\"\n    },\n    \"key\": {\n      \"@id\": \"ozon:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"ozon:lastModified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"ozon:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"ozon:size\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/apache-ozone/refs/heads/main/json-ld/apache-ozone-context.jsonld
tags:
- Distributed Storage
- Hadoop
- Object Storage
- S3-Compatible
- Apache
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
