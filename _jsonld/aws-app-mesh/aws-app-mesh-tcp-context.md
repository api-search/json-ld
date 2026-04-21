---
class_count: 4
classes:
- TcpRouteMatch
- TcpTimeout
- TcpRoute
- TcpRouteAction
context_file: json-ld/aws-app-mesh-tcp-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tcp-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Tcp from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Tcp Context
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
  name: action
  type: string
- container: ''
  name: match
  type: string
- container: ''
  name: timeout
  type: string
- container: ''
  name: idle
  type: string
- container: ''
  name: weightedTargets
  type: string
- container: ''
  name: port
  type: string
property_count: 6
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-tcp-context
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
