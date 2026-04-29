---
class_count: 25
classes:
- AccountQuota
- AvailabilityZone
- Certificate
- CollectorResponse
- Connection
- DatabaseResponse
- Endpoint
- EventSubscription
- Limitation
- OrderableReplicationInstance
- PendingMaintenanceAction
- RefreshSchemasStatus
- ReplicationInstance
- ReplicationSubnetGroup
- ReplicationInstanceTaskLog
- ReplicationTask
- ReplicationTaskStats
- ReplicationTaskAssessmentResult
- ReplicationTaskAssessmentRun
- SchemaResponse
- Subnet
- SupportedEndpointType
- TableStatistics
- Tag
- VpcSecurityGroupMembership
context_file: json-ld/amazon-dms-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/json-ld/amazon-dms-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Dms from Amazon DMS.
layout: jsonld
name: Amazon Dms Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: dms
  uri: https://aws.amazon.com/dms/vocab#
properties:
- container: ''
  name: AccountQuotaName
  type: string
- container: ''
  name: Used
  type: string
- container: ''
  name: Max
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: CertificateIdentifier
  type: string
- container: ''
  name: CertificateCreationDate
  type: string
- container: ''
  name: CertificatePem
  type: string
- container: ''
  name: CertificateWallet
  type: string
- container: ''
  name: CertificateArn
  type: string
- container: ''
  name: CertificateOwner
  type: string
- container: ''
  name: ValidFromDate
  type: string
- container: ''
  name: ValidToDate
  type: string
- container: ''
  name: SigningAlgorithm
  type: string
- container: ''
  name: KeyLength
  type: string
- container: ''
  name: CollectorReferencedId
  type: string
- container: ''
  name: CollectorName
  type: string
- container: ''
  name: CollectorVersion
  type: string
- container: ''
  name: VersionStatus
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: S3BucketName
  type: string
- container: ''
  name: ServiceAccessRoleArn
  type: string
- container: ''
  name: CollectorHealthCheck
  type: string
- container: ''
  name: LastDataReceived
  type: string
- container: ''
  name: RegisteredDate
  type: string
- container: ''
  name: CreatedDate
  type: string
- container: ''
  name: ModifiedDate
  type: string
- container: ''
  name: InventoryData
  type: string
- container: ''
  name: ReplicationInstanceArn
  type: string
- container: ''
  name: EndpointArn
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: LastFailureMessage
  type: string
- container: ''
  name: EndpointIdentifier
  type: string
- container: ''
  name: ReplicationInstanceIdentifier
  type: string
- container: ''
  name: DatabaseId
  type: string
- container: ''
  name: DatabaseName
  type: string
- container: ''
  name: IpAddress
  type: string
- container: ''
  name: NumberOfSchemas
  type: string
- container: ''
  name: Server
  type: string
- container: ''
  name: SoftwareDetails
  type: string
- container: ''
  name: Collectors
  type: string
- container: ''
  name: EndpointType
  type: string
- container: ''
  name: EngineName
  type: string
- container: ''
  name: EngineDisplayName
  type: string
- container: ''
  name: Username
  type: string
- container: ''
  name: ServerName
  type: string
- container: ''
  name: Port
  type: string
- container: ''
  name: ExtraConnectionAttributes
  type: string
- container: ''
  name: KmsKeyId
  type: string
- container: ''
  name: SslMode
  type: string
- container: ''
  name: ExternalTableDefinition
  type: string
- container: ''
  name: ExternalId
  type: string
- container: ''
  name: DynamoDbSettings
  type: string
- container: ''
  name: S3Settings
  type: string
- container: ''
  name: DmsTransferSettings
  type: string
- container: ''
  name: MongoDbSettings
  type: string
- container: ''
  name: KinesisSettings
  type: string
- container: ''
  name: KafkaSettings
  type: string
- container: ''
  name: ElasticsearchSettings
  type: string
- container: ''
  name: NeptuneSettings
  type: string
- container: ''
  name: RedshiftSettings
  type: string
- container: ''
  name: PostgreSQLSettings
  type: string
- container: ''
  name: MySQLSettings
  type: string
- container: ''
  name: OracleSettings
  type: string
- container: ''
  name: SybaseSettings
  type: string
- container: ''
  name: MicrosoftSQLServerSettings
  type: string
