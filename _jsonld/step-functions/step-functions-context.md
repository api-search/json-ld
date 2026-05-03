---
api_specs:
- filename: step-functions-openapi.yml
  format: yaml
  label: AWS Step Functions API
  slug: step-functions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/openapi/step-functions-openapi.yml
class_count: 16
classes:
- name
- description
- definition
- roleArn
- type
- status
- creationDate
- input
- output
- startDate
- stopDate
- loggingConfiguration
- tracingConfiguration
- tags
- taskToken
- revisionId
context_file: json-ld/step-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/json-ld/step-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Step Functions from AWS Step Functions.
layout: jsonld
name: Step Functions Context
namespaces:
- prefix: sfn
  uri: https://aws.amazon.com/step-functions/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: aws
  uri: https://aws.amazon.com/vocab/
properties:
- container: ''
  name: StateMachine
  type: reference
- container: ''
  name: Execution
  type: reference
- container: ''
  name: Activity
  type: reference
- container: ''
  name: StateMachineVersion
  type: reference
- container: ''
  name: StateMachineAlias
  type: reference
- container: ''
  name: stateMachineArn
  type: ''
- container: ''
  name: executionArn
  type: ''
- container: ''
  name: activityArn
  type: ''
property_count: 8
provider_name: AWS Step Functions
provider_slug: step-functions
slug: step-functions-context
source_filename: step-functions-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sfn\": \"https://aws.amazon.com/step-functions/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"aws\": \"https://aws.amazon.com/vocab/\",\n    \"StateMachine\": {\n      \"@id\": \"sfn:StateMachine\",\n      \"@type\": \"@id\"\n    },\n    \"Execution\": {\n      \"@id\": \"sfn:Execution\",\n      \"@type\": \"@id\"\n    },\n    \"Activity\": {\n      \"@id\": \"sfn:Activity\",\n      \"@type\": \"@id\"\n    },\n    \"StateMachineVersion\": {\n      \"@id\": \"sfn:StateMachineVersion\",\n      \"@type\": \"@id\"\n    },\n    \"StateMachineAlias\": {\n      \"@id\": \"sfn:StateMachineAlias\",\n      \"@type\": \"@id\"\n    },\n    \"stateMachineArn\": {\n      \"@id\": \"aws:arn\"\n    },\n    \"executionArn\": {\n      \"@id\": \"aws:arn\"\n    },\n    \"activityArn\": {\n      \"@id\": \"aws:arn\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"definition\": \"sfn:stateMachineDefinition\"\
  ,\n    \"roleArn\": \"aws:iamRoleArn\",\n    \"type\": \"sfn:workflowType\",\n    \"status\": \"sfn:status\",\n    \"creationDate\": \"schema:dateCreated\",\n    \"input\": \"sfn:executionInput\",\n    \"output\": \"sfn:executionOutput\",\n    \"startDate\": \"schema:startDate\",\n    \"stopDate\": \"schema:endDate\",\n    \"loggingConfiguration\": \"sfn:loggingConfiguration\",\n    \"tracingConfiguration\": \"sfn:tracingConfiguration\",\n    \"tags\": \"aws:tags\",\n    \"taskToken\": \"sfn:taskToken\",\n    \"revisionId\": \"schema:version\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/step-functions/refs/heads/main/json-ld/step-functions-context.jsonld
tags:
- API Composition
- Serverless Orchestration
- Workflow
- State Machine
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
