---
api_specs:
- filename: thesports-football-openapi.yml
  format: yaml
  label: TheSports Football API
  slug: football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/openapi/thesports-football-openapi.yml
class_count: 27
classes:
- Match
- Competition
- Team
- Player
- home_team_id
- away_team_id
- home_score
- away_score
- scheduled
- competition_id
- season_id
- stage_id
- venue_id
- referee_id
- status
- short_name
- logo
- country_id
- jersey_number
- position
- market_value
- possession
- shots_on_target
- points
- goal_difference
- goals_for
- goals_against
context_file: json-ld/thesports-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/json-ld/thesports-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thesports from TheSports.
layout: jsonld
name: Thesports Context
namespaces:
- prefix: thesports
  uri: https://api.thesports.com/vocab#
properties: []
property_count: 0
provider_name: TheSports
provider_slug: thesports
slug: thesports-context
source_filename: thesports-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"thesports\": \"https://api.thesports.com/vocab#\",\n    \"Match\": \"SportsEvent\",\n    \"Competition\": \"SportsOrganization\",\n    \"Team\": \"SportsTeam\",\n    \"Player\": \"Person\",\n    \"home_team_id\": \"homeTeam\",\n    \"away_team_id\": \"awayTeam\",\n    \"home_score\": \"homeScore\",\n    \"away_score\": \"awayScore\",\n    \"scheduled\": \"startDate\",\n    \"competition_id\": \"organizer\",\n    \"season_id\": \"thesports:season\",\n    \"stage_id\": \"thesports:stage\",\n    \"venue_id\": \"location\",\n    \"referee_id\": \"thesports:referee\",\n    \"status\": \"thesports:matchStatus\",\n    \"short_name\": \"alternateName\",\n    \"logo\": \"logo\",\n    \"country_id\": \"nationality\",\n    \"jersey_number\": \"thesports:jerseyNumber\",\n    \"position\": \"thesports:playingPosition\",\n    \"market_value\": \"thesports:marketValue\",\n    \"possession\": \"thesports:possession\",\n\
  \    \"shots_on_target\": \"thesports:shotsOnTarget\",\n    \"points\": \"thesports:points\",\n    \"goal_difference\": \"thesports:goalDifference\",\n    \"goals_for\": \"thesports:goalsScored\",\n    \"goals_against\": \"thesports:goalsConceded\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thesports/refs/heads/main/json-ld/thesports-context.jsonld
tags:
- Sports
- Football
- Basketball
- Tennis
- Esports
- Data
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
