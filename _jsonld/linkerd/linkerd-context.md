---
api_specs:
- filename: linkerd-proxy-admin-openapi.yml
  format: yaml
  label: Linkerd Proxy Admin API
  slug: proxy-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-proxy-admin-openapi.yml
- filename: linkerd-viz-metrics-openapi.yml
  format: yaml
  label: Linkerd Viz Metrics API
  slug: viz-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-viz-metrics-openapi.yml
- filename: linkerd-tap-openapi.yml
  format: yaml
  label: Linkerd Tap API
  slug: tap-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/openapi/linkerd-tap-openapi.yml
class_count: 0
classes: []
context_file: json-ld/linkerd-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/json-ld/linkerd-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Linkerd from Linkerd.
layout: jsonld
name: Linkerd Context
namespaces:
- prefix: linkerd
  uri: https://linkerd.io/2-edge/reference/
properties:
- container: ''
  name: TapEvent
  type: ''
- container: ''
  name: StatSummary
  type: ''
- container: ''
  name: Edge
  type: ''
- container: ''
  name: Gateway
  type: ''
- container: ''
  name: Resource
  type: ''
- container: ''
  name: TcpAddress
  type: ''
property_count: 6
provider_name: Linkerd
provider_slug: linkerd
slug: linkerd-context
source_filename: linkerd-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"linkerd\": \"https://linkerd.io/2-edge/reference/\",\n    \"TapEvent\": {\n      \"@id\": \"linkerd:cli/viz/\",\n      \"@context\": {\n        \"source\": \"https://schema.org/sender\",\n        \"source_meta\": \"https://schema.org/additionalProperty\",\n        \"destination\": \"https://schema.org/recipient\",\n        \"destination_meta\": \"https://schema.org/additionalProperty\",\n        \"route_meta\": \"https://schema.org/additionalProperty\",\n        \"proxy_direction\": \"https://schema.org/direction\",\n        \"request_init\": \"https://schema.org/potentialAction\",\n        \"response_init\": \"https://schema.org/result\",\n        \"response_end\": \"https://schema.org/result\",\n        \"method\": \"https://schema.org/httpMethod\",\n        \"path\": \"https://schema.org/urlTemplate\",\n        \"authority\": \"https://schema.org/hostingOrganization\",\n        \"http_status\": \"https://schema.org/statusCode\"\
  ,\n        \"latency_ns\": \"https://schema.org/duration\",\n        \"duration_ns\": \"https://schema.org/duration\",\n        \"labels\": \"https://schema.org/keywords\"\n      }\n    },\n    \"StatSummary\": {\n      \"@id\": \"linkerd:cli/viz/\",\n      \"@context\": {\n        \"resource\": \"https://schema.org/about\",\n        \"time_window\": \"https://schema.org/duration\",\n        \"status\": \"https://schema.org/status\",\n        \"meshed_pod_count\": \"https://schema.org/quantity\",\n        \"running_pod_count\": \"https://schema.org/quantity\",\n        \"failed_pod_count\": \"https://schema.org/quantity\",\n        \"success_count\": \"https://schema.org/quantity\",\n        \"failure_count\": \"https://schema.org/quantity\",\n        \"latency_ms_p50\": \"https://schema.org/duration\",\n        \"latency_ms_p95\": \"https://schema.org/duration\",\n        \"latency_ms_p99\": \"https://schema.org/duration\"\n      }\n    },\n    \"Edge\": {\n      \"@id\": \"linkerd:cli/viz/\"\
  ,\n      \"@context\": {\n        \"src\": \"https://schema.org/sender\",\n        \"dst\": \"https://schema.org/recipient\",\n        \"client_id\": \"https://schema.org/identifier\",\n        \"server_id\": \"https://schema.org/identifier\",\n        \"no_identity_msg\": \"https://schema.org/description\"\n      }\n    },\n    \"Gateway\": {\n      \"@id\": \"linkerd:cli/viz/\",\n      \"@context\": {\n        \"namespace\": \"https://schema.org/isPartOf\",\n        \"name\": \"https://schema.org/name\",\n        \"cluster_name\": \"https://schema.org/name\",\n        \"paired_services\": \"https://schema.org/quantity\",\n        \"alive\": \"https://schema.org/status\",\n        \"latency_ms_p50\": \"https://schema.org/duration\",\n        \"latency_ms_p95\": \"https://schema.org/duration\",\n        \"latency_ms_p99\": \"https://schema.org/duration\"\n      }\n    },\n    \"Resource\": {\n      \"@id\": \"linkerd:cli/viz/\",\n      \"@context\": {\n        \"namespace\": \"https://schema.org/isPartOf\"\
  ,\n        \"type\": \"https://schema.org/category\",\n        \"name\": \"https://schema.org/name\"\n      }\n    },\n    \"TcpAddress\": {\n      \"@id\": \"linkerd:proxy-configuration/\",\n      \"@context\": {\n        \"ip\": \"https://schema.org/identifier\",\n        \"port\": \"https://schema.org/identifier\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/linkerd/refs/heads/main/json-ld/linkerd-context.jsonld
tags:
- Kubernetes
- mTLS
- Observability
- Security
- Service Mesh
- JSON-LD
- Linked Data
- Semantic Web
---
