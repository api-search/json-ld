---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 51
classes:
- ActivityResponse
- ListJourneysResponse
- JourneysResponse
- GetJourneyExecutionActivityMetricsRequest
- JourneyLimits
- UpdateJourneyResponse
- JourneyResponse
- WaitTime
- EmailMessageActivity
- DeleteJourneyResponse
- JourneyStateRequest
- SimpleCondition
- EventCondition
- JourneyExecutionActivityMetricsResponse
- HoldoutActivity
- JourneyEmailMessage
- GetJourneyResponse
- DeleteJourneyRequest
- GetJourneyDateRangeKpiResponse
- JourneyDateRangeKpiResponse
- JourneyChannelSettings
- GetJourneyExecutionMetricsResponse
- JourneyExecutionMetricsResponse
- JourneySchedule
- JourneyPushMessage
- GetJourneyRequest
- Activity
- EventStartCondition
- MultiConditionalSplitActivity
- WriteJourneyRequest
- StartCondition
- WaitActivity
- UpdateJourneyStateRequest
- UpdateJourneyRequest
- ListJourneysRequest
- JourneyCustomMessage
- SMSMessageActivity
- CustomMessageActivity
- JourneySMSMessage
- UpdateJourneyStateResponse
- ConditionalSplitActivity
- Condition
- GetJourneyExecutionActivityMetricsResponse
- PushMessageActivity
- CreateJourneyRequest
- GetJourneyDateRangeKpiRequest
- RandomSplitActivity
- MultiConditionalBranch
- CreateJourneyResponse
- GetJourneyExecutionMetricsRequest
- ContactCenterActivity
context_file: json-ld/amazon-pinpoint-journeys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-journeys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Journeys from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Journeys Context
namespaces:
- prefix: pinpoint
  uri: https://pinpoint.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: CampaignId
  type: string
- container: ''
  name: End
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Result
  type: string
- container: ''
  name: ScheduledStart
  type: string
- container: ''
  name: Start
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: SuccessfulEndpointCount
  type: string
- container: ''
  name: TimezonesCompletedCount
  type: string
- container: ''
  name: TimezonesTotalCount
  type: string
- container: ''
  name: TotalEndpointCount
  type: string
- container: ''
  name: TreatmentId
  type: string
- container: ''
  name: DailyCap
  type: string
- container: ''
  name: EndpointReentryCap
  type: string
- container: ''
  name: MessagesPerSecond
  type: string
- container: ''
  name: EndpointReentryInterval
  type: string
- container: ''
  name: WaitFor
  type: string
- container: ''
  name: WaitUntil
  type: string
- container: ''
  name: MessageConfig
  type: string
- container: ''
  name: NextActivity
  type: string
- container: ''
  name: TemplateName
  type: string
- container: ''
  name: TemplateVersion
  type: string
- container: ''
  name: SegmentCondition
  type: string
- container: ''
  name: SegmentDimensions
  type: string
- container: ''
  name: ActivityType
  type: string
- container: ''
  name: JourneyActivityId
  type: string
- container: ''
  name: JourneyId
  type: string
- container: ''
  name: LastEvaluatedTime
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: Percentage
  type: string
- container: ''
  name: FromAddress
  type: string
- container: ''
  name: ConnectCampaignArn
  type: string
- container: ''
  name: ConnectCampaignExecutionRoleArn
  type: string
- container: ''
  name: Item
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: EndTime
  type: string
- container: ''
  name: KpiName
  type: string
- container: ''
  name: KpiResult
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: Timezone
  type: string
- container: ''
  name: TimeToLive
  type: string
- container: ''
  name: CUSTOM
  type: string
- container: ''
  name: ConditionalSplit
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: EMAIL
  type: string
- container: ''
  name: Holdout
  type: string
- container: ''
  name: MultiCondition
  type: string
- container: ''
  name: PUSH
  type: string
- container: ''
  name: RandomSplit
  type: string
- container: ''
  name: SMS
  type: string
- container: ''
  name: Wait
  type: string
- container: ''
  name: ContactCenter
  type: string
- container: ''
  name: EventFilter
  type: string
- container: ''
  name: SegmentId
  type: string
- container: ''
  name: Branches
  type: string
- container: ''
  name: DefaultActivity
  type: string
