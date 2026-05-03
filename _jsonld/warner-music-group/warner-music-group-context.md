---
api_specs:
- filename: warner-music-group-licensing-openapi.yml
  format: yaml
  label: Warner Music Group Licensing API
  slug: wmg-licensing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/openapi/warner-music-group-licensing-openapi.yml
class_count: 5
classes:
- MusicRecording
- MusicComposition
- MusicGroup
- RecordLabel
- License
context_file: json-ld/warner-music-group-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/json-ld/warner-music-group-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Warner Music Group from Warner Music Group.
layout: jsonld
name: Warner Music Group Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: wmg
  uri: https://api.wmg.com/#
- prefix: mo
  uri: http://purl.org/ontology/mo/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: isrc
  type: string
- container: ''
  name: iswc
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: artistName
  type: string
- container: ''
  name: albumTitle
  type: string
- container: ''
  name: duration
  type: integer
- container: ''
  name: releaseDate
  type: date
- container: ''
  name: genre
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: licenseType
  type: string
- container: ''
  name: territory
  type: string
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: useCase
  type: string
- container: ''
  name: fee
  type: decimal
property_count: 15
provider_name: Warner Music Group
provider_slug: warner-music-group
slug: warner-music-group-context
source_filename: warner-music-group-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"wmg\": \"https://api.wmg.com/#\",\n    \"mo\": \"http://purl.org/ontology/mo/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"MusicRecording\": \"schema:MusicRecording\",\n    \"MusicComposition\": \"schema:MusicComposition\",\n    \"MusicGroup\": \"schema:MusicGroup\",\n    \"RecordLabel\": \"schema:Organization\",\n    \"License\": \"wmg:License\",\n\n    \"isrc\": {\n      \"@id\": \"mo:isrc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iswc\": {\n      \"@id\": \"mo:iswc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artistName\": {\n      \"@id\": \"schema:byArtist\",\n      \"@type\": \"xsd:string\"\n    },\n    \"albumTitle\": {\n      \"@id\": \"schema:inAlbum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"genre\": {\n      \"@id\": \"schema:genre\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"schema:recordLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseType\": {\n      \"@id\": \"wmg:licenseType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"territory\": {\n      \"@id\": \"schema:spatialCoverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"useCase\": {\n      \"@id\": \"wmg:useCase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fee\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/warner-music-group/refs/heads/main/json-ld/warner-music-group-context.jsonld
tags:
- Music
- Entertainment
- Streaming
- Licensing
- Publishing
- JSON-LD
- Linked Data
- Semantic Web
---
