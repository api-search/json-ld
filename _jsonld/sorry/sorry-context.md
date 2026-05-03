---
api_specs:
- filename: sorry-status-page-openapi.yml
  format: yaml
  label: Sorry Status Page API
  slug: sorry-status-page-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/openapi/sorry-status-page-openapi.yml
class_count: 6
classes:
- StatusPage
- Component
- Notice
- NoticeUpdate
- Subscriber
- id
context_file: json-ld/sorry-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/json-ld/sorry-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Sorry from Sorry.
layout: jsonld
name: Sorry Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: sorry
  uri: https://docs.sorryapp.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: support_email
  type: string
- container: ''
  name: support_url
  type: reference
- container: ''
  name: locale
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: synopsis
  type: string
- container: ''
  name: link
  type: reference
- container: ''
  name: began_at
  type: dateTime
- container: ''
  name: ended_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: email
  type: string
- container: ''
  name: content
  type: string
property_count: 16
provider_name: Sorry
provider_slug: sorry
slug: sorry-context
source_filename: sorry-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"sorry\": \"https://docs.sorryapp.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"StatusPage\": \"sorry:StatusPage\",\n    \"Component\": \"sorry:Component\",\n    \"Notice\": \"sorry:Notice\",\n    \"NoticeUpdate\": \"sorry:NoticeUpdate\",\n    \"Subscriber\": \"schema:Person\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"sorry:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"sorry:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"support_email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"support_url\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"locale\": {\n      \"@id\": \"schema:inLanguage\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"type\": {\n      \"@id\": \"sorry:noticeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"schema:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"synopsis\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"link\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"@id\"\n    },\n    \"began_at\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ended_at\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"schema:text\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/sorry/refs/heads/main/json-ld/sorry-context.jsonld
tags:
- Status Pages
- Incident Management
- Developer Tools
- Monitoring
- Notifications
- JSON-LD
- Linked Data
- Semantic Web
---
