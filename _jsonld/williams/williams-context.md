---
class_count: 14
classes:
- Pipeline
- NominationRequest
- ShippingContract
- GasTransportation
- CompressorStation
- StorageFacility
- GatheringSystem
- ProcessingPlant
- Organization
- name
- description
- url
- address
- telephone
context_file: json-ld/williams-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/williams/refs/heads/main/json-ld/williams-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Williams from Williams Companies.
layout: jsonld
name: Williams Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: williams
  uri: https://www.williams.com/vocab#
- prefix: energy
  uri: https://energy.gov/vocab#
properties:
- container: ''
  name: pipelineName
  type: string
- container: ''
  name: pipelineLength
  type: decimal
- container: ''
  name: capacity
  type: decimal
- container: ''
  name: capacityUnit
  type: string
- container: ''
  name: nominationQuantity
  type: decimal
- container: ''
  name: nominationPeriod
  type: string
- container: ''
  name: injectionPoint
  type: string
- container: ''
  name: withdrawalPoint
  type: string
- container: ''
  name: shipper
  type: reference
- container: ''
  name: contractNumber
  type: string
- container: ''
  name: measurementUnit
  type: string
- container: ''
  name: dekatherms
  type: decimal
- container: ''
  name: pressurePSI
  type: decimal
- container: ''
  name: compressorStations
  type: integer
- container: ''
  name: ferc
  type: reference
- container: ''
  name: regulatoryDocket
  type: string
property_count: 16
provider_name: Williams Companies
provider_slug: williams
slug: williams-context
source_filename: williams-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"williams\": \"https://www.williams.com/vocab#\",\n    \"energy\": \"https://energy.gov/vocab#\",\n\n    \"Pipeline\": \"williams:Pipeline\",\n    \"NominationRequest\": \"williams:NominationRequest\",\n    \"ShippingContract\": \"williams:ShippingContract\",\n    \"GasTransportation\": \"williams:GasTransportation\",\n    \"CompressorStation\": \"williams:CompressorStation\",\n    \"StorageFacility\": \"williams:StorageFacility\",\n    \"GatheringSystem\": \"williams:GatheringSystem\",\n    \"ProcessingPlant\": \"williams:ProcessingPlant\",\n\n    \"pipelineName\": {\n      \"@id\": \"williams:pipelineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineLength\": {\n      \"@id\": \"williams:pipelineLength\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"capacity\": {\n      \"@id\": \"williams:capacity\",\n      \"\
  @type\": \"xsd:decimal\"\n    },\n    \"capacityUnit\": {\n      \"@id\": \"williams:capacityUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nominationQuantity\": {\n      \"@id\": \"williams:nominationQuantity\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"nominationPeriod\": {\n      \"@id\": \"williams:nominationPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"injectionPoint\": {\n      \"@id\": \"williams:injectionPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"withdrawalPoint\": {\n      \"@id\": \"williams:withdrawalPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shipper\": {\n      \"@id\": \"williams:shipper\",\n      \"@type\": \"@id\"\n    },\n    \"contractNumber\": {\n      \"@id\": \"williams:contractNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"measurementUnit\": {\n      \"@id\": \"williams:measurementUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dekatherms\": {\n      \"@id\": \"williams:dekatherms\",\n     \
  \ \"@type\": \"xsd:decimal\"\n    },\n    \"pressurePSI\": {\n      \"@id\": \"williams:pressurePSI\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"compressorStations\": {\n      \"@id\": \"williams:compressorStations\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ferc\": {\n      \"@id\": \"energy:ferc\",\n      \"@type\": \"@id\"\n    },\n    \"regulatoryDocket\": {\n      \"@id\": \"williams:regulatoryDocket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"address\": \"schema:address\",\n    \"telephone\": \"schema:telephone\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/williams/refs/heads/main/json-ld/williams-context.jsonld
tags:
- Energy
- Natural Gas
- Pipeline
- Infrastructure
- Fortune 500
- Midstream
- Utilities
- JSON-LD
- Linked Data
- Semantic Web
---
