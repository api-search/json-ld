---
class_count: 0
classes: []
context_file: json-ld/vpn-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vpn/refs/heads/main/json-ld/vpn-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vpn from VPN.
layout: jsonld
name: Vpn Context
namespaces:
- prefix: vpn
  uri: https://en.wikipedia.org/wiki/Virtual_private_network#
- prefix: net
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: iana
  uri: https://www.iana.org/assignments/
- prefix: VirtualPrivateNetwork
  uri: https://schema.org/SoftwareApplication
- prefix: NetworkServer
  uri: https://schema.org/Thing
- prefix: CommunicationProtocol
  uri: https://schema.org/Thing
- prefix: name
  uri: https://schema.org/name
- prefix: description
  uri: https://schema.org/description
- prefix: url
  uri: https://schema.org/url
- prefix: SoftwareApplication
  uri: https://schema.org/SoftwareApplication
- prefix: license
  uri: https://schema.org/license
properties:
- container: ''
  name: vpn:protocol
  type: string
- container: ''
  name: vpn:encryption
  type: string
- container: ''
  name: vpn:tunnelType
  type: string
- container: ''
  name: vpn:serverLoad
  type: decimal
- container: ''
  name: vpn:serverCountry
  type: string
- container: ''
  name: vpn:ipAddress
  type: string
- container: ''
  name: vpn:port
  type: integer
property_count: 7
provider_name: VPN
provider_slug: vpn
slug: vpn-context
source_filename: vpn-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"vpn\": \"https://en.wikipedia.org/wiki/Virtual_private_network#\",\n    \"net\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"iana\": \"https://www.iana.org/assignments/\",\n\n    \"VirtualPrivateNetwork\": \"https://schema.org/SoftwareApplication\",\n    \"NetworkServer\": \"https://schema.org/Thing\",\n    \"CommunicationProtocol\": \"https://schema.org/Thing\",\n\n    \"vpn:protocol\": {\"@type\": \"xsd:string\"},\n    \"vpn:encryption\": {\"@type\": \"xsd:string\"},\n    \"vpn:tunnelType\": {\"@type\": \"xsd:string\"},\n    \"vpn:serverLoad\": {\"@type\": \"xsd:decimal\"},\n    \"vpn:serverCountry\": {\"@type\": \"xsd:string\"},\n    \"vpn:ipAddress\": {\"@type\": \"xsd:string\"},\n    \"vpn:port\": {\"@type\": \"xsd:integer\"},\n\n    \"name\": \"https://schema.org/name\",\n    \"description\": \"https://schema.org/description\",\n    \"url\": \"https://schema.org/url\"\
  ,\n    \"SoftwareApplication\": \"https://schema.org/SoftwareApplication\",\n    \"license\": \"https://schema.org/license\"\n  },\n  \"@graph\": [\n    {\n      \"@id\": \"https://en.wikipedia.org/wiki/Virtual_private_network\",\n      \"@type\": \"VirtualPrivateNetwork\",\n      \"name\": \"Virtual Private Network (VPN)\",\n      \"description\": \"Technology for creating encrypted tunnels for secure network communication, privacy, and access.\",\n      \"vpn:protocols\": [\"WireGuard\", \"OpenVPN\", \"IKEv2\", \"IPSec\", \"L2TP\"]\n    },\n    {\n      \"@id\": \"https://www.wireguard.com/\",\n      \"@type\": \"CommunicationProtocol\",\n      \"name\": \"WireGuard\",\n      \"description\": \"Modern, high-performance VPN protocol using Curve25519 key exchange and ChaCha20-Poly1305 encryption.\",\n      \"url\": \"https://www.wireguard.com/\",\n      \"license\": \"GPLv2\"\n    },\n    {\n      \"@id\": \"https://openvpn.net/\",\n      \"@type\": \"CommunicationProtocol\",\n      \"\
  name\": \"OpenVPN\",\n      \"description\": \"Open-source VPN protocol based on TLS, widely supported across platforms.\",\n      \"url\": \"https://openvpn.net/\",\n      \"license\": \"GPL\"\n    }\n  ]\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vpn/refs/heads/main/json-ld/vpn-context.jsonld
tags:
- Encryption
- Networking
- Privacy
- Security
- VPN
- JSON-LD
- Linked Data
- Semantic Web
---
