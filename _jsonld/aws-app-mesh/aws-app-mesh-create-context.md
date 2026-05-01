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
source_filename: aws-app-mesh-create-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateVirtualRouterInput\": \"aws:CreateVirtualRouterInput\",\n    \"CreateMeshOutput\": \"aws:CreateMeshOutput\",\n    \"CreateRouteInput\": \"aws:CreateRouteInput\",\n    \"CreateVirtualRouterOutput\": \"aws:CreateVirtualRouterOutput\",\n    \"CreateVirtualServiceInput\": \"aws:CreateVirtualServiceInput\",\n    \"CreateVirtualServiceOutput\": \"aws:CreateVirtualServiceOutput\",\n    \"CreateVirtualGatewayOutput\": \"aws:CreateVirtualGatewayOutput\",\n    \"CreateGatewayRouteInput\": \"aws:CreateGatewayRouteInput\",\n    \"CreateVirtualNodeOutput\": \"aws:CreateVirtualNodeOutput\",\n    \"CreateVirtualNodeInput\": \"aws:CreateVirtualNodeInput\",\n    \"CreateMeshInput\": \"aws:CreateMeshInput\",\n    \"CreateGatewayRouteOutput\": \"\
  aws:CreateGatewayRouteOutput\",\n    \"CreateVirtualGatewayInput\": \"aws:CreateVirtualGatewayInput\",\n    \"CreateRouteOutput\": \"aws:CreateRouteOutput\",\n    \"gatewayRoute\": {\n      \"@id\": \"aws:gatewayRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"aws:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNodeName\": {\n      \"@id\": \"aws:virtualNodeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouter\": {\n      \"@id\": \"aws:virtualRouter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayName\": {\n      \"@id\": \"aws:virtualGatewayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNode\": {\n      \"@id\": \"aws:virtualNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGateway\": {\n\
  \      \"@id\": \"aws:virtualGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routeName\": {\n      \"@id\": \"aws:routeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualService\": {\n      \"@id\": \"aws:virtualService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mesh\": {\n      \"@id\": \"aws:mesh\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouterName\": {\n      \"@id\": \"aws:virtualRouterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayRouteName\": {\n      \"@id\": \"aws:gatewayRouteName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshName\": {\n      \"@id\": \"aws:meshName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"route\": {\n      \"@id\": \"aws:route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualServiceName\": {\n      \"@id\": \"aws:virtualServiceName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-create-context.jsonld
tags:
- Deprecated
- Envoy
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
