---
api_specs:
- filename: nokia-netact-nbi-openapi.yml
  format: yaml
  label: Nokia NetAct / Ericsson OSS API
  slug: nokia-netact-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/nokia-netact/refs/heads/main/openapi/nokia-netact-nbi-openapi.yml
class_count: 8
classes:
- NetworkElement
- distinguishedName
- location
- address
- siteId
- Alarm
- alarmId
- specificProblem
context_file: json-ld/nokia-netact-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/nokia-netact/refs/heads/main/json-ld/nokia-netact-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Nokia Netact from Nokia NetAct.
layout: jsonld
name: Nokia Netact Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: netact
  uri: https://www.nokia.com/ontology/netact/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: neType
  type: string
- container: ''
  name: technology
  type: string
- container: ''
  name: vendor
  type: string
- container: ''
  name: softwareVersion
  type: string
- container: ''
  name: operationalState
  type: string
- container: ''
  name: administrativeState
  type: string
- container: ''
  name: alarmState
  type: string
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: severity
  type: string
- container: ''
  name: alarmType
  type: string
- container: ''
  name: raisedTime
  type: dateTime
- container: ''
  name: clearedTime
  type: dateTime
property_count: 14
provider_name: Nokia NetAct
provider_slug: nokia-netact
slug: nokia-netact-context
source_filename: nokia-netact-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"netact\": \"https://www.nokia.com/ontology/netact/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"NetworkElement\": \"schema:Place\",\n    \"distinguishedName\": \"schema:identifier\",\n    \"neType\": {\n      \"@id\": \"netact:neType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"technology\": {\n      \"@id\": \"netact:technology\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendor\": {\n      \"@id\": \"schema:brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"softwareVersion\": {\n      \"@id\": \"schema:softwareVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationalState\": {\n      \"@id\": \"netact:operationalState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"administrativeState\": {\n      \"@id\": \"netact:administrativeState\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"alarmState\": {\n      \"@id\": \"netact:alarmState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"schema:ipAddressOfServer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": \"schema:location\",\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"address\": \"schema:address\",\n    \"siteId\": \"schema:identifier\",\n    \"Alarm\": \"schema:Warning\",\n    \"alarmId\": \"schema:identifier\",\n    \"severity\": {\n      \"@id\": \"netact:alarmSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmType\": {\n      \"@id\": \"netact:alarmType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specificProblem\": \"schema:description\",\n    \"raisedTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"clearedTime\": {\n      \"@id\"\
  : \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/nokia-netact/refs/heads/main/json-ld/nokia-netact-context.jsonld
tags:
- Network Management
- OSS
- SNMP
- Telecom
- JSON-LD
- Linked Data
- Semantic Web
---
