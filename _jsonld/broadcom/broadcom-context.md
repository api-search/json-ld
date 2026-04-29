---
class_count: 3
classes:
- name
- description
- status
context_file: json-ld/broadcom-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/json-ld/broadcom-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Broadcom from Broadcom.
layout: jsonld
name: Broadcom Context
namespaces:
- prefix: broadcom
  uri: https://developer.broadcom.com/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
properties:
- container: ''
  name: vm
  type: string
- container: ''
  name: power_state
  type: string
- container: ''
  name: cpu_count
  type: integer
- container: ''
  name: memory_size_MiB
  type: integer
- container: ''
  name: guest_OS
  type: string
- container: ''
  name: fqdn
  type: string
- container: ''
  name: connection_state
  type: string
- container: ''
  name: ha_enabled
  type: boolean
- container: ''
  name: drs_enabled
  type: boolean
- container: ''
  name: vsan_enabled
  type: boolean
- container: ''
  name: severity
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: creatorId
  type: string
- container: ''
  name: workloadDomainType
  type: string
- container: ''
  name: isCancellable
  type: boolean
- container: ''
  name: isRetryable
  type: boolean
- container: ''
  name: creationTimestamp
  type: dateTime
- container: ''
  name: completionTimestamp
  type: dateTime
property_count: 18
provider_name: Broadcom
provider_slug: broadcom
slug: broadcom-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"broadcom\": \"https://developer.broadcom.com/\",\n    \"vm\": {\n      \"@id\": \"broadcom:vm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"power_state\": {\n      \"@id\": \"broadcom:power_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpu_count\": {\n      \"@id\": \"broadcom:cpu_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"memory_size_MiB\": {\n      \"@id\": \"broadcom:memory_size_MiB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"guest_OS\": {\n      \"@id\": \"broadcom:guest_OS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fqdn\": {\n      \"@id\": \"broadcom:fqdn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connection_state\": {\n      \"@id\": \"broadcom:connection_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ha_enabled\": {\n      \"@id\": \"broadcom:ha_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"drs_enabled\": {\n      \"@id\"\
  : \"broadcom:drs_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"vsan_enabled\": {\n      \"@id\": \"broadcom:vsan_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"severity\": {\n      \"@id\": \"broadcom:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"broadcom:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorId\": {\n      \"@id\": \"broadcom:creatorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workloadDomainType\": {\n      \"@id\": \"broadcom:workloadDomainType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isCancellable\": {\n      \"@id\": \"broadcom:isCancellable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRetryable\": {\n      \"@id\": \"broadcom:isRetryable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"broadcom:creationTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completionTimestamp\": {\n      \"@id\": \"\
  broadcom:completionTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"schema:status\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/broadcom/refs/heads/main/json-ld/broadcom-context.jsonld
tags:
- Cloud Infrastructure
- Gateways
- Management
- Networks
- Observability
- Virtualization
- JSON-LD
- Linked Data
- Semantic Web
---
