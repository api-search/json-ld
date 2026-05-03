---
api_specs:
- filename: starwood-hotel-search-openapi.yml
  format: yaml
  label: Hotel Search API
  slug: hotel-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/openapi/starwood-hotel-search-openapi.yml
class_count: 23
classes:
- Hotel
- HotelSearch
- HotelAvailability
- RoomRate
- SPGMember
- id
- name
- description
- address
- city
- state
- country
- zipcode
- phone
- fax
- latitude
- longitude
- brandName
- category
- currency
- redeemPoints
- redeemCashPoints
- availability
context_file: json-ld/starwood-hotels-and-resorts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/json-ld/starwood-hotels-and-resorts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Starwood Hotels And Resorts from Starwood Hotels and Resorts.
layout: jsonld
name: Starwood Hotels And Resorts Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: starwood
  uri: https://www.starwoodhotels.com/ontology/
properties:
- container: ''
  name: thumbnail
  type: reference
- container: ''
  name: brand
  type: schema:Brand
- container: ''
  name: bestRate
  type: schema:Number
- container: list
  name: amenities
  type: ''
- container: ''
  name: arrivalDate
  type: schema:Date
- container: ''
  name: departureDate
  type: schema:Date
- container: ''
  name: pricePerNight
  type: schema:Number
- container: ''
  name: totalPrice
  type: schema:Number
property_count: 8
provider_name: Starwood Hotels and Resorts
provider_slug: starwood-hotels-and-resorts
slug: starwood-hotels-and-resorts-context
source_filename: starwood-hotels-and-resorts-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"starwood\": \"https://www.starwoodhotels.com/ontology/\",\n\n    \"Hotel\": \"schema:LodgingBusiness\",\n    \"HotelSearch\": \"schema:SearchAction\",\n    \"HotelAvailability\": \"schema:Offer\",\n    \"RoomRate\": \"schema:Accommodation\",\n    \"SPGMember\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"thumbnail\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"address\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"country\": \"schema:addressCountry\",\n    \"zipcode\": \"schema:postalCode\",\n    \"phone\": \"schema:telephone\",\n    \"fax\": \"schema:faxNumber\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\",\n    \"brand\": {\n      \"@id\": \"schema:brand\"\
  ,\n      \"@type\": \"schema:Brand\"\n    },\n    \"brandName\": \"schema:legalName\",\n    \"category\": \"starwood:spgCategory\",\n    \"bestRate\": {\n      \"@id\": \"schema:lowPrice\",\n      \"@type\": \"schema:Number\"\n    },\n    \"currency\": \"schema:priceCurrency\",\n    \"amenities\": {\n      \"@id\": \"schema:amenityFeature\",\n      \"@container\": \"@list\"\n    },\n    \"redeemPoints\": \"starwood:starpoints\",\n    \"redeemCashPoints\": \"starwood:cashAndPoints\",\n    \"arrivalDate\": {\n      \"@id\": \"schema:checkinTime\",\n      \"@type\": \"schema:Date\"\n    },\n    \"departureDate\": {\n      \"@id\": \"schema:checkoutTime\",\n      \"@type\": \"schema:Date\"\n    },\n    \"pricePerNight\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"schema:Number\"\n    },\n    \"availability\": \"schema:availability\",\n    \"totalPrice\": {\n      \"@id\": \"schema:totalPrice\",\n      \"@type\": \"schema:Number\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/starwood-hotels-and-resorts/refs/heads/main/json-ld/starwood-hotels-and-resorts-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
