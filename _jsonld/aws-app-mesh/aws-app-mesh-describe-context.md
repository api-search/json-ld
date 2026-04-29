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
- DescribeMeshOutput
- DescribeMeshInput
- DescribeGatewayRouteOutput
- DescribeVirtualGatewayInput
- DescribeVirtualNodeInput
- DescribeVirtualServiceOutput
- DescribeRouteInput
- DescribeVirtualServiceInput
- DescribeVirtualRouterOutput
- DescribeGatewayRouteInput
- DescribeVirtualGatewayOutput
- DescribeRouteOutput
- DescribeVirtualNodeOutput
- DescribeVirtualRouterInput
context_file: json-ld/aws-app-mesh-describe-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-describe-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Describe from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Describe Context
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
  name: virtualService
  type: string
- container: ''
  name: virtualNode
  type: string
- container: ''
  name: virtualGateway
  type: string
- container: ''
  name: mesh
  type: string
- container: ''
  name: route
  type: string
- container: ''
  name: virtualRouter
  type: string
property_count: 7
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-describe-context
source_filename: aws-app-mesh-describe-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DescribeMeshOutput\": \"aws:DescribeMeshOutput\",\n    \"DescribeMeshInput\": \"aws:DescribeMeshInput\",\n    \"DescribeGatewayRouteOutput\": \"aws:DescribeGatewayRouteOutput\",\n    \"DescribeVirtualGatewayInput\": \"aws:DescribeVirtualGatewayInput\",\n    \"DescribeVirtualNodeInput\": \"aws:DescribeVirtualNodeInput\",\n    \"DescribeVirtualServiceOutput\": \"aws:DescribeVirtualServiceOutput\",\n    \"DescribeRouteInput\": \"aws:DescribeRouteInput\",\n    \"DescribeVirtualServiceInput\": \"aws:DescribeVirtualServiceInput\",\n    \"DescribeVirtualRouterOutput\": \"aws:DescribeVirtualRouterOutput\",\n    \"DescribeGatewayRouteInput\": \"aws:DescribeGatewayRouteInput\",\n    \"DescribeVirtualGatewayOutput\": \"aws:DescribeVirtualGatewayOutput\"\
  ,\n    \"DescribeRouteOutput\": \"aws:DescribeRouteOutput\",\n    \"DescribeVirtualNodeOutput\": \"aws:DescribeVirtualNodeOutput\",\n    \"DescribeVirtualRouterInput\": \"aws:DescribeVirtualRouterInput\",\n    \"gatewayRoute\": {\n      \"@id\": \"aws:gatewayRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualService\": {\n      \"@id\": \"aws:virtualService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNode\": {\n      \"@id\": \"aws:virtualNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGateway\": {\n      \"@id\": \"aws:virtualGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mesh\": {\n      \"@id\": \"aws:mesh\",\n      \"@type\": \"xsd:string\"\n    },\n    \"route\": {\n      \"@id\": \"aws:route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouter\": {\n      \"@id\": \"aws:virtualRouter\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-describe-context.jsonld
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
