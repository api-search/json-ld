---
class_count: 8
classes:
- BandwidthAllocation
- IKEGateway
- IKEGatewayConfig
- IPsecTunnel
- OnboardingStatus
- PrismaAccessLocation
- RemoteNetwork
- RemoteNetworkRequest
context_file: json-ld/palo-alto-sase-config-orchestration-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-config-orchestration-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Config Orchestration Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Config Orchestration Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: allocatedBandwidthMbps
  type: integer
- container: ''
  name: authenticationType
  type: string
- container: ''
  name: availableBandwidthMbps
  type: integer
- container: ''
  name: bandwidthMbps
  type: integer
- container: ''
  name: city
  type: string
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: country
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ikeGateway
  type: reference
- container: ''
  name: ikeVersion
  type: string
- container: ''
  name: ipsecTunnel
  type: reference
- container: ''
  name: licensedBandwidthMbps
  type: integer
- container: ''
  name: localAddress
  type: string
- container: ''
  name: localIp
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: peerId
  type: string
- container: ''
  name: peerIp
  type: string
- container: ''
  name: preSharedKey
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: remoteAddress
  type: string
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: step
  type: string
- container: set
  name: steps
  type: reference
- container: set
  name: subnets
  type: string
- container: ''
  name: tunnelInterface
  type: string
- container: ''
  name: tunnelStatus
  type: string
- container: ''
  name: updatedAt
  type: dateTime
property_count: 34
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-config-orchestration-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BandwidthAllocation\": \"pan:BandwidthAllocation\",\n    \"IKEGateway\": \"pan:IKEGateway\",\n    \"IKEGatewayConfig\": \"pan:IKEGatewayConfig\",\n    \"IPsecTunnel\": \"pan:IPsecTunnel\",\n    \"OnboardingStatus\": \"pan:OnboardingStatus\",\n    \"PrismaAccessLocation\": \"pan:PrismaAccessLocation\",\n    \"RemoteNetwork\": \"pan:RemoteNetwork\",\n    \"RemoteNetworkRequest\": \"pan:RemoteNetworkRequest\",\n    \"allocatedBandwidthMbps\": {\n      \"@id\": \"pan:allocated_bandwidth_mbps\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"authenticationType\": {\n      \"@id\": \"pan:authentication_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availableBandwidthMbps\": {\n      \"@id\": \"pan:available_bandwidth_mbps\",\n      \"\
  @type\": \"xsd:integer\"\n    },\n    \"bandwidthMbps\": {\n      \"@id\": \"pan:bandwidth_mbps\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"city\": {\n      \"@id\": \"pan:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedAt\": {\n      \"@id\": \"pan:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"country\": {\n      \"@id\": \"pan:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ikeGateway\": {\n      \"@id\": \"pan:ike_gateway\",\n      \"\
  @type\": \"@id\"\n    },\n    \"ikeVersion\": {\n      \"@id\": \"pan:ike_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipsecTunnel\": {\n      \"@id\": \"pan:ipsec_tunnel\",\n      \"@type\": \"@id\"\n    },\n    \"licensedBandwidthMbps\": {\n      \"@id\": \"pan:licensed_bandwidth_mbps\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"localAddress\": {\n      \"@id\": \"pan:local_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localIp\": {\n      \"@id\": \"pan:local_ip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"pan:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerId\": {\n      \"@id\": \"pan:peer_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"peerIp\": {\n      \"@id\": \"pan:peer_ip\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"preSharedKey\": {\n      \"@id\": \"pan:pre_shared_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteAddress\": {\n      \"@id\": \"pan:remote_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedAt\": {\n      \"@id\": \"pan:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"step\": {\n      \"@id\": \"pan:step\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"pan:steps\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"subnets\": {\n      \"@id\": \"pan:subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tunnelInterface\": {\n      \"@id\": \"pan:tunnel_interface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tunnelStatus\": {\n      \"@id\": \"pan:tunnel_status\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-config-orchestration-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
