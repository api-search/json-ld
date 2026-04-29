---
class_count: 3
classes:
- Amplitude Experiment
- name
- description
context_file: json-ld/amplitude-amplitude-experiment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-amplitude-experiment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Amplitude Experiment from Amplitude.
layout: jsonld
name: Amplitude Amplitude Experiment Context
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
  name: projectId
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: evaluationMode
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: bucketingKey
  type: string
- container: ''
  name: bucketingSalt
  type: string
- container: set
  name: variants
  type: string
- container: set
  name: segments
  type: string
- container: set
  name: deployments
  type: string
- container: ''
  name: rolledOutVariant
  type: string
- container: ''
  name: startDate
  type: dateTime
- container: ''
  name: endDate
  type: dateTime
property_count: 15
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-amplitude-experiment-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Amplitude Experiment\": \"amplitude:Amplitude Experiment\",\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"amplitude:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amplitude:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\": {\n      \"@id\": \"amplitude:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"amplitude:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"evaluationMode\": {\n      \"@id\": \"amplitude:evaluationMode\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"state\": {\n      \"@id\": \"amplitude:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketingKey\": {\n      \"@id\": \"amplitude:bucketingKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketingSalt\": {\n      \"@id\": \"amplitude:bucketingSalt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variants\": {\n      \"@id\": \"amplitude:variants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segments\": {\n      \"@id\": \"amplitude:segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deployments\": {\n      \"@id\": \"amplitude:deployments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rolledOutVariant\": {\n      \"@id\": \"amplitude:rolledOutVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"amplitude:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"amplitude:endDate\"\
  ,\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-amplitude-experiment-context.jsonld
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
