---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 37
classes:
- SegmentLocation
- GetSegmentVersionsResponse
- SegmentsResponse
- SetDimension
- SegmentGroup
- WriteSegmentRequest
- EndpointDemographic
- GetSegmentExportJobsRequest
- UpdateSegmentRequest
- GetSegmentVersionRequest
- SegmentResponse
- GetSegmentImportJobsRequest
- CreateSegmentResponse
- SegmentGroupList
- EventDimensions
- CreateSegmentRequest
- SegmentImportResource
- RecencyDimension
- UpdateSegmentResponse
- GetSegmentVersionResponse
- DeleteSegmentResponse
- GPSPointDimension
- GetSegmentResponse
- GetSegmentExportJobsResponse
- SegmentReference
- SegmentBehaviors
- MetricDimension
- GetSegmentVersionsRequest
- GetSegmentRequest
- GetSegmentsRequest
- SegmentDemographics
- SegmentCondition
- DeleteSegmentRequest
- AttributeDimension
- GetSegmentImportJobsResponse
- GetSegmentsResponse
- SegmentDimensions
context_file: json-ld/amazon-pinpoint-segments-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-segments-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Segments from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Segments Context
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
  name: Country
  type: string
- container: ''
  name: GPSPoint
  type: string
- container: ''
  name: DimensionType
  type: string
- container: ''
  name: Values
  type: string
- container: ''
  name: Dimensions
  type: string
- container: ''
  name: SourceSegments
  type: string
- container: ''
  name: SourceType
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: SegmentGroups
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: AppVersion
  type: string
- container: ''
  name: Locale
  type: string
- container: ''
  name: Make
  type: string
- container: ''
  name: Model
  type: string
- container: ''
  name: ModelVersion
  type: string
- container: ''
  name: Platform
  type: string
- container: ''
  name: PlatformVersion
  type: string
- container: ''
  name: Timezone
  type: string
- container: ''
  name: ApplicationId
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: ImportDefinition
  type: string
- container: ''
  name: LastModifiedDate
  type: string
- container: ''
  name: SegmentType
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Groups
  type: string
- container: ''
  name: Include
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: EventType
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: ChannelCounts
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: Format
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: S3Url
  type: string
- container: ''
  name: Size
  type: string
- container: ''
  name: Duration
  type: string
- container: ''
  name: RecencyType
  type: string
- container: ''
  name: Item
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Coordinates
  type: string
- container: ''
  name: RangeInKilometers
  type: string
- container: ''
  name: ExportJobsResponse
  type: string
- container: ''
  name: Recency
  type: string
- container: ''
  name: ComparisonOperator
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Channel
  type: string
- container: ''
  name: DeviceType
  type: string
- container: ''
  name: SegmentId
  type: string
- container: ''
  name: AttributeType
  type: string
- container: ''
  name: ImportJobsResponse
  type: string
- container: ''
  name: Behavior
  type: string
- container: ''
  name: Demographic
  type: string
- container: ''
  name: Location
  type: string
- container: ''
  name: UserAttributes
  type: string
