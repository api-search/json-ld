---
api_specs:
- filename: uber-riders-openapi.yml
  format: yaml
  label: Uber Riders API
  slug: uber-riders
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-riders-openapi.yml
- filename: uber-drivers-openapi.yml
  format: yaml
  label: Uber Drivers API
  slug: uber-drivers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-drivers-openapi.yml
- filename: uber-eats-openapi.yml
  format: yaml
  label: Uber Eats API
  slug: uber-eats
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-eats-openapi.yml
- filename: uber-direct-openapi.yml
  format: yaml
  label: Uber Direct API
  slug: uber-direct
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-direct-openapi.yml
- filename: uber-vouchers-openapi.yml
  format: yaml
  label: Uber Vouchers API
  slug: uber-vouchers
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-vouchers-openapi.yml
- filename: uber-businesses-openapi.yml
  format: yaml
  label: Uber for Business API
  slug: uber-businesses
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/openapi/uber-businesses-openapi.yml
class_count: 8
classes:
- Product
- RideRequest
- Delivery
- RiderProfile
- DriverProfile
- Order
- Store
- BusinessLocation
context_file: json-ld/uber-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/json-ld/uber-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uber from Uber.
layout: jsonld
name: Uber Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: uber
  uri: https://developer.uber.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: product_id
  type: string
- container: ''
  name: display_name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: capacity
  type: integer
- container: ''
  name: image
  type: reference
- container: ''
  name: request_id
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: eta
  type: integer
- container: ''
  name: surge_multiplier
  type: double
- container: ''
  name: start_latitude
  type: double
- container: ''
  name: start_longitude
  type: double
- container: ''
  name: end_latitude
  type: double
- container: ''
  name: end_longitude
  type: double
- container: ''
  name: tracking_url
  type: reference
- container: ''
  name: pickup_eta
  type: dateTime
- container: ''
  name: dropoff_eta
  type: dateTime
- container: ''
  name: fee
  type: integer
- container: ''
  name: currency
  type: string
- container: ''
  name: currency_code
  type: string
- container: ''
  name: first_name
  type: string
- container: ''
  name: last_name
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: phone_number
  type: string
- container: ''
  name: picture
  type: reference
- container: ''
  name: promo_code
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: store_id
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: placed_at
  type: dateTime
- container: ''
  name: total
  type: double
property_count: 30
provider_name: Uber
provider_slug: uber
slug: uber-context
source_filename: uber-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"uber\": \"https://developer.uber.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Product\": \"schema:Product\",\n    \"RideRequest\": \"uber:RideRequest\",\n    \"Delivery\": \"uber:Delivery\",\n    \"RiderProfile\": \"schema:Person\",\n    \"DriverProfile\": \"schema:Person\",\n    \"Order\": \"schema:Order\",\n    \"Store\": \"schema:FoodEstablishment\",\n    \"BusinessLocation\": \"schema:Place\",\n\n    \"product_id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"display_name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"description\": { \"@id\": \"schema:description\", \"@type\": \"xsd:string\" },\n    \"capacity\": { \"@id\": \"uber:capacity\", \"@type\": \"xsd:integer\" },\n    \"image\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n\n    \"request_id\": { \"@id\": \"schema:identifier\", \"@type\"\
  : \"xsd:string\" },\n    \"status\": { \"@id\": \"schema:orderStatus\", \"@type\": \"xsd:string\" },\n    \"eta\": { \"@id\": \"uber:estimatedTimeOfArrival\", \"@type\": \"xsd:integer\" },\n    \"surge_multiplier\": { \"@id\": \"uber:surgeMultiplier\", \"@type\": \"xsd:double\" },\n\n    \"start_latitude\": { \"@id\": \"uber:startLatitude\", \"@type\": \"xsd:double\" },\n    \"start_longitude\": { \"@id\": \"uber:startLongitude\", \"@type\": \"xsd:double\" },\n    \"end_latitude\": { \"@id\": \"uber:endLatitude\", \"@type\": \"xsd:double\" },\n    \"end_longitude\": { \"@id\": \"uber:endLongitude\", \"@type\": \"xsd:double\" },\n\n    \"tracking_url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"pickup_eta\": { \"@id\": \"uber:pickupEta\", \"@type\": \"xsd:dateTime\" },\n    \"dropoff_eta\": { \"@id\": \"uber:dropoffEta\", \"@type\": \"xsd:dateTime\" },\n    \"fee\": { \"@id\": \"schema:price\", \"@type\": \"xsd:integer\" },\n    \"currency\": { \"@id\": \"schema:priceCurrency\"\
  , \"@type\": \"xsd:string\" },\n    \"currency_code\": { \"@id\": \"schema:priceCurrency\", \"@type\": \"xsd:string\" },\n\n    \"first_name\": { \"@id\": \"schema:givenName\", \"@type\": \"xsd:string\" },\n    \"last_name\": { \"@id\": \"schema:familyName\", \"@type\": \"xsd:string\" },\n    \"email\": { \"@id\": \"schema:email\", \"@type\": \"xsd:string\" },\n    \"phone_number\": { \"@id\": \"schema:telephone\", \"@type\": \"xsd:string\" },\n    \"picture\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"promo_code\": { \"@id\": \"uber:promoCode\", \"@type\": \"xsd:string\" },\n    \"uuid\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n\n    \"store_id\": { \"@id\": \"schema:identifier\", \"@type\": \"xsd:string\" },\n    \"address\": { \"@id\": \"schema:address\", \"@type\": \"xsd:string\" },\n    \"placed_at\": { \"@id\": \"schema:orderDate\", \"@type\": \"xsd:dateTime\" },\n    \"total\": { \"@id\": \"schema:totalPrice\", \"@type\": \"xsd:double\" }\n\
  \  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uber/refs/heads/main/json-ld/uber-context.jsonld
tags:
- Ride-Sharing
- Rides
- Taxis
- Transportation
- Food Delivery
- Delivery
- Logistics
- JSON-LD
- Linked Data
- Semantic Web
---
