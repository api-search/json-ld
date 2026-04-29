---
api_specs:
- filename: amazon-rekognition-openapi.yml
  format: yaml
  label: Amazon Rekognition
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-rekognition/refs/heads/main/openapi/amazon-rekognition-openapi.yml
class_count: 30
classes:
- CompareFacesResponse
- DetectLabelsResponse
- DetectModerationLabelsRequest
- ListCollectionsResponse
- CreateFaceLivenessSessionRequest
- DetectModerationLabelsResponse
- DetectTextResponse
- IndexFacesResponse
- GetFaceLivenessSessionResultsRequest
- StartLabelDetectionRequest
- DetectFacesRequest
- SearchFacesByImageResponse
- StartVideoJobResponse
- DetectLabelsRequest
- DetectCustomLabelsRequest
- CreateFaceLivenessSessionResponse
- CreateCollectionResponse
- CompareFacesRequest
- FaceDetail
- SearchFacesByImageRequest
- Label
- CreateCollectionRequest
- GetVideoJobResultRequest
- DetectCustomLabelsResponse
- IndexFacesRequest
- RecognizeCelebritiesResponse
- GetLabelDetectionResponse
- GetFaceLivenessSessionResultsResponse
- DetectFacesResponse
- ImageOnlyRequest
context_file: json-ld/amazon-rekognition-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-rekognition/refs/heads/main/json-ld/amazon-rekognition-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Rekognition from Amazon Rekognition.
layout: jsonld
name: Amazon Rekognition Context
namespaces:
- prefix: rekognition
  uri: https://rekognition.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Video
  type: string
- container: ''
  name: BoundingBox
  type: string
- container: ''
  name: S3Object
  type: string
- container: ''
  name: Image
  type: string
- container: ''
  name: NotificationChannel
  type: string
- container: ''
  name: SourceImageFace
  type: reference
- container: ''
  name: Confidence
  type: float
- container: set
  name: FaceMatches
  type: reference
- container: ''
  name: Similarity
  type: float
- container: ''
  name: Face
  type: reference
- container: set
  name: UnmatchedFaces
  type: reference
- container: set
  name: Labels
  type: reference
- container: ''
  name: Name
  type: string
- container: set
  name: Instances
  type: reference
- container: set
  name: Parents
  type: reference
- container: set
  name: Aliases
  type: reference
- container: set
  name: Categories
  type: reference
- container: ''
  name: LabelModelVersion
  type: string
- container: ''
  name: ImageProperties
  type: reference
- container: ''
  name: Quality
  type: reference
- container: ''
  name: Brightness
  type: decimal
- container: ''
  name: Sharpness
  type: decimal
- container: ''
  name: Contrast
  type: decimal
- container: set
  name: DominantColors
  type: reference
- container: ''
  name: Red
  type: integer
- container: ''
  name: Green
  type: integer
- container: ''
  name: Blue
  type: integer
- container: ''
  name: HexCode
  type: string
- container: ''
  name: SimplifiedColor
  type: string
- container: ''
  name: CSSColor
  type: string
- container: ''
  name: PixelPercent
  type: decimal
- container: ''
  name: MinConfidence
  type: float
- container: ''
  name: HumanLoopConfig
  type: reference
- container: ''
  name: ProjectVersion
  type: string
- container: set
  name: CollectionIds
  type: string
- container: ''
  name: NextToken
  type: string
- container: set
  name: FaceModelVersions
  type: string
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: Settings
  type: reference
- container: ''
  name: ClientRequestToken
  type: string
- container: ''
  name: Width
  type: float
- container: ''
  name: Height
  type: float
- container: ''
  name: Left
  type: float
- container: ''
  name: Top
  type: float
- container: set
  name: ModerationLabels
  type: reference
- container: ''
  name: ParentName
  type: string
- container: ''
  name: ModerationModelVersion
  type: string
- container: ''
  name: HumanLoopActivationOutput
  type: reference
