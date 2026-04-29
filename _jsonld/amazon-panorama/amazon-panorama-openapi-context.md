---
api_specs:
- filename: amazon-panorama-openapi.yml
  format: yaml
  label: AWS Panorama API
  slug: aws-panorama-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/openapi/amazon-panorama-openapi.yml
class_count: 169
classes:
- AccessDeniedException
- AlternateSoftwareMetadata
- ApplicationInstance
- ApplicationInstanceArn
- ApplicationInstanceHealthStatus
- ApplicationInstanceName
- ApplicationInstanceStatus
- ApplicationInstanceStatusDescription
- Boolean
- ConflictException
- CreateApplicationInstanceRequest
- CreateApplicationInstanceResponse
- CreateJobForDevicesRequest
- CreateJobForDevicesResponse
- CreateNodeFromTemplateJobRequest
- CreateNodeFromTemplateJobResponse
- CreatePackageImportJobRequest
- CreatePackageImportJobResponse
- CreatePackageRequest
- CreatePackageResponse
- DeleteDeviceRequest
- DeleteDeviceResponse
- DeletePackageRequest
- DeletePackageResponse
- DeregisterPackageVersionRequest
- DeregisterPackageVersionResponse
- DescribeApplicationInstanceDetailsRequest
- DescribeApplicationInstanceDetailsResponse
- DescribeApplicationInstanceRequest
- DescribeApplicationInstanceResponse
- DescribeDeviceJobRequest
- DescribeDeviceJobResponse
- DescribeDeviceRequest
- DescribeDeviceResponse
- DescribeNodeFromTemplateJobRequest
- DescribeNodeFromTemplateJobResponse
- DescribeNodeRequest
- DescribeNodeResponse
- DescribePackageImportJobRequest
- DescribePackageImportJobResponse
- DescribePackageRequest
- DescribePackageResponse
- DescribePackageVersionRequest
- DescribePackageVersionResponse
- Device
- DeviceBrand
- DeviceIdList
- DeviceJob
- DeviceJobList
- DeviceList
- DeviceSerialNumber
- DeviceStatus
- DnsList
- EthernetPayload
- EthernetStatus
- InputPortList
- InternalServerException
- IpAddressOrServerName
- Job
- JobList
- JobResourceTags
- JobResourceType
- JobTagsList
- ListApplicationInstanceDependenciesRequest
- ListApplicationInstanceDependenciesResponse
- ListApplicationInstanceNodeInstancesRequest
- ListApplicationInstanceNodeInstancesResponse
- ListApplicationInstancesRequest
- ListApplicationInstancesResponse
- ListDevicesJobsRequest
- ListDevicesJobsResponse
- ListDevicesRequest
- ListDevicesResponse
- ListDevicesSortBy
- ListNodeFromTemplateJobsRequest
- ListNodeFromTemplateJobsResponse
- ListNodesRequest
- ListNodesResponse
- ListPackageImportJobsRequest
- ListPackageImportJobsResponse
- ListPackagesRequest
- ListPackagesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ManifestOverridesPayloadData
- ManifestPayloadData
- MarkLatestPatch
- MaxSize25
- NameFilter
- NetworkConnectionStatus
- NetworkPayload
- NetworkStatus
- Node
- NodeAssetName
- NodeCategory
- NodeFromTemplateJob
- NodeFromTemplateJobList
- NodeFromTemplateJobStatus
- NodeFromTemplateJobStatusMessage
- NodeInputPort
- NodeInstance
- NodeInstanceStatus
- NodeOutputPort
- NodePackageArn
- NodePackageId
- NodePackageName
- NodePackagePatchVersion
- NodePackageVersion
- NodeSignal
- NodeSignalList
- NodeSignalValue
- NodesList
- NtpPayload
- NtpServerList
- Object
- OutPutS3Location
- OutputPortList
- PackageImportJob
- PackageImportJobInputConfig
- PackageImportJobList
- PackageImportJobOutput
- PackageImportJobOutputConfig
- PackageImportJobStatus
- PackageImportJobStatusMessage
- PackageImportJobType
- PackageList
- PackageListItem
- PackageObject
- PackageOwnerAccount
- PackageVersionStatus
- PackageVersionStatusDescription
- PortDefaultValue
- PortName
- PortType
- PrincipalArn
- PrincipalArnsList
- ProvisionDeviceRequest
- ProvisionDeviceResponse
- RegisterPackageVersionRequest
- RegisterPackageVersionResponse
- RemoveApplicationInstanceRequest
- RemoveApplicationInstanceResponse
- ReportedRuntimeContextState
- ReportedRuntimeContextStates
- ResourceArn
- ResourceNotFoundException
- ServiceQuotaExceededException
- SignalApplicationInstanceNodeInstancesRequest
- SignalApplicationInstanceNodeInstancesResponse
- SortOrder
- StatusFilter
- TagKey
- TagKeyList
- TagMap
- TagResourceRequest
- TagResourceResponse
- TagValue
- TemplateKey
- TemplateParametersMap
- TemplateValue
- TimeStamp
- Token
- UntagResourceRequest
- UntagResourceResponse
- UpdateCreatedTime
- UpdateDeviceMetadataRequest
- UpdateDeviceMetadataResponse
- UpdateProgress
- ValidationException
context_file: json-ld/amazon-panorama-openapi-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/json-ld/amazon-panorama-openapi-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Panorama Openapi from Amazon Panorama.
layout: jsonld
name: Amazon Panorama Openapi Context
namespaces:
- prefix: panorama
  uri: https://panorama.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AlternateSoftwares
  type: string
