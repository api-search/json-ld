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
class_count: 7
classes:
- Device
- ThreatAssessmentRequest
- ThreatIndicator
- ThreatAssessment
- ThreatSubscriptionRequest
- ThreatSubscription
- description
context_file: json-ld/at-t-developer-hub-mobility-threat-anomaly-detection-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-mobility-threat-anomaly-detection-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At T Developer Hub Mobility Threat Anomaly Detection Api from AT&T Developer Hub.
layout: jsonld
name: At T Developer Hub Mobility Threat Anomaly Detection Api Context
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
  name: device
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: detectedAt
  type: dateTime
- container: ''
  name: riskLevel
  type: string
- container: ''
  name: anomalyScore
  type: string
- container: set
  name: threats
  type: reference
- container: ''
  name: assessedAt
  type: dateTime
- container: ''
  name: notificationUrl
  type: reference
- container: ''
  name: minRiskLevel
  type: string
- container: ''
  name: notificationAuthToken
  type: string
- container: ''
  name: subscriptionId
  type: string
- container: ''
  name: status
  type: string
property_count: 14
provider_name: AT&T Developer Hub
provider_slug: at-t-developer-hub
slug: at-t-developer-hub-mobility-threat-anomaly-detection-api-context
source_filename: at-t-developer-hub-mobility-threat-anomaly-detection-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"att\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Device\": \"att:Device\",\n    \"ThreatAssessmentRequest\": \"att:ThreatAssessmentRequest\",\n    \"ThreatIndicator\": \"att:ThreatIndicator\",\n    \"ThreatAssessment\": \"att:ThreatAssessment\",\n    \"ThreatSubscriptionRequest\": \"att:ThreatSubscriptionRequest\",\n    \"ThreatSubscription\": \"att:ThreatSubscription\",\n    \"phoneNumber\": {\n      \"@id\": \"att:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"device\": {\n      \"@id\": \"att:device\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"att:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"att:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"\
  detectedAt\": {\n      \"@id\": \"att:detectedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"riskLevel\": {\n      \"@id\": \"att:riskLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"anomalyScore\": {\n      \"@id\": \"att:anomalyScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threats\": {\n      \"@id\": \"att:threats\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"assessedAt\": {\n      \"@id\": \"att:assessedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"notificationUrl\": {\n      \"@id\": \"att:notificationUrl\",\n      \"@type\": \"@id\"\n    },\n    \"minRiskLevel\": {\n      \"@id\": \"att:minRiskLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationAuthToken\": {\n      \"@id\": \"att:notificationAuthToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionId\": {\n      \"@id\": \"att:subscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"att:status\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-mobility-threat-anomaly-detection-api-context.jsonld
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
