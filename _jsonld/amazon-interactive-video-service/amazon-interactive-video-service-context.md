---
api_specs:
- filename: amazon-ivs-openapi-original.yml
  format: yaml
  label: AWS Amazon IVS API
  slug: aws-ivs-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-interactive-video-service/refs/heads/main/openapi/amazon-ivs-openapi-original.yml
class_count: 82
classes:
- AudioConfiguration
- BatchError
- BatchGetChannelRequest
- BatchGetChannelResponse
- BatchGetStreamKeyRequest
- BatchGetStreamKeyResponse
- BatchStartViewerSessionRevocationError
- BatchStartViewerSessionRevocationRequest
- BatchStartViewerSessionRevocationResponse
- BatchStartViewerSessionRevocationViewerSession
- Channel
- ChannelSummary
- CreateChannelRequest
- CreateChannelResponse
- CreateRecordingConfigurationRequest
- CreateRecordingConfigurationResponse
- CreateStreamKeyRequest
- CreateStreamKeyResponse
- DeleteChannelRequest
- DeletePlaybackKeyPairRequest
- DeletePlaybackKeyPairResponse
- DeleteRecordingConfigurationRequest
- DeleteStreamKeyRequest
- DestinationConfiguration
- GetChannelRequest
- GetChannelResponse
- GetPlaybackKeyPairRequest
- GetPlaybackKeyPairResponse
- GetRecordingConfigurationRequest
- GetRecordingConfigurationResponse
- GetStreamKeyRequest
- GetStreamKeyResponse
- GetStreamRequest
- GetStreamResponse
- GetStreamSessionRequest
- GetStreamSessionResponse
- ImportPlaybackKeyPairRequest
- ImportPlaybackKeyPairResponse
- IngestConfiguration
- ListChannelsRequest
- ListChannelsResponse
- ListPlaybackKeyPairsRequest
- ListPlaybackKeyPairsResponse
- ListRecordingConfigurationsRequest
- ListRecordingConfigurationsResponse
- ListStreamKeysRequest
- ListStreamKeysResponse
- ListStreamSessionsRequest
- ListStreamSessionsResponse
- ListStreamsRequest
- ListStreamsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- PlaybackKeyPair
- PlaybackKeyPairSummary
- PutMetadataRequest
- RecordingConfiguration
- RecordingConfigurationSummary
- RenditionConfiguration
- S3DestinationConfiguration
- StartViewerSessionRevocationRequest
- StartViewerSessionRevocationResponse
- StopStreamRequest
- StopStreamResponse
- Stream
- StreamEvent
- StreamFilters
- StreamKey
- StreamKeySummary
- StreamSession
- StreamSessionSummary
- StreamSummary
- TagResourceRequest
- TagResourceResponse
- Tags
- ThumbnailConfiguration
- UntagResourceRequest
- UntagResourceResponse
- UpdateChannelRequest
- UpdateChannelResponse
- VideoConfiguration
- name
context_file: json-ld/amazon-interactive-video-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-interactive-video-service/refs/heads/main/json-ld/amazon-interactive-video-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Interactive Video Service from Amazon Interactive Video Service.
layout: jsonld
name: Amazon Interactive Video Service Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/
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
  name: arns
  type: string
- container: ''
  name: audio
  type: string
- container: ''
  name: authorized
  type: string
- container: ''
  name: avcLevel
  type: string
- container: ''
  name: avcProfile
  type: string
- container: ''
  name: bucketName
  type: string
- container: ''
  name: channel
  type: string
- container: ''
  name: channelArn
  type: string
- container: ''
  name: channels
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: codec
  type: string
- container: ''
  name: destinationConfiguration
  type: string
- container: ''
  name: encoder
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: eventTime
  type: string
- container: ''
  name: filterBy
  type: string
- container: ''
  name: filterByName
  type: string
- container: ''
  name: filterByRecordingConfigurationArn
  type: string
- container: ''
  name: fingerprint
  type: string
- container: ''
  name: hasErrorEvent
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: ingestConfiguration
  type: string
- container: ''
  name: ingestEndpoint
  type: string
- container: ''
  name: insecureIngest
  type: string
- container: ''
  name: keyPair
  type: string
- container: ''
  name: keyPairs
  type: string
- container: ''
  name: latencyMode
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: playbackUrl
  type: string
- container: ''
  name: preset
  type: string
- container: ''
  name: publicKeyMaterial
  type: string
