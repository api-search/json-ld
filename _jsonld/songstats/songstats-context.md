---
api_specs:
- filename: songstats-openapi.yml
  format: yaml
  label: Songstats Enterprise API
  slug: songstats-enterprise-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/openapi/songstats-openapi.yml
class_count: 5
classes:
- songstats_artist_id
- songstats_track_id
- songstats_label_id
- name
- title
context_file: json-ld/songstats-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/json-ld/songstats-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Songstats from Songstats.
layout: jsonld
name: Songstats Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: mo
  uri: http://purl.org/ontology/mo/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Artist
  type: reference
- container: ''
  name: Track
  type: reference
- container: ''
  name: Label
  type: reference
- container: ''
  name: Collaborator
  type: reference
- container: set
  name: genres
  type: ''
- container: ''
  name: isrc
  type: string
- container: ''
  name: release_date
  type: date
- container: ''
  name: image_url
  type: reference
- container: set
  name: artists
  type: ''
- container: ''
  name: followers
  type: integer
- container: ''
  name: monthly_listeners
  type: integer
- container: ''
  name: streams
  type: integer
- container: ''
  name: source
  type: string
property_count: 13
provider_name: Songstats
provider_slug: songstats
slug: songstats-context
source_filename: songstats-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"mo\": \"http://purl.org/ontology/mo/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Artist\": {\n      \"@id\": \"schema:MusicGroup\",\n      \"@type\": \"@id\"\n    },\n    \"Track\": {\n      \"@id\": \"schema:MusicRecording\",\n      \"@type\": \"@id\"\n    },\n    \"Label\": {\n      \"@id\": \"schema:MusicLabel\",\n      \"@type\": \"@id\"\n    },\n    \"Collaborator\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\"\n    },\n\n    \"songstats_artist_id\": \"@id\",\n    \"songstats_track_id\": \"@id\",\n    \"songstats_label_id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"title\": \"schema:name\",\n    \"genres\": {\n      \"@id\": \"schema:genre\",\n      \"@container\": \"@set\"\n    },\n    \"isrc\": {\n      \"@id\": \"schema:isrcCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"release_date\": {\n      \"@id\": \"schema:datePublished\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"image_url\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"artists\": {\n      \"@id\": \"schema:byArtist\",\n      \"@container\": \"@set\"\n    },\n    \"followers\": {\n      \"@id\": \"schema:followeeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"monthly_listeners\": {\n      \"@id\": \"mo:performer\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"streams\": {\n      \"@id\": \"schema:interactionCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"source\": {\n      \"@id\": \"schema:provider\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/songstats/refs/heads/main/json-ld/songstats-context.jsonld
tags:
- Analytics
- Music
- Streaming
- Artists
- Tracks
- Labels
- JSON-LD
- Linked Data
- Semantic Web
---
