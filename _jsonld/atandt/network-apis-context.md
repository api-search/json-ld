---
class_count: 0
classes: []
context_file: json-ld/network-apis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/network-apis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Network Apis from AT&T.
layout: jsonld
name: Network Apis Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: phoneNumber
  uri: https://api.att.com/vocab/phoneNumber
- prefix: connectivityStatus
  uri: https://api.att.com/vocab/connectivityStatus
- prefix: networkGeneration
  uri: https://api.att.com/vocab/networkGeneration
- prefix: countryCode
  uri: https://api.att.com/vocab/countryCode
- prefix: countryName
  uri: https://api.att.com/vocab/countryName
- prefix: qosProfile
  uri: https://api.att.com/vocab/qosProfile
- prefix: sessionId
  uri: https://api.att.com/vocab/sessionId
- prefix: qosStatus
  uri: https://api.att.com/vocab/qosStatus
- prefix: signalStrength
  uri: https://api.att.com/vocab/signalStrength
- prefix: congestionLevel
  uri: https://api.att.com/vocab/congestionLevel
- prefix: riskLevel
  uri: https://api.att.com/vocab/riskLevel
- prefix: threats
  uri: https://api.att.com/vocab/threats
properties:
- container: ''
  name: maxAge
  type: integer
- container: ''
  name: swapped
  type: boolean
- container: ''
  name: roaming
  type: boolean
- container: ''
  name: devicePhoneNumberVerified
  type: boolean
- container: ''
  name: duration
  type: integer
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: estimatedDownlinkThroughput
  type: decimal
- container: ''
  name: estimatedLatency
  type: integer
- container: ''
  name: anomalyScore
  type: decimal
property_count: 9
provider_name: AT&T
provider_slug: atandt
slug: network-apis-context
tags:
- Telecommunications
- Fortune 100
- Wireless
- Wireline
- Broadband
- Enterprise
- 5G
- Network
- JSON-LD
- Linked Data
- Semantic Web
---
