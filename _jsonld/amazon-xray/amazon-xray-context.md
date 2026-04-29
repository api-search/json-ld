---
class_count: 108
classes:
- BatchGetTracesResult
- CreateGroupResult
- Group
- Tag
- CreateSamplingRuleResult
- SamplingRuleRecord
- AttributeMap
- DeleteGroupResult
- DeleteResourcePolicyResult
- DeleteSamplingRuleResult
- GetEncryptionConfigResult
- EncryptionConfig
- GetGroupResult
- GetGroupsResult
- GetInsightResult
- Insight
- GetInsightEventsResult
- GetInsightImpactGraphResult
- GetInsightSummariesResult
- GetSamplingRulesResult
- GetSamplingStatisticSummariesResult
- GetSamplingTargetsResult
- UnprocessedStatistics
- SamplingStatisticsDocument
- GetServiceGraphResult
- GetTimeSeriesServiceStatisticsResult
- TimeSeriesServiceStatistics
- GetTraceGraphResult
- GetTraceSummariesResult
- ListResourcePoliciesResult
- ListTagsForResourceResponse
- PutEncryptionConfigResult
- PutResourcePolicyResult
- ResourcePolicy
- PutTelemetryRecordsResult
- TelemetryRecord
- BackendConnectionErrors
- PutTraceSegmentsResult
- TagResourceResponse
- UntagResourceResponse
- UpdateGroupResult
- UpdateSamplingRuleResult
- Alias
- AnomalousService
- AvailabilityZoneDetail
- BatchGetTracesRequest
- CreateGroupRequest
- CreateSamplingRuleRequest
- DeleteGroupRequest
- DeleteResourcePolicyRequest
- DeleteSamplingRuleRequest
- EdgeStatistics
- ErrorStatistics
- FaultStatistics
- Edge
- ErrorRootCause
- ErrorRootCauseEntity
- ErrorRootCauseService
- FaultRootCause
- FaultRootCauseEntity
- FaultRootCauseService
- GetEncryptionConfigRequest
- GetGroupRequest
- GetGroupsRequest
- GetInsightEventsRequest
- GetInsightImpactGraphRequest
- GetInsightRequest
- GetInsightSummariesRequest
- GetSamplingRulesRequest
- GetSamplingStatisticSummariesRequest
- GetSamplingTargetsRequest
- GetServiceGraphRequest
- GetTimeSeriesServiceStatisticsRequest
- GetTraceGraphRequest
- GetTraceSummariesRequest
- GroupSummary
- HistogramEntry
- RequestImpactStatistics
- InsightEvent
- InsightImpactGraphEdge
- InsightImpactGraphService
- InsightSummary
- InstanceIdDetail
- ListResourcePoliciesRequest
- ListTagsForResourceRequest
- PutEncryptionConfigRequest
- PutResourcePolicyRequest
- PutTelemetryRecordsRequest
- PutTraceSegmentsRequest
- ResourceARNDetail
- ResponseTimeRootCause
- ResponseTimeRootCauseEntity
- ResponseTimeRootCauseService
- RootCauseException
- SamplingStatisticSummary
- SamplingTargetDocument
- Segment
- ServiceStatistics
- Service
- TagResourceRequest
- Trace
- TraceSummary
- TraceUser
- UnprocessedTraceSegment
- UntagResourceRequest
- UpdateGroupRequest
- UpdateSamplingRuleRequest
- ValueWithServiceIds
context_file: json-ld/amazon-xray-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-xray/refs/heads/main/json-ld/amazon-xray-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Xray from Amazon X-Ray.
layout: jsonld
name: Amazon Xray Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Traces
  type: string
- container: ''
  name: UnprocessedTraceIds
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Groups
  type: string
- container: ''
  name: InsightEvents
  type: string
- container: ''
  name: InsightId
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: EndTime
  type: string
- container: ''
  name: ServiceGraphStartTime
  type: string
- container: ''
  name: ServiceGraphEndTime
  type: string
- container: ''
  name: Services
  type: string
- container: ''
  name: InsightSummaries
  type: string
