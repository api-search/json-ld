---
class_count: 0
classes: []
context_file: json-ld/amazon-batch-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/json-ld/amazon-batch-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Batch from Amazon Batch.
layout: jsonld
name: Amazon Batch Context
namespaces:
- prefix: batch
  uri: https://docs.aws.amazon.com/batch/latest/APIReference/
- prefix: aws
  uri: https://aws.amazon.com/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
properties:
- container: ''
  name: JobDefinition
  type: ''
- container: ''
  name: JobDetail
  type: ''
- container: ''
  name: ComputeEnvironment
  type: ''
- container: ''
  name: JobQueue
  type: ''
- container: ''
  name: ContainerProperties
  type: ''
property_count: 5
provider_name: Amazon Batch
provider_slug: amazon-batch
slug: amazon-batch-context
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"batch\": \"https://docs.aws.amazon.com/batch/latest/APIReference/\",\n    \"aws\": \"https://aws.amazon.com/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n\n    \"JobDefinition\": {\n      \"@id\": \"batch:API_JobDefinition\",\n      \"@context\": {\n        \"jobDefinitionName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobDefinitionArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"revision\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"status\": {\n          \"@id\": \"batch:jobDefinitionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n  \
  \        \"@id\": \"batch:jobDefinitionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parameters\": {\n          \"@id\": \"batch:parameters\",\n          \"@container\": \"@index\"\n        },\n        \"containerProperties\": {\n          \"@id\": \"batch:containerProperties\",\n          \"@type\": \"batch:ContainerProperties\"\n        },\n        \"retryStrategy\": {\n          \"@id\": \"batch:retryStrategy\",\n          \"@type\": \"batch:RetryStrategy\"\n        },\n        \"timeout\": {\n          \"@id\": \"batch:timeout\",\n          \"@type\": \"batch:JobTimeout\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@index\"\n        },\n        \"platformCapabilities\": {\n          \"@id\": \"batch:platformCapabilities\",\n          \"@container\": \"@list\"\n        },\n        \"propagateTags\": {\n          \"@id\": \"batch:propagateTags\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n\
  \    },\n\n    \"JobDetail\": {\n      \"@id\": \"batch:API_JobDetail\",\n      \"@context\": {\n        \"jobArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobId\": {\n          \"@id\": \"batch:jobId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobQueue\": {\n          \"@id\": \"batch:jobQueue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"batch:jobStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"statusReason\": {\n          \"@id\": \"batch:statusReason\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdAt\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startedAt\": {\n          \"@id\": \"batch:startedAt\",\n          \"@type\": \"xsd:integer\"\
  \n        },\n        \"stoppedAt\": {\n          \"@id\": \"batch:stoppedAt\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"jobDefinition\": {\n          \"@id\": \"batch:jobDefinition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"container\": {\n          \"@id\": \"batch:container\",\n          \"@type\": \"batch:ContainerDetail\"\n        }\n      }\n    },\n\n    \"ComputeEnvironment\": {\n      \"@id\": \"batch:API_ComputeEnvironmentDetail\",\n      \"@context\": {\n        \"computeEnvironmentName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"computeEnvironmentArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"batch:computeEnvironmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"batch:computeEnvironmentState\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"status\": {\n          \"@id\": \"batch:computeEnvironmentStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"serviceRole\": {\n          \"@id\": \"batch:serviceRole\",\n          \"@type\": \"xsd:string\"\n        },\n        \"computeResources\": {\n          \"@id\": \"batch:computeResources\",\n          \"@type\": \"batch:ComputeResource\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"JobQueue\": {\n      \"@id\": \"batch:API_JobQueueDetail\",\n      \"@context\": {\n        \"jobQueueName\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"jobQueueArn\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"batch:jobQueueState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n  \
  \        \"@id\": \"batch:jobQueueStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"batch:priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"computeEnvironmentOrder\": {\n          \"@id\": \"batch:computeEnvironmentOrder\",\n          \"@container\": \"@list\"\n        },\n        \"schedulingPolicyArn\": {\n          \"@id\": \"batch:schedulingPolicyArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@index\"\n        }\n      }\n    },\n\n    \"ContainerProperties\": {\n      \"@id\": \"batch:ContainerProperties\",\n      \"@context\": {\n        \"image\": {\n          \"@id\": \"batch:image\",\n          \"@type\": \"xsd:string\"\n        },\n        \"command\": {\n          \"@id\": \"batch:command\",\n          \"@container\": \"@list\"\n        },\n        \"jobRoleArn\": {\n          \"@id\": \"batch:jobRoleArn\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"executionRoleArn\": {\n          \"@id\": \"batch:executionRoleArn\",\n          \"@type\": \"xsd:string\"\n        },\n        \"environment\": {\n          \"@id\": \"batch:environment\",\n          \"@container\": \"@list\"\n        },\n        \"resourceRequirements\": {\n          \"@id\": \"batch:resourceRequirements\",\n          \"@container\": \"@list\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-batch/refs/heads/main/json-ld/amazon-batch-context.jsonld
tags:
- AWS
- Batch Computing
- Compute
- Containers
- HPC
- Job Scheduling
- Serverless
- Fargate
- EKS
- Spot Instances
- JSON-LD
- Linked Data
- Semantic Web
---
