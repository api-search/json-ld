---
class_count: 0
classes: []
context_file: json-ld/youtube-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Youtube from Youtube.
layout: jsonld
name: Youtube Context
namespaces:
- prefix: yt
  uri: https://developers.google.com/youtube/v3/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: Video
  type: ''
- container: ''
  name: Channel
  type: ''
- container: ''
  name: Playlist
  type: ''
- container: ''
  name: PlaylistItem
  type: ''
- container: ''
  name: Comment
  type: ''
- container: ''
  name: CommentThread
  type: ''
- container: ''
  name: Subscription
  type: ''
- container: ''
  name: LiveBroadcast
  type: ''
- container: ''
  name: LiveStream
  type: ''
- container: ''
  name: AnalyticsReport
  type: ''
property_count: 10
provider_name: Youtube
provider_slug: youtube
slug: youtube-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"yt\": \"https://developers.google.com/youtube/v3/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"Video\": {\n      \"@id\": \"schema:VideoObject\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"channelTitle\": \"yt:channelTitle\",\n        \"thumbnails\": \"yt:thumbnails\",\n        \"tags\": \"yt:tags\",\n        \"categoryId\": \"yt:categoryId\",\n        \"statistics\": \"yt:statistics\",\n \
  \       \"viewCount\": {\n          \"@id\": \"schema:interactionCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"likeCount\": {\n          \"@id\": \"yt:likeCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"commentCount\": {\n          \"@id\": \"schema:commentCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"favoriteCount\": {\n          \"@id\": \"yt:favoriteCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"contentDetails\": \"yt:contentDetails\",\n        \"duration\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:duration\"\n        },\n        \"dimension\": \"yt:dimension\",\n        \"definition\": \"yt:definition\",\n        \"caption\": \"yt:caption\",\n        \"licensedContent\": \"yt:licensedContent\",\n        \"status\": \"yt:status\",\n        \"uploadStatus\": \"yt:uploadStatus\",\n        \"privacyStatus\": \"yt:privacyStatus\",\n        \"embeddable\": \"yt:embeddable\"\
  ,\n        \"publicStatsViewable\": \"yt:publicStatsViewable\",\n        \"player\": \"yt:player\",\n        \"embedHtml\": \"yt:embedHtml\"\n      }\n    },\n\n    \"Channel\": {\n      \"@id\": \"schema:Organization\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"customUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"country\": {\n          \"@id\": \"schema:addressCountry\"\n        },\n        \"thumbnails\": \"yt:thumbnails\",\n        \"statistics\": \"yt:statistics\",\n        \"subscriberCount\": {\n          \"@id\": \"yt:subscriberCount\",\n   \
  \       \"@type\": \"xsd:integer\"\n        },\n        \"viewCount\": {\n          \"@id\": \"yt:viewCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"videoCount\": {\n          \"@id\": \"yt:videoCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"hiddenSubscriberCount\": \"yt:hiddenSubscriberCount\",\n        \"contentDetails\": \"yt:contentDetails\",\n        \"relatedPlaylists\": \"yt:relatedPlaylists\",\n        \"brandingSettings\": \"yt:brandingSettings\"\n      }\n    },\n\n    \"Playlist\": {\n      \"@id\": \"yt:Playlist\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"channelTitle\"\
  : \"yt:channelTitle\",\n        \"thumbnails\": \"yt:thumbnails\",\n        \"tags\": \"yt:tags\",\n        \"status\": \"yt:status\",\n        \"privacyStatus\": \"yt:privacyStatus\",\n        \"contentDetails\": \"yt:contentDetails\",\n        \"itemCount\": {\n          \"@id\": \"yt:itemCount\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PlaylistItem\": {\n      \"@id\": \"yt:PlaylistItem\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"channelTitle\": \"yt:channelTitle\",\n        \"playlistId\": \"yt:playlistId\",\n        \"position\": {\n          \"@id\": \"yt:position\",\n          \"\
  @type\": \"xsd:integer\"\n        },\n        \"resourceId\": \"yt:resourceId\",\n        \"videoId\": \"yt:videoId\",\n        \"thumbnails\": \"yt:thumbnails\",\n        \"contentDetails\": \"yt:contentDetails\",\n        \"status\": \"yt:status\"\n      }\n    },\n\n    \"Comment\": {\n      \"@id\": \"schema:Comment\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"textOriginal\": {\n          \"@id\": \"schema:text\"\n        },\n        \"textDisplay\": \"yt:textDisplay\",\n        \"authorDisplayName\": {\n          \"@id\": \"schema:author\"\n        },\n        \"authorProfileImageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        },\n        \"authorChannelUrl\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"likeCount\": {\n          \"@id\": \"yt:likeCount\",\n          \"@type\": \"\
  xsd:integer\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"videoId\": \"yt:videoId\",\n        \"parentId\": \"yt:parentId\",\n        \"canRate\": \"yt:canRate\",\n        \"moderationStatus\": \"yt:moderationStatus\"\n      }\n    },\n\n    \"CommentThread\": {\n      \"@id\": \"yt:CommentThread\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"channelId\": \"yt:channelId\",\n        \"videoId\": \"yt:videoId\",\n        \"topLevelComment\": {\n          \"@id\": \"yt:topLevelComment\",\n          \"@type\": \"schema:Comment\"\n        },\n        \"canReply\": \"yt:canReply\",\n        \"totalReplyCount\": {\n          \"@id\": \"yt:totalReplyCount\",\n   \
  \       \"@type\": \"xsd:integer\"\n        },\n        \"isPublic\": \"yt:isPublic\",\n        \"replies\": \"yt:replies\"\n      }\n    },\n\n    \"Subscription\": {\n      \"@id\": \"yt:Subscription\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"resourceId\": \"yt:resourceId\",\n        \"thumbnails\": \"yt:thumbnails\",\n        \"contentDetails\": \"yt:contentDetails\",\n        \"subscriberSnippet\": \"yt:subscriberSnippet\"\n      }\n    },\n\n    \"LiveBroadcast\": {\n      \"@id\": \"schema:BroadcastEvent\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\"\
  ,\n        \"snippet\": \"yt:snippet\",\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\"\n        },\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheduledStartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"scheduledEndTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"actualStartTime\": {\n          \"@id\": \"yt:actualStartTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"actualEndTime\": {\n          \"@id\": \"yt:actualEndTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"liveChatId\": \"yt:liveChatId\",\n        \"isDefaultBroadcast\": \"yt:isDefaultBroadcast\",\n        \"thumbnails\": \"yt:thumbnails\"\
  ,\n        \"status\": \"yt:status\",\n        \"lifeCycleStatus\": \"yt:lifeCycleStatus\",\n        \"privacyStatus\": \"yt:privacyStatus\",\n        \"recordingStatus\": \"yt:recordingStatus\",\n        \"contentDetails\": \"yt:contentDetails\"\n      }\n    },\n\n    \"LiveStream\": {\n      \"@id\": \"yt:LiveStream\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"kind\": \"yt:kind\",\n        \"etag\": \"yt:etag\",\n        \"snippet\": \"yt:snippet\",\n        \"title\": \"dcterms:title\",\n        \"description\": \"dcterms:description\",\n        \"publishedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"channelId\": \"yt:channelId\",\n        \"isDefaultStream\": \"yt:isDefaultStream\",\n        \"cdn\": \"yt:cdn\",\n        \"ingestionType\": \"yt:ingestionType\",\n        \"ingestionInfo\": \"yt:ingestionInfo\",\n        \"streamName\": \"yt:streamName\",\n        \"ingestionAddress\": {\n          \"\
  @id\": \"yt:ingestionAddress\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"yt:status\",\n        \"streamStatus\": \"yt:streamStatus\",\n        \"healthStatus\": \"yt:healthStatus\",\n        \"contentDetails\": \"yt:contentDetails\"\n      }\n    },\n\n    \"AnalyticsReport\": {\n      \"@id\": \"yt:AnalyticsReport\",\n      \"@context\": {\n        \"kind\": \"yt:kind\",\n        \"columnHeaders\": \"yt:columnHeaders\",\n        \"rows\": \"yt:rows\",\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"columnType\": \"yt:columnType\",\n        \"dataType\": \"yt:dataType\",\n        \"startDate\": {\n          \"@id\": \"yt:startDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"endDate\": {\n          \"@id\": \"yt:endDate\",\n          \"@type\": \"xsd:date\"\n        },\n        \"metrics\": \"yt:metrics\",\n        \"dimensions\": \"yt:dimensions\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/youtube/refs/heads/main/json-ld/youtube-context.jsonld
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
