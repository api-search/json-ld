---
api_specs:
- filename: warner-bros-discovery-content-partner-openapi.yml
  format: yaml
  label: Warner Bros. Discovery Content Partner API
  slug: wbd-content-partner-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/openapi/warner-bros-discovery-content-partner-openapi.yml
class_count: 6
classes:
- ContentDelivery
- MediaAsset
- VideoAsset
- AudioAsset
- SubtitleAsset
- id
context_file: json-ld/warner-bros-discovery-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/json-ld/warner-bros-discovery-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Warner Bros Discovery from Warner Bros. Discovery.
layout: jsonld
name: Warner Bros Discovery Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: wbd
  uri: https://partnerhub.warnermedia.com/#
- prefix: mmc
  uri: http://www.movielabs.com/md/manifest/v1.8#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: title
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: manifestPath
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: filename
  type: string
- container: ''
  name: size
  type: integer
- container: ''
  name: languageCode
  type: string
- container: ''
  name: checksum
  type: string
- container: set
  name: assets
  type: ''
property_count: 11
provider_name: Warner Bros. Discovery
provider_slug: warner-bros-discovery
slug: warner-bros-discovery-context
source_filename: warner-bros-discovery-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"wbd\": \"https://partnerhub.warnermedia.com/#\",\n    \"mmc\": \"http://www.movielabs.com/md/manifest/v1.8#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ContentDelivery\": \"wbd:ContentDelivery\",\n    \"MediaAsset\": \"schema:MediaObject\",\n    \"VideoAsset\": \"schema:VideoObject\",\n    \"AudioAsset\": \"schema:AudioObject\",\n    \"SubtitleAsset\": \"schema:MediaObject\",\n\n    \"id\": \"@id\",\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"schema:additionalType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"wbd:deliveryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestPath\": {\n      \"@id\": \"mmc:manifestLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n\
  \      \"@type\": \"xsd:dateTime\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"filename\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"size\": {\n      \"@id\": \"schema:contentSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"languageCode\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checksum\": {\n      \"@id\": \"wbd:checksum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assets\": {\n      \"@id\": \"schema:associatedMedia\",\n      \"@container\": \"@set\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/warner-bros-discovery/refs/heads/main/json-ld/warner-bros-discovery-context.jsonld
tags:
- Entertainment
- Media
- Streaming
- Content
- Television
- Film
- JSON-LD
- Linked Data
- Semantic Web
---
