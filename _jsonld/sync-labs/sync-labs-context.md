---
api_specs:
- filename: sync-labs-openapi.yml
  format: yaml
  label: Sync Labs API
  slug: sync-labs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/openapi/sync-labs-openapi.yml
class_count: 0
classes: []
context_file: json-ld/sync-labs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/json-ld/sync-labs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sync Labs from Sync Labs.
layout: jsonld
name: Sync Labs Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: synclabs
  uri: https://sync.so/vocab#
properties:
- container: ''
  name: LipSyncGeneration
  type: reference
- container: ''
  name: BatchGeneration
  type: reference
- container: ''
  name: LipSyncModel
  type: reference
- container: ''
  name: MediaAsset
  type: reference
- container: ''
  name: VideoAsset
  type: reference
- container: ''
  name: AudioAsset
  type: reference
- container: ''
  name: DubbingProject
  type: reference
- container: ''
  name: generationId
  type: string
- container: ''
  name: generationStatus
  type: string
- container: ''
  name: modelId
  type: string
- container: ''
  name: videoUrl
  type: reference
- container: ''
  name: audioUrl
  type: reference
- container: ''
  name: outputVideoUrl
  type: reference
- container: ''
  name: durationSeconds
  type: decimal
- container: ''
  name: costUsd
  type: decimal
- container: ''
  name: costPerSecond
  type: decimal
- container: ''
  name: maxFaceResolution
  type: integer
- container: ''
  name: batchId
  type: string
- container: ''
  name: batchSize
  type: integer
- container: ''
  name: webhookUrl
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
property_count: 22
provider_name: Sync Labs
provider_slug: sync-labs
slug: sync-labs-context
source_filename: sync-labs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"synclabs\": \"https://sync.so/vocab#\",\n\n    \"LipSyncGeneration\": {\n      \"@id\": \"synclabs:LipSyncGeneration\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"An AI-powered video lip synchronization job\"\n    },\n    \"BatchGeneration\": {\n      \"@id\": \"synclabs:BatchGeneration\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"synclabs:LipSyncGeneration\" }\n    },\n    \"LipSyncModel\": {\n      \"@id\": \"synclabs:LipSyncModel\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:SoftwareApplication\" }\n    },\n    \"MediaAsset\": {\n      \"@id\": \"synclabs:MediaAsset\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:MediaObject\" }\n    },\n    \"VideoAsset\": {\n      \"@id\": \"synclabs:VideoAsset\",\n      \"@type\": \"@id\",\n\
  \      \"rdfs:subClassOf\": { \"@id\": \"schema:VideoObject\" }\n    },\n    \"AudioAsset\": {\n      \"@id\": \"synclabs:AudioAsset\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:AudioObject\" }\n    },\n    \"DubbingProject\": {\n      \"@id\": \"synclabs:DubbingProject\",\n      \"@type\": \"@id\",\n      \"skos:definition\": \"A content localization project using AI lip-sync technology\"\n    },\n\n    \"generationId\": { \"@id\": \"synclabs:generationId\", \"@type\": \"xsd:string\" },\n    \"generationStatus\": { \"@id\": \"synclabs:generationStatus\", \"@type\": \"xsd:string\" },\n    \"modelId\": { \"@id\": \"synclabs:modelId\", \"@type\": \"xsd:string\" },\n    \"videoUrl\": { \"@id\": \"schema:contentUrl\", \"@type\": \"@id\" },\n    \"audioUrl\": { \"@id\": \"synclabs:audioUrl\", \"@type\": \"@id\" },\n    \"outputVideoUrl\": { \"@id\": \"synclabs:outputVideoUrl\", \"@type\": \"@id\" },\n    \"durationSeconds\": { \"@id\": \"schema:duration\", \"\
  @type\": \"xsd:decimal\" },\n    \"costUsd\": { \"@id\": \"schema:price\", \"@type\": \"xsd:decimal\" },\n    \"costPerSecond\": { \"@id\": \"synclabs:costPerSecond\", \"@type\": \"xsd:decimal\" },\n    \"maxFaceResolution\": { \"@id\": \"synclabs:maxFaceResolution\", \"@type\": \"xsd:integer\" },\n    \"batchId\": { \"@id\": \"synclabs:batchId\", \"@type\": \"xsd:string\" },\n    \"batchSize\": { \"@id\": \"synclabs:batchSize\", \"@type\": \"xsd:integer\" },\n    \"webhookUrl\": { \"@id\": \"synclabs:webhookUrl\", \"@type\": \"@id\" },\n    \"createdAt\": { \"@id\": \"schema:dateCreated\", \"@type\": \"xsd:dateTime\" },\n    \"completedAt\": { \"@id\": \"schema:dateModified\", \"@type\": \"xsd:dateTime\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sync-labs/refs/heads/main/json-ld/sync-labs-context.jsonld
tags:
- Artificial Intelligence
- Content Localization
- Dubbing
- Lip Sync
- Media
- Video
- Visual AI
- JSON-LD
- Linked Data
- Semantic Web
---
