---
api_specs:
- filename: amazon-ec2-auto-scaling-openapi.yaml
  format: yaml
  label: Amazon EC2 Auto Scaling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-auto-scaling/refs/heads/main/openapi/amazon-ec2-auto-scaling-openapi.yaml
class_count: 48
classes:
- AcceleratorCountRequest
- AcceleratorTotalMemoryMiBRequest
- ActivitiesType
- Activity
- ActivityType
- Alarm
- AttachInstancesQuery
- AttachLoadBalancerTargetGroupsResultType
- AttachLoadBalancerTargetGroupsType
- AttachLoadBalancersResultType
- AttachLoadBalancersType
- AttachTrafficSourcesResultType
- AttachTrafficSourcesType
- AutoScalingGroup
- AutoScalingGroupNamesType
- AutoScalingGroupsType
- AutoScalingInstanceDetails
- AutoScalingInstancesType
- BaselineEbsBandwidthMbpsRequest
- BatchDeleteScheduledActionAnswer
- BatchDeleteScheduledActionType
- BatchPutScheduledUpdateGroupActionAnswer
- BatchPutScheduledUpdateGroupActionType
- BlockDeviceMapping
- CancelInstanceRefreshAnswer
- CancelInstanceRefreshType
- CapacityForecast
- CompleteLifecycleActionAnswer
- CompleteLifecycleActionType
- CreateAutoScalingGroupType
- CreateLaunchConfigurationType
- CreateOrUpdateTagsType
- DeleteAutoScalingGroupType
- DeleteLifecycleHookAnswer
- DeleteLifecycleHookType
- DeleteNotificationConfigurationType
- DeletePolicyType
- DeleteScheduledActionType
- DeleteTagsType
- DeleteWarmPoolAnswer
- DeleteWarmPoolType
- DescribeAccountLimitsAnswer
- DescribeAdjustmentTypesAnswer
- DescribeAutoScalingInstancesType
- DescribeAutoScalingNotificationTypesAnswer
- DescribeInstanceRefreshesAnswer
- DescribeInstanceRefreshesType
- DescribeLifecycleHookTypesAnswer
context_file: json-ld/amazon-ec2-auto-scaling-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-auto-scaling/refs/heads/main/json-ld/amazon-ec2-auto-scaling-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ec2 Auto Scaling from Amazon EC2 Auto Scaling.
layout: jsonld
name: Amazon Ec2 Auto Scaling Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: pan
  uri: https://aws.amazon.com/schema/
properties:
- container: ''
  name: AdjustmentType
  type: string
- container: ''
  name: CustomizedMetricSpecification
  type: string
- container: ''
  name: MetricSpecifications
  type: string
- container: ''
  name: Mode
  type: string
- container: ''
  name: SchedulingBufferTime
  type: string
- container: ''
  name: MaxCapacityBreachBehavior
  type: string
- container: ''
  name: MaxCapacityBuffer
  type: string
- container: ''
  name: LifecycleHookName
  type: string
- container: ''
  name: LifecycleTransition
  type: string
- container: ''
  name: NotificationMetadata
  type: string
- container: ''
  name: HeartbeatTimeout
  type: string
- container: ''
  name: DefaultResult
  type: string
- container: ''
  name: NotificationTargetARN
  type: string
- container: ''
  name: RoleARN
  type: string
- container: ''
  name: PolicyARN
  type: string
- container: ''
  name: Alarms
  type: string
- container: ''
  name: AutoScalingGroupName
  type: string
- container: ''
  name: PolicyName
  type: string
- container: ''
  name: PercentageComplete
  type: string
- container: ''
  name: InstancesToUpdate
  type: string
- container: ''
  name: MetricIntervalLowerBound
  type: string
- container: ''
  name: MetricIntervalUpperBound
  type: string
- container: ''
  name: ScalingAdjustment
  type: string
- container: ''
  name: MetricDataQueries
  type: string
- container: ''
  name: LoadBalancers
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: PolicyNames
  type: string
- container: ''
  name: PolicyTypes
  type: string
- container: ''
  name: MaxRecords
  type: string
- container: ''
  name: AdjustmentTypes
  type: string
- container: ''
  name: Min
  type: string
- container: ''
  name: Max
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: TrafficSourceType
  type: string
