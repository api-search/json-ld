---
class_count: 14
classes:
- GrpcGatewayRouteMetadata
- GrpcRouteAction
- GrpcGatewayRouteAction
- GrpcRoute
- GrpcTimeout
- GrpcGatewayRoute
- GrpcRouteMatch
- GrpcRetryPolicy
- GrpcRouteMetadata
- GrpcGatewayRouteRewrite
- GrpcRouteMetadataMatchMethod
- GrpcGatewayRouteMatch
- GrpcMetadataMatchMethod
- name
context_file: json-ld/aws-app-mesh-grpc-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-grpc-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Grpc from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Grpc Context
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
  name: hostname
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: methodName
  type: string
- container: ''
  name: invert
  type: string
- container: ''
  name: match
  type: string
- container: ''
  name: grpcRetryEvents
  type: string
- container: ''
  name: httpRetryEvents
  type: string
- container: ''
  name: maxRetries
  type: string
- container: ''
  name: perRetryTimeout
  type: string
- container: ''
  name: tcpRetryEvents
  type: string
- container: ''
  name: rewrite
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: weightedTargets
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: retryPolicy
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: idle
  type: string
- container: ''
  name: perRequest
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: range
  type: string
- container: ''
  name: regex
  type: string
- container: ''
  name: suffix
  type: string
property_count: 25
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-grpc-context
tags:
- AWS
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
