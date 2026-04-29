---
api_specs:
- filename: at-t-developer-hub-network-insights-api.yaml
  format: yaml
  label: AT&T Network Insights API
  slug: att-network-insights-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-network-insights-api.yaml
- filename: at-t-developer-hub-mobility-threat-anomaly-detection-api.yaml
  format: yaml
  label: AT&T Mobility Threat and Anomaly Detection API
  slug: att-mobility-threat-anomaly-detection-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-mobility-threat-anomaly-detection-api.yaml
- filename: at-t-developer-hub-sim-swap-api.yaml
  format: yaml
  label: AT&T SIM Swap API
  slug: att-sim-swap-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-sim-swap-api.yaml
- filename: at-t-developer-hub-device-status-api.yaml
  format: yaml
  label: AT&T Device Status API
  slug: att-device-status-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-device-status-api.yaml
- filename: at-t-developer-hub-quality-on-demand-api.yaml
  format: yaml
  label: AT&T Quality on Demand API
  slug: att-quality-on-demand-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-quality-on-demand-api.yaml
- filename: at-t-developer-hub-number-verification-api.yaml
  format: yaml
  label: AT&T Number Verification API
  slug: att-number-verification-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/openapi/at-t-developer-hub-number-verification-api.yaml
class_count: 3
classes:
- Device
- NetworkMetricsRequest
- NetworkMetrics
context_file: json-ld/at-t-developer-hub-network-insights-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-network-insights-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At T Developer Hub Network Insights Api from AT&T Developer Hub.
layout: jsonld
name: At T Developer Hub Network Insights Api Context
namespaces:
- prefix: att
  uri: https://att.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: phoneNumber
  type: string
- container: ''
  name: ipv4Address
  type: reference
- container: ''
  name: publicAddress
  type: string
- container: ''
  name: device
  type: reference
- container: ''
  name: networkGeneration
  type: string
- container: ''
  name: signalStrength
  type: string
- container: ''
  name: estimatedDownlinkThroughput
  type: integer
- container: ''
  name: estimatedUplinkThroughput
  type: integer
- container: ''
  name: estimatedLatency
  type: integer
- container: ''
  name: congestionLevel
  type: string
property_count: 10
provider_name: AT&T Developer Hub
provider_slug: at-t-developer-hub
slug: at-t-developer-hub-network-insights-api-context
source_filename: at-t-developer-hub-network-insights-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"att\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Device\": \"att:Device\",\n    \"NetworkMetricsRequest\": \"att:NetworkMetricsRequest\",\n    \"NetworkMetrics\": \"att:NetworkMetrics\",\n    \"phoneNumber\": {\n      \"@id\": \"att:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipv4Address\": {\n      \"@id\": \"att:ipv4Address\",\n      \"@type\": \"@id\"\n    },\n    \"publicAddress\": {\n      \"@id\": \"att:publicAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"device\": {\n      \"@id\": \"att:device\",\n      \"@type\": \"@id\"\n    },\n    \"networkGeneration\": {\n      \"@id\": \"att:networkGeneration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalStrength\": {\n      \"@id\": \"att:signalStrength\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"estimatedDownlinkThroughput\": {\n      \"@id\": \"att:estimatedDownlinkThroughput\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimatedUplinkThroughput\": {\n      \"@id\": \"att:estimatedUplinkThroughput\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"estimatedLatency\": {\n      \"@id\": \"att:estimatedLatency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"congestionLevel\": {\n      \"@id\": \"att:congestionLevel\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-network-insights-api-context.jsonld
tags:
- 5G
- Network APIs
- CAMARA
- Connectivity
- Telecommunications
- Edge Computing
- Device Status
- SIM Swap
- JSON-LD
- Linked Data
- Semantic Web
---
