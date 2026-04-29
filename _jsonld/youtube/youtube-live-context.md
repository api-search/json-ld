---
class_count: 0
classes: []
context_file: json-ld/youtube-live-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-live-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youtube Live from Youtube.
layout: jsonld
name: Youtube Live Context
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
  name: PageInfo
  type: ''
- container: ''
  name: LiveBroadcastSnippet
  type: ''
- container: ''
  name: LiveBroadcastStatus
  type: ''
- container: ''
  name: LiveBroadcastContentDetails
  type: ''
- container: ''
  name: LiveBroadcast
  type: ''
- container: ''
  name: LiveBroadcastListResponse
  type: ''
- container: ''
  name: LiveStreamSnippet
  type: ''
- container: ''
  name: LiveStreamStatus
  type: ''
- container: ''
  name: LiveStreamContentDetails
  type: ''
- container: ''
  name: LiveStream
  type: ''
- container: ''
  name: LiveStreamListResponse
  type: ''
- container: ''
  name: LiveChatMessage
  type: ''
- container: ''
  name: LiveChatMessageListResponse
  type: ''
- container: ''
  name: LiveChatModerator
  type: ''
- container: ''
  name: LiveChatModeratorListResponse
  type: ''
- container: ''
  name: ErrorResponse
  type: ''
