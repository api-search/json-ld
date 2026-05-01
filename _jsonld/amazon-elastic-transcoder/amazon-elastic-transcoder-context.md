---
api_specs:
- filename: amazon-elastic-transcoder-openapi.yml
  format: yaml
  label: Amazon Elastic Transcoder API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-transcoder/refs/heads/main/openapi/amazon-elastic-transcoder-openapi.yml
class_count: 67
classes:
- Artwork
- Encryption
- AudioCodecOptions
- AudioParameters
- CodecOptions
- CancelJobRequest
- CancelJobResponse
- CaptionFormat
- CaptionSource
- Captions
- Clip
- TimeSpan
- CreateJobOutput
- CreateJobPlaylist
- HlsContentProtection
- PlayReadyDrm
- CreateJobRequest
- UserMetadata
- CreateJobResponse
- Job
- CreatePipelineRequest
- Notifications
- CreatePipelineResponse
- Pipeline
- CreatePresetRequest
- Thumbnails
- CreatePresetResponse
- Preset
- Warning
- DeletePipelineRequest
- DeletePipelineResponse
- DeletePresetRequest
- DeletePresetResponse
- DetectedProperties
- InputCaptions
- JobAlbumArt
- JobInput
- JobOutput
- Timing
- JobWatermark
- ListJobsByPipelineRequest
- ListJobsByPipelineResponse
- ListJobsByStatusRequest
- ListJobsByStatusResponse
- ListPipelinesRequest
- ListPipelinesResponse
- ListPresetsRequest
- ListPresetsResponse
- Permission
- PipelineOutputConfig
- Playlist
- PresetWatermark
- ReadJobRequest
- ReadJobResponse
- ReadPipelineRequest
- ReadPipelineResponse
- ReadPresetRequest
- ReadPresetResponse
- TestRoleRequest
- TestRoleResponse
- UpdatePipelineNotificationsRequest
- UpdatePipelineNotificationsResponse
- UpdatePipelineRequest
- UpdatePipelineResponse
- UpdatePipelineStatusRequest
- UpdatePipelineStatusResponse
- VideoParameters
context_file: json-ld/amazon-elastic-transcoder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-transcoder/refs/heads/main/json-ld/amazon-elastic-transcoder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Elastic Transcoder from Amazon Elastic Transcoder.
layout: jsonld
name: Amazon Elastic Transcoder Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: InputKey
  type: string
- container: ''
  name: MaxWidth
  type: string
- container: ''
  name: MaxHeight
  type: string
- container: ''
  name: SizingPolicy
  type: string
- container: ''
  name: PaddingPolicy
  type: string
- container: ''
  name: AlbumArtFormat
  type: string
- container: ''
  name: Profile
  type: string
- container: ''
  name: BitDepth
  type: string
- container: ''
  name: BitOrder
  type: string
- container: ''
  name: Signed
  type: string
- container: ''
  name: Codec
  type: string
- container: ''
  name: SampleRate
  type: string
- container: ''
  name: BitRate
  type: string
- container: ''
  name: Channels
  type: string
- container: ''
  name: AudioPackingMode
  type: string
- container: ''
  name: Format
  type: string
- container: ''
  name: Pattern
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Language
  type: string
- container: ''
  name: TimeOffset
  type: string
- container: ''
  name: Label
  type: string
- container: ''
  name: MergePolicy
  type: string
- container: ''
  name: CaptionSources
  type: string
- container: ''
  name: CaptionFormats
  type: string
- container: ''
  name: ThumbnailPattern
  type: string
- container: ''
  name: ThumbnailEncryption
  type: string
- container: ''
  name: Rotate
  type: string
- container: ''
  name: PresetId
  type: string
- container: ''
  name: SegmentDuration
  type: string
- container: ''
  name: Watermarks
  type: string
- container: ''
  name: AlbumArt
  type: string
- container: ''
  name: Composition
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: OutputKeys
  type: string
- container: ''
  name: PipelineId
  type: string
