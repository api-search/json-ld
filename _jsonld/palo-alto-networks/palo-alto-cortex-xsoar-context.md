---
class_count: 2
classes:
- Cortex XSOAR Integration Manifest
- script
context_file: json-ld/palo-alto-cortex-xsoar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsoar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Cortex Xsoar from Palo Alto Networks.
layout: jsonld
name: Palo Alto Cortex Xsoar Context
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
- container: set
  name: arguments
  type: ''
- container: ''
  name: category
  type: string
- container: set
  name: commands
  type: ''
- container: set
  name: configuration
  type: ''
- container: ''
  name: contextPath
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: defaultvalue
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: detaileddescription
  type: string
- container: ''
  name: display
  type: string
- container: ''
  name: feed
  type: boolean
- container: ''
  name: fromversion
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: isArray
  type: boolean
- container: ''
  name: isfetch
  type: boolean
- container: ''
  name: longRunning
  type: boolean
- container: ''
  name: longRunningPort
  type: boolean
- container: ''
  name: name
  type: string
- container: set
  name: options
  type: string
- container: set
  name: outputs
  type: ''
- container: ''
  name: required
  type: boolean
- container: ''
  name: runonce
  type: boolean
- container: ''
  name: section
  type: string
- container: ''
  name: toversion
  type: string
- container: ''
  name: type
  type: string
property_count: 25
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-cortex-xsoar-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Cortex XSOAR Integration Manifest\": \"pan:Cortex XSOAR Integration Manifest\",\n    \"arguments\": {\n      \"@id\": \"pan:arguments\",\n      \"@container\": \"@set\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commands\": {\n      \"@id\": \"pan:commands\",\n      \"@container\": \"@set\"\n    },\n    \"configuration\": {\n      \"@id\": \"pan:configuration\",\n      \"@container\": \"@set\"\n    },\n    \"contextPath\": {\n      \"@id\": \"pan:contextPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"pan:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultvalue\": {\n      \"@id\": \"pan:defaultvalue\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detaileddescription\": {\n      \"@id\": \"pan:detaileddescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"display\": {\n      \"@id\": \"pan:display\",\n      \"@type\": \"xsd:string\"\n    },\n    \"feed\": {\n      \"@id\": \"pan:feed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fromversion\": {\n      \"@id\": \"pan:fromversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"pan:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isArray\": {\n      \"@id\": \"pan:isArray\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isfetch\": {\n      \"@id\": \"pan:isfetch\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"longRunning\": {\n      \"@id\": \"pan:longRunning\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"longRunningPort\": {\n      \"@id\": \"pan:longRunningPort\",\n  \
  \    \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"pan:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"pan:outputs\",\n      \"@container\": \"@set\"\n    },\n    \"required\": {\n      \"@id\": \"pan:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"runonce\": {\n      \"@id\": \"pan:runonce\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"script\": \"pan:script\",\n    \"section\": {\n      \"@id\": \"pan:section\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toversion\": {\n      \"@id\": \"pan:toversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-cortex-xsoar-context.jsonld
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
