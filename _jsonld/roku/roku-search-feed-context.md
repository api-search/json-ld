---
api_specs:
- filename: roku-external-control-protocol.yaml
  format: yaml
  label: Roku External Control Protocol (ECP)
  slug: external-control-protocol
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-external-control-protocol.yaml
- filename: roku-pay-web-services.yaml
  format: yaml
  label: Roku Pay Web Services
  slug: pay
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-pay-web-services.yaml
- filename: roku-nabu-cloud.yaml
  format: yaml
  label: Roku Nabu Cloud
  slug: nabu-cloud
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/openapi/roku-nabu-cloud.yaml
class_count: 0
classes: []
context_file: json-ld/roku-search-feed-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-search-feed-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roku Search Feed from Roku.
layout: jsonld
name: Roku Search Feed Context
namespaces:
- prefix: roku
  uri: https://developer.roku.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: advisoryRatings
  type: ''
- container: set
  name: assets
  type: reference
- container: ''
  name: birthDate
  type: string
- container: ''
  name: content
  type: reference
- container: set
  name: credits
  type: reference
- container: ''
  name: deathDate
  type: string
- container: set
  name: defaultAvailabilityCountries
  type: ''
- container: ''
  name: defaultLanguage
  type: ''
- container: ''
  name: durationInMilliseconds
  type: decimal
- container: ''
  name: durationInSeconds
  type: integer
- container: ''
  name: episodeInfo
  type: reference
- container: ''
  name: episodeNumber
  type: integer
- container: ''
  name: externalIdSource
  type: ''
- container: set
  name: externalIds
  type: ''
- container: set
  name: genres
  type: ''
- container: ''
  name: id
  type: string
- container: ''
  name: imageUrl
  type: string
- container: set
  name: images
  type: ''
- container: ''
  name: isOriginal
  type: boolean
- container: set
  name: linearEvents
  type: ''
- container: set
  name: longDescriptions
  type: ''
- container: ''
  name: media
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: nextPageUrl
  type: string
- container: set
  name: playOptions
  type: ''
- container: ''
  name: releaseDate
  type: string
- container: ''
  name: releaseYear
  type: integer
- container: ''
  name: role
  type: string
- container: ''
  name: seasonInfo
  type: reference
- container: ''
  name: seasonNumber
  type: integer
- container: ''
  name: seriesId
  type: string
- container: set
  name: shortDescriptions
  type: ''
- container: set
  name: tags
  type: string
- container: set
  name: titles
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: version
  type: ''
property_count: 36
provider_name: Roku
provider_slug: roku
slug: roku-search-feed-context
source_filename: roku-search-feed-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"roku\": \"https://developer.roku.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"advisoryRatings\": {\n      \"@id\": \"roku:advisoryRatings\",\n      \"@container\": \"@set\"\n    },\n    \"assets\": {\n      \"@id\": \"roku:assets\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"birthDate\": {\n      \"@id\": \"roku:birthDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"roku:content\",\n      \"@type\": \"@id\"\n    },\n    \"credits\": {\n      \"@id\": \"roku:credits\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deathDate\": {\n      \"@id\": \"roku:deathDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultAvailabilityCountries\": {\n      \"@id\": \"roku:defaultAvailabilityCountries\",\n      \"@container\"\
  : \"@set\"\n    },\n    \"defaultLanguage\": {\n      \"@id\": \"roku:defaultLanguage\"\n    },\n    \"durationInMilliseconds\": {\n      \"@id\": \"roku:durationInMilliseconds\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"durationInSeconds\": {\n      \"@id\": \"roku:durationInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"episodeInfo\": {\n      \"@id\": \"roku:episodeInfo\",\n      \"@type\": \"@id\"\n    },\n    \"episodeNumber\": {\n      \"@id\": \"roku:episodeNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"externalIdSource\": {\n      \"@id\": \"roku:externalIdSource\"\n    },\n    \"externalIds\": {\n      \"@id\": \"roku:externalIds\",\n      \"@container\": \"@set\"\n    },\n    \"genres\": {\n      \"@id\": \"roku:genres\",\n      \"@container\": \"@set\"\n    },\n    \"id\": {\n      \"@id\": \"roku:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageUrl\": {\n      \"@id\": \"roku:imageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"images\": {\n      \"@id\": \"roku:images\",\n      \"@container\": \"@set\"\n    },\n    \"isOriginal\": {\n      \"@id\": \"roku:isOriginal\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"linearEvents\": {\n      \"@id\": \"roku:linearEvents\",\n      \"@container\": \"@set\"\n    },\n    \"longDescriptions\": {\n      \"@id\": \"roku:longDescriptions\",\n      \"@container\": \"@set\"\n    },\n    \"media\": {\n      \"@id\": \"roku:media\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"nextPageUrl\": {\n      \"@id\": \"roku:nextPageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playOptions\": {\n      \"@id\": \"roku:playOptions\",\n      \"@container\": \"@set\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"roku:releaseDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"releaseYear\": {\n      \"@id\": \"roku:releaseYear\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"role\": {\n      \"@id\": \"roku:role\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"seasonInfo\": {\n      \"@id\": \"roku:seasonInfo\",\n      \"@type\": \"@id\"\n    },\n    \"seasonNumber\": {\n      \"@id\": \"roku:seasonNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"seriesId\": {\n      \"@id\": \"roku:seriesId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shortDescriptions\": {\n      \"@id\": \"roku:shortDescriptions\",\n      \"@container\": \"@set\"\n    },\n    \"tags\": {\n      \"@id\": \"roku:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"titles\": {\n      \"@id\": \"roku:titles\",\n      \"@container\": \"@set\"\n    },\n    \"type\": {\n      \"@id\": \"roku:type\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roku/refs/heads/main/json-ld/roku-search-feed-context.jsonld
tags:
- Streaming
- Television
- Media
- Entertainment
- Connected TV
- Consumer Electronics
- JSON-LD
- Linked Data
- Semantic Web
---
