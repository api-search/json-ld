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
class_count: 1
classes:
- Api
context_file: json-ld/aws-api-gateway-v2-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V2 Api from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V2 Api Context
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
  name: ApiId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: ProtocolType
  type: string
- container: ''
  name: ApiEndpoint
  type: string
- container: ''
  name: RouteSelectionExpression
  type: string
- container: ''
  name: CreatedDate
  type: dateTime
property_count: 6
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v2-api-context
source_filename: aws-api-gateway-v2-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Api\": \"aws:Api\",\n    \"ApiId\": {\n      \"@id\": \"aws:ApiId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtocolType\": {\n      \"@id\": \"aws:ProtocolType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApiEndpoint\": {\n      \"@id\": \"aws:ApiEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RouteSelectionExpression\": {\n      \"@id\": \"aws:RouteSelectionExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"aws:CreatedDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-api-context.jsonld
tags:
- API Gateway
- Cloud
- REST
- WebSocket
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
