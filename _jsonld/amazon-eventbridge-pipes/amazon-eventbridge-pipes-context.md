---
api_specs:
- filename: amazon-eventbridge-pipes-openapi.yml
  format: yaml
  label: Amazon EventBridge Pipes API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-pipes/refs/heads/main/openapi/amazon-eventbridge-pipes-openapi.yml
class_count: 83
classes:
- AwsVpcConfiguration
- BatchArrayProperties
- BatchContainerOverrides
- BatchEnvironmentVariable
- BatchJobDependency
- BatchParametersMap
- BatchResourceRequirement
- BatchRetryStrategy
- CapacityProviderStrategyItem
- CreatePipeRequest
- CreatePipeResponse
- DeadLetterConfig
- DeletePipeRequest
- DeletePipeResponse
- DescribePipeRequest
- DescribePipeResponse
- EcsContainerOverride
- EcsEnvironmentFile
- EcsEnvironmentVariable
- name
- EcsEphemeralStorage
- EcsInferenceAcceleratorOverride
- EcsResourceRequirement
- EcsTaskOverride
- FilterCriteria
- Filter
- HeaderParametersMap
- ListPipesRequest
- ListPipesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- MQBrokerAccessCredentials
- MSKAccessCredentials
- NetworkConfiguration
- PipeEnrichmentHttpParameters
- PipeEnrichmentParameters
- Pipe
- PipeSourceActiveMQBrokerParameters
- PipeSourceDynamoDBStreamParameters
- PipeSourceKinesisStreamParameters
- PipeSourceManagedStreamingKafkaParameters
- PipeSourceParameters
- PipeSourceRabbitMQBrokerParameters
- PipeSourceSelfManagedKafkaParameters
- PipeSourceSqsQueueParameters
- PipeTargetBatchJobParameters
- PipeTargetCloudWatchLogsParameters
- PipeTargetEcsTaskParameters
- PlacementStrategy
- PipeTargetEventBridgeEventBusParameters
- PipeTargetHttpParameters
- PipeTargetKinesisStreamParameters
- PipeTargetLambdaFunctionParameters
- PipeTargetParameters
- PipeTargetRedshiftDataParameters
- PipeTargetSageMakerPipelineParameters
- PipeTargetSqsQueueParameters
- PipeTargetStateMachineParameters
- PlacementConstraint
- QueryStringParametersMap
- SageMakerPipelineParameter
- SelfManagedKafkaAccessConfigurationCredentials
- SelfManagedKafkaAccessConfigurationVpc
- StartPipeRequest
- StartPipeResponse
- StopPipeRequest
- StopPipeResponse
- TagMap
- TagResourceRequest
- TagResourceResponse
- Tag
- UntagResourceRequest
- UntagResourceResponse
- UpdatePipeRequest
- UpdatePipeResponse
- UpdatePipeSourceActiveMQBrokerParameters
- UpdatePipeSourceDynamoDBStreamParameters
- UpdatePipeSourceKinesisStreamParameters
- UpdatePipeSourceManagedStreamingKafkaParameters
- UpdatePipeSourceParameters
- UpdatePipeSourceRabbitMQBrokerParameters
- UpdatePipeSourceSelfManagedKafkaParameters
- UpdatePipeSourceSqsQueueParameters
context_file: json-ld/amazon-eventbridge-pipes-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-pipes/refs/heads/main/json-ld/amazon-eventbridge-pipes-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Eventbridge Pipes from Amazon EventBridge Pipes.
layout: jsonld
name: Amazon Eventbridge Pipes Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AssignPublicIp
  type: string
- container: ''
  name: SecurityGroups
  type: string
- container: ''
  name: Subnets
  type: string
- container: ''
  name: Size
  type: string
- container: ''
  name: Command
  type: string
- container: ''
  name: Environment
  type: string
- container: ''
  name: InstanceType
  type: string
- container: ''
  name: ResourceRequirements
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: JobId
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: Attempts
  type: string
- container: ''
  name: base
  type: string
- container: ''
  name: capacityProvider
  type: string
- container: ''
  name: weight
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: DesiredState
  type: string
- container: ''
  name: Enrichment
  type: string
- container: ''
  name: EnrichmentParameters
  type: string
- container: ''
  name: RoleArn
  type: string
- container: ''
  name: Source
  type: string
- container: ''
  name: SourceParameters
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Target
  type: string
- container: ''
  name: TargetParameters
  type: string
- container: ''
  name: Arn
  type: string