- container: ''
  name: MetricName
  type: string
- container: ''
  name: Namespace
  type: string
- container: ''
  name: Dimensions
  type: string
- container: ''
  name: Statistic
  type: string
- container: ''
  name: Unit
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: Activities
  type: string
- container: ''
  name: LaunchTemplate
  type: string
- container: ''
  name: InstancesDistribution
  type: string
- container: ''
  name: Granularity
  type: string
- container: ''
  name: LifecycleHookNames
  type: string
- container: ''
  name: LaunchConfigurations
  type: string
- container: ''
  name: InstanceId
  type: string
- container: ''
  name: ShouldDecrementDesiredCapacity
  type: string
- container: ''
  name: ScheduledUpdateGroupActions
  type: string
- container: ''
  name: MinHealthyPercentage
  type: string
- container: ''
  name: InstanceWarmup
  type: string
- container: ''
  name: CheckpointPercentages
  type: string
- container: ''
  name: CheckpointDelay
  type: string
- container: ''
  name: SkipMatching
  type: string
- container: ''
  name: AutoRollback
  type: string
- container: ''
  name: ScaleInProtectedInstances
  type: string
- container: ''
  name: StandbyInstances
  type: string
- container: ''
  name: Metric
  type: string
- container: ''
  name: Stat
  type: string
- container: ''
  name: AutoScalingInstances
  type: string
- container: ''
  name: InstanceType
  type: string
- container: ''
  name: WeightedCapacity
  type: string
- container: ''
  name: LaunchTemplateSpecification
  type: string
- container: ''
  name: InstanceRequirements
  type: string
- container: ''
  name: LoadBalancerName
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: LoadBalancerTargetGroupARN
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Strategy
  type: string
- container: ''
  name: DesiredConfiguration
  type: string
- container: ''
  name: Preferences
  type: string
- container: ''
  name: Timestamps
  type: string
- container: ''
  name: Values
  type: string
- container: ''
  name: InstanceRefreshId
  type: string
- container: ''
  name: TrafficSource
  type: string
- container: ''
  name: Identifier
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: TopicARN
  type: string
- container: ''
  name: ScheduledActionName
  type: string
- container: ''
  name: Time
  type: string
- container: ''
  name: StartTime
  type: string
- container: ''
  name: EndTime
  type: string
- container: ''
  name: Recurrence
  type: string
- container: ''
  name: MinSize
  type: string
- container: ''
  name: MaxSize
  type: string
- container: ''
  name: DesiredCapacity
  type: string
- container: ''
  name: TimeZone
  type: string
- container: ''
  name: OnDemandAllocationStrategy
  type: string
- container: ''
  name: OnDemandBaseCapacity
  type: string
- container: ''
  name: OnDemandPercentageAboveBaseCapacity
  type: string
- container: ''
  name: SpotAllocationStrategy
  type: string
- container: ''
  name: SpotInstancePools
  type: string
- container: ''
  name: SpotMaxPrice
  type: string
- container: ''
  name: LaunchConfigurationName
  type: string
- container: ''
  name: MixedInstancesPolicy
  type: string
- container: ''
  name: DefaultCooldown
  type: string
- container: ''
  name: AvailabilityZones
  type: string
- container: ''
  name: HealthCheckType
  type: string
- container: ''
  name: HealthCheckGracePeriod
  type: string
- container: ''
  name: PlacementGroup
  type: string
- container: ''
  name: VPCZoneIdentifier
  type: string
- container: ''
  name: TerminationPolicies
  type: string
- container: ''
  name: NewInstancesProtectedFromScaleIn
  type: string
- container: ''
  name: ServiceLinkedRoleARN
  type: string
- container: ''
  name: MaxInstanceLifetime
  type: string
- container: ''
  name: CapacityRebalance
  type: string
- container: ''
  name: Context
  type: string
- container: ''
  name: DesiredCapacityType
  type: string
- container: ''
  name: DefaultInstanceWarmup
  type: string
- container: ''
  name: LoadBalancerNames
  type: string
- container: ''
  name: FailedScheduledActions
  type: string
- container: ''
  name: VirtualName
  type: string
- container: ''
  name: DeviceName
  type: string
- container: ''
  name: Ebs
  type: string
