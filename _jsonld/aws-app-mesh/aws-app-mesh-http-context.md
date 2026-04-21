---
class_count: 16
classes:
- HttpGatewayRoute
- HttpRouteHeader
- HttpRouteMatch
- HttpRoute
- HttpGatewayRouteRewrite
- HttpGatewayRouteMatch
- HttpGatewayRoutePathRewrite
- HttpPathMatch
- HttpTimeout
- HttpGatewayRouteHeader
- HttpRouteAction
- HttpRetryPolicy
- HttpGatewayRoutePrefixRewrite
- HttpGatewayRouteAction
- HttpQueryParameter
- name
context_file: json-ld/aws-app-mesh-http-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-http-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Http from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Http Context
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
  name: action
  type: string
- container: ''
  name: match
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: headers
  type: string
- container: ''
  name: hostname
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: port
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: queryParameters
  type: string
- container: ''
  name: defaultPrefix
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: idle
  type: string
- container: ''
  name: perRequest
  type: string
- container: ''
  name: invert
  type: string
- container: ''
  name: rewrite
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: scheme
  type: string
- container: ''
  name: retryPolicy
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: regex
  type: string
- container: ''
  name: weightedTargets
  type: string
property_count: 26
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-http-context
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
