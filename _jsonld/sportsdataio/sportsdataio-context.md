---
api_specs:
- filename: sportsdataio-nfl-openapi.yml
  format: yaml
  label: SportsDataIO NFL API
  slug: sportsdataio-nfl
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nfl-openapi.yml
- filename: sportsdataio-mlb-openapi.yml
  format: yaml
  label: SportsDataIO MLB API
  slug: sportsdataio-mlb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-mlb-openapi.yml
- filename: sportsdataio-nba-openapi.yml
  format: yaml
  label: SportsDataIO NBA API
  slug: sportsdataio-nba
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nba-openapi.yml
- filename: sportsdataio-nhl-openapi.yml
  format: yaml
  label: SportsDataIO NHL API
  slug: sportsdataio-nhl
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-nhl-openapi.yml
- filename: sportsdataio-soccer-openapi.yml
  format: yaml
  label: SportsDataIO Soccer API
  slug: sportsdataio-soccer
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/openapi/sportsdataio-soccer-openapi.yml
class_count: 39
classes:
- Game
- gameId
- season
- week
- homeScore
- awayScore
- status
- Player
- playerId
- name
- position
- injury
- PlayerStats
- playerStatId
- fantasyPoints
- fantasyPointsPPR
- passingYards
- rushingYards
- receivingYards
- touchdowns
- Team
- teamId
- fullName
- abbreviation
- city
- conference
- division
- Standing
- wins
- losses
- ties
- winPercentage
- pointsFor
- pointsAgainst
- Odds
- pointSpread
- overUnder
- homeMoneyLine
- awayMoneyLine
context_file: json-ld/sportsdataio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/json-ld/sportsdataio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sportsdataio from SportsDataIO.
layout: jsonld
name: Sportsdataio Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: homeTeam
  type: schema:SportsTeam
- container: ''
  name: awayTeam
  type: schema:SportsTeam
- container: ''
  name: gameDate
  type: dateTime
- container: ''
  name: team
  type: schema:SportsTeam
property_count: 4
provider_name: SportsDataIO
provider_slug: sportsdataio
slug: sportsdataio-context
source_filename: sportsdataio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://sportsdata.io/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Game\": \"schema:SportsEvent\",\n    \"gameId\": \"@id\",\n    \"season\": \"sportsdataio:season\",\n    \"week\": \"sportsdataio:week\",\n    \"homeTeam\": {\n      \"@id\": \"schema:homeTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"awayTeam\": {\n      \"@id\": \"schema:awayTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"homeScore\": \"sportsdataio:homeScore\",\n    \"awayScore\": \"sportsdataio:awayScore\",\n    \"status\": \"schema:eventStatus\",\n    \"gameDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Player\": \"schema:Person\",\n    \"playerId\": \"@id\",\n    \"name\": \"schema:name\",\n    \"position\": \"schema:jobTitle\",\n    \"team\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"schema:SportsTeam\"\
  \n    },\n    \"status\": \"sportsdataio:playerStatus\",\n    \"injury\": \"sportsdataio:injuryStatus\",\n\n    \"PlayerStats\": \"sportsdataio:PlayerStatistics\",\n    \"playerStatId\": \"@id\",\n    \"fantasyPoints\": \"sportsdataio:fantasyPoints\",\n    \"fantasyPointsPPR\": \"sportsdataio:fantasyPointsPPR\",\n    \"passingYards\": \"sportsdataio:passingYards\",\n    \"rushingYards\": \"sportsdataio:rushingYards\",\n    \"receivingYards\": \"sportsdataio:receivingYards\",\n    \"touchdowns\": \"sportsdataio:touchdowns\",\n\n    \"Team\": \"schema:SportsTeam\",\n    \"teamId\": \"@id\",\n    \"fullName\": \"schema:name\",\n    \"abbreviation\": \"schema:alternateName\",\n    \"city\": \"schema:addressLocality\",\n    \"conference\": \"sportsdataio:conference\",\n    \"division\": \"sportsdataio:division\",\n\n    \"Standing\": \"sportsdataio:TeamStanding\",\n    \"wins\": \"sportsdataio:wins\",\n    \"losses\": \"sportsdataio:losses\",\n    \"ties\": \"sportsdataio:ties\",\n    \"winPercentage\"\
  : \"sportsdataio:winPercentage\",\n    \"pointsFor\": \"sportsdataio:pointsFor\",\n    \"pointsAgainst\": \"sportsdataio:pointsAgainst\",\n\n    \"Odds\": \"sportsdataio:BettingOdds\",\n    \"pointSpread\": \"sportsdataio:pointSpread\",\n    \"overUnder\": \"sportsdataio:overUnder\",\n    \"homeMoneyLine\": \"sportsdataio:homeMoneyLine\",\n    \"awayMoneyLine\": \"sportsdataio:awayMoneyLine\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sportsdataio/refs/heads/main/json-ld/sportsdataio-context.jsonld
tags:
- Sports Data
- Statistics
- Live Scores
- Fantasy Sports
- Odds
- NFL
- NBA
- MLB
- NHL
- Soccer
- JSON-LD
- Linked Data
- Semantic Web
---
