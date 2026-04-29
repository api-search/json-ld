---
class_count: 3
classes:
- InstagramUser
- InstagramMedia
- InstagramComment
context_file: json-ld/facebook-instagram-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-instagram-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Facebook Instagram Api from Facebook.
layout: jsonld
name: Facebook Instagram Api Context
namespaces:
- prefix: fb
  uri: https://developers.facebook.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: username
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: biography
  type: string
- container: ''
  name: followersCount
  type: integer
- container: ''
  name: mediaCount
  type: integer
- container: ''
  name: caption
  type: string
- container: ''
  name: mediaType
  type: string
- container: ''
  name: mediaUrl
  type: reference
- container: ''
  name: permalink
  type: reference
- container: ''
  name: likeCount
  type: integer
- container: ''
  name: commentsCount
  type: integer
property_count: 11
provider_name: Facebook
provider_slug: facebook
slug: facebook-instagram-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fb\": \"https://developers.facebook.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InstagramUser\": \"fb:InstagramUser\",\n    \"InstagramMedia\": \"fb:InstagramMedia\",\n    \"InstagramComment\": \"fb:InstagramComment\",\n    \"username\": { \"@id\": \"fb:username\", \"@type\": \"xsd:string\" },\n    \"name\": { \"@id\": \"schema:name\", \"@type\": \"xsd:string\" },\n    \"biography\": { \"@id\": \"fb:biography\", \"@type\": \"xsd:string\" },\n    \"followersCount\": { \"@id\": \"fb:followers_count\", \"@type\": \"xsd:integer\" },\n    \"mediaCount\": { \"@id\": \"fb:media_count\", \"@type\": \"xsd:integer\" },\n    \"caption\": { \"@id\": \"fb:caption\", \"@type\": \"xsd:string\" },\n    \"mediaType\": { \"@id\": \"fb:media_type\", \"@type\": \"xsd:string\" },\n    \"mediaUrl\": { \"@id\": \"fb:media_url\"\
  , \"@type\": \"@id\" },\n    \"permalink\": { \"@id\": \"fb:permalink\", \"@type\": \"@id\" },\n    \"likeCount\": { \"@id\": \"fb:like_count\", \"@type\": \"xsd:integer\" },\n    \"commentsCount\": { \"@id\": \"fb:comments_count\", \"@type\": \"xsd:integer\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/facebook/refs/heads/main/json-ld/facebook-instagram-api-context.jsonld
tags:
- Advertising
- Content Publishing
- Messaging
- Social Media
- Social Networking
- JSON-LD
- Linked Data
- Semantic Web
---
