---
api_specs:
- filename: project44-tracking-openapi.yml
  format: yaml
  label: project44 Tracking API
  slug: project44-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/openapi/project44-tracking-openapi.yml
- filename: project44-shipment-events-asyncapi.yml
  format: yaml
  label: project44 Webhooks API
  slug: project44-webhooks-api
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/asyncapi/project44-shipment-events-asyncapi.yml
class_count: 0
classes: []
context_file: json-ld/project44-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/json-ld/project44-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Project44 from project44.
layout: jsonld
name: Project44 Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: p44
  uri: https://api.project44.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wgs84
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: Shipment
  type: reference
- container: ''
  name: id
  type: ''
- container: ''
  name: masterShipmentId
  type: ''
- container: ''
  name: mode
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: carrierCode
  type: ''
- container: ''
  name: carrierName
  type: ''
- container: ''
  name: proNumber
  type: ''
- container: ''
  name: bolNumber
  type: ''
- container: ''
  name: origin
  type: ''
- container: ''
  name: destination
  type: ''
- container: ''
  name: estimatedDelivery
  type: ''
- container: ''
  name: ShipmentStop
  type: reference
- container: ''
  name: city
  type: ''
- container: ''
  name: state
  type: ''
- container: ''
  name: postalCode
  type: ''
- container: ''
  name: country
  type: ''
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: Position
  type: reference
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: speed
  type: decimal
- container: ''
  name: ETAWindow
  type: reference
- container: ''
  name: estimatedAt
  type: dateTime
- container: ''
  name: predictedOnTime
  type: boolean
- container: ''
  name: ShipmentException
  type: reference
- container: ''
  name: exceptionCode
  type: ''
- container: ''
  name: severity
  type: ''
property_count: 28
provider_name: project44
provider_slug: project44
slug: project44-context
source_filename: project44-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"p44\": \"https://api.project44.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wgs84\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Shipment\": {\n      \"@id\": \"schema:ParcelDelivery\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"masterShipmentId\": {\n      \"@id\": \"schema:orderNumber\"\n    },\n    \"mode\": {\n      \"@id\": \"schema:deliveryMethod\"\n    },\n    \"status\": {\n      \"@id\": \"schema:deliveryStatus\"\n    },\n    \"carrierCode\": {\n      \"@id\": \"p44:carrierScac\"\n    },\n    \"carrierName\": {\n      \"@id\": \"schema:provider\"\n    },\n    \"proNumber\": {\n      \"@id\": \"p44:proNumber\"\n    },\n    \"bolNumber\": {\n      \"@id\": \"p44:billOfLadingNumber\"\n    },\n    \"origin\": {\n      \"@id\": \"schema:originAddress\"\n    },\n    \"destination\"\
  : {\n      \"@id\": \"schema:deliveryAddress\"\n    },\n    \"estimatedDelivery\": {\n      \"@id\": \"schema:expectedArrivalFrom\"\n    },\n\n    \"ShipmentStop\": {\n      \"@id\": \"schema:Place\",\n      \"@type\": \"@id\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\"\n    },\n    \"postalCode\": {\n      \"@id\": \"schema:postalCode\"\n    },\n    \"country\": {\n      \"@id\": \"schema:addressCountry\"\n    },\n    \"latitude\": {\n      \"@id\": \"wgs84:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"wgs84:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"Position\": {\n      \"@id\": \"schema:GeoCoordinates\",\n      \"@type\": \"@id\"\n    },\n    \"timestamp\": {\n      \"@id\": \"schema:dateTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"speed\": {\n      \"@id\": \"schema:speed\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n \
  \   \"ETAWindow\": {\n      \"@id\": \"schema:DeliveryTimeSettings\",\n      \"@type\": \"@id\"\n    },\n    \"estimatedAt\": {\n      \"@id\": \"schema:expectedArrivalFrom\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"predictedOnTime\": {\n      \"@id\": \"p44:predictedOnTime\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"ShipmentException\": {\n      \"@id\": \"schema:EventStatusType\",\n      \"@type\": \"@id\"\n    },\n    \"exceptionCode\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"severity\": {\n      \"@id\": \"p44:severity\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/project44/refs/heads/main/json-ld/project44-context.jsonld
tags:
- Logistics
- Freight
- Supply Chain
- Visibility
- Tracking
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
