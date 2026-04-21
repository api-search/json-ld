---
class_count: 14
classes:
- UpdateVirtualNodeOutput
- UpdateGatewayRouteInput
- UpdateVirtualGatewayInput
- UpdateRouteOutput
- UpdateVirtualNodeInput
- UpdateVirtualRouterInput
- UpdateMeshOutput
- UpdateVirtualRouterOutput
- UpdateGatewayRouteOutput
- UpdateRouteInput
- UpdateVirtualGatewayOutput
- UpdateVirtualServiceOutput
- UpdateMeshInput
- UpdateVirtualServiceInput
context_file: json-ld/aws-app-mesh-update-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-update-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Update from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Update Context
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
  name: clientToken
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: mesh
  type: reference
- container: ''
  name: virtualNode
  type: string
- container: ''
  name: route
  type: string
- container: ''
  name: virtualService
  type: string
- container: ''
  name: virtualRouter
  type: string
- container: ''
  name: virtualGateway
  type: string
- container: ''
  name: gatewayRoute
  type: string
property_count: 9
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-update-context
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
