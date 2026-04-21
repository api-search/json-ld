---
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