- container: ''
  name: SamplingRuleRecords
  type: string
- container: ''
  name: SamplingStatisticSummaries
  type: string
- container: ''
  name: SamplingTargetDocuments
  type: string
- container: ''
  name: LastRuleModification
  type: string
- container: ''
  name: RuleName
  type: string
- container: ''
  name: ClientID
  type: string
- container: ''
  name: Timestamp
  type: string
- container: ''
  name: RequestCount
  type: string
- container: ''
  name: SampledCount
  type: string
- container: ''
  name: BorrowCount
  type: string
- container: ''
  name: ContainsOldGroupVersions
  type: string
- container: ''
  name: TraceSummaries
  type: string
- container: ''
  name: ApproximateTime
  type: string
- container: ''
  name: TracesProcessedCount
  type: string
- container: ''
  name: ResourcePolicies
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: SegmentsReceivedCount
  type: string
- container: ''
  name: SegmentsSentCount
  type: string
- container: ''
  name: SegmentsSpilloverCount
  type: string
- container: ''
  name: SegmentsRejectedCount
  type: string
- container: ''
  name: UnprocessedTraceSegments
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Names
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: AnnotationValue
  type: string
- container: ''
  name: NumberValue
  type: string
- container: ''
  name: BooleanValue
  type: string
- container: ''
  name: StringValue
  type: string
- container: ''
  name: Annotations
  type: string
- container: ''
  name: ServiceId
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: TimeoutCount
  type: string
- container: ''
  name: ConnectionRefusedCount
  type: string
- container: ''
  name: HTTPCode4XXCount
  type: string
- container: ''
  name: HTTPCode5XXCount
  type: string
- container: ''
  name: UnknownHostCount
  type: string
- container: ''
  name: OtherCount
  type: string
- container: ''
  name: TraceIds
  type: string
- container: ''
  name: InsightsConfiguration
  type: string
- container: ''
  name: InsightsEnabled
  type: string
- container: ''
  name: NotificationsEnabled
  type: string
- container: ''
  name: GroupName
  type: string
- container: ''
  name: FilterExpression
  type: string
- container: ''
  name: GroupARN
  type: string
- container: ''
  name: SamplingRule
  type: string
- container: ''
  name: RuleARN
  type: string
- container: ''
  name: ResourceARN
  type: string
- container: ''
  name: Priority
  type: string
- container: ''
  name: FixedRate
  type: string
- container: ''
  name: ReservoirSize
  type: string
- container: ''
  name: ServiceName
  type: string
- container: ''
  name: ServiceType
  type: string
- container: ''
  name: Host
  type: string
- container: ''
  name: HTTPMethod
  type: string
- container: ''
  name: URLPath
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: CreatedAt
  type: string
- container: ''
  name: ModifiedAt
  type: string
- container: ''
  name: PolicyName
  type: string
- container: ''
  name: PolicyRevisionId
  type: string
- container: ''
  name: OkCount
  type: string
- container: ''
  name: TotalCount
  type: string
- container: ''
  name: TotalResponseTime
  type: string
- container: ''
  name: ReferenceId
  type: string
- container: ''
  name: SummaryStatistics
  type: string
- container: ''
  name: ResponseTimeHistogram
  type: string
- container: ''
  name: Aliases
  type: string
- container: ''
  name: EdgeType
  type: string
- container: ''
  name: ReceivedEventAgeHistogram
  type: string
- container: ''
  name: ThrottleCount
  type: string
- container: ''
  name: KeyId
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: ClientImpacting
  type: string
- container: ''
  name: Exceptions
  type: string
- container: ''
  name: Remote
  type: string
- container: ''
  name: EntityPath
  type: string
- container: ''
  name: Inferred
  type: string
- container: ''
  name: ForecastStatistics
  type: string
- container: ''
  name: FaultCountHigh
  type: string
- container: ''
  name: FaultCountLow
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: RootCauseServiceId
  type: string
- container: ''
  name: Categories
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: Summary
  type: string
- container: ''
  name: ClientRequestImpactStatistics
  type: string