- container: ''
  name: NoDevice
  type: string
- container: ''
  name: Enabled
  type: string
- container: ''
  name: ScheduledActionARN
  type: string
- container: ''
  name: LifecycleHookTypes
  type: string
- container: ''
  name: InstanceIds
  type: string
- container: ''
  name: WarmPoolConfiguration
  type: string
- container: ''
  name: Instances
  type: string
- container: ''
  name: FailedScheduledUpdateGroupActions
  type: string
- container: ''
  name: MetricSpecification
  type: string
- container: ''
  name: LoadBalancerTargetGroups
  type: string
- container: ''
  name: PolicyType
  type: string
- container: ''
  name: MinAdjustmentStep
  type: string
- container: ''
  name: MinAdjustmentMagnitude
  type: string
- container: ''
  name: Cooldown
  type: string
- container: ''
  name: MetricAggregationType
  type: string
- container: ''
  name: StepAdjustments
  type: string
- container: ''
  name: EstimatedInstanceWarmup
  type: string
- container: ''
  name: TargetTrackingConfiguration
  type: string
- container: ''
  name: PredictiveScalingConfiguration
  type: string
- container: ''
  name: PredefinedMetricSpecification
  type: string
- container: ''
  name: TargetValue
  type: string
- container: ''
  name: DisableScaleIn
  type: string
- container: ''
  name: Overrides
  type: string
- container: ''
  name: PredefinedMetricType
  type: string
- container: ''
  name: ResourceLabel
  type: string
- container: ''
  name: ReuseOnScaleIn
  type: string
- container: ''
  name: ResourceId
  type: string
- container: ''
  name: ResourceType
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: PropagateAtLaunch
  type: string
- container: ''
  name: LaunchConfigurationARN
  type: string
- container: ''
  name: ImageId
  type: string
- container: ''
  name: KeyName
  type: string
- container: ''
  name: SecurityGroups
  type: string
- container: ''
  name: ClassicLinkVPCId
  type: string
- container: ''
  name: ClassicLinkVPCSecurityGroups
  type: string
- container: ''
  name: UserData
  type: string
- container: ''
  name: KernelId
  type: string
- container: ''
  name: RamdiskId
  type: string
- container: ''
  name: BlockDeviceMappings
  type: string
- container: ''
  name: InstanceMonitoring
  type: string
- container: ''
  name: SpotPrice
  type: string
- container: ''
  name: IamInstanceProfile
  type: string
- container: ''
  name: CreatedTime
  type: string
- container: ''
  name: EbsOptimized
  type: string
- container: ''
  name: AssociatePublicIpAddress
  type: string
- container: ''
  name: PlacementTenancy
  type: string
- container: ''
  name: MetadataOptions
  type: string
- container: ''
  name: ScheduledActionNames
  type: string
- container: ''
  name: LifecycleActionToken
  type: string
- container: ''
  name: LifecycleActionResult
  type: string
- container: ''
  name: ActivityIds
  type: string
- container: ''
  name: IncludeDeletedGroups
  type: string
- container: ''
  name: TrafficSources
  type: string
- container: ''
  name: RollbackReason
  type: string
- container: ''
  name: RollbackStartTime
  type: string
- container: ''
  name: PercentageCompleteOnRollback
  type: string
- container: ''
  name: InstancesToUpdateOnRollback
  type: string
- container: ''
  name: ProgressDetailsOnRollback
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: StatusReason
  type: string
- container: ''
  name: ProgressDetails
  type: string
- container: ''
  name: RollbackDetails
  type: string
- container: ''
  name: InstanceRefreshes
  type: string
- container: ''
  name: TargetGroupARNs
  type: string
- container: ''
  name: ErrorCode
  type: string
- container: ''
  name: ErrorMessage
  type: string
- container: ''
  name: AutoScalingGroupARN
  type: string
- container: ''
  name: PredictedCapacity
  type: string
- container: ''
  name: SuspendedProcesses
  type: string
- container: ''
  name: EnabledMetrics
  type: string
- container: ''
  name: WarmPoolSize
  type: string
- container: ''
  name: LaunchTemplateId
  type: string
- container: ''
  name: LaunchTemplateName
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Processes
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Expression
  type: string
- container: ''
  name: MetricStat
  type: string
