---
api_specs:
- filename: sportradar-sports-data-openapi.yml
  format: yaml
  label: Sportradar Sports Data API
  slug: sports-data-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/openapi/sportradar-sports-data-openapi.yml
class_count: 42
classes:
- SportEvent
- Competitor
- Player
- Venue
- Tournament
- Season
- id
- name
- abbreviation
- shortName
- description
- url
- startTimeConfirmed
- status
- qualifier
- homeTeam
- awayTeam
- tournament
- season
- round
- venue
- country
- countryCode
- city
- capacity
- gender
- sport
- category
- homeScore
- awayScore
- winPct
- wins
- losses
- rank
- nationality
- height
- weight
- jerseyNumber
- position
- starter
- live
- coverage
context_file: json-ld/sportradar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/json-ld/sportradar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sportradar from Sportradar.
layout: jsonld
name: Sportradar Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sportradar
  uri: https://developer.sportradar.com/vocab#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: scheduled
  type: dateTime
- container: set
  name: competitors
  type: ''
- container: ''
  name: dateOfBirth
  type: date
property_count: 3
provider_name: Sportradar
provider_slug: sportradar
slug: sportradar-context
source_filename: sportradar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sportradar\": \"https://developer.sportradar.com/vocab#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"SportEvent\": \"schema:SportsEvent\",\n    \"Competitor\": \"schema:SportsTeam\",\n    \"Player\": \"schema:Person\",\n    \"Venue\": \"schema:SportsActivityLocation\",\n    \"Tournament\": \"schema:SportsOrganization\",\n    \"Season\": \"schema:Event\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"abbreviation\": \"sportradar:abbreviation\",\n    \"shortName\": \"schema:alternateName\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n\n    \"scheduled\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startTimeConfirmed\": \"sportradar:startTimeConfirmed\",\n    \"status\": \"sportradar:eventStatus\",\n\n    \"competitors\": {\n      \"@id\": \"sportradar:hasCompetitor\",\n\
  \      \"@container\": \"@set\"\n    },\n    \"qualifier\": \"sportradar:qualifier\",\n    \"homeTeam\": \"schema:homeTeam\",\n    \"awayTeam\": \"schema:awayTeam\",\n\n    \"tournament\": \"sportradar:tournament\",\n    \"season\": \"sportradar:season\",\n    \"round\": \"sportradar:round\",\n    \"venue\": \"schema:location\",\n\n    \"country\": \"schema:addressCountry\",\n    \"countryCode\": \"schema:addressCountry\",\n    \"city\": \"schema:addressLocality\",\n    \"capacity\": \"sportradar:capacity\",\n    \"gender\": \"schema:gender\",\n\n    \"sport\": \"sportradar:sport\",\n    \"category\": \"sportradar:category\",\n\n    \"homeScore\": \"sportradar:homeScore\",\n    \"awayScore\": \"sportradar:awayScore\",\n    \"winPct\": \"sportradar:winPercentage\",\n    \"wins\": \"sportradar:wins\",\n    \"losses\": \"sportradar:losses\",\n    \"rank\": \"sportradar:rank\",\n\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"nationality\"\
  : \"schema:nationality\",\n    \"height\": \"sportradar:height\",\n    \"weight\": \"sportradar:weight\",\n    \"jerseyNumber\": \"sportradar:jerseyNumber\",\n    \"position\": \"sportradar:position\",\n    \"starter\": \"sportradar:starter\",\n\n    \"live\": \"sportradar:liveCoverage\",\n    \"coverage\": \"sportradar:coverage\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sportradar/refs/heads/main/json-ld/sportradar-context.jsonld
tags:
- Data
- Esports
- Fantasy Sports
- Media
- Real-Time
- Sports
- Sports Data
- Statistics
- JSON-LD
- Linked Data
- Semantic Web
---
