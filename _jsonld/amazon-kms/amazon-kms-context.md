---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon KMS API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/kms/2014-11-01/openapi.yaml
class_count: 1
classes:
- Key
context_file: json-ld/amazon-kms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-kms/refs/heads/main/json-ld/amazon-kms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Kms from Amazon KMS.
layout: jsonld
name: Amazon Kms Context
namespaces:
- prefix: kms
  uri: https://kms.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
property_count: 7
provider_name: Amazon KMS
provider_slug: amazon-kms
slug: amazon-kms-context
source_filename: amazon-kms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kms\": \"https://kms.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Key\": \"kms:Key\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kms:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"kms:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-kms/refs/heads/main/json-ld/amazon-kms-context.jsonld
tags:
- Cryptography
- Data Protection
- Encryption
- Key Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
