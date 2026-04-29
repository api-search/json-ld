---
class_count: 4
classes:
- EvaluationResponse
- EvaluationRequest
- Variant
- FlagConfiguration
context_file: json-ld/amplitude-experiment-evaluation-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-experiment-evaluation-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Experiment Evaluation Api from Amplitude.
layout: jsonld
name: Amplitude Experiment Evaluation Api Context
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
  name: userId
  type: string
- container: ''
  name: deviceId
  type: string
- container: ''
  name: userProperties
  type: reference
- container: ''
  name: groups
  type: reference
- container: ''
  name: groupProperties
  type: reference
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: metadata
  type: reference
- container: ''
  name: experimentKey
  type: string
- container: ''
  name: flagType
  type: string
- container: ''
  name: flagVersion
  type: integer
- container: ''
  name: default
  type: boolean
- container: ''
  name: deployed
  type: boolean
- container: ''
  name: evaluationMode
  type: string
- container: set
  name: segments
  type: reference
- container: set
  name: conditions
  type: reference
- container: ''
  name: variant
  type: string
- container: ''
  name: variants
  type: reference
property_count: 19
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-experiment-evaluation-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EvaluationResponse\": \"amplitude:EvaluationResponse\",\n    \"EvaluationRequest\": \"amplitude:EvaluationRequest\",\n    \"Variant\": \"amplitude:Variant\",\n    \"FlagConfiguration\": \"amplitude:FlagConfiguration\",\n    \"userId\": {\n      \"@id\": \"amplitude:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceId\": {\n      \"@id\": \"amplitude:device_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProperties\": {\n      \"@id\": \"amplitude:user_properties\",\n      \"@type\": \"@id\"\n    },\n    \"groups\": {\n      \"@id\": \"amplitude:groups\",\n      \"@type\": \"@id\"\n    },\n    \"groupProperties\": {\n      \"@id\": \"amplitude:group_properties\",\n      \"@type\": \"@id\"\n    },\n    \"\
  key\": {\n      \"@id\": \"amplitude:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amplitude:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"amplitude:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amplitude:metadata\",\n      \"@type\": \"@id\"\n    },\n    \"experimentKey\": {\n      \"@id\": \"amplitude:experimentKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flagType\": {\n      \"@id\": \"amplitude:flagType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flagVersion\": {\n      \"@id\": \"amplitude:flagVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"default\": {\n      \"@id\": \"amplitude:default\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deployed\": {\n      \"@id\": \"amplitude:deployed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"evaluationMode\": {\n      \"@id\": \"amplitude:evaluationMode\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"segments\": {\n      \"@id\": \"amplitude:segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"conditions\": {\n      \"@id\": \"amplitude:conditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"variant\": {\n      \"@id\": \"amplitude:variant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variants\": {\n      \"@id\": \"amplitude:variants\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-experiment-evaluation-api-context.jsonld
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
