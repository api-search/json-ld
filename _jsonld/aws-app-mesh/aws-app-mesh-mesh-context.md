---
class_count: 6
classes:
- MeshStatus
- MeshData
- MeshRef
- MeshSpec
- MeshServiceDiscovery
- version
context_file: json-ld/aws-app-mesh-mesh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-mesh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Mesh from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Mesh Context
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
  name: meshName
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: ipPreference
  type: string
- container: ''
  name: egressFilter
  type: string
- container: ''
  name: serviceDiscovery
  type: reference
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
property_count: 12
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-mesh-context
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
