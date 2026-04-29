---
class_count: 26
classes:
- Certificate
- ClientCertAuthSettings
- Computer
- ConditionalForwarder
- DirectoryConfigurationStatus
- DirectoryConnectSettings
- DirectoryConnectSettingsDescription
- DirectoryDescription
- RadiusSettings
- OwnerDirectoryDescription
- DirectoryLimits
- DirectoryVpcSettings
- DirectoryVpcSettingsDescription
- EventTopic
- IpRoute
- IpRouteInfo
- LDAPSSettingInfo
- LogSubscription
- OSUpdateSettings
- RegionDescription
- SchemaExtensionInfo
- SharedDirectory
- Snapshot
- SnapshotLimits
- Tag
- Trust
context_file: json-ld/amazon-directory-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/json-ld/amazon-directory-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Directory Service from Amazon Directory Service.
layout: jsonld
name: Amazon Directory Service Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: ds
  uri: https://aws.amazon.com/directoryservice/vocab#
properties:
- container: ''
  name: CertificateId
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: StateReason
  type: string
- container: ''
  name: CommonName
  type: string
- container: ''
  name: RegisteredDateTime
  type: string
- container: ''
  name: ExpiryDateTime
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: OCSPUrl
  type: string
- container: ''
  name: ComputerId
  type: string
- container: ''
  name: ComputerName
  type: string
- container: ''
  name: ComputerAttributes
  type: string
- container: ''
  name: RemoteDomainName
  type: string
- container: ''
  name: DnsIpAddrs
  type: string
- container: ''
  name: ReplicationScope
  type: string
- container: ''
  name: VpcId
  type: string
- container: ''
  name: SubnetIds
  type: string
- container: ''
  name: CustomerDnsIps
  type: string
- container: ''
  name: CustomerUserName
  type: string
- container: ''
  name: SecurityGroupId
  type: string
- container: ''
  name: AvailabilityZones
  type: string
- container: ''
  name: ConnectIps
  type: string
- container: ''
  name: DirectoryId
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: ShortName
  type: string
- container: ''
  name: Size
  type: string
- container: ''
  name: Edition
  type: string
- container: ''
  name: Alias
  type: string
- container: ''
  name: AccessUrl
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Stage
  type: string
- container: ''
  name: ShareStatus
  type: string
- container: ''
  name: ShareMethod
  type: string
- container: ''
  name: ShareNotes
  type: string
- container: ''
  name: LaunchTime
  type: string
- container: ''
  name: StageLastUpdatedDateTime
  type: string
- container: ''
  name: VpcSettings
  type: string
- container: ''
  name: ConnectSettings
  type: string
- container: ''
  name: RadiusStatus
  type: string
- container: ''
  name: StageReason
  type: string
- container: ''
  name: SsoEnabled
  type: string
- container: ''
  name: DesiredNumberOfDomainControllers
  type: string
- container: ''
  name: RegionsInfo
  type: string
- container: ''
  name: OsVersion
  type: string
- container: ''
  name: CloudOnlyDirectoriesLimit
  type: string
- container: ''
  name: CloudOnlyDirectoriesCurrentCount
  type: string
- container: ''
  name: CloudOnlyDirectoriesLimitReached
  type: string
- container: ''
  name: CloudOnlyMicrosoftADLimit
  type: string
- container: ''
  name: CloudOnlyMicrosoftADCurrentCount
  type: string
- container: ''
  name: CloudOnlyMicrosoftADLimitReached
  type: string
- container: ''
  name: ConnectedDirectoriesLimit
  type: string
- container: ''
  name: ConnectedDirectoriesCurrentCount
  type: string
- container: ''
  name: ConnectedDirectoriesLimitReached
  type: string
- container: ''
  name: TopicName
  type: string
- container: ''
  name: TopicArn
  type: string
- container: ''
  name: CreatedDateTime
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: CidrIp
  type: string
- container: ''
  name: IpRouteStatusMsg
  type: string
- container: ''
  name: AddedDateTime
  type: string
- container: ''
  name: IpRouteStatusReason
  type: string
