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
- CreateSessionRequest
- SessionInfo
context_file: json-ld/at-t-developer-hub-quality-on-demand-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-quality-on-demand-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At T Developer Hub Quality On Demand Api from AT&T Developer Hub.
layout: jsonld
name: At T Developer Hub Quality On Demand Api Context
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
  name: privateAddress
  type: string
- container: ''
  name: device
  type: reference
- container: ''
  name: qosProfile
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: notificationUrl
  type: reference
- container: ''
  name: notificationAuthToken
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: qosStatus
  type: string
property_count: 13
provider_name: AT&T Developer Hub
provider_slug: at-t-developer-hub
slug: at-t-developer-hub-quality-on-demand-api-context
source_filename: at-t-developer-hub-quality-on-demand-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"att\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Device\": \"att:Device\",\n    \"CreateSessionRequest\": \"att:CreateSessionRequest\",\n    \"SessionInfo\": \"att:SessionInfo\",\n    \"phoneNumber\": {\n      \"@id\": \"att:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipv4Address\": {\n      \"@id\": \"att:ipv4Address\",\n      \"@type\": \"@id\"\n    },\n    \"publicAddress\": {\n      \"@id\": \"att:publicAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateAddress\": {\n      \"@id\": \"att:privateAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"device\": {\n      \"@id\": \"att:device\",\n      \"@type\": \"@id\"\n    },\n    \"qosProfile\": {\n      \"@id\": \"att:qosProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n\
  \      \"@id\": \"att:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"notificationUrl\": {\n      \"@id\": \"att:notificationUrl\",\n      \"@type\": \"@id\"\n    },\n    \"notificationAuthToken\": {\n      \"@id\": \"att:notificationAuthToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"att:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"att:startedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"att:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"qosStatus\": {\n      \"@id\": \"att:qosStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-quality-on-demand-api-context.jsonld
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
