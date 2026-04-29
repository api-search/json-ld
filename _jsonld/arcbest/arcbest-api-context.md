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
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"arcbest\": \"https://api.arcbest.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ErrorResponse\": \"arcbest:ErrorResponse\",\n    \"message\": {\n      \"@id\": \"arcbest:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"arcbest:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Address\": \"arcbest:Address\",\n    \"name\": {\n      \"@id\": \"arcbest:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"arcbest:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"arcbest:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"arcbest:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"zip\": {\n      \"@id\": \"arcbest:zip\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"country\": {\n      \"@id\": \"arcbest:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FreightItem\": \"arcbest:FreightItem\",\n    \"weight\": {\n      \"@id\": \"arcbest:weight\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"freightClass\": {\n      \"@id\": \"arcbest:freightClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pieces\": {\n      \"@id\": \"arcbest:pieces\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"arcbest:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"arcbest:length\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"width\": {\n      \"@id\": \"arcbest:width\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"height\": {\n      \"@id\": \"arcbest:height\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"RateRequest\": \"arcbest:RateRequest\",\n    \"origin\": {\n      \"@id\": \"arcbest:origin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\"\
  : {\n      \"@id\": \"arcbest:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"arcbest:items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceType\": {\n      \"@id\": \"arcbest:serviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RateResponse\": \"arcbest:RateResponse\",\n    \"quoteNumber\": {\n      \"@id\": \"arcbest:quoteNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCharge\": {\n      \"@id\": \"arcbest:totalCharge\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"transitDays\": {\n      \"@id\": \"arcbest:transitDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serviceLevel\": {\n      \"@id\": \"arcbest:serviceLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"arcbest:expiresAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Shipment\": \"arcbest:Shipment\",\n    \"proNumber\": {\n      \"@id\": \"arcbest:proNumber\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"bolNumber\": {\n      \"@id\": \"arcbest:bolNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"arcbest:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipmentRequest\": \"arcbest:ShipmentRequest\",\n    \"shipper\": {\n      \"@id\": \"arcbest:shipper\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consignee\": {\n      \"@id\": \"arcbest:consignee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceNumber\": {\n      \"@id\": \"arcbest:referenceNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipmentList\": \"arcbest:ShipmentList\",\n    \"shipments\": {\n      \"@id\": \"arcbest:shipments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"arcbest:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"TrackingEvent\": \"arcbest:TrackingEvent\",\n    \"date\": {\n      \"@id\": \"arcbest:date\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"location\": {\n\
  \      \"@id\": \"arcbest:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackingStatus\": \"arcbest:TrackingStatus\",\n    \"lastLocation\": {\n      \"@id\": \"arcbest:lastLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedDelivery\": {\n      \"@id\": \"arcbest:estimatedDelivery\",\n      \"@type\": \"xsd:date\"\n    },\n    \"events\": {\n      \"@id\": \"arcbest:events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PickupRequest\": \"arcbest:PickupRequest\",\n    \"pickupDate\": {\n      \"@id\": \"arcbest:pickupDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"readyTime\": {\n      \"@id\": \"arcbest:readyTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"closeTime\": {\n      \"@id\": \"arcbest:closeTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PickupConfirmation\": \"arcbest:PickupConfirmation\",\n    \"confirmationNumber\": {\n      \"@id\": \"arcbest:confirmationNumber\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/arcbest/refs/heads/main/json-ld/arcbest-api-context.jsonld
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
