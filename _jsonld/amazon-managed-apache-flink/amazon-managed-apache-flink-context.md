---
api_specs:
- filename: amazon-managed-apache-flink-openapi-original.yaml
  format: yaml
  label: Amazon Managed Service for Apache Flink API
  slug: aws-managed-flink-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/openapi/amazon-managed-apache-flink-openapi-original.yaml
class_count: 182
classes:
- AddApplicationCloudWatchLoggingOptionRequest
- AddApplicationCloudWatchLoggingOptionResponse
- AddApplicationInputProcessingConfigurationRequest
- AddApplicationInputProcessingConfigurationResponse
- AddApplicationInputRequest
- AddApplicationInputResponse
- AddApplicationOutputRequest
- AddApplicationOutputResponse
- AddApplicationReferenceDataSourceRequest
- AddApplicationReferenceDataSourceResponse
- AddApplicationVpcConfigurationRequest
- AddApplicationVpcConfigurationResponse
- ApplicationCodeConfiguration
- ApplicationCodeConfigurationDescription
- ApplicationCodeConfigurationUpdate
- ApplicationConfiguration
- ApplicationConfigurationDescription
- ApplicationConfigurationUpdate
- ApplicationDetail
- ApplicationMaintenanceConfigurationDescription
- ApplicationMaintenanceConfigurationUpdate
- ApplicationRestoreConfiguration
- ApplicationSnapshotConfiguration
- ApplicationSnapshotConfigurationDescription
- ApplicationSnapshotConfigurationUpdate
- ApplicationSummary
- ApplicationVersionSummary
- CSVMappingParameters
- CatalogConfiguration
- CatalogConfigurationDescription
- CatalogConfigurationUpdate
- CheckpointConfiguration
- CheckpointConfigurationDescription
- CheckpointConfigurationUpdate
- CloudWatchLoggingOption
- CloudWatchLoggingOptionDescription
- CloudWatchLoggingOptionUpdate
- CodeContent
- CodeContentDescription
- CodeContentUpdate
- CreateApplicationPresignedUrlRequest
- CreateApplicationPresignedUrlResponse
- CreateApplicationRequest
- CreateApplicationResponse
- CreateApplicationSnapshotRequest
- CreateApplicationSnapshotResponse
- CustomArtifactConfiguration
- CustomArtifactConfigurationDescription
- DeleteApplicationCloudWatchLoggingOptionRequest
- DeleteApplicationCloudWatchLoggingOptionResponse
- DeleteApplicationInputProcessingConfigurationRequest
- DeleteApplicationInputProcessingConfigurationResponse
- DeleteApplicationOutputRequest
- DeleteApplicationOutputResponse
- DeleteApplicationReferenceDataSourceRequest
- DeleteApplicationReferenceDataSourceResponse
- DeleteApplicationRequest
- DeleteApplicationResponse
- DeleteApplicationSnapshotRequest
- DeleteApplicationSnapshotResponse
- DeleteApplicationVpcConfigurationRequest
- DeleteApplicationVpcConfigurationResponse
- DeployAsApplicationConfiguration
- DeployAsApplicationConfigurationDescription
- DeployAsApplicationConfigurationUpdate
- DescribeApplicationRequest
- DescribeApplicationResponse
- DescribeApplicationSnapshotRequest
- DescribeApplicationSnapshotResponse
- DescribeApplicationVersionRequest
- DescribeApplicationVersionResponse
- DestinationSchema
- DiscoverInputSchemaRequest
- DiscoverInputSchemaResponse
- EnvironmentProperties
- EnvironmentPropertyDescriptions
- EnvironmentPropertyUpdates
- FlinkApplicationConfiguration
- FlinkApplicationConfigurationDescription
- FlinkApplicationConfigurationUpdate
- FlinkRunConfiguration
- GlueDataCatalogConfiguration
- GlueDataCatalogConfigurationDescription
- GlueDataCatalogConfigurationUpdate
- Input
- InputDescription
- InputLambdaProcessor
- InputLambdaProcessorDescription
- InputLambdaProcessorUpdate
- InputParallelism
- InputParallelismUpdate
- InputProcessingConfiguration
- InputProcessingConfigurationDescription
- InputProcessingConfigurationUpdate
- InputSchemaUpdate
- InputStartingPositionConfiguration
- InputUpdate
- JSONMappingParameters
- KinesisFirehoseInput
- KinesisFirehoseInputDescription
- KinesisFirehoseInputUpdate
- KinesisFirehoseOutput
- KinesisFirehoseOutputDescription
- KinesisFirehoseOutputUpdate
- KinesisStreamsInput
- KinesisStreamsInputDescription
- KinesisStreamsInputUpdate
- KinesisStreamsOutput
- KinesisStreamsOutputDescription
- KinesisStreamsOutputUpdate
- LambdaOutput
- LambdaOutputDescription
- LambdaOutputUpdate
- ListApplicationSnapshotsRequest
- ListApplicationSnapshotsResponse
- ListApplicationVersionsRequest
- ListApplicationVersionsResponse
- ListApplicationsRequest
- ListApplicationsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- MappingParameters
- MavenReference
- MonitoringConfiguration
- MonitoringConfigurationDescription
- MonitoringConfigurationUpdate
- Output
- OutputDescription
- OutputUpdate
- ParallelismConfiguration
- ParallelismConfigurationDescription
- ParallelismConfigurationUpdate
- PropertyGroup
- PropertyMap
- RecordColumn
- RecordFormat
- ReferenceDataSource
- ReferenceDataSourceDescription
- ReferenceDataSourceUpdate
- RollbackApplicationRequest
- RollbackApplicationResponse
- RunConfiguration
- RunConfigurationDescription
- RunConfigurationUpdate
- S3ApplicationCodeLocationDescription
- S3Configuration
- S3ContentBaseLocation
- S3ContentBaseLocationDescription
- S3ContentBaseLocationUpdate
- S3ContentLocation
- S3ContentLocationUpdate
- S3ReferenceDataSource
- S3ReferenceDataSourceDescription
- S3ReferenceDataSourceUpdate
- SnapshotDetails
- SourceSchema
- SqlApplicationConfiguration
- SqlApplicationConfigurationDescription
- SqlApplicationConfigurationUpdate
- SqlRunConfiguration
- StartApplicationRequest
- StartApplicationResponse
- StopApplicationRequest
- StopApplicationResponse
- Tag
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateApplicationMaintenanceConfigurationRequest
- UpdateApplicationMaintenanceConfigurationResponse
- UpdateApplicationRequest
- UpdateApplicationResponse
- VpcConfiguration
- VpcConfigurationDescription
- VpcConfigurationUpdate
- ZeppelinApplicationConfiguration
- ZeppelinApplicationConfigurationDescription
- ZeppelinApplicationConfigurationUpdate
- ZeppelinMonitoringConfiguration
- ZeppelinMonitoringConfigurationDescription
- ZeppelinMonitoringConfigurationUpdate
context_file: json-ld/amazon-managed-apache-flink-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/json-ld/amazon-managed-apache-flink-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Managed Apache Flink from Amazon Managed Service for Apache Flink.
layout: jsonld
name: Amazon Managed Apache Flink Context
namespaces:
- prefix: amsaf
  uri: https://amsaf.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AllowNonRestoredState
  type: ''
