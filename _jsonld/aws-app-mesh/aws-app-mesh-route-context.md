---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
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
source_filename: aws-app-mesh-route-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"RouteData\": \"aws:RouteData\",\n    \"RouteStatus\": \"aws:RouteStatus\",\n    \"RouteRef\": \"aws:RouteRef\",\n    \"RouteSpec\": \"aws:RouteSpec\",\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grpcRoute\": {\n      \"@id\": \"aws:grpcRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"http2Route\": {\n      \"@id\": \"aws:http2Route\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpRoute\": {\n      \"@id\": \"aws:httpRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aws:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tcpRoute\": {\n      \"@id\": \"aws:tcpRoute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshName\"\
  : {\n      \"@id\": \"aws:meshName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"aws:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routeName\": {\n      \"@id\": \"aws:routeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouterName\": {\n      \"@id\": \"aws:virtualRouterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"aws:lastUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshOwner\": {\n      \"@id\": \"aws:meshOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOwner\": {\n      \"@id\": \"aws:resourceOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\"\
  \n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-route-context.jsonld
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
