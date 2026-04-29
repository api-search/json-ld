---
api_specs:
- filename: amazon-lookout-for-metrics-openapi-original.yaml
  format: yaml
  label: Amazon Lookout for Metrics API
  slug: amazon-lookout-for-metrics-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/openapi/amazon-lookout-for-metrics-openapi-original.yaml
class_count: 117
classes:
- Action
- ActivateAnomalyDetectorRequest
- ActivateAnomalyDetectorResponse
- Alert
- AlertFilters
- AlertSummary
- AnomalyDetectorConfig
- AnomalyDetectorConfigSummary
- AnomalyDetectorDataQualityMetric
- AnomalyDetectorSummary
- AnomalyGroup
- AnomalyGroupStatistics
- AnomalyGroupSummary
- AnomalyGroupTimeSeries
- AnomalyGroupTimeSeriesFeedback
- AppFlowConfig
- AthenaSourceConfig
- AttributeValue
- AutoDetectionMetricSource
- AutoDetectionS3SourceConfig
- BackTestAnomalyDetectorRequest
- BackTestAnomalyDetectorResponse
- BackTestConfiguration
- CloudWatchConfig
- ContributionMatrix
- CreateAlertRequest
- CreateAlertResponse
- CreateAnomalyDetectorRequest
- CreateAnomalyDetectorResponse
- CreateMetricSetRequest
- CreateMetricSetResponse
- CsvFormatDescriptor
- DataQualityMetric
- DeactivateAnomalyDetectorRequest
- DeactivateAnomalyDetectorResponse
- DeleteAlertRequest
- DeleteAlertResponse
- DeleteAnomalyDetectorRequest
- DeleteAnomalyDetectorResponse
- DescribeAlertRequest
- DescribeAlertResponse
- DescribeAnomalyDetectionExecutionsRequest
- DescribeAnomalyDetectionExecutionsResponse
- DescribeAnomalyDetectorRequest
- DescribeAnomalyDetectorResponse
- DescribeMetricSetRequest
- DescribeMetricSetResponse
- DetectMetricSetConfigRequest
- DetectMetricSetConfigResponse
- DetectedCsvFormatDescriptor
- DetectedField
- DetectedFileFormatDescriptor
- DetectedJsonFormatDescriptor
- DetectedMetricSetConfig
- DetectedMetricSource
- DetectedS3SourceConfig
- DimensionContribution
- DimensionFilter
- DimensionNameValue
- DimensionValueContribution
- ExecutionStatus
- FileFormatDescriptor
- Filter
- GetAnomalyGroupRequest
- GetAnomalyGroupResponse
- GetDataQualityMetricsRequest
- GetDataQualityMetricsResponse
- GetFeedbackRequest
- GetFeedbackResponse
- GetSampleDataRequest
- GetSampleDataResponse
- InterMetricImpactDetails
- ItemizedMetricStats
- JsonFormatDescriptor
- LambdaConfiguration
- ListAlertsRequest
- ListAlertsResponse
- ListAnomalyDetectorsRequest
- ListAnomalyDetectorsResponse
- ListAnomalyGroupRelatedMetricsRequest
- ListAnomalyGroupRelatedMetricsResponse
- ListAnomalyGroupSummariesRequest
- ListAnomalyGroupSummariesResponse
- ListAnomalyGroupTimeSeriesRequest
- ListAnomalyGroupTimeSeriesResponse
- ListMetricSetsRequest
- ListMetricSetsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- Metric
- MetricLevelImpact
- MetricSetDataQualityMetric
- MetricSetDimensionFilter
- MetricSetSummary
- MetricSource
- PutFeedbackRequest
- PutFeedbackResponse
- RDSSourceConfig
- RedshiftSourceConfig
- S3SourceConfig
- SNSConfiguration
- SampleDataS3SourceConfig
- TagMap
- TagResourceRequest
- TagResourceResponse
- TimeSeries
- TimeSeriesFeedback
- TimestampColumn
- UntagResourceRequest
- UntagResourceResponse
- UpdateAlertRequest
- UpdateAlertResponse
- UpdateAnomalyDetectorRequest
- UpdateAnomalyDetectorResponse
- UpdateMetricSetRequest
- UpdateMetricSetResponse
- VpcConfiguration
context_file: json-ld/amazon-lookout-for-metrics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/json-ld/amazon-lookout-for-metrics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Lookout For Metrics from Amazon Lookout for Metrics.
layout: jsonld
name: Amazon Lookout For Metrics Context
namespaces:
- prefix: alm
  uri: https://alm.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AggregationFunction
  type: ''