- container: ''
  name: ApplicationARN
  type: ''
- container: ''
  name: ApplicationDescription
  type: ''
- container: ''
  name: ApplicationMaintenanceWindowEndTime
  type: ''
- container: ''
  name: ApplicationMaintenanceWindowStartTime
  type: ''
- container: ''
  name: ApplicationMaintenanceWindowStartTimeUpdate
  type: ''
- container: ''
  name: ApplicationMode
  type: ''
- container: ''
  name: ApplicationName
  type: ''
- container: ''
  name: ApplicationRestoreConfigurationDescription
  type: ''
- container: ''
  name: ApplicationRestoreType
  type: ''
- container: ''
  name: ApplicationStatus
  type: ''
- container: ''
  name: ApplicationSummaries
  type: ''
- container: ''
  name: ApplicationVersionDetail
  type: ''
- container: ''
  name: ApplicationVersionId
  type: ''
- container: ''
  name: ApplicationVersionRolledBackFrom
  type: ''
- container: ''
  name: ApplicationVersionRolledBackTo
  type: ''
- container: ''
  name: ApplicationVersionSummaries
  type: ''
- container: ''
  name: ApplicationVersionUpdatedFrom
  type: ''
- container: ''
  name: ArtifactId
  type: ''
- container: ''
  name: ArtifactType
  type: ''
- container: ''
  name: AuthorizedUrl
  type: ''
- container: ''
  name: AutoScalingEnabled
  type: ''
- container: ''
  name: AutoScalingEnabledUpdate
  type: ''
- container: ''
  name: BasePath
  type: ''
- container: ''
  name: BasePathUpdate
  type: ''
- container: ''
  name: BucketARN
  type: ''
- container: ''
  name: BucketARNUpdate
  type: ''
- container: ''
  name: CheckpointInterval
  type: ''
- container: ''
  name: CheckpointIntervalUpdate
  type: ''
- container: ''
  name: CheckpointingEnabled
  type: ''
- container: ''
  name: CheckpointingEnabledUpdate
  type: ''
- container: ''
  name: CloudWatchLoggingOptionDescriptions
  type: ''
- container: ''
  name: CloudWatchLoggingOptionId
  type: ''
- container: ''
  name: CloudWatchLoggingOptionUpdates
  type: ''
- container: ''
  name: CloudWatchLoggingOptions
  type: ''
- container: ''
  name: CodeContentType
  type: ''
- container: ''
  name: CodeContentTypeUpdate
  type: ''
- container: ''
  name: CodeMD5
  type: ''
- container: ''
  name: CodeSize
  type: ''
- container: ''
  name: ConditionalToken
  type: ''
- container: ''
  name: ConfigurationType
  type: ''
- container: ''
  name: ConfigurationTypeUpdate
  type: ''
- container: ''
  name: Count
  type: ''
- container: ''
  name: CountUpdate
  type: ''
- container: ''
  name: CreateTimestamp
  type: ''
- container: ''
  name: CurrentApplicationVersionId
  type: ''
- container: ''
  name: CurrentParallelism
  type: ''
- container: ''
  name: CustomArtifactsConfiguration
  type: ''
- container: ''
  name: CustomArtifactsConfigurationDescription
  type: ''
- container: ''
  name: CustomArtifactsConfigurationUpdate
  type: ''
- container: ''
  name: DatabaseARN
  type: ''
- container: ''
  name: DatabaseARNUpdate
  type: ''
- container: ''
  name: DestinationSchemaUpdate
  type: ''
- container: ''
  name: FileKey
  type: ''
- container: ''
  name: FileKeyUpdate
  type: ''
- container: ''
  name: FlinkRunConfigurationDescription
  type: ''
- container: ''
  name: Force
  type: ''
- container: ''
  name: GroupId
  type: ''
- container: ''
  name: InAppStreamNames
  type: ''
- container: ''
  name: IncludeAdditionalDetails
  type: ''
- container: ''
  name: InputDescriptions
  type: ''
- container: ''
  name: InputId
  type: ''
- container: ''
  name: InputSchema
  type: ''
- container: ''
  name: InputStartingPosition
  type: ''
- container: ''
  name: InputUpdates
  type: ''
- container: ''
  name: Inputs
  type: ''
- container: ''
  name: JobPlanDescription
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: LastUpdateTimestamp
  type: ''
- container: ''
  name: Limit
  type: ''
- container: ''
  name: LogLevel
  type: ''
- container: ''
  name: LogLevelUpdate
  type: ''
- container: ''
  name: LogStreamARN
  type: ''
- container: ''
  name: LogStreamARNUpdate
  type: ''
- container: ''
  name: Mapping
  type: ''
- container: ''
  name: MavenReferenceDescription
  type: ''
- container: ''
  name: MetricsLevel
  type: ''
- container: ''
  name: MetricsLevelUpdate
  type: ''
- container: ''
  name: MinPauseBetweenCheckpoints
  type: ''
- container: ''
  name: MinPauseBetweenCheckpointsUpdate
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: NamePrefix
  type: ''
- container: ''
  name: NamePrefixUpdate
  type: ''
- container: ''
  name: NameUpdate
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: ObjectVersion
  type: ''
- container: ''
  name: ObjectVersionUpdate
  type: ''
- container: ''
  name: OutputDescriptions
  type: ''
- container: ''
  name: OutputId
  type: ''
- container: ''
  name: OutputUpdates
  type: ''
- container: ''
  name: Outputs
  type: ''
- container: ''
  name: Parallelism
  type: ''
- container: ''
  name: ParallelismPerKPU
  type: ''
- container: ''
  name: ParallelismPerKPUUpdate
  type: ''
- container: ''
  name: ParallelismUpdate
  type: ''
- container: ''
  name: ParsedInputRecords
  type: ''
- container: ''
  name: ProcessedInputRecords
  type: ''
- container: ''
  name: PropertyGroupDescriptions
  type: ''
- container: ''
  name: PropertyGroupId
  type: ''
- container: ''
  name: PropertyGroups
  type: ''
- container: ''
  name: RawInputRecords
  type: ''
- container: ''
  name: RecordColumnDelimiter
  type: ''
- container: ''
  name: RecordColumnUpdates
  type: ''
- container: ''
  name: RecordColumns
  type: ''
