---
api_specs:
- filename: atandt-wireless-apis.yaml
  format: yaml
  label: AT&T Wireless APIs
  slug: att-wireless-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-wireless-apis.yaml
- filename: atandt-network-apis.yaml
  format: yaml
  label: AT&T 5G Network APIs
  slug: att-network-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-network-apis.yaml
- filename: atandt-enterprise-connectivity-apis.yaml
  format: yaml
  label: AT&T Enterprise Connectivity APIs
  slug: att-enterprise-connectivity-apis
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/openapi/atandt-enterprise-connectivity-apis.yaml
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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://api.att.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"phoneNumber\": \"https://api.att.com/vocab/phoneNumber\",\n    \"maxAge\": {\n      \"@id\": \"https://api.att.com/vocab/maxAge\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"swapped\": {\n      \"@id\": \"https://api.att.com/vocab/swapped\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"connectivityStatus\": \"https://api.att.com/vocab/connectivityStatus\",\n    \"networkGeneration\": \"https://api.att.com/vocab/networkGeneration\",\n    \"roaming\": {\n      \"@id\": \"https://api.att.com/vocab/roaming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"countryCode\": \"https://api.att.com/vocab/countryCode\",\n    \"countryName\": \"https://api.att.com/vocab/countryName\",\n    \"devicePhoneNumberVerified\": {\n      \"@id\": \"https://api.att.com/vocab/devicePhoneNumberVerified\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"qosProfile\": \"https://api.att.com/vocab/qosProfile\",\n    \"duration\": {\n      \"@id\": \"https://api.att.com/vocab/duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sessionId\": \"https://api.att.com/vocab/sessionId\",\n    \"qosStatus\": \"https://api.att.com/vocab/qosStatus\",\n    \"expiresAt\": {\n      \"@id\": \"https://api.att.com/vocab/expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"signalStrength\": \"https://api.att.com/vocab/signalStrength\",\n    \"estimatedDownlinkThroughput\": {\n      \"@id\": \"https://api.att.com/vocab/estimatedDownlinkThroughput\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"estimatedLatency\": {\n      \"@id\": \"https://api.att.com/vocab/estimatedLatency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"congestionLevel\": \"https://api.att.com/vocab/congestionLevel\",\n    \"riskLevel\": \"https://api.att.com/vocab/riskLevel\",\n    \"anomalyScore\": {\n      \"@id\": \"https://api.att.com/vocab/anomalyScore\"\
  ,\n      \"@type\": \"xsd:decimal\"\n    },\n    \"threats\": \"https://api.att.com/vocab/threats\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/atandt/refs/heads/main/json-ld/network-apis-context.jsonld
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