- container: ''
  name: AlertArn
  type: ''
- container: ''
  name: AlertDescription
  type: ''
- container: ''
  name: AlertName
  type: ''
- container: ''
  name: AlertSensitivityThreshold
  type: ''
- container: ''
  name: AlertStatus
  type: ''
- container: ''
  name: AlertSummaryList
  type: ''
- container: ''
  name: AlertType
  type: ''
- container: ''
  name: AnomalyDetectorArn
  type: ''
- container: ''
  name: AnomalyDetectorDataQualityMetricList
  type: ''
- container: ''
  name: AnomalyDetectorDescription
  type: ''
- container: ''
  name: AnomalyDetectorFrequency
  type: ''
- container: ''
  name: AnomalyDetectorName
  type: ''
- container: ''
  name: AnomalyDetectorSummaryList
  type: ''
- container: ''
  name: AnomalyGroupId
  type: ''
- container: ''
  name: AnomalyGroupScore
  type: ''
- container: ''
  name: AnomalyGroupSummaryList
  type: ''
- container: ''
  name: B
  type: ''
- container: ''
  name: BS
  type: ''
- container: ''
  name: Charset
  type: ''
- container: ''
  name: ClusterIdentifier
  type: ''
- container: ''
  name: ColumnFormat
  type: ''
- container: ''
  name: ColumnName
  type: ''
- container: ''
  name: Confidence
  type: ''
- container: ''
  name: ContainsHeader
  type: ''
- container: ''
  name: ContributionPercentage
  type: ''
- container: ''
  name: ContributionScore
  type: ''
- container: ''
  name: CreationTime
  type: ''
- container: ''
  name: DBInstanceIdentifier
  type: ''
- container: ''
  name: DataCatalog
  type: ''
- container: ''
  name: DataQualityMetricList
  type: ''
- container: ''
  name: DatabaseHost
  type: ''
- container: ''
  name: DatabaseName
  type: ''
- container: ''
  name: DatabasePort
  type: ''
- container: ''
  name: Delimiter
  type: ''
- container: ''
  name: DimensionContributionList
  type: ''
- container: ''
  name: DimensionFilterList
  type: ''
- container: ''
  name: DimensionList
  type: ''
- container: ''
  name: DimensionName
  type: ''
- container: ''
  name: DimensionValue
  type: ''
- container: ''
  name: DimensionValueContributionList
  type: ''
- container: ''
  name: DimensionValueList
  type: ''
- container: ''
  name: EndTime
  type: ''
- container: ''
  name: EvaluationStartDate
  type: ''
- container: ''
  name: ExecutionList
  type: ''
- container: ''
  name: FailureReason
  type: ''
- container: ''
  name: FailureType
  type: ''
- container: ''
  name: FileCompression
  type: ''
- container: ''
  name: FilterList
  type: ''
- container: ''
  name: FilterOperation
  type: ''
- container: ''
  name: FlowName
  type: ''
- container: ''
  name: HeaderList
  type: ''
- container: ''
  name: HeaderValues
  type: ''
- container: ''
  name: HistoricalDataPathList
  type: ''
- container: ''
  name: InterMetricImpactList
  type: ''
- container: ''
  name: IsAnomaly
  type: ''
- container: ''
  name: ItemizedMetricStatsList
  type: ''
- container: ''
  name: KmsKeyArn
  type: ''
- container: ''
  name: LambdaArn
  type: ''
- container: ''
  name: LastModificationTime
  type: ''
- container: ''
  name: MaxResults
  type: ''
- container: ''
  name: Message
  type: ''
- container: ''
  name: MetricDescription
  type: ''
- container: ''
  name: MetricLevelImpactList
  type: ''
- container: ''
  name: MetricList
  type: ''
- container: ''
  name: MetricName
  type: ''
- container: ''
  name: MetricSetArn
  type: ''
