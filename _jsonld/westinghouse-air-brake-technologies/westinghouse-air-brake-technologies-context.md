---
class_count: 0
classes: []
context_file: json-ld/westinghouse-air-brake-technologies-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/westinghouse-air-brake-technologies/refs/heads/main/json-ld/westinghouse-air-brake-technologies-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Westinghouse Air Brake Technologies from westinghouse-air-brake-technologies.
layout: jsonld
name: Westinghouse Air Brake Technologies Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wabtec
  uri: https://www.wabteccorp.com/ontology/
properties:
- container: ''
  name: Locomotive
  type: reference
- container: ''
  name: locomotiveId
  type: string
- container: ''
  name: roadNumber
  type: string
- container: ''
  name: locomotiveModel
  type: string
- container: ''
  name: manufacturer
  type: reference
- container: ''
  name: railroad
  type: string
- container: ''
  name: operationalStatus
  type: string
- container: ''
  name: horsepower
  type: integer
- container: ''
  name: engineType
  type: string
- container: ''
  name: mileage
  type: double
- container: ''
  name: fuelLevel
  type: double
- container: ''
  name: faultCodes
  type: string
- container: ''
  name: WorkOrder
  type: reference
- container: ''
  name: workOrderId
  type: string
- container: ''
  name: workType
  type: string
- container: ''
  name: workOrderStatus
  type: string
- container: ''
  name: priority
  type: string
- container: ''
  name: assignedTechnician
  type: reference
- container: ''
  name: GeoLocation
  type: reference
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
property_count: 21
provider_name: westinghouse-air-brake-technologies
provider_slug: westinghouse-air-brake-technologies
slug: westinghouse-air-brake-technologies-context
source_filename: westinghouse-air-brake-technologies-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wabtec\": \"https://www.wabteccorp.com/ontology/\",\n\n    \"Locomotive\": {\n      \"@id\": \"wabtec:Locomotive\",\n      \"@type\": \"@id\"\n    },\n    \"locomotiveId\": {\n      \"@id\": \"wabtec:locomotiveId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roadNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locomotiveModel\": {\n      \"@id\": \"schema:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\",\n      \"@type\": \"@id\"\n    },\n    \"railroad\": {\n      \"@id\": \"wabtec:railroad\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationalStatus\": {\n      \"@id\": \"schema:operatingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"horsepower\": {\n      \"@id\": \"wabtec:horsepower\",\n\
  \      \"@type\": \"xsd:integer\"\n    },\n    \"engineType\": {\n      \"@id\": \"wabtec:engineType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mileage\": {\n      \"@id\": \"schema:mileageFromOdometer\",\n      \"@type\": \"xsd:double\"\n    },\n    \"fuelLevel\": {\n      \"@id\": \"wabtec:fuelLevel\",\n      \"@type\": \"xsd:double\"\n    },\n    \"faultCodes\": {\n      \"@id\": \"wabtec:faultCodes\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"WorkOrder\": {\n      \"@id\": \"wabtec:WorkOrder\",\n      \"@type\": \"@id\"\n    },\n    \"workOrderId\": {\n      \"@id\": \"wabtec:workOrderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workType\": {\n      \"@id\": \"wabtec:workType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workOrderStatus\": {\n      \"@id\": \"schema:orderStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"schema:priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignedTechnician\": {\n \
  \     \"@id\": \"schema:worksFor\",\n      \"@type\": \"@id\"\n    },\n\n    \"GeoLocation\": {\n      \"@id\": \"schema:GeoCoordinates\",\n      \"@type\": \"@id\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:double\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/westinghouse-air-brake-technologies/refs/heads/main/json-ld/westinghouse-air-brake-technologies-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
