---
class_count: 121
classes:
- DescribeMapRunInput
- DescribeMapRunOutput
- StartExecutionOutput
- ActivitySucceededEventDetails
- LambdaFunctionTimedOutEventDetails
- LambdaFunctionFailedEventDetails
- CreateStateMachineOutput
- ExecutionAbortedEventDetails
- ListStateMachineAliasesInput
- ListStateMachineAliasesOutput
- TaskStartedEventDetails
- StopExecutionOutput
- DeleteStateMachineAliasInput
- LambdaFunctionScheduledEventDetails
- StateExitedEventDetails
- UpdateMapRunOutput
- DeleteStateMachineVersionInput
- StartSyncExecutionInput
- StartExecutionInput
- DescribeActivityOutput
- MapRunFailedEventDetails
- DescribeStateMachineAliasOutput
- DeleteActivityOutput
- StateMachineVersionListItem
- LoggingConfiguration
- ActivityFailedEventDetails
- GetExecutionHistoryInput
- StartSyncExecutionOutput
- SendTaskHeartbeatInput
- MapIterationEventDetails
- SendTaskSuccessInput
- TaskCredentials
- CloudWatchEventsExecutionDataDetails
- RoutingConfigurationListItem
- GetActivityTaskInput
- ExecutionSucceededEventDetails
- BillingDetails
- CreateActivityInput
- DescribeExecutionInput
- ListActivitiesOutput
- ActivityScheduleFailedEventDetails
- DeleteStateMachineAliasOutput
- LogDestination
- SendTaskSuccessOutput
- TaskScheduledEventDetails
- PublishStateMachineVersionOutput
- LambdaFunctionStartFailedEventDetails
- ListStateMachineVersionsInput
- Amazon Step Functions State Machine
- ExecutionFailedEventDetails
- MapRunItemCounts
- SendTaskHeartbeatOutput
- DescribeStateMachineInput
- TaskTimedOutEventDetails
- DeleteActivityInput
- ListTagsForResourceInput
- UpdateStateMachineAliasOutput
- MapRunStartedEventDetails
- MapStateStartedEventDetails
- ListActivitiesInput
- TaskSubmitFailedEventDetails
- UpdateStateMachineInput
- DeleteStateMachineVersionOutput
- TaskStartFailedEventDetails
- TaskFailedEventDetails
- ListExecutionsOutput
- DescribeActivityInput
- UntagResourceInput
- ExecutionTimedOutEventDetails
- PublishStateMachineVersionInput
- ActivityListItem
- CreateStateMachineInput
- StopExecutionInput
- ListMapRunsOutput
- TaskSubmittedEventDetails
- CreateStateMachineAliasInput
- CreateActivityOutput
- MapRunExecutionCounts
- TaskSucceededEventDetails
- DescribeExecutionOutput
- HistoryEvent
- DeleteStateMachineInput
- ListStateMachinesInput
- ExecutionStartedEventDetails
- StateEnteredEventDetails
- StateMachineListItem
- StateMachineAliasListItem
- DescribeStateMachineAliasInput
- DescribeStateMachineOutput
- TagResourceOutput
- UpdateMapRunInput
- ActivityTimedOutEventDetails
- DeleteStateMachineOutput
- ListStateMachinesOutput
- ListStateMachineVersionsOutput
- SendTaskFailureInput
- ListExecutionsInput
- CloudWatchLogsLogGroup
- LambdaFunctionSucceededEventDetails
- TracingConfiguration
- TagResourceInput
- ListMapRunsInput
- MapRunListItem
- GetExecutionHistoryOutput
- ExecutionListItem
- Tag
- GetActivityTaskOutput
- DescribeStateMachineForExecutionInput
- UpdateStateMachineAliasInput
- HistoryEventExecutionDataDetails
- LambdaFunctionScheduleFailedEventDetails
- UpdateStateMachineOutput
- CreateStateMachineAliasOutput
- ListTagsForResourceOutput
- ActivityStartedEventDetails
- DescribeStateMachineForExecutionOutput
- ActivityScheduledEventDetails
- UntagResourceOutput
- SendTaskFailureOutput
- name
- description
context_file: json-ld/amazon-step-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-step-functions/refs/heads/main/json-ld/amazon-step-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Step Functions from Amazon Step Functions.
layout: jsonld
name: Amazon Step Functions Context
namespaces:
- prefix: aws
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: mapRunArn
  type: string
