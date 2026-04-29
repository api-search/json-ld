---
class_count: 12
classes:
- Address
- AddressGroup
- CommitStatus
- NatRule
- PanOsResponse
- QosRule
- SecurityRule
- Service
- ServiceGroup
- Tag
- VirtualSystem
- line
context_file: json-ld/palo-alto-pan-os-rest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-pan-os-rest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Pan Os Rest Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Pan Os Rest Api Context
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
  name: action
  type: reference
- container: ''
  name: any
  type: reference
- container: ''
  name: application
  type: reference
- container: ''
  name: bi-directional
  type: string
- container: ''
  name: category
  type: reference
- container: ''
  name: class
  type: string
- container: ''
  name: color
  type: string
- container: ''
  name: comments
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: destination
  type: reference
- container: ''
  name: destination-translation
  type: reference
- container: ''
  name: details
  type: reference
- container: ''
  name: disabled
  type: string
- container: ''
  name: display-name
  type: string
- container: ''
  name: dscp-tos
  type: reference
- container: ''
  name: dynamic
  type: reference
- container: ''
  name: dynamic-ip-and-port
  type: reference
- container: ''
  name: filter
  type: string
- container: ''
  name: fqdn
  type: string
- container: ''
  name: from
  type: reference
- container: ''
  name: group
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: import
  type: reference
- container: ''
  name: interface
  type: string
- container: ''
  name: interface-address
  type: reference
- container: ''
  name: ip-netmask
  type: string
- container: ''
  name: ip-range
  type: string
- container: ''
  name: ip-wildcard
  type: string
- container: ''
  name: job
  type: reference
- container: ''
  name: log-end
  type: string
- container: ''
  name: log-setting
  type: string
- container: ''
  name: log-start
  type: string
- container: set
  name: member
  type: string
- container: ''
  name: members
  type: reference
- container: ''
  name: msg
  type: string
- container: ''
  name: nat-type
  type: string
- container: ''
  name: network
  type: reference
- container: ''
  name: port
  type: string
- container: ''
  name: profile-setting
  type: reference
- container: ''
  name: progress
  type: string
- container: ''
  name: protocol
  type: reference
- container: ''
  name: result
  type: reference
- container: ''
  name: service
  type: string
- container: ''
  name: source
  type: reference
- container: ''
  name: source-port
  type: string
- container: ''
  name: source-translation
  type: reference
- container: ''
  name: source-user
  type: reference
- container: ''
  name: static
  type: reference
- container: ''
  name: static-ip
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: tag
  type: reference
- container: ''
  name: tcp
  type: reference
- container: ''
  name: to
  type: reference
- container: ''
  name: translated-address
  type: reference
- container: ''
  name: translated-port
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: udp
  type: reference
