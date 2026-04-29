---
class_count: 122
classes:
- DeleteScheduleRequest
- S3TableOutputOptions
- UpdateScheduleRequest
- BatchDeleteRecipeVersionRequest
- ListSchedulesResponse
- ParameterMap
- ListRecipesResponse
- UpdateRecipeRequest
- TagResourceRequest
- ListJobsResponse
- CreateProfileJobRequest
- RecipeAction
- ValidationConfiguration
- StartJobRunResponse
- ListDatasetsResponse
- UpdateRecipeJobResponse
- CreateRulesetRequest
- ListJobRunsRequest
- CsvOutputOptions
- Output
- DeleteDatasetRequest
- StartProjectSessionResponse
- StopJobRunRequest
- CreateDatasetResponse
- DescribeProjectRequest
- DescribeJobRunRequest
- DescribeRulesetResponse
- StartProjectSessionRequest
- ColumnSelector
- PublishRecipeResponse
- ListRecipeVersionsResponse
- DeleteRecipeVersionRequest
- PathParametersMap
- DeleteJobRequest
- CreateRecipeJobRequest
- UpdateProfileJobResponse
- UpdateScheduleResponse
- ListJobRunsResponse
- Recipe
- CsvOptions
- DescribeJobResponse
- UpdateProjectResponse
- DescribeDatasetRequest
- JsonOptions
- DeleteProjectResponse
- UpdateRulesetRequest
- StatisticsConfiguration
- DataCatalogOutput
- DeleteScheduleResponse
- StopJobRunResponse
- CreateRulesetResponse
- UpdateRecipeJobRequest
- SendProjectSessionActionResponse
- DescribeDatasetResponse
- DescribeRecipeResponse
- RulesetItem
- DescribeRecipeRequest
- StartJobRunRequest
- ListProjectsRequest
- DeleteProjectRequest
- ListRulesetsResponse
- DatabaseTableOutputOptions
- PublishRecipeRequest
- FilterExpression
- Schedule
- DescribeScheduleRequest
- TagResourceResponse
- OutputFormatOptions
- ColumnStatisticsConfiguration
- DatasetParameter
- ListTagsForResourceRequest
- UpdateRulesetResponse
- CreateRecipeResponse
- ListRecipeVersionsRequest
- DescribeJobRunResponse
- RecipeVersionErrorDetail
- UpdateProjectRequest
- CreateProfileJobResponse
- DeleteRulesetResponse
- UntagResourceRequest
- Dataset
- CreateProjectResponse
- CreateDatasetRequest
- DeleteRecipeVersionResponse
- ListRulesetsRequest
- ConditionExpression
- DeleteRulesetRequest
- BatchDeleteRecipeVersionResponse
- S3Location
- DescribeJobRequest
- CreateRecipeJobResponse
- CreateScheduleResponse
- Rule
- DeleteJobResponse
- JobRun
- ListRecipesRequest
- ListProjectsResponse
- TagMap
- CreateScheduleRequest
- DatabaseOutput
- StatisticOverride
- DescribeScheduleResponse
- ListTagsForResourceResponse
- UpdateRecipeResponse
- ListJobsRequest
- UpdateDatasetResponse
- SendProjectSessionActionRequest
- CreateProjectRequest
- CreateRecipeRequest
- DeleteDatasetResponse
- UpdateProfileJobRequest
- UntagResourceResponse
- ExcelOptions
- ListSchedulesRequest
- DescribeRulesetRequest
- Project
- ListDatasetsRequest
- UpdateDatasetRequest
- Job
- DescribeProjectResponse
- Description
- Name
context_file: json-ld/amazon-glue-databrew-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-glue-databrew/refs/heads/main/json-ld/amazon-glue-databrew-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Glue Databrew from Amazon Glue DataBrew.
layout: jsonld
name: Amazon Glue Databrew Context
namespaces:
- prefix: databrew
  uri: https://aws.amazon.com/glue/databrew/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: RecipeStep
  type: string
- container: ''
  name: EntityDetectorConfiguration
  type: string
