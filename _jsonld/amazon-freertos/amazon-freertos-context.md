---
api_specs:
- filename: amazon-freertos-openapi.yml
  format: yaml
  label: Amazon FreeRTOS API
  slug: amazon-freertos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/openapi/amazon-freertos-openapi.yml
class_count: 5
classes:
- SoftwareConfiguration
- OtaUpdate
- Device
- OtaFile
- Tag
context_file: json-ld/amazon-freertos-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/json-ld/amazon-freertos-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Freertos from Amazon FreeRTOS.
layout: jsonld
name: Amazon Freertos Context
namespaces:
- prefix: freertos
  uri: https://aws.amazon.com/freertos/vocabulary/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: softwareConfigurationId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: hardwarePlatform
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: otaUpdateId
  type: string
- container: ''
  name: targets
  type: ''
- container: ''
  name: otaUpdateStatus
  type: string
- container: ''
  name: thingName
  type: string
- container: ''
  name: creationDate
  type: dateTime
- container: ''
  name: lastModifiedDate
  type: dateTime
property_count: 11
provider_name: Amazon FreeRTOS
provider_slug: amazon-freertos
slug: amazon-freertos-context
source_filename: amazon-freertos-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"freertos\": \"https://aws.amazon.com/freertos/vocabulary/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SoftwareConfiguration\": \"freertos:SoftwareConfiguration\",\n    \"OtaUpdate\": \"freertos:OtaUpdate\",\n    \"Device\": \"schema:Thing\",\n    \"OtaFile\": \"freertos:OtaFile\",\n    \"Tag\": \"schema:PropertyValue\",\n    \"softwareConfigurationId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hardwarePlatform\": {\n      \"@id\": \"freertos:hardwarePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"freertos:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"otaUpdateId\": {\n \
  \     \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targets\": {\n      \"@id\": \"freertos:targets\"\n    },\n    \"otaUpdateStatus\": {\n      \"@id\": \"freertos:otaUpdateStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingName\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedDate\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-freertos/refs/heads/main/json-ld/amazon-freertos-context.jsonld
tags:
- AWS
- Embedded Systems
- IoT
- Microcontrollers
- RTOS
- JSON-LD
- Linked Data
- Semantic Web
---
