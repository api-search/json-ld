---
api_specs:
- filename: amazon-neptune-management-openapi.yml
  format: yaml
  label: Amazon Neptune Management API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-management-openapi.yml
- filename: amazon-neptune-data-openapi.yml
  format: yaml
  label: Amazon Neptune Data API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-data-openapi.yml
- filename: amazon-neptune-gremlin-openapi.yml
  format: yaml
  label: Neptune Gremlin API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-gremlin-openapi.yml
- filename: amazon-neptune-sparql-openapi.yml
  format: yaml
  label: Neptune SPARQL API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-sparql-openapi.yml
- filename: amazon-neptune-opencypher-openapi.yml
  format: yaml
  label: Neptune openCypher API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-opencypher-openapi.yml
- filename: amazon-neptune-streams-openapi.yml
  format: yaml
  label: Neptune Streams API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-streams-openapi.yml
- filename: amazon-neptune-loader-openapi.yml
  format: yaml
  label: Neptune Loader API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-loader-openapi.yml
- filename: amazon-neptune-ml-openapi.yml
  format: yaml
  label: Neptune ML API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-ml-openapi.yml
- filename: amazon-neptune-analytics-openapi.yml
  format: yaml
  label: Neptune Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/openapi/amazon-neptune-analytics-openapi.yml
class_count: 10
classes:
- CreateDataProcessingJobRequest
- CreateInferenceEndpointRequest
- CreateModelTrainingJobRequest
- CreateModelTransformJobRequest
- EndpointCreatedResponse
- EndpointListResponse
- EndpointStatusResponse
- JobCreatedResponse
- JobListResponse
- JobStatusResponse
context_file: json-ld/amazon-neptune-ml-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-ml-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Neptune Ml from Amazon Neptune.
layout: jsonld
name: Amazon Neptune Ml Context
namespaces:
- prefix: neptune
  uri: https://neptune.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: arn
  type: string
- container: ''
  name: baseProcessingInstanceType
  type: string
- container: ''
  name: baseProcessingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: cloudwatchLogUrl
  type: string
- container: ''
  name: configFileName
  type: string
- container: ''
  name: customModelTrainingParameters
  type: reference
- container: ''
  name: customModelTransformParameters
  type: reference
- container: ''
  name: dataProcessingJobId
  type: string
- container: ''
  name: enableInterContainerTrafficEncryption
  type: boolean
- container: ''
  name: enableManagedSpotTraining
  type: boolean
- container: ''
  name: endpoint
  type: reference
- container: ''
  name: endpointConfig
  type: reference
- container: ''
  name: failureReason
  type: string
- container: ''
  name: id
  type: string
- container: set
  name: ids
  type: string
- container: ''
  name: inputDataS3Location
  type: string
- container: ''
  name: instanceCount
  type: integer
- container: ''
  name: instanceType
  type: string
- container: ''
  name: maxHPONumberOfTrainingJobs
  type: integer
- container: ''
  name: maxHPOParallelTrainingJobs
  type: integer
- container: ''
  name: mlModelTrainingJobId
  type: string
- container: ''
  name: mlModelTransformJobId
  type: string
- container: ''
  name: modelName
  type: string
- container: ''
  name: modelTransformOutputS3Location
  type: string
- container: ''
  name: modelType
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: neptuneIamRoleArn
  type: string
- container: ''
  name: outputLocation
  type: string
- container: ''
  name: previousDataProcessingJobId
  type: string
- container: ''
  name: previousModelTrainingJobId
  type: string
- container: ''
  name: processedDataS3Location
  type: string
- container: ''
  name: processingInstanceType
  type: string
- container: ''
  name: processingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: processingJob
  type: reference
- container: ''
  name: processingTimeOutInSeconds
  type: integer
- container: ''
  name: s3OutputEncryptionKMSKey
  type: string
- container: ''
  name: sagemakerIamRoleArn
  type: string
- container: set
  name: securityGroupIds
  type: string
- container: ''
  name: sourceS3DirectoryPath
  type: string
- container: ''
  name: status
  type: string
- container: set
  name: subnets
  type: string
- container: ''
  name: trainModelS3Location
  type: string
- container: ''
  name: trainingEntryPointScript
  type: string
- container: ''
  name: trainingInstanceType
  type: string
- container: ''
  name: trainingInstanceVolumeSizeInGB
  type: integer
- container: ''
  name: trainingJobName
  type: string
- container: ''
  name: trainingTimeOutInSeconds
  type: integer
- container: ''
  name: transformEntryPointScript
  type: string
- container: ''
  name: update
  type: boolean
- container: ''
  name: volumeEncryptionKMSKey
  type: string
