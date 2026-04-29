---
class_count: 93
classes:
- Accessor
- AccessorSummary
- ApprovalThresholdPolicy
- CreateAccessorInput
- CreateAccessorOutput
- CreateMemberInput
- CreateMemberOutput
- CreateNetworkInput
- CreateNetworkOutput
- CreateNodeInput
- CreateNodeOutput
- CreateProposalInput
- CreateProposalOutput
- DeleteAccessorInput
- DeleteAccessorOutput
- DeleteMemberInput
- DeleteMemberOutput
- DeleteNodeInput
- DeleteNodeOutput
- GetAccessorInput
- GetAccessorOutput
- GetMemberInput
- GetMemberOutput
- GetNetworkInput
- GetNetworkOutput
- GetNodeInput
- GetNodeOutput
- GetProposalInput
- GetProposalOutput
- InputTagMap
- Invitation
- InviteAction
- ListAccessorsInput
- ListAccessorsOutput
- ListInvitationsInput
- ListInvitationsOutput
- ListMembersInput
- ListMembersOutput
- ListNetworksInput
- ListNetworksOutput
- ListNodesInput
- ListNodesOutput
- ListProposalVotesInput
- ListProposalVotesOutput
- ListProposalsInput
- ListProposalsOutput
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- LogConfiguration
- LogConfigurations
- Member
- MemberConfiguration
- MemberFabricAttributes
- MemberFabricConfiguration
- MemberFabricLogPublishingConfiguration
- MemberFrameworkAttributes
- MemberFrameworkConfiguration
- MemberLogPublishingConfiguration
- MemberSummary
- Network
- NetworkEthereumAttributes
- NetworkFabricAttributes
- NetworkFabricConfiguration
- NetworkFrameworkAttributes
- NetworkFrameworkConfiguration
- NetworkSummary
- Node
- NodeConfiguration
- NodeEthereumAttributes
- NodeFabricAttributes
- NodeFabricLogPublishingConfiguration
- NodeFrameworkAttributes
- NodeLogPublishingConfiguration
- NodeSummary
- OutputTagMap
- Proposal
- ProposalActions
- ProposalSummary
- RejectInvitationInput
- RejectInvitationOutput
- RemoveAction
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateMemberInput
- UpdateMemberOutput
- UpdateNodeInput
- UpdateNodeOutput
- VoteOnProposalInput
- VoteOnProposalOutput
- VoteSummary
- VotingPolicy
context_file: json-ld/amazon-managed-blockchain-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/json-ld/amazon-managed-blockchain-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Managed Blockchain from Amazon Managed Blockchain.
layout: jsonld
name: Amazon Managed Blockchain Context
namespaces:
- prefix: ambc
  uri: https://ambc.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AccessorId
  type: ''
- container: ''
  name: AccessorType
  type: ''
- container: ''
  name: Accessors
  type: ''
- container: ''
  name: Actions
  type: ''
- container: ''
  name: AdminPassword
  type: ''
- container: ''
  name: AdminUsername
  type: ''
- container: ''
  name: Arn
  type: ''
- container: ''
  name: AvailabilityZone
  type: ''
- container: ''
  name: BillingToken
  type: ''
- container: ''
  name: CaEndpoint
  type: ''
- container: ''
  name: CaLogs
  type: ''
- container: ''
  name: ChainId
  type: ''
- container: ''
  name: ChaincodeLogs
  type: ''
- container: ''
  name: ClientRequestToken
  type: ''
- container: ''
  name: Cloudwatch
  type: ''
- container: ''
  name: CreationDate
  type: ''
- container: ''
  name: Description
  type: ''
- container: ''
  name: Edition
  type: ''
- container: ''
  name: Enabled
  type: ''
- container: ''
  name: Ethereum
  type: ''
- container: ''
  name: ExpirationDate
  type: ''
- container: ''
  name: Fabric
  type: ''
- container: ''
  name: Framework
  type: ''
- container: ''
  name: FrameworkAttributes
  type: ''
- container: ''
  name: FrameworkConfiguration
  type: ''
- container: ''
  name: FrameworkVersion
  type: ''
- container: ''
  name: HttpEndpoint
  type: ''
- container: ''
  name: Id
  type: ''