- container: ''
  name: ApplicationInstanceId
  type: string
- container: ''
  name: ApplicationInstances
  type: string
- container: ''
  name: Bucket
  type: string
- container: ''
  name: BucketName
  type: string
- container: ''
  name: Certificates
  type: string
- container: ''
  name: ClientToken
  type: string
- container: ''
  name: ConnectionType
  type: string
- container: ''
  name: CreatedTime
  type: string
- container: ''
  name: CurrentSoftware
  type: string
- container: ''
  name: DefaultGateway
  type: string
- container: ''
  name: DefaultRuntimeContextDevice
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: DesiredState
  type: string
- container: ''
  name: DeviceAggregatedStatus
  type: string
- container: ''
  name: DeviceArn
  type: string
- container: ''
  name: DeviceConnectionStatus
  type: string
- container: ''
  name: DeviceId
  type: string
- container: ''
  name: DeviceJobConfig
  type: string
- container: ''
  name: DeviceName
  type: string
- container: ''
  name: DeviceReportedStatus
  type: string
- container: ''
  name: DeviceType
  type: string
- container: ''
  name: Dns
  type: string
- container: ''
  name: HwAddress
  type: string
- container: ''
  name: ImageVersion
  type: string
- container: ''
  name: IotThingName
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: JobId
  type: string
- container: ''
  name: JobType
  type: string
- container: ''
  name: LastUpdatedTime
  type: string
- container: ''
  name: LatestAlternateSoftware
  type: string
- container: ''
  name: LatestDeviceJob
  type: string
- container: ''
  name: LatestSoftware
  type: string
- container: ''
  name: LeaseExpirationTime
  type: string
- container: ''
  name: ManifestOverridesPayload
  type: string
- container: ''
  name: ManifestPayload
  type: string
- container: ''
  name: Mask
  type: string
- container: ''
  name: MaxConnections
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: NodeId
  type: string
- container: ''
  name: NodeInstanceId
  type: string
- container: ''
  name: NodeInstances
  type: string
- container: ''
  name: NodeInterface
  type: string
- container: ''
  name: NodeName
  type: string
- container: ''
  name: NtpServerName
  type: string
- container: ''
  name: NtpStatus
  type: string
- container: ''
  name: OTAJobConfig
  type: string
- container: ''
  name: ObjectKey
  type: string
- container: ''
  name: PackageObjects
  type: string
- container: ''
  name: PackageVersionInputConfig
  type: string
- container: ''
  name: PackageVersionOutputConfig
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: RuntimeContextName
  type: string
- container: ''
  name: RuntimeRoleArn
  type: string
- container: ''
  name: S3Location
  type: string
- container: ''
  name: StaticIpConnectionInfo
  type: string
- container: ''
  name: StorageLocation
  type: string
- container: ''
  name: TemplateType
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: AllowMajorVersionUpdate
  type: string
- container: ''
  name: ApplicationInstanceIdToReplace
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: AssetName
  type: string
- container: ''
  name: BinaryPrefixLocation
  type: string
- container: ''
  name: Brand
  type: string
- container: ''
  name: Category
  type: string
- container: ''
  name: ConnectionStatus
  type: string
- container: ''
  name: CurrentNetworkingStatus
  type: string
- container: ''
  name: CurrentStatus
  type: string
- container: ''
  name: DefaultRuntimeContextDeviceName
  type: string
- container: ''
  name: DefaultValue
  type: string
- container: ''
  name: DeviceIds
  type: string
- container: ''
  name: DeviceJobs
  type: string
