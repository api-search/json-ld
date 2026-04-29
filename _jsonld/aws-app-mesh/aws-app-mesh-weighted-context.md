---
class_count: 1
classes:
- WeightedTarget
context_file: json-ld/aws-app-mesh-weighted-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-weighted-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Weighted from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Weighted Context
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
  name: port
  type: string
- container: ''
  name: virtualNode
  type: string
- container: ''
  name: weight
  type: string
property_count: 3
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-weighted-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WeightedTarget\": \"aws:WeightedTarget\",\n    \"port\": {\n      \"@id\": \"aws:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualNode\": {\n      \"@id\": \"aws:virtualNode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"aws:weight\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-weighted-context.jsonld
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
