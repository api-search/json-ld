---
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
