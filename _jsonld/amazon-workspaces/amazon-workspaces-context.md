---
api_specs:
- filename: amazon-workspaces-openapi-original.yaml
  format: yaml
  label: Amazon WorkSpaces API
  slug: amazon-workspaces-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/openapi/amazon-workspaces-openapi-original.yaml
class_count: 175
classes:
- AssociateConnectionAliasResult
- AssociateConnectionAliasRequest
- AssociateIpGroupsResult
- AssociateIpGroupsRequest
- AuthorizeIpRulesResult
- AuthorizeIpRulesRequest
- CopyWorkspaceImageResult
- CopyWorkspaceImageRequest
- CreateConnectClientAddInResult
- CreateConnectClientAddInRequest
- CreateConnectionAliasResult
- CreateConnectionAliasRequest
- CreateIpGroupResult
- CreateIpGroupRequest
- CreateStandbyWorkspacesResult
- CreateStandbyWorkspacesRequest
- CreateTagsResult
- CreateTagsRequest
- CreateUpdatedWorkspaceImageResult
- CreateUpdatedWorkspaceImageRequest
- CreateWorkspaceBundleResult
- WorkspaceBundle
- CreateWorkspaceBundleRequest
- ComputeType
- UserStorage
- RootStorage
- CreateWorkspaceImageResult
- OperatingSystem
- CreateWorkspaceImageRequest
- CreateWorkspacesResult
- CreateWorkspacesRequest
- DeleteClientBrandingResult
- DeleteClientBrandingRequest
- DeleteConnectClientAddInResult
- DeleteConnectClientAddInRequest
- DeleteConnectionAliasResult
- DeleteConnectionAliasRequest
- DeleteIpGroupResult
- DeleteIpGroupRequest
- DeleteTagsResult
- DeleteTagsRequest
- DeleteWorkspaceBundleResult
- DeleteWorkspaceBundleRequest
- DeleteWorkspaceImageResult
- DeleteWorkspaceImageRequest
- DeregisterWorkspaceDirectoryResult
- DeregisterWorkspaceDirectoryRequest
- DescribeAccountResult
- DescribeAccountRequest
- DescribeAccountModificationsResult
- DescribeAccountModificationsRequest
- DescribeClientBrandingResult
- DescribeClientBrandingRequest
- DescribeClientPropertiesResult
- DescribeClientPropertiesRequest
- DescribeConnectClientAddInsResult
- DescribeConnectClientAddInsRequest
- DescribeConnectionAliasPermissionsResult
- DescribeConnectionAliasPermissionsRequest
- DescribeConnectionAliasesResult
- DescribeConnectionAliasesRequest
- DescribeIpGroupsResult
- DescribeIpGroupsRequest
- DescribeTagsResult
- DescribeTagsRequest
- DescribeWorkspaceBundlesResult
- DescribeWorkspaceBundlesRequest
- DescribeWorkspaceDirectoriesResult
- DescribeWorkspaceDirectoriesRequest
- DescribeWorkspaceImagePermissionsResult
- DescribeWorkspaceImagePermissionsRequest
- DescribeWorkspaceImagesResult
- DescribeWorkspaceImagesRequest
- DescribeWorkspaceSnapshotsResult
- DescribeWorkspaceSnapshotsRequest
- DescribeWorkspacesResult
- DescribeWorkspacesRequest
- DescribeWorkspacesConnectionStatusResult
- DescribeWorkspacesConnectionStatusRequest
- DisassociateConnectionAliasResult
- DisassociateConnectionAliasRequest
- DisassociateIpGroupsResult
- DisassociateIpGroupsRequest
- ImportClientBrandingResult
- ImportClientBrandingRequest
- ImportWorkspaceImageResult
- ImportWorkspaceImageRequest
- ListAvailableManagementCidrRangesResult
- ListAvailableManagementCidrRangesRequest
- MigrateWorkspaceResult
- MigrateWorkspaceRequest
- ModifyAccountResult
- ModifyAccountRequest
- ModifyCertificateBasedAuthPropertiesResult
- ModifyCertificateBasedAuthPropertiesRequest
- CertificateBasedAuthProperties
- ModifyClientPropertiesResult
- ModifyClientPropertiesRequest
- ClientProperties
- ModifySamlPropertiesResult
- ModifySamlPropertiesRequest
- SamlProperties
- ModifySelfservicePermissionsResult
- ModifySelfservicePermissionsRequest
- SelfservicePermissions
- ModifyWorkspaceAccessPropertiesResult
- ModifyWorkspaceAccessPropertiesRequest
- WorkspaceAccessProperties
- ModifyWorkspaceCreationPropertiesResult
- ModifyWorkspaceCreationPropertiesRequest
- WorkspaceCreationProperties
- ModifyWorkspacePropertiesResult
- ModifyWorkspacePropertiesRequest
- WorkspaceProperties
- ModifyWorkspaceStateResult
- ModifyWorkspaceStateRequest
- RebootWorkspacesResult
- RebootWorkspacesRequest
- RebuildWorkspacesResult
- RebuildWorkspacesRequest
- RegisterWorkspaceDirectoryResult
- RegisterWorkspaceDirectoryRequest
- RestoreWorkspaceResult
- RestoreWorkspaceRequest
- RevokeIpRulesResult
- RevokeIpRulesRequest
- StartWorkspacesResult
- StartWorkspacesRequest
- StopWorkspacesResult
- StopWorkspacesRequest
- TerminateWorkspacesResult
- TerminateWorkspacesRequest
- UpdateConnectClientAddInResult
- UpdateConnectClientAddInRequest
- UpdateConnectionAliasPermissionResult
- UpdateConnectionAliasPermissionRequest
- ConnectionAliasPermission
- UpdateRulesOfIpGroupResult
- UpdateRulesOfIpGroupRequest
- UpdateWorkspaceBundleResult
- UpdateWorkspaceBundleRequest
- UpdateWorkspaceImagePermissionResult
- UpdateWorkspaceImagePermissionRequest
- AccountModification
- ModificationState
- ClientPropertiesResult
- ConnectClientAddIn
- ConnectionAlias
- ConnectionAliasAssociation
- DefaultClientBrandingAttributes
- DefaultImportClientBrandingAttributes
- DefaultWorkspaceCreationProperties
- IosClientBrandingAttributes
- WorkspaceDirectory
- StandbyWorkspace
- FailedCreateStandbyWorkspacesRequest
- FailedCreateWorkspaceRequest
- FailedWorkspaceChangeRequest
- ImagePermission
- IosImportClientBrandingAttributes
- IpRuleItem
- PendingCreateStandbyWorkspacesRequest
- RebootRequest
- RebuildRequest
- RelatedWorkspaceProperties
- Snapshot
- StartRequest
- StopRequest
- Tag
- TerminateRequest
- UpdateResult
- Workspace
- WorkspaceConnectionStatus
- WorkspaceImage
- WorkspacesIpGroup
context_file: json-ld/amazon-workspaces-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/json-ld/amazon-workspaces-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Workspaces from Amazon WorkSpaces.
layout: jsonld
name: Amazon Workspaces Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ConnectionIdentifier
  type: string
