---
api_specs:
- filename: amazon-workmail-openapi-original.yaml
  format: yaml
  label: Amazon WorkMail API
  slug: amazon-workmail-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/openapi/amazon-workmail-openapi-original.yaml
class_count: 184
classes:
- AccessControlRule
- AssociateDelegateToResourceRequest
- AssociateDelegateToResourceResponse
- AssociateMemberToGroupRequest
- AssociateMemberToGroupResponse
- AssumeImpersonationRoleRequest
- AssumeImpersonationRoleResponse
- AvailabilityConfiguration
- CancelMailboxExportJobRequest
- CancelMailboxExportJobResponse
- CreateAliasRequest
- CreateAliasResponse
- CreateAvailabilityConfigurationRequest
- CreateAvailabilityConfigurationResponse
- CreateGroupRequest
- CreateGroupResponse
- CreateImpersonationRoleRequest
- CreateImpersonationRoleResponse
- CreateMobileDeviceAccessRuleRequest
- CreateMobileDeviceAccessRuleResponse
- CreateOrganizationRequest
- CreateOrganizationResponse
- CreateResourceRequest
- CreateResourceResponse
- CreateUserRequest
- CreateUserResponse
- Delegate
- DeleteAccessControlRuleRequest
- DeleteAccessControlRuleResponse
- DeleteAliasRequest
- DeleteAliasResponse
- DeleteAvailabilityConfigurationRequest
- DeleteAvailabilityConfigurationResponse
- DeleteEmailMonitoringConfigurationRequest
- DeleteEmailMonitoringConfigurationResponse
- DeleteGroupRequest
- DeleteGroupResponse
- DeleteImpersonationRoleRequest
- DeleteImpersonationRoleResponse
- DeleteMailboxPermissionsRequest
- DeleteMailboxPermissionsResponse
- DeleteMobileDeviceAccessOverrideRequest
- DeleteMobileDeviceAccessOverrideResponse
- DeleteMobileDeviceAccessRuleRequest
- DeleteMobileDeviceAccessRuleResponse
- DeleteOrganizationRequest
- DeleteOrganizationResponse
- DeleteResourceRequest
- DeleteResourceResponse
- DeleteRetentionPolicyRequest
- DeleteRetentionPolicyResponse
- DeleteUserRequest
- DeleteUserResponse
- DeregisterFromWorkMailRequest
- DeregisterFromWorkMailResponse
- DeregisterMailDomainRequest
- DeregisterMailDomainResponse
- DescribeEmailMonitoringConfigurationRequest
- DescribeEmailMonitoringConfigurationResponse
- DescribeGroupRequest
- DescribeGroupResponse
- DescribeInboundDmarcSettingsRequest
- DescribeInboundDmarcSettingsResponse
- DescribeMailboxExportJobRequest
- DescribeMailboxExportJobResponse
- DescribeOrganizationRequest
- DescribeOrganizationResponse
- DescribeResourceRequest
- DescribeResourceResponse
- DescribeUserRequest
- DescribeUserResponse
- DisassociateDelegateFromResourceRequest
- DisassociateDelegateFromResourceResponse
- DisassociateMemberFromGroupRequest
- DisassociateMemberFromGroupResponse
- DnsRecord
- Domain
- EwsAvailabilityProvider
- FolderConfiguration
- GetAccessControlEffectRequest
- GetAccessControlEffectResponse
- GetDefaultRetentionPolicyRequest
- GetDefaultRetentionPolicyResponse
- GetImpersonationRoleEffectRequest
- GetImpersonationRoleEffectResponse
- GetImpersonationRoleRequest
- GetImpersonationRoleResponse
- GetMailDomainRequest
- GetMailDomainResponse
- GetMailboxDetailsRequest
- GetMailboxDetailsResponse
- GetMobileDeviceAccessEffectRequest
- GetMobileDeviceAccessEffectResponse
- GetMobileDeviceAccessOverrideRequest
- GetMobileDeviceAccessOverrideResponse
- Group
- ImpersonationMatchedRule
- ImpersonationRole
- ImpersonationRule
- LambdaAvailabilityProvider
- ListAccessControlRulesRequest
- ListAccessControlRulesResponse
- ListAliasesRequest
- ListAliasesResponse
- ListAvailabilityConfigurationsRequest
- ListAvailabilityConfigurationsResponse
- ListGroupMembersRequest
- ListGroupMembersResponse
- ListGroupsRequest
- ListGroupsResponse
- ListImpersonationRolesRequest
- ListImpersonationRolesResponse
- ListMailDomainsRequest
- ListMailDomainsResponse
- ListMailboxExportJobsRequest
- ListMailboxExportJobsResponse
- ListMailboxPermissionsRequest
- ListMailboxPermissionsResponse
- ListMobileDeviceAccessOverridesRequest
- ListMobileDeviceAccessOverridesResponse
- ListMobileDeviceAccessRulesRequest
- ListMobileDeviceAccessRulesResponse
- ListOrganizationsRequest
- ListOrganizationsResponse
- ListResourceDelegatesRequest
- ListResourceDelegatesResponse
- ListResourcesRequest
- ListResourcesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListUsersRequest
- ListUsersResponse
- MailDomainSummary
- MailboxExportJob
- Member
- MobileDeviceAccessMatchedRule
- MobileDeviceAccessOverride
- MobileDeviceAccessRule
- OrganizationSummary
- Permission
- PutAccessControlRuleRequest
- PutAccessControlRuleResponse
- PutEmailMonitoringConfigurationRequest
- PutEmailMonitoringConfigurationResponse
- PutInboundDmarcSettingsRequest
- PutInboundDmarcSettingsResponse
- PutMailboxPermissionsRequest
- PutMailboxPermissionsResponse
- PutMobileDeviceAccessOverrideRequest
- PutMobileDeviceAccessOverrideResponse
- PutRetentionPolicyRequest
- PutRetentionPolicyResponse
- RedactedEwsAvailabilityProvider
- RegisterMailDomainRequest
- RegisterMailDomainResponse
- RegisterToWorkMailRequest
- RegisterToWorkMailResponse
- ResetPasswordRequest
- ResetPasswordResponse
- Resource
- StartMailboxExportJobRequest
- StartMailboxExportJobResponse
- TagResourceRequest
- TagResourceResponse
- Tag
- TestAvailabilityConfigurationRequest
- TestAvailabilityConfigurationResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateAvailabilityConfigurationRequest
- UpdateAvailabilityConfigurationResponse
- UpdateDefaultMailDomainRequest
- UpdateDefaultMailDomainResponse
- UpdateImpersonationRoleRequest
- UpdateImpersonationRoleResponse
- UpdateMailboxQuotaRequest
- UpdateMailboxQuotaResponse
- UpdateMobileDeviceAccessRuleRequest
- UpdateMobileDeviceAccessRuleResponse
- UpdatePrimaryEmailAddressRequest
- UpdatePrimaryEmailAddressResponse
- UpdateResourceRequest
- UpdateResourceResponse
- User
context_file: json-ld/amazon-workmail-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/json-ld/amazon-workmail-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Workmail from Amazon WorkMail.
layout: jsonld
name: Amazon Workmail Context
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
  name: Name
  type: string