property_count: 57
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-segments-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"SegmentLocation\": \"pinpoint:SegmentLocation\",\n    \"Country\": {\n      \"@id\": \"pinpoint:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GPSPoint\": {\n      \"@id\": \"pinpoint:GPSPoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentVersionsResponse\": \"pinpoint:GetSegmentVersionsResponse\",\n    \"SegmentsResponse\": \"pinpoint:SegmentsResponse\",\n    \"SetDimension\": \"pinpoint:SetDimension\",\n    \"DimensionType\": {\n      \"@id\": \"pinpoint:DimensionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Values\": {\n      \"@id\": \"pinpoint:Values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentGroup\": \"pinpoint:SegmentGroup\",\n    \"Dimensions\": {\n      \"@id\"\
  : \"pinpoint:Dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceSegments\": {\n      \"@id\": \"pinpoint:SourceSegments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceType\": {\n      \"@id\": \"pinpoint:SourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"pinpoint:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WriteSegmentRequest\": \"pinpoint:WriteSegmentRequest\",\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentGroups\": {\n      \"@id\": \"pinpoint:SegmentGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointDemographic\": \"pinpoint:EndpointDemographic\",\n    \"AppVersion\": {\n      \"@id\": \"pinpoint:AppVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Locale\": {\n      \"@id\": \"pinpoint:Locale\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Make\": {\n      \"@id\": \"pinpoint:Make\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Model\": {\n      \"@id\": \"pinpoint:Model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModelVersion\": {\n      \"@id\": \"pinpoint:ModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Platform\": {\n      \"@id\": \"pinpoint:Platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlatformVersion\": {\n      \"@id\": \"pinpoint:PlatformVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timezone\": {\n      \"@id\": \"pinpoint:Timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentExportJobsRequest\": \"pinpoint:GetSegmentExportJobsRequest\",\n    \"UpdateSegmentRequest\": \"pinpoint:UpdateSegmentRequest\",\n    \"GetSegmentVersionRequest\": \"pinpoint:GetSegmentVersionRequest\",\n    \"SegmentResponse\": \"pinpoint:SegmentResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImportDefinition\": {\n      \"@id\": \"pinpoint:ImportDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentType\": {\n      \"@id\": \"pinpoint:SegmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"pinpoint:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentImportJobsRequest\": \"pinpoint:GetSegmentImportJobsRequest\",\n    \"CreateSegmentResponse\": \"pinpoint:CreateSegmentResponse\",\n    \"SegmentGroupList\": \"pinpoint:SegmentGroupList\",\n    \"Groups\": {\n      \"@id\": \"pinpoint:Groups\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Include\": {\n      \"@id\": \"pinpoint:Include\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventDimensions\": \"pinpoint:EventDimensions\",\n    \"Attributes\": {\n      \"@id\": \"pinpoint:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventType\": {\n      \"@id\": \"pinpoint:EventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"pinpoint:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateSegmentRequest\": \"pinpoint:CreateSegmentRequest\",\n    \"SegmentImportResource\": \"pinpoint:SegmentImportResource\",\n    \"ChannelCounts\": {\n      \"@id\": \"pinpoint:ChannelCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalId\": {\n      \"@id\": \"pinpoint:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Format\": {\n      \"@id\": \"pinpoint:Format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"pinpoint:RoleArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Url\": {\n      \"@id\": \"pinpoint:S3Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Size\": {\n      \"@id\": \"pinpoint:Size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecencyDimension\": \"pinpoint:RecencyDimension\",\n    \"Duration\": {\n      \"@id\": \"pinpoint:Duration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecencyType\": {\n      \"@id\": \"pinpoint:RecencyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateSegmentResponse\": \"pinpoint:UpdateSegmentResponse\",\n    \"GetSegmentVersionResponse\": \"pinpoint:GetSegmentVersionResponse\",\n    \"DeleteSegmentResponse\": \"pinpoint:DeleteSegmentResponse\",\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pinpoint:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GPSPointDimension\": \"pinpoint:GPSPointDimension\",\n    \"Coordinates\": {\n      \"@id\"\
  : \"pinpoint:Coordinates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RangeInKilometers\": {\n      \"@id\": \"pinpoint:RangeInKilometers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentResponse\": \"pinpoint:GetSegmentResponse\",\n    \"GetSegmentExportJobsResponse\": \"pinpoint:GetSegmentExportJobsResponse\",\n    \"ExportJobsResponse\": {\n      \"@id\": \"pinpoint:ExportJobsResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentReference\": \"pinpoint:SegmentReference\",\n    \"SegmentBehaviors\": \"pinpoint:SegmentBehaviors\",\n    \"Recency\": {\n      \"@id\": \"pinpoint:Recency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricDimension\": \"pinpoint:MetricDimension\",\n    \"ComparisonOperator\": {\n      \"@id\": \"pinpoint:ComparisonOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pinpoint:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentVersionsRequest\": \"pinpoint:GetSegmentVersionsRequest\"\
  ,\n    \"GetSegmentRequest\": \"pinpoint:GetSegmentRequest\",\n    \"GetSegmentsRequest\": \"pinpoint:GetSegmentsRequest\",\n    \"SegmentDemographics\": \"pinpoint:SegmentDemographics\",\n    \"Channel\": {\n      \"@id\": \"pinpoint:Channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceType\": {\n      \"@id\": \"pinpoint:DeviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentCondition\": \"pinpoint:SegmentCondition\",\n    \"SegmentId\": {\n      \"@id\": \"pinpoint:SegmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteSegmentRequest\": \"pinpoint:DeleteSegmentRequest\",\n    \"AttributeDimension\": \"pinpoint:AttributeDimension\",\n    \"AttributeType\": {\n      \"@id\": \"pinpoint:AttributeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetSegmentImportJobsResponse\": \"pinpoint:GetSegmentImportJobsResponse\",\n    \"ImportJobsResponse\": {\n      \"@id\": \"pinpoint:ImportJobsResponse\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"GetSegmentsResponse\": \"pinpoint:GetSegmentsResponse\",\n    \"SegmentDimensions\": \"pinpoint:SegmentDimensions\",\n    \"Behavior\": {\n      \"@id\": \"pinpoint:Behavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Demographic\": {\n      \"@id\": \"pinpoint:Demographic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Location\": {\n      \"@id\": \"pinpoint:Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserAttributes\": {\n      \"@id\": \"pinpoint:UserAttributes\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-segments-context.jsonld
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
