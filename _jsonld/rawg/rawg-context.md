---
api_specs:
- filename: rawg-openapi.yml
  format: yaml
  label: RAWG Video Games Database API
  slug: rawg
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/openapi/rawg-openapi.yml
class_count: 39
classes:
- id
- slug
- name
- description
- rating
- ratings_count
- metacritic
- playtime
- esrb_rating
- alternative_names
- screenshots_count
- movies_count
- achievements_count
- additions_count
- game_series_count
- Game
- Platform
- Developer
- Publisher
- Genre
- Tag
- Store
- Person
- Position
- EsrbRating
- tba
- games_count
- year_start
- year_end
- domain
- language
- reviews_count
- suggestions_count
- added
- added_by_status
- reactions
- reddit_count
- twitch_count
- youtube_count
context_file: json-ld/rawg-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-ld/rawg-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Rawg from RAWG.
layout: jsonld
name: Rawg Context
namespaces:
- prefix: rawg
  uri: https://rawg.io/ontology/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: released
  type: date
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: website
  type: reference
- container: ''
  name: background_image
  type: reference
- container: ''
  name: metacritic_url
  type: reference
- container: set
  name: platforms
  type: ''
- container: set
  name: genres
  type: ''
- container: set
  name: tags
  type: ''
- container: set
  name: developers
  type: ''
- container: set
  name: publishers
  type: ''
- container: ''
  name: reddit_url
  type: reference
- container: ''
  name: image_background
  type: reference
property_count: 12
provider_name: RAWG
provider_slug: rawg
slug: rawg-context
source_filename: rawg-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"rawg\": \"https://rawg.io/ontology/\",\n    \"id\": \"@id\",\n    \"slug\": \"rawg:slug\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"released\": {\n      \"@id\": \"datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"updated\": {\n      \"@id\": \"dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"website\": {\n      \"@id\": \"url\",\n      \"@type\": \"@id\"\n    },\n    \"background_image\": {\n      \"@id\": \"image\",\n      \"@type\": \"@id\"\n    },\n    \"rating\": \"aggregateRating\",\n    \"ratings_count\": \"ratingCount\",\n    \"metacritic\": \"rawg:metacriticScore\",\n    \"metacritic_url\": {\n      \"@id\": \"rawg:metacriticUrl\",\n      \"@type\": \"@id\"\n    },\n    \"playtime\": \"rawg:averagePlaytime\",\n    \"esrb_rating\": \"contentRating\",\n    \"platforms\": {\n      \"@id\": \"gamePlatform\",\n      \"@container\": \"@set\"\n\
  \    },\n    \"genres\": {\n      \"@id\": \"genre\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"keywords\",\n      \"@container\": \"@set\"\n    },\n    \"developers\": {\n      \"@id\": \"creator\",\n      \"@container\": \"@set\"\n    },\n    \"publishers\": {\n      \"@id\": \"publisher\",\n      \"@container\": \"@set\"\n    },\n    \"alternative_names\": \"alternateName\",\n    \"screenshots_count\": \"rawg:screenshotsCount\",\n    \"movies_count\": \"rawg:trailersCount\",\n    \"achievements_count\": \"rawg:achievementsCount\",\n    \"additions_count\": \"rawg:additionsCount\",\n    \"game_series_count\": \"rawg:gameSeriesCount\",\n    \"reddit_url\": {\n      \"@id\": \"rawg:subredditUrl\",\n      \"@type\": \"@id\"\n    },\n    \"Game\": \"VideoGame\",\n    \"Platform\": \"GameServer\",\n    \"Developer\": \"Organization\",\n    \"Publisher\": \"Organization\",\n    \"Genre\": \"rawg:Genre\",\n    \"Tag\": \"rawg:Tag\",\n    \"Store\": \"rawg:Storefront\"\
  ,\n    \"Person\": \"Person\",\n    \"Position\": \"JobTitle\",\n    \"EsrbRating\": \"rawg:EsrbRating\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"tba\": \"rawg:toBeAnnounced\",\n    \"games_count\": \"rawg:gamesCount\",\n    \"image_background\": {\n      \"@id\": \"rawg:backgroundImage\",\n      \"@type\": \"@id\"\n    },\n    \"year_start\": \"rawg:yearStart\",\n    \"year_end\": \"rawg:yearEnd\",\n    \"domain\": \"domainName\",\n    \"language\": \"inLanguage\",\n    \"reviews_count\": \"reviewCount\",\n    \"suggestions_count\": \"rawg:suggestionsCount\",\n    \"added\": \"rawg:addedToCollectionCount\",\n    \"added_by_status\": \"rawg:addedByStatus\",\n    \"reactions\": \"rawg:reactions\",\n    \"reddit_count\": \"rawg:redditPostCount\",\n    \"twitch_count\": \"rawg:twitchStreamCount\",\n    \"youtube_count\": \"rawg:youtubeVideoCount\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/rawg/refs/heads/main/json-ld/rawg-context.jsonld
tags:
- Database
- Entertainment
- Game Discovery
- Games
- Gaming
- Metadata
- Video Games
- JSON-LD
- Linked Data
- Semantic Web
---
