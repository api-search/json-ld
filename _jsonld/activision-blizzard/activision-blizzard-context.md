---
api_specs:
- filename: activision-blizzard-battle-net.json
  format: json
  label: Battle.net API
  slug: battle-net
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/openapi/activision-blizzard-battle-net.json
class_count: 17
classes:
- WoWItem
- HearthstoneDeck
- WoWCharacter
- D3HeroSummary
- WoWCharacterSummary
- WoWRealmsIndex
- BattleNetProfile
- WoWProfileSummary
- WoWAccount
- D3CareerProfile
- WoWGuild
- WoWCharacterAchievements
- WoWRealm
- HearthstoneCardsResponse
- SC2Profile
- D3Hero
- HearthstoneCard
context_file: json-ld/activision-blizzard-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/json-ld/activision-blizzard-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Activision Blizzard from activision-blizzard.
layout: jsonld
name: Activision Blizzard Context
namespaces:
- prefix: blizzard
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
  name: name
  type: string
- container: ''
  name: quality
  type: string
- container: ''
  name: level
  type: integer
- container: ''
  name: itemClass
  type: string
- container: ''
  name: itemSubclass
  type: string
- container: ''
  name: inventoryType
  type: string
- container: ''
  name: purchasePrice
  type: integer
- container: ''
  name: sellPrice
  type: integer
- container: ''
  name: deckCode
  type: string
- container: ''
  name: version
  type: integer
- container: ''
  name: format
  type: string
- container: ''
  name: hero
  type: string
- container: ''
  name: heroPower
  type: string
- container: ''
  name: class
  type: string
- container: set
  name: cards
  type: string
- container: ''
  name: cardCount
  type: integer
- container: ''
  name: gender
  type: string
- container: ''
  name: faction
  type: string
- container: ''
  name: race
  type: string
- container: ''
  name: characterClass
  type: string
- container: ''
  name: activeSpec
  type: string
- container: ''
  name: realm
  type: string
- container: ''
  name: guild
  type: string
- container: ''
  name: experience
  type: integer
- container: ''
  name: achievementPoints
  type: integer
- container: ''
  name: lastLoginTimestamp
  type: integer
- container: ''
  name: hardcore
  type: boolean
- container: ''
  name: seasonal
  type: boolean
- container: ''
  name: dead
  type: boolean
- container: ''
  name: character
  type: string
- container: ''
  name: protectedCharacter
  type: string
- container: ''
  name: playableClass
  type: string
- container: ''
  name: playableRace
  type: string
- container: set
  name: realms
  type: string
- container: ''
  name: battletag
  type: string
- container: ''
  name: sub
  type: string
- container: set
  name: wowAccounts
  type: string
- container: set
  name: characters
  type: string
- container: ''
  name: paragonLevel
  type: integer
- container: ''
  name: paragonLevelHardcore
  type: integer
- container: ''
  name: guildName
  type: string
- container: set
  name: heroes
  type: string
- container: ''
  name: lastHeroPlayed
  type: integer
- container: ''
  name: kills
  type: string
- container: ''
  name: timePlayed
  type: string
- container: ''
  name: memberCount
  type: integer
- container: ''
  name: totalQuantity
  type: integer
- container: ''
  name: totalPoints
  type: integer
- container: set
  name: achievements
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: locale
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: isTournament
  type: boolean
- container: ''
  name: pageCount
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: summary
  type: string
- container: ''
  name: snapshot
  type: string
- container: ''
  name: skills
  type: string
- container: ''
  name: items
  type: string
- container: ''
  name: stats
  type: string
- container: ''
  name: collectible
  type: integer
- container: ''
  name: classId
  type: integer
- container: set
  name: multiClassIds
  type: integer
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
  name: text
  type: string
- container: ''
  name: image
  type: reference
- container: ''
  name: imageGold
  type: reference
- container: ''
  name: flavorText
  type: string
- container: ''
  name: cropImage
  type: reference