property_count: 57
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-pan-os-rest-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Address\": \"pan:Address\",\n    \"AddressGroup\": \"pan:AddressGroup\",\n    \"CommitStatus\": \"pan:CommitStatus\",\n    \"NatRule\": \"pan:NatRule\",\n    \"PanOsResponse\": \"pan:PanOsResponse\",\n    \"QosRule\": \"pan:QosRule\",\n    \"SecurityRule\": \"pan:SecurityRule\",\n    \"Service\": \"pan:Service\",\n    \"ServiceGroup\": \"pan:ServiceGroup\",\n    \"Tag\": \"pan:Tag\",\n    \"VirtualSystem\": \"pan:VirtualSystem\",\n    \"@code\": {\n      \"@id\": \"pan:@code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@name\": {\n      \"@id\": \"pan:@name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@status\": {\n      \"@id\": \"pan:@status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"pan:action\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"any\": {\n      \"@id\": \"pan:any\",\n      \"@type\": \"@id\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@type\": \"@id\"\n    },\n    \"bi-directional\": {\n      \"@id\": \"pan:bi-directional\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"@id\"\n    },\n    \"class\": {\n      \"@id\": \"pan:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"color\": {\n      \"@id\": \"pan:color\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comments\": {\n      \"@id\": \"pan:comments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"pan:destination\",\n      \"@type\": \"@id\"\n    },\n    \"destination-translation\": {\n      \"@id\": \"pan:destination-translation\",\n      \"@type\": \"@id\"\n    },\n\
  \    \"details\": {\n      \"@id\": \"pan:details\",\n      \"@type\": \"@id\"\n    },\n    \"disabled\": {\n      \"@id\": \"pan:disabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"display-name\": {\n      \"@id\": \"pan:display-name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dscp-tos\": {\n      \"@id\": \"pan:dscp-tos\",\n      \"@type\": \"@id\"\n    },\n    \"dynamic\": {\n      \"@id\": \"pan:dynamic\",\n      \"@type\": \"@id\"\n    },\n    \"dynamic-ip-and-port\": {\n      \"@id\": \"pan:dynamic-ip-and-port\",\n      \"@type\": \"@id\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdn\": {\n      \"@id\": \"pan:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@type\": \"@id\"\n    },\n    \"group\": {\n      \"@id\": \"pan:group\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"import\": {\n      \"@id\": \"pan:import\",\n      \"@type\": \"@id\"\n    },\n    \"interface\": {\n      \"@id\": \"pan:interface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interface-address\": {\n      \"@id\": \"pan:interface-address\",\n      \"@type\": \"@id\"\n    },\n    \"ip-netmask\": {\n      \"@id\": \"pan:ip-netmask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip-range\": {\n      \"@id\": \"pan:ip-range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ip-wildcard\": {\n      \"@id\": \"pan:ip-wildcard\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job\": {\n      \"@id\": \"pan:job\",\n      \"@type\": \"@id\"\n    },\n    \"line\": \"pan:line\",\n    \"log-end\": {\n      \"@id\": \"pan:log-end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"log-setting\": {\n      \"@id\": \"pan:log-setting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"log-start\": {\n      \"@id\": \"pan:log-start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"member\"\
  : {\n      \"@id\": \"pan:member\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\": {\n      \"@id\": \"pan:members\",\n      \"@type\": \"@id\"\n    },\n    \"msg\": {\n      \"@id\": \"pan:msg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nat-type\": {\n      \"@id\": \"pan:nat-type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"pan:network\",\n      \"@type\": \"@id\"\n    },\n    \"port\": {\n      \"@id\": \"pan:port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile-setting\": {\n      \"@id\": \"pan:profile-setting\",\n      \"@type\": \"@id\"\n    },\n    \"progress\": {\n      \"@id\": \"pan:progress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"pan:protocol\",\n      \"@type\": \"@id\"\n    },\n    \"result\": {\n      \"@id\": \"pan:result\",\n      \"@type\": \"@id\"\n    },\n    \"service\": {\n      \"@id\": \"pan:service\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@type\": \"@id\"\n    },\n    \"source-port\": {\n      \"@id\": \"pan:source-port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source-translation\": {\n      \"@id\": \"pan:source-translation\",\n      \"@type\": \"@id\"\n    },\n    \"source-user\": {\n      \"@id\": \"pan:source-user\",\n      \"@type\": \"@id\"\n    },\n    \"static\": {\n      \"@id\": \"pan:static\",\n      \"@type\": \"@id\"\n    },\n    \"static-ip\": {\n      \"@id\": \"pan:static-ip\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@type\": \"@id\"\n    },\n    \"tcp\": {\n      \"@id\": \"pan:tcp\",\n      \"@type\": \"@id\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@type\": \"@id\"\n    },\n    \"translated-address\": {\n      \"@id\": \"pan:translated-address\",\n      \"\
  @type\": \"@id\"\n    },\n    \"translated-port\": {\n      \"@id\": \"pan:translated-port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"udp\": {\n      \"@id\": \"pan:udp\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-pan-os-rest-api-context.jsonld
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
