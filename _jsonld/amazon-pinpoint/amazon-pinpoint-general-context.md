---
class_count: 39
classes:
- OpenHoursRule
- Session
- GPSCoordinates
- RandomSplitEntry
- UpdateRecommenderConfigurationRequest
- UpdateRecommenderConfiguration
- TagResourceRequest
- TagsModel
- NumberValidateRequest
- PhoneNumberValidateRequest
- EventsRequest
- OpenHours
- AttributesResource
- WriteEventStream
- GetRecommenderConfigurationsRequest
- Event
- QuietTime
- EventFilter
- DeleteEventStreamRequest
- EventsBatch
- RemoveAttributesRequest
- UpdateAttributesRequest
- CreateRecommenderConfiguration
- OverrideButtonConfiguration
- ClosedDays
- EventStream
- GetRecommenderConfigurationRequest
- CreateRecommenderConfigurationRequest
- DeleteRecommenderConfigurationRequest
- PutEventsRequest
- Amazon Pinpoint Application Definition
- ClosedDaysRule
- Schedule
- CustomDeliveryConfiguration
- GetEventStreamRequest
- DefaultButtonConfiguration
- PutEventStreamRequest
- ListTagsForResourceRequest
- UntagResourceRequest
context_file: json-ld/amazon-pinpoint-general-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-general-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint General from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint General Context
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
  name: StartTime
  type: string
- container: ''
  name: EndTime
  type: string
- container: ''
  name: Duration
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: StartTimestamp
  type: string
- container: ''
  name: StopTimestamp
  type: string
- container: ''
  name: Latitude
  type: string
- container: ''
  name: Longitude
  type: string
- container: ''
  name: NextActivity
  type: string
- container: ''
  name: Percentage
  type: string
- container: ''
  name: IsoCountryCode
  type: string
- container: ''
  name: PhoneNumber
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: RecommendationProviderIdType
  type: string
- container: ''
  name: RecommendationProviderRoleArn
  type: string
- container: ''
  name: RecommendationProviderUri
  type: string
- container: ''
  name: RecommendationTransformerUri
  type: string
- container: ''
  name: RecommendationsDisplayName
  type: string
- container: ''
  name: RecommendationsPerMessage
  type: string
- container: ''
  name: BatchItem
  type: string
- container: ''
  name: EMAIL
  type: string
- container: ''
  name: SMS
  type: string
- container: ''
  name: PUSH
  type: string
- container: ''
  name: VOICE
  type: string
- container: ''
  name: CUSTOM
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: AttributeType
  type: string
- container: ''
  name: DestinationStreamArn
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: AppPackageName
  type: string
- container: ''
  name: AppTitle
  type: string
- container: ''
  name: AppVersionCode
  type: string
- container: ''
  name: ClientSdkVersion
  type: string
- container: ''
  name: EventType
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: SdkName
  type: string
- container: ''
  name: Timestamp
  type: string
- container: ''
  name: End
  type: string
- container: ''
  name: Start
  type: string
- container: ''
  name: Dimensions
  type: string
- container: ''
  name: FilterType
  type: string
- container: ''
  name: Endpoint
  type: string
- container: ''
  name: Events
  type: string
- container: ''
  name: ButtonAction
  type: string
- container: ''
  name: Link
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: LastUpdatedBy
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: CreationDate
  type: string
- container: set
  name: Campaigns
  type: string
- container: set
  name: Segments
  type: string
- container: ''
  name: Channels
  type: string
- container: ''
  name: StartDateTime
  type: string
- container: ''
  name: EndDateTime
  type: string
- container: ''
  name: Frequency
  type: string
- container: ''
  name: IsLocalTime
  type: string
- container: ''
  name: Timezone
  type: string
- container: ''
  name: DeliveryUri
  type: string
- container: ''
  name: EndpointTypes
  type: string
- container: ''
  name: Blacklist
  type: string
- container: ''
  name: BackgroundColor
  type: string
- container: ''
  name: BorderRadius
  type: string
- container: ''
  name: Text
  type: string
