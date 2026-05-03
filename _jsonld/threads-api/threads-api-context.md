---
api_specs:
- filename: threads-api-openapi.yml
  format: yaml
  label: Threads API
  slug: threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/threads-api/refs/heads/main/openapi/threads-api-openapi.yml
class_count: 26
classes:
- Thread
- UserProfile
- MediaObject
- Insight
- text
- username
- permalink
- timestamp
- media_type
- media_url
- thumbnail_url
- is_quote_post
- has_replies
- is_reply
- reply_control
- hide_status
- root_post
- replied_to
- views
- likes
- replies
- reposts
- quotes
- followers_count
- access_token
- expires_in
context_file: json-ld/threads-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/threads-api/refs/heads/main/json-ld/threads-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Threads Api from Threads.
layout: jsonld
name: Threads Api Context
namespaces:
- prefix: threads
  uri: https://developers.facebook.com/docs/threads/vocab#
properties: []
property_count: 0
provider_name: Threads
provider_slug: threads-api
slug: threads-api-context
source_filename: threads-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"threads\": \"https://developers.facebook.com/docs/threads/vocab#\",\n    \"Thread\": \"SocialMediaPosting\",\n    \"UserProfile\": \"Person\",\n    \"MediaObject\": \"MediaObject\",\n    \"Insight\": \"threads:AnalyticsMetric\",\n    \"text\": \"text\",\n    \"username\": \"identifier\",\n    \"permalink\": \"url\",\n    \"timestamp\": \"datePublished\",\n    \"media_type\": \"encodingFormat\",\n    \"media_url\": \"contentUrl\",\n    \"thumbnail_url\": \"thumbnailUrl\",\n    \"is_quote_post\": \"threads:isQuotePost\",\n    \"has_replies\": \"threads:hasReplies\",\n    \"is_reply\": \"threads:isReply\",\n    \"reply_control\": \"threads:replyControl\",\n    \"hide_status\": \"threads:hideStatus\",\n    \"root_post\": \"threads:rootPost\",\n    \"replied_to\": \"threads:repliedTo\",\n    \"views\": \"threads:viewCount\",\n    \"likes\": \"interactionCount\",\n    \"replies\": \"threads:replyCount\",\n    \"\
  reposts\": \"threads:repostCount\",\n    \"quotes\": \"threads:quoteCount\",\n    \"followers_count\": \"threads:followerCount\",\n    \"access_token\": \"threads:accessToken\",\n    \"expires_in\": \"threads:tokenExpiresIn\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/threads-api/refs/heads/main/json-ld/threads-api-context.jsonld
tags:
- Social
- Social Networks
- Meta
- Publishing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