- container: ''
  name: AliasId
  type: string
- container: ''
  name: ResourceId
  type: string
- container: ''
  name: DirectoryId
  type: string
- container: ''
  name: GroupIds
  type: string
- container: ''
  name: GroupId
  type: string
- container: ''
  name: UserRules
  type: string
- container: ''
  name: ImageId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: SourceImageId
  type: string
- container: ''
  name: SourceRegion
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: AddInId
  type: string
- container: ''
  name: URL
  type: string
- container: ''
  name: ConnectionString
  type: string
- container: ''
  name: GroupName
  type: string
- container: ''
  name: GroupDesc
  type: string
- container: ''
  name: FailedStandbyRequests
  type: string
- container: ''
  name: PendingStandbyRequests
  type: string
- container: ''
  name: PrimaryRegion
  type: string
- container: ''
  name: StandbyWorkspaces
  type: string
- container: ''
  name: BundleName
  type: string
- container: ''
  name: BundleDescription
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: RequiredTenancy
  type: string
- container: ''
  name: Created
  type: string
- container: ''
  name: OwnerAccountId
  type: string
- container: ''
  name: WorkspaceId
  type: string
- container: ''
  name: FailedRequests
  type: string
- container: ''
  name: PendingRequests
  type: string
- container: ''
  name: Workspaces
  type: string
- container: ''
  name: Platforms
  type: string
- container: ''
  name: TagKeys
  type: string
- container: ''
  name: BundleId
  type: string
- container: ''
  name: DedicatedTenancySupport
  type: string
- container: ''
  name: DedicatedTenancyManagementCidrRange
  type: string
- container: ''
  name: AccountModifications
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: DeviceTypeWindows
  type: string
- container: ''
  name: DeviceTypeOsx
  type: string
- container: ''
  name: DeviceTypeAndroid
  type: string
- container: ''
  name: DeviceTypeIos
  type: string
- container: ''
  name: DeviceTypeLinux
  type: string
- container: ''
  name: DeviceTypeWeb
  type: string
- container: ''
  name: ClientPropertiesList
  type: string
- container: ''
  name: ResourceIds
  type: string
- container: ''
  name: AddIns
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: ConnectionAliasPermissions
  type: string
- container: ''
  name: ConnectionAliases
  type: string
- container: ''
  name: AliasIds
  type: string
- container: ''
  name: Limit
  type: string
- container: ''
  name: Result
  type: string
- container: ''
  name: TagList
  type: string
- container: ''
  name: Bundles
  type: string
- container: ''
  name: BundleIds
  type: string
- container: ''
  name: Owner
  type: string
- container: ''
  name: Directories
  type: string
- container: ''
  name: DirectoryIds
  type: string
- container: ''
  name: ImagePermissions
  type: string
- container: ''
  name: Images
  type: string
- container: ''
  name: ImageIds
  type: string
- container: ''
  name: ImageType
  type: string
- container: ''
  name: RebuildSnapshots
  type: string
- container: ''
  name: RestoreSnapshots
  type: string
- container: ''
  name: WorkspaceIds
  type: string
- container: ''
  name: UserName
  type: string
- container: ''
  name: WorkspacesConnectionStatus
  type: string
- container: ''
  name: Ec2ImageId
  type: string
- container: ''
  name: IngestionProcess
  type: string
- container: ''
  name: ImageName
  type: string
- container: ''
  name: ImageDescription
  type: string
- container: ''
  name: Applications
  type: string
- container: ''
  name: ManagementCidrRanges
  type: string
- container: ''
  name: ManagementCidrRangeConstraint
  type: string
- container: ''
  name: SourceWorkspaceId
  type: string
- container: ''
  name: TargetWorkspaceId
  type: string
- container: ''
  name: PropertiesToDelete
  type: string
- container: ''
  name: WorkspaceState
  type: string
- container: ''
  name: RebootWorkspaceRequests
  type: string
- container: ''
  name: RebuildWorkspaceRequests
  type: string
- container: ''
  name: SubnetIds
  type: string
- container: ''
  name: EnableWorkDocs
  type: string
- container: ''
  name: EnableSelfService
  type: string
- container: ''
  name: Tenancy
  type: string
- container: ''
  name: StartWorkspaceRequests
  type: string
- container: ''
  name: StopWorkspaceRequests
  type: string
- container: ''
  name: TerminateWorkspaceRequests
  type: string
- container: ''
  name: AllowCopyImage
  type: string
