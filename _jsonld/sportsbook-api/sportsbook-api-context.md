---
api_specs:
- filename: sportsbook-api-openapi.yml
  format: yaml
  label: Sportsbook API
  slug: sportsbook-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportsbook-api/refs/heads/main/openapi/sportsbook-api-openapi.yml
class_count: 29
classes:
- OddsResponse
- sport
- league
- events
- EventOdds
- eventId
- status
- markets
- MarketOdds
- market
- period
- bookmakers
- BookmakerOdds
- bookmaker
- homeOdds
- awayOdds
- line
- ArbitrageOpportunity
- bookmaker1
- bookmaker2
- profit
- impliedProbabilitySum
- PositiveEvBet
- expectedValue
- fairOdds
- MiddleOpportunity
- window
- line1
- line2
context_file: json-ld/sportsbook-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sportsbook-api/refs/heads/main/json-ld/sportsbook-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sportsbook Api from Sportsbook API.
layout: jsonld
name: Sportsbook Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: gr
  uri: http://purl.org/goodrelations/v1#
properties:
- container: ''
  name: homeTeam
  type: schema:SportsTeam
- container: ''
  name: awayTeam
  type: schema:SportsTeam
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: lastUpdated
  type: dateTime
- container: ''
  name: detectedAt
  type: dateTime
property_count: 5
provider_name: Sportsbook API
provider_slug: sportsbook-api
slug: sportsbook-api-context
source_filename: sportsbook-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://sportsbookapi.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"gr\": \"http://purl.org/goodrelations/v1#\",\n\n    \"OddsResponse\": \"sportsbook:OddsDataSet\",\n    \"sport\": \"sportsbook:sport\",\n    \"league\": \"sportsbook:league\",\n    \"events\": \"sportsbook:hasEvent\",\n\n    \"EventOdds\": \"schema:SportsEvent\",\n    \"eventId\": \"@id\",\n    \"homeTeam\": {\n      \"@id\": \"schema:homeTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"awayTeam\": {\n      \"@id\": \"schema:awayTeam\",\n      \"@type\": \"schema:SportsTeam\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": \"schema:eventStatus\",\n    \"markets\": \"sportsbook:hasBettingMarket\",\n\n    \"MarketOdds\": \"sportsbook:BettingMarket\",\n    \"market\": \"sportsbook:marketType\",\n    \"period\"\
  : \"sportsbook:gamePeriod\",\n    \"bookmakers\": \"sportsbook:hasBookmaker\",\n\n    \"BookmakerOdds\": \"sportsbook:BookmakerLine\",\n    \"bookmaker\": \"sportsbook:bookmakerName\",\n    \"homeOdds\": \"sportsbook:homeOdds\",\n    \"awayOdds\": \"sportsbook:awayOdds\",\n    \"line\": \"sportsbook:pointLine\",\n    \"lastUpdated\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"ArbitrageOpportunity\": \"sportsbook:ArbitrageBet\",\n    \"bookmaker1\": \"sportsbook:primaryBookmaker\",\n    \"bookmaker2\": \"sportsbook:secondaryBookmaker\",\n    \"profit\": \"sportsbook:guaranteedProfit\",\n    \"impliedProbabilitySum\": \"sportsbook:impliedProbabilitySum\",\n    \"detectedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"PositiveEvBet\": \"sportsbook:PositiveExpectedValueBet\",\n    \"expectedValue\": \"sportsbook:expectedValue\",\n    \"fairOdds\": \"sportsbook:noVigOdds\",\n\n    \"MiddleOpportunity\"\
  : \"sportsbook:MiddleBet\",\n    \"window\": \"sportsbook:middleWindow\",\n    \"line1\": \"sportsbook:primaryLine\",\n    \"line2\": \"sportsbook:secondaryLine\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sportsbook-api/refs/heads/main/json-ld/sportsbook-api-context.jsonld
tags:
- Sports Betting
- Odds
- Sports Data
- Gambling
- JSON-LD
- Linked Data
- Semantic Web
---
