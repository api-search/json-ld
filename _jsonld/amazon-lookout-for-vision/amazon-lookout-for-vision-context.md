---
api_specs:
- filename: amazon-lookout-for-vision-openapi-original.yaml
  format: yaml
  label: Amazon Lookout for Vision API
  slug: amazon-lookout-for-vision-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/openapi/amazon-lookout-for-vision-openapi-original.yaml
class_count: 70
classes:
- Anomaly
- CreateDatasetRequest
- CreateDatasetResponse
- CreateModelRequest
- CreateModelResponse
- CreateProjectRequest
- CreateProjectResponse
- DatasetDescription
- DatasetGroundTruthManifest
- DatasetImageStats
- DatasetMetadata
- DatasetSource
- DeleteDatasetRequest
- DeleteDatasetResponse
- DeleteModelRequest
- DeleteModelResponse
- DeleteProjectRequest
- DeleteProjectResponse
- DescribeDatasetRequest
- DescribeDatasetResponse
- DescribeModelPackagingJobRequest
- DescribeModelPackagingJobResponse
- DescribeModelRequest
- DescribeModelResponse
- DescribeProjectRequest
- DescribeProjectResponse
- DetectAnomaliesRequest
- DetectAnomaliesResponse
- DetectAnomalyResult
- GreengrassConfiguration
- GreengrassOutputDetails
- ImageSource
- InputS3Object
- ListDatasetEntriesRequest
- ListDatasetEntriesResponse
- ListModelPackagingJobsRequest
- ListModelPackagingJobsResponse
- ListModelsRequest
- ListModelsResponse
- ListProjectsRequest
- ListProjectsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ModelDescription
- ModelMetadata
- ModelPackagingConfiguration
- ModelPackagingDescription
- ModelPackagingJobMetadata
- ModelPackagingOutputDetails
- ModelPerformance
- OutputConfig
- OutputS3Object
- PixelAnomaly
- ProjectDescription
- ProjectMetadata
- S3Location
- StartModelPackagingJobRequest
- StartModelPackagingJobResponse
- StartModelRequest
- StartModelResponse
- StopModelRequest
- StopModelResponse
- Tag
- TagResourceRequest
- TagResourceResponse
- TargetPlatform
- UntagResourceRequest
- UntagResourceResponse
- UpdateDatasetEntriesRequest
- UpdateDatasetEntriesResponse
context_file: json-ld/amazon-lookout-for-vision-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/json-ld/amazon-lookout-for-vision-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lookout For Vision from Amazon Lookout for Vision.
layout: jsonld
name: Amazon Lookout For Vision Context
namespaces:
- prefix: alv
  uri: https://alv.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Accelerator
  type: ''
- container: ''
  name: Anomalies
  type: ''
- container: ''
  name: AnomalyMask
  type: ''
- container: ''
  name: Arch
  type: ''
- container: ''
  name: Body
  type: ''
- container: ''
  name: Bucket
  type: ''
- container: ''
  name: Changes
  type: ''
- container: ''
  name: Color
  type: ''
- container: ''
  name: CompilerOptions
  type: ''
- container: ''
  name: ComponentDescription
  type: ''
- container: ''
  name: ComponentName
  type: ''
- container: ''
  name: ComponentVersion
  type: ''
- container: ''
  name: ComponentVersionArn
  type: ''
- container: ''
  name: Confidence
  type: ''
- container: ''
  name: Configuration
  type: ''
- container: ''
  name: CreationTimestamp
  type: ''
- container: ''
  name: DatasetEntries
  type: ''
- container: ''
  name: DatasetType
  type: ''
- container: ''
  name: Datasets
  type: ''
- container: ''
  name: Description
  type: ''
- container: ''
  name: EvaluationEndTimestamp
  type: ''
- container: ''
  name: EvaluationManifest
  type: ''
- container: ''
  name: EvaluationResult
  type: ''
- container: ''
  name: F1Score
  type: ''
- container: ''
  name: Greengrass
  type: ''
- container: ''
  name: GroundTruthManifest
  type: ''
- container: ''
  name: ImageStats
  type: ''
- container: ''
  name: IsAnomalous
  type: ''
- container: ''
  name: JobName
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: KmsKeyId
  type: ''
- container: ''
  name: Labeled
  type: ''
- container: ''
  name: LastUpdatedTimestamp
  type: ''
- container: ''
  name: MaxInferenceUnits
  type: ''
- container: ''
  name: MinInferenceUnits
  type: ''
- container: ''
  name: ModelArn
  type: ''
