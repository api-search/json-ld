---
api_specs:
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Activities API
  slug: youtube-activities-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Channels API
  slug: youtube-channels-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Comments API
  slug: youtube-comments-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Comment Threads API
  slug: youtube-comment-threads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Playlists API
  slug: youtube-playlists-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Playlist Items API
  slug: youtube-playlist-items-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Search API
  slug: youtube-search-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Subscriptions API
  slug: youtube-subscriptions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Videos API
  slug: youtube-videos-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Captions API
  slug: youtube-captions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube Video Categories API
  slug: youtube-video-categories-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube I18n Languages API
  slug: youtube-i18n-languages-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-data-api-openapi.yml
  format: yaml
  label: Youtube I18n Regions API
  slug: youtube-i18n-regions-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-data-api-openapi.yml
- filename: youtube-analytics-openapi.yml
  format: yaml
  label: YouTube Analytics API
  slug: youtube-analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-analytics-openapi.yml
- filename: youtube-reporting-openapi.yml
  format: yaml
  label: YouTube Reporting API
  slug: youtube-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-reporting-openapi.yml
- filename: youtube-live-streaming-openapi.yml
  format: yaml
  label: YouTube Live Streaming API
  slug: youtube-live-streaming-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/openapi/youtube-live-streaming-openapi.yml
class_count: 0
classes: []
context_file: json-ld/youtube-analytics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-analytics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youtube Analytics from Youtube.
layout: jsonld
name: Youtube Analytics Context
namespaces:
- prefix: yt
  uri: https://developers.google.com/youtube/v3/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ColumnHeader
  type: ''
- container: ''
  name: QueryResponse
  type: ''
- container: ''
  name: GroupContentDetails
  type: ''
- container: ''
  name: Group
  type: ''
- container: ''
  name: GroupListResponse
  type: ''
- container: ''
  name: GroupItem
  type: ''
- container: ''
  name: GroupItemListResponse
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 8
provider_name: Youtube
provider_slug: youtube
slug: youtube-analytics-context
source_filename: youtube-analytics-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"yt\": \"https://developers.google.com/youtube/v3/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"ColumnHeader\": {\n      \"@id\": \"yt:ColumnHeader\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"columnType\": {\n          \"@id\": \"yt:columnType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataType\": {\n          \"@id\": \"yt:dataType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"QueryResponse\": {\n      \"@id\": \"yt:QueryResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"columnHeaders\": \"yt:columnHeaders\",\n        \"rows\": \"yt:rows\"\n      }\n    },\n    \"GroupContentDetails\": {\n      \"@id\": \"yt:GroupContentDetails\",\n      \"\
  @context\": {\n        \"itemCount\": {\n          \"@id\": \"yt:itemCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"itemType\": {\n          \"@id\": \"yt:itemType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"Group\": {\n      \"@id\": \"yt:Group\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snippet\": \"yt:snippet\",\n        \"contentDetails\": {\n          \"@id\": \"yt:contentDetails\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"GroupListResponse\": {\n      \"@id\": \"yt:GroupListResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n    \
  \    },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"GroupItem\": {\n      \"@id\": \"yt:GroupItem\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"groupId\": {\n          \"@id\": \"yt:groupId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"resource\": \"yt:resource\"\n      }\n    },\n    \"GroupItemListResponse\": {\n      \"@id\": \"yt:GroupItemListResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"yt:ErrorResponse\",\n      \"@context\": {\n        \"error\": \"yt:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-analytics-context.jsonld
tags:
- Google
- Media
- Social
- Streaming
- Video
- Videos
- JSON-LD
- Linked Data
- Semantic Web
---
