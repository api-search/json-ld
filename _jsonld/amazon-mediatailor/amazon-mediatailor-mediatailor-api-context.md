---
api_specs:
- filename: amazon-mediatailor-openapi-original.yml
  format: yaml
  label: Amazon MediaTailor API
  slug: mediatailor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/openapi/amazon-mediatailor-openapi-original.yml
class_count: 154
classes:
- DeleteVodSourceResponse
- PutPlaybackConfigurationRequest
- LogTypes
- ListVodSourcesResponse
- CreateProgramRequest
- AvailMatchingCriteria
- Tier
- StopChannelRequest
- ScheduleEntry
- ScheduleConfiguration
- PutChannelPolicyRequest
- AccessConfiguration
- ListPrefetchSchedulesResponse
- ManifestProcessingRules
- TimeSignalMessage
- AdMarkerPassthrough
- DescribeSourceLocationResponse
- RequestOutputItem
- AccessType
- DeleteVodSourceRequest
- ListLiveSourcesRequest
- CreateVodSourceResponse
- UpdateProgramTransition
- DashConfigurationForPut
- StopChannelResponse
- MessageType
- MaxResults
- VodSource
- UpdateProgramResponse
- DeleteChannelPolicyResponse
- AvailSuppression
- CreatePrefetchScheduleRequest
- Type
- LogConfiguration
- HttpPackageConfigurations
- SlateSource
- DescribeVodSourceResponse
- Transition
- DeleteProgramResponse
- StartChannelResponse
- UpdateSourceLocationRequest
- UpdateProgramRequest
- ListSourceLocationsRequest
- ChannelState
- ConfigurationAliasesResponse
- DescribeProgramResponse
- DefaultSegmentDeliveryConfiguration
- UpdateVodSourceRequest
- CreateLiveSourceResponse
- ListPlaybackConfigurationsRequest
- Long
- UpdateLiveSourceRequest
- TagResourceRequest
- String
- UpdateProgramScheduleConfiguration
- PutPlaybackConfigurationResponse
- SegmentationDescriptor
- CreateChannelResponse
- GetChannelPolicyResponse
- ConfigureLogsForPlaybackConfigurationResponse
- PrefetchSchedule
- StartChannelRequest
- HttpConfiguration
- GetChannelScheduleResponse
- DeleteChannelRequest
- SecretsManagerAccessTokenConfiguration
- Bumper
- DashPlaylistSettings
- DescribeChannelRequest
- DescribeSourceLocationRequest
- ScheduleEntryType
- CreateVodSourceRequest
- LivePreRollConfiguration
- ListChannelsRequest
- ListAlertsResponse
- DeletePlaybackConfigurationResponse
- GetPrefetchScheduleRequest
- GetPlaybackConfigurationResponse
- CreatePrefetchScheduleResponse
- DescribeLiveSourceResponse
- RelativePosition
- Integer
- DeleteLiveSourceRequest
- DeletePrefetchScheduleRequest
- GetPrefetchScheduleResponse
- CreateSourceLocationRequest
- DeleteChannelResponse
- ListChannelsResponse
- ListVodSourcesRequest
- UpdateChannelResponse
- LogConfigurationForChannel
- HlsPlaylistSettings
- ScheduleAdBreak
- ListTagsForResourceRequest
- UpdateSourceLocationResponse
- DeleteProgramRequest
- DashConfiguration
- GetChannelPolicyRequest
- DescribeProgramRequest
- ConfigurationAliasesRequest
- AdBreak
- Operator
- DeleteLiveSourceResponse
- ListPrefetchSchedulesRequest
- ListTagsForResourceResponse
- SegmentDeliveryConfiguration
- ListLiveSourcesResponse
- LiveSource
- CreateLiveSourceRequest
- ConfigureLogsForChannelResponse
- ListPlaybackConfigurationsResponse
- DeleteSourceLocationResponse
- DeleteChannelPolicyRequest
- UpdateLiveSourceResponse
- HttpPackageConfiguration
- RequestOutputs
- ResponseOutputItem
- UpdateChannelRequest
- CreateSourceLocationResponse
- DescribeLiveSourceRequest
- SourceLocation
- UntagResourceRequest
- ClipRange
- GetPlaybackConfigurationRequest
- CdnConfiguration
- Mode
- UpdateVodSourceResponse
- DeleteSourceLocationRequest
- DescribeVodSourceRequest
- SpliceInsertMessage
- PlaybackMode
- Alert
- DeletePrefetchScheduleResponse
- ResponseOutputs
- PrefetchRetrieval
- ListSourceLocationsResponse
- PutChannelPolicyResponse
- CreateProgramResponse
- DeletePlaybackConfigurationRequest
- GetChannelScheduleRequest
- ConfigureLogsForChannelRequest
- CreateChannelRequest
- SegmentationDescriptorList
- LogType
- PrefetchConsumption
- HlsConfiguration
- DescribeChannelResponse
- OriginManifestType
- Channel
- ListAlertsRequest
- PlaybackConfiguration
- ConfigureLogsForPlaybackConfigurationRequest
- name
- creationTime
context_file: json-ld/amazon-mediatailor-mediatailor-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/json-ld/amazon-mediatailor-mediatailor-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mediatailor Mediatailor Api from Amazon MediaTailor.
layout: jsonld
name: Amazon Mediatailor Mediatailor Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: adDecisionServerUrl
  type: string