- container: ''
  name: InstanceType
  type: ''
- container: ''
  name: InvitationId
  type: ''
- container: ''
  name: Invitations
  type: ''
- container: ''
  name: IsOwned
  type: ''
- container: ''
  name: KmsKeyArn
  type: ''
- container: ''
  name: LogPublishingConfiguration
  type: ''
- container: ''
  name: MemberId
  type: ''
- container: ''
  name: MemberName
  type: ''
- container: ''
  name: Members
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: NetworkId
  type: ''
- container: ''
  name: Networks
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: NoVoteCount
  type: ''
- container: ''
  name: NodeId
  type: ''
- container: ''
  name: Nodes
  type: ''
- container: ''
  name: OrderingServiceEndpoint
  type: ''
- container: ''
  name: OutstandingVoteCount
  type: ''
- container: ''
  name: PeerEndpoint
  type: ''
- container: ''
  name: PeerEventEndpoint
  type: ''
- container: ''
  name: PeerLogs
  type: ''
- container: ''
  name: Principal
  type: ''
- container: ''
  name: ProposalDurationInHours
  type: ''
- container: ''
  name: ProposalId
  type: ''
- container: ''
  name: ProposalVotes
  type: ''
- container: ''
  name: Proposals
  type: ''
- container: ''
  name: ProposedByMemberId
  type: ''
- container: ''
  name: ProposedByMemberName
  type: ''
- container: ''
  name: Removals
  type: ''
- container: ''
  name: StateDB
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: Tags
  type: ''
- container: ''
  name: ThresholdComparator
  type: ''
- container: ''
  name: ThresholdPercentage
  type: ''
- container: ''
  name: Type
  type: ''
- container: ''
  name: Vote
  type: ''
- container: ''
  name: VoterMemberId
  type: ''
- container: ''
  name: VpcEndpointServiceName
  type: ''
- container: ''
  name: WebSocketEndpoint
  type: ''
- container: ''
  name: YesVoteCount
  type: ''
