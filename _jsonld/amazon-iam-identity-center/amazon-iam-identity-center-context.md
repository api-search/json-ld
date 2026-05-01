---
api_specs:
- filename: amazon-iam-identity-center-sso-admin-openapi-original.yml
  format: yaml
  label: AWS IAM Identity Center SSO Admin API
  slug: aws-sso-admin-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/openapi/amazon-iam-identity-center-sso-admin-openapi-original.yml
- filename: amazon-iam-identity-center-identitystore-openapi-original.yml
  format: yaml
  label: AWS IAM Identity Center Identity Store API
  slug: aws-identitystore-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/openapi/amazon-iam-identity-center-identitystore-openapi-original.yml
class_count: 130
classes:
- AccessControlAttribute
- AccessControlAttributeValue
- AccountAssignment
- AccountAssignmentOperationStatus
- AccountAssignmentOperationStatusMetadata
- Address
- AttachCustomerManagedPolicyReferenceToPermissionSetRequest
- AttachCustomerManagedPolicyReferenceToPermissionSetResponse
- AttachManagedPolicyToPermissionSetRequest
- AttachManagedPolicyToPermissionSetResponse
- AttachedManagedPolicy
- AttributeOperation
- CreateAccountAssignmentRequest
- CreateAccountAssignmentResponse
- CreateGroupMembershipRequest
- CreateGroupMembershipResponse
- CreateGroupRequest
- CreateGroupResponse
- CreateInstanceAccessControlAttributeConfigurationRequest
- CreateInstanceAccessControlAttributeConfigurationResponse
- CreatePermissionSetRequest
- CreatePermissionSetResponse
- CreateUserRequest
- CreateUserResponse
- DeleteAccountAssignmentRequest
- DeleteAccountAssignmentResponse
- DeleteGroupMembershipRequest
- DeleteGroupMembershipResponse
- DeleteGroupRequest
- DeleteGroupResponse
- DeleteInlinePolicyFromPermissionSetRequest
- DeleteInlinePolicyFromPermissionSetResponse
- DeleteInstanceAccessControlAttributeConfigurationRequest
- DeleteInstanceAccessControlAttributeConfigurationResponse
- DeletePermissionSetRequest
- DeletePermissionSetResponse
- DeletePermissionsBoundaryFromPermissionSetRequest
- DeletePermissionsBoundaryFromPermissionSetResponse
- DeleteUserRequest
- DeleteUserResponse
- DescribeAccountAssignmentCreationStatusRequest
- DescribeAccountAssignmentCreationStatusResponse
- DescribeAccountAssignmentDeletionStatusRequest
- DescribeAccountAssignmentDeletionStatusResponse
- DescribeGroupMembershipRequest
- DescribeGroupMembershipResponse
- DescribeGroupRequest
- DescribeGroupResponse
- DescribeInstanceAccessControlAttributeConfigurationRequest
- DescribeInstanceAccessControlAttributeConfigurationResponse
- DescribePermissionSetProvisioningStatusRequest
- DescribePermissionSetProvisioningStatusResponse
- DescribePermissionSetRequest
- DescribePermissionSetResponse
- DescribeUserRequest
- DescribeUserResponse
- DetachCustomerManagedPolicyReferenceFromPermissionSetRequest
- DetachCustomerManagedPolicyReferenceFromPermissionSetResponse
- DetachManagedPolicyFromPermissionSetRequest
- DetachManagedPolicyFromPermissionSetResponse
- Email
- GetGroupIdRequest
- GetGroupIdResponse
- GetGroupMembershipIdRequest
- GetGroupMembershipIdResponse
- GetInlinePolicyForPermissionSetRequest
- GetInlinePolicyForPermissionSetResponse
- GetPermissionsBoundaryForPermissionSetRequest
- GetPermissionsBoundaryForPermissionSetResponse
- GetUserIdRequest
- GetUserIdResponse
- Group
- GroupMembership
- GroupMembershipExistenceResult
- InstanceMetadata
- IsMemberInGroupsRequest
- IsMemberInGroupsResponse
- ListAccountAssignmentCreationStatusRequest
- ListAccountAssignmentCreationStatusResponse
- ListAccountAssignmentDeletionStatusRequest
- ListAccountAssignmentDeletionStatusResponse
- ListAccountAssignmentsRequest
- ListAccountAssignmentsResponse
- ListAccountsForProvisionedPermissionSetRequest
- ListAccountsForProvisionedPermissionSetResponse
- ListCustomerManagedPolicyReferencesInPermissionSetRequest
- ListCustomerManagedPolicyReferencesInPermissionSetResponse
- ListGroupMembershipsForMemberRequest
- ListGroupMembershipsForMemberResponse
- ListGroupMembershipsRequest
- ListGroupMembershipsResponse
- ListGroupsRequest
- ListGroupsResponse
- ListInstancesRequest
- ListInstancesResponse
- ListManagedPoliciesInPermissionSetRequest
- ListManagedPoliciesInPermissionSetResponse
- ListPermissionSetProvisioningStatusRequest
- ListPermissionSetProvisioningStatusResponse
- ListPermissionSetsProvisionedToAccountRequest
- ListPermissionSetsProvisionedToAccountResponse
- ListPermissionSetsRequest
- ListPermissionSetsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListUsersRequest
- ListUsersResponse
- OperationStatusFilter
- PermissionSetProvisioningStatusMetadata
- PhoneNumber
- ProvisionPermissionSetRequest
- ProvisionPermissionSetResponse
- PutInlinePolicyToPermissionSetRequest
- PutInlinePolicyToPermissionSetResponse
- PutPermissionsBoundaryToPermissionSetRequest
- PutPermissionsBoundaryToPermissionSetResponse
- Tag
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateGroupRequest
- UpdateGroupResponse
- UpdateInstanceAccessControlAttributeConfigurationRequest
- UpdateInstanceAccessControlAttributeConfigurationResponse
- UpdatePermissionSetRequest
- UpdatePermissionSetResponse
- UpdateUserRequest
- UpdateUserResponse
- User
context_file: json-ld/amazon-iam-identity-center-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/json-ld/amazon-iam-identity-center-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iam Identity Center from Amazon IAM Identity Center.
layout: jsonld
name: Amazon Iam Identity Center Context
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
  name: AlternateIdentifier
  type: string
