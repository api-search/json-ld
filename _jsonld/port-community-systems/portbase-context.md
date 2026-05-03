---
api_specs:
- filename: portbase-port-community-openapi.yml
  format: yaml
  label: Portbase Port Community System API
  slug: portbase
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/openapi/portbase-port-community-openapi.yml
class_count: 0
classes: []
context_file: json-ld/portbase-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/json-ld/portbase-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Portbase from Port Community Systems.
layout: jsonld
name: Portbase Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: pcs
  uri: https://www.portbase.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wgs84
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: VesselCall
  type: reference
- container: ''
  name: vesselCallId
  type: ''
- container: ''
  name: imoNumber
  type: ''
- container: ''
  name: mmsi
  type: ''
- container: ''
  name: vesselName
  type: ''
- container: ''
  name: callSign
  type: ''
- container: ''
  name: flag
  type: ''
- container: ''
  name: portCode
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: eta
  type: dateTime
- container: ''
  name: etd
  type: dateTime
- container: ''
  name: ata
  type: dateTime
- container: ''
  name: atd
  type: dateTime
- container: ''
  name: pilotageRequired
  type: boolean
- container: ''
  name: CargoManifest
  type: reference
- container: ''
  name: manifestId
  type: ''
- container: ''
  name: billOfLadingNumber
  type: ''
- container: ''
  name: hsCode
  type: ''
- container: ''
  name: grossWeight
  type: decimal
- container: ''
  name: portOfLoading
  type: ''
- container: ''
  name: portOfDischarge
  type: ''
- container: ''
  name: shipper
  type: ''
- container: ''
  name: consignee
  type: ''
- container: ''
  name: Container
  type: reference
- container: ''
  name: containerNumber
  type: ''
- container: ''
  name: isoType
  type: ''
- container: ''
  name: customsStatus
  type: ''
- container: ''
  name: CustomsDeclaration
  type: reference
- container: ''
  name: declarationId
  type: ''
- container: ''
  name: mrn
  type: ''
property_count: 30
provider_name: Port Community Systems
provider_slug: port-community-systems
slug: portbase-context
source_filename: portbase-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"pcs\": \"https://www.portbase.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wgs84\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"VesselCall\": {\n      \"@id\": \"schema:Event\",\n      \"@type\": \"@id\"\n    },\n    \"vesselCallId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"imoNumber\": {\n      \"@id\": \"pcs:imoNumber\"\n    },\n    \"mmsi\": {\n      \"@id\": \"pcs:mmsi\"\n    },\n    \"vesselName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"callSign\": {\n      \"@id\": \"pcs:callSign\"\n    },\n    \"flag\": {\n      \"@id\": \"pcs:flagState\"\n    },\n    \"portCode\": {\n      \"@id\": \"pcs:portUnlocode\"\n    },\n    \"status\": {\n      \"@id\": \"schema:eventStatus\"\n    },\n    \"eta\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"etd\": {\n      \"@id\": \"schema:departureTime\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ata\": {\n      \"@id\": \"pcs:actualArrival\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"atd\": {\n      \"@id\": \"pcs:actualDeparture\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"pilotageRequired\": {\n      \"@id\": \"pcs:pilotageRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"CargoManifest\": {\n      \"@id\": \"schema:ItemList\",\n      \"@type\": \"@id\"\n    },\n    \"manifestId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"billOfLadingNumber\": {\n      \"@id\": \"pcs:billOfLadingNumber\"\n    },\n    \"hsCode\": {\n      \"@id\": \"pcs:hsTariffCode\"\n    },\n    \"grossWeight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"portOfLoading\": {\n      \"@id\": \"schema:departureTerminal\"\n    },\n    \"portOfDischarge\": {\n      \"@id\": \"schema:arrivalTerminal\"\n    },\n    \"shipper\": {\n      \"@id\": \"schema:shipper\"\n    },\n    \"\
  consignee\": {\n      \"@id\": \"schema:recipient\"\n    },\n\n    \"Container\": {\n      \"@id\": \"schema:Product\",\n      \"@type\": \"@id\"\n    },\n    \"containerNumber\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"isoType\": {\n      \"@id\": \"pcs:containerIsoType\"\n    },\n    \"customsStatus\": {\n      \"@id\": \"pcs:customsStatus\"\n    },\n\n    \"CustomsDeclaration\": {\n      \"@id\": \"schema:GovernmentService\",\n      \"@type\": \"@id\"\n    },\n    \"declarationId\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"mrn\": {\n      \"@id\": \"pcs:movementReferenceNumber\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/port-community-systems/refs/heads/main/json-ld/portbase-context.jsonld
tags:
- Maritime
- Port
- Logistics
- Customs
- Cargo
- Shipping
- JSON-LD
- Linked Data
- Semantic Web
---
