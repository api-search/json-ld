---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
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
source_filename: aws-app-mesh-tcp-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TcpRouteMatch\": \"aws:TcpRouteMatch\",\n    \"TcpTimeout\": \"aws:TcpTimeout\",\n    \"TcpRoute\": \"aws:TcpRoute\",\n    \"TcpRouteAction\": \"aws:TcpRouteAction\",\n    \"action\": {\n      \"@id\": \"aws:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"match\": {\n      \"@id\": \"aws:match\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeout\": {\n      \"@id\": \"aws:timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idle\": {\n      \"@id\": \"aws:idle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weightedTargets\": {\n      \"@id\": \"aws:weightedTargets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tcp-context.jsonld
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
