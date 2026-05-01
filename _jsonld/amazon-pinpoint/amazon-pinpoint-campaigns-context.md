---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 34
classes:
- TreatmentResource
- GetCampaignResponse
- CampaignResponse
- UpdateCampaignResponse
- CampaignDateRangeKpiResponse
- CampaignHook
- GetCampaignVersionRequest
- CampaignState
- GetCampaignsResponse
- CampaignsResponse
- CreateCampaignRequest
- WriteCampaignRequest
- DeleteCampaignResponse
- GetCampaignActivitiesResponse
- CampaignCustomMessage
- GetCampaignsRequest
- CampaignInAppMessage
- CampaignEmailMessage
- InAppCampaignSchedule
- GetCampaignDateRangeKpiRequest
- CreateCampaignResponse
- GetCampaignVersionsRequest
- InAppMessageCampaign
- CampaignEventFilter
- GetCampaignVersionsResponse
- GetCampaignVersionResponse
- CampaignSmsMessage
- GetCampaignDateRangeKpiResponse
- GetCampaignRequest
- DeleteCampaignRequest
- GetCampaignActivitiesRequest
- CampaignLimits
- UpdateCampaignRequest
- WriteTreatmentResource
context_file: json-ld/amazon-pinpoint-campaigns-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-campaigns-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Campaigns from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Campaigns Context
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
  name: CustomDeliveryConfiguration
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: MessageConfiguration
  type: string
- container: ''
  name: Schedule
  type: string
- container: ''
  name: SizePercent
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: TemplateConfiguration
  type: string
- container: ''
  name: TreatmentDescription
  type: string
- container: ''
  name: TreatmentName
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: CampaignId
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
  name: NextToken
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: LambdaFunctionName
  type: string
- container: ''
  name: Mode
  type: string
- container: ''
  name: WebUrl
  type: string
- container: ''
  name: CampaignStatus
  type: string
- container: ''
  name: ActivitiesResponse
  type: string
- container: ''
  name: Data
  type: string
- container: ''
  name: AdditionalTreatments
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: HoldoutPercent
  type: string
- container: ''
  name: Hook
  type: string
- container: ''
  name: IsPaused
  type: string
- container: ''
  name: Limits
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: SegmentId
  type: string
- container: ''
  name: SegmentVersion
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: Priority
  type: string
- container: ''
  name: Body
  type: string
- container: ''
  name: Content
  type: string
- container: ''
  name: CustomConfig
  type: string
- container: ''
  name: Layout
  type: string
- container: ''
  name: FromAddress
  type: string
- container: ''
  name: HtmlBody
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: DefaultState
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: EndDate
  type: string
- container: ''
  name: EventFilter
  type: string
- container: ''
  name: QuietTime
  type: string
- container: ''
  name: DailyCap
  type: string
- container: ''
  name: InAppMessage
  type: string
- container: ''
  name: SessionCap
  type: string
- container: ''
  name: TotalCap
  type: string
- container: ''
  name: TreatmentId
  type: string
- container: ''
  name: Dimensions
  type: string
- container: ''
  name: FilterType
  type: string
- container: ''
  name: Item
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
  name: Daily
  type: string
- container: ''
  name: MaximumDuration
  type: string
- container: ''
  name: MessagesPerSecond
  type: string
- container: ''
  name: Total
  type: string
- container: ''
  name: Session
  type: string
