---
api_specs:
- filename: amazon-lambda-openapi.yml
  format: yaml
  label: Amazon Lambda API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lambda/refs/heads/main/openapi/amazon-lambda-openapi.yml
class_count: 2
classes:
- Function
- EventSourceMapping
context_file: json-ld/amazon-lambda-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lambda/refs/heads/main/json-ld/amazon-lambda-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lambda from Amazon Lambda.
layout: jsonld
name: Amazon Lambda Context
namespaces:
- prefix: lambda
  uri: https://lambda.amazonaws.com/schema/
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
provider_name: Amazon Lambda
provider_slug: amazon-lambda
slug: amazon-lambda-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lambda\": \"https://lambda.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Function\": \"lambda:Function\",\n    \"EventSourceMapping\": \"lambda:EventSourceMapping\",\n    \"id\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"lambda:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"lambda:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lambda/refs/heads/main/json-ld/amazon-lambda-context.jsonld
tags:
- AWS
- Compute
- Event-Driven
- FaaS
- Functions
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
