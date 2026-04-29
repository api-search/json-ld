---
class_count: 79
classes:
- ListTagsForResourceRequest
- AdMarkers
- ConfigureLogsResponse
- IngestEndpoint
- DescribeOriginEndpointRequest
- HlsPackage
- CmafEncryption
- HlsManifest
- UpdateChannelRequest
- Authorization
- RotateIngestEndpointCredentialsResponse
- ListChannelsResponse
- DescribeHarvestJobResponse
- CmafPackage
- Channel
- AdsOnDeliveryRestrictions
- CmafPackageCreateOrUpdateParameters
- DescribeChannelRequest
- MaxResults
- MssEncryption
- DeleteOriginEndpointRequest
- SpekeKeyProvider
- CreateOriginEndpointResponse
- DeleteChannelResponse
- Status
- UpdateChannelResponse
- StreamSelection
- HarvestJob
- DeleteOriginEndpointResponse
- CmafEncryptionMethod
- StreamOrder
- ListChannelsRequest
- CreateChannelRequest
- IngressAccessLogs
- ListTagsForResourceResponse
- CreateHarvestJobResponse
- UntagResourceRequest
- Profile
- HlsIngest
- ListOriginEndpointsResponse
- UpdateOriginEndpointResponse
- CreateOriginEndpointRequest
- ListHarvestJobsResponse
- DashEncryption
- CreateHarvestJobRequest
- TagResourceRequest
- AdTriggers
- EncryptionContractConfiguration
- DescribeHarvestJobRequest
- CreateChannelResponse
- DescribeChannelResponse
- ListOriginEndpointsRequest
- PresetSpeke20Audio
- S3Destination
- UpdateOriginEndpointRequest
- MssPackage
- SegmentTemplateFormat
- RotateIngestEndpointCredentialsRequest
- ConfigureLogsRequest
- DashPackage
- ManifestLayout
- OriginEndpoint
- DeleteChannelRequest
- PlaylistType
- EncryptionMethod
- RotateChannelCredentialsRequest
- UtcTiming
- PresetSpeke20Video
- RotateChannelCredentialsResponse
- Tags
- DescribeOriginEndpointResponse
- HlsManifestCreateOrUpdateParameters
- Origination
- HlsEncryption
- EgressAccessLogs
- ListHarvestJobsRequest
- createdAt
- description
- url
context_file: json-ld/amazon-mediapackage-mediapackage-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/json-ld/amazon-mediapackage-mediapackage-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mediapackage Mediapackage Api from Amazon MediaPackage.
layout: jsonld
name: Amazon Mediapackage Mediapackage Api Context
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
  name: arn
  type: string
- container: ''
  name: egressAccessLogs
  type: string
- container: ''
  name: hlsIngest
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ingressAccessLogs
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: adMarkers
  type: string
- container: ''
  name: adTriggers
  type: string
- container: ''
  name: adsOnDeliveryRestrictions
  type: string
- container: ''
  name: encryption
  type: string
- container: ''
  name: includeDvbSubtitles
  type: string
- container: ''
  name: includeIframeOnlyStream
  type: string
- container: ''
  name: playlistType
  type: string
- container: ''
  name: playlistWindowSeconds
  type: string
- container: ''
  name: programDateTimeIntervalSeconds
  type: string
- container: ''
  name: segmentDurationSeconds
  type: string
- container: ''
  name: streamSelection
  type: string
- container: ''
  name: useAudioRenditionGroup
  type: string
- container: ''
  name: constantInitializationVector
  type: string
- container: ''
  name: encryptionMethod
  type: string
- container: ''
  name: keyRotationIntervalSeconds
  type: string
- container: ''
  name: spekeKeyProvider
  type: string
- container: ''
  name: manifestName
  type: string
- container: ''
  name: cdnIdentifierSecret
  type: string
- container: ''
  name: secretsRoleArn
  type: string
- container: ''
  name: channels
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: channelId
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: originEndpointId
  type: string
- container: ''
  name: s3Destination
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: hlsManifests
  type: string
- container: ''
  name: segmentPrefix
  type: string
- container: ''
  name: certificateArn
  type: string
- container: ''
  name: encryptionContractConfiguration
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: systemIds
  type: string
- container: ''
  name: authorization
  type: string
- container: ''
  name: cmafPackage
  type: string
- container: ''
  name: dashPackage
  type: string
- container: ''
  name: hlsPackage
  type: string