- container: ''
  name: CreationTime
  type: string
- container: ''
  name: CurrentState
  type: string
- container: ''
  name: LastModifiedTime
  type: string
- container: ''
  name: StateReason
  type: string
- container: ''
  name: Cpu
  type: string
- container: ''
  name: EnvironmentFiles
  type: string
- container: ''
  name: Memory
  type: string
- container: ''
  name: MemoryReservation
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: sizeInGiB
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: deviceType
  type: string
- container: ''
  name: ContainerOverrides
  type: string
- container: ''
  name: EphemeralStorage
  type: string
- container: ''
  name: ExecutionRoleArn
  type: string
- container: ''
  name: InferenceAcceleratorOverrides
  type: string
- container: ''
  name: TaskRoleArn
  type: string
- container: ''
  name: Filters
  type: string
- container: ''
  name: Pattern
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: Pipes
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: BasicAuth
  type: string
- container: ''
  name: ClientCertificateTlsAuth
  type: string
- container: ''
  name: SaslScram512Auth
  type: string
- container: ''
  name: awsvpcConfiguration
  type: string
- container: ''
  name: HeaderParameters
  type: string
- container: ''
  name: PathParameterValues
  type: string
- container: ''
  name: QueryStringParameters
  type: string
- container: ''
  name: HttpParameters
  type: string
- container: ''
  name: InputTemplate
  type: string
- container: ''
  name: BatchSize
  type: string
- container: ''
  name: Credentials
  type: string
- container: ''
  name: MaximumBatchingWindowInSeconds
  type: string
- container: ''
  name: QueueName
  type: string
- container: ''
  name: MaximumRecordAgeInSeconds
  type: string
- container: ''
  name: MaximumRetryAttempts
  type: string
- container: ''
  name: OnPartialBatchItemFailure
  type: string
- container: ''
  name: ParallelizationFactor
  type: string
- container: ''
  name: StartingPosition
  type: string
- container: ''
  name: StartingPositionTimestamp
  type: string
- container: ''
  name: ConsumerGroupID
  type: string
- container: ''
  name: TopicName
  type: string
- container: ''
  name: ActiveMQBrokerParameters
  type: string
- container: ''
  name: DynamoDBStreamParameters
  type: string
- container: ''
  name: KinesisStreamParameters
  type: string
- container: ''
  name: ManagedStreamingKafkaParameters
  type: string
- container: ''
  name: RabbitMQBrokerParameters
  type: string
- container: ''
  name: SelfManagedKafkaParameters
  type: string
- container: ''
  name: SqsQueueParameters
  type: string
- container: ''
  name: VirtualHost
  type: string
- container: ''
  name: AdditionalBootstrapServers
  type: string
- container: ''
  name: ServerRootCaCertificate
  type: string
- container: ''
  name: Vpc
  type: string
- container: ''
  name: ArrayProperties
  type: string
- container: ''
  name: DependsOn
  type: string
- container: ''
  name: JobDefinition
  type: string
- container: ''
  name: JobName
  type: string
- container: ''
  name: Parameters
  type: string
- container: ''
  name: RetryStrategy
  type: string
- container: ''
  name: LogStreamName
  type: string
- container: ''
  name: Timestamp
  type: string
- container: ''
  name: CapacityProviderStrategy
  type: string
- container: ''
  name: EnableECSManagedTags
  type: string
- container: ''
  name: EnableExecuteCommand
  type: string
- container: ''
  name: Group
  type: string
- container: ''
  name: LaunchType
  type: string
- container: ''
  name: Overrides
  type: string
- container: ''
  name: PlacementConstraints
  type: string
- container: ''
  name: PlatformVersion
  type: string
- container: ''
  name: PropagateTags
  type: string
- container: ''
  name: ReferenceId
  type: string
- container: ''
  name: TaskCount
  type: string
- container: ''
  name: TaskDefinitionArn
  type: string
- container: ''
  name: DetailType
  type: string
- container: ''
  name: EndpointId
  type: string
- container: ''
  name: Resources
  type: string
- container: ''
  name: Time
  type: string
- container: ''
  name: PartitionKey
  type: string
- container: ''
  name: InvocationType
  type: string
- container: ''
  name: BatchJobParameters
  type: string
- container: ''
  name: CloudWatchLogsParameters
  type: string
- container: ''
  name: EcsTaskParameters
  type: string
- container: ''
  name: EventBridgeEventBusParameters
  type: string
