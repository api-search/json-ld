---
class_count: 0
classes: []
context_file: json-ld/sanmina-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sanmina/refs/heads/main/json-ld/sanmina-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sanmina from Sanmina.
layout: jsonld
name: Sanmina Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sanmina
  uri: https://api-evangelist.github.io/sanmina/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Sanmina
  type: ''
- container: ''
  name: ManufacturingExecutionSystem
  type: schema:SoftwareApplication
- container: ''
  name: WorkOrder
  type: schema:Order
- container: ''
  name: ProductionRun
  type: schema:Event
- container: ''
  name: TraceabilityRecord
  type: schema:ItemList
- container: ''
  name: QualityEvent
  type: schema:Event
- container: ''
  name: 42QMes
  type: schema:SoftwareApplication
- container: ''
  name: workOrderId
  type: string
- container: ''
  name: serialNumber
  type: string
- container: ''
  name: lotNumber
  type: string
- container: ''
  name: plant
  type: schema:Place
property_count: 11
provider_name: Sanmina
provider_slug: sanmina
slug: sanmina-context
source_filename: sanmina-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sanmina\": \"https://api-evangelist.github.io/sanmina/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Sanmina\": {\n      \"@id\": \"schema:Organization\",\n      \"schema:name\": \"Sanmina Corporation\",\n      \"schema:description\": \"Global contract manufacturer and end-to-end manufacturing solutions provider\"\n    },\n\n    \"ManufacturingExecutionSystem\": {\n      \"@id\": \"sanmina:MES\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:description\": \"System that tracks and controls manufacturing operations\"\n    },\n\n    \"WorkOrder\": {\n      \"@id\": \"sanmina:WorkOrder\",\n      \"@type\": \"schema:Order\",\n      \"schema:description\": \"Manufacturing directive specifying production requirements\"\n    },\n\n    \"ProductionRun\": {\n      \"@id\": \"sanmina:ProductionRun\",\n      \"@type\": \"schema:Event\",\n      \"schema:description\"\
  : \"An instance of manufacturing execution for a specific work order\"\n    },\n\n    \"TraceabilityRecord\": {\n      \"@id\": \"sanmina:TraceabilityRecord\",\n      \"@type\": \"schema:ItemList\",\n      \"schema:description\": \"Complete genealogy of materials and components in a manufactured product\"\n    },\n\n    \"QualityEvent\": {\n      \"@id\": \"sanmina:QualityEvent\",\n      \"@type\": \"schema:Event\",\n      \"schema:description\": \"A quality inspection, test, or non-conformance event in manufacturing\"\n    },\n\n    \"42QMes\": {\n      \"@id\": \"sanmina:42Q\",\n      \"@type\": \"schema:SoftwareApplication\",\n      \"schema:name\": \"42Q\",\n      \"schema:description\": \"Sanmina's cloud-based Manufacturing Execution System\"\n    },\n\n    \"workOrderId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"serialNumber\": {\n      \"@id\": \"schema:serialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"lotNumber\"\
  : {\n      \"@id\": \"sanmina:lotNumber\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"plant\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"schema:Place\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sanmina/refs/heads/main/json-ld/sanmina-context.jsonld
tags:
- Manufacturing
- Contract Manufacturing
- MES
- Supply Chain
- Industrial
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
