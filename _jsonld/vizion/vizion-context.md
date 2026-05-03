---
api_specs:
- filename: vizion-container-tracking-openapi.yml
  format: yaml
  label: Vizion Container Tracking API
  slug: container-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vizion/refs/heads/main/openapi/vizion-container-tracking-openapi.yml
class_count: 7
classes:
- Reference
- TrackingUpdate
- TrackingEvent
- Location
- Vessel
- Port
- ShippingDelivery
context_file: json-ld/vizion-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vizion/refs/heads/main/json-ld/vizion-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vizion from Vizion.
layout: jsonld
name: Vizion Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: vizion
  uri: https://vizionapi.com/vocabulary#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties:
- container: ''
  name: id
  type: ''
- container: ''
  name: reference_id
  type: string
- container: ''
  name: container_id
  type: string
- container: ''
  name: carrier_scac
  type: string
- container: ''
  name: active
  type: boolean
- container: ''
  name: callback_url
  type: reference
- container: ''
  name: last_update_status
  type: string
- container: list
  name: events
  type: ''
- container: ''
  name: event_type
  type: string
- container: ''
  name: event_timestamp
  type: dateTime
- container: ''
  name: description
  type: ''
- container: ''
  name: is_actual
  type: boolean
- container: ''
  name: estimated_departure
  type: dateTime
- container: ''
  name: actual_departure
  type: dateTime
- container: ''
  name: estimated_arrival
  type: dateTime
- container: ''
  name: actual_arrival
  type: dateTime
- container: ''
  name: origin
  type: reference
- container: ''
  name: destination
  type: reference
- container: ''
  name: locode
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: imo
  type: string
- container: ''
  name: voyage
  type: string
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: trackingNumber
  type: ''
property_count: 29
provider_name: Vizion
provider_slug: vizion
slug: vizion-context
source_filename: vizion-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"vizion\": \"https://vizionapi.com/vocabulary#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n\n    \"Reference\": \"vizion:Reference\",\n    \"TrackingUpdate\": \"vizion:TrackingUpdate\",\n    \"TrackingEvent\": \"vizion:TrackingEvent\",\n    \"Location\": \"vizion:Location\",\n    \"Vessel\": \"vizion:Vessel\",\n\n    \"id\": {\"@id\": \"@id\"},\n    \"reference_id\": {\"@id\": \"vizion:referenceId\", \"@type\": \"xsd:string\"},\n    \"container_id\": {\"@id\": \"vizion:containerId\", \"@type\": \"xsd:string\"},\n    \"carrier_scac\": {\"@id\": \"vizion:carrierScac\", \"@type\": \"xsd:string\"},\n    \"active\": {\"@id\": \"vizion:active\", \"@type\": \"xsd:boolean\"},\n    \"callback_url\": {\"@id\": \"vizion:callbackUrl\", \"@type\": \"@id\"},\n    \"last_update_status\": {\"@id\": \"vizion:lastUpdateStatus\"\
  , \"@type\": \"xsd:string\"},\n\n    \"events\": {\"@id\": \"vizion:events\", \"@container\": \"@list\"},\n    \"event_type\": {\"@id\": \"vizion:eventType\", \"@type\": \"xsd:string\"},\n    \"event_timestamp\": {\"@id\": \"vizion:eventTimestamp\", \"@type\": \"xsd:dateTime\"},\n    \"description\": {\"@id\": \"schema:description\"},\n    \"is_actual\": {\"@id\": \"vizion:isActual\", \"@type\": \"xsd:boolean\"},\n\n    \"estimated_departure\": {\"@id\": \"vizion:estimatedDeparture\", \"@type\": \"xsd:dateTime\"},\n    \"actual_departure\": {\"@id\": \"vizion:actualDeparture\", \"@type\": \"xsd:dateTime\"},\n    \"estimated_arrival\": {\"@id\": \"vizion:estimatedArrival\", \"@type\": \"xsd:dateTime\"},\n    \"actual_arrival\": {\"@id\": \"vizion:actualArrival\", \"@type\": \"xsd:dateTime\"},\n\n    \"origin\": {\"@id\": \"vizion:origin\", \"@type\": \"@id\"},\n    \"destination\": {\"@id\": \"vizion:destination\", \"@type\": \"@id\"},\n\n    \"locode\": {\"@id\": \"vizion:locode\", \"\
  @type\": \"xsd:string\"},\n    \"country\": {\"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\"},\n    \"city\": {\"@id\": \"schema:addressLocality\", \"@type\": \"xsd:string\"},\n    \"state\": {\"@id\": \"schema:addressRegion\", \"@type\": \"xsd:string\"},\n    \"timezone\": {\"@id\": \"vizion:timezone\", \"@type\": \"xsd:string\"},\n\n    \"name\": {\"@id\": \"schema:name\"},\n    \"imo\": {\"@id\": \"vizion:imoNumber\", \"@type\": \"xsd:string\"},\n    \"voyage\": {\"@id\": \"vizion:voyageNumber\", \"@type\": \"xsd:string\"},\n\n    \"created_at\": {\"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\"},\n    \"updated_at\": {\"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\"},\n\n    \"Port\": \"schema:Place\",\n    \"ShippingDelivery\": \"schema:ParcelDelivery\",\n    \"trackingNumber\": {\"@id\": \"schema:trackingNumber\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vizion/refs/heads/main/json-ld/vizion-context.jsonld
tags:
- Container Tracking
- Logistics
- Ocean Freight
- Shipping
- Supply Chain
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