property_count: 16
provider_name: Youtube
provider_slug: youtube
slug: youtube-live-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"yt\": \"https://developers.google.com/youtube/v3/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"PageInfo\": {\n      \"@id\": \"yt:PageInfo\",\n      \"@context\": {\n        \"totalResults\": {\n          \"@id\": \"yt:totalResults\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"resultsPerPage\": {\n          \"@id\": \"yt:resultsPerPage\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n    \"LiveBroadcastSnippet\": {\n      \"@id\": \"yt:LiveBroadcastSnippet\",\n      \"@context\": {\n        \"publishedAt\": \"dcterms:created\",\n        \"channelId\": {\n          \"@id\": \"yt:channelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"thumbnails\": \"yt:thumbnails\",\n  \
  \      \"scheduledStartTime\": {\n          \"@id\": \"yt:scheduledStartTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"scheduledEndTime\": {\n          \"@id\": \"yt:scheduledEndTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actualStartTime\": {\n          \"@id\": \"yt:actualStartTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actualEndTime\": {\n          \"@id\": \"yt:actualEndTime\",\n          \"@type\": \"xsd:string\"\n        },\n        \"liveChatId\": {\n          \"@id\": \"yt:liveChatId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isDefaultBroadcast\": {\n          \"@id\": \"yt:isDefaultBroadcast\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"LiveBroadcastStatus\": {\n      \"@id\": \"yt:LiveBroadcastStatus\",\n      \"@context\": {\n        \"lifeCycleStatus\": {\n          \"@id\": \"yt:lifeCycleStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  privacyStatus\": {\n          \"@id\": \"yt:privacyStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recordingStatus\": {\n          \"@id\": \"yt:recordingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"madeForKids\": {\n          \"@id\": \"yt:madeForKids\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"selfDeclaredMadeForKids\": {\n          \"@id\": \"yt:selfDeclaredMadeForKids\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"LiveBroadcastContentDetails\": {\n      \"@id\": \"yt:LiveBroadcastContentDetails\",\n      \"@context\": {\n        \"boundStreamId\": {\n          \"@id\": \"yt:boundStreamId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"boundStreamLastUpdateTimeMs\": {\n          \"@id\": \"yt:boundStreamLastUpdateTimeMs\",\n          \"@type\": \"xsd:string\"\n        },\n        \"monitorStream\": \"yt:monitorStream\",\n        \"enableEmbed\": {\n          \"@id\": \"yt:enableEmbed\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enableDvr\": {\n          \"@id\": \"yt:enableDvr\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enableContentEncryption\": {\n          \"@id\": \"yt:enableContentEncryption\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"startWithSlate\": {\n          \"@id\": \"yt:startWithSlate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"closedCaptionsType\": {\n          \"@id\": \"yt:closedCaptionsType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enableLowLatency\": {\n          \"@id\": \"yt:enableLowLatency\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"latencyPreference\": {\n          \"@id\": \"yt:latencyPreference\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enableAutoStart\": {\n          \"@id\": \"yt:enableAutoStart\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"enableAutoStop\": {\n          \"@id\": \"\
  yt:enableAutoStop\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"LiveBroadcast\": {\n      \"@id\": \"yt:LiveBroadcast\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snippet\": {\n          \"@id\": \"yt:snippet\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"yt:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentDetails\": {\n          \"@id\": \"yt:contentDetails\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statistics\": \"yt:statistics\"\n      }\n    },\n    \"LiveBroadcastListResponse\": {\n      \"@id\": \"yt:LiveBroadcastListResponse\",\n      \"@context\": {\n        \"\
  kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prevPageToken\": {\n          \"@id\": \"yt:prevPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageInfo\": {\n          \"@id\": \"yt:pageInfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"LiveStreamSnippet\": {\n      \"@id\": \"yt:LiveStreamSnippet\",\n      \"@context\": {\n        \"channelId\": {\n          \"@id\": \"yt:channelId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": \"dcterms:created\",\n        \"isDefaultStream\": {\n          \"@id\": \"yt:isDefaultStream\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"LiveStreamStatus\": {\n      \"@id\": \"yt:LiveStreamStatus\",\n      \"@context\": {\n        \"streamStatus\": {\n          \"@id\": \"yt:streamStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"healthStatus\": \"yt:healthStatus\"\n      }\n    },\n    \"LiveStreamContentDetails\": {\n      \"@id\": \"yt:LiveStreamContentDetails\",\n      \"@context\": {\n        \"boundBroadcastId\": {\n          \"@id\": \"yt:boundBroadcastId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isReusable\": {\n          \"@id\": \"yt:isReusable\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n    \"LiveStream\": {\n      \"@id\": \"yt:LiveStream\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snippet\": {\n          \"@id\": \"yt:snippet\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cdn\": \"yt:cdn\",\n        \"status\": {\n          \"@id\": \"yt:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"contentDetails\": {\n          \"@id\": \"yt:contentDetails\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n    \"LiveStreamListResponse\": {\n      \"@id\": \"yt:LiveStreamListResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prevPageToken\": {\n          \"@id\": \"yt:prevPageToken\",\n          \"\
  @type\": \"xsd:string\"\n        },\n        \"pageInfo\": {\n          \"@id\": \"yt:pageInfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"LiveChatMessage\": {\n      \"@id\": \"yt:LiveChatMessage\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snippet\": \"yt:snippet\",\n        \"authorDetails\": \"yt:authorDetails\"\n      }\n    },\n    \"LiveChatMessageListResponse\": {\n      \"@id\": \"yt:LiveChatMessageListResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pollingIntervalMillis\": {\n          \"@id\": \"yt:pollingIntervalMillis\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"offlineAt\": {\n          \"@id\": \"yt:offlineAt\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageInfo\": {\n          \"@id\": \"yt:pageInfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"LiveChatModerator\": {\n      \"@id\": \"yt:LiveChatModerator\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"id\": {\n          \"@id\": \"yt:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"snippet\": \"yt:snippet\"\n      }\n    },\n\
  \    \"LiveChatModeratorListResponse\": {\n      \"@id\": \"yt:LiveChatModeratorListResponse\",\n      \"@context\": {\n        \"kind\": {\n          \"@id\": \"yt:kind\",\n          \"@type\": \"xsd:string\"\n        },\n        \"etag\": {\n          \"@id\": \"yt:etag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"nextPageToken\": {\n          \"@id\": \"yt:nextPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"prevPageToken\": {\n          \"@id\": \"yt:prevPageToken\",\n          \"@type\": \"xsd:string\"\n        },\n        \"pageInfo\": {\n          \"@id\": \"yt:pageInfo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"items\": \"yt:items\"\n      }\n    },\n    \"ErrorResponse\": {\n      \"@id\": \"yt:ErrorResponse\",\n      \"@context\": {\n        \"error\": \"yt:error\"\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-live-context.jsonld
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