- container: ''
  name: RootCauseServiceRequestImpactStatistics
  type: string
- container: ''
  name: TopAnomalousServices
  type: string
- container: ''
  name: States
  type: string
- container: ''
  name: SamplingStatisticsDocuments
  type: string
- container: ''
  name: EntitySelectorExpression
  type: string
- container: ''
  name: Period
  type: string
- container: ''
  name: SamplingStrategy
  type: string
- container: ''
  name: TimeRangeType
  type: string
- container: ''
  name: Sampling
  type: string
- container: ''
  name: Count
  type: string
- container: ''
  name: Http
  type: string
- container: ''
  name: HttpURL
  type: string
- container: ''
  name: HttpStatus
  type: string
- container: ''
  name: HttpMethod
  type: string
- container: ''
  name: UserAgent
  type: string
- container: ''
  name: ClientIp
  type: string
- container: ''
  name: FaultCount
  type: string
- container: ''
  name: EventTime
  type: string
- container: ''
  name: Edges
  type: string
- container: ''
  name: LastUpdateTime
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: PolicyDocument
  type: string
- container: ''
  name: BypassPolicyLockoutCheck
  type: string
- container: ''
  name: LastUpdatedTime
  type: string
- container: ''
  name: TelemetryRecords
  type: string
- container: ''
  name: EC2InstanceId
  type: string
- container: ''
  name: Hostname
  type: string
- container: ''
  name: TraceSegmentDocuments
  type: string
- container: ''
  name: ARN
  type: string
- container: ''
  name: Coverage
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: SamplingRuleUpdate
  type: string
- container: ''
  name: ReservoirQuota
  type: string
- container: ''
  name: ReservoirQuotaTTL
  type: string
- container: ''
  name: Interval
  type: string
- container: ''
  name: Document
  type: string
- container: ''
  name: Root
  type: string
- container: ''
  name: DurationHistogram
  type: string
- container: ''
  name: EdgeSummaryStatistics
  type: string
- container: ''
  name: ServiceSummaryStatistics
  type: string
- container: ''
  name: ServiceForecastStatistics
  type: string
- container: ''
  name: Duration
  type: string
- container: ''
  name: LimitExceeded
  type: string
- container: ''
  name: Segments
  type: string
- container: ''
  name: ResponseTime
  type: string
- container: ''
  name: HasFault
  type: string
- container: ''
  name: HasError
  type: string
- container: ''
  name: HasThrottle
  type: string
- container: ''
  name: IsPartial
  type: string
- container: ''
  name: Users
  type: string
- container: ''
  name: ServiceIds
  type: string
- container: ''
  name: ResourceARNs
  type: string
- container: ''
  name: InstanceIds
  type: string
- container: ''
  name: AvailabilityZones
  type: string
- container: ''
  name: EntryPoint
  type: string
- container: ''
  name: FaultRootCauses
  type: string
- container: ''
  name: ErrorRootCauses
  type: string
- container: ''
  name: ResponseTimeRootCauses
  type: string
- container: ''
  name: Revision
  type: string
- container: ''
  name: MatchedEventTime
  type: string
- container: ''
  name: UserName
  type: string
- container: ''
  name: ErrorCode
  type: string
- container: ''
  name: TagKeys
  type: string
