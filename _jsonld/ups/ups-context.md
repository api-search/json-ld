---
api_specs:
- filename: ups-shipping-openapi.yml
  format: yaml
  label: UPS Shipping API
  slug: ups-shipping
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/openapi/ups-shipping-openapi.yml
class_count: 4
classes:
- Shipment
- Address
- Rate
- Pickup
context_file: json-ld/ups-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/json-ld/ups-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ups from UPS.
layout: jsonld
name: Ups Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: ups
  uri: https://onlinetools.ups.com/api/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: trackingNumber
  type: string
- container: ''
  name: shipper
  type: schema:Organization
- container: ''
  name: shipTo
  type: schema:Person
- container: ''
  name: deliveryDate
  type: date
- container: ''
  name: serviceCode
  type: string
- container: ''
  name: addressLine1
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: stateProvinceCode
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: residential
  type: boolean
- container: ''
  name: totalAmount
  type: decimal
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: businessDaysInTransit
  type: integer
- container: ''
  name: pickupDate
  type: date
- container: ''
  name: readyTime
  type: string
- container: ''
  name: closeTime
  type: string
property_count: 17
provider_name: UPS
provider_slug: ups
slug: ups-context
source_filename: ups-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"ups\": \"https://onlinetools.ups.com/api/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Shipment\": \"schema:ParcelDelivery\",\n    \"trackingNumber\": { \"@id\": \"schema:trackingNumber\", \"@type\": \"xsd:string\" },\n    \"shipper\": { \"@id\": \"schema:sender\", \"@type\": \"schema:Organization\" },\n    \"shipTo\": { \"@id\": \"schema:recipient\", \"@type\": \"schema:Person\" },\n    \"deliveryDate\": { \"@id\": \"schema:expectedArrivalUntil\", \"@type\": \"xsd:date\" },\n    \"serviceCode\": { \"@id\": \"ups:serviceCode\", \"@type\": \"xsd:string\" },\n\n    \"Address\": \"schema:PostalAddress\",\n    \"addressLine1\": { \"@id\": \"schema:streetAddress\", \"@type\": \"xsd:string\" },\n    \"city\": { \"@id\": \"schema:addressLocality\", \"@type\": \"xsd:string\" },\n    \"stateProvinceCode\": { \"@id\": \"schema:addressRegion\", \"@type\": \"xsd:string\" },\n\
  \    \"postalCode\": { \"@id\": \"schema:postalCode\", \"@type\": \"xsd:string\" },\n    \"countryCode\": { \"@id\": \"schema:addressCountry\", \"@type\": \"xsd:string\" },\n    \"residential\": { \"@id\": \"ups:residentialAddress\", \"@type\": \"xsd:boolean\" },\n\n    \"Rate\": \"schema:PriceSpecification\",\n    \"totalAmount\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"currencyCode\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n    \"businessDaysInTransit\": { \"@id\": \"ups:businessDaysInTransit\", \"@type\": \"xsd:integer\" },\n\n    \"Pickup\": \"schema:DeliveryEvent\",\n    \"pickupDate\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:date\" },\n    \"readyTime\": { \"@id\": \"ups:readyTime\", \"@type\": \"xsd:string\" },\n    \"closeTime\": { \"@id\": \"ups:closeTime\", \"@type\": \"xsd:string\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ups/refs/heads/main/json-ld/ups-context.jsonld
tags:
- Logistics
- Shipping
- Fortune 500
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
