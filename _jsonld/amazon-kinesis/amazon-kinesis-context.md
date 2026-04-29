---
api_specs:
- filename: amazon-kinesis-data-streams-openapi.yml
  format: yaml
  label: Amazon Kinesis Data Streams
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis/refs/heads/main/openapi/amazon-kinesis-data-streams-openapi.yml
class_count: 2
classes:
- Stream
- Record
context_file: json-ld/amazon-kinesis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis/refs/heads/main/json-ld/amazon-kinesis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Kinesis from Amazon Kinesis.
layout: jsonld
name: Amazon Kinesis Context
namespaces:
- prefix: kinesis
  uri: https://kinesis.amazonaws.com/schema/
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
provider_name: Amazon Kinesis
provider_slug: amazon-kinesis
slug: amazon-kinesis-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kinesis\": \"https://kinesis.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Stream\": \"kinesis:Stream\",\n    \"Record\": \"kinesis:Record\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"kinesis:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"kinesis:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"\
  xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-kinesis/refs/heads/main/json-ld/amazon-kinesis-context.jsonld
tags:
- Analytics
- Big Data
- Data Processing
- Real-Time
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