- container: ''
  name: LambdaFunctionParameters
  type: string
- container: ''
  name: RedshiftDataParameters
  type: string
- container: ''
  name: SageMakerPipelineParameters
  type: string
- container: ''
  name: StepFunctionStateMachineParameters
  type: string
- container: ''
  name: Database
  type: string
- container: ''
  name: DbUser
  type: string
- container: ''
  name: SecretManagerArn
  type: string
- container: ''
  name: Sqls
  type: string
- container: ''
  name: StatementName
  type: string
- container: ''
  name: WithEvent
  type: string
- container: ''
  name: PipelineParameterList
  type: string
- container: ''
  name: MessageDeduplicationId
  type: string
- container: ''
  name: MessageGroupId
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: SaslScram256Auth
  type: string
- container: ''
  name: SecurityGroup
  type: string
- container: ''
  name: Key
  type: string
property_count: 130
provider_name: Amazon EventBridge Pipes
provider_slug: amazon-eventbridge-pipes
slug: amazon-eventbridge-pipes-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AwsVpcConfiguration\": \"aws:AwsVpcConfiguration\",\n    \"AssignPublicIp\": {\n      \"@id\": \"aws:AssignPublicIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroups\": {\n      \"@id\": \"aws:SecurityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subnets\": {\n      \"@id\": \"aws:Subnets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchArrayProperties\": \"aws:BatchArrayProperties\",\n    \"Size\": {\n      \"@id\": \"aws:Size\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchContainerOverrides\": \"aws:BatchContainerOverrides\",\n    \"Command\": {\n      \"@id\": \"aws:Command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Environment\": {\n      \"@id\": \"aws:Environment\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"InstanceType\": {\n      \"@id\": \"aws:InstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceRequirements\": {\n      \"@id\": \"aws:ResourceRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchEnvironmentVariable\": \"aws:BatchEnvironmentVariable\",\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchJobDependency\": \"aws:BatchJobDependency\",\n    \"JobId\": {\n      \"@id\": \"aws:JobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"aws:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BatchParametersMap\": \"aws:BatchParametersMap\",\n    \"BatchResourceRequirement\": \"aws:BatchResourceRequirement\",\n    \"BatchRetryStrategy\": \"aws:BatchRetryStrategy\",\n    \"Attempts\": {\n      \"@id\": \"aws:Attempts\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"CapacityProviderStrategyItem\": \"aws:CapacityProviderStrategyItem\",\n    \"base\": {\n      \"@id\": \"aws:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacityProvider\": {\n      \"@id\": \"aws:capacityProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"aws:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatePipeRequest\": \"aws:CreatePipeRequest\",\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredState\": {\n      \"@id\": \"aws:DesiredState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Enrichment\": {\n      \"@id\": \"aws:Enrichment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnrichmentParameters\": {\n      \"@id\": \"aws:EnrichmentParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n      \"@id\": \"aws:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"aws:Source\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceParameters\": {\n      \"@id\": \"aws:SourceParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Target\": {\n      \"@id\": \"aws:Target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetParameters\": {\n      \"@id\": \"aws:TargetParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatePipeResponse\": \"aws:CreatePipeResponse\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"aws:CreationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentState\": {\n      \"@id\": \"aws:CurrentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModifiedTime\": {\n      \"@id\": \"aws:LastModifiedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeadLetterConfig\": \"aws:DeadLetterConfig\",\n    \"DeletePipeRequest\": \"aws:DeletePipeRequest\"\
  ,\n    \"DeletePipeResponse\": \"aws:DeletePipeResponse\",\n    \"DescribePipeRequest\": \"aws:DescribePipeRequest\",\n    \"DescribePipeResponse\": \"aws:DescribePipeResponse\",\n    \"StateReason\": {\n      \"@id\": \"aws:StateReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsContainerOverride\": \"aws:EcsContainerOverride\",\n    \"Cpu\": {\n      \"@id\": \"aws:Cpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnvironmentFiles\": {\n      \"@id\": \"aws:EnvironmentFiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Memory\": {\n      \"@id\": \"aws:Memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MemoryReservation\": {\n      \"@id\": \"aws:MemoryReservation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsEnvironmentFile\": \"aws:EcsEnvironmentFile\",\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsEnvironmentVariable\"\
  : \"aws:EcsEnvironmentVariable\",\n    \"name\": \"schema:name\",\n    \"EcsEphemeralStorage\": \"aws:EcsEphemeralStorage\",\n    \"sizeInGiB\": {\n      \"@id\": \"aws:sizeInGiB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsInferenceAcceleratorOverride\": \"aws:EcsInferenceAcceleratorOverride\",\n    \"deviceName\": {\n      \"@id\": \"aws:deviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceType\": {\n      \"@id\": \"aws:deviceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsResourceRequirement\": \"aws:EcsResourceRequirement\",\n    \"EcsTaskOverride\": \"aws:EcsTaskOverride\",\n    \"ContainerOverrides\": {\n      \"@id\": \"aws:ContainerOverrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EphemeralStorage\": {\n      \"@id\": \"aws:EphemeralStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExecutionRoleArn\": {\n      \"@id\": \"aws:ExecutionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InferenceAcceleratorOverrides\"\
  : {\n      \"@id\": \"aws:InferenceAcceleratorOverrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskRoleArn\": {\n      \"@id\": \"aws:TaskRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilterCriteria\": \"aws:FilterCriteria\",\n    \"Filters\": {\n      \"@id\": \"aws:Filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Filter\": \"aws:Filter\",\n    \"Pattern\": {\n      \"@id\": \"aws:Pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HeaderParametersMap\": \"aws:HeaderParametersMap\",\n    \"ListPipesRequest\": \"aws:ListPipesRequest\",\n    \"ListPipesResponse\": \"aws:ListPipesResponse\",\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pipes\": {\n      \"@id\": \"aws:Pipes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceRequest\": \"aws:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"aws:ListTagsForResourceResponse\",\n    \"tags\": {\n      \"\
  @id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MQBrokerAccessCredentials\": \"aws:MQBrokerAccessCredentials\",\n    \"BasicAuth\": {\n      \"@id\": \"aws:BasicAuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MSKAccessCredentials\": \"aws:MSKAccessCredentials\",\n    \"ClientCertificateTlsAuth\": {\n      \"@id\": \"aws:ClientCertificateTlsAuth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SaslScram512Auth\": {\n      \"@id\": \"aws:SaslScram512Auth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkConfiguration\": \"aws:NetworkConfiguration\",\n    \"awsvpcConfiguration\": {\n      \"@id\": \"aws:awsvpcConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeEnrichmentHttpParameters\": \"aws:PipeEnrichmentHttpParameters\",\n    \"HeaderParameters\": {\n      \"@id\": \"aws:HeaderParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PathParameterValues\": {\n      \"@id\": \"aws:PathParameterValues\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"QueryStringParameters\": {\n      \"@id\": \"aws:QueryStringParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeEnrichmentParameters\": \"aws:PipeEnrichmentParameters\",\n    \"HttpParameters\": {\n      \"@id\": \"aws:HttpParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InputTemplate\": {\n      \"@id\": \"aws:InputTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Pipe\": \"aws:Pipe\",\n    \"PipeSourceActiveMQBrokerParameters\": \"aws:PipeSourceActiveMQBrokerParameters\",\n    \"BatchSize\": {\n      \"@id\": \"aws:BatchSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Credentials\": {\n      \"@id\": \"aws:Credentials\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumBatchingWindowInSeconds\": {\n      \"@id\": \"aws:MaximumBatchingWindowInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueueName\": {\n      \"@id\": \"aws:QueueName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceDynamoDBStreamParameters\"\
  : \"aws:PipeSourceDynamoDBStreamParameters\",\n    \"MaximumRecordAgeInSeconds\": {\n      \"@id\": \"aws:MaximumRecordAgeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumRetryAttempts\": {\n      \"@id\": \"aws:MaximumRetryAttempts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OnPartialBatchItemFailure\": {\n      \"@id\": \"aws:OnPartialBatchItemFailure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ParallelizationFactor\": {\n      \"@id\": \"aws:ParallelizationFactor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartingPosition\": {\n      \"@id\": \"aws:StartingPosition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceKinesisStreamParameters\": \"aws:PipeSourceKinesisStreamParameters\",\n    \"StartingPositionTimestamp\": {\n      \"@id\": \"aws:StartingPositionTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceManagedStreamingKafkaParameters\": \"aws:PipeSourceManagedStreamingKafkaParameters\",\n    \"ConsumerGroupID\"\
  : {\n      \"@id\": \"aws:ConsumerGroupID\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TopicName\": {\n      \"@id\": \"aws:TopicName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceParameters\": \"aws:PipeSourceParameters\",\n    \"ActiveMQBrokerParameters\": {\n      \"@id\": \"aws:ActiveMQBrokerParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DynamoDBStreamParameters\": {\n      \"@id\": \"aws:DynamoDBStreamParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KinesisStreamParameters\": {\n      \"@id\": \"aws:KinesisStreamParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ManagedStreamingKafkaParameters\": {\n      \"@id\": \"aws:ManagedStreamingKafkaParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RabbitMQBrokerParameters\": {\n      \"@id\": \"aws:RabbitMQBrokerParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SelfManagedKafkaParameters\": {\n      \"@id\": \"aws:SelfManagedKafkaParameters\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"SqsQueueParameters\": {\n      \"@id\": \"aws:SqsQueueParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceRabbitMQBrokerParameters\": \"aws:PipeSourceRabbitMQBrokerParameters\",\n    \"VirtualHost\": {\n      \"@id\": \"aws:VirtualHost\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceSelfManagedKafkaParameters\": \"aws:PipeSourceSelfManagedKafkaParameters\",\n    \"AdditionalBootstrapServers\": {\n      \"@id\": \"aws:AdditionalBootstrapServers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServerRootCaCertificate\": {\n      \"@id\": \"aws:ServerRootCaCertificate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Vpc\": {\n      \"@id\": \"aws:Vpc\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeSourceSqsQueueParameters\": \"aws:PipeSourceSqsQueueParameters\",\n    \"PipeTargetBatchJobParameters\": \"aws:PipeTargetBatchJobParameters\",\n    \"ArrayProperties\": {\n      \"@id\": \"aws:ArrayProperties\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"DependsOn\": {\n      \"@id\": \"aws:DependsOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobDefinition\": {\n      \"@id\": \"aws:JobDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"JobName\": {\n      \"@id\": \"aws:JobName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Parameters\": {\n      \"@id\": \"aws:Parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RetryStrategy\": {\n      \"@id\": \"aws:RetryStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetCloudWatchLogsParameters\": \"aws:PipeTargetCloudWatchLogsParameters\",\n    \"LogStreamName\": {\n      \"@id\": \"aws:LogStreamName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamp\": {\n      \"@id\": \"aws:Timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetEcsTaskParameters\": \"aws:PipeTargetEcsTaskParameters\",\n    \"CapacityProviderStrategy\": {\n      \"@id\": \"aws:CapacityProviderStrategy\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"EnableECSManagedTags\": {\n      \"@id\": \"aws:EnableECSManagedTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableExecuteCommand\": {\n      \"@id\": \"aws:EnableExecuteCommand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Group\": {\n      \"@id\": \"aws:Group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchType\": {\n      \"@id\": \"aws:LaunchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Overrides\": {\n      \"@id\": \"aws:Overrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementConstraints\": {\n      \"@id\": \"aws:PlacementConstraints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementStrategy\": \"aws:PlacementStrategy\",\n    \"PlatformVersion\": {\n      \"@id\": \"aws:PlatformVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PropagateTags\": {\n      \"@id\": \"aws:PropagateTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReferenceId\": {\n      \"@id\": \"aws:ReferenceId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskCount\": {\n      \"@id\": \"aws:TaskCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskDefinitionArn\": {\n      \"@id\": \"aws:TaskDefinitionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetEventBridgeEventBusParameters\": \"aws:PipeTargetEventBridgeEventBusParameters\",\n    \"DetailType\": {\n      \"@id\": \"aws:DetailType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndpointId\": {\n      \"@id\": \"aws:EndpointId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Resources\": {\n      \"@id\": \"aws:Resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Time\": {\n      \"@id\": \"aws:Time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetHttpParameters\": \"aws:PipeTargetHttpParameters\",\n    \"PipeTargetKinesisStreamParameters\": \"aws:PipeTargetKinesisStreamParameters\",\n    \"PartitionKey\": {\n      \"@id\": \"aws:PartitionKey\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"PipeTargetLambdaFunctionParameters\": \"aws:PipeTargetLambdaFunctionParameters\",\n    \"InvocationType\": {\n      \"@id\": \"aws:InvocationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetParameters\": \"aws:PipeTargetParameters\",\n    \"BatchJobParameters\": {\n      \"@id\": \"aws:BatchJobParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CloudWatchLogsParameters\": {\n      \"@id\": \"aws:CloudWatchLogsParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EcsTaskParameters\": {\n      \"@id\": \"aws:EcsTaskParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventBridgeEventBusParameters\": {\n      \"@id\": \"aws:EventBridgeEventBusParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LambdaFunctionParameters\": {\n      \"@id\": \"aws:LambdaFunctionParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RedshiftDataParameters\": {\n      \"@id\": \"aws:RedshiftDataParameters\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"SageMakerPipelineParameters\": {\n      \"@id\": \"aws:SageMakerPipelineParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StepFunctionStateMachineParameters\": {\n      \"@id\": \"aws:StepFunctionStateMachineParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetRedshiftDataParameters\": \"aws:PipeTargetRedshiftDataParameters\",\n    \"Database\": {\n      \"@id\": \"aws:Database\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DbUser\": {\n      \"@id\": \"aws:DbUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecretManagerArn\": {\n      \"@id\": \"aws:SecretManagerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Sqls\": {\n      \"@id\": \"aws:Sqls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatementName\": {\n      \"@id\": \"aws:StatementName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WithEvent\": {\n      \"@id\": \"aws:WithEvent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetSageMakerPipelineParameters\"\
  : \"aws:PipeTargetSageMakerPipelineParameters\",\n    \"PipelineParameterList\": {\n      \"@id\": \"aws:PipelineParameterList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetSqsQueueParameters\": \"aws:PipeTargetSqsQueueParameters\",\n    \"MessageDeduplicationId\": {\n      \"@id\": \"aws:MessageDeduplicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MessageGroupId\": {\n      \"@id\": \"aws:MessageGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PipeTargetStateMachineParameters\": \"aws:PipeTargetStateMachineParameters\",\n    \"PlacementConstraint\": \"aws:PlacementConstraint\",\n    \"expression\": {\n      \"@id\": \"aws:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"aws:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QueryStringParametersMap\": \"aws:QueryStringParametersMap\",\n    \"SageMakerPipelineParameter\": \"aws:SageMakerPipelineParameter\",\n    \"SelfManagedKafkaAccessConfigurationCredentials\"\
  : \"aws:SelfManagedKafkaAccessConfigurationCredentials\",\n    \"SaslScram256Auth\": {\n      \"@id\": \"aws:SaslScram256Auth\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SelfManagedKafkaAccessConfigurationVpc\": \"aws:SelfManagedKafkaAccessConfigurationVpc\",\n    \"SecurityGroup\": {\n      \"@id\": \"aws:SecurityGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartPipeRequest\": \"aws:StartPipeRequest\",\n    \"StartPipeResponse\": \"aws:StartPipeResponse\",\n    \"StopPipeRequest\": \"aws:StopPipeRequest\",\n    \"StopPipeResponse\": \"aws:StopPipeResponse\",\n    \"TagMap\": \"aws:TagMap\",\n    \"TagResourceRequest\": \"aws:TagResourceRequest\",\n    \"TagResourceResponse\": \"aws:TagResourceResponse\",\n    \"Tag\": \"aws:Tag\",\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UntagResourceRequest\": \"aws:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"aws:UntagResourceResponse\",\n    \"UpdatePipeRequest\": \"\
  aws:UpdatePipeRequest\",\n    \"UpdatePipeResponse\": \"aws:UpdatePipeResponse\",\n    \"UpdatePipeSourceActiveMQBrokerParameters\": \"aws:UpdatePipeSourceActiveMQBrokerParameters\",\n    \"UpdatePipeSourceDynamoDBStreamParameters\": \"aws:UpdatePipeSourceDynamoDBStreamParameters\",\n    \"UpdatePipeSourceKinesisStreamParameters\": \"aws:UpdatePipeSourceKinesisStreamParameters\",\n    \"UpdatePipeSourceManagedStreamingKafkaParameters\": \"aws:UpdatePipeSourceManagedStreamingKafkaParameters\",\n    \"UpdatePipeSourceParameters\": \"aws:UpdatePipeSourceParameters\",\n    \"UpdatePipeSourceRabbitMQBrokerParameters\": \"aws:UpdatePipeSourceRabbitMQBrokerParameters\",\n    \"UpdatePipeSourceSelfManagedKafkaParameters\": \"aws:UpdatePipeSourceSelfManagedKafkaParameters\",\n    \"UpdatePipeSourceSqsQueueParameters\": \"aws:UpdatePipeSourceSqsQueueParameters\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-pipes/refs/heads/main/json-ld/amazon-eventbridge-pipes-context.jsonld
tags:
- Amazon Web Services
- AWS
- Event-Driven
- Integration
- Messaging
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
