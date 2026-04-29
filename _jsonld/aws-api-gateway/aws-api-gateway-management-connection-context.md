---
class_count: 1
classes:
- Connection
context_file: json-ld/aws-api-gateway-management-connection-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-management-connection-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway Management Connection from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway Management Connection Context
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
  name: ConnectedAt
  type: dateTime
- container: ''
  name: LastActiveAt
  type: dateTime
- container: ''
  name: Identity
  type: reference
- container: ''
  name: SourceIp
  type: string
- container: ''
  name: UserAgent
  type: string
property_count: 5
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-management-connection-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Connection\": \"aws:Connection\",\n    \"ConnectedAt\": {\n      \"@id\": \"aws:ConnectedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastActiveAt\": {\n      \"@id\": \"aws:LastActiveAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Identity\": {\n      \"@id\": \"aws:Identity\",\n      \"@type\": \"@id\"\n    },\n    \"SourceIp\": {\n      \"@id\": \"aws:SourceIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserAgent\": {\n      \"@id\": \"aws:UserAgent\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-management-connection-context.jsonld
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