- container: ''
  name: MetricSetDataQualityMetricList
  type: ''
- container: ''
  name: MetricSetDescription
  type: ''
- container: ''
  name: MetricSetFrequency
  type: ''
- container: ''
  name: MetricSetName
  type: ''
- container: ''
  name: MetricSetSummaryList
  type: ''
- container: ''
  name: MetricType
  type: ''
- container: ''
  name: MetricValue
  type: ''
- container: ''
  name: MetricValueList
  type: ''
- container: ''
  name: N
  type: ''
- container: ''
  name: NS
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: Namespace
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: NumTimeSeries
  type: ''
- container: ''
  name: OccurrenceCount
  type: ''
- container: ''
  name: Offset
  type: ''
- container: ''
  name: PrimaryMetricName
  type: ''
- container: ''
  name: QuoteSymbol
  type: ''
- container: ''
  name: RelatedColumnName
  type: ''
- container: ''
  name: RelationshipType
  type: ''
- container: ''
  name: RelationshipTypeFilter
  type: ''
- container: ''
  name: RoleArn
  type: ''
- container: ''
  name: RunBackTestMode
  type: ''
- container: ''
  name: S
  type: ''
- container: ''
  name: S3ResultsPath
  type: ''
- container: ''
  name: SS
  type: ''
- container: ''
  name: SampleRows
  type: ''
- container: ''
  name: SecretManagerArn
  type: ''
- container: ''
  name: SecurityGroupIdList
  type: ''
- container: ''
  name: SensitivityThreshold
  type: ''
- container: ''
  name: SnsFormat
  type: ''
- container: ''
  name: SnsTopicArn
  type: ''
- container: ''
  name: StartTime
  type: ''
- container: ''
  name: StartTimestamp
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: SubnetIdList
  type: ''
- container: ''
  name: TableName
  type: ''
- container: ''
  name: Tags
  type: ''
- container: ''
  name: TemplatedPathList
  type: ''
- container: ''
  name: TimeSeriesId
  type: ''
- container: ''
  name: TimeSeriesList
  type: ''
- container: ''
  name: Timestamp
  type: ''
- container: ''
  name: TimestampList
  type: ''
- container: ''
  name: Timezone
  type: ''
- container: ''
  name: TotalCount
  type: ''
- container: ''
  name: Value
  type: ''
- container: ''
  name: WorkGroupName
  type: ''