- container: ''
  name: ModelPackagingJobDescription
  type: ''
- container: ''
  name: ModelPackagingJobs
  type: ''
- container: ''
  name: ModelPackagingMethod
  type: ''
- container: ''
  name: ModelVersion
  type: ''
- container: ''
  name: Models
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: Normal
  type: ''
- container: ''
  name: Os
  type: ''
- container: ''
  name: Performance
  type: ''
- container: ''
  name: Precision
  type: ''
- container: ''
  name: Prefix
  type: ''
- container: ''
  name: ProjectArn
  type: ''
- container: ''
  name: ProjectName
  type: ''
- container: ''
  name: Projects
  type: ''
- container: ''
  name: Recall
  type: ''
- container: ''
  name: S3Object
  type: ''
- container: ''
  name: S3OutputLocation
  type: ''
- container: ''
  name: Source
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: StatusMessage
  type: ''
- container: ''
  name: Tags
  type: ''
- container: ''
  name: TargetDevice
  type: ''
- container: ''
  name: Total
  type: ''
- container: ''
  name: TotalPercentageArea
  type: ''
- container: ''
  name: Type
  type: ''
- container: ''
  name: Value
  type: ''
- container: ''
  name: VersionId
  type: ''
property_count: 64
provider_name: Amazon Lookout for Vision
provider_slug: amazon-lookout-for-vision
slug: amazon-lookout-for-vision-context
source_filename: amazon-lookout-for-vision-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alv\": \"https://alv.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Anomaly\": \"alv:Anomaly\",\n    \"CreateDatasetRequest\": \"alv:CreateDatasetRequest\",\n    \"CreateDatasetResponse\": \"alv:CreateDatasetResponse\",\n    \"CreateModelRequest\": \"alv:CreateModelRequest\",\n    \"CreateModelResponse\": \"alv:CreateModelResponse\",\n    \"CreateProjectRequest\": \"alv:CreateProjectRequest\",\n    \"CreateProjectResponse\": \"alv:CreateProjectResponse\",\n    \"DatasetDescription\": \"alv:DatasetDescription\",\n    \"DatasetGroundTruthManifest\": \"alv:DatasetGroundTruthManifest\",\n    \"DatasetImageStats\": \"alv:DatasetImageStats\",\n    \"DatasetMetadata\": \"alv:DatasetMetadata\",\n    \"DatasetSource\": \"alv:DatasetSource\",\n    \"DeleteDatasetRequest\": \"alv:DeleteDatasetRequest\",\n \
  \   \"DeleteDatasetResponse\": \"alv:DeleteDatasetResponse\",\n    \"DeleteModelRequest\": \"alv:DeleteModelRequest\",\n    \"DeleteModelResponse\": \"alv:DeleteModelResponse\",\n    \"DeleteProjectRequest\": \"alv:DeleteProjectRequest\",\n    \"DeleteProjectResponse\": \"alv:DeleteProjectResponse\",\n    \"DescribeDatasetRequest\": \"alv:DescribeDatasetRequest\",\n    \"DescribeDatasetResponse\": \"alv:DescribeDatasetResponse\",\n    \"DescribeModelPackagingJobRequest\": \"alv:DescribeModelPackagingJobRequest\",\n    \"DescribeModelPackagingJobResponse\": \"alv:DescribeModelPackagingJobResponse\",\n    \"DescribeModelRequest\": \"alv:DescribeModelRequest\",\n    \"DescribeModelResponse\": \"alv:DescribeModelResponse\",\n    \"DescribeProjectRequest\": \"alv:DescribeProjectRequest\",\n    \"DescribeProjectResponse\": \"alv:DescribeProjectResponse\",\n    \"DetectAnomaliesRequest\": \"alv:DetectAnomaliesRequest\",\n    \"DetectAnomaliesResponse\": \"alv:DetectAnomaliesResponse\",\n    \"\
  DetectAnomalyResult\": \"alv:DetectAnomalyResult\",\n    \"GreengrassConfiguration\": \"alv:GreengrassConfiguration\",\n    \"GreengrassOutputDetails\": \"alv:GreengrassOutputDetails\",\n    \"ImageSource\": \"alv:ImageSource\",\n    \"InputS3Object\": \"alv:InputS3Object\",\n    \"ListDatasetEntriesRequest\": \"alv:ListDatasetEntriesRequest\",\n    \"ListDatasetEntriesResponse\": \"alv:ListDatasetEntriesResponse\",\n    \"ListModelPackagingJobsRequest\": \"alv:ListModelPackagingJobsRequest\",\n    \"ListModelPackagingJobsResponse\": \"alv:ListModelPackagingJobsResponse\",\n    \"ListModelsRequest\": \"alv:ListModelsRequest\",\n    \"ListModelsResponse\": \"alv:ListModelsResponse\",\n    \"ListProjectsRequest\": \"alv:ListProjectsRequest\",\n    \"ListProjectsResponse\": \"alv:ListProjectsResponse\",\n    \"ListTagsForResourceRequest\": \"alv:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"alv:ListTagsForResourceResponse\",\n    \"ModelDescription\": \"alv:ModelDescription\"\
  ,\n    \"ModelMetadata\": \"alv:ModelMetadata\",\n    \"ModelPackagingConfiguration\": \"alv:ModelPackagingConfiguration\",\n    \"ModelPackagingDescription\": \"alv:ModelPackagingDescription\",\n    \"ModelPackagingJobMetadata\": \"alv:ModelPackagingJobMetadata\",\n    \"ModelPackagingOutputDetails\": \"alv:ModelPackagingOutputDetails\",\n    \"ModelPerformance\": \"alv:ModelPerformance\",\n    \"OutputConfig\": \"alv:OutputConfig\",\n    \"OutputS3Object\": \"alv:OutputS3Object\",\n    \"PixelAnomaly\": \"alv:PixelAnomaly\",\n    \"ProjectDescription\": \"alv:ProjectDescription\",\n    \"ProjectMetadata\": \"alv:ProjectMetadata\",\n    \"S3Location\": \"alv:S3Location\",\n    \"StartModelPackagingJobRequest\": \"alv:StartModelPackagingJobRequest\",\n    \"StartModelPackagingJobResponse\": \"alv:StartModelPackagingJobResponse\",\n    \"StartModelRequest\": \"alv:StartModelRequest\",\n    \"StartModelResponse\": \"alv:StartModelResponse\",\n    \"StopModelRequest\": \"alv:StopModelRequest\"\
  ,\n    \"StopModelResponse\": \"alv:StopModelResponse\",\n    \"Tag\": \"alv:Tag\",\n    \"TagResourceRequest\": \"alv:TagResourceRequest\",\n    \"TagResourceResponse\": \"alv:TagResourceResponse\",\n    \"TargetPlatform\": \"alv:TargetPlatform\",\n    \"UntagResourceRequest\": \"alv:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"alv:UntagResourceResponse\",\n    \"UpdateDatasetEntriesRequest\": \"alv:UpdateDatasetEntriesRequest\",\n    \"UpdateDatasetEntriesResponse\": \"alv:UpdateDatasetEntriesResponse\",\n    \"Accelerator\": {\n      \"@id\": \"alv:Accelerator\"\n    },\n    \"Anomalies\": {\n      \"@id\": \"alv:Anomalies\"\n    },\n    \"AnomalyMask\": {\n      \"@id\": \"alv:AnomalyMask\"\n    },\n    \"Arch\": {\n      \"@id\": \"alv:Arch\"\n    },\n    \"Body\": {\n      \"@id\": \"alv:Body\"\n    },\n    \"Bucket\": {\n      \"@id\": \"alv:Bucket\"\n    },\n    \"Changes\": {\n      \"@id\": \"alv:Changes\"\n    },\n    \"Color\": {\n      \"@id\": \"alv:Color\"\n\
  \    },\n    \"CompilerOptions\": {\n      \"@id\": \"alv:CompilerOptions\"\n    },\n    \"ComponentDescription\": {\n      \"@id\": \"alv:ComponentDescription\"\n    },\n    \"ComponentName\": {\n      \"@id\": \"alv:ComponentName\"\n    },\n    \"ComponentVersion\": {\n      \"@id\": \"alv:ComponentVersion\"\n    },\n    \"ComponentVersionArn\": {\n      \"@id\": \"alv:ComponentVersionArn\"\n    },\n    \"Confidence\": {\n      \"@id\": \"alv:Confidence\"\n    },\n    \"Configuration\": {\n      \"@id\": \"alv:Configuration\"\n    },\n    \"CreationTimestamp\": {\n      \"@id\": \"alv:CreationTimestamp\"\n    },\n    \"DatasetEntries\": {\n      \"@id\": \"alv:DatasetEntries\"\n    },\n    \"DatasetType\": {\n      \"@id\": \"alv:DatasetType\"\n    },\n    \"Datasets\": {\n      \"@id\": \"alv:Datasets\"\n    },\n    \"Description\": {\n      \"@id\": \"alv:Description\"\n    },\n    \"EvaluationEndTimestamp\": {\n      \"@id\": \"alv:EvaluationEndTimestamp\"\n    },\n    \"EvaluationManifest\"\
  : {\n      \"@id\": \"alv:EvaluationManifest\"\n    },\n    \"EvaluationResult\": {\n      \"@id\": \"alv:EvaluationResult\"\n    },\n    \"F1Score\": {\n      \"@id\": \"alv:F1Score\"\n    },\n    \"Greengrass\": {\n      \"@id\": \"alv:Greengrass\"\n    },\n    \"GroundTruthManifest\": {\n      \"@id\": \"alv:GroundTruthManifest\"\n    },\n    \"ImageStats\": {\n      \"@id\": \"alv:ImageStats\"\n    },\n    \"IsAnomalous\": {\n      \"@id\": \"alv:IsAnomalous\"\n    },\n    \"JobName\": {\n      \"@id\": \"alv:JobName\"\n    },\n    \"Key\": {\n      \"@id\": \"alv:Key\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"alv:KmsKeyId\"\n    },\n    \"Labeled\": {\n      \"@id\": \"alv:Labeled\"\n    },\n    \"LastUpdatedTimestamp\": {\n      \"@id\": \"alv:LastUpdatedTimestamp\"\n    },\n    \"MaxInferenceUnits\": {\n      \"@id\": \"alv:MaxInferenceUnits\"\n    },\n    \"MinInferenceUnits\": {\n      \"@id\": \"alv:MinInferenceUnits\"\n    },\n    \"ModelArn\": {\n      \"@id\": \"alv:ModelArn\"\
  \n    },\n    \"ModelPackagingJobDescription\": {\n      \"@id\": \"alv:ModelPackagingJobDescription\"\n    },\n    \"ModelPackagingJobs\": {\n      \"@id\": \"alv:ModelPackagingJobs\"\n    },\n    \"ModelPackagingMethod\": {\n      \"@id\": \"alv:ModelPackagingMethod\"\n    },\n    \"ModelVersion\": {\n      \"@id\": \"alv:ModelVersion\"\n    },\n    \"Models\": {\n      \"@id\": \"alv:Models\"\n    },\n    \"Name\": {\n      \"@id\": \"alv:Name\"\n    },\n    \"NextToken\": {\n      \"@id\": \"alv:NextToken\"\n    },\n    \"Normal\": {\n      \"@id\": \"alv:Normal\"\n    },\n    \"Os\": {\n      \"@id\": \"alv:Os\"\n    },\n    \"Performance\": {\n      \"@id\": \"alv:Performance\"\n    },\n    \"Precision\": {\n      \"@id\": \"alv:Precision\"\n    },\n    \"Prefix\": {\n      \"@id\": \"alv:Prefix\"\n    },\n    \"ProjectArn\": {\n      \"@id\": \"alv:ProjectArn\"\n    },\n    \"ProjectName\": {\n      \"@id\": \"alv:ProjectName\"\n    },\n    \"Projects\": {\n      \"@id\": \"alv:Projects\"\
  \n    },\n    \"Recall\": {\n      \"@id\": \"alv:Recall\"\n    },\n    \"S3Object\": {\n      \"@id\": \"alv:S3Object\"\n    },\n    \"S3OutputLocation\": {\n      \"@id\": \"alv:S3OutputLocation\"\n    },\n    \"Source\": {\n      \"@id\": \"alv:Source\"\n    },\n    \"Status\": {\n      \"@id\": \"alv:Status\"\n    },\n    \"StatusMessage\": {\n      \"@id\": \"alv:StatusMessage\"\n    },\n    \"Tags\": {\n      \"@id\": \"alv:Tags\"\n    },\n    \"TargetDevice\": {\n      \"@id\": \"alv:TargetDevice\"\n    },\n    \"Total\": {\n      \"@id\": \"alv:Total\"\n    },\n    \"TotalPercentageArea\": {\n      \"@id\": \"alv:TotalPercentageArea\"\n    },\n    \"Type\": {\n      \"@id\": \"alv:Type\"\n    },\n    \"Value\": {\n      \"@id\": \"alv:Value\"\n    },\n    \"VersionId\": {\n      \"@id\": \"alv:VersionId\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-vision/refs/heads/main/json-ld/amazon-lookout-for-vision-context.jsonld
tags:
- Computer Vision
- Machine Learning
- Manufacturing
- Quality Inspection
- Anomaly Detection
- JSON-LD
- Linked Data
- Semantic Web
---