- container: ''
  name: SharedAccountId
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: ErrorCode
  type: string
- container: ''
  name: ErrorMessage
  type: string
- container: ''
  name: LastUpdatedTime
  type: string
- container: ''
  name: CreationTime
  type: string
- container: ''
  name: BundleType
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: CertificateAuthorityArn
  type: string
- container: ''
  name: ReconnectEnabled
  type: string
- container: ''
  name: LogUploadEnabled
  type: string
- container: ''
  name: Associations
  type: string
- container: ''
  name: AssociationStatus
  type: string
- container: ''
  name: AssociatedAccountId
  type: string
- container: ''
  name: AllowAssociation
  type: string
- container: ''
  name: Capacity
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: LoginMessage
  type: string
- container: ''
  name: LogoUrl
  type: string
- container: ''
  name: SupportEmail
  type: string
- container: ''
  name: SupportLink
  type: string
- container: ''
  name: ForgotPasswordLink
  type: string
- container: ''
  name: Logo
  type: string
- container: ''
  name: EnableInternetAccess
  type: string
- container: ''
  name: DefaultOu
  type: string
- container: ''
  name: CustomSecurityGroupId
  type: string
- container: ''
  name: UserEnabledAsLocalAdministrator
  type: string
- container: ''
  name: EnableMaintenanceMode
  type: string
- container: ''
  name: Logo2xUrl
  type: string
- container: ''
  name: Logo3xUrl
  type: string
- container: ''
  name: Alias
  type: string
- container: ''
  name: DirectoryName
  type: string
- container: ''
  name: RegistrationCode
  type: string
- container: ''
  name: DnsIpAddresses
  type: string
- container: ''
  name: CustomerUserName
  type: string
- container: ''
  name: IamRoleId
  type: string
- container: ''
  name: DirectoryType
  type: string
- container: ''
  name: WorkspaceSecurityGroupId
  type: string
- container: ''
  name: ipGroupIds
  type: string
- container: ''
  name: PrimaryWorkspaceId
  type: string
- container: ''
  name: VolumeEncryptionKey
  type: string
- container: ''
  name: StandbyWorkspaceRequest
  type: string
- container: ''
  name: WorkspaceRequest
  type: string
- container: ''
  name: UserVolumeEncryptionEnabled
  type: string
- container: ''
  name: RootVolumeEncryptionEnabled
  type: string
- container: ''
  name: Logo2x
  type: string
- container: ''
  name: Logo3x
  type: string
- container: ''
  name: ipRule
  type: string
- container: ''
  name: ruleDesc
  type: string
- container: ''
  name: Resource
  type: string
- container: ''
  name: UserAccessUrl
  type: string
- container: ''
  name: RelayStateParameterName
  type: string
- container: ''
  name: RestartWorkspace
  type: string
- container: ''
  name: IncreaseVolumeSize
  type: string
- container: ''
  name: ChangeComputeType
  type: string
- container: ''
  name: SwitchRunningMode
  type: string
- container: ''
  name: RebuildWorkspace
  type: string
- container: ''
  name: DeviceTypeChromeOs
  type: string
- container: ''
  name: DeviceTypeZeroClient
  type: string
- container: ''
  name: RunningMode
  type: string
- container: ''
  name: RunningModeAutoStopTimeoutInMinutes
  type: string
- container: ''
  name: RootVolumeSizeGib
  type: string
- container: ''
  name: UserVolumeSizeGib
  type: string
- container: ''
  name: ComputeTypeName
  type: string
- container: ''
  name: Protocols
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: SnapshotTime
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: UpdateAvailable
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: SubnetId
  type: string
- container: ''
  name: ComputerName
  type: string
- container: ''
  name: ModificationStates
  type: string
- container: ''
  name: RelatedWorkspaces
  type: string
- container: ''
  name: ConnectionState
  type: string
- container: ''
  name: ConnectionStateCheckTimestamp
  type: string
- container: ''
  name: LastKnownUserConnectionTimestamp
  type: string
- container: ''
  name: Updates
  type: string
- container: ''
  name: groupId
  type: string
- container: ''
  name: groupName
  type: string
- container: ''
  name: groupDesc
  type: string
- container: ''
  name: userRules
  type: string