- container: ''
  name: LDAPSStatus
  type: string
- container: ''
  name: LDAPSStatusReason
  type: string
- container: ''
  name: LastUpdatedDateTime
  type: string
- container: ''
  name: LogGroupName
  type: string
- container: ''
  name: SubscriptionCreatedDateTime
  type: string
- container: ''
  name: OSVersion
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: RadiusServers
  type: string
- container: ''
  name: RadiusPort
  type: string
- container: ''
  name: RadiusTimeout
  type: string
- container: ''
  name: RadiusRetries
  type: string
- container: ''
  name: SharedSecret
  type: string
- container: ''
  name: AuthenticationProtocol
  type: string
- container: ''
  name: DisplayLabel
  type: string
- container: ''
  name: UseSameUsername
  type: string
- container: ''
  name: RegionName
  type: string
- container: ''
  name: RegionType
  type: string
- container: ''
  name: StatusLastUpdatedDateTime
  type: string
- container: ''
  name: SchemaExtensionId
  type: string
- container: ''
  name: SchemaExtensionStatus
  type: string
- container: ''
  name: SchemaExtensionStatusReason
  type: string
- container: ''
  name: StartDateTime
  type: string
- container: ''
  name: EndDateTime
  type: string
- container: ''
  name: OwnerAccountId
  type: string
- container: ''
  name: OwnerDirectoryId
  type: string
- container: ''
  name: SharedAccountId
  type: string
- container: ''
  name: SharedDirectoryId
  type: string
- container: ''
  name: SnapshotId
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: ManualSnapshotsLimit
  type: string
- container: ''
  name: ManualSnapshotsCurrentCount
  type: string
- container: ''
  name: ManualSnapshotsLimitReached
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: TrustId
  type: string
- container: ''
  name: TrustType
  type: string
- container: ''
  name: TrustDirection
  type: string
- container: ''
  name: TrustState
  type: string
- container: ''
  name: StateLastUpdatedDateTime
  type: string
- container: ''
  name: TrustStateReason
  type: string
- container: ''
  name: SelectiveAuth
  type: string
