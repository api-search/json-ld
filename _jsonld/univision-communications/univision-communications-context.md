---
class_count: 24
classes:
- TelevisaUnivision
- MediaCompany
- StreamingService
- BroadcastNetwork
- RadioStation
- TelevisionChannel
- AdvertisingPlatform
- ContentPlatform
- name
- description
- url
- identifier
- language
- audience
- creator
- publisher
- contentRating
- genre
- duration
- episodeNumber
- seasonNumber
- videoFormat
- bitrate
- encodingFormat
context_file: json-ld/univision-communications-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/univision-communications/refs/heads/main/json-ld/univision-communications-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Univision Communications from TelevisaUnivision (Univision Communications).
layout: jsonld
name: Univision Communications Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tu
  uri: https://corporate.televisaunivision.com/ontology#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: vix
  type: schema:StreamingService
- container: ''
  name: uforia
  type: schema:AudioObject
- container: ''
  name: univision
  type: schema:BroadcastChannel
- container: ''
  name: tudn
  type: schema:BroadcastChannel
- container: ''
  name: galavision
  type: schema:BroadcastChannel
- container: ''
  name: unimas
  type: schema:BroadcastChannel
- container: ''
  name: dateCreated
  type: date
- container: ''
  name: dateModified
  type: date
- container: ''
  name: advertiser
  type: schema:Organization
- container: ''
  name: adFormat
  type: string
- container: ''
  name: adSegment
  type: string
- container: ''
  name: householdGraph
  type: schema:Dataset
- container: ''
  name: turnkeySegment
  type: schema:Audience
- container: ''
  name: cleanRoom
  type: schema:Service
- container: ''
  name: programmatic
  type: boolean
- container: ''
  name: addressable
  type: boolean
- container: ''
  name: ctvInventory
  type: schema:Offer
- container: ''
  name: hispanicAudience
  type: schema:Audience
- container: ''
  name: bilingualAudience
  type: schema:Audience
- container: ''
  name: spanishLanguage
  type: string
- container: ''
  name: isFreeToWatch
  type: boolean
- container: ''
  name: subscriptionRequired
  type: boolean
- container: ''
  name: adSupported
  type: boolean
- container: ''
  name: fastChannel
  type: boolean
- container: ''
  name: broadcastNetwork
  type: schema:BroadcastChannel
- container: ''
  name: stationCount
  type: integer
- container: ''
  name: radioStationCount
  type: integer
property_count: 27
provider_name: TelevisaUnivision (Univision Communications)
provider_slug: univision-communications
slug: univision-communications-context
source_filename: univision-communications-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tu\": \"https://corporate.televisaunivision.com/ontology#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"TelevisaUnivision\": \"schema:Organization\",\n    \"MediaCompany\": \"schema:MediaOrganization\",\n    \"StreamingService\": \"schema:StreamingService\",\n    \"BroadcastNetwork\": \"schema:BroadcastChannel\",\n    \"RadioStation\": \"schema:RadioStation\",\n    \"TelevisionChannel\": \"schema:TelevisionChannel\",\n    \"AdvertisingPlatform\": \"schema:Service\",\n    \"ContentPlatform\": \"schema:SoftwareApplication\",\n\n    \"vix\": {\n      \"@id\": \"tu:vix\",\n      \"@type\": \"schema:StreamingService\"\n    },\n    \"uforia\": {\n      \"@id\": \"tu:uforia\",\n      \"@type\": \"schema:AudioObject\"\n    },\n    \"univision\": {\n      \"@id\": \"tu:univision\",\n      \"@type\": \"schema:BroadcastChannel\"\n    },\n    \"tudn\": {\n      \"@id\": \"tu:tudn\"\
  ,\n      \"@type\": \"schema:BroadcastChannel\"\n    },\n    \"galavision\": {\n      \"@id\": \"tu:galavision\",\n      \"@type\": \"schema:BroadcastChannel\"\n    },\n    \"unimas\": {\n      \"@id\": \"tu:unimas\",\n      \"@type\": \"schema:BroadcastChannel\"\n    },\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"language\": \"schema:inLanguage\",\n    \"audience\": \"schema:audience\",\n    \"creator\": \"schema:creator\",\n    \"publisher\": \"schema:publisher\",\n    \"dateCreated\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"contentRating\": \"schema:contentRating\",\n    \"genre\": \"schema:genre\",\n    \"duration\": \"schema:duration\",\n    \"episodeNumber\": \"schema:episodeNumber\",\n    \"seasonNumber\": \"schema:seasonNumber\"\
  ,\n    \"videoFormat\": \"schema:videoFormat\",\n    \"bitrate\": \"schema:bitrate\",\n    \"encodingFormat\": \"schema:encodingFormat\",\n\n    \"advertiser\": {\n      \"@id\": \"schema:advertiser\",\n      \"@type\": \"schema:Organization\"\n    },\n    \"adFormat\": {\n      \"@id\": \"tu:adFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adSegment\": {\n      \"@id\": \"tu:adSegment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"householdGraph\": {\n      \"@id\": \"tu:householdGraph\",\n      \"@type\": \"schema:Dataset\"\n    },\n    \"turnkeySegment\": {\n      \"@id\": \"tu:turnkeySegment\",\n      \"@type\": \"schema:Audience\"\n    },\n    \"cleanRoom\": {\n      \"@id\": \"tu:cleanRoom\",\n      \"@type\": \"schema:Service\"\n    },\n    \"programmatic\": {\n      \"@id\": \"tu:programmatic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"addressable\": {\n      \"@id\": \"tu:addressable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ctvInventory\": {\n\
  \      \"@id\": \"tu:ctvInventory\",\n      \"@type\": \"schema:Offer\"\n    },\n\n    \"hispanicAudience\": {\n      \"@id\": \"tu:hispanicAudience\",\n      \"@type\": \"schema:Audience\"\n    },\n    \"bilingualAudience\": {\n      \"@id\": \"tu:bilingualAudience\",\n      \"@type\": \"schema:Audience\"\n    },\n    \"spanishLanguage\": {\n      \"@id\": \"tu:spanishLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n\n    \"isFreeToWatch\": {\n      \"@id\": \"schema:isFamilyFriendly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"subscriptionRequired\": {\n      \"@id\": \"tu:subscriptionRequired\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"adSupported\": {\n      \"@id\": \"tu:adSupported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"fastChannel\": {\n      \"@id\": \"tu:fastChannel\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"broadcastNetwork\": {\n      \"@id\": \"tu:broadcastNetwork\",\n      \"@type\": \"schema:BroadcastChannel\"\n    },\n    \"stationCount\"\
  : {\n      \"@id\": \"tu:stationCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"radioStationCount\": {\n      \"@id\": \"tu:radioStationCount\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/univision-communications/refs/heads/main/json-ld/univision-communications-context.jsonld
tags:
- Media
- Streaming
- Hispanic
- Advertising
- Television
- Radio
- Content
- JSON-LD
- Linked Data
- Semantic Web
---