- container: ''
  name: EvaluationWaitTime
  type: string
- container: ''
  name: Activities
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: Limits
  type: string
- container: ''
  name: LocalTime
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: QuietTime
  type: string
- container: ''
  name: RefreshFrequency
  type: string
- container: ''
  name: Schedule
  type: string
- container: ''
  name: StartActivity
  type: string
- container: ''
  name: WaitForQuietTime
  type: string
- container: ''
  name: RefreshOnSegmentUpdate
  type: string
- container: ''
  name: SendingSchedule
  type: string
- container: ''
  name: OpenHours
  type: string
- container: ''
  name: ClosedDays
  type: string
- container: ''
  name: Data
  type: string
- container: ''
  name: Dimensions
  type: string
- container: ''
  name: MessageActivity
  type: string
- container: ''
  name: DeliveryUri
  type: string
- container: ''
  name: EndpointTypes
  type: string
- container: ''
  name: MessageType
  type: string
- container: ''
  name: OriginationNumber
  type: string
- container: ''
  name: SenderId
  type: string
- container: ''
  name: EntityId
  type: string
- container: ''
  name: TemplateId
  type: string
- container: ''
  name: FalseActivity
  type: string
- container: ''
  name: TrueActivity
  type: string
- container: ''
  name: Conditions
  type: string
- container: ''
  name: Operator
  type: string
- container: ''
  name: SegmentStartCondition
  type: string
- container: ''
  name: tags
  type: string
