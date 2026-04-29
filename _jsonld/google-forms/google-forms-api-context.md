---
class_count: 5
classes:
- Form
- FormResponse
- Watch
- Question
- Item
context_file: json-ld/google-forms-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/google-forms/refs/heads/main/json-ld/google-forms-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Google Forms Api from Google Forms.
layout: jsonld
name: Google Forms Api Context
namespaces:
- prefix: gforms
  uri: https://developers.google.com/forms/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: formId
  type: string
- container: ''
  name: responseId
  type: string
- container: ''
  name: questionId
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: lastSubmittedTime
  type: dateTime
- container: ''
  name: expireTime
  type: dateTime
- container: ''
  name: respondentEmail
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: responderUri
  type: reference
- container: ''
  name: linkedSheetId
  type: string
- container: ''
  name: totalScore
  type: decimal
- container: ''
  name: eventType
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: items
  type: reference
- container: ''
  name: answers
  type: reference
property_count: 17
provider_name: Google Forms
provider_slug: google-forms
slug: google-forms-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"gforms\": \"https://developers.google.com/forms/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Form\": \"gforms:Form\",\n    \"FormResponse\": \"gforms:FormResponse\",\n    \"Watch\": \"gforms:Watch\",\n    \"Question\": \"gforms:Question\",\n    \"Item\": \"gforms:Item\",\n    \"formId\": {\n      \"@id\": \"gforms:formId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responseId\": {\n      \"@id\": \"gforms:responseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questionId\": {\n      \"@id\": \"gforms:questionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"schema:dateCreated\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSubmittedTime\": {\n      \"@id\": \"gforms:lastSubmittedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"expireTime\": {\n      \"@id\": \"gforms:expireTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"respondentEmail\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"gforms:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responderUri\": {\n      \"@id\": \"gforms:responderUri\",\n      \"@type\": \"@id\"\n    },\n    \"linkedSheetId\": {\n      \"@id\": \"gforms:linkedSheetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalScore\": {\n      \"@id\": \"gforms:totalScore\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"eventType\": {\n      \"@id\": \"gforms:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"gforms:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n\
  \      \"@id\": \"gforms:items\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"answers\": {\n      \"@id\": \"gforms:answers\",\n      \"@type\": \"@id\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/google-forms/refs/heads/main/json-ld/google-forms-api-context.jsonld
tags:
- Data Collection
- Forms
- Google
- Google Workspace
- Questionnaires
- Responses
- Surveys
- JSON-LD
- Linked Data
- Semantic Web
---
