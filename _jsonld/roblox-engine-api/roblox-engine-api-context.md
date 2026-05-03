---
api_specs:
- filename: openapi
  format: yaml
  label: Roblox Open Cloud API
  slug: roblox-open-cloud-api
  spec_type: OpenAPI
  url: https://create.roblox.com/docs/cloud/reference/openapi
class_count: 30
classes:
- Universe
- id
- displayName
- description
- visibility
- createTime
- updateTime
- Place
- serverSize
- User
- name
- premium
- idVerified
- locale
- about
- Group
- memberCount
- publicEntryAllowed
- locked
- verified
- DataStore
- entryKey
- UserRestriction
- active
- duration
- displayReason
- Asset
- assetType
- Message
- topic
context_file: json-ld/roblox-engine-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-ld/roblox-engine-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Roblox Engine Api from Roblox Engine API.
layout: jsonld
name: Roblox Engine Api Context
namespaces:
- prefix: roblox
  uri: https://api-evangelist.github.io/roblox-engine-api/vocab#
properties: []
property_count: 0
provider_name: Roblox Engine API
provider_slug: roblox-engine-api
slug: roblox-engine-api-context
source_filename: roblox-engine-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"roblox\": \"https://api-evangelist.github.io/roblox-engine-api/vocab#\",\n    \"Universe\": \"schema:VideoGame\",\n    \"id\": \"schema:identifier\",\n    \"displayName\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"visibility\": \"roblox:visibility\",\n    \"createTime\": \"schema:dateCreated\",\n    \"updateTime\": \"schema:dateModified\",\n    \"Place\": \"roblox:Place\",\n    \"serverSize\": \"roblox:serverSize\",\n    \"User\": \"schema:Person\",\n    \"name\": \"schema:alternateName\",\n    \"premium\": \"roblox:premiumMember\",\n    \"idVerified\": \"roblox:identityVerified\",\n    \"locale\": \"schema:inLanguage\",\n    \"about\": \"schema:description\",\n    \"Group\": \"schema:Organization\",\n    \"memberCount\": \"schema:numberOfEmployees\",\n    \"publicEntryAllowed\": \"roblox:publicEntryAllowed\",\n    \"locked\": \"roblox:locked\",\n    \"verified\": \"roblox:verified\"\
  ,\n    \"DataStore\": \"roblox:DataStore\",\n    \"entryKey\": \"roblox:entryKey\",\n    \"UserRestriction\": \"roblox:UserRestriction\",\n    \"active\": \"roblox:restrictionActive\",\n    \"duration\": \"schema:duration\",\n    \"displayReason\": \"roblox:displayReason\",\n    \"Asset\": \"schema:CreativeWork\",\n    \"assetType\": \"schema:encodingFormat\",\n    \"Message\": \"schema:Message\",\n    \"topic\": \"schema:about\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/roblox-engine-api/refs/heads/main/json-ld/roblox-engine-api-context.jsonld
tags:
- Gaming
- Game Development
- Metaverse
- Roblox
- Open Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
