---
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
