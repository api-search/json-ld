---
class_count: 16
classes:
- Flag
- Segment
- CreateExperimentRequest
- Experiment
- UpdateExperimentRequest
- VersionListResponse
- ExperimentListResponse
- DeploymentListResponse
- VariantConfig
- FlagListResponse
- CreateFlagRequest
- Deployment
- UpdateFlagRequest
- name
- description
- version
context_file: json-ld/amplitude-experiment-management-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-experiment-management-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amplitude Experiment Management Api from Amplitude.
layout: jsonld
name: Amplitude Experiment Management Api Context
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
  name: enabled
  type: boolean
- container: ''
  name: evaluationMode
  type: string
- container: ''
  name: bucketingKey
  type: string
- container: ''
  name: bucketingSalt
  type: string
- container: set
  name: variants
  type: reference
- container: ''
  name: payload
  type: string
- container: ''
  name: rolloutWeight
  type: integer
- container: set
  name: deployments
  type: string
- container: set
  name: segments
  type: reference
- container: set
  name: conditions
  type: reference
- container: ''
  name: type
  type: string
- container: ''
  name: prop
  type: string
- container: ''
  name: op
  type: string
- container: set
  name: values
  type: string
- container: ''
  name: variant
  type: string
- container: ''
  name: percentage
  type: integer
- container: ''
  name: state
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
- container: set
  name: versions
  type: reference
- container: ''
  name: flagId
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: createdBy
  type: string
- container: ''
  name: nextCursor
  type: string
- container: set
  name: experiments
  type: reference
- container: ''
  name: label
  type: string
- container: ''
  name: deleted
  type: boolean
- container: set
  name: flags
  type: reference
property_count: 32
provider_name: Amplitude
provider_slug: amplitude
slug: amplitude-experiment-management-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amplitude\": \"https://amplitude.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Flag\": \"amplitude:Flag\",\n    \"Segment\": \"amplitude:Segment\",\n    \"CreateExperimentRequest\": \"amplitude:CreateExperimentRequest\",\n    \"Experiment\": \"amplitude:Experiment\",\n    \"UpdateExperimentRequest\": \"amplitude:UpdateExperimentRequest\",\n    \"VersionListResponse\": \"amplitude:VersionListResponse\",\n    \"ExperimentListResponse\": \"amplitude:ExperimentListResponse\",\n    \"DeploymentListResponse\": \"amplitude:DeploymentListResponse\",\n    \"VariantConfig\": \"amplitude:VariantConfig\",\n    \"FlagListResponse\": \"amplitude:FlagListResponse\",\n    \"CreateFlagRequest\": \"amplitude:CreateFlagRequest\",\n    \"Deployment\": \"amplitude:Deployment\",\n    \"UpdateFlagRequest\": \"amplitude:UpdateFlagRequest\"\
  ,\n    \"id\": {\n      \"@id\": \"amplitude:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"amplitude:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amplitude:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"enabled\": {\n      \"@id\": \"amplitude:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"evaluationMode\": {\n      \"@id\": \"amplitude:evaluationMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketingKey\": {\n      \"@id\": \"amplitude:bucketingKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketingSalt\": {\n      \"@id\": \"amplitude:bucketingSalt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variants\": {\n      \"@id\": \"amplitude:variants\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"payload\": {\n      \"@id\": \"amplitude:payload\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"rolloutWeight\": {\n      \"@id\": \"amplitude:rolloutWeight\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deployments\": {\n      \"@id\": \"amplitude:deployments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segments\": {\n      \"@id\": \"amplitude:segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"conditions\": {\n      \"@id\": \"amplitude:conditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"type\": {\n      \"@id\": \"amplitude:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prop\": {\n      \"@id\": \"amplitude:prop\",\n      \"@type\": \"xsd:string\"\n    },\n    \"op\": {\n      \"@id\": \"amplitude:op\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amplitude:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variant\": {\n      \"@id\": \"amplitude:variant\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"percentage\": {\n      \"@id\": \"amplitude:percentage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"amplitude:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rolledOutVariant\": {\n      \"@id\": \"amplitude:rolledOutVariant\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"amplitude:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endDate\": {\n      \"@id\": \"amplitude:endDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"versions\": {\n      \"@id\": \"amplitude:versions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"flagId\": {\n      \"@id\": \"amplitude:flagId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"createdAt\": {\n      \"@id\": \"amplitude:createdAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"createdBy\": {\n      \"@id\": \"amplitude:createdBy\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"nextCursor\": {\n      \"@id\": \"amplitude:nextCursor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"experiments\": {\n      \"@id\": \"amplitude:experiments\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"label\": {\n      \"@id\": \"amplitude:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleted\": {\n      \"@id\": \"amplitude:deleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"flags\": {\n      \"@id\": \"amplitude:flags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amplitude/refs/heads/main/json-ld/amplitude-experiment-management-api-context.jsonld
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
