---
class_count: 12
classes:
- MetadataItem
- name
- Deck
- version
- Metadata
- DeckClass
- DeckCard
- ErrorResponse
- CardBack
- CardSearchResponse
- CardBackSearchResponse
- Card
context_file: json-ld/battle-net-hearthstone-game-data-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/battle-net/refs/heads/main/json-ld/battle-net-hearthstone-game-data-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Battle Net Hearthstone Game Data from Battle.net.
layout: jsonld
name: Battle Net Hearthstone Game Data Context
namespaces:
- prefix: bnet
  uri: https://develop.battle.net/schema/
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
  name: slug
  type: string
- container: ''
  name: deckCode
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: class
  type: string
- container: set
  name: cards
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: cardCount
  type: integer
- container: set
  name: sets
  type: string
- container: set
  name: setGroups
  type: string
- container: set
  name: classes
  type: string
- container: set
  name: keywords
  type: string
- container: set
  name: types
  type: string
- container: set
  name: rarities
  type: string
- container: set
  name: minionTypes
  type: string
- container: ''
  name: code
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: sortCategory
  type: integer
- container: ''
  name: text
  type: string
- container: ''
  name: image
  type: reference
- container: ''
  name: collectible
  type: integer
- container: ''
  name: classId
  type: integer
- container: set
  name: multiClassIds
  type: string
- container: ''
  name: cardTypeId
  type: integer
- container: ''
  name: cardSetId
  type: integer
- container: ''
  name: rarityId
  type: integer
- container: ''
  name: artistName
  type: string
- container: ''
  name: health
  type: integer
- container: ''
  name: attack
  type: integer
- container: ''
  name: manaCost
  type: integer
- container: ''
  name: flavorText
  type: string
- container: ''
  name: cropImage
  type: reference
- container: set
  name: childIds
  type: string
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: page
  type: integer
- container: set
  name: cardBacks
  type: string
property_count: 37
provider_name: Battle.net
provider_slug: battle-net
slug: battle-net-hearthstone-game-data-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"bnet\": \"https://develop.battle.net/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"MetadataItem\": \"bnet:MetadataItem\",\n    \"id\": {\n      \"@id\": \"bnet:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"slug\": {\n      \"@id\": \"bnet:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Deck\": \"bnet:Deck\",\n    \"deckCode\": {\n      \"@id\": \"bnet:deckCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"format\": {\n      \"@id\": \"bnet:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"bnet:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cards\": {\n      \"@id\": \"bnet:cards\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n\
  \      \"@id\": \"bnet:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cardCount\": {\n      \"@id\": \"bnet:cardCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Metadata\": \"bnet:Metadata\",\n    \"sets\": {\n      \"@id\": \"bnet:sets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"setGroups\": {\n      \"@id\": \"bnet:setGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"classes\": {\n      \"@id\": \"bnet:classes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keywords\": {\n      \"@id\": \"bnet:keywords\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"types\": {\n      \"@id\": \"bnet:types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rarities\": {\n      \"@id\": \"bnet:rarities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minionTypes\":\
  \ {\n      \"@id\": \"bnet:minionTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeckClass\": \"bnet:DeckClass\",\n    \"DeckCard\": \"bnet:DeckCard\",\n    \"ErrorResponse\": \"bnet:ErrorResponse\",\n    \"code\": {\n      \"@id\": \"bnet:code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"bnet:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"bnet:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CardBack\": \"bnet:CardBack\",\n    \"sortCategory\": {\n      \"@id\": \"bnet:sortCategory\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"text\": {\n      \"@id\": \"bnet:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"bnet:image\",\n      \"@type\": \"@id\"\n    },\n    \"CardSearchResponse\": \"bnet:CardSearchResponse\",\n    \"collectible\": {\n      \"@id\": \"bnet:collectible\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  classId\": {\n      \"@id\": \"bnet:classId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"multiClassIds\": {\n      \"@id\": \"bnet:multiClassIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardTypeId\": {\n      \"@id\": \"bnet:cardTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cardSetId\": {\n      \"@id\": \"bnet:cardSetId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rarityId\": {\n      \"@id\": \"bnet:rarityId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"artistName\": {\n      \"@id\": \"bnet:artistName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"bnet:health\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attack\": {\n      \"@id\": \"bnet:attack\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"manaCost\": {\n      \"@id\": \"bnet:manaCost\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flavorText\": {\n      \"@id\": \"bnet:flavorText\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"cropImage\": {\n      \"@id\": \"bnet:cropImage\",\n      \"@type\": \"@id\"\n    },\n    \"childIds\": {\n      \"@id\": \"bnet:childIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pageCount\": {\n      \"@id\": \"bnet:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"bnet:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CardBackSearchResponse\": \"bnet:CardBackSearchResponse\",\n    \"cardBacks\": {\n      \"@id\": \"bnet:cardBacks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Card\": \"bnet:Card\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/battle-net/refs/heads/main/json-ld/battle-net-hearthstone-game-data-context.jsonld
tags:
- Games
- Gaming
- Blizzard
- World Of Warcraft
- Diablo
- Hearthstone
- Starcraft
- JSON-LD
- Linked Data
- Semantic Web
---
