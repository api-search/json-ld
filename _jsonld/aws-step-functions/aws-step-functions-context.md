---
api_specs:
- filename: aws-step-functions-openapi.json
  format: json
  label: AWS Step Functions
  slug: aws-step-functions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/openapi/aws-step-functions-openapi.json
class_count: 40
classes:
- CreateActivityOutput
- CreateActivityInput
- ActivityLimitExceeded
- InvalidName
- TooManyTags
- CreateStateMachineOutput
- CreateStateMachineInput
- InvalidArn
- InvalidDefinition
- InvalidLoggingConfiguration
- InvalidTracingConfiguration
- StateMachineAlreadyExists
- StateMachineDeleting
- StateMachineLimitExceeded
- StateMachineTypeNotSupported
- DeleteActivityOutput
- DeleteActivityInput
- DeleteStateMachineOutput
- DeleteStateMachineInput
- ValidationException
- DescribeActivityOutput
- DescribeActivityInput
- ActivityDoesNotExist
- DescribeExecutionOutput
- DescribeExecutionInput
- ExecutionDoesNotExist
- DescribeMapRunOutput
- DescribeMapRunInput
- ResourceNotFound
- DescribeStateMachineOutput
- DescribeStateMachineInput
- StateMachineDoesNotExist
- DescribeStateMachineForExecutionOutput
- DescribeStateMachineForExecutionInput
- GetActivityTaskOutput
- GetActivityTaskInput
- ActivityWorkerLimitExceeded
- GetExecutionHistoryOutput
- GetExecutionHistoryInput
- InvalidToken
context_file: json-ld/aws-step-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/json-ld/aws-step-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aws Step Functions from AWS Step Functions.
layout: jsonld
name: Aws Step Functions Context
namespaces:
- prefix: sfn
  uri: https://docs.aws.amazon.com/step-functions/latest/apireference/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: AWS Step Functions
provider_slug: aws-step-functions
slug: aws-step-functions-context
source_filename: aws-step-functions-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sfn\": \"https://docs.aws.amazon.com/step-functions/latest/apireference/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateActivityOutput\": \"sfn:CreateActivityOutput\",\n    \"CreateActivityInput\": \"sfn:CreateActivityInput\",\n    \"ActivityLimitExceeded\": \"sfn:ActivityLimitExceeded\",\n    \"InvalidName\": \"sfn:InvalidName\",\n    \"TooManyTags\": \"sfn:TooManyTags\",\n    \"CreateStateMachineOutput\": \"sfn:CreateStateMachineOutput\",\n    \"CreateStateMachineInput\": \"sfn:CreateStateMachineInput\",\n    \"InvalidArn\": \"sfn:InvalidArn\",\n    \"InvalidDefinition\": \"sfn:InvalidDefinition\",\n    \"InvalidLoggingConfiguration\": \"sfn:InvalidLoggingConfiguration\",\n    \"InvalidTracingConfiguration\": \"sfn:InvalidTracingConfiguration\",\n    \"StateMachineAlreadyExists\": \"sfn:StateMachineAlreadyExists\",\n    \"StateMachineDeleting\": \"sfn:StateMachineDeleting\"\
  ,\n    \"StateMachineLimitExceeded\": \"sfn:StateMachineLimitExceeded\",\n    \"StateMachineTypeNotSupported\": \"sfn:StateMachineTypeNotSupported\",\n    \"DeleteActivityOutput\": \"sfn:DeleteActivityOutput\",\n    \"DeleteActivityInput\": \"sfn:DeleteActivityInput\",\n    \"DeleteStateMachineOutput\": \"sfn:DeleteStateMachineOutput\",\n    \"DeleteStateMachineInput\": \"sfn:DeleteStateMachineInput\",\n    \"ValidationException\": \"sfn:ValidationException\",\n    \"DescribeActivityOutput\": \"sfn:DescribeActivityOutput\",\n    \"DescribeActivityInput\": \"sfn:DescribeActivityInput\",\n    \"ActivityDoesNotExist\": \"sfn:ActivityDoesNotExist\",\n    \"DescribeExecutionOutput\": \"sfn:DescribeExecutionOutput\",\n    \"DescribeExecutionInput\": \"sfn:DescribeExecutionInput\",\n    \"ExecutionDoesNotExist\": \"sfn:ExecutionDoesNotExist\",\n    \"DescribeMapRunOutput\": \"sfn:DescribeMapRunOutput\",\n    \"DescribeMapRunInput\": \"sfn:DescribeMapRunInput\",\n    \"ResourceNotFound\": \"sfn:ResourceNotFound\"\
  ,\n    \"DescribeStateMachineOutput\": \"sfn:DescribeStateMachineOutput\",\n    \"DescribeStateMachineInput\": \"sfn:DescribeStateMachineInput\",\n    \"StateMachineDoesNotExist\": \"sfn:StateMachineDoesNotExist\",\n    \"DescribeStateMachineForExecutionOutput\": \"sfn:DescribeStateMachineForExecutionOutput\",\n    \"DescribeStateMachineForExecutionInput\": \"sfn:DescribeStateMachineForExecutionInput\",\n    \"GetActivityTaskOutput\": \"sfn:GetActivityTaskOutput\",\n    \"GetActivityTaskInput\": \"sfn:GetActivityTaskInput\",\n    \"ActivityWorkerLimitExceeded\": \"sfn:ActivityWorkerLimitExceeded\",\n    \"GetExecutionHistoryOutput\": \"sfn:GetExecutionHistoryOutput\",\n    \"GetExecutionHistoryInput\": \"sfn:GetExecutionHistoryInput\",\n    \"InvalidToken\": \"sfn:InvalidToken\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aws-step-functions/refs/heads/main/json-ld/aws-step-functions-context.jsonld
tags:
- iPaaS
- Orchestration
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
