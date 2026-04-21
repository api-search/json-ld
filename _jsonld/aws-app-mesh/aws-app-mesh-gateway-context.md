---
class_count: 9
classes:
- GatewayRouteHostnameRewrite
- GatewayRouteHostnameMatch
- GatewayRouteVirtualService
- GatewayRouteData
- GatewayRouteRef
- GatewayRouteSpec
- GatewayRouteStatus
- GatewayRouteTarget
- version
context_file: json-ld/aws-app-mesh-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Gateway from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Gateway Context
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
  name: defaultTargetHostname
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: suffix
  type: string
- container: ''
  name: grpcRoute
  type: string
- container: ''
  name: http2Route
  type: string
- container: ''
  name: httpRoute
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: virtualService
  type: string
- container: ''
  name: gatewayRouteName
  type: string
- container: ''
  name: meshName
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: virtualGatewayName
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: lastUpdatedAt
  type: string
- container: ''
  name: meshOwner
  type: string
- container: ''
  name: resourceOwner
  type: string
- container: ''
  name: virtualServiceName
  type: string
property_count: 21
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-gateway-context
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
