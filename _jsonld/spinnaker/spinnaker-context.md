---
api_specs:
- filename: spinnaker-gate-openapi.yml
  format: yaml
  label: Spinnaker Gate API
  slug: spinnaker-gate-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/openapi/spinnaker-gate-openapi.yml
class_count: 8
classes:
- Application
- Pipeline
- PipelineExecution
- Stage
- Cluster
- ServerGroup
- LoadBalancer
- id
context_file: json-ld/spinnaker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/json-ld/spinnaker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Spinnaker from Spinnaker.
layout: jsonld
name: Spinnaker Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: spinnaker
  uri: https://spinnaker.io/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: application
  type: string
- container: list
  name: stages
  type: ''
- container: ''
  name: startTime
  type: integer
- container: ''
  name: endTime
  type: integer
- container: ''
  name: trigger
  type: reference
- container: ''
  name: account
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: email
  type: string
property_count: 12
provider_name: Spinnaker
provider_slug: spinnaker
slug: spinnaker-context
source_filename: spinnaker-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"spinnaker\": \"https://spinnaker.io/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Application\": \"spinnaker:Application\",\n    \"Pipeline\": \"spinnaker:Pipeline\",\n    \"PipelineExecution\": \"spinnaker:PipelineExecution\",\n    \"Stage\": \"spinnaker:Stage\",\n    \"Cluster\": \"spinnaker:Cluster\",\n    \"ServerGroup\": \"spinnaker:ServerGroup\",\n    \"LoadBalancer\": \"spinnaker:LoadBalancer\",\n\n    \"id\": \"@id\",\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"spinnaker:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"spinnaker:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stages\": {\n      \"@id\": \"\
  spinnaker:stages\",\n      \"@container\": \"@list\"\n    },\n    \"startTime\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"endTime\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trigger\": {\n      \"@id\": \"spinnaker:trigger\",\n      \"@type\": \"@id\"\n    },\n    \"account\": {\n      \"@id\": \"spinnaker:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"spinnaker:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"spinnaker:stageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/spinnaker/refs/heads/main/json-ld/spinnaker-context.jsonld
tags:
- Continuous Delivery
- Containers
- DevOps
- Multi-Cloud
- Pipelines
- JSON-LD
- Linked Data
- Semantic Web
---
