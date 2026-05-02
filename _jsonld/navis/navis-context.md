---
api_specs:
- filename: navis-n4-openapi.yml
  format: yaml
  label: NAVIS N4 Terminal Operating System API
  slug: n4
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/navis/refs/heads/main/openapi/navis-n4-openapi.yml
class_count: 9
classes:
- Unit
- unitNbr
- YardPosition
- blockName
- slotName
- VesselVisit
- visitId
- vesselName
- GateTransaction
context_file: json-ld/navis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/navis/refs/heads/main/json-ld/navis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Navis from Navis (Kaleris).
layout: jsonld
name: Navis Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: navis
  uri: https://kaleris.com/ontology/n4/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: category
  type: string
- container: ''
  name: freightKind
  type: string
- container: ''
  name: equipmentType
  type: string
- container: ''
  name: equipmentLength
  type: integer
- container: ''
  name: lineOperator
  type: string
- container: ''
  name: hazardous
  type: boolean
- container: ''
  name: reefer
  type: boolean
- container: ''
  name: weight
  type: decimal
- container: ''
  name: locType
  type: string
- container: ''
  name: berth
  type: string
- container: ''
  name: eta
  type: dateTime
- container: ''
  name: etd
  type: dateTime
- container: ''
  name: transactionTime
  type: dateTime
property_count: 13
provider_name: Navis (Kaleris)
provider_slug: navis
slug: navis-context
source_filename: navis-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"navis\": \"https://kaleris.com/ontology/n4/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Unit\": \"schema:Product\",\n    \"unitNbr\": \"schema:identifier\",\n    \"category\": {\n      \"@id\": \"navis:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"freightKind\": {\n      \"@id\": \"navis:freightKind\",\n      \"@type\": \"xsd:string\"\n    },\n    \"equipmentType\": {\n      \"@id\": \"schema:vehicleSpecialUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"equipmentLength\": {\n      \"@id\": \"schema:depth\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lineOperator\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hazardous\": {\n      \"@id\": \"navis:hazardous\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reefer\": {\n      \"@id\"\
  : \"navis:refrigerated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"YardPosition\": \"schema:Place\",\n    \"locType\": {\n      \"@id\": \"navis:locationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockName\": \"schema:name\",\n    \"slotName\": \"schema:identifier\",\n    \"VesselVisit\": \"schema:Event\",\n    \"visitId\": \"schema:identifier\",\n    \"vesselName\": \"schema:name\",\n    \"berth\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eta\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"etd\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"GateTransaction\": \"schema:TradeAction\",\n    \"transactionTime\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/navis/refs/heads/main/json-ld/navis-context.jsonld
tags:
- Maritime
- Port
- Terminal
- Container
- Logistics
- JSON-LD
- Linked Data
- Semantic Web
---
