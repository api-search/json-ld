---
api_specs:
- filename: blizzard-world-of-warcraft-openapi.yml
  format: yaml
  label: World of Warcraft Game Data API
  slug: world-of-warcraft-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/openapi/blizzard-world-of-warcraft-openapi.yml
- filename: blizzard-diablo-iii-openapi.yml
  format: yaml
  label: Diablo III Community API
  slug: diablo-iii-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/openapi/blizzard-diablo-iii-openapi.yml
- filename: blizzard-starcraft-ii-openapi.yml
  format: yaml
  label: StarCraft II Community API
  slug: starcraft-ii-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/openapi/blizzard-starcraft-ii-openapi.yml
- filename: blizzard-hearthstone-openapi.yml
  format: yaml
  label: Hearthstone Game Data API
  slug: hearthstone-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/openapi/blizzard-hearthstone-openapi.yml
- filename: blizzard-oauth-openapi.yml
  format: yaml
  label: Battle.net OAuth API
  slug: oauth-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/openapi/blizzard-oauth-openapi.yml
class_count: 38
classes:
- Realm
- ConnectedRealm
- Character
- Guild
- Auction
- AuctionList
- Achievement
- Mount
- Item
- Hero
- Act
- Artisan
- Ladder
- Card
- CardBack
- Deck
- AccessToken
- UserInfo
- id
- name
- locale
- region
- namespace
- battletag
- faction
- playableClass
- playableRace
- realm
- guild
- timeLeft
- achievementCriteria
- deckCode
- cardSet
- rarity
- accessToken
- tokenType
- scope
- sub
context_file: json-ld/blizzard-entertainment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/json-ld/blizzard-entertainment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Blizzard Entertainment from Blizzard Entertainment.
layout: jsonld
name: Blizzard Entertainment Context
namespaces:
- prefix: blizzard
  uri: https://api.blizzard.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: slug
  type: string
- container: ''
  name: level
  type: integer
- container: ''
  name: auctionId
  type: integer
- container: ''
  name: buyout
  type: integer
- container: ''
  name: bid
  type: integer
- container: ''
  name: manaCost
  type: integer
- container: ''
  name: attack
  type: integer
- container: ''
  name: health
  type: integer
- container: ''
  name: expiresIn
  type: integer
property_count: 9
provider_name: Blizzard Entertainment
provider_slug: blizzard-entertainment
slug: blizzard-entertainment-context
source_filename: blizzard-entertainment-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"blizzard\": \"https://api.blizzard.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Realm\": \"blizzard:Realm\",\n    \"ConnectedRealm\": \"blizzard:ConnectedRealm\",\n    \"Character\": \"blizzard:Character\",\n    \"Guild\": \"blizzard:Guild\",\n    \"Auction\": \"blizzard:Auction\",\n    \"AuctionList\": \"blizzard:AuctionList\",\n    \"Achievement\": \"blizzard:Achievement\",\n    \"Mount\": \"blizzard:Mount\",\n    \"Item\": \"blizzard:Item\",\n    \"Hero\": \"blizzard:Hero\",\n    \"Act\": \"blizzard:Act\",\n    \"Artisan\": \"blizzard:Artisan\",\n    \"Ladder\": \"blizzard:Ladder\",\n    \"Card\": \"blizzard:Card\",\n    \"CardBack\": \"blizzard:CardBack\",\n    \"Deck\": \"blizzard:Deck\",\n    \"AccessToken\": \"blizzard:AccessToken\",\n    \"UserInfo\": \"blizzard:UserInfo\",\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"slug\": {\n\
  \      \"@id\": \"blizzard:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": \"schema:inLanguage\",\n    \"region\": \"schema:areaServed\",\n    \"namespace\": \"blizzard:namespace\",\n    \"battletag\": \"blizzard:battletag\",\n    \"level\": {\n      \"@id\": \"blizzard:level\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"faction\": \"blizzard:faction\",\n    \"playableClass\": \"blizzard:playableClass\",\n    \"playableRace\": \"blizzard:playableRace\",\n    \"realm\": \"blizzard:realm\",\n    \"guild\": \"blizzard:guild\",\n    \"auctionId\": {\n      \"@id\": \"blizzard:auctionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"buyout\": {\n      \"@id\": \"blizzard:buyout\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bid\": {\n      \"@id\": \"blizzard:bid\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeLeft\": \"blizzard:timeLeft\",\n    \"achievementCriteria\": \"blizzard:achievementCriteria\",\n    \"deckCode\": \"blizzard:deckCode\",\n  \
  \  \"cardSet\": \"blizzard:cardSet\",\n    \"rarity\": \"blizzard:rarity\",\n    \"manaCost\": {\n      \"@id\": \"blizzard:manaCost\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attack\": {\n      \"@id\": \"blizzard:attack\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"health\": {\n      \"@id\": \"blizzard:health\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"accessToken\": \"blizzard:accessToken\",\n    \"tokenType\": \"blizzard:tokenType\",\n    \"expiresIn\": {\n      \"@id\": \"blizzard:expiresIn\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scope\": \"blizzard:scope\",\n    \"sub\": \"blizzard:sub\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/json-ld/blizzard-entertainment-context.jsonld
tags:
- Games
- Entertainment
- Video Games
- Game Data
- Battle.net
- JSON-LD
- Linked Data
- Semantic Web
---
