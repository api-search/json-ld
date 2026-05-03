---
api_specs:
- filename: thesportsdb-openapi.yml
  format: yaml
  label: TheSportsDB API
  slug: thesportsdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/openapi/thesportsdb-openapi.yml
class_count: 0
classes: []
context_file: json-ld/thesportsdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/json-ld/thesportsdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thesportsdb from TheSportsDB.
layout: jsonld
name: Thesportsdb Context
namespaces:
- prefix: sportsdb
  uri: https://www.thesportsdb.com/ontology/
properties:
- container: ''
  name: SportsTeam
  type: ''
- container: ''
  name: SportsEvent
  type: ''
- container: ''
  name: Athlete
  type: ''
- container: ''
  name: SportsLeague
  type: ''
property_count: 4
provider_name: TheSportsDB
provider_slug: thesportsdb
slug: thesportsdb-context
source_filename: thesportsdb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sportsdb\": \"https://www.thesportsdb.com/ontology/\",\n    \"SportsTeam\": {\n      \"@id\": \"https://schema.org/SportsTeam\",\n      \"@context\": {\n        \"idTeam\": \"https://schema.org/identifier\",\n        \"strTeam\": \"https://schema.org/name\",\n        \"strTeamShort\": \"https://schema.org/alternateName\",\n        \"strLeague\": {\n          \"@id\": \"https://schema.org/memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"strSport\": \"https://schema.org/sport\",\n        \"strCountry\": \"https://schema.org/addressCountry\",\n        \"strStadium\": {\n          \"@id\": \"https://schema.org/location\",\n          \"@type\": \"@id\"\n        },\n        \"strWebsite\": \"https://schema.org/url\",\n        \"strDescriptionEN\": \"https://schema.org/description\",\n        \"strTeamBadge\": \"https://schema.org/logo\",\n        \"intFormedYear\": \"https://schema.org/foundingDate\"\
  \n      }\n    },\n    \"SportsEvent\": {\n      \"@id\": \"https://schema.org/SportsEvent\",\n      \"@context\": {\n        \"idEvent\": \"https://schema.org/identifier\",\n        \"strEvent\": \"https://schema.org/name\",\n        \"strLeague\": {\n          \"@id\": \"https://schema.org/superEvent\",\n          \"@type\": \"@id\"\n        },\n        \"strHomeTeam\": {\n          \"@id\": \"https://schema.org/homeTeam\",\n          \"@type\": \"@id\"\n        },\n        \"strAwayTeam\": {\n          \"@id\": \"https://schema.org/awayTeam\",\n          \"@type\": \"@id\"\n        },\n        \"dateEvent\": \"https://schema.org/startDate\",\n        \"strVenue\": {\n          \"@id\": \"https://schema.org/location\",\n          \"@type\": \"@id\"\n        },\n        \"strStatus\": \"https://schema.org/eventStatus\"\n      }\n    },\n    \"Athlete\": {\n      \"@id\": \"https://schema.org/Person\",\n      \"@context\": {\n        \"idPlayer\": \"https://schema.org/identifier\",\n \
  \       \"strPlayer\": \"https://schema.org/name\",\n        \"strTeam\": {\n          \"@id\": \"https://schema.org/memberOf\",\n          \"@type\": \"@id\"\n        },\n        \"strSport\": \"https://schema.org/sport\",\n        \"dateBorn\": \"https://schema.org/birthDate\",\n        \"strNationality\": \"https://schema.org/nationality\",\n        \"strPosition\": \"https://schema.org/hasOccupation\"\n      }\n    },\n    \"SportsLeague\": {\n      \"@id\": \"https://schema.org/SportsOrganization\",\n      \"@context\": {\n        \"idLeague\": \"https://schema.org/identifier\",\n        \"strLeague\": \"https://schema.org/name\",\n        \"strSport\": \"https://schema.org/sport\",\n        \"strCountry\": \"https://schema.org/addressCountry\",\n        \"strBadge\": \"https://schema.org/logo\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/json-ld/thesportsdb-context.jsonld
tags:
- Sports
- Database
- Free
- Open Data
- Teams
- Players
- Events
- JSON-LD
- Linked Data
- Semantic Web
---
