---
api_specs:
- filename: statorium-football-api-openapi.yml
  format: yaml
  label: Statorium Football API
  slug: football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-football-api-openapi.yml
- filename: statorium-basketball-api-openapi.yml
  format: yaml
  label: Statorium Basketball API
  slug: basketball-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-basketball-api-openapi.yml
- filename: statorium-american-football-api-openapi.yml
  format: yaml
  label: Statorium American Football API
  slug: american-football-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/openapi/statorium-american-football-api-openapi.yml
class_count: 37
classes:
- id
- type
- Match
- Team
- Player
- League
- Season
- homeTeam
- awayTeam
- homeScore
- awayScore
- status
- matchDate
- name
- country
- logoUrl
- founded
- stadium
- city
- nationality
- position
- dateOfBirth
- shirtNumber
- leagueId
- seasonId
- minute
- nameTranslated
- venue
- referee
- points
- wins
- losses
- draws
- goalsFor
- goalsAgainst
- goalDifference
- played
context_file: json-ld/statorium-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/json-ld/statorium-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Statorium from Statorium.
layout: jsonld
name: Statorium Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: statorium
  uri: https://statorium.com/vocab/
properties: []
property_count: 0
provider_name: Statorium
provider_slug: statorium
slug: statorium-context
source_filename: statorium-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"statorium\": \"https://statorium.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Match\": \"schema:SportsEvent\",\n    \"Team\": \"schema:SportsTeam\",\n    \"Player\": \"schema:Person\",\n    \"League\": \"schema:SportsOrganization\",\n    \"Season\": \"statorium:Season\",\n    \"homeTeam\": \"schema:homeTeam\",\n    \"awayTeam\": \"schema:awayTeam\",\n    \"homeScore\": \"schema:homeScore\",\n    \"awayScore\": \"schema:awayScore\",\n    \"status\": \"schema:eventStatus\",\n    \"matchDate\": \"schema:startDate\",\n    \"name\": \"schema:name\",\n    \"country\": \"schema:addressCountry\",\n    \"logoUrl\": \"schema:logo\",\n    \"founded\": \"schema:foundingDate\",\n    \"stadium\": \"schema:location\",\n    \"city\": \"schema:addressLocality\",\n    \"nationality\": \"schema:nationality\",\n    \"position\": \"schema:jobTitle\",\n    \"dateOfBirth\": \"schema:birthDate\"\
  ,\n    \"shirtNumber\": \"statorium:shirtNumber\",\n    \"leagueId\": \"statorium:leagueId\",\n    \"seasonId\": \"statorium:seasonId\",\n    \"minute\": \"statorium:matchMinute\",\n    \"nameTranslated\": \"statorium:nameTranslated\",\n    \"venue\": \"schema:location\",\n    \"referee\": \"statorium:referee\",\n    \"points\": \"statorium:points\",\n    \"wins\": \"statorium:wins\",\n    \"losses\": \"statorium:losses\",\n    \"draws\": \"statorium:draws\",\n    \"goalsFor\": \"statorium:goalsFor\",\n    \"goalsAgainst\": \"statorium:goalsAgainst\",\n    \"goalDifference\": \"statorium:goalDifference\",\n    \"played\": \"statorium:played\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/statorium/refs/heads/main/json-ld/statorium-context.jsonld
tags:
- Sports
- Sports Data
- Football
- Soccer
- Basketball
- American Football
- Live Scores
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---
