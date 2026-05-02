---
api_specs:
- filename: lyft-ride-sharing-openapi.yml
  format: yaml
  label: Lyft Ride-Sharing API
  slug: ride-sharing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/openapi/lyft-ride-sharing-openapi.yml
- filename: lyft-concierge-openapi.yml
  format: yaml
  label: Lyft Concierge API
  slug: concierge-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/openapi/lyft-concierge-openapi.yml
class_count: 0
classes: []
context_file: json-ld/lyft-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/json-ld/lyft-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Lyft from lyft.
layout: jsonld
name: Lyft Context
namespaces:
- prefix: lyft
  uri: https://api.lyft.com/v1/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Ride
  type: ''
- container: ''
  name: RideType
  type: ''
- container: ''
  name: Location
  type: ''
- container: ''
  name: Driver
  type: ''
- container: ''
  name: Vehicle
  type: ''
- container: ''
  name: Passenger
  type: ''
- container: ''
  name: CostEstimate
  type: ''
- container: ''
  name: Profile
  type: ''
- container: ''
  name: Receipt
  type: ''
property_count: 9
provider_name: lyft
provider_slug: lyft
slug: lyft-context
source_filename: lyft-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"lyft\": \"https://api.lyft.com/v1/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Ride\": {\n      \"@id\": \"lyft:Ride\",\n      \"@context\": {\n        \"rideId\": \"lyft:ride_id\",\n        \"rideType\": \"lyft:ride_type\",\n        \"status\": \"lyft:status\",\n        \"origin\": \"lyft:origin\",\n        \"destination\": \"lyft:destination\",\n        \"pickup\": \"lyft:pickup\",\n        \"dropoff\": \"lyft:dropoff\",\n        \"driver\": \"lyft:driver\",\n        \"vehicle\": \"lyft:vehicle\",\n        \"passenger\": \"lyft:passenger\",\n        \"requestedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"completedAt\": {\n          \"@id\": \"lyft:completedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"canceledAt\": {\n     \
  \     \"@id\": \"lyft:canceledAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheduledPickupTime\": {\n          \"@id\": \"lyft:scheduledPickupTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"price\": \"schema:price\"\n      }\n    },\n\n    \"RideType\": {\n      \"@id\": \"lyft:RideType\",\n      \"@context\": {\n        \"rideType\": \"lyft:ride_type\",\n        \"displayName\": \"schema:name\",\n        \"seats\": \"schema:seatingCapacity\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"pricingDetails\": \"lyft:pricingDetails\"\n      }\n    },\n\n    \"Location\": {\n      \"@id\": \"schema:Place\",\n      \"@context\": {\n        \"lat\": \"schema:latitude\",\n        \"lng\": \"schema:longitude\",\n        \"address\": \"schema:streetAddress\",\n        \"city\": \"schema:addressLocality\",\n        \"state\": \"schema:addressRegion\",\n        \"zip\": \"schema:postalCode\"\
  \n      }\n    },\n\n    \"Driver\": {\n      \"@id\": \"lyft:Driver\",\n      \"@context\": {\n        \"firstName\": \"schema:givenName\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"rating\": \"schema:ratingValue\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Vehicle\": {\n      \"@id\": \"schema:Vehicle\",\n      \"@context\": {\n        \"make\": \"schema:manufacturer\",\n        \"model\": \"schema:model\",\n        \"year\": {\n          \"@id\": \"schema:vehicleModelDate\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"licensePlate\": \"lyft:licensePlate\",\n        \"licensePlateState\": \"lyft:licensePlateState\",\n        \"color\": \"schema:color\",\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Passenger\": {\n      \"@id\": \"lyft:Passenger\",\n      \"@context\": {\n        \"\
  firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"phoneNumber\": \"schema:telephone\",\n        \"email\": \"schema:email\"\n      }\n    },\n\n    \"CostEstimate\": {\n      \"@id\": \"lyft:CostEstimate\",\n      \"@context\": {\n        \"rideType\": \"lyft:ride_type\",\n        \"displayName\": \"schema:name\",\n        \"currency\": \"schema:priceCurrency\",\n        \"estimatedCostCentsMin\": \"schema:minPrice\",\n        \"estimatedCostCentsMax\": \"schema:maxPrice\",\n        \"estimatedDistanceMiles\": \"schema:distance\",\n        \"estimatedDurationSeconds\": \"schema:duration\",\n        \"primetimePercentage\": \"lyft:primetimePercentage\"\n      }\n    },\n\n    \"Profile\": {\n      \"@id\": \"lyft:Profile\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"hasTakenARide\": \"lyft:hasTakenARide\"\n      }\n    },\n\n\
  \    \"Receipt\": {\n      \"@id\": \"lyft:Receipt\",\n      \"@context\": {\n        \"rideId\": \"lyft:ride_id\",\n        \"price\": \"schema:price\",\n        \"lineItems\": {\n          \"@id\": \"lyft:lineItems\",\n          \"@container\": \"@set\"\n        },\n        \"charges\": {\n          \"@id\": \"lyft:charges\",\n          \"@container\": \"@set\"\n        },\n        \"requestedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/lyft/refs/heads/main/json-ld/lyft-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
