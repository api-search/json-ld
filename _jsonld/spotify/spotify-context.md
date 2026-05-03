---
api_specs:
- filename: spotify-openapi-original.yml
  format: yaml
  label: Spotify Web API
  slug: spotify-web-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/openapi/spotify-openapi-original.yml
class_count: 54
classes:
- MusicRecording
- MusicPlaylist
- MusicAlbum
- MusicGroup
- PodcastSeries
- PodcastEpisode
- Track
- Artist
- Album
- Playlist
- Show
- Episode
- id
- uri
- name
- description
- duration_ms
- explicit
- popularity
- preview_url
- track_number
- disc_number
- is_playable
- is_local
- release_date
- album_type
- total_tracks
- collaborative
- public
- snapshot_id
- followers
- images
- artists
- album
- tracks
- owner
- added_at
- added_by
- available_markets
- external_urls
- external_ids
- isrc
- tempo
- key
- mode
- energy
- danceability
- valence
- acousticness
- instrumentalness
- liveness
- loudness
- speechiness
- time_signature
context_file: json-ld/spotify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/json-ld/spotify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spotify from Spotify.
layout: jsonld
name: Spotify Context
namespaces:
- prefix: spotify
  uri: https://developer.spotify.com/vocab#
properties:
- container: ''
  name: audio_features
  type: '@json'
property_count: 1
provider_name: Spotify
provider_slug: spotify
slug: spotify-context
source_filename: spotify-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"spotify\": \"https://developer.spotify.com/vocab#\",\n    \"MusicRecording\": \"MusicRecording\",\n    \"MusicPlaylist\": \"MusicPlaylist\",\n    \"MusicAlbum\": \"MusicAlbum\",\n    \"MusicGroup\": \"MusicGroup\",\n    \"PodcastSeries\": \"PodcastSeries\",\n    \"PodcastEpisode\": \"PodcastEpisode\",\n    \"Track\": \"MusicRecording\",\n    \"Artist\": \"MusicGroup\",\n    \"Album\": \"MusicAlbum\",\n    \"Playlist\": \"MusicPlaylist\",\n    \"Show\": \"PodcastSeries\",\n    \"Episode\": \"PodcastEpisode\",\n    \"id\": \"spotify:spotifyId\",\n    \"uri\": \"spotify:spotifyUri\",\n    \"name\": \"name\",\n    \"description\": \"description\",\n    \"duration_ms\": \"spotify:durationMs\",\n    \"explicit\": \"spotify:explicit\",\n    \"popularity\": \"spotify:popularity\",\n    \"preview_url\": \"contentUrl\",\n    \"track_number\": \"position\",\n    \"disc_number\": \"spotify:discNumber\",\n    \"is_playable\"\
  : \"spotify:isPlayable\",\n    \"is_local\": \"spotify:isLocal\",\n    \"release_date\": \"datePublished\",\n    \"album_type\": \"albumProductionType\",\n    \"total_tracks\": \"numTracks\",\n    \"collaborative\": \"spotify:collaborative\",\n    \"public\": \"isAccessibleForFree\",\n    \"snapshot_id\": \"spotify:snapshotId\",\n    \"followers\": \"interactionStatistic\",\n    \"images\": \"image\",\n    \"artists\": \"byArtist\",\n    \"album\": \"inAlbum\",\n    \"tracks\": \"track\",\n    \"owner\": \"author\",\n    \"added_at\": \"dateCreated\",\n    \"added_by\": \"creator\",\n    \"available_markets\": \"areaServed\",\n    \"external_urls\": \"sameAs\",\n    \"external_ids\": \"identifier\",\n    \"isrc\": \"isrcCode\",\n    \"audio_features\": {\n      \"@id\": \"spotify:audioFeatures\",\n      \"@type\": \"@json\"\n    },\n    \"tempo\": \"spotify:tempo\",\n    \"key\": \"spotify:key\",\n    \"mode\": \"spotify:mode\",\n    \"energy\": \"spotify:energy\",\n    \"danceability\"\
  : \"spotify:danceability\",\n    \"valence\": \"spotify:valence\",\n    \"acousticness\": \"spotify:acousticness\",\n    \"instrumentalness\": \"spotify:instrumentalness\",\n    \"liveness\": \"spotify:liveness\",\n    \"loudness\": \"spotify:loudness\",\n    \"speechiness\": \"spotify:speechiness\",\n    \"time_signature\": \"spotify:timeSignature\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spotify/refs/heads/main/json-ld/spotify-context.jsonld
tags:
- Music
- Audio
- Streaming
- Podcasts
- Playlists
- JSON-LD
- Linked Data
- Semantic Web
---
