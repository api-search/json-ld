---
api_specs:
- filename: applovin-max-revenue-reporting.yaml
  format: yaml
  label: AppLovin MAX Revenue Reporting API
  slug: applovin-max-revenue-reporting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-max-revenue-reporting.yaml
- filename: applovin-max-ad-unit-management.yaml
  format: yaml
  label: AppLovin MAX Ad Unit Management API
  slug: applovin-max-ad-unit-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-max-ad-unit-management.yaml
- filename: applovin-growth-reporting.yaml
  format: yaml
  label: AppLovin Growth (Axon / AppDiscovery) Reporting API
  slug: applovin-growth-reporting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-growth-reporting.yaml
- filename: applovin-growth-asset-reporting.yaml
  format: yaml
  label: AppLovin Growth Asset Reporting API
  slug: applovin-growth-asset-reporting
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-growth-asset-reporting.yaml
- filename: applovin-axon-campaign-management.yaml
  format: yaml
  label: AppLovin Axon Campaign Management API
  slug: applovin-axon-campaign-management
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-axon-campaign-management.yaml
- filename: applovin-conversion-api-lead-gen.yaml
  format: yaml
  label: AppLovin Conversion API for Lead Generation
  slug: applovin-conversion-api-lead-gen
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/openapi/applovin-conversion-api-lead-gen.yaml
class_count: 50
classes:
- Campaign
- CreativeSet
- CreativeAsset
- AdUnit
- Waterfall
- AdNetworkSetting
- Segment
- Experiment
- TestDevice
- ConversionEvent
- RevenueReportRow
- GrowthReportRow
- AssetReportRow
- id
- name
- description
- platform
- package_name
- itunes_id
- status
- bidding_strategy
- budget
- goal
- goal_type
- tracking
- tracking_method
- targeting
- country_code
- region_codes
- metro_names
- ad_format
- ad_network
- cpm
- ecpm
- impressions
- clicks
- conversions
- ctr
- cost
- revenue
- currency
- value
- user_data
- client_ip_address
- client_user_agent
- email
- phone
- esi
- ifa
- idfv
context_file: json-ld/applovin-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/json-ld/applovin-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Applovin from AppLovin.
layout: jsonld
name: Applovin Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: applovin
  uri: https://github.com/api-evangelist/applovin/vocabulary#
properties:
- container: ''
  name: start_date
  type: schema:DateTime
- container: ''
  name: end_date
  type: schema:DateTime
- container: ''
  name: impression_url
  type: reference
- container: ''
  name: click_url
  type: reference
- container: ''
  name: campaign_id
  type: reference
- container: ''
  name: creative_set_id
  type: reference
- container: ''
  name: asset_id
  type: reference
- container: ''
  name: asset_url
  type: reference
- container: ''
  name: event_time
  type: schema:DateTime
- container: ''
  name: event_source_url
  type: reference
property_count: 10
provider_name: AppLovin
provider_slug: applovin
slug: applovin-context
source_filename: applovin-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"applovin\": \"https://github.com/api-evangelist/applovin/vocabulary#\",\n    \"Campaign\": \"applovin:Campaign\",\n    \"CreativeSet\": \"applovin:CreativeSet\",\n    \"CreativeAsset\": \"applovin:CreativeAsset\",\n    \"AdUnit\": \"applovin:AdUnit\",\n    \"Waterfall\": \"applovin:Waterfall\",\n    \"AdNetworkSetting\": \"applovin:AdNetworkSetting\",\n    \"Segment\": \"applovin:Segment\",\n    \"Experiment\": \"applovin:Experiment\",\n    \"TestDevice\": \"applovin:TestDevice\",\n    \"ConversionEvent\": \"applovin:ConversionEvent\",\n    \"RevenueReportRow\": \"applovin:RevenueReportRow\",\n    \"GrowthReportRow\": \"applovin:GrowthReportRow\",\n    \"AssetReportRow\": \"applovin:AssetReportRow\",\n    \"id\": \"schema:identifier\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"platform\": \"applovin:platform\",\n    \"package_name\": \"applovin:packageName\"\
  ,\n    \"itunes_id\": \"applovin:itunesId\",\n    \"start_date\": {\"@id\": \"schema:startDate\", \"@type\": \"schema:DateTime\"},\n    \"end_date\": {\"@id\": \"schema:endDate\", \"@type\": \"schema:DateTime\"},\n    \"status\": \"schema:actionStatus\",\n    \"bidding_strategy\": \"applovin:biddingStrategy\",\n    \"budget\": \"applovin:budget\",\n    \"goal\": \"applovin:goal\",\n    \"goal_type\": \"applovin:goalType\",\n    \"tracking\": \"applovin:tracking\",\n    \"tracking_method\": \"applovin:trackingMethod\",\n    \"impression_url\": {\"@id\": \"applovin:impressionUrl\", \"@type\": \"@id\"},\n    \"click_url\": {\"@id\": \"applovin:clickUrl\", \"@type\": \"@id\"},\n    \"targeting\": \"applovin:targeting\",\n    \"country_code\": \"schema:addressCountry\",\n    \"region_codes\": \"schema:addressRegion\",\n    \"metro_names\": \"applovin:metroNames\",\n    \"ad_format\": \"applovin:adFormat\",\n    \"ad_network\": \"applovin:adNetwork\",\n    \"cpm\": \"applovin:cpm\",\n    \"\
  ecpm\": \"applovin:ecpm\",\n    \"campaign_id\": {\"@id\": \"applovin:campaignId\", \"@type\": \"@id\"},\n    \"creative_set_id\": {\"@id\": \"applovin:creativeSetId\", \"@type\": \"@id\"},\n    \"asset_id\": {\"@id\": \"applovin:assetId\", \"@type\": \"@id\"},\n    \"asset_url\": {\"@id\": \"applovin:assetUrl\", \"@type\": \"@id\"},\n    \"impressions\": \"applovin:impressions\",\n    \"clicks\": \"applovin:clicks\",\n    \"conversions\": \"applovin:conversions\",\n    \"ctr\": \"applovin:ctr\",\n    \"cost\": \"applovin:cost\",\n    \"revenue\": \"applovin:revenue\",\n    \"currency\": \"schema:priceCurrency\",\n    \"value\": \"schema:price\",\n    \"event_time\": {\"@id\": \"schema:dateCreated\", \"@type\": \"schema:DateTime\"},\n    \"event_source_url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"user_data\": \"applovin:userData\",\n    \"client_ip_address\": \"applovin:clientIpAddress\",\n    \"client_user_agent\": \"applovin:clientUserAgent\",\n    \"email\": \"schema:email\"\
  ,\n    \"phone\": \"schema:telephone\",\n    \"esi\": \"applovin:eventSourceIndicator\",\n    \"ifa\": \"applovin:idForAdvertisers\",\n    \"idfv\": \"applovin:idForVendors\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/applovin/refs/heads/main/json-ld/applovin-context.jsonld
tags:
- Advertising
- Mobile
- AdTech
- App Monetization
- Mediation
- User Acquisition
- Marketing Technology
- Conversion Tracking
- JSON-LD
- Linked Data
- Semantic Web
---
