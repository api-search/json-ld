---
class_count: 5
classes:
- CountFilterRequest
- IncidentsCountRequest
- MappingRequest
- ThroughputRequest
- TrendRequest
context_file: json-ld/palo-alto-sase-5g-monitor-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-5g-monitor-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sase 5G Monitor Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sase 5G Monitor Api Context
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
  name: alias
  type: string
- container: ''
  name: enableEmptyInterval
  type: boolean
- container: ''
  name: filter
  type: reference
- container: ''
  name: function
  type: string
- container: ''
  name: histogram
  type: reference
- container: ''
  name: operator
  type: string
- container: ''
  name: pageNum
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: set
  name: properties
  type: reference
- container: ''
  name: property
  type: string
- container: ''
  name: range
  type: string
- container: ''
  name: region
  type: string
- container: set
  name: rules
  type: reference
- container: ''
  name: searchKey
  type: string
- container: set
  name: tenant
  type: string
- container: ''
  name: value
  type: string
- container: set
  name: values
  type: reference
property_count: 17
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sase-5g-monitor-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CountFilterRequest\": \"pan:CountFilterRequest\",\n    \"IncidentsCountRequest\": \"pan:IncidentsCountRequest\",\n    \"MappingRequest\": \"pan:MappingRequest\",\n    \"ThroughputRequest\": \"pan:ThroughputRequest\",\n    \"TrendRequest\": \"pan:TrendRequest\",\n    \"alias\": {\n      \"@id\": \"pan:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableEmptyInterval\": {\n      \"@id\": \"pan:enableEmptyInterval\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"@id\"\n    },\n    \"function\": {\n      \"@id\": \"pan:function\",\n      \"@type\": \"xsd:string\"\n    },\n    \"histogram\": {\n      \"@id\": \"pan:histogram\",\n      \"@type\": \"@id\"\n    },\n    \"\
  operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageNum\": {\n      \"@id\": \"pan:pageNum\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pageSize\": {\n      \"@id\": \"pan:pageSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"properties\": {\n      \"@id\": \"pan:properties\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"property\": {\n      \"@id\": \"pan:property\",\n      \"@type\": \"xsd:string\"\n    },\n    \"range\": {\n      \"@id\": \"pan:range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rules\": {\n      \"@id\": \"pan:rules\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"searchKey\": {\n      \"@id\": \"pan:searchKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenant\": {\n      \"@id\": \"pan:tenant\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"pan:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sase-5g-monitor-api-context.jsonld
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
