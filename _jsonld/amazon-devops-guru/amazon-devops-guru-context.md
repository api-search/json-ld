---
api_specs:
- filename: amazon-devops-guru-openapi.yaml
  format: yaml
  label: Amazon DevOps Guru API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-devops-guru/refs/heads/main/openapi/amazon-devops-guru-openapi.yaml
class_count: 23
classes:
- AnomalousLogGroup
- CloudFormationCollection
- CloudFormationHealth
- Event
- EventSourcesConfig
- InsightHealth
- LogAnomalyShowcase
- NotificationChannel
- OpsCenterIntegration
- PerformanceInsightsMetricQuery
- ProactiveAnomaly
- ProactiveInsight
- ReactiveAnomaly
- ReactiveInsight
- Recommendation
- ServiceCollection
- ServiceHealth
- ServiceInsightHealth
- SnsChannelConfig
- TagCollection
- TagHealth
- Description
- Name
context_file: json-ld/amazon-devops-guru-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-devops-guru/refs/heads/main/json-ld/amazon-devops-guru-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Devops Guru from Amazon DevOps Guru.
layout: jsonld
name: Amazon Devops Guru Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/devops-guru/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ResourceCollection
  type: string
- container: ''
  name: AmazonCodeGuruProfiler
  type: string
- container: ''
  name: AnalyzedResourceCount
  type: string
- container: ''
  name: AnomalyReportedTimeRange
  type: string
- container: ''
  name: AnomalyResources
  type: string
- container: ''
  name: AnomalyTimeRange
  type: string
- container: ''
  name: AppBoundaryKey
  type: string
- container: ''
  name: AssociatedInsightId
  type: string
- container: ''
  name: Category
  type: string
- container: ''
  name: CausalAnomalyId
  type: string
- container: ''
  name: CloudFormation
  type: string
- container: ''
  name: Config
  type: string
- container: ''
  name: DataSource
  type: string
- container: ''
  name: EventClass
  type: string
- container: ''
  name: EventSource
  type: string
- container: ''
  name: Filter
  type: string
- container: ''
  name: GroupBy
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: ImpactEndTime
  type: string
- container: ''
  name: ImpactStartTime
  type: string
- container: ''
  name: Insight
  type: string
- container: ''
  name: InsightTimeRange
  type: string
- container: ''
  name: Limit
  type: string
- container: ''
  name: Link
  type: string
- container: ''
  name: LogAnomalyClasses
  type: string
- container: ''
  name: LogAnomalyShowcases
  type: string
- container: ''
  name: LogGroupName
  type: string
- container: ''
  name: MeanTimeToRecoverInMilliseconds
  type: string
- container: ''
  name: Metric
  type: string
- container: ''
  name: NumberOfLogLinesScanned
  type: string
- container: ''
  name: OpenProactiveInsights
  type: string
- container: ''
  name: OpenReactiveInsights
  type: string
- container: ''
  name: OptInStatus
  type: string
- container: ''
  name: PredictionTimeRange
  type: string
- container: ''
  name: Reason
  type: string
- container: ''
  name: RelatedAnomalies
  type: string
- container: ''
  name: RelatedEvents
  type: string
- container: ''
  name: Resources
  type: string
- container: ''
  name: ServiceName
  type: string
- container: ''
  name: ServiceNames
  type: string
- container: ''
  name: Severity
  type: string
- container: ''
  name: SourceDetails
  type: string
- container: ''
  name: SourceMetadata
  type: string
- container: ''
  name: SsmOpsItemId
  type: string
- container: ''
  name: StackName
  type: string
- container: ''
  name: StackNames
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: TagValue
  type: string
- container: ''
  name: TagValues
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Time
  type: string
- container: ''
  name: TopicArn
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: UpdateTime
  type: string
