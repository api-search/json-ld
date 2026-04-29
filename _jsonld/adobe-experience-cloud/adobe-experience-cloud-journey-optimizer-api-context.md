---
class_count: 27
classes:
- Campaign
- MessageInput
- JourneyList
- Offer
- PlacementList
- CollectionInput
- ContentTemplateList
- CollectionList
- DecisionRuleList
- OfferInput
- JourneyInput
- DecisionRuleInput
- MessageList
- DecisionRule
- Journey
- ContentTemplateInput
- PlacementInput
- Message
- CampaignInput
- OfferList
- Collection
- CampaignList
- ContentTemplate
- Placement
- name
- description
- version
context_file: json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Journey Optimizer Api from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Journey Optimizer Api Context
namespaces:
- prefix: aec
  uri: https://developer.adobe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: id
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: schedule
  type: reference
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
- container: ''
  name: content
  type: reference
- container: set
  name: journeys
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: totalCount
  type: integer
- container: set
  name: representations
  type: string
- container: ''
  name: placement
  type: string
- container: ''
  name: priority
  type: integer
- container: set
  name: placements
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: filter
  type: reference
- container: set
  name: templates
  type: string
- container: set
  name: collections
  type: string
- container: set
  name: decisionRules
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: eligibilityRule
  type: string
- container: ''
  name: entryCondition
  type: reference
- container: set
  name: activities
  type: string
- container: set
  name: messages
  type: string
- container: ''
  name: audienceId
  type: string
- container: set
  name: offers
  type: string
- container: set
  name: campaigns
  type: string
property_count: 28
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-journey-optimizer-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Campaign\": \"aec:Campaign\",\n    \"MessageInput\": \"aec:MessageInput\",\n    \"JourneyList\": \"aec:JourneyList\",\n    \"Offer\": \"aec:Offer\",\n    \"PlacementList\": \"aec:PlacementList\",\n    \"CollectionInput\": \"aec:CollectionInput\",\n    \"ContentTemplateList\": \"aec:ContentTemplateList\",\n    \"CollectionList\": \"aec:CollectionList\",\n    \"DecisionRuleList\": \"aec:DecisionRuleList\",\n    \"OfferInput\": \"aec:OfferInput\",\n    \"JourneyInput\": \"aec:JourneyInput\",\n    \"DecisionRuleInput\": \"aec:DecisionRuleInput\",\n    \"MessageList\": \"aec:MessageList\",\n    \"DecisionRule\": \"aec:DecisionRule\",\n    \"Journey\": \"aec:Journey\",\n    \"ContentTemplateInput\": \"aec:ContentTemplateInput\",\n  \
  \  \"PlacementInput\": \"aec:PlacementInput\",\n    \"Message\": \"aec:Message\",\n    \"CampaignInput\": \"aec:CampaignInput\",\n    \"OfferList\": \"aec:OfferList\",\n    \"Collection\": \"aec:Collection\",\n    \"CampaignList\": \"aec:CampaignList\",\n    \"ContentTemplate\": \"aec:ContentTemplate\",\n    \"Placement\": \"aec:Placement\",\n    \"id\": {\n      \"@id\": \"aec:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"channel\": {\n      \"@id\": \"aec:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aec:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"aec:schedule\",\n      \"@type\": \"@id\"\n    },\n    \"startDate\": {\n      \"@id\": \"aec:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"aec:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"content\": {\n \
  \     \"@id\": \"aec:content\",\n      \"@type\": \"@id\"\n    },\n    \"journeys\": {\n      \"@id\": \"aec:journeys\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"createdAt\": {\n      \"@id\": \"aec:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"aec:modifiedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"totalCount\": {\n      \"@id\": \"aec:totalCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"representations\": {\n      \"@id\": \"aec:representations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"placement\": {\n      \"@id\": \"aec:placement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aec:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"placements\": {\n      \"@id\": \"aec:placements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"contentType\": {\n      \"@id\": \"aec:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"aec:filter\",\n      \"@type\": \"@id\"\n    },\n    \"templates\": {\n      \"@id\": \"aec:templates\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collections\": {\n      \"@id\": \"aec:collections\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"decisionRules\": {\n      \"@id\": \"aec:decisionRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"aec:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eligibilityRule\": {\n      \"@id\": \"aec:eligibilityRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entryCondition\": {\n      \"@id\": \"aec:entryCondition\",\n      \"@type\": \"@id\"\n    },\n    \"activities\": {\n      \"@id\": \"aec:activities\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"messages\": {\n      \"@id\": \"aec:messages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audienceId\": {\n      \"@id\": \"aec:audienceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offers\": {\n      \"@id\": \"aec:offers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaigns\": {\n      \"@id\": \"aec:campaigns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-journey-optimizer-api-context.jsonld
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
