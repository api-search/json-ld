---
api_specs:
- filename: amazon-eventbridge-scheduler-openapi.yml
  format: yaml
  label: Amazon EventBridge Scheduler API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-scheduler/refs/heads/main/openapi/amazon-eventbridge-scheduler-openapi.yml
class_count: 44
classes:
- AwsVpcConfiguration
- CapacityProviderStrategyItem
- CreateScheduleGroupInput
- CreateScheduleGroupOutput
- CreateScheduleInput
- FlexibleTimeWindow
- Target
- CreateScheduleOutput
- DeadLetterConfig
- DeleteScheduleGroupInput
- DeleteScheduleGroupOutput
- DeleteScheduleInput
- DeleteScheduleOutput
- EcsParameters
- NetworkConfiguration
- PlacementStrategy
- EventBridgeParameters
- GetScheduleGroupInput
- GetScheduleGroupOutput
- GetScheduleInput
- GetScheduleOutput
- KinesisParameters
- ListScheduleGroupsInput
- ListScheduleGroupsOutput
- ListSchedulesInput
- ListSchedulesOutput
- ListTagsForResourceInput
- ListTagsForResourceOutput
- PlacementConstraint
- RetryPolicy
- SageMakerPipelineParameter
- SageMakerPipelineParameters
- ScheduleGroupSummary
- ScheduleSummary
- SqsParameters
- TagMap
- TagResourceInput
- TagResourceOutput
- Tag
- TargetSummary
- UntagResourceInput
- UntagResourceOutput
- UpdateScheduleInput
- UpdateScheduleOutput
context_file: json-ld/amazon-eventbridge-scheduler-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-scheduler/refs/heads/main/json-ld/amazon-eventbridge-scheduler-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Eventbridge Scheduler from Amazon EventBridge Scheduler.
layout: jsonld
name: Amazon Eventbridge Scheduler Context
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
  name: base
  type: string
- container: ''
  name: capacityProvider
  type: string
- container: ''
  name: weight
  type: string
- container: ''
  name: ClientToken
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: ScheduleGroupArn
  type: string
- container: ''
  name: ActionAfterCompletion
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: EndDate
  type: string
- container: ''
  name: GroupName
  type: string
- container: ''
  name: KmsKeyArn
  type: string
- container: ''
  name: ScheduleExpression
  type: string
- container: ''
  name: ScheduleExpressionTimezone
  type: string
- container: ''
  name: StartDate
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: ScheduleArn
  type: string
- container: ''
  name: Arn
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
  name: Source
  type: string
- container: ''
  name: MaximumWindowInMinutes
  type: string
- container: ''
  name: Mode
  type: string
- container: ''
  name: CreationDate
  type: string
- container: ''
  name: LastModificationDate
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: PartitionKey
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: ScheduleGroups
  type: string
- container: ''
  name: Schedules
  type: string
- container: ''
  name: awsvpcConfiguration
  type: string
- container: ''
  name: expression
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: field
  type: string
- container: ''
  name: MaximumEventAgeInSeconds
  type: string
- container: ''
  name: MaximumRetryAttempts
  type: string
- container: ''
  name: Value
  type: string
- container: ''
  name: PipelineParameterList
  type: string
- container: ''
  name: MessageGroupId
  type: string
- container: ''
  name: Key
  type: string
- container: ''
  name: Input
  type: string
- container: ''
  name: RoleArn
  type: string
