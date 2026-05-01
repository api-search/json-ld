---
api_specs:
- filename: cargosmart-shipment-tracking-openapi.yml
  format: yaml
  label: CargoSmart Container Booking API
  slug: cargosmart-container-booking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml
- filename: cargosmart-shipment-tracking-openapi.yml
  format: yaml
  label: CargoSmart Shipment Tracking API
  slug: cargosmart-shipment-tracking-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml
- filename: cargosmart-shipment-tracking-openapi.yml
  format: yaml
  label: CargoSmart Vessel Schedule API
  slug: cargosmart-vessel-schedule-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml
- filename: cargosmart-shipment-tracking-openapi.yml
  format: yaml
  label: CargoSmart Shipping Documentation API
  slug: cargosmart-shipping-documents-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/openapi/cargosmart-shipment-tracking-openapi.yml
class_count: 0
classes: []
context_file: json-ld/cargosmart-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Cargosmart from CargoSmart.
layout: jsonld
name: Cargosmart Context
namespaces:
- prefix: cs
  uri: https://www.cargosmart.com/ontology/
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ContainerTracking
  type: ''
- container: ''
  name: TrackingEvent
  type: ''
- container: ''
  name: Booking
  type: ''
- container: ''
  name: BillOfLading
  type: ''
- container: ''
  name: Port
  type: ''
- container: ''
  name: VesselPosition
  type: ''
property_count: 6
provider_name: CargoSmart
provider_slug: cargosmart
slug: cargosmart-context
source_filename: cargosmart-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"cs\": \"https://www.cargosmart.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ContainerTracking\": {\n      \"@id\": \"schema:Parcel\",\n      \"@context\": {\n        \"containerId\": {\"@id\": \"schema:identifier\"},\n        \"containerType\": {\"@id\": \"cs:containerType\"},\n        \"carrierCode\": {\"@id\": \"cs:carrierCode\"},\n        \"vesselName\": {\"@id\": \"cs:vesselName\"},\n        \"voyageNumber\": {\"@id\": \"cs:voyageNumber\"},\n        \"currentStatus\": {\"@id\": \"schema:deliveryStatus\"},\n        \"originPort\": {\"@id\": \"schema:originAddress\"},\n        \"destinationPort\": {\"@id\": \"schema:destinationAddress\"},\n        \"estimatedArrival\": {\"@id\": \"schema:expectedArrivalUntil\", \"@type\": \"xsd:dateTime\"\
  },\n        \"actualArrival\": {\"@id\": \"schema:expectedArrivalFrom\", \"@type\": \"xsd:dateTime\"},\n        \"events\": {\"@id\": \"cs:trackingEvent\", \"@container\": \"@set\"}\n      }\n    },\n\n    \"TrackingEvent\": {\n      \"@id\": \"schema:Event\",\n      \"@context\": {\n        \"eventId\": {\"@id\": \"schema:identifier\"},\n        \"eventType\": {\"@id\": \"cs:eventType\"},\n        \"description\": {\"@id\": \"schema:description\"},\n        \"location\": {\"@id\": \"schema:location\"},\n        \"vesselName\": {\"@id\": \"cs:vesselName\"},\n        \"eventTime\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n        \"isActual\": {\"@id\": \"cs:isActualEvent\", \"@type\": \"xsd:boolean\"}\n      }\n    },\n\n    \"Booking\": {\n      \"@id\": \"schema:Order\",\n      \"@context\": {\n        \"bookingId\": {\"@id\": \"schema:identifier\"},\n        \"bookingNumber\": {\"@id\": \"schema:orderNumber\"},\n        \"carrierCode\": {\"@id\": \"cs:carrierCode\"\
  },\n        \"status\": {\"@id\": \"schema:orderStatus\"},\n        \"originPort\": {\"@id\": \"schema:originAddress\"},\n        \"destinationPort\": {\"@id\": \"schema:destinationAddress\"},\n        \"requestedDepartureDate\": {\"@id\": \"schema:scheduledTime\", \"@type\": \"xsd:date\"},\n        \"containers\": {\"@id\": \"schema:orderedItem\", \"@container\": \"@set\"},\n        \"shipper\": {\"@id\": \"schema:seller\"},\n        \"consignee\": {\"@id\": \"schema:buyer\"}\n      }\n    },\n\n    \"BillOfLading\": {\n      \"@id\": \"schema:Invoice\",\n      \"@context\": {\n        \"blNumber\": {\"@id\": \"schema:identifier\"},\n        \"blType\": {\"@id\": \"cs:blType\"},\n        \"carrierCode\": {\"@id\": \"cs:carrierCode\"},\n        \"issueDate\": {\"@id\": \"schema:dateIssued\", \"@type\": \"xsd:date\"},\n        \"shipper\": {\"@id\": \"schema:seller\"},\n        \"consignee\": {\"@id\": \"schema:buyer\"},\n        \"originPort\": {\"@id\": \"schema:originAddress\"},\n  \
  \      \"destinationPort\": {\"@id\": \"schema:destinationAddress\"},\n        \"vesselName\": {\"@id\": \"cs:vesselName\"},\n        \"cargoDescription\": {\"@id\": \"schema:description\"},\n        \"freightTerms\": {\"@id\": \"cs:freightTerms\"}\n      }\n    },\n\n    \"Port\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"locode\": {\"@id\": \"cs:locode\"},\n        \"portName\": {\"@id\": \"schema:name\"},\n        \"countryCode\": {\"@id\": \"schema:addressCountry\"},\n        \"terminalName\": {\"@id\": \"cs:terminalName\"}\n      }\n    },\n\n    \"VesselPosition\": {\n      \"@id\": \"geo:Point\",\n      \"@context\": {\n        \"vesselIMO\": {\"@id\": \"cs:imoNumber\"},\n        \"vesselName\": {\"@id\": \"schema:name\"},\n        \"latitude\": {\"@id\": \"geo:lat\", \"@type\": \"xsd:decimal\"},\n        \"longitude\": {\"@id\": \"geo:long\", \"@type\": \"xsd:decimal\"},\n        \"speed\": {\"@id\": \"cs:speedOverGround\", \"@type\": \"xsd:decimal\"\
  },\n        \"heading\": {\"@id\": \"cs:courseOverGround\", \"@type\": \"xsd:decimal\"},\n        \"destination\": {\"@id\": \"cs:destination\"},\n        \"eta\": {\"@id\": \"cs:estimatedTimeOfArrival\", \"@type\": \"xsd:dateTime\"},\n        \"timestamp\": {\"@id\": \"dcterms:modified\", \"@type\": \"xsd:dateTime\"}\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/cargosmart/refs/heads/main/json-ld/cargosmart-context.jsonld
tags:
- Booking
- Container
- Documentation
- GSBN
- IQAX
- Logistics
- Maritime
- Ocean Freight
- Schedule
- Shipping
- Supply Chain
- Tracking
- Visibility
- Vessel
- JSON-LD
- Linked Data
- Semantic Web
---
