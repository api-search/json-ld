---
class_count: 3
classes:
- ApiKey
- ApiKeys
- name
context_file: json-ld/aws-api-gateway-v1-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V1 Api from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V1 Api Context
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
- container: set
  name: items
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: enabled
  type: boolean
property_count: 4
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v1-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiKey\": \"aws:ApiKey\",\n    \"ApiKeys\": \"aws:ApiKeys\",\n    \"items\": {\n      \"@id\": \"aws:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"enabled\": {\n      \"@id\": \"aws:enabled\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-api-context.jsonld
tags:
- API Gateway
- AWS
- Cloud
- REST
- WebSocket
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
