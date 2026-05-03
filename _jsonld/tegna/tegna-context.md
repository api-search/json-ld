---
api_specs:
- filename: tegna-audience-one-openapi.yml
  format: yaml
  label: TEGNA AudienceOne API
  slug: audience-one-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/openapi/tegna-audience-one-openapi.yml
- filename: tegna-premion-openapi.yml
  format: yaml
  label: TEGNA Premion OTT Advertising API
  slug: premion-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/openapi/tegna-premion-openapi.yml
class_count: 37
classes:
- Campaign
- campaignId
- name
- status
- startDate
- endDate
- budget
- dailyBudget
- targetAudiences
- targetMarkets
- adFormats
- AudienceSegment
- audienceId
- description
- type
- size
- markets
- PerformanceReport
- impressions
- clicks
- ctr
- spend
- completionRate
- reach
- OttCampaign
- targetPlatforms
- impressionGoal
- completionRateTarget
- OttInventory
- platform
- channel
- genre
- cpm
- Market
- marketCode
- stations
- monthlyReach
context_file: json-ld/tegna-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/json-ld/tegna-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Tegna from TEGNA.
layout: jsonld
name: Tegna Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: tegna
  uri: https://www.tegna.com/
- prefix: adtech
  uri: https://www.iab.com/
properties: []
property_count: 0
provider_name: TEGNA
provider_slug: tegna
slug: tegna-context
source_filename: tegna-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"tegna\": \"https://www.tegna.com/\",\n    \"adtech\": \"https://www.iab.com/\",\n\n    \"Campaign\": \"schema:BroadcastEvent\",\n    \"campaignId\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"status\": \"schema:status\",\n    \"startDate\": \"schema:startDate\",\n    \"endDate\": \"schema:endDate\",\n    \"budget\": \"schema:price\",\n    \"dailyBudget\": \"tegna:dailyBudget\",\n    \"targetAudiences\": \"schema:audience\",\n    \"targetMarkets\": \"schema:areaServed\",\n    \"adFormats\": \"schema:encodingFormat\",\n\n    \"AudienceSegment\": \"schema:Audience\",\n    \"audienceId\": \"schema:identifier\",\n    \"description\": \"schema:description\",\n    \"type\": \"schema:additionalType\",\n    \"size\": \"schema:numberOfItems\",\n    \"markets\": \"schema:areaServed\",\n\n    \"PerformanceReport\": \"schema:Report\",\n    \"impressions\": \"adtech:impressions\"\
  ,\n    \"clicks\": \"adtech:clicks\",\n    \"ctr\": \"adtech:clickThroughRate\",\n    \"spend\": \"schema:price\",\n    \"completionRate\": \"adtech:videoCompletionRate\",\n    \"reach\": \"schema:numberOfItems\",\n\n    \"OttCampaign\": \"schema:BroadcastEvent\",\n    \"targetPlatforms\": \"schema:distribution\",\n    \"impressionGoal\": \"adtech:impressionGoal\",\n    \"completionRateTarget\": \"adtech:videoCompletionRate\",\n\n    \"OttInventory\": \"schema:MediaObject\",\n    \"platform\": \"schema:distribution\",\n    \"channel\": \"schema:broadcastChannel\",\n    \"genre\": \"schema:genre\",\n    \"cpm\": \"adtech:cpm\",\n\n    \"Market\": \"schema:Place\",\n    \"marketCode\": \"schema:identifier\",\n    \"stations\": \"schema:subjectOf\",\n    \"monthlyReach\": \"schema:numberOfItems\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/tegna/refs/heads/main/json-ld/tegna-context.jsonld
tags:
- Broadcasting
- Media
- Television
- Digital Advertising
- OTT
- CTV
- Fortune 500
- JSON-LD
- Linked Data
- Semantic Web
---
