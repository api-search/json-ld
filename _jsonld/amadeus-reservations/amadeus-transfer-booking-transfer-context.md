---
class_count: 2
classes:
- Transfer
- TransferOrder
context_file: json-ld/amadeus-transfer-booking-transfer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-transfer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Transfer from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Transfer Context
namespaces:
- prefix: amadeus
  uri: https://amadeus.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: transferType
  type: string
- container: ''
  name: start
  type: string
- container: ''
  name: end
  type: string
- container: set
  name: stopOvers
  type: string
- container: set
  name: passenegerCharacteristics
  type: string
- container: ''
  name: duration
  type: string
- container: ''
  name: vehicle
  type: string
- container: ''
  name: serviceProvider
  type: string
- container: ''
  name: partnerInfo
  type: string
- container: ''
  name: quotation
  type: string
- container: ''
  name: converted
  type: string
- container: set
  name: extraServices
  type: string
- container: set
  name: equipment
  type: string
- container: set
  name: cancellationRules
  type: string
- container: set
  name: methodsOfPaymentAccepted
  type: string
- container: set
  name: discountCodes
  type: string
- container: ''
  name: distance
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: reference
  type: string
- container: set
  name: transfers
  type: string
- container: set
  name: passengers
  type: string
- container: ''
  name: agency
  type: string
property_count: 23
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-transfer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Transfer\": \"amadeus:Transfer\",\n    \"TransferOrder\": \"amadeus:TransferOrder\",\n    \"transferType\": {\n      \"@id\": \"amadeus:transferType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"amadeus:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"amadeus:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopOvers\": {\n      \"@id\": \"amadeus:stopOvers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passenegerCharacteristics\": {\n      \"@id\": \"amadeus:passenegerCharacteristics\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"amadeus:duration\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"vehicle\": {\n      \"@id\": \"amadeus:vehicle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceProvider\": {\n      \"@id\": \"amadeus:serviceProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerInfo\": {\n      \"@id\": \"amadeus:partnerInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quotation\": {\n      \"@id\": \"amadeus:quotation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"converted\": {\n      \"@id\": \"amadeus:converted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extraServices\": {\n      \"@id\": \"amadeus:extraServices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"equipment\": {\n      \"@id\": \"amadeus:equipment\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cancellationRules\": {\n      \"@id\": \"amadeus:cancellationRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"methodsOfPaymentAccepted\"\
  : {\n      \"@id\": \"amadeus:methodsOfPaymentAccepted\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discountCodes\": {\n      \"@id\": \"amadeus:discountCodes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distance\": {\n      \"@id\": \"amadeus:distance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amadeus:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"amadeus:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transfers\": {\n      \"@id\": \"amadeus:transfers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"passengers\": {\n      \"@id\": \"amadeus:passengers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agency\": {\n      \"@id\": \"amadeus:agency\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-transfer-context.jsonld
tags:
- Booking
- Flights
- Hotels
- Reservations
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
