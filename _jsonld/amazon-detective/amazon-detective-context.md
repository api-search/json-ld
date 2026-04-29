---
class_count: 53
classes:
- AcceptInvitationRequest
- Account
- Administrator
- BatchGetGraphMemberDatasourcesRequest
- BatchGetGraphMemberDatasourcesResponse
- BatchGetMembershipDatasourcesRequest
- BatchGetMembershipDatasourcesResponse
- CreateGraphRequest
- CreateGraphResponse
- CreateMembersRequest
- CreateMembersResponse
- DatasourcePackageIngestDetail
- DeleteGraphRequest
- DeleteMembersRequest
- DeleteMembersResponse
- DescribeOrganizationConfigurationRequest
- DescribeOrganizationConfigurationResponse
- DisassociateMembershipRequest
- EnableOrganizationAdminAccountRequest
- GetInvestigationRequest
- GetInvestigationResponse
- GetMembersRequest
- GetMembersResponse
- Graph
- Indicator
- InvestigationDetail
- ListDatasourcePackagesRequest
- ListDatasourcePackagesResponse
- ListGraphsRequest
- ListGraphsResponse
- ListIndicatorsRequest
- ListIndicatorsResponse
- ListInvestigationsRequest
- ListInvestigationsResponse
- ListInvitationsRequest
- ListInvitationsResponse
- ListMembersRequest
- ListMembersResponse
- ListOrganizationAdminAccountsRequest
- ListOrganizationAdminAccountsResponse
- ListTagsForResourceResponse
- MemberDetail
- RejectInvitationRequest
- StartInvestigationRequest
- StartInvestigationResponse
- StartMonitoringMemberRequest
- TagResourceRequest
- TimestampForCollection
- UnprocessedAccount
- UnprocessedGraph
- UpdateDatasourcePackagesRequest
- UpdateInvestigationStateRequest
- UpdateOrganizationConfigurationRequest
context_file: json-ld/amazon-detective-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-detective/refs/heads/main/json-ld/amazon-detective-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Detective from Amazon Detective.
layout: jsonld
name: Amazon Detective Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/detective/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: MembershipDatasources
  type: string
- container: ''
  name: AccountId
  type: string
- container: set
  name: AccountIds
  type: string
- container: set
  name: Accounts
  type: string
- container: ''
  name: AdministratorId
  type: string
- container: set
  name: Administrators
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: AutoEnable
  type: boolean
- container: ''
  name: CreatedTime
  type: dateTime
- container: ''
  name: DatasourcePackageIngestHistory
  type: reference
- container: ''
  name: DatasourcePackageIngestState
  type: string
- container: ''
  name: DatasourcePackages
  type: reference
- container: ''
  name: DelegationTime
  type: dateTime
- container: ''
  name: DisableEmailNotification
  type: boolean
- container: ''
  name: DisabledReason
  type: string
- container: ''
  name: EmailAddress
  type: string
- container: ''
  name: EntityArn
  type: string
- container: ''
  name: EntityType
  type: string
- container: ''
  name: Field
  type: string
- container: ''
  name: FilterCriteria
  type: reference
- container: ''
  name: GraphArn
  type: string
- container: set
  name: GraphArns
  type: string
- container: set
  name: GraphList
  type: string
- container: ''
  name: IndicatorDetail
  type: reference
- container: ''
  name: IndicatorType
  type: string
- container: set
  name: Indicators
  type: string
- container: set
  name: InvestigationDetails
  type: string
- container: ''
  name: InvestigationId
  type: string
- container: ''
  name: InvitationType
  type: string
- container: set
  name: Invitations
  type: string
- container: ''
  name: InvitedTime
  type: dateTime
- container: ''
  name: LastIngestStateChange
  type: reference
- container: ''
  name: MaxResults
  type: integer
- container: set
  name: MemberDatasources
  type: string
- container: set
  name: MemberDetails
  type: string
- container: set
  name: Members
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: PercentOfGraphUtilization
  type: decimal
- container: ''
  name: Reason
  type: string
- container: ''
  name: ScopeEndTime
  type: dateTime
- container: ''
  name: ScopeStartTime
  type: dateTime
- container: ''
  name: Severity
  type: string
- container: ''
  name: SortCriteria
  type: reference
- container: ''
  name: SortOrder
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: Tags
  type: reference
- container: ''
  name: Timestamp
  type: dateTime
- container: set
  name: UnprocessedAccounts
  type: string
- container: set
  name: UnprocessedGraphs
  type: string
- container: ''
  name: UpdatedTime
  type: dateTime
- container: ''
  name: Value
  type: string
- container: ''
  name: VolumeUsageInBytes
  type: integer
- container: ''
  name: VolumeUsageUpdatedTime
  type: dateTime
