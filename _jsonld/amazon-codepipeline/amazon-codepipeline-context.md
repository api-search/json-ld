---
api_specs:
- filename: amazon-codepipeline-openapi-original.yaml
  format: yaml
  label: Amazon CodePipeline API
  slug: amazon-codepipeline-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/openapi/amazon-codepipeline-openapi-original.yaml
class_count: 9
classes:
- Pipeline
- CreatePipelineInput
- StageDeclaration
- ActionDeclaration
- PipelineExecution
- PipelineList
- Tag
- name
- version
context_file: json-ld/amazon-codepipeline-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/json-ld/amazon-codepipeline-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codepipeline from Amazon CodePipeline.
layout: jsonld
name: Amazon Codepipeline Context
namespaces:
- prefix: amazon-code-pipeline
  uri: https://amazon-code-pipeline.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: roleArn
  type: string
- container: set
  name: stages
  type: string
- container: ''
  name: pipeline
  type: string
- container: set
  name: tags
  type: string
- container: set
  name: actions
  type: string
- container: ''
  name: actionTypeId
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: configuration
  type: string
- container: set
  name: inputArtifacts
  type: string
- container: set
  name: outputArtifacts
  type: string
- container: ''
  name: pipelineName
  type: string
- container: ''
  name: pipelineExecutionId
  type: string
- container: ''
  name: pipelineVersion
  type: integer
- container: ''
  name: status
  type: string
- container: ''
  name: statusSummary
  type: string
- container: set
  name: pipelines
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: updated
  type: dateTime
- container: ''
  name: nextToken
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
property_count: 23
provider_name: Amazon CodePipeline
provider_slug: amazon-codepipeline
slug: amazon-codepipeline-context
source_filename: amazon-codepipeline-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-pipeline\": \"https://amazon-code-pipeline.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Pipeline\": \"amazon-code-pipeline:Pipeline\",\n    \"CreatePipelineInput\": \"amazon-code-pipeline:CreatePipelineInput\",\n    \"StageDeclaration\": \"amazon-code-pipeline:StageDeclaration\",\n    \"ActionDeclaration\": \"amazon-code-pipeline:ActionDeclaration\",\n    \"PipelineExecution\": \"amazon-code-pipeline:PipelineExecution\",\n    \"PipelineList\": \"amazon-code-pipeline:PipelineList\",\n    \"Tag\": \"amazon-code-pipeline:Tag\",\n    \"name\": \"schema:name\",\n    \"roleArn\": {\n      \"@id\": \"amazon-code-pipeline:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stages\": {\n      \"@id\": \"amazon-code-pipeline:stages\",\n      \"@container\": \"@set\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"pipeline\": {\n      \"@id\": \"amazon-code-pipeline:pipeline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amazon-code-pipeline:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"amazon-code-pipeline:actions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actionTypeId\": {\n      \"@id\": \"amazon-code-pipeline:actionTypeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"amazon-code-pipeline:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"amazon-code-pipeline:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"amazon-code-pipeline:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"amazon-code-pipeline:configuration\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"inputArtifacts\": {\n      \"@id\": \"amazon-code-pipeline:inputArtifacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputArtifacts\": {\n      \"@id\": \"amazon-code-pipeline:outputArtifacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineName\": {\n      \"@id\": \"amazon-code-pipeline:pipelineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineExecutionId\": {\n      \"@id\": \"amazon-code-pipeline:pipelineExecutionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineVersion\": {\n      \"@id\": \"amazon-code-pipeline:pipelineVersion\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"status\": {\n      \"@id\": \"amazon-code-pipeline:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusSummary\": {\n      \"@id\": \"amazon-code-pipeline:statusSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelines\": {\n     \
  \ \"@id\": \"amazon-code-pipeline:pipelines\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"amazon-code-pipeline:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated\": {\n      \"@id\": \"amazon-code-pipeline:updated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-pipeline:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amazon-code-pipeline:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amazon-code-pipeline:value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codepipeline/refs/heads/main/json-ld/amazon-codepipeline-context.jsonld
tags:
- Amazon
- CI/CD
- Continuous Delivery
- DevOps
- Pipeline
- Release Automation
- JSON-LD
- Linked Data
- Semantic Web
---
