---
api_specs:
- filename: spacex-api-openapi.yml
  format: yaml
  label: SpaceX API
  slug: spacex-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/openapi/spacex-api-openapi.yml
class_count: 17
classes:
- Launch
- Rocket
- Capsule
- Core
- CrewMember
- Launchpad
- Landpad
- Payload
- Ship
- StarlinkSatellite
- id
- name
- details
- flight_number
- reuse_count
- landing_success
- orbit
context_file: json-ld/spacex-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/json-ld/spacex-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spacex Api from SpaceX API.
layout: jsonld
name: Spacex Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spacex
  uri: https://api.spacexdata.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: date_utc
  type: dateTime
- container: ''
  name: upcoming
  type: boolean
- container: ''
  name: success
  type: boolean
- container: ''
  name: rocket
  type: reference
- container: ''
  name: launchpad
  type: reference
- container: ''
  name: payloads
  type: reference
- container: ''
  name: crew
  type: ''
- container: ''
  name: cores
  type: ''
- container: ''
  name: links
  type: ''
- container: ''
  name: active
  type: ''
- container: ''
  name: latitude
  type: decimal
- container: ''
  name: longitude
  type: decimal
- container: ''
  name: image
  type: reference
- container: ''
  name: wikipedia
  type: reference
- container: ''
  name: mass_kg
  type: decimal
property_count: 15
provider_name: SpaceX API
provider_slug: spacex-api
slug: spacex-api-context
source_filename: spacex-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spacex\": \"https://api.spacexdata.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Launch\": \"schema:Event\",\n    \"Rocket\": \"schema:Vehicle\",\n    \"Capsule\": \"schema:Vehicle\",\n    \"Core\": \"spacex:BoosterCore\",\n    \"CrewMember\": \"schema:Person\",\n    \"Launchpad\": \"schema:Place\",\n    \"Landpad\": \"schema:Place\",\n    \"Payload\": \"schema:Product\",\n    \"Ship\": \"schema:Vehicle\",\n    \"StarlinkSatellite\": \"schema:Vehicle\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"details\": \"schema:description\",\n    \"date_utc\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"flight_number\": \"spacex:flightNumber\",\n    \"upcoming\": {\n      \"@id\": \"spacex:upcoming\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"success\": {\n      \"@id\": \"spacex:success\",\n\
  \      \"@type\": \"xsd:boolean\"\n    },\n    \"rocket\": {\n      \"@id\": \"spacex:rocket\",\n      \"@type\": \"@id\"\n    },\n    \"launchpad\": {\n      \"@id\": \"schema:location\",\n      \"@type\": \"@id\"\n    },\n    \"payloads\": {\n      \"@id\": \"spacex:payload\",\n      \"@type\": \"@id\"\n    },\n    \"crew\": {\n      \"@id\": \"schema:performer\"\n    },\n    \"cores\": {\n      \"@id\": \"spacex:boosterCore\"\n    },\n    \"links\": {\n      \"@id\": \"schema:associatedMedia\"\n    },\n    \"active\": {\n      \"@id\": \"schema:isRelatedTo\"\n    },\n    \"latitude\": {\n      \"@id\": \"schema:latitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"longitude\": {\n      \"@id\": \"schema:longitude\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"image\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"wikipedia\": {\n      \"@id\": \"schema:sameAs\",\n      \"@type\": \"@id\"\n    },\n    \"reuse_count\": \"spacex:reuseCount\",\n\
  \    \"landing_success\": \"spacex:landingSuccess\",\n    \"orbit\": \"spacex:targetOrbit\",\n    \"mass_kg\": {\n      \"@id\": \"schema:weight\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spacex-api/refs/heads/main/json-ld/spacex-api-context.jsonld
tags:
- Space
- Aerospace
- Launches
- SpaceX
- JSON-LD
- Linked Data
- Semantic Web
---