- container: ''
  name: Effect
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: IpRanges
  type: string
- container: ''
  name: NotIpRanges
  type: string
- container: ''
  name: Actions
  type: string
- container: ''
  name: NotActions
  type: string
- container: ''
  name: UserIds
  type: string
- container: ''
  name: NotUserIds
  type: string
- container: ''
  name: DateCreated
  type: string
- container: ''
  name: DateModified
  type: string
- container: ''
  name: ImpersonationRoleIds
  type: string
- container: ''
  name: NotImpersonationRoleIds
  type: string
- container: ''
  name: OrganizationId
  type: string
- container: ''
  name: ResourceId
  type: string
- container: ''
  name: EntityId
  type: string
- container: ''
  name: GroupId
  type: string
- container: ''
  name: MemberId
  type: string
- container: ''
  name: ImpersonationRoleId
  type: string
- container: ''
  name: Token
  type: string
- container: ''
  name: ExpiresIn
  type: string
- container: ''
  name: DomainName
  type: string
- container: ''
  name: ProviderType
  type: string
- container: ''
  name: EwsProvider
  type: string
- container: ''
  name: LambdaProvider
  type: string
- container: ''
  name: BookingOptions
  type: string
- container: ''
  name: AutoAcceptRequests
  type: string
- container: ''
  name: AutoDeclineRecurringRequests
  type: string
- container: ''
  name: AutoDeclineConflictingRequests
  type: string
- container: ''
  name: ClientToken
  type: string
- container: ''
  name: JobId
  type: string
- container: ''
  name: Alias
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: Rules
  type: string
- container: ''
  name: DeviceTypes
  type: string
- container: ''
  name: NotDeviceTypes
  type: string
- container: ''
  name: DeviceModels
  type: string
- container: ''
  name: NotDeviceModels
  type: string
- container: ''
  name: DeviceOperatingSystems
  type: string
- container: ''
  name: NotDeviceOperatingSystems
  type: string
- container: ''
  name: DeviceUserAgents
  type: string
- container: ''
  name: NotDeviceUserAgents
  type: string
- container: ''
  name: MobileDeviceAccessRuleId
  type: string
- container: ''
  name: DirectoryId
  type: string
- container: ''
  name: Domains
  type: string
- container: ''
  name: KmsKeyArn
  type: string
- container: ''
  name: EnableInteroperability
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: Password
  type: string
- container: ''
  name: UserId
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: GranteeId
  type: string
- container: ''
  name: DeviceId
  type: string
- container: ''
  name: DeleteDirectory
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: LogGroupArn
  type: string
- container: ''
  name: Email
  type: string
- container: ''
  name: EnabledDate
  type: string
- container: ''
  name: DisabledDate
  type: string
- container: ''
  name: Enforced
  type: string
