---
class_count: 5
classes:
- LearnerReference
- LearningObjectReference
- WebhookEventBase
- name
- email
context_file: json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Adobe Captivate Learning Manager Webhooks from Adobe Captivate.
layout: jsonld
name: Adobe Captivate Learning Manager Webhooks Context
namespaces:
- prefix: alm
  uri: https://learningmanager.adobe.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: userId
  type: string
- container: ''
  name: loId
  type: string
- container: ''
  name: loType
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventId
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: timestamp
  type: dateTime
- container: ''
  name: source
  type: string
property_count: 9
provider_name: Adobe Captivate
provider_slug: adobe-captivate
slug: adobe-captivate-learning-manager-webhooks-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alm\": \"https://learningmanager.adobe.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"LearnerReference\": \"alm:LearnerReference\",\n    \"LearningObjectReference\": \"alm:LearningObjectReference\",\n    \"WebhookEventBase\": \"alm:WebhookEventBase\",\n    \"userId\": {\n      \"@id\": \"alm:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"email\": \"schema:email\",\n    \"loId\": {\n      \"@id\": \"alm:loId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loType\": {\n      \"@id\": \"alm:loType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"alm:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"alm:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventId\": {\n      \"\
  @id\": \"alm:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"alm:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"alm:timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"source\": {\n      \"@id\": \"alm:source\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/adobe-captivate/refs/heads/main/json-ld/adobe-captivate-learning-manager-webhooks-context.jsonld
tags:
- Authoring
- Education
- eLearning
- LMS
- SCORM
- Training
- xAPI
- JSON-LD
- Linked Data
- Semantic Web
---
