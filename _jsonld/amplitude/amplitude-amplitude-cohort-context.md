---
class_count: 3
classes:
- Amplitude Cohort
- name
- description
context_file: json-ld/amplitude-amplitude-cohort-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-amplitude-cohort-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Amplitude Cohort from Amplitude.
layout: jsonld
name: Amplitude Amplitude Cohort Context
namespaces:
- prefix: amplitude
  uri: https://amplitude.com/schema/
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
  name: size
  type: integer
- container: ''
  name: lastComputed
  type: dateTime
- container: ''
  name: archived
  type: boolean
- container: ''
  name: owner
  type: string
- container: ''
  name: appId
  type: integer
- container: ''
  name: definition
  type: string
property_count: 7
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-amplitude-cohort-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amplitude Cohort\": \"amplitude:Amplitude Cohort\",\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"size\": {\n      \"@id\": \"amplitude:size\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastComputed\": {\n      \"@id\": \"amplitude:lastComputed\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"archived\": {\n      \"@id\": \"amplitude:archived\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"owner\": {\n      \"@id\": \"amplitude:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"amplitude:appId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"definition\"\
  : {\n      \"@id\": \"amplitude:definition\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-amplitude-cohort-context.jsonld
tags:
- A/B Testing
- Analytics
- Experimentation
- Feature Flags
- Product Analytics
- User Behavior
- JSON-LD
- Linked Data
- Semantic Web
---