- container: ''
  name: S3BucketName
  type: string
- container: ''
  name: S3Prefix
  type: string
- container: ''
  name: S3Path
  type: string
- container: ''
  name: EstimatedProgress
  type: string
- container: ''
  name: ErrorInfo
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: EndTime
  type: string
- container: ''
  name: DirectoryType
  type: string
- container: ''
  name: DefaultMailDomain
  type: string
- container: ''
  name: CompletedDate
  type: string
- container: ''
  name: ErrorMessage
  type: string
- container: ''
  name: ARN
  type: string
- container: ''
  name: UserRole
  type: string
- container: ''
  name: Hostname
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: HostedZoneId
  type: string
- container: ''
  name: EwsEndpoint
  type: string
- container: ''
  name: EwsUsername
  type: string
- container: ''
  name: EwsPassword
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: Period
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: MatchedRules
  type: string
- container: ''
  name: FolderConfigurations
  type: string
- container: ''
  name: TargetUser
  type: string
- container: ''
  name: Records
  type: string
- container: ''
  name: IsTestDomain
  type: string
- container: ''
  name: IsDefault
  type: string
- container: ''
  name: OwnershipVerificationStatus
  type: string
- container: ''
  name: DkimVerificationStatus
  type: string
- container: ''
  name: MailboxQuota
  type: string
- container: ''
  name: MailboxSize
  type: string
- container: ''
  name: DeviceType
  type: string
- container: ''
  name: DeviceModel
  type: string
- container: ''
  name: DeviceOperatingSystem
  type: string
- container: ''
  name: DeviceUserAgent
  type: string
- container: ''
  name: ImpersonationRuleId
  type: string
- container: ''
  name: TargetUsers
  type: string
- container: ''
  name: NotTargetUsers
  type: string
- container: ''
  name: LambdaArn
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: Aliases
  type: string
- container: ''
  name: AvailabilityConfigurations
  type: string
- container: ''
  name: Members
  type: string
- container: ''
  name: Groups
  type: string
- container: ''
  name: Roles
  type: string
- container: ''
  name: MailDomains
  type: string
- container: ''
  name: Jobs
  type: string
- container: ''
  name: Permissions
  type: string
- container: ''
  name: Overrides
  type: string
- container: ''
  name: OrganizationSummaries
  type: string
- container: ''
  name: Delegates
  type: string
- container: ''
  name: Resources
  type: string
- container: ''
  name: ResourceARN
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Users
  type: string
- container: ''
  name: DefaultDomain
  type: string
- container: ''
  name: GranteeType
  type: string
- container: ''
  name: PermissionValues
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: TestPassed
  type: string
- container: ''
  name: FailureReason
  type: string
- container: ''
  name: TagKeys
  type: string