- container: ''
  name: availSuppression
  type: string
- container: ''
  name: bumper
  type: string
- container: ''
  name: cdnConfiguration
  type: string
- container: ''
  name: configurationAliases
  type: string
- container: ''
  name: dashConfiguration
  type: string
- container: ''
  name: livePreRollConfiguration
  type: string
- container: ''
  name: manifestProcessingRules
  type: string
- container: ''
  name: personalizationThresholdSeconds
  type: string
- container: ''
  name: slateAdUrl
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: transcodeProfileName
  type: string
- container: ''
  name: videoContentSourceUrl
  type: string
- container: ''
  name: items
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: adBreaks
  type: string
- container: ''
  name: liveSourceName
  type: string
- container: ''
  name: scheduleConfiguration
  type: string
- container: ''
  name: sourceLocationName
  type: string
- container: ''
  name: vodSourceName
  type: string
- container: ''
  name: dynamicVariable
  type: string
- container: ''
  name: operator
  type: string
- container: ''
  name: approximateDurationSeconds
  type: string
- container: ''
  name: approximateStartTime
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: channelName
  type: string
- container: ''
  name: programName
  type: string
- container: ''
  name: scheduleAdBreaks
  type: string
- container: ''
  name: scheduleEntryType
  type: string
- container: ''
  name: clipRange
  type: string
- container: ''
  name: transition
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: accessType
  type: string
- container: ''
  name: secretsManagerAccessTokenConfiguration
  type: string
- container: ''
  name: adMarkerPassthrough
  type: string
- container: ''
  name: segmentationDescriptors
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: accessConfiguration
  type: string
- container: ''
  name: defaultSegmentDeliveryConfiguration
  type: string
- container: ''
  name: httpConfiguration
  type: string
- container: ''
  name: lastModifiedTime
  type: string
- container: ''
  name: segmentDeliveryConfigurations
  type: string
- container: ''
  name: dashPlaylistSettings
  type: string
- container: ''
  name: hlsPlaylistSettings
  type: string
- container: ''
  name: manifestName
  type: string
- container: ''
  name: sourceGroup
  type: string
- container: ''
  name: httpPackageConfigurations
  type: string
- container: ''
  name: durationMillis
  type: string
- container: ''
  name: scheduledStartTimeMillis
  type: string
- container: ''
  name: mpdLocation
  type: string
- container: ''
  name: originManifestType
  type: string
- container: ''
  name: scheduledStartTime
  type: string
- container: ''
  name: mode
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: consumption
  type: string
- container: ''
  name: retrieval
  type: string
- container: ''
  name: streamId
  type: string
- container: ''
  name: percentEnabled
  type: string
- container: ''
  name: relativePosition
  type: string