- container: ''
  name: mssPackage
  type: string
- container: ''
  name: origination
  type: string
- container: ''
  name: startoverWindowSeconds
  type: string
- container: ''
  name: timeDelaySeconds
  type: string
- container: ''
  name: whitelist
  type: string
- container: ''
  name: maxVideoBitsPerSecond
  type: string
- container: ''
  name: minVideoBitsPerSecond
  type: string
- container: ''
  name: streamOrder
  type: string
- container: ''
  name: logGroupName
  type: string
- container: ''
  name: ingestEndpoints
  type: string
- container: ''
  name: originEndpoints
  type: string
- container: ''
  name: harvestJobs
  type: string
- container: ''
  name: presetSpeke20Audio
  type: string
- container: ''
  name: presetSpeke20Video
  type: string
- container: ''
  name: bucketName
  type: string
- container: ''
  name: manifestKey
  type: string
- container: ''
  name: manifestWindowSeconds
  type: string
- container: ''
  name: manifestLayout
  type: string
- container: ''
  name: minBufferTimeSeconds
  type: string
- container: ''
  name: minUpdatePeriodSeconds
  type: string
- container: ''
  name: periodTriggers
  type: string
- container: ''
  name: profile
  type: string
- container: ''
  name: segmentTemplateFormat
  type: string
- container: ''
  name: suggestedPresentationDelaySeconds
  type: string
- container: ''
  name: utcTiming
  type: string
- container: ''
  name: utcTimingUri
  type: string
- container: ''
  name: repeatExtXKey
  type: string
