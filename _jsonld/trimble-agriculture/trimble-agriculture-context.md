---
api_specs:
- filename: trimble-agriculture-openapi.yml
  format: yaml
  label: Trimble Agriculture Data API
  slug: trimble-agriculture-data
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/openapi/trimble-agriculture-openapi.yml
class_count: 9
classes:
- Organization
- Farm
- Field
- CropZone
- EquipmentActivity
- WorkOrder
- Prescription
- Material
- Boundary
context_file: json-ld/trimble-agriculture-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/json-ld/trimble-agriculture-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Trimble Agriculture from Trimble Agriculture.
layout: jsonld
name: Trimble Agriculture Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: agri
  uri: http://def.seegrid.csiro.au/isotc211/iso19156/2011/observation#
- prefix: geo
  uri: http://www.opengis.net/ont/geosparql#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: trimble-ag
  uri: https://cloud.api.trimble.com/vocab/agriculture/
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: farmId
  type: string
- container: ''
  name: fieldId
  type: string
- container: ''
  name: organizationId
  type: string
- container: ''
  name: cropZoneId
  type: string
- container: ''
  name: season
  type: integer
- container: ''
  name: cropType
  type: string
- container: ''
  name: variety
  type: string
- container: ''
  name: area
  type: ''
- container: ''
  name: boundary
  type: ''
- container: ''
  name: geometry
  type: ''
- container: ''
  name: activityType
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: status
  type: string
- container: set
  name: materials
  type: ''
- container: ''
  name: applicationRate
  type: float
- container: ''
  name: unit
  type: string
- container: ''
  name: materialType
  type: string
- container: ''
  name: manufacturer
  type: ''
- container: ''
  name: assignedOperatorId
  type: string
- container: ''
  name: scheduledDate
  type: date
- container: ''
  name: country
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: address
  type: string
property_count: 28
provider_name: Trimble Agriculture
provider_slug: trimble-agriculture
slug: trimble-agriculture-context
source_filename: trimble-agriculture-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"agri\": \"http://def.seegrid.csiro.au/isotc211/iso19156/2011/observation#\",\n    \"geo\": \"http://www.opengis.net/ont/geosparql#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"trimble-ag\": \"https://cloud.api.trimble.com/vocab/agriculture/\",\n\n    \"Organization\": \"schema:Organization\",\n    \"Farm\": \"schema:Place\",\n    \"Field\": \"trimble-ag:Field\",\n    \"CropZone\": \"trimble-ag:CropZone\",\n    \"EquipmentActivity\": \"trimble-ag:EquipmentActivity\",\n    \"WorkOrder\": \"trimble-ag:WorkOrder\",\n    \"Prescription\": \"trimble-ag:Prescription\",\n    \"Material\": \"schema:Product\",\n    \"Boundary\": \"geo:Feature\",\n\n    \"id\": {\n      \"@id\": \"@id\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\
  \n    },\n\n    \"farmId\": {\n      \"@id\": \"trimble-ag:farmId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldId\": {\n      \"@id\": \"trimble-ag:fieldId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationId\": {\n      \"@id\": \"trimble-ag:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cropZoneId\": {\n      \"@id\": \"trimble-ag:cropZoneId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"season\": {\n      \"@id\": \"trimble-ag:season\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cropType\": {\n      \"@id\": \"trimble-ag:cropType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variety\": {\n      \"@id\": \"trimble-ag:variety\",\n      \"@type\": \"xsd:string\"\n    },\n    \"area\": {\n      \"@id\": \"schema:area\"\n    },\n    \"boundary\": {\n      \"@id\": \"geo:hasGeometry\"\n    },\n    \"geometry\": {\n      \"@id\": \"geo:asWKT\"\n    },\n\n    \"activityType\": {\n      \"@id\": \"trimble-ag:activityType\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"trimble-ag:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"materials\": {\n      \"@id\": \"trimble-ag:materials\",\n      \"@container\": \"@set\"\n    },\n    \"applicationRate\": {\n      \"@id\": \"trimble-ag:applicationRate\",\n      \"@type\": \"xsd:float\"\n    },\n    \"unit\": {\n      \"@id\": \"schema:unitText\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"materialType\": {\n      \"@id\": \"trimble-ag:materialType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"schema:manufacturer\"\n    },\n\n    \"assignedOperatorId\": {\n      \"@id\": \"trimble-ag:assignedOperatorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledDate\": {\n      \"@id\"\
  : \"schema:scheduledTime\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"country\": {\n      \"@id\": \"schema:addressCountry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/trimble-agriculture/refs/heads/main/json-ld/trimble-agriculture-context.jsonld
tags:
- Agriculture
- Farming
- IoT
- Precision Agriculture
- Field Management
- Prescriptions
- Telematics
- JSON-LD
- Linked Data
- Semantic Web
---
