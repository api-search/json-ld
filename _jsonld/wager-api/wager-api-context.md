---
api_specs:
- filename: wager-api-openapi.yml
  format: yaml
  label: Wager API - Sports Odds
  slug: wager-api-odds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml
- filename: wager-api-openapi.yml
  format: yaml
  label: Wager API - Fantasy Sports Data
  slug: wager-api-fantasy
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/openapi/wager-api-openapi.yml
class_count: 34
classes:
- SportsOdds
- Game
- game_id
- sport
- league
- venue
- status
- home_score
- away_score
- OddsMarket
- market
- sportsbook
- home_line
- home_odds
- away_line
- away_odds
- PlayerProp
- prop_id
- player_id
- player_name
- line
- over_odds
- under_odds
- Player
- first_name
- last_name
- full_name
- position
- team_name
- InjuryReport
- injury_type
- injury_status
- practice_status
- return_timeline
context_file: json-ld/wager-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/json-ld/wager-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Wager Api from Wager API.
layout: jsonld
name: Wager Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: wager
  uri: https://wagerapi.com/vocab/
properties:
- container: ''
  name: home_team
  type: schema:SportsTeam
- container: ''
  name: away_team
  type: schema:SportsTeam
- container: ''
  name: game_date
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
property_count: 4
provider_name: Wager API
provider_slug: wager-api
slug: wager-api-context
source_filename: wager-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"wager\": \"https://wagerapi.com/vocab/\",\n\n    \"SportsOdds\": \"wager:SportsOdds\",\n    \"Game\": \"schema:SportsEvent\",\n    \"game_id\": \"@id\",\n    \"sport\": \"wager:sport\",\n    \"league\": \"schema:organizer\",\n    \"home_team\": {\n      \"@id\": \"schema:homeTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"away_team\": {\n      \"@id\": \"schema:awayTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"game_date\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"venue\": \"schema:location\",\n    \"status\": \"schema:eventStatus\",\n    \"home_score\": \"wager:homeScore\",\n    \"away_score\": \"wager:awayScore\",\n\n    \"OddsMarket\": \"wager:OddsMarket\",\n    \"market\": \"wager:marketType\",\n    \"sportsbook\": \"wager:sportsbook\",\n    \"home_line\"\
  : \"wager:homeLine\",\n    \"home_odds\": \"wager:homeOdds\",\n    \"away_line\": \"wager:awayLine\",\n    \"away_odds\": \"wager:awayOdds\",\n\n    \"PlayerProp\": \"wager:PlayerProp\",\n    \"prop_id\": \"@id\",\n    \"player_id\": \"wager:playerId\",\n    \"player_name\": \"schema:name\",\n    \"line\": \"wager:propLine\",\n    \"over_odds\": \"wager:overOdds\",\n    \"under_odds\": \"wager:underOdds\",\n\n    \"Player\": \"schema:Person\",\n    \"first_name\": \"schema:givenName\",\n    \"last_name\": \"schema:familyName\",\n    \"full_name\": \"schema:name\",\n    \"position\": \"schema:jobTitle\",\n    \"team_name\": \"schema:memberOf\",\n\n    \"InjuryReport\": \"wager:InjuryReport\",\n    \"injury_type\": \"wager:injuryType\",\n    \"injury_status\": \"wager:injuryStatus\",\n    \"practice_status\": \"wager:practiceStatus\",\n    \"return_timeline\": \"wager:returnTimeline\",\n\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n\
  \    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/wager-api/refs/heads/main/json-ld/wager-api-context.jsonld
tags:
- Sports Betting
- Sports Odds
- Fantasy Sports
- Sports Data
- NFL
- NBA
- MLB
- NHL
- NCAA
- JSON-LD
- Linked Data
- Semantic Web
---
