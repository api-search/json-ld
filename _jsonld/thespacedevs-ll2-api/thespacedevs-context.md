---
api_specs:
- filename: thespacedevs-ll2-api-openapi.yml
  format: yaml
  label: TheSpaceDevs Launch Library 2 API
  slug: thespacedevs-ll2-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thespacedevs-ll2-api/refs/heads/main/openapi/thespacedevs-ll2-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/thespacedevs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thespacedevs-ll2-api/refs/heads/main/json-ld/thespacedevs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thespacedevs from TheSpaceDevs LL2 API.
layout: jsonld
name: Thespacedevs Context
namespaces:
- prefix: spacedev
  uri: https://thespacedevs.com/ontology/
properties:
- container: ''
  name: SpaceLaunch
  type: ''
- container: ''
  name: Astronaut
  type: ''
- container: ''
  name: SpaceAgency
  type: ''
- container: ''
  name: SpaceStation
  type: ''
- container: ''
  name: LaunchPad
  type: ''
property_count: 5
provider_name: TheSpaceDevs LL2 API
provider_slug: thespacedevs-ll2-api
slug: thespacedevs-context
source_filename: thespacedevs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spacedev\": \"https://thespacedevs.com/ontology/\",\n    \"SpaceLaunch\": {\n      \"@id\": \"https://schema.org/Event\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"net\": \"https://schema.org/startDate\",\n        \"window_start\": \"https://schema.org/doorTime\",\n        \"window_end\": \"https://schema.org/endDate\",\n        \"status\": \"https://schema.org/eventStatus\",\n        \"probability\": \"spacedev:launchProbability\",\n        \"rocket\": {\n          \"@id\": \"spacedev:launchVehicle\",\n          \"@type\": \"@id\"\n        },\n        \"mission\": {\n          \"@id\": \"spacedev:mission\",\n          \"@type\": \"@id\"\n        },\n        \"pad\": {\n          \"@id\": \"https://schema.org/location\",\n          \"@type\": \"@id\"\n        },\n        \"launch_service_provider\": {\n          \"\
  @id\": \"https://schema.org/organizer\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"Astronaut\": {\n      \"@id\": \"https://schema.org/Person\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"nationality\": \"https://schema.org/nationality\",\n        \"agency\": {\n          \"@id\": \"https://schema.org/worksFor\",\n          \"@type\": \"@id\"\n        },\n        \"flights_count\": \"spacedev:spaceflightCount\",\n        \"spacewalks_count\": \"spacedev:spacewalkCount\",\n        \"status\": \"https://schema.org/hasOccupation\"\n      }\n    },\n    \"SpaceAgency\": {\n      \"@id\": \"https://schema.org/Organization\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"abbrev\": \"https://schema.org/alternateName\",\n        \"country_code\": \"https://schema.org/addressCountry\",\n        \"\
  total_launch_count\": \"spacedev:totalLaunches\"\n      }\n    },\n    \"SpaceStation\": {\n      \"@id\": \"spacedev:SpaceStation\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"orbit\": \"spacedev:orbitalRegime\",\n        \"status\": \"https://schema.org/operatingStatus\",\n        \"owners\": {\n          \"@id\": \"https://schema.org/owner\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n    \"LaunchPad\": {\n      \"@id\": \"https://schema.org/Place\",\n      \"@context\": {\n        \"id\": \"https://schema.org/identifier\",\n        \"name\": \"https://schema.org/name\",\n        \"latitude\": \"https://schema.org/latitude\",\n        \"longitude\": \"https://schema.org/longitude\",\n        \"location\": {\n          \"@id\": \"https://schema.org/containedInPlace\",\n          \"@type\": \"@id\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thespacedevs-ll2-api/refs/heads/main/json-ld/thespacedevs-context.jsonld
tags:
- Space
- Satellites
- Launches
- Rockets
- Astronauts
- JSON-LD
- Linked Data
- Semantic Web
---
