---
api_specs:
- filename: routeros-rest-api-openapi.yml
  format: yaml
  label: RouterOS REST API
  slug: routeros-rest-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/openapi/routeros-rest-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/routeros-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-ld/routeros-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Routeros from RouterOS.
layout: jsonld
name: Routeros Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: routeros
  uri: https://help.mikrotik.com/docs/spaces/ROS/vocab#
properties:
- container: ''
  name: RouterOSDevice
  type: reference
- container: ''
  name: RouterOSInterface
  type: reference
- container: ''
  name: RouterOSIpAddress
  type: reference
- container: ''
  name: RouterOSFirewallRule
  type: reference
- container: ''
  name: RouterOSRoute
  type: reference
- container: ''
  name: address
  type: string
- container: ''
  name: interface
  type: string
- container: ''
  name: network
  type: string
- container: ''
  name: gateway
  type: string
- container: ''
  name: macAddress
  type: string
- container: ''
  name: chain
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: uptime
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: cpuLoad
  type: string
- container: ''
  name: freeMemory
  type: string
- container: ''
  name: totalMemory
  type: string
- container: ''
  name: disabled
  type: string
- container: ''
  name: comment
  type: string
- container: ''
  name: ssid
  type: string
- container: ''
  name: signalStrength
  type: string
- container: ''
  name: leaseTime
  type: string
- container: ''
  name: dnsServers
  type: string
property_count: 24
provider_name: RouterOS
provider_slug: routeros
slug: routeros-context
source_filename: routeros-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"routeros\": \"https://help.mikrotik.com/docs/spaces/ROS/vocab#\",\n\n    \"RouterOSDevice\": {\n      \"@id\": \"schema:NetworkDevice\",\n      \"@type\": \"@id\"\n    },\n    \"RouterOSInterface\": {\n      \"@id\": \"routeros:Interface\",\n      \"@type\": \"@id\"\n    },\n    \"RouterOSIpAddress\": {\n      \"@id\": \"routeros:IpAddress\",\n      \"@type\": \"@id\"\n    },\n    \"RouterOSFirewallRule\": {\n      \"@id\": \"routeros:FirewallRule\",\n      \"@type\": \"@id\"\n    },\n    \"RouterOSRoute\": {\n      \"@id\": \"routeros:Route\",\n      \"@type\": \"@id\"\n    },\n\n    \"address\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interface\": {\n      \"@id\": \"routeros:interface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"routeros:network\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"gateway\": {\n      \"@id\": \"routeros:gateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macAddress\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chain\": {\n      \"@id\": \"routeros:chain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"routeros:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"routeros:protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uptime\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuLoad\": {\n      \"@id\": \"routeros:cpuLoad\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freeMemory\": {\n      \"@id\": \"routeros:freeMemory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalMemory\": {\n      \"@id\": \"routeros:totalMemory\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled\": {\n      \"@id\": \"schema:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssid\": {\n      \"@id\": \"routeros:ssid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signalStrength\": {\n      \"@id\": \"routeros:signalStrength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leaseTime\": {\n      \"@id\": \"routeros:leaseTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dnsServers\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/routeros/refs/heads/main/json-ld/routeros-context.jsonld
tags:
- Networking
- Routers
- Network Management
- Firewall
- MikroTik
- JSON-LD
- Linked Data
- Semantic Web
---
