---
api_specs:
- filename: amazon-snow-family.yaml
  format: yaml
  label: AWS Snow Device Management API
  slug: aws-snow-device-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/openapi/amazon-snow-family.yaml
class_count: 77
classes:
- UpdateJobShipmentStateRequest
- ListCompatibleImagesResult
- GetSnowballUsageRequest
- TGWOnDeviceServiceConfiguration
- ClusterListEntry
- UpdateLongTermPricingResult
- CancelJobRequest
- Ec2AmiResource
- NFSOnDeviceServiceConfiguration
- CreateReturnShippingLabelRequest
- UpdateClusterRequest
- DescribeAddressRequest
- CreateLongTermPricingResult
- ListJobsRequest
- DependentService
- ListCompatibleImagesRequest
- ListServiceVersionsResult
- LambdaResource
- GetSoftwareUpdatesResult
- CancelClusterRequest
- GetJobManifestRequest
- CancelJobResult
- CancelClusterResult
- DescribeReturnShippingLabelRequest
- ListLongTermPricingRequest
- DescribeJobRequest
- DescribeReturnShippingLabelResult
- ListPickupLocationsResult
- DataTransfer
- ListClustersResult
- ListClusterJobsRequest
- DescribeAddressesResult
- GetJobUnlockCodeResult
- CreateClusterRequest
- GetSnowballUsageResult
- GetJobUnlockCodeRequest
- UpdateClusterResult
- DescribeAddressesRequest
- ListClusterJobsResult
- S3Resource
- CreateClusterResult
- CreateAddressResult
- CreateJobResult
- TargetOnDeviceService
- DescribeClusterRequest
- CreateJobRequest
- Shipment
- DescribeAddressResult
- S3OnDeviceServiceConfiguration
- DescribeClusterResult
- CreateLongTermPricingRequest
- UpdateJobShipmentStateResult
- CreateReturnShippingLabelResult
- LongTermPricingListEntry
- ListServiceVersionsRequest
- JobLogs
- INDTaxDocuments
- JobListEntry
- UpdateLongTermPricingRequest
- CreateAddressRequest
- GetJobManifestResult
- EventTriggerDefinition
- EKSOnDeviceServiceConfiguration
- GetSoftwareUpdatesRequest
- ListLongTermPricingResult
- UpdateJobRequest
- DescribeJobResult
- ListClustersRequest
- ListJobsResult
- UpdateJobResult
- CompatibleImage
- JobResource
- ListPickupLocationsRequest
- Description
- Name
- Email
- Version
context_file: json-ld/amazon-snow-family-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/json-ld/amazon-snow-family-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Snow Family from Amazon Snow Family.
layout: jsonld
name: Amazon Snow Family Context
namespaces:
- prefix: aws
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: PickupDetails
  type: string
- container: ''
  name: ClusterMetadata
  type: string
- container: ''
  name: DeviceConfiguration
  type: string
- container: ''
  name: TaxDocuments
  type: string
- container: ''
  name: JobMetadata
  type: string
- container: ''
  name: WirelessConnection
  type: string
- container: ''
  name: SnowconeDeviceConfiguration
  type: string
- container: ''
  name: Address
  type: string
- container: ''
  name: KeyRange
  type: string
- container: ''
  name: ShippingDetails
  type: string
- container: ''
  name: OnDeviceServiceConfiguration
  type: string
- container: ''
  name: ServiceVersion
  type: string
- container: ''
  name: Notification
  type: string
- container: ''
  name: JobId
  type: string
- container: ''
  name: ShipmentState
  type: string
- container: ''
  name: CompatibleImages
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: StorageLimit
  type: string
- container: ''
  name: StorageUnit
  type: string
- container: ''
  name: ClusterId
  type: string
- container: ''
  name: ClusterState
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: AmiId
  type: string
- container: ''
  name: SnowballAmiId
  type: string
- container: ''
  name: ShippingOption
  type: string
- container: ''
  name: RoleARN
  type: string
- container: ''
  name: Resources
  type: string
- container: ''
  name: AddressId
  type: string
- container: ''
  name: ForwardingAddressId
  type: string
- container: ''
  name: LongTermPricingId
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: ServiceName
  type: string
