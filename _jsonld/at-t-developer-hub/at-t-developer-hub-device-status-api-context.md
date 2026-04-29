---
class_count: 5
classes:
- Device
- DeviceConnectivityRequest
- DeviceConnectivityStatus
- DeviceRoamingRequest
- DeviceRoamingStatus
context_file: json-ld/at-t-developer-hub-device-status-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-device-status-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for At T Developer Hub Device Status Api from AT&T Developer Hub.
layout: jsonld
name: At T Developer Hub Device Status Api Context
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
  name: publicPort
  type: integer
- container: ''
  name: networkAccessIdentifier
  type: string
- container: ''
  name: device
  type: reference
- container: ''
  name: connectivityStatus
  type: string
- container: ''
  name: roaming
  type: boolean
- container: ''
  name: countryCode
  type: integer
- container: set
  name: countryName
  type: string
property_count: 11
provider_name: AT&T Developer Hub
provider_slug: at-t-developer-hub
slug: at-t-developer-hub-device-status-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"att\": \"https://att.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Device\": \"att:Device\",\n    \"DeviceConnectivityRequest\": \"att:DeviceConnectivityRequest\",\n    \"DeviceConnectivityStatus\": \"att:DeviceConnectivityStatus\",\n    \"DeviceRoamingRequest\": \"att:DeviceRoamingRequest\",\n    \"DeviceRoamingStatus\": \"att:DeviceRoamingStatus\",\n    \"phoneNumber\": {\n      \"@id\": \"att:phoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipv4Address\": {\n      \"@id\": \"att:ipv4Address\",\n      \"@type\": \"@id\"\n    },\n    \"publicAddress\": {\n      \"@id\": \"att:publicAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateAddress\": {\n      \"@id\": \"att:privateAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicPort\": {\n      \"@id\": \"att:publicPort\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"networkAccessIdentifier\": {\n      \"@id\": \"att:networkAccessIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"device\": {\n      \"@id\": \"att:device\",\n      \"@type\": \"@id\"\n    },\n    \"connectivityStatus\": {\n      \"@id\": \"att:connectivityStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roaming\": {\n      \"@id\": \"att:roaming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"countryCode\": {\n      \"@id\": \"att:countryCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countryName\": {\n      \"@id\": \"att:countryName\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/at-t-developer-hub/refs/heads/main/json-ld/at-t-developer-hub-device-status-api-context.jsonld
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
