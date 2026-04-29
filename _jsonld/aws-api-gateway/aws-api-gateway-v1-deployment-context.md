---
api_specs:
- filename: aws-api-gateway-v1-openapi.yml
  format: yaml
  label: Amazon API Gateway V1 (REST)
  slug: aws-api-gateway-v1
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-v1-openapi.yml
- filename: aws-api-gateway-v2-openapi.yml
  format: yaml
  label: Amazon API Gateway V2 (HTTP and WebSocket)
  slug: aws-api-gateway-v2
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-v2-openapi.yml
- filename: aws-api-gateway-management-openapi.yml
  format: yaml
  label: Amazon API Gateway Management API
  slug: aws-api-gateway-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/openapi/aws-api-gateway-management-openapi.yml
class_count: 2
classes:
- Deployment
- description
context_file: json-ld/aws-api-gateway-v1-deployment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-deployment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V1 Deployment from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V1 Deployment Context
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
  name: id
  type: string
- container: ''
  name: createdDate
  type: dateTime
property_count: 2
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v1-deployment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Deployment\": \"aws:Deployment\",\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"createdDate\": {\n      \"@id\": \"aws:createdDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-deployment-context.jsonld
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