property_count: 101
provider_name: Amazon Directory Service
provider_slug: amazon-directory-service
slug: amazon-directory-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"ds\": \"https://aws.amazon.com/directoryservice/vocab#\",\n    \"Certificate\": \"ds:Certificate\",\n    \"CertificateId\": {\n      \"@id\": \"ds:CertificateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"ds:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StateReason\": {\n      \"@id\": \"ds:StateReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommonName\": {\n      \"@id\": \"ds:CommonName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisteredDateTime\": {\n      \"@id\": \"ds:RegisteredDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExpiryDateTime\": {\n      \"@id\": \"ds:ExpiryDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"ds:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientCertAuthSettings\": \"ds:ClientCertAuthSettings\"\
  ,\n    \"OCSPUrl\": {\n      \"@id\": \"ds:OCSPUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Computer\": \"ds:Computer\",\n    \"ComputerId\": {\n      \"@id\": \"ds:ComputerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ComputerName\": {\n      \"@id\": \"ds:ComputerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ComputerAttributes\": {\n      \"@id\": \"ds:ComputerAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConditionalForwarder\": \"ds:ConditionalForwarder\",\n    \"RemoteDomainName\": {\n      \"@id\": \"ds:RemoteDomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsIpAddrs\": {\n      \"@id\": \"ds:DnsIpAddrs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationScope\": {\n      \"@id\": \"ds:ReplicationScope\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryConfigurationStatus\": \"ds:DirectoryConfigurationStatus\",\n    \"DirectoryConnectSettings\": \"ds:DirectoryConnectSettings\",\n    \"VpcId\": {\n      \"\
  @id\": \"ds:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetIds\": {\n      \"@id\": \"ds:SubnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerDnsIps\": {\n      \"@id\": \"ds:CustomerDnsIps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustomerUserName\": {\n      \"@id\": \"ds:CustomerUserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryConnectSettingsDescription\": \"ds:DirectoryConnectSettingsDescription\",\n    \"SecurityGroupId\": {\n      \"@id\": \"ds:SecurityGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZones\": {\n      \"@id\": \"ds:AvailabilityZones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectIps\": {\n      \"@id\": \"ds:ConnectIps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryDescription\": \"ds:DirectoryDescription\",\n    \"DirectoryId\": {\n      \"@id\": \"ds:DirectoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"ds:Name\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"ShortName\": {\n      \"@id\": \"ds:ShortName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Size\": {\n      \"@id\": \"ds:Size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Edition\": {\n      \"@id\": \"ds:Edition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Alias\": {\n      \"@id\": \"ds:Alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccessUrl\": {\n      \"@id\": \"ds:AccessUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"ds:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Stage\": {\n      \"@id\": \"ds:Stage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShareStatus\": {\n      \"@id\": \"ds:ShareStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShareMethod\": {\n      \"@id\": \"ds:ShareMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShareNotes\": {\n      \"@id\": \"ds:ShareNotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  LaunchTime\": {\n      \"@id\": \"ds:LaunchTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StageLastUpdatedDateTime\": {\n      \"@id\": \"ds:StageLastUpdatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcSettings\": {\n      \"@id\": \"ds:VpcSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectSettings\": {\n      \"@id\": \"ds:ConnectSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RadiusSettings\": \"ds:RadiusSettings\",\n    \"RadiusStatus\": {\n      \"@id\": \"ds:RadiusStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StageReason\": {\n      \"@id\": \"ds:StageReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SsoEnabled\": {\n      \"@id\": \"ds:SsoEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredNumberOfDomainControllers\": {\n      \"@id\": \"ds:DesiredNumberOfDomainControllers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerDirectoryDescription\": \"ds:OwnerDirectoryDescription\",\n    \"\
  RegionsInfo\": {\n      \"@id\": \"ds:RegionsInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OsVersion\": {\n      \"@id\": \"ds:OsVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryLimits\": \"ds:DirectoryLimits\",\n    \"CloudOnlyDirectoriesLimit\": {\n      \"@id\": \"ds:CloudOnlyDirectoriesLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudOnlyDirectoriesCurrentCount\": {\n      \"@id\": \"ds:CloudOnlyDirectoriesCurrentCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudOnlyDirectoriesLimitReached\": {\n      \"@id\": \"ds:CloudOnlyDirectoriesLimitReached\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudOnlyMicrosoftADLimit\": {\n      \"@id\": \"ds:CloudOnlyMicrosoftADLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudOnlyMicrosoftADCurrentCount\": {\n      \"@id\": \"ds:CloudOnlyMicrosoftADCurrentCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudOnlyMicrosoftADLimitReached\": {\n      \"@id\": \"ds:CloudOnlyMicrosoftADLimitReached\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectedDirectoriesLimit\": {\n      \"@id\": \"ds:ConnectedDirectoriesLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectedDirectoriesCurrentCount\": {\n      \"@id\": \"ds:ConnectedDirectoriesCurrentCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectedDirectoriesLimitReached\": {\n      \"@id\": \"ds:ConnectedDirectoriesLimitReached\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DirectoryVpcSettings\": \"ds:DirectoryVpcSettings\",\n    \"DirectoryVpcSettingsDescription\": \"ds:DirectoryVpcSettingsDescription\",\n    \"EventTopic\": \"ds:EventTopic\",\n    \"TopicName\": {\n      \"@id\": \"ds:TopicName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TopicArn\": {\n      \"@id\": \"ds:TopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedDateTime\": {\n      \"@id\": \"ds:CreatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"ds:Status\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"IpRoute\": \"ds:IpRoute\",\n    \"CidrIp\": {\n      \"@id\": \"ds:CidrIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpRouteInfo\": \"ds:IpRouteInfo\",\n    \"IpRouteStatusMsg\": {\n      \"@id\": \"ds:IpRouteStatusMsg\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AddedDateTime\": {\n      \"@id\": \"ds:AddedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpRouteStatusReason\": {\n      \"@id\": \"ds:IpRouteStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LDAPSSettingInfo\": \"ds:LDAPSSettingInfo\",\n    \"LDAPSStatus\": {\n      \"@id\": \"ds:LDAPSStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LDAPSStatusReason\": {\n      \"@id\": \"ds:LDAPSStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedDateTime\": {\n      \"@id\": \"ds:LastUpdatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LogSubscription\": \"ds:LogSubscription\",\n    \"LogGroupName\": {\n      \"\
  @id\": \"ds:LogGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionCreatedDateTime\": {\n      \"@id\": \"ds:SubscriptionCreatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OSUpdateSettings\": \"ds:OSUpdateSettings\",\n    \"OSVersion\": {\n      \"@id\": \"ds:OSVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"ds:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RadiusServers\": {\n      \"@id\": \"ds:RadiusServers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RadiusPort\": {\n      \"@id\": \"ds:RadiusPort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RadiusTimeout\": {\n      \"@id\": \"ds:RadiusTimeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RadiusRetries\": {\n      \"@id\": \"ds:RadiusRetries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedSecret\": {\n      \"@id\": \"ds:SharedSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AuthenticationProtocol\": {\n\
  \      \"@id\": \"ds:AuthenticationProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayLabel\": {\n      \"@id\": \"ds:DisplayLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UseSameUsername\": {\n      \"@id\": \"ds:UseSameUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegionDescription\": \"ds:RegionDescription\",\n    \"RegionName\": {\n      \"@id\": \"ds:RegionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegionType\": {\n      \"@id\": \"ds:RegionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusLastUpdatedDateTime\": {\n      \"@id\": \"ds:StatusLastUpdatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaExtensionInfo\": \"ds:SchemaExtensionInfo\",\n    \"SchemaExtensionId\": {\n      \"@id\": \"ds:SchemaExtensionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaExtensionStatus\": {\n      \"@id\": \"ds:SchemaExtensionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaExtensionStatusReason\"\
  : {\n      \"@id\": \"ds:SchemaExtensionStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartDateTime\": {\n      \"@id\": \"ds:StartDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndDateTime\": {\n      \"@id\": \"ds:EndDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedDirectory\": \"ds:SharedDirectory\",\n    \"OwnerAccountId\": {\n      \"@id\": \"ds:OwnerAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OwnerDirectoryId\": {\n      \"@id\": \"ds:OwnerDirectoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedAccountId\": {\n      \"@id\": \"ds:SharedAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedDirectoryId\": {\n      \"@id\": \"ds:SharedDirectoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Snapshot\": \"ds:Snapshot\",\n    \"SnapshotId\": {\n      \"@id\": \"ds:SnapshotId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"ds:StartTime\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"SnapshotLimits\": \"ds:SnapshotLimits\",\n    \"ManualSnapshotsLimit\": {\n      \"@id\": \"ds:ManualSnapshotsLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManualSnapshotsCurrentCount\": {\n      \"@id\": \"ds:ManualSnapshotsCurrentCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManualSnapshotsLimitReached\": {\n      \"@id\": \"ds:ManualSnapshotsLimitReached\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"ds:Tag\",\n    \"Key\": {\n      \"@id\": \"ds:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"ds:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Trust\": \"ds:Trust\",\n    \"TrustId\": {\n      \"@id\": \"ds:TrustId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrustType\": {\n      \"@id\": \"ds:TrustType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrustDirection\": {\n      \"@id\": \"ds:TrustDirection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrustState\"\
  : {\n      \"@id\": \"ds:TrustState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StateLastUpdatedDateTime\": {\n      \"@id\": \"ds:StateLastUpdatedDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrustStateReason\": {\n      \"@id\": \"ds:TrustStateReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SelectiveAuth\": {\n      \"@id\": \"ds:SelectiveAuth\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-directory-service/refs/heads/main/json-ld/amazon-directory-service-context.jsonld
tags:
- Active Directory
- Authentication
- AWS
- Directory Services
- Identity Management
- JSON-LD
- Linked Data
- Semantic Web
---