- container: ''
  name: PathOptions
  type: string
- container: ''
  name: Input
  type: string
- container: ''
  name: FilesLimit
  type: string
- container: ''
  name: ViewFrame
  type: string
- container: ''
  name: JobSample
  type: string
- container: ''
  name: Metadata
  type: string
- container: ''
  name: RecipeReference
  type: string
- container: ''
  name: ProfileConfiguration
  type: string
- container: ''
  name: DatabaseInputDefinition
  type: string
- container: ''
  name: AllowedStatistics
  type: string
- container: ''
  name: DataCatalogInputDefinition
  type: string
- container: ''
  name: ValuesMap
  type: string
- container: ''
  name: FormatOptions
  type: string
- container: ''
  name: DatetimeOptions
  type: string
- container: ''
  name: Sample
  type: string
- container: ''
  name: Threshold
  type: string
- container: ''
  name: Location
  type: string
- container: ''
  name: JobNames
  type: string
- container: ''
  name: CronExpression
  type: string
- container: ''
  name: RecipeVersions
  type: string
- container: ''
  name: Schedules
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Recipes
  type: string
- container: ''
  name: Steps
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Jobs
  type: string
- container: ''
  name: DatasetName
  type: string
- container: ''
  name: EncryptionKeyArn
  type: string
- container: ''
  name: EncryptionMode
  type: string
- container: ''
  name: LogSubscription
  type: string
- container: ''
  name: MaxCapacity
  type: string
- container: ''
  name: MaxRetries
  type: string
- container: ''
  name: OutputLocation
  type: string
- container: ''
  name: Configuration
  type: string
- container: ''
  name: ValidationConfigurations
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: Timeout
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: ConditionExpressions
  type: string
- container: ''
  name: Operation
  type: string
- container: ''
  name: Parameters
  type: string
- container: ''
  name: RulesetArn
  type: string
- container: ''
  name: ValidationMode
  type: string
- container: ''
  name: RunId
  type: string
- container: ''
  name: Datasets
  type: string
- container: ''
  name: TargetArn
  type: string
- container: ''
  name: Rules
  type: string
- container: ''
  name: Delimiter
  type: string
- container: ''
  name: CompressionFormat
  type: string
- container: ''
  name: Format
  type: string
- container: ''
  name: PartitionColumns
  type: string
- container: ''
  name: Overwrite
  type: string
- container: ''
  name: MaxOutputFiles
  type: string
- container: ''
  name: ClientSessionId
  type: string
- container: ''
  name: EntityTypes
  type: string
- container: ''
  name: CreateDate
  type: string
- container: ''
  name: CreatedBy
  type: string
- container: ''
  name: LastModifiedBy
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: AssumeControl
  type: string
- container: ''
  name: Regex
  type: string
- container: ''
  name: LastModifiedDateCondition
  type: string
- container: ''
  name: Outputs
  type: string
- container: ''
  name: DataCatalogOutputs
  type: string
- container: ''
  name: DatabaseOutputs
  type: string
- container: ''
  name: ProjectName
  type: string
- container: ''
  name: S3InputDefinition
  type: string
- container: ''
  name: JobRuns
  type: string
- container: ''
  name: PublishedBy
  type: string
- container: ''
  name: PublishedDate
  type: string
- container: ''
  name: RecipeVersion
  type: string
- container: ''
  name: HeaderRow
  type: string
- container: ''
  name: MaxFiles
  type: string
- container: ''
  name: OrderedBy
  type: string
- container: ''
  name: Order
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: MultiLine
  type: string
- container: ''
  name: IncludedStatistics
  type: string
- container: ''
  name: Overrides
  type: string
- container: ''
  name: StartColumnIndex
  type: string
- container: ''
  name: ColumnRange
  type: string
- container: ''
  name: HiddenColumns
  type: string
- container: ''
  name: StartRowIndex
  type: string
- container: ''
  name: RowRange
  type: string
- container: ''
  name: Analytics
  type: string
- container: ''
  name: CatalogId
  type: string
