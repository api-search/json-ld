---
api_specs:
- filename: reference
  format: yaml
  label: Twitch API
  slug: ''
  spec_type: OpenAPI
  url: https://dev.twitch.tv/docs/api/reference
- filename: twitch-eventsub-asyncapi.yml
  format: yaml
  label: Twitch EventSub
  slug: ''
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/asyncapi/twitch-eventsub-asyncapi.yml
- filename: twitch-extensions-openapi.yml
  format: yaml
  label: Twitch Extensions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-extensions-openapi.yml
- filename: twitch-drops-openapi.yml
  format: yaml
  label: Twitch Drops API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-drops-openapi.yml
- filename: twitch-video-broadcast-openapi.yml
  format: yaml
  label: Twitch Video Broadcast API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-video-broadcast-openapi.yml
- filename: twitch-insights-analytics-openapi.yml
  format: yaml
  label: Twitch Insights and Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-insights-analytics-openapi.yml
- filename: twitch-igdb-openapi.yml
  format: yaml
  label: IGDB API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/openapi/twitch-igdb-openapi.yml
class_count: 0
classes: []
context_file: json-ld/twitch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/json-ld/twitch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Twitch from Twitch.
layout: jsonld
name: Twitch Context
namespaces:
- prefix: twitch
  uri: https://dev.twitch.tv/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: User
  type: ''
- container: ''
  name: Stream
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: Video
  type: ''
- container: ''
  name: Clip
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: Game
  type: ''
- container: ''
  name: Emote
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: Extension
  type: ''
- container: ''
  name: EventSubSubscription
  type: ''
property_count: 11
provider_name: Twitch
provider_slug: twitch
slug: twitch-context
source_filename: twitch-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"twitch\": \"https://dev.twitch.tv/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"User\": {\n      \"@id\": \"twitch:User\",\n      \"@context\": {\n        \"login\": \"schema:alternateName\",\n        \"display_name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"broadcaster_type\": \"twitch:broadcasterType\",\n        \"profile_image_url\": \"schema:image\",\n        \"offline_image_url\": \"twitch:offlineImageUrl\",\n        \"email\": \"schema:email\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Stream\": {\n      \"@id\": \"twitch:Stream\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"game_name\": \"twitch:gameName\",\n        \"viewer_count\": {\n\
  \          \"@id\": \"twitch:viewerCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"language\": \"schema:inLanguage\",\n        \"started_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"thumbnail_url\": \"schema:thumbnailUrl\",\n        \"is_mature\": {\n          \"@id\": \"twitch:isMature\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"twitch:Channel\",\n      \"@context\": {\n        \"broadcaster_name\": \"schema:name\",\n        \"broadcaster_language\": \"schema:inLanguage\",\n        \"title\": \"schema:headline\",\n        \"game_name\": \"twitch:gameName\",\n        \"delay\": {\n          \"@id\": \"twitch:delay\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"is_branded_content\": {\n          \"@id\": \"twitch:isBrandedContent\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Video\": {\n\
  \      \"@id\": \"twitch:Video\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"url\": \"schema:url\",\n        \"thumbnail_url\": \"schema:thumbnailUrl\",\n        \"view_count\": {\n          \"@id\": \"schema:interactionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"language\": \"schema:inLanguage\",\n        \"duration\": \"schema:duration\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"published_at\": {\n          \"@id\": \"dcterms:issued\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Clip\": {\n      \"@id\": \"twitch:Clip\",\n      \"@context\": {\n        \"title\": \"schema:name\",\n        \"url\": \"schema:url\",\n        \"embed_url\": \"schema:embedUrl\",\n        \"broadcaster_name\": \"twitch:broadcasterName\",\n        \"creator_name\": \"schema:creator\",\n\
  \        \"view_count\": {\n          \"@id\": \"schema:interactionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"thumbnail_url\": \"schema:thumbnailUrl\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"twitch:Subscription\",\n      \"@context\": {\n        \"broadcaster_name\": \"twitch:broadcasterName\",\n        \"user_name\": \"schema:name\",\n        \"tier\": \"twitch:tier\",\n        \"plan_name\": \"twitch:planName\",\n        \"is_gift\": {\n          \"@id\": \"twitch:isGift\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"gifter_name\": \"twitch:gifterName\"\n      }\n    },\n\n    \"Game\": {\n      \"@id\": \"twitch:Game\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n       \
  \ \"box_art_url\": \"schema:image\",\n        \"igdb_id\": \"twitch:igdbId\"\n      }\n    },\n\n    \"Emote\": {\n      \"@id\": \"twitch:Emote\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"emote_type\": \"twitch:emoteType\",\n        \"emote_set_id\": \"twitch:emoteSetId\",\n        \"tier\": \"twitch:tier\"\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"twitch:Team\",\n      \"@context\": {\n        \"team_display_name\": \"schema:name\",\n        \"info\": \"schema:description\",\n        \"thumbnail_url\": \"schema:image\",\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updated_at\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Extension\": {\n      \"@id\": \"twitch:Extension\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n   \
  \     \"author_name\": \"schema:author\",\n        \"version\": \"schema:softwareVersion\",\n        \"icon_url\": \"schema:image\",\n        \"state\": \"twitch:extensionState\",\n        \"bits_enabled\": {\n          \"@id\": \"twitch:bitsEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"EventSubSubscription\": {\n      \"@id\": \"twitch:EventSubSubscription\",\n      \"@context\": {\n        \"type\": \"twitch:eventType\",\n        \"version\": \"schema:version\",\n        \"status\": \"twitch:status\",\n        \"cost\": {\n          \"@id\": \"twitch:cost\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"created_at\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/twitch/refs/heads/main/json-ld/twitch-context.jsonld
tags:
- Entertainment
- Gaming
- Live Video
- Streaming
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