property_count: 114
provider_name: Amazon Lookout for Metrics
provider_slug: amazon-lookout-for-metrics
slug: amazon-lookout-for-metrics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alm\": \"https://alm.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Action\": \"alm:Action\",\n    \"ActivateAnomalyDetectorRequest\": \"alm:ActivateAnomalyDetectorRequest\",\n    \"ActivateAnomalyDetectorResponse\": \"alm:ActivateAnomalyDetectorResponse\",\n    \"Alert\": \"alm:Alert\",\n    \"AlertFilters\": \"alm:AlertFilters\",\n    \"AlertSummary\": \"alm:AlertSummary\",\n    \"AnomalyDetectorConfig\": \"alm:AnomalyDetectorConfig\",\n    \"AnomalyDetectorConfigSummary\": \"alm:AnomalyDetectorConfigSummary\",\n    \"AnomalyDetectorDataQualityMetric\": \"alm:AnomalyDetectorDataQualityMetric\",\n    \"AnomalyDetectorSummary\": \"alm:AnomalyDetectorSummary\",\n    \"AnomalyGroup\": \"alm:AnomalyGroup\",\n    \"AnomalyGroupStatistics\": \"alm:AnomalyGroupStatistics\",\n    \"AnomalyGroupSummary\"\
  : \"alm:AnomalyGroupSummary\",\n    \"AnomalyGroupTimeSeries\": \"alm:AnomalyGroupTimeSeries\",\n    \"AnomalyGroupTimeSeriesFeedback\": \"alm:AnomalyGroupTimeSeriesFeedback\",\n    \"AppFlowConfig\": \"alm:AppFlowConfig\",\n    \"AthenaSourceConfig\": \"alm:AthenaSourceConfig\",\n    \"AttributeValue\": \"alm:AttributeValue\",\n    \"AutoDetectionMetricSource\": \"alm:AutoDetectionMetricSource\",\n    \"AutoDetectionS3SourceConfig\": \"alm:AutoDetectionS3SourceConfig\",\n    \"BackTestAnomalyDetectorRequest\": \"alm:BackTestAnomalyDetectorRequest\",\n    \"BackTestAnomalyDetectorResponse\": \"alm:BackTestAnomalyDetectorResponse\",\n    \"BackTestConfiguration\": \"alm:BackTestConfiguration\",\n    \"CloudWatchConfig\": \"alm:CloudWatchConfig\",\n    \"ContributionMatrix\": \"alm:ContributionMatrix\",\n    \"CreateAlertRequest\": \"alm:CreateAlertRequest\",\n    \"CreateAlertResponse\": \"alm:CreateAlertResponse\",\n    \"CreateAnomalyDetectorRequest\": \"alm:CreateAnomalyDetectorRequest\"\
  ,\n    \"CreateAnomalyDetectorResponse\": \"alm:CreateAnomalyDetectorResponse\",\n    \"CreateMetricSetRequest\": \"alm:CreateMetricSetRequest\",\n    \"CreateMetricSetResponse\": \"alm:CreateMetricSetResponse\",\n    \"CsvFormatDescriptor\": \"alm:CsvFormatDescriptor\",\n    \"DataQualityMetric\": \"alm:DataQualityMetric\",\n    \"DeactivateAnomalyDetectorRequest\": \"alm:DeactivateAnomalyDetectorRequest\",\n    \"DeactivateAnomalyDetectorResponse\": \"alm:DeactivateAnomalyDetectorResponse\",\n    \"DeleteAlertRequest\": \"alm:DeleteAlertRequest\",\n    \"DeleteAlertResponse\": \"alm:DeleteAlertResponse\",\n    \"DeleteAnomalyDetectorRequest\": \"alm:DeleteAnomalyDetectorRequest\",\n    \"DeleteAnomalyDetectorResponse\": \"alm:DeleteAnomalyDetectorResponse\",\n    \"DescribeAlertRequest\": \"alm:DescribeAlertRequest\",\n    \"DescribeAlertResponse\": \"alm:DescribeAlertResponse\",\n    \"DescribeAnomalyDetectionExecutionsRequest\": \"alm:DescribeAnomalyDetectionExecutionsRequest\",\n\
  \    \"DescribeAnomalyDetectionExecutionsResponse\": \"alm:DescribeAnomalyDetectionExecutionsResponse\",\n    \"DescribeAnomalyDetectorRequest\": \"alm:DescribeAnomalyDetectorRequest\",\n    \"DescribeAnomalyDetectorResponse\": \"alm:DescribeAnomalyDetectorResponse\",\n    \"DescribeMetricSetRequest\": \"alm:DescribeMetricSetRequest\",\n    \"DescribeMetricSetResponse\": \"alm:DescribeMetricSetResponse\",\n    \"DetectMetricSetConfigRequest\": \"alm:DetectMetricSetConfigRequest\",\n    \"DetectMetricSetConfigResponse\": \"alm:DetectMetricSetConfigResponse\",\n    \"DetectedCsvFormatDescriptor\": \"alm:DetectedCsvFormatDescriptor\",\n    \"DetectedField\": \"alm:DetectedField\",\n    \"DetectedFileFormatDescriptor\": \"alm:DetectedFileFormatDescriptor\",\n    \"DetectedJsonFormatDescriptor\": \"alm:DetectedJsonFormatDescriptor\",\n    \"DetectedMetricSetConfig\": \"alm:DetectedMetricSetConfig\",\n    \"DetectedMetricSource\": \"alm:DetectedMetricSource\",\n    \"DetectedS3SourceConfig\"\
  : \"alm:DetectedS3SourceConfig\",\n    \"DimensionContribution\": \"alm:DimensionContribution\",\n    \"DimensionFilter\": \"alm:DimensionFilter\",\n    \"DimensionNameValue\": \"alm:DimensionNameValue\",\n    \"DimensionValueContribution\": \"alm:DimensionValueContribution\",\n    \"ExecutionStatus\": \"alm:ExecutionStatus\",\n    \"FileFormatDescriptor\": \"alm:FileFormatDescriptor\",\n    \"Filter\": \"alm:Filter\",\n    \"GetAnomalyGroupRequest\": \"alm:GetAnomalyGroupRequest\",\n    \"GetAnomalyGroupResponse\": \"alm:GetAnomalyGroupResponse\",\n    \"GetDataQualityMetricsRequest\": \"alm:GetDataQualityMetricsRequest\",\n    \"GetDataQualityMetricsResponse\": \"alm:GetDataQualityMetricsResponse\",\n    \"GetFeedbackRequest\": \"alm:GetFeedbackRequest\",\n    \"GetFeedbackResponse\": \"alm:GetFeedbackResponse\",\n    \"GetSampleDataRequest\": \"alm:GetSampleDataRequest\",\n    \"GetSampleDataResponse\": \"alm:GetSampleDataResponse\",\n    \"InterMetricImpactDetails\": \"alm:InterMetricImpactDetails\"\
  ,\n    \"ItemizedMetricStats\": \"alm:ItemizedMetricStats\",\n    \"JsonFormatDescriptor\": \"alm:JsonFormatDescriptor\",\n    \"LambdaConfiguration\": \"alm:LambdaConfiguration\",\n    \"ListAlertsRequest\": \"alm:ListAlertsRequest\",\n    \"ListAlertsResponse\": \"alm:ListAlertsResponse\",\n    \"ListAnomalyDetectorsRequest\": \"alm:ListAnomalyDetectorsRequest\",\n    \"ListAnomalyDetectorsResponse\": \"alm:ListAnomalyDetectorsResponse\",\n    \"ListAnomalyGroupRelatedMetricsRequest\": \"alm:ListAnomalyGroupRelatedMetricsRequest\",\n    \"ListAnomalyGroupRelatedMetricsResponse\": \"alm:ListAnomalyGroupRelatedMetricsResponse\",\n    \"ListAnomalyGroupSummariesRequest\": \"alm:ListAnomalyGroupSummariesRequest\",\n    \"ListAnomalyGroupSummariesResponse\": \"alm:ListAnomalyGroupSummariesResponse\",\n    \"ListAnomalyGroupTimeSeriesRequest\": \"alm:ListAnomalyGroupTimeSeriesRequest\",\n    \"ListAnomalyGroupTimeSeriesResponse\": \"alm:ListAnomalyGroupTimeSeriesResponse\",\n    \"ListMetricSetsRequest\"\
  : \"alm:ListMetricSetsRequest\",\n    \"ListMetricSetsResponse\": \"alm:ListMetricSetsResponse\",\n    \"ListTagsForResourceRequest\": \"alm:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"alm:ListTagsForResourceResponse\",\n    \"Metric\": \"alm:Metric\",\n    \"MetricLevelImpact\": \"alm:MetricLevelImpact\",\n    \"MetricSetDataQualityMetric\": \"alm:MetricSetDataQualityMetric\",\n    \"MetricSetDimensionFilter\": \"alm:MetricSetDimensionFilter\",\n    \"MetricSetSummary\": \"alm:MetricSetSummary\",\n    \"MetricSource\": \"alm:MetricSource\",\n    \"PutFeedbackRequest\": \"alm:PutFeedbackRequest\",\n    \"PutFeedbackResponse\": \"alm:PutFeedbackResponse\",\n    \"RDSSourceConfig\": \"alm:RDSSourceConfig\",\n    \"RedshiftSourceConfig\": \"alm:RedshiftSourceConfig\",\n    \"S3SourceConfig\": \"alm:S3SourceConfig\",\n    \"SNSConfiguration\": \"alm:SNSConfiguration\",\n    \"SampleDataS3SourceConfig\": \"alm:SampleDataS3SourceConfig\",\n    \"TagMap\": \"alm:TagMap\"\
  ,\n    \"TagResourceRequest\": \"alm:TagResourceRequest\",\n    \"TagResourceResponse\": \"alm:TagResourceResponse\",\n    \"TimeSeries\": \"alm:TimeSeries\",\n    \"TimeSeriesFeedback\": \"alm:TimeSeriesFeedback\",\n    \"TimestampColumn\": \"alm:TimestampColumn\",\n    \"UntagResourceRequest\": \"alm:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"alm:UntagResourceResponse\",\n    \"UpdateAlertRequest\": \"alm:UpdateAlertRequest\",\n    \"UpdateAlertResponse\": \"alm:UpdateAlertResponse\",\n    \"UpdateAnomalyDetectorRequest\": \"alm:UpdateAnomalyDetectorRequest\",\n    \"UpdateAnomalyDetectorResponse\": \"alm:UpdateAnomalyDetectorResponse\",\n    \"UpdateMetricSetRequest\": \"alm:UpdateMetricSetRequest\",\n    \"UpdateMetricSetResponse\": \"alm:UpdateMetricSetResponse\",\n    \"VpcConfiguration\": \"alm:VpcConfiguration\",\n    \"AggregationFunction\": {\n      \"@id\": \"alm:AggregationFunction\"\n    },\n    \"AlertArn\": {\n      \"@id\": \"alm:AlertArn\"\n    },\n    \"\
  AlertDescription\": {\n      \"@id\": \"alm:AlertDescription\"\n    },\n    \"AlertName\": {\n      \"@id\": \"alm:AlertName\"\n    },\n    \"AlertSensitivityThreshold\": {\n      \"@id\": \"alm:AlertSensitivityThreshold\"\n    },\n    \"AlertStatus\": {\n      \"@id\": \"alm:AlertStatus\"\n    },\n    \"AlertSummaryList\": {\n      \"@id\": \"alm:AlertSummaryList\"\n    },\n    \"AlertType\": {\n      \"@id\": \"alm:AlertType\"\n    },\n    \"AnomalyDetectorArn\": {\n      \"@id\": \"alm:AnomalyDetectorArn\"\n    },\n    \"AnomalyDetectorDataQualityMetricList\": {\n      \"@id\": \"alm:AnomalyDetectorDataQualityMetricList\"\n    },\n    \"AnomalyDetectorDescription\": {\n      \"@id\": \"alm:AnomalyDetectorDescription\"\n    },\n    \"AnomalyDetectorFrequency\": {\n      \"@id\": \"alm:AnomalyDetectorFrequency\"\n    },\n    \"AnomalyDetectorName\": {\n      \"@id\": \"alm:AnomalyDetectorName\"\n    },\n    \"AnomalyDetectorSummaryList\": {\n      \"@id\": \"alm:AnomalyDetectorSummaryList\"\
  \n    },\n    \"AnomalyGroupId\": {\n      \"@id\": \"alm:AnomalyGroupId\"\n    },\n    \"AnomalyGroupScore\": {\n      \"@id\": \"alm:AnomalyGroupScore\"\n    },\n    \"AnomalyGroupSummaryList\": {\n      \"@id\": \"alm:AnomalyGroupSummaryList\"\n    },\n    \"B\": {\n      \"@id\": \"alm:B\"\n    },\n    \"BS\": {\n      \"@id\": \"alm:BS\"\n    },\n    \"Charset\": {\n      \"@id\": \"alm:Charset\"\n    },\n    \"ClusterIdentifier\": {\n      \"@id\": \"alm:ClusterIdentifier\"\n    },\n    \"ColumnFormat\": {\n      \"@id\": \"alm:ColumnFormat\"\n    },\n    \"ColumnName\": {\n      \"@id\": \"alm:ColumnName\"\n    },\n    \"Confidence\": {\n      \"@id\": \"alm:Confidence\"\n    },\n    \"ContainsHeader\": {\n      \"@id\": \"alm:ContainsHeader\"\n    },\n    \"ContributionPercentage\": {\n      \"@id\": \"alm:ContributionPercentage\"\n    },\n    \"ContributionScore\": {\n      \"@id\": \"alm:ContributionScore\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"alm:CreationTime\"\
  \n    },\n    \"DBInstanceIdentifier\": {\n      \"@id\": \"alm:DBInstanceIdentifier\"\n    },\n    \"DataCatalog\": {\n      \"@id\": \"alm:DataCatalog\"\n    },\n    \"DataQualityMetricList\": {\n      \"@id\": \"alm:DataQualityMetricList\"\n    },\n    \"DatabaseHost\": {\n      \"@id\": \"alm:DatabaseHost\"\n    },\n    \"DatabaseName\": {\n      \"@id\": \"alm:DatabaseName\"\n    },\n    \"DatabasePort\": {\n      \"@id\": \"alm:DatabasePort\"\n    },\n    \"Delimiter\": {\n      \"@id\": \"alm:Delimiter\"\n    },\n    \"DimensionContributionList\": {\n      \"@id\": \"alm:DimensionContributionList\"\n    },\n    \"DimensionFilterList\": {\n      \"@id\": \"alm:DimensionFilterList\"\n    },\n    \"DimensionList\": {\n      \"@id\": \"alm:DimensionList\"\n    },\n    \"DimensionName\": {\n      \"@id\": \"alm:DimensionName\"\n    },\n    \"DimensionValue\": {\n      \"@id\": \"alm:DimensionValue\"\n    },\n    \"DimensionValueContributionList\": {\n      \"@id\": \"alm:DimensionValueContributionList\"\
  \n    },\n    \"DimensionValueList\": {\n      \"@id\": \"alm:DimensionValueList\"\n    },\n    \"EndTime\": {\n      \"@id\": \"alm:EndTime\"\n    },\n    \"EvaluationStartDate\": {\n      \"@id\": \"alm:EvaluationStartDate\"\n    },\n    \"ExecutionList\": {\n      \"@id\": \"alm:ExecutionList\"\n    },\n    \"FailureReason\": {\n      \"@id\": \"alm:FailureReason\"\n    },\n    \"FailureType\": {\n      \"@id\": \"alm:FailureType\"\n    },\n    \"FileCompression\": {\n      \"@id\": \"alm:FileCompression\"\n    },\n    \"FilterList\": {\n      \"@id\": \"alm:FilterList\"\n    },\n    \"FilterOperation\": {\n      \"@id\": \"alm:FilterOperation\"\n    },\n    \"FlowName\": {\n      \"@id\": \"alm:FlowName\"\n    },\n    \"HeaderList\": {\n      \"@id\": \"alm:HeaderList\"\n    },\n    \"HeaderValues\": {\n      \"@id\": \"alm:HeaderValues\"\n    },\n    \"HistoricalDataPathList\": {\n      \"@id\": \"alm:HistoricalDataPathList\"\n    },\n    \"InterMetricImpactList\": {\n      \"@id\"\
  : \"alm:InterMetricImpactList\"\n    },\n    \"IsAnomaly\": {\n      \"@id\": \"alm:IsAnomaly\"\n    },\n    \"ItemizedMetricStatsList\": {\n      \"@id\": \"alm:ItemizedMetricStatsList\"\n    },\n    \"KmsKeyArn\": {\n      \"@id\": \"alm:KmsKeyArn\"\n    },\n    \"LambdaArn\": {\n      \"@id\": \"alm:LambdaArn\"\n    },\n    \"LastModificationTime\": {\n      \"@id\": \"alm:LastModificationTime\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"alm:MaxResults\"\n    },\n    \"Message\": {\n      \"@id\": \"alm:Message\"\n    },\n    \"MetricDescription\": {\n      \"@id\": \"alm:MetricDescription\"\n    },\n    \"MetricLevelImpactList\": {\n      \"@id\": \"alm:MetricLevelImpactList\"\n    },\n    \"MetricList\": {\n      \"@id\": \"alm:MetricList\"\n    },\n    \"MetricName\": {\n      \"@id\": \"alm:MetricName\"\n    },\n    \"MetricSetArn\": {\n      \"@id\": \"alm:MetricSetArn\"\n    },\n    \"MetricSetDataQualityMetricList\": {\n      \"@id\": \"alm:MetricSetDataQualityMetricList\"\
  \n    },\n    \"MetricSetDescription\": {\n      \"@id\": \"alm:MetricSetDescription\"\n    },\n    \"MetricSetFrequency\": {\n      \"@id\": \"alm:MetricSetFrequency\"\n    },\n    \"MetricSetName\": {\n      \"@id\": \"alm:MetricSetName\"\n    },\n    \"MetricSetSummaryList\": {\n      \"@id\": \"alm:MetricSetSummaryList\"\n    },\n    \"MetricType\": {\n      \"@id\": \"alm:MetricType\"\n    },\n    \"MetricValue\": {\n      \"@id\": \"alm:MetricValue\"\n    },\n    \"MetricValueList\": {\n      \"@id\": \"alm:MetricValueList\"\n    },\n    \"N\": {\n      \"@id\": \"alm:N\"\n    },\n    \"NS\": {\n      \"@id\": \"alm:NS\"\n    },\n    \"Name\": {\n      \"@id\": \"alm:Name\"\n    },\n    \"Namespace\": {\n      \"@id\": \"alm:Namespace\"\n    },\n    \"NextToken\": {\n      \"@id\": \"alm:NextToken\"\n    },\n    \"NumTimeSeries\": {\n      \"@id\": \"alm:NumTimeSeries\"\n    },\n    \"OccurrenceCount\": {\n      \"@id\": \"alm:OccurrenceCount\"\n    },\n    \"Offset\": {\n      \"\
  @id\": \"alm:Offset\"\n    },\n    \"PrimaryMetricName\": {\n      \"@id\": \"alm:PrimaryMetricName\"\n    },\n    \"QuoteSymbol\": {\n      \"@id\": \"alm:QuoteSymbol\"\n    },\n    \"RelatedColumnName\": {\n      \"@id\": \"alm:RelatedColumnName\"\n    },\n    \"RelationshipType\": {\n      \"@id\": \"alm:RelationshipType\"\n    },\n    \"RelationshipTypeFilter\": {\n      \"@id\": \"alm:RelationshipTypeFilter\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"alm:RoleArn\"\n    },\n    \"RunBackTestMode\": {\n      \"@id\": \"alm:RunBackTestMode\"\n    },\n    \"S\": {\n      \"@id\": \"alm:S\"\n    },\n    \"S3ResultsPath\": {\n      \"@id\": \"alm:S3ResultsPath\"\n    },\n    \"SS\": {\n      \"@id\": \"alm:SS\"\n    },\n    \"SampleRows\": {\n      \"@id\": \"alm:SampleRows\"\n    },\n    \"SecretManagerArn\": {\n      \"@id\": \"alm:SecretManagerArn\"\n    },\n    \"SecurityGroupIdList\": {\n      \"@id\": \"alm:SecurityGroupIdList\"\n    },\n    \"SensitivityThreshold\": {\n     \
  \ \"@id\": \"alm:SensitivityThreshold\"\n    },\n    \"SnsFormat\": {\n      \"@id\": \"alm:SnsFormat\"\n    },\n    \"SnsTopicArn\": {\n      \"@id\": \"alm:SnsTopicArn\"\n    },\n    \"StartTime\": {\n      \"@id\": \"alm:StartTime\"\n    },\n    \"StartTimestamp\": {\n      \"@id\": \"alm:StartTimestamp\"\n    },\n    \"Status\": {\n      \"@id\": \"alm:Status\"\n    },\n    \"SubnetIdList\": {\n      \"@id\": \"alm:SubnetIdList\"\n    },\n    \"TableName\": {\n      \"@id\": \"alm:TableName\"\n    },\n    \"Tags\": {\n      \"@id\": \"alm:Tags\"\n    },\n    \"TemplatedPathList\": {\n      \"@id\": \"alm:TemplatedPathList\"\n    },\n    \"TimeSeriesId\": {\n      \"@id\": \"alm:TimeSeriesId\"\n    },\n    \"TimeSeriesList\": {\n      \"@id\": \"alm:TimeSeriesList\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"alm:Timestamp\"\n    },\n    \"TimestampList\": {\n      \"@id\": \"alm:TimestampList\"\n    },\n    \"Timezone\": {\n      \"@id\": \"alm:Timezone\"\n    },\n    \"TotalCount\"\
  : {\n      \"@id\": \"alm:TotalCount\"\n    },\n    \"Value\": {\n      \"@id\": \"alm:Value\"\n    },\n    \"WorkGroupName\": {\n      \"@id\": \"alm:WorkGroupName\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-lookout-for-metrics/refs/heads/main/json-ld/amazon-lookout-for-metrics-context.jsonld
tags:
- Anomaly Detection
- AWS
- Business Intelligence
- Machine Learning
- Metrics
- Monitoring
- JSON-LD
- Linked Data
- Semantic Web
---
