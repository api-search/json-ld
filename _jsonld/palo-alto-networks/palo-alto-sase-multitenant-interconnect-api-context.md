---
class_count: 8
classes:
- DedicatedVlanAttachmentDetailsEntry
- IPBlockEntry
- IPPoolRequest
- InterconnectRequest
- PhysicalConnectionEntry
- SettingsEntry
- VlanAttachmentCustomIpAddress
- VlanAttachmentRequest
context_file: json-ld/palo-alto-sase-multitenant-interconnect-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-multitenant-interconnect-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase Multitenant Interconnect Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase Multitenant Interconnect Api Context
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
  name: bandwidth
  type: string
- container: ''
  name: bgpPeerAsn
  type: integer
- container: ''
  name: bgpPeerBfdMinReceiveInterval
  type: integer
- container: ''
  name: bgpPeerBfdMinTransmitInterval
  type: integer
- container: ''
  name: bgpPeerBfdMultiplier
  type: integer
- container: ''
  name: bgpPeerBfdSessionInitMode
  type: string
- container: ''
  name: bgpPeerMd5AuthEnabled
  type: boolean
- container: ''
  name: candidateCloudRouterIpAddress
  type: string
- container: ''
  name: candidateCustomerRouterIpAddress
  type: string
- container: set
  name: cidr
  type: string
- container: ''
  name: cloudProvider
  type: string
- container: set
  name: coloFacilities
  type: string
- container: set
  name: dedicatedConnectionDetails
  type: reference
- container: ''
  name: edgeAvailability
  type: string
- container: ''
  name: edgeLocation
  type: string
- container: ''
  name: egressType
  type: string
- container: set
  name: ipBlocks
  type: reference
- container: ''
  name: ipPool
  type: reference
- container: ''
  name: ipProvider
  type: string
- container: ''
  name: linkType
  type: string
- container: ''
  name: macSecEnabled
  type: boolean
- container: ''
  name: name
  type: string
- container: ''
  name: partnerEmail
  type: string
- container: ''
  name: partnerName
  type: string
- container: ''
  name: physicalConnection
  type: reference
- container: ''
  name: physicalConnectionName
  type: string
- container: ''
  name: primaryAttachmentCustomIpAddress
  type: reference
- container: ''
  name: redundantAttachmentCustomIpAddress
  type: reference
- container: ''
  name: region
  type: string
- container: ''
  name: requestedLinkCount
  type: integer
- container: ''
  name: stackType
  type: string
- container: ''
  name: tsgId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: usage
  type: string
- container: ''
  name: vlanAttachment
  type: reference
property_count: 35
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-multitenant-interconnect-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DedicatedVlanAttachmentDetailsEntry\": \"pan:DedicatedVlanAttachmentDetailsEntry\",\n    \"IPBlockEntry\": \"pan:IPBlockEntry\",\n    \"IPPoolRequest\": \"pan:IPPoolRequest\",\n    \"InterconnectRequest\": \"pan:InterconnectRequest\",\n    \"PhysicalConnectionEntry\": \"pan:PhysicalConnectionEntry\",\n    \"SettingsEntry\": \"pan:SettingsEntry\",\n    \"VlanAttachmentCustomIpAddress\": \"pan:VlanAttachmentCustomIpAddress\",\n    \"VlanAttachmentRequest\": \"pan:VlanAttachmentRequest\",\n    \"bandwidth\": {\n      \"@id\": \"pan:bandwidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpPeerAsn\": {\n      \"@id\": \"pan:bgpPeerAsn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bgpPeerBfdMinReceiveInterval\": {\n      \"@id\": \"\
  pan:bgpPeerBfdMinReceiveInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bgpPeerBfdMinTransmitInterval\": {\n      \"@id\": \"pan:bgpPeerBfdMinTransmitInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bgpPeerBfdMultiplier\": {\n      \"@id\": \"pan:bgpPeerBfdMultiplier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bgpPeerBfdSessionInitMode\": {\n      \"@id\": \"pan:bgpPeerBfdSessionInitMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bgpPeerMd5AuthEnabled\": {\n      \"@id\": \"pan:bgpPeerMd5AuthEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"candidateCloudRouterIpAddress\": {\n      \"@id\": \"pan:candidateCloudRouterIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"candidateCustomerRouterIpAddress\": {\n      \"@id\": \"pan:candidateCustomerRouterIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cidr\": {\n      \"@id\": \"pan:cidr\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  cloudProvider\": {\n      \"@id\": \"pan:cloudProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coloFacilities\": {\n      \"@id\": \"pan:coloFacilities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dedicatedConnectionDetails\": {\n      \"@id\": \"pan:dedicatedConnectionDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"edgeAvailability\": {\n      \"@id\": \"pan:edgeAvailability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"edgeLocation\": {\n      \"@id\": \"pan:edgeLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"egressType\": {\n      \"@id\": \"pan:egressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipBlocks\": {\n      \"@id\": \"pan:ipBlocks\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ipPool\": {\n      \"@id\": \"pan:ipPool\",\n      \"@type\": \"@id\"\n    },\n    \"ipProvider\": {\n      \"@id\": \"pan:ipProvider\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"linkType\": {\n      \"@id\": \"pan:linkType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macSecEnabled\": {\n      \"@id\": \"pan:macSecEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerEmail\": {\n      \"@id\": \"pan:partnerEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerName\": {\n      \"@id\": \"pan:partnerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"physicalConnection\": {\n      \"@id\": \"pan:physicalConnection\",\n      \"@type\": \"@id\"\n    },\n    \"physicalConnectionName\": {\n      \"@id\": \"pan:physicalConnectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryAttachmentCustomIpAddress\": {\n      \"@id\": \"pan:primaryAttachmentCustomIpAddress\",\n      \"@type\": \"@id\"\n    },\n    \"redundantAttachmentCustomIpAddress\": {\n      \"@id\": \"pan:redundantAttachmentCustomIpAddress\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedLinkCount\": {\n      \"@id\": \"pan:requestedLinkCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"stackType\": {\n      \"@id\": \"pan:stackType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tsgId\": {\n      \"@id\": \"pan:tsgId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"usage\": {\n      \"@id\": \"pan:usage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vlanAttachment\": {\n      \"@id\": \"pan:vlanAttachment\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-multitenant-interconnect-api-context.jsonld
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