- container: ''
  name: DatabaseName
  type: string
- container: ''
  name: TableName
  type: string
- container: ''
  name: S3Options
  type: string
- container: ''
  name: DatabaseOptions
  type: string
- container: ''
  name: Mode
  type: string
- container: ''
  name: Size
  type: string
- container: ''
  name: Result
  type: string
- container: ''
  name: ActionId
  type: string
- container: ''
  name: Source
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: RuleCount
  type: string
- container: ''
  name: SourceArn
  type: string
- container: ''
  name: Rulesets
  type: string
- container: ''
  name: TempDirectory
  type: string
- container: ''
  name: DatasetStatisticsConfiguration
  type: string
- container: ''
  name: ProfileColumns
  type: string
- container: ''
  name: ColumnStatisticsConfigurations
  type: string
- container: ''
  name: Expression
  type: string
- container: ''
  name: Csv
  type: string
- container: ''
  name: Selectors
  type: string
- container: ''
  name: Statistics
  type: string
- container: ''
  name: CreateColumn
  type: string
- container: ''
  name: Filter
  type: string
- container: ''
  name: GlueConnectionName
  type: string
- container: ''
  name: DatabaseTableName
  type: string
- container: ''
  name: QueryString
  type: string
- container: ''
  name: Attempt
  type: string
- container: ''
  name: CompletedOn
  type: string
- container: ''
  name: ErrorMessage
  type: string
- container: ''
  name: ExecutionTime
  type: string
- container: ''
  name: JobName
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: LogGroupName
  type: string
- container: ''
  name: StartedBy
  type: string
- container: ''
  name: StartedOn
  type: string
- container: ''
  name: ErrorCode
  type: string
- container: ''
  name: Condition
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: TargetColumn
  type: string
- container: ''
  name: Json
  type: string
- container: ''
  name: Excel
  type: string
- container: ''
  name: Errors
  type: string
- container: ''
  name: Bucket
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: BucketOwner
  type: string
- container: ''
  name: TimezoneOffset
  type: string
- container: ''
  name: LocaleCode
  type: string
- container: ''
  name: Disabled
  type: string
- container: ''
  name: CheckExpression
  type: string
- container: ''
  name: SubstitutionMap
  type: string
- container: ''
  name: ColumnSelectors
  type: string
- container: ''
  name: Projects
  type: string
- container: ''
  name: DatabaseOutputMode
  type: string
- container: ''
  name: Statistic
  type: string
- container: ''
  name: Unit
  type: string
- container: ''
  name: Preview
  type: string
- container: ''
  name: StepIndex
  type: string
- container: ''
  name: RecipeName
  type: string
- container: ''
  name: SheetNames
  type: string
- container: ''
  name: SheetIndexes
  type: string
- container: ''
  name: OpenedBy
  type: string
- container: ''
  name: OpenDate
  type: string
- container: ''
  name: SessionStatus
  type: string