- container: ''
  name: Label
  type: string
- container: ''
  name: ReturnData
  type: string
- container: ''
  name: HonorCooldown
  type: string
- container: ''
  name: MetricValue
  type: string
- container: ''
  name: BreachThreshold
  type: string
- container: ''
  name: LivePoolProgress
  type: string
property_count: 200
provider_name: Amazon EC2 Auto Scaling
provider_slug: amazon-ec2-auto-scaling
slug: amazon-ec2-auto-scaling-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"AcceleratorCountRequest\": \"aws:AcceleratorCountRequest\",\n    \"AcceleratorTotalMemoryMiBRequest\": \"aws:AcceleratorTotalMemoryMiBRequest\",\n    \"ActivitiesType\": \"aws:ActivitiesType\",\n    \"Activity\": \"aws:Activity\",\n    \"ActivityType\": \"aws:ActivityType\",\n    \"AdjustmentType\": {\n      \"@id\": \"pan:AdjustmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Alarm\": \"aws:Alarm\",\n    \"AttachInstancesQuery\": \"aws:AttachInstancesQuery\",\n    \"AttachLoadBalancerTargetGroupsResultType\": \"aws:AttachLoadBalancerTargetGroupsResultType\",\n    \"AttachLoadBalancerTargetGroupsType\": \"aws:AttachLoadBalancerTargetGroupsType\",\n    \"AttachLoadBalancersResultType\"\
  : \"aws:AttachLoadBalancersResultType\",\n    \"AttachLoadBalancersType\": \"aws:AttachLoadBalancersType\",\n    \"AttachTrafficSourcesResultType\": \"aws:AttachTrafficSourcesResultType\",\n    \"AttachTrafficSourcesType\": \"aws:AttachTrafficSourcesType\",\n    \"AutoScalingGroup\": \"aws:AutoScalingGroup\",\n    \"AutoScalingGroupNamesType\": \"aws:AutoScalingGroupNamesType\",\n    \"AutoScalingGroupsType\": \"aws:AutoScalingGroupsType\",\n    \"AutoScalingInstanceDetails\": \"aws:AutoScalingInstanceDetails\",\n    \"AutoScalingInstancesType\": \"aws:AutoScalingInstancesType\",\n    \"BaselineEbsBandwidthMbpsRequest\": \"aws:BaselineEbsBandwidthMbpsRequest\",\n    \"BatchDeleteScheduledActionAnswer\": \"aws:BatchDeleteScheduledActionAnswer\",\n    \"BatchDeleteScheduledActionType\": \"aws:BatchDeleteScheduledActionType\",\n    \"BatchPutScheduledUpdateGroupActionAnswer\": \"aws:BatchPutScheduledUpdateGroupActionAnswer\",\n    \"BatchPutScheduledUpdateGroupActionType\": \"aws:BatchPutScheduledUpdateGroupActionType\"\
  ,\n    \"BlockDeviceMapping\": \"aws:BlockDeviceMapping\",\n    \"CancelInstanceRefreshAnswer\": \"aws:CancelInstanceRefreshAnswer\",\n    \"CancelInstanceRefreshType\": \"aws:CancelInstanceRefreshType\",\n    \"CapacityForecast\": \"aws:CapacityForecast\",\n    \"CompleteLifecycleActionAnswer\": \"aws:CompleteLifecycleActionAnswer\",\n    \"CompleteLifecycleActionType\": \"aws:CompleteLifecycleActionType\",\n    \"CreateAutoScalingGroupType\": \"aws:CreateAutoScalingGroupType\",\n    \"CreateLaunchConfigurationType\": \"aws:CreateLaunchConfigurationType\",\n    \"CreateOrUpdateTagsType\": \"aws:CreateOrUpdateTagsType\",\n    \"CustomizedMetricSpecification\": {\n      \"@id\": \"pan:CustomizedMetricSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteAutoScalingGroupType\": \"aws:DeleteAutoScalingGroupType\",\n    \"DeleteLifecycleHookAnswer\": \"aws:DeleteLifecycleHookAnswer\",\n    \"DeleteLifecycleHookType\": \"aws:DeleteLifecycleHookType\",\n    \"DeleteNotificationConfigurationType\"\
  : \"aws:DeleteNotificationConfigurationType\",\n    \"DeletePolicyType\": \"aws:DeletePolicyType\",\n    \"DeleteScheduledActionType\": \"aws:DeleteScheduledActionType\",\n    \"DeleteTagsType\": \"aws:DeleteTagsType\",\n    \"DeleteWarmPoolAnswer\": \"aws:DeleteWarmPoolAnswer\",\n    \"DeleteWarmPoolType\": \"aws:DeleteWarmPoolType\",\n    \"DescribeAccountLimitsAnswer\": \"aws:DescribeAccountLimitsAnswer\",\n    \"DescribeAdjustmentTypesAnswer\": \"aws:DescribeAdjustmentTypesAnswer\",\n    \"DescribeAutoScalingInstancesType\": \"aws:DescribeAutoScalingInstancesType\",\n    \"DescribeAutoScalingNotificationTypesAnswer\": \"aws:DescribeAutoScalingNotificationTypesAnswer\",\n    \"DescribeInstanceRefreshesAnswer\": \"aws:DescribeInstanceRefreshesAnswer\",\n    \"DescribeInstanceRefreshesType\": \"aws:DescribeInstanceRefreshesType\",\n    \"DescribeLifecycleHookTypesAnswer\": \"aws:DescribeLifecycleHookTypesAnswer\",\n    \"MetricSpecifications\": {\n      \"@id\": \"pan:MetricSpecifications\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Mode\": {\n      \"@id\": \"pan:Mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SchedulingBufferTime\": {\n      \"@id\": \"pan:SchedulingBufferTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxCapacityBreachBehavior\": {\n      \"@id\": \"pan:MaxCapacityBreachBehavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxCapacityBuffer\": {\n      \"@id\": \"pan:MaxCapacityBuffer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleHookName\": {\n      \"@id\": \"pan:LifecycleHookName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleTransition\": {\n      \"@id\": \"pan:LifecycleTransition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotificationMetadata\": {\n      \"@id\": \"pan:NotificationMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HeartbeatTimeout\": {\n      \"@id\": \"pan:HeartbeatTimeout\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultResult\": {\n      \"@id\"\
  : \"pan:DefaultResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NotificationTargetARN\": {\n      \"@id\": \"pan:NotificationTargetARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleARN\": {\n      \"@id\": \"pan:RoleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyARN\": {\n      \"@id\": \"pan:PolicyARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Alarms\": {\n      \"@id\": \"pan:Alarms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoScalingGroupName\": {\n      \"@id\": \"pan:AutoScalingGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyName\": {\n      \"@id\": \"pan:PolicyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PercentageComplete\": {\n      \"@id\": \"pan:PercentageComplete\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstancesToUpdate\": {\n      \"@id\": \"pan:InstancesToUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricIntervalLowerBound\": {\n      \"@id\": \"pan:MetricIntervalLowerBound\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricIntervalUpperBound\": {\n      \"@id\": \"pan:MetricIntervalUpperBound\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScalingAdjustment\": {\n      \"@id\": \"pan:ScalingAdjustment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricDataQueries\": {\n      \"@id\": \"pan:MetricDataQueries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancers\": {\n      \"@id\": \"pan:LoadBalancers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"pan:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyNames\": {\n      \"@id\": \"pan:PolicyNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyTypes\": {\n      \"@id\": \"pan:PolicyTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxRecords\": {\n      \"@id\": \"pan:MaxRecords\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdjustmentTypes\": {\n      \"@id\": \"pan:AdjustmentTypes\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Min\": {\n      \"@id\": \"pan:Min\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Max\": {\n      \"@id\": \"pan:Max\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"pan:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrafficSourceType\": {\n      \"@id\": \"pan:TrafficSourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricName\": {\n      \"@id\": \"pan:MetricName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Namespace\": {\n      \"@id\": \"pan:Namespace\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Dimensions\": {\n      \"@id\": \"pan:Dimensions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Statistic\": {\n      \"@id\": \"pan:Statistic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Unit\": {\n      \"@id\": \"pan:Unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"pan:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Value\": {\n      \"@id\": \"pan:Value\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Activities\": {\n      \"@id\": \"pan:Activities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchTemplate\": {\n      \"@id\": \"pan:LaunchTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstancesDistribution\": {\n      \"@id\": \"pan:InstancesDistribution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Granularity\": {\n      \"@id\": \"pan:Granularity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleHookNames\": {\n      \"@id\": \"pan:LifecycleHookNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchConfigurations\": {\n      \"@id\": \"pan:LaunchConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceId\": {\n      \"@id\": \"pan:InstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShouldDecrementDesiredCapacity\": {\n      \"@id\": \"pan:ShouldDecrementDesiredCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduledUpdateGroupActions\": {\n      \"\
  @id\": \"pan:ScheduledUpdateGroupActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinHealthyPercentage\": {\n      \"@id\": \"pan:MinHealthyPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceWarmup\": {\n      \"@id\": \"pan:InstanceWarmup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckpointPercentages\": {\n      \"@id\": \"pan:CheckpointPercentages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckpointDelay\": {\n      \"@id\": \"pan:CheckpointDelay\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SkipMatching\": {\n      \"@id\": \"pan:SkipMatching\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoRollback\": {\n      \"@id\": \"pan:AutoRollback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScaleInProtectedInstances\": {\n      \"@id\": \"pan:ScaleInProtectedInstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StandbyInstances\": {\n      \"@id\": \"pan:StandbyInstances\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"Metric\": {\n      \"@id\": \"pan:Metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Stat\": {\n      \"@id\": \"pan:Stat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoScalingInstances\": {\n      \"@id\": \"pan:AutoScalingInstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceType\": {\n      \"@id\": \"pan:InstanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WeightedCapacity\": {\n      \"@id\": \"pan:WeightedCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchTemplateSpecification\": {\n      \"@id\": \"pan:LaunchTemplateSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceRequirements\": {\n      \"@id\": \"pan:InstanceRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancerName\": {\n      \"@id\": \"pan:LoadBalancerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"pan:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancerTargetGroupARN\"\
  : {\n      \"@id\": \"pan:LoadBalancerTargetGroupARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"pan:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Strategy\": {\n      \"@id\": \"pan:Strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredConfiguration\": {\n      \"@id\": \"pan:DesiredConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Preferences\": {\n      \"@id\": \"pan:Preferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Timestamps\": {\n      \"@id\": \"pan:Timestamps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Values\": {\n      \"@id\": \"pan:Values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceRefreshId\": {\n      \"@id\": \"pan:InstanceRefreshId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrafficSource\": {\n      \"@id\": \"pan:TrafficSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Identifier\": {\n      \"@id\": \"pan:Identifier\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"Type\": {\n      \"@id\": \"pan:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TopicARN\": {\n      \"@id\": \"pan:TopicARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduledActionName\": {\n      \"@id\": \"pan:ScheduledActionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Time\": {\n      \"@id\": \"pan:Time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"pan:StartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndTime\": {\n      \"@id\": \"pan:EndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Recurrence\": {\n      \"@id\": \"pan:Recurrence\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinSize\": {\n      \"@id\": \"pan:MinSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxSize\": {\n      \"@id\": \"pan:MaxSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredCapacity\": {\n      \"@id\": \"pan:DesiredCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TimeZone\"\
  : {\n      \"@id\": \"pan:TimeZone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OnDemandAllocationStrategy\": {\n      \"@id\": \"pan:OnDemandAllocationStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OnDemandBaseCapacity\": {\n      \"@id\": \"pan:OnDemandBaseCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OnDemandPercentageAboveBaseCapacity\": {\n      \"@id\": \"pan:OnDemandPercentageAboveBaseCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpotAllocationStrategy\": {\n      \"@id\": \"pan:SpotAllocationStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpotInstancePools\": {\n      \"@id\": \"pan:SpotInstancePools\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpotMaxPrice\": {\n      \"@id\": \"pan:SpotMaxPrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchConfigurationName\": {\n      \"@id\": \"pan:LaunchConfigurationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MixedInstancesPolicy\": {\n      \"@id\": \"\
  pan:MixedInstancesPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultCooldown\": {\n      \"@id\": \"pan:DefaultCooldown\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AvailabilityZones\": {\n      \"@id\": \"pan:AvailabilityZones\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HealthCheckType\": {\n      \"@id\": \"pan:HealthCheckType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HealthCheckGracePeriod\": {\n      \"@id\": \"pan:HealthCheckGracePeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementGroup\": {\n      \"@id\": \"pan:PlacementGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VPCZoneIdentifier\": {\n      \"@id\": \"pan:VPCZoneIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TerminationPolicies\": {\n      \"@id\": \"pan:TerminationPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NewInstancesProtectedFromScaleIn\": {\n      \"@id\": \"pan:NewInstancesProtectedFromScaleIn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ServiceLinkedRoleARN\": {\n      \"@id\": \"pan:ServiceLinkedRoleARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxInstanceLifetime\": {\n      \"@id\": \"pan:MaxInstanceLifetime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CapacityRebalance\": {\n      \"@id\": \"pan:CapacityRebalance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Context\": {\n      \"@id\": \"pan:Context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DesiredCapacityType\": {\n      \"@id\": \"pan:DesiredCapacityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DefaultInstanceWarmup\": {\n      \"@id\": \"pan:DefaultInstanceWarmup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancerNames\": {\n      \"@id\": \"pan:LoadBalancerNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailedScheduledActions\": {\n      \"@id\": \"pan:FailedScheduledActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VirtualName\": {\n      \"@id\": \"pan:VirtualName\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"DeviceName\": {\n      \"@id\": \"pan:DeviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Ebs\": {\n      \"@id\": \"pan:Ebs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NoDevice\": {\n      \"@id\": \"pan:NoDevice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Enabled\": {\n      \"@id\": \"pan:Enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduledActionARN\": {\n      \"@id\": \"pan:ScheduledActionARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleHookTypes\": {\n      \"@id\": \"pan:LifecycleHookTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceIds\": {\n      \"@id\": \"pan:InstanceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WarmPoolConfiguration\": {\n      \"@id\": \"pan:WarmPoolConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Instances\": {\n      \"@id\": \"pan:Instances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FailedScheduledUpdateGroupActions\"\
  : {\n      \"@id\": \"pan:FailedScheduledUpdateGroupActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricSpecification\": {\n      \"@id\": \"pan:MetricSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LoadBalancerTargetGroups\": {\n      \"@id\": \"pan:LoadBalancerTargetGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PolicyType\": {\n      \"@id\": \"pan:PolicyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinAdjustmentStep\": {\n      \"@id\": \"pan:MinAdjustmentStep\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinAdjustmentMagnitude\": {\n      \"@id\": \"pan:MinAdjustmentMagnitude\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Cooldown\": {\n      \"@id\": \"pan:Cooldown\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricAggregationType\": {\n      \"@id\": \"pan:MetricAggregationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StepAdjustments\": {\n      \"@id\": \"pan:StepAdjustments\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"EstimatedInstanceWarmup\": {\n      \"@id\": \"pan:EstimatedInstanceWarmup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetTrackingConfiguration\": {\n      \"@id\": \"pan:TargetTrackingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredictiveScalingConfiguration\": {\n      \"@id\": \"pan:PredictiveScalingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredefinedMetricSpecification\": {\n      \"@id\": \"pan:PredefinedMetricSpecification\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetValue\": {\n      \"@id\": \"pan:TargetValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisableScaleIn\": {\n      \"@id\": \"pan:DisableScaleIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Overrides\": {\n      \"@id\": \"pan:Overrides\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredefinedMetricType\": {\n      \"@id\": \"pan:PredefinedMetricType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceLabel\": {\n\
  \      \"@id\": \"pan:ResourceLabel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReuseOnScaleIn\": {\n      \"@id\": \"pan:ReuseOnScaleIn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceId\": {\n      \"@id\": \"pan:ResourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ResourceType\": {\n      \"@id\": \"pan:ResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Key\": {\n      \"@id\": \"pan:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PropagateAtLaunch\": {\n      \"@id\": \"pan:PropagateAtLaunch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchConfigurationARN\": {\n      \"@id\": \"pan:LaunchConfigurationARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImageId\": {\n      \"@id\": \"pan:ImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KeyName\": {\n      \"@id\": \"pan:KeyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroups\": {\n      \"@id\": \"pan:SecurityGroups\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"ClassicLinkVPCId\": {\n      \"@id\": \"pan:ClassicLinkVPCId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClassicLinkVPCSecurityGroups\": {\n      \"@id\": \"pan:ClassicLinkVPCSecurityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserData\": {\n      \"@id\": \"pan:UserData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KernelId\": {\n      \"@id\": \"pan:KernelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RamdiskId\": {\n      \"@id\": \"pan:RamdiskId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BlockDeviceMappings\": {\n      \"@id\": \"pan:BlockDeviceMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceMonitoring\": {\n      \"@id\": \"pan:InstanceMonitoring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpotPrice\": {\n      \"@id\": \"pan:SpotPrice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IamInstanceProfile\": {\n      \"@id\": \"pan:IamInstanceProfile\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"CreatedTime\": {\n      \"@id\": \"pan:CreatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EbsOptimized\": {\n      \"@id\": \"pan:EbsOptimized\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociatePublicIpAddress\": {\n      \"@id\": \"pan:AssociatePublicIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementTenancy\": {\n      \"@id\": \"pan:PlacementTenancy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetadataOptions\": {\n      \"@id\": \"pan:MetadataOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduledActionNames\": {\n      \"@id\": \"pan:ScheduledActionNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleActionToken\": {\n      \"@id\": \"pan:LifecycleActionToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LifecycleActionResult\": {\n      \"@id\": \"pan:LifecycleActionResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ActivityIds\": {\n      \"@id\": \"pan:ActivityIds\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"IncludeDeletedGroups\": {\n      \"@id\": \"pan:IncludeDeletedGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TrafficSources\": {\n      \"@id\": \"pan:TrafficSources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RollbackReason\": {\n      \"@id\": \"pan:RollbackReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RollbackStartTime\": {\n      \"@id\": \"pan:RollbackStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PercentageCompleteOnRollback\": {\n      \"@id\": \"pan:PercentageCompleteOnRollback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstancesToUpdateOnRollback\": {\n      \"@id\": \"pan:InstancesToUpdateOnRollback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProgressDetailsOnRollback\": {\n      \"@id\": \"pan:ProgressDetailsOnRollback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"pan:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StatusReason\": {\n      \"@id\": \"pan:StatusReason\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ProgressDetails\": {\n      \"@id\": \"pan:ProgressDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RollbackDetails\": {\n      \"@id\": \"pan:RollbackDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"InstanceRefreshes\": {\n      \"@id\": \"pan:InstanceRefreshes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetGroupARNs\": {\n      \"@id\": \"pan:TargetGroupARNs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"pan:ErrorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ErrorMessage\": {\n      \"@id\": \"pan:ErrorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AutoScalingGroupARN\": {\n      \"@id\": \"pan:AutoScalingGroupARN\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PredictedCapacity\": {\n      \"@id\": \"pan:PredictedCapacity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SuspendedProcesses\": {\n      \"@id\": \"pan:SuspendedProcesses\",\n  \
  \    \"@type\": \"xsd:string\"\n    },\n    \"EnabledMetrics\": {\n      \"@id\": \"pan:EnabledMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WarmPoolSize\": {\n      \"@id\": \"pan:WarmPoolSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchTemplateId\": {\n      \"@id\": \"pan:LaunchTemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchTemplateName\": {\n      \"@id\": \"pan:LaunchTemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"pan:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Processes\": {\n      \"@id\": \"pan:Processes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"pan:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Expression\": {\n      \"@id\": \"pan:Expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricStat\": {\n      \"@id\": \"pan:MetricStat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Label\": {\n      \"@id\": \"pan:Label\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ReturnData\": {\n      \"@id\": \"pan:ReturnData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HonorCooldown\": {\n      \"@id\": \"pan:HonorCooldown\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MetricValue\": {\n      \"@id\": \"pan:MetricValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BreachThreshold\": {\n      \"@id\": \"pan:BreachThreshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LivePoolProgress\": {\n      \"@id\": \"pan:LivePoolProgress\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-auto-scaling/refs/heads/main/json-ld/amazon-ec2-auto-scaling-context.jsonld
tags:
- Amazon Web Services
- Auto Scaling
- AWS
- Compute
- EC2
- High Availability
- Scaling
- JSON-LD
- Linked Data
- Semantic Web
---