- container: ''
  name: RecordEncoding
  type: ''
- container: ''
  name: RecordEncodingUpdate
  type: ''
- container: ''
  name: RecordFormatType
  type: ''
- container: ''
  name: RecordFormatUpdate
  type: ''
- container: ''
  name: RecordRowDelimiter
  type: ''
- container: ''
  name: RecordRowPath
  type: ''
- container: ''
  name: ReferenceDataSourceDescriptions
  type: ''
- container: ''
  name: ReferenceDataSourceUpdates
  type: ''
- container: ''
  name: ReferenceDataSources
  type: ''
- container: ''
  name: ReferenceId
  type: ''
- container: ''
  name: ReferenceRoleARN
  type: ''
- container: ''
  name: ReferenceSchema
  type: ''
- container: ''
  name: ReferenceSchemaUpdate
  type: ''
- container: ''
  name: ResourceARN
  type: ''
- container: ''
  name: ResourceARNUpdate
  type: ''
- container: ''
  name: RoleARN
  type: ''
- container: ''
  name: RuntimeEnvironment
  type: ''
- container: ''
  name: S3ContentLocationDescription
  type: ''
- container: ''
  name: SecurityGroupIdUpdates
  type: ''
- container: ''
  name: SecurityGroupIds
  type: ''
- container: ''
  name: ServiceExecutionRole
  type: ''
- container: ''
  name: ServiceExecutionRoleUpdate
  type: ''
- container: ''
  name: SessionExpirationDurationInSeconds
  type: ''
- container: ''
  name: SnapshotCreationTimestamp
  type: ''
- container: ''
  name: SnapshotName
  type: ''
- container: ''
  name: SnapshotStatus
  type: ''
- container: ''
  name: SnapshotSummaries
  type: ''
- container: ''
  name: SnapshotsEnabled
  type: ''
- container: ''
  name: SnapshotsEnabledUpdate
  type: ''
- container: ''
  name: SqlRunConfigurations
  type: ''
- container: ''
  name: SqlType
  type: ''
- container: ''
  name: SubnetIdUpdates
  type: ''
- container: ''
  name: SubnetIds
  type: ''
- container: ''
  name: TableName
  type: ''
- container: ''
  name: TableNameUpdate
  type: ''
- container: ''
  name: TagKeys
  type: ''
- container: ''
  name: Tags
  type: ''
- container: ''
  name: TextContent
  type: ''
- container: ''
  name: TextContentUpdate
  type: ''
- container: ''
  name: UrlType
  type: ''
- container: ''
  name: Value
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: VpcConfigurationDescriptions
  type: ''
- container: ''
  name: VpcConfigurationId
  type: ''
- container: ''
  name: VpcConfigurationUpdates
  type: ''
- container: ''
  name: VpcConfigurations
  type: ''
- container: ''
  name: VpcId
  type: ''
- container: ''
  name: ZipFileContent
  type: ''
- container: ''
  name: ZipFileContentUpdate
  type: ''