property_count: 68
provider_name: Amazon Managed Blockchain
provider_slug: amazon-managed-blockchain
slug: amazon-managed-blockchain-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ambc\": \"https://ambc.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Accessor\": \"ambc:Accessor\",\n    \"AccessorSummary\": \"ambc:AccessorSummary\",\n    \"ApprovalThresholdPolicy\": \"ambc:ApprovalThresholdPolicy\",\n    \"CreateAccessorInput\": \"ambc:CreateAccessorInput\",\n    \"CreateAccessorOutput\": \"ambc:CreateAccessorOutput\",\n    \"CreateMemberInput\": \"ambc:CreateMemberInput\",\n    \"CreateMemberOutput\": \"ambc:CreateMemberOutput\",\n    \"CreateNetworkInput\": \"ambc:CreateNetworkInput\",\n    \"CreateNetworkOutput\": \"ambc:CreateNetworkOutput\",\n    \"CreateNodeInput\": \"ambc:CreateNodeInput\",\n    \"CreateNodeOutput\": \"ambc:CreateNodeOutput\",\n    \"CreateProposalInput\": \"ambc:CreateProposalInput\",\n    \"CreateProposalOutput\": \"ambc:CreateProposalOutput\",\n    \"DeleteAccessorInput\": \"ambc:DeleteAccessorInput\"\
  ,\n    \"DeleteAccessorOutput\": \"ambc:DeleteAccessorOutput\",\n    \"DeleteMemberInput\": \"ambc:DeleteMemberInput\",\n    \"DeleteMemberOutput\": \"ambc:DeleteMemberOutput\",\n    \"DeleteNodeInput\": \"ambc:DeleteNodeInput\",\n    \"DeleteNodeOutput\": \"ambc:DeleteNodeOutput\",\n    \"GetAccessorInput\": \"ambc:GetAccessorInput\",\n    \"GetAccessorOutput\": \"ambc:GetAccessorOutput\",\n    \"GetMemberInput\": \"ambc:GetMemberInput\",\n    \"GetMemberOutput\": \"ambc:GetMemberOutput\",\n    \"GetNetworkInput\": \"ambc:GetNetworkInput\",\n    \"GetNetworkOutput\": \"ambc:GetNetworkOutput\",\n    \"GetNodeInput\": \"ambc:GetNodeInput\",\n    \"GetNodeOutput\": \"ambc:GetNodeOutput\",\n    \"GetProposalInput\": \"ambc:GetProposalInput\",\n    \"GetProposalOutput\": \"ambc:GetProposalOutput\",\n    \"InputTagMap\": \"ambc:InputTagMap\",\n    \"Invitation\": \"ambc:Invitation\",\n    \"InviteAction\": \"ambc:InviteAction\",\n    \"ListAccessorsInput\": \"ambc:ListAccessorsInput\",\n  \
  \  \"ListAccessorsOutput\": \"ambc:ListAccessorsOutput\",\n    \"ListInvitationsInput\": \"ambc:ListInvitationsInput\",\n    \"ListInvitationsOutput\": \"ambc:ListInvitationsOutput\",\n    \"ListMembersInput\": \"ambc:ListMembersInput\",\n    \"ListMembersOutput\": \"ambc:ListMembersOutput\",\n    \"ListNetworksInput\": \"ambc:ListNetworksInput\",\n    \"ListNetworksOutput\": \"ambc:ListNetworksOutput\",\n    \"ListNodesInput\": \"ambc:ListNodesInput\",\n    \"ListNodesOutput\": \"ambc:ListNodesOutput\",\n    \"ListProposalVotesInput\": \"ambc:ListProposalVotesInput\",\n    \"ListProposalVotesOutput\": \"ambc:ListProposalVotesOutput\",\n    \"ListProposalsInput\": \"ambc:ListProposalsInput\",\n    \"ListProposalsOutput\": \"ambc:ListProposalsOutput\",\n    \"ListTagsForResourceRequest\": \"ambc:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"ambc:ListTagsForResourceResponse\",\n    \"LogConfiguration\": \"ambc:LogConfiguration\",\n    \"LogConfigurations\": \"ambc:LogConfigurations\"\
  ,\n    \"Member\": \"ambc:Member\",\n    \"MemberConfiguration\": \"ambc:MemberConfiguration\",\n    \"MemberFabricAttributes\": \"ambc:MemberFabricAttributes\",\n    \"MemberFabricConfiguration\": \"ambc:MemberFabricConfiguration\",\n    \"MemberFabricLogPublishingConfiguration\": \"ambc:MemberFabricLogPublishingConfiguration\",\n    \"MemberFrameworkAttributes\": \"ambc:MemberFrameworkAttributes\",\n    \"MemberFrameworkConfiguration\": \"ambc:MemberFrameworkConfiguration\",\n    \"MemberLogPublishingConfiguration\": \"ambc:MemberLogPublishingConfiguration\",\n    \"MemberSummary\": \"ambc:MemberSummary\",\n    \"Network\": \"ambc:Network\",\n    \"NetworkEthereumAttributes\": \"ambc:NetworkEthereumAttributes\",\n    \"NetworkFabricAttributes\": \"ambc:NetworkFabricAttributes\",\n    \"NetworkFabricConfiguration\": \"ambc:NetworkFabricConfiguration\",\n    \"NetworkFrameworkAttributes\": \"ambc:NetworkFrameworkAttributes\",\n    \"NetworkFrameworkConfiguration\": \"ambc:NetworkFrameworkConfiguration\"\
  ,\n    \"NetworkSummary\": \"ambc:NetworkSummary\",\n    \"Node\": \"ambc:Node\",\n    \"NodeConfiguration\": \"ambc:NodeConfiguration\",\n    \"NodeEthereumAttributes\": \"ambc:NodeEthereumAttributes\",\n    \"NodeFabricAttributes\": \"ambc:NodeFabricAttributes\",\n    \"NodeFabricLogPublishingConfiguration\": \"ambc:NodeFabricLogPublishingConfiguration\",\n    \"NodeFrameworkAttributes\": \"ambc:NodeFrameworkAttributes\",\n    \"NodeLogPublishingConfiguration\": \"ambc:NodeLogPublishingConfiguration\",\n    \"NodeSummary\": \"ambc:NodeSummary\",\n    \"OutputTagMap\": \"ambc:OutputTagMap\",\n    \"Proposal\": \"ambc:Proposal\",\n    \"ProposalActions\": \"ambc:ProposalActions\",\n    \"ProposalSummary\": \"ambc:ProposalSummary\",\n    \"RejectInvitationInput\": \"ambc:RejectInvitationInput\",\n    \"RejectInvitationOutput\": \"ambc:RejectInvitationOutput\",\n    \"RemoveAction\": \"ambc:RemoveAction\",\n    \"TagResourceRequest\": \"ambc:TagResourceRequest\",\n    \"TagResourceResponse\"\
  : \"ambc:TagResourceResponse\",\n    \"UntagResourceRequest\": \"ambc:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"ambc:UntagResourceResponse\",\n    \"UpdateMemberInput\": \"ambc:UpdateMemberInput\",\n    \"UpdateMemberOutput\": \"ambc:UpdateMemberOutput\",\n    \"UpdateNodeInput\": \"ambc:UpdateNodeInput\",\n    \"UpdateNodeOutput\": \"ambc:UpdateNodeOutput\",\n    \"VoteOnProposalInput\": \"ambc:VoteOnProposalInput\",\n    \"VoteOnProposalOutput\": \"ambc:VoteOnProposalOutput\",\n    \"VoteSummary\": \"ambc:VoteSummary\",\n    \"VotingPolicy\": \"ambc:VotingPolicy\",\n    \"AccessorId\": {\n      \"@id\": \"ambc:AccessorId\"\n    },\n    \"AccessorType\": {\n      \"@id\": \"ambc:AccessorType\"\n    },\n    \"Accessors\": {\n      \"@id\": \"ambc:Accessors\"\n    },\n    \"Actions\": {\n      \"@id\": \"ambc:Actions\"\n    },\n    \"AdminPassword\": {\n      \"@id\": \"ambc:AdminPassword\"\n    },\n    \"AdminUsername\": {\n      \"@id\": \"ambc:AdminUsername\"\n    },\n\
  \    \"Arn\": {\n      \"@id\": \"ambc:Arn\"\n    },\n    \"AvailabilityZone\": {\n      \"@id\": \"ambc:AvailabilityZone\"\n    },\n    \"BillingToken\": {\n      \"@id\": \"ambc:BillingToken\"\n    },\n    \"CaEndpoint\": {\n      \"@id\": \"ambc:CaEndpoint\"\n    },\n    \"CaLogs\": {\n      \"@id\": \"ambc:CaLogs\"\n    },\n    \"ChainId\": {\n      \"@id\": \"ambc:ChainId\"\n    },\n    \"ChaincodeLogs\": {\n      \"@id\": \"ambc:ChaincodeLogs\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"ambc:ClientRequestToken\"\n    },\n    \"Cloudwatch\": {\n      \"@id\": \"ambc:Cloudwatch\"\n    },\n    \"CreationDate\": {\n      \"@id\": \"ambc:CreationDate\"\n    },\n    \"Description\": {\n      \"@id\": \"ambc:Description\"\n    },\n    \"Edition\": {\n      \"@id\": \"ambc:Edition\"\n    },\n    \"Enabled\": {\n      \"@id\": \"ambc:Enabled\"\n    },\n    \"Ethereum\": {\n      \"@id\": \"ambc:Ethereum\"\n    },\n    \"ExpirationDate\": {\n      \"@id\": \"ambc:ExpirationDate\"\
  \n    },\n    \"Fabric\": {\n      \"@id\": \"ambc:Fabric\"\n    },\n    \"Framework\": {\n      \"@id\": \"ambc:Framework\"\n    },\n    \"FrameworkAttributes\": {\n      \"@id\": \"ambc:FrameworkAttributes\"\n    },\n    \"FrameworkConfiguration\": {\n      \"@id\": \"ambc:FrameworkConfiguration\"\n    },\n    \"FrameworkVersion\": {\n      \"@id\": \"ambc:FrameworkVersion\"\n    },\n    \"HttpEndpoint\": {\n      \"@id\": \"ambc:HttpEndpoint\"\n    },\n    \"Id\": {\n      \"@id\": \"ambc:Id\"\n    },\n    \"InstanceType\": {\n      \"@id\": \"ambc:InstanceType\"\n    },\n    \"InvitationId\": {\n      \"@id\": \"ambc:InvitationId\"\n    },\n    \"Invitations\": {\n      \"@id\": \"ambc:Invitations\"\n    },\n    \"IsOwned\": {\n      \"@id\": \"ambc:IsOwned\"\n    },\n    \"KmsKeyArn\": {\n      \"@id\": \"ambc:KmsKeyArn\"\n    },\n    \"LogPublishingConfiguration\": {\n      \"@id\": \"ambc:LogPublishingConfiguration\"\n    },\n    \"MemberId\": {\n      \"@id\": \"ambc:MemberId\"\
  \n    },\n    \"MemberName\": {\n      \"@id\": \"ambc:MemberName\"\n    },\n    \"Members\": {\n      \"@id\": \"ambc:Members\"\n    },\n    \"Name\": {\n      \"@id\": \"ambc:Name\"\n    },\n    \"NetworkId\": {\n      \"@id\": \"ambc:NetworkId\"\n    },\n    \"Networks\": {\n      \"@id\": \"ambc:Networks\"\n    },\n    \"NextToken\": {\n      \"@id\": \"ambc:NextToken\"\n    },\n    \"NoVoteCount\": {\n      \"@id\": \"ambc:NoVoteCount\"\n    },\n    \"NodeId\": {\n      \"@id\": \"ambc:NodeId\"\n    },\n    \"Nodes\": {\n      \"@id\": \"ambc:Nodes\"\n    },\n    \"OrderingServiceEndpoint\": {\n      \"@id\": \"ambc:OrderingServiceEndpoint\"\n    },\n    \"OutstandingVoteCount\": {\n      \"@id\": \"ambc:OutstandingVoteCount\"\n    },\n    \"PeerEndpoint\": {\n      \"@id\": \"ambc:PeerEndpoint\"\n    },\n    \"PeerEventEndpoint\": {\n      \"@id\": \"ambc:PeerEventEndpoint\"\n    },\n    \"PeerLogs\": {\n      \"@id\": \"ambc:PeerLogs\"\n    },\n    \"Principal\": {\n      \"@id\"\
  : \"ambc:Principal\"\n    },\n    \"ProposalDurationInHours\": {\n      \"@id\": \"ambc:ProposalDurationInHours\"\n    },\n    \"ProposalId\": {\n      \"@id\": \"ambc:ProposalId\"\n    },\n    \"ProposalVotes\": {\n      \"@id\": \"ambc:ProposalVotes\"\n    },\n    \"Proposals\": {\n      \"@id\": \"ambc:Proposals\"\n    },\n    \"ProposedByMemberId\": {\n      \"@id\": \"ambc:ProposedByMemberId\"\n    },\n    \"ProposedByMemberName\": {\n      \"@id\": \"ambc:ProposedByMemberName\"\n    },\n    \"Removals\": {\n      \"@id\": \"ambc:Removals\"\n    },\n    \"StateDB\": {\n      \"@id\": \"ambc:StateDB\"\n    },\n    \"Status\": {\n      \"@id\": \"ambc:Status\"\n    },\n    \"Tags\": {\n      \"@id\": \"ambc:Tags\"\n    },\n    \"ThresholdComparator\": {\n      \"@id\": \"ambc:ThresholdComparator\"\n    },\n    \"ThresholdPercentage\": {\n      \"@id\": \"ambc:ThresholdPercentage\"\n    },\n    \"Type\": {\n      \"@id\": \"ambc:Type\"\n    },\n    \"Vote\": {\n      \"@id\": \"ambc:Vote\"\
  \n    },\n    \"VoterMemberId\": {\n      \"@id\": \"ambc:VoterMemberId\"\n    },\n    \"VpcEndpointServiceName\": {\n      \"@id\": \"ambc:VpcEndpointServiceName\"\n    },\n    \"WebSocketEndpoint\": {\n      \"@id\": \"ambc:WebSocketEndpoint\"\n    },\n    \"YesVoteCount\": {\n      \"@id\": \"ambc:YesVoteCount\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-managed-blockchain/refs/heads/main/json-ld/amazon-managed-blockchain-context.jsonld
tags:
- AWS
- Blockchain
- Distributed Ledger
- Hyperledger Fabric
- Ethereum
- JSON-LD
- Linked Data
- Semantic Web
---
