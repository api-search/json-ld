---
api_specs:
- filename: amazon-pinpoint-openapi.yml
  format: yaml
  label: Amazon Pinpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/openapi/amazon-pinpoint-openapi.yml
class_count: 54
classes:
- ExportJobsResponse
- GetApplicationDateRangeKpiRequest
- GetRecommenderConfigurationsResponse
- ListRecommenderConfigurationsResponse
- ResultRowValue
- GetImportJobsResponse
- ImportJobsResponse
- ImportJobResource
- GetImportJobRequest
- ApplicationsResponse
- GetAppResponse
- ApplicationResponse
- BaseKpiResult
- ApplicationDateRangeKpiResponse
- PutEventsResponse
- EventsResponse
- GetExportJobRequest
- CreateRecommenderConfigurationResponse
- RecommenderConfigurationResponse
- CreateAppResponse
- GetExportJobsResponse
- ExportJobResource
- NumberValidateResponse
- GetApplicationDateRangeKpiResponse
- GetRecommenderConfigurationResponse
- DeleteAppResponse
- PutEventStreamResponse
- ActivitiesResponse
- GetExportJobsRequest
- GetAppsResponse
- CreateImportJobRequest
- ImportJobRequest
- ResultRow
- DeleteRecommenderConfigurationResponse
- CreateExportJobResponse
- ExportJobResponse
- UpdateApplicationSettingsResponse
- PhoneNumberValidateResponse
- ListTagsForResourceResponse
- GetImportJobResponse
- ImportJobResponse
- EventItemResponse
- DeleteEventStreamResponse
- VerificationResponse
- ExportJobRequest
- GetExportJobResponse
- ItemResponse
- GetEventStreamResponse
- UpdateRecommenderConfigurationResponse
- GetApplicationSettingsResponse
- CreateImportJobResponse
- CreateExportJobRequest
- GetImportJobsRequest
- RemoveAttributesResponse
context_file: json-ld/amazon-pinpoint-analytics-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-analytics-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Pinpoint Analytics from Amazon Pinpoint.
layout: jsonld
name: Amazon Pinpoint Analytics Context
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
  name: Item
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: DefineSegment
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: Format
  type: string
- container: ''
  name: RegisterEndpoints
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: S3Url
  type: string
- container: ''
  name: SegmentId
  type: string
- container: ''
  name: SegmentName
  type: string
- container: ''
  name: Rows
  type: string
- container: ''
  name: ApplicationId
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
  name: S3UrlPrefix
  type: string
- container: ''
  name: SegmentVersion
  type: string
- container: ''
  name: Carrier
  type: string
- container: ''
  name: City
  type: string
- container: ''
  name: CleansedPhoneNumberE164
  type: string
- container: ''
  name: CleansedPhoneNumberNational
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: CountryCodeIso2
  type: string
- container: ''
  name: CountryCodeNumeric
  type: string
- container: ''
  name: County
  type: string
- container: ''
  name: OriginalCountryCodeIso2
  type: string
- container: ''
  name: OriginalPhoneNumber
  type: string
- container: ''
  name: PhoneType
  type: string
- container: ''
  name: PhoneTypeCode
  type: string
- container: ''
  name: Timezone
  type: string
- container: ''
  name: ZipCode
  type: string
- container: ''
  name: EventStream
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: GroupedBys
  type: string
- container: ''
  name: Values
  type: string
- container: ''
  name: ApplicationSettingsResource
  type: string
- container: ''
  name: TagsModel
  type: string
- container: ''
  name: CompletedPieces
  type: string
- container: ''
  name: CompletionDate
  type: string
- container: ''
  name: Definition
  type: string
- container: ''
  name: FailedPieces
  type: string
- container: ''
  name: Failures
  type: string
- container: ''
  name: JobStatus
  type: string
- container: ''
  name: TotalFailures
  type: string
- container: ''
  name: TotalPieces
  type: string
- container: ''
  name: TotalProcessed
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: StatusCode
  type: string
- container: ''
  name: Valid
  type: string
- container: ''
  name: Results
  type: string
- container: ''
  name: EndpointItemResponse
  type: string
- container: ''
  name: EventsItemResponse
  type: string
- container: ''
  name: Attributes
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: LastModifiedDate
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
  name: AttributesResource
  type: string
