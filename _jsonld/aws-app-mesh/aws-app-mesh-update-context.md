---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateVirtualNodeOutput\": \"aws:UpdateVirtualNodeOutput\",\n    \"UpdateGatewayRouteInput\": \"aws:UpdateGatewayRouteInput\",\n    \"UpdateVirtualGatewayInput\": \"aws:UpdateVirtualGatewayInput\",\n    \"UpdateRouteOutput\": \"aws:UpdateRouteOutput\",\n    \"UpdateVirtualNodeInput\": \"aws:UpdateVirtualNodeInput\",\n    \"UpdateVirtualRouterInput\": \"aws:UpdateVirtualRouterInput\",\n    \"UpdateMeshOutput\": \"aws:UpdateMeshOutput\",\n    \"UpdateVirtualRouterOutput\": \"aws:UpdateVirtualRouterOutput\",\n    \"UpdateGatewayRouteOutput\": \"aws:UpdateGatewayRouteOutput\",\n    \"UpdateRouteInput\": \"aws:UpdateRouteInput\",\n    \"UpdateVirtualGatewayOutput\": \"aws:UpdateVirtualGatewayOutput\",\n    \"UpdateVirtualServiceOutput\"\
  : \"aws:UpdateVirtualServiceOutput\",\n    \"UpdateMeshInput\": \"aws:UpdateMeshInput\",\n    \"UpdateVirtualServiceInput\": \"aws:UpdateVirtualServiceInput\",\n    \"clientToken\": {\n      \"@id\": \"aws:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mesh\": {\n      \"@id\": \"aws:mesh\",\n      \"@type\": \"@id\"\n    },\n    \"virtualNode\": {\n      \"@id\": \"aws:virtualNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"route\": {\n      \"@id\": \"aws:route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualService\": {\n      \"@id\": \"aws:virtualService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouter\": {\n      \"@id\": \"aws:virtualRouter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGateway\": {\n      \"@id\": \"aws:virtualGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayRoute\": {\n      \"@id\": \"aws:gatewayRoute\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-update-context.jsonld
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
