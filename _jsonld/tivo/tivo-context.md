---
api_specs:
- filename: tivo-video-metadata-openapi.yml
  format: yaml
  label: TiVo Video Metadata API
  slug: tivo-video-metadata
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/openapi/tivo-video-metadata-openapi.yml
class_count: 37
classes:
- Movie
- TVSeries
- TVEpisode
- TVSeason
- Person
- MusicGroup
- ContentItem
- Image
- id
- title
- description
- genres
- rating
- languages
- cast
- personId
- name
- role
- character
- images
- url
- imageType
- width
- height
- language
- externalIds
- rovi
- rovi2
- tmdb
- eidr
- availableOn
- seasonNumber
- episodeNumber
- episodeCount
- biography
- birthPlace
- credits
context_file: json-ld/tivo-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-ld/tivo-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tivo from Tivo.
layout: jsonld
name: Tivo Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tivo
  uri: https://business.tivo.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: year
  type: gYear
- container: ''
  name: runtime
  type: integer
- container: ''
  name: airDate
  type: date
- container: ''
  name: birthDate
  type: date
property_count: 4
provider_name: Tivo
provider_slug: tivo
slug: tivo-context
source_filename: tivo-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tivo\": \"https://business.tivo.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Movie\": \"schema:Movie\",\n    \"TVSeries\": \"schema:TVSeries\",\n    \"TVEpisode\": \"schema:TVEpisode\",\n    \"TVSeason\": \"schema:TVSeason\",\n    \"Person\": \"schema:Person\",\n    \"MusicGroup\": \"schema:MusicGroup\",\n    \"ContentItem\": \"tivo:ContentItem\",\n    \"Image\": \"schema:ImageObject\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"year\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"genres\": \"schema:genre\",\n    \"rating\": \"schema:contentRating\",\n    \"runtime\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"languages\": \"schema:availableLanguage\",\n\n    \"cast\": \"schema:actor\",\n    \"personId\"\
  : \"@id\",\n    \"name\": \"schema:name\",\n    \"role\": \"schema:roleName\",\n    \"character\": \"schema:characterName\",\n\n    \"images\": \"schema:image\",\n    \"url\": \"schema:url\",\n    \"imageType\": \"schema:additionalType\",\n    \"width\": \"schema:width\",\n    \"height\": \"schema:height\",\n    \"language\": \"schema:inLanguage\",\n\n    \"externalIds\": \"schema:identifier\",\n    \"rovi\": \"tivo:roviId\",\n    \"rovi2\": \"tivo:roviId2\",\n    \"tmdb\": \"tivo:tmdbId\",\n    \"eidr\": \"tivo:eidrId\",\n\n    \"availableOn\": \"schema:availableOn\",\n\n    \"seasonNumber\": \"schema:seasonNumber\",\n    \"episodeNumber\": \"schema:episodeNumber\",\n    \"airDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"episodeCount\": \"schema:numberOfEpisodes\",\n\n    \"biography\": \"schema:description\",\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"birthPlace\": \"schema:birthPlace\"\
  ,\n    \"credits\": \"schema:performerIn\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tivo/refs/heads/main/json-ld/tivo-context.jsonld
tags:
- Entertainment
- Metadata
- Television
- Movies
- Music
- Streaming
- JSON-LD
- Linked Data
- Semantic Web
---