property_count: 79
provider_name: activision-blizzard
provider_slug: activision-blizzard
slug: activision-blizzard-context
source_filename: activision-blizzard-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"blizzard\": \"https://develop.battle.net/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"WoWItem\": \"blizzard:WoWItem\",\n    \"HearthstoneDeck\": \"blizzard:HearthstoneDeck\",\n    \"WoWCharacter\": \"blizzard:WoWCharacter\",\n    \"D3HeroSummary\": \"blizzard:D3HeroSummary\",\n    \"WoWCharacterSummary\": \"blizzard:WoWCharacterSummary\",\n    \"WoWRealmsIndex\": \"blizzard:WoWRealmsIndex\",\n    \"BattleNetProfile\": \"blizzard:BattleNetProfile\",\n    \"WoWProfileSummary\": \"blizzard:WoWProfileSummary\",\n    \"WoWAccount\": \"blizzard:WoWAccount\",\n    \"D3CareerProfile\": \"blizzard:D3CareerProfile\",\n    \"WoWGuild\": \"blizzard:WoWGuild\",\n    \"WoWCharacterAchievements\": \"blizzard:WoWCharacterAchievements\",\n    \"WoWRealm\": \"blizzard:WoWRealm\",\n    \"HearthstoneCardsResponse\": \"blizzard:HearthstoneCardsResponse\"\
  ,\n    \"SC2Profile\": \"blizzard:SC2Profile\",\n    \"D3Hero\": \"blizzard:D3Hero\",\n    \"HearthstoneCard\": \"blizzard:HearthstoneCard\",\n    \"id\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality\": {\n      \"@id\": \"blizzard:quality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"blizzard:level\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"itemClass\": {\n      \"@id\": \"blizzard:item_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemSubclass\": {\n      \"@id\": \"blizzard:item_subclass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inventoryType\": {\n      \"@id\": \"blizzard:inventory_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"purchasePrice\": {\n      \"@id\": \"blizzard:purchase_price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sellPrice\": {\n      \"@id\"\
  : \"blizzard:sell_price\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deckCode\": {\n      \"@id\": \"blizzard:deckCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"blizzard:version\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"format\": {\n      \"@id\": \"blizzard:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hero\": {\n      \"@id\": \"blizzard:hero\",\n      \"@type\": \"xsd:string\"\n    },\n    \"heroPower\": {\n      \"@id\": \"blizzard:heroPower\",\n      \"@type\": \"xsd:string\"\n    },\n    \"class\": {\n      \"@id\": \"blizzard:class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cards\": {\n      \"@id\": \"blizzard:cards\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cardCount\": {\n      \"@id\": \"blizzard:cardCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"gender\": {\n      \"@id\": \"blizzard:gender\",\n      \"@type\": \"xsd:string\"\n    },\n    \"faction\"\
  : {\n      \"@id\": \"blizzard:faction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"race\": {\n      \"@id\": \"blizzard:race\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characterClass\": {\n      \"@id\": \"blizzard:character_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeSpec\": {\n      \"@id\": \"blizzard:active_spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realm\": {\n      \"@id\": \"blizzard:realm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"guild\": {\n      \"@id\": \"blizzard:guild\",\n      \"@type\": \"xsd:string\"\n    },\n    \"experience\": {\n      \"@id\": \"blizzard:experience\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"achievementPoints\": {\n      \"@id\": \"blizzard:achievement_points\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastLoginTimestamp\": {\n      \"@id\": \"blizzard:last_login_timestamp\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hardcore\": {\n      \"@id\": \"blizzard:hardcore\",\n \
  \     \"@type\": \"xsd:boolean\"\n    },\n    \"seasonal\": {\n      \"@id\": \"blizzard:seasonal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"dead\": {\n      \"@id\": \"blizzard:dead\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"character\": {\n      \"@id\": \"blizzard:character\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protectedCharacter\": {\n      \"@id\": \"blizzard:protected_character\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playableClass\": {\n      \"@id\": \"blizzard:playable_class\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playableRace\": {\n      \"@id\": \"blizzard:playable_race\",\n      \"@type\": \"xsd:string\"\n    },\n    \"realms\": {\n      \"@id\": \"blizzard:realms\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"battletag\": {\n      \"@id\": \"blizzard:battletag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sub\": {\n      \"@id\": \"blizzard:sub\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"wowAccounts\": {\n      \"@id\": \"blizzard:wow_accounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"characters\": {\n      \"@id\": \"blizzard:characters\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paragonLevel\": {\n      \"@id\": \"blizzard:paragonLevel\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"paragonLevelHardcore\": {\n      \"@id\": \"blizzard:paragonLevelHardcore\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"guildName\": {\n      \"@id\": \"blizzard:guildName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"heroes\": {\n      \"@id\": \"blizzard:heroes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastHeroPlayed\": {\n      \"@id\": \"blizzard:lastHeroPlayed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"kills\": {\n      \"@id\": \"blizzard:kills\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timePlayed\": {\n      \"@id\"\
  : \"blizzard:timePlayed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memberCount\": {\n      \"@id\": \"blizzard:member_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalQuantity\": {\n      \"@id\": \"blizzard:total_quantity\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalPoints\": {\n      \"@id\": \"blizzard:total_points\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"achievements\": {\n      \"@id\": \"blizzard:achievements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"blizzard:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"blizzard:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"blizzard:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": {\n      \"@id\": \"blizzard:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"blizzard:timezone\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"blizzard:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isTournament\": {\n      \"@id\": \"blizzard:is_tournament\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"pageCount\": {\n      \"@id\": \"blizzard:pageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"blizzard:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"summary\": {\n      \"@id\": \"blizzard:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshot\": {\n      \"@id\": \"blizzard:snapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"skills\": {\n      \"@id\": \"blizzard:skills\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"blizzard:items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stats\": {\n      \"@id\": \"blizzard:stats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectible\": {\n      \"@id\": \"blizzard:collectible\",\n      \"@type\": \"\
  xsd:integer\"\n    },\n    \"classId\": {\n      \"@id\": \"blizzard:classId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"multiClassIds\": {\n      \"@id\": \"blizzard:multiClassIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cardTypeId\": {\n      \"@id\": \"blizzard:cardTypeId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cardSetId\": {\n      \"@id\": \"blizzard:cardSetId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rarityId\": {\n      \"@id\": \"blizzard:rarityId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"artistName\": {\n      \"@id\": \"blizzard:artistName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"blizzard:health\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attack\": {\n      \"@id\": \"blizzard:attack\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"manaCost\": {\n      \"@id\": \"blizzard:manaCost\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"text\": {\n\
  \      \"@id\": \"blizzard:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"blizzard:image\",\n      \"@type\": \"@id\"\n    },\n    \"imageGold\": {\n      \"@id\": \"blizzard:imageGold\",\n      \"@type\": \"@id\"\n    },\n    \"flavorText\": {\n      \"@id\": \"blizzard:flavorText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cropImage\": {\n      \"@id\": \"blizzard:cropImage\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/activision-blizzard/refs/heads/main/json-ld/activision-blizzard-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
