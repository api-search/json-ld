---
api_specs:
- filename: amazon-iot-events-openapi-original.yml
  format: yaml
  label: AWS IoT Events API
  slug: aws-iot-events-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/openapi/amazon-iot-events-openapi-original.yml
class_count: 101
classes:
- AcknowledgeFlow
- Action
- AlarmAction
- AlarmCapabilities
- AlarmEventActions
- AlarmModelSummary
- AlarmModelVersionSummary
- AlarmNotification
- AlarmRule
- AnalysisResult
- AnalysisResultLocation
- AssetPropertyTimestamp
- AssetPropertyValue
- AssetPropertyVariant
- Attribute
- ClearTimerAction
- CreateAlarmModelRequest
- CreateAlarmModelResponse
- CreateDetectorModelRequest
- CreateDetectorModelResponse
- CreateInputRequest
- CreateInputResponse
- DeleteAlarmModelRequest
- DeleteAlarmModelResponse
- DeleteDetectorModelRequest
- DeleteDetectorModelResponse
- DeleteInputRequest
- DeleteInputResponse
- DescribeAlarmModelRequest
- DescribeAlarmModelResponse
- DescribeDetectorModelAnalysisRequest
- DescribeDetectorModelAnalysisResponse
- DescribeDetectorModelRequest
- DescribeDetectorModelResponse
- DescribeInputRequest
- DescribeInputResponse
- DescribeLoggingOptionsRequest
- DescribeLoggingOptionsResponse
- DetectorDebugOption
- DetectorModel
- DetectorModelConfiguration
- DetectorModelDefinition
- DetectorModelSummary
- DetectorModelVersionSummary
- DynamoDBAction
- DynamoDBv2Action
- EmailConfiguration
- EmailContent
- EmailRecipients
- Event
- FirehoseAction
- GetDetectorModelAnalysisResultsRequest
- GetDetectorModelAnalysisResultsResponse
- InitializationConfiguration
- Input
- InputConfiguration
- InputDefinition
- InputIdentifier
- InputSummary
- IotEventsAction
- IotEventsInputIdentifier
- IotSiteWiseAction
- IotSiteWiseAssetModelPropertyIdentifier
- IotSiteWiseInputIdentifier
- IotTopicPublishAction
- LambdaAction
- ListAlarmModelVersionsRequest
- ListAlarmModelVersionsResponse
- ListAlarmModelsRequest
- ListAlarmModelsResponse
- ListDetectorModelVersionsRequest
- ListDetectorModelVersionsResponse
- ListDetectorModelsRequest
- ListDetectorModelsResponse
- ListInputRoutingsRequest
- ListInputRoutingsResponse
- ListInputsRequest
- ListInputsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- LoggingOptions
- NotificationAction
- NotificationTargetActions
- OnEnterLifecycle
- OnExitLifecycle
- OnInputLifecycle
- Payload
- PutLoggingOptionsRequest
- RecipientDetail
- ResetTimerAction
- RoutedResource
- SMSConfiguration
- SNSTopicPublishAction
- SSOIdentity
- SetTimerAction
- SetVariableAction
- SimpleRule
- SqsAction
- StartDetectorModelAnalysisRequest
- StartDetectorModelAnalysisResponse
- name
context_file: json-ld/amazon-iot-events-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/json-ld/amazon-iot-events-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Events from Amazon IoT Events.
layout: jsonld
name: Amazon Iot Events Context
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
  name: acknowledgeFlow
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actions
  type: string
- container: ''
  name: additionalMessage
  type: string
- container: ''
  name: alarmActions
  type: string
- container: ''
  name: alarmCapabilities
  type: string
- container: ''
  name: alarmEventActions
  type: string
- container: ''
  name: alarmModelArn
  type: string
- container: ''
  name: alarmModelDescription
  type: string
- container: ''
  name: alarmModelName
  type: string
- container: ''
  name: alarmModelSummaries
  type: string
- container: ''
  name: alarmModelVersion
  type: string
- container: ''
  name: alarmModelVersionSummaries
  type: string
- container: ''
  name: alarmNotification
  type: string
- container: ''
  name: alarmRule
  type: string
- container: ''
  name: analysisId
  type: string
- container: ''
  name: analysisResults
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: assetId
  type: string
- container: ''
  name: assetModelId
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: booleanValue
  type: string
- container: ''
  name: clearTimer
  type: string
- container: ''
  name: comparisonOperator
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: contentExpression
  type: string