- container: ''
  name: AttributeValue
  type: string
- container: ''
  name: CustomerManagedPolicyReference
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: Filter
  type: string
- container: ''
  name: InstanceAccessControlAttributeConfiguration
  type: string
- container: ''
  name: MemberId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: PermissionSet
  type: string
- container: ''
  name: PermissionSetProvisioningStatus
  type: string
- container: ''
  name: PermissionsBoundary
  type: string
- container: ''
  name: UniqueAttribute
  type: string
- container: ''
  name: AccessControlAttributes
  type: string
- container: ''
  name: AccountAssignmentCreationRequestId
  type: string
- container: ''
  name: AccountAssignmentCreationStatus
  type: string
- container: ''
  name: AccountAssignmentDeletionRequestId
  type: string
- container: ''
  name: AccountAssignmentDeletionStatus
  type: string
- container: ''
  name: AccountAssignments
  type: string
- container: ''
  name: AccountAssignmentsCreationStatus
  type: string
- container: ''
  name: AccountAssignmentsDeletionStatus
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: AccountIds
  type: string
- container: ''
  name: Addresses
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: AttachedManagedPolicies
  type: string
- container: ''
  name: AttributePath
  type: string
- container: ''
  name: Country
  type: string
- container: ''
  name: CreatedDate
  type: string
- container: ''
  name: CustomerManagedPolicyReferences
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: Emails
  type: string
- container: ''
  name: ExternalIds
  type: string
- container: ''
  name: FailureReason
  type: string
- container: ''
  name: FamilyName
  type: string