- container: set
  name: TextDetections
  type: reference
- container: ''
  name: DetectedText
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: Id
  type: integer
- container: ''
  name: ParentId
  type: integer
- container: ''
  name: Geometry
  type: reference
- container: ''
  name: TextModelVersion
  type: string
- container: set
  name: FaceRecords
  type: reference
- container: ''
  name: OrientationCorrection
  type: string
- container: ''
  name: FaceModelVersion
  type: string
- container: set
  name: UnindexedFaces
  type: reference
- container: ''
  name: SessionId
  type: string
- container: ''
  name: JobTag
  type: string
- container: set
  name: Features
  type: string
- container: set
  name: Attributes
  type: string
- container: ''
  name: SearchedFaceBoundingBox
  type: string
- container: ''
  name: SearchedFaceConfidence
  type: float
- container: ''
  name: JobId
  type: string
- container: ''
  name: MaxLabels
  type: integer
- container: ''
  name: ProjectVersionArn
  type: string
- container: ''
  name: MaxResults
  type: integer
- container: ''
  name: StatusCode
  type: integer
- container: ''
  name: CollectionArn
  type: string
- container: ''
  name: SourceImage
  type: string
- container: ''
  name: TargetImage
  type: string
- container: ''
  name: SimilarityThreshold
  type: float
- container: ''
  name: QualityFilter
  type: string
- container: ''
  name: AgeRange
  type: reference
- container: ''
  name: Low
  type: integer
- container: ''
  name: High
  type: integer
- container: ''
  name: Smile
  type: reference
- container: ''
  name: Value
  type: boolean
- container: ''
  name: Gender
  type: reference
- container: set
  name: Emotions
  type: reference
- container: ''
  name: CollectionId
  type: string
- container: ''
  name: MaxFaces
  type: integer
- container: ''
  name: FaceMatchThreshold
  type: float
- container: ''
  name: Tags
  type: reference
- container: ''
  name: Bucket
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: SortBy
  type: string
- container: ''
  name: AggregateBy
  type: string
- container: ''
  name: Bytes
  type: string
- container: set
  name: CustomLabels
  type: reference
- container: ''
  name: SNSTopicArn
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: ExternalImageId
  type: string
- container: set
  name: DetectionAttributes
  type: string
- container: set
  name: CelebrityFaces
  type: reference
- container: set
  name: Urls
  type: string
- container: ''
  name: MatchConfidence
  type: float
- container: ''
  name: KnownGender
  type: reference
- container: set
  name: UnrecognizedFaces
  type: reference
- container: ''
  name: JobStatus
  type: string
- container: ''
  name: StatusMessage
  type: string
- container: ''
  name: VideoMetadata
  type: reference
- container: ''
  name: Status
  type: string
- container: ''
  name: ReferenceImage
  type: reference
- container: set
  name: AuditImages
  type: reference
- container: set
  name: FaceDetails
  type: string