- container: ''
  name: creationTime
  type: string
- container: ''
  name: deliveryStreamName
  type: string
- container: ''
  name: detectorDebugOptions
  type: string
- container: ''
  name: detectorModel
  type: string
- container: ''
  name: detectorModelArn
  type: string
- container: ''
  name: detectorModelConfiguration
  type: string
- container: ''
  name: detectorModelDefinition
  type: string
- container: ''
  name: detectorModelDescription
  type: string
- container: ''
  name: detectorModelName
  type: string
- container: ''
  name: detectorModelSummaries
  type: string
- container: ''
  name: detectorModelVersion
  type: string
- container: ''
  name: detectorModelVersionSummaries
  type: string
- container: ''
  name: disabledOnInitialization
  type: string
- container: ''
  name: doubleValue
  type: string
- container: ''
  name: durationExpression
  type: string
- container: ''
  name: dynamoDB
  type: string
- container: ''
  name: dynamoDBv2
  type: string
- container: ''
  name: emailConfigurations
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: entryId
  type: string
- container: ''
  name: evaluationMethod
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: events
  type: string
- container: ''
  name: firehose
  type: string
- container: ''
  name: from
  type: string
- container: ''
  name: functionArn
  type: string
- container: ''
  name: hashKeyField
  type: string
- container: ''
  name: hashKeyType
  type: string
- container: ''
  name: hashKeyValue
  type: string
- container: ''
  name: identityStoreId
  type: string
- container: ''
  name: initialStateName
  type: string
- container: ''
  name: initializationConfiguration
  type: string
- container: ''
  name: input
  type: string
- container: ''
  name: inputArn
  type: string
- container: ''
  name: inputConfiguration
  type: string
- container: ''
  name: inputDefinition
  type: string
- container: ''
  name: inputDescription
  type: string
- container: ''
  name: inputIdentifier
  type: string
- container: ''
  name: inputName
  type: string
- container: ''
  name: inputProperty
  type: string
- container: ''
  name: inputSummaries
  type: string
- container: ''
  name: integerValue
  type: string
- container: ''
  name: iotEvents
  type: string
- container: ''
  name: iotEventsInputIdentifier
  type: string
- container: ''
  name: iotSiteWise
  type: string
- container: ''
  name: iotSiteWiseAssetModelPropertyIdentifier
  type: string
- container: ''
  name: iotSiteWiseInputIdentifier
  type: string
- container: ''
  name: iotTopicPublish
  type: string
- container: ''
  name: jsonPath
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: keyValue
  type: string
- container: ''
  name: lambda
  type: string
- container: ''
  name: lambdaAction
  type: string
- container: ''
  name: lastUpdateTime
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: locations
  type: string
- container: ''
  name: loggingOptions
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: mqttTopic
  type: string
- container: ''
  name: nextState
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: notificationActions
  type: string
- container: ''
  name: offsetInNanos
  type: string
- container: ''
  name: onEnter
  type: string
- container: ''
  name: onExit
  type: string
- container: ''
  name: onInput
  type: string
- container: ''
  name: operation
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: payload
  type: string
- container: ''
  name: payloadField
  type: string
- container: ''
  name: propertyAlias
  type: string
- container: ''
  name: propertyId
  type: string
- container: ''
  name: propertyValue
  type: string
- container: ''
  name: quality
  type: string
- container: ''
  name: queueUrl
  type: string
- container: ''
  name: rangeKeyField
  type: string
- container: ''
  name: rangeKeyType
  type: string
- container: ''
  name: rangeKeyValue
  type: string
- container: ''
  name: recipients
  type: string
- container: ''
  name: resetTimer
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: routedResources
  type: string
- container: ''
  name: seconds
  type: string
- container: ''
  name: senderId
  type: string
- container: ''
  name: separator
  type: string
- container: ''
  name: setTimer
  type: string
- container: ''
  name: setVariable
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: simpleRule
  type: string
- container: ''
  name: smsConfigurations
  type: string
- container: ''
  name: sns
  type: string
- container: ''
  name: sqs
  type: string
- container: ''
  name: ssoIdentity
  type: string
- container: ''
  name: stateName
  type: string
- container: ''
  name: states
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: stringValue
  type: string
- container: ''
  name: subject
  type: string
- container: ''
  name: tableName
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetArn
  type: string
- container: ''
  name: threshold
  type: string
- container: ''
  name: timeInSeconds
  type: string
- container: ''
  name: timerName
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: to
  type: string