property_count: 153
provider_name: Amazon Managed Service for Apache Flink
provider_slug: amazon-managed-apache-flink
slug: amazon-managed-apache-flink-context
source_filename: amazon-managed-apache-flink-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amsaf\": \"https://amsaf.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddApplicationCloudWatchLoggingOptionRequest\": \"amsaf:AddApplicationCloudWatchLoggingOptionRequest\",\n    \"AddApplicationCloudWatchLoggingOptionResponse\": \"amsaf:AddApplicationCloudWatchLoggingOptionResponse\",\n    \"AddApplicationInputProcessingConfigurationRequest\": \"amsaf:AddApplicationInputProcessingConfigurationRequest\",\n    \"AddApplicationInputProcessingConfigurationResponse\": \"amsaf:AddApplicationInputProcessingConfigurationResponse\",\n    \"AddApplicationInputRequest\": \"amsaf:AddApplicationInputRequest\",\n    \"AddApplicationInputResponse\": \"amsaf:AddApplicationInputResponse\",\n    \"AddApplicationOutputRequest\": \"amsaf:AddApplicationOutputRequest\",\n    \"AddApplicationOutputResponse\": \"amsaf:AddApplicationOutputResponse\",\n    \"AddApplicationReferenceDataSourceRequest\"\
  : \"amsaf:AddApplicationReferenceDataSourceRequest\",\n    \"AddApplicationReferenceDataSourceResponse\": \"amsaf:AddApplicationReferenceDataSourceResponse\",\n    \"AddApplicationVpcConfigurationRequest\": \"amsaf:AddApplicationVpcConfigurationRequest\",\n    \"AddApplicationVpcConfigurationResponse\": \"amsaf:AddApplicationVpcConfigurationResponse\",\n    \"ApplicationCodeConfiguration\": \"amsaf:ApplicationCodeConfiguration\",\n    \"ApplicationCodeConfigurationDescription\": \"amsaf:ApplicationCodeConfigurationDescription\",\n    \"ApplicationCodeConfigurationUpdate\": \"amsaf:ApplicationCodeConfigurationUpdate\",\n    \"ApplicationConfiguration\": \"amsaf:ApplicationConfiguration\",\n    \"ApplicationConfigurationDescription\": \"amsaf:ApplicationConfigurationDescription\",\n    \"ApplicationConfigurationUpdate\": \"amsaf:ApplicationConfigurationUpdate\",\n    \"ApplicationDetail\": \"amsaf:ApplicationDetail\",\n    \"ApplicationMaintenanceConfigurationDescription\": \"amsaf:ApplicationMaintenanceConfigurationDescription\"\
  ,\n    \"ApplicationMaintenanceConfigurationUpdate\": \"amsaf:ApplicationMaintenanceConfigurationUpdate\",\n    \"ApplicationRestoreConfiguration\": \"amsaf:ApplicationRestoreConfiguration\",\n    \"ApplicationSnapshotConfiguration\": \"amsaf:ApplicationSnapshotConfiguration\",\n    \"ApplicationSnapshotConfigurationDescription\": \"amsaf:ApplicationSnapshotConfigurationDescription\",\n    \"ApplicationSnapshotConfigurationUpdate\": \"amsaf:ApplicationSnapshotConfigurationUpdate\",\n    \"ApplicationSummary\": \"amsaf:ApplicationSummary\",\n    \"ApplicationVersionSummary\": \"amsaf:ApplicationVersionSummary\",\n    \"CSVMappingParameters\": \"amsaf:CSVMappingParameters\",\n    \"CatalogConfiguration\": \"amsaf:CatalogConfiguration\",\n    \"CatalogConfigurationDescription\": \"amsaf:CatalogConfigurationDescription\",\n    \"CatalogConfigurationUpdate\": \"amsaf:CatalogConfigurationUpdate\",\n    \"CheckpointConfiguration\": \"amsaf:CheckpointConfiguration\",\n    \"CheckpointConfigurationDescription\"\
  : \"amsaf:CheckpointConfigurationDescription\",\n    \"CheckpointConfigurationUpdate\": \"amsaf:CheckpointConfigurationUpdate\",\n    \"CloudWatchLoggingOption\": \"amsaf:CloudWatchLoggingOption\",\n    \"CloudWatchLoggingOptionDescription\": \"amsaf:CloudWatchLoggingOptionDescription\",\n    \"CloudWatchLoggingOptionUpdate\": \"amsaf:CloudWatchLoggingOptionUpdate\",\n    \"CodeContent\": \"amsaf:CodeContent\",\n    \"CodeContentDescription\": \"amsaf:CodeContentDescription\",\n    \"CodeContentUpdate\": \"amsaf:CodeContentUpdate\",\n    \"CreateApplicationPresignedUrlRequest\": \"amsaf:CreateApplicationPresignedUrlRequest\",\n    \"CreateApplicationPresignedUrlResponse\": \"amsaf:CreateApplicationPresignedUrlResponse\",\n    \"CreateApplicationRequest\": \"amsaf:CreateApplicationRequest\",\n    \"CreateApplicationResponse\": \"amsaf:CreateApplicationResponse\",\n    \"CreateApplicationSnapshotRequest\": \"amsaf:CreateApplicationSnapshotRequest\",\n    \"CreateApplicationSnapshotResponse\"\
  : \"amsaf:CreateApplicationSnapshotResponse\",\n    \"CustomArtifactConfiguration\": \"amsaf:CustomArtifactConfiguration\",\n    \"CustomArtifactConfigurationDescription\": \"amsaf:CustomArtifactConfigurationDescription\",\n    \"DeleteApplicationCloudWatchLoggingOptionRequest\": \"amsaf:DeleteApplicationCloudWatchLoggingOptionRequest\",\n    \"DeleteApplicationCloudWatchLoggingOptionResponse\": \"amsaf:DeleteApplicationCloudWatchLoggingOptionResponse\",\n    \"DeleteApplicationInputProcessingConfigurationRequest\": \"amsaf:DeleteApplicationInputProcessingConfigurationRequest\",\n    \"DeleteApplicationInputProcessingConfigurationResponse\": \"amsaf:DeleteApplicationInputProcessingConfigurationResponse\",\n    \"DeleteApplicationOutputRequest\": \"amsaf:DeleteApplicationOutputRequest\",\n    \"DeleteApplicationOutputResponse\": \"amsaf:DeleteApplicationOutputResponse\",\n    \"DeleteApplicationReferenceDataSourceRequest\": \"amsaf:DeleteApplicationReferenceDataSourceRequest\",\n    \"\
  DeleteApplicationReferenceDataSourceResponse\": \"amsaf:DeleteApplicationReferenceDataSourceResponse\",\n    \"DeleteApplicationRequest\": \"amsaf:DeleteApplicationRequest\",\n    \"DeleteApplicationResponse\": \"amsaf:DeleteApplicationResponse\",\n    \"DeleteApplicationSnapshotRequest\": \"amsaf:DeleteApplicationSnapshotRequest\",\n    \"DeleteApplicationSnapshotResponse\": \"amsaf:DeleteApplicationSnapshotResponse\",\n    \"DeleteApplicationVpcConfigurationRequest\": \"amsaf:DeleteApplicationVpcConfigurationRequest\",\n    \"DeleteApplicationVpcConfigurationResponse\": \"amsaf:DeleteApplicationVpcConfigurationResponse\",\n    \"DeployAsApplicationConfiguration\": \"amsaf:DeployAsApplicationConfiguration\",\n    \"DeployAsApplicationConfigurationDescription\": \"amsaf:DeployAsApplicationConfigurationDescription\",\n    \"DeployAsApplicationConfigurationUpdate\": \"amsaf:DeployAsApplicationConfigurationUpdate\",\n    \"DescribeApplicationRequest\": \"amsaf:DescribeApplicationRequest\"\
  ,\n    \"DescribeApplicationResponse\": \"amsaf:DescribeApplicationResponse\",\n    \"DescribeApplicationSnapshotRequest\": \"amsaf:DescribeApplicationSnapshotRequest\",\n    \"DescribeApplicationSnapshotResponse\": \"amsaf:DescribeApplicationSnapshotResponse\",\n    \"DescribeApplicationVersionRequest\": \"amsaf:DescribeApplicationVersionRequest\",\n    \"DescribeApplicationVersionResponse\": \"amsaf:DescribeApplicationVersionResponse\",\n    \"DestinationSchema\": \"amsaf:DestinationSchema\",\n    \"DiscoverInputSchemaRequest\": \"amsaf:DiscoverInputSchemaRequest\",\n    \"DiscoverInputSchemaResponse\": \"amsaf:DiscoverInputSchemaResponse\",\n    \"EnvironmentProperties\": \"amsaf:EnvironmentProperties\",\n    \"EnvironmentPropertyDescriptions\": \"amsaf:EnvironmentPropertyDescriptions\",\n    \"EnvironmentPropertyUpdates\": \"amsaf:EnvironmentPropertyUpdates\",\n    \"FlinkApplicationConfiguration\": \"amsaf:FlinkApplicationConfiguration\",\n    \"FlinkApplicationConfigurationDescription\"\
  : \"amsaf:FlinkApplicationConfigurationDescription\",\n    \"FlinkApplicationConfigurationUpdate\": \"amsaf:FlinkApplicationConfigurationUpdate\",\n    \"FlinkRunConfiguration\": \"amsaf:FlinkRunConfiguration\",\n    \"GlueDataCatalogConfiguration\": \"amsaf:GlueDataCatalogConfiguration\",\n    \"GlueDataCatalogConfigurationDescription\": \"amsaf:GlueDataCatalogConfigurationDescription\",\n    \"GlueDataCatalogConfigurationUpdate\": \"amsaf:GlueDataCatalogConfigurationUpdate\",\n    \"Input\": \"amsaf:Input\",\n    \"InputDescription\": \"amsaf:InputDescription\",\n    \"InputLambdaProcessor\": \"amsaf:InputLambdaProcessor\",\n    \"InputLambdaProcessorDescription\": \"amsaf:InputLambdaProcessorDescription\",\n    \"InputLambdaProcessorUpdate\": \"amsaf:InputLambdaProcessorUpdate\",\n    \"InputParallelism\": \"amsaf:InputParallelism\",\n    \"InputParallelismUpdate\": \"amsaf:InputParallelismUpdate\",\n    \"InputProcessingConfiguration\": \"amsaf:InputProcessingConfiguration\",\n   \
  \ \"InputProcessingConfigurationDescription\": \"amsaf:InputProcessingConfigurationDescription\",\n    \"InputProcessingConfigurationUpdate\": \"amsaf:InputProcessingConfigurationUpdate\",\n    \"InputSchemaUpdate\": \"amsaf:InputSchemaUpdate\",\n    \"InputStartingPositionConfiguration\": \"amsaf:InputStartingPositionConfiguration\",\n    \"InputUpdate\": \"amsaf:InputUpdate\",\n    \"JSONMappingParameters\": \"amsaf:JSONMappingParameters\",\n    \"KinesisFirehoseInput\": \"amsaf:KinesisFirehoseInput\",\n    \"KinesisFirehoseInputDescription\": \"amsaf:KinesisFirehoseInputDescription\",\n    \"KinesisFirehoseInputUpdate\": \"amsaf:KinesisFirehoseInputUpdate\",\n    \"KinesisFirehoseOutput\": \"amsaf:KinesisFirehoseOutput\",\n    \"KinesisFirehoseOutputDescription\": \"amsaf:KinesisFirehoseOutputDescription\",\n    \"KinesisFirehoseOutputUpdate\": \"amsaf:KinesisFirehoseOutputUpdate\",\n    \"KinesisStreamsInput\": \"amsaf:KinesisStreamsInput\",\n    \"KinesisStreamsInputDescription\"\
  : \"amsaf:KinesisStreamsInputDescription\",\n    \"KinesisStreamsInputUpdate\": \"amsaf:KinesisStreamsInputUpdate\",\n    \"KinesisStreamsOutput\": \"amsaf:KinesisStreamsOutput\",\n    \"KinesisStreamsOutputDescription\": \"amsaf:KinesisStreamsOutputDescription\",\n    \"KinesisStreamsOutputUpdate\": \"amsaf:KinesisStreamsOutputUpdate\",\n    \"LambdaOutput\": \"amsaf:LambdaOutput\",\n    \"LambdaOutputDescription\": \"amsaf:LambdaOutputDescription\",\n    \"LambdaOutputUpdate\": \"amsaf:LambdaOutputUpdate\",\n    \"ListApplicationSnapshotsRequest\": \"amsaf:ListApplicationSnapshotsRequest\",\n    \"ListApplicationSnapshotsResponse\": \"amsaf:ListApplicationSnapshotsResponse\",\n    \"ListApplicationVersionsRequest\": \"amsaf:ListApplicationVersionsRequest\",\n    \"ListApplicationVersionsResponse\": \"amsaf:ListApplicationVersionsResponse\",\n    \"ListApplicationsRequest\": \"amsaf:ListApplicationsRequest\",\n    \"ListApplicationsResponse\": \"amsaf:ListApplicationsResponse\",\n   \
  \ \"ListTagsForResourceRequest\": \"amsaf:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amsaf:ListTagsForResourceResponse\",\n    \"MappingParameters\": \"amsaf:MappingParameters\",\n    \"MavenReference\": \"amsaf:MavenReference\",\n    \"MonitoringConfiguration\": \"amsaf:MonitoringConfiguration\",\n    \"MonitoringConfigurationDescription\": \"amsaf:MonitoringConfigurationDescription\",\n    \"MonitoringConfigurationUpdate\": \"amsaf:MonitoringConfigurationUpdate\",\n    \"Output\": \"amsaf:Output\",\n    \"OutputDescription\": \"amsaf:OutputDescription\",\n    \"OutputUpdate\": \"amsaf:OutputUpdate\",\n    \"ParallelismConfiguration\": \"amsaf:ParallelismConfiguration\",\n    \"ParallelismConfigurationDescription\": \"amsaf:ParallelismConfigurationDescription\",\n    \"ParallelismConfigurationUpdate\": \"amsaf:ParallelismConfigurationUpdate\",\n    \"PropertyGroup\": \"amsaf:PropertyGroup\",\n    \"PropertyMap\": \"amsaf:PropertyMap\",\n    \"RecordColumn\"\
  : \"amsaf:RecordColumn\",\n    \"RecordFormat\": \"amsaf:RecordFormat\",\n    \"ReferenceDataSource\": \"amsaf:ReferenceDataSource\",\n    \"ReferenceDataSourceDescription\": \"amsaf:ReferenceDataSourceDescription\",\n    \"ReferenceDataSourceUpdate\": \"amsaf:ReferenceDataSourceUpdate\",\n    \"RollbackApplicationRequest\": \"amsaf:RollbackApplicationRequest\",\n    \"RollbackApplicationResponse\": \"amsaf:RollbackApplicationResponse\",\n    \"RunConfiguration\": \"amsaf:RunConfiguration\",\n    \"RunConfigurationDescription\": \"amsaf:RunConfigurationDescription\",\n    \"RunConfigurationUpdate\": \"amsaf:RunConfigurationUpdate\",\n    \"S3ApplicationCodeLocationDescription\": \"amsaf:S3ApplicationCodeLocationDescription\",\n    \"S3Configuration\": \"amsaf:S3Configuration\",\n    \"S3ContentBaseLocation\": \"amsaf:S3ContentBaseLocation\",\n    \"S3ContentBaseLocationDescription\": \"amsaf:S3ContentBaseLocationDescription\",\n    \"S3ContentBaseLocationUpdate\": \"amsaf:S3ContentBaseLocationUpdate\"\
  ,\n    \"S3ContentLocation\": \"amsaf:S3ContentLocation\",\n    \"S3ContentLocationUpdate\": \"amsaf:S3ContentLocationUpdate\",\n    \"S3ReferenceDataSource\": \"amsaf:S3ReferenceDataSource\",\n    \"S3ReferenceDataSourceDescription\": \"amsaf:S3ReferenceDataSourceDescription\",\n    \"S3ReferenceDataSourceUpdate\": \"amsaf:S3ReferenceDataSourceUpdate\",\n    \"SnapshotDetails\": \"amsaf:SnapshotDetails\",\n    \"SourceSchema\": \"amsaf:SourceSchema\",\n    \"SqlApplicationConfiguration\": \"amsaf:SqlApplicationConfiguration\",\n    \"SqlApplicationConfigurationDescription\": \"amsaf:SqlApplicationConfigurationDescription\",\n    \"SqlApplicationConfigurationUpdate\": \"amsaf:SqlApplicationConfigurationUpdate\",\n    \"SqlRunConfiguration\": \"amsaf:SqlRunConfiguration\",\n    \"StartApplicationRequest\": \"amsaf:StartApplicationRequest\",\n    \"StartApplicationResponse\": \"amsaf:StartApplicationResponse\",\n    \"StopApplicationRequest\": \"amsaf:StopApplicationRequest\",\n    \"StopApplicationResponse\"\
  : \"amsaf:StopApplicationResponse\",\n    \"Tag\": \"amsaf:Tag\",\n    \"TagResourceRequest\": \"amsaf:TagResourceRequest\",\n    \"TagResourceResponse\": \"amsaf:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amsaf:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amsaf:UntagResourceResponse\",\n    \"UpdateApplicationMaintenanceConfigurationRequest\": \"amsaf:UpdateApplicationMaintenanceConfigurationRequest\",\n    \"UpdateApplicationMaintenanceConfigurationResponse\": \"amsaf:UpdateApplicationMaintenanceConfigurationResponse\",\n    \"UpdateApplicationRequest\": \"amsaf:UpdateApplicationRequest\",\n    \"UpdateApplicationResponse\": \"amsaf:UpdateApplicationResponse\",\n    \"VpcConfiguration\": \"amsaf:VpcConfiguration\",\n    \"VpcConfigurationDescription\": \"amsaf:VpcConfigurationDescription\",\n    \"VpcConfigurationUpdate\": \"amsaf:VpcConfigurationUpdate\",\n    \"ZeppelinApplicationConfiguration\": \"amsaf:ZeppelinApplicationConfiguration\",\n    \"ZeppelinApplicationConfigurationDescription\"\
  : \"amsaf:ZeppelinApplicationConfigurationDescription\",\n    \"ZeppelinApplicationConfigurationUpdate\": \"amsaf:ZeppelinApplicationConfigurationUpdate\",\n    \"ZeppelinMonitoringConfiguration\": \"amsaf:ZeppelinMonitoringConfiguration\",\n    \"ZeppelinMonitoringConfigurationDescription\": \"amsaf:ZeppelinMonitoringConfigurationDescription\",\n    \"ZeppelinMonitoringConfigurationUpdate\": \"amsaf:ZeppelinMonitoringConfigurationUpdate\",\n    \"AllowNonRestoredState\": {\n      \"@id\": \"amsaf:AllowNonRestoredState\"\n    },\n    \"ApplicationARN\": {\n      \"@id\": \"amsaf:ApplicationARN\"\n    },\n    \"ApplicationDescription\": {\n      \"@id\": \"amsaf:ApplicationDescription\"\n    },\n    \"ApplicationMaintenanceWindowEndTime\": {\n      \"@id\": \"amsaf:ApplicationMaintenanceWindowEndTime\"\n    },\n    \"ApplicationMaintenanceWindowStartTime\": {\n      \"@id\": \"amsaf:ApplicationMaintenanceWindowStartTime\"\n    },\n    \"ApplicationMaintenanceWindowStartTimeUpdate\": {\n\
  \      \"@id\": \"amsaf:ApplicationMaintenanceWindowStartTimeUpdate\"\n    },\n    \"ApplicationMode\": {\n      \"@id\": \"amsaf:ApplicationMode\"\n    },\n    \"ApplicationName\": {\n      \"@id\": \"amsaf:ApplicationName\"\n    },\n    \"ApplicationRestoreConfigurationDescription\": {\n      \"@id\": \"amsaf:ApplicationRestoreConfigurationDescription\"\n    },\n    \"ApplicationRestoreType\": {\n      \"@id\": \"amsaf:ApplicationRestoreType\"\n    },\n    \"ApplicationStatus\": {\n      \"@id\": \"amsaf:ApplicationStatus\"\n    },\n    \"ApplicationSummaries\": {\n      \"@id\": \"amsaf:ApplicationSummaries\"\n    },\n    \"ApplicationVersionDetail\": {\n      \"@id\": \"amsaf:ApplicationVersionDetail\"\n    },\n    \"ApplicationVersionId\": {\n      \"@id\": \"amsaf:ApplicationVersionId\"\n    },\n    \"ApplicationVersionRolledBackFrom\": {\n      \"@id\": \"amsaf:ApplicationVersionRolledBackFrom\"\n    },\n    \"ApplicationVersionRolledBackTo\": {\n      \"@id\": \"amsaf:ApplicationVersionRolledBackTo\"\
  \n    },\n    \"ApplicationVersionSummaries\": {\n      \"@id\": \"amsaf:ApplicationVersionSummaries\"\n    },\n    \"ApplicationVersionUpdatedFrom\": {\n      \"@id\": \"amsaf:ApplicationVersionUpdatedFrom\"\n    },\n    \"ArtifactId\": {\n      \"@id\": \"amsaf:ArtifactId\"\n    },\n    \"ArtifactType\": {\n      \"@id\": \"amsaf:ArtifactType\"\n    },\n    \"AuthorizedUrl\": {\n      \"@id\": \"amsaf:AuthorizedUrl\"\n    },\n    \"AutoScalingEnabled\": {\n      \"@id\": \"amsaf:AutoScalingEnabled\"\n    },\n    \"AutoScalingEnabledUpdate\": {\n      \"@id\": \"amsaf:AutoScalingEnabledUpdate\"\n    },\n    \"BasePath\": {\n      \"@id\": \"amsaf:BasePath\"\n    },\n    \"BasePathUpdate\": {\n      \"@id\": \"amsaf:BasePathUpdate\"\n    },\n    \"BucketARN\": {\n      \"@id\": \"amsaf:BucketARN\"\n    },\n    \"BucketARNUpdate\": {\n      \"@id\": \"amsaf:BucketARNUpdate\"\n    },\n    \"CheckpointInterval\": {\n      \"@id\": \"amsaf:CheckpointInterval\"\n    },\n    \"CheckpointIntervalUpdate\"\
  : {\n      \"@id\": \"amsaf:CheckpointIntervalUpdate\"\n    },\n    \"CheckpointingEnabled\": {\n      \"@id\": \"amsaf:CheckpointingEnabled\"\n    },\n    \"CheckpointingEnabledUpdate\": {\n      \"@id\": \"amsaf:CheckpointingEnabledUpdate\"\n    },\n    \"CloudWatchLoggingOptionDescriptions\": {\n      \"@id\": \"amsaf:CloudWatchLoggingOptionDescriptions\"\n    },\n    \"CloudWatchLoggingOptionId\": {\n      \"@id\": \"amsaf:CloudWatchLoggingOptionId\"\n    },\n    \"CloudWatchLoggingOptionUpdates\": {\n      \"@id\": \"amsaf:CloudWatchLoggingOptionUpdates\"\n    },\n    \"CloudWatchLoggingOptions\": {\n      \"@id\": \"amsaf:CloudWatchLoggingOptions\"\n    },\n    \"CodeContentType\": {\n      \"@id\": \"amsaf:CodeContentType\"\n    },\n    \"CodeContentTypeUpdate\": {\n      \"@id\": \"amsaf:CodeContentTypeUpdate\"\n    },\n    \"CodeMD5\": {\n      \"@id\": \"amsaf:CodeMD5\"\n    },\n    \"CodeSize\": {\n      \"@id\": \"amsaf:CodeSize\"\n    },\n    \"ConditionalToken\": {\n    \
  \  \"@id\": \"amsaf:ConditionalToken\"\n    },\n    \"ConfigurationType\": {\n      \"@id\": \"amsaf:ConfigurationType\"\n    },\n    \"ConfigurationTypeUpdate\": {\n      \"@id\": \"amsaf:ConfigurationTypeUpdate\"\n    },\n    \"Count\": {\n      \"@id\": \"amsaf:Count\"\n    },\n    \"CountUpdate\": {\n      \"@id\": \"amsaf:CountUpdate\"\n    },\n    \"CreateTimestamp\": {\n      \"@id\": \"amsaf:CreateTimestamp\"\n    },\n    \"CurrentApplicationVersionId\": {\n      \"@id\": \"amsaf:CurrentApplicationVersionId\"\n    },\n    \"CurrentParallelism\": {\n      \"@id\": \"amsaf:CurrentParallelism\"\n    },\n    \"CustomArtifactsConfiguration\": {\n      \"@id\": \"amsaf:CustomArtifactsConfiguration\"\n    },\n    \"CustomArtifactsConfigurationDescription\": {\n      \"@id\": \"amsaf:CustomArtifactsConfigurationDescription\"\n    },\n    \"CustomArtifactsConfigurationUpdate\": {\n      \"@id\": \"amsaf:CustomArtifactsConfigurationUpdate\"\n    },\n    \"DatabaseARN\": {\n      \"@id\"\
  : \"amsaf:DatabaseARN\"\n    },\n    \"DatabaseARNUpdate\": {\n      \"@id\": \"amsaf:DatabaseARNUpdate\"\n    },\n    \"DestinationSchemaUpdate\": {\n      \"@id\": \"amsaf:DestinationSchemaUpdate\"\n    },\n    \"FileKey\": {\n      \"@id\": \"amsaf:FileKey\"\n    },\n    \"FileKeyUpdate\": {\n      \"@id\": \"amsaf:FileKeyUpdate\"\n    },\n    \"FlinkRunConfigurationDescription\": {\n      \"@id\": \"amsaf:FlinkRunConfigurationDescription\"\n    },\n    \"Force\": {\n      \"@id\": \"amsaf:Force\"\n    },\n    \"GroupId\": {\n      \"@id\": \"amsaf:GroupId\"\n    },\n    \"InAppStreamNames\": {\n      \"@id\": \"amsaf:InAppStreamNames\"\n    },\n    \"IncludeAdditionalDetails\": {\n      \"@id\": \"amsaf:IncludeAdditionalDetails\"\n    },\n    \"InputDescriptions\": {\n      \"@id\": \"amsaf:InputDescriptions\"\n    },\n    \"InputId\": {\n      \"@id\": \"amsaf:InputId\"\n    },\n    \"InputSchema\": {\n      \"@id\": \"amsaf:InputSchema\"\n    },\n    \"InputStartingPosition\": {\n\
  \      \"@id\": \"amsaf:InputStartingPosition\"\n    },\n    \"InputUpdates\": {\n      \"@id\": \"amsaf:InputUpdates\"\n    },\n    \"Inputs\": {\n      \"@id\": \"amsaf:Inputs\"\n    },\n    \"JobPlanDescription\": {\n      \"@id\": \"amsaf:JobPlanDescription\"\n    },\n    \"Key\": {\n      \"@id\": \"amsaf:Key\"\n    },\n    \"LastUpdateTimestamp\": {\n      \"@id\": \"amsaf:LastUpdateTimestamp\"\n    },\n    \"Limit\": {\n      \"@id\": \"amsaf:Limit\"\n    },\n    \"LogLevel\": {\n      \"@id\": \"amsaf:LogLevel\"\n    },\n    \"LogLevelUpdate\": {\n      \"@id\": \"amsaf:LogLevelUpdate\"\n    },\n    \"LogStreamARN\": {\n      \"@id\": \"amsaf:LogStreamARN\"\n    },\n    \"LogStreamARNUpdate\": {\n      \"@id\": \"amsaf:LogStreamARNUpdate\"\n    },\n    \"Mapping\": {\n      \"@id\": \"amsaf:Mapping\"\n    },\n    \"MavenReferenceDescription\": {\n      \"@id\": \"amsaf:MavenReferenceDescription\"\n    },\n    \"MetricsLevel\": {\n      \"@id\": \"amsaf:MetricsLevel\"\n    },\n\
  \    \"MetricsLevelUpdate\": {\n      \"@id\": \"amsaf:MetricsLevelUpdate\"\n    },\n    \"MinPauseBetweenCheckpoints\": {\n      \"@id\": \"amsaf:MinPauseBetweenCheckpoints\"\n    },\n    \"MinPauseBetweenCheckpointsUpdate\": {\n      \"@id\": \"amsaf:MinPauseBetweenCheckpointsUpdate\"\n    },\n    \"Name\": {\n      \"@id\": \"amsaf:Name\"\n    },\n    \"NamePrefix\": {\n      \"@id\": \"amsaf:NamePrefix\"\n    },\n    \"NamePrefixUpdate\": {\n      \"@id\": \"amsaf:NamePrefixUpdate\"\n    },\n    \"NameUpdate\": {\n      \"@id\": \"amsaf:NameUpdate\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amsaf:NextToken\"\n    },\n    \"ObjectVersion\": {\n      \"@id\": \"amsaf:ObjectVersion\"\n    },\n    \"ObjectVersionUpdate\": {\n      \"@id\": \"amsaf:ObjectVersionUpdate\"\n    },\n    \"OutputDescriptions\": {\n      \"@id\": \"amsaf:OutputDescriptions\"\n    },\n    \"OutputId\": {\n      \"@id\": \"amsaf:OutputId\"\n    },\n    \"OutputUpdates\": {\n      \"@id\": \"amsaf:OutputUpdates\"\
  \n    },\n    \"Outputs\": {\n      \"@id\": \"amsaf:Outputs\"\n    },\n    \"Parallelism\": {\n      \"@id\": \"amsaf:Parallelism\"\n    },\n    \"ParallelismPerKPU\": {\n      \"@id\": \"amsaf:ParallelismPerKPU\"\n    },\n    \"ParallelismPerKPUUpdate\": {\n      \"@id\": \"amsaf:ParallelismPerKPUUpdate\"\n    },\n    \"ParallelismUpdate\": {\n      \"@id\": \"amsaf:ParallelismUpdate\"\n    },\n    \"ParsedInputRecords\": {\n      \"@id\": \"amsaf:ParsedInputRecords\"\n    },\n    \"ProcessedInputRecords\": {\n      \"@id\": \"amsaf:ProcessedInputRecords\"\n    },\n    \"PropertyGroupDescriptions\": {\n      \"@id\": \"amsaf:PropertyGroupDescriptions\"\n    },\n    \"PropertyGroupId\": {\n      \"@id\": \"amsaf:PropertyGroupId\"\n    },\n    \"PropertyGroups\": {\n      \"@id\": \"amsaf:PropertyGroups\"\n    },\n    \"RawInputRecords\": {\n      \"@id\": \"amsaf:RawInputRecords\"\n    },\n    \"RecordColumnDelimiter\": {\n      \"@id\": \"amsaf:RecordColumnDelimiter\"\n    },\n    \"\
  RecordColumnUpdates\": {\n      \"@id\": \"amsaf:RecordColumnUpdates\"\n    },\n    \"RecordColumns\": {\n      \"@id\": \"amsaf:RecordColumns\"\n    },\n    \"RecordEncoding\": {\n      \"@id\": \"amsaf:RecordEncoding\"\n    },\n    \"RecordEncodingUpdate\": {\n      \"@id\": \"amsaf:RecordEncodingUpdate\"\n    },\n    \"RecordFormatType\": {\n      \"@id\": \"amsaf:RecordFormatType\"\n    },\n    \"RecordFormatUpdate\": {\n      \"@id\": \"amsaf:RecordFormatUpdate\"\n    },\n    \"RecordRowDelimiter\": {\n      \"@id\": \"amsaf:RecordRowDelimiter\"\n    },\n    \"RecordRowPath\": {\n      \"@id\": \"amsaf:RecordRowPath\"\n    },\n    \"ReferenceDataSourceDescriptions\": {\n      \"@id\": \"amsaf:ReferenceDataSourceDescriptions\"\n    },\n    \"ReferenceDataSourceUpdates\": {\n      \"@id\": \"amsaf:ReferenceDataSourceUpdates\"\n    },\n    \"ReferenceDataSources\": {\n      \"@id\": \"amsaf:ReferenceDataSources\"\n    },\n    \"ReferenceId\": {\n      \"@id\": \"amsaf:ReferenceId\"\n\
  \    },\n    \"ReferenceRoleARN\": {\n      \"@id\": \"amsaf:ReferenceRoleARN\"\n    },\n    \"ReferenceSchema\": {\n      \"@id\": \"amsaf:ReferenceSchema\"\n    },\n    \"ReferenceSchemaUpdate\": {\n      \"@id\": \"amsaf:ReferenceSchemaUpdate\"\n    },\n    \"ResourceARN\": {\n      \"@id\": \"amsaf:ResourceARN\"\n    },\n    \"ResourceARNUpdate\": {\n      \"@id\": \"amsaf:ResourceARNUpdate\"\n    },\n    \"RoleARN\": {\n      \"@id\": \"amsaf:RoleARN\"\n    },\n    \"RuntimeEnvironment\": {\n      \"@id\": \"amsaf:RuntimeEnvironment\"\n    },\n    \"S3ContentLocationDescription\": {\n      \"@id\": \"amsaf:S3ContentLocationDescription\"\n    },\n    \"SecurityGroupIdUpdates\": {\n      \"@id\": \"amsaf:SecurityGroupIdUpdates\"\n    },\n    \"SecurityGroupIds\": {\n      \"@id\": \"amsaf:SecurityGroupIds\"\n    },\n    \"ServiceExecutionRole\": {\n      \"@id\": \"amsaf:ServiceExecutionRole\"\n    },\n    \"ServiceExecutionRoleUpdate\": {\n      \"@id\": \"amsaf:ServiceExecutionRoleUpdate\"\
  \n    },\n    \"SessionExpirationDurationInSeconds\": {\n      \"@id\": \"amsaf:SessionExpirationDurationInSeconds\"\n    },\n    \"SnapshotCreationTimestamp\": {\n      \"@id\": \"amsaf:SnapshotCreationTimestamp\"\n    },\n    \"SnapshotName\": {\n      \"@id\": \"amsaf:SnapshotName\"\n    },\n    \"SnapshotStatus\": {\n      \"@id\": \"amsaf:SnapshotStatus\"\n    },\n    \"SnapshotSummaries\": {\n      \"@id\": \"amsaf:SnapshotSummaries\"\n    },\n    \"SnapshotsEnabled\": {\n      \"@id\": \"amsaf:SnapshotsEnabled\"\n    },\n    \"SnapshotsEnabledUpdate\": {\n      \"@id\": \"amsaf:SnapshotsEnabledUpdate\"\n    },\n    \"SqlRunConfigurations\": {\n      \"@id\": \"amsaf:SqlRunConfigurations\"\n    },\n    \"SqlType\": {\n      \"@id\": \"amsaf:SqlType\"\n    },\n    \"SubnetIdUpdates\": {\n      \"@id\": \"amsaf:SubnetIdUpdates\"\n    },\n    \"SubnetIds\": {\n      \"@id\": \"amsaf:SubnetIds\"\n    },\n    \"TableName\": {\n      \"@id\": \"amsaf:TableName\"\n    },\n    \"TableNameUpdate\"\
  : {\n      \"@id\": \"amsaf:TableNameUpdate\"\n    },\n    \"TagKeys\": {\n      \"@id\": \"amsaf:TagKeys\"\n    },\n    \"Tags\": {\n      \"@id\": \"amsaf:Tags\"\n    },\n    \"TextContent\": {\n      \"@id\": \"amsaf:TextContent\"\n    },\n    \"TextContentUpdate\": {\n      \"@id\": \"amsaf:TextContentUpdate\"\n    },\n    \"UrlType\": {\n      \"@id\": \"amsaf:UrlType\"\n    },\n    \"Value\": {\n      \"@id\": \"amsaf:Value\"\n    },\n    \"Version\": {\n      \"@id\": \"amsaf:Version\"\n    },\n    \"VpcConfigurationDescriptions\": {\n      \"@id\": \"amsaf:VpcConfigurationDescriptions\"\n    },\n    \"VpcConfigurationId\": {\n      \"@id\": \"amsaf:VpcConfigurationId\"\n    },\n    \"VpcConfigurationUpdates\": {\n      \"@id\": \"amsaf:VpcConfigurationUpdates\"\n    },\n    \"VpcConfigurations\": {\n      \"@id\": \"amsaf:VpcConfigurations\"\n    },\n    \"VpcId\": {\n      \"@id\": \"amsaf:VpcId\"\n    },\n    \"ZipFileContent\": {\n      \"@id\": \"amsaf:ZipFileContent\"\n  \
  \  },\n    \"ZipFileContentUpdate\": {\n      \"@id\": \"amsaf:ZipFileContentUpdate\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-apache-flink/refs/heads/main/json-ld/amazon-managed-apache-flink-context.jsonld
tags:
- Apache Flink
- AWS
- Big Data
- Real-Time Processing
- Streaming Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
