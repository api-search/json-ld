---
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