- container: ''
  name: ServiceVersions
  type: string
- container: ''
  name: DependentServices
  type: string
- container: ''
  name: LambdaArn
  type: string
- container: ''
  name: EventTriggers
  type: string
- container: ''
  name: UpdatesURI
  type: string
- container: ''
  name: PhoneNumber
  type: string
- container: ''
  name: IdentificationNumber
  type: string
- container: ''
  name: IdentificationExpirationDate
  type: string
- container: ''
  name: IdentificationIssuingOrg
  type: string
- container: ''
  name: DevicePickupId
  type: string
- container: ''
  name: KmsKeyARN
  type: string
- container: ''
  name: JobType
  type: string
- container: ''
  name: SnowballType
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: ExpirationDate
  type: string
- container: ''
  name: ReturnShippingLabelURI
  type: string
- container: ''
  name: Addresses
  type: string
- container: ''
  name: BytesTransferred
  type: string
- container: ''
  name: ObjectsTransferred
  type: string
- container: ''
  name: TotalBytes
  type: string
- container: ''
  name: TotalObjects
  type: string
- container: ''
  name: ClusterListEntries
  type: string
- container: ''
  name: UnlockCode
  type: string
- container: ''
  name: RemoteManagement
  type: string
- container: ''
  name: InitialClusterSize
  type: string
- container: ''
  name: ForceCreateJobs
  type: string
- container: ''
  name: LongTermPricingIds
  type: string
- container: ''
  name: SnowballCapacityPreference
  type: string
- container: ''
  name: SnowballLimit
  type: string
- container: ''
  name: SnowballsInUse
  type: string
- container: ''
  name: IND
  type: string
- container: ''
  name: JobState
  type: string
- container: ''
  name: DataTransferProgress
  type: string
- container: ''
  name: JobLogInfo
  type: string
- container: ''
  name: ImpactLevel
  type: string
- container: ''
  name: SnowballId
  type: string
- container: ''
  name: JobListEntries
  type: string
- container: ''
  name: BucketArn
  type: string
- container: ''
  name: TargetOnDeviceServices
  type: string
- container: ''
  name: TransferOption
  type: string
- container: ''
  name: TrackingNumber
  type: string
- container: ''
  name: IsWifiEnabled
  type: string
- container: ''
  name: ServiceSize
  type: string
- container: ''
  name: FaultTolerance
  type: string
- container: ''
  name: LongTermPricingType
  type: string
- container: ''
  name: IsLongTermPricingAutoRenew
  type: string
- container: ''
  name: Company
  type: string
- container: ''
  name: Street1
  type: string
- container: ''
  name: Street2
  type: string
- container: ''
  name: Street3
  type: string
- container: ''
  name: City
  type: string
- container: ''
  name: StateOrProvince
  type: string
- container: ''
  name: PrefectureOrDistrict
  type: string
- container: ''
  name: Landmark
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: PostalCode
  type: string
- container: ''
  name: IsRestricted
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: LongTermPricingEndDate
  type: string
- container: ''
  name: LongTermPricingStartDate
  type: string
- container: ''
  name: CurrentActiveJob
  type: string
- container: ''
  name: ReplacementJob
  type: string
- container: ''
  name: LongTermPricingStatus
  type: string
- container: ''
  name: JobIds
  type: string
- container: ''
  name: BeginMarker
  type: string
- container: ''
  name: EndMarker
  type: string
- container: ''
  name: JobCompletionReportURI
  type: string
- container: ''
  name: JobSuccessLogURI
  type: string
- container: ''
  name: JobFailureLogURI
  type: string
- container: ''
  name: GSTIN
  type: string
- container: ''
  name: IsMaster
  type: string
- container: ''
  name: InboundShipment
  type: string
- container: ''
  name: OutboundShipment
  type: string
- container: ''
  name: NFSOnDeviceService
  type: string
- container: ''
  name: TGWOnDeviceService
  type: string
- container: ''
  name: EKSOnDeviceService
  type: string
- container: ''
  name: S3OnDeviceService
  type: string
- container: ''
  name: ManifestURI
  type: string
- container: ''
  name: EventResourceARN
  type: string