property_count: 66
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-campaigns-context
source_filename: amazon-pinpoint-campaigns-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"TreatmentResource\": \"pinpoint:TreatmentResource\",\n    \"CustomDeliveryConfiguration\": {\n      \"@id\": \"pinpoint:CustomDeliveryConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageConfiguration\": {\n      \"@id\": \"pinpoint:MessageConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schedule\": {\n      \"@id\": \"pinpoint:Schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SizePercent\": {\n      \"@id\": \"pinpoint:SizePercent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"pinpoint:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateConfiguration\"\
  : {\n      \"@id\": \"pinpoint:TemplateConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TreatmentDescription\": {\n      \"@id\": \"pinpoint:TreatmentDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TreatmentName\": {\n      \"@id\": \"pinpoint:TreatmentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignResponse\": \"pinpoint:GetCampaignResponse\",\n    \"CampaignResponse\": \"pinpoint:CampaignResponse\",\n    \"UpdateCampaignResponse\": \"pinpoint:UpdateCampaignResponse\",\n    \"CampaignDateRangeKpiResponse\": \"pinpoint:CampaignDateRangeKpiResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignId\": {\n      \"@id\": \"pinpoint:CampaignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"pinpoint:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KpiName\": {\n      \"@id\": \"pinpoint:KpiName\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"KpiResult\": {\n      \"@id\": \"pinpoint:KpiResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pinpoint:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"pinpoint:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignHook\": \"pinpoint:CampaignHook\",\n    \"LambdaFunctionName\": {\n      \"@id\": \"pinpoint:LambdaFunctionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Mode\": {\n      \"@id\": \"pinpoint:Mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WebUrl\": {\n      \"@id\": \"pinpoint:WebUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignVersionRequest\": \"pinpoint:GetCampaignVersionRequest\",\n    \"CampaignState\": \"pinpoint:CampaignState\",\n    \"CampaignStatus\": {\n      \"@id\": \"pinpoint:CampaignStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignsResponse\": \"pinpoint:GetCampaignsResponse\",\n\
  \    \"CampaignsResponse\": \"pinpoint:CampaignsResponse\",\n    \"CreateCampaignRequest\": \"pinpoint:CreateCampaignRequest\",\n    \"WriteCampaignRequest\": \"pinpoint:WriteCampaignRequest\",\n    \"DeleteCampaignResponse\": \"pinpoint:DeleteCampaignResponse\",\n    \"GetCampaignActivitiesResponse\": \"pinpoint:GetCampaignActivitiesResponse\",\n    \"ActivitiesResponse\": {\n      \"@id\": \"pinpoint:ActivitiesResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignCustomMessage\": \"pinpoint:CampaignCustomMessage\",\n    \"Data\": {\n      \"@id\": \"pinpoint:Data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignsRequest\": \"pinpoint:GetCampaignsRequest\",\n    \"AdditionalTreatments\": {\n      \"@id\": \"pinpoint:AdditionalTreatments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"pinpoint:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HoldoutPercent\": {\n      \"@id\": \"pinpoint:HoldoutPercent\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Hook\": {\n      \"@id\": \"pinpoint:Hook\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsPaused\": {\n      \"@id\": \"pinpoint:IsPaused\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limits\": {\n      \"@id\": \"pinpoint:Limits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentId\": {\n      \"@id\": \"pinpoint:SegmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentVersion\": {\n      \"@id\": \"pinpoint:SegmentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Priority\": {\n      \"@id\": \"pinpoint:Priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignInAppMessage\": \"pinpoint:CampaignInAppMessage\",\n    \"Body\": {\n      \"@id\": \"pinpoint:Body\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  Content\": {\n      \"@id\": \"pinpoint:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomConfig\": {\n      \"@id\": \"pinpoint:CustomConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Layout\": {\n      \"@id\": \"pinpoint:Layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignEmailMessage\": \"pinpoint:CampaignEmailMessage\",\n    \"FromAddress\": {\n      \"@id\": \"pinpoint:FromAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HtmlBody\": {\n      \"@id\": \"pinpoint:HtmlBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"pinpoint:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultState\": {\n      \"@id\": \"pinpoint:DefaultState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\"\
  : {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"pinpoint:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InAppCampaignSchedule\": \"pinpoint:InAppCampaignSchedule\",\n    \"EndDate\": {\n      \"@id\": \"pinpoint:EndDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventFilter\": {\n      \"@id\": \"pinpoint:EventFilter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuietTime\": {\n      \"@id\": \"pinpoint:QuietTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignDateRangeKpiRequest\": \"pinpoint:GetCampaignDateRangeKpiRequest\",\n    \"CreateCampaignResponse\": \"pinpoint:CreateCampaignResponse\",\n    \"GetCampaignVersionsRequest\": \"pinpoint:GetCampaignVersionsRequest\",\n    \"InAppMessageCampaign\": \"pinpoint:InAppMessageCampaign\",\n    \"DailyCap\": {\n      \"@id\": \"pinpoint:DailyCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InAppMessage\": {\n    \
  \  \"@id\": \"pinpoint:InAppMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SessionCap\": {\n      \"@id\": \"pinpoint:SessionCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalCap\": {\n      \"@id\": \"pinpoint:TotalCap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TreatmentId\": {\n      \"@id\": \"pinpoint:TreatmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CampaignEventFilter\": \"pinpoint:CampaignEventFilter\",\n    \"Dimensions\": {\n      \"@id\": \"pinpoint:Dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterType\": {\n      \"@id\": \"pinpoint:FilterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignVersionsResponse\": \"pinpoint:GetCampaignVersionsResponse\",\n    \"GetCampaignVersionResponse\": \"pinpoint:GetCampaignVersionResponse\",\n    \"CampaignSmsMessage\": \"pinpoint:CampaignSmsMessage\",\n    \"MessageType\"\
  : {\n      \"@id\": \"pinpoint:MessageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginationNumber\": {\n      \"@id\": \"pinpoint:OriginationNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SenderId\": {\n      \"@id\": \"pinpoint:SenderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityId\": {\n      \"@id\": \"pinpoint:EntityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateId\": {\n      \"@id\": \"pinpoint:TemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetCampaignDateRangeKpiResponse\": \"pinpoint:GetCampaignDateRangeKpiResponse\",\n    \"GetCampaignRequest\": \"pinpoint:GetCampaignRequest\",\n    \"DeleteCampaignRequest\": \"pinpoint:DeleteCampaignRequest\",\n    \"GetCampaignActivitiesRequest\": \"pinpoint:GetCampaignActivitiesRequest\",\n    \"CampaignLimits\": \"pinpoint:CampaignLimits\",\n    \"Daily\": {\n      \"@id\": \"pinpoint:Daily\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumDuration\": {\n      \"\
  @id\": \"pinpoint:MaximumDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessagesPerSecond\": {\n      \"@id\": \"pinpoint:MessagesPerSecond\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Total\": {\n      \"@id\": \"pinpoint:Total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Session\": {\n      \"@id\": \"pinpoint:Session\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateCampaignRequest\": \"pinpoint:UpdateCampaignRequest\",\n    \"WriteTreatmentResource\": \"pinpoint:WriteTreatmentResource\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-campaigns-context.jsonld
tags:
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
