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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MeshStatus\": \"aws:MeshStatus\",\n    \"MeshData\": \"aws:MeshData\",\n    \"MeshRef\": \"aws:MeshRef\",\n    \"MeshSpec\": \"aws:MeshSpec\",\n    \"MeshServiceDiscovery\": \"aws:MeshServiceDiscovery\",\n    \"meshName\": {\n      \"@id\": \"aws:meshName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"aws:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"aws:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipPreference\": {\n      \"@id\": \"aws:ipPreference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"egressFilter\": {\n      \"@id\": \"aws:egressFilter\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceDiscovery\": {\n      \"@id\": \"aws:serviceDiscovery\",\n      \"@type\": \"@id\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"aws:lastUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meshOwner\": {\n      \"@id\": \"aws:meshOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOwner\": {\n      \"@id\": \"aws:resourceOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-mesh-context.jsonld
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
