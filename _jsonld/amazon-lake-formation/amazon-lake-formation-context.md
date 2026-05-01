---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Amazon Lake Formation API
  slug: ''
  spec_type: OpenAPI
  url: https://api.apis.guru/v2/specs/amazonaws.com/lakeformation/2017-03-31/openapi.yaml
class_count: 2
classes:
- DataLakeResource
- Permission
context_file: json-ld/amazon-lake-formation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lake-formation/refs/heads/main/json-ld/amazon-lake-formation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lake Formation from Amazon Lake Formation.
layout: jsonld
name: Amazon Lake Formation Context
namespaces:
- prefix: lakeformation
  uri: https://lakeformation.amazonaws.com/schema/
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
provider_name: Amazon Lake Formation
provider_slug: amazon-lake-formation
slug: amazon-lake-formation-context
source_filename: amazon-lake-formation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lakeformation\": \"https://lakeformation.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DataLakeResource\": \"lakeformation:DataLakeResource\",\n    \"Permission\": \"lakeformation:Permission\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lakeformation:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lakeformation:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\"\
  : {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lake-formation/refs/heads/main/json-ld/amazon-lake-formation-context.jsonld
tags:
- Access Control
- Analytics
- Data Governance
- Data Lake
- S3
- JSON-LD
- Linked Data
- Semantic Web
---