property_count: 89
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-journeys-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ActivityResponse\": \"pinpoint:ActivityResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignId\": {\n      \"@id\": \"pinpoint:CampaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"End\": {\n      \"@id\": \"pinpoint:End\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Result\": {\n      \"@id\": \"pinpoint:Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduledStart\": {\n      \"@id\": \"pinpoint:ScheduledStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Start\": {\n      \"@id\": \"pinpoint:Start\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"pinpoint:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SuccessfulEndpointCount\": {\n      \"@id\": \"pinpoint:SuccessfulEndpointCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimezonesCompletedCount\": {\n      \"@id\": \"pinpoint:TimezonesCompletedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimezonesTotalCount\": {\n      \"@id\": \"pinpoint:TimezonesTotalCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalEndpointCount\": {\n      \"@id\": \"pinpoint:TotalEndpointCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TreatmentId\": {\n      \"@id\": \"pinpoint:TreatmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListJourneysResponse\": \"pinpoint:ListJourneysResponse\",\n    \"JourneysResponse\": \"pinpoint:JourneysResponse\",\n    \"GetJourneyExecutionActivityMetricsRequest\": \"pinpoint:GetJourneyExecutionActivityMetricsRequest\",\n    \"JourneyLimits\": \"pinpoint:JourneyLimits\"\
  ,\n    \"DailyCap\": {\n      \"@id\": \"pinpoint:DailyCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointReentryCap\": {\n      \"@id\": \"pinpoint:EndpointReentryCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessagesPerSecond\": {\n      \"@id\": \"pinpoint:MessagesPerSecond\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointReentryInterval\": {\n      \"@id\": \"pinpoint:EndpointReentryInterval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateJourneyResponse\": \"pinpoint:UpdateJourneyResponse\",\n    \"JourneyResponse\": \"pinpoint:JourneyResponse\",\n    \"WaitTime\": \"pinpoint:WaitTime\",\n    \"WaitFor\": {\n      \"@id\": \"pinpoint:WaitFor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WaitUntil\": {\n      \"@id\": \"pinpoint:WaitUntil\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailMessageActivity\": \"pinpoint:EmailMessageActivity\",\n    \"MessageConfig\": {\n      \"@id\": \"pinpoint:MessageConfig\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"NextActivity\": {\n      \"@id\": \"pinpoint:NextActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"pinpoint:TemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateVersion\": {\n      \"@id\": \"pinpoint:TemplateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteJourneyResponse\": \"pinpoint:DeleteJourneyResponse\",\n    \"JourneyStateRequest\": \"pinpoint:JourneyStateRequest\",\n    \"SimpleCondition\": \"pinpoint:SimpleCondition\",\n    \"EventCondition\": \"pinpoint:EventCondition\",\n    \"SegmentCondition\": {\n      \"@id\": \"pinpoint:SegmentCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentDimensions\": {\n      \"@id\": \"pinpoint:SegmentDimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneyExecutionActivityMetricsResponse\": \"pinpoint:JourneyExecutionActivityMetricsResponse\",\n    \"ActivityType\": {\n      \"@id\": \"pinpoint:ActivityType\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"JourneyActivityId\": {\n      \"@id\": \"pinpoint:JourneyActivityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneyId\": {\n      \"@id\": \"pinpoint:JourneyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastEvaluatedTime\": {\n      \"@id\": \"pinpoint:LastEvaluatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"pinpoint:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HoldoutActivity\": \"pinpoint:HoldoutActivity\",\n    \"Percentage\": {\n      \"@id\": \"pinpoint:Percentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneyEmailMessage\": \"pinpoint:JourneyEmailMessage\",\n    \"FromAddress\": {\n      \"@id\": \"pinpoint:FromAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJourneyResponse\": \"pinpoint:GetJourneyResponse\",\n    \"DeleteJourneyRequest\": \"pinpoint:DeleteJourneyRequest\",\n    \"GetJourneyDateRangeKpiResponse\": \"pinpoint:GetJourneyDateRangeKpiResponse\"\
  ,\n    \"JourneyDateRangeKpiResponse\": \"pinpoint:JourneyDateRangeKpiResponse\",\n    \"JourneyChannelSettings\": \"pinpoint:JourneyChannelSettings\",\n    \"ConnectCampaignArn\": {\n      \"@id\": \"pinpoint:ConnectCampaignArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectCampaignExecutionRoleArn\": {\n      \"@id\": \"pinpoint:ConnectCampaignExecutionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pinpoint:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJourneyExecutionMetricsResponse\": \"pinpoint:GetJourneyExecutionMetricsResponse\",\n    \"JourneyExecutionMetricsResponse\": \"pinpoint:JourneyExecutionMetricsResponse\",\n    \"EndTime\": {\n      \"@id\": \"pinpoint:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KpiName\": {\n      \"@id\": \"pinpoint:KpiName\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"KpiResult\": {\n      \"@id\": \"pinpoint:KpiResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"pinpoint:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneySchedule\": \"pinpoint:JourneySchedule\",\n    \"Timezone\": {\n      \"@id\": \"pinpoint:Timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneyPushMessage\": \"pinpoint:JourneyPushMessage\",\n    \"TimeToLive\": {\n      \"@id\": \"pinpoint:TimeToLive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJourneyRequest\": \"pinpoint:GetJourneyRequest\",\n    \"Activity\": \"pinpoint:Activity\",\n    \"CUSTOM\": {\n      \"@id\": \"pinpoint:CUSTOM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionalSplit\": {\n      \"@id\": \"pinpoint:ConditionalSplit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"pinpoint:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EMAIL\": {\n      \"@id\": \"pinpoint:EMAIL\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Holdout\": {\n      \"@id\": \"pinpoint:Holdout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MultiCondition\": {\n      \"@id\": \"pinpoint:MultiCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PUSH\": {\n      \"@id\": \"pinpoint:PUSH\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RandomSplit\": {\n      \"@id\": \"pinpoint:RandomSplit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMS\": {\n      \"@id\": \"pinpoint:SMS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Wait\": {\n      \"@id\": \"pinpoint:Wait\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ContactCenter\": {\n      \"@id\": \"pinpoint:ContactCenter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventStartCondition\": \"pinpoint:EventStartCondition\",\n    \"EventFilter\": {\n      \"@id\": \"pinpoint:EventFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentId\": {\n      \"@id\": \"pinpoint:SegmentId\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"MultiConditionalSplitActivity\": \"pinpoint:MultiConditionalSplitActivity\",\n    \"Branches\": {\n      \"@id\": \"pinpoint:Branches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultActivity\": {\n      \"@id\": \"pinpoint:DefaultActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EvaluationWaitTime\": {\n      \"@id\": \"pinpoint:EvaluationWaitTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WriteJourneyRequest\": \"pinpoint:WriteJourneyRequest\",\n    \"Activities\": {\n      \"@id\": \"pinpoint:Activities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limits\": {\n      \"@id\": \"pinpoint:Limits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LocalTime\": {\n      \"@id\": \"pinpoint:LocalTime\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuietTime\": {\n      \"@id\": \"pinpoint:QuietTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RefreshFrequency\": {\n      \"@id\": \"pinpoint:RefreshFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schedule\": {\n      \"@id\": \"pinpoint:Schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartActivity\": {\n      \"@id\": \"pinpoint:StartActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartCondition\": \"pinpoint:StartCondition\",\n    \"WaitForQuietTime\": {\n      \"@id\": \"pinpoint:WaitForQuietTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RefreshOnSegmentUpdate\": {\n      \"@id\": \"pinpoint:RefreshOnSegmentUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SendingSchedule\": {\n      \"@id\": \"pinpoint:SendingSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenHours\"\
  : {\n      \"@id\": \"pinpoint:OpenHours\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClosedDays\": {\n      \"@id\": \"pinpoint:ClosedDays\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WaitActivity\": \"pinpoint:WaitActivity\",\n    \"UpdateJourneyStateRequest\": \"pinpoint:UpdateJourneyStateRequest\",\n    \"UpdateJourneyRequest\": \"pinpoint:UpdateJourneyRequest\",\n    \"ListJourneysRequest\": \"pinpoint:ListJourneysRequest\",\n    \"JourneyCustomMessage\": \"pinpoint:JourneyCustomMessage\",\n    \"Data\": {\n      \"@id\": \"pinpoint:Data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dimensions\": {\n      \"@id\": \"pinpoint:Dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageActivity\": {\n      \"@id\": \"pinpoint:MessageActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMSMessageActivity\": \"pinpoint:SMSMessageActivity\",\n    \"CustomMessageActivity\": \"pinpoint:CustomMessageActivity\",\n    \"DeliveryUri\": {\n      \"@id\": \"pinpoint:DeliveryUri\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointTypes\": {\n      \"@id\": \"pinpoint:EndpointTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JourneySMSMessage\": \"pinpoint:JourneySMSMessage\",\n    \"MessageType\": {\n      \"@id\": \"pinpoint:MessageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginationNumber\": {\n      \"@id\": \"pinpoint:OriginationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SenderId\": {\n      \"@id\": \"pinpoint:SenderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityId\": {\n      \"@id\": \"pinpoint:EntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateId\": {\n      \"@id\": \"pinpoint:TemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateJourneyStateResponse\": \"pinpoint:UpdateJourneyStateResponse\",\n    \"ConditionalSplitActivity\": \"pinpoint:ConditionalSplitActivity\",\n    \"Condition\": \"pinpoint:Condition\",\n    \"FalseActivity\": {\n      \"@id\": \"pinpoint:FalseActivity\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"TrueActivity\": {\n      \"@id\": \"pinpoint:TrueActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJourneyExecutionActivityMetricsResponse\": \"pinpoint:GetJourneyExecutionActivityMetricsResponse\",\n    \"Conditions\": {\n      \"@id\": \"pinpoint:Conditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Operator\": {\n      \"@id\": \"pinpoint:Operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentStartCondition\": {\n      \"@id\": \"pinpoint:SegmentStartCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PushMessageActivity\": \"pinpoint:PushMessageActivity\",\n    \"CreateJourneyRequest\": \"pinpoint:CreateJourneyRequest\",\n    \"GetJourneyDateRangeKpiRequest\": \"pinpoint:GetJourneyDateRangeKpiRequest\",\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RandomSplitActivity\": \"pinpoint:RandomSplitActivity\",\n    \"MultiConditionalBranch\": \"\
  pinpoint:MultiConditionalBranch\",\n    \"CreateJourneyResponse\": \"pinpoint:CreateJourneyResponse\",\n    \"GetJourneyExecutionMetricsRequest\": \"pinpoint:GetJourneyExecutionMetricsRequest\",\n    \"ContactCenterActivity\": \"pinpoint:ContactCenterActivity\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-journeys-context.jsonld
tags:
- AWS
- Campaigns
- Communications
- Email
- Marketing
- Messaging
- Push Notifications
- SMS
- Voice
- Customer Engagement
- Segmentation
- Journeys
- Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
