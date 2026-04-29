---
class_count: 14
classes:
- EmailList
- Service
- Email
- TransactionalMessageRequest
- TransactionalMessageResponse
- ServiceList
- ProfileList
- Profile
- WorkflowList
- ServiceInput
- ProfileInput
- Workflow
- name
- email
context_file: json-ld/adobe-experience-cloud-campaign-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-campaign-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Experience Cloud Campaign Api from Adobe Experience Cloud.
layout: jsonld
name: Adobe Experience Cloud Campaign Api Context
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
- container: set
  name: content
  type: string
- container: ''
  name: PKey
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: htmlContent
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: sender
  type: reference
- container: ''
  name: created
  type: dateTime
- container: ''
  name: label
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: ctx
  type: reference
- container: ''
  name: eventId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: birthDate
  type: date
- container: ''
  name: phone
  type: string
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: count
  type: reference
- container: ''
  name: value
  type: integer
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: messageType
  type: string
property_count: 20
provider_name: Adobe Experience Cloud
provider_slug: adobe-experience-cloud
slug: adobe-experience-cloud-campaign-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aec\": \"https://developer.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmailList\": \"aec:EmailList\",\n    \"Service\": \"aec:Service\",\n    \"Email\": \"aec:Email\",\n    \"TransactionalMessageRequest\": \"aec:TransactionalMessageRequest\",\n    \"TransactionalMessageResponse\": \"aec:TransactionalMessageResponse\",\n    \"ServiceList\": \"aec:ServiceList\",\n    \"ProfileList\": \"aec:ProfileList\",\n    \"Profile\": \"aec:Profile\",\n    \"WorkflowList\": \"aec:WorkflowList\",\n    \"ServiceInput\": \"aec:ServiceInput\",\n    \"ProfileInput\": \"aec:ProfileInput\",\n    \"Workflow\": \"aec:Workflow\",\n    \"content\": {\n      \"@id\": \"aec:content\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PKey\": {\n      \"@id\": \"aec:PKey\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"aec:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"htmlContent\": {\n      \"@id\": \"aec:htmlContent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aec:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sender\": {\n      \"@id\": \"aec:sender\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"created\": {\n      \"@id\": \"aec:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"label\": {\n      \"@id\": \"aec:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"aec:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ctx\": {\n      \"@id\": \"aec:ctx\",\n      \"@type\": \"@id\"\n    },\n    \"eventId\": {\n      \"@id\": \"aec:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"aec:firstName\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"lastName\": {\n      \"@id\": \"aec:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"birthDate\": {\n      \"@id\": \"aec:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"phone\": {\n      \"@id\": \"aec:phone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"aec:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"count\": {\n      \"@id\": \"aec:count\",\n      \"@type\": \"@id\"\n    },\n    \"value\": {\n      \"@id\": \"aec:value\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startDate\": {\n      \"@id\": \"aec:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"messageType\": {\n      \"@id\": \"aec:messageType\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-experience-cloud/refs/heads/main/json-ld/adobe-experience-cloud-campaign-api-context.jsonld
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
