---
class_count: 4
classes:
- Organization
- Network
- Device
- Client
context_file: json-ld/cisco-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/json-ld/cisco-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cisco from Cisco.
layout: jsonld
name: Cisco Context
namespaces:
- prefix: cisco
  uri: https://cisco.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: serial
  type: string
- container: ''
  name: mac
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: networkId
  type: string
- container: ''
  name: lanIp
  type: string
- container: ''
  name: firmware
  type: string
- container: set
  name: productTypes
  type: ''
- container: set
  name: tags
  type: ''
- container: ''
  name: timeZone
  type: string
- container: ''
  name: ip
  type: string
- container: ''
  name: os
  type: string
- container: ''
  name: status
  type: string
property_count: 14
provider_name: Cisco
provider_slug: cisco
slug: cisco-context
source_filename: cisco-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cisco\": \"https://cisco.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Organization\": \"cisco:Organization\",\n    \"Network\": \"cisco:Network\",\n    \"Device\": \"cisco:Device\",\n    \"Client\": \"cisco:Client\",\n    \"id\": { \"@id\": \"cisco:id\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"serial\": { \"@id\": \"cisco:serial\", \"@type\": \"xsd:string\" },\n    \"mac\": { \"@id\": \"cisco:mac\", \"@type\": \"xsd:string\" },\n    \"model\": { \"@id\": \"cisco:model\", \"@type\": \"xsd:string\" },\n    \"networkId\": { \"@id\": \"cisco:networkId\", \"@type\": \"xsd:string\" },\n    \"lanIp\": { \"@id\": \"cisco:lanIp\", \"@type\": \"xsd:string\" },\n    \"firmware\": { \"@id\": \"cisco:firmware\", \"@type\": \"xsd:string\" },\n    \"productTypes\": { \"@id\": \"cisco:productTypes\",\
  \ \"@container\": \"@set\" },\n    \"tags\": { \"@id\": \"cisco:tags\", \"@container\": \"@set\" },\n    \"timeZone\": { \"@id\": \"cisco:timeZone\", \"@type\": \"xsd:string\" },\n    \"ip\": { \"@id\": \"cisco:ip\", \"@type\": \"xsd:string\" },\n    \"os\": { \"@id\": \"cisco:os\", \"@type\": \"xsd:string\" },\n    \"status\": { \"@id\": \"cisco:status\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cisco/refs/heads/main/json-ld/cisco-context.jsonld
tags:
- Collaboration
- Enterprise
- Networking
- Security
- SD-WAN
- JSON-LD
- Linked Data
- Semantic Web
---