- container: ''
  name: relativeProgram
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: baseUrl
  type: string
- container: ''
  name: hlsConfiguration
  type: string
- container: ''
  name: logConfiguration
  type: string
- container: ''
  name: playbackConfigurationArn
  type: string
- container: ''
  name: playbackEndpointPrefix
  type: string
- container: ''
  name: sessionInitializationEndpointPrefix
  type: string
- container: ''
  name: segmentNum
  type: string
- container: ''
  name: segmentationEventId
  type: string
- container: ''
  name: segmentationTypeId
  type: string
- container: ''
  name: segmentationUpid
  type: string
- container: ''
  name: segmentationUpidType
  type: string
- container: ''
  name: segmentsExpected
  type: string
- container: ''
  name: subSegmentNum
  type: string
- container: ''
  name: subSegmentsExpected
  type: string
- container: ''
  name: channelState
  type: string
- container: ''
  name: fillerSlate
  type: string
- container: ''
  name: outputs
  type: string
- container: ''
  name: playbackMode
  type: string
- container: ''
  name: tier
  type: string
- container: ''
  name: playbackConfigurationName
  type: string
- container: ''
  name: headerName
  type: string
- container: ''
  name: secretArn
  type: string
- container: ''
  name: secretStringKey
  type: string
- container: ''
  name: endUrl
  type: string
- container: ''
  name: startUrl
  type: string
- container: ''
  name: manifestWindowSeconds
  type: string
- container: ''
  name: minBufferTimeSeconds
  type: string
- container: ''
  name: minUpdatePeriodSeconds
  type: string
- container: ''
  name: suggestedPresentationDelaySeconds
  type: string
- container: ''
  name: maxDurationSeconds
  type: string
- container: ''
  name: logTypes
  type: string
- container: ''
  name: manifestEndpointPrefix
  type: string
- container: ''
  name: messageType
  type: string
- container: ''
  name: offsetMillis
  type: string
- container: ''
  name: slate
  type: string
- container: ''
  name: spliceInsertMessage
  type: string
- container: ''
  name: timeSignalMessage
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: playbackUrl
  type: string
- container: ''
  name: endOffsetMillis
  type: string
- container: ''
  name: adSegmentUrlPrefix
  type: string
- container: ''
  name: contentSegmentUrlPrefix
  type: string
- container: ''
  name: availNum
  type: string
- container: ''
  name: availsExpected
  type: string
- container: ''
  name: spliceEventId
  type: string
- container: ''
  name: uniqueProgramId
  type: string
- container: ''
  name: alertCode
  type: string
- container: ''
  name: alertMessage
  type: string
- container: ''
  name: relatedResourceArns
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: dynamicVariables
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: availMatchingCriteria
  type: string