property_count: 152
provider_name: Amazon Glue DataBrew
provider_slug: amazon-glue-databrew
slug: amazon-glue-databrew-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"databrew\": \"https://aws.amazon.com/glue/databrew/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeleteScheduleRequest\": \"databrew:DeleteScheduleRequest\",\n    \"S3TableOutputOptions\": \"databrew:S3TableOutputOptions\",\n    \"UpdateScheduleRequest\": \"databrew:UpdateScheduleRequest\",\n    \"BatchDeleteRecipeVersionRequest\": \"databrew:BatchDeleteRecipeVersionRequest\",\n    \"ListSchedulesResponse\": \"databrew:ListSchedulesResponse\",\n    \"ParameterMap\": \"databrew:ParameterMap\",\n    \"ListRecipesResponse\": \"databrew:ListRecipesResponse\",\n    \"UpdateRecipeRequest\": \"databrew:UpdateRecipeRequest\",\n    \"TagResourceRequest\": \"databrew:TagResourceRequest\",\n    \"ListJobsResponse\": \"databrew:ListJobsResponse\",\n    \"CreateProfileJobRequest\": \"databrew:CreateProfileJobRequest\",\n\
  \    \"RecipeStep\": {\n      \"@id\": \"databrew:RecipeStep\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecipeAction\": \"databrew:RecipeAction\",\n    \"ValidationConfiguration\": \"databrew:ValidationConfiguration\",\n    \"StartJobRunResponse\": \"databrew:StartJobRunResponse\",\n    \"ListDatasetsResponse\": \"databrew:ListDatasetsResponse\",\n    \"UpdateRecipeJobResponse\": \"databrew:UpdateRecipeJobResponse\",\n    \"CreateRulesetRequest\": \"databrew:CreateRulesetRequest\",\n    \"ListJobRunsRequest\": \"databrew:ListJobRunsRequest\",\n    \"CsvOutputOptions\": \"databrew:CsvOutputOptions\",\n    \"Output\": \"databrew:Output\",\n    \"DeleteDatasetRequest\": \"databrew:DeleteDatasetRequest\",\n    \"StartProjectSessionResponse\": \"databrew:StartProjectSessionResponse\",\n    \"StopJobRunRequest\": \"databrew:StopJobRunRequest\",\n    \"CreateDatasetResponse\": \"databrew:CreateDatasetResponse\",\n    \"DescribeProjectRequest\": \"databrew:DescribeProjectRequest\",\n \
  \   \"EntityDetectorConfiguration\": {\n      \"@id\": \"databrew:EntityDetectorConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeJobRunRequest\": \"databrew:DescribeJobRunRequest\",\n    \"DescribeRulesetResponse\": \"databrew:DescribeRulesetResponse\",\n    \"StartProjectSessionRequest\": \"databrew:StartProjectSessionRequest\",\n    \"ColumnSelector\": \"databrew:ColumnSelector\",\n    \"PathOptions\": {\n      \"@id\": \"databrew:PathOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublishRecipeResponse\": \"databrew:PublishRecipeResponse\",\n    \"ListRecipeVersionsResponse\": \"databrew:ListRecipeVersionsResponse\",\n    \"DeleteRecipeVersionRequest\": \"databrew:DeleteRecipeVersionRequest\",\n    \"PathParametersMap\": \"databrew:PathParametersMap\",\n    \"DeleteJobRequest\": \"databrew:DeleteJobRequest\",\n    \"CreateRecipeJobRequest\": \"databrew:CreateRecipeJobRequest\",\n    \"UpdateProfileJobResponse\": \"databrew:UpdateProfileJobResponse\"\
  ,\n    \"Input\": {\n      \"@id\": \"databrew:Input\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateScheduleResponse\": \"databrew:UpdateScheduleResponse\",\n    \"ListJobRunsResponse\": \"databrew:ListJobRunsResponse\",\n    \"Recipe\": \"databrew:Recipe\",\n    \"CsvOptions\": \"databrew:CsvOptions\",\n    \"FilesLimit\": {\n      \"@id\": \"databrew:FilesLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeJobResponse\": \"databrew:DescribeJobResponse\",\n    \"UpdateProjectResponse\": \"databrew:UpdateProjectResponse\",\n    \"DescribeDatasetRequest\": \"databrew:DescribeDatasetRequest\",\n    \"JsonOptions\": \"databrew:JsonOptions\",\n    \"DeleteProjectResponse\": \"databrew:DeleteProjectResponse\",\n    \"UpdateRulesetRequest\": \"databrew:UpdateRulesetRequest\",\n    \"StatisticsConfiguration\": \"databrew:StatisticsConfiguration\",\n    \"ViewFrame\": {\n      \"@id\": \"databrew:ViewFrame\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataCatalogOutput\"\
  : \"databrew:DataCatalogOutput\",\n    \"DeleteScheduleResponse\": \"databrew:DeleteScheduleResponse\",\n    \"JobSample\": {\n      \"@id\": \"databrew:JobSample\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StopJobRunResponse\": \"databrew:StopJobRunResponse\",\n    \"CreateRulesetResponse\": \"databrew:CreateRulesetResponse\",\n    \"UpdateRecipeJobRequest\": \"databrew:UpdateRecipeJobRequest\",\n    \"SendProjectSessionActionResponse\": \"databrew:SendProjectSessionActionResponse\",\n    \"DescribeDatasetResponse\": \"databrew:DescribeDatasetResponse\",\n    \"DescribeRecipeResponse\": \"databrew:DescribeRecipeResponse\",\n    \"RulesetItem\": \"databrew:RulesetItem\",\n    \"Metadata\": {\n      \"@id\": \"databrew:Metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeRecipeRequest\": \"databrew:DescribeRecipeRequest\",\n    \"StartJobRunRequest\": \"databrew:StartJobRunRequest\",\n    \"ListProjectsRequest\": \"databrew:ListProjectsRequest\",\n    \"DeleteProjectRequest\"\
  : \"databrew:DeleteProjectRequest\",\n    \"ListRulesetsResponse\": \"databrew:ListRulesetsResponse\",\n    \"DatabaseTableOutputOptions\": \"databrew:DatabaseTableOutputOptions\",\n    \"RecipeReference\": {\n      \"@id\": \"databrew:RecipeReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileConfiguration\": {\n      \"@id\": \"databrew:ProfileConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublishRecipeRequest\": \"databrew:PublishRecipeRequest\",\n    \"FilterExpression\": \"databrew:FilterExpression\",\n    \"Schedule\": \"databrew:Schedule\",\n    \"DescribeScheduleRequest\": \"databrew:DescribeScheduleRequest\",\n    \"TagResourceResponse\": \"databrew:TagResourceResponse\",\n    \"OutputFormatOptions\": \"databrew:OutputFormatOptions\",\n    \"ColumnStatisticsConfiguration\": \"databrew:ColumnStatisticsConfiguration\",\n    \"DatasetParameter\": \"databrew:DatasetParameter\",\n    \"ListTagsForResourceRequest\": \"databrew:ListTagsForResourceRequest\"\
  ,\n    \"DatabaseInputDefinition\": {\n      \"@id\": \"databrew:DatabaseInputDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateRulesetResponse\": \"databrew:UpdateRulesetResponse\",\n    \"CreateRecipeResponse\": \"databrew:CreateRecipeResponse\",\n    \"ListRecipeVersionsRequest\": \"databrew:ListRecipeVersionsRequest\",\n    \"DescribeJobRunResponse\": \"databrew:DescribeJobRunResponse\",\n    \"RecipeVersionErrorDetail\": \"databrew:RecipeVersionErrorDetail\",\n    \"UpdateProjectRequest\": \"databrew:UpdateProjectRequest\",\n    \"CreateProfileJobResponse\": \"databrew:CreateProfileJobResponse\",\n    \"AllowedStatistics\": {\n      \"@id\": \"databrew:AllowedStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteRulesetResponse\": \"databrew:DeleteRulesetResponse\",\n    \"UntagResourceRequest\": \"databrew:UntagResourceRequest\",\n    \"Dataset\": \"databrew:Dataset\",\n    \"CreateProjectResponse\": \"databrew:CreateProjectResponse\",\n    \"CreateDatasetRequest\"\
  : \"databrew:CreateDatasetRequest\",\n    \"DeleteRecipeVersionResponse\": \"databrew:DeleteRecipeVersionResponse\",\n    \"DataCatalogInputDefinition\": {\n      \"@id\": \"databrew:DataCatalogInputDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListRulesetsRequest\": \"databrew:ListRulesetsRequest\",\n    \"ConditionExpression\": \"databrew:ConditionExpression\",\n    \"DeleteRulesetRequest\": \"databrew:DeleteRulesetRequest\",\n    \"ValuesMap\": {\n      \"@id\": \"databrew:ValuesMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FormatOptions\": {\n      \"@id\": \"databrew:FormatOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchDeleteRecipeVersionResponse\": \"databrew:BatchDeleteRecipeVersionResponse\",\n    \"S3Location\": \"databrew:S3Location\",\n    \"DescribeJobRequest\": \"databrew:DescribeJobRequest\",\n    \"DatetimeOptions\": {\n      \"@id\": \"databrew:DatetimeOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateRecipeJobResponse\"\
  : \"databrew:CreateRecipeJobResponse\",\n    \"Sample\": {\n      \"@id\": \"databrew:Sample\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateScheduleResponse\": \"databrew:CreateScheduleResponse\",\n    \"Rule\": \"databrew:Rule\",\n    \"DeleteJobResponse\": \"databrew:DeleteJobResponse\",\n    \"JobRun\": \"databrew:JobRun\",\n    \"ListRecipesRequest\": \"databrew:ListRecipesRequest\",\n    \"ListProjectsResponse\": \"databrew:ListProjectsResponse\",\n    \"TagMap\": \"databrew:TagMap\",\n    \"CreateScheduleRequest\": \"databrew:CreateScheduleRequest\",\n    \"DatabaseOutput\": \"databrew:DatabaseOutput\",\n    \"StatisticOverride\": \"databrew:StatisticOverride\",\n    \"DescribeScheduleResponse\": \"databrew:DescribeScheduleResponse\",\n    \"ListTagsForResourceResponse\": \"databrew:ListTagsForResourceResponse\",\n    \"UpdateRecipeResponse\": \"databrew:UpdateRecipeResponse\",\n    \"ListJobsRequest\": \"databrew:ListJobsRequest\",\n    \"Threshold\": {\n      \"@id\"\
  : \"databrew:Threshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateDatasetResponse\": \"databrew:UpdateDatasetResponse\",\n    \"SendProjectSessionActionRequest\": \"databrew:SendProjectSessionActionRequest\",\n    \"CreateProjectRequest\": \"databrew:CreateProjectRequest\",\n    \"CreateRecipeRequest\": \"databrew:CreateRecipeRequest\",\n    \"DeleteDatasetResponse\": \"databrew:DeleteDatasetResponse\",\n    \"UpdateProfileJobRequest\": \"databrew:UpdateProfileJobRequest\",\n    \"UntagResourceResponse\": \"databrew:UntagResourceResponse\",\n    \"ExcelOptions\": \"databrew:ExcelOptions\",\n    \"ListSchedulesRequest\": \"databrew:ListSchedulesRequest\",\n    \"DescribeRulesetRequest\": \"databrew:DescribeRulesetRequest\",\n    \"Project\": \"databrew:Project\",\n    \"ListDatasetsRequest\": \"databrew:ListDatasetsRequest\",\n    \"UpdateDatasetRequest\": \"databrew:UpdateDatasetRequest\",\n    \"Job\": \"databrew:Job\",\n    \"DescribeProjectResponse\": \"databrew:DescribeProjectResponse\"\
  ,\n    \"Location\": {\n      \"@id\": \"databrew:Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobNames\": {\n      \"@id\": \"databrew:JobNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CronExpression\": {\n      \"@id\": \"databrew:CronExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecipeVersions\": {\n      \"@id\": \"databrew:RecipeVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schedules\": {\n      \"@id\": \"databrew:Schedules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"databrew:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Recipes\": {\n      \"@id\": \"databrew:Recipes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": \"schema:description\",\n    \"Steps\": {\n      \"@id\": \"databrew:Steps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"databrew:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Jobs\": {\n      \"@id\"\
  : \"databrew:Jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetName\": {\n      \"@id\": \"databrew:DatasetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EncryptionKeyArn\": {\n      \"@id\": \"databrew:EncryptionKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EncryptionMode\": {\n      \"@id\": \"databrew:EncryptionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": \"schema:name\",\n    \"LogSubscription\": {\n      \"@id\": \"databrew:LogSubscription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxCapacity\": {\n      \"@id\": \"databrew:MaxCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxRetries\": {\n      \"@id\": \"databrew:MaxRetries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputLocation\": {\n      \"@id\": \"databrew:OutputLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Configuration\": {\n      \"@id\": \"databrew:Configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationConfigurations\"\
  : {\n      \"@id\": \"databrew:ValidationConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"databrew:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timeout\": {\n      \"@id\": \"databrew:Timeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Action\": {\n      \"@id\": \"databrew:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionExpressions\": {\n      \"@id\": \"databrew:ConditionExpressions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Operation\": {\n      \"@id\": \"databrew:Operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Parameters\": {\n      \"@id\": \"databrew:Parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RulesetArn\": {\n      \"@id\": \"databrew:RulesetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationMode\": {\n      \"@id\": \"databrew:ValidationMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RunId\": {\n      \"@id\": \"databrew:RunId\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Datasets\": {\n      \"@id\": \"databrew:Datasets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetArn\": {\n      \"@id\": \"databrew:TargetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rules\": {\n      \"@id\": \"databrew:Rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Delimiter\": {\n      \"@id\": \"databrew:Delimiter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompressionFormat\": {\n      \"@id\": \"databrew:CompressionFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Format\": {\n      \"@id\": \"databrew:Format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PartitionColumns\": {\n      \"@id\": \"databrew:PartitionColumns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Overwrite\": {\n      \"@id\": \"databrew:Overwrite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxOutputFiles\": {\n      \"@id\": \"databrew:MaxOutputFiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  ClientSessionId\": {\n      \"@id\": \"databrew:ClientSessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityTypes\": {\n      \"@id\": \"databrew:EntityTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateDate\": {\n      \"@id\": \"databrew:CreateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedBy\": {\n      \"@id\": \"databrew:CreatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedBy\": {\n      \"@id\": \"databrew:LastModifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"databrew:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"databrew:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssumeControl\": {\n      \"@id\": \"databrew:AssumeControl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Regex\": {\n      \"@id\": \"databrew:Regex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDateCondition\"\
  : {\n      \"@id\": \"databrew:LastModifiedDateCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Outputs\": {\n      \"@id\": \"databrew:Outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataCatalogOutputs\": {\n      \"@id\": \"databrew:DataCatalogOutputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseOutputs\": {\n      \"@id\": \"databrew:DatabaseOutputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProjectName\": {\n      \"@id\": \"databrew:ProjectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3InputDefinition\": {\n      \"@id\": \"databrew:S3InputDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobRuns\": {\n      \"@id\": \"databrew:JobRuns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublishedBy\": {\n      \"@id\": \"databrew:PublishedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PublishedDate\": {\n      \"@id\": \"databrew:PublishedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecipeVersion\"\
  : {\n      \"@id\": \"databrew:RecipeVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HeaderRow\": {\n      \"@id\": \"databrew:HeaderRow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxFiles\": {\n      \"@id\": \"databrew:MaxFiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderedBy\": {\n      \"@id\": \"databrew:OrderedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Order\": {\n      \"@id\": \"databrew:Order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"databrew:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MultiLine\": {\n      \"@id\": \"databrew:MultiLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncludedStatistics\": {\n      \"@id\": \"databrew:IncludedStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Overrides\": {\n      \"@id\": \"databrew:Overrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartColumnIndex\": {\n      \"@id\": \"databrew:StartColumnIndex\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"ColumnRange\": {\n      \"@id\": \"databrew:ColumnRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HiddenColumns\": {\n      \"@id\": \"databrew:HiddenColumns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartRowIndex\": {\n      \"@id\": \"databrew:StartRowIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RowRange\": {\n      \"@id\": \"databrew:RowRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Analytics\": {\n      \"@id\": \"databrew:Analytics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CatalogId\": {\n      \"@id\": \"databrew:CatalogId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseName\": {\n      \"@id\": \"databrew:DatabaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableName\": {\n      \"@id\": \"databrew:TableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Options\": {\n      \"@id\": \"databrew:S3Options\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseOptions\"\
  : {\n      \"@id\": \"databrew:DatabaseOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Mode\": {\n      \"@id\": \"databrew:Mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Size\": {\n      \"@id\": \"databrew:Size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Result\": {\n      \"@id\": \"databrew:Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActionId\": {\n      \"@id\": \"databrew:ActionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"databrew:Source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"databrew:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleCount\": {\n      \"@id\": \"databrew:RuleCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceArn\": {\n      \"@id\": \"databrew:SourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rulesets\": {\n      \"@id\": \"databrew:Rulesets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TempDirectory\"\
  : {\n      \"@id\": \"databrew:TempDirectory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasetStatisticsConfiguration\": {\n      \"@id\": \"databrew:DatasetStatisticsConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileColumns\": {\n      \"@id\": \"databrew:ProfileColumns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ColumnStatisticsConfigurations\": {\n      \"@id\": \"databrew:ColumnStatisticsConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Expression\": {\n      \"@id\": \"databrew:Expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Csv\": {\n      \"@id\": \"databrew:Csv\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Selectors\": {\n      \"@id\": \"databrew:Selectors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Statistics\": {\n      \"@id\": \"databrew:Statistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateColumn\": {\n      \"@id\": \"databrew:CreateColumn\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"Filter\": {\n      \"@id\": \"databrew:Filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GlueConnectionName\": {\n      \"@id\": \"databrew:GlueConnectionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseTableName\": {\n      \"@id\": \"databrew:DatabaseTableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueryString\": {\n      \"@id\": \"databrew:QueryString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attempt\": {\n      \"@id\": \"databrew:Attempt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompletedOn\": {\n      \"@id\": \"databrew:CompletedOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorMessage\": {\n      \"@id\": \"databrew:ErrorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExecutionTime\": {\n      \"@id\": \"databrew:ExecutionTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobName\": {\n      \"@id\": \"databrew:JobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n    \
  \  \"@id\": \"databrew:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogGroupName\": {\n      \"@id\": \"databrew:LogGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartedBy\": {\n      \"@id\": \"databrew:StartedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartedOn\": {\n      \"@id\": \"databrew:StartedOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"databrew:ErrorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Condition\": {\n      \"@id\": \"databrew:Condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"databrew:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetColumn\": {\n      \"@id\": \"databrew:TargetColumn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Json\": {\n      \"@id\": \"databrew:Json\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Excel\": {\n      \"@id\": \"databrew:Excel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Errors\"\
  : {\n      \"@id\": \"databrew:Errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Bucket\": {\n      \"@id\": \"databrew:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"databrew:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketOwner\": {\n      \"@id\": \"databrew:BucketOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimezoneOffset\": {\n      \"@id\": \"databrew:TimezoneOffset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LocaleCode\": {\n      \"@id\": \"databrew:LocaleCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Disabled\": {\n      \"@id\": \"databrew:Disabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckExpression\": {\n      \"@id\": \"databrew:CheckExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubstitutionMap\": {\n      \"@id\": \"databrew:SubstitutionMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ColumnSelectors\": {\n      \"@id\": \"databrew:ColumnSelectors\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Projects\": {\n      \"@id\": \"databrew:Projects\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseOutputMode\": {\n      \"@id\": \"databrew:DatabaseOutputMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Statistic\": {\n      \"@id\": \"databrew:Statistic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Unit\": {\n      \"@id\": \"databrew:Unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Preview\": {\n      \"@id\": \"databrew:Preview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StepIndex\": {\n      \"@id\": \"databrew:StepIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecipeName\": {\n      \"@id\": \"databrew:RecipeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SheetNames\": {\n      \"@id\": \"databrew:SheetNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SheetIndexes\": {\n      \"@id\": \"databrew:SheetIndexes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenedBy\": {\n\
  \      \"@id\": \"databrew:OpenedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenDate\": {\n      \"@id\": \"databrew:OpenDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SessionStatus\": {\n      \"@id\": \"databrew:SessionStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-glue-databrew/refs/heads/main/json-ld/amazon-glue-databrew-context.jsonld
tags:
- AWS
- Data Analytics
- Data Preparation
- ETL
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
