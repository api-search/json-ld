---
api_specs:
- filename: openapi.json
  format: json
  label: KonbiniAPI Main Spec
  slug: main
  spec_type: OpenAPI
  url: https://docs.konbiniapi.com/openapi.json
class_count: 25
classes:
- Person
- Note
- Article
- Image
- Video
- Audio
- Link
- Tag
- Place
- Collection
- OrderedCollection
- id
- type
- name
- preferredUsername
- summary
- attachment
- tag
- location
- content
- mediaType
- rel
- entityId
- platform
- data
context_file: json-ld/konbiniapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/konbiniapi/refs/heads/main/json-ld/konbiniapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Konbiniapi from KonbiniAPI.
layout: jsonld
name: Konbiniapi Context
namespaces:
- prefix: as
  uri: https://www.w3.org/ns/activitystreams#
- prefix: konbini
  uri: https://konbiniapi.com/ns/social#
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: icon
  type: reference
- container: ''
  name: image
  type: reference
- container: ''
  name: published
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: attributedTo
  type: reference
- container: ''
  name: inReplyTo
  type: reference
- container: ''
  name: duration
  type: duration
- container: ''
  name: href
  type: reference
- container: ''
  name: isVerified
  type: boolean
- container: ''
  name: isPrivate
  type: boolean
- container: ''
  name: isLive
  type: boolean
- container: ''
  name: followerCount
  type: integer
- container: ''
  name: followingCount
  type: integer
- container: ''
  name: likeCount
  type: integer
- container: ''
  name: commentCount
  type: integer
- container: ''
  name: shareCount
  type: integer
- container: ''
  name: viewCount
  type: integer
- container: ''
  name: playCount
  type: integer
- container: ''
  name: videoCount
  type: integer
- container: ''
  name: creditsUsed
  type: integer
- container: ''
  name: creditsRemaining
  type: integer
- container: ''
  name: next
  type: reference
- container: ''
  name: previous
  type: reference
property_count: 24
provider_name: KonbiniAPI
provider_slug: konbiniapi
slug: konbiniapi-context
source_filename: konbiniapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"as\": \"https://www.w3.org/ns/activitystreams#\",\n    \"konbini\": \"https://konbiniapi.com/ns/social#\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Person\": \"as:Person\",\n    \"Note\": \"as:Note\",\n    \"Article\": \"as:Article\",\n    \"Image\": \"as:Image\",\n    \"Video\": \"as:Video\",\n    \"Audio\": \"as:Audio\",\n    \"Link\": \"as:Link\",\n    \"Tag\": \"as:Tag\",\n    \"Place\": \"as:Place\",\n    \"Collection\": \"as:Collection\",\n    \"OrderedCollection\": \"as:OrderedCollection\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"url\": { \"@id\": \"as:url\", \"@type\": \"@id\" },\n    \"name\": \"as:name\",\n    \"preferredUsername\": \"as:preferredUsername\",\n    \"summary\": \"as:summary\",\n    \"icon\": { \"@id\": \"as:icon\", \"@type\": \"@id\" },\n    \"image\": { \"@id\": \"as:image\", \"@type\": \"@id\" },\n    \"published\": {\
  \ \"@id\": \"as:published\", \"@type\": \"xsd:dateTime\" },\n    \"updated\": { \"@id\": \"as:updated\", \"@type\": \"xsd:dateTime\" },\n    \"attributedTo\": { \"@id\": \"as:attributedTo\", \"@type\": \"@id\" },\n    \"inReplyTo\": { \"@id\": \"as:inReplyTo\", \"@type\": \"@id\" },\n    \"attachment\": \"as:attachment\",\n    \"tag\": \"as:tag\",\n    \"location\": \"as:location\",\n    \"content\": \"as:content\",\n    \"mediaType\": \"as:mediaType\",\n    \"duration\": { \"@id\": \"as:duration\", \"@type\": \"xsd:duration\" },\n    \"href\": { \"@id\": \"as:href\", \"@type\": \"@id\" },\n    \"rel\": \"as:rel\",\n\n    \"entityId\": \"konbini:entityId\",\n    \"platform\": \"konbini:platform\",\n    \"isVerified\": { \"@id\": \"konbini:isVerified\", \"@type\": \"xsd:boolean\" },\n    \"isPrivate\": { \"@id\": \"konbini:isPrivate\", \"@type\": \"xsd:boolean\" },\n    \"isLive\": { \"@id\": \"konbini:isLive\", \"@type\": \"xsd:boolean\" },\n    \"followerCount\": { \"@id\": \"konbini:followerCount\"\
  , \"@type\": \"xsd:integer\" },\n    \"followingCount\": { \"@id\": \"konbini:followingCount\", \"@type\": \"xsd:integer\" },\n    \"likeCount\": { \"@id\": \"konbini:likeCount\", \"@type\": \"xsd:integer\" },\n    \"commentCount\": { \"@id\": \"konbini:commentCount\", \"@type\": \"xsd:integer\" },\n    \"shareCount\": { \"@id\": \"konbini:shareCount\", \"@type\": \"xsd:integer\" },\n    \"viewCount\": { \"@id\": \"konbini:viewCount\", \"@type\": \"xsd:integer\" },\n    \"playCount\": { \"@id\": \"konbini:playCount\", \"@type\": \"xsd:integer\" },\n    \"videoCount\": { \"@id\": \"konbini:videoCount\", \"@type\": \"xsd:integer\" },\n\n    \"creditsUsed\": { \"@id\": \"konbini:creditsUsed\", \"@type\": \"xsd:integer\" },\n    \"creditsRemaining\": { \"@id\": \"konbini:creditsRemaining\", \"@type\": \"xsd:integer\" },\n\n    \"data\": \"konbini:data\",\n    \"next\": { \"@id\": \"konbini:nextCursor\", \"@type\": \"@id\" },\n    \"previous\": { \"@id\": \"konbini:previousCursor\", \"@type\"\
  : \"@id\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/konbiniapi/refs/heads/main/json-ld/konbiniapi-context.jsonld
tags:
- API
- Social Media
- Instagram
- TikTok
- ActivityStreams 2.0
- Scraping
- Data Extraction
- Public Data
- Influencer Marketing
- Social Listening
- Creator Tools
- MCP
- Model Context Protocol
- JSON-LD
- Linked Data
- Semantic Web
---
