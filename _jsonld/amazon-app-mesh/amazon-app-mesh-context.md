---
class_count: 0
classes: []
context_file: json-ld/amazon-app-mesh-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/json-ld/amazon-app-mesh-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon App Mesh from Amazon App Mesh.
layout: jsonld
name: Amazon App Mesh Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: gatewayRoute
  type: string
property_count: 1
provider_name: Amazon App Mesh
provider_slug: amazon-app-mesh
slug: amazon-app-mesh-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"gatewayRoute\": {\n      \"@id\": \"schema:gatewayRoute\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-app-mesh/refs/heads/main/json-ld/amazon-app-mesh-context.jsonld
tags:
- AWS
- Microservices
- Networking
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
