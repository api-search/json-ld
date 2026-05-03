---
class_count: 31
classes:
- ShippingRate
- FreightCarrier
- Port
- Shipment
- Surcharge
- Container
- id
- carrierId
- carrierName
- serviceLevel
- origin
- destination
- name
- country
- region
- rate
- amount
- currency
- unit
- transitTime
- sailingFrequency
- surcharges
- commodity
- FCL
- LCL
- TEU
- FEU
- BAF
- PSS
- GRI
- THC
context_file: json-ld/shipping-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/shipping/refs/heads/main/json-ld/shipping-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Shipping from Shipping.com.
layout: jsonld
name: Shipping Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gs1
  uri: https://www.gs1.org/voc/
- prefix: sh
  uri: https://api-evangelist.github.io/shipping/vocabulary/
properties:
- container: ''
  name: unlocode
  type: string
- container: ''
  name: validFrom
  type: date
- container: ''
  name: validTo
  type: date
- container: ''
  name: createdAt
  type: dateTime
property_count: 4
provider_name: Shipping.com
provider_slug: shipping
slug: shipping-context
source_filename: shipping-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gs1\": \"https://www.gs1.org/voc/\",\n    \"sh\": \"https://api-evangelist.github.io/shipping/vocabulary/\",\n\n    \"ShippingRate\": \"schema:PriceSpecification\",\n    \"FreightCarrier\": \"schema:Organization\",\n    \"Port\": \"schema:Place\",\n    \"Shipment\": \"schema:ParcelDelivery\",\n    \"Surcharge\": \"schema:PriceSpecification\",\n    \"Container\": \"sh:Container\",\n\n    \"id\": \"@id\",\n    \"carrierId\": \"schema:identifier\",\n    \"carrierName\": \"schema:name\",\n    \"serviceLevel\": \"schema:serviceType\",\n    \"origin\": \"schema:originAddress\",\n    \"destination\": \"schema:deliveryAddress\",\n    \"unlocode\": {\n      \"@id\": \"sh:unlocode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"country\": \"schema:addressCountry\",\n    \"region\": \"schema:addressRegion\"\
  ,\n    \"rate\": \"schema:priceSpecification\",\n    \"amount\": \"schema:price\",\n    \"currency\": \"schema:priceCurrency\",\n    \"unit\": \"schema:unitCode\",\n    \"validFrom\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"validTo\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n    \"transitTime\": \"sh:transitTimeDays\",\n    \"sailingFrequency\": \"sh:sailingFrequency\",\n    \"surcharges\": \"sh:surcharges\",\n    \"commodity\": \"sh:commodity\",\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"FCL\": \"sh:FullContainerLoad\",\n    \"LCL\": \"sh:LessThanContainerLoad\",\n    \"TEU\": \"sh:TwentyFootEquivalentUnit\",\n    \"FEU\": \"sh:FortyFootEquivalentUnit\",\n    \"BAF\": \"sh:BunkerAdjustmentFactor\",\n    \"PSS\": \"sh:PeakSeasonSurcharge\",\n    \"GRI\": \"sh:GeneralRateIncrease\",\n    \"THC\": \"sh:TerminalHandlingCharge\"\n  }\n\
  }\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/shipping/refs/heads/main/json-ld/shipping-context.jsonld
tags:
- Shipping
- Freight
- Logistics
- Transportation
- Marketplace
- Rate Intelligence
- Ocean Freight
- Supply Chain
- JSON-LD
- Linked Data
- Semantic Web
---
