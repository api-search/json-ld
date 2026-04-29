---
api_specs:
- filename: amazon-lakeformation-openapi.yml
  format: yaml
  label: AWS Lake Formation API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lakeformation/refs/heads/main/openapi/amazon-lakeformation-openapi.yml
class_count: 2
classes:
- Database
- DataCellsFilter
context_file: json-ld/amazon-lakeformation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lakeformation/refs/heads/main/json-ld/amazon-lakeformation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lakeformation from AWS Lake Formation.
layout: jsonld
name: Amazon Lakeformation Context
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
provider_name: AWS Lake Formation
provider_slug: amazon-lakeformation
slug: amazon-lakeformation-context
source_filename: amazon-lakeformation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lakeformation\": \"https://lakeformation.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Database\": \"lakeformation:Database\",\n    \"DataCellsFilter\": \"lakeformation:DataCellsFilter\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lakeformation:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lakeformation:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n\
  \      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lakeformation/refs/heads/main/json-ld/amazon-lakeformation-context.jsonld
tags:
- Analytics
- AWS
- Data Lake
- Governance
- JSON-LD
- Linked Data
- Semantic Web
---
