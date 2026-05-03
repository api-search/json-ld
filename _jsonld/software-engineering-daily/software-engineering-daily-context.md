---
class_count: 19
classes:
- Episode
- Podcast
- Person
- Organization
- id
- type
- title
- name
- description
- summary
- topics
- upvotes
- isPremium
- organization
- jobTitle
- language
- explicit
- episodeNumber
- season
context_file: json-ld/software-engineering-daily-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/software-engineering-daily/refs/heads/main/json-ld/software-engineering-daily-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Software Engineering Daily from Software Engineering Daily.
layout: jsonld
name: Software Engineering Daily Context
namespaces:
- prefix: sed
  uri: https://api-evangelist.com/vocab/software-engineering-daily#
- prefix: schema
  uri: https://schema.org/
- prefix: podcast
  uri: https://podcastindex.org/namespace/1.0#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: audioUrl
  type: reference
- container: ''
  name: duration
  type: integer
- container: ''
  name: publishedAt
  type: dateTime
- container: ''
  name: episodeUrl
  type: reference
- container: ''
  name: imageUrl
  type: reference
- container: set
  name: guests
  type: ''
- container: ''
  name: feedUrl
  type: reference
property_count: 7
provider_name: Software Engineering Daily
provider_slug: software-engineering-daily
slug: software-engineering-daily-context
source_filename: software-engineering-daily-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sed\": \"https://api-evangelist.com/vocab/software-engineering-daily#\",\n    \"schema\": \"https://schema.org/\",\n    \"podcast\": \"https://podcastindex.org/namespace/1.0#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Episode\": \"schema:PodcastEpisode\",\n    \"Podcast\": \"schema:PodcastSeries\",\n    \"Person\": \"schema:Person\",\n    \"Organization\": \"schema:Organization\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"title\": \"schema:name\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"summary\": \"schema:abstract\",\n\n    \"audioUrl\": {\n      \"@id\": \"schema:associatedMedia\",\n      \"@type\": \"@id\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"publishedAt\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"episodeUrl\"\
  : {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"imageUrl\": {\n      \"@id\": \"schema:image\",\n      \"@type\": \"@id\"\n    },\n    \"guests\": {\n      \"@id\": \"schema:author\",\n      \"@container\": \"@set\"\n    },\n    \"topics\": \"schema:keywords\",\n    \"upvotes\": \"sed:upvotes\",\n    \"isPremium\": \"sed:isPremium\",\n\n    \"organization\": \"schema:affiliation\",\n    \"jobTitle\": \"schema:jobTitle\",\n\n    \"feedUrl\": {\n      \"@id\": \"podcast:feedUrl\",\n      \"@type\": \"@id\"\n    },\n    \"language\": \"schema:inLanguage\",\n    \"explicit\": \"podcast:explicit\",\n    \"episodeNumber\": \"podcast:episode\",\n    \"season\": \"podcast:season\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/software-engineering-daily/refs/heads/main/json-ld/software-engineering-daily-context.jsonld
tags:
- Media
- Podcasts
- Software Engineering
- Technical Content
- Open Source
- JSON-LD
- Linked Data
- Semantic Web
---