- container: ''
  name: KubernetesVersion
  type: string
- container: ''
  name: EKSAnywhereVersion
  type: string
- container: ''
  name: LongTermPricingEntries
  type: string
- container: ''
  name: SubJobMetadata
  type: string
- container: ''
  name: SnsTopicARN
  type: string
- container: ''
  name: JobStatesToNotify
  type: string
- container: ''
  name: NotifyAll
  type: string
- container: ''
  name: DevicePickupSnsTopicARN
  type: string
- container: ''
  name: S3Resources
  type: string
- container: ''
  name: LambdaResources
  type: string
- container: ''
  name: Ec2AmiResources
  type: string
property_count: 122
provider_name: Amazon Snow Family
provider_slug: amazon-snow-family
slug: amazon-snow-family-context
source_filename: amazon-snow-family-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"UpdateJobShipmentStateRequest\": \"aws:UpdateJobShipmentStateRequest\",\n    \"ListCompatibleImagesResult\": \"aws:ListCompatibleImagesResult\",\n    \"GetSnowballUsageRequest\": \"aws:GetSnowballUsageRequest\",\n    \"TGWOnDeviceServiceConfiguration\": \"aws:TGWOnDeviceServiceConfiguration\",\n    \"ClusterListEntry\": \"aws:ClusterListEntry\",\n    \"UpdateLongTermPricingResult\": \"aws:UpdateLongTermPricingResult\",\n    \"CancelJobRequest\": \"aws:CancelJobRequest\",\n    \"Ec2AmiResource\": \"aws:Ec2AmiResource\",\n    \"NFSOnDeviceServiceConfiguration\": \"aws:NFSOnDeviceServiceConfiguration\",\n    \"CreateReturnShippingLabelRequest\": \"aws:CreateReturnShippingLabelRequest\",\n    \"UpdateClusterRequest\": \"aws:UpdateClusterRequest\"\
  ,\n    \"DescribeAddressRequest\": \"aws:DescribeAddressRequest\",\n    \"CreateLongTermPricingResult\": \"aws:CreateLongTermPricingResult\",\n    \"ListJobsRequest\": \"aws:ListJobsRequest\",\n    \"DependentService\": \"aws:DependentService\",\n    \"ListCompatibleImagesRequest\": \"aws:ListCompatibleImagesRequest\",\n    \"ListServiceVersionsResult\": \"aws:ListServiceVersionsResult\",\n    \"LambdaResource\": \"aws:LambdaResource\",\n    \"GetSoftwareUpdatesResult\": \"aws:GetSoftwareUpdatesResult\",\n    \"PickupDetails\": {\n      \"@id\": \"aws:PickupDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelClusterRequest\": \"aws:CancelClusterRequest\",\n    \"ClusterMetadata\": {\n      \"@id\": \"aws:ClusterMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJobManifestRequest\": \"aws:GetJobManifestRequest\",\n    \"CancelJobResult\": \"aws:CancelJobResult\",\n    \"CancelClusterResult\": \"aws:CancelClusterResult\",\n    \"DescribeReturnShippingLabelRequest\"\
  : \"aws:DescribeReturnShippingLabelRequest\",\n    \"ListLongTermPricingRequest\": \"aws:ListLongTermPricingRequest\",\n    \"DescribeJobRequest\": \"aws:DescribeJobRequest\",\n    \"DescribeReturnShippingLabelResult\": \"aws:DescribeReturnShippingLabelResult\",\n    \"ListPickupLocationsResult\": \"aws:ListPickupLocationsResult\",\n    \"DataTransfer\": \"aws:DataTransfer\",\n    \"ListClustersResult\": \"aws:ListClustersResult\",\n    \"ListClusterJobsRequest\": \"aws:ListClusterJobsRequest\",\n    \"DescribeAddressesResult\": \"aws:DescribeAddressesResult\",\n    \"GetJobUnlockCodeResult\": \"aws:GetJobUnlockCodeResult\",\n    \"CreateClusterRequest\": \"aws:CreateClusterRequest\",\n    \"GetSnowballUsageResult\": \"aws:GetSnowballUsageResult\",\n    \"GetJobUnlockCodeRequest\": \"aws:GetJobUnlockCodeRequest\",\n    \"DeviceConfiguration\": {\n      \"@id\": \"aws:DeviceConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateClusterResult\": \"aws:UpdateClusterResult\"\
  ,\n    \"TaxDocuments\": {\n      \"@id\": \"aws:TaxDocuments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeAddressesRequest\": \"aws:DescribeAddressesRequest\",\n    \"JobMetadata\": {\n      \"@id\": \"aws:JobMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListClusterJobsResult\": \"aws:ListClusterJobsResult\",\n    \"S3Resource\": \"aws:S3Resource\",\n    \"CreateClusterResult\": \"aws:CreateClusterResult\",\n    \"CreateAddressResult\": \"aws:CreateAddressResult\",\n    \"CreateJobResult\": \"aws:CreateJobResult\",\n    \"TargetOnDeviceService\": \"aws:TargetOnDeviceService\",\n    \"DescribeClusterRequest\": \"aws:DescribeClusterRequest\",\n    \"CreateJobRequest\": \"aws:CreateJobRequest\",\n    \"Shipment\": \"aws:Shipment\",\n    \"DescribeAddressResult\": \"aws:DescribeAddressResult\",\n    \"WirelessConnection\": {\n      \"@id\": \"aws:WirelessConnection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3OnDeviceServiceConfiguration\": \"aws:S3OnDeviceServiceConfiguration\"\
  ,\n    \"SnowconeDeviceConfiguration\": {\n      \"@id\": \"aws:SnowconeDeviceConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeClusterResult\": \"aws:DescribeClusterResult\",\n    \"CreateLongTermPricingRequest\": \"aws:CreateLongTermPricingRequest\",\n    \"UpdateJobShipmentStateResult\": \"aws:UpdateJobShipmentStateResult\",\n    \"CreateReturnShippingLabelResult\": \"aws:CreateReturnShippingLabelResult\",\n    \"Address\": {\n      \"@id\": \"aws:Address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingListEntry\": \"aws:LongTermPricingListEntry\",\n    \"ListServiceVersionsRequest\": \"aws:ListServiceVersionsRequest\",\n    \"KeyRange\": {\n      \"@id\": \"aws:KeyRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobLogs\": \"aws:JobLogs\",\n    \"INDTaxDocuments\": \"aws:INDTaxDocuments\",\n    \"JobListEntry\": \"aws:JobListEntry\",\n    \"ShippingDetails\": {\n      \"@id\": \"aws:ShippingDetails\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"UpdateLongTermPricingRequest\": \"aws:UpdateLongTermPricingRequest\",\n    \"CreateAddressRequest\": \"aws:CreateAddressRequest\",\n    \"OnDeviceServiceConfiguration\": {\n      \"@id\": \"aws:OnDeviceServiceConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceVersion\": {\n      \"@id\": \"aws:ServiceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetJobManifestResult\": \"aws:GetJobManifestResult\",\n    \"EventTriggerDefinition\": \"aws:EventTriggerDefinition\",\n    \"EKSOnDeviceServiceConfiguration\": \"aws:EKSOnDeviceServiceConfiguration\",\n    \"GetSoftwareUpdatesRequest\": \"aws:GetSoftwareUpdatesRequest\",\n    \"ListLongTermPricingResult\": \"aws:ListLongTermPricingResult\",\n    \"UpdateJobRequest\": \"aws:UpdateJobRequest\",\n    \"DescribeJobResult\": \"aws:DescribeJobResult\",\n    \"ListClustersRequest\": \"aws:ListClustersRequest\",\n    \"ListJobsResult\": \"aws:ListJobsResult\",\n    \"UpdateJobResult\": \"aws:UpdateJobResult\"\
  ,\n    \"Notification\": {\n      \"@id\": \"aws:Notification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompatibleImage\": \"aws:CompatibleImage\",\n    \"JobResource\": \"aws:JobResource\",\n    \"ListPickupLocationsRequest\": \"aws:ListPickupLocationsRequest\",\n    \"JobId\": {\n      \"@id\": \"aws:JobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShipmentState\": {\n      \"@id\": \"aws:ShipmentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompatibleImages\": {\n      \"@id\": \"aws:CompatibleImages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageLimit\": {\n      \"@id\": \"aws:StorageLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageUnit\": {\n      \"@id\": \"aws:StorageUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterId\": {\n      \"@id\": \"aws:ClusterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterState\"\
  : {\n      \"@id\": \"aws:ClusterState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"aws:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": \"schema:description\",\n    \"AmiId\": {\n      \"@id\": \"aws:AmiId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballAmiId\": {\n      \"@id\": \"aws:SnowballAmiId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShippingOption\": {\n      \"@id\": \"aws:ShippingOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleARN\": {\n      \"@id\": \"aws:RoleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Resources\": {\n      \"@id\": \"aws:Resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddressId\": {\n      \"@id\": \"aws:AddressId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForwardingAddressId\": {\n      \"@id\": \"aws:ForwardingAddressId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingId\": {\n      \"@id\": \"aws:LongTermPricingId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"aws:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceName\": {\n      \"@id\": \"aws:ServiceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceVersions\": {\n      \"@id\": \"aws:ServiceVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DependentServices\": {\n      \"@id\": \"aws:DependentServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LambdaArn\": {\n      \"@id\": \"aws:LambdaArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventTriggers\": {\n      \"@id\": \"aws:EventTriggers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatesURI\": {\n      \"@id\": \"aws:UpdatesURI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": \"schema:name\",\n    \"PhoneNumber\": {\n      \"@id\": \"aws:PhoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Email\": \"schema:email\",\n    \"IdentificationNumber\": {\n      \"@id\": \"aws:IdentificationNumber\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentificationExpirationDate\": {\n      \"@id\": \"aws:IdentificationExpirationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentificationIssuingOrg\": {\n      \"@id\": \"aws:IdentificationIssuingOrg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DevicePickupId\": {\n      \"@id\": \"aws:DevicePickupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyARN\": {\n      \"@id\": \"aws:KmsKeyARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobType\": {\n      \"@id\": \"aws:JobType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballType\": {\n      \"@id\": \"aws:SnowballType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"aws:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpirationDate\": {\n      \"@id\": \"aws:ExpirationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReturnShippingLabelURI\": {\n      \"@id\": \"aws:ReturnShippingLabelURI\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"Addresses\": {\n      \"@id\": \"aws:Addresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BytesTransferred\": {\n      \"@id\": \"aws:BytesTransferred\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ObjectsTransferred\": {\n      \"@id\": \"aws:ObjectsTransferred\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalBytes\": {\n      \"@id\": \"aws:TotalBytes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TotalObjects\": {\n      \"@id\": \"aws:TotalObjects\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClusterListEntries\": {\n      \"@id\": \"aws:ClusterListEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnlockCode\": {\n      \"@id\": \"aws:UnlockCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RemoteManagement\": {\n      \"@id\": \"aws:RemoteManagement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InitialClusterSize\": {\n      \"@id\": \"aws:InitialClusterSize\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ForceCreateJobs\": {\n      \"@id\": \"aws:ForceCreateJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingIds\": {\n      \"@id\": \"aws:LongTermPricingIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballCapacityPreference\": {\n      \"@id\": \"aws:SnowballCapacityPreference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballLimit\": {\n      \"@id\": \"aws:SnowballLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballsInUse\": {\n      \"@id\": \"aws:SnowballsInUse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IND\": {\n      \"@id\": \"aws:IND\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobState\": {\n      \"@id\": \"aws:JobState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DataTransferProgress\": {\n      \"@id\": \"aws:DataTransferProgress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobLogInfo\": {\n      \"@id\": \"aws:JobLogInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpactLevel\"\
  : {\n      \"@id\": \"aws:ImpactLevel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnowballId\": {\n      \"@id\": \"aws:SnowballId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobListEntries\": {\n      \"@id\": \"aws:JobListEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketArn\": {\n      \"@id\": \"aws:BucketArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetOnDeviceServices\": {\n      \"@id\": \"aws:TargetOnDeviceServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TransferOption\": {\n      \"@id\": \"aws:TransferOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrackingNumber\": {\n      \"@id\": \"aws:TrackingNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsWifiEnabled\": {\n      \"@id\": \"aws:IsWifiEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceSize\": {\n      \"@id\": \"aws:ServiceSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FaultTolerance\": {\n      \"@id\": \"aws:FaultTolerance\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingType\": {\n      \"@id\": \"aws:LongTermPricingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsLongTermPricingAutoRenew\": {\n      \"@id\": \"aws:IsLongTermPricingAutoRenew\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Company\": {\n      \"@id\": \"aws:Company\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Street1\": {\n      \"@id\": \"aws:Street1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Street2\": {\n      \"@id\": \"aws:Street2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Street3\": {\n      \"@id\": \"aws:Street3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"City\": {\n      \"@id\": \"aws:City\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StateOrProvince\": {\n      \"@id\": \"aws:StateOrProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrefectureOrDistrict\": {\n      \"@id\": \"aws:PrefectureOrDistrict\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Landmark\"\
  : {\n      \"@id\": \"aws:Landmark\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"aws:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PostalCode\": {\n      \"@id\": \"aws:PostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsRestricted\": {\n      \"@id\": \"aws:IsRestricted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingEndDate\": {\n      \"@id\": \"aws:LongTermPricingEndDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingStartDate\": {\n      \"@id\": \"aws:LongTermPricingStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentActiveJob\": {\n      \"@id\": \"aws:CurrentActiveJob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplacementJob\": {\n      \"@id\": \"aws:ReplacementJob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongTermPricingStatus\": {\n      \"@id\": \"aws:LongTermPricingStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"JobIds\": {\n      \"@id\": \"aws:JobIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BeginMarker\": {\n      \"@id\": \"aws:BeginMarker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndMarker\": {\n      \"@id\": \"aws:EndMarker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobCompletionReportURI\": {\n      \"@id\": \"aws:JobCompletionReportURI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobSuccessLogURI\": {\n      \"@id\": \"aws:JobSuccessLogURI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobFailureLogURI\": {\n      \"@id\": \"aws:JobFailureLogURI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GSTIN\": {\n      \"@id\": \"aws:GSTIN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsMaster\": {\n      \"@id\": \"aws:IsMaster\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InboundShipment\": {\n      \"@id\": \"aws:InboundShipment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutboundShipment\"\
  : {\n      \"@id\": \"aws:OutboundShipment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NFSOnDeviceService\": {\n      \"@id\": \"aws:NFSOnDeviceService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TGWOnDeviceService\": {\n      \"@id\": \"aws:TGWOnDeviceService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EKSOnDeviceService\": {\n      \"@id\": \"aws:EKSOnDeviceService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3OnDeviceService\": {\n      \"@id\": \"aws:S3OnDeviceService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": \"schema:version\",\n    \"ManifestURI\": {\n      \"@id\": \"aws:ManifestURI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventResourceARN\": {\n      \"@id\": \"aws:EventResourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KubernetesVersion\": {\n      \"@id\": \"aws:KubernetesVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EKSAnywhereVersion\": {\n      \"@id\": \"aws:EKSAnywhereVersion\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"LongTermPricingEntries\": {\n      \"@id\": \"aws:LongTermPricingEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubJobMetadata\": {\n      \"@id\": \"aws:SubJobMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnsTopicARN\": {\n      \"@id\": \"aws:SnsTopicARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobStatesToNotify\": {\n      \"@id\": \"aws:JobStatesToNotify\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotifyAll\": {\n      \"@id\": \"aws:NotifyAll\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DevicePickupSnsTopicARN\": {\n      \"@id\": \"aws:DevicePickupSnsTopicARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Resources\": {\n      \"@id\": \"aws:S3Resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LambdaResources\": {\n      \"@id\": \"aws:LambdaResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ec2AmiResources\": {\n      \"@id\": \"aws:Ec2AmiResources\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-snow-family/refs/heads/main/json-ld/amazon-snow-family-context.jsonld
tags:
- AWS
- Data Migration
- Edge Computing
- Offline Transfer
- Physical Appliance
- JSON-LD
- Linked Data
- Semantic Web
---
