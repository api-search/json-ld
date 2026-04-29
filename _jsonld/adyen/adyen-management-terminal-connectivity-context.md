---
class_count: 5
classes:
- TerminalConnectivityBluetooth
- TerminalConnectivityCellular
- TerminalConnectivityEthernet
- TerminalConnectivity
- TerminalConnectivityWifi
context_file: json-ld/adyen-management-terminal-connectivity-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-connectivity-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adyen Management Terminal Connectivity from Adyen.
layout: jsonld
name: Adyen Management Terminal Connectivity Context
namespaces:
- prefix: adyen
  uri: https://docs.adyen.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: macAddress
  type: string
- container: ''
  name: iccid
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: linkNegotiation
  type: string
- container: ''
  name: bluetooth
  type: string
- container: ''
  name: cellular
  type: string
- container: ''
  name: ethernet
  type: string
- container: ''
  name: wifi
  type: string
- container: ''
  name: ssid
  type: string
property_count: 10
provider_name: Adyen
provider_slug: adyen
slug: adyen-management-terminal-connectivity-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adyen\": \"https://docs.adyen.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TerminalConnectivityBluetooth\": \"adyen:TerminalConnectivityBluetooth\",\n    \"TerminalConnectivityCellular\": \"adyen:TerminalConnectivityCellular\",\n    \"TerminalConnectivityEthernet\": \"adyen:TerminalConnectivityEthernet\",\n    \"TerminalConnectivity\": \"adyen:TerminalConnectivity\",\n    \"TerminalConnectivityWifi\": \"adyen:TerminalConnectivityWifi\",\n    \"ipAddress\": {\n      \"@id\": \"adyen:ipAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macAddress\": {\n      \"@id\": \"adyen:macAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iccid\": {\n      \"@id\": \"adyen:iccid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"adyen:status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"linkNegotiation\": {\n      \"@id\": \"adyen:linkNegotiation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bluetooth\": {\n      \"@id\": \"adyen:bluetooth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cellular\": {\n      \"@id\": \"adyen:cellular\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ethernet\": {\n      \"@id\": \"adyen:ethernet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wifi\": {\n      \"@id\": \"adyen:wifi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssid\": {\n      \"@id\": \"adyen:ssid\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adyen/refs/heads/main/json-ld/adyen-management-terminal-connectivity-context.jsonld
tags:
- Payments
- Financial Services
- Fintech
- JSON-LD
- Linked Data
- Semantic Web
---