- container: ''
  name: executionArn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startDate
  type: string
- container: ''
  name: stopDate
  type: string
- container: ''
  name: maxConcurrency
  type: string
- container: ''
  name: toleratedFailurePercentage
  type: string
- container: ''
  name: toleratedFailureCount
  type: string
- container: ''
  name: itemCounts
  type: string
- container: ''
  name: executionCounts
  type: string
- container: ''
  name: output
  type: string
- container: ''
  name: outputDetails
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: cause
  type: string
- container: ''
  name: stateMachineArn
  type: string
- container: ''
  name: creationDate
  type: string
- container: ''
  name: stateMachineVersionArn
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: stateMachineAliases
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: stateMachineAliasArn
  type: string
- container: ''
  name: input
  type: string
- container: ''
  name: inputDetails
  type: string
- container: ''
  name: timeoutInSeconds
  type: string
- container: ''
  name: taskCredentials
  type: string
- container: ''
  name: traceHeader
  type: string
- container: ''
  name: activityArn
  type: string
- container: ''
  name: routingConfiguration
  type: string
- container: ''
  name: updateDate
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: includeExecutionData
  type: string
- container: ''
  name: destinations
  type: string
- container: ''
  name: reverseOrder
  type: string
- container: ''
  name: billingDetails
  type: string
- container: ''
  name: taskToken
  type: string
- container: ''
  name: index
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: included
  type: string
- container: ''
  name: weight
  type: string
- container: ''
  name: workerName
  type: string
- container: ''
  name: billedMemoryUsedInMB
  type: string
- container: ''
  name: billedDurationInMilliseconds
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: activities
  type: string
- container: ''
  name: cloudWatchLogsLogGroup
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: heartbeatInSeconds
  type: string
- container: ''
  name: definition
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: loggingConfiguration
  type: string
- container: ''
  name: tracingConfiguration
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: pending
  type: string
- container: ''
  name: running
  type: string
- container: ''
  name: succeeded
  type: string
- container: ''
  name: failed
  type: string
- container: ''
  name: timedOut
  type: string
- container: ''
  name: aborted
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: resultsWritten
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: length
  type: string
- container: ''
  name: publish
  type: string
- container: ''
  name: versionDescription
  type: string
- container: ''
  name: executions
  type: string
- container: ''
  name: tagKeys
  type: string
- container: ''
  name: mapRuns
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: previousEventId
  type: string
- container: ''
  name: activityFailedEventDetails
  type: string
- container: ''
  name: activityScheduleFailedEventDetails
  type: string
- container: ''
  name: activityScheduledEventDetails
  type: string
- container: ''
  name: activityStartedEventDetails
  type: string
- container: ''
  name: activitySucceededEventDetails
  type: string
- container: ''
  name: activityTimedOutEventDetails
  type: string
- container: ''
  name: taskFailedEventDetails
  type: string
- container: ''
  name: taskScheduledEventDetails
  type: string
- container: ''
  name: taskStartFailedEventDetails
  type: string
- container: ''
  name: taskStartedEventDetails
  type: string
- container: ''
  name: taskSubmitFailedEventDetails
  type: string
- container: ''
  name: taskSubmittedEventDetails
  type: string
- container: ''
  name: taskSucceededEventDetails
  type: string
- container: ''
  name: taskTimedOutEventDetails
  type: string
- container: ''
  name: executionFailedEventDetails
  type: string
- container: ''
  name: executionStartedEventDetails
  type: string
- container: ''
  name: executionSucceededEventDetails
  type: string
- container: ''
  name: executionAbortedEventDetails
  type: string
- container: ''
  name: executionTimedOutEventDetails
  type: string
- container: ''
  name: mapStateStartedEventDetails
  type: string