property_count: 173
provider_name: Amazon WorkSpaces
provider_slug: amazon-workspaces
slug: amazon-workspaces-context
source_filename: amazon-workspaces-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociateConnectionAliasResult\": \"amz:AssociateConnectionAliasResult\",\n    \"ConnectionIdentifier\": {\n      \"@id\": \"amz:ConnectionIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateConnectionAliasRequest\": \"amz:AssociateConnectionAliasRequest\",\n    \"AliasId\": {\n      \"@id\": \"amz:AliasId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceId\": {\n      \"@id\": \"amz:ResourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateIpGroupsResult\": \"amz:AssociateIpGroupsResult\",\n    \"AssociateIpGroupsRequest\": \"amz:AssociateIpGroupsRequest\",\n    \"DirectoryId\": {\n      \"@id\": \"amz:DirectoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupIds\": {\n      \"@id\"\
  : \"amz:GroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthorizeIpRulesResult\": \"amz:AuthorizeIpRulesResult\",\n    \"AuthorizeIpRulesRequest\": \"amz:AuthorizeIpRulesRequest\",\n    \"GroupId\": {\n      \"@id\": \"amz:GroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserRules\": {\n      \"@id\": \"amz:UserRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CopyWorkspaceImageResult\": \"amz:CopyWorkspaceImageResult\",\n    \"ImageId\": {\n      \"@id\": \"amz:ImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CopyWorkspaceImageRequest\": \"amz:CopyWorkspaceImageRequest\",\n    \"Name\": {\n      \"@id\": \"amz:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"amz:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceImageId\": {\n      \"@id\": \"amz:SourceImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceRegion\": {\n      \"@id\": \"amz:SourceRegion\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Tags\": {\n      \"@id\": \"amz:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConnectClientAddInResult\": \"amz:CreateConnectClientAddInResult\",\n    \"AddInId\": {\n      \"@id\": \"amz:AddInId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConnectClientAddInRequest\": \"amz:CreateConnectClientAddInRequest\",\n    \"URL\": {\n      \"@id\": \"amz:URL\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateConnectionAliasResult\": \"amz:CreateConnectionAliasResult\",\n    \"CreateConnectionAliasRequest\": \"amz:CreateConnectionAliasRequest\",\n    \"ConnectionString\": {\n      \"@id\": \"amz:ConnectionString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateIpGroupResult\": \"amz:CreateIpGroupResult\",\n    \"CreateIpGroupRequest\": \"amz:CreateIpGroupRequest\",\n    \"GroupName\": {\n      \"@id\": \"amz:GroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupDesc\": {\n      \"@id\": \"amz:GroupDesc\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"CreateStandbyWorkspacesResult\": \"amz:CreateStandbyWorkspacesResult\",\n    \"FailedStandbyRequests\": {\n      \"@id\": \"amz:FailedStandbyRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingStandbyRequests\": {\n      \"@id\": \"amz:PendingStandbyRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateStandbyWorkspacesRequest\": \"amz:CreateStandbyWorkspacesRequest\",\n    \"PrimaryRegion\": {\n      \"@id\": \"amz:PrimaryRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StandbyWorkspaces\": {\n      \"@id\": \"amz:StandbyWorkspaces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTagsResult\": \"amz:CreateTagsResult\",\n    \"CreateTagsRequest\": \"amz:CreateTagsRequest\",\n    \"CreateUpdatedWorkspaceImageResult\": \"amz:CreateUpdatedWorkspaceImageResult\",\n    \"CreateUpdatedWorkspaceImageRequest\": \"amz:CreateUpdatedWorkspaceImageRequest\",\n    \"CreateWorkspaceBundleResult\": \"amz:CreateWorkspaceBundleResult\"\
  ,\n    \"WorkspaceBundle\": \"amz:WorkspaceBundle\",\n    \"CreateWorkspaceBundleRequest\": \"amz:CreateWorkspaceBundleRequest\",\n    \"BundleName\": {\n      \"@id\": \"amz:BundleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BundleDescription\": {\n      \"@id\": \"amz:BundleDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ComputeType\": \"amz:ComputeType\",\n    \"UserStorage\": \"amz:UserStorage\",\n    \"RootStorage\": \"amz:RootStorage\",\n    \"CreateWorkspaceImageResult\": \"amz:CreateWorkspaceImageResult\",\n    \"OperatingSystem\": \"amz:OperatingSystem\",\n    \"State\": {\n      \"@id\": \"amz:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequiredTenancy\": {\n      \"@id\": \"amz:RequiredTenancy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Created\": {\n      \"@id\": \"amz:Created\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerAccountId\": {\n      \"@id\": \"amz:OwnerAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"CreateWorkspaceImageRequest\": \"amz:CreateWorkspaceImageRequest\",\n    \"WorkspaceId\": {\n      \"@id\": \"amz:WorkspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateWorkspacesResult\": \"amz:CreateWorkspacesResult\",\n    \"FailedRequests\": {\n      \"@id\": \"amz:FailedRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingRequests\": {\n      \"@id\": \"amz:PendingRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateWorkspacesRequest\": \"amz:CreateWorkspacesRequest\",\n    \"Workspaces\": {\n      \"@id\": \"amz:Workspaces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteClientBrandingResult\": \"amz:DeleteClientBrandingResult\",\n    \"DeleteClientBrandingRequest\": \"amz:DeleteClientBrandingRequest\",\n    \"Platforms\": {\n      \"@id\": \"amz:Platforms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteConnectClientAddInResult\": \"amz:DeleteConnectClientAddInResult\",\n    \"DeleteConnectClientAddInRequest\": \"amz:DeleteConnectClientAddInRequest\"\
  ,\n    \"DeleteConnectionAliasResult\": \"amz:DeleteConnectionAliasResult\",\n    \"DeleteConnectionAliasRequest\": \"amz:DeleteConnectionAliasRequest\",\n    \"DeleteIpGroupResult\": \"amz:DeleteIpGroupResult\",\n    \"DeleteIpGroupRequest\": \"amz:DeleteIpGroupRequest\",\n    \"DeleteTagsResult\": \"amz:DeleteTagsResult\",\n    \"DeleteTagsRequest\": \"amz:DeleteTagsRequest\",\n    \"TagKeys\": {\n      \"@id\": \"amz:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteWorkspaceBundleResult\": \"amz:DeleteWorkspaceBundleResult\",\n    \"DeleteWorkspaceBundleRequest\": \"amz:DeleteWorkspaceBundleRequest\",\n    \"BundleId\": {\n      \"@id\": \"amz:BundleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteWorkspaceImageResult\": \"amz:DeleteWorkspaceImageResult\",\n    \"DeleteWorkspaceImageRequest\": \"amz:DeleteWorkspaceImageRequest\",\n    \"DeregisterWorkspaceDirectoryResult\": \"amz:DeregisterWorkspaceDirectoryResult\",\n    \"DeregisterWorkspaceDirectoryRequest\"\
  : \"amz:DeregisterWorkspaceDirectoryRequest\",\n    \"DescribeAccountResult\": \"amz:DescribeAccountResult\",\n    \"DedicatedTenancySupport\": {\n      \"@id\": \"amz:DedicatedTenancySupport\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DedicatedTenancyManagementCidrRange\": {\n      \"@id\": \"amz:DedicatedTenancyManagementCidrRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeAccountRequest\": \"amz:DescribeAccountRequest\",\n    \"DescribeAccountModificationsResult\": \"amz:DescribeAccountModificationsResult\",\n    \"AccountModifications\": {\n      \"@id\": \"amz:AccountModifications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amz:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeAccountModificationsRequest\": \"amz:DescribeAccountModificationsRequest\",\n    \"DescribeClientBrandingResult\": \"amz:DescribeClientBrandingResult\",\n    \"DeviceTypeWindows\": {\n      \"@id\": \"amz:DeviceTypeWindows\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeOsx\": {\n      \"@id\": \"amz:DeviceTypeOsx\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeAndroid\": {\n      \"@id\": \"amz:DeviceTypeAndroid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeIos\": {\n      \"@id\": \"amz:DeviceTypeIos\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeLinux\": {\n      \"@id\": \"amz:DeviceTypeLinux\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeWeb\": {\n      \"@id\": \"amz:DeviceTypeWeb\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeClientBrandingRequest\": \"amz:DescribeClientBrandingRequest\",\n    \"DescribeClientPropertiesResult\": \"amz:DescribeClientPropertiesResult\",\n    \"ClientPropertiesList\": {\n      \"@id\": \"amz:ClientPropertiesList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeClientPropertiesRequest\": \"amz:DescribeClientPropertiesRequest\",\n    \"ResourceIds\": {\n      \"@id\": \"amz:ResourceIds\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeConnectClientAddInsResult\": \"amz:DescribeConnectClientAddInsResult\",\n    \"AddIns\": {\n      \"@id\": \"amz:AddIns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeConnectClientAddInsRequest\": \"amz:DescribeConnectClientAddInsRequest\",\n    \"MaxResults\": {\n      \"@id\": \"amz:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeConnectionAliasPermissionsResult\": \"amz:DescribeConnectionAliasPermissionsResult\",\n    \"ConnectionAliasPermissions\": {\n      \"@id\": \"amz:ConnectionAliasPermissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeConnectionAliasPermissionsRequest\": \"amz:DescribeConnectionAliasPermissionsRequest\",\n    \"DescribeConnectionAliasesResult\": \"amz:DescribeConnectionAliasesResult\",\n    \"ConnectionAliases\": {\n      \"@id\": \"amz:ConnectionAliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeConnectionAliasesRequest\": \"amz:DescribeConnectionAliasesRequest\"\
  ,\n    \"AliasIds\": {\n      \"@id\": \"amz:AliasIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limit\": {\n      \"@id\": \"amz:Limit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeIpGroupsResult\": \"amz:DescribeIpGroupsResult\",\n    \"Result\": {\n      \"@id\": \"amz:Result\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeIpGroupsRequest\": \"amz:DescribeIpGroupsRequest\",\n    \"DescribeTagsResult\": \"amz:DescribeTagsResult\",\n    \"TagList\": {\n      \"@id\": \"amz:TagList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeTagsRequest\": \"amz:DescribeTagsRequest\",\n    \"DescribeWorkspaceBundlesResult\": \"amz:DescribeWorkspaceBundlesResult\",\n    \"Bundles\": {\n      \"@id\": \"amz:Bundles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceBundlesRequest\": \"amz:DescribeWorkspaceBundlesRequest\",\n    \"BundleIds\": {\n      \"@id\": \"amz:BundleIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Owner\": {\n  \
  \    \"@id\": \"amz:Owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceDirectoriesResult\": \"amz:DescribeWorkspaceDirectoriesResult\",\n    \"Directories\": {\n      \"@id\": \"amz:Directories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceDirectoriesRequest\": \"amz:DescribeWorkspaceDirectoriesRequest\",\n    \"DirectoryIds\": {\n      \"@id\": \"amz:DirectoryIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceImagePermissionsResult\": \"amz:DescribeWorkspaceImagePermissionsResult\",\n    \"ImagePermissions\": {\n      \"@id\": \"amz:ImagePermissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceImagePermissionsRequest\": \"amz:DescribeWorkspaceImagePermissionsRequest\",\n    \"DescribeWorkspaceImagesResult\": \"amz:DescribeWorkspaceImagesResult\",\n    \"Images\": {\n      \"@id\": \"amz:Images\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceImagesRequest\": \"amz:DescribeWorkspaceImagesRequest\"\
  ,\n    \"ImageIds\": {\n      \"@id\": \"amz:ImageIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageType\": {\n      \"@id\": \"amz:ImageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceSnapshotsResult\": \"amz:DescribeWorkspaceSnapshotsResult\",\n    \"RebuildSnapshots\": {\n      \"@id\": \"amz:RebuildSnapshots\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestoreSnapshots\": {\n      \"@id\": \"amz:RestoreSnapshots\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspaceSnapshotsRequest\": \"amz:DescribeWorkspaceSnapshotsRequest\",\n    \"DescribeWorkspacesResult\": \"amz:DescribeWorkspacesResult\",\n    \"DescribeWorkspacesRequest\": \"amz:DescribeWorkspacesRequest\",\n    \"WorkspaceIds\": {\n      \"@id\": \"amz:WorkspaceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserName\": {\n      \"@id\": \"amz:UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspacesConnectionStatusResult\": \"amz:DescribeWorkspacesConnectionStatusResult\"\
  ,\n    \"WorkspacesConnectionStatus\": {\n      \"@id\": \"amz:WorkspacesConnectionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeWorkspacesConnectionStatusRequest\": \"amz:DescribeWorkspacesConnectionStatusRequest\",\n    \"DisassociateConnectionAliasResult\": \"amz:DisassociateConnectionAliasResult\",\n    \"DisassociateConnectionAliasRequest\": \"amz:DisassociateConnectionAliasRequest\",\n    \"DisassociateIpGroupsResult\": \"amz:DisassociateIpGroupsResult\",\n    \"DisassociateIpGroupsRequest\": \"amz:DisassociateIpGroupsRequest\",\n    \"ImportClientBrandingResult\": \"amz:ImportClientBrandingResult\",\n    \"ImportClientBrandingRequest\": \"amz:ImportClientBrandingRequest\",\n    \"ImportWorkspaceImageResult\": \"amz:ImportWorkspaceImageResult\",\n    \"ImportWorkspaceImageRequest\": \"amz:ImportWorkspaceImageRequest\",\n    \"Ec2ImageId\": {\n      \"@id\": \"amz:Ec2ImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IngestionProcess\": {\n      \"@id\"\
  : \"amz:IngestionProcess\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageName\": {\n      \"@id\": \"amz:ImageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageDescription\": {\n      \"@id\": \"amz:ImageDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Applications\": {\n      \"@id\": \"amz:Applications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAvailableManagementCidrRangesResult\": \"amz:ListAvailableManagementCidrRangesResult\",\n    \"ManagementCidrRanges\": {\n      \"@id\": \"amz:ManagementCidrRanges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAvailableManagementCidrRangesRequest\": \"amz:ListAvailableManagementCidrRangesRequest\",\n    \"ManagementCidrRangeConstraint\": {\n      \"@id\": \"amz:ManagementCidrRangeConstraint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MigrateWorkspaceResult\": \"amz:MigrateWorkspaceResult\",\n    \"SourceWorkspaceId\": {\n      \"@id\": \"amz:SourceWorkspaceId\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"TargetWorkspaceId\": {\n      \"@id\": \"amz:TargetWorkspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MigrateWorkspaceRequest\": \"amz:MigrateWorkspaceRequest\",\n    \"ModifyAccountResult\": \"amz:ModifyAccountResult\",\n    \"ModifyAccountRequest\": \"amz:ModifyAccountRequest\",\n    \"ModifyCertificateBasedAuthPropertiesResult\": \"amz:ModifyCertificateBasedAuthPropertiesResult\",\n    \"ModifyCertificateBasedAuthPropertiesRequest\": \"amz:ModifyCertificateBasedAuthPropertiesRequest\",\n    \"CertificateBasedAuthProperties\": \"amz:CertificateBasedAuthProperties\",\n    \"PropertiesToDelete\": {\n      \"@id\": \"amz:PropertiesToDelete\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModifyClientPropertiesResult\": \"amz:ModifyClientPropertiesResult\",\n    \"ModifyClientPropertiesRequest\": \"amz:ModifyClientPropertiesRequest\",\n    \"ClientProperties\": \"amz:ClientProperties\",\n    \"ModifySamlPropertiesResult\": \"amz:ModifySamlPropertiesResult\"\
  ,\n    \"ModifySamlPropertiesRequest\": \"amz:ModifySamlPropertiesRequest\",\n    \"SamlProperties\": \"amz:SamlProperties\",\n    \"ModifySelfservicePermissionsResult\": \"amz:ModifySelfservicePermissionsResult\",\n    \"ModifySelfservicePermissionsRequest\": \"amz:ModifySelfservicePermissionsRequest\",\n    \"SelfservicePermissions\": \"amz:SelfservicePermissions\",\n    \"ModifyWorkspaceAccessPropertiesResult\": \"amz:ModifyWorkspaceAccessPropertiesResult\",\n    \"ModifyWorkspaceAccessPropertiesRequest\": \"amz:ModifyWorkspaceAccessPropertiesRequest\",\n    \"WorkspaceAccessProperties\": \"amz:WorkspaceAccessProperties\",\n    \"ModifyWorkspaceCreationPropertiesResult\": \"amz:ModifyWorkspaceCreationPropertiesResult\",\n    \"ModifyWorkspaceCreationPropertiesRequest\": \"amz:ModifyWorkspaceCreationPropertiesRequest\",\n    \"WorkspaceCreationProperties\": \"amz:WorkspaceCreationProperties\",\n    \"ModifyWorkspacePropertiesResult\": \"amz:ModifyWorkspacePropertiesResult\",\n    \"\
  ModifyWorkspacePropertiesRequest\": \"amz:ModifyWorkspacePropertiesRequest\",\n    \"WorkspaceProperties\": \"amz:WorkspaceProperties\",\n    \"ModifyWorkspaceStateResult\": \"amz:ModifyWorkspaceStateResult\",\n    \"ModifyWorkspaceStateRequest\": \"amz:ModifyWorkspaceStateRequest\",\n    \"WorkspaceState\": {\n      \"@id\": \"amz:WorkspaceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RebootWorkspacesResult\": \"amz:RebootWorkspacesResult\",\n    \"RebootWorkspacesRequest\": \"amz:RebootWorkspacesRequest\",\n    \"RebootWorkspaceRequests\": {\n      \"@id\": \"amz:RebootWorkspaceRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RebuildWorkspacesResult\": \"amz:RebuildWorkspacesResult\",\n    \"RebuildWorkspacesRequest\": \"amz:RebuildWorkspacesRequest\",\n    \"RebuildWorkspaceRequests\": {\n      \"@id\": \"amz:RebuildWorkspaceRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisterWorkspaceDirectoryResult\": \"amz:RegisterWorkspaceDirectoryResult\",\n\
  \    \"RegisterWorkspaceDirectoryRequest\": \"amz:RegisterWorkspaceDirectoryRequest\",\n    \"SubnetIds\": {\n      \"@id\": \"amz:SubnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableWorkDocs\": {\n      \"@id\": \"amz:EnableWorkDocs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableSelfService\": {\n      \"@id\": \"amz:EnableSelfService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tenancy\": {\n      \"@id\": \"amz:Tenancy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestoreWorkspaceResult\": \"amz:RestoreWorkspaceResult\",\n    \"RestoreWorkspaceRequest\": \"amz:RestoreWorkspaceRequest\",\n    \"RevokeIpRulesResult\": \"amz:RevokeIpRulesResult\",\n    \"RevokeIpRulesRequest\": \"amz:RevokeIpRulesRequest\",\n    \"StartWorkspacesResult\": \"amz:StartWorkspacesResult\",\n    \"StartWorkspacesRequest\": \"amz:StartWorkspacesRequest\",\n    \"StartWorkspaceRequests\": {\n      \"@id\": \"amz:StartWorkspaceRequests\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"StopWorkspacesResult\": \"amz:StopWorkspacesResult\",\n    \"StopWorkspacesRequest\": \"amz:StopWorkspacesRequest\",\n    \"StopWorkspaceRequests\": {\n      \"@id\": \"amz:StopWorkspaceRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TerminateWorkspacesResult\": \"amz:TerminateWorkspacesResult\",\n    \"TerminateWorkspacesRequest\": \"amz:TerminateWorkspacesRequest\",\n    \"TerminateWorkspaceRequests\": {\n      \"@id\": \"amz:TerminateWorkspaceRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateConnectClientAddInResult\": \"amz:UpdateConnectClientAddInResult\",\n    \"UpdateConnectClientAddInRequest\": \"amz:UpdateConnectClientAddInRequest\",\n    \"UpdateConnectionAliasPermissionResult\": \"amz:UpdateConnectionAliasPermissionResult\",\n    \"UpdateConnectionAliasPermissionRequest\": \"amz:UpdateConnectionAliasPermissionRequest\",\n    \"ConnectionAliasPermission\": \"amz:ConnectionAliasPermission\",\n    \"UpdateRulesOfIpGroupResult\": \"amz:UpdateRulesOfIpGroupResult\"\
  ,\n    \"UpdateRulesOfIpGroupRequest\": \"amz:UpdateRulesOfIpGroupRequest\",\n    \"UpdateWorkspaceBundleResult\": \"amz:UpdateWorkspaceBundleResult\",\n    \"UpdateWorkspaceBundleRequest\": \"amz:UpdateWorkspaceBundleRequest\",\n    \"UpdateWorkspaceImagePermissionResult\": \"amz:UpdateWorkspaceImagePermissionResult\",\n    \"UpdateWorkspaceImagePermissionRequest\": \"amz:UpdateWorkspaceImagePermissionRequest\",\n    \"AllowCopyImage\": {\n      \"@id\": \"amz:AllowCopyImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedAccountId\": {\n      \"@id\": \"amz:SharedAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountModification\": \"amz:AccountModification\",\n    \"ModificationState\": \"amz:ModificationState\",\n    \"StartTime\": {\n      \"@id\": \"amz:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"amz:ErrorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorMessage\": {\n      \"@id\": \"amz:ErrorMessage\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedTime\": {\n      \"@id\": \"amz:LastUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"amz:CreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BundleType\": {\n      \"@id\": \"amz:BundleType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amz:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateAuthorityArn\": {\n      \"@id\": \"amz:CertificateAuthorityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReconnectEnabled\": {\n      \"@id\": \"amz:ReconnectEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogUploadEnabled\": {\n      \"@id\": \"amz:LogUploadEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientPropertiesResult\": \"amz:ClientPropertiesResult\",\n    \"ConnectClientAddIn\": \"amz:ConnectClientAddIn\",\n    \"ConnectionAlias\": \"amz:ConnectionAlias\",\n    \"Associations\": {\n \
  \     \"@id\": \"amz:Associations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionAliasAssociation\": \"amz:ConnectionAliasAssociation\",\n    \"AssociationStatus\": {\n      \"@id\": \"amz:AssociationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociatedAccountId\": {\n      \"@id\": \"amz:AssociatedAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllowAssociation\": {\n      \"@id\": \"amz:AllowAssociation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Capacity\": {\n      \"@id\": \"amz:Capacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"amz:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoginMessage\": {\n      \"@id\": \"amz:LoginMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultClientBrandingAttributes\": \"amz:DefaultClientBrandingAttributes\",\n    \"LogoUrl\": {\n      \"@id\": \"amz:LogoUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportEmail\": {\n      \"@id\"\
  : \"amz:SupportEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportLink\": {\n      \"@id\": \"amz:SupportLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForgotPasswordLink\": {\n      \"@id\": \"amz:ForgotPasswordLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultImportClientBrandingAttributes\": \"amz:DefaultImportClientBrandingAttributes\",\n    \"Logo\": {\n      \"@id\": \"amz:Logo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultWorkspaceCreationProperties\": \"amz:DefaultWorkspaceCreationProperties\",\n    \"EnableInternetAccess\": {\n      \"@id\": \"amz:EnableInternetAccess\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultOu\": {\n      \"@id\": \"amz:DefaultOu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomSecurityGroupId\": {\n      \"@id\": \"amz:CustomSecurityGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserEnabledAsLocalAdministrator\": {\n      \"@id\": \"amz:UserEnabledAsLocalAdministrator\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"EnableMaintenanceMode\": {\n      \"@id\": \"amz:EnableMaintenanceMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IosClientBrandingAttributes\": \"amz:IosClientBrandingAttributes\",\n    \"Logo2xUrl\": {\n      \"@id\": \"amz:Logo2xUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Logo3xUrl\": {\n      \"@id\": \"amz:Logo3xUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspaceDirectory\": \"amz:WorkspaceDirectory\",\n    \"Alias\": {\n      \"@id\": \"amz:Alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryName\": {\n      \"@id\": \"amz:DirectoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegistrationCode\": {\n      \"@id\": \"amz:RegistrationCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsIpAddresses\": {\n      \"@id\": \"amz:DnsIpAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerUserName\": {\n      \"@id\": \"amz:CustomerUserName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"IamRoleId\": {\n      \"@id\": \"amz:IamRoleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryType\": {\n      \"@id\": \"amz:DirectoryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspaceSecurityGroupId\": {\n      \"@id\": \"amz:WorkspaceSecurityGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipGroupIds\": {\n      \"@id\": \"amz:ipGroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StandbyWorkspace\": \"amz:StandbyWorkspace\",\n    \"PrimaryWorkspaceId\": {\n      \"@id\": \"amz:PrimaryWorkspaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VolumeEncryptionKey\": {\n      \"@id\": \"amz:VolumeEncryptionKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailedCreateStandbyWorkspacesRequest\": \"amz:FailedCreateStandbyWorkspacesRequest\",\n    \"StandbyWorkspaceRequest\": {\n      \"@id\": \"amz:StandbyWorkspaceRequest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspaceRequest\": {\n      \"@id\": \"amz:WorkspaceRequest\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"UserVolumeEncryptionEnabled\": {\n      \"@id\": \"amz:UserVolumeEncryptionEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RootVolumeEncryptionEnabled\": {\n      \"@id\": \"amz:RootVolumeEncryptionEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailedCreateWorkspaceRequest\": \"amz:FailedCreateWorkspaceRequest\",\n    \"FailedWorkspaceChangeRequest\": \"amz:FailedWorkspaceChangeRequest\",\n    \"ImagePermission\": \"amz:ImagePermission\",\n    \"IosImportClientBrandingAttributes\": \"amz:IosImportClientBrandingAttributes\",\n    \"Logo2x\": {\n      \"@id\": \"amz:Logo2x\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Logo3x\": {\n      \"@id\": \"amz:Logo3x\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpRuleItem\": \"amz:IpRuleItem\",\n    \"ipRule\": {\n      \"@id\": \"amz:ipRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleDesc\": {\n      \"@id\": \"amz:ruleDesc\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Resource\": {\n      \"@id\": \"amz:Resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserAccessUrl\": {\n      \"@id\": \"amz:UserAccessUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelayStateParameterName\": {\n      \"@id\": \"amz:RelayStateParameterName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RestartWorkspace\": {\n      \"@id\": \"amz:RestartWorkspace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncreaseVolumeSize\": {\n      \"@id\": \"amz:IncreaseVolumeSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChangeComputeType\": {\n      \"@id\": \"amz:ChangeComputeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SwitchRunningMode\": {\n      \"@id\": \"amz:SwitchRunningMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RebuildWorkspace\": {\n      \"@id\": \"amz:RebuildWorkspace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceTypeChromeOs\": {\n      \"@id\": \"amz:DeviceTypeChromeOs\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"DeviceTypeZeroClient\": {\n      \"@id\": \"amz:DeviceTypeZeroClient\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RunningMode\": {\n      \"@id\": \"amz:RunningMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RunningModeAutoStopTimeoutInMinutes\": {\n      \"@id\": \"amz:RunningModeAutoStopTimeoutInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RootVolumeSizeGib\": {\n      \"@id\": \"amz:RootVolumeSizeGib\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserVolumeSizeGib\": {\n      \"@id\": \"amz:UserVolumeSizeGib\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ComputeTypeName\": {\n      \"@id\": \"amz:ComputeTypeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Protocols\": {\n      \"@id\": \"amz:Protocols\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingCreateStandbyWorkspacesRequest\": \"amz:PendingCreateStandbyWorkspacesRequest\",\n    \"RebootRequest\": \"amz:RebootRequest\",\n    \"RebuildRequest\": \"amz:RebuildRequest\"\
  ,\n    \"RelatedWorkspaceProperties\": \"amz:RelatedWorkspaceProperties\",\n    \"Region\": {\n      \"@id\": \"amz:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Snapshot\": \"amz:Snapshot\",\n    \"SnapshotTime\": {\n      \"@id\": \"amz:SnapshotTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartRequest\": \"amz:StartRequest\",\n    \"StopRequest\": \"amz:StopRequest\",\n    \"Tag\": \"amz:Tag\",\n    \"Key\": {\n      \"@id\": \"amz:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amz:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TerminateRequest\": \"amz:TerminateRequest\",\n    \"UpdateResult\": \"amz:UpdateResult\",\n    \"UpdateAvailable\": {\n      \"@id\": \"amz:UpdateAvailable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Workspace\": \"amz:Workspace\",\n    \"IpAddress\": {\n      \"@id\": \"amz:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetId\": {\n      \"@id\": \"amz:SubnetId\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"ComputerName\": {\n      \"@id\": \"amz:ComputerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModificationStates\": {\n      \"@id\": \"amz:ModificationStates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelatedWorkspaces\": {\n      \"@id\": \"amz:RelatedWorkspaces\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspaceConnectionStatus\": \"amz:WorkspaceConnectionStatus\",\n    \"ConnectionState\": {\n      \"@id\": \"amz:ConnectionState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionStateCheckTimestamp\": {\n      \"@id\": \"amz:ConnectionStateCheckTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastKnownUserConnectionTimestamp\": {\n      \"@id\": \"amz:LastKnownUserConnectionTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspaceImage\": \"amz:WorkspaceImage\",\n    \"Updates\": {\n      \"@id\": \"amz:Updates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkspacesIpGroup\"\
  : \"amz:WorkspacesIpGroup\",\n    \"groupId\": {\n      \"@id\": \"amz:groupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupName\": {\n      \"@id\": \"amz:groupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupDesc\": {\n      \"@id\": \"amz:groupDesc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userRules\": {\n      \"@id\": \"amz:userRules\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-workspaces/refs/heads/main/json-ld/amazon-workspaces-context.jsonld
tags:
- Desktop
- End User Computing
- Virtual Desktop
- Desktop as a Service
- JSON-LD
- Linked Data
- Semantic Web
---
