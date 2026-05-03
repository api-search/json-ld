---
api_specs:
- filename: the-odds-api-openapi.yml
  format: yaml
  label: The Odds API
  slug: the-odds-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/openapi/the-odds-api-openapi.yml
class_count: 24
classes:
- Event
- Sport
- Bookmaker
- Team
- id
- sport_key
- sport_title
- bookmakers
- markets
- outcomes
- key
- title
- price
- point
- name
- description
- completed
- scores
- score
- active
- group
- has_outrights
- previous_timestamp
- next_timestamp
context_file: json-ld/the-odds-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/json-ld/the-odds-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for The Odds Api from The Odds API.
layout: jsonld
name: The Odds Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: odds
  uri: https://the-odds-api.com/vocabulary/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: commence_time
  type: dateTime
- container: ''
  name: home_team
  type: schema:SportsTeam
- container: ''
  name: away_team
  type: schema:SportsTeam
- container: ''
  name: last_update
  type: dateTime
- container: ''
  name: timestamp
  type: dateTime
property_count: 5
provider_name: The Odds API
provider_slug: the-odds-api
slug: the-odds-api-context
source_filename: the-odds-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"odds\": \"https://the-odds-api.com/vocabulary/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Event\": \"schema:SportsEvent\",\n    \"Sport\": \"schema:SportsOrganization\",\n    \"Bookmaker\": \"schema:Organization\",\n    \"Team\": \"schema:SportsTeam\",\n\n    \"id\": \"schema:identifier\",\n    \"sport_key\": \"odds:sportKey\",\n    \"sport_title\": \"schema:name\",\n    \"commence_time\": { \"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\" },\n    \"home_team\": { \"@id\": \"odds:homeTeam\", \"@type\": \"schema:SportsTeam\" },\n    \"away_team\": { \"@id\": \"odds:awayTeam\", \"@type\": \"schema:SportsTeam\" },\n    \"bookmakers\": \"odds:bookmakers\",\n    \"markets\": \"odds:markets\",\n    \"outcomes\": \"odds:outcomes\",\n\n    \"key\": \"schema:identifier\",\n    \"title\": \"schema:name\",\n    \"last_update\": { \"@id\": \"schema:dateModified\"\
  , \"@type\": \"xsd:dateTime\" },\n    \"price\": \"odds:price\",\n    \"point\": \"odds:pointSpread\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n\n    \"completed\": \"odds:completed\",\n    \"scores\": \"odds:scores\",\n    \"score\": \"odds:score\",\n\n    \"active\": \"odds:active\",\n    \"group\": \"schema:category\",\n    \"has_outrights\": \"odds:hasOutrights\",\n\n    \"timestamp\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"previous_timestamp\": \"odds:previousTimestamp\",\n    \"next_timestamp\": \"odds:nextTimestamp\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/the-odds-api/refs/heads/main/json-ld/the-odds-api-context.jsonld
tags:
- Betting
- Odds
- Sports
- Scores
- Historical Data
- JSON-LD
- Linked Data
- Semantic Web
---
