---
api_specs:
- filename: union-pacific-api.yaml
  format: yaml
  label: Union Pacific API
  slug: union-pacific
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/openapi/union-pacific-api.yaml
class_count: 0
classes: []
context_file: json-ld/union-pacific-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Union Pacific from Union Pacific.
layout: jsonld
name: Union Pacific Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: up
  uri: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld#
properties:
- container: ''
  name: Shipment
  type: schema:ParcelDelivery
- container: ''
  name: Equipment
  type: schema:Vehicle
- container: ''
  name: Location
  type: schema:Place
- container: ''
  name: Case
  type: schema:Report
- container: ''
  name: Waybill
  type: schema:ShippingDeliveryTime
- container: ''
  name: IntermodalReservation
  type: schema:Reservation
- container: ''
  name: shipmentId
  type: string
- container: ''
  name: waybillNumber
  type: string
- container: ''
  name: equipmentNumber
  type: string
- container: ''
  name: origin
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: estimatedArrival
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: commodity
  type: string
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
property_count: 18
provider_name: Union Pacific
provider_slug: union-pacific
slug: union-pacific-context
source_filename: union-pacific-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"up\": \"https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld#\",\n\n    \"Shipment\": {\n      \"@id\": \"up:Shipment\",\n      \"@type\": \"schema:ParcelDelivery\"\n    },\n    \"Equipment\": {\n      \"@id\": \"up:Equipment\",\n      \"@type\": \"schema:Vehicle\"\n    },\n    \"Location\": {\n      \"@id\": \"up:Location\",\n      \"@type\": \"schema:Place\"\n    },\n    \"Case\": {\n      \"@id\": \"up:Case\",\n      \"@type\": \"schema:Report\"\n    },\n    \"Waybill\": {\n      \"@id\": \"up:Waybill\",\n      \"@type\": \"schema:ShippingDeliveryTime\"\n    },\n    \"IntermodalReservation\": {\n      \"@id\": \"up:IntermodalReservation\",\n      \"@type\": \"schema:Reservation\"\n    },\n\n    \"shipmentId\"\
  : {\n      \"@id\": \"schema:trackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"waybillNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"equipmentNumber\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origin\": {\n      \"@id\": \"schema:departureStation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"schema:arrivalStation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedArrival\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"schema:deliveryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commodity\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\
  \n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/union-pacific/refs/heads/main/json-ld/union-pacific-context.jsonld
tags:
- Freight
- Railroads
- Shipping
- Trains
- Supply Chain
- Logistics
- JSON-LD
- Linked Data
- Semantic Web
---