- container: ''
  name: Input
  type: string
- container: ''
  name: Inputs
  type: string
- container: ''
  name: Output
  type: string
- container: ''
  name: Outputs
  type: string
- container: ''
  name: OutputKeyPrefix
  type: string
- container: ''
  name: Playlists
  type: string
- container: ''
  name: InputBucket
  type: string
- container: ''
  name: OutputBucket
  type: string
- container: ''
  name: Role
  type: string
- container: ''
  name: AwsKmsKeyArn
  type: string
- container: ''
  name: ContentConfig
  type: string
- container: ''
  name: ThumbnailConfig
  type: string
- container: ''
  name: Warnings
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Container
  type: string
- container: ''
  name: Video
  type: string
- container: ''
  name: Audio
  type: string
- container: ''
  name: Width
  type: string
- container: ''
  name: Height
  type: string
- container: ''
  name: FrameRate
  type: string
- container: ''
  name: FileSize
  type: string
- container: ''
  name: DurationMillis
  type: string
- container: ''
  name: Mode
  type: string
- container: ''
  name: KeyMd5
  type: string
- container: ''
  name: InitializationVector
  type: string
- container: ''
  name: Method
  type: string
- container: ''
  name: LicenseAcquisitionUrl
  type: string
- container: ''
  name: KeyStoragePolicy
  type: string
- container: ''
  name: Resolution
  type: string
- container: ''
  name: AspectRatio
  type: string
- container: ''
  name: Interlaced
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: StatusDetail
  type: string
- container: ''
  name: Duration
  type: string
- container: ''
  name: AppliedColorSpaceConversion
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: PresetWatermarkId
  type: string
- container: ''
  name: Jobs
  type: string
- container: ''
  name: NextPageToken
  type: string
- container: ''
  name: Pipelines
  type: string
- container: ''
  name: Presets
  type: string
- container: ''
  name: Progressing
  type: string
- container: ''
  name: Completed
  type: string
- container: ''
  name: Error
  type: string
- container: ''
  name: GranteeType
  type: string
- container: ''
  name: Grantee
  type: string
- container: ''
  name: Access
  type: string
- container: ''
  name: Bucket
  type: string
- container: ''
  name: StorageClass
  type: string
- container: ''
  name: Permissions
  type: string
- container: ''
  name: KeyId
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: HorizontalAlign
  type: string
- container: ''
  name: HorizontalOffset
  type: string
- container: ''
  name: VerticalAlign
  type: string
- container: ''
  name: VerticalOffset
  type: string
- container: ''
  name: Opacity
  type: string
- container: ''
  name: Target
  type: string
- container: ''
  name: Topics
  type: string
- container: ''
  name: Success
  type: string
- container: ''
  name: Messages
  type: string
- container: ''
  name: Interval
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: SubmitTimeMillis
  type: string
- container: ''
  name: StartTimeMillis
  type: string
- container: ''
  name: FinishTimeMillis
  type: string
- container: ''
  name: KeyframesMaxDist
  type: string
- container: ''
  name: FixedGOP
  type: string
- container: ''
  name: MaxFrameRate
  type: string
- container: ''
  name: DisplayAspectRatio
  type: string
- container: ''
  name: Code
  type: string
- container: ''
  name: Message
  type: string
