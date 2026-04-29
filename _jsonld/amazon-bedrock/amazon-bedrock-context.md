---
class_count: 20
classes:
- FoundationModel
- CustomModel
- ProvisionedThroughput
- ModelCustomizationJob
- modelId
- modelArn
- modelName
- providerName
- jobArn
- jobName
- baseModelIdentifier
- customModelName
- customizationType
- trainingDataConfig
- outputDataConfig
- hyperParameters
- provisionedModelArn
- provisionedModelName
- commitmentDuration
- status
context_file: json-ld/amazon-bedrock-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/json-ld/amazon-bedrock-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Bedrock from Amazon Bedrock.
layout: jsonld
name: Amazon Bedrock Context
namespaces:
- prefix: bedrock
  uri: https://aws.amazon.com/bedrock/ns#
- prefix: aws
  uri: https://aws.amazon.com/ns#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: inputModalities
  type: '@vocab'
- container: ''
  name: outputModalities
  type: '@vocab'
- container: ''
  name: responseStreamingSupported
  type: boolean
- container: ''
  name: customizationsSupported
  type: '@vocab'
- container: ''
  name: inferenceTypesSupported
  type: '@vocab'
- container: ''
  name: modelUnits
  type: integer
- container: ''
  name: creationTime
  type: dateTime
- container: ''
  name: lastModifiedTime
  type: dateTime
property_count: 8
provider_name: Amazon Bedrock
provider_slug: amazon-bedrock
slug: amazon-bedrock-context
source_filename: amazon-bedrock-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"bedrock\": \"https://aws.amazon.com/bedrock/ns#\",\n    \"aws\": \"https://aws.amazon.com/ns#\",\n\n    \"FoundationModel\": \"bedrock:FoundationModel\",\n    \"CustomModel\": \"bedrock:CustomModel\",\n    \"ProvisionedThroughput\": \"bedrock:ProvisionedThroughput\",\n    \"ModelCustomizationJob\": \"bedrock:ModelCustomizationJob\",\n\n    \"modelId\": \"bedrock:modelId\",\n    \"modelArn\": \"bedrock:modelArn\",\n    \"modelName\": \"bedrock:modelName\",\n    \"providerName\": \"bedrock:providerName\",\n\n    \"inputModalities\": {\n      \"@id\": \"bedrock:inputModalities\",\n      \"@type\": \"@vocab\"\n    },\n    \"outputModalities\": {\n      \"@id\": \"bedrock:outputModalities\",\n      \"@type\": \"@vocab\"\n    },\n    \"responseStreamingSupported\": {\n      \"@id\": \"bedrock:responseStreamingSupported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"customizationsSupported\": {\n      \"@id\"\
  : \"bedrock:customizationsSupported\",\n      \"@type\": \"@vocab\"\n    },\n    \"inferenceTypesSupported\": {\n      \"@id\": \"bedrock:inferenceTypesSupported\",\n      \"@type\": \"@vocab\"\n    },\n\n    \"jobArn\": \"bedrock:jobArn\",\n    \"jobName\": \"bedrock:jobName\",\n    \"baseModelIdentifier\": \"bedrock:baseModelIdentifier\",\n    \"customModelName\": \"bedrock:customModelName\",\n    \"customizationType\": \"bedrock:customizationType\",\n    \"trainingDataConfig\": \"bedrock:trainingDataConfig\",\n    \"outputDataConfig\": \"bedrock:outputDataConfig\",\n    \"hyperParameters\": \"bedrock:hyperParameters\",\n\n    \"provisionedModelArn\": \"bedrock:provisionedModelArn\",\n    \"provisionedModelName\": \"bedrock:provisionedModelName\",\n    \"modelUnits\": {\n      \"@id\": \"bedrock:modelUnits\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"commitmentDuration\": \"bedrock:commitmentDuration\",\n\n    \"status\": \"bedrock:status\",\n    \"creationTime\": {\n      \"\
  @id\": \"bedrock:creationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"bedrock:lastModifiedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-bedrock/refs/heads/main/json-ld/amazon-bedrock-context.jsonld
tags:
- AI
- AWS
- Foundation Models
- Generative AI
- LLM
- Machine Learning
- RAG
- Agents
- Responsible AI
- JSON-LD
- Linked Data
- Semantic Web
---
