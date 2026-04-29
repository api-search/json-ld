---
class_count: 1
classes:
- CreditCard
context_file: json-ld/amadeus-transfer-booking-credit-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-credit-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Transfer Booking Credit from Amadeus Reservations.
layout: jsonld
name: Amadeus Transfer Booking Credit Context
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
  name: number
  type: string
- container: ''
  name: holderName
  type: string
- container: ''
  name: vendorCode
  type: string
- container: ''
  name: expiryDate
  type: string
- container: ''
  name: cvv
  type: string
property_count: 5
provider_name: Amadeus Reservations
provider_slug: amadeus-reservations
slug: amadeus-transfer-booking-credit-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreditCard\": \"amadeus:CreditCard\",\n    \"number\": {\n      \"@id\": \"amadeus:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"holderName\": {\n      \"@id\": \"amadeus:holderName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorCode\": {\n      \"@id\": \"amadeus:vendorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiryDate\": {\n      \"@id\": \"amadeus:expiryDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvv\": {\n      \"@id\": \"amadeus:cvv\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-reservations/refs/heads/main/json-ld/amadeus-transfer-booking-credit-context.jsonld
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