- container: ''
  name: IBMDb2Settings
  type: string
- container: ''
  name: DocDbSettings
  type: string
- container: ''
  name: RedisSettings
  type: string
- container: ''
  name: GcpMySQLSettings
  type: string
- container: ''
  name: CustomerAwsId
  type: string
- container: ''
  name: CustSubscriptionId
  type: string
- container: ''
  name: SnsTopicArn
  type: string
- container: ''
  name: SubscriptionCreationTime
  type: string
- container: ''
  name: SourceType
  type: string
- container: ''
  name: SourceIdsList
  type: string
- container: ''
  name: EventCategoriesList
  type: string
- container: ''
  name: Enabled
  type: string
- container: ''
  name: Impact
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: EngineVersion
  type: string
- container: ''
  name: ReplicationInstanceClass
  type: string
- container: ''
  name: StorageType
  type: string
- container: ''
  name: MinAllocatedStorage
  type: string
- container: ''
  name: MaxAllocatedStorage
  type: string
- container: ''
  name: DefaultAllocatedStorage
  type: string
- container: ''
  name: IncludedAllocatedStorage
  type: string
- container: ''
  name: AvailabilityZones
  type: string
- container: ''
  name: ReleaseStatus
  type: string
- container: ''
  name: Action
  type: string
- container: ''
  name: AutoAppliedAfterDate
  type: string
- container: ''
  name: ForcedApplyDate
  type: string
- container: ''
  name: OptInStatus
  type: string
- container: ''
  name: CurrentApplyDate
  type: string
- container: ''
  name: LastRefreshDate
  type: string
- container: ''
  name: ReplicationInstanceStatus
  type: string
- container: ''
  name: AllocatedStorage
  type: string
- container: ''
  name: InstanceCreateTime
  type: string
- container: ''
  name: VpcSecurityGroups
  type: string
- container: ''
  name: PreferredMaintenanceWindow
  type: string
- container: ''
  name: PendingModifiedValues
  type: string
- container: ''
  name: MultiAZ
  type: string
- container: ''
  name: AutoMinorVersionUpgrade
  type: string
- container: ''
  name: ReplicationInstancePublicIpAddress
  type: string
- container: ''
  name: ReplicationInstancePrivateIpAddress
  type: string
- container: ''
  name: ReplicationInstancePublicIpAddresses
  type: string
- container: ''
  name: ReplicationInstancePrivateIpAddresses
  type: string
- container: ''
  name: ReplicationInstanceIpv6Addresses
  type: string
- container: ''
  name: PubliclyAccessible
  type: string
- container: ''
  name: SecondaryAvailabilityZone
  type: string
- container: ''
  name: FreeUntil
  type: string
- container: ''
  name: DnsNameServers
  type: string
- container: ''
  name: NetworkType
  type: string
- container: ''
  name: ReplicationTaskName
  type: string
- container: ''
  name: ReplicationTaskArn
  type: string
- container: ''
  name: ReplicationInstanceTaskLogSize
  type: string
- container: ''
  name: ReplicationSubnetGroupIdentifier
  type: string
- container: ''
  name: ReplicationSubnetGroupDescription
  type: string
- container: ''
  name: VpcId
  type: string
- container: ''
  name: SubnetGroupStatus
  type: string
- container: ''
  name: Subnets
  type: string
- container: ''
  name: SupportedNetworkTypes
  type: string
- container: ''
  name: ReplicationTaskIdentifier
  type: string
- container: ''
  name: SourceEndpointArn
  type: string
- container: ''
  name: TargetEndpointArn
  type: string
- container: ''
  name: MigrationType
  type: string
- container: ''
  name: TableMappings
  type: string
- container: ''
  name: ReplicationTaskSettings
  type: string
- container: ''
  name: StopReason
  type: string
- container: ''
  name: ReplicationTaskCreationDate
  type: string
- container: ''
  name: ReplicationTaskStartDate
  type: string
- container: ''
  name: CdcStartPosition
  type: string
- container: ''
  name: CdcStopPosition
  type: string
- container: ''
  name: RecoveryCheckpoint
  type: string
- container: ''
  name: TaskData
  type: string
- container: ''
  name: TargetReplicationInstanceArn
  type: string
- container: ''
  name: ReplicationTaskLastAssessmentDate
  type: string
- container: ''
  name: AssessmentStatus
  type: string
