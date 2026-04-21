---
class_count: 14
classes:
- CreateVirtualRouterInput
- CreateMeshOutput
- CreateRouteInput
- CreateVirtualRouterOutput
- CreateVirtualServiceInput
- CreateVirtualServiceOutput
- CreateVirtualGatewayOutput
- CreateGatewayRouteInput
- CreateVirtualNodeOutput
- CreateVirtualNodeInput
- CreateMeshInput
- CreateGatewayRouteOutput
- CreateVirtualGatewayInput
- CreateRouteOutput
context_file: json-ld/aws-app-mesh-create-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-create-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Create from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Create Context
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
  name: gatewayRoute
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: virtualNodeName
  type: string
- container: ''
  name: virtualRouter
  type: string
- container: ''
  name: virtualGatewayName
  type: string
- container: ''
  name: virtualNode
  type: string
- container: ''
  name: virtualGateway
  type: string
- container: ''
  name: routeName
  type: string
- container: ''
  name: virtualService
  type: string
- container: ''
  name: mesh
  type: string
- container: ''
  name: virtualRouterName
  type: string
- container: ''
  name: gatewayRouteName
  type: string
- container: ''
  name: meshName
  type: string
- container: ''
  name: route
  type: string
- container: ''
  name: virtualServiceName
  type: string
property_count: 17
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-create-context
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
