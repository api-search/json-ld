---
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