property_count: 54
provider_name: Amazon EventBridge Scheduler
provider_slug: amazon-eventbridge-scheduler
slug: amazon-eventbridge-scheduler-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AwsVpcConfiguration\": \"aws:AwsVpcConfiguration\",\n    \"AssignPublicIp\": {\n      \"@id\": \"aws:AssignPublicIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SecurityGroups\": {\n      \"@id\": \"aws:SecurityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Subnets\": {\n      \"@id\": \"aws:Subnets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CapacityProviderStrategyItem\": \"aws:CapacityProviderStrategyItem\",\n    \"base\": {\n      \"@id\": \"aws:base\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capacityProvider\": {\n      \"@id\": \"aws:capacityProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"aws:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateScheduleGroupInput\"\
  : \"aws:CreateScheduleGroupInput\",\n    \"ClientToken\": {\n      \"@id\": \"aws:ClientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Tags\": {\n      \"@id\": \"aws:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateScheduleGroupOutput\": \"aws:CreateScheduleGroupOutput\",\n    \"ScheduleGroupArn\": {\n      \"@id\": \"aws:ScheduleGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateScheduleInput\": \"aws:CreateScheduleInput\",\n    \"ActionAfterCompletion\": {\n      \"@id\": \"aws:ActionAfterCompletion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"aws:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndDate\": {\n      \"@id\": \"aws:EndDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FlexibleTimeWindow\": \"aws:FlexibleTimeWindow\",\n    \"GroupName\": {\n      \"@id\": \"aws:GroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KmsKeyArn\": {\n      \"@id\": \"aws:KmsKeyArn\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleExpression\": {\n      \"@id\": \"aws:ScheduleExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleExpressionTimezone\": {\n      \"@id\": \"aws:ScheduleExpressionTimezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartDate\": {\n      \"@id\": \"aws:StartDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"aws:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Target\": \"aws:Target\",\n    \"CreateScheduleOutput\": \"aws:CreateScheduleOutput\",\n    \"ScheduleArn\": {\n      \"@id\": \"aws:ScheduleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeadLetterConfig\": \"aws:DeadLetterConfig\",\n    \"Arn\": {\n      \"@id\": \"aws:Arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteScheduleGroupInput\": \"aws:DeleteScheduleGroupInput\",\n    \"DeleteScheduleGroupOutput\": \"aws:DeleteScheduleGroupOutput\",\n    \"DeleteScheduleInput\": \"aws:DeleteScheduleInput\"\
  ,\n    \"DeleteScheduleOutput\": \"aws:DeleteScheduleOutput\",\n    \"EcsParameters\": \"aws:EcsParameters\",\n    \"CapacityProviderStrategy\": {\n      \"@id\": \"aws:CapacityProviderStrategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableECSManagedTags\": {\n      \"@id\": \"aws:EnableECSManagedTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnableExecuteCommand\": {\n      \"@id\": \"aws:EnableExecuteCommand\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Group\": {\n      \"@id\": \"aws:Group\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LaunchType\": {\n      \"@id\": \"aws:LaunchType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NetworkConfiguration\": \"aws:NetworkConfiguration\",\n    \"PlacementConstraints\": {\n      \"@id\": \"aws:PlacementConstraints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementStrategy\": \"aws:PlacementStrategy\",\n    \"PlatformVersion\": {\n      \"@id\": \"aws:PlatformVersion\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"PropagateTags\": {\n      \"@id\": \"aws:PropagateTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReferenceId\": {\n      \"@id\": \"aws:ReferenceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskCount\": {\n      \"@id\": \"aws:TaskCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TaskDefinitionArn\": {\n      \"@id\": \"aws:TaskDefinitionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventBridgeParameters\": \"aws:EventBridgeParameters\",\n    \"DetailType\": {\n      \"@id\": \"aws:DetailType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"aws:Source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumWindowInMinutes\": {\n      \"@id\": \"aws:MaximumWindowInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Mode\": {\n      \"@id\": \"aws:Mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetScheduleGroupInput\": \"aws:GetScheduleGroupInput\",\n    \"GetScheduleGroupOutput\": \"aws:GetScheduleGroupOutput\"\
  ,\n    \"CreationDate\": {\n      \"@id\": \"aws:CreationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastModificationDate\": {\n      \"@id\": \"aws:LastModificationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"aws:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetScheduleInput\": \"aws:GetScheduleInput\",\n    \"GetScheduleOutput\": \"aws:GetScheduleOutput\",\n    \"KinesisParameters\": \"aws:KinesisParameters\",\n    \"PartitionKey\": {\n      \"@id\": \"aws:PartitionKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListScheduleGroupsInput\": \"aws:ListScheduleGroupsInput\",\n    \"ListScheduleGroupsOutput\": \"aws:ListScheduleGroupsOutput\",\n    \"NextToken\": {\n      \"@id\": \"aws:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleGroups\": {\n      \"@id\": \"aws:ScheduleGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListSchedulesInput\": \"aws:ListSchedulesInput\",\n    \"ListSchedulesOutput\"\
  : \"aws:ListSchedulesOutput\",\n    \"Schedules\": {\n      \"@id\": \"aws:Schedules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"ListTagsForResourceOutput\": \"aws:ListTagsForResourceOutput\",\n    \"awsvpcConfiguration\": {\n      \"@id\": \"aws:awsvpcConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PlacementConstraint\": \"aws:PlacementConstraint\",\n    \"expression\": {\n      \"@id\": \"aws:expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"field\": {\n      \"@id\": \"aws:field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RetryPolicy\": \"aws:RetryPolicy\",\n    \"MaximumEventAgeInSeconds\": {\n      \"@id\": \"aws:MaximumEventAgeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaximumRetryAttempts\": {\n      \"@id\": \"aws:MaximumRetryAttempts\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"SageMakerPipelineParameter\": \"aws:SageMakerPipelineParameter\",\n    \"Value\": {\n      \"@id\": \"aws:Value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SageMakerPipelineParameters\": \"aws:SageMakerPipelineParameters\",\n    \"PipelineParameterList\": {\n      \"@id\": \"aws:PipelineParameterList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ScheduleGroupSummary\": \"aws:ScheduleGroupSummary\",\n    \"ScheduleSummary\": \"aws:ScheduleSummary\",\n    \"SqsParameters\": \"aws:SqsParameters\",\n    \"MessageGroupId\": {\n      \"@id\": \"aws:MessageGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagMap\": \"aws:TagMap\",\n    \"TagResourceInput\": \"aws:TagResourceInput\",\n    \"TagResourceOutput\": \"aws:TagResourceOutput\",\n    \"Tag\": \"aws:Tag\",\n    \"Key\": {\n      \"@id\": \"aws:Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Input\": {\n      \"@id\": \"aws:Input\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RoleArn\": {\n\
  \      \"@id\": \"aws:RoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetSummary\": \"aws:TargetSummary\",\n    \"UntagResourceInput\": \"aws:UntagResourceInput\",\n    \"UntagResourceOutput\": \"aws:UntagResourceOutput\",\n    \"UpdateScheduleInput\": \"aws:UpdateScheduleInput\",\n    \"UpdateScheduleOutput\": \"aws:UpdateScheduleOutput\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-eventbridge-scheduler/refs/heads/main/json-ld/amazon-eventbridge-scheduler-context.jsonld
tags:
- Amazon Web Services
- AWS
- Cron
- Event-Driven
- Scheduling
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