property_count: 125
provider_name: Amazon WorkMail
provider_slug: amazon-workmail
slug: amazon-workmail-context
source_filename: amazon-workmail-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessControlRule\": \"amz:AccessControlRule\",\n    \"Name\": {\n      \"@id\": \"amz:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Effect\": {\n      \"@id\": \"amz:Effect\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"amz:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpRanges\": {\n      \"@id\": \"amz:IpRanges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotIpRanges\": {\n      \"@id\": \"amz:NotIpRanges\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Actions\": {\n      \"@id\": \"amz:Actions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotActions\": {\n      \"@id\": \"amz:NotActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserIds\": {\n\
  \      \"@id\": \"amz:UserIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotUserIds\": {\n      \"@id\": \"amz:NotUserIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DateCreated\": {\n      \"@id\": \"amz:DateCreated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DateModified\": {\n      \"@id\": \"amz:DateModified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpersonationRoleIds\": {\n      \"@id\": \"amz:ImpersonationRoleIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotImpersonationRoleIds\": {\n      \"@id\": \"amz:NotImpersonationRoleIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateDelegateToResourceRequest\": \"amz:AssociateDelegateToResourceRequest\",\n    \"OrganizationId\": {\n      \"@id\": \"amz:OrganizationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceId\": {\n      \"@id\": \"amz:ResourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityId\": {\n      \"@id\": \"amz:EntityId\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"AssociateDelegateToResourceResponse\": \"amz:AssociateDelegateToResourceResponse\",\n    \"AssociateMemberToGroupRequest\": \"amz:AssociateMemberToGroupRequest\",\n    \"GroupId\": {\n      \"@id\": \"amz:GroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MemberId\": {\n      \"@id\": \"amz:MemberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateMemberToGroupResponse\": \"amz:AssociateMemberToGroupResponse\",\n    \"AssumeImpersonationRoleRequest\": \"amz:AssumeImpersonationRoleRequest\",\n    \"ImpersonationRoleId\": {\n      \"@id\": \"amz:ImpersonationRoleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssumeImpersonationRoleResponse\": \"amz:AssumeImpersonationRoleResponse\",\n    \"Token\": {\n      \"@id\": \"amz:Token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiresIn\": {\n      \"@id\": \"amz:ExpiresIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityConfiguration\": \"amz:AvailabilityConfiguration\",\n    \"DomainName\"\
  : {\n      \"@id\": \"amz:DomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderType\": {\n      \"@id\": \"amz:ProviderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EwsProvider\": {\n      \"@id\": \"amz:EwsProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LambdaProvider\": {\n      \"@id\": \"amz:LambdaProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BookingOptions\": {\n      \"@id\": \"amz:BookingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoAcceptRequests\": {\n      \"@id\": \"amz:AutoAcceptRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoDeclineRecurringRequests\": {\n      \"@id\": \"amz:AutoDeclineRecurringRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoDeclineConflictingRequests\": {\n      \"@id\": \"amz:AutoDeclineConflictingRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelMailboxExportJobRequest\": \"amz:CancelMailboxExportJobRequest\",\n    \"ClientToken\": {\n\
  \      \"@id\": \"amz:ClientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobId\": {\n      \"@id\": \"amz:JobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelMailboxExportJobResponse\": \"amz:CancelMailboxExportJobResponse\",\n    \"CreateAliasRequest\": \"amz:CreateAliasRequest\",\n    \"Alias\": {\n      \"@id\": \"amz:Alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateAliasResponse\": \"amz:CreateAliasResponse\",\n    \"CreateAvailabilityConfigurationRequest\": \"amz:CreateAvailabilityConfigurationRequest\",\n    \"CreateAvailabilityConfigurationResponse\": \"amz:CreateAvailabilityConfigurationResponse\",\n    \"CreateGroupRequest\": \"amz:CreateGroupRequest\",\n    \"CreateGroupResponse\": \"amz:CreateGroupResponse\",\n    \"CreateImpersonationRoleRequest\": \"amz:CreateImpersonationRoleRequest\",\n    \"Type\": {\n      \"@id\": \"amz:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Rules\": {\n      \"@id\": \"amz:Rules\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"CreateImpersonationRoleResponse\": \"amz:CreateImpersonationRoleResponse\",\n    \"CreateMobileDeviceAccessRuleRequest\": \"amz:CreateMobileDeviceAccessRuleRequest\",\n    \"DeviceTypes\": {\n      \"@id\": \"amz:DeviceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotDeviceTypes\": {\n      \"@id\": \"amz:NotDeviceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceModels\": {\n      \"@id\": \"amz:DeviceModels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotDeviceModels\": {\n      \"@id\": \"amz:NotDeviceModels\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceOperatingSystems\": {\n      \"@id\": \"amz:DeviceOperatingSystems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotDeviceOperatingSystems\": {\n      \"@id\": \"amz:NotDeviceOperatingSystems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceUserAgents\": {\n      \"@id\": \"amz:DeviceUserAgents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotDeviceUserAgents\"\
  : {\n      \"@id\": \"amz:NotDeviceUserAgents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMobileDeviceAccessRuleResponse\": \"amz:CreateMobileDeviceAccessRuleResponse\",\n    \"MobileDeviceAccessRuleId\": {\n      \"@id\": \"amz:MobileDeviceAccessRuleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateOrganizationRequest\": \"amz:CreateOrganizationRequest\",\n    \"DirectoryId\": {\n      \"@id\": \"amz:DirectoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Domains\": {\n      \"@id\": \"amz:Domains\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyArn\": {\n      \"@id\": \"amz:KmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableInteroperability\": {\n      \"@id\": \"amz:EnableInteroperability\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateOrganizationResponse\": \"amz:CreateOrganizationResponse\",\n    \"CreateResourceRequest\": \"amz:CreateResourceRequest\",\n    \"CreateResourceResponse\": \"amz:CreateResourceResponse\"\
  ,\n    \"CreateUserRequest\": \"amz:CreateUserRequest\",\n    \"DisplayName\": {\n      \"@id\": \"amz:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Password\": {\n      \"@id\": \"amz:Password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateUserResponse\": \"amz:CreateUserResponse\",\n    \"UserId\": {\n      \"@id\": \"amz:UserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Delegate\": \"amz:Delegate\",\n    \"Id\": {\n      \"@id\": \"amz:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteAccessControlRuleRequest\": \"amz:DeleteAccessControlRuleRequest\",\n    \"DeleteAccessControlRuleResponse\": \"amz:DeleteAccessControlRuleResponse\",\n    \"DeleteAliasRequest\": \"amz:DeleteAliasRequest\",\n    \"DeleteAliasResponse\": \"amz:DeleteAliasResponse\",\n    \"DeleteAvailabilityConfigurationRequest\": \"amz:DeleteAvailabilityConfigurationRequest\",\n    \"DeleteAvailabilityConfigurationResponse\": \"amz:DeleteAvailabilityConfigurationResponse\"\
  ,\n    \"DeleteEmailMonitoringConfigurationRequest\": \"amz:DeleteEmailMonitoringConfigurationRequest\",\n    \"DeleteEmailMonitoringConfigurationResponse\": \"amz:DeleteEmailMonitoringConfigurationResponse\",\n    \"DeleteGroupRequest\": \"amz:DeleteGroupRequest\",\n    \"DeleteGroupResponse\": \"amz:DeleteGroupResponse\",\n    \"DeleteImpersonationRoleRequest\": \"amz:DeleteImpersonationRoleRequest\",\n    \"DeleteImpersonationRoleResponse\": \"amz:DeleteImpersonationRoleResponse\",\n    \"DeleteMailboxPermissionsRequest\": \"amz:DeleteMailboxPermissionsRequest\",\n    \"GranteeId\": {\n      \"@id\": \"amz:GranteeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteMailboxPermissionsResponse\": \"amz:DeleteMailboxPermissionsResponse\",\n    \"DeleteMobileDeviceAccessOverrideRequest\": \"amz:DeleteMobileDeviceAccessOverrideRequest\",\n    \"DeviceId\": {\n      \"@id\": \"amz:DeviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteMobileDeviceAccessOverrideResponse\"\
  : \"amz:DeleteMobileDeviceAccessOverrideResponse\",\n    \"DeleteMobileDeviceAccessRuleRequest\": \"amz:DeleteMobileDeviceAccessRuleRequest\",\n    \"DeleteMobileDeviceAccessRuleResponse\": \"amz:DeleteMobileDeviceAccessRuleResponse\",\n    \"DeleteOrganizationRequest\": \"amz:DeleteOrganizationRequest\",\n    \"DeleteDirectory\": {\n      \"@id\": \"amz:DeleteDirectory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteOrganizationResponse\": \"amz:DeleteOrganizationResponse\",\n    \"State\": {\n      \"@id\": \"amz:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteResourceRequest\": \"amz:DeleteResourceRequest\",\n    \"DeleteResourceResponse\": \"amz:DeleteResourceResponse\",\n    \"DeleteRetentionPolicyRequest\": \"amz:DeleteRetentionPolicyRequest\",\n    \"DeleteRetentionPolicyResponse\": \"amz:DeleteRetentionPolicyResponse\",\n    \"DeleteUserRequest\": \"amz:DeleteUserRequest\",\n    \"DeleteUserResponse\": \"amz:DeleteUserResponse\",\n    \"DeregisterFromWorkMailRequest\"\
  : \"amz:DeregisterFromWorkMailRequest\",\n    \"DeregisterFromWorkMailResponse\": \"amz:DeregisterFromWorkMailResponse\",\n    \"DeregisterMailDomainRequest\": \"amz:DeregisterMailDomainRequest\",\n    \"DeregisterMailDomainResponse\": \"amz:DeregisterMailDomainResponse\",\n    \"DescribeEmailMonitoringConfigurationRequest\": \"amz:DescribeEmailMonitoringConfigurationRequest\",\n    \"DescribeEmailMonitoringConfigurationResponse\": \"amz:DescribeEmailMonitoringConfigurationResponse\",\n    \"RoleArn\": {\n      \"@id\": \"amz:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogGroupArn\": {\n      \"@id\": \"amz:LogGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeGroupRequest\": \"amz:DescribeGroupRequest\",\n    \"DescribeGroupResponse\": \"amz:DescribeGroupResponse\",\n    \"Email\": {\n      \"@id\": \"amz:Email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnabledDate\": {\n      \"@id\": \"amz:EnabledDate\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"DisabledDate\": {\n      \"@id\": \"amz:DisabledDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeInboundDmarcSettingsRequest\": \"amz:DescribeInboundDmarcSettingsRequest\",\n    \"DescribeInboundDmarcSettingsResponse\": \"amz:DescribeInboundDmarcSettingsResponse\",\n    \"Enforced\": {\n      \"@id\": \"amz:Enforced\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeMailboxExportJobRequest\": \"amz:DescribeMailboxExportJobRequest\",\n    \"DescribeMailboxExportJobResponse\": \"amz:DescribeMailboxExportJobResponse\",\n    \"S3BucketName\": {\n      \"@id\": \"amz:S3BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Prefix\": {\n      \"@id\": \"amz:S3Prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Path\": {\n      \"@id\": \"amz:S3Path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EstimatedProgress\": {\n      \"@id\": \"amz:EstimatedProgress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorInfo\": {\n      \"@id\": \"amz:ErrorInfo\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"amz:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"amz:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeOrganizationRequest\": \"amz:DescribeOrganizationRequest\",\n    \"DescribeOrganizationResponse\": \"amz:DescribeOrganizationResponse\",\n    \"DirectoryType\": {\n      \"@id\": \"amz:DirectoryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultMailDomain\": {\n      \"@id\": \"amz:DefaultMailDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompletedDate\": {\n      \"@id\": \"amz:CompletedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorMessage\": {\n      \"@id\": \"amz:ErrorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ARN\": {\n      \"@id\": \"amz:ARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeResourceRequest\": \"amz:DescribeResourceRequest\",\n    \"DescribeResourceResponse\"\
  : \"amz:DescribeResourceResponse\",\n    \"DescribeUserRequest\": \"amz:DescribeUserRequest\",\n    \"DescribeUserResponse\": \"amz:DescribeUserResponse\",\n    \"UserRole\": {\n      \"@id\": \"amz:UserRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisassociateDelegateFromResourceRequest\": \"amz:DisassociateDelegateFromResourceRequest\",\n    \"DisassociateDelegateFromResourceResponse\": \"amz:DisassociateDelegateFromResourceResponse\",\n    \"DisassociateMemberFromGroupRequest\": \"amz:DisassociateMemberFromGroupRequest\",\n    \"DisassociateMemberFromGroupResponse\": \"amz:DisassociateMemberFromGroupResponse\",\n    \"DnsRecord\": \"amz:DnsRecord\",\n    \"Hostname\": {\n      \"@id\": \"amz:Hostname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amz:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Domain\": \"amz:Domain\",\n    \"HostedZoneId\": {\n      \"@id\": \"amz:HostedZoneId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  EwsAvailabilityProvider\": \"amz:EwsAvailabilityProvider\",\n    \"EwsEndpoint\": {\n      \"@id\": \"amz:EwsEndpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EwsUsername\": {\n      \"@id\": \"amz:EwsUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EwsPassword\": {\n      \"@id\": \"amz:EwsPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FolderConfiguration\": \"amz:FolderConfiguration\",\n    \"Action\": {\n      \"@id\": \"amz:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Period\": {\n      \"@id\": \"amz:Period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetAccessControlEffectRequest\": \"amz:GetAccessControlEffectRequest\",\n    \"IpAddress\": {\n      \"@id\": \"amz:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetAccessControlEffectResponse\": \"amz:GetAccessControlEffectResponse\",\n    \"MatchedRules\": {\n      \"@id\": \"amz:MatchedRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetDefaultRetentionPolicyRequest\"\
  : \"amz:GetDefaultRetentionPolicyRequest\",\n    \"GetDefaultRetentionPolicyResponse\": \"amz:GetDefaultRetentionPolicyResponse\",\n    \"FolderConfigurations\": {\n      \"@id\": \"amz:FolderConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetImpersonationRoleEffectRequest\": \"amz:GetImpersonationRoleEffectRequest\",\n    \"TargetUser\": {\n      \"@id\": \"amz:TargetUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetImpersonationRoleEffectResponse\": \"amz:GetImpersonationRoleEffectResponse\",\n    \"GetImpersonationRoleRequest\": \"amz:GetImpersonationRoleRequest\",\n    \"GetImpersonationRoleResponse\": \"amz:GetImpersonationRoleResponse\",\n    \"GetMailDomainRequest\": \"amz:GetMailDomainRequest\",\n    \"GetMailDomainResponse\": \"amz:GetMailDomainResponse\",\n    \"Records\": {\n      \"@id\": \"amz:Records\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsTestDomain\": {\n      \"@id\": \"amz:IsTestDomain\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"IsDefault\": {\n      \"@id\": \"amz:IsDefault\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnershipVerificationStatus\": {\n      \"@id\": \"amz:OwnershipVerificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DkimVerificationStatus\": {\n      \"@id\": \"amz:DkimVerificationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMailboxDetailsRequest\": \"amz:GetMailboxDetailsRequest\",\n    \"GetMailboxDetailsResponse\": \"amz:GetMailboxDetailsResponse\",\n    \"MailboxQuota\": {\n      \"@id\": \"amz:MailboxQuota\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MailboxSize\": {\n      \"@id\": \"amz:MailboxSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMobileDeviceAccessEffectRequest\": \"amz:GetMobileDeviceAccessEffectRequest\",\n    \"DeviceType\": {\n      \"@id\": \"amz:DeviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceModel\": {\n      \"@id\": \"amz:DeviceModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  DeviceOperatingSystem\": {\n      \"@id\": \"amz:DeviceOperatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeviceUserAgent\": {\n      \"@id\": \"amz:DeviceUserAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMobileDeviceAccessEffectResponse\": \"amz:GetMobileDeviceAccessEffectResponse\",\n    \"GetMobileDeviceAccessOverrideRequest\": \"amz:GetMobileDeviceAccessOverrideRequest\",\n    \"GetMobileDeviceAccessOverrideResponse\": \"amz:GetMobileDeviceAccessOverrideResponse\",\n    \"Group\": \"amz:Group\",\n    \"ImpersonationMatchedRule\": \"amz:ImpersonationMatchedRule\",\n    \"ImpersonationRuleId\": {\n      \"@id\": \"amz:ImpersonationRuleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImpersonationRole\": \"amz:ImpersonationRole\",\n    \"ImpersonationRule\": \"amz:ImpersonationRule\",\n    \"TargetUsers\": {\n      \"@id\": \"amz:TargetUsers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotTargetUsers\": {\n      \"@id\": \"amz:NotTargetUsers\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LambdaAvailabilityProvider\": \"amz:LambdaAvailabilityProvider\",\n    \"LambdaArn\": {\n      \"@id\": \"amz:LambdaArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAccessControlRulesRequest\": \"amz:ListAccessControlRulesRequest\",\n    \"ListAccessControlRulesResponse\": \"amz:ListAccessControlRulesResponse\",\n    \"ListAliasesRequest\": \"amz:ListAliasesRequest\",\n    \"NextToken\": {\n      \"@id\": \"amz:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"amz:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAliasesResponse\": \"amz:ListAliasesResponse\",\n    \"Aliases\": {\n      \"@id\": \"amz:Aliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListAvailabilityConfigurationsRequest\": \"amz:ListAvailabilityConfigurationsRequest\",\n    \"ListAvailabilityConfigurationsResponse\": \"amz:ListAvailabilityConfigurationsResponse\",\n    \"AvailabilityConfigurations\"\
  : {\n      \"@id\": \"amz:AvailabilityConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListGroupMembersRequest\": \"amz:ListGroupMembersRequest\",\n    \"ListGroupMembersResponse\": \"amz:ListGroupMembersResponse\",\n    \"Members\": {\n      \"@id\": \"amz:Members\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListGroupsRequest\": \"amz:ListGroupsRequest\",\n    \"ListGroupsResponse\": \"amz:ListGroupsResponse\",\n    \"Groups\": {\n      \"@id\": \"amz:Groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListImpersonationRolesRequest\": \"amz:ListImpersonationRolesRequest\",\n    \"ListImpersonationRolesResponse\": \"amz:ListImpersonationRolesResponse\",\n    \"Roles\": {\n      \"@id\": \"amz:Roles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListMailDomainsRequest\": \"amz:ListMailDomainsRequest\",\n    \"ListMailDomainsResponse\": \"amz:ListMailDomainsResponse\",\n    \"MailDomains\": {\n      \"@id\": \"amz:MailDomains\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ListMailboxExportJobsRequest\": \"amz:ListMailboxExportJobsRequest\",\n    \"ListMailboxExportJobsResponse\": \"amz:ListMailboxExportJobsResponse\",\n    \"Jobs\": {\n      \"@id\": \"amz:Jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListMailboxPermissionsRequest\": \"amz:ListMailboxPermissionsRequest\",\n    \"ListMailboxPermissionsResponse\": \"amz:ListMailboxPermissionsResponse\",\n    \"Permissions\": {\n      \"@id\": \"amz:Permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListMobileDeviceAccessOverridesRequest\": \"amz:ListMobileDeviceAccessOverridesRequest\",\n    \"ListMobileDeviceAccessOverridesResponse\": \"amz:ListMobileDeviceAccessOverridesResponse\",\n    \"Overrides\": {\n      \"@id\": \"amz:Overrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListMobileDeviceAccessRulesRequest\": \"amz:ListMobileDeviceAccessRulesRequest\",\n    \"ListMobileDeviceAccessRulesResponse\": \"amz:ListMobileDeviceAccessRulesResponse\",\n    \"ListOrganizationsRequest\"\
  : \"amz:ListOrganizationsRequest\",\n    \"ListOrganizationsResponse\": \"amz:ListOrganizationsResponse\",\n    \"OrganizationSummaries\": {\n      \"@id\": \"amz:OrganizationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListResourceDelegatesRequest\": \"amz:ListResourceDelegatesRequest\",\n    \"ListResourceDelegatesResponse\": \"amz:ListResourceDelegatesResponse\",\n    \"Delegates\": {\n      \"@id\": \"amz:Delegates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListResourcesRequest\": \"amz:ListResourcesRequest\",\n    \"ListResourcesResponse\": \"amz:ListResourcesResponse\",\n    \"Resources\": {\n      \"@id\": \"amz:Resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceRequest\": \"amz:ListTagsForResourceRequest\",\n    \"ResourceARN\": {\n      \"@id\": \"amz:ResourceARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceResponse\": \"amz:ListTagsForResourceResponse\",\n    \"Tags\": {\n      \"@id\": \"amz:Tags\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ListUsersRequest\": \"amz:ListUsersRequest\",\n    \"ListUsersResponse\": \"amz:ListUsersResponse\",\n    \"Users\": {\n      \"@id\": \"amz:Users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MailDomainSummary\": \"amz:MailDomainSummary\",\n    \"DefaultDomain\": {\n      \"@id\": \"amz:DefaultDomain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MailboxExportJob\": \"amz:MailboxExportJob\",\n    \"Member\": \"amz:Member\",\n    \"MobileDeviceAccessMatchedRule\": \"amz:MobileDeviceAccessMatchedRule\",\n    \"MobileDeviceAccessOverride\": \"amz:MobileDeviceAccessOverride\",\n    \"MobileDeviceAccessRule\": \"amz:MobileDeviceAccessRule\",\n    \"OrganizationSummary\": \"amz:OrganizationSummary\",\n    \"Permission\": \"amz:Permission\",\n    \"GranteeType\": {\n      \"@id\": \"amz:GranteeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionValues\": {\n      \"@id\": \"amz:PermissionValues\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"PutAccessControlRuleRequest\": \"amz:PutAccessControlRuleRequest\",\n    \"PutAccessControlRuleResponse\": \"amz:PutAccessControlRuleResponse\",\n    \"PutEmailMonitoringConfigurationRequest\": \"amz:PutEmailMonitoringConfigurationRequest\",\n    \"PutEmailMonitoringConfigurationResponse\": \"amz:PutEmailMonitoringConfigurationResponse\",\n    \"PutInboundDmarcSettingsRequest\": \"amz:PutInboundDmarcSettingsRequest\",\n    \"PutInboundDmarcSettingsResponse\": \"amz:PutInboundDmarcSettingsResponse\",\n    \"PutMailboxPermissionsRequest\": \"amz:PutMailboxPermissionsRequest\",\n    \"PutMailboxPermissionsResponse\": \"amz:PutMailboxPermissionsResponse\",\n    \"PutMobileDeviceAccessOverrideRequest\": \"amz:PutMobileDeviceAccessOverrideRequest\",\n    \"PutMobileDeviceAccessOverrideResponse\": \"amz:PutMobileDeviceAccessOverrideResponse\",\n    \"PutRetentionPolicyRequest\": \"amz:PutRetentionPolicyRequest\",\n    \"PutRetentionPolicyResponse\": \"amz:PutRetentionPolicyResponse\"\
  ,\n    \"RedactedEwsAvailabilityProvider\": \"amz:RedactedEwsAvailabilityProvider\",\n    \"RegisterMailDomainRequest\": \"amz:RegisterMailDomainRequest\",\n    \"RegisterMailDomainResponse\": \"amz:RegisterMailDomainResponse\",\n    \"RegisterToWorkMailRequest\": \"amz:RegisterToWorkMailRequest\",\n    \"RegisterToWorkMailResponse\": \"amz:RegisterToWorkMailResponse\",\n    \"ResetPasswordRequest\": \"amz:ResetPasswordRequest\",\n    \"ResetPasswordResponse\": \"amz:ResetPasswordResponse\",\n    \"Resource\": \"amz:Resource\",\n    \"StartMailboxExportJobRequest\": \"amz:StartMailboxExportJobRequest\",\n    \"StartMailboxExportJobResponse\": \"amz:StartMailboxExportJobResponse\",\n    \"TagResourceRequest\": \"amz:TagResourceRequest\",\n    \"TagResourceResponse\": \"amz:TagResourceResponse\",\n    \"Tag\": \"amz:Tag\",\n    \"Key\": {\n      \"@id\": \"amz:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TestAvailabilityConfigurationRequest\": \"amz:TestAvailabilityConfigurationRequest\"\
  ,\n    \"TestAvailabilityConfigurationResponse\": \"amz:TestAvailabilityConfigurationResponse\",\n    \"TestPassed\": {\n      \"@id\": \"amz:TestPassed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailureReason\": {\n      \"@id\": \"amz:FailureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceRequest\": \"amz:UntagResourceRequest\",\n    \"TagKeys\": {\n      \"@id\": \"amz:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceResponse\": \"amz:UntagResourceResponse\",\n    \"UpdateAvailabilityConfigurationRequest\": \"amz:UpdateAvailabilityConfigurationRequest\",\n    \"UpdateAvailabilityConfigurationResponse\": \"amz:UpdateAvailabilityConfigurationResponse\",\n    \"UpdateDefaultMailDomainRequest\": \"amz:UpdateDefaultMailDomainRequest\",\n    \"UpdateDefaultMailDomainResponse\": \"amz:UpdateDefaultMailDomainResponse\",\n    \"UpdateImpersonationRoleRequest\": \"amz:UpdateImpersonationRoleRequest\",\n    \"UpdateImpersonationRoleResponse\"\
  : \"amz:UpdateImpersonationRoleResponse\",\n    \"UpdateMailboxQuotaRequest\": \"amz:UpdateMailboxQuotaRequest\",\n    \"UpdateMailboxQuotaResponse\": \"amz:UpdateMailboxQuotaResponse\",\n    \"UpdateMobileDeviceAccessRuleRequest\": \"amz:UpdateMobileDeviceAccessRuleRequest\",\n    \"UpdateMobileDeviceAccessRuleResponse\": \"amz:UpdateMobileDeviceAccessRuleResponse\",\n    \"UpdatePrimaryEmailAddressRequest\": \"amz:UpdatePrimaryEmailAddressRequest\",\n    \"UpdatePrimaryEmailAddressResponse\": \"amz:UpdatePrimaryEmailAddressResponse\",\n    \"UpdateResourceRequest\": \"amz:UpdateResourceRequest\",\n    \"UpdateResourceResponse\": \"amz:UpdateResourceResponse\",\n    \"User\": \"amz:User\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-workmail/refs/heads/main/json-ld/amazon-workmail-context.jsonld
tags:
- AWS
- Business Communication
- Calendar
- Email
- Exchange
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
