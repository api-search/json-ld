---
class_count: 0
classes: []
context_file: json-ld/software-defined-networking-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-ld/software-defined-networking-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Defined Networking from Software-Defined Networking.
layout: jsonld
name: Software Defined Networking Context
namespaces:
- prefix: sdn
  uri: https://opennetworking.org/sdn/ns#
- prefix: nml
  uri: http://schemas.ogf.org/nml/2013/05/base#
properties:
- container: ''
  name: Topology
  type: reference
- container: ''
  name: Node
  type: reference
- container: ''
  name: Link
  type: reference
- container: ''
  name: TerminationPoint
  type: reference
- container: ''
  name: FlowRule
  type: reference
- container: ''
  name: SDNController
  type: reference
- container: ''
  name: topology-id
  type: ''
- container: ''
  name: node-id
  type: ''
- container: ''
  name: link-id
  type: ''
- container: ''
  name: ip-address
  type: ''
- container: ''
  name: mac-address
  type: ''
- container: ''
  name: bandwidth
  type: ''
- container: ''
  name: priority
  type: integer
- container: ''
  name: OpenFlow
  type: ''
- container: ''
  name: RESTCONF
  type: ''
- container: ''
  name: NETCONF
  type: ''
- container: ''
  name: OpenDaylight
  type: ''
- container: ''
  name: ONOS
  type: ''
property_count: 18
provider_name: Software-Defined Networking
provider_slug: software-defined-networking
slug: software-defined-networking-context
source_filename: software-defined-networking-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sdn\": \"https://opennetworking.org/sdn/ns#\",\n    \"nml\": \"http://schemas.ogf.org/nml/2013/05/base#\",\n    \"Topology\": {\n      \"@id\": \"nml:Topology\",\n      \"@type\": \"@id\"\n    },\n    \"Node\": {\n      \"@id\": \"nml:Node\",\n      \"@type\": \"@id\"\n    },\n    \"Link\": {\n      \"@id\": \"nml:Link\",\n      \"@type\": \"@id\"\n    },\n    \"TerminationPoint\": {\n      \"@id\": \"nml:Port\",\n      \"@type\": \"@id\"\n    },\n    \"FlowRule\": {\n      \"@id\": \"sdn:FlowRule\",\n      \"@type\": \"@id\"\n    },\n    \"SDNController\": {\n      \"@id\": \"sdn:Controller\",\n      \"@type\": \"@id\"\n    },\n    \"topology-id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"node-id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"link-id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"ip-address\": {\n      \"@id\": \"sdn:ipAddress\"\n    },\n    \"mac-address\"\
  : {\n      \"@id\": \"sdn:macAddress\"\n    },\n    \"bandwidth\": {\n      \"@id\": \"sdn:bandwidth\"\n    },\n    \"priority\": {\n      \"@id\": \"sdn:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"OpenFlow\": {\n      \"@id\": \"sdn:OpenFlow\"\n    },\n    \"RESTCONF\": {\n      \"@id\": \"sdn:RESTCONF\"\n    },\n    \"NETCONF\": {\n      \"@id\": \"sdn:NETCONF\"\n    },\n    \"OpenDaylight\": {\n      \"@id\": \"sdn:OpenDaylightController\"\n    },\n    \"ONOS\": {\n      \"@id\": \"sdn:ONOSController\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-ld/software-defined-networking-context.jsonld
tags:
- Cloud Infrastructure
- Network Architecture
- Networking
- Virtualization
- SDN
- OpenDaylight
- ONOS
- JSON-LD
- Linked Data
- Semantic Web
---