- container: ''
  name: TextColor
  type: string
property_count: 68
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-general-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"OpenHoursRule\": \"pinpoint:OpenHoursRule\",\n    \"StartTime\": {\n      \"@id\": \"pinpoint:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"pinpoint:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Session\": \"pinpoint:Session\",\n    \"Duration\": {\n      \"@id\": \"pinpoint:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTimestamp\": {\n      \"@id\": \"pinpoint:StartTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StopTimestamp\": {\n      \"@id\": \"pinpoint:StopTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GPSCoordinates\": \"\
  pinpoint:GPSCoordinates\",\n    \"Latitude\": {\n      \"@id\": \"pinpoint:Latitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Longitude\": {\n      \"@id\": \"pinpoint:Longitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RandomSplitEntry\": \"pinpoint:RandomSplitEntry\",\n    \"NextActivity\": {\n      \"@id\": \"pinpoint:NextActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Percentage\": {\n      \"@id\": \"pinpoint:Percentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateRecommenderConfigurationRequest\": \"pinpoint:UpdateRecommenderConfigurationRequest\",\n    \"UpdateRecommenderConfiguration\": \"pinpoint:UpdateRecommenderConfiguration\",\n    \"TagResourceRequest\": \"pinpoint:TagResourceRequest\",\n    \"TagsModel\": \"pinpoint:TagsModel\",\n    \"NumberValidateRequest\": \"pinpoint:NumberValidateRequest\",\n    \"IsoCountryCode\": {\n      \"@id\": \"pinpoint:IsoCountryCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneNumber\": {\n\
  \      \"@id\": \"pinpoint:PhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attributes\": {\n      \"@id\": \"pinpoint:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"pinpoint:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderIdType\": {\n      \"@id\": \"pinpoint:RecommendationProviderIdType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderRoleArn\": {\n      \"@id\": \"pinpoint:RecommendationProviderRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderUri\": {\n      \"@id\": \"pinpoint:RecommendationProviderUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationTransformerUri\": {\n      \"@id\": \"pinpoint:RecommendationTransformerUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationsDisplayName\": {\n      \"@id\"\
  : \"pinpoint:RecommendationsDisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationsPerMessage\": {\n      \"@id\": \"pinpoint:RecommendationsPerMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneNumberValidateRequest\": \"pinpoint:PhoneNumberValidateRequest\",\n    \"EventsRequest\": \"pinpoint:EventsRequest\",\n    \"BatchItem\": {\n      \"@id\": \"pinpoint:BatchItem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OpenHours\": \"pinpoint:OpenHours\",\n    \"EMAIL\": {\n      \"@id\": \"pinpoint:EMAIL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SMS\": {\n      \"@id\": \"pinpoint:SMS\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PUSH\": {\n      \"@id\": \"pinpoint:PUSH\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VOICE\": {\n      \"@id\": \"pinpoint:VOICE\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CUSTOM\": {\n      \"@id\": \"pinpoint:CUSTOM\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributesResource\": \"pinpoint:AttributesResource\"\
  ,\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributeType\": {\n      \"@id\": \"pinpoint:AttributeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WriteEventStream\": \"pinpoint:WriteEventStream\",\n    \"DestinationStreamArn\": {\n      \"@id\": \"pinpoint:DestinationStreamArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"pinpoint:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetRecommenderConfigurationsRequest\": \"pinpoint:GetRecommenderConfigurationsRequest\",\n    \"Event\": \"pinpoint:Event\",\n    \"AppPackageName\": {\n      \"@id\": \"pinpoint:AppPackageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppTitle\": {\n      \"@id\": \"pinpoint:AppTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppVersionCode\": {\n      \"@id\": \"pinpoint:AppVersionCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientSdkVersion\": {\n    \
  \  \"@id\": \"pinpoint:ClientSdkVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventType\": {\n      \"@id\": \"pinpoint:EventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"pinpoint:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SdkName\": {\n      \"@id\": \"pinpoint:SdkName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"pinpoint:Timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuietTime\": \"pinpoint:QuietTime\",\n    \"End\": {\n      \"@id\": \"pinpoint:End\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Start\": {\n      \"@id\": \"pinpoint:Start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventFilter\": \"pinpoint:EventFilter\",\n    \"Dimensions\": {\n      \"@id\": \"pinpoint:Dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterType\": {\n      \"@id\": \"pinpoint:FilterType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEventStreamRequest\"\
  : \"pinpoint:DeleteEventStreamRequest\",\n    \"EventsBatch\": \"pinpoint:EventsBatch\",\n    \"Endpoint\": {\n      \"@id\": \"pinpoint:Endpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Events\": {\n      \"@id\": \"pinpoint:Events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RemoveAttributesRequest\": \"pinpoint:RemoveAttributesRequest\",\n    \"UpdateAttributesRequest\": \"pinpoint:UpdateAttributesRequest\",\n    \"CreateRecommenderConfiguration\": \"pinpoint:CreateRecommenderConfiguration\",\n    \"OverrideButtonConfiguration\": \"pinpoint:OverrideButtonConfiguration\",\n    \"ButtonAction\": {\n      \"@id\": \"pinpoint:ButtonAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Link\": {\n      \"@id\": \"pinpoint:Link\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClosedDays\": \"pinpoint:ClosedDays\",\n    \"EventStream\": \"pinpoint:EventStream\",\n    \"ExternalId\": {\n      \"@id\": \"pinpoint:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedBy\": {\n      \"@id\": \"pinpoint:LastUpdatedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetRecommenderConfigurationRequest\": \"pinpoint:GetRecommenderConfigurationRequest\",\n    \"CreateRecommenderConfigurationRequest\": \"pinpoint:CreateRecommenderConfigurationRequest\",\n    \"DeleteRecommenderConfigurationRequest\": \"pinpoint:DeleteRecommenderConfigurationRequest\",\n    \"PutEventsRequest\": \"pinpoint:PutEventsRequest\",\n    \"Amazon Pinpoint Application Definition\": \"pinpoint:Amazon Pinpoint Application Definition\",\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"@id\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Campaigns\": {\n      \"\
  @id\": \"pinpoint:Campaigns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Segments\": {\n      \"@id\": \"pinpoint:Segments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Channels\": {\n      \"@id\": \"pinpoint:Channels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClosedDaysRule\": \"pinpoint:ClosedDaysRule\",\n    \"StartDateTime\": {\n      \"@id\": \"pinpoint:StartDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndDateTime\": {\n      \"@id\": \"pinpoint:EndDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Schedule\": \"pinpoint:Schedule\",\n    \"Frequency\": {\n      \"@id\": \"pinpoint:Frequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsLocalTime\": {\n      \"@id\": \"pinpoint:IsLocalTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timezone\": {\n      \"@id\": \"pinpoint:Timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomDeliveryConfiguration\"\
  : \"pinpoint:CustomDeliveryConfiguration\",\n    \"DeliveryUri\": {\n      \"@id\": \"pinpoint:DeliveryUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointTypes\": {\n      \"@id\": \"pinpoint:EndpointTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEventStreamRequest\": \"pinpoint:GetEventStreamRequest\",\n    \"Blacklist\": {\n      \"@id\": \"pinpoint:Blacklist\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultButtonConfiguration\": \"pinpoint:DefaultButtonConfiguration\",\n    \"BackgroundColor\": {\n      \"@id\": \"pinpoint:BackgroundColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BorderRadius\": {\n      \"@id\": \"pinpoint:BorderRadius\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Text\": {\n      \"@id\": \"pinpoint:Text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TextColor\": {\n      \"@id\": \"pinpoint:TextColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutEventStreamRequest\": \"pinpoint:PutEventStreamRequest\",\n\
  \    \"ListTagsForResourceRequest\": \"pinpoint:ListTagsForResourceRequest\",\n    \"UntagResourceRequest\": \"pinpoint:UntagResourceRequest\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-general-context.jsonld
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