- container: ''
  name: DeviceReportedTime
  type: string
- container: ''
  name: Devices
  type: string
- container: ''
  name: Ethernet0
  type: string
- container: ''
  name: Ethernet0Status
  type: string
- container: ''
  name: Ethernet1
  type: string
- container: ''
  name: Ethernet1Status
  type: string
- container: ''
  name: GeneratedPrefixLocation
  type: string
- container: ''
  name: HealthStatus
  type: string
- container: ''
  name: InputConfig
  type: string
- container: ''
  name: Inputs
  type: string
- container: ''
  name: IsLatestPatch
  type: string
- container: ''
  name: JobTags
  type: string
- container: ''
  name: Jobs
  type: string
- container: ''
  name: ManifestPrefixLocation
  type: string
- container: ''
  name: MarkLatest
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: NetworkingConfiguration
  type: string
- container: ''
  name: NodeDescription
  type: string
- container: ''
  name: NodeFromTemplateJobs
  type: string
- container: ''
  name: NodeSignals
  type: string
- container: ''
  name: Nodes
  type: string
- container: ''
  name: Ntp
  type: string
- container: ''
  name: NtpServers
  type: string
- container: ''
  name: Output
  type: string
- container: ''
  name: OutputConfig
  type: string
- container: ''
  name: OutputPackageName
  type: string
- container: ''
  name: OutputPackageVersion
  type: string
- container: ''
  name: OutputS3Location
  type: string
- container: ''
  name: Outputs
  type: string
- container: ''
  name: OwnerAccount
  type: string
- container: ''
  name: PackageArn
  type: string
- container: ''
  name: PackageId
  type: string
- container: ''
  name: PackageImportJobs
  type: string
- container: ''
  name: PackageName
  type: string
- container: ''
  name: PackagePatchVersion
  type: string
- container: ''
  name: PackageVersion
  type: string
- container: ''
  name: Packages
  type: string
- container: ''
  name: PatchVersion
  type: string
- container: ''
  name: PayloadData
  type: string
- container: ''
  name: ProvisioningStatus
  type: string
- container: ''
  name: ReadAccessPrincipalArns
  type: string
- container: ''
  name: RegisteredTime
  type: string
- container: ''
  name: RepoPrefixLocation
  type: string
- container: ''
  name: ResourceType
  type: string
- container: ''
  name: RuntimeContextStates
  type: string
- container: ''
  name: SerialNumber
  type: string
- container: ''
  name: Signal
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: StatusDescription
  type: string
- container: ''
  name: StatusMessage
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: TemplateParameters
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: WriteAccessPrincipalArns
  type: string
