---
api_specs:
- filename: taddy-podcast-openapi.yml
  format: yaml
  label: Taddy Podcast API
  slug: taddy-podcast-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/openapi/taddy-podcast-openapi.yml
class_count: 4
classes:
- PodcastSeries
- PodcastEpisode
- Person
- Genre
context_file: json-ld/taddy-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-ld/taddy-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Taddy Api from Taddy API.
layout: jsonld
name: Taddy Api Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: taddy
  uri: https://taddy.org/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: uuid
  type: string
- container: ''
  name: guid
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: imageUrl
  type: reference
- container: ''
  name: websiteUrl
  type: reference
- container: ''
  name: rssUrl
  type: reference
- container: ''
  name: audioUrl
  type: reference
- container: ''
  name: videoUrl
  type: reference
- container: ''
  name: datePublished
  type: integer
- container: ''
  name: duration
  type: integer
- container: ''
  name: episodeNumber
  type: integer
- container: ''
  name: seasonNumber
  type: integer
- container: ''
  name: totalEpisodesCount
  type: integer
- container: ''
  name: itunesId
  type: integer
- container: ''
  name: isExplicitContent
  type: boolean
- container: ''
  name: isCompleted
  type: boolean
- container: ''
  name: isBlocked
  type: boolean
- container: ''
  name: isRemoved
  type: boolean
- container: ''
  name: copyright
  type: ''
- container: ''
  name: authorName
  type: ''
- container: ''
  name: rssOwnerName
  type: ''
- container: ''
  name: rssOwnerPublicEmail
  type: ''
- container: ''
  name: seriesType
  type: ''
- container: ''
  name: contentType
  type: ''
- container: ''
  name: episodeType
  type: ''
- container: ''
  name: language
  type: ''
- container: set
  name: genres
  type: ''
- container: set
  name: persons
  type: ''
- container: set
  name: episodes
  type: ''
- container: ''
  name: popularityRank
  type: ''
- container: ''
  name: rank
  type: integer
- container: list
  name: transcript
  type: ''
- container: set
  name: transcriptUrls
  type: ''
- container: ''
  name: taddyTranscribeStatus
  type: ''
- container: list
  name: chapters
  type: ''
- container: ''
  name: role
  type: ''
- container: ''
  name: startTime
  type: decimal
- container: ''
  name: endTime
  type: decimal
- container: ''
  name: hash
  type: ''
- container: ''
  name: childrenHash
  type: ''
property_count: 41
provider_name: Taddy API
provider_slug: taddy-api
slug: taddy-api-context
source_filename: taddy-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"taddy\": \"https://taddy.org/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"PodcastSeries\": \"schema:PodcastSeries\",\n    \"PodcastEpisode\": \"schema:PodcastEpisode\",\n    \"Person\": \"schema:Person\",\n    \"Genre\": \"schema:Genre\",\n\n    \"uuid\": { \"@id\": \"taddy:uuid\", \"@type\": \"xsd:string\" },\n    \"guid\": { \"@id\": \"taddy:guid\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\" },\n    \"description\": { \"@id\": \"schema:description\" },\n    \"imageUrl\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"websiteUrl\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"rssUrl\": { \"@id\": \"schema:webFeed\", \"@type\": \"@id\" },\n    \"audioUrl\": { \"@id\": \"schema:contentUrl\", \"@type\": \"@id\" },\n    \"videoUrl\": { \"@id\": \"schema:contentUrl\", \"@type\": \"@id\" },\n    \"datePublished\"\
  : { \"@id\": \"schema:datePublished\", \"@type\": \"xsd:integer\" },\n    \"duration\": { \"@id\": \"schema:duration\", \"@type\": \"xsd:integer\" },\n    \"episodeNumber\": { \"@id\": \"schema:episodeNumber\", \"@type\": \"xsd:integer\" },\n    \"seasonNumber\": { \"@id\": \"schema:seasonNumber\", \"@type\": \"xsd:integer\" },\n    \"totalEpisodesCount\": { \"@id\": \"taddy:totalEpisodesCount\", \"@type\": \"xsd:integer\" },\n    \"itunesId\": { \"@id\": \"taddy:itunesId\", \"@type\": \"xsd:integer\" },\n    \"isExplicitContent\": { \"@id\": \"taddy:isExplicitContent\", \"@type\": \"xsd:boolean\" },\n    \"isCompleted\": { \"@id\": \"taddy:isCompleted\", \"@type\": \"xsd:boolean\" },\n    \"isBlocked\": { \"@id\": \"taddy:isBlocked\", \"@type\": \"xsd:boolean\" },\n    \"isRemoved\": { \"@id\": \"taddy:isRemoved\", \"@type\": \"xsd:boolean\" },\n    \"copyright\": { \"@id\": \"schema:copyrightNotice\" },\n    \"authorName\": { \"@id\": \"schema:author\" },\n    \"rssOwnerName\": { \"\
  @id\": \"taddy:rssOwnerName\" },\n    \"rssOwnerPublicEmail\": { \"@id\": \"taddy:rssOwnerPublicEmail\" },\n    \"seriesType\": { \"@id\": \"taddy:seriesType\" },\n    \"contentType\": { \"@id\": \"taddy:contentType\" },\n    \"episodeType\": { \"@id\": \"taddy:episodeType\" },\n    \"language\": { \"@id\": \"schema:inLanguage\" },\n    \"genres\": { \"@id\": \"schema:genre\", \"@container\": \"@set\" },\n    \"persons\": { \"@id\": \"schema:actor\", \"@container\": \"@set\" },\n    \"episodes\": { \"@id\": \"schema:episode\", \"@container\": \"@set\" },\n    \"popularityRank\": { \"@id\": \"taddy:popularityRank\" },\n    \"rank\": { \"@id\": \"schema:position\", \"@type\": \"xsd:integer\" },\n    \"transcript\": { \"@id\": \"taddy:transcript\", \"@container\": \"@list\" },\n    \"transcriptUrls\": { \"@id\": \"taddy:transcriptUrls\", \"@container\": \"@set\" },\n    \"taddyTranscribeStatus\": { \"@id\": \"taddy:transcribeStatus\" },\n    \"chapters\": { \"@id\": \"taddy:chapters\", \"\
  @container\": \"@list\" },\n    \"role\": { \"@id\": \"schema:roleName\" },\n    \"startTime\": { \"@id\": \"schema:startOffset\", \"@type\": \"xsd:decimal\" },\n    \"endTime\": { \"@id\": \"schema:endOffset\", \"@type\": \"xsd:decimal\" },\n    \"hash\": { \"@id\": \"taddy:hash\" },\n    \"childrenHash\": { \"@id\": \"taddy:childrenHash\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-ld/taddy-api-context.jsonld
tags:
- Audio
- Comics
- GraphQL
- Media
- Podcasts
- Transcripts
- Webhooks
- JSON-LD
- Linked Data
- Semantic Web
---