- container: ''
  name: recordingConfiguration
  type: string
- container: ''
  name: recordingConfigurationArn
  type: string
- container: ''
  name: recordingConfigurations
  type: string
- container: ''
  name: recordingMode
  type: string
- container: ''
  name: recordingReconnectWindowSeconds
  type: string
- container: ''
  name: renditionConfiguration
  type: string
- container: ''
  name: renditionSelection
  type: string
- container: ''
  name: renditions
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: sampleRate
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: storage
  type: string
- container: ''
  name: stream
  type: string
- container: ''
  name: streamId
  type: string
- container: ''
  name: streamKey
  type: string
- container: ''
  name: streamKeys
  type: string
- container: ''
  name: streamSession
  type: string
- container: ''
  name: streamSessions
  type: string
- container: ''
  name: streams
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetBitrate
  type: string
- container: ''
  name: targetFramerate
  type: string
- container: ''
  name: targetIntervalSeconds
  type: string
- container: ''
  name: thumbnailConfiguration
  type: string
- container: ''
  name: truncatedEvents
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: video
  type: string
- container: ''
  name: videoHeight
  type: string
- container: ''
  name: videoWidth
  type: string
- container: ''
  name: viewerCount
  type: string
- container: ''
  name: viewerId
  type: string
- container: ''
  name: viewerSessionVersionsLessThanOrEqualTo
  type: string
- container: ''
  name: viewerSessions
  type: string
