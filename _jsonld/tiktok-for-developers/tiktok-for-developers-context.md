---
api_specs:
- filename: tiktok-display-openapi.yml
  format: yaml
  label: TikTok Display API
  slug: tiktok-display-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-display-openapi.yml
- filename: tiktok-content-posting-openapi.yml
  format: yaml
  label: TikTok Content Posting API
  slug: tiktok-content-posting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-content-posting-openapi.yml
- filename: tiktok-research-openapi.yml
  format: yaml
  label: TikTok Research API
  slug: tiktok-research-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-research-openapi.yml
- filename: tiktok-login-kit-openapi.yml
  format: yaml
  label: TikTok Login Kit
  slug: tiktok-login-kit
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/openapi/tiktok-login-kit-openapi.yml
class_count: 27
classes:
- open_id
- union_id
- avatar_url
- display_name
- bio_description
- profile_deep_link
- is_verified
- follower_count
- following_count
- likes_count
- video_count
- cover_image_url
- share_url
- video_description
- view_count
- like_count
- comment_count
- share_count
- hashtag_names
- region_code
- publish_id
- privacy_level
- create_time
- duration
- TikTokVideo
- TikTokUser
- TikTokComment
context_file: json-ld/tiktok-for-developers-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/json-ld/tiktok-for-developers-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tiktok For Developers from TikTok for Developers.
layout: jsonld
name: Tiktok For Developers Context
namespaces:
- prefix: tiktok
  uri: https://developers.tiktok.com/vocab/
properties: []
property_count: 0
provider_name: TikTok for Developers
provider_slug: tiktok-for-developers
slug: tiktok-for-developers-context
source_filename: tiktok-for-developers-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"tiktok\": \"https://developers.tiktok.com/vocab/\",\n    \"open_id\": \"tiktok:openId\",\n    \"union_id\": \"tiktok:unionId\",\n    \"avatar_url\": \"image\",\n    \"display_name\": \"name\",\n    \"bio_description\": \"description\",\n    \"profile_deep_link\": \"url\",\n    \"is_verified\": \"tiktok:isVerified\",\n    \"follower_count\": \"tiktok:followerCount\",\n    \"following_count\": \"tiktok:followingCount\",\n    \"likes_count\": \"tiktok:likesCount\",\n    \"video_count\": \"tiktok:videoCount\",\n    \"cover_image_url\": \"thumbnailUrl\",\n    \"share_url\": \"url\",\n    \"video_description\": \"description\",\n    \"view_count\": \"tiktok:viewCount\",\n    \"like_count\": \"tiktok:likeCount\",\n    \"comment_count\": \"commentCount\",\n    \"share_count\": \"tiktok:shareCount\",\n    \"hashtag_names\": \"keywords\",\n    \"region_code\": \"addressCountry\",\n    \"publish_id\": \"tiktok:publishId\"\
  ,\n    \"privacy_level\": \"tiktok:privacyLevel\",\n    \"create_time\": \"dateCreated\",\n    \"duration\": \"duration\",\n    \"TikTokVideo\": \"VideoObject\",\n    \"TikTokUser\": \"Person\",\n    \"TikTokComment\": \"Comment\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tiktok-for-developers/refs/heads/main/json-ld/tiktok-for-developers-context.jsonld
tags:
- Advertising
- Analytics
- Authentication
- Content
- Social Media
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
