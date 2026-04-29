---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
class_count: 3
classes:
- TagRef
- TagResourceInput
- TagResourceOutput
context_file: json-ld/aws-app-mesh-tag-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tag-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Tag from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Tag Context
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
  name: tags
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
property_count: 3
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-tag-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TagRef\": \"aws:TagRef\",\n    \"TagResourceInput\": \"aws:TagResourceInput\",\n    \"TagResourceOutput\": \"aws:TagResourceOutput\",\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-tag-context.jsonld
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
