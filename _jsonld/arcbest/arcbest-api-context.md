---
class_count: 12
classes:
- ErrorResponse
- Address
- FreightItem
- RateRequest
- RateResponse
- Shipment
- ShipmentRequest
- ShipmentList
- TrackingEvent
- TrackingStatus
- PickupRequest
- PickupConfirmation
context_file: json-ld/arcbest-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/json-ld/arcbest-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Arcbest Api from ArcBest.
layout: jsonld
name: Arcbest Api Context
namespaces:
- prefix: arcbest
  uri: https://api.arcbest.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: zip
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: weight
  type: decimal
- container: ''
  name: freightClass
  type: string
- container: ''
  name: pieces
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: length
  type: decimal
- container: ''
  name: width
  type: decimal
- container: ''
  name: height
  type: decimal
- container: ''
  name: origin
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: items
  type: string
- container: ''
  name: serviceType
  type: string
- container: ''
  name: quoteNumber
  type: string
- container: ''
  name: totalCharge
  type: decimal
- container: ''
  name: transitDays
  type: integer
- container: ''
  name: serviceLevel
  type: string
- container: ''
  name: expiresAt
  type: dateTime
- container: ''
  name: proNumber
  type: string
- container: ''
  name: bolNumber
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: shipper
  type: string
- container: ''
  name: consignee
  type: string
- container: ''
  name: referenceNumber
  type: string
- container: ''
  name: shipments
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: date
  type: dateTime
- container: ''
  name: location
  type: string
- container: ''
  name: lastLocation
  type: string
- container: ''
  name: estimatedDelivery
  type: date
- container: ''
  name: events
  type: string
- container: ''
  name: pickupDate
  type: date
- container: ''
  name: readyTime
  type: string
- container: ''
  name: closeTime
  type: string
- container: ''
  name: confirmationNumber
  type: string
property_count: 41
provider_name: ArcBest
provider_slug: arcbest
slug: arcbest-api-context
tags:
- Logistics
- Freight
- LTL
- Supply Chain
- Shipping
- Transportation
- JSON-LD
- Linked Data
- Semantic Web
---