property_count: 164
provider_name: Amazon X-Ray
provider_slug: amazon-xray
slug: amazon-xray-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchGetTracesResult\": \"amz:BatchGetTracesResult\",\n    \"Traces\": {\n      \"@id\": \"amz:Traces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnprocessedTraceIds\": {\n      \"@id\": \"amz:UnprocessedTraceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amz:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateGroupResult\": \"amz:CreateGroupResult\",\n    \"Group\": \"amz:Group\",\n    \"Tag\": \"amz:Tag\",\n    \"Key\": {\n      \"@id\": \"amz:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amz:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSamplingRuleResult\": \"amz:CreateSamplingRuleResult\",\n    \"SamplingRuleRecord\"\
  : \"amz:SamplingRuleRecord\",\n    \"AttributeMap\": \"amz:AttributeMap\",\n    \"DeleteGroupResult\": \"amz:DeleteGroupResult\",\n    \"DeleteResourcePolicyResult\": \"amz:DeleteResourcePolicyResult\",\n    \"DeleteSamplingRuleResult\": \"amz:DeleteSamplingRuleResult\",\n    \"GetEncryptionConfigResult\": \"amz:GetEncryptionConfigResult\",\n    \"EncryptionConfig\": \"amz:EncryptionConfig\",\n    \"GetGroupResult\": \"amz:GetGroupResult\",\n    \"GetGroupsResult\": \"amz:GetGroupsResult\",\n    \"Groups\": {\n      \"@id\": \"amz:Groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetInsightResult\": \"amz:GetInsightResult\",\n    \"Insight\": \"amz:Insight\",\n    \"GetInsightEventsResult\": \"amz:GetInsightEventsResult\",\n    \"InsightEvents\": {\n      \"@id\": \"amz:InsightEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetInsightImpactGraphResult\": \"amz:GetInsightImpactGraphResult\",\n    \"InsightId\": {\n      \"@id\": \"amz:InsightId\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"amz:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"amz:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceGraphStartTime\": {\n      \"@id\": \"amz:ServiceGraphStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceGraphEndTime\": {\n      \"@id\": \"amz:ServiceGraphEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Services\": {\n      \"@id\": \"amz:Services\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetInsightSummariesResult\": \"amz:GetInsightSummariesResult\",\n    \"InsightSummaries\": {\n      \"@id\": \"amz:InsightSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSamplingRulesResult\": \"amz:GetSamplingRulesResult\",\n    \"SamplingRuleRecords\": {\n      \"@id\": \"amz:SamplingRuleRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSamplingStatisticSummariesResult\": \"amz:GetSamplingStatisticSummariesResult\"\
  ,\n    \"SamplingStatisticSummaries\": {\n      \"@id\": \"amz:SamplingStatisticSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSamplingTargetsResult\": \"amz:GetSamplingTargetsResult\",\n    \"SamplingTargetDocuments\": {\n      \"@id\": \"amz:SamplingTargetDocuments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastRuleModification\": {\n      \"@id\": \"amz:LastRuleModification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnprocessedStatistics\": \"amz:UnprocessedStatistics\",\n    \"SamplingStatisticsDocument\": \"amz:SamplingStatisticsDocument\",\n    \"RuleName\": {\n      \"@id\": \"amz:RuleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientID\": {\n      \"@id\": \"amz:ClientID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"amz:Timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestCount\": {\n      \"@id\": \"amz:RequestCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SampledCount\"\
  : {\n      \"@id\": \"amz:SampledCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BorrowCount\": {\n      \"@id\": \"amz:BorrowCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetServiceGraphResult\": \"amz:GetServiceGraphResult\",\n    \"ContainsOldGroupVersions\": {\n      \"@id\": \"amz:ContainsOldGroupVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetTimeSeriesServiceStatisticsResult\": \"amz:GetTimeSeriesServiceStatisticsResult\",\n    \"TimeSeriesServiceStatistics\": \"amz:TimeSeriesServiceStatistics\",\n    \"GetTraceGraphResult\": \"amz:GetTraceGraphResult\",\n    \"GetTraceSummariesResult\": \"amz:GetTraceSummariesResult\",\n    \"TraceSummaries\": {\n      \"@id\": \"amz:TraceSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApproximateTime\": {\n      \"@id\": \"amz:ApproximateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TracesProcessedCount\": {\n      \"@id\": \"amz:TracesProcessedCount\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"ListResourcePoliciesResult\": \"amz:ListResourcePoliciesResult\",\n    \"ResourcePolicies\": {\n      \"@id\": \"amz:ResourcePolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceResponse\": \"amz:ListTagsForResourceResponse\",\n    \"Tags\": {\n      \"@id\": \"amz:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutEncryptionConfigResult\": \"amz:PutEncryptionConfigResult\",\n    \"PutResourcePolicyResult\": \"amz:PutResourcePolicyResult\",\n    \"ResourcePolicy\": \"amz:ResourcePolicy\",\n    \"PutTelemetryRecordsResult\": \"amz:PutTelemetryRecordsResult\",\n    \"TelemetryRecord\": \"amz:TelemetryRecord\",\n    \"SegmentsReceivedCount\": {\n      \"@id\": \"amz:SegmentsReceivedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentsSentCount\": {\n      \"@id\": \"amz:SegmentsSentCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentsSpilloverCount\": {\n      \"@id\": \"amz:SegmentsSpilloverCount\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"SegmentsRejectedCount\": {\n      \"@id\": \"amz:SegmentsRejectedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BackendConnectionErrors\": \"amz:BackendConnectionErrors\",\n    \"PutTraceSegmentsResult\": \"amz:PutTraceSegmentsResult\",\n    \"UnprocessedTraceSegments\": {\n      \"@id\": \"amz:UnprocessedTraceSegments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceResponse\": \"amz:TagResourceResponse\",\n    \"UntagResourceResponse\": \"amz:UntagResourceResponse\",\n    \"UpdateGroupResult\": \"amz:UpdateGroupResult\",\n    \"UpdateSamplingRuleResult\": \"amz:UpdateSamplingRuleResult\",\n    \"Alias\": \"amz:Alias\",\n    \"Name\": {\n      \"@id\": \"amz:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Names\": {\n      \"@id\": \"amz:Names\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"amz:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnnotationValue\": {\n      \"@id\": \"amz:AnnotationValue\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberValue\": {\n      \"@id\": \"amz:NumberValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BooleanValue\": {\n      \"@id\": \"amz:BooleanValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StringValue\": {\n      \"@id\": \"amz:StringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Annotations\": {\n      \"@id\": \"amz:Annotations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceId\": {\n      \"@id\": \"amz:ServiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"amz:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnomalousService\": \"amz:AnomalousService\",\n    \"AvailabilityZoneDetail\": \"amz:AvailabilityZoneDetail\",\n    \"TimeoutCount\": {\n      \"@id\": \"amz:TimeoutCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionRefusedCount\": {\n      \"@id\": \"amz:ConnectionRefusedCount\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"HTTPCode4XXCount\": {\n      \"@id\": \"amz:HTTPCode4XXCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HTTPCode5XXCount\": {\n      \"@id\": \"amz:HTTPCode5XXCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnknownHostCount\": {\n      \"@id\": \"amz:UnknownHostCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OtherCount\": {\n      \"@id\": \"amz:OtherCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchGetTracesRequest\": \"amz:BatchGetTracesRequest\",\n    \"TraceIds\": {\n      \"@id\": \"amz:TraceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightsConfiguration\": {\n      \"@id\": \"amz:InsightsConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightsEnabled\": {\n      \"@id\": \"amz:InsightsEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotificationsEnabled\": {\n      \"@id\": \"amz:NotificationsEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateGroupRequest\": \"amz:CreateGroupRequest\"\
  ,\n    \"GroupName\": {\n      \"@id\": \"amz:GroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterExpression\": {\n      \"@id\": \"amz:FilterExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupARN\": {\n      \"@id\": \"amz:GroupARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SamplingRule\": {\n      \"@id\": \"amz:SamplingRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleARN\": {\n      \"@id\": \"amz:RuleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceARN\": {\n      \"@id\": \"amz:ResourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Priority\": {\n      \"@id\": \"amz:Priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FixedRate\": {\n      \"@id\": \"amz:FixedRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReservoirSize\": {\n      \"@id\": \"amz:ReservoirSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"amz:ServiceName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ServiceType\": {\n      \"@id\": \"amz:ServiceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Host\": {\n      \"@id\": \"amz:Host\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HTTPMethod\": {\n      \"@id\": \"amz:HTTPMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"URLPath\": {\n      \"@id\": \"amz:URLPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"amz:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attributes\": {\n      \"@id\": \"amz:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSamplingRuleRequest\": \"amz:CreateSamplingRuleRequest\",\n    \"CreatedAt\": {\n      \"@id\": \"amz:CreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModifiedAt\": {\n      \"@id\": \"amz:ModifiedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteGroupRequest\": \"amz:DeleteGroupRequest\",\n    \"DeleteResourcePolicyRequest\": \"amz:DeleteResourcePolicyRequest\",\n    \"PolicyName\"\
  : {\n      \"@id\": \"amz:PolicyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyRevisionId\": {\n      \"@id\": \"amz:PolicyRevisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteSamplingRuleRequest\": \"amz:DeleteSamplingRuleRequest\",\n    \"EdgeStatistics\": \"amz:EdgeStatistics\",\n    \"OkCount\": {\n      \"@id\": \"amz:OkCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorStatistics\": \"amz:ErrorStatistics\",\n    \"FaultStatistics\": \"amz:FaultStatistics\",\n    \"TotalCount\": {\n      \"@id\": \"amz:TotalCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalResponseTime\": {\n      \"@id\": \"amz:TotalResponseTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Edge\": \"amz:Edge\",\n    \"ReferenceId\": {\n      \"@id\": \"amz:ReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SummaryStatistics\": {\n      \"@id\": \"amz:SummaryStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResponseTimeHistogram\":\
  \ {\n      \"@id\": \"amz:ResponseTimeHistogram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Aliases\": {\n      \"@id\": \"amz:Aliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EdgeType\": {\n      \"@id\": \"amz:EdgeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReceivedEventAgeHistogram\": {\n      \"@id\": \"amz:ReceivedEventAgeHistogram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThrottleCount\": {\n      \"@id\": \"amz:ThrottleCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyId\": {\n      \"@id\": \"amz:KeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amz:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorRootCause\": \"amz:ErrorRootCause\",\n    \"ClientImpacting\": {\n      \"@id\": \"amz:ClientImpacting\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorRootCauseEntity\": \"amz:ErrorRootCauseEntity\",\n    \"Exceptions\": {\n      \"@id\": \"amz:Exceptions\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"Remote\": {\n      \"@id\": \"amz:Remote\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorRootCauseService\": \"amz:ErrorRootCauseService\",\n    \"EntityPath\": {\n      \"@id\": \"amz:EntityPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Inferred\": {\n      \"@id\": \"amz:Inferred\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaultRootCause\": \"amz:FaultRootCause\",\n    \"FaultRootCauseEntity\": \"amz:FaultRootCauseEntity\",\n    \"FaultRootCauseService\": \"amz:FaultRootCauseService\",\n    \"ForecastStatistics\": {\n      \"@id\": \"amz:ForecastStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaultCountHigh\": {\n      \"@id\": \"amz:FaultCountHigh\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaultCountLow\": {\n      \"@id\": \"amz:FaultCountLow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEncryptionConfigRequest\": \"amz:GetEncryptionConfigRequest\",\n    \"GetGroupRequest\": \"amz:GetGroupRequest\",\n\
  \    \"GetGroupsRequest\": \"amz:GetGroupsRequest\",\n    \"GetInsightEventsRequest\": \"amz:GetInsightEventsRequest\",\n    \"MaxResults\": {\n      \"@id\": \"amz:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetInsightImpactGraphRequest\": \"amz:GetInsightImpactGraphRequest\",\n    \"GetInsightRequest\": \"amz:GetInsightRequest\",\n    \"RootCauseServiceId\": {\n      \"@id\": \"amz:RootCauseServiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Categories\": {\n      \"@id\": \"amz:Categories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"amz:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Summary\": {\n      \"@id\": \"amz:Summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientRequestImpactStatistics\": {\n      \"@id\": \"amz:ClientRequestImpactStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RootCauseServiceRequestImpactStatistics\": {\n      \"@id\": \"amz:RootCauseServiceRequestImpactStatistics\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"TopAnomalousServices\": {\n      \"@id\": \"amz:TopAnomalousServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetInsightSummariesRequest\": \"amz:GetInsightSummariesRequest\",\n    \"States\": {\n      \"@id\": \"amz:States\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSamplingRulesRequest\": \"amz:GetSamplingRulesRequest\",\n    \"GetSamplingStatisticSummariesRequest\": \"amz:GetSamplingStatisticSummariesRequest\",\n    \"GetSamplingTargetsRequest\": \"amz:GetSamplingTargetsRequest\",\n    \"SamplingStatisticsDocuments\": {\n      \"@id\": \"amz:SamplingStatisticsDocuments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetServiceGraphRequest\": \"amz:GetServiceGraphRequest\",\n    \"GetTimeSeriesServiceStatisticsRequest\": \"amz:GetTimeSeriesServiceStatisticsRequest\",\n    \"EntitySelectorExpression\": {\n      \"@id\": \"amz:EntitySelectorExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Period\": {\n\
  \      \"@id\": \"amz:Period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetTraceGraphRequest\": \"amz:GetTraceGraphRequest\",\n    \"SamplingStrategy\": {\n      \"@id\": \"amz:SamplingStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetTraceSummariesRequest\": \"amz:GetTraceSummariesRequest\",\n    \"TimeRangeType\": {\n      \"@id\": \"amz:TimeRangeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sampling\": {\n      \"@id\": \"amz:Sampling\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupSummary\": \"amz:GroupSummary\",\n    \"HistogramEntry\": \"amz:HistogramEntry\",\n    \"Count\": {\n      \"@id\": \"amz:Count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Http\": {\n      \"@id\": \"amz:Http\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HttpURL\": {\n      \"@id\": \"amz:HttpURL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HttpStatus\": {\n      \"@id\": \"amz:HttpStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HttpMethod\"\
  : {\n      \"@id\": \"amz:HttpMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserAgent\": {\n      \"@id\": \"amz:UserAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientIp\": {\n      \"@id\": \"amz:ClientIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestImpactStatistics\": \"amz:RequestImpactStatistics\",\n    \"FaultCount\": {\n      \"@id\": \"amz:FaultCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightEvent\": \"amz:InsightEvent\",\n    \"EventTime\": {\n      \"@id\": \"amz:EventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightImpactGraphEdge\": \"amz:InsightImpactGraphEdge\",\n    \"InsightImpactGraphService\": \"amz:InsightImpactGraphService\",\n    \"Edges\": {\n      \"@id\": \"amz:Edges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InsightSummary\": \"amz:InsightSummary\",\n    \"LastUpdateTime\": {\n      \"@id\": \"amz:LastUpdateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceIdDetail\": \"amz:InstanceIdDetail\"\
  ,\n    \"Id\": {\n      \"@id\": \"amz:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListResourcePoliciesRequest\": \"amz:ListResourcePoliciesRequest\",\n    \"ListTagsForResourceRequest\": \"amz:ListTagsForResourceRequest\",\n    \"PutEncryptionConfigRequest\": \"amz:PutEncryptionConfigRequest\",\n    \"PutResourcePolicyRequest\": \"amz:PutResourcePolicyRequest\",\n    \"PolicyDocument\": {\n      \"@id\": \"amz:PolicyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BypassPolicyLockoutCheck\": {\n      \"@id\": \"amz:BypassPolicyLockoutCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedTime\": {\n      \"@id\": \"amz:LastUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutTelemetryRecordsRequest\": \"amz:PutTelemetryRecordsRequest\",\n    \"TelemetryRecords\": {\n      \"@id\": \"amz:TelemetryRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EC2InstanceId\": {\n      \"@id\": \"amz:EC2InstanceId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Hostname\": {\n      \"@id\": \"amz:Hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutTraceSegmentsRequest\": \"amz:PutTraceSegmentsRequest\",\n    \"TraceSegmentDocuments\": {\n      \"@id\": \"amz:TraceSegmentDocuments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceARNDetail\": \"amz:ResourceARNDetail\",\n    \"ARN\": {\n      \"@id\": \"amz:ARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResponseTimeRootCause\": \"amz:ResponseTimeRootCause\",\n    \"ResponseTimeRootCauseEntity\": \"amz:ResponseTimeRootCauseEntity\",\n    \"Coverage\": {\n      \"@id\": \"amz:Coverage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResponseTimeRootCauseService\": \"amz:ResponseTimeRootCauseService\",\n    \"RootCauseException\": \"amz:RootCauseException\",\n    \"Message\": {\n      \"@id\": \"amz:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SamplingRuleUpdate\": {\n      \"@id\": \"amz:SamplingRuleUpdate\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"SamplingStatisticSummary\": \"amz:SamplingStatisticSummary\",\n    \"SamplingTargetDocument\": \"amz:SamplingTargetDocument\",\n    \"ReservoirQuota\": {\n      \"@id\": \"amz:ReservoirQuota\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReservoirQuotaTTL\": {\n      \"@id\": \"amz:ReservoirQuotaTTL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Interval\": {\n      \"@id\": \"amz:Interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Segment\": \"amz:Segment\",\n    \"Document\": {\n      \"@id\": \"amz:Document\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceStatistics\": \"amz:ServiceStatistics\",\n    \"Service\": \"amz:Service\",\n    \"Root\": {\n      \"@id\": \"amz:Root\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DurationHistogram\": {\n      \"@id\": \"amz:DurationHistogram\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceRequest\": \"amz:TagResourceRequest\",\n    \"EdgeSummaryStatistics\": {\n      \"@id\": \"amz:EdgeSummaryStatistics\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceSummaryStatistics\": {\n      \"@id\": \"amz:ServiceSummaryStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceForecastStatistics\": {\n      \"@id\": \"amz:ServiceForecastStatistics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Trace\": \"amz:Trace\",\n    \"Duration\": {\n      \"@id\": \"amz:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LimitExceeded\": {\n      \"@id\": \"amz:LimitExceeded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Segments\": {\n      \"@id\": \"amz:Segments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TraceSummary\": \"amz:TraceSummary\",\n    \"ResponseTime\": {\n      \"@id\": \"amz:ResponseTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HasFault\": {\n      \"@id\": \"amz:HasFault\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HasError\": {\n      \"@id\": \"amz:HasError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HasThrottle\": {\n   \
  \   \"@id\": \"amz:HasThrottle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsPartial\": {\n      \"@id\": \"amz:IsPartial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Users\": {\n      \"@id\": \"amz:Users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceIds\": {\n      \"@id\": \"amz:ServiceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceARNs\": {\n      \"@id\": \"amz:ResourceARNs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceIds\": {\n      \"@id\": \"amz:InstanceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZones\": {\n      \"@id\": \"amz:AvailabilityZones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntryPoint\": {\n      \"@id\": \"amz:EntryPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaultRootCauses\": {\n      \"@id\": \"amz:FaultRootCauses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorRootCauses\": {\n      \"@id\": \"amz:ErrorRootCauses\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"ResponseTimeRootCauses\": {\n      \"@id\": \"amz:ResponseTimeRootCauses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Revision\": {\n      \"@id\": \"amz:Revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MatchedEventTime\": {\n      \"@id\": \"amz:MatchedEventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TraceUser\": \"amz:TraceUser\",\n    \"UserName\": {\n      \"@id\": \"amz:UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"amz:ErrorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnprocessedTraceSegment\": \"amz:UnprocessedTraceSegment\",\n    \"UntagResourceRequest\": \"amz:UntagResourceRequest\",\n    \"TagKeys\": {\n      \"@id\": \"amz:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateGroupRequest\": \"amz:UpdateGroupRequest\",\n    \"UpdateSamplingRuleRequest\": \"amz:UpdateSamplingRuleRequest\",\n    \"ValueWithServiceIds\": \"amz:ValueWithServiceIds\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-xray/refs/heads/main/json-ld/amazon-xray-context.jsonld
tags:
- Application Performance
- AWS
- Debugging
- Distributed Tracing
- Monitoring
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
