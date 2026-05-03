---
class_count: 13
classes:
- MusicRecording
- MusicGroup
- MusicAlbum
- RadioStation
- PodcastEpisode
- PodcastSeries
- MusicPlaylist
- Track
- Station
- trackToken
- stationId
- songRating
- genre
context_file: json-ld/sirius-xm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/json-ld/sirius-xm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sirius Xm from Sirius XM.
layout: jsonld
name: Sirius Xm Context
namespaces:
- prefix: sxm
  uri: https://developer.pandora.com/schema/
properties:
- container: ''
  name: stationName
  type: ''
- container: ''
  name: songName
  type: ''
- container: ''
  name: artistName
  type: schema:MusicGroup
- container: ''
  name: albumName
  type: schema:MusicAlbum
- container: ''
  name: albumArtUrl
  type: reference
- container: ''
  name: audioUrl
  type: reference
- container: ''
  name: trackLength
  type: ''
- container: ''
  name: dateCreated
  type: schema:DateTime
property_count: 8
provider_name: Sirius XM
provider_slug: sirius-xm
slug: sirius-xm-context
source_filename: sirius-xm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"sxm\": \"https://developer.pandora.com/schema/\",\n    \"MusicRecording\": \"schema:MusicRecording\",\n    \"MusicGroup\": \"schema:MusicGroup\",\n    \"MusicAlbum\": \"schema:MusicAlbum\",\n    \"RadioStation\": \"schema:RadioStation\",\n    \"PodcastEpisode\": \"schema:PodcastEpisode\",\n    \"PodcastSeries\": \"schema:PodcastSeries\",\n    \"MusicPlaylist\": \"schema:MusicPlaylist\",\n    \"Track\": \"sxm:Track\",\n    \"Station\": \"sxm:Station\",\n    \"trackToken\": \"sxm:trackToken\",\n    \"stationId\": \"sxm:stationId\",\n    \"stationName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"songName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"artistName\": {\n      \"@id\": \"schema:byArtist\",\n      \"@type\": \"schema:MusicGroup\"\n    },\n    \"albumName\": {\n      \"@id\": \"schema:inAlbum\",\n      \"@type\": \"schema:MusicAlbum\"\n    },\n    \"albumArtUrl\": {\n      \"@id\": \"\
  schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"audioUrl\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"trackLength\": {\n      \"@id\": \"schema:duration\"\n    },\n    \"songRating\": \"sxm:feedback\",\n    \"genre\": \"schema:genre\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sirius-xm/refs/heads/main/json-ld/sirius-xm-context.jsonld
tags:
- Audio
- Streaming
- Radio
- Music
- Podcast
- Advertising
- Entertainment
- JSON-LD
- Linked Data
- Semantic Web
---