property_count: 108
provider_name: Amazon Elastic Transcoder
provider_slug: amazon-elastic-transcoder
slug: amazon-elastic-transcoder-context
source_filename: amazon-elastic-transcoder-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Artwork\": \"aws:Artwork\",\n    \"InputKey\": {\n      \"@id\": \"aws:InputKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxWidth\": {\n      \"@id\": \"aws:MaxWidth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxHeight\": {\n      \"@id\": \"aws:MaxHeight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SizingPolicy\": {\n      \"@id\": \"aws:SizingPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PaddingPolicy\": {\n      \"@id\": \"aws:PaddingPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlbumArtFormat\": {\n      \"@id\": \"aws:AlbumArtFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Encryption\": \"aws:Encryption\",\n    \"AudioCodecOptions\": \"aws:AudioCodecOptions\",\n    \"Profile\"\
  : {\n      \"@id\": \"aws:Profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BitDepth\": {\n      \"@id\": \"aws:BitDepth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BitOrder\": {\n      \"@id\": \"aws:BitOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Signed\": {\n      \"@id\": \"aws:Signed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AudioParameters\": \"aws:AudioParameters\",\n    \"Codec\": {\n      \"@id\": \"aws:Codec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SampleRate\": {\n      \"@id\": \"aws:SampleRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BitRate\": {\n      \"@id\": \"aws:BitRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Channels\": {\n      \"@id\": \"aws:Channels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AudioPackingMode\": {\n      \"@id\": \"aws:AudioPackingMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodecOptions\": \"aws:CodecOptions\",\n    \"CancelJobRequest\": \"aws:CancelJobRequest\"\
  ,\n    \"CancelJobResponse\": \"aws:CancelJobResponse\",\n    \"CaptionFormat\": \"aws:CaptionFormat\",\n    \"Format\": {\n      \"@id\": \"aws:Format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pattern\": {\n      \"@id\": \"aws:Pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CaptionSource\": \"aws:CaptionSource\",\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Language\": {\n      \"@id\": \"aws:Language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeOffset\": {\n      \"@id\": \"aws:TimeOffset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Label\": {\n      \"@id\": \"aws:Label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Captions\": \"aws:Captions\",\n    \"MergePolicy\": {\n      \"@id\": \"aws:MergePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CaptionSources\": {\n      \"@id\": \"aws:CaptionSources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CaptionFormats\": {\n      \"@id\": \"\
  aws:CaptionFormats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Clip\": \"aws:Clip\",\n    \"TimeSpan\": \"aws:TimeSpan\",\n    \"CreateJobOutput\": \"aws:CreateJobOutput\",\n    \"ThumbnailPattern\": {\n      \"@id\": \"aws:ThumbnailPattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThumbnailEncryption\": {\n      \"@id\": \"aws:ThumbnailEncryption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rotate\": {\n      \"@id\": \"aws:Rotate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PresetId\": {\n      \"@id\": \"aws:PresetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentDuration\": {\n      \"@id\": \"aws:SegmentDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Watermarks\": {\n      \"@id\": \"aws:Watermarks\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlbumArt\": {\n      \"@id\": \"aws:AlbumArt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Composition\": {\n      \"@id\": \"aws:Composition\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"CreateJobPlaylist\": \"aws:CreateJobPlaylist\",\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputKeys\": {\n      \"@id\": \"aws:OutputKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HlsContentProtection\": \"aws:HlsContentProtection\",\n    \"PlayReadyDrm\": \"aws:PlayReadyDrm\",\n    \"CreateJobRequest\": \"aws:CreateJobRequest\",\n    \"PipelineId\": {\n      \"@id\": \"aws:PipelineId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Input\": {\n      \"@id\": \"aws:Input\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Inputs\": {\n      \"@id\": \"aws:Inputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Output\": {\n      \"@id\": \"aws:Output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Outputs\": {\n      \"@id\": \"aws:Outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputKeyPrefix\": {\n      \"@id\": \"aws:OutputKeyPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Playlists\"\
  : {\n      \"@id\": \"aws:Playlists\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserMetadata\": \"aws:UserMetadata\",\n    \"CreateJobResponse\": \"aws:CreateJobResponse\",\n    \"Job\": \"aws:Job\",\n    \"CreatePipelineRequest\": \"aws:CreatePipelineRequest\",\n    \"InputBucket\": {\n      \"@id\": \"aws:InputBucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputBucket\": {\n      \"@id\": \"aws:OutputBucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Role\": {\n      \"@id\": \"aws:Role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AwsKmsKeyArn\": {\n      \"@id\": \"aws:AwsKmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Notifications\": \"aws:Notifications\",\n    \"ContentConfig\": {\n      \"@id\": \"aws:ContentConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ThumbnailConfig\": {\n      \"@id\": \"aws:ThumbnailConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatePipelineResponse\": \"aws:CreatePipelineResponse\",\n  \
  \  \"Pipeline\": \"aws:Pipeline\",\n    \"Warnings\": {\n      \"@id\": \"aws:Warnings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatePresetRequest\": \"aws:CreatePresetRequest\",\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Container\": {\n      \"@id\": \"aws:Container\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Video\": {\n      \"@id\": \"aws:Video\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Audio\": {\n      \"@id\": \"aws:Audio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Thumbnails\": \"aws:Thumbnails\",\n    \"CreatePresetResponse\": \"aws:CreatePresetResponse\",\n    \"Preset\": \"aws:Preset\",\n    \"Warning\": \"aws:Warning\",\n    \"DeletePipelineRequest\": \"aws:DeletePipelineRequest\",\n    \"DeletePipelineResponse\": \"aws:DeletePipelineResponse\",\n    \"DeletePresetRequest\": \"aws:DeletePresetRequest\",\n    \"DeletePresetResponse\": \"aws:DeletePresetResponse\",\n    \"DetectedProperties\"\
  : \"aws:DetectedProperties\",\n    \"Width\": {\n      \"@id\": \"aws:Width\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Height\": {\n      \"@id\": \"aws:Height\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FrameRate\": {\n      \"@id\": \"aws:FrameRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FileSize\": {\n      \"@id\": \"aws:FileSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DurationMillis\": {\n      \"@id\": \"aws:DurationMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Mode\": {\n      \"@id\": \"aws:Mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyMd5\": {\n      \"@id\": \"aws:KeyMd5\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InitializationVector\": {\n      \"@id\": \"aws:InitializationVector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Method\": {\n      \"@id\": \"aws:Method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LicenseAcquisitionUrl\": {\n      \"@id\": \"aws:LicenseAcquisitionUrl\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"KeyStoragePolicy\": {\n      \"@id\": \"aws:KeyStoragePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputCaptions\": \"aws:InputCaptions\",\n    \"JobAlbumArt\": \"aws:JobAlbumArt\",\n    \"JobInput\": \"aws:JobInput\",\n    \"Resolution\": {\n      \"@id\": \"aws:Resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AspectRatio\": {\n      \"@id\": \"aws:AspectRatio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Interlaced\": {\n      \"@id\": \"aws:Interlaced\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobOutput\": \"aws:JobOutput\",\n    \"Id\": {\n      \"@id\": \"aws:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusDetail\": {\n      \"@id\": \"aws:StatusDetail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Duration\": {\n      \"@id\": \"aws:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppliedColorSpaceConversion\"\
  : {\n      \"@id\": \"aws:AppliedColorSpaceConversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timing\": \"aws:Timing\",\n    \"JobWatermark\": \"aws:JobWatermark\",\n    \"PresetWatermarkId\": {\n      \"@id\": \"aws:PresetWatermarkId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListJobsByPipelineRequest\": \"aws:ListJobsByPipelineRequest\",\n    \"ListJobsByPipelineResponse\": \"aws:ListJobsByPipelineResponse\",\n    \"Jobs\": {\n      \"@id\": \"aws:Jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextPageToken\": {\n      \"@id\": \"aws:NextPageToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListJobsByStatusRequest\": \"aws:ListJobsByStatusRequest\",\n    \"ListJobsByStatusResponse\": \"aws:ListJobsByStatusResponse\",\n    \"ListPipelinesRequest\": \"aws:ListPipelinesRequest\",\n    \"ListPipelinesResponse\": \"aws:ListPipelinesResponse\",\n    \"Pipelines\": {\n  \
  \    \"@id\": \"aws:Pipelines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListPresetsRequest\": \"aws:ListPresetsRequest\",\n    \"ListPresetsResponse\": \"aws:ListPresetsResponse\",\n    \"Presets\": {\n      \"@id\": \"aws:Presets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Progressing\": {\n      \"@id\": \"aws:Progressing\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Completed\": {\n      \"@id\": \"aws:Completed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Error\": {\n      \"@id\": \"aws:Error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Permission\": \"aws:Permission\",\n    \"GranteeType\": {\n      \"@id\": \"aws:GranteeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Grantee\": {\n      \"@id\": \"aws:Grantee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Access\": {\n      \"@id\": \"aws:Access\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipelineOutputConfig\": \"aws:PipelineOutputConfig\",\n    \"Bucket\": {\n      \"@id\": \"\
  aws:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageClass\": {\n      \"@id\": \"aws:StorageClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Permissions\": {\n      \"@id\": \"aws:Permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyId\": {\n      \"@id\": \"aws:KeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Playlist\": \"aws:Playlist\",\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PresetWatermark\": \"aws:PresetWatermark\",\n    \"HorizontalAlign\": {\n      \"@id\": \"aws:HorizontalAlign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HorizontalOffset\": {\n      \"@id\": \"aws:HorizontalOffset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VerticalAlign\": {\n      \"@id\": \"aws:VerticalAlign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VerticalOffset\": {\n      \"@id\": \"aws:VerticalOffset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Opacity\": {\n      \"@id\": \"\
  aws:Opacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Target\": {\n      \"@id\": \"aws:Target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReadJobRequest\": \"aws:ReadJobRequest\",\n    \"ReadJobResponse\": \"aws:ReadJobResponse\",\n    \"ReadPipelineRequest\": \"aws:ReadPipelineRequest\",\n    \"ReadPipelineResponse\": \"aws:ReadPipelineResponse\",\n    \"ReadPresetRequest\": \"aws:ReadPresetRequest\",\n    \"ReadPresetResponse\": \"aws:ReadPresetResponse\",\n    \"TestRoleRequest\": \"aws:TestRoleRequest\",\n    \"Topics\": {\n      \"@id\": \"aws:Topics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TestRoleResponse\": \"aws:TestRoleResponse\",\n    \"Success\": {\n      \"@id\": \"aws:Success\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Messages\": {\n      \"@id\": \"aws:Messages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Interval\": {\n      \"@id\": \"aws:Interval\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\":\
  \ \"aws:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubmitTimeMillis\": {\n      \"@id\": \"aws:SubmitTimeMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTimeMillis\": {\n      \"@id\": \"aws:StartTimeMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FinishTimeMillis\": {\n      \"@id\": \"aws:FinishTimeMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatePipelineNotificationsRequest\": \"aws:UpdatePipelineNotificationsRequest\",\n    \"UpdatePipelineNotificationsResponse\": \"aws:UpdatePipelineNotificationsResponse\",\n    \"UpdatePipelineRequest\": \"aws:UpdatePipelineRequest\",\n    \"UpdatePipelineResponse\": \"aws:UpdatePipelineResponse\",\n    \"UpdatePipelineStatusRequest\": \"aws:UpdatePipelineStatusRequest\",\n    \"UpdatePipelineStatusResponse\": \"aws:UpdatePipelineStatusResponse\",\n    \"VideoParameters\": \"aws:VideoParameters\",\n    \"KeyframesMaxDist\": {\n      \"@id\": \"aws:KeyframesMaxDist\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"FixedGOP\": {\n      \"@id\": \"aws:FixedGOP\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxFrameRate\": {\n      \"@id\": \"aws:MaxFrameRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayAspectRatio\": {\n      \"@id\": \"aws:DisplayAspectRatio\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Code\": {\n      \"@id\": \"aws:Code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": {\n      \"@id\": \"aws:Message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-elastic-transcoder/refs/heads/main/json-ld/amazon-elastic-transcoder-context.jsonld
tags:
- Amazon Web Services
- Media
- Transcoding
- Video
- JSON-LD
- Linked Data
- Semantic Web
---
