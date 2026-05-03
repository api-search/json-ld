---
api_specs:
- filename: stats-perform-stats-api-openapi.yml
  format: yaml
  label: STATS API
  slug: stats-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/openapi/stats-perform-stats-api-openapi.yml
class_count: 42
classes:
- id
- type
- Event
- Team
- Player
- Article
- BoxScore
- PlayByPlay
- eventId
- startDateTime
- status
- sport
- league
- homeTeam
- awayTeam
- homeScore
- awayScore
- periods
- teamId
- name
- abbreviation
- city
- conference
- division
- logoUrl
- founded
- venue
- playerId
- firstName
- lastName
- position
- jerseyNumber
- birthDate
- birthCity
- headline
- publishedAt
- body
- season
- wins
- losses
- winPct
- points
context_file: json-ld/stats-perform-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/json-ld/stats-perform-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Stats Perform from Stats Perform.
layout: jsonld
name: Stats Perform Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: stats
  uri: https://statsperform.com/vocab/
properties: []
property_count: 0
provider_name: Stats Perform
provider_slug: stats-perform
slug: stats-perform-context
source_filename: stats-perform-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"stats\": \"https://statsperform.com/vocab/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Event\": \"schema:SportsEvent\",\n    \"Team\": \"schema:SportsTeam\",\n    \"Player\": \"schema:Person\",\n    \"Article\": \"schema:NewsArticle\",\n    \"BoxScore\": \"stats:BoxScore\",\n    \"PlayByPlay\": \"stats:PlayByPlay\",\n    \"eventId\": \"stats:eventId\",\n    \"startDateTime\": \"schema:startDate\",\n    \"status\": \"schema:eventStatus\",\n    \"sport\": \"stats:sport\",\n    \"league\": \"stats:league\",\n    \"homeTeam\": \"schema:homeTeam\",\n    \"awayTeam\": \"schema:awayTeam\",\n    \"homeScore\": \"schema:homeScore\",\n    \"awayScore\": \"schema:awayScore\",\n    \"periods\": \"stats:periods\",\n    \"teamId\": \"stats:teamId\",\n    \"name\": \"schema:name\",\n    \"abbreviation\": \"stats:abbreviation\",\n    \"city\": \"schema:addressLocality\",\n    \"conference\"\
  : \"stats:conference\",\n    \"division\": \"stats:division\",\n    \"logoUrl\": \"schema:logo\",\n    \"founded\": \"schema:foundingDate\",\n    \"venue\": \"schema:location\",\n    \"playerId\": \"stats:playerId\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"position\": \"schema:jobTitle\",\n    \"jerseyNumber\": \"stats:jerseyNumber\",\n    \"birthDate\": \"schema:birthDate\",\n    \"birthCity\": \"schema:birthPlace\",\n    \"headline\": \"schema:headline\",\n    \"publishedAt\": \"schema:datePublished\",\n    \"body\": \"schema:articleBody\",\n    \"season\": \"stats:season\",\n    \"wins\": \"stats:wins\",\n    \"losses\": \"stats:losses\",\n    \"winPct\": \"stats:winPercentage\",\n    \"points\": \"stats:points\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/stats-perform/refs/heads/main/json-ld/stats-perform-context.jsonld
tags:
- Sports
- Sports Data
- Football
- Baseball
- Basketball
- Hockey
- Soccer
- Golf
- Tennis
- Live Scores
- Statistics
- Sports Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
