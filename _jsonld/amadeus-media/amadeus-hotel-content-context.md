---
api_specs:
- filename: amadeus-media-hotel-content-openapi.yaml
  format: yaml
  label: Hotel Content API
  slug: hotel-content-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/openapi/amadeus-media-hotel-content-openapi.yaml
- filename: amadeus-media-hotel-list-openapi.yaml
  format: yaml
  label: Hotel List API
  slug: hotel-list-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/openapi/amadeus-media-hotel-list-openapi.yaml
class_count: 13
classes:
- HotelContact
- GeoCode
- HotelBasicInfo
- HotelContent
- HotelMediaItem
- HotelContentResponse
- HotelMediaData
- MediaAsset
- HotelDescription
- HotelAddress
- HotelMediaResponse
- email
- name
context_file: json-ld/amadeus-hotel-content-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/json-ld/amadeus-hotel-content-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amadeus Hotel Content from Amadeus Media.
layout: jsonld
name: Amadeus Hotel Content Context
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
  name: phone
  type: string
- container: ''
  name: fax
  type: string
- container: ''
  name: website
  type: reference
- container: ''
  name: latitude
  type: double
- container: ''
  name: longitude
  type: double
- container: ''
  name: category
  type: integer
- container: ''
  name: rating
  type: string
- container: ''
  name: numberOfRooms
  type: integer
- container: ''
  name: checkInTime
  type: string
- container: ''
  name: checkOutTime
  type: string
- container: ''
  name: hotelId
  type: string
- container: ''
  name: chainCode
  type: string
- container: ''
  name: iataCode
  type: string
- container: ''
  name: basicInfo
  type: string
- container: set
  name: descriptions
  type: string
- container: ''
  name: contact
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: geoCode
  type: string
- container: set
  name: amenities
  type: string
- container: set
  name: media
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: uri
  type: reference
- container: ''
  name: thumbnailUri
  type: reference
- container: ''
  name: caption
  type: string
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: ''
  name: format
  type: string
- container: ''
  name: isPrimary
  type: boolean
- container: set
  name: data
  type: string
- container: ''
  name: meta
  type: string
- container: ''
  name: lang
  type: string
- container: ''
  name: text
  type: string
- container: set
  name: lines
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: cityName
  type: string
- container: ''
  name: countryCode
  type: string
- container: ''
  name: stateCode
  type: string
property_count: 37
provider_name: Amadeus Media
provider_slug: amadeus-media
slug: amadeus-hotel-content-context
source_filename: amadeus-hotel-content-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amadeus\": \"https://amadeus.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HotelContact\": \"amadeus:HotelContact\",\n    \"GeoCode\": \"amadeus:GeoCode\",\n    \"HotelBasicInfo\": \"amadeus:HotelBasicInfo\",\n    \"HotelContent\": \"amadeus:HotelContent\",\n    \"HotelMediaItem\": \"amadeus:HotelMediaItem\",\n    \"HotelContentResponse\": \"amadeus:HotelContentResponse\",\n    \"HotelMediaData\": \"amadeus:HotelMediaData\",\n    \"MediaAsset\": \"amadeus:MediaAsset\",\n    \"HotelDescription\": \"amadeus:HotelDescription\",\n    \"HotelAddress\": \"amadeus:HotelAddress\",\n    \"HotelMediaResponse\": \"amadeus:HotelMediaResponse\",\n    \"phone\": {\n      \"@id\": \"amadeus:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fax\": {\n      \"@id\": \"amadeus:fax\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"email\": \"schema:email\",\n    \"website\": {\n      \"@id\": \"amadeus:website\",\n      \"@type\": \"@id\"\n    },\n    \"latitude\": {\n      \"@id\": \"amadeus:latitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"longitude\": {\n      \"@id\": \"amadeus:longitude\",\n      \"@type\": \"xsd:double\"\n    },\n    \"category\": {\n      \"@id\": \"amadeus:category\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rating\": {\n      \"@id\": \"amadeus:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfRooms\": {\n      \"@id\": \"amadeus:numberOfRooms\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"checkInTime\": {\n      \"@id\": \"amadeus:checkInTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkOutTime\": {\n      \"@id\": \"amadeus:checkOutTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hotelId\": {\n      \"@id\": \"amadeus:hotelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chainCode\": {\n      \"@id\": \"amadeus:chainCode\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"iataCode\": {\n      \"@id\": \"amadeus:iataCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"basicInfo\": {\n      \"@id\": \"amadeus:basicInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"descriptions\": {\n      \"@id\": \"amadeus:descriptions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contact\": {\n      \"@id\": \"amadeus:contact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"amadeus:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geoCode\": {\n      \"@id\": \"amadeus:geoCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amenities\": {\n      \"@id\": \"amadeus:amenities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media\": {\n      \"@id\": \"amadeus:media\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\"\
  : \"amadeus:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"amadeus:uri\",\n      \"@type\": \"@id\"\n    },\n    \"thumbnailUri\": {\n      \"@id\": \"amadeus:thumbnailUri\",\n      \"@type\": \"@id\"\n    },\n    \"caption\": {\n      \"@id\": \"amadeus:caption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"width\": {\n      \"@id\": \"amadeus:width\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"height\": {\n      \"@id\": \"amadeus:height\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"format\": {\n      \"@id\": \"amadeus:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPrimary\": {\n      \"@id\": \"amadeus:isPrimary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"data\": {\n      \"@id\": \"amadeus:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"meta\": {\n      \"@id\": \"amadeus:meta\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lang\": {\n      \"@id\": \"amadeus:lang\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"text\": {\n      \"@id\": \"amadeus:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lines\": {\n      \"@id\": \"amadeus:lines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"amadeus:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cityName\": {\n      \"@id\": \"amadeus:cityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countryCode\": {\n      \"@id\": \"amadeus:countryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateCode\": {\n      \"@id\": \"amadeus:stateCode\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amadeus-media/refs/heads/main/json-ld/amadeus-hotel-content-context.jsonld
tags:
- Content
- Hotels
- Images
- Media
- Travel
- JSON-LD
- Linked Data
- Semantic Web
---
