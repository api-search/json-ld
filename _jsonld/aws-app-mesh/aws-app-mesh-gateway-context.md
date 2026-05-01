---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
class_count: 9
classes:
- GatewayRouteHostnameRewrite
- GatewayRouteHostnameMatch
- GatewayRouteVirtualService
- GatewayRouteData
- GatewayRouteRef
- GatewayRouteSpec
- GatewayRouteStatus
- GatewayRouteTarget
- version
context_file: json-ld/aws-app-mesh-gateway-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-gateway-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Gateway from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Gateway Context
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
  name: defaultTargetHostname
  type: string
- container: ''
  name: exact
  type: string
- container: ''
  name: suffix
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
  name: port
  type: string
- container: ''
  name: virtualService
  type: string
- container: ''
  name: gatewayRouteName
  type: string
- container: ''
  name: meshName
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: spec
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: virtualGatewayName
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
- container: ''
  name: virtualServiceName
  type: string
property_count: 21
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-gateway-context
source_filename: aws-app-mesh-gateway-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"GatewayRouteHostnameRewrite\": \"aws:GatewayRouteHostnameRewrite\",\n    \"GatewayRouteHostnameMatch\": \"aws:GatewayRouteHostnameMatch\",\n    \"GatewayRouteVirtualService\": \"aws:GatewayRouteVirtualService\",\n    \"GatewayRouteData\": \"aws:GatewayRouteData\",\n    \"GatewayRouteRef\": \"aws:GatewayRouteRef\",\n    \"GatewayRouteSpec\": \"aws:GatewayRouteSpec\",\n    \"GatewayRouteStatus\": \"aws:GatewayRouteStatus\",\n    \"GatewayRouteTarget\": \"aws:GatewayRouteTarget\",\n    \"defaultTargetHostname\": {\n      \"@id\": \"aws:defaultTargetHostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exact\": {\n      \"@id\": \"aws:exact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"aws:suffix\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"grpcRoute\": {\n      \"@id\": \"aws:grpcRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http2Route\": {\n      \"@id\": \"aws:http2Route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpRoute\": {\n      \"@id\": \"aws:httpRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aws:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualService\": {\n      \"@id\": \"aws:virtualService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayRouteName\": {\n      \"@id\": \"aws:gatewayRouteName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshName\": {\n      \"@id\": \"aws:meshName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"aws:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGatewayName\": {\n      \"@id\": \"aws:virtualGatewayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"aws:lastUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshOwner\": {\n      \"@id\": \"aws:meshOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOwner\": {\n      \"@id\": \"aws:resourceOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"virtualServiceName\": {\n      \"@id\": \"aws:virtualServiceName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-gateway-context.jsonld
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
