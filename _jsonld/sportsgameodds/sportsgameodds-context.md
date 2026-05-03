---
api_specs:
- filename: sportsgameodds-openapi.yml
  format: yaml
  label: SportsGameOdds API
  slug: sportsgameodds
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsgameodds/refs/heads/main/openapi/sportsgameodds-openapi.yml
class_count: 36
classes:
- Event
- eventId
- sport
- status
- Team
- teamId
- name
- abbreviation
- OddsLine
- bookmaker
- market
- period
- oddId
- homeOdds
- awayOdds
- line
- Market
- marketId
- betType
- description
- Player
- playerId
- position
- team
- Sport
- sportId
- leagues
- League
- leagueId
- country
- UsageStats
- requestsToday
- requestsMonth
- dailyLimit
- monthlyLimit
- planName
context_file: json-ld/sportsgameodds-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sportsgameodds/refs/heads/main/json-ld/sportsgameodds-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sportsgameodds from SportsGameOdds.
layout: jsonld
name: Sportsgameodds Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: league
  type: schema:SportsOrganization
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: homeTeam
  type: schema:SportsTeam
- container: ''
  name: awayTeam
  type: schema:SportsTeam
- container: ''
  name: lastUpdated
  type: dateTime
property_count: 5
provider_name: SportsGameOdds
provider_slug: sportsgameodds
slug: sportsgameodds-context
source_filename: sportsgameodds-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://sportsgameodds.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Event\": \"schema:SportsEvent\",\n    \"eventId\": \"@id\",\n    \"sport\": \"schema:sport\",\n    \"league\": {\n      \"@id\": \"schema:memberOf\",\n      \"@type\": \"schema:SportsOrganization\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:eventStatus\",\n    \"homeTeam\": {\n      \"@id\": \"schema:homeTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"awayTeam\": {\n      \"@id\": \"schema:awayTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n\n    \"Team\": \"schema:SportsTeam\",\n    \"teamId\": \"@id\",\n    \"name\": \"schema:name\",\n    \"abbreviation\": \"schema:alternateName\",\n\n    \"OddsLine\": \"sportsgameodds:BettingOddsLine\",\n    \"bookmaker\": \"sportsgameodds:bookmaker\"\
  ,\n    \"market\": \"sportsgameodds:bettingMarket\",\n    \"period\": \"sportsgameodds:gamePeriod\",\n    \"oddId\": \"sportsgameodds:oddIdentifier\",\n    \"homeOdds\": \"sportsgameodds:homeOdds\",\n    \"awayOdds\": \"sportsgameodds:awayOdds\",\n    \"line\": \"sportsgameodds:pointSpread\",\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"Market\": \"sportsgameodds:BettingMarket\",\n    \"marketId\": \"@id\",\n    \"betType\": \"sportsgameodds:betType\",\n    \"description\": \"schema:description\",\n\n    \"Player\": \"schema:Person\",\n    \"playerId\": \"@id\",\n    \"position\": \"schema:jobTitle\",\n    \"team\": \"schema:memberOf\",\n\n    \"Sport\": \"sportsgameodds:Sport\",\n    \"sportId\": \"@id\",\n    \"leagues\": \"sportsgameodds:hasLeague\",\n\n    \"League\": \"sportsgameodds:League\",\n    \"leagueId\": \"@id\",\n    \"country\": \"schema:addressCountry\",\n\n    \"UsageStats\": \"sportsgameodds:ApiUsageStatistics\"\
  ,\n    \"requestsToday\": \"sportsgameodds:dailyRequestCount\",\n    \"requestsMonth\": \"sportsgameodds:monthlyRequestCount\",\n    \"dailyLimit\": \"sportsgameodds:dailyRateLimit\",\n    \"monthlyLimit\": \"sportsgameodds:monthlyRateLimit\",\n    \"planName\": \"sportsgameodds:subscriptionPlan\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sportsgameodds/refs/heads/main/json-ld/sportsgameodds-context.jsonld
tags:
- Sports Betting
- Odds
- Sports Data
- Fantasy Sports
- Gambling
- JSON-LD
- Linked Data
- Semantic Web
---