property_count: 50
provider_name: Amazon Neptune
provider_slug: amazon-neptune
slug: amazon-neptune-ml-context
source_filename: amazon-neptune-ml-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"neptune\": \"https://neptune.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateDataProcessingJobRequest\": \"neptune:CreateDataProcessingJobRequest\",\n    \"CreateInferenceEndpointRequest\": \"neptune:CreateInferenceEndpointRequest\",\n    \"CreateModelTrainingJobRequest\": \"neptune:CreateModelTrainingJobRequest\",\n    \"CreateModelTransformJobRequest\": \"neptune:CreateModelTransformJobRequest\",\n    \"EndpointCreatedResponse\": \"neptune:EndpointCreatedResponse\",\n    \"EndpointListResponse\": \"neptune:EndpointListResponse\",\n    \"EndpointStatusResponse\": \"neptune:EndpointStatusResponse\",\n    \"JobCreatedResponse\": \"neptune:JobCreatedResponse\",\n    \"JobListResponse\": \"neptune:JobListResponse\",\n    \"JobStatusResponse\": \"neptune:JobStatusResponse\",\n    \"arn\": {\n      \"@id\"\
  : \"neptune:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseProcessingInstanceType\": {\n      \"@id\": \"neptune:baseProcessingInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseProcessingInstanceVolumeSizeInGB\": {\n      \"@id\": \"neptune:baseProcessingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"cloudwatchLogUrl\": {\n      \"@id\": \"neptune:cloudwatchLogUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configFileName\": {\n      \"@id\": \"neptune:configFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customModelTrainingParameters\": {\n      \"@id\": \"neptune:customModelTrainingParameters\",\n      \"@type\": \"@id\"\n    },\n    \"customModelTransformParameters\": {\n      \"@id\": \"neptune:customModelTransformParameters\",\n      \"@type\": \"@id\"\n    },\n    \"dataProcessingJobId\": {\n      \"@id\": \"neptune:dataProcessingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enableInterContainerTrafficEncryption\"\
  : {\n      \"@id\": \"neptune:enableInterContainerTrafficEncryption\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"enableManagedSpotTraining\": {\n      \"@id\": \"neptune:enableManagedSpotTraining\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"endpoint\": {\n      \"@id\": \"neptune:endpoint\",\n      \"@type\": \"@id\"\n    },\n    \"endpointConfig\": {\n      \"@id\": \"neptune:endpointConfig\",\n      \"@type\": \"@id\"\n    },\n    \"failureReason\": {\n      \"@id\": \"neptune:failureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"neptune:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ids\": {\n      \"@id\": \"neptune:ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDataS3Location\": {\n      \"@id\": \"neptune:inputDataS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceCount\": {\n      \"@id\": \"neptune:instanceCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"instanceType\": {\n      \"@id\": \"neptune:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxHPONumberOfTrainingJobs\": {\n      \"@id\": \"neptune:maxHPONumberOfTrainingJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxHPOParallelTrainingJobs\": {\n      \"@id\": \"neptune:maxHPOParallelTrainingJobs\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mlModelTrainingJobId\": {\n      \"@id\": \"neptune:mlModelTrainingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mlModelTransformJobId\": {\n      \"@id\": \"neptune:mlModelTransformJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelName\": {\n      \"@id\": \"neptune:modelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelTransformOutputS3Location\": {\n      \"@id\": \"neptune:modelTransformOutputS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelType\": {\n      \"@id\": \"neptune:modelType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n \
  \     \"@id\": \"schema:name\"\n    },\n    \"neptuneIamRoleArn\": {\n      \"@id\": \"neptune:neptuneIamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputLocation\": {\n      \"@id\": \"neptune:outputLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousDataProcessingJobId\": {\n      \"@id\": \"neptune:previousDataProcessingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousModelTrainingJobId\": {\n      \"@id\": \"neptune:previousModelTrainingJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedDataS3Location\": {\n      \"@id\": \"neptune:processedDataS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingInstanceType\": {\n      \"@id\": \"neptune:processingInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processingInstanceVolumeSizeInGB\": {\n      \"@id\": \"neptune:processingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"processingJob\": {\n      \"@id\": \"neptune:processingJob\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"processingTimeOutInSeconds\": {\n      \"@id\": \"neptune:processingTimeOutInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"s3OutputEncryptionKMSKey\": {\n      \"@id\": \"neptune:s3OutputEncryptionKMSKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sagemakerIamRoleArn\": {\n      \"@id\": \"neptune:sagemakerIamRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"neptune:securityGroupIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceS3DirectoryPath\": {\n      \"@id\": \"neptune:sourceS3DirectoryPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"neptune:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnets\": {\n      \"@id\": \"neptune:subnets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainModelS3Location\": {\n      \"@id\": \"neptune:trainModelS3Location\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingEntryPointScript\": {\n      \"@id\": \"neptune:trainingEntryPointScript\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingInstanceType\": {\n      \"@id\": \"neptune:trainingInstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingInstanceVolumeSizeInGB\": {\n      \"@id\": \"neptune:trainingInstanceVolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainingJobName\": {\n      \"@id\": \"neptune:trainingJobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trainingTimeOutInSeconds\": {\n      \"@id\": \"neptune:trainingTimeOutInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transformEntryPointScript\": {\n      \"@id\": \"neptune:transformEntryPointScript\",\n      \"@type\": \"xsd:string\"\n    },\n    \"update\": {\n      \"@id\": \"neptune:update\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"volumeEncryptionKMSKey\": {\n      \"@id\": \"neptune:volumeEncryptionKMSKey\"\
  ,\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-neptune/refs/heads/main/json-ld/amazon-neptune-ml-context.jsonld
tags:
- Database
- Graph Database
- Gremlin
- Neptune
- Property Graph
- RDF
- SPARQL
- JSON-LD
- Linked Data
- Semantic Web
---