property_count: 73
provider_name: Amazon MediaPackage
provider_slug: amazon-mediapackage
slug: amazon-mediapackage-mediapackage-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ListTagsForResourceRequest\": \"pan:ListTagsForResourceRequest\",\n    \"AdMarkers\": \"pan:AdMarkers\",\n    \"ConfigureLogsResponse\": \"pan:ConfigureLogsResponse\",\n    \"IngestEndpoint\": \"pan:IngestEndpoint\",\n    \"DescribeOriginEndpointRequest\": \"pan:DescribeOriginEndpointRequest\",\n    \"HlsPackage\": \"pan:HlsPackage\",\n    \"CmafEncryption\": \"pan:CmafEncryption\",\n    \"HlsManifest\": \"pan:HlsManifest\",\n    \"UpdateChannelRequest\": \"pan:UpdateChannelRequest\",\n    \"Authorization\": \"pan:Authorization\",\n    \"RotateIngestEndpointCredentialsResponse\": \"pan:RotateIngestEndpointCredentialsResponse\",\n    \"ListChannelsResponse\": \"pan:ListChannelsResponse\",\n    \"DescribeHarvestJobResponse\": \"pan:DescribeHarvestJobResponse\"\
  ,\n    \"CmafPackage\": \"pan:CmafPackage\",\n    \"Channel\": \"pan:Channel\",\n    \"AdsOnDeliveryRestrictions\": \"pan:AdsOnDeliveryRestrictions\",\n    \"CmafPackageCreateOrUpdateParameters\": \"pan:CmafPackageCreateOrUpdateParameters\",\n    \"DescribeChannelRequest\": \"pan:DescribeChannelRequest\",\n    \"MaxResults\": \"pan:MaxResults\",\n    \"MssEncryption\": \"pan:MssEncryption\",\n    \"DeleteOriginEndpointRequest\": \"pan:DeleteOriginEndpointRequest\",\n    \"SpekeKeyProvider\": \"pan:SpekeKeyProvider\",\n    \"CreateOriginEndpointResponse\": \"pan:CreateOriginEndpointResponse\",\n    \"DeleteChannelResponse\": \"pan:DeleteChannelResponse\",\n    \"Status\": \"pan:Status\",\n    \"UpdateChannelResponse\": \"pan:UpdateChannelResponse\",\n    \"StreamSelection\": \"pan:StreamSelection\",\n    \"HarvestJob\": \"pan:HarvestJob\",\n    \"DeleteOriginEndpointResponse\": \"pan:DeleteOriginEndpointResponse\",\n    \"CmafEncryptionMethod\": \"pan:CmafEncryptionMethod\",\n    \"StreamOrder\"\
  : \"pan:StreamOrder\",\n    \"ListChannelsRequest\": \"pan:ListChannelsRequest\",\n    \"CreateChannelRequest\": \"pan:CreateChannelRequest\",\n    \"IngressAccessLogs\": \"pan:IngressAccessLogs\",\n    \"ListTagsForResourceResponse\": \"pan:ListTagsForResourceResponse\",\n    \"CreateHarvestJobResponse\": \"pan:CreateHarvestJobResponse\",\n    \"UntagResourceRequest\": \"pan:UntagResourceRequest\",\n    \"Profile\": \"pan:Profile\",\n    \"HlsIngest\": \"pan:HlsIngest\",\n    \"ListOriginEndpointsResponse\": \"pan:ListOriginEndpointsResponse\",\n    \"UpdateOriginEndpointResponse\": \"pan:UpdateOriginEndpointResponse\",\n    \"CreateOriginEndpointRequest\": \"pan:CreateOriginEndpointRequest\",\n    \"ListHarvestJobsResponse\": \"pan:ListHarvestJobsResponse\",\n    \"DashEncryption\": \"pan:DashEncryption\",\n    \"CreateHarvestJobRequest\": \"pan:CreateHarvestJobRequest\",\n    \"TagResourceRequest\": \"pan:TagResourceRequest\",\n    \"AdTriggers\": \"pan:AdTriggers\",\n    \"EncryptionContractConfiguration\"\
  : \"pan:EncryptionContractConfiguration\",\n    \"DescribeHarvestJobRequest\": \"pan:DescribeHarvestJobRequest\",\n    \"CreateChannelResponse\": \"pan:CreateChannelResponse\",\n    \"DescribeChannelResponse\": \"pan:DescribeChannelResponse\",\n    \"ListOriginEndpointsRequest\": \"pan:ListOriginEndpointsRequest\",\n    \"PresetSpeke20Audio\": \"pan:PresetSpeke20Audio\",\n    \"S3Destination\": \"pan:S3Destination\",\n    \"UpdateOriginEndpointRequest\": \"pan:UpdateOriginEndpointRequest\",\n    \"MssPackage\": \"pan:MssPackage\",\n    \"SegmentTemplateFormat\": \"pan:SegmentTemplateFormat\",\n    \"RotateIngestEndpointCredentialsRequest\": \"pan:RotateIngestEndpointCredentialsRequest\",\n    \"ConfigureLogsRequest\": \"pan:ConfigureLogsRequest\",\n    \"DashPackage\": \"pan:DashPackage\",\n    \"ManifestLayout\": \"pan:ManifestLayout\",\n    \"OriginEndpoint\": \"pan:OriginEndpoint\",\n    \"DeleteChannelRequest\": \"pan:DeleteChannelRequest\",\n    \"PlaylistType\": \"pan:PlaylistType\"\
  ,\n    \"EncryptionMethod\": \"pan:EncryptionMethod\",\n    \"RotateChannelCredentialsRequest\": \"pan:RotateChannelCredentialsRequest\",\n    \"UtcTiming\": \"pan:UtcTiming\",\n    \"PresetSpeke20Video\": \"pan:PresetSpeke20Video\",\n    \"RotateChannelCredentialsResponse\": \"pan:RotateChannelCredentialsResponse\",\n    \"Tags\": \"pan:Tags\",\n    \"DescribeOriginEndpointResponse\": \"pan:DescribeOriginEndpointResponse\",\n    \"HlsManifestCreateOrUpdateParameters\": \"pan:HlsManifestCreateOrUpdateParameters\",\n    \"Origination\": \"pan:Origination\",\n    \"HlsEncryption\": \"pan:HlsEncryption\",\n    \"EgressAccessLogs\": \"pan:EgressAccessLogs\",\n    \"ListHarvestJobsRequest\": \"pan:ListHarvestJobsRequest\",\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"description\": \"schema:description\",\n    \"egressAccessLogs\": {\n      \"@id\": \"pan:egress_access_logs\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"hlsIngest\": {\n      \"@id\": \"pan:hls_ingest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingressAccessLogs\": {\n      \"@id\": \"pan:ingress_access_logs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"pan:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"username\": {\n      \"@id\": \"pan:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adMarkers\": {\n      \"@id\": \"pan:ad_markers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adTriggers\": {\n      \"@id\": \"pan:ad_triggers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adsOnDeliveryRestrictions\": {\n      \"@id\": \"pan:ads_on_delivery_restrictions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryption\": {\n      \"@id\": \"pan:encryption\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"includeDvbSubtitles\": {\n      \"@id\": \"pan:include_dvb_subtitles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeIframeOnlyStream\": {\n      \"@id\": \"pan:include_iframe_only_stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playlistType\": {\n      \"@id\": \"pan:playlist_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"playlistWindowSeconds\": {\n      \"@id\": \"pan:playlist_window_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"programDateTimeIntervalSeconds\": {\n      \"@id\": \"pan:program_date_time_interval_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentDurationSeconds\": {\n      \"@id\": \"pan:segment_duration_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamSelection\": {\n      \"@id\": \"pan:stream_selection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useAudioRenditionGroup\": {\n      \"@id\": \"pan:use_audio_rendition_group\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"constantInitializationVector\": {\n      \"@id\": \"pan:constant_initialization_vector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionMethod\": {\n      \"@id\": \"pan:encryption_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyRotationIntervalSeconds\": {\n      \"@id\": \"pan:key_rotation_interval_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spekeKeyProvider\": {\n      \"@id\": \"pan:speke_key_provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestName\": {\n      \"@id\": \"pan:manifest_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cdnIdentifierSecret\": {\n      \"@id\": \"pan:cdn_identifier_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretsRoleArn\": {\n      \"@id\": \"pan:secrets_role_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"pan:channels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"channelId\": {\n      \"@id\": \"pan:channel_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originEndpointId\": {\n      \"@id\": \"pan:origin_endpoint_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Destination\": {\n      \"@id\": \"pan:s3_destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"pan:start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hlsManifests\": {\n      \"@id\": \"pan:hls_manifests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentPrefix\": {\n      \"@id\": \"pan:segment_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"certificateArn\": {\n      \"@id\": \"pan:certificate_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionContractConfiguration\"\
  : {\n      \"@id\": \"pan:encryption_contract_configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"pan:resource_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"pan:role_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemIds\": {\n      \"@id\": \"pan:system_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorization\": {\n      \"@id\": \"pan:authorization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cmafPackage\": {\n      \"@id\": \"pan:cmaf_package\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dashPackage\": {\n      \"@id\": \"pan:dash_package\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hlsPackage\": {\n      \"@id\": \"pan:hls_package\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mssPackage\": {\n      \"@id\": \"pan:mss_package\",\n      \"@type\": \"xsd:string\"\n    },\n    \"origination\": {\n      \"@id\": \"pan:origination\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"startoverWindowSeconds\": {\n      \"@id\": \"pan:startover_window_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeDelaySeconds\": {\n      \"@id\": \"pan:time_delay_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"whitelist\": {\n      \"@id\": \"pan:whitelist\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxVideoBitsPerSecond\": {\n      \"@id\": \"pan:max_video_bits_per_second\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minVideoBitsPerSecond\": {\n      \"@id\": \"pan:min_video_bits_per_second\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamOrder\": {\n      \"@id\": \"pan:stream_order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logGroupName\": {\n      \"@id\": \"pan:log_group_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingestEndpoints\": {\n      \"@id\": \"pan:ingest_endpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"originEndpoints\": {\n      \"@id\": \"pan:origin_endpoints\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"harvestJobs\": {\n      \"@id\": \"pan:harvest_jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"presetSpeke20Audio\": {\n      \"@id\": \"pan:preset_speke20_audio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"presetSpeke20Video\": {\n      \"@id\": \"pan:preset_speke20_video\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketName\": {\n      \"@id\": \"pan:bucket_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestKey\": {\n      \"@id\": \"pan:manifest_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestWindowSeconds\": {\n      \"@id\": \"pan:manifest_window_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"manifestLayout\": {\n      \"@id\": \"pan:manifest_layout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minBufferTimeSeconds\": {\n      \"@id\": \"pan:min_buffer_time_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minUpdatePeriodSeconds\": {\n      \"@id\": \"pan:min_update_period_seconds\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"periodTriggers\": {\n      \"@id\": \"pan:period_triggers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"pan:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentTemplateFormat\": {\n      \"@id\": \"pan:segment_template_format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedPresentationDelaySeconds\": {\n      \"@id\": \"pan:suggested_presentation_delay_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utcTiming\": {\n      \"@id\": \"pan:utc_timing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"utcTimingUri\": {\n      \"@id\": \"pan:utc_timing_uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repeatExtXKey\": {\n      \"@id\": \"pan:repeat_ext_x_key\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mediapackage/refs/heads/main/json-ld/amazon-mediapackage-mediapackage-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