property_count: 116
provider_name: Amazon MediaTailor
provider_slug: amazon-mediatailor
slug: amazon-mediatailor-mediatailor-api-context
source_filename: amazon-mediatailor-mediatailor-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeleteVodSourceResponse\": \"pan:DeleteVodSourceResponse\",\n    \"PutPlaybackConfigurationRequest\": \"pan:PutPlaybackConfigurationRequest\",\n    \"LogTypes\": \"pan:LogTypes\",\n    \"ListVodSourcesResponse\": \"pan:ListVodSourcesResponse\",\n    \"CreateProgramRequest\": \"pan:CreateProgramRequest\",\n    \"AvailMatchingCriteria\": \"pan:AvailMatchingCriteria\",\n    \"Tier\": \"pan:Tier\",\n    \"StopChannelRequest\": \"pan:StopChannelRequest\",\n    \"ScheduleEntry\": \"pan:ScheduleEntry\",\n    \"ScheduleConfiguration\": \"pan:ScheduleConfiguration\",\n    \"PutChannelPolicyRequest\": \"pan:PutChannelPolicyRequest\",\n    \"AccessConfiguration\": \"pan:AccessConfiguration\",\n    \"ListPrefetchSchedulesResponse\": \"pan:ListPrefetchSchedulesResponse\"\
  ,\n    \"ManifestProcessingRules\": \"pan:ManifestProcessingRules\",\n    \"TimeSignalMessage\": \"pan:TimeSignalMessage\",\n    \"AdMarkerPassthrough\": \"pan:AdMarkerPassthrough\",\n    \"DescribeSourceLocationResponse\": \"pan:DescribeSourceLocationResponse\",\n    \"RequestOutputItem\": \"pan:RequestOutputItem\",\n    \"AccessType\": \"pan:AccessType\",\n    \"DeleteVodSourceRequest\": \"pan:DeleteVodSourceRequest\",\n    \"ListLiveSourcesRequest\": \"pan:ListLiveSourcesRequest\",\n    \"CreateVodSourceResponse\": \"pan:CreateVodSourceResponse\",\n    \"UpdateProgramTransition\": \"pan:UpdateProgramTransition\",\n    \"DashConfigurationForPut\": \"pan:DashConfigurationForPut\",\n    \"StopChannelResponse\": \"pan:StopChannelResponse\",\n    \"MessageType\": \"pan:MessageType\",\n    \"MaxResults\": \"pan:MaxResults\",\n    \"VodSource\": \"pan:VodSource\",\n    \"UpdateProgramResponse\": \"pan:UpdateProgramResponse\",\n    \"DeleteChannelPolicyResponse\": \"pan:DeleteChannelPolicyResponse\"\
  ,\n    \"AvailSuppression\": \"pan:AvailSuppression\",\n    \"CreatePrefetchScheduleRequest\": \"pan:CreatePrefetchScheduleRequest\",\n    \"Type\": \"pan:Type\",\n    \"LogConfiguration\": \"pan:LogConfiguration\",\n    \"HttpPackageConfigurations\": \"pan:HttpPackageConfigurations\",\n    \"SlateSource\": \"pan:SlateSource\",\n    \"DescribeVodSourceResponse\": \"pan:DescribeVodSourceResponse\",\n    \"Transition\": \"pan:Transition\",\n    \"DeleteProgramResponse\": \"pan:DeleteProgramResponse\",\n    \"StartChannelResponse\": \"pan:StartChannelResponse\",\n    \"UpdateSourceLocationRequest\": \"pan:UpdateSourceLocationRequest\",\n    \"UpdateProgramRequest\": \"pan:UpdateProgramRequest\",\n    \"ListSourceLocationsRequest\": \"pan:ListSourceLocationsRequest\",\n    \"ChannelState\": \"pan:ChannelState\",\n    \"ConfigurationAliasesResponse\": \"pan:ConfigurationAliasesResponse\",\n    \"DescribeProgramResponse\": \"pan:DescribeProgramResponse\",\n    \"DefaultSegmentDeliveryConfiguration\"\
  : \"pan:DefaultSegmentDeliveryConfiguration\",\n    \"UpdateVodSourceRequest\": \"pan:UpdateVodSourceRequest\",\n    \"CreateLiveSourceResponse\": \"pan:CreateLiveSourceResponse\",\n    \"ListPlaybackConfigurationsRequest\": \"pan:ListPlaybackConfigurationsRequest\",\n    \"Long\": \"pan:Long\",\n    \"UpdateLiveSourceRequest\": \"pan:UpdateLiveSourceRequest\",\n    \"TagResourceRequest\": \"pan:TagResourceRequest\",\n    \"String\": \"pan:String\",\n    \"UpdateProgramScheduleConfiguration\": \"pan:UpdateProgramScheduleConfiguration\",\n    \"PutPlaybackConfigurationResponse\": \"pan:PutPlaybackConfigurationResponse\",\n    \"SegmentationDescriptor\": \"pan:SegmentationDescriptor\",\n    \"CreateChannelResponse\": \"pan:CreateChannelResponse\",\n    \"GetChannelPolicyResponse\": \"pan:GetChannelPolicyResponse\",\n    \"ConfigureLogsForPlaybackConfigurationResponse\": \"pan:ConfigureLogsForPlaybackConfigurationResponse\",\n    \"PrefetchSchedule\": \"pan:PrefetchSchedule\",\n    \"StartChannelRequest\"\
  : \"pan:StartChannelRequest\",\n    \"HttpConfiguration\": \"pan:HttpConfiguration\",\n    \"GetChannelScheduleResponse\": \"pan:GetChannelScheduleResponse\",\n    \"DeleteChannelRequest\": \"pan:DeleteChannelRequest\",\n    \"SecretsManagerAccessTokenConfiguration\": \"pan:SecretsManagerAccessTokenConfiguration\",\n    \"Bumper\": \"pan:Bumper\",\n    \"DashPlaylistSettings\": \"pan:DashPlaylistSettings\",\n    \"DescribeChannelRequest\": \"pan:DescribeChannelRequest\",\n    \"DescribeSourceLocationRequest\": \"pan:DescribeSourceLocationRequest\",\n    \"ScheduleEntryType\": \"pan:ScheduleEntryType\",\n    \"CreateVodSourceRequest\": \"pan:CreateVodSourceRequest\",\n    \"LivePreRollConfiguration\": \"pan:LivePreRollConfiguration\",\n    \"ListChannelsRequest\": \"pan:ListChannelsRequest\",\n    \"ListAlertsResponse\": \"pan:ListAlertsResponse\",\n    \"DeletePlaybackConfigurationResponse\": \"pan:DeletePlaybackConfigurationResponse\",\n    \"GetPrefetchScheduleRequest\": \"pan:GetPrefetchScheduleRequest\"\
  ,\n    \"GetPlaybackConfigurationResponse\": \"pan:GetPlaybackConfigurationResponse\",\n    \"CreatePrefetchScheduleResponse\": \"pan:CreatePrefetchScheduleResponse\",\n    \"DescribeLiveSourceResponse\": \"pan:DescribeLiveSourceResponse\",\n    \"RelativePosition\": \"pan:RelativePosition\",\n    \"Integer\": \"pan:Integer\",\n    \"DeleteLiveSourceRequest\": \"pan:DeleteLiveSourceRequest\",\n    \"DeletePrefetchScheduleRequest\": \"pan:DeletePrefetchScheduleRequest\",\n    \"GetPrefetchScheduleResponse\": \"pan:GetPrefetchScheduleResponse\",\n    \"CreateSourceLocationRequest\": \"pan:CreateSourceLocationRequest\",\n    \"DeleteChannelResponse\": \"pan:DeleteChannelResponse\",\n    \"ListChannelsResponse\": \"pan:ListChannelsResponse\",\n    \"ListVodSourcesRequest\": \"pan:ListVodSourcesRequest\",\n    \"UpdateChannelResponse\": \"pan:UpdateChannelResponse\",\n    \"LogConfigurationForChannel\": \"pan:LogConfigurationForChannel\",\n    \"HlsPlaylistSettings\": \"pan:HlsPlaylistSettings\"\
  ,\n    \"ScheduleAdBreak\": \"pan:ScheduleAdBreak\",\n    \"ListTagsForResourceRequest\": \"pan:ListTagsForResourceRequest\",\n    \"UpdateSourceLocationResponse\": \"pan:UpdateSourceLocationResponse\",\n    \"DeleteProgramRequest\": \"pan:DeleteProgramRequest\",\n    \"DashConfiguration\": \"pan:DashConfiguration\",\n    \"GetChannelPolicyRequest\": \"pan:GetChannelPolicyRequest\",\n    \"DescribeProgramRequest\": \"pan:DescribeProgramRequest\",\n    \"ConfigurationAliasesRequest\": \"pan:ConfigurationAliasesRequest\",\n    \"AdBreak\": \"pan:AdBreak\",\n    \"Operator\": \"pan:Operator\",\n    \"DeleteLiveSourceResponse\": \"pan:DeleteLiveSourceResponse\",\n    \"ListPrefetchSchedulesRequest\": \"pan:ListPrefetchSchedulesRequest\",\n    \"ListTagsForResourceResponse\": \"pan:ListTagsForResourceResponse\",\n    \"SegmentDeliveryConfiguration\": \"pan:SegmentDeliveryConfiguration\",\n    \"ListLiveSourcesResponse\": \"pan:ListLiveSourcesResponse\",\n    \"LiveSource\": \"pan:LiveSource\"\
  ,\n    \"CreateLiveSourceRequest\": \"pan:CreateLiveSourceRequest\",\n    \"ConfigureLogsForChannelResponse\": \"pan:ConfigureLogsForChannelResponse\",\n    \"ListPlaybackConfigurationsResponse\": \"pan:ListPlaybackConfigurationsResponse\",\n    \"DeleteSourceLocationResponse\": \"pan:DeleteSourceLocationResponse\",\n    \"DeleteChannelPolicyRequest\": \"pan:DeleteChannelPolicyRequest\",\n    \"UpdateLiveSourceResponse\": \"pan:UpdateLiveSourceResponse\",\n    \"HttpPackageConfiguration\": \"pan:HttpPackageConfiguration\",\n    \"RequestOutputs\": \"pan:RequestOutputs\",\n    \"ResponseOutputItem\": \"pan:ResponseOutputItem\",\n    \"UpdateChannelRequest\": \"pan:UpdateChannelRequest\",\n    \"CreateSourceLocationResponse\": \"pan:CreateSourceLocationResponse\",\n    \"DescribeLiveSourceRequest\": \"pan:DescribeLiveSourceRequest\",\n    \"SourceLocation\": \"pan:SourceLocation\",\n    \"UntagResourceRequest\": \"pan:UntagResourceRequest\",\n    \"ClipRange\": \"pan:ClipRange\",\n    \"\
  GetPlaybackConfigurationRequest\": \"pan:GetPlaybackConfigurationRequest\",\n    \"CdnConfiguration\": \"pan:CdnConfiguration\",\n    \"Mode\": \"pan:Mode\",\n    \"UpdateVodSourceResponse\": \"pan:UpdateVodSourceResponse\",\n    \"DeleteSourceLocationRequest\": \"pan:DeleteSourceLocationRequest\",\n    \"DescribeVodSourceRequest\": \"pan:DescribeVodSourceRequest\",\n    \"SpliceInsertMessage\": \"pan:SpliceInsertMessage\",\n    \"PlaybackMode\": \"pan:PlaybackMode\",\n    \"Alert\": \"pan:Alert\",\n    \"DeletePrefetchScheduleResponse\": \"pan:DeletePrefetchScheduleResponse\",\n    \"ResponseOutputs\": \"pan:ResponseOutputs\",\n    \"PrefetchRetrieval\": \"pan:PrefetchRetrieval\",\n    \"ListSourceLocationsResponse\": \"pan:ListSourceLocationsResponse\",\n    \"PutChannelPolicyResponse\": \"pan:PutChannelPolicyResponse\",\n    \"CreateProgramResponse\": \"pan:CreateProgramResponse\",\n    \"DeletePlaybackConfigurationRequest\": \"pan:DeletePlaybackConfigurationRequest\",\n    \"GetChannelScheduleRequest\"\
  : \"pan:GetChannelScheduleRequest\",\n    \"ConfigureLogsForChannelRequest\": \"pan:ConfigureLogsForChannelRequest\",\n    \"CreateChannelRequest\": \"pan:CreateChannelRequest\",\n    \"SegmentationDescriptorList\": \"pan:SegmentationDescriptorList\",\n    \"LogType\": \"pan:LogType\",\n    \"PrefetchConsumption\": \"pan:PrefetchConsumption\",\n    \"HlsConfiguration\": \"pan:HlsConfiguration\",\n    \"DescribeChannelResponse\": \"pan:DescribeChannelResponse\",\n    \"OriginManifestType\": \"pan:OriginManifestType\",\n    \"Channel\": \"pan:Channel\",\n    \"ListAlertsRequest\": \"pan:ListAlertsRequest\",\n    \"PlaybackConfiguration\": \"pan:PlaybackConfiguration\",\n    \"ConfigureLogsForPlaybackConfigurationRequest\": \"pan:ConfigureLogsForPlaybackConfigurationRequest\",\n    \"adDecisionServerUrl\": {\n      \"@id\": \"pan:ad_decision_server_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availSuppression\": {\n      \"@id\": \"pan:avail_suppression\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"bumper\": {\n      \"@id\": \"pan:bumper\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cdnConfiguration\": {\n      \"@id\": \"pan:cdn_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationAliases\": {\n      \"@id\": \"pan:configuration_aliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashConfiguration\": {\n      \"@id\": \"pan:dash_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"livePreRollConfiguration\": {\n      \"@id\": \"pan:live_pre_roll_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestProcessingRules\": {\n      \"@id\": \"pan:manifest_processing_rules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"personalizationThresholdSeconds\": {\n      \"@id\": \"pan:personalization_threshold_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slateAdUrl\": {\n      \"@id\": \"pan:slate_ad_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\"\
  : {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transcodeProfileName\": {\n      \"@id\": \"pan:transcode_profile_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoContentSourceUrl\": {\n      \"@id\": \"pan:video_content_source_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"items\": {\n      \"@id\": \"pan:items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adBreaks\": {\n      \"@id\": \"pan:ad_breaks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"liveSourceName\": {\n      \"@id\": \"pan:live_source_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleConfiguration\": {\n      \"@id\": \"pan:schedule_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLocationName\": {\n      \"@id\": \"pan:source_location_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vodSourceName\": {\n      \"@id\"\
  : \"pan:vod_source_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamicVariable\": {\n      \"@id\": \"pan:dynamic_variable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operator\": {\n      \"@id\": \"pan:operator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approximateDurationSeconds\": {\n      \"@id\": \"pan:approximate_duration_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"approximateStartTime\": {\n      \"@id\": \"pan:approximate_start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelName\": {\n      \"@id\": \"pan:channel_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programName\": {\n      \"@id\": \"pan:program_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleAdBreaks\": {\n      \"@id\": \"pan:schedule_ad_breaks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleEntryType\": {\n      \"@id\": \"pan:schedule_entry_type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"clipRange\": {\n      \"@id\": \"pan:clip_range\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transition\": {\n      \"@id\": \"pan:transition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"pan:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessType\": {\n      \"@id\": \"pan:access_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretsManagerAccessTokenConfiguration\": {\n      \"@id\": \"pan:secrets_manager_access_token_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adMarkerPassthrough\": {\n      \"@id\": \"pan:ad_marker_passthrough\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentationDescriptors\": {\n      \"@id\": \"pan:segmentation_descriptors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessConfiguration\": {\n      \"@id\": \"pan:access_configuration\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": \"schema:dateCreated\",\n    \"defaultSegmentDeliveryConfiguration\": {\n      \"@id\": \"pan:default_segment_delivery_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpConfiguration\": {\n      \"@id\": \"pan:http_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"pan:last_modified_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentDeliveryConfigurations\": {\n      \"@id\": \"pan:segment_delivery_configurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashPlaylistSettings\": {\n      \"@id\": \"pan:dash_playlist_settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hlsPlaylistSettings\": {\n      \"@id\": \"pan:hls_playlist_settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestName\": {\n      \"@id\": \"pan:manifest_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceGroup\": {\n      \"@id\": \"\
  pan:source_group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpPackageConfigurations\": {\n      \"@id\": \"pan:http_package_configurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"durationMillis\": {\n      \"@id\": \"pan:duration_millis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledStartTimeMillis\": {\n      \"@id\": \"pan:scheduled_start_time_millis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mpdLocation\": {\n      \"@id\": \"pan:mpd_location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originManifestType\": {\n      \"@id\": \"pan:origin_manifest_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledStartTime\": {\n      \"@id\": \"pan:scheduled_start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mode\": {\n      \"@id\": \"pan:mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"consumption\": {\n      \"@id\": \"pan:consumption\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"retrieval\": {\n      \"@id\": \"pan:retrieval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamId\": {\n      \"@id\": \"pan:stream_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentEnabled\": {\n      \"@id\": \"pan:percent_enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relativePosition\": {\n      \"@id\": \"pan:relative_position\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relativeProgram\": {\n      \"@id\": \"pan:relative_program\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseUrl\": {\n      \"@id\": \"pan:base_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hlsConfiguration\": {\n      \"@id\": \"pan:hls_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logConfiguration\": {\n      \"@id\": \"pan:log_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playbackConfigurationArn\"\
  : {\n      \"@id\": \"pan:playback_configuration_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playbackEndpointPrefix\": {\n      \"@id\": \"pan:playback_endpoint_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionInitializationEndpointPrefix\": {\n      \"@id\": \"pan:session_initialization_endpoint_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentNum\": {\n      \"@id\": \"pan:segment_num\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentationEventId\": {\n      \"@id\": \"pan:segmentation_event_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentationTypeId\": {\n      \"@id\": \"pan:segmentation_type_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentationUpid\": {\n      \"@id\": \"pan:segmentation_upid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentationUpidType\": {\n      \"@id\": \"pan:segmentation_upid_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentsExpected\": {\n      \"@id\": \"pan:segments_expected\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"subSegmentNum\": {\n      \"@id\": \"pan:sub_segment_num\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subSegmentsExpected\": {\n      \"@id\": \"pan:sub_segments_expected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelState\": {\n      \"@id\": \"pan:channel_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fillerSlate\": {\n      \"@id\": \"pan:filler_slate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"pan:outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playbackMode\": {\n      \"@id\": \"pan:playback_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tier\": {\n      \"@id\": \"pan:tier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playbackConfigurationName\": {\n      \"@id\": \"pan:playback_configuration_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headerName\": {\n      \"@id\": \"pan:header_name\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"secretArn\": {\n      \"@id\": \"pan:secret_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretStringKey\": {\n      \"@id\": \"pan:secret_string_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endUrl\": {\n      \"@id\": \"pan:end_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startUrl\": {\n      \"@id\": \"pan:start_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestWindowSeconds\": {\n      \"@id\": \"pan:manifest_window_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minBufferTimeSeconds\": {\n      \"@id\": \"pan:min_buffer_time_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minUpdatePeriodSeconds\": {\n      \"@id\": \"pan:min_update_period_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedPresentationDelaySeconds\": {\n      \"@id\": \"pan:suggested_presentation_delay_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxDurationSeconds\": {\n      \"@id\": \"pan:max_duration_seconds\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"logTypes\": {\n      \"@id\": \"pan:log_types\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestEndpointPrefix\": {\n      \"@id\": \"pan:manifest_endpoint_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"messageType\": {\n      \"@id\": \"pan:message_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offsetMillis\": {\n      \"@id\": \"pan:offset_millis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"slate\": {\n      \"@id\": \"pan:slate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spliceInsertMessage\": {\n      \"@id\": \"pan:splice_insert_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeSignalMessage\": {\n      \"@id\": \"pan:time_signal_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"pan:max_results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"pan:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playbackUrl\"\
  : {\n      \"@id\": \"pan:playback_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endOffsetMillis\": {\n      \"@id\": \"pan:end_offset_millis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adSegmentUrlPrefix\": {\n      \"@id\": \"pan:ad_segment_url_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentSegmentUrlPrefix\": {\n      \"@id\": \"pan:content_segment_url_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availNum\": {\n      \"@id\": \"pan:avail_num\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availsExpected\": {\n      \"@id\": \"pan:avails_expected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spliceEventId\": {\n      \"@id\": \"pan:splice_event_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uniqueProgramId\": {\n      \"@id\": \"pan:unique_program_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertCode\": {\n      \"@id\": \"pan:alert_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alertMessage\": {\n     \
  \ \"@id\": \"pan:alert_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedResourceArns\": {\n      \"@id\": \"pan:related_resource_arns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"pan:resource_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamicVariables\": {\n      \"@id\": \"pan:dynamic_variables\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"pan:start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"availMatchingCriteria\": {\n      \"@id\": \"pan:avail_matching_criteria\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediatailor/refs/heads/main/json-ld/amazon-mediatailor-mediatailor-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