- container: ''
  name: AssessmentResultsFile
  type: string
- container: ''
  name: AssessmentResults
  type: string
- container: ''
  name: S3ObjectUrl
  type: string
- container: ''
  name: ReplicationTaskAssessmentRunArn
  type: string
- container: ''
  name: ReplicationTaskAssessmentRunCreationDate
  type: string
- container: ''
  name: AssessmentProgress
  type: string
- container: ''
  name: ResultLocationBucket
  type: string
- container: ''
  name: ResultLocationFolder
  type: string
- container: ''
  name: ResultEncryptionMode
  type: string
- container: ''
  name: ResultKmsKeyArn
  type: string
- container: ''
  name: AssessmentRunName
  type: string
- container: ''
  name: FullLoadProgressPercent
  type: string
- container: ''
  name: ElapsedTimeMillis
  type: string
- container: ''
  name: TablesLoaded
  type: string
- container: ''
  name: TablesLoading
  type: string
- container: ''
  name: TablesQueued
  type: string
- container: ''
  name: TablesErrored
  type: string
- container: ''
  name: FreshStartDate
  type: string
- container: ''
  name: StartDate
  type: string
- container: ''
  name: StopDate
  type: string
- container: ''
  name: FullLoadStartDate
  type: string
- container: ''
  name: FullLoadFinishDate
  type: string
- container: ''
  name: CodeLineCount
  type: string
- container: ''
  name: CodeSize
  type: string
- container: ''
  name: Complexity
  type: string
- container: ''
  name: DatabaseInstance
  type: string
- container: ''
  name: SchemaId
  type: string
- container: ''
  name: SchemaName
  type: string
- container: ''
  name: OriginalSchema
  type: string
- container: ''
  name: Similarity
  type: string
- container: ''
  name: SubnetIdentifier
  type: string
- container: ''
  name: SubnetAvailabilityZone
  type: string
- container: ''
  name: SubnetStatus
  type: string
- container: ''
  name: SupportsCDC
  type: string
- container: ''
  name: ReplicationInstanceEngineMinimumVersion
  type: string
- container: ''
  name: TableName
  type: string
- container: ''
  name: Inserts
  type: string
- container: ''
  name: Deletes
  type: string
- container: ''
  name: Updates
  type: string
- container: ''
  name: Ddls
  type: string
- container: ''
  name: AppliedInserts
  type: string
- container: ''
  name: AppliedDeletes
  type: string
- container: ''
  name: AppliedUpdates
  type: string
- container: ''
  name: AppliedDdls
  type: string
- container: ''
  name: FullLoadRows
  type: string
- container: ''
  name: FullLoadCondtnlChkFailedRows
  type: string
- container: ''
  name: FullLoadErrorRows
  type: string
- container: ''
  name: FullLoadStartTime
  type: string
- container: ''
  name: FullLoadEndTime
  type: string
- container: ''
  name: FullLoadReloaded
  type: string
- container: ''
  name: LastUpdateTime
  type: string
- container: ''
  name: TableState
  type: string
- container: ''
  name: ValidationPendingRecords
  type: string
- container: ''
  name: ValidationFailedRecords
  type: string
- container: ''
  name: ValidationSuspendedRecords
  type: string
- container: ''
  name: ValidationState
  type: string
- container: ''
  name: ValidationStateDetails
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: ResourceArn
  type: string
- container: ''
  name: VpcSecurityGroupId
  type: string
