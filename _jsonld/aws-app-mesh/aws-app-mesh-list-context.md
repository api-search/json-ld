---
class_count: 16
classes:
- ListVirtualNodesOutput
- ListVirtualRoutersInput
- ListRoutesInput
- ListVirtualGatewaysInput
- ListGatewayRoutesOutput
- ListVirtualGatewaysOutput
- ListMeshesInput
- ListTagsForResourceOutput
- ListVirtualRoutersOutput
- ListRoutesOutput
- ListVirtualNodesInput
- ListMeshesOutput
- ListTagsForResourceInput
- ListVirtualServicesOutput
- ListGatewayRoutesInput
- ListVirtualServicesInput
context_file: json-ld/aws-app-mesh-list-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-list-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh List from AWS App Mesh.
layout: jsonld
name: Aws App Mesh List Context
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
  name: nextToken
  type: string
- container: ''
  name: virtualNodes
  type: string
- container: ''
  name: routes
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: virtualServices
  type: string
- container: ''
  name: virtualRouters
  type: string
- container: ''
  name: gatewayRoutes
  type: string
- container: ''
  name: meshes
  type: string
- container: ''
  name: virtualGateways
  type: string
property_count: 9
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-list-context
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
