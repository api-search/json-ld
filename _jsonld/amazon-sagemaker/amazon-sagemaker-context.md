---
api_specs:
- filename: amazon-sagemaker-openapi.yml
  format: yaml
  label: Amazon SageMaker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-sagemaker/refs/heads/main/openapi/amazon-sagemaker-openapi.yml
class_count: 5
classes:
- Tag
- NotebookInstance
- TrainingJob
- Model
- Endpoint
context_file: json-ld/amazon-sagemaker-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-sagemaker/refs/heads/main/json-ld/amazon-sagemaker-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Sagemaker from Amazon SageMaker.
layout: jsonld
name: Amazon Sagemaker Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: NotebookInstanceArn
  type: string
- container: ''
  name: NotebookInstanceName
  type: string
- container: ''
  name: NotebookInstanceStatus
  type: string
- container: ''
  name: InstanceType
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: SubnetId
  type: string
- container: set
  name: SecurityGroups
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: VolumeSizeInGB
  type: integer
- container: ''
  name: CreationTime
  type: dateTime
- container: ''
  name: LastModifiedTime
  type: dateTime
- container: ''
  name: TrainingJobName
  type: string
- container: ''
  name: TrainingJobArn
  type: string
- container: ''
  name: TrainingJobStatus
  type: string
- container: ''
  name: SecondaryStatus
  type: string
- container: ''
  name: AlgorithmSpecification
  type: string
- container: ''
  name: TrainingImage
  type: string
- container: ''
  name: TrainingInputMode
  type: string
- container: ''
  name: AlgorithmName
  type: string
- container: set
  name: InputDataConfig
  type: string
- container: ''
  name: OutputDataConfig
  type: string
- container: ''
  name: S3OutputPath
  type: string
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: ResourceConfig
  type: string
- container: ''
  name: InstanceCount
  type: integer
- container: ''
  name: StoppingCondition
  type: string
- container: ''
  name: MaxRuntimeInSeconds
  type: integer
- container: ''
  name: MaxWaitTimeInSeconds
  type: integer
- container: ''
  name: HyperParameters
  type: string
- container: ''
  name: ModelArtifacts
  type: string
- container: ''
  name: S3ModelArtifacts
  type: string
- container: ''
  name: TrainingStartTime
  type: dateTime
- container: ''
  name: TrainingEndTime
  type: dateTime
- container: ''
  name: BillableTimeInSeconds
  type: integer
- container: ''
  name: FailureReason
  type: string
- container: ''
  name: ModelName
  type: string
- container: ''
  name: ModelArn
  type: string
- container: ''
  name: PrimaryContainer
  type: string
- container: ''
  name: Image
  type: string
- container: ''
  name: ModelDataUrl
  type: string
- container: ''
  name: Environment
  type: string
- container: ''
  name: ExecutionRoleArn
  type: string
- container: ''
  name: EndpointName
  type: string
- container: ''
  name: EndpointArn
  type: string
- container: ''
  name: EndpointConfigName
  type: string
- container: ''
  name: EndpointStatus
  type: string
- container: set
  name: ProductionVariants
  type: string
property_count: 49
provider_name: Amazon SageMaker
provider_slug: amazon-sagemaker
slug: amazon-sagemaker-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Tag\": \"aws:Tag\",\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotebookInstance\": \"aws:NotebookInstance\",\n    \"NotebookInstanceArn\": {\n      \"@id\": \"aws:NotebookInstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotebookInstanceName\": {\n      \"@id\": \"aws:NotebookInstanceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotebookInstanceStatus\": {\n      \"@id\": \"aws:NotebookInstanceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceType\": {\n      \"@id\": \"aws:InstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n     \
  \ \"@id\": \"aws:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetId\": {\n      \"@id\": \"aws:SubnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroups\": {\n      \"@id\": \"aws:SecurityGroups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"aws:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VolumeSizeInGB\": {\n      \"@id\": \"aws:VolumeSizeInGB\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"aws:CreationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastModifiedTime\": {\n      \"@id\": \"aws:LastModifiedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"TrainingJob\": \"aws:TrainingJob\",\n    \"TrainingJobName\": {\n      \"@id\": \"aws:TrainingJobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrainingJobArn\": {\n      \"@id\": \"aws:TrainingJobArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrainingJobStatus\"\
  : {\n      \"@id\": \"aws:TrainingJobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecondaryStatus\": {\n      \"@id\": \"aws:SecondaryStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlgorithmSpecification\": {\n      \"@id\": \"aws:AlgorithmSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrainingImage\": {\n      \"@id\": \"aws:TrainingImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrainingInputMode\": {\n      \"@id\": \"aws:TrainingInputMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlgorithmName\": {\n      \"@id\": \"aws:AlgorithmName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputDataConfig\": {\n      \"@id\": \"aws:InputDataConfig\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputDataConfig\": {\n      \"@id\": \"aws:OutputDataConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3OutputPath\": {\n      \"@id\": \"aws:S3OutputPath\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"KmsKeyId\": {\n      \"@id\": \"aws:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceConfig\": {\n      \"@id\": \"aws:ResourceConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceCount\": {\n      \"@id\": \"aws:InstanceCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"StoppingCondition\": {\n      \"@id\": \"aws:StoppingCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxRuntimeInSeconds\": {\n      \"@id\": \"aws:MaxRuntimeInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MaxWaitTimeInSeconds\": {\n      \"@id\": \"aws:MaxWaitTimeInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HyperParameters\": {\n      \"@id\": \"aws:HyperParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModelArtifacts\": {\n      \"@id\": \"aws:ModelArtifacts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3ModelArtifacts\": {\n      \"@id\": \"aws:S3ModelArtifacts\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"TrainingStartTime\": {\n      \"@id\": \"aws:TrainingStartTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"TrainingEndTime\": {\n      \"@id\": \"aws:TrainingEndTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"BillableTimeInSeconds\": {\n      \"@id\": \"aws:BillableTimeInSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"FailureReason\": {\n      \"@id\": \"aws:FailureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Model\": \"aws:Model\",\n    \"ModelName\": {\n      \"@id\": \"aws:ModelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModelArn\": {\n      \"@id\": \"aws:ModelArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrimaryContainer\": {\n      \"@id\": \"aws:PrimaryContainer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Image\": {\n      \"@id\": \"aws:Image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModelDataUrl\": {\n      \"@id\": \"aws:ModelDataUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  Environment\": {\n      \"@id\": \"aws:Environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExecutionRoleArn\": {\n      \"@id\": \"aws:ExecutionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Endpoint\": \"aws:Endpoint\",\n    \"EndpointName\": {\n      \"@id\": \"aws:EndpointName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointArn\": {\n      \"@id\": \"aws:EndpointArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointConfigName\": {\n      \"@id\": \"aws:EndpointConfigName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointStatus\": {\n      \"@id\": \"aws:EndpointStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProductionVariants\": {\n      \"@id\": \"aws:ProductionVariants\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-sagemaker/refs/heads/main/json-ld/amazon-sagemaker-context.jsonld
tags:
- AI
- AWS
- Inference
- Machine Learning
- MLOps
- Training
- JSON-LD
- Linked Data
- Semantic Web
---