property_count: 70
provider_name: Amazon Pinpoint
provider_slug: amazon-pinpoint
slug: amazon-pinpoint-analytics-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pinpoint\": \"https://pinpoint.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ExportJobsResponse\": \"pinpoint:ExportJobsResponse\",\n    \"Item\": {\n      \"@id\": \"pinpoint:Item\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pinpoint:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApplicationDateRangeKpiRequest\": \"pinpoint:GetApplicationDateRangeKpiRequest\",\n    \"GetRecommenderConfigurationsResponse\": \"pinpoint:GetRecommenderConfigurationsResponse\",\n    \"ListRecommenderConfigurationsResponse\": \"pinpoint:ListRecommenderConfigurationsResponse\",\n    \"ResultRowValue\": \"pinpoint:ResultRowValue\",\n    \"Key\": {\n      \"@id\": \"pinpoint:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"pinpoint:Type\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pinpoint:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetImportJobsResponse\": \"pinpoint:GetImportJobsResponse\",\n    \"ImportJobsResponse\": \"pinpoint:ImportJobsResponse\",\n    \"ImportJobResource\": \"pinpoint:ImportJobResource\",\n    \"DefineSegment\": {\n      \"@id\": \"pinpoint:DefineSegment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalId\": {\n      \"@id\": \"pinpoint:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Format\": {\n      \"@id\": \"pinpoint:Format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisterEndpoints\": {\n      \"@id\": \"pinpoint:RegisterEndpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"pinpoint:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Url\": {\n      \"@id\": \"pinpoint:S3Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentId\": {\n      \"@id\": \"pinpoint:SegmentId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentName\": {\n      \"@id\": \"pinpoint:SegmentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetImportJobRequest\": \"pinpoint:GetImportJobRequest\",\n    \"ApplicationsResponse\": \"pinpoint:ApplicationsResponse\",\n    \"GetAppResponse\": \"pinpoint:GetAppResponse\",\n    \"ApplicationResponse\": \"pinpoint:ApplicationResponse\",\n    \"BaseKpiResult\": \"pinpoint:BaseKpiResult\",\n    \"Rows\": {\n      \"@id\": \"pinpoint:Rows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationDateRangeKpiResponse\": \"pinpoint:ApplicationDateRangeKpiResponse\",\n    \"ApplicationId\": {\n      \"@id\": \"pinpoint:ApplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"pinpoint:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KpiName\": {\n      \"@id\": \"pinpoint:KpiName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KpiResult\": {\n      \"@id\": \"pinpoint:KpiResult\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"pinpoint:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PutEventsResponse\": \"pinpoint:PutEventsResponse\",\n    \"EventsResponse\": \"pinpoint:EventsResponse\",\n    \"GetExportJobRequest\": \"pinpoint:GetExportJobRequest\",\n    \"CreateRecommenderConfigurationResponse\": \"pinpoint:CreateRecommenderConfigurationResponse\",\n    \"RecommenderConfigurationResponse\": \"pinpoint:RecommenderConfigurationResponse\",\n    \"CreateAppResponse\": \"pinpoint:CreateAppResponse\",\n    \"GetExportJobsResponse\": \"pinpoint:GetExportJobsResponse\",\n    \"ExportJobResource\": \"pinpoint:ExportJobResource\",\n    \"S3UrlPrefix\": {\n      \"@id\": \"pinpoint:S3UrlPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SegmentVersion\": {\n      \"@id\": \"pinpoint:SegmentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberValidateResponse\": \"pinpoint:NumberValidateResponse\",\n    \"\
  Carrier\": {\n      \"@id\": \"pinpoint:Carrier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"City\": {\n      \"@id\": \"pinpoint:City\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CleansedPhoneNumberE164\": {\n      \"@id\": \"pinpoint:CleansedPhoneNumberE164\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CleansedPhoneNumberNational\": {\n      \"@id\": \"pinpoint:CleansedPhoneNumberNational\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"pinpoint:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CountryCodeIso2\": {\n      \"@id\": \"pinpoint:CountryCodeIso2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CountryCodeNumeric\": {\n      \"@id\": \"pinpoint:CountryCodeNumeric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"County\": {\n      \"@id\": \"pinpoint:County\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginalCountryCodeIso2\": {\n      \"@id\": \"pinpoint:OriginalCountryCodeIso2\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"OriginalPhoneNumber\": {\n      \"@id\": \"pinpoint:OriginalPhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneType\": {\n      \"@id\": \"pinpoint:PhoneType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneTypeCode\": {\n      \"@id\": \"pinpoint:PhoneTypeCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timezone\": {\n      \"@id\": \"pinpoint:Timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ZipCode\": {\n      \"@id\": \"pinpoint:ZipCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApplicationDateRangeKpiResponse\": \"pinpoint:GetApplicationDateRangeKpiResponse\",\n    \"GetRecommenderConfigurationResponse\": \"pinpoint:GetRecommenderConfigurationResponse\",\n    \"DeleteAppResponse\": \"pinpoint:DeleteAppResponse\",\n    \"PutEventStreamResponse\": \"pinpoint:PutEventStreamResponse\",\n    \"EventStream\": {\n      \"@id\": \"pinpoint:EventStream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActivitiesResponse\"\
  : \"pinpoint:ActivitiesResponse\",\n    \"GetExportJobsRequest\": \"pinpoint:GetExportJobsRequest\",\n    \"Arn\": {\n      \"@id\": \"pinpoint:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pinpoint:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pinpoint:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pinpoint:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"pinpoint:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetAppsResponse\": \"pinpoint:GetAppsResponse\",\n    \"CreateImportJobRequest\": \"pinpoint:CreateImportJobRequest\",\n    \"ImportJobRequest\": \"pinpoint:ImportJobRequest\",\n    \"ResultRow\": \"pinpoint:ResultRow\",\n    \"GroupedBys\": {\n      \"@id\": \"pinpoint:GroupedBys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Values\": {\n      \"@id\": \"pinpoint:Values\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"DeleteRecommenderConfigurationResponse\": \"pinpoint:DeleteRecommenderConfigurationResponse\",\n    \"CreateExportJobResponse\": \"pinpoint:CreateExportJobResponse\",\n    \"ExportJobResponse\": \"pinpoint:ExportJobResponse\",\n    \"UpdateApplicationSettingsResponse\": \"pinpoint:UpdateApplicationSettingsResponse\",\n    \"ApplicationSettingsResource\": {\n      \"@id\": \"pinpoint:ApplicationSettingsResource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneNumberValidateResponse\": \"pinpoint:PhoneNumberValidateResponse\",\n    \"ListTagsForResourceResponse\": \"pinpoint:ListTagsForResourceResponse\",\n    \"TagsModel\": {\n      \"@id\": \"pinpoint:TagsModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetImportJobResponse\": \"pinpoint:GetImportJobResponse\",\n    \"ImportJobResponse\": \"pinpoint:ImportJobResponse\",\n    \"CompletedPieces\": {\n      \"@id\": \"pinpoint:CompletedPieces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompletionDate\"\
  : {\n      \"@id\": \"pinpoint:CompletionDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Definition\": {\n      \"@id\": \"pinpoint:Definition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailedPieces\": {\n      \"@id\": \"pinpoint:FailedPieces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Failures\": {\n      \"@id\": \"pinpoint:Failures\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobStatus\": {\n      \"@id\": \"pinpoint:JobStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalFailures\": {\n      \"@id\": \"pinpoint:TotalFailures\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalPieces\": {\n      \"@id\": \"pinpoint:TotalPieces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalProcessed\": {\n      \"@id\": \"pinpoint:TotalProcessed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventItemResponse\": \"pinpoint:EventItemResponse\",\n    \"Message\": {\n      \"@id\": \"pinpoint:Message\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"StatusCode\": {\n      \"@id\": \"pinpoint:StatusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEventStreamResponse\": \"pinpoint:DeleteEventStreamResponse\",\n    \"VerificationResponse\": \"pinpoint:VerificationResponse\",\n    \"Valid\": {\n      \"@id\": \"pinpoint:Valid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExportJobRequest\": \"pinpoint:ExportJobRequest\",\n    \"GetExportJobResponse\": \"pinpoint:GetExportJobResponse\",\n    \"Results\": {\n      \"@id\": \"pinpoint:Results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ItemResponse\": \"pinpoint:ItemResponse\",\n    \"EndpointItemResponse\": {\n      \"@id\": \"pinpoint:EndpointItemResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventsItemResponse\": {\n      \"@id\": \"pinpoint:EventsItemResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEventStreamResponse\": \"pinpoint:GetEventStreamResponse\",\n    \"UpdateRecommenderConfigurationResponse\": \"pinpoint:UpdateRecommenderConfigurationResponse\"\
  ,\n    \"Attributes\": {\n      \"@id\": \"pinpoint:Attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"pinpoint:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedDate\": {\n      \"@id\": \"pinpoint:LastModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderIdType\": {\n      \"@id\": \"pinpoint:RecommendationProviderIdType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderRoleArn\": {\n      \"@id\": \"pinpoint:RecommendationProviderRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationProviderUri\": {\n      \"@id\": \"pinpoint:RecommendationProviderUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationTransformerUri\": {\n      \"@id\": \"pinpoint:RecommendationTransformerUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationsDisplayName\": {\n      \"@id\": \"pinpoint:RecommendationsDisplayName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"RecommendationsPerMessage\": {\n      \"@id\": \"pinpoint:RecommendationsPerMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetApplicationSettingsResponse\": \"pinpoint:GetApplicationSettingsResponse\",\n    \"CreateImportJobResponse\": \"pinpoint:CreateImportJobResponse\",\n    \"CreateExportJobRequest\": \"pinpoint:CreateExportJobRequest\",\n    \"GetImportJobsRequest\": \"pinpoint:GetImportJobsRequest\",\n    \"RemoveAttributesResponse\": \"pinpoint:RemoveAttributesResponse\",\n    \"AttributesResource\": {\n      \"@id\": \"pinpoint:AttributesResource\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-pinpoint/refs/heads/main/json-ld/amazon-pinpoint-analytics-context.jsonld
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