property_count: 54
provider_name: Amazon DevOps Guru
provider_slug: amazon-devops-guru
slug: amazon-devops-guru-context
source_filename: amazon-devops-guru-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/devops-guru/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AnomalousLogGroup\": \"amz:AnomalousLogGroup\",\n    \"CloudFormationCollection\": \"amz:CloudFormationCollection\",\n    \"CloudFormationHealth\": \"amz:CloudFormationHealth\",\n    \"Event\": \"amz:Event\",\n    \"EventSourcesConfig\": \"amz:EventSourcesConfig\",\n    \"InsightHealth\": \"amz:InsightHealth\",\n    \"LogAnomalyShowcase\": \"amz:LogAnomalyShowcase\",\n    \"NotificationChannel\": \"amz:NotificationChannel\",\n    \"OpsCenterIntegration\": \"amz:OpsCenterIntegration\",\n    \"PerformanceInsightsMetricQuery\": \"amz:PerformanceInsightsMetricQuery\",\n    \"ProactiveAnomaly\": \"amz:ProactiveAnomaly\",\n    \"ProactiveInsight\": \"amz:ProactiveInsight\",\n    \"ReactiveAnomaly\": \"amz:ReactiveAnomaly\",\n \
  \   \"ReactiveInsight\": \"amz:ReactiveInsight\",\n    \"Recommendation\": \"amz:Recommendation\",\n    \"ResourceCollection\": {\n      \"@id\": \"amz:ResourceCollection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceCollection\": \"amz:ServiceCollection\",\n    \"ServiceHealth\": \"amz:ServiceHealth\",\n    \"ServiceInsightHealth\": \"amz:ServiceInsightHealth\",\n    \"SnsChannelConfig\": \"amz:SnsChannelConfig\",\n    \"TagCollection\": \"amz:TagCollection\",\n    \"TagHealth\": \"amz:TagHealth\",\n    \"AmazonCodeGuruProfiler\": {\n      \"@id\": \"amz:AmazonCodeGuruProfiler\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnalyzedResourceCount\": {\n      \"@id\": \"amz:AnalyzedResourceCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnomalyReportedTimeRange\": {\n      \"@id\": \"amz:AnomalyReportedTimeRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnomalyResources\": {\n      \"@id\": \"amz:AnomalyResources\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"AnomalyTimeRange\": {\n      \"@id\": \"amz:AnomalyTimeRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppBoundaryKey\": {\n      \"@id\": \"amz:AppBoundaryKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociatedInsightId\": {\n      \"@id\": \"amz:AssociatedInsightId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Category\": {\n      \"@id\": \"amz:Category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CausalAnomalyId\": {\n      \"@id\": \"amz:CausalAnomalyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudFormation\": {\n      \"@id\": \"amz:CloudFormation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Config\": {\n      \"@id\": \"amz:Config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataSource\": {\n      \"@id\": \"amz:DataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": \"schema:description\",\n    \"EventClass\": {\n      \"@id\": \"amz:EventClass\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"EventSource\": {\n      \"@id\": \"amz:EventSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Filter\": {\n      \"@id\": \"amz:Filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupBy\": {\n      \"@id\": \"amz:GroupBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"amz:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpactEndTime\": {\n      \"@id\": \"amz:ImpactEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpactStartTime\": {\n      \"@id\": \"amz:ImpactStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Insight\": {\n      \"@id\": \"amz:Insight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightTimeRange\": {\n      \"@id\": \"amz:InsightTimeRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limit\": {\n      \"@id\": \"amz:Limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Link\": {\n      \"@id\": \"amz:Link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogAnomalyClasses\": {\n\
  \      \"@id\": \"amz:LogAnomalyClasses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogAnomalyShowcases\": {\n      \"@id\": \"amz:LogAnomalyShowcases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogGroupName\": {\n      \"@id\": \"amz:LogGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MeanTimeToRecoverInMilliseconds\": {\n      \"@id\": \"amz:MeanTimeToRecoverInMilliseconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metric\": {\n      \"@id\": \"amz:Metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": \"schema:name\",\n    \"NumberOfLogLinesScanned\": {\n      \"@id\": \"amz:NumberOfLogLinesScanned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenProactiveInsights\": {\n      \"@id\": \"amz:OpenProactiveInsights\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenReactiveInsights\": {\n      \"@id\": \"amz:OpenReactiveInsights\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OptInStatus\": {\n      \"@id\": \"amz:OptInStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"PredictionTimeRange\": {\n      \"@id\": \"amz:PredictionTimeRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reason\": {\n      \"@id\": \"amz:Reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelatedAnomalies\": {\n      \"@id\": \"amz:RelatedAnomalies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelatedEvents\": {\n      \"@id\": \"amz:RelatedEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Resources\": {\n      \"@id\": \"amz:Resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"amz:ServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceNames\": {\n      \"@id\": \"amz:ServiceNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Severity\": {\n      \"@id\": \"amz:Severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceDetails\": {\n      \"@id\": \"amz:SourceDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceMetadata\"\
  : {\n      \"@id\": \"amz:SourceMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SsmOpsItemId\": {\n      \"@id\": \"amz:SsmOpsItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StackName\": {\n      \"@id\": \"amz:StackName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StackNames\": {\n      \"@id\": \"amz:StackNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amz:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagValue\": {\n      \"@id\": \"amz:TagValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagValues\": {\n      \"@id\": \"amz:TagValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"amz:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Time\": {\n      \"@id\": \"amz:Time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TopicArn\": {\n      \"@id\": \"amz:TopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"amz:Type\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"UpdateTime\": {\n      \"@id\": \"amz:UpdateTime\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-devops-guru/refs/heads/main/json-ld/amazon-devops-guru-context.jsonld
tags:
- Anomaly Detection
- AWS
- DevOps
- Machine Learning
- Operational Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
