---
api_specs:
- filename: vector-observability-api-openapi.yml
  format: yaml
  label: Vector Observability API
  slug: vector-observability-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/openapi/vector-observability-api-openapi.yml
class_count: 1
classes:
- HealthResponse
context_file: json-ld/vector-observability-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/json-ld/vector-observability-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vector Observability Api from Vector.
layout: jsonld
name: Vector Observability Api Context
namespaces:
- prefix: vector
  uri: https://vector.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ok
  type: boolean
property_count: 1
provider_name: Vector
provider_slug: vector
slug: vector-observability-api-context
source_filename: vector-observability-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"vector\": \"https://vector.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HealthResponse\": \"vector:HealthResponse\",\n    \"ok\": {\n      \"@id\": \"vector:ok\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vector/refs/heads/main/json-ld/vector-observability-api-context.jsonld
tags:
- Data Pipeline
- Logs
- Metrics
- Observability
- Open Source
- Rust
- Traces
- JSON-LD
- Linked Data
- Semantic Web
---
