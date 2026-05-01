---
api_specs:
- filename: aws-app-mesh-openapi.yaml
  format: yaml
  label: AWS App Mesh API
  slug: aws-app-mesh-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/openapi/aws-app-mesh-openapi.yaml
class_count: 2
classes:
- Logging
- LoggingFormat
context_file: json-ld/aws-app-mesh-logging-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-logging-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws App Mesh Logging from AWS App Mesh.
layout: jsonld
name: Aws App Mesh Logging Context
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
  name: accessLog
  type: string
- container: ''
  name: json
  type: string
- container: ''
  name: text
  type: string
property_count: 3
provider_name: AWS App Mesh
provider_slug: aws-app-mesh
slug: aws-app-mesh-logging-context
source_filename: aws-app-mesh-logging-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Logging\": \"aws:Logging\",\n    \"LoggingFormat\": \"aws:LoggingFormat\",\n    \"accessLog\": {\n      \"@id\": \"aws:accessLog\",\n      \"@type\": \"xsd:string\"\n    },\n    \"json\": {\n      \"@id\": \"aws:json\",\n      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"aws:text\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-app-mesh/refs/heads/main/json-ld/aws-app-mesh-logging-context.jsonld
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
