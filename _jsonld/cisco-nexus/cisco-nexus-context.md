---
class_count: 3
classes:
- ietf
- ietf-if
- ieee802
context_file: json-ld/cisco-nexus-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco-nexus/refs/heads/main/json-ld/cisco-nexus-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco Nexus from Cisco Nexus Dashboard.
layout: jsonld
name: Cisco Nexus Context
namespaces:
- prefix: cisco
  uri: https://developer.cisco.com/docs/nexus-model/latest/#
- prefix: nxos
  uri: https://developer.cisco.com/docs/nx-os/
- prefix: nxapi
  uri: https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: NexusSwitch
  type: ''
- container: ''
  name: PhysicalInterface
  type: ''
- container: ''
  name: SviInterface
  type: ''
- container: ''
  name: VlanBridgeDomain
  type: ''
- container: ''
  name: Ipv4StaticRoute
  type: ''
- container: ''
  name: Ipv4Nexthop
  type: ''
- container: ''
  name: BgpInstance
  type: ''
- container: ''
  name: BgpDomain
  type: ''
- container: ''
  name: BgpPeer
  type: ''
- container: ''
  name: EthernetStatistics
  type: ''
- container: ''
  name: VlanStatistics
  type: ''
- container: set
  name: interfaces
  type: reference
- container: set
  name: vlans
  type: reference
- container: set
  name: routes
  type: reference
- container: ''
  name: bgp
  type: reference
