---
api_specs:
- filename: travelcenters-of-america-openapi.yml
  format: yaml
  label: TravelCenters of America API
  slug: travelcenters-of-america
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/openapi/travelcenters-of-america-openapi.yml
class_count: 42
classes:
- TravelCenter
- Location
- WorkOrder
- FuelCode
- FuelPrice
- ParkingAvailability
- ShowerAvailability
- Document
- Amenity
- id
- name
- brand
- address
- city
- state
- zip
- lat
- lon
- phone
- hours
- truck_lanes
- truck_parking_spaces
- amenities
- available_spaces
- total_spaces
- occupied_spaces
- available_showers
- total_showers
- estimated_wait_minutes
- fuel_type
- price_per_gallon
- updated_at
- timestamp
- work_order_id
- vehicle_id
- status
- services
- total_amount
- document_type
- code
- active
- fuel_types
context_file: json-ld/travelcenters-of-america-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/json-ld/travelcenters-of-america-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Travelcenters Of America from TravelCenters of America.
layout: jsonld
name: Travelcenters Of America Context
namespaces:
- prefix: ta
  uri: https://ta-petro.com/vocab/
- prefix: geo
  uri: http://www.w3.org/2003/01/geo/wgs84_pos#
properties: []
property_count: 0
provider_name: TravelCenters of America
provider_slug: travelcenters-of-america
slug: travelcenters-of-america-context
source_filename: travelcenters-of-america-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"ta\": \"https://ta-petro.com/vocab/\",\n    \"geo\": \"http://www.w3.org/2003/01/geo/wgs84_pos#\",\n    \"TravelCenter\": \"schema:LocalBusiness\",\n    \"Location\": \"schema:Place\",\n    \"WorkOrder\": \"ta:WorkOrder\",\n    \"FuelCode\": \"ta:FuelCode\",\n    \"FuelPrice\": \"ta:FuelPrice\",\n    \"ParkingAvailability\": \"ta:ParkingAvailability\",\n    \"ShowerAvailability\": \"ta:ShowerAvailability\",\n    \"Document\": \"schema:DigitalDocument\",\n    \"Amenity\": \"schema:LocationFeatureSpecification\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"brand\": \"schema:brand\",\n    \"address\": \"schema:streetAddress\",\n    \"city\": \"schema:addressLocality\",\n    \"state\": \"schema:addressRegion\",\n    \"zip\": \"schema:postalCode\",\n    \"lat\": \"geo:lat\",\n    \"lon\": \"geo:long\",\n    \"phone\": \"schema:telephone\",\n    \"hours\": \"schema:openingHours\",\n    \"truck_lanes\"\
  : \"ta:truckFuelLanes\",\n    \"truck_parking_spaces\": \"ta:truckParkingCapacity\",\n    \"amenities\": \"schema:amenityFeature\",\n    \"available_spaces\": \"ta:availableParkingSpaces\",\n    \"total_spaces\": \"ta:totalParkingSpaces\",\n    \"occupied_spaces\": \"ta:occupiedParkingSpaces\",\n    \"available_showers\": \"ta:availableShowers\",\n    \"total_showers\": \"ta:totalShowers\",\n    \"estimated_wait_minutes\": \"ta:estimatedWaitMinutes\",\n    \"fuel_type\": \"ta:fuelType\",\n    \"price_per_gallon\": \"schema:price\",\n    \"updated_at\": \"schema:dateModified\",\n    \"timestamp\": \"schema:datePublished\",\n    \"work_order_id\": \"ta:workOrder\",\n    \"vehicle_id\": \"ta:vehicle\",\n    \"status\": \"schema:orderStatus\",\n    \"services\": \"ta:services\",\n    \"total_amount\": \"schema:totalPaymentDue\",\n    \"document_type\": \"schema:fileFormat\",\n    \"code\": \"ta:fuelAuthorizationCode\",\n    \"active\": \"schema:isRelatedTo\",\n    \"fuel_types\": \"ta:fuelTypes\"\
  \n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/travelcenters-of-america/refs/heads/main/json-ld/travelcenters-of-america-context.jsonld
tags:
- Travel Centers
- Truck Service
- Retail
- Fuel
- Locations
- Trucking
- Fleet Management
- JSON-LD
- Linked Data
- Semantic Web
---