- container: ''
  name: Filters
  type: string
- container: ''
  name: Formatted
  type: string
- container: ''
  name: GivenName
  type: string
- container: ''
  name: GroupId
  type: string
- container: ''
  name: GroupIds
  type: string
- container: ''
  name: GroupMemberships
  type: string
- container: ''
  name: Groups
  type: string
- container: ''
  name: HonorificPrefix
  type: string
- container: ''
  name: HonorificSuffix
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: IdentityStoreId
  type: string
- container: ''
  name: InlinePolicy
  type: string
- container: ''
  name: InstanceArn
  type: string
- container: ''
  name: Instances
  type: string
- container: ''
  name: Issuer
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Locale
  type: string
- container: ''
  name: Locality
  type: string
- container: ''
  name: ManagedPolicyArn
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: MembershipExists
  type: string
- container: ''
  name: MembershipId
  type: string
- container: ''
  name: MiddleName
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: NickName
  type: string
- container: ''
  name: Operations
  type: string
- container: ''
  name: Path
  type: string
- container: ''
  name: PermissionSetArn
  type: string
- container: ''
  name: PermissionSets
  type: string
- container: ''
  name: PermissionSetsProvisioningStatus
  type: string
- container: ''
  name: PhoneNumbers
  type: string
- container: ''
  name: PostalCode
  type: string
- container: ''
  name: PreferredLanguage
  type: string
- container: ''
  name: Primary
  type: string
- container: ''
  name: PrincipalId
  type: string
- container: ''
  name: PrincipalType
  type: string
- container: ''
  name: ProfileUrl
  type: string
- container: ''
  name: ProvisionPermissionSetRequestId
  type: string
- container: ''
  name: ProvisioningStatus
  type: string
- container: ''
  name: Region
  type: string
- container: ''
  name: RelayState
  type: string
- container: ''
  name: RequestId
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: Results
  type: string
- container: ''
  name: SessionDuration
  type: string
- container: ''
  name: Source
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: StatusReason
  type: string
- container: ''
  name: StreetAddress
  type: string
- container: ''
  name: TagKeys
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: TargetId
  type: string
- container: ''
  name: TargetType
  type: string
- container: ''
  name: Timezone
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: UserId
  type: string
- container: ''
  name: UserName
  type: string
- container: ''
  name: UserType
  type: string
- container: ''
  name: Users
  type: string
- container: ''
  name: Value
  type: string