property_count: 55
provider_name: Amazon Detective
provider_slug: amazon-detective
slug: amazon-detective-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/detective/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcceptInvitationRequest\": \"amz:AcceptInvitationRequest\",\n    \"Account\": \"amz:Account\",\n    \"Administrator\": \"amz:Administrator\",\n    \"BatchGetGraphMemberDatasourcesRequest\": \"amz:BatchGetGraphMemberDatasourcesRequest\",\n    \"BatchGetGraphMemberDatasourcesResponse\": \"amz:BatchGetGraphMemberDatasourcesResponse\",\n    \"BatchGetMembershipDatasourcesRequest\": \"amz:BatchGetMembershipDatasourcesRequest\",\n    \"BatchGetMembershipDatasourcesResponse\": \"amz:BatchGetMembershipDatasourcesResponse\",\n    \"CreateGraphRequest\": \"amz:CreateGraphRequest\",\n    \"CreateGraphResponse\": \"amz:CreateGraphResponse\",\n    \"CreateMembersRequest\": \"amz:CreateMembersRequest\",\n    \"CreateMembersResponse\": \"\
  amz:CreateMembersResponse\",\n    \"DatasourcePackageIngestDetail\": \"amz:DatasourcePackageIngestDetail\",\n    \"DeleteGraphRequest\": \"amz:DeleteGraphRequest\",\n    \"DeleteMembersRequest\": \"amz:DeleteMembersRequest\",\n    \"DeleteMembersResponse\": \"amz:DeleteMembersResponse\",\n    \"DescribeOrganizationConfigurationRequest\": \"amz:DescribeOrganizationConfigurationRequest\",\n    \"DescribeOrganizationConfigurationResponse\": \"amz:DescribeOrganizationConfigurationResponse\",\n    \"DisassociateMembershipRequest\": \"amz:DisassociateMembershipRequest\",\n    \"EnableOrganizationAdminAccountRequest\": \"amz:EnableOrganizationAdminAccountRequest\",\n    \"GetInvestigationRequest\": \"amz:GetInvestigationRequest\",\n    \"GetInvestigationResponse\": \"amz:GetInvestigationResponse\",\n    \"GetMembersRequest\": \"amz:GetMembersRequest\",\n    \"GetMembersResponse\": \"amz:GetMembersResponse\",\n    \"Graph\": \"amz:Graph\",\n    \"Indicator\": \"amz:Indicator\",\n    \"InvestigationDetail\"\
  : \"amz:InvestigationDetail\",\n    \"ListDatasourcePackagesRequest\": \"amz:ListDatasourcePackagesRequest\",\n    \"ListDatasourcePackagesResponse\": \"amz:ListDatasourcePackagesResponse\",\n    \"ListGraphsRequest\": \"amz:ListGraphsRequest\",\n    \"ListGraphsResponse\": \"amz:ListGraphsResponse\",\n    \"ListIndicatorsRequest\": \"amz:ListIndicatorsRequest\",\n    \"ListIndicatorsResponse\": \"amz:ListIndicatorsResponse\",\n    \"ListInvestigationsRequest\": \"amz:ListInvestigationsRequest\",\n    \"ListInvestigationsResponse\": \"amz:ListInvestigationsResponse\",\n    \"ListInvitationsRequest\": \"amz:ListInvitationsRequest\",\n    \"ListInvitationsResponse\": \"amz:ListInvitationsResponse\",\n    \"ListMembersRequest\": \"amz:ListMembersRequest\",\n    \"ListMembersResponse\": \"amz:ListMembersResponse\",\n    \"ListOrganizationAdminAccountsRequest\": \"amz:ListOrganizationAdminAccountsRequest\",\n    \"ListOrganizationAdminAccountsResponse\": \"amz:ListOrganizationAdminAccountsResponse\"\
  ,\n    \"ListTagsForResourceResponse\": \"amz:ListTagsForResourceResponse\",\n    \"MemberDetail\": \"amz:MemberDetail\",\n    \"MembershipDatasources\": {\n      \"@id\": \"amz:MembershipDatasources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RejectInvitationRequest\": \"amz:RejectInvitationRequest\",\n    \"StartInvestigationRequest\": \"amz:StartInvestigationRequest\",\n    \"StartInvestigationResponse\": \"amz:StartInvestigationResponse\",\n    \"StartMonitoringMemberRequest\": \"amz:StartMonitoringMemberRequest\",\n    \"TagResourceRequest\": \"amz:TagResourceRequest\",\n    \"TimestampForCollection\": \"amz:TimestampForCollection\",\n    \"UnprocessedAccount\": \"amz:UnprocessedAccount\",\n    \"UnprocessedGraph\": \"amz:UnprocessedGraph\",\n    \"UpdateDatasourcePackagesRequest\": \"amz:UpdateDatasourcePackagesRequest\",\n    \"UpdateInvestigationStateRequest\": \"amz:UpdateInvestigationStateRequest\",\n    \"UpdateOrganizationConfigurationRequest\"\
  : \"amz:UpdateOrganizationConfigurationRequest\",\n    \"AccountId\": {\n      \"@id\": \"amz:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountIds\": {\n      \"@id\": \"amz:AccountIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Accounts\": {\n      \"@id\": \"amz:Accounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdministratorId\": {\n      \"@id\": \"amz:AdministratorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Administrators\": {\n      \"@id\": \"amz:Administrators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Arn\": {\n      \"@id\": \"amz:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoEnable\": {\n      \"@id\": \"amz:AutoEnable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CreatedTime\": {\n      \"@id\": \"amz:CreatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DatasourcePackageIngestHistory\": {\n   \
  \   \"@id\": \"amz:DatasourcePackageIngestHistory\",\n      \"@type\": \"@id\"\n    },\n    \"DatasourcePackageIngestState\": {\n      \"@id\": \"amz:DatasourcePackageIngestState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatasourcePackages\": {\n      \"@id\": \"amz:DatasourcePackages\",\n      \"@type\": \"@id\"\n    },\n    \"DelegationTime\": {\n      \"@id\": \"amz:DelegationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"DisableEmailNotification\": {\n      \"@id\": \"amz:DisableEmailNotification\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"DisabledReason\": {\n      \"@id\": \"amz:DisabledReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailAddress\": {\n      \"@id\": \"amz:EmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityArn\": {\n      \"@id\": \"amz:EntityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EntityType\": {\n      \"@id\": \"amz:EntityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Field\": {\n\
  \      \"@id\": \"amz:Field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterCriteria\": {\n      \"@id\": \"amz:FilterCriteria\",\n      \"@type\": \"@id\"\n    },\n    \"GraphArn\": {\n      \"@id\": \"amz:GraphArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GraphArns\": {\n      \"@id\": \"amz:GraphArns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GraphList\": {\n      \"@id\": \"amz:GraphList\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IndicatorDetail\": {\n      \"@id\": \"amz:IndicatorDetail\",\n      \"@type\": \"@id\"\n    },\n    \"IndicatorType\": {\n      \"@id\": \"amz:IndicatorType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Indicators\": {\n      \"@id\": \"amz:Indicators\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvestigationDetails\": {\n      \"@id\": \"amz:InvestigationDetails\",\n      \"@container\": \"@set\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"InvestigationId\": {\n      \"@id\": \"amz:InvestigationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvitationType\": {\n      \"@id\": \"amz:InvitationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Invitations\": {\n      \"@id\": \"amz:Invitations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InvitedTime\": {\n      \"@id\": \"amz:InvitedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"LastIngestStateChange\": {\n      \"@id\": \"amz:LastIngestStateChange\",\n      \"@type\": \"@id\"\n    },\n    \"MaxResults\": {\n      \"@id\": \"amz:MaxResults\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MemberDatasources\": {\n      \"@id\": \"amz:MemberDatasources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MemberDetails\": {\n      \"@id\": \"amz:MemberDetails\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Members\"\
  : {\n      \"@id\": \"amz:Members\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": {\n      \"@id\": \"amz:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amz:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PercentOfGraphUtilization\": {\n      \"@id\": \"amz:PercentOfGraphUtilization\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"Reason\": {\n      \"@id\": \"amz:Reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScopeEndTime\": {\n      \"@id\": \"amz:ScopeEndTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ScopeStartTime\": {\n      \"@id\": \"amz:ScopeStartTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Severity\": {\n      \"@id\": \"amz:Severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SortCriteria\": {\n      \"@id\": \"amz:SortCriteria\",\n      \"@type\": \"@id\"\n    },\n    \"SortOrder\": {\n      \"@id\": \"amz:SortOrder\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"amz:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amz:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"amz:Tags\",\n      \"@type\": \"@id\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"amz:Timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"UnprocessedAccounts\": {\n      \"@id\": \"amz:UnprocessedAccounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UnprocessedGraphs\": {\n      \"@id\": \"amz:UnprocessedGraphs\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedTime\": {\n      \"@id\": \"amz:UpdatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Value\": {\n      \"@id\": \"amz:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VolumeUsageInBytes\": {\n      \"@id\": \"amz:VolumeUsageInBytes\",\n      \"@type\": \"xsd:integer\"\n  \
  \  },\n    \"VolumeUsageUpdatedTime\": {\n      \"@id\": \"amz:VolumeUsageUpdatedTime\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-detective/refs/heads/main/json-ld/amazon-detective-context.jsonld
tags:
- AWS
- Forensics
- Investigation
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