property_count: 108
provider_name: Amazon Rekognition
provider_slug: amazon-rekognition
slug: amazon-rekognition-context
source_filename: amazon-rekognition-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"rekognition\": \"https://rekognition.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CompareFacesResponse\": \"rekognition:CompareFacesResponse\",\n    \"DetectLabelsResponse\": \"rekognition:DetectLabelsResponse\",\n    \"Video\": {\n      \"@id\": \"rekognition:Video\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DetectModerationLabelsRequest\": \"rekognition:DetectModerationLabelsRequest\",\n    \"ListCollectionsResponse\": \"rekognition:ListCollectionsResponse\",\n    \"CreateFaceLivenessSessionRequest\": \"rekognition:CreateFaceLivenessSessionRequest\",\n    \"BoundingBox\": {\n      \"@id\": \"rekognition:BoundingBox\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DetectModerationLabelsResponse\": \"rekognition:DetectModerationLabelsResponse\",\n    \"DetectTextResponse\": \"rekognition:DetectTextResponse\"\
  ,\n    \"IndexFacesResponse\": \"rekognition:IndexFacesResponse\",\n    \"GetFaceLivenessSessionResultsRequest\": \"rekognition:GetFaceLivenessSessionResultsRequest\",\n    \"StartLabelDetectionRequest\": \"rekognition:StartLabelDetectionRequest\",\n    \"DetectFacesRequest\": \"rekognition:DetectFacesRequest\",\n    \"SearchFacesByImageResponse\": \"rekognition:SearchFacesByImageResponse\",\n    \"StartVideoJobResponse\": \"rekognition:StartVideoJobResponse\",\n    \"DetectLabelsRequest\": \"rekognition:DetectLabelsRequest\",\n    \"DetectCustomLabelsRequest\": \"rekognition:DetectCustomLabelsRequest\",\n    \"CreateFaceLivenessSessionResponse\": \"rekognition:CreateFaceLivenessSessionResponse\",\n    \"CreateCollectionResponse\": \"rekognition:CreateCollectionResponse\",\n    \"CompareFacesRequest\": \"rekognition:CompareFacesRequest\",\n    \"FaceDetail\": \"rekognition:FaceDetail\",\n    \"SearchFacesByImageRequest\": \"rekognition:SearchFacesByImageRequest\",\n    \"Label\": \"rekognition:Label\"\
  ,\n    \"CreateCollectionRequest\": \"rekognition:CreateCollectionRequest\",\n    \"S3Object\": {\n      \"@id\": \"rekognition:S3Object\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetVideoJobResultRequest\": \"rekognition:GetVideoJobResultRequest\",\n    \"Image\": {\n      \"@id\": \"rekognition:Image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DetectCustomLabelsResponse\": \"rekognition:DetectCustomLabelsResponse\",\n    \"NotificationChannel\": {\n      \"@id\": \"rekognition:NotificationChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IndexFacesRequest\": \"rekognition:IndexFacesRequest\",\n    \"RecognizeCelebritiesResponse\": \"rekognition:RecognizeCelebritiesResponse\",\n    \"GetLabelDetectionResponse\": \"rekognition:GetLabelDetectionResponse\",\n    \"GetFaceLivenessSessionResultsResponse\": \"rekognition:GetFaceLivenessSessionResultsResponse\",\n    \"DetectFacesResponse\": \"rekognition:DetectFacesResponse\",\n    \"ImageOnlyRequest\": \"rekognition:ImageOnlyRequest\"\
  ,\n    \"SourceImageFace\": {\n      \"@id\": \"rekognition:SourceImageFace\",\n      \"@type\": \"@id\"\n    },\n    \"Confidence\": {\n      \"@id\": \"rekognition:Confidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"FaceMatches\": {\n      \"@id\": \"rekognition:FaceMatches\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Similarity\": {\n      \"@id\": \"rekognition:Similarity\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Face\": {\n      \"@id\": \"rekognition:Face\",\n      \"@type\": \"@id\"\n    },\n    \"UnmatchedFaces\": {\n      \"@id\": \"rekognition:UnmatchedFaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Labels\": {\n      \"@id\": \"rekognition:Labels\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Name\": {\n      \"@id\": \"rekognition:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Instances\": {\n      \"@id\": \"rekognition:Instances\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Parents\": {\n      \"@id\": \"rekognition:Parents\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Aliases\": {\n      \"@id\": \"rekognition:Aliases\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Categories\": {\n      \"@id\": \"rekognition:Categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"LabelModelVersion\": {\n      \"@id\": \"rekognition:LabelModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageProperties\": {\n      \"@id\": \"rekognition:ImageProperties\",\n      \"@type\": \"@id\"\n    },\n    \"Quality\": {\n      \"@id\": \"rekognition:Quality\",\n      \"@type\": \"@id\"\n    },\n    \"Brightness\": {\n      \"@id\": \"rekognition:Brightness\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Sharpness\": {\n      \"@id\": \"rekognition:Sharpness\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Contrast\": {\n\
  \      \"@id\": \"rekognition:Contrast\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"DominantColors\": {\n      \"@id\": \"rekognition:DominantColors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Red\": {\n      \"@id\": \"rekognition:Red\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Green\": {\n      \"@id\": \"rekognition:Green\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Blue\": {\n      \"@id\": \"rekognition:Blue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"HexCode\": {\n      \"@id\": \"rekognition:HexCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SimplifiedColor\": {\n      \"@id\": \"rekognition:SimplifiedColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CSSColor\": {\n      \"@id\": \"rekognition:CSSColor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PixelPercent\": {\n      \"@id\": \"rekognition:PixelPercent\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"MinConfidence\": {\n      \"@id\": \"rekognition:MinConfidence\"\
  ,\n      \"@type\": \"xsd:float\"\n    },\n    \"HumanLoopConfig\": {\n      \"@id\": \"rekognition:HumanLoopConfig\",\n      \"@type\": \"@id\"\n    },\n    \"ProjectVersion\": {\n      \"@id\": \"rekognition:ProjectVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectionIds\": {\n      \"@id\": \"rekognition:CollectionIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"rekognition:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaceModelVersions\": {\n      \"@id\": \"rekognition:FaceModelVersions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"rekognition:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Settings\": {\n      \"@id\": \"rekognition:Settings\",\n      \"@type\": \"@id\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"rekognition:ClientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Width\": {\n      \"@id\": \"rekognition:Width\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Height\": {\n      \"@id\": \"rekognition:Height\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Left\": {\n      \"@id\": \"rekognition:Left\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Top\": {\n      \"@id\": \"rekognition:Top\",\n      \"@type\": \"xsd:float\"\n    },\n    \"ModerationLabels\": {\n      \"@id\": \"rekognition:ModerationLabels\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"ParentName\": {\n      \"@id\": \"rekognition:ParentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModerationModelVersion\": {\n      \"@id\": \"rekognition:ModerationModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HumanLoopActivationOutput\": {\n      \"@id\": \"rekognition:HumanLoopActivationOutput\",\n      \"@type\": \"@id\"\n    },\n    \"TextDetections\": {\n      \"@id\": \"rekognition:TextDetections\",\n      \"@container\": \"\
  @set\",\n      \"@type\": \"@id\"\n    },\n    \"DetectedText\": {\n      \"@id\": \"rekognition:DetectedText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"rekognition:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"rekognition:Id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ParentId\": {\n      \"@id\": \"rekognition:ParentId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Geometry\": {\n      \"@id\": \"rekognition:Geometry\",\n      \"@type\": \"@id\"\n    },\n    \"TextModelVersion\": {\n      \"@id\": \"rekognition:TextModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaceRecords\": {\n      \"@id\": \"rekognition:FaceRecords\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"OrientationCorrection\": {\n      \"@id\": \"rekognition:OrientationCorrection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaceModelVersion\": {\n      \"@id\": \"rekognition:FaceModelVersion\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"UnindexedFaces\": {\n      \"@id\": \"rekognition:UnindexedFaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"SessionId\": {\n      \"@id\": \"rekognition:SessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobTag\": {\n      \"@id\": \"rekognition:JobTag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Features\": {\n      \"@id\": \"rekognition:Features\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Attributes\": {\n      \"@id\": \"rekognition:Attributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SearchedFaceBoundingBox\": {\n      \"@id\": \"rekognition:SearchedFaceBoundingBox\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SearchedFaceConfidence\": {\n      \"@id\": \"rekognition:SearchedFaceConfidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"JobId\": {\n      \"@id\": \"rekognition:JobId\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"MaxLabels\": {\n      \"@id\": \"rekognition:MaxLabels\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ProjectVersionArn\": {\n      \"@id\": \"rekognition:ProjectVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"rekognition:MaxResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"StatusCode\": {\n      \"@id\": \"rekognition:StatusCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"CollectionArn\": {\n      \"@id\": \"rekognition:CollectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceImage\": {\n      \"@id\": \"rekognition:SourceImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetImage\": {\n      \"@id\": \"rekognition:TargetImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SimilarityThreshold\": {\n      \"@id\": \"rekognition:SimilarityThreshold\",\n      \"@type\": \"xsd:float\"\n    },\n    \"QualityFilter\": {\n      \"@id\": \"rekognition:QualityFilter\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"AgeRange\": {\n      \"@id\": \"rekognition:AgeRange\",\n      \"@type\": \"@id\"\n    },\n    \"Low\": {\n      \"@id\": \"rekognition:Low\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"High\": {\n      \"@id\": \"rekognition:High\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Smile\": {\n      \"@id\": \"rekognition:Smile\",\n      \"@type\": \"@id\"\n    },\n    \"Value\": {\n      \"@id\": \"rekognition:Value\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Gender\": {\n      \"@id\": \"rekognition:Gender\",\n      \"@type\": \"@id\"\n    },\n    \"Emotions\": {\n      \"@id\": \"rekognition:Emotions\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"CollectionId\": {\n      \"@id\": \"rekognition:CollectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxFaces\": {\n      \"@id\": \"rekognition:MaxFaces\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"FaceMatchThreshold\": {\n     \
  \ \"@id\": \"rekognition:FaceMatchThreshold\",\n      \"@type\": \"xsd:float\"\n    },\n    \"Tags\": {\n      \"@id\": \"rekognition:Tags\",\n      \"@type\": \"@id\"\n    },\n    \"Bucket\": {\n      \"@id\": \"rekognition:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"rekognition:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SortBy\": {\n      \"@id\": \"rekognition:SortBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AggregateBy\": {\n      \"@id\": \"rekognition:AggregateBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Bytes\": {\n      \"@id\": \"rekognition:Bytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomLabels\": {\n      \"@id\": \"rekognition:CustomLabels\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"SNSTopicArn\": {\n      \"@id\": \"rekognition:SNSTopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"rekognition:RoleArn\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"ExternalImageId\": {\n      \"@id\": \"rekognition:ExternalImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DetectionAttributes\": {\n      \"@id\": \"rekognition:DetectionAttributes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CelebrityFaces\": {\n      \"@id\": \"rekognition:CelebrityFaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"Urls\": {\n      \"@id\": \"rekognition:Urls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MatchConfidence\": {\n      \"@id\": \"rekognition:MatchConfidence\",\n      \"@type\": \"xsd:float\"\n    },\n    \"KnownGender\": {\n      \"@id\": \"rekognition:KnownGender\",\n      \"@type\": \"@id\"\n    },\n    \"UnrecognizedFaces\": {\n      \"@id\": \"rekognition:UnrecognizedFaces\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"JobStatus\": {\n      \"@id\": \"rekognition:JobStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusMessage\": {\n      \"@id\": \"rekognition:StatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VideoMetadata\": {\n      \"@id\": \"rekognition:VideoMetadata\",\n      \"@type\": \"@id\"\n    },\n    \"Status\": {\n      \"@id\": \"rekognition:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReferenceImage\": {\n      \"@id\": \"rekognition:ReferenceImage\",\n      \"@type\": \"@id\"\n    },\n    \"AuditImages\": {\n      \"@id\": \"rekognition:AuditImages\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"FaceDetails\": {\n      \"@id\": \"rekognition:FaceDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-rekognition/refs/heads/main/json-ld/amazon-rekognition-context.jsonld
tags:
- AWS
- Celebrity Recognition
- Computer Vision
- Content Moderation
- Custom Labels
- Deep Learning
- Face Liveness
- Facial Recognition
- Image Analysis
- Machine Learning
- Object Detection
- Text Detection
- Video Analysis
- JSON-LD
- Linked Data
- Semantic Web
---
