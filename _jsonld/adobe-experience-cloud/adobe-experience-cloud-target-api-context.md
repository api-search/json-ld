---
class_count: 15
classes:
- Activity
- ActivityList
- OfferList
- DeliveryRequest
- Offer
- OfferInput
- PropertyList
- AudienceList
- Audience
- AudienceInput
- EnvironmentList
- DeliveryResponse
- ActivityInput
- name
- description
context_file: json-ld/adobe-experience-cloud-target-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-target-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Target Api from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Target Api Context
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
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: modifiedAt
  type: dateTime
- container: ''
  name: startsAt
  type: dateTime
- container: ''
  name: endsAt
  type: dateTime
- container: ''
  name: total
  type: integer
- container: ''
  name: offset
  type: integer
- container: ''
  name: limit
  type: integer
- container: set
  name: activities
  type: string
- container: set
  name: offers
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: context
  type: reference
- container: ''
  name: channel
  type: string
- container: ''
  name: userAgent
  type: string
- container: ''
  name: execute
  type: reference
- container: set
  name: mboxes
  type: string
- container: ''
  name: index
  type: integer
- container: ''
  name: prefetch
  type: reference
- container: set
  name: views
  type: string
- container: set
  name: properties
  type: string
- container: ''
  name: token
  type: string
- container: set
  name: audiences
  type: string
- container: ''
  name: targetRule
  type: reference
- container: set
  name: environments
  type: string
- container: ''
  name: requestId
  type: string
- container: set
  name: options
  type: string
property_count: 28
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-target-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Activity\": \"aec:Activity\",\n    \"ActivityList\": \"aec:ActivityList\",\n    \"OfferList\": \"aec:OfferList\",\n    \"DeliveryRequest\": \"aec:DeliveryRequest\",\n    \"Offer\": \"aec:Offer\",\n    \"OfferInput\": \"aec:OfferInput\",\n    \"PropertyList\": \"aec:PropertyList\",\n    \"AudienceList\": \"aec:AudienceList\",\n    \"Audience\": \"aec:Audience\",\n    \"AudienceInput\": \"aec:AudienceInput\",\n    \"EnvironmentList\": \"aec:EnvironmentList\",\n    \"DeliveryResponse\": \"aec:DeliveryResponse\",\n    \"ActivityInput\": \"aec:ActivityInput\",\n    \"id\": {\n      \"@id\": \"aec:id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": \"schema:name\",\n    \"type\": {\n      \"@id\": \"aec:type\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"aec:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aec:priority\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"modifiedAt\": {\n      \"@id\": \"aec:modifiedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startsAt\": {\n      \"@id\": \"aec:startsAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endsAt\": {\n      \"@id\": \"aec:endsAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"total\": {\n      \"@id\": \"aec:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"offset\": {\n      \"@id\": \"aec:offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"limit\": {\n      \"@id\": \"aec:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activities\": {\n      \"@id\": \"aec:activities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offers\": {\n      \"@id\": \"aec:offers\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"aec:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"context\": {\n      \"@id\": \"aec:context\",\n      \"@type\": \"@id\"\n    },\n    \"channel\": {\n      \"@id\": \"aec:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAgent\": {\n      \"@id\": \"aec:userAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execute\": {\n      \"@id\": \"aec:execute\",\n      \"@type\": \"@id\"\n    },\n    \"mboxes\": {\n      \"@id\": \"aec:mboxes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"aec:index\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"prefetch\": {\n      \"@id\": \"aec:prefetch\",\n      \"@type\": \"@id\"\n    },\n    \"views\": {\n      \"@id\": \"aec:views\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"aec:properties\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"aec:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audiences\": {\n      \"@id\": \"aec:audiences\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"targetRule\": {\n      \"@id\": \"aec:targetRule\",\n      \"@type\": \"@id\"\n    },\n    \"environments\": {\n      \"@id\": \"aec:environments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"aec:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"aec:options\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-target-api-context.jsonld
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
