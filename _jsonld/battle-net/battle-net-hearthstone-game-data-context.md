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
