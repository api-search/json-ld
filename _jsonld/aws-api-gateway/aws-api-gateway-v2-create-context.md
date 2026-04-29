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
class_count: 6
classes:
- CreateRouteRequest
- CreateApiRequest
- CreateDeploymentRequest
- CreateAuthorizerRequest
- CreateStageRequest
- CreateIntegrationRequest
context_file: json-ld/aws-api-gateway-v2-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Api Gateway V2 Create from Amazon API Gateway.
layout: jsonld
name: Aws Api Gateway V2 Create Context
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
  name: RouteKey
  type: string
- container: ''
  name: Target
  type: string
- container: ''
  name: AuthorizationType
  type: string
- container: ''
  name: StageName
  type: string
- container: ''
  name: DeploymentId
  type: string
- container: ''
  name: AutoDeploy
  type: boolean
- container: ''
  name: Name
  type: string
- container: ''
  name: AuthorizerType
  type: string
- container: set
  name: IdentitySource
  type: string
- container: ''
  name: AuthorizerUri
  type: string
- container: ''
  name: IntegrationType
  type: string
- container: ''
  name: IntegrationUri
  type: string
- container: ''
  name: PayloadFormatVersion
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: ProtocolType
  type: string
- container: ''
  name: RouteSelectionExpression
  type: string
property_count: 16
provider_name: Amazon API Gateway
provider_slug: aws-api-gateway
slug: aws-api-gateway-v2-create-context
source_filename: aws-api-gateway-v2-create-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateRouteRequest\": \"aws:CreateRouteRequest\",\n    \"CreateApiRequest\": \"aws:CreateApiRequest\",\n    \"CreateDeploymentRequest\": \"aws:CreateDeploymentRequest\",\n    \"CreateAuthorizerRequest\": \"aws:CreateAuthorizerRequest\",\n    \"CreateStageRequest\": \"aws:CreateStageRequest\",\n    \"CreateIntegrationRequest\": \"aws:CreateIntegrationRequest\",\n    \"RouteKey\": {\n      \"@id\": \"aws:RouteKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Target\": {\n      \"@id\": \"aws:Target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizationType\": {\n      \"@id\": \"aws:AuthorizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StageName\": {\n      \"@id\": \"aws:StageName\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"DeploymentId\": {\n      \"@id\": \"aws:DeploymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoDeploy\": {\n      \"@id\": \"aws:AutoDeploy\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizerType\": {\n      \"@id\": \"aws:AuthorizerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentitySource\": {\n      \"@id\": \"aws:IdentitySource\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizerUri\": {\n      \"@id\": \"aws:AuthorizerUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IntegrationType\": {\n      \"@id\": \"aws:IntegrationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IntegrationUri\": {\n      \"@id\": \"aws:IntegrationUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayloadFormatVersion\": {\n      \"@id\": \"aws:PayloadFormatVersion\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProtocolType\": {\n      \"@id\": \"aws:ProtocolType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RouteSelectionExpression\": {\n      \"@id\": \"aws:RouteSelectionExpression\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/json-ld/aws-api-gateway-v2-create-context.jsonld
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
