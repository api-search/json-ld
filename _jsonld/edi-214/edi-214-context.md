---
class_count: 0
classes: []
context_file: json-ld/edi-214-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/json-ld/edi-214-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Edi 214 from edi-214.
layout: jsonld
name: Edi 214 Context
namespaces:
- prefix: edi
  uri: https://x12.org/schemas/edi-214/
- prefix: schema
  uri: https://schema.org/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: Edi214Document
  type: schema:ParcelDelivery
- container: ''
  name: B10Segment
  type: ''
- container: ''
  name: At7Segment
  type: schema:DeliveryEvent
- container: ''
  name: Ms1Segment
  type: schema:Place
- container: ''
  name: Ms2Segment
  type: ''
- container: ''
  name: LxLoop
  type: ''
- container: ''
  name: transactionSetId
  type: ''
- container: ''
  name: referenceIdentification
  type: ''
- container: ''
  name: shipmentIdentificationNumber
  type: ''
- container: ''
  name: scac
  type: ''
- container: ''
  name: shipmentStatusCode
  type: ''
- container: ''
  name: statusReasonCode
  type: ''
- container: ''
  name: date
  type: ''
- container: ''
  name: time
  type: ''
- container: ''
  name: timeCode
  type: ''
- container: ''
  name: cityName
  type: ''
- container: ''
  name: stateOrProvinceCode
  type: ''
- container: ''
  name: countryCode
  type: ''
- container: ''
  name: longitudeCode
  type: ''
- container: ''
  name: latitudeCode
  type: ''
- container: ''
  name: equipmentNumber
  type: ''
- container: ''
  name: equipmentDescriptionCode
  type: ''
- container: ''
  name: weight
  type: schema:QuantitativeValue
- container: ''
  name: ladingQuantity
  type: integer
- container: ''
  name: commodityDescription
  type: ''
- container: set
  name: statusEvents
  type: ''
- container: set
  name: shipmentGroups
  type: ''
- container: set
  name: referenceNumbers
  type: ''
- container: ''
  name: referenceIdentificationNumber
  type: ''
- container: ''
  name: referenceIdentificationQualifier
  type: ''
property_count: 30
provider_name: edi-214
provider_slug: edi-214
slug: edi-214-context
source_filename: edi-214-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"edi\": \"https://x12.org/schemas/edi-214/\",\n    \"schema\": \"https://schema.org/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Edi214Document\": {\n      \"@id\": \"edi:ShipmentStatusMessage\",\n      \"@type\": \"schema:ParcelDelivery\"\n    },\n    \"B10Segment\": {\n      \"@id\": \"edi:ShipmentHeader\"\n    },\n    \"At7Segment\": {\n      \"@id\": \"edi:StatusEvent\",\n      \"@type\": \"schema:DeliveryEvent\"\n    },\n    \"Ms1Segment\": {\n      \"@id\": \"edi:ShipmentLocation\",\n      \"@type\": \"schema:Place\"\n    },\n    \"Ms2Segment\": {\n      \"@id\": \"edi:EquipmentInfo\"\n    },\n    \"LxLoop\": {\n      \"@id\": \"edi:StatusGroup\"\n    },\n\n    \"transactionSetId\": {\n      \"@id\": \"edi:transactionSetControlNumber\"\n    },\n    \"referenceIdentification\": {\n\
  \      \"@id\": \"schema:trackingNumber\"\n    },\n    \"shipmentIdentificationNumber\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"scac\": {\n      \"@id\": \"edi:standardCarrierAlphaCode\"\n    },\n    \"shipmentStatusCode\": {\n      \"@id\": \"edi:statusCode\"\n    },\n    \"statusReasonCode\": {\n      \"@id\": \"edi:reasonCode\"\n    },\n    \"date\": {\n      \"@id\": \"schema:startDate\"\n    },\n    \"time\": {\n      \"@id\": \"edi:eventTime\"\n    },\n    \"timeCode\": {\n      \"@id\": \"edi:timeZone\"\n    },\n    \"cityName\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"stateOrProvinceCode\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"countryCode\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"longitudeCode\": {\n      \"@id\": \"geo:long\"\n    },\n    \"latitudeCode\": {\n      \"@id\": \"geo:lat\"\n    },\n    \"equipmentNumber\": {\n      \"@id\": \"schema:serialNumber\"\n    },\n    \"equipmentDescriptionCode\"\
  : {\n      \"@id\": \"edi:equipmentType\"\n    },\n    \"weight\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"ladingQuantity\": {\n      \"@id\": \"schema:numberOfItems\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commodityDescription\": {\n      \"@id\": \"schema:description\"\n    },\n    \"statusEvents\": {\n      \"@id\": \"edi:hasStatusEvent\",\n      \"@container\": \"@set\"\n    },\n    \"shipmentGroups\": {\n      \"@id\": \"edi:hasShipmentGroup\",\n      \"@container\": \"@set\"\n    },\n    \"referenceNumbers\": {\n      \"@id\": \"edi:hasReference\",\n      \"@container\": \"@set\"\n    },\n    \"referenceIdentificationNumber\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"referenceIdentificationQualifier\": {\n      \"@id\": \"edi:referenceQualifier\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/edi-214/refs/heads/main/json-ld/edi-214-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
