---
class_count: 5
classes:
- IIODevice
- IIOChannel
- IIOContext
- name
- description
context_file: json-ld/analog-devices-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/json-ld/analog-devices-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Analog Devices from Analog Devices.
layout: jsonld
name: Analog Devices Context
namespaces:
- prefix: adi
  uri: https://www.analog.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: label
  type: string
- container: set
  name: channels
  type: ''
- container: ''
  name: attrs
  type: reference
- container: ''
  name: scanElement
  type: boolean
- container: set
  name: devices
  type: ''
property_count: 6
provider_name: Analog Devices
provider_slug: analog-devices
slug: analog-devices-context
source_filename: analog-devices-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"adi\": \"https://www.analog.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"IIODevice\": \"adi:IIODevice\",\n    \"IIOChannel\": \"adi:IIOChannel\",\n    \"IIOContext\": \"adi:IIOContext\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"id\": {\n      \"@id\": \"adi:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"adi:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"adi:channels\",\n      \"@container\": \"@set\"\n    },\n    \"attrs\": {\n      \"@id\": \"adi:attrs\",\n      \"@type\": \"@id\"\n    },\n    \"scanElement\": {\n      \"@id\": \"adi:scan_element\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"devices\": {\n      \"@id\": \"adi:devices\",\n      \"@container\": \"@set\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/analog-devices/refs/heads/main/json-ld/analog-devices-context.jsonld
tags:
- Embedded Systems
- Hardware
- IoT
- Semiconductor
- Signal Processing
- JSON-LD
- Linked Data
- Semantic Web
---
