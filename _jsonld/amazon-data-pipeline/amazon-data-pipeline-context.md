---
api_specs:
- filename: amazon-data-pipeline-openapi.yml
  format: yaml
  label: AWS Data Pipeline API
  slug: aws-data-pipeline-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/openapi/amazon-data-pipeline-openapi.yml
class_count: 0
classes: []
context_file: json-ld/amazon-data-pipeline-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/json-ld/amazon-data-pipeline-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Data Pipeline from Amazon Data Pipeline.
layout: jsonld
name: Amazon Data Pipeline Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/datapipeline/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Pipeline
  type: ''
- container: ''
  name: PipelineObject
  type: ''
- container: ''
  name: PipelineDescription
  type: ''
- container: ''
  name: Field
  type: ''
- container: ''
  name: Tag
  type: ''
- container: ''
  name: ValidationError
  type: ''
- container: ''
  name: pipelineId
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: uniqueId
  type: string
- container: ''
  name: pipelineState
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: stringValue
  type: string
- container: ''
  name: refValue
  type: string
- container: set
  name: fields
  type: ''
- container: set
  name: tags
  type: ''
- container: set
  name: pipelineObjects
  type: ''
- container: set
  name: pipelineIdList
  type: ''
- container: set
  name: pipelineDescriptionList
  type: ''
- container: ''
  name: hasMoreResults
  type: boolean
- container: ''
  name: marker
  type: string
- container: ''
  name: errored
  type: boolean
- container: set
  name: validationErrors
  type: ''
- container: set
  name: validationWarnings
  type: ''
- container: ''
  name: startTimestamp
  type: dateTime
- container: ''
  name: cancelActive
  type: boolean
- container: ''
  name: sphere
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: code
  type: string
property_count: 30
provider_name: Amazon Data Pipeline
provider_slug: amazon-data-pipeline
slug: amazon-data-pipeline-context
source_filename: amazon-data-pipeline-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/datapipeline/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Pipeline\": {\"@id\": \"aws:Pipeline\"},\n    \"PipelineObject\": {\"@id\": \"aws:PipelineObject\"},\n    \"PipelineDescription\": {\"@id\": \"aws:PipelineDescription\"},\n    \"Field\": {\"@id\": \"aws:Field\"},\n    \"Tag\": {\"@id\": \"aws:Tag\"},\n    \"ValidationError\": {\"@id\": \"aws:ValidationError\"},\n\n    \"pipelineId\": {\"@id\": \"aws:pipelineId\", \"@type\": \"xsd:string\"},\n    \"name\": {\"@id\": \"schema:name\", \"@type\": \"xsd:string\"},\n    \"description\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"uniqueId\": {\"@id\": \"aws:uniqueId\", \"@type\": \"xsd:string\"},\n    \"pipelineState\": {\"@id\": \"aws:pipelineState\", \"@type\": \"xsd:string\"},\n    \"id\": {\"@id\": \"aws:objectId\", \"@type\": \"xsd:string\"},\n\n  \
  \  \"key\": {\"@id\": \"aws:fieldKey\", \"@type\": \"xsd:string\"},\n    \"stringValue\": {\"@id\": \"aws:stringValue\", \"@type\": \"xsd:string\"},\n    \"refValue\": {\"@id\": \"aws:refValue\", \"@type\": \"xsd:string\"},\n\n    \"fields\": {\"@id\": \"aws:fields\", \"@container\": \"@set\"},\n    \"tags\": {\"@id\": \"aws:tags\", \"@container\": \"@set\"},\n    \"pipelineObjects\": {\"@id\": \"aws:pipelineObjects\", \"@container\": \"@set\"},\n    \"pipelineIdList\": {\"@id\": \"aws:pipelineIdList\", \"@container\": \"@set\"},\n    \"pipelineDescriptionList\": {\"@id\": \"aws:pipelineDescriptionList\", \"@container\": \"@set\"},\n\n    \"hasMoreResults\": {\"@id\": \"aws:hasMoreResults\", \"@type\": \"xsd:boolean\"},\n    \"marker\": {\"@id\": \"aws:marker\", \"@type\": \"xsd:string\"},\n    \"errored\": {\"@id\": \"aws:errored\", \"@type\": \"xsd:boolean\"},\n    \"validationErrors\": {\"@id\": \"aws:validationErrors\", \"@container\": \"@set\"},\n    \"validationWarnings\": {\"@id\"\
  : \"aws:validationWarnings\", \"@container\": \"@set\"},\n\n    \"startTimestamp\": {\"@id\": \"schema:startDate\", \"@type\": \"xsd:dateTime\"},\n    \"cancelActive\": {\"@id\": \"aws:cancelActive\", \"@type\": \"xsd:boolean\"},\n    \"sphere\": {\"@id\": \"aws:sphere\", \"@type\": \"xsd:string\"},\n\n    \"message\": {\"@id\": \"schema:description\", \"@type\": \"xsd:string\"},\n    \"code\": {\"@id\": \"aws:errorCode\", \"@type\": \"xsd:string\"}\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-data-pipeline/refs/heads/main/json-ld/amazon-data-pipeline-context.jsonld
tags:
- AWS
- Data Processing
- ETL
- Workflows
- Data Pipeline
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
