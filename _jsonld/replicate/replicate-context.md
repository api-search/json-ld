---
api_specs:
- filename: replicate-openapi.yml
  format: yaml
  label: Replicate
  slug: replicate
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/openapi/replicate-openapi.yml
class_count: 2
classes:
- id
- type
context_file: json-ld/replicate-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/json-ld/replicate-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Replicate from Replicate.
layout: jsonld
name: Replicate Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: replicate
  uri: https://replicate.com/docs/reference/http#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Prediction
  type: schema:Action
- container: ''
  name: Model
  type: schema:SoftwareApplication
- container: ''
  name: ModelVersion
  type: schema:SoftwareApplication
- container: ''
  name: Deployment
  type: schema:WebAPI
- container: ''
  name: Training
  type: schema:Action
- container: ''
  name: predictionId
  type: string
- container: ''
  name: status
  type: '@vocab'
- container: ''
  name: input
  type: ''
- container: ''
  name: output
  type: ''
- container: ''
  name: error
  type: ''
- container: ''
  name: logs
  type: ''
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: modelName
  type: ''
- container: ''
  name: owner
  type: schema:Person
- container: ''
  name: description
  type: ''
- container: ''
  name: visibility
  type: ''
- container: ''
  name: githubUrl
  type: anyURI
- container: ''
  name: paperUrl
  type: anyURI
- container: ''
  name: runCount
  type: integer
- container: ''
  name: hardware
  type: ''
- container: ''
  name: minInstances
  type: integer
- container: ''
  name: maxInstances
  type: integer
- container: ''
  name: version
  type: ''
- container: ''
  name: cogVersion
  type: ''
- container: ''
  name: openApiSchema
  type: ''
- container: ''
  name: destination
  type: ''
- container: ''
  name: predictTime
  type: decimal
- container: ''
  name: totalTime
  type: decimal
- container: ''
  name: webhook
  type: anyURI
- container: ''
  name: webhookEventsFilter
  type: ''
property_count: 32
provider_name: Replicate
provider_slug: replicate
slug: replicate-context
source_filename: replicate-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"replicate\": \"https://replicate.com/docs/reference/http#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Prediction\": {\n      \"@id\": \"replicate:Prediction\",\n      \"@type\": \"schema:Action\"\n    },\n    \"Model\": {\n      \"@id\": \"replicate:Model\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"ModelVersion\": {\n      \"@id\": \"replicate:ModelVersion\",\n      \"@type\": \"schema:SoftwareApplication\"\n    },\n    \"Deployment\": {\n      \"@id\": \"replicate:Deployment\",\n      \"@type\": \"schema:WebAPI\"\n    },\n    \"Training\": {\n      \"@id\": \"replicate:Training\",\n      \"@type\": \"schema:Action\"\n    },\n\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n\n    \"predictionId\": {\n      \"@id\": \"schema:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"schema:actionStatus\",\n\
  \      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"starting\": \"schema:ActiveActionStatus\",\n        \"processing\": \"schema:ActiveActionStatus\",\n        \"succeeded\": \"schema:CompletedActionStatus\",\n        \"failed\": \"schema:FailedActionStatus\",\n        \"canceled\": \"schema:CanceledEventStatus\"\n      }\n    },\n    \"input\": {\n      \"@id\": \"schema:object\"\n    },\n    \"output\": {\n      \"@id\": \"schema:result\"\n    },\n    \"error\": {\n      \"@id\": \"schema:errorMessage\"\n    },\n    \"logs\": {\n      \"@id\": \"schema:description\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"startedAt\": {\n      \"@id\": \"schema:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"modelName\": {\n      \"@id\": \"schema:name\"\n    },\n    \"owner\": {\n      \"@id\"\
  : \"schema:author\",\n      \"@type\": \"schema:Person\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\"\n    },\n    \"visibility\": {\n      \"@id\": \"schema:accessMode\"\n    },\n    \"githubUrl\": {\n      \"@id\": \"schema:codeRepository\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"paperUrl\": {\n      \"@id\": \"schema:citation\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"runCount\": {\n      \"@id\": \"schema:numberOfPages\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"hardware\": {\n      \"@id\": \"replicate:hardware\"\n    },\n    \"minInstances\": {\n      \"@id\": \"replicate:minInstances\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxInstances\": {\n      \"@id\": \"replicate:maxInstances\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"version\": {\n      \"@id\": \"schema:version\"\n    },\n    \"cogVersion\": {\n      \"@id\": \"replicate:cogVersion\"\n    },\n    \"openApiSchema\": {\n      \"@id\": \"schema:documentation\"\
  \n    },\n\n    \"destination\": {\n      \"@id\": \"replicate:trainingDestination\"\n    },\n    \"predictTime\": {\n      \"@id\": \"replicate:predictTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"totalTime\": {\n      \"@id\": \"replicate:totalTime\",\n      \"@type\": \"xsd:decimal\"\n    },\n\n    \"webhook\": {\n      \"@id\": \"schema:url\",\n      \"@type\": \"xsd:anyURI\"\n    },\n    \"webhookEventsFilter\": {\n      \"@id\": \"replicate:webhookEventsFilter\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/replicate/refs/heads/main/json-ld/replicate-context.jsonld
tags:
- Artificial Intelligence
- Machine Learning
- Image Generation
- Language Models
- Model Deployment
- JSON-LD
- Linked Data
- Semantic Web
---
