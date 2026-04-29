---
api_specs:
- filename: adobe-analytics-api-openapi.yml
  format: yaml
  label: Adobe Analytics 2.0 API
  slug: analytics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-analytics-api-openapi.yml
- filename: adobe-experience-platform-api-openapi.yml
  format: yaml
  label: Adobe Experience Platform API
  slug: experience-platform-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-experience-platform-api-openapi.yml
- filename: adobe-target-api-openapi.yml
  format: yaml
  label: Adobe Target API
  slug: target-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-target-api-openapi.yml
- filename: adobe-journey-optimizer-api-openapi.yml
  format: yaml
  label: Adobe Journey Optimizer API
  slug: journey-optimizer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-journey-optimizer-api-openapi.yml
- filename: adobe-campaign-api-openapi.yml
  format: yaml
  label: Adobe Campaign API
  slug: campaign-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/openapi/adobe-campaign-api-openapi.yml
- filename: adobe-io-events-asyncapi.yml
  format: yaml
  label: Adobe I/O Events
  slug: io-events
  spec_type: AsyncAPI
  url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/asyncapi/adobe-io-events-asyncapi.yml
class_count: 7
classes:
- id
- type
- name
- description
- tags
- owner
- status
context_file: json-ld/adobe-experience-cloud-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Context
namespaces:
- prefix: aep
  uri: https://ns.adobe.com/experience/platform/
- prefix: xdm
  uri: https://ns.adobe.com/xdm/
- prefix: schema
  uri: https://schema.org/
- prefix: adobe
  uri: https://ns.adobe.com/
properties:
- container: ''
  name: Profile
  type: ''
- container: ''
  name: ExperienceEvent
  type: ''
- container: ''
  name: Segment
  type: ''
- container: ''
  name: Journey
  type: ''
- container: ''
  name: Campaign
  type: ''
- container: ''
  name: Offer
  type: ''
- container: ''
  name: Activity
  type: ''
- container: ''
  name: ReportSuite
  type: ''
- container: ''
  name: Dataset
  type: ''
- container: ''
  name: created
  type: schema:DateTime
- container: ''
  name: lastModified
  type: schema:DateTime
property_count: 11
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-context
source_filename: adobe-experience-cloud-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://ns.adobe.com/experience/\",\n    \"aep\": \"https://ns.adobe.com/experience/platform/\",\n    \"xdm\": \"https://ns.adobe.com/xdm/\",\n    \"schema\": \"https://schema.org/\",\n    \"adobe\": \"https://ns.adobe.com/\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"Profile\": {\n      \"@id\": \"xdm:Profile\",\n      \"@context\": {\n        \"profileId\": \"xdm:profileId\",\n        \"identityMap\": \"xdm:identityMap\",\n        \"person\": \"xdm:person\",\n        \"personalEmail\": \"xdm:personalEmail\",\n        \"mobilePhone\": \"xdm:mobilePhone\",\n        \"homeAddress\": \"xdm:homeAddress\",\n        \"segmentMembership\": \"xdm:segmentMembership\",\n        \"consents\": \"xdm:consents\",\n        \"firstName\": \"xdm:firstName\",\n        \"lastName\": \"xdm:lastName\",\n        \"fullName\": \"xdm:fullName\",\n        \"birthDate\": {\n          \"@id\": \"xdm:birthDate\",\n          \"@type\": \"schema:Date\"\
  \n        },\n        \"gender\": \"xdm:gender\",\n        \"address\": {\n          \"@id\": \"schema:address\",\n          \"@type\": \"schema:PostalAddress\"\n        },\n        \"email\": \"schema:email\"\n      }\n    },\n    \"ExperienceEvent\": {\n      \"@id\": \"xdm:ExperienceEvent\",\n      \"@context\": {\n        \"eventId\": \"xdm:eventId\",\n        \"eventType\": \"xdm:eventType\",\n        \"timestamp\": {\n          \"@id\": \"xdm:timestamp\",\n          \"@type\": \"schema:DateTime\"\n        },\n        \"web\": \"xdm:web\",\n        \"commerce\": \"xdm:commerce\",\n        \"device\": \"xdm:device\",\n        \"environment\": \"xdm:environment\"\n      }\n    },\n    \"Segment\": {\n      \"@id\": \"aep:SegmentDefinition\",\n      \"@context\": {\n        \"segmentId\": \"aep:segmentId\",\n        \"expression\": \"aep:segmentExpression\",\n        \"evaluationType\": \"aep:evaluationType\",\n        \"mergePolicyId\": \"aep:mergePolicyId\",\n        \"profileCount\"\
  : \"aep:segmentProfileCount\",\n        \"status\": \"aep:segmentStatus\"\n      }\n    },\n    \"Journey\": {\n      \"@id\": \"adobe:journey/Journey\",\n      \"@context\": {\n        \"journeyId\": \"adobe:journey/journeyId\",\n        \"entryCondition\": \"adobe:journey/entryCondition\",\n        \"activities\": \"adobe:journey/activities\",\n        \"version\": \"adobe:journey/version\",\n        \"status\": \"adobe:journey/status\"\n      }\n    },\n    \"Campaign\": {\n      \"@id\": \"adobe:campaign/Campaign\",\n      \"@context\": {\n        \"campaignId\": \"adobe:campaign/campaignId\",\n        \"channel\": \"adobe:campaign/channel\",\n        \"audience\": \"adobe:campaign/audience\",\n        \"schedule\": \"adobe:campaign/schedule\",\n        \"metrics\": \"adobe:campaign/metrics\"\n      }\n    },\n    \"Offer\": {\n      \"@id\": \"adobe:offer/Offer\",\n      \"@context\": {\n        \"offerId\": \"adobe:offer/offerId\",\n        \"offerType\": \"adobe:offer/offerType\"\
  ,\n        \"representations\": \"adobe:offer/representations\",\n        \"eligibilityRule\": \"adobe:offer/eligibilityRule\",\n        \"priority\": \"adobe:offer/priority\",\n        \"cappingConstraint\": \"adobe:offer/cappingConstraint\"\n      }\n    },\n    \"Activity\": {\n      \"@id\": \"adobe:target/Activity\",\n      \"@context\": {\n        \"activityId\": \"adobe:target/activityId\",\n        \"activityType\": \"adobe:target/activityType\",\n        \"state\": \"adobe:target/state\",\n        \"experiences\": \"adobe:target/experiences\"\n      }\n    },\n    \"ReportSuite\": {\n      \"@id\": \"adobe:analytics/ReportSuite\",\n      \"@context\": {\n        \"rsid\": \"adobe:analytics/rsid\",\n        \"currency\": \"adobe:analytics/currency\",\n        \"timezone\": \"adobe:analytics/timezone\"\n      }\n    },\n    \"Dataset\": {\n      \"@id\": \"aep:Dataset\",\n      \"@context\": {\n        \"datasetId\": \"aep:datasetId\",\n        \"schemaRef\": \"aep:schemaRef\",\n\
  \        \"fileDescription\": \"aep:fileDescription\"\n      }\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"tags\": \"schema:keywords\",\n    \"owner\": \"schema:creator\",\n    \"status\": \"schema:status\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-context.jsonld
tags:
- Analytics
- Customer Experience
- Digital Marketing
- Personalization
- Campaign Management
- Journey Orchestration
- JSON-LD
- Linked Data
- Semantic Web
---
