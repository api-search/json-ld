---
api_specs:
- filename: google-ads-api-openapi.yml
  format: yaml
  label: Google Ads API
  slug: google-ads-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/openapi/google-ads-api-openapi.yml
class_count: 70
classes:
- Campaign
- AdGroup
- Ad
- AdGroupAd
- AdGroupCriterion
- Keyword
- CampaignBudget
- BiddingStrategy
- ResponsiveSearchAd
- ResponsiveDisplayAd
- Customer
- PerformanceReport
- ConversionAction
- GeoTarget
- AdAsset
- Label
- AdExtension
- Audience
- RemarketingList
- name
- description
- identifier
- dateCreated
- dateModified
- status
- currency
- price
- priceCurrency
- amount
- value
- category
- keywords
- position
- resourceName
- campaignId
- adGroupId
- adId
- customerId
- criterionId
- advertisingChannelType
- advertisingChannelSubType
- biddingStrategyType
- targetRoas
- conversions
- conversionsValue
- ctr
- conversionRate
- costPerConversion
- searchImpressionShare
- interactionRate
- qualityScore
- keywordText
- matchType
- headlines
- descriptions
- finalUrls
- finalMobileUrls
- trackingUrlTemplate
- adType
- adStrength
- device
- adNetworkType
- dayOfWeek
- descriptiveName
- currencyCode
- timeZone
- approvalStatus
- reviewStatus
- deliveryMethod
- optimizationScore
context_file: json-ld/google-ads-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/json-ld/google-ads-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Ads from Google Ads.
layout: jsonld
name: Google Ads Context
namespaces:
- prefix: gads
  uri: https://developers.google.com/google-ads/api/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: url
  type: reference
- container: ''
  name: startDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: image
  type: reference
- container: ''
  name: provider
  type: reference
- container: ''
  name: sponsor
  type: reference
- container: ''
  name: advertiser
  type: reference
- container: ''
  name: audience
  type: reference
- container: ''
  name: offer
  type: reference
- container: ''
  name: campaignBudget
  type: reference
- container: ''
  name: targetCpaMicros
  type: long
- container: ''
  name: cpcBidMicros
  type: long
- container: ''
  name: cpmBidMicros
  type: long
- container: ''
  name: amountMicros
  type: long
- container: ''
  name: costMicros
  type: long
- container: ''
  name: averageCpc
  type: long
- container: ''
  name: impressions
  type: long
- container: ''
  name: clicks
  type: long
- container: ''
  name: viewThroughConversions
  type: long
- container: ''
  name: negative
  type: boolean
- container: ''
  name: targetGoogleSearch
  type: boolean
- container: ''
  name: targetSearchNetwork
  type: boolean
- container: ''
  name: targetContentNetwork
  type: boolean
- container: ''
  name: enhancedCpcEnabled
  type: boolean
- container: ''
  name: date
  type: date
- container: ''
  name: manager
  type: boolean
- container: ''
  name: testAccount
  type: boolean
- container: ''
  name: belongsToCampaign
  type: reference
- container: ''
  name: belongsToAdGroup
  type: reference
- container: ''
  name: belongsToCustomer
  type: reference
- container: ''
  name: hasBudget
  type: reference
- container: ''
  name: hasBiddingStrategy
  type: reference
- container: ''
  name: hasAdGroup
  type: reference
- container: ''
  name: hasAd
  type: reference
- container: ''
  name: hasKeyword
  type: reference
- container: ''
  name: hasLabel
  type: reference