property_count: 127
provider_name: Amazon Panorama
provider_slug: amazon-panorama
slug: amazon-panorama-openapi-context
source_filename: amazon-panorama-openapi-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"panorama\": \"https://panorama.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessDeniedException\": \"panorama:AccessDeniedException\",\n    \"AlternateSoftwareMetadata\": \"panorama:AlternateSoftwareMetadata\",\n    \"AlternateSoftwares\": {\n      \"@id\": \"panorama:AlternateSoftwares\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInstance\": \"panorama:ApplicationInstance\",\n    \"ApplicationInstanceArn\": \"panorama:ApplicationInstanceArn\",\n    \"ApplicationInstanceHealthStatus\": \"panorama:ApplicationInstanceHealthStatus\",\n    \"ApplicationInstanceId\": {\n      \"@id\": \"panorama:ApplicationInstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInstanceName\": \"panorama:ApplicationInstanceName\",\n    \"ApplicationInstanceStatus\": \"panorama:ApplicationInstanceStatus\"\
  ,\n    \"ApplicationInstanceStatusDescription\": \"panorama:ApplicationInstanceStatusDescription\",\n    \"ApplicationInstances\": {\n      \"@id\": \"panorama:ApplicationInstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Boolean\": \"panorama:Boolean\",\n    \"Bucket\": {\n      \"@id\": \"panorama:Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketName\": {\n      \"@id\": \"panorama:BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Certificates\": {\n      \"@id\": \"panorama:Certificates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientToken\": {\n      \"@id\": \"panorama:ClientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConflictException\": \"panorama:ConflictException\",\n    \"ConnectionType\": {\n      \"@id\": \"panorama:ConnectionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateApplicationInstanceRequest\": \"panorama:CreateApplicationInstanceRequest\",\n    \"CreateApplicationInstanceResponse\": \"panorama:CreateApplicationInstanceResponse\"\
  ,\n    \"CreateJobForDevicesRequest\": \"panorama:CreateJobForDevicesRequest\",\n    \"CreateJobForDevicesResponse\": \"panorama:CreateJobForDevicesResponse\",\n    \"CreateNodeFromTemplateJobRequest\": \"panorama:CreateNodeFromTemplateJobRequest\",\n    \"CreateNodeFromTemplateJobResponse\": \"panorama:CreateNodeFromTemplateJobResponse\",\n    \"CreatePackageImportJobRequest\": \"panorama:CreatePackageImportJobRequest\",\n    \"CreatePackageImportJobResponse\": \"panorama:CreatePackageImportJobResponse\",\n    \"CreatePackageRequest\": \"panorama:CreatePackageRequest\",\n    \"CreatePackageResponse\": \"panorama:CreatePackageResponse\",\n    \"CreatedTime\": {\n      \"@id\": \"panorama:CreatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentSoftware\": {\n      \"@id\": \"panorama:CurrentSoftware\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultGateway\": {\n      \"@id\": \"panorama:DefaultGateway\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultRuntimeContextDevice\"\
  : {\n      \"@id\": \"panorama:DefaultRuntimeContextDevice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteDeviceRequest\": \"panorama:DeleteDeviceRequest\",\n    \"DeleteDeviceResponse\": \"panorama:DeleteDeviceResponse\",\n    \"DeletePackageRequest\": \"panorama:DeletePackageRequest\",\n    \"DeletePackageResponse\": \"panorama:DeletePackageResponse\",\n    \"DeregisterPackageVersionRequest\": \"panorama:DeregisterPackageVersionRequest\",\n    \"DeregisterPackageVersionResponse\": \"panorama:DeregisterPackageVersionResponse\",\n    \"DescribeApplicationInstanceDetailsRequest\": \"panorama:DescribeApplicationInstanceDetailsRequest\",\n    \"DescribeApplicationInstanceDetailsResponse\": \"panorama:DescribeApplicationInstanceDetailsResponse\",\n    \"DescribeApplicationInstanceRequest\": \"panorama:DescribeApplicationInstanceRequest\",\n    \"DescribeApplicationInstanceResponse\": \"panorama:DescribeApplicationInstanceResponse\",\n    \"DescribeDeviceJobRequest\": \"panorama:DescribeDeviceJobRequest\"\
  ,\n    \"DescribeDeviceJobResponse\": \"panorama:DescribeDeviceJobResponse\",\n    \"DescribeDeviceRequest\": \"panorama:DescribeDeviceRequest\",\n    \"DescribeDeviceResponse\": \"panorama:DescribeDeviceResponse\",\n    \"DescribeNodeFromTemplateJobRequest\": \"panorama:DescribeNodeFromTemplateJobRequest\",\n    \"DescribeNodeFromTemplateJobResponse\": \"panorama:DescribeNodeFromTemplateJobResponse\",\n    \"DescribeNodeRequest\": \"panorama:DescribeNodeRequest\",\n    \"DescribeNodeResponse\": \"panorama:DescribeNodeResponse\",\n    \"DescribePackageImportJobRequest\": \"panorama:DescribePackageImportJobRequest\",\n    \"DescribePackageImportJobResponse\": \"panorama:DescribePackageImportJobResponse\",\n    \"DescribePackageRequest\": \"panorama:DescribePackageRequest\",\n    \"DescribePackageResponse\": \"panorama:DescribePackageResponse\",\n    \"DescribePackageVersionRequest\": \"panorama:DescribePackageVersionRequest\",\n    \"DescribePackageVersionResponse\": \"panorama:DescribePackageVersionResponse\"\
  ,\n    \"Description\": {\n      \"@id\": \"panorama:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredState\": {\n      \"@id\": \"panorama:DesiredState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Device\": \"panorama:Device\",\n    \"DeviceAggregatedStatus\": {\n      \"@id\": \"panorama:DeviceAggregatedStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceArn\": {\n      \"@id\": \"panorama:DeviceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceBrand\": \"panorama:DeviceBrand\",\n    \"DeviceConnectionStatus\": {\n      \"@id\": \"panorama:DeviceConnectionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceId\": {\n      \"@id\": \"panorama:DeviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceIdList\": \"panorama:DeviceIdList\",\n    \"DeviceJob\": \"panorama:DeviceJob\",\n    \"DeviceJobConfig\": {\n      \"@id\": \"panorama:DeviceJobConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceJobList\": \"\
  panorama:DeviceJobList\",\n    \"DeviceList\": \"panorama:DeviceList\",\n    \"DeviceName\": {\n      \"@id\": \"panorama:DeviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceReportedStatus\": {\n      \"@id\": \"panorama:DeviceReportedStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceSerialNumber\": \"panorama:DeviceSerialNumber\",\n    \"DeviceStatus\": \"panorama:DeviceStatus\",\n    \"DeviceType\": {\n      \"@id\": \"panorama:DeviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dns\": {\n      \"@id\": \"panorama:Dns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsList\": \"panorama:DnsList\",\n    \"EthernetPayload\": \"panorama:EthernetPayload\",\n    \"EthernetStatus\": \"panorama:EthernetStatus\",\n    \"HwAddress\": {\n      \"@id\": \"panorama:HwAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageVersion\": {\n      \"@id\": \"panorama:ImageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputPortList\": \"panorama:InputPortList\"\
  ,\n    \"InternalServerException\": \"panorama:InternalServerException\",\n    \"IotThingName\": {\n      \"@id\": \"panorama:IotThingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpAddress\": {\n      \"@id\": \"panorama:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpAddressOrServerName\": \"panorama:IpAddressOrServerName\",\n    \"Job\": \"panorama:Job\",\n    \"JobId\": {\n      \"@id\": \"panorama:JobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobList\": \"panorama:JobList\",\n    \"JobResourceTags\": \"panorama:JobResourceTags\",\n    \"JobResourceType\": \"panorama:JobResourceType\",\n    \"JobTagsList\": \"panorama:JobTagsList\",\n    \"JobType\": {\n      \"@id\": \"panorama:JobType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedTime\": {\n      \"@id\": \"panorama:LastUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LatestAlternateSoftware\": {\n      \"@id\": \"panorama:LatestAlternateSoftware\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"LatestDeviceJob\": {\n      \"@id\": \"panorama:LatestDeviceJob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LatestSoftware\": {\n      \"@id\": \"panorama:LatestSoftware\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LeaseExpirationTime\": {\n      \"@id\": \"panorama:LeaseExpirationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListApplicationInstanceDependenciesRequest\": \"panorama:ListApplicationInstanceDependenciesRequest\",\n    \"ListApplicationInstanceDependenciesResponse\": \"panorama:ListApplicationInstanceDependenciesResponse\",\n    \"ListApplicationInstanceNodeInstancesRequest\": \"panorama:ListApplicationInstanceNodeInstancesRequest\",\n    \"ListApplicationInstanceNodeInstancesResponse\": \"panorama:ListApplicationInstanceNodeInstancesResponse\",\n    \"ListApplicationInstancesRequest\": \"panorama:ListApplicationInstancesRequest\",\n    \"ListApplicationInstancesResponse\": \"panorama:ListApplicationInstancesResponse\"\
  ,\n    \"ListDevicesJobsRequest\": \"panorama:ListDevicesJobsRequest\",\n    \"ListDevicesJobsResponse\": \"panorama:ListDevicesJobsResponse\",\n    \"ListDevicesRequest\": \"panorama:ListDevicesRequest\",\n    \"ListDevicesResponse\": \"panorama:ListDevicesResponse\",\n    \"ListDevicesSortBy\": \"panorama:ListDevicesSortBy\",\n    \"ListNodeFromTemplateJobsRequest\": \"panorama:ListNodeFromTemplateJobsRequest\",\n    \"ListNodeFromTemplateJobsResponse\": \"panorama:ListNodeFromTemplateJobsResponse\",\n    \"ListNodesRequest\": \"panorama:ListNodesRequest\",\n    \"ListNodesResponse\": \"panorama:ListNodesResponse\",\n    \"ListPackageImportJobsRequest\": \"panorama:ListPackageImportJobsRequest\",\n    \"ListPackageImportJobsResponse\": \"panorama:ListPackageImportJobsResponse\",\n    \"ListPackagesRequest\": \"panorama:ListPackagesRequest\",\n    \"ListPackagesResponse\": \"panorama:ListPackagesResponse\",\n    \"ListTagsForResourceRequest\": \"panorama:ListTagsForResourceRequest\",\n\
  \    \"ListTagsForResourceResponse\": \"panorama:ListTagsForResourceResponse\",\n    \"ManifestOverridesPayload\": {\n      \"@id\": \"panorama:ManifestOverridesPayload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManifestOverridesPayloadData\": \"panorama:ManifestOverridesPayloadData\",\n    \"ManifestPayload\": {\n      \"@id\": \"panorama:ManifestPayload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManifestPayloadData\": \"panorama:ManifestPayloadData\",\n    \"MarkLatestPatch\": \"panorama:MarkLatestPatch\",\n    \"Mask\": {\n      \"@id\": \"panorama:Mask\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxConnections\": {\n      \"@id\": \"panorama:MaxConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxSize25\": \"panorama:MaxSize25\",\n    \"NameFilter\": \"panorama:NameFilter\",\n    \"NetworkConnectionStatus\": \"panorama:NetworkConnectionStatus\",\n    \"NetworkPayload\": \"panorama:NetworkPayload\",\n    \"NetworkStatus\": \"panorama:NetworkStatus\"\
  ,\n    \"NextToken\": {\n      \"@id\": \"panorama:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Node\": \"panorama:Node\",\n    \"NodeAssetName\": \"panorama:NodeAssetName\",\n    \"NodeCategory\": \"panorama:NodeCategory\",\n    \"NodeFromTemplateJob\": \"panorama:NodeFromTemplateJob\",\n    \"NodeFromTemplateJobList\": \"panorama:NodeFromTemplateJobList\",\n    \"NodeFromTemplateJobStatus\": \"panorama:NodeFromTemplateJobStatus\",\n    \"NodeFromTemplateJobStatusMessage\": \"panorama:NodeFromTemplateJobStatusMessage\",\n    \"NodeId\": {\n      \"@id\": \"panorama:NodeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeInputPort\": \"panorama:NodeInputPort\",\n    \"NodeInstance\": \"panorama:NodeInstance\",\n    \"NodeInstanceId\": {\n      \"@id\": \"panorama:NodeInstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeInstanceStatus\": \"panorama:NodeInstanceStatus\",\n    \"NodeInstances\": {\n      \"@id\": \"panorama:NodeInstances\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"NodeInterface\": {\n      \"@id\": \"panorama:NodeInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeName\": {\n      \"@id\": \"panorama:NodeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeOutputPort\": \"panorama:NodeOutputPort\",\n    \"NodePackageArn\": \"panorama:NodePackageArn\",\n    \"NodePackageId\": \"panorama:NodePackageId\",\n    \"NodePackageName\": \"panorama:NodePackageName\",\n    \"NodePackagePatchVersion\": \"panorama:NodePackagePatchVersion\",\n    \"NodePackageVersion\": \"panorama:NodePackageVersion\",\n    \"NodeSignal\": \"panorama:NodeSignal\",\n    \"NodeSignalList\": \"panorama:NodeSignalList\",\n    \"NodeSignalValue\": \"panorama:NodeSignalValue\",\n    \"NodesList\": \"panorama:NodesList\",\n    \"NtpPayload\": \"panorama:NtpPayload\",\n    \"NtpServerList\": \"panorama:NtpServerList\",\n    \"NtpServerName\": {\n      \"@id\": \"panorama:NtpServerName\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"NtpStatus\": {\n      \"@id\": \"panorama:NtpStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OTAJobConfig\": {\n      \"@id\": \"panorama:OTAJobConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Object\": \"panorama:Object\",\n    \"ObjectKey\": {\n      \"@id\": \"panorama:ObjectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutPutS3Location\": \"panorama:OutPutS3Location\",\n    \"OutputPortList\": \"panorama:OutputPortList\",\n    \"PackageImportJob\": \"panorama:PackageImportJob\",\n    \"PackageImportJobInputConfig\": \"panorama:PackageImportJobInputConfig\",\n    \"PackageImportJobList\": \"panorama:PackageImportJobList\",\n    \"PackageImportJobOutput\": \"panorama:PackageImportJobOutput\",\n    \"PackageImportJobOutputConfig\": \"panorama:PackageImportJobOutputConfig\",\n    \"PackageImportJobStatus\": \"panorama:PackageImportJobStatus\",\n    \"PackageImportJobStatusMessage\": \"panorama:PackageImportJobStatusMessage\",\n    \"PackageImportJobType\"\
  : \"panorama:PackageImportJobType\",\n    \"PackageList\": \"panorama:PackageList\",\n    \"PackageListItem\": \"panorama:PackageListItem\",\n    \"PackageObject\": \"panorama:PackageObject\",\n    \"PackageObjects\": {\n      \"@id\": \"panorama:PackageObjects\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageOwnerAccount\": \"panorama:PackageOwnerAccount\",\n    \"PackageVersionInputConfig\": {\n      \"@id\": \"panorama:PackageVersionInputConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageVersionOutputConfig\": {\n      \"@id\": \"panorama:PackageVersionOutputConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageVersionStatus\": \"panorama:PackageVersionStatus\",\n    \"PackageVersionStatusDescription\": \"panorama:PackageVersionStatusDescription\",\n    \"PortDefaultValue\": \"panorama:PortDefaultValue\",\n    \"PortName\": \"panorama:PortName\",\n    \"PortType\": \"panorama:PortType\",\n    \"PrincipalArn\": \"panorama:PrincipalArn\",\n    \"PrincipalArnsList\"\
  : \"panorama:PrincipalArnsList\",\n    \"ProvisionDeviceRequest\": \"panorama:ProvisionDeviceRequest\",\n    \"ProvisionDeviceResponse\": \"panorama:ProvisionDeviceResponse\",\n    \"Region\": {\n      \"@id\": \"panorama:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisterPackageVersionRequest\": \"panorama:RegisterPackageVersionRequest\",\n    \"RegisterPackageVersionResponse\": \"panorama:RegisterPackageVersionResponse\",\n    \"RemoveApplicationInstanceRequest\": \"panorama:RemoveApplicationInstanceRequest\",\n    \"RemoveApplicationInstanceResponse\": \"panorama:RemoveApplicationInstanceResponse\",\n    \"ReportedRuntimeContextState\": \"panorama:ReportedRuntimeContextState\",\n    \"ReportedRuntimeContextStates\": \"panorama:ReportedRuntimeContextStates\",\n    \"ResourceArn\": \"panorama:ResourceArn\",\n    \"ResourceNotFoundException\": \"panorama:ResourceNotFoundException\",\n    \"RuntimeContextName\": {\n      \"@id\": \"panorama:RuntimeContextName\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"RuntimeRoleArn\": {\n      \"@id\": \"panorama:RuntimeRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Location\": {\n      \"@id\": \"panorama:S3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceQuotaExceededException\": \"panorama:ServiceQuotaExceededException\",\n    \"SignalApplicationInstanceNodeInstancesRequest\": \"panorama:SignalApplicationInstanceNodeInstancesRequest\",\n    \"SignalApplicationInstanceNodeInstancesResponse\": \"panorama:SignalApplicationInstanceNodeInstancesResponse\",\n    \"SortOrder\": \"panorama:SortOrder\",\n    \"StaticIpConnectionInfo\": {\n      \"@id\": \"panorama:StaticIpConnectionInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusFilter\": \"panorama:StatusFilter\",\n    \"StorageLocation\": {\n      \"@id\": \"panorama:StorageLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagKey\": \"panorama:TagKey\",\n    \"TagKeyList\": \"panorama:TagKeyList\",\n    \"TagMap\"\
  : \"panorama:TagMap\",\n    \"TagResourceRequest\": \"panorama:TagResourceRequest\",\n    \"TagResourceResponse\": \"panorama:TagResourceResponse\",\n    \"TagValue\": \"panorama:TagValue\",\n    \"TemplateKey\": \"panorama:TemplateKey\",\n    \"TemplateParametersMap\": \"panorama:TemplateParametersMap\",\n    \"TemplateType\": {\n      \"@id\": \"panorama:TemplateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateValue\": \"panorama:TemplateValue\",\n    \"TimeStamp\": \"panorama:TimeStamp\",\n    \"Token\": \"panorama:Token\",\n    \"UntagResourceRequest\": \"panorama:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"panorama:UntagResourceResponse\",\n    \"UpdateCreatedTime\": \"panorama:UpdateCreatedTime\",\n    \"UpdateDeviceMetadataRequest\": \"panorama:UpdateDeviceMetadataRequest\",\n    \"UpdateDeviceMetadataResponse\": \"panorama:UpdateDeviceMetadataResponse\",\n    \"UpdateProgress\": \"panorama:UpdateProgress\",\n    \"ValidationException\": \"panorama:ValidationException\"\
  ,\n    \"Version\": {\n      \"@id\": \"panorama:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowMajorVersionUpdate\": {\n      \"@id\": \"panorama:AllowMajorVersionUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ApplicationInstanceIdToReplace\": {\n      \"@id\": \"panorama:ApplicationInstanceIdToReplace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"panorama:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssetName\": {\n      \"@id\": \"panorama:AssetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BinaryPrefixLocation\": {\n      \"@id\": \"panorama:BinaryPrefixLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Brand\": {\n      \"@id\": \"panorama:Brand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Category\": {\n      \"@id\": \"panorama:Category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionStatus\": {\n      \"@id\": \"panorama:ConnectionStatus\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"CurrentNetworkingStatus\": {\n      \"@id\": \"panorama:CurrentNetworkingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentStatus\": {\n      \"@id\": \"panorama:CurrentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultRuntimeContextDeviceName\": {\n      \"@id\": \"panorama:DefaultRuntimeContextDeviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultValue\": {\n      \"@id\": \"panorama:DefaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceIds\": {\n      \"@id\": \"panorama:DeviceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceJobs\": {\n      \"@id\": \"panorama:DeviceJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceReportedTime\": {\n      \"@id\": \"panorama:DeviceReportedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Devices\": {\n      \"@id\": \"panorama:Devices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ethernet0\": {\n      \"@id\": \"panorama:Ethernet0\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"Ethernet0Status\": {\n      \"@id\": \"panorama:Ethernet0Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ethernet1\": {\n      \"@id\": \"panorama:Ethernet1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ethernet1Status\": {\n      \"@id\": \"panorama:Ethernet1Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GeneratedPrefixLocation\": {\n      \"@id\": \"panorama:GeneratedPrefixLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HealthStatus\": {\n      \"@id\": \"panorama:HealthStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputConfig\": {\n      \"@id\": \"panorama:InputConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Inputs\": {\n      \"@id\": \"panorama:Inputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsLatestPatch\": {\n      \"@id\": \"panorama:IsLatestPatch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobTags\": {\n      \"@id\": \"panorama:JobTags\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"Jobs\": {\n      \"@id\": \"panorama:Jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManifestPrefixLocation\": {\n      \"@id\": \"panorama:ManifestPrefixLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MarkLatest\": {\n      \"@id\": \"panorama:MarkLatest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"panorama:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkingConfiguration\": {\n      \"@id\": \"panorama:NetworkingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeDescription\": {\n      \"@id\": \"panorama:NodeDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeFromTemplateJobs\": {\n      \"@id\": \"panorama:NodeFromTemplateJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NodeSignals\": {\n      \"@id\": \"panorama:NodeSignals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Nodes\": {\n      \"@id\": \"panorama:Nodes\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Ntp\": {\n      \"@id\": \"panorama:Ntp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NtpServers\": {\n      \"@id\": \"panorama:NtpServers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Output\": {\n      \"@id\": \"panorama:Output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputConfig\": {\n      \"@id\": \"panorama:OutputConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputPackageName\": {\n      \"@id\": \"panorama:OutputPackageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputPackageVersion\": {\n      \"@id\": \"panorama:OutputPackageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputS3Location\": {\n      \"@id\": \"panorama:OutputS3Location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Outputs\": {\n      \"@id\": \"panorama:Outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerAccount\": {\n      \"@id\": \"panorama:OwnerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageArn\"\
  : {\n      \"@id\": \"panorama:PackageArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageId\": {\n      \"@id\": \"panorama:PackageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageImportJobs\": {\n      \"@id\": \"panorama:PackageImportJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageName\": {\n      \"@id\": \"panorama:PackageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackagePatchVersion\": {\n      \"@id\": \"panorama:PackagePatchVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PackageVersion\": {\n      \"@id\": \"panorama:PackageVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Packages\": {\n      \"@id\": \"panorama:Packages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PatchVersion\": {\n      \"@id\": \"panorama:PatchVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayloadData\": {\n      \"@id\": \"panorama:PayloadData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisioningStatus\": {\n\
  \      \"@id\": \"panorama:ProvisioningStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReadAccessPrincipalArns\": {\n      \"@id\": \"panorama:ReadAccessPrincipalArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisteredTime\": {\n      \"@id\": \"panorama:RegisteredTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepoPrefixLocation\": {\n      \"@id\": \"panorama:RepoPrefixLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"panorama:ResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuntimeContextStates\": {\n      \"@id\": \"panorama:RuntimeContextStates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SerialNumber\": {\n      \"@id\": \"panorama:SerialNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Signal\": {\n      \"@id\": \"panorama:Signal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"panorama:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  StatusDescription\": {\n      \"@id\": \"panorama:StatusDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusMessage\": {\n      \"@id\": \"panorama:StatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"panorama:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateParameters\": {\n      \"@id\": \"panorama:TemplateParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"panorama:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WriteAccessPrincipalArns\": {\n      \"@id\": \"panorama:WriteAccessPrincipalArns\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-panorama/refs/heads/main/json-ld/amazon-panorama-openapi-context.jsonld
tags:
- AWS
- Cameras
- Computer Vision
- Edge ML
- Industrial IoT
- JSON-LD
- Linked Data
- Semantic Web
---