property_count: 198
provider_name: Amazon DMS
provider_slug: amazon-dms
slug: amazon-dms-context
source_filename: amazon-dms-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"dms\": \"https://aws.amazon.com/dms/vocab#\",\n    \"AccountQuota\": \"dms:AccountQuota\",\n    \"AccountQuotaName\": {\n      \"@id\": \"dms:AccountQuotaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Used\": {\n      \"@id\": \"dms:Used\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Max\": {\n      \"@id\": \"dms:Max\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZone\": \"dms:AvailabilityZone\",\n    \"Name\": {\n      \"@id\": \"dms:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Certificate\": \"dms:Certificate\",\n    \"CertificateIdentifier\": {\n      \"@id\": \"dms:CertificateIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateCreationDate\": {\n      \"@id\": \"dms:CertificateCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificatePem\": {\n   \
  \   \"@id\": \"dms:CertificatePem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateWallet\": {\n      \"@id\": \"dms:CertificateWallet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateArn\": {\n      \"@id\": \"dms:CertificateArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CertificateOwner\": {\n      \"@id\": \"dms:CertificateOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidFromDate\": {\n      \"@id\": \"dms:ValidFromDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidToDate\": {\n      \"@id\": \"dms:ValidToDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SigningAlgorithm\": {\n      \"@id\": \"dms:SigningAlgorithm\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyLength\": {\n      \"@id\": \"dms:KeyLength\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectorResponse\": \"dms:CollectorResponse\",\n    \"CollectorReferencedId\": {\n      \"@id\": \"dms:CollectorReferencedId\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"CollectorName\": {\n      \"@id\": \"dms:CollectorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectorVersion\": {\n      \"@id\": \"dms:CollectorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionStatus\": {\n      \"@id\": \"dms:VersionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"dms:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3BucketName\": {\n      \"@id\": \"dms:S3BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceAccessRoleArn\": {\n      \"@id\": \"dms:ServiceAccessRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CollectorHealthCheck\": {\n      \"@id\": \"dms:CollectorHealthCheck\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastDataReceived\": {\n      \"@id\": \"dms:LastDataReceived\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RegisteredDate\": {\n      \"@id\": \"dms:RegisteredDate\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"CreatedDate\": {\n      \"@id\": \"dms:CreatedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ModifiedDate\": {\n      \"@id\": \"dms:ModifiedDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InventoryData\": {\n      \"@id\": \"dms:InventoryData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Connection\": \"dms:Connection\",\n    \"ReplicationInstanceArn\": {\n      \"@id\": \"dms:ReplicationInstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointArn\": {\n      \"@id\": \"dms:EndpointArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"dms:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastFailureMessage\": {\n      \"@id\": \"dms:LastFailureMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointIdentifier\": {\n      \"@id\": \"dms:EndpointIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceIdentifier\": {\n      \"@id\": \"dms:ReplicationInstanceIdentifier\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseResponse\": \"dms:DatabaseResponse\",\n    \"DatabaseId\": {\n      \"@id\": \"dms:DatabaseId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseName\": {\n      \"@id\": \"dms:DatabaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IpAddress\": {\n      \"@id\": \"dms:IpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NumberOfSchemas\": {\n      \"@id\": \"dms:NumberOfSchemas\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Server\": {\n      \"@id\": \"dms:Server\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SoftwareDetails\": {\n      \"@id\": \"dms:SoftwareDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Collectors\": {\n      \"@id\": \"dms:Collectors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Endpoint\": \"dms:Endpoint\",\n    \"EndpointType\": {\n      \"@id\": \"dms:EndpointType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EngineName\": {\n      \"@id\": \"dms:EngineName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"EngineDisplayName\": {\n      \"@id\": \"dms:EngineDisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Username\": {\n      \"@id\": \"dms:Username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerName\": {\n      \"@id\": \"dms:ServerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Port\": {\n      \"@id\": \"dms:Port\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExtraConnectionAttributes\": {\n      \"@id\": \"dms:ExtraConnectionAttributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyId\": {\n      \"@id\": \"dms:KmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SslMode\": {\n      \"@id\": \"dms:SslMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalTableDefinition\": {\n      \"@id\": \"dms:ExternalTableDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExternalId\": {\n      \"@id\": \"dms:ExternalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DynamoDbSettings\"\
  : {\n      \"@id\": \"dms:DynamoDbSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Settings\": {\n      \"@id\": \"dms:S3Settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DmsTransferSettings\": {\n      \"@id\": \"dms:DmsTransferSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MongoDbSettings\": {\n      \"@id\": \"dms:MongoDbSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KinesisSettings\": {\n      \"@id\": \"dms:KinesisSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KafkaSettings\": {\n      \"@id\": \"dms:KafkaSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ElasticsearchSettings\": {\n      \"@id\": \"dms:ElasticsearchSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NeptuneSettings\": {\n      \"@id\": \"dms:NeptuneSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RedshiftSettings\": {\n      \"@id\": \"dms:RedshiftSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PostgreSQLSettings\"\
  : {\n      \"@id\": \"dms:PostgreSQLSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MySQLSettings\": {\n      \"@id\": \"dms:MySQLSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OracleSettings\": {\n      \"@id\": \"dms:OracleSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SybaseSettings\": {\n      \"@id\": \"dms:SybaseSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MicrosoftSQLServerSettings\": {\n      \"@id\": \"dms:MicrosoftSQLServerSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IBMDb2Settings\": {\n      \"@id\": \"dms:IBMDb2Settings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DocDbSettings\": {\n      \"@id\": \"dms:DocDbSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RedisSettings\": {\n      \"@id\": \"dms:RedisSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GcpMySQLSettings\": {\n      \"@id\": \"dms:GcpMySQLSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventSubscription\"\
  : \"dms:EventSubscription\",\n    \"CustomerAwsId\": {\n      \"@id\": \"dms:CustomerAwsId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CustSubscriptionId\": {\n      \"@id\": \"dms:CustSubscriptionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SnsTopicArn\": {\n      \"@id\": \"dms:SnsTopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscriptionCreationTime\": {\n      \"@id\": \"dms:SubscriptionCreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceType\": {\n      \"@id\": \"dms:SourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceIdsList\": {\n      \"@id\": \"dms:SourceIdsList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventCategoriesList\": {\n      \"@id\": \"dms:EventCategoriesList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Enabled\": {\n      \"@id\": \"dms:Enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Limitation\": \"dms:Limitation\",\n    \"Impact\": {\n      \"@id\": \"dms:Impact\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"dms:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrderableReplicationInstance\": \"dms:OrderableReplicationInstance\",\n    \"EngineVersion\": {\n      \"@id\": \"dms:EngineVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceClass\": {\n      \"@id\": \"dms:ReplicationInstanceClass\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageType\": {\n      \"@id\": \"dms:StorageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinAllocatedStorage\": {\n      \"@id\": \"dms:MinAllocatedStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxAllocatedStorage\": {\n      \"@id\": \"dms:MaxAllocatedStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultAllocatedStorage\": {\n      \"@id\": \"dms:DefaultAllocatedStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IncludedAllocatedStorage\": {\n      \"@id\": \"dms:IncludedAllocatedStorage\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"AvailabilityZones\": {\n      \"@id\": \"dms:AvailabilityZones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReleaseStatus\": {\n      \"@id\": \"dms:ReleaseStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingMaintenanceAction\": \"dms:PendingMaintenanceAction\",\n    \"Action\": {\n      \"@id\": \"dms:Action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoAppliedAfterDate\": {\n      \"@id\": \"dms:AutoAppliedAfterDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ForcedApplyDate\": {\n      \"@id\": \"dms:ForcedApplyDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OptInStatus\": {\n      \"@id\": \"dms:OptInStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentApplyDate\": {\n      \"@id\": \"dms:CurrentApplyDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RefreshSchemasStatus\": \"dms:RefreshSchemasStatus\",\n    \"LastRefreshDate\": {\n      \"@id\": \"dms:LastRefreshDate\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"ReplicationInstance\": \"dms:ReplicationInstance\",\n    \"ReplicationInstanceStatus\": {\n      \"@id\": \"dms:ReplicationInstanceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AllocatedStorage\": {\n      \"@id\": \"dms:AllocatedStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceCreateTime\": {\n      \"@id\": \"dms:InstanceCreateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcSecurityGroups\": {\n      \"@id\": \"dms:VpcSecurityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationSubnetGroup\": \"dms:ReplicationSubnetGroup\",\n    \"PreferredMaintenanceWindow\": {\n      \"@id\": \"dms:PreferredMaintenanceWindow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PendingModifiedValues\": {\n      \"@id\": \"dms:PendingModifiedValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MultiAZ\": {\n      \"@id\": \"dms:MultiAZ\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoMinorVersionUpgrade\": {\n\
  \      \"@id\": \"dms:AutoMinorVersionUpgrade\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstancePublicIpAddress\": {\n      \"@id\": \"dms:ReplicationInstancePublicIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstancePrivateIpAddress\": {\n      \"@id\": \"dms:ReplicationInstancePrivateIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstancePublicIpAddresses\": {\n      \"@id\": \"dms:ReplicationInstancePublicIpAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstancePrivateIpAddresses\": {\n      \"@id\": \"dms:ReplicationInstancePrivateIpAddresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceIpv6Addresses\": {\n      \"@id\": \"dms:ReplicationInstanceIpv6Addresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PubliclyAccessible\": {\n      \"@id\": \"dms:PubliclyAccessible\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecondaryAvailabilityZone\": {\n      \"\
  @id\": \"dms:SecondaryAvailabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FreeUntil\": {\n      \"@id\": \"dms:FreeUntil\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DnsNameServers\": {\n      \"@id\": \"dms:DnsNameServers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkType\": {\n      \"@id\": \"dms:NetworkType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceTaskLog\": \"dms:ReplicationInstanceTaskLog\",\n    \"ReplicationTaskName\": {\n      \"@id\": \"dms:ReplicationTaskName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskArn\": {\n      \"@id\": \"dms:ReplicationTaskArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceTaskLogSize\": {\n      \"@id\": \"dms:ReplicationInstanceTaskLogSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationSubnetGroupIdentifier\": {\n      \"@id\": \"dms:ReplicationSubnetGroupIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationSubnetGroupDescription\"\
  : {\n      \"@id\": \"dms:ReplicationSubnetGroupDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcId\": {\n      \"@id\": \"dms:VpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetGroupStatus\": {\n      \"@id\": \"dms:SubnetGroupStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subnets\": {\n      \"@id\": \"dms:Subnets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedNetworkTypes\": {\n      \"@id\": \"dms:SupportedNetworkTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTask\": \"dms:ReplicationTask\",\n    \"ReplicationTaskIdentifier\": {\n      \"@id\": \"dms:ReplicationTaskIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceEndpointArn\": {\n      \"@id\": \"dms:SourceEndpointArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetEndpointArn\": {\n      \"@id\": \"dms:TargetEndpointArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MigrationType\": {\n      \"@id\": \"dms:MigrationType\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"TableMappings\": {\n      \"@id\": \"dms:TableMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskSettings\": {\n      \"@id\": \"dms:ReplicationTaskSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StopReason\": {\n      \"@id\": \"dms:StopReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskCreationDate\": {\n      \"@id\": \"dms:ReplicationTaskCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskStartDate\": {\n      \"@id\": \"dms:ReplicationTaskStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CdcStartPosition\": {\n      \"@id\": \"dms:CdcStartPosition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CdcStopPosition\": {\n      \"@id\": \"dms:CdcStopPosition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecoveryCheckpoint\": {\n      \"@id\": \"dms:RecoveryCheckpoint\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskStats\"\
  : \"dms:ReplicationTaskStats\",\n    \"TaskData\": {\n      \"@id\": \"dms:TaskData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetReplicationInstanceArn\": {\n      \"@id\": \"dms:TargetReplicationInstanceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskAssessmentResult\": \"dms:ReplicationTaskAssessmentResult\",\n    \"ReplicationTaskLastAssessmentDate\": {\n      \"@id\": \"dms:ReplicationTaskLastAssessmentDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssessmentStatus\": {\n      \"@id\": \"dms:AssessmentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssessmentResultsFile\": {\n      \"@id\": \"dms:AssessmentResultsFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssessmentResults\": {\n      \"@id\": \"dms:AssessmentResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3ObjectUrl\": {\n      \"@id\": \"dms:S3ObjectUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskAssessmentRun\": \"dms:ReplicationTaskAssessmentRun\"\
  ,\n    \"ReplicationTaskAssessmentRunArn\": {\n      \"@id\": \"dms:ReplicationTaskAssessmentRunArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationTaskAssessmentRunCreationDate\": {\n      \"@id\": \"dms:ReplicationTaskAssessmentRunCreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssessmentProgress\": {\n      \"@id\": \"dms:AssessmentProgress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultLocationBucket\": {\n      \"@id\": \"dms:ResultLocationBucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultLocationFolder\": {\n      \"@id\": \"dms:ResultLocationFolder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultEncryptionMode\": {\n      \"@id\": \"dms:ResultEncryptionMode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResultKmsKeyArn\": {\n      \"@id\": \"dms:ResultKmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssessmentRunName\": {\n      \"@id\": \"dms:AssessmentRunName\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"FullLoadProgressPercent\": {\n      \"@id\": \"dms:FullLoadProgressPercent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ElapsedTimeMillis\": {\n      \"@id\": \"dms:ElapsedTimeMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TablesLoaded\": {\n      \"@id\": \"dms:TablesLoaded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TablesLoading\": {\n      \"@id\": \"dms:TablesLoading\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TablesQueued\": {\n      \"@id\": \"dms:TablesQueued\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TablesErrored\": {\n      \"@id\": \"dms:TablesErrored\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FreshStartDate\": {\n      \"@id\": \"dms:FreshStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartDate\": {\n      \"@id\": \"dms:StartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StopDate\": {\n      \"@id\": \"dms:StopDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadStartDate\": {\n\
  \      \"@id\": \"dms:FullLoadStartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadFinishDate\": {\n      \"@id\": \"dms:FullLoadFinishDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaResponse\": \"dms:SchemaResponse\",\n    \"CodeLineCount\": {\n      \"@id\": \"dms:CodeLineCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeSize\": {\n      \"@id\": \"dms:CodeSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Complexity\": {\n      \"@id\": \"dms:Complexity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DatabaseInstance\": {\n      \"@id\": \"dms:DatabaseInstance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaId\": {\n      \"@id\": \"dms:SchemaId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchemaName\": {\n      \"@id\": \"dms:SchemaName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OriginalSchema\": {\n      \"@id\": \"dms:OriginalSchema\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Similarity\": {\n      \"\
  @id\": \"dms:Similarity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subnet\": \"dms:Subnet\",\n    \"SubnetIdentifier\": {\n      \"@id\": \"dms:SubnetIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetAvailabilityZone\": {\n      \"@id\": \"dms:SubnetAvailabilityZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubnetStatus\": {\n      \"@id\": \"dms:SubnetStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SupportedEndpointType\": \"dms:SupportedEndpointType\",\n    \"SupportsCDC\": {\n      \"@id\": \"dms:SupportsCDC\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReplicationInstanceEngineMinimumVersion\": {\n      \"@id\": \"dms:ReplicationInstanceEngineMinimumVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableStatistics\": \"dms:TableStatistics\",\n    \"TableName\": {\n      \"@id\": \"dms:TableName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Inserts\": {\n      \"@id\": \"dms:Inserts\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"Deletes\": {\n      \"@id\": \"dms:Deletes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Updates\": {\n      \"@id\": \"dms:Updates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ddls\": {\n      \"@id\": \"dms:Ddls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppliedInserts\": {\n      \"@id\": \"dms:AppliedInserts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppliedDeletes\": {\n      \"@id\": \"dms:AppliedDeletes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppliedUpdates\": {\n      \"@id\": \"dms:AppliedUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AppliedDdls\": {\n      \"@id\": \"dms:AppliedDdls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadRows\": {\n      \"@id\": \"dms:FullLoadRows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadCondtnlChkFailedRows\": {\n      \"@id\": \"dms:FullLoadCondtnlChkFailedRows\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadErrorRows\": {\n      \"@id\": \"dms:FullLoadErrorRows\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadStartTime\": {\n      \"@id\": \"dms:FullLoadStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadEndTime\": {\n      \"@id\": \"dms:FullLoadEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullLoadReloaded\": {\n      \"@id\": \"dms:FullLoadReloaded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdateTime\": {\n      \"@id\": \"dms:LastUpdateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TableState\": {\n      \"@id\": \"dms:TableState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationPendingRecords\": {\n      \"@id\": \"dms:ValidationPendingRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationFailedRecords\": {\n      \"@id\": \"dms:ValidationFailedRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationSuspendedRecords\": {\n      \"@id\": \"dms:ValidationSuspendedRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationState\": {\n\
  \      \"@id\": \"dms:ValidationState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValidationStateDetails\": {\n      \"@id\": \"dms:ValidationStateDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tag\": \"dms:Tag\",\n    \"Key\": {\n      \"@id\": \"dms:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"dms:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceArn\": {\n      \"@id\": \"dms:ResourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VpcSecurityGroupMembership\": \"dms:VpcSecurityGroupMembership\",\n    \"VpcSecurityGroupId\": {\n      \"@id\": \"dms:VpcSecurityGroupId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-dms/refs/heads/main/json-ld/amazon-dms-context.jsonld
tags:
- AWS
- Data Replication
- Database
- Database Migration
- Migration
- JSON-LD
- Linked Data
- Semantic Web
---