property_count: 36
provider_name: Google Ads
provider_slug: google-ads
slug: google-ads-context
source_filename: google-ads-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gads\": \"https://developers.google.com/google-ads/api/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Campaign\": \"gads:Campaign\",\n    \"AdGroup\": \"gads:AdGroup\",\n    \"Ad\": \"gads:Ad\",\n    \"AdGroupAd\": \"gads:AdGroupAd\",\n    \"AdGroupCriterion\": \"gads:AdGroupCriterion\",\n    \"Keyword\": \"gads:Keyword\",\n    \"CampaignBudget\": \"gads:CampaignBudget\",\n    \"BiddingStrategy\": \"gads:BiddingStrategy\",\n    \"ResponsiveSearchAd\": \"gads:ResponsiveSearchAd\",\n    \"ResponsiveDisplayAd\": \"gads:ResponsiveDisplayAd\",\n    \"Customer\": \"gads:Customer\",\n    \"PerformanceReport\": \"gads:PerformanceReport\",\n    \"ConversionAction\": \"gads:ConversionAction\",\n    \"GeoTarget\": \"gads:GeoTarget\",\n    \"AdAsset\": \"gads:AdAsset\",\n    \"Label\": \"gads:Label\",\n    \"AdExtension\": \"gads:AdExtension\",\n    \"Audience\": \"gads:Audience\"\
  ,\n    \"RemarketingList\": \"gads:RemarketingList\",\n\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": {\"@id\": \"schema:url\", \"@type\": \"@id\"},\n    \"identifier\": \"schema:identifier\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"startDate\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:date\"},\n    \"endDate\": {\"@id\": \"schema:endDate\", \"@type\": \"xsd:date\"},\n    \"status\": \"schema:creativeWorkStatus\",\n    \"image\": {\"@id\": \"schema:image\", \"@type\": \"@id\"},\n\n    \"provider\": {\"@id\": \"schema:provider\", \"@type\": \"@id\"},\n    \"sponsor\": {\"@id\": \"schema:sponsor\", \"@type\": \"@id\"},\n    \"advertiser\": {\"@id\": \"schema:advertiser\", \"@type\": \"@id\"},\n    \"audience\": {\"@id\": \"schema:audience\", \"@type\": \"@id\"},\n\n    \"currency\": \"schema:currency\",\n    \"price\": \"schema:price\",\n    \"priceCurrency\": \"schema:priceCurrency\"\
  ,\n    \"amount\": \"schema:amount\",\n    \"value\": \"schema:value\",\n\n    \"offer\": {\"@id\": \"schema:offers\", \"@type\": \"@id\"},\n    \"category\": \"schema:category\",\n    \"keywords\": \"schema:keywords\",\n    \"position\": \"schema:position\",\n\n    \"resourceName\": \"gads:resourceName\",\n    \"campaignId\": \"gads:campaignId\",\n    \"adGroupId\": \"gads:adGroupId\",\n    \"adId\": \"gads:adId\",\n    \"customerId\": \"gads:customerId\",\n    \"criterionId\": \"gads:criterionId\",\n\n    \"advertisingChannelType\": \"gads:advertisingChannelType\",\n    \"advertisingChannelSubType\": \"gads:advertisingChannelSubType\",\n    \"biddingStrategyType\": \"gads:biddingStrategyType\",\n    \"campaignBudget\": {\"@id\": \"gads:campaignBudget\", \"@type\": \"@id\"},\n\n    \"targetCpaMicros\": {\"@id\": \"gads:targetCpaMicros\", \"@type\": \"xsd:long\"},\n    \"targetRoas\": \"gads:targetRoas\",\n    \"cpcBidMicros\": {\"@id\": \"gads:cpcBidMicros\", \"@type\": \"xsd:long\"},\n\
  \    \"cpmBidMicros\": {\"@id\": \"gads:cpmBidMicros\", \"@type\": \"xsd:long\"},\n    \"amountMicros\": {\"@id\": \"gads:amountMicros\", \"@type\": \"xsd:long\"},\n    \"costMicros\": {\"@id\": \"gads:costMicros\", \"@type\": \"xsd:long\"},\n    \"averageCpc\": {\"@id\": \"gads:averageCpc\", \"@type\": \"xsd:long\"},\n\n    \"impressions\": {\"@id\": \"gads:impressions\", \"@type\": \"xsd:long\"},\n    \"clicks\": {\"@id\": \"gads:clicks\", \"@type\": \"xsd:long\"},\n    \"conversions\": \"gads:conversions\",\n    \"conversionsValue\": \"gads:conversionsValue\",\n    \"ctr\": \"gads:ctr\",\n    \"conversionRate\": \"gads:conversionRate\",\n    \"costPerConversion\": \"gads:costPerConversion\",\n    \"searchImpressionShare\": \"gads:searchImpressionShare\",\n    \"viewThroughConversions\": {\"@id\": \"gads:viewThroughConversions\", \"@type\": \"xsd:long\"},\n    \"interactionRate\": \"gads:interactionRate\",\n    \"qualityScore\": \"gads:qualityScore\",\n\n    \"keywordText\": \"gads:keywordText\"\
  ,\n    \"matchType\": \"gads:matchType\",\n    \"negative\": {\"@id\": \"gads:negative\", \"@type\": \"xsd:boolean\"},\n\n    \"headlines\": \"gads:headlines\",\n    \"descriptions\": \"gads:descriptions\",\n    \"finalUrls\": \"gads:finalUrls\",\n    \"finalMobileUrls\": \"gads:finalMobileUrls\",\n    \"trackingUrlTemplate\": \"gads:trackingUrlTemplate\",\n    \"adType\": \"gads:adType\",\n    \"adStrength\": \"gads:adStrength\",\n\n    \"targetGoogleSearch\": {\"@id\": \"gads:targetGoogleSearch\", \"@type\": \"xsd:boolean\"},\n    \"targetSearchNetwork\": {\"@id\": \"gads:targetSearchNetwork\", \"@type\": \"xsd:boolean\"},\n    \"targetContentNetwork\": {\"@id\": \"gads:targetContentNetwork\", \"@type\": \"xsd:boolean\"},\n    \"enhancedCpcEnabled\": {\"@id\": \"gads:enhancedCpcEnabled\", \"@type\": \"xsd:boolean\"},\n\n    \"device\": \"gads:device\",\n    \"adNetworkType\": \"gads:adNetworkType\",\n    \"dayOfWeek\": \"gads:dayOfWeek\",\n    \"date\": {\"@id\": \"gads:date\", \"@type\"\
  : \"xsd:date\"},\n\n    \"descriptiveName\": \"gads:descriptiveName\",\n    \"currencyCode\": \"gads:currencyCode\",\n    \"timeZone\": \"gads:timeZone\",\n    \"manager\": {\"@id\": \"gads:manager\", \"@type\": \"xsd:boolean\"},\n    \"testAccount\": {\"@id\": \"gads:testAccount\", \"@type\": \"xsd:boolean\"},\n\n    \"approvalStatus\": \"gads:approvalStatus\",\n    \"reviewStatus\": \"gads:reviewStatus\",\n    \"deliveryMethod\": \"gads:deliveryMethod\",\n    \"optimizationScore\": \"gads:optimizationScore\",\n\n    \"belongsToCampaign\": {\"@id\": \"gads:belongsToCampaign\", \"@type\": \"@id\"},\n    \"belongsToAdGroup\": {\"@id\": \"gads:belongsToAdGroup\", \"@type\": \"@id\"},\n    \"belongsToCustomer\": {\"@id\": \"gads:belongsToCustomer\", \"@type\": \"@id\"},\n    \"hasBudget\": {\"@id\": \"gads:hasBudget\", \"@type\": \"@id\"},\n    \"hasBiddingStrategy\": {\"@id\": \"gads:hasBiddingStrategy\", \"@type\": \"@id\"},\n    \"hasAdGroup\": {\"@id\": \"gads:hasAdGroup\", \"@type\"\
  : \"@id\"},\n    \"hasAd\": {\"@id\": \"gads:hasAd\", \"@type\": \"@id\"},\n    \"hasKeyword\": {\"@id\": \"gads:hasKeyword\", \"@type\": \"@id\"},\n    \"hasLabel\": {\"@id\": \"gads:hasLabel\", \"@type\": \"@id\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-ads/refs/heads/main/json-ld/google-ads-context.jsonld
tags:
- Advertising
- Campaign Management
- Digital Advertising
- Google
- Marketing
- PPC
- JSON-LD
- Linked Data
- Semantic Web
---
