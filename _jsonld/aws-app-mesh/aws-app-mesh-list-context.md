---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
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
source_filename: aws-app-mesh-list-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListVirtualNodesOutput\": \"aws:ListVirtualNodesOutput\",\n    \"ListVirtualRoutersInput\": \"aws:ListVirtualRoutersInput\",\n    \"ListRoutesInput\": \"aws:ListRoutesInput\",\n    \"ListVirtualGatewaysInput\": \"aws:ListVirtualGatewaysInput\",\n    \"ListGatewayRoutesOutput\": \"aws:ListGatewayRoutesOutput\",\n    \"ListVirtualGatewaysOutput\": \"aws:ListVirtualGatewaysOutput\",\n    \"ListMeshesInput\": \"aws:ListMeshesInput\",\n    \"ListTagsForResourceOutput\": \"aws:ListTagsForResourceOutput\",\n    \"ListVirtualRoutersOutput\": \"aws:ListVirtualRoutersOutput\",\n    \"ListRoutesOutput\": \"aws:ListRoutesOutput\",\n    \"ListVirtualNodesInput\": \"aws:ListVirtualNodesInput\",\n    \"ListMeshesOutput\": \"aws:ListMeshesOutput\"\
  ,\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"ListVirtualServicesOutput\": \"aws:ListVirtualServicesOutput\",\n    \"ListGatewayRoutesInput\": \"aws:ListGatewayRoutesInput\",\n    \"ListVirtualServicesInput\": \"aws:ListVirtualServicesInput\",\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNodes\": {\n      \"@id\": \"aws:virtualNodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routes\": {\n      \"@id\": \"aws:routes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualServices\": {\n      \"@id\": \"aws:virtualServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualRouters\": {\n      \"@id\": \"aws:virtualRouters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gatewayRoutes\": {\n      \"@id\": \"aws:gatewayRoutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshes\": {\n\
  \      \"@id\": \"aws:meshes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualGateways\": {\n      \"@id\": \"aws:virtualGateways\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-list-context.jsonld
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
