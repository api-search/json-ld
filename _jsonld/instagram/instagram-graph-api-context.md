---
class_count: 11
classes:
- Comment
- CommentList
- ContainerResponse
- CreateContainerRequest
- ErrorResponse
- InsightsResponse
- Media
- MediaList
- Paging
- SuccessResponse
- User
context_file: json-ld/instagram-graph-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/json-ld/instagram-graph-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Instagram Graph Api from Instagram.
layout: jsonld
name: Instagram Graph Api Context
namespaces:
- prefix: ig
  uri: https://developers.facebook.com/docs/instagram-api/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: access_token
  type: string
- container: ''
  name: alt_text
  type: string
- container: ''
  name: biography
  type: string
- container: ''
  name: caption
  type: string
- container: ''
  name: comments_count
  type: integer
- container: ''
  name: cursors
  type: reference
- container: set
  name: data
  type: string
- container: ''
  name: error
  type: reference
- container: ''
  name: followers_count
  type: integer
- container: ''
  name: follows_count
  type: integer
- container: ''
  name: hidden
  type: boolean
- container: ''
  name: id
  type: string
- container: ''
  name: image_url
  type: string
- container: ''
  name: is_carousel_item
  type: boolean
- container: ''
  name: is_comment_enabled
  type: boolean
- container: ''
  name: is_shared_to_feed
  type: boolean
- container: ''
  name: like_count
  type: integer
- container: ''
  name: location_id
  type: string
- container: ''
  name: media_count
  type: integer
- container: ''
  name: media_type
  type: string
- container: ''
  name: media_url
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: next
  type: string
- container: ''
  name: paging
  type: string
- container: ''
  name: parent_id
  type: string
- container: ''
  name: permalink
  type: string
- container: ''
  name: previous
  type: string
- container: ''
  name: profile_picture_url
  type: string
- container: ''
  name: shortcode
  type: string
- container: ''
  name: success
  type: boolean
- container: ''
  name: text
  type: string
- container: ''
  name: thumbnail_url
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: set
  name: user_tags
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: video_url
  type: string
- container: ''
  name: website
  type: string
property_count: 37
provider_name: Instagram
provider_slug: instagram
slug: instagram-graph-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ig\": \"https://developers.facebook.com/docs/instagram-api/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Comment\": \"ig:Comment\",\n    \"CommentList\": \"ig:CommentList\",\n    \"ContainerResponse\": \"ig:ContainerResponse\",\n    \"CreateContainerRequest\": \"ig:CreateContainerRequest\",\n    \"ErrorResponse\": \"ig:ErrorResponse\",\n    \"InsightsResponse\": \"ig:InsightsResponse\",\n    \"Media\": \"ig:Media\",\n    \"MediaList\": \"ig:MediaList\",\n    \"Paging\": \"ig:Paging\",\n    \"SuccessResponse\": \"ig:SuccessResponse\",\n    \"User\": \"ig:User\",\n    \"access_token\": {\n      \"@id\": \"ig:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alt_text\": {\n      \"@id\": \"ig:alt_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"biography\": {\n      \"@id\": \"ig:biography\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  caption\": {\n      \"@id\": \"ig:caption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comments_count\": {\n      \"@id\": \"ig:comments_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cursors\": {\n      \"@id\": \"ig:cursors\",\n      \"@type\": \"@id\"\n    },\n    \"data\": {\n      \"@id\": \"ig:data\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"ig:error\",\n      \"@type\": \"@id\"\n    },\n    \"followers_count\": {\n      \"@id\": \"ig:followers_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"follows_count\": {\n      \"@id\": \"ig:follows_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hidden\": {\n      \"@id\": \"ig:hidden\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"id\": {\n      \"@id\": \"ig:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image_url\": {\n      \"@id\": \"ig:image_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"is_carousel_item\": {\n\
  \      \"@id\": \"ig:is_carousel_item\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_comment_enabled\": {\n      \"@id\": \"ig:is_comment_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"is_shared_to_feed\": {\n      \"@id\": \"ig:is_shared_to_feed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"like_count\": {\n      \"@id\": \"ig:like_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"location_id\": {\n      \"@id\": \"ig:location_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media_count\": {\n      \"@id\": \"ig:media_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"media_type\": {\n      \"@id\": \"ig:media_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"media_url\": {\n      \"@id\": \"ig:media_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"next\": {\n      \"@id\": \"ig:next\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paging\"\
  : {\n      \"@id\": \"ig:paging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent_id\": {\n      \"@id\": \"ig:parent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permalink\": {\n      \"@id\": \"ig:permalink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previous\": {\n      \"@id\": \"ig:previous\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile_picture_url\": {\n      \"@id\": \"ig:profile_picture_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortcode\": {\n      \"@id\": \"ig:shortcode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"success\": {\n      \"@id\": \"ig:success\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"text\": {\n      \"@id\": \"ig:text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbnail_url\": {\n      \"@id\": \"ig:thumbnail_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"ig:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"user_tags\": {\n      \"@id\"\
  : \"ig:user_tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"ig:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"video_url\": {\n      \"@id\": \"ig:video_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"website\": {\n      \"@id\": \"ig:website\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/instagram/refs/heads/main/json-ld/instagram-graph-api-context.jsonld
tags:
- Instagram
- Meta
- Photos
- Social Media
- Videos
- Content Publishing
- JSON-LD
- Linked Data
- Semantic Web
---
