---
class_count: 5
classes:
- RouteData
- RouteStatus
- RouteRef
- RouteSpec
- version
context_file: json-ld/aws-app-mesh-route-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-route-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Route from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Route Context
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
  name: status
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
  name: tcpRoute
  type: string
- container: ''
  name: meshName
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: routeName
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: virtualRouterName
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
property_count: 16
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-route-context
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
