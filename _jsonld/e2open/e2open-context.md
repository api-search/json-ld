---
class_count: 4
classes:
- bookingId
- portName
- country
- vesselName
context_file: json-ld/e2open-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-ld/e2open-context.jsonld
description: JSON-LD context defining the semantic vocabulary for E2Open from e2open.
layout: jsonld
name: E2Open Context
namespaces:
- prefix: e2open
  uri: https://api.inttra.com/v1/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: mar
  uri: https://www.w3.org/ns/maritime#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Shipment
  type: schema:ParcelDelivery
- container: ''
  name: Booking
  type: schema:Order
- container: ''
  name: Container
  type: schema:Product
- container: ''
  name: Vessel
  type: schema:Vehicle
- container: ''
  name: TradeParty
  type: schema:Organization
- container: ''
  name: Port
  type: schema:Place
- container: ''
  name: TrackingEvent
  type: schema:DeliveryEvent
- container: ''
  name: carrierBookingReference
  type: ''
- container: ''
  name: carrier
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: originPort
  type: ''
- container: ''
  name: destinationPort
  type: ''
- container: ''
  name: etd
  type: date
- container: ''
  name: eta
  type: date
- container: ''
  name: portCode
  type: ''
- container: ''
  name: imoNumber
  type: ''
- container: ''
  name: shipper
  type: schema:Organization
- container: ''
  name: consignee
  type: schema:Organization
- container: set
  name: containers
  type: ''
- container: ''
  name: containerNumber
  type: ''
- container: ''
  name: containerType
  type: ''
- container: ''
  name: grossWeightKg
  type: schema:QuantitativeValue
- container: ''
  name: commodity
  type: ''
- container: ''
  name: hsCode
  type: ''
- container: ''
  name: eventType
  type: ''
- container: ''
  name: eventDateTime
  type: dateTime
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: confirmedAt
  type: dateTime
property_count: 28
provider_name: e2open
provider_slug: e2open
slug: e2open-context
source_filename: e2open-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"e2open\": \"https://api.inttra.com/v1/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"mar\": \"https://www.w3.org/ns/maritime#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Shipment\": {\n      \"@id\": \"schema:ParcelDelivery\",\n      \"@type\": \"schema:ParcelDelivery\"\n    },\n    \"Booking\": {\n      \"@id\": \"e2open:Booking\",\n      \"@type\": \"schema:Order\"\n    },\n    \"Container\": {\n      \"@id\": \"e2open:Container\",\n      \"@type\": \"schema:Product\"\n    },\n    \"Vessel\": {\n      \"@id\": \"e2open:Vessel\",\n      \"@type\": \"schema:Vehicle\"\n    },\n    \"TradeParty\": {\n      \"@id\": \"e2open:TradeParty\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"Port\": {\n      \"@id\": \"e2open:Port\",\n      \"@type\": \"schema:Place\"\n    },\n    \"TrackingEvent\": {\n      \"@id\": \"e2open:TrackingEvent\"\
  ,\n      \"@type\": \"schema:DeliveryEvent\"\n    },\n\n    \"bookingId\": \"@id\",\n    \"carrierBookingReference\": {\n      \"@id\": \"schema:confirmationNumber\"\n    },\n    \"carrier\": {\n      \"@id\": \"schema:provider\"\n    },\n    \"status\": {\n      \"@id\": \"schema:orderStatus\"\n    },\n    \"originPort\": {\n      \"@id\": \"schema:originAddress\"\n    },\n    \"destinationPort\": {\n      \"@id\": \"schema:deliveryAddress\"\n    },\n    \"etd\": {\n      \"@id\": \"schema:departureTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"eta\": {\n      \"@id\": \"schema:arrivalTime\",\n      \"@type\": \"xsd:date\"\n    },\n    \"portCode\": {\n      \"@id\": \"schema:identifier\"\n    },\n    \"portName\": \"schema:name\",\n    \"country\": \"schema:addressCountry\",\n    \"vesselName\": \"schema:name\",\n    \"imoNumber\": {\n      \"@id\": \"e2open:imoNumber\"\n    },\n    \"shipper\": {\n      \"@id\": \"schema:sender\",\n      \"@type\": \"schema:Organization\"\n \
  \   },\n    \"consignee\": {\n      \"@id\": \"schema:recipient\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"containers\": {\n      \"@id\": \"e2open:hasContainer\",\n      \"@container\": \"@set\"\n    },\n    \"containerNumber\": {\n      \"@id\": \"schema:serialNumber\"\n    },\n    \"containerType\": {\n      \"@id\": \"schema:productID\"\n    },\n    \"grossWeightKg\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"schema:QuantitativeValue\"\n    },\n    \"commodity\": {\n      \"@id\": \"schema:description\"\n    },\n    \"hsCode\": {\n      \"@id\": \"e2open:harmonizedSystemCode\"\n    },\n    \"eventType\": {\n      \"@id\": \"schema:name\"\n    },\n    \"eventDateTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"confirmedAt\": {\n      \"@id\": \"schema:dateIssued\",\n      \"@type\": \"xsd:dateTime\"\
  \n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/e2open/refs/heads/main/json-ld/e2open-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
