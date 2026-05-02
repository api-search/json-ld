---
api_specs:
- filename: kuma-api-openapi.yml
  format: yaml
  label: Kuma API
  slug: kuma-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/openapi/kuma-api-openapi.yml
class_count: 20
classes:
- name
- description
- type
- mesh
- dataplane
- zone
- policy
- targetRef
- from
- to
- labels
- Mesh
- Dataplane
- MeshTrafficPermission
- MeshRetry
- MeshTimeout
- MeshCircuitBreaker
- MeshHealthCheck
- MeshFaultInjection
- MeshRateLimit
context_file: json-ld/kuma-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/json-ld/kuma-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kuma from Kuma.
layout: jsonld
name: Kuma Context
namespaces:
- prefix: kuma
  uri: https://kuma.io/docs/latest/reference/
properties: []
property_count: 0
provider_name: Kuma
provider_slug: kuma
slug: kuma-context
source_filename: kuma-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"kuma\": \"https://kuma.io/docs/latest/reference/\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"mesh\": \"kuma:mesh\",\n    \"dataplane\": \"kuma:dataplane\",\n    \"zone\": \"kuma:zone\",\n    \"policy\": \"kuma:policy\",\n    \"targetRef\": \"kuma:targetRef\",\n    \"from\": \"kuma:from\",\n    \"to\": \"kuma:to\",\n    \"labels\": \"kuma:labels\",\n    \"Mesh\": \"kuma:Mesh\",\n    \"Dataplane\": \"kuma:Dataplane\",\n    \"MeshTrafficPermission\": \"kuma:MeshTrafficPermission\",\n    \"MeshRetry\": \"kuma:MeshRetry\",\n    \"MeshTimeout\": \"kuma:MeshTimeout\",\n    \"MeshCircuitBreaker\": \"kuma:MeshCircuitBreaker\",\n    \"MeshHealthCheck\": \"kuma:MeshHealthCheck\",\n    \"MeshFaultInjection\": \"kuma:MeshFaultInjection\",\n    \"MeshRateLimit\": \"kuma:MeshRateLimit\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kuma/refs/heads/main/json-ld/kuma-context.jsonld
tags:
- Envoy
- Kubernetes
- Microservices
- Security
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
