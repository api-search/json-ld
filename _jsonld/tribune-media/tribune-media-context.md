---
api_specs:
- filename: tms-onconnect-openapi.yml
  format: yaml
  label: TMS OnConnect API
  slug: tms-onconnect
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tribune-media/refs/heads/main/openapi/tms-onconnect-openapi.yml
class_count: 9
classes:
- Program
- Movie
- Episode
- Series
- Airing
- Station
- Lineup
- Theatre
- Celebrity
context_file: json-ld/tribune-media-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tribune-media/refs/heads/main/json-ld/tribune-media-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tribune Media from Tribune Media.
layout: jsonld
name: Tribune Media Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tms
  uri: https://data.tmsapi.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: tmsId
  type: string
- container: ''
  name: rootId
  type: string
- container: ''
  name: seriesId
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: shortDescription
  type: string
- container: ''
  name: entityType
  type: string
- container: ''
  name: subType
  type: string
- container: set
  name: genres
  type: ''
- container: ''
  name: releaseYear
  type: gYear
- container: ''
  name: releaseDate
  type: date
- container: set
  name: ratings
  type: ''
- container: ''
  name: preferredImage
  type: ''
- container: ''
  name: runTime
  type: duration
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: duration
  type: ''
- container: ''
  name: stationId
  type: string
- container: set
  name: qualifiers
  type: ''
- container: ''
  name: lineupId
  type: string
- container: ''
  name: callSign
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: uri
  type: reference
- container: ''
  name: width
  type: ''
- container: ''
  name: height
  type: ''
- container: ''
  name: primary
  type: boolean
- container: ''
  name: category
  type: string
- container: ''
  name: theatreId
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: distance
  type: ''
- container: ''
  name: personId
  type: string
- container: ''
  name: biography
  type: string
- container: ''
  name: birthDate
  type: date
- container: ''
  name: birthPlace
  type: string
- container: ''
  name: sportsId
  type: string
- container: ''
  name: teamBrandId
  type: string
- container: ''
  name: organizationId
  type: string
- container: ''
  name: liveEvent
  type: boolean
property_count: 41
provider_name: Tribune Media
provider_slug: tribune-media
slug: tribune-media-context
source_filename: tribune-media-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tms\": \"https://data.tmsapi.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Program\": \"schema:TVSeries\",\n    \"Movie\": \"schema:Movie\",\n    \"Episode\": \"schema:TVEpisode\",\n    \"Series\": \"schema:TVSeries\",\n    \"Airing\": \"schema:BroadcastEvent\",\n    \"Station\": \"schema:BroadcastService\",\n    \"Lineup\": \"tms:Lineup\",\n    \"Theatre\": \"schema:MovieTheater\",\n    \"Celebrity\": \"schema:Person\",\n\n    \"tmsId\": {\n      \"@id\": \"tms:tmsId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rootId\": {\n      \"@id\": \"tms:rootId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seriesId\": {\n      \"@id\": \"tms:seriesId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"shortDescription\": {\n      \"@id\": \"schema:abstract\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityType\": {\n      \"@id\": \"tms:entityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subType\": {\n      \"@id\": \"tms:subType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"genres\": {\n      \"@id\": \"schema:genre\",\n      \"@container\": \"@set\"\n    },\n    \"releaseYear\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:gYear\"\n    },\n    \"releaseDate\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"ratings\": {\n      \"@id\": \"schema:contentRating\",\n      \"@container\": \"@set\"\n    },\n    \"preferredImage\": {\n      \"@id\": \"schema:image\"\n    },\n    \"runTime\": {\n      \"@id\": \"schema:duration\",\n      \"@type\": \"xsd:duration\"\n    },\n\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\
  \n    },\n    \"endTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"duration\": {\n      \"@id\": \"schema:duration\"\n    },\n    \"stationId\": {\n      \"@id\": \"tms:stationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"qualifiers\": {\n      \"@id\": \"tms:qualifiers\",\n      \"@container\": \"@set\"\n    },\n    \"lineupId\": {\n      \"@id\": \"tms:lineupId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"callSign\": {\n      \"@id\": \"schema:callSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"schema:broadcastChannelId\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"uri\": {\n      \"@id\": \"schema:contentUrl\",\n      \"@type\": \"@id\"\n    },\n    \"width\": {\n      \"@id\": \"schema:width\"\n    },\n    \"height\": {\n      \"@id\": \"schema:height\"\n    },\n    \"primary\": {\n      \"@id\": \"tms:primary\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"category\":\
  \ {\n      \"@id\": \"tms:imageCategory\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"theatreId\": {\n      \"@id\": \"tms:theatreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"schema:streetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"schema:addressLocality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"schema:addressRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"schema:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distance\": {\n      \"@id\": \"schema:distance\"\n    },\n\n    \"personId\": {\n      \"@id\": \"tms:personId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"biography\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"birthPlace\": {\n      \"@id\": \"\
  schema:birthPlace\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"sportsId\": {\n      \"@id\": \"tms:sportsId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"teamBrandId\": {\n      \"@id\": \"tms:teamBrandId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationId\": {\n      \"@id\": \"tms:organizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveEvent\": {\n      \"@id\": \"schema:isLiveBroadcast\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tribune-media/refs/heads/main/json-ld/tribune-media-context.jsonld
tags:
- Media
- Entertainment
- Broadcasting
- Television
- Movies
- Sports
- Celebrity
- JSON-LD
- Linked Data
- Semantic Web
---
