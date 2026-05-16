---
api_specs:
- filename: openapi
  format: yaml
  label: Memesio API
  slug: ''
  spec_type: OpenAPI
  url: https://memesio.com/api/openapi
class_count: 35
classes:
- id
- type
- Memesio
- Meme
- Template
- AiJob
- Agent
- ApiKey
- Caption
- OverlayImage
- CanvasConfig
- WatermarkConfig
- name
- description
- slug
- tags
- id_
- text
- fontFamily
- color
- stroke
- textAlign
- sourceTemplateId
- watermark
- agentId
- handle
- displayName
- status
- keyId
- keyPrefix
- scope
- jobId
- workerId
- output
- quota
context_file: json-ld/memesio-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/memesio/refs/heads/main/json-ld/memesio-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Memesio from Memesio.
layout: jsonld
name: Memesio Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: memesio
  uri: https://memesio.com/vocab#
- prefix: dct
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: image
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: imageUrl
  type: reference
- container: ''
  name: thumbnailUrl
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: width
  type: integer
- container: ''
  name: height
  type: integer
- container: set
  name: captions
  type: ''
- container: ''
  name: captionCount
  type: integer
- container: ''
  name: boxCount
  type: integer
- container: ''
  name: fontSize
  type: integer
- container: ''
  name: maxLines
  type: integer
- container: ''
  name: boxWidthPct
  type: decimal
- container: ''
  name: boxHeightPct
  type: decimal
- container: ''
  name: x
  type: decimal
- container: ''
  name: y
  type: decimal
- container: ''
  name: template
  type: reference
- container: set
  name: variants
  type: ''
- container: ''
  name: ownerUserId
  type: reference
- container: ''
  name: approvedAt
  type: dateTime
- container: ''
  name: revokedAt
  type: dateTime
- container: ''
  name: estimatedCostUsd
  type: decimal
- container: ''
  name: page
  type: integer
- container: ''
  name: pageSize
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: nextPage
  type: integer
- container: set
  name: items
  type: ''
- container: ''
  name: remaining
  type: integer
- container: ''
  name: resetAt
  type: dateTime
property_count: 30
provider_name: Memesio
provider_slug: memesio
slug: memesio-context
source_filename: memesio-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"memesio\": \"https://memesio.com/vocab#\",\n    \"dct\": \"http://purl.org/dc/terms/\",\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"Memesio\": \"schema:Organization\",\n    \"Meme\": \"memesio:Meme\",\n    \"Template\": \"memesio:Template\",\n    \"AiJob\": \"memesio:AiJob\",\n    \"Agent\": \"memesio:Agent\",\n    \"ApiKey\": \"memesio:ApiKey\",\n    \"Caption\": \"memesio:Caption\",\n    \"OverlayImage\": \"memesio:OverlayImage\",\n    \"CanvasConfig\": \"memesio:CanvasConfig\",\n    \"WatermarkConfig\": \"memesio:WatermarkConfig\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"image\": { \"@id\": \"schema:image\", \"@type\": \"@id\" },\n    \"url\": { \"@id\": \"schema:url\", \"@type\": \"@id\" },\n    \"imageUrl\": { \"@id\": \"schema:contentUrl\", \"@type\": \"@id\" },\n\
  \    \"thumbnailUrl\": { \"@id\": \"schema:thumbnailUrl\", \"@type\": \"@id\" },\n    \"slug\": \"schema:identifier\",\n    \"tags\": \"schema:keywords\",\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"updatedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" },\n\n    \"id_\": \"schema:identifier\",\n    \"width\": { \"@id\": \"schema:width\", \"@type\": \"xsd:integer\" },\n    \"height\": { \"@id\": \"schema:height\", \"@type\": \"xsd:integer\" },\n\n    \"captions\": { \"@id\": \"memesio:hasCaption\", \"@container\": \"@set\" },\n    \"captionCount\": { \"@id\": \"memesio:captionCount\", \"@type\": \"xsd:integer\" },\n    \"boxCount\": { \"@id\": \"memesio:boxCount\", \"@type\": \"xsd:integer\" },\n    \"text\": \"schema:text\",\n    \"fontSize\": { \"@id\": \"memesio:fontSize\", \"@type\": \"xsd:integer\" },\n    \"fontFamily\": \"memesio:fontFamily\",\n    \"color\": \"schema:color\",\n    \"stroke\": \"memesio:stroke\"\
  ,\n    \"textAlign\": \"memesio:textAlign\",\n    \"maxLines\": { \"@id\": \"memesio:maxLines\", \"@type\": \"xsd:integer\" },\n    \"boxWidthPct\": { \"@id\": \"memesio:boxWidthPct\", \"@type\": \"xsd:decimal\" },\n    \"boxHeightPct\": { \"@id\": \"memesio:boxHeightPct\", \"@type\": \"xsd:decimal\" },\n    \"x\": { \"@id\": \"memesio:positionX\", \"@type\": \"xsd:decimal\" },\n    \"y\": { \"@id\": \"memesio:positionY\", \"@type\": \"xsd:decimal\" },\n\n    \"template\": { \"@id\": \"memesio:template\", \"@type\": \"@id\" },\n    \"sourceTemplateId\": \"schema:isBasedOn\",\n    \"variants\": { \"@id\": \"memesio:variant\", \"@container\": \"@set\" },\n    \"watermark\": \"memesio:watermark\",\n\n    \"agentId\": \"schema:identifier\",\n    \"handle\": \"schema:alternateName\",\n    \"displayName\": \"schema:name\",\n    \"ownerUserId\": { \"@id\": \"memesio:ownedBy\", \"@type\": \"@id\" },\n    \"status\": \"schema:status\",\n    \"approvedAt\": { \"@id\": \"memesio:approvedAt\", \"\
  @type\": \"xsd:dateTime\" },\n\n    \"keyId\": \"schema:identifier\",\n    \"keyPrefix\": \"memesio:keyPrefix\",\n    \"scope\": \"memesio:scope\",\n    \"revokedAt\": { \"@id\": \"memesio:revokedAt\", \"@type\": \"xsd:dateTime\" },\n\n    \"jobId\": \"schema:identifier\",\n    \"workerId\": \"memesio:workerId\",\n    \"estimatedCostUsd\": { \"@id\": \"memesio:estimatedCostUsd\", \"@type\": \"xsd:decimal\" },\n    \"output\": \"schema:result\",\n\n    \"page\": { \"@id\": \"memesio:page\", \"@type\": \"xsd:integer\" },\n    \"pageSize\": { \"@id\": \"memesio:pageSize\", \"@type\": \"xsd:integer\" },\n    \"total\": { \"@id\": \"memesio:total\", \"@type\": \"xsd:integer\" },\n    \"nextPage\": { \"@id\": \"memesio:nextPage\", \"@type\": \"xsd:integer\" },\n    \"items\": { \"@id\": \"memesio:items\", \"@container\": \"@set\" },\n\n    \"quota\": \"memesio:quota\",\n    \"remaining\": { \"@id\": \"memesio:quotaRemaining\", \"@type\": \"xsd:integer\" },\n    \"resetAt\": { \"@id\": \"memesio:quotaResetAt\"\
  , \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/memesio/refs/heads/main/json-ld/memesio-context.jsonld
tags:
- Memes
- Media
- Image Generation
- Content
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
