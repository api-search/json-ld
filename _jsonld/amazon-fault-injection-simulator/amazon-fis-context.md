---
api_specs:
- filename: amazon-fis-openapi.yml
  format: yaml
  label: AWS Fault Injection Simulator API
  slug: aws-fis-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/openapi/amazon-fis-openapi.yml
class_count: 13
classes:
- ExperimentTemplateTarget
- TargetResourceType
- description
- ExperimentTemplateStopCondition
- ExperimentState
- SafetyLeverState
- SafetyLever
- ExperimentTemplate
- creationTime
- lastUpdateTime
- Action
- ExperimentTemplateAction
- Experiment
context_file: json-ld/amazon-fis-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/json-ld/amazon-fis-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Fis from Amazon Fault Injection Simulator.
layout: jsonld
name: Amazon Fis Context
namespaces:
- prefix: fis
  uri: https://aws.amazon.com/fis/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: resourceType
  type: string
- container: set
  name: resourceArns
  type: string
- container: ''
  name: resourceTags
  type: reference
- container: set
  name: filters
  type: reference
- container: ''
  name: selectionMode
  type: string
- container: ''
  name: parameters
  type: reference
- container: ''
  name: source
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: targets
  type: reference
- container: ''
  name: actions
  type: reference
- container: set
  name: stopConditions
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: actionId
  type: string
- container: set
  name: startAfter
  type: string
- container: ''
  name: experimentTemplateId
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
property_count: 23
provider_name: Amazon Fault Injection Simulator
provider_slug: amazon-fault-injection-simulator
slug: amazon-fis-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fis\": \"https://aws.amazon.com/fis/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExperimentTemplateTarget\": \"fis:ExperimentTemplateTarget\",\n    \"resourceType\": {\n      \"@id\": \"fis:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArns\": {\n      \"@id\": \"fis:resourceArns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceTags\": {\n      \"@id\": \"fis:resourceTags\",\n      \"@type\": \"@id\"\n    },\n    \"filters\": {\n      \"@id\": \"fis:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"selectionMode\": {\n      \"@id\": \"fis:selectionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetResourceType\": \"fis:TargetResourceType\",\n    \"description\": \"schema:description\",\n    \"parameters\"\
  : {\n      \"@id\": \"fis:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"ExperimentTemplateStopCondition\": \"fis:ExperimentTemplateStopCondition\",\n    \"source\": {\n      \"@id\": \"fis:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"fis:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExperimentState\": \"fis:ExperimentState\",\n    \"status\": {\n      \"@id\": \"fis:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"fis:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SafetyLeverState\": \"fis:SafetyLeverState\",\n    \"SafetyLever\": \"fis:SafetyLever\",\n    \"id\": {\n      \"@id\": \"fis:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"fis:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"fis:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExperimentTemplate\": \"fis:ExperimentTemplate\",\n    \"targets\"\
  : {\n      \"@id\": \"fis:targets\",\n      \"@type\": \"@id\"\n    },\n    \"actions\": {\n      \"@id\": \"fis:actions\",\n      \"@type\": \"@id\"\n    },\n    \"stopConditions\": {\n      \"@id\": \"fis:stopConditions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": \"schema:dateCreated\",\n    \"lastUpdateTime\": \"schema:dateModified\",\n    \"roleArn\": {\n      \"@id\": \"fis:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"fis:tags\",\n      \"@type\": \"@id\"\n    },\n    \"Action\": \"fis:Action\",\n    \"ExperimentTemplateAction\": \"fis:ExperimentTemplateAction\",\n    \"actionId\": {\n      \"@id\": \"fis:actionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startAfter\": {\n      \"@id\": \"fis:startAfter\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Experiment\": \"fis:Experiment\",\n    \"experimentTemplateId\": {\n      \"@id\": \"fis:experimentTemplateId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"fis:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"fis:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-fault-injection-simulator/refs/heads/main/json-ld/amazon-fis-context.jsonld
tags:
- AWS
- Chaos Engineering
- DevOps
- Fault Injection
- Resilience Testing
- JSON-LD
- Linked Data
- Semantic Web
---
