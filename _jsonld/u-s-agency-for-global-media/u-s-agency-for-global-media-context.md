---
class_count: 5
classes:
- MediaNetwork
- BroadcastProgram
- InternetFreedomProject
- PressFreedomReport
- AudienceResearch
context_file: json-ld/u-s-agency-for-global-media-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/u-s-agency-for-global-media/refs/heads/main/json-ld/u-s-agency-for-global-media-context.jsonld
description: JSON-LD context defining the semantic vocabulary for U S Agency For Global Media from U.S. Agency for Global Media.
layout: jsonld
name: U S Agency For Global Media Context
namespaces:
- prefix: usagm
  uri: https://www.usagm.gov/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: url
  type: reference
- container: ''
  name: repositoryUrl
  type: reference
- container: set
  name: languages
  type: string
- container: set
  name: targetRegions
  type: string
- container: ''
  name: weeklyReach
  type: integer
- container: ''
  name: broadcastHours
  type: integer
- container: ''
  name: language
  type: string
- container: ''
  name: network
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: frequency
  type: string
- container: ''
  name: fundingAmount
  type: decimal
- container: ''
  name: status
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: datePublished
  type: date
- container: ''
  name: version
  type: string
property_count: 19
provider_name: U.S. Agency for Global Media
provider_slug: u-s-agency-for-global-media
slug: u-s-agency-for-global-media-context
source_filename: u-s-agency-for-global-media-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"usagm\": \"https://www.usagm.gov/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"MediaNetwork\": \"usagm:MediaNetwork\",\n    \"BroadcastProgram\": \"usagm:BroadcastProgram\",\n    \"InternetFreedomProject\": \"usagm:InternetFreedomProject\",\n    \"PressFreedomReport\": \"usagm:PressFreedomReport\",\n    \"AudienceResearch\": \"usagm:AudienceResearch\",\n\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"repositoryUrl\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"@id\"\
  \n    },\n    \"languages\": {\n      \"@id\": \"usagm:languages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetRegions\": {\n      \"@id\": \"usagm:targetRegions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weeklyReach\": {\n      \"@id\": \"usagm:weeklyReach\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"broadcastHours\": {\n      \"@id\": \"usagm:broadcastHours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"language\": {\n      \"@id\": \"dcterms:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"network\": {\n      \"@id\": \"usagm:network\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"usagm:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequency\": {\n      \"@id\": \"usagm:frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fundingAmount\": {\n      \"@id\": \"usagm:fundingAmount\",\n      \"@type\": \"xsd:decimal\"\n    },\n\
  \    \"status\": {\n      \"@id\": \"usagm:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"dcterms:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"dcterms:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"datePublished\": {\n      \"@id\": \"schema:datePublished\",\n      \"@type\": \"xsd:date\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/u-s-agency-for-global-media/refs/heads/main/json-ld/u-s-agency-for-global-media-context.jsonld
tags:
- Federal Government
- Media
- Broadcasting
- International
- Press Freedom
- Internet Freedom
- JSON-LD
- Linked Data
- Semantic Web
---
