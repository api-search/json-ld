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
class_count: 7
classes:
- CreateUsagePlanRequest
- CreateDeploymentRequest
- CreateApiKeyRequest
- CreateRestApiRequest
- name
- description
- version
context_file: json-ld/aws-api-gateway-v1-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V1 Create from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V1 Create Context
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
  name: endpointConfiguration
  type: reference
- container: set
  name: types
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: throttle
  type: reference
- container: ''
  name: burstLimit
  type: integer
- container: ''
  name: rateLimit
  type: decimal
- container: ''
  name: quota
  type: reference
- container: ''
  name: limit
  type: integer
- container: ''
  name: period
  type: string
- container: ''
  name: stageName
  type: string
property_count: 10
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v1-create-context
source_filename: aws-api-gateway-v1-create-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateUsagePlanRequest\": \"aws:CreateUsagePlanRequest\",\n    \"CreateDeploymentRequest\": \"aws:CreateDeploymentRequest\",\n    \"CreateApiKeyRequest\": \"aws:CreateApiKeyRequest\",\n    \"CreateRestApiRequest\": \"aws:CreateRestApiRequest\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"version\": \"schema:version\",\n    \"endpointConfiguration\": {\n      \"@id\": \"aws:endpointConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"types\": {\n      \"@id\": \"aws:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"aws:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"throttle\": {\n      \"@id\": \"aws:throttle\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"burstLimit\": {\n      \"@id\": \"aws:burstLimit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rateLimit\": {\n      \"@id\": \"aws:rateLimit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"quota\": {\n      \"@id\": \"aws:quota\",\n      \"@type\": \"@id\"\n    },\n    \"limit\": {\n      \"@id\": \"aws:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"period\": {\n      \"@id\": \"aws:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stageName\": {\n      \"@id\": \"aws:stageName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v1-create-context.jsonld
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