- container: ''
  name: mapIterationStartedEventDetails
  type: string
- container: ''
  name: mapIterationSucceededEventDetails
  type: string
- container: ''
  name: mapIterationFailedEventDetails
  type: string
- container: ''
  name: mapIterationAbortedEventDetails
  type: string
- container: ''
  name: lambdaFunctionFailedEventDetails
  type: string
- container: ''
  name: lambdaFunctionScheduleFailedEventDetails
  type: string
- container: ''
  name: lambdaFunctionScheduledEventDetails
  type: string
- container: ''
  name: lambdaFunctionStartFailedEventDetails
  type: string
- container: ''
  name: lambdaFunctionSucceededEventDetails
  type: string
- container: ''
  name: lambdaFunctionTimedOutEventDetails
  type: string
- container: ''
  name: stateEnteredEventDetails
  type: string
- container: ''
  name: stateExitedEventDetails
  type: string
- container: ''
  name: mapRunStartedEventDetails
  type: string
- container: ''
  name: mapRunFailedEventDetails
  type: string
- container: ''
  name: stateMachines
  type: string
- container: ''
  name: stateMachineVersions
  type: string
- container: ''
  name: statusFilter
  type: string
- container: ''
  name: logGroupArn
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: events
  type: string
- container: ''
  name: itemCount
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: truncated
  type: string
