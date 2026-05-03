---
api_specs:
- filename: rentcast-openapi.json
  format: json
  label: RentCast API
  slug: rentcast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/openapi/rentcast-openapi.json
class_count: 22
classes:
- Property
- Estimate
- Listing
- MarketStatistics
- id
- formattedAddress
- addressLine1
- city
- state
- zipCode
- county
- propertyType
- bedrooms
- bathrooms
- ownerOccupied
- owner
- price
- priceRangeLow
- priceRangeHigh
- comparables
- distance
- daysOnMarket
context_file: json-ld/rentcast-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/json-ld/rentcast-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rentcast from RentCast.
layout: jsonld
name: Rentcast Context
namespaces:
- prefix: rentcast
  uri: https://api.rentcast.io/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: squareFootage
  type: integer
- container: ''
  name: lotSize
  type: integer
- container: ''
  name: yearBuilt
  type: integer
- container: ''
  name: assessedValue
  type: decimal
- container: ''
  name: lastSaleDate
  type: date
- container: ''
  name: lastSalePrice
  type: decimal
- container: ''
  name: propertyTypes
  type: '@vocab'
property_count: 9
provider_name: RentCast
provider_slug: rentcast
slug: rentcast-context
source_filename: rentcast-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rentcast\": \"https://api.rentcast.io/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Property\": \"schema:RealEstateListing\",\n    \"Estimate\": \"rentcast:Estimate\",\n    \"Listing\": \"schema:RealEstateListing\",\n    \"MarketStatistics\": \"rentcast:MarketStatistics\",\n\n    \"id\": \"@id\",\n    \"formattedAddress\": \"schema:address\",\n    \"addressLine1\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zipCode\": \"schema:postalCode\",\n    \"county\": \"schema:addressLocality\",\n    \"latitude\": {\n      \"@id\": \"geo:lat\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"geo:long\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"propertyType\": \"rentcast:propertyType\",\n    \"\
  bedrooms\": \"schema:numberOfRooms\",\n    \"bathrooms\": \"rentcast:bathrooms\",\n    \"squareFootage\": {\n      \"@id\": \"schema:floorSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lotSize\": {\n      \"@id\": \"schema:lotSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"yearBuilt\": {\n      \"@id\": \"schema:yearBuilt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"assessedValue\": {\n      \"@id\": \"schema:priceSpecification\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"lastSaleDate\": {\n      \"@id\": \"schema:datePosted\",\n      \"@type\": \"xsd:date\"\n    },\n    \"lastSalePrice\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"ownerOccupied\": \"rentcast:ownerOccupied\",\n    \"owner\": \"schema:owns\",\n\n    \"price\": \"schema:price\",\n    \"priceRangeLow\": \"schema:minPrice\",\n    \"priceRangeHigh\": \"schema:maxPrice\",\n    \"comparables\": \"rentcast:comparables\",\n    \"distance\": \"schema:distance\"\
  ,\n    \"daysOnMarket\": \"rentcast:daysOnMarket\",\n\n    \"propertyTypes\": {\n      \"@id\": \"rentcast:propertyTypes\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"Single Family\": \"rentcast:SingleFamily\",\n        \"Condo\": \"rentcast:Condo\",\n        \"Townhouse\": \"rentcast:Townhouse\",\n        \"Multi-Family\": \"rentcast:MultiFamily\",\n        \"Apartment\": \"rentcast:Apartment\",\n        \"Land\": \"rentcast:Land\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rentcast/refs/heads/main/json-ld/rentcast-context.jsonld
tags:
- Real Estate
- Property Data
- Valuation
- Rental Market
- AVM
- JSON-LD
- Linked Data
- Semantic Web
---
