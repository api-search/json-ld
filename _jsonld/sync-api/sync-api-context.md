---
class_count: 0
classes: []
context_file: json-ld/sync-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sync-api/refs/heads/main/json-ld/sync-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sync Api from Sync API.
layout: jsonld
name: Sync Api Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: syncapi
  uri: https://sync-api.com/vocab#
- prefix: iab
  uri: https://www.iab.com/vocab#
properties:
- container: ''
  name: AdvertisingCampaign
  type: reference
- container: ''
  name: BidRequest
  type: reference
- container: ''
  name: BidResponse
  type: reference
- container: ''
  name: AdImpression
  type: reference
- container: ''
  name: MobileApp
  type: reference
- container: ''
  name: Audience
  type: reference
- container: ''
  name: UserAcquisitionCampaign
  type: reference
- container: ''
  name: ReEngagementCampaign
  type: reference
- container: ''
  name: InAppEvent
  type: reference
- container: ''
  name: campaignId
  type: string
- container: ''
  name: campaignName
  type: string
- container: ''
  name: bidPrice
  type: decimal
- container: ''
  name: winRate
  type: decimal
- container: ''
  name: lifetimeValue
  type: decimal
- container: ''
  name: costPerInstall
  type: decimal
- container: ''
  name: returnOnAdSpend
  type: decimal
- container: ''
  name: impressionCount
  type: integer
- container: ''
  name: clickCount
  type: integer
- container: ''
  name: installCount
  type: integer
- container: ''
  name: audienceSize
  type: integer
- container: ''
  name: targetCountry
  type: string
- container: ''
  name: targetOs
  type: string
- container: ''
  name: bundleId
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: eventRevenue
  type: decimal
property_count: 25
provider_name: Sync API
provider_slug: sync-api
slug: sync-api-context
source_filename: sync-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"syncapi\": \"https://sync-api.com/vocab#\",\n    \"iab\": \"https://www.iab.com/vocab#\",\n\n    \"AdvertisingCampaign\": {\n      \"@id\": \"syncapi:AdvertisingCampaign\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:MarketingAction\" }\n    },\n    \"BidRequest\": {\n      \"@id\": \"iab:BidRequest\",\n      \"@type\": \"@id\"\n    },\n    \"BidResponse\": {\n      \"@id\": \"iab:BidResponse\",\n      \"@type\": \"@id\"\n    },\n    \"AdImpression\": {\n      \"@id\": \"syncapi:AdImpression\",\n      \"@type\": \"@id\"\n    },\n    \"MobileApp\": {\n      \"@id\": \"syncapi:MobileApp\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"schema:MobileApplication\" }\n    },\n    \"Audience\": {\n      \"@id\": \"syncapi:Audience\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\"\
  : { \"@id\": \"schema:Audience\" }\n    },\n    \"UserAcquisitionCampaign\": {\n      \"@id\": \"syncapi:UserAcquisitionCampaign\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"syncapi:AdvertisingCampaign\" }\n    },\n    \"ReEngagementCampaign\": {\n      \"@id\": \"syncapi:ReEngagementCampaign\",\n      \"@type\": \"@id\",\n      \"rdfs:subClassOf\": { \"@id\": \"syncapi:AdvertisingCampaign\" }\n    },\n    \"InAppEvent\": {\n      \"@id\": \"syncapi:InAppEvent\",\n      \"@type\": \"@id\"\n    },\n\n    \"campaignId\": { \"@id\": \"syncapi:campaignId\", \"@type\": \"xsd:string\" },\n    \"campaignName\": { \"@id\": \"syncapi:campaignName\", \"@type\": \"xsd:string\" },\n    \"bidPrice\": { \"@id\": \"syncapi:bidPrice\", \"@type\": \"xsd:decimal\" },\n    \"winRate\": { \"@id\": \"syncapi:winRate\", \"@type\": \"xsd:decimal\" },\n    \"lifetimeValue\": { \"@id\": \"syncapi:lifetimeValue\", \"@type\": \"xsd:decimal\" },\n    \"costPerInstall\": { \"@id\": \"syncapi:costPerInstall\"\
  , \"@type\": \"xsd:decimal\" },\n    \"returnOnAdSpend\": { \"@id\": \"syncapi:returnOnAdSpend\", \"@type\": \"xsd:decimal\" },\n    \"impressionCount\": { \"@id\": \"syncapi:impressionCount\", \"@type\": \"xsd:integer\" },\n    \"clickCount\": { \"@id\": \"syncapi:clickCount\", \"@type\": \"xsd:integer\" },\n    \"installCount\": { \"@id\": \"syncapi:installCount\", \"@type\": \"xsd:integer\" },\n    \"audienceSize\": { \"@id\": \"syncapi:audienceSize\", \"@type\": \"xsd:integer\" },\n    \"targetCountry\": { \"@id\": \"syncapi:targetCountry\", \"@type\": \"xsd:string\" },\n    \"targetOs\": { \"@id\": \"syncapi:targetOs\", \"@type\": \"xsd:string\" },\n    \"bundleId\": { \"@id\": \"syncapi:bundleId\", \"@type\": \"xsd:string\" },\n    \"eventName\": { \"@id\": \"syncapi:eventName\", \"@type\": \"xsd:string\" },\n    \"eventRevenue\": { \"@id\": \"syncapi:eventRevenue\", \"@type\": \"xsd:decimal\" }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sync-api/refs/heads/main/json-ld/sync-api-context.jsonld
tags:
- Advertising
- Digital Marketing
- In-App Advertising
- Mobile
- Programmatic
- Real-Time Bidding
- User Acquisition
- JSON-LD
- Linked Data
- Semantic Web
---
