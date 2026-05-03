---
api_specs:
- filename: taylor-morrison-home-search-openapi.yml
  format: yaml
  label: Taylor Morrison Home Search API
  slug: taylor-morrison-home-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/taylor-morrison-home/refs/heads/main/openapi/taylor-morrison-home-search-openapi.yml
class_count: 26
classes:
- Residence
- House
- homeId
- communityId
- lotId
- floorPlanId
- constructionStatus
- bedrooms
- bathrooms
- sqft
- price
- address
- images
- virtualTourUrl
- Community
- FloorPlan
- Lot
- Reservation
- DesignOption
- amenities
- estimatedCompletion
- LandmarksOrHistoricalBuildings
- RealEstateListing
- geo
- latitude
- longitude
context_file: json-ld/taylor-morrison-home-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/taylor-morrison-home/refs/heads/main/json-ld/taylor-morrison-home-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Taylor Morrison Home from taylor-morrison-home.
layout: jsonld
name: Taylor Morrison Home Context
namespaces:
- prefix: tm
  uri: https://www.taylormorrison.com/vocab/
properties: []
property_count: 0
provider_name: taylor-morrison-home
provider_slug: taylor-morrison-home
slug: taylor-morrison-home-context
source_filename: taylor-morrison-home-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tm\": \"https://www.taylormorrison.com/vocab/\",\n    \"Residence\": \"schema:Residence\",\n    \"House\": \"schema:House\",\n    \"homeId\": \"tm:homeId\",\n    \"communityId\": \"tm:communityId\",\n    \"lotId\": \"tm:lotId\",\n    \"floorPlanId\": \"tm:floorPlanId\",\n    \"constructionStatus\": \"tm:constructionStatus\",\n    \"bedrooms\": \"schema:numberOfRooms\",\n    \"bathrooms\": \"schema:numberOfBathroomsTotal\",\n    \"sqft\": \"schema:floorSize\",\n    \"price\": \"schema:price\",\n    \"address\": \"schema:address\",\n    \"images\": \"schema:image\",\n    \"virtualTourUrl\": \"schema:virtualTourUrl\",\n    \"Community\": \"tm:Community\",\n    \"FloorPlan\": \"tm:FloorPlan\",\n    \"Lot\": \"tm:Lot\",\n    \"Reservation\": \"tm:Reservation\",\n    \"DesignOption\": \"tm:DesignOption\",\n    \"amenities\": \"schema:amenityFeature\",\n    \"estimatedCompletion\": \"schema:dateCreated\",\n    \"\
  LandmarksOrHistoricalBuildings\": \"schema:LandmarksOrHistoricalBuildings\",\n    \"RealEstateListing\": \"schema:RealEstateListing\",\n    \"geo\": \"schema:geo\",\n    \"latitude\": \"schema:latitude\",\n    \"longitude\": \"schema:longitude\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/taylor-morrison-home/refs/heads/main/json-ld/taylor-morrison-home-context.jsonld
tags:
- Homebuilding
- Real Estate
- Fortune 1000
- New Homes
- Communities
- Mortgage
- JSON-LD
- Linked Data
- Semantic Web
---