- container: ''
  name: transitionEvents
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: useBase64
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: variableName
  type: string
property_count: 141
provider_name: Amazon IoT Events
provider_slug: amazon-iot-events
slug: amazon-iot-events-context
source_filename: amazon-iot-events-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcknowledgeFlow\": \"amzn:AcknowledgeFlow\",\n    \"Action\": \"amzn:Action\",\n    \"AlarmAction\": \"amzn:AlarmAction\",\n    \"AlarmCapabilities\": \"amzn:AlarmCapabilities\",\n    \"AlarmEventActions\": \"amzn:AlarmEventActions\",\n    \"AlarmModelSummary\": \"amzn:AlarmModelSummary\",\n    \"AlarmModelVersionSummary\": \"amzn:AlarmModelVersionSummary\",\n    \"AlarmNotification\": \"amzn:AlarmNotification\",\n    \"AlarmRule\": \"amzn:AlarmRule\",\n    \"AnalysisResult\": \"amzn:AnalysisResult\",\n    \"AnalysisResultLocation\": \"amzn:AnalysisResultLocation\",\n    \"AssetPropertyTimestamp\": \"amzn:AssetPropertyTimestamp\",\n    \"AssetPropertyValue\": \"amzn:AssetPropertyValue\",\n    \"AssetPropertyVariant\": \"amzn:AssetPropertyVariant\"\
  ,\n    \"Attribute\": \"amzn:Attribute\",\n    \"ClearTimerAction\": \"amzn:ClearTimerAction\",\n    \"CreateAlarmModelRequest\": \"amzn:CreateAlarmModelRequest\",\n    \"CreateAlarmModelResponse\": \"amzn:CreateAlarmModelResponse\",\n    \"CreateDetectorModelRequest\": \"amzn:CreateDetectorModelRequest\",\n    \"CreateDetectorModelResponse\": \"amzn:CreateDetectorModelResponse\",\n    \"CreateInputRequest\": \"amzn:CreateInputRequest\",\n    \"CreateInputResponse\": \"amzn:CreateInputResponse\",\n    \"DeleteAlarmModelRequest\": \"amzn:DeleteAlarmModelRequest\",\n    \"DeleteAlarmModelResponse\": \"amzn:DeleteAlarmModelResponse\",\n    \"DeleteDetectorModelRequest\": \"amzn:DeleteDetectorModelRequest\",\n    \"DeleteDetectorModelResponse\": \"amzn:DeleteDetectorModelResponse\",\n    \"DeleteInputRequest\": \"amzn:DeleteInputRequest\",\n    \"DeleteInputResponse\": \"amzn:DeleteInputResponse\",\n    \"DescribeAlarmModelRequest\": \"amzn:DescribeAlarmModelRequest\",\n    \"DescribeAlarmModelResponse\"\
  : \"amzn:DescribeAlarmModelResponse\",\n    \"DescribeDetectorModelAnalysisRequest\": \"amzn:DescribeDetectorModelAnalysisRequest\",\n    \"DescribeDetectorModelAnalysisResponse\": \"amzn:DescribeDetectorModelAnalysisResponse\",\n    \"DescribeDetectorModelRequest\": \"amzn:DescribeDetectorModelRequest\",\n    \"DescribeDetectorModelResponse\": \"amzn:DescribeDetectorModelResponse\",\n    \"DescribeInputRequest\": \"amzn:DescribeInputRequest\",\n    \"DescribeInputResponse\": \"amzn:DescribeInputResponse\",\n    \"DescribeLoggingOptionsRequest\": \"amzn:DescribeLoggingOptionsRequest\",\n    \"DescribeLoggingOptionsResponse\": \"amzn:DescribeLoggingOptionsResponse\",\n    \"DetectorDebugOption\": \"amzn:DetectorDebugOption\",\n    \"DetectorModel\": \"amzn:DetectorModel\",\n    \"DetectorModelConfiguration\": \"amzn:DetectorModelConfiguration\",\n    \"DetectorModelDefinition\": \"amzn:DetectorModelDefinition\",\n    \"DetectorModelSummary\": \"amzn:DetectorModelSummary\",\n    \"DetectorModelVersionSummary\"\
  : \"amzn:DetectorModelVersionSummary\",\n    \"DynamoDBAction\": \"amzn:DynamoDBAction\",\n    \"DynamoDBv2Action\": \"amzn:DynamoDBv2Action\",\n    \"EmailConfiguration\": \"amzn:EmailConfiguration\",\n    \"EmailContent\": \"amzn:EmailContent\",\n    \"EmailRecipients\": \"amzn:EmailRecipients\",\n    \"Event\": \"amzn:Event\",\n    \"FirehoseAction\": \"amzn:FirehoseAction\",\n    \"GetDetectorModelAnalysisResultsRequest\": \"amzn:GetDetectorModelAnalysisResultsRequest\",\n    \"GetDetectorModelAnalysisResultsResponse\": \"amzn:GetDetectorModelAnalysisResultsResponse\",\n    \"InitializationConfiguration\": \"amzn:InitializationConfiguration\",\n    \"Input\": \"amzn:Input\",\n    \"InputConfiguration\": \"amzn:InputConfiguration\",\n    \"InputDefinition\": \"amzn:InputDefinition\",\n    \"InputIdentifier\": \"amzn:InputIdentifier\",\n    \"InputSummary\": \"amzn:InputSummary\",\n    \"IotEventsAction\": \"amzn:IotEventsAction\",\n    \"IotEventsInputIdentifier\": \"amzn:IotEventsInputIdentifier\"\
  ,\n    \"IotSiteWiseAction\": \"amzn:IotSiteWiseAction\",\n    \"IotSiteWiseAssetModelPropertyIdentifier\": \"amzn:IotSiteWiseAssetModelPropertyIdentifier\",\n    \"IotSiteWiseInputIdentifier\": \"amzn:IotSiteWiseInputIdentifier\",\n    \"IotTopicPublishAction\": \"amzn:IotTopicPublishAction\",\n    \"LambdaAction\": \"amzn:LambdaAction\",\n    \"ListAlarmModelVersionsRequest\": \"amzn:ListAlarmModelVersionsRequest\",\n    \"ListAlarmModelVersionsResponse\": \"amzn:ListAlarmModelVersionsResponse\",\n    \"ListAlarmModelsRequest\": \"amzn:ListAlarmModelsRequest\",\n    \"ListAlarmModelsResponse\": \"amzn:ListAlarmModelsResponse\",\n    \"ListDetectorModelVersionsRequest\": \"amzn:ListDetectorModelVersionsRequest\",\n    \"ListDetectorModelVersionsResponse\": \"amzn:ListDetectorModelVersionsResponse\",\n    \"ListDetectorModelsRequest\": \"amzn:ListDetectorModelsRequest\",\n    \"ListDetectorModelsResponse\": \"amzn:ListDetectorModelsResponse\",\n    \"ListInputRoutingsRequest\": \"amzn:ListInputRoutingsRequest\"\
  ,\n    \"ListInputRoutingsResponse\": \"amzn:ListInputRoutingsResponse\",\n    \"ListInputsRequest\": \"amzn:ListInputsRequest\",\n    \"ListInputsResponse\": \"amzn:ListInputsResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"LoggingOptions\": \"amzn:LoggingOptions\",\n    \"NotificationAction\": \"amzn:NotificationAction\",\n    \"NotificationTargetActions\": \"amzn:NotificationTargetActions\",\n    \"OnEnterLifecycle\": \"amzn:OnEnterLifecycle\",\n    \"OnExitLifecycle\": \"amzn:OnExitLifecycle\",\n    \"OnInputLifecycle\": \"amzn:OnInputLifecycle\",\n    \"Payload\": \"amzn:Payload\",\n    \"PutLoggingOptionsRequest\": \"amzn:PutLoggingOptionsRequest\",\n    \"RecipientDetail\": \"amzn:RecipientDetail\",\n    \"ResetTimerAction\": \"amzn:ResetTimerAction\",\n    \"RoutedResource\": \"amzn:RoutedResource\",\n    \"SMSConfiguration\": \"amzn:SMSConfiguration\",\n    \"\
  SNSTopicPublishAction\": \"amzn:SNSTopicPublishAction\",\n    \"SSOIdentity\": \"amzn:SSOIdentity\",\n    \"SetTimerAction\": \"amzn:SetTimerAction\",\n    \"SetVariableAction\": \"amzn:SetVariableAction\",\n    \"SimpleRule\": \"amzn:SimpleRule\",\n    \"SqsAction\": \"amzn:SqsAction\",\n    \"StartDetectorModelAnalysisRequest\": \"amzn:StartDetectorModelAnalysisRequest\",\n    \"StartDetectorModelAnalysisResponse\": \"amzn:StartDetectorModelAnalysisResponse\",\n    \"acknowledgeFlow\": {\n      \"@id\": \"amzn:acknowledgeFlow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"amzn:actions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalMessage\": {\n      \"@id\": \"amzn:additionalMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmActions\": {\n      \"@id\": \"amzn:alarmActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmCapabilities\"\
  : {\n      \"@id\": \"amzn:alarmCapabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmEventActions\": {\n      \"@id\": \"amzn:alarmEventActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelArn\": {\n      \"@id\": \"amzn:alarmModelArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelDescription\": {\n      \"@id\": \"amzn:alarmModelDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelName\": {\n      \"@id\": \"amzn:alarmModelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelSummaries\": {\n      \"@id\": \"amzn:alarmModelSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelVersion\": {\n      \"@id\": \"amzn:alarmModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmModelVersionSummaries\": {\n      \"@id\": \"amzn:alarmModelVersionSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alarmNotification\": {\n      \"@id\": \"amzn:alarmNotification\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"alarmRule\": {\n      \"@id\": \"amzn:alarmRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analysisId\": {\n      \"@id\": \"amzn:analysisId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analysisResults\": {\n      \"@id\": \"amzn:analysisResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetId\": {\n      \"@id\": \"amzn:assetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assetModelId\": {\n      \"@id\": \"amzn:assetModelId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amzn:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"booleanValue\": {\n      \"@id\": \"amzn:booleanValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clearTimer\": {\n      \"@id\": \"amzn:clearTimer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comparisonOperator\": {\n      \"@id\": \"amzn:comparisonOperator\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"amzn:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"amzn:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentExpression\": {\n      \"@id\": \"amzn:contentExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"amzn:creationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deliveryStreamName\": {\n      \"@id\": \"amzn:deliveryStreamName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorDebugOptions\": {\n      \"@id\": \"amzn:detectorDebugOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModel\": {\n      \"@id\": \"amzn:detectorModel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelArn\": {\n      \"@id\": \"amzn:detectorModelArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelConfiguration\": {\n      \"@id\": \"amzn:detectorModelConfiguration\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelDefinition\": {\n      \"@id\": \"amzn:detectorModelDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelDescription\": {\n      \"@id\": \"amzn:detectorModelDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelName\": {\n      \"@id\": \"amzn:detectorModelName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelSummaries\": {\n      \"@id\": \"amzn:detectorModelSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelVersion\": {\n      \"@id\": \"amzn:detectorModelVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorModelVersionSummaries\": {\n      \"@id\": \"amzn:detectorModelVersionSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disabledOnInitialization\": {\n      \"@id\": \"amzn:disabledOnInitialization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"doubleValue\": {\n      \"@id\": \"amzn:doubleValue\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"durationExpression\": {\n      \"@id\": \"amzn:durationExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamoDB\": {\n      \"@id\": \"amzn:dynamoDB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamoDBv2\": {\n      \"@id\": \"amzn:dynamoDBv2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailConfigurations\": {\n      \"@id\": \"amzn:emailConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"amzn:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entryId\": {\n      \"@id\": \"amzn:entryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"evaluationMethod\": {\n      \"@id\": \"amzn:evaluationMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"amzn:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"events\": {\n      \"@id\": \"amzn:events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firehose\": {\n      \"@id\": \"\
  amzn:firehose\",\n      \"@type\": \"xsd:string\"\n    },\n    \"from\": {\n      \"@id\": \"amzn:from\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionArn\": {\n      \"@id\": \"amzn:functionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hashKeyField\": {\n      \"@id\": \"amzn:hashKeyField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hashKeyType\": {\n      \"@id\": \"amzn:hashKeyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hashKeyValue\": {\n      \"@id\": \"amzn:hashKeyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityStoreId\": {\n      \"@id\": \"amzn:identityStoreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialStateName\": {\n      \"@id\": \"amzn:initialStateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initializationConfiguration\": {\n      \"@id\": \"amzn:initializationConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"input\": {\n      \"@id\": \"amzn:input\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"inputArn\": {\n      \"@id\": \"amzn:inputArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputConfiguration\": {\n      \"@id\": \"amzn:inputConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDefinition\": {\n      \"@id\": \"amzn:inputDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputDescription\": {\n      \"@id\": \"amzn:inputDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputIdentifier\": {\n      \"@id\": \"amzn:inputIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputName\": {\n      \"@id\": \"amzn:inputName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputProperty\": {\n      \"@id\": \"amzn:inputProperty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputSummaries\": {\n      \"@id\": \"amzn:inputSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integerValue\": {\n      \"@id\": \"amzn:integerValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotEvents\": {\n\
  \      \"@id\": \"amzn:iotEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotEventsInputIdentifier\": {\n      \"@id\": \"amzn:iotEventsInputIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotSiteWise\": {\n      \"@id\": \"amzn:iotSiteWise\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotSiteWiseAssetModelPropertyIdentifier\": {\n      \"@id\": \"amzn:iotSiteWiseAssetModelPropertyIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotSiteWiseInputIdentifier\": {\n      \"@id\": \"amzn:iotSiteWiseInputIdentifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotTopicPublish\": {\n      \"@id\": \"amzn:iotTopicPublish\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jsonPath\": {\n      \"@id\": \"amzn:jsonPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyValue\": {\n      \"@id\": \"amzn:keyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  lambda\": {\n      \"@id\": \"amzn:lambda\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaAction\": {\n      \"@id\": \"amzn:lambdaAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdateTime\": {\n      \"@id\": \"amzn:lastUpdateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"amzn:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amzn:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loggingOptions\": {\n      \"@id\": \"amzn:loggingOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mqttTopic\": {\n      \"@id\": \"amzn:mqttTopic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextState\": {\n      \"@id\": \"amzn:nextState\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationActions\": {\n      \"@id\": \"amzn:notificationActions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offsetInNanos\": {\n      \"@id\": \"amzn:offsetInNanos\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onEnter\": {\n      \"@id\": \"amzn:onEnter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onExit\": {\n      \"@id\": \"amzn:onExit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onInput\": {\n      \"@id\": \"amzn:onInput\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operation\": {\n      \"@id\": \"amzn:operation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"amzn:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payload\": {\n      \"@id\": \"amzn:payload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payloadField\": {\n      \"@id\": \"amzn:payloadField\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"propertyAlias\": {\n      \"@id\": \"amzn:propertyAlias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyId\": {\n      \"@id\": \"amzn:propertyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"propertyValue\": {\n      \"@id\": \"amzn:propertyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quality\": {\n      \"@id\": \"amzn:quality\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueUrl\": {\n      \"@id\": \"amzn:queueUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeKeyField\": {\n      \"@id\": \"amzn:rangeKeyField\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeKeyType\": {\n      \"@id\": \"amzn:rangeKeyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rangeKeyValue\": {\n      \"@id\": \"amzn:rangeKeyValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipients\": {\n      \"@id\": \"amzn:recipients\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resetTimer\": {\n      \"@id\": \"amzn:resetTimer\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routedResources\": {\n      \"@id\": \"amzn:routedResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"seconds\": {\n      \"@id\": \"amzn:seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"senderId\": {\n      \"@id\": \"amzn:senderId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"separator\": {\n      \"@id\": \"amzn:separator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"setTimer\": {\n      \"@id\": \"amzn:setTimer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"setVariable\": {\n      \"@id\": \"amzn:setVariable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"amzn:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simpleRule\": {\n      \"@id\": \"amzn:simpleRule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"smsConfigurations\": {\n      \"@id\": \"amzn:smsConfigurations\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sns\": {\n      \"@id\": \"amzn:sns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sqs\": {\n      \"@id\": \"amzn:sqs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssoIdentity\": {\n      \"@id\": \"amzn:ssoIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateName\": {\n      \"@id\": \"amzn:stateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"states\": {\n      \"@id\": \"amzn:states\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"amzn:statusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValue\": {\n      \"@id\": \"amzn:stringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subject\": {\n      \"@id\": \"amzn:subject\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tableName\": {\n      \"@id\": \"amzn:tableName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetArn\": {\n      \"@id\": \"amzn:targetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threshold\": {\n      \"@id\": \"amzn:threshold\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeInSeconds\": {\n      \"@id\": \"amzn:timeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timerName\": {\n      \"@id\": \"amzn:timerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amzn:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"to\": {\n      \"@id\": \"amzn:to\",\n      \"@type\": \"xsd:string\"\n    },\n    \"transitionEvents\": {\n      \"@id\": \"amzn:transitionEvents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useBase64\": {\n      \"@id\": \"amzn:useBase64\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\"\
  : {\n      \"@id\": \"amzn:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variableName\": {\n      \"@id\": \"amzn:variableName\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-events/refs/heads/main/json-ld/amazon-iot-events-context.jsonld
tags:
- Event Detection
- IoT
- State Machine
- Automation
- JSON-LD
- Linked Data
- Semantic Web
---