property_count: 118
provider_name: Amazon Step Functions
provider_slug: amazon-step-functions
slug: amazon-step-functions-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DescribeMapRunInput\": \"aws:DescribeMapRunInput\",\n    \"DescribeMapRunOutput\": \"aws:DescribeMapRunOutput\",\n    \"StartExecutionOutput\": \"aws:StartExecutionOutput\",\n    \"ActivitySucceededEventDetails\": \"aws:ActivitySucceededEventDetails\",\n    \"LambdaFunctionTimedOutEventDetails\": \"aws:LambdaFunctionTimedOutEventDetails\",\n    \"LambdaFunctionFailedEventDetails\": \"aws:LambdaFunctionFailedEventDetails\",\n    \"CreateStateMachineOutput\": \"aws:CreateStateMachineOutput\",\n    \"ExecutionAbortedEventDetails\": \"aws:ExecutionAbortedEventDetails\",\n    \"ListStateMachineAliasesInput\": \"aws:ListStateMachineAliasesInput\",\n    \"ListStateMachineAliasesOutput\": \"aws:ListStateMachineAliasesOutput\",\n    \"TaskStartedEventDetails\"\
  : \"aws:TaskStartedEventDetails\",\n    \"StopExecutionOutput\": \"aws:StopExecutionOutput\",\n    \"DeleteStateMachineAliasInput\": \"aws:DeleteStateMachineAliasInput\",\n    \"LambdaFunctionScheduledEventDetails\": \"aws:LambdaFunctionScheduledEventDetails\",\n    \"StateExitedEventDetails\": \"aws:StateExitedEventDetails\",\n    \"UpdateMapRunOutput\": \"aws:UpdateMapRunOutput\",\n    \"DeleteStateMachineVersionInput\": \"aws:DeleteStateMachineVersionInput\",\n    \"StartSyncExecutionInput\": \"aws:StartSyncExecutionInput\",\n    \"StartExecutionInput\": \"aws:StartExecutionInput\",\n    \"DescribeActivityOutput\": \"aws:DescribeActivityOutput\",\n    \"MapRunFailedEventDetails\": \"aws:MapRunFailedEventDetails\",\n    \"DescribeStateMachineAliasOutput\": \"aws:DescribeStateMachineAliasOutput\",\n    \"DeleteActivityOutput\": \"aws:DeleteActivityOutput\",\n    \"StateMachineVersionListItem\": \"aws:StateMachineVersionListItem\",\n    \"LoggingConfiguration\": \"aws:LoggingConfiguration\"\
  ,\n    \"ActivityFailedEventDetails\": \"aws:ActivityFailedEventDetails\",\n    \"GetExecutionHistoryInput\": \"aws:GetExecutionHistoryInput\",\n    \"StartSyncExecutionOutput\": \"aws:StartSyncExecutionOutput\",\n    \"SendTaskHeartbeatInput\": \"aws:SendTaskHeartbeatInput\",\n    \"MapIterationEventDetails\": \"aws:MapIterationEventDetails\",\n    \"SendTaskSuccessInput\": \"aws:SendTaskSuccessInput\",\n    \"TaskCredentials\": \"aws:TaskCredentials\",\n    \"CloudWatchEventsExecutionDataDetails\": \"aws:CloudWatchEventsExecutionDataDetails\",\n    \"RoutingConfigurationListItem\": \"aws:RoutingConfigurationListItem\",\n    \"GetActivityTaskInput\": \"aws:GetActivityTaskInput\",\n    \"ExecutionSucceededEventDetails\": \"aws:ExecutionSucceededEventDetails\",\n    \"BillingDetails\": \"aws:BillingDetails\",\n    \"CreateActivityInput\": \"aws:CreateActivityInput\",\n    \"DescribeExecutionInput\": \"aws:DescribeExecutionInput\",\n    \"ListActivitiesOutput\": \"aws:ListActivitiesOutput\"\
  ,\n    \"ActivityScheduleFailedEventDetails\": \"aws:ActivityScheduleFailedEventDetails\",\n    \"DeleteStateMachineAliasOutput\": \"aws:DeleteStateMachineAliasOutput\",\n    \"LogDestination\": \"aws:LogDestination\",\n    \"SendTaskSuccessOutput\": \"aws:SendTaskSuccessOutput\",\n    \"TaskScheduledEventDetails\": \"aws:TaskScheduledEventDetails\",\n    \"PublishStateMachineVersionOutput\": \"aws:PublishStateMachineVersionOutput\",\n    \"LambdaFunctionStartFailedEventDetails\": \"aws:LambdaFunctionStartFailedEventDetails\",\n    \"ListStateMachineVersionsInput\": \"aws:ListStateMachineVersionsInput\",\n    \"Amazon Step Functions State Machine\": \"aws:Amazon Step Functions State Machine\",\n    \"ExecutionFailedEventDetails\": \"aws:ExecutionFailedEventDetails\",\n    \"MapRunItemCounts\": \"aws:MapRunItemCounts\",\n    \"SendTaskHeartbeatOutput\": \"aws:SendTaskHeartbeatOutput\",\n    \"DescribeStateMachineInput\": \"aws:DescribeStateMachineInput\",\n    \"TaskTimedOutEventDetails\"\
  : \"aws:TaskTimedOutEventDetails\",\n    \"DeleteActivityInput\": \"aws:DeleteActivityInput\",\n    \"ListTagsForResourceInput\": \"aws:ListTagsForResourceInput\",\n    \"UpdateStateMachineAliasOutput\": \"aws:UpdateStateMachineAliasOutput\",\n    \"MapRunStartedEventDetails\": \"aws:MapRunStartedEventDetails\",\n    \"MapStateStartedEventDetails\": \"aws:MapStateStartedEventDetails\",\n    \"ListActivitiesInput\": \"aws:ListActivitiesInput\",\n    \"TaskSubmitFailedEventDetails\": \"aws:TaskSubmitFailedEventDetails\",\n    \"UpdateStateMachineInput\": \"aws:UpdateStateMachineInput\",\n    \"DeleteStateMachineVersionOutput\": \"aws:DeleteStateMachineVersionOutput\",\n    \"TaskStartFailedEventDetails\": \"aws:TaskStartFailedEventDetails\",\n    \"TaskFailedEventDetails\": \"aws:TaskFailedEventDetails\",\n    \"ListExecutionsOutput\": \"aws:ListExecutionsOutput\",\n    \"DescribeActivityInput\": \"aws:DescribeActivityInput\",\n    \"UntagResourceInput\": \"aws:UntagResourceInput\",\n  \
  \  \"ExecutionTimedOutEventDetails\": \"aws:ExecutionTimedOutEventDetails\",\n    \"PublishStateMachineVersionInput\": \"aws:PublishStateMachineVersionInput\",\n    \"ActivityListItem\": \"aws:ActivityListItem\",\n    \"CreateStateMachineInput\": \"aws:CreateStateMachineInput\",\n    \"StopExecutionInput\": \"aws:StopExecutionInput\",\n    \"ListMapRunsOutput\": \"aws:ListMapRunsOutput\",\n    \"TaskSubmittedEventDetails\": \"aws:TaskSubmittedEventDetails\",\n    \"CreateStateMachineAliasInput\": \"aws:CreateStateMachineAliasInput\",\n    \"CreateActivityOutput\": \"aws:CreateActivityOutput\",\n    \"MapRunExecutionCounts\": \"aws:MapRunExecutionCounts\",\n    \"TaskSucceededEventDetails\": \"aws:TaskSucceededEventDetails\",\n    \"DescribeExecutionOutput\": \"aws:DescribeExecutionOutput\",\n    \"HistoryEvent\": \"aws:HistoryEvent\",\n    \"DeleteStateMachineInput\": \"aws:DeleteStateMachineInput\",\n    \"ListStateMachinesInput\": \"aws:ListStateMachinesInput\",\n    \"ExecutionStartedEventDetails\"\
  : \"aws:ExecutionStartedEventDetails\",\n    \"StateEnteredEventDetails\": \"aws:StateEnteredEventDetails\",\n    \"StateMachineListItem\": \"aws:StateMachineListItem\",\n    \"StateMachineAliasListItem\": \"aws:StateMachineAliasListItem\",\n    \"DescribeStateMachineAliasInput\": \"aws:DescribeStateMachineAliasInput\",\n    \"DescribeStateMachineOutput\": \"aws:DescribeStateMachineOutput\",\n    \"TagResourceOutput\": \"aws:TagResourceOutput\",\n    \"UpdateMapRunInput\": \"aws:UpdateMapRunInput\",\n    \"ActivityTimedOutEventDetails\": \"aws:ActivityTimedOutEventDetails\",\n    \"DeleteStateMachineOutput\": \"aws:DeleteStateMachineOutput\",\n    \"ListStateMachinesOutput\": \"aws:ListStateMachinesOutput\",\n    \"ListStateMachineVersionsOutput\": \"aws:ListStateMachineVersionsOutput\",\n    \"SendTaskFailureInput\": \"aws:SendTaskFailureInput\",\n    \"ListExecutionsInput\": \"aws:ListExecutionsInput\",\n    \"CloudWatchLogsLogGroup\": \"aws:CloudWatchLogsLogGroup\",\n    \"LambdaFunctionSucceededEventDetails\"\
  : \"aws:LambdaFunctionSucceededEventDetails\",\n    \"TracingConfiguration\": \"aws:TracingConfiguration\",\n    \"TagResourceInput\": \"aws:TagResourceInput\",\n    \"ListMapRunsInput\": \"aws:ListMapRunsInput\",\n    \"MapRunListItem\": \"aws:MapRunListItem\",\n    \"GetExecutionHistoryOutput\": \"aws:GetExecutionHistoryOutput\",\n    \"ExecutionListItem\": \"aws:ExecutionListItem\",\n    \"Tag\": \"aws:Tag\",\n    \"GetActivityTaskOutput\": \"aws:GetActivityTaskOutput\",\n    \"DescribeStateMachineForExecutionInput\": \"aws:DescribeStateMachineForExecutionInput\",\n    \"UpdateStateMachineAliasInput\": \"aws:UpdateStateMachineAliasInput\",\n    \"HistoryEventExecutionDataDetails\": \"aws:HistoryEventExecutionDataDetails\",\n    \"LambdaFunctionScheduleFailedEventDetails\": \"aws:LambdaFunctionScheduleFailedEventDetails\",\n    \"UpdateStateMachineOutput\": \"aws:UpdateStateMachineOutput\",\n    \"CreateStateMachineAliasOutput\": \"aws:CreateStateMachineAliasOutput\",\n    \"ListTagsForResourceOutput\"\
  : \"aws:ListTagsForResourceOutput\",\n    \"ActivityStartedEventDetails\": \"aws:ActivityStartedEventDetails\",\n    \"DescribeStateMachineForExecutionOutput\": \"aws:DescribeStateMachineForExecutionOutput\",\n    \"ActivityScheduledEventDetails\": \"aws:ActivityScheduledEventDetails\",\n    \"UntagResourceOutput\": \"aws:UntagResourceOutput\",\n    \"SendTaskFailureOutput\": \"aws:SendTaskFailureOutput\",\n    \"mapRunArn\": {\n      \"@id\": \"aws:mapRunArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionArn\": {\n      \"@id\": \"aws:executionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startDate\": {\n      \"@id\": \"aws:startDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopDate\": {\n      \"@id\": \"aws:stopDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxConcurrency\": {\n      \"@id\": \"aws:maxConcurrency\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"toleratedFailurePercentage\": {\n      \"@id\": \"aws:toleratedFailurePercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"toleratedFailureCount\": {\n      \"@id\": \"aws:toleratedFailureCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemCounts\": {\n      \"@id\": \"aws:itemCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionCounts\": {\n      \"@id\": \"aws:executionCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"output\": {\n      \"@id\": \"aws:output\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputDetails\": {\n      \"@id\": \"aws:outputDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"aws:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cause\": {\n      \"@id\": \"aws:cause\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachineArn\": {\n      \"@id\": \"aws:stateMachineArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationDate\": {\n      \"@id\"\
  : \"aws:creationDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachineVersionArn\": {\n      \"@id\": \"aws:stateMachineVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"aws:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachineAliases\": {\n      \"@id\": \"aws:stateMachineAliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"aws:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"aws:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachineAliasArn\": {\n      \"@id\": \"aws:stateMachineAliasArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"input\": {\n      \"@id\": \"aws:input\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDetails\": {\n      \"@id\": \"aws:inputDetails\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"timeoutInSeconds\": {\n      \"@id\": \"aws:timeoutInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskCredentials\": {\n      \"@id\": \"aws:taskCredentials\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"traceHeader\": {\n      \"@id\": \"aws:traceHeader\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityArn\": {\n      \"@id\": \"aws:activityArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"routingConfiguration\": {\n      \"@id\": \"aws:routingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateDate\": {\n      \"@id\": \"aws:updateDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"aws:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"includeExecutionData\": {\n      \"@id\": \"aws:includeExecutionData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"aws:destinations\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"reverseOrder\": {\n      \"@id\": \"aws:reverseOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billingDetails\": {\n      \"@id\": \"aws:billingDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskToken\": {\n      \"@id\": \"aws:taskToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"aws:index\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"aws:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"included\": {\n      \"@id\": \"aws:included\",\n      \"@type\": \"xsd:string\"\n    },\n    \"weight\": {\n      \"@id\": \"aws:weight\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workerName\": {\n      \"@id\": \"aws:workerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billedMemoryUsedInMB\": {\n      \"@id\": \"aws:billedMemoryUsedInMB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"billedDurationInMilliseconds\": {\n      \"@id\"\
  : \"aws:billedDurationInMilliseconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activities\": {\n      \"@id\": \"aws:activities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudWatchLogsLogGroup\": {\n      \"@id\": \"aws:cloudWatchLogsLogGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"aws:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"aws:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"heartbeatInSeconds\": {\n      \"@id\": \"aws:heartbeatInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"definition\": {\n      \"@id\": \"aws:definition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loggingConfiguration\": {\n      \"@id\": \"aws:loggingConfiguration\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"tracingConfiguration\": {\n      \"@id\": \"aws:tracingConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"aws:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"aws:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pending\": {\n      \"@id\": \"aws:pending\",\n      \"@type\": \"xsd:string\"\n    },\n    \"running\": {\n      \"@id\": \"aws:running\",\n      \"@type\": \"xsd:string\"\n    },\n    \"succeeded\": {\n      \"@id\": \"aws:succeeded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failed\": {\n      \"@id\": \"aws:failed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timedOut\": {\n      \"@id\": \"aws:timedOut\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aborted\": {\n      \"@id\": \"aws:aborted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"aws:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resultsWritten\"\
  : {\n      \"@id\": \"aws:resultsWritten\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"aws:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"aws:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publish\": {\n      \"@id\": \"aws:publish\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionDescription\": {\n      \"@id\": \"aws:versionDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executions\": {\n      \"@id\": \"aws:executions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagKeys\": {\n      \"@id\": \"aws:tagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapRuns\": {\n      \"@id\": \"aws:mapRuns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"aws:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousEventId\": {\n      \"@id\"\
  : \"aws:previousEventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityFailedEventDetails\": {\n      \"@id\": \"aws:activityFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityScheduleFailedEventDetails\": {\n      \"@id\": \"aws:activityScheduleFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityScheduledEventDetails\": {\n      \"@id\": \"aws:activityScheduledEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityStartedEventDetails\": {\n      \"@id\": \"aws:activityStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activitySucceededEventDetails\": {\n      \"@id\": \"aws:activitySucceededEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activityTimedOutEventDetails\": {\n      \"@id\": \"aws:activityTimedOutEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskFailedEventDetails\": {\n      \"@id\": \"aws:taskFailedEventDetails\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"taskScheduledEventDetails\": {\n      \"@id\": \"aws:taskScheduledEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskStartFailedEventDetails\": {\n      \"@id\": \"aws:taskStartFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskStartedEventDetails\": {\n      \"@id\": \"aws:taskStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskSubmitFailedEventDetails\": {\n      \"@id\": \"aws:taskSubmitFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskSubmittedEventDetails\": {\n      \"@id\": \"aws:taskSubmittedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskSucceededEventDetails\": {\n      \"@id\": \"aws:taskSucceededEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskTimedOutEventDetails\": {\n      \"@id\": \"aws:taskTimedOutEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionFailedEventDetails\": {\n      \"@id\": \"aws:executionFailedEventDetails\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"executionStartedEventDetails\": {\n      \"@id\": \"aws:executionStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionSucceededEventDetails\": {\n      \"@id\": \"aws:executionSucceededEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionAbortedEventDetails\": {\n      \"@id\": \"aws:executionAbortedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionTimedOutEventDetails\": {\n      \"@id\": \"aws:executionTimedOutEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapStateStartedEventDetails\": {\n      \"@id\": \"aws:mapStateStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapIterationStartedEventDetails\": {\n      \"@id\": \"aws:mapIterationStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapIterationSucceededEventDetails\": {\n      \"@id\": \"aws:mapIterationSucceededEventDetails\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"mapIterationFailedEventDetails\": {\n      \"@id\": \"aws:mapIterationFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapIterationAbortedEventDetails\": {\n      \"@id\": \"aws:mapIterationAbortedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionFailedEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionScheduleFailedEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionScheduleFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionScheduledEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionScheduledEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionStartFailedEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionStartFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionSucceededEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionSucceededEventDetails\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionTimedOutEventDetails\": {\n      \"@id\": \"aws:lambdaFunctionTimedOutEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateEnteredEventDetails\": {\n      \"@id\": \"aws:stateEnteredEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateExitedEventDetails\": {\n      \"@id\": \"aws:stateExitedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapRunStartedEventDetails\": {\n      \"@id\": \"aws:mapRunStartedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mapRunFailedEventDetails\": {\n      \"@id\": \"aws:mapRunFailedEventDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachines\": {\n      \"@id\": \"aws:stateMachines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateMachineVersions\": {\n      \"@id\": \"aws:stateMachineVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusFilter\": {\n      \"@id\": \"aws:statusFilter\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"logGroupArn\": {\n      \"@id\": \"aws:logGroupArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"aws:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"aws:events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemCount\": {\n      \"@id\": \"aws:itemCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"truncated\": {\n      \"@id\": \"aws:truncated\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-step-functions/refs/heads/main/json-ld/amazon-step-functions-context.jsonld
tags:
- AWS
- Orchestration
- Serverless
- State Machine
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
