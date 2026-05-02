---
api_specs:
- filename: lunar-dev-gateway-admin-openapi.yml
  format: yaml
  label: Lunar.dev Gateway Admin API
  slug: gateway-admin
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-admin-openapi.yml
- filename: lunar-dev-gateway-proxy-openapi.yml
  format: yaml
  label: Lunar.dev Gateway Proxy API
  slug: gateway-proxy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/openapi/lunar-dev-gateway-proxy-openapi.yml
class_count: 0
classes: []
context_file: json-ld/lunar-dev-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/json-ld/lunar-dev-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Lunar Dev from Lunar.dev.
layout: jsonld
name: Lunar Dev Context
namespaces:
- prefix: lunar
  uri: https://docs.lunar.dev/
properties:
- container: ''
  name: HealthStatus
  type: ''
- container: ''
  name: DiscoveredEndpoint
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Flow
  type: ''
- container: ''
  name: ValidationResult
  type: ''
property_count: 5
provider_name: Lunar.dev
provider_slug: lunar-dev
slug: lunar-dev-context
source_filename: lunar-dev-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"lunar\": \"https://docs.lunar.dev/\",\n    \"HealthStatus\": {\n      \"@id\": \"lunar:product-features/health-check\",\n      \"@context\": {\n        \"status\": \"https://schema.org/status\"\n      }\n    },\n    \"DiscoveredEndpoint\": {\n      \"@id\": \"lunar:product-features/endpoint-discovery\",\n      \"@context\": {\n        \"method\": \"https://schema.org/httpMethod\",\n        \"url\": \"https://schema.org/url\",\n        \"status_codes\": \"https://schema.org/measuredValue\",\n        \"count\": \"https://schema.org/interactionCount\",\n        \"average_latency_ms\": \"https://schema.org/duration\"\n      }\n    },\n    \"Policy\": {\n      \"@id\": \"lunar:product-features/policies\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"enabled\": \"https://schema.org/status\",\n        \"endpoint\"\
  : \"https://schema.org/urlTemplate\",\n        \"method\": \"https://schema.org/httpMethod\",\n        \"type\": \"https://schema.org/category\",\n        \"config\": \"https://schema.org/PropertyValue\",\n        \"consumer_tag\": \"https://schema.org/identifier\"\n      }\n    },\n    \"Flow\": {\n      \"@id\": \"lunar:product-features/flows\",\n      \"@context\": {\n        \"name\": \"https://schema.org/name\",\n        \"description\": \"https://schema.org/description\",\n        \"enabled\": \"https://schema.org/status\",\n        \"filter\": \"https://schema.org/filter\",\n        \"processors\": \"https://schema.org/hasPart\"\n      }\n    },\n    \"ValidationResult\": {\n      \"@id\": \"lunar:product-features/validation\",\n      \"@context\": {\n        \"valid\": \"https://schema.org/status\",\n        \"errors\": \"https://schema.org/error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/lunar-dev/refs/heads/main/json-ld/lunar-dev-context.jsonld
tags:
- AI Gateway
- Automation
- Consumption Gateway
- Control
- Deployment
- Integrations
- MCP Gateway
- Performance
- Platform
- Version Control
- Visibility
- Workflows
- JSON-LD
- Linked Data
- Semantic Web
---
