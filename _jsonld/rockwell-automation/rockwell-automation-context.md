---
class_count: 7
classes:
- ManufacturingOrganization
- IndustrialAutomationSystem
- PLC
- Tag
- ERPSystem
- ManufacturingProject
- DigitalTwin
context_file: json-ld/rockwell-automation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rockwell-automation/refs/heads/main/json-ld/rockwell-automation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rockwell Automation from Rockwell Automation.
layout: jsonld
name: Rockwell Automation Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ra
  uri: https://api-evangelist.github.io/rockwell-automation/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: version
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: environment
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: tagName
  type: string
- container: ''
  name: tagValue
  type: ''
- container: ''
  name: dataType
  type: string
- container: ''
  name: engineeringUnit
  type: string
- container: ''
  name: customer
  type: reference
- container: ''
  name: orderDate
  type: dateTime
- container: ''
  name: product
  type: reference
- container: ''
  name: quantity
  type: integer
property_count: 15
provider_name: Rockwell Automation
provider_slug: rockwell-automation
slug: rockwell-automation-context
source_filename: rockwell-automation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ra\": \"https://api-evangelist.github.io/rockwell-automation/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ManufacturingOrganization\": \"schema:Organization\",\n    \"IndustrialAutomationSystem\": \"ra:IndustrialAutomationSystem\",\n    \"PLC\": \"ra:PLC\",\n    \"Tag\": \"ra:Tag\",\n    \"ERPSystem\": \"ra:ERPSystem\",\n    \"ManufacturingProject\": \"ra:ManufacturingProject\",\n    \"DigitalTwin\": \"ra:DigitalTwin\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n\
  \      \"@type\": \"@id\"\n    },\n    \"environment\": {\n      \"@id\": \"ra:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"ra:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagName\": {\n      \"@id\": \"ra:tagName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagValue\": {\n      \"@id\": \"ra:tagValue\"\n    },\n    \"dataType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engineeringUnit\": {\n      \"@id\": \"schema:unitCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customer\": {\n      \"@id\": \"schema:customer\",\n      \"@type\": \"@id\"\n    },\n    \"orderDate\": {\n      \"@id\": \"schema:orderDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"product\": {\n      \"@id\": \"schema:product\",\n      \"@type\": \"@id\"\n    },\n    \"quantity\": {\n      \"@id\": \"schema:quantity\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rockwell-automation/refs/heads/main/json-ld/rockwell-automation-context.jsonld
tags:
- Industrial Automation
- Manufacturing
- PLC
- SCADA
- IIoT
- JSON-LD
- Linked Data
- Semantic Web
---
