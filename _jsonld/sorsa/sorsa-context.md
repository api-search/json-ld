---
api_specs:
- filename: sorsa-openapi.yml
  format: yaml
  label: Sorsa API v3
  slug: sorsa-api-v3
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/openapi/sorsa-openapi.yml
class_count: 36
classes:
- User
- Follower
- Tweet
- Article
- List
- Community
- Place
- Trend
- id
- screen_name
- name
- display_name
- description
- bio
- verified
- protected
- country
- followers_count
- follows_count
- friends_count
- statuses_count
- full_text
- text
- favorite_count
- retweet_count
- reply_count
- quote_count
- view_count
- bookmark_count
- lang
- score
- score_changes
- followers_stats
- top_followers
- top_following
- next_cursor
context_file: json-ld/sorsa-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/json-ld/sorsa-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sorsa from Sorsa.
layout: jsonld
name: Sorsa Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: sorsa
  uri: https://api.sorsa.io/v3/vocab#
properties:
- container: ''
  name: avatar
  type: reference
- container: ''
  name: banner
  type: reference
- container: ''
  name: profile_image_url
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: registered
  type: dateTime
- container: ''
  name: user
  type: reference
- container: ''
  name: author
  type: reference
- container: ''
  name: in_reply_to_status_id
  type: reference
- container: ''
  name: quoted_status
  type: reference
- container: ''
  name: retweeted_status
  type: reference
property_count: 11
provider_name: Sorsa
provider_slug: sorsa
slug: sorsa-context
source_filename: sorsa-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"sorsa\": \"https://api.sorsa.io/v3/vocab#\",\n\n    \"User\": \"schema:Person\",\n    \"Follower\": \"schema:Person\",\n    \"Tweet\": \"schema:SocialMediaPosting\",\n    \"Article\": \"schema:Article\",\n    \"List\": \"sorsa:List\",\n    \"Community\": \"sorsa:Community\",\n    \"Place\": \"schema:Event\",\n    \"Trend\": \"sorsa:Trend\",\n\n    \"id\": \"schema:identifier\",\n    \"screen_name\": \"schema:alternateName\",\n    \"name\": \"schema:name\",\n    \"display_name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"bio\": \"schema:description\",\n    \"avatar\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"banner\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"profile_image_url\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"url\": { \"@id\": \"schema:url\",\
  \ \"@type\": \"@id\" },\n\n    \"created_at\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"registered\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"verified\": \"sorsa:isVerified\",\n    \"protected\": \"sorsa:isProtected\",\n    \"country\": \"schema:addressCountry\",\n\n    \"followers_count\": \"sorsa:followerCount\",\n    \"follows_count\": \"sorsa:followingCount\",\n    \"friends_count\": \"sorsa:followingCount\",\n    \"statuses_count\": \"sorsa:statusCount\",\n\n    \"full_text\": \"schema:articleBody\",\n    \"text\": \"schema:text\",\n    \"favorite_count\": \"schema:likeCount\",\n    \"retweet_count\": \"sorsa:retweetCount\",\n    \"reply_count\": \"sorsa:replyCount\",\n    \"quote_count\": \"sorsa:quoteCount\",\n    \"view_count\": \"sorsa:viewCount\",\n    \"bookmark_count\": \"sorsa:bookmarkCount\",\n    \"lang\": \"schema:inLanguage\",\n\n    \"user\": { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n    \"author\"\
  : { \"@id\": \"schema:author\", \"@type\": \"@id\" },\n    \"in_reply_to_status_id\": { \"@id\": \"sorsa:inReplyTo\", \"@type\": \"@id\" },\n    \"quoted_status\": { \"@id\": \"sorsa:quotes\", \"@type\": \"@id\" },\n    \"retweeted_status\": { \"@id\": \"sorsa:retweets\", \"@type\": \"@id\" },\n\n    \"score\": \"sorsa:sorsaScore\",\n    \"score_changes\": \"sorsa:sorsaScoreChanges\",\n    \"followers_stats\": \"sorsa:followerCategoryStats\",\n    \"top_followers\": \"sorsa:topFollowersByScore\",\n    \"top_following\": \"sorsa:topFollowingByScore\",\n\n    \"next_cursor\": \"sorsa:nextCursor\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sorsa/refs/heads/main/json-ld/sorsa-context.jsonld
tags:
- Twitter
- X
- Social Media
- Data Extraction
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
