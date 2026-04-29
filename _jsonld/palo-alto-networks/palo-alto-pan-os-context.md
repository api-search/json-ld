---
class_count: 3
classes:
- PAN-OS Security Rule
- profile-setting
- profiles
context_file: json-ld/palo-alto-pan-os-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-pan-os-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Pan Os from Palo Alto Networks.
layout: jsonld
name: Palo Alto Pan Os Context
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
  type: string
- container: set
  name: application
  type: string
- container: set
  name: data-filtering
  type: string
- container: ''
  name: description
  type: string
- container: set
  name: destination
  type: string
- container: ''
  name: disabled
  type: boolean
- container: set
  name: file-blocking
  type: string
- container: set
  name: from
  type: string
- container: set
  name: group
  type: string
- container: ''
  name: log-end
  type: boolean
- container: ''
  name: log-setting
  type: string
- container: ''
  name: log-start
  type: boolean
- container: ''
  name: name
  type: string
- container: ''
  name: negate-destination
  type: boolean
- container: ''
  name: negate-source
  type: boolean
- container: ''
  name: rule-type
  type: string
- container: ''
  name: schedule
  type: string
- container: set
  name: service
  type: string
- container: set
  name: source
  type: string
- container: set
  name: source-user
  type: string
- container: set
  name: spyware
  type: string
- container: set
  name: tag
  type: string
- container: set
  name: to
  type: string
- container: set
  name: url-filtering
  type: string
- container: set
  name: virus
  type: string
- container: set
  name: vulnerability
  type: string
- container: set
  name: wildfire-analysis
  type: string
property_count: 27
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-pan-os-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"PAN-OS Security Rule\": \"pan:PAN-OS Security Rule\",\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"pan:application\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data-filtering\": {\n      \"@id\": \"pan:data-filtering\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"pan:destination\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabled\": {\n      \"@id\": \"pan:disabled\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"file-blocking\": {\n      \"@id\": \"pan:file-blocking\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"pan:from\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"group\": {\n      \"@id\": \"pan:group\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"log-end\": {\n      \"@id\": \"pan:log-end\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"log-setting\": {\n      \"@id\": \"pan:log-setting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"log-start\": {\n      \"@id\": \"pan:log-start\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"negate-destination\": {\n      \"@id\": \"pan:negate-destination\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"negate-source\": {\n      \"@id\": \"pan:negate-source\",\n      \"@type\": \"xsd:boolean\"\n   \
  \ },\n    \"profile-setting\": \"pan:profile-setting\",\n    \"profiles\": \"pan:profiles\",\n    \"rule-type\": {\n      \"@id\": \"pan:rule-type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"pan:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"pan:service\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source-user\": {\n      \"@id\": \"pan:source-user\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spyware\": {\n      \"@id\": \"pan:spyware\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tag\": {\n      \"@id\": \"pan:tag\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"pan:to\",\n      \"@container\": \"@set\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"url-filtering\": {\n      \"@id\": \"pan:url-filtering\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virus\": {\n      \"@id\": \"pan:virus\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerability\": {\n      \"@id\": \"pan:vulnerability\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"wildfire-analysis\": {\n      \"@id\": \"pan:wildfire-analysis\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-pan-os-context.jsonld
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
