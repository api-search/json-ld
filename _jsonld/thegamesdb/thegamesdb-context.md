---
api_specs:
- filename: thegamesdb-openapi.yml
  format: yaml
  label: TheGamesDB API
  slug: thegamesdb
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/openapi/thegamesdb-openapi.yml
class_count: 9
classes:
- Game
- GameImage
- GamesImagesResponse
- PlatformsResponse
- GamesByGameIDResponse
- Platform
- GamesUpdatesResponse
- GenresDevelopersPublishersResponse
- name
context_file: json-ld/thegamesdb-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/json-ld/thegamesdb-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Thegamesdb from TheGamesDB.
layout: jsonld
name: Thegamesdb Context
namespaces:
- prefix: gamesdb
  uri: https://api.thegamesdb.net/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: integer
- container: ''
  name: gameTitle
  type: string
- container: ''
  name: releaseDate
  type: string
- container: ''
  name: platform
  type: integer
- container: ''
  name: regionId
  type: integer
- container: ''
  name: countryId
  type: integer
- container: ''
  name: overview
  type: string
- container: ''
  name: youtube
  type: string
- container: ''
  name: players
  type: integer
- container: ''
  name: coop
  type: string
- container: ''
  name: rating
  type: string
- container: set
  name: alternates
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: side
  type: string
- container: ''
  name: filename
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: images
  type: string
- container: ''
  name: baseUrl
  type: string
- container: ''
  name: original
  type: string
- container: ''
  name: medium
  type: string
- container: ''
  name: small
  type: string
- container: ''
  name: large
  type: string
- container: ''
  name: thumb
  type: string
- container: ''
  name: remainingMonthlyAllowance
  type: integer
- container: ''
  name: extraAllowance
  type: integer
- container: ''
  name: alias
  type: string
- container: ''
  name: icon
  type: string
- container: ''
  name: console
  type: string
- container: ''
  name: controller
  type: string
- container: ''
  name: developer
  type: string
- container: ''
  name: manufacturer
  type: string
property_count: 35
provider_name: TheGamesDB
provider_slug: thegamesdb
slug: thegamesdb-context
source_filename: thegamesdb-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gamesdb\": \"https://api.thegamesdb.net/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Game\": \"gamesdb:Game\",\n    \"GameImage\": \"gamesdb:GameImage\",\n    \"GamesImagesResponse\": \"gamesdb:GamesImagesResponse\",\n    \"PlatformsResponse\": \"gamesdb:PlatformsResponse\",\n    \"GamesByGameIDResponse\": \"gamesdb:GamesByGameIDResponse\",\n    \"Platform\": \"gamesdb:Platform\",\n    \"GamesUpdatesResponse\": \"gamesdb:GamesUpdatesResponse\",\n    \"GenresDevelopersPublishersResponse\": \"gamesdb:GenresDevelopersPublishersResponse\",\n    \"id\": {\n      \"@id\": \"gamesdb:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gameTitle\": {\n      \"@id\": \"gamesdb:game_title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"gamesdb:release_date\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"gamesdb:platform\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"regionId\": {\n      \"@id\": \"gamesdb:region_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"countryId\": {\n      \"@id\": \"gamesdb:country_id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"overview\": {\n      \"@id\": \"gamesdb:overview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"youtube\": {\n      \"@id\": \"gamesdb:youtube\",\n      \"@type\": \"xsd:string\"\n    },\n    \"players\": {\n      \"@id\": \"gamesdb:players\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"coop\": {\n      \"@id\": \"gamesdb:coop\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rating\": {\n      \"@id\": \"gamesdb:rating\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alternates\": {\n      \"@id\": \"gamesdb:alternates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"gamesdb:type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"side\": {\n      \"@id\": \"gamesdb:side\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filename\": {\n      \"@id\": \"gamesdb:filename\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"gamesdb:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"gamesdb:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"gamesdb:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"gamesdb:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"gamesdb:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"images\": {\n      \"@id\": \"gamesdb:images\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"gamesdb:base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"original\": {\n      \"@id\": \"gamesdb:original\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"medium\": {\n      \"@id\": \"gamesdb:medium\",\n      \"@type\": \"xsd:string\"\n    },\n    \"small\": {\n      \"@id\": \"gamesdb:small\",\n      \"@type\": \"xsd:string\"\n    },\n    \"large\": {\n      \"@id\": \"gamesdb:large\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumb\": {\n      \"@id\": \"gamesdb:thumb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remainingMonthlyAllowance\": {\n      \"@id\": \"gamesdb:remaining_monthly_allowance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"extraAllowance\": {\n      \"@id\": \"gamesdb:extra_allowance\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"alias\": {\n      \"@id\": \"gamesdb:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"icon\": {\n      \"@id\": \"gamesdb:icon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"console\": {\n      \"@id\": \"gamesdb:console\",\n      \"@type\": \"xsd:string\"\n    },\n    \"controller\": {\n      \"@id\": \"gamesdb:controller\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"developer\": {\n      \"@id\": \"gamesdb:developer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manufacturer\": {\n      \"@id\": \"gamesdb:manufacturer\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/thegamesdb/refs/heads/main/json-ld/thegamesdb-context.jsonld
tags:
- Database
- Gaming
- Video Games
- Metadata
- Artwork
- JSON-LD
- Linked Data
- Semantic Web
---