property_count: 96
provider_name: Amazon IAM Identity Center
provider_slug: amazon-iam-identity-center
slug: amazon-iam-identity-center-context
source_filename: amazon-iam-identity-center-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessControlAttribute\": \"amzn:AccessControlAttribute\",\n    \"AccessControlAttributeValue\": \"amzn:AccessControlAttributeValue\",\n    \"AccountAssignment\": \"amzn:AccountAssignment\",\n    \"AccountAssignmentOperationStatus\": \"amzn:AccountAssignmentOperationStatus\",\n    \"AccountAssignmentOperationStatusMetadata\": \"amzn:AccountAssignmentOperationStatusMetadata\",\n    \"Address\": \"amzn:Address\",\n    \"AlternateIdentifier\": {\n      \"@id\": \"amzn:AlternateIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttachCustomerManagedPolicyReferenceToPermissionSetRequest\": \"amzn:AttachCustomerManagedPolicyReferenceToPermissionSetRequest\",\n    \"AttachCustomerManagedPolicyReferenceToPermissionSetResponse\":\
  \ \"amzn:AttachCustomerManagedPolicyReferenceToPermissionSetResponse\",\n    \"AttachManagedPolicyToPermissionSetRequest\": \"amzn:AttachManagedPolicyToPermissionSetRequest\",\n    \"AttachManagedPolicyToPermissionSetResponse\": \"amzn:AttachManagedPolicyToPermissionSetResponse\",\n    \"AttachedManagedPolicy\": \"amzn:AttachedManagedPolicy\",\n    \"AttributeOperation\": \"amzn:AttributeOperation\",\n    \"AttributeValue\": {\n      \"@id\": \"amzn:AttributeValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateAccountAssignmentRequest\": \"amzn:CreateAccountAssignmentRequest\",\n    \"CreateAccountAssignmentResponse\": \"amzn:CreateAccountAssignmentResponse\",\n    \"CreateGroupMembershipRequest\": \"amzn:CreateGroupMembershipRequest\",\n    \"CreateGroupMembershipResponse\": \"amzn:CreateGroupMembershipResponse\",\n    \"CreateGroupRequest\": \"amzn:CreateGroupRequest\",\n    \"CreateGroupResponse\": \"amzn:CreateGroupResponse\",\n    \"CreateInstanceAccessControlAttributeConfigurationRequest\"\
  : \"amzn:CreateInstanceAccessControlAttributeConfigurationRequest\",\n    \"CreateInstanceAccessControlAttributeConfigurationResponse\": \"amzn:CreateInstanceAccessControlAttributeConfigurationResponse\",\n    \"CreatePermissionSetRequest\": \"amzn:CreatePermissionSetRequest\",\n    \"CreatePermissionSetResponse\": \"amzn:CreatePermissionSetResponse\",\n    \"CreateUserRequest\": \"amzn:CreateUserRequest\",\n    \"CreateUserResponse\": \"amzn:CreateUserResponse\",\n    \"CustomerManagedPolicyReference\": {\n      \"@id\": \"amzn:CustomerManagedPolicyReference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteAccountAssignmentRequest\": \"amzn:DeleteAccountAssignmentRequest\",\n    \"DeleteAccountAssignmentResponse\": \"amzn:DeleteAccountAssignmentResponse\",\n    \"DeleteGroupMembershipRequest\": \"amzn:DeleteGroupMembershipRequest\",\n    \"DeleteGroupMembershipResponse\": \"amzn:DeleteGroupMembershipResponse\",\n    \"DeleteGroupRequest\": \"amzn:DeleteGroupRequest\",\n    \"\
  DeleteGroupResponse\": \"amzn:DeleteGroupResponse\",\n    \"DeleteInlinePolicyFromPermissionSetRequest\": \"amzn:DeleteInlinePolicyFromPermissionSetRequest\",\n    \"DeleteInlinePolicyFromPermissionSetResponse\": \"amzn:DeleteInlinePolicyFromPermissionSetResponse\",\n    \"DeleteInstanceAccessControlAttributeConfigurationRequest\": \"amzn:DeleteInstanceAccessControlAttributeConfigurationRequest\",\n    \"DeleteInstanceAccessControlAttributeConfigurationResponse\": \"amzn:DeleteInstanceAccessControlAttributeConfigurationResponse\",\n    \"DeletePermissionSetRequest\": \"amzn:DeletePermissionSetRequest\",\n    \"DeletePermissionSetResponse\": \"amzn:DeletePermissionSetResponse\",\n    \"DeletePermissionsBoundaryFromPermissionSetRequest\": \"amzn:DeletePermissionsBoundaryFromPermissionSetRequest\",\n    \"DeletePermissionsBoundaryFromPermissionSetResponse\": \"amzn:DeletePermissionsBoundaryFromPermissionSetResponse\",\n    \"DeleteUserRequest\": \"amzn:DeleteUserRequest\",\n    \"DeleteUserResponse\"\
  : \"amzn:DeleteUserResponse\",\n    \"DescribeAccountAssignmentCreationStatusRequest\": \"amzn:DescribeAccountAssignmentCreationStatusRequest\",\n    \"DescribeAccountAssignmentCreationStatusResponse\": \"amzn:DescribeAccountAssignmentCreationStatusResponse\",\n    \"DescribeAccountAssignmentDeletionStatusRequest\": \"amzn:DescribeAccountAssignmentDeletionStatusRequest\",\n    \"DescribeAccountAssignmentDeletionStatusResponse\": \"amzn:DescribeAccountAssignmentDeletionStatusResponse\",\n    \"DescribeGroupMembershipRequest\": \"amzn:DescribeGroupMembershipRequest\",\n    \"DescribeGroupMembershipResponse\": \"amzn:DescribeGroupMembershipResponse\",\n    \"DescribeGroupRequest\": \"amzn:DescribeGroupRequest\",\n    \"DescribeGroupResponse\": \"amzn:DescribeGroupResponse\",\n    \"DescribeInstanceAccessControlAttributeConfigurationRequest\": \"amzn:DescribeInstanceAccessControlAttributeConfigurationRequest\",\n    \"DescribeInstanceAccessControlAttributeConfigurationResponse\": \"amzn:DescribeInstanceAccessControlAttributeConfigurationResponse\"\
  ,\n    \"DescribePermissionSetProvisioningStatusRequest\": \"amzn:DescribePermissionSetProvisioningStatusRequest\",\n    \"DescribePermissionSetProvisioningStatusResponse\": \"amzn:DescribePermissionSetProvisioningStatusResponse\",\n    \"DescribePermissionSetRequest\": \"amzn:DescribePermissionSetRequest\",\n    \"DescribePermissionSetResponse\": \"amzn:DescribePermissionSetResponse\",\n    \"DescribeUserRequest\": \"amzn:DescribeUserRequest\",\n    \"DescribeUserResponse\": \"amzn:DescribeUserResponse\",\n    \"DetachCustomerManagedPolicyReferenceFromPermissionSetRequest\": \"amzn:DetachCustomerManagedPolicyReferenceFromPermissionSetRequest\",\n    \"DetachCustomerManagedPolicyReferenceFromPermissionSetResponse\": \"amzn:DetachCustomerManagedPolicyReferenceFromPermissionSetResponse\",\n    \"DetachManagedPolicyFromPermissionSetRequest\": \"amzn:DetachManagedPolicyFromPermissionSetRequest\",\n    \"DetachManagedPolicyFromPermissionSetResponse\": \"amzn:DetachManagedPolicyFromPermissionSetResponse\"\
  ,\n    \"Email\": \"amzn:Email\",\n    \"ExternalId\": {\n      \"@id\": \"amzn:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Filter\": {\n      \"@id\": \"amzn:Filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetGroupIdRequest\": \"amzn:GetGroupIdRequest\",\n    \"GetGroupIdResponse\": \"amzn:GetGroupIdResponse\",\n    \"GetGroupMembershipIdRequest\": \"amzn:GetGroupMembershipIdRequest\",\n    \"GetGroupMembershipIdResponse\": \"amzn:GetGroupMembershipIdResponse\",\n    \"GetInlinePolicyForPermissionSetRequest\": \"amzn:GetInlinePolicyForPermissionSetRequest\",\n    \"GetInlinePolicyForPermissionSetResponse\": \"amzn:GetInlinePolicyForPermissionSetResponse\",\n    \"GetPermissionsBoundaryForPermissionSetRequest\": \"amzn:GetPermissionsBoundaryForPermissionSetRequest\",\n    \"GetPermissionsBoundaryForPermissionSetResponse\": \"amzn:GetPermissionsBoundaryForPermissionSetResponse\",\n    \"GetUserIdRequest\": \"amzn:GetUserIdRequest\",\n    \"GetUserIdResponse\"\
  : \"amzn:GetUserIdResponse\",\n    \"Group\": \"amzn:Group\",\n    \"GroupMembership\": \"amzn:GroupMembership\",\n    \"GroupMembershipExistenceResult\": \"amzn:GroupMembershipExistenceResult\",\n    \"InstanceAccessControlAttributeConfiguration\": {\n      \"@id\": \"amzn:InstanceAccessControlAttributeConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceMetadata\": \"amzn:InstanceMetadata\",\n    \"IsMemberInGroupsRequest\": \"amzn:IsMemberInGroupsRequest\",\n    \"IsMemberInGroupsResponse\": \"amzn:IsMemberInGroupsResponse\",\n    \"ListAccountAssignmentCreationStatusRequest\": \"amzn:ListAccountAssignmentCreationStatusRequest\",\n    \"ListAccountAssignmentCreationStatusResponse\": \"amzn:ListAccountAssignmentCreationStatusResponse\",\n    \"ListAccountAssignmentDeletionStatusRequest\": \"amzn:ListAccountAssignmentDeletionStatusRequest\",\n    \"ListAccountAssignmentDeletionStatusResponse\": \"amzn:ListAccountAssignmentDeletionStatusResponse\",\n    \"ListAccountAssignmentsRequest\"\
  : \"amzn:ListAccountAssignmentsRequest\",\n    \"ListAccountAssignmentsResponse\": \"amzn:ListAccountAssignmentsResponse\",\n    \"ListAccountsForProvisionedPermissionSetRequest\": \"amzn:ListAccountsForProvisionedPermissionSetRequest\",\n    \"ListAccountsForProvisionedPermissionSetResponse\": \"amzn:ListAccountsForProvisionedPermissionSetResponse\",\n    \"ListCustomerManagedPolicyReferencesInPermissionSetRequest\": \"amzn:ListCustomerManagedPolicyReferencesInPermissionSetRequest\",\n    \"ListCustomerManagedPolicyReferencesInPermissionSetResponse\": \"amzn:ListCustomerManagedPolicyReferencesInPermissionSetResponse\",\n    \"ListGroupMembershipsForMemberRequest\": \"amzn:ListGroupMembershipsForMemberRequest\",\n    \"ListGroupMembershipsForMemberResponse\": \"amzn:ListGroupMembershipsForMemberResponse\",\n    \"ListGroupMembershipsRequest\": \"amzn:ListGroupMembershipsRequest\",\n    \"ListGroupMembershipsResponse\": \"amzn:ListGroupMembershipsResponse\",\n    \"ListGroupsRequest\":\
  \ \"amzn:ListGroupsRequest\",\n    \"ListGroupsResponse\": \"amzn:ListGroupsResponse\",\n    \"ListInstancesRequest\": \"amzn:ListInstancesRequest\",\n    \"ListInstancesResponse\": \"amzn:ListInstancesResponse\",\n    \"ListManagedPoliciesInPermissionSetRequest\": \"amzn:ListManagedPoliciesInPermissionSetRequest\",\n    \"ListManagedPoliciesInPermissionSetResponse\": \"amzn:ListManagedPoliciesInPermissionSetResponse\",\n    \"ListPermissionSetProvisioningStatusRequest\": \"amzn:ListPermissionSetProvisioningStatusRequest\",\n    \"ListPermissionSetProvisioningStatusResponse\": \"amzn:ListPermissionSetProvisioningStatusResponse\",\n    \"ListPermissionSetsProvisionedToAccountRequest\": \"amzn:ListPermissionSetsProvisionedToAccountRequest\",\n    \"ListPermissionSetsProvisionedToAccountResponse\": \"amzn:ListPermissionSetsProvisionedToAccountResponse\",\n    \"ListPermissionSetsRequest\": \"amzn:ListPermissionSetsRequest\",\n    \"ListPermissionSetsResponse\": \"amzn:ListPermissionSetsResponse\"\
  ,\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"ListUsersRequest\": \"amzn:ListUsersRequest\",\n    \"ListUsersResponse\": \"amzn:ListUsersResponse\",\n    \"MemberId\": {\n      \"@id\": \"amzn:MemberId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"amzn:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OperationStatusFilter\": \"amzn:OperationStatusFilter\",\n    \"PermissionSet\": {\n      \"@id\": \"amzn:PermissionSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionSetProvisioningStatus\": {\n      \"@id\": \"amzn:PermissionSetProvisioningStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionSetProvisioningStatusMetadata\": \"amzn:PermissionSetProvisioningStatusMetadata\",\n    \"PermissionsBoundary\": {\n      \"@id\": \"amzn:PermissionsBoundary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneNumber\"\
  : \"amzn:PhoneNumber\",\n    \"ProvisionPermissionSetRequest\": \"amzn:ProvisionPermissionSetRequest\",\n    \"ProvisionPermissionSetResponse\": \"amzn:ProvisionPermissionSetResponse\",\n    \"PutInlinePolicyToPermissionSetRequest\": \"amzn:PutInlinePolicyToPermissionSetRequest\",\n    \"PutInlinePolicyToPermissionSetResponse\": \"amzn:PutInlinePolicyToPermissionSetResponse\",\n    \"PutPermissionsBoundaryToPermissionSetRequest\": \"amzn:PutPermissionsBoundaryToPermissionSetRequest\",\n    \"PutPermissionsBoundaryToPermissionSetResponse\": \"amzn:PutPermissionsBoundaryToPermissionSetResponse\",\n    \"Tag\": \"amzn:Tag\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"TagResourceResponse\": \"amzn:TagResourceResponse\",\n    \"UniqueAttribute\": {\n      \"@id\": \"amzn:UniqueAttribute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceRequest\": \"amzn:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amzn:UntagResourceResponse\",\n    \"UpdateGroupRequest\"\
  : \"amzn:UpdateGroupRequest\",\n    \"UpdateGroupResponse\": \"amzn:UpdateGroupResponse\",\n    \"UpdateInstanceAccessControlAttributeConfigurationRequest\": \"amzn:UpdateInstanceAccessControlAttributeConfigurationRequest\",\n    \"UpdateInstanceAccessControlAttributeConfigurationResponse\": \"amzn:UpdateInstanceAccessControlAttributeConfigurationResponse\",\n    \"UpdatePermissionSetRequest\": \"amzn:UpdatePermissionSetRequest\",\n    \"UpdatePermissionSetResponse\": \"amzn:UpdatePermissionSetResponse\",\n    \"UpdateUserRequest\": \"amzn:UpdateUserRequest\",\n    \"UpdateUserResponse\": \"amzn:UpdateUserResponse\",\n    \"User\": \"amzn:User\",\n    \"AccessControlAttributes\": {\n      \"@id\": \"amzn:AccessControlAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentCreationRequestId\": {\n      \"@id\": \"amzn:AccountAssignmentCreationRequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentCreationStatus\": {\n      \"@id\": \"amzn:AccountAssignmentCreationStatus\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentDeletionRequestId\": {\n      \"@id\": \"amzn:AccountAssignmentDeletionRequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentDeletionStatus\": {\n      \"@id\": \"amzn:AccountAssignmentDeletionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignments\": {\n      \"@id\": \"amzn:AccountAssignments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentsCreationStatus\": {\n      \"@id\": \"amzn:AccountAssignmentsCreationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountAssignmentsDeletionStatus\": {\n      \"@id\": \"amzn:AccountAssignmentsDeletionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"amzn:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountIds\": {\n      \"@id\": \"amzn:AccountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Addresses\": {\n      \"@id\": \"amzn:Addresses\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"amzn:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttachedManagedPolicies\": {\n      \"@id\": \"amzn:AttachedManagedPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AttributePath\": {\n      \"@id\": \"amzn:AttributePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Country\": {\n      \"@id\": \"amzn:Country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDate\": {\n      \"@id\": \"amzn:CreatedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerManagedPolicyReferences\": {\n      \"@id\": \"amzn:CustomerManagedPolicyReferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"amzn:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayName\": {\n      \"@id\": \"amzn:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Emails\": {\n      \"@id\": \"amzn:Emails\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"ExternalIds\": {\n      \"@id\": \"amzn:ExternalIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailureReason\": {\n      \"@id\": \"amzn:FailureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FamilyName\": {\n      \"@id\": \"amzn:FamilyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Filters\": {\n      \"@id\": \"amzn:Filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Formatted\": {\n      \"@id\": \"amzn:Formatted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GivenName\": {\n      \"@id\": \"amzn:GivenName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupId\": {\n      \"@id\": \"amzn:GroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupIds\": {\n      \"@id\": \"amzn:GroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GroupMemberships\": {\n      \"@id\": \"amzn:GroupMemberships\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Groups\": {\n      \"@id\": \"amzn:Groups\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"HonorificPrefix\": {\n      \"@id\": \"amzn:HonorificPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HonorificSuffix\": {\n      \"@id\": \"amzn:HonorificSuffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"amzn:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IdentityStoreId\": {\n      \"@id\": \"amzn:IdentityStoreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InlinePolicy\": {\n      \"@id\": \"amzn:InlinePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceArn\": {\n      \"@id\": \"amzn:InstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Instances\": {\n      \"@id\": \"amzn:Instances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Issuer\": {\n      \"@id\": \"amzn:Issuer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"amzn:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Locale\": {\n      \"@id\": \"amzn:Locale\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"Locality\": {\n      \"@id\": \"amzn:Locality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManagedPolicyArn\": {\n      \"@id\": \"amzn:ManagedPolicyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"amzn:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MembershipExists\": {\n      \"@id\": \"amzn:MembershipExists\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MembershipId\": {\n      \"@id\": \"amzn:MembershipId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MiddleName\": {\n      \"@id\": \"amzn:MiddleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amzn:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NickName\": {\n      \"@id\": \"amzn:NickName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Operations\": {\n      \"@id\": \"amzn:Operations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Path\": {\n      \"@id\": \"amzn:Path\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"PermissionSetArn\": {\n      \"@id\": \"amzn:PermissionSetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionSets\": {\n      \"@id\": \"amzn:PermissionSets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionSetsProvisioningStatus\": {\n      \"@id\": \"amzn:PermissionSetsProvisioningStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PhoneNumbers\": {\n      \"@id\": \"amzn:PhoneNumbers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PostalCode\": {\n      \"@id\": \"amzn:PostalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PreferredLanguage\": {\n      \"@id\": \"amzn:PreferredLanguage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Primary\": {\n      \"@id\": \"amzn:Primary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrincipalId\": {\n      \"@id\": \"amzn:PrincipalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrincipalType\": {\n      \"@id\": \"amzn:PrincipalType\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"ProfileUrl\": {\n      \"@id\": \"amzn:ProfileUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisionPermissionSetRequestId\": {\n      \"@id\": \"amzn:ProvisionPermissionSetRequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProvisioningStatus\": {\n      \"@id\": \"amzn:ProvisioningStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Region\": {\n      \"@id\": \"amzn:Region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RelayState\": {\n      \"@id\": \"amzn:RelayState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestId\": {\n      \"@id\": \"amzn:RequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"amzn:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Results\": {\n      \"@id\": \"amzn:Results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SessionDuration\": {\n      \"@id\": \"amzn:SessionDuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"\
  amzn:Source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amzn:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusReason\": {\n      \"@id\": \"amzn:StatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StreetAddress\": {\n      \"@id\": \"amzn:StreetAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagKeys\": {\n      \"@id\": \"amzn:TagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"amzn:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetId\": {\n      \"@id\": \"amzn:TargetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetType\": {\n      \"@id\": \"amzn:TargetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timezone\": {\n      \"@id\": \"amzn:Timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"amzn:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"amzn:Type\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"UserId\": {\n      \"@id\": \"amzn:UserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserName\": {\n      \"@id\": \"amzn:UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserType\": {\n      \"@id\": \"amzn:UserType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Users\": {\n      \"@id\": \"amzn:Users\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"amzn:Value\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-identity-center/refs/heads/main/json-ld/amazon-iam-identity-center-context.jsonld
tags:
- Access Control
- Authentication
- Identity Management
- Single Sign-On
- JSON-LD
- Linked Data
- Semantic Web
---
