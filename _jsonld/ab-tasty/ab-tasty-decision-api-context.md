---
class_count: 13
classes:
- ActivationRequest
- BatchActivationItem
- BatchActivationRequest
- Campaign
- CampaignRequest
- CampaignResponseFull
- CampaignResponseNormal
- CampaignResponseSimple
- CampaignVariation
- Flag
- FlagMetadata
- FlagsResponse
- SingleCampaignRequest
context_file: json-ld/ab-tasty-decision-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-ld/ab-tasty-decision-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ab Tasty Decision Api from AB Tasty.
layout: jsonld
name: Ab Tasty Decision Api Context
namespaces:
- prefix: abt
  uri: https://abtasty.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: visitorId
  type: string
- container: ''
  name: anonymousId
  type: string
- container: ''
  name: context
  type: ''
- container: ''
  name: visitorConsent
  type: boolean
- container: ''
  name: triggerHit
  type: boolean
- container: ''
  name: decisionGroup
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: variationGroupId
  type: string
- container: ''
  name: variation
  type: ''
- container: ''
  name: campaignId
  type: string
- container: ''
  name: variationId
  type: string
- container: set
  name: campaigns
  type: ''
- container: ''
  name: value
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: vid
  type: string
- container: ''
  name: aid
  type: string
- container: ''
  name: cid
  type: string
- container: ''
  name: caid
  type: string
- container: ''
  name: vaid
  type: string
- container: set
  name: batch
  type: ''
- container: set
  name: campaignsVariation
  type: ''
- container: ''
  name: mergedModifications
  type: ''
- container: ''
  name: qt
  type: integer
- container: ''
  name: campaignName
  type: string
- container: ''
  name: slug
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: variationGroupName
  type: string
- container: ''
  name: variationName
  type: string
- container: ''
  name: reference
  type: boolean
property_count: 29
provider_name: AB Tasty
provider_slug: ab-tasty
slug: ab-tasty-decision-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"abt\": \"https://abtasty.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ActivationRequest\": \"abt:ActivationRequest\",\n    \"BatchActivationItem\": \"abt:BatchActivationItem\",\n    \"BatchActivationRequest\": \"abt:BatchActivationRequest\",\n    \"Campaign\": \"abt:Campaign\",\n    \"CampaignRequest\": \"abt:CampaignRequest\",\n    \"CampaignResponseFull\": \"abt:CampaignResponseFull\",\n    \"CampaignResponseNormal\": \"abt:CampaignResponseNormal\",\n    \"CampaignResponseSimple\": \"abt:CampaignResponseSimple\",\n    \"CampaignVariation\": \"abt:CampaignVariation\",\n    \"Flag\": \"abt:Flag\",\n    \"FlagMetadata\": \"abt:FlagMetadata\",\n    \"FlagsResponse\": \"abt:FlagsResponse\",\n    \"SingleCampaignRequest\": \"abt:SingleCampaignRequest\",\n    \"visitorId\": {\n      \"@id\": \"abt:visitor_id\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"anonymousId\": {\n      \"@id\": \"abt:anonymous_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"abt:context\"\n    },\n    \"visitorConsent\": {\n      \"@id\": \"abt:visitor_consent\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"triggerHit\": {\n      \"@id\": \"abt:trigger_hit\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"decisionGroup\": {\n      \"@id\": \"abt:decision_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"abt:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variationGroupId\": {\n      \"@id\": \"abt:variationGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variation\": {\n      \"@id\": \"abt:variation\"\n    },\n    \"campaignId\": {\n      \"@id\": \"abt:campaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variationId\": {\n      \"@id\": \"abt:variationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaigns\"\
  : {\n      \"@id\": \"abt:campaigns\",\n      \"@container\": \"@set\"\n    },\n    \"value\": {\n      \"@id\": \"abt:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"abt:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vid\": {\n      \"@id\": \"abt:vid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aid\": {\n      \"@id\": \"abt:aid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cid\": {\n      \"@id\": \"abt:cid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"caid\": {\n      \"@id\": \"abt:caid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vaid\": {\n      \"@id\": \"abt:vaid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"batch\": {\n      \"@id\": \"abt:batch\",\n      \"@container\": \"@set\"\n    },\n    \"campaignsVariation\": {\n      \"@id\": \"abt:campaignsVariation\",\n      \"@container\": \"@set\"\n    },\n    \"mergedModifications\": {\n      \"@id\": \"abt:mergedModifications\"\n    },\n    \"qt\":\
  \ {\n      \"@id\": \"abt:qt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"campaignName\": {\n      \"@id\": \"abt:campaignName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slug\": {\n      \"@id\": \"abt:slug\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"abt:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variationGroupName\": {\n      \"@id\": \"abt:variationGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variationName\": {\n      \"@id\": \"abt:variationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"abt:reference\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ab-tasty/refs/heads/main/json-ld/ab-tasty-decision-api-context.jsonld
tags:
- Aggregation
- Experimentation
- Feature Flags
- Personalization
- A/B Testing
- JSON-LD
- Linked Data
- Semantic Web
---