property_count: 15
provider_name: Cisco Nexus Dashboard
provider_slug: cisco-nexus
slug: cisco-nexus-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"cisco\": \"https://developer.cisco.com/docs/nexus-model/latest/#\",\n    \"nxos\": \"https://developer.cisco.com/docs/nx-os/\",\n    \"nxapi\": \"https://developer.cisco.com/docs/cisco-nexus-3000-and-9000-series-nx-api-rest-sdk-user-guide-and-api-reference/latest/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"ietf\": \"urn:ietf:params:xml:ns:yang:\",\n    \"ietf-if\": \"urn:ietf:params:xml:ns:yang:ietf-interfaces:\",\n    \"ieee802\": \"urn:ieee:std:802.1Q:yang:\",\n\n    \"NexusSwitch\": {\n      \"@id\": \"cisco:topSystem\",\n      \"@context\": {\n        \"hostname\": {\n          \"@id\": \"cisco:topSystem/name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serialNumber\": {\n          \"@id\": \"cisco:topSystem/serial\",\n          \"@type\"\
  : \"xsd:string\"\n        },\n        \"softwareVersion\": {\n          \"@id\": \"cisco:topSystem/version\",\n          \"@type\": \"xsd:string\"\n        },\n        \"systemState\": {\n          \"@id\": \"cisco:topSystem/state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastBootTime\": {\n          \"@id\": \"cisco:topSystem/upTs\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"PhysicalInterface\": {\n      \"@id\": \"cisco:l1PhysIf\",\n      \"@context\": {\n        \"distinguishedName\": {\n          \"@id\": \"cisco:l1PhysIf/dn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"interfaceId\": {\n          \"@id\": \"cisco:l1PhysIf/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"ietf-if:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"cisco:l1PhysIf/descr\",\n          \"@type\": \"xsd:string\"\n        },\n     \
  \   \"adminState\": {\n          \"@id\": \"cisco:l1PhysIf/adminSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operState\": {\n          \"@id\": \"cisco:l1PhysIf/operSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"layer\": {\n          \"@id\": \"cisco:l1PhysIf/layer\",\n          \"@type\": \"xsd:string\"\n        },\n        \"switchportMode\": {\n          \"@id\": \"cisco:l1PhysIf/mode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"speed\": {\n          \"@id\": \"cisco:l1PhysIf/speed\",\n          \"@type\": \"xsd:string\"\n        },\n        \"duplex\": {\n          \"@id\": \"cisco:l1PhysIf/duplex\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mtu\": {\n          \"@id\": \"cisco:l1PhysIf/mtu\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bandwidth\": {\n          \"@id\": \"cisco:l1PhysIf/bw\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"accessVlan\": {\n          \"@id\": \"\
  cisco:l1PhysIf/accessVlan\",\n          \"@type\": \"@id\"\n        },\n        \"trunkVlans\": {\n          \"@id\": \"cisco:l1PhysIf/trunkVlans\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nativeVlan\": {\n          \"@id\": \"cisco:l1PhysIf/nativeVlan\",\n          \"@type\": \"@id\"\n        },\n        \"lastModified\": {\n          \"@id\": \"cisco:l1PhysIf/modTs\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"SviInterface\": {\n      \"@id\": \"cisco:sviIf\",\n      \"@context\": {\n        \"distinguishedName\": {\n          \"@id\": \"cisco:sviIf/dn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"interfaceId\": {\n          \"@id\": \"cisco:sviIf/id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"cisco:sviIf/descr\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminState\": {\n          \"@id\": \"cisco:sviIf/adminSt\",\n          \"@type\": \"\
  xsd:string\"\n        },\n        \"operState\": {\n          \"@id\": \"cisco:sviIf/operSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"mtu\": {\n          \"@id\": \"cisco:sviIf/mtu\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bandwidth\": {\n          \"@id\": \"cisco:sviIf/bw\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"macAddress\": {\n          \"@id\": \"cisco:sviIf/mac\",\n          \"@type\": \"xsd:string\"\n        },\n        \"medium\": {\n          \"@id\": \"cisco:sviIf/medium\",\n          \"@type\": \"xsd:string\"\n        },\n        \"autostate\": {\n          \"@id\": \"cisco:sviIf/autostate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"lastModified\": {\n          \"@id\": \"cisco:sviIf/modTs\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"VlanBridgeDomain\": {\n      \"@id\": \"cisco:l2BD\",\n      \"@context\": {\n        \"distinguishedName\": {\n          \"\
  @id\": \"cisco:l2BD/dn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fabricEncapsulation\": {\n          \"@id\": \"cisco:l2BD/fabEncap\",\n          \"@type\": \"xsd:string\"\n        },\n        \"vlanName\": {\n          \"@id\": \"cisco:l2BD/name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"policyControlTag\": {\n          \"@id\": \"cisco:l2BD/pcTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminState\": {\n          \"@id\": \"cisco:l2BD/adminSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operState\": {\n          \"@id\": \"cisco:l2BD/operSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"bridgeDomainId\": {\n          \"@id\": \"cisco:l2BD/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"bridgeMode\": {\n          \"@id\": \"cisco:l2BD/bridgeMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"forwardingMode\": {\n          \"@id\": \"cisco:l2BD/fwdMode\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"lastModified\": {\n          \"@id\": \"cisco:l2BD/modTs\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Ipv4StaticRoute\": {\n      \"@id\": \"cisco:ipv4Route\",\n      \"@context\": {\n        \"distinguishedName\": {\n          \"@id\": \"cisco:ipv4Route/dn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prefix\": {\n          \"@id\": \"cisco:ipv4Route/prefix\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nexthops\": {\n          \"@id\": \"cisco:ipv4Route/children\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Ipv4Nexthop\": {\n      \"@id\": \"cisco:ipv4Nexthop\",\n      \"@context\": {\n        \"nexthopAddress\": {\n          \"@id\": \"cisco:ipv4Nexthop/nhAddr\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nexthopInterface\": {\n          \"@id\": \"cisco:ipv4Nexthop/nhIf\",\n     \
  \     \"@type\": \"xsd:string\"\n        },\n        \"nexthopVrf\": {\n          \"@id\": \"cisco:ipv4Nexthop/nhVrf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"preference\": {\n          \"@id\": \"cisco:ipv4Nexthop/pref\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"routeName\": {\n          \"@id\": \"cisco:ipv4Nexthop/rtname\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tag\": {\n          \"@id\": \"cisco:ipv4Nexthop/tag\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"BgpInstance\": {\n      \"@id\": \"cisco:bgpInst\",\n      \"@context\": {\n        \"autonomousSystemNumber\": {\n          \"@id\": \"cisco:bgpInst/asn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminState\": {\n          \"@id\": \"cisco:bgpEntity/adminSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"domains\": {\n          \"@id\": \"cisco:bgpInst/children\",\n          \"@type\": \"@id\",\n   \
  \       \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"BgpDomain\": {\n      \"@id\": \"cisco:bgpDom\",\n      \"@context\": {\n        \"domainName\": {\n          \"@id\": \"cisco:bgpDom/name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"routerId\": {\n          \"@id\": \"cisco:bgpDom/rtrId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"peers\": {\n          \"@id\": \"cisco:bgpDom/children\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"BgpPeer\": {\n      \"@id\": \"cisco:bgpPeer\",\n      \"@context\": {\n        \"peerAddress\": {\n          \"@id\": \"cisco:bgpPeer/addr\",\n          \"@type\": \"xsd:string\"\n        },\n        \"remoteAsn\": {\n          \"@id\": \"cisco:bgpPeer/asn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"adminState\": {\n          \"@id\": \"cisco:bgpPeer/adminSt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceInterface\"\
  : {\n          \"@id\": \"cisco:bgpPeer/srcIf\",\n          \"@type\": \"xsd:string\"\n        },\n        \"passwordType\": {\n          \"@id\": \"cisco:bgpPeer/passwdType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"EthernetStatistics\": {\n      \"@id\": \"cisco:rmonEtherStats\",\n      \"@context\": {\n        \"broadcastPackets\": {\n          \"@id\": \"cisco:rmonEtherStats/broadcastPkts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"multicastPackets\": {\n          \"@id\": \"cisco:rmonEtherStats/multicastPkts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalOctets\": {\n          \"@id\": \"cisco:rmonEtherStats/octets\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"crcErrors\": {\n          \"@id\": \"cisco:rmonEtherStats/cRCAlignErrors\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dropEvents\": {\n          \"@id\": \"cisco:rmonEtherStats/dropEvents\",\n          \"@type\":\
  \ \"xsd:integer\"\n        },\n        \"collisions\": {\n          \"@id\": \"cisco:rmonEtherStats/collisions\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"VlanStatistics\": {\n      \"@id\": \"cisco:l2VlanStats\",\n      \"@context\": {\n        \"inboundBroadcastPackets\": {\n          \"@id\": \"cisco:l2VlanStats/inBcastPkts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inboundMulticastPackets\": {\n          \"@id\": \"cisco:l2VlanStats/inMcastPkts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"inboundUnicastPackets\": {\n          \"@id\": \"cisco:l2VlanStats/inUcastPkts\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"outboundUnicastPackets\": {\n          \"@id\": \"cisco:l2VlanStats/outUcastPkts\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"interfaces\": {\n      \"@id\": \"cisco:interfaceEntity\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n\
  \    \"vlans\": {\n      \"@id\": \"cisco:bdEntity\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"routes\": {\n      \"@id\": \"cisco:ipv4Inst\",\n      \"@type\": \"@id\",\n      \"@container\": \"@set\"\n    },\n    \"bgp\": {\n      \"@id\": \"cisco:bgpEntity\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco-nexus/refs/heads/main/json-ld/cisco-nexus-context.jsonld
tags:
- Data Center
- Infrastructure
- Network Automation
- Networking
- SDN
- Switches
- JSON-LD
- Linked Data
- Semantic Web
---
