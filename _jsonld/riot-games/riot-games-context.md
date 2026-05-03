---
api_specs:
- filename: riot-games-league-of-legends-openapi.yml
  format: yaml
  label: League of Legends API
  slug: league-of-legends-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/openapi/riot-games-league-of-legends-openapi.yml
class_count: 48
classes:
- Summoner
- Match
- LeagueEntry
- ChampionMastery
- Champion
- LiveGame
- puuid
- summonerId
- summonerName
- summonerLevel
- profileIconId
- accountId
- matchId
- gameMode
- gameType
- gameDuration
- queueId
- mapId
- platformId
- gameVersion
- participants
- tier
- rank
- leaguePoints
- queueType
- wins
- losses
- hotStreak
- veteran
- championId
- championName
- championLevel
- championPoints
- kills
- deaths
- assists
- goldEarned
- totalDamageDealt
- win
- teamId
- teamPosition
- gameName
- tagLine
- name
- description
- url
- identifier
- dateCreated
context_file: json-ld/riot-games-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-ld/riot-games-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Riot Games from Riot Games.
layout: jsonld
name: Riot Games Context
namespaces:
- prefix: riot
  uri: https://developer.riotgames.com/vocab#
- prefix: lol
  uri: https://developer.riotgames.com/vocab/lol#
properties: []
property_count: 0
provider_name: Riot Games
provider_slug: riot-games
slug: riot-games-context
source_filename: riot-games-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"riot\": \"https://developer.riotgames.com/vocab#\",\n    \"lol\": \"https://developer.riotgames.com/vocab/lol#\",\n\n    \"Summoner\": \"riot:Summoner\",\n    \"Match\": \"riot:Match\",\n    \"LeagueEntry\": \"riot:LeagueEntry\",\n    \"ChampionMastery\": \"riot:ChampionMastery\",\n    \"Champion\": \"riot:Champion\",\n    \"LiveGame\": \"riot:LiveGame\",\n\n    \"puuid\": \"riot:puuid\",\n    \"summonerId\": \"riot:summonerId\",\n    \"summonerName\": \"riot:summonerName\",\n    \"summonerLevel\": \"riot:summonerLevel\",\n    \"profileIconId\": \"riot:profileIconId\",\n    \"accountId\": \"riot:accountId\",\n\n    \"matchId\": \"riot:matchId\",\n    \"gameMode\": \"riot:gameMode\",\n    \"gameType\": \"riot:gameType\",\n    \"gameDuration\": \"riot:gameDuration\",\n    \"queueId\": \"riot:queueId\",\n    \"mapId\": \"riot:mapId\",\n    \"platformId\": \"riot:platformId\",\n    \"gameVersion\": \"riot:gameVersion\"\
  ,\n    \"participants\": \"riot:participants\",\n\n    \"tier\": \"riot:tier\",\n    \"rank\": \"riot:rank\",\n    \"leaguePoints\": \"riot:leaguePoints\",\n    \"queueType\": \"riot:queueType\",\n    \"wins\": \"riot:wins\",\n    \"losses\": \"riot:losses\",\n    \"hotStreak\": \"riot:hotStreak\",\n    \"veteran\": \"riot:veteran\",\n\n    \"championId\": \"riot:championId\",\n    \"championName\": \"riot:championName\",\n    \"championLevel\": \"riot:championLevel\",\n    \"championPoints\": \"riot:championPoints\",\n\n    \"kills\": \"riot:kills\",\n    \"deaths\": \"riot:deaths\",\n    \"assists\": \"riot:assists\",\n    \"goldEarned\": \"riot:goldEarned\",\n    \"totalDamageDealt\": \"riot:totalDamageDealt\",\n    \"win\": \"riot:win\",\n    \"teamId\": \"riot:teamId\",\n    \"teamPosition\": \"riot:teamPosition\",\n\n    \"gameName\": \"riot:gameName\",\n    \"tagLine\": \"riot:tagLine\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\"\
  : \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/riot-games/refs/heads/main/json-ld/riot-games-context.jsonld
tags:
- Esports
- Gaming
- League of Legends
- Legends of Runeterra
- Teamfight Tactics
- VALORANT
- JSON-LD
- Linked Data
- Semantic Web
---