property_count: 72
provider_name: Amazon Interactive Video Service
provider_slug: amazon-interactive-video-service
slug: amazon-interactive-video-service-context
source_filename: amazon-interactive-video-service-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AudioConfiguration\": \"amzn:AudioConfiguration\",\n    \"BatchError\": \"amzn:BatchError\",\n    \"BatchGetChannelRequest\": \"amzn:BatchGetChannelRequest\",\n    \"BatchGetChannelResponse\": \"amzn:BatchGetChannelResponse\",\n    \"BatchGetStreamKeyRequest\": \"amzn:BatchGetStreamKeyRequest\",\n    \"BatchGetStreamKeyResponse\": \"amzn:BatchGetStreamKeyResponse\",\n    \"BatchStartViewerSessionRevocationError\": \"amzn:BatchStartViewerSessionRevocationError\",\n    \"BatchStartViewerSessionRevocationRequest\": \"amzn:BatchStartViewerSessionRevocationRequest\",\n    \"BatchStartViewerSessionRevocationResponse\": \"amzn:BatchStartViewerSessionRevocationResponse\",\n    \"BatchStartViewerSessionRevocationViewerSession\": \"amzn:BatchStartViewerSessionRevocationViewerSession\"\
  ,\n    \"Channel\": \"amzn:Channel\",\n    \"ChannelSummary\": \"amzn:ChannelSummary\",\n    \"CreateChannelRequest\": \"amzn:CreateChannelRequest\",\n    \"CreateChannelResponse\": \"amzn:CreateChannelResponse\",\n    \"CreateRecordingConfigurationRequest\": \"amzn:CreateRecordingConfigurationRequest\",\n    \"CreateRecordingConfigurationResponse\": \"amzn:CreateRecordingConfigurationResponse\",\n    \"CreateStreamKeyRequest\": \"amzn:CreateStreamKeyRequest\",\n    \"CreateStreamKeyResponse\": \"amzn:CreateStreamKeyResponse\",\n    \"DeleteChannelRequest\": \"amzn:DeleteChannelRequest\",\n    \"DeletePlaybackKeyPairRequest\": \"amzn:DeletePlaybackKeyPairRequest\",\n    \"DeletePlaybackKeyPairResponse\": \"amzn:DeletePlaybackKeyPairResponse\",\n    \"DeleteRecordingConfigurationRequest\": \"amzn:DeleteRecordingConfigurationRequest\",\n    \"DeleteStreamKeyRequest\": \"amzn:DeleteStreamKeyRequest\",\n    \"DestinationConfiguration\": \"amzn:DestinationConfiguration\",\n    \"GetChannelRequest\"\
  : \"amzn:GetChannelRequest\",\n    \"GetChannelResponse\": \"amzn:GetChannelResponse\",\n    \"GetPlaybackKeyPairRequest\": \"amzn:GetPlaybackKeyPairRequest\",\n    \"GetPlaybackKeyPairResponse\": \"amzn:GetPlaybackKeyPairResponse\",\n    \"GetRecordingConfigurationRequest\": \"amzn:GetRecordingConfigurationRequest\",\n    \"GetRecordingConfigurationResponse\": \"amzn:GetRecordingConfigurationResponse\",\n    \"GetStreamKeyRequest\": \"amzn:GetStreamKeyRequest\",\n    \"GetStreamKeyResponse\": \"amzn:GetStreamKeyResponse\",\n    \"GetStreamRequest\": \"amzn:GetStreamRequest\",\n    \"GetStreamResponse\": \"amzn:GetStreamResponse\",\n    \"GetStreamSessionRequest\": \"amzn:GetStreamSessionRequest\",\n    \"GetStreamSessionResponse\": \"amzn:GetStreamSessionResponse\",\n    \"ImportPlaybackKeyPairRequest\": \"amzn:ImportPlaybackKeyPairRequest\",\n    \"ImportPlaybackKeyPairResponse\": \"amzn:ImportPlaybackKeyPairResponse\",\n    \"IngestConfiguration\": \"amzn:IngestConfiguration\",\n  \
  \  \"ListChannelsRequest\": \"amzn:ListChannelsRequest\",\n    \"ListChannelsResponse\": \"amzn:ListChannelsResponse\",\n    \"ListPlaybackKeyPairsRequest\": \"amzn:ListPlaybackKeyPairsRequest\",\n    \"ListPlaybackKeyPairsResponse\": \"amzn:ListPlaybackKeyPairsResponse\",\n    \"ListRecordingConfigurationsRequest\": \"amzn:ListRecordingConfigurationsRequest\",\n    \"ListRecordingConfigurationsResponse\": \"amzn:ListRecordingConfigurationsResponse\",\n    \"ListStreamKeysRequest\": \"amzn:ListStreamKeysRequest\",\n    \"ListStreamKeysResponse\": \"amzn:ListStreamKeysResponse\",\n    \"ListStreamSessionsRequest\": \"amzn:ListStreamSessionsRequest\",\n    \"ListStreamSessionsResponse\": \"amzn:ListStreamSessionsResponse\",\n    \"ListStreamsRequest\": \"amzn:ListStreamsRequest\",\n    \"ListStreamsResponse\": \"amzn:ListStreamsResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n\
  \    \"PlaybackKeyPair\": \"amzn:PlaybackKeyPair\",\n    \"PlaybackKeyPairSummary\": \"amzn:PlaybackKeyPairSummary\",\n    \"PutMetadataRequest\": \"amzn:PutMetadataRequest\",\n    \"RecordingConfiguration\": \"amzn:RecordingConfiguration\",\n    \"RecordingConfigurationSummary\": \"amzn:RecordingConfigurationSummary\",\n    \"RenditionConfiguration\": \"amzn:RenditionConfiguration\",\n    \"S3DestinationConfiguration\": \"amzn:S3DestinationConfiguration\",\n    \"StartViewerSessionRevocationRequest\": \"amzn:StartViewerSessionRevocationRequest\",\n    \"StartViewerSessionRevocationResponse\": \"amzn:StartViewerSessionRevocationResponse\",\n    \"StopStreamRequest\": \"amzn:StopStreamRequest\",\n    \"StopStreamResponse\": \"amzn:StopStreamResponse\",\n    \"Stream\": \"amzn:Stream\",\n    \"StreamEvent\": \"amzn:StreamEvent\",\n    \"StreamFilters\": \"amzn:StreamFilters\",\n    \"StreamKey\": \"amzn:StreamKey\",\n    \"StreamKeySummary\": \"amzn:StreamKeySummary\",\n    \"StreamSession\"\
  : \"amzn:StreamSession\",\n    \"StreamSessionSummary\": \"amzn:StreamSessionSummary\",\n    \"StreamSummary\": \"amzn:StreamSummary\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"TagResourceResponse\": \"amzn:TagResourceResponse\",\n    \"Tags\": \"amzn:Tags\",\n    \"ThumbnailConfiguration\": \"amzn:ThumbnailConfiguration\",\n    \"UntagResourceRequest\": \"amzn:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amzn:UntagResourceResponse\",\n    \"UpdateChannelRequest\": \"amzn:UpdateChannelRequest\",\n    \"UpdateChannelResponse\": \"amzn:UpdateChannelResponse\",\n    \"VideoConfiguration\": \"amzn:VideoConfiguration\",\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arns\": {\n      \"@id\": \"amzn:arns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"audio\": {\n      \"@id\": \"amzn:audio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"authorized\": {\n      \"@id\": \"amzn:authorized\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"avcLevel\": {\n      \"@id\": \"amzn:avcLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"avcProfile\": {\n      \"@id\": \"amzn:avcProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketName\": {\n      \"@id\": \"amzn:bucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channel\": {\n      \"@id\": \"amzn:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channelArn\": {\n      \"@id\": \"amzn:channelArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"amzn:channels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amzn:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codec\": {\n      \"@id\": \"amzn:codec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationConfiguration\": {\n      \"@id\": \"amzn:destinationConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encoder\": {\n      \"@id\": \"amzn:encoder\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amzn:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTime\": {\n      \"@id\": \"amzn:eventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterBy\": {\n      \"@id\": \"amzn:filterBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterByName\": {\n      \"@id\": \"amzn:filterByName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterByRecordingConfigurationArn\": {\n      \"@id\": \"amzn:filterByRecordingConfigurationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fingerprint\": {\n      \"@id\": \"amzn:fingerprint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasErrorEvent\": {\n      \"@id\": \"amzn:hasErrorEvent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"health\": {\n      \"@id\": \"amzn:health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingestConfiguration\": {\n      \"\
  @id\": \"amzn:ingestConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ingestEndpoint\": {\n      \"@id\": \"amzn:ingestEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insecureIngest\": {\n      \"@id\": \"amzn:insecureIngest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPair\": {\n      \"@id\": \"amzn:keyPair\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPairs\": {\n      \"@id\": \"amzn:keyPairs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latencyMode\": {\n      \"@id\": \"amzn:latencyMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amzn:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"playbackUrl\": {\n      \"@id\": \"amzn:playbackUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preset\": {\n      \"@id\": \"amzn:preset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicKeyMaterial\": {\n      \"@id\": \"amzn:publicKeyMaterial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingConfiguration\": {\n      \"@id\": \"amzn:recordingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingConfigurationArn\": {\n      \"@id\": \"amzn:recordingConfigurationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingConfigurations\": {\n      \"@id\": \"amzn:recordingConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingMode\": {\n      \"@id\": \"amzn:recordingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordingReconnectWindowSeconds\": {\n      \"@id\": \"amzn:recordingReconnectWindowSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renditionConfiguration\": {\n      \"@id\"\
  : \"amzn:renditionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renditionSelection\": {\n      \"@id\": \"amzn:renditionSelection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"renditions\": {\n      \"@id\": \"amzn:renditions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"amzn:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"amzn:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sampleRate\": {\n      \"@id\": \"amzn:sampleRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amzn:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storage\": {\n      \"@id\": \"amzn:storage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stream\": {\n      \"@id\": \"amzn:stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamId\": {\n      \"@id\": \"amzn:streamId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"streamKey\": {\n      \"@id\": \"amzn:streamKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamKeys\": {\n      \"@id\": \"amzn:streamKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamSession\": {\n      \"@id\": \"amzn:streamSession\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamSessions\": {\n      \"@id\": \"amzn:streamSessions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streams\": {\n      \"@id\": \"amzn:streams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetBitrate\": {\n      \"@id\": \"amzn:targetBitrate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetFramerate\": {\n      \"@id\": \"amzn:targetFramerate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetIntervalSeconds\": {\n      \"@id\": \"amzn:targetIntervalSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thumbnailConfiguration\"\
  : {\n      \"@id\": \"amzn:thumbnailConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"truncatedEvents\": {\n      \"@id\": \"amzn:truncatedEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"video\": {\n      \"@id\": \"amzn:video\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoHeight\": {\n      \"@id\": \"amzn:videoHeight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"videoWidth\": {\n      \"@id\": \"amzn:videoWidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewerCount\": {\n      \"@id\": \"amzn:viewerCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewerId\": {\n      \"@id\": \"amzn:viewerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewerSessionVersionsLessThanOrEqualTo\": {\n      \"@id\": \"amzn:viewerSessionVersionsLessThanOrEqualTo\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"viewerSessions\": {\n      \"@id\": \"amzn:viewerSessions\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-interactive-video-service/refs/heads/main/json-ld/amazon-interactive-video-service-context.jsonld
tags:
- AWS
- Live Streaming
- Media
- Video
- Real-Time
- JSON-LD
- Linked Data
- Semantic Web
---
