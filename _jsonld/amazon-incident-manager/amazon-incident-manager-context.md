---
api_specs:
- filename: amazon-incident-manager-openapi-original.yml
  format: yaml
  label: AWS Systems Manager Incident Manager API
  slug: aws-ssm-incidents-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-incident-manager/refs/heads/main/openapi/amazon-incident-manager-openapi-original.yml
class_count: 100
classes:
- Action
- AddRegionAction
- AttributeValueList
- AutomationExecution
- ChatChannel
- Condition
- CreateReplicationSetInput
- CreateReplicationSetOutput
- CreateResponsePlanInput
- CreateResponsePlanOutput
- CreateTimelineEventInput
- CreateTimelineEventOutput
- DeleteIncidentRecordInput
- DeleteIncidentRecordOutput
- DeleteRegionAction
- DeleteReplicationSetInput
- DeleteReplicationSetOutput
- DeleteResourcePolicyInput
- DeleteResourcePolicyOutput
- DeleteResponsePlanInput
- DeleteResponsePlanOutput
- DeleteTimelineEventInput
- DeleteTimelineEventOutput
- DynamicSsmParameterValue
- DynamicSsmParameters
- EmptyChatChannel
- EventReference
- EventSummary
- Filter
- GetIncidentRecordInput
- GetIncidentRecordOutput
- GetReplicationSetInput
- GetReplicationSetOutput
- GetResourcePoliciesInput
- GetResourcePoliciesOutput
- GetResponsePlanInput
- GetResponsePlanOutput
- GetTimelineEventInput
- GetTimelineEventOutput
- IncidentRecord
- IncidentRecordSource
- IncidentRecordSummary
- IncidentTemplate
- Integration
- ItemIdentifier
- ItemValue
- ListIncidentRecordsInput
- ListIncidentRecordsOutput
- ListRelatedItemsInput
- ListRelatedItemsOutput
- ListReplicationSetsInput
- ListReplicationSetsOutput
- ListResponsePlansInput
- ListResponsePlansOutput
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListTimelineEventsInput
- ListTimelineEventsOutput
- NotificationTargetItem
- PagerDutyConfiguration
- PagerDutyIncidentConfiguration
- PagerDutyIncidentDetail
- PutResourcePolicyInput
- PutResourcePolicyOutput
- RegionInfo
- RegionInfoMap
- RegionMapInput
- RegionMapInputValue
- RelatedItem
- RelatedItemsUpdate
- ReplicationSet
- ResourcePolicy
- ResponsePlanSummary
- SsmAutomation
- SsmParameters
- StartIncidentInput
- StartIncidentOutput
- TagMap
- TagMapUpdate
- TagResourceRequest
- TagResourceResponse
- TimelineEvent
- TriggerDetails
- UntagResourceRequest
- UntagResourceResponse
- UpdateDeletionProtectionInput
- UpdateDeletionProtectionOutput
- UpdateIncidentRecordInput
- UpdateIncidentRecordOutput
- UpdateRelatedItemsInput
- UpdateRelatedItemsOutput
- UpdateReplicationSetAction
- UpdateReplicationSetInput
- UpdateReplicationSetOutput
- UpdateResponsePlanInput
- UpdateResponsePlanOutput
- UpdateTimelineEventInput
- UpdateTimelineEventOutput
- name
- url
context_file: json-ld/amazon-incident-manager-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-incident-manager/refs/heads/main/json-ld/amazon-incident-manager-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Incident Manager from Amazon Incident Manager.
layout: jsonld
name: Amazon Incident Manager Context
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
  name: actions
  type: string
- container: ''
  name: addRegionAction
  type: string
- container: ''
  name: after
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: autoResolve
  type: string
- container: ''
  name: automationExecutions
  type: string
- container: ''
  name: before
  type: string
- container: ''
  name: chatChannel
  type: string
- container: ''
  name: chatbotSns
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: createdBy
  type: string
- container: ''
  name: createdTime
  type: string
- container: ''
  name: creationTime
  type: string
- container: ''
  name: dedupeString
  type: string
- container: ''
  name: deleteRegionAction
  type: string
- container: ''
  name: deletionProtected
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: documentName
  type: string
- container: ''
  name: documentVersion
  type: string
- container: ''
  name: dynamicParameters
  type: string
- container: ''
  name: empty
  type: string
- container: ''
  name: engagements
  type: string
- container: ''
  name: equals
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: eventData
  type: string
- container: ''
  name: eventId
  type: string
- container: ''
  name: eventReferences
  type: string
- container: ''
  name: eventSummaries
  type: string
- container: ''
  name: eventTime
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventUpdatedTime
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: generatedId
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: impact
  type: string
- container: ''
  name: incidentRecord
  type: string
- container: ''
  name: incidentRecordArn
  type: string
- container: ''
  name: incidentRecordSource
  type: string
- container: ''
  name: incidentRecordSummaries
  type: string
- container: ''
  name: incidentTags
  type: string
- container: ''
  name: incidentTemplate
  type: string
- container: ''
  name: incidentTemplateDedupeString
  type: string
- container: ''
  name: incidentTemplateImpact
  type: string
- container: ''
  name: incidentTemplateNotificationTargets
  type: string
- container: ''
  name: incidentTemplateSummary
  type: string
- container: ''
  name: incidentTemplateTags
  type: string
- container: ''
  name: incidentTemplateTitle
  type: string
- container: ''
  name: integerValues
  type: string
- container: ''
  name: integrations
  type: string
- container: ''
  name: invokedBy
  type: string
- container: ''
  name: itemToAdd
  type: string
- container: ''
  name: itemToRemove
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: lastModifiedBy
  type: string
- container: ''
  name: lastModifiedTime
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: metricDefinition
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: notificationTargets
  type: string
- container: ''
  name: pagerDutyConfiguration
  type: string
- container: ''
  name: pagerDutyIncidentConfiguration
  type: string
- container: ''
  name: pagerDutyIncidentDetail
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: policyDocument
  type: string
- container: ''
  name: policyId
  type: string
- container: ''
  name: ramResourceShareRegion
  type: string
- container: ''
  name: rawData
  type: string
- container: ''
  name: regionMap
  type: string
- container: ''
  name: regionName
  type: string
- container: ''
  name: regions
  type: string
- container: ''
  name: relatedItemId
  type: string
- container: ''
  name: relatedItems
  type: string
- container: ''
  name: relatedItemsUpdate
  type: string
- container: ''
  name: replicationSet
  type: string
- container: ''
  name: replicationSetArns
  type: string
- container: ''
  name: resolvedTime
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: resourcePolicies
  type: string
- container: ''
  name: responsePlanArn
  type: string
- container: ''
  name: responsePlanSummaries
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: secretId
  type: string
- container: ''
  name: serviceId
  type: string
- container: ''
  name: snsTopicArn
  type: string
- container: ''
  name: sortBy
  type: string
- container: ''
  name: sortOrder
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sseKmsKeyId
  type: string
- container: ''
  name: ssmAutomation
  type: string
- container: ''
  name: ssmExecutionArn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: statusUpdateDateTime
  type: string
- container: ''
  name: stringValues
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetAccount
  type: string
- container: ''
  name: timestamp
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: triggerArn
  type: string
- container: ''
  name: triggerDetails
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: variable
  type: string
property_count: 108
provider_name: Amazon Incident Manager
provider_slug: amazon-incident-manager
slug: amazon-incident-manager-context
source_filename: amazon-incident-manager-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Action\": \"amzn:Action\",\n    \"AddRegionAction\": \"amzn:AddRegionAction\",\n    \"AttributeValueList\": \"amzn:AttributeValueList\",\n    \"AutomationExecution\": \"amzn:AutomationExecution\",\n    \"ChatChannel\": \"amzn:ChatChannel\",\n    \"Condition\": \"amzn:Condition\",\n    \"CreateReplicationSetInput\": \"amzn:CreateReplicationSetInput\",\n    \"CreateReplicationSetOutput\": \"amzn:CreateReplicationSetOutput\",\n    \"CreateResponsePlanInput\": \"amzn:CreateResponsePlanInput\",\n    \"CreateResponsePlanOutput\": \"amzn:CreateResponsePlanOutput\",\n    \"CreateTimelineEventInput\": \"amzn:CreateTimelineEventInput\",\n    \"CreateTimelineEventOutput\": \"amzn:CreateTimelineEventOutput\",\n    \"DeleteIncidentRecordInput\"\
  : \"amzn:DeleteIncidentRecordInput\",\n    \"DeleteIncidentRecordOutput\": \"amzn:DeleteIncidentRecordOutput\",\n    \"DeleteRegionAction\": \"amzn:DeleteRegionAction\",\n    \"DeleteReplicationSetInput\": \"amzn:DeleteReplicationSetInput\",\n    \"DeleteReplicationSetOutput\": \"amzn:DeleteReplicationSetOutput\",\n    \"DeleteResourcePolicyInput\": \"amzn:DeleteResourcePolicyInput\",\n    \"DeleteResourcePolicyOutput\": \"amzn:DeleteResourcePolicyOutput\",\n    \"DeleteResponsePlanInput\": \"amzn:DeleteResponsePlanInput\",\n    \"DeleteResponsePlanOutput\": \"amzn:DeleteResponsePlanOutput\",\n    \"DeleteTimelineEventInput\": \"amzn:DeleteTimelineEventInput\",\n    \"DeleteTimelineEventOutput\": \"amzn:DeleteTimelineEventOutput\",\n    \"DynamicSsmParameterValue\": \"amzn:DynamicSsmParameterValue\",\n    \"DynamicSsmParameters\": \"amzn:DynamicSsmParameters\",\n    \"EmptyChatChannel\": \"amzn:EmptyChatChannel\",\n    \"EventReference\": \"amzn:EventReference\",\n    \"EventSummary\"\
  : \"amzn:EventSummary\",\n    \"Filter\": \"amzn:Filter\",\n    \"GetIncidentRecordInput\": \"amzn:GetIncidentRecordInput\",\n    \"GetIncidentRecordOutput\": \"amzn:GetIncidentRecordOutput\",\n    \"GetReplicationSetInput\": \"amzn:GetReplicationSetInput\",\n    \"GetReplicationSetOutput\": \"amzn:GetReplicationSetOutput\",\n    \"GetResourcePoliciesInput\": \"amzn:GetResourcePoliciesInput\",\n    \"GetResourcePoliciesOutput\": \"amzn:GetResourcePoliciesOutput\",\n    \"GetResponsePlanInput\": \"amzn:GetResponsePlanInput\",\n    \"GetResponsePlanOutput\": \"amzn:GetResponsePlanOutput\",\n    \"GetTimelineEventInput\": \"amzn:GetTimelineEventInput\",\n    \"GetTimelineEventOutput\": \"amzn:GetTimelineEventOutput\",\n    \"IncidentRecord\": \"amzn:IncidentRecord\",\n    \"IncidentRecordSource\": \"amzn:IncidentRecordSource\",\n    \"IncidentRecordSummary\": \"amzn:IncidentRecordSummary\",\n    \"IncidentTemplate\": \"amzn:IncidentTemplate\",\n    \"Integration\": \"amzn:Integration\",\n\
  \    \"ItemIdentifier\": \"amzn:ItemIdentifier\",\n    \"ItemValue\": \"amzn:ItemValue\",\n    \"ListIncidentRecordsInput\": \"amzn:ListIncidentRecordsInput\",\n    \"ListIncidentRecordsOutput\": \"amzn:ListIncidentRecordsOutput\",\n    \"ListRelatedItemsInput\": \"amzn:ListRelatedItemsInput\",\n    \"ListRelatedItemsOutput\": \"amzn:ListRelatedItemsOutput\",\n    \"ListReplicationSetsInput\": \"amzn:ListReplicationSetsInput\",\n    \"ListReplicationSetsOutput\": \"amzn:ListReplicationSetsOutput\",\n    \"ListResponsePlansInput\": \"amzn:ListResponsePlansInput\",\n    \"ListResponsePlansOutput\": \"amzn:ListResponsePlansOutput\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"ListTimelineEventsInput\": \"amzn:ListTimelineEventsInput\",\n    \"ListTimelineEventsOutput\": \"amzn:ListTimelineEventsOutput\",\n    \"NotificationTargetItem\": \"amzn:NotificationTargetItem\",\n    \"\
  PagerDutyConfiguration\": \"amzn:PagerDutyConfiguration\",\n    \"PagerDutyIncidentConfiguration\": \"amzn:PagerDutyIncidentConfiguration\",\n    \"PagerDutyIncidentDetail\": \"amzn:PagerDutyIncidentDetail\",\n    \"PutResourcePolicyInput\": \"amzn:PutResourcePolicyInput\",\n    \"PutResourcePolicyOutput\": \"amzn:PutResourcePolicyOutput\",\n    \"RegionInfo\": \"amzn:RegionInfo\",\n    \"RegionInfoMap\": \"amzn:RegionInfoMap\",\n    \"RegionMapInput\": \"amzn:RegionMapInput\",\n    \"RegionMapInputValue\": \"amzn:RegionMapInputValue\",\n    \"RelatedItem\": \"amzn:RelatedItem\",\n    \"RelatedItemsUpdate\": \"amzn:RelatedItemsUpdate\",\n    \"ReplicationSet\": \"amzn:ReplicationSet\",\n    \"ResourcePolicy\": \"amzn:ResourcePolicy\",\n    \"ResponsePlanSummary\": \"amzn:ResponsePlanSummary\",\n    \"SsmAutomation\": \"amzn:SsmAutomation\",\n    \"SsmParameters\": \"amzn:SsmParameters\",\n    \"StartIncidentInput\": \"amzn:StartIncidentInput\",\n    \"StartIncidentOutput\": \"amzn:StartIncidentOutput\"\
  ,\n    \"TagMap\": \"amzn:TagMap\",\n    \"TagMapUpdate\": \"amzn:TagMapUpdate\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"TagResourceResponse\": \"amzn:TagResourceResponse\",\n    \"TimelineEvent\": \"amzn:TimelineEvent\",\n    \"TriggerDetails\": \"amzn:TriggerDetails\",\n    \"UntagResourceRequest\": \"amzn:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amzn:UntagResourceResponse\",\n    \"UpdateDeletionProtectionInput\": \"amzn:UpdateDeletionProtectionInput\",\n    \"UpdateDeletionProtectionOutput\": \"amzn:UpdateDeletionProtectionOutput\",\n    \"UpdateIncidentRecordInput\": \"amzn:UpdateIncidentRecordInput\",\n    \"UpdateIncidentRecordOutput\": \"amzn:UpdateIncidentRecordOutput\",\n    \"UpdateRelatedItemsInput\": \"amzn:UpdateRelatedItemsInput\",\n    \"UpdateRelatedItemsOutput\": \"amzn:UpdateRelatedItemsOutput\",\n    \"UpdateReplicationSetAction\": \"amzn:UpdateReplicationSetAction\",\n    \"UpdateReplicationSetInput\": \"amzn:UpdateReplicationSetInput\"\
  ,\n    \"UpdateReplicationSetOutput\": \"amzn:UpdateReplicationSetOutput\",\n    \"UpdateResponsePlanInput\": \"amzn:UpdateResponsePlanInput\",\n    \"UpdateResponsePlanOutput\": \"amzn:UpdateResponsePlanOutput\",\n    \"UpdateTimelineEventInput\": \"amzn:UpdateTimelineEventInput\",\n    \"UpdateTimelineEventOutput\": \"amzn:UpdateTimelineEventOutput\",\n    \"actions\": {\n      \"@id\": \"amzn:actions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addRegionAction\": {\n      \"@id\": \"amzn:addRegionAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"after\": {\n      \"@id\": \"amzn:after\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoResolve\": {\n      \"@id\": \"amzn:autoResolve\",\n      \"@type\": \"xsd:string\"\n    },\n    \"automationExecutions\": {\n      \"@id\": \"amzn:automationExecutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"before\": {\n      \"@id\": \"\
  amzn:before\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chatChannel\": {\n      \"@id\": \"amzn:chatChannel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chatbotSns\": {\n      \"@id\": \"amzn:chatbotSns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amzn:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"amzn:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdBy\": {\n      \"@id\": \"amzn:createdBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"amzn:createdTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTime\": {\n      \"@id\": \"amzn:creationTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dedupeString\": {\n      \"@id\": \"amzn:dedupeString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteRegionAction\": {\n      \"@id\": \"amzn:deleteRegionAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deletionProtected\"\
  : {\n      \"@id\": \"amzn:deletionProtected\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amzn:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentName\": {\n      \"@id\": \"amzn:documentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"documentVersion\": {\n      \"@id\": \"amzn:documentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dynamicParameters\": {\n      \"@id\": \"amzn:dynamicParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"empty\": {\n      \"@id\": \"amzn:empty\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engagements\": {\n      \"@id\": \"amzn:engagements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"equals\": {\n      \"@id\": \"amzn:equals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"event\": {\n      \"@id\": \"amzn:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventData\": {\n      \"@id\": \"amzn:eventData\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"eventId\": {\n      \"@id\": \"amzn:eventId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventReferences\": {\n      \"@id\": \"amzn:eventReferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSummaries\": {\n      \"@id\": \"amzn:eventSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTime\": {\n      \"@id\": \"amzn:eventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"amzn:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventUpdatedTime\": {\n      \"@id\": \"amzn:eventUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"amzn:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatedId\": {\n      \"@id\": \"amzn:generatedId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amzn:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identifier\": {\n      \"@id\": \"amzn:identifier\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"impact\": {\n      \"@id\": \"amzn:impact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentRecord\": {\n      \"@id\": \"amzn:incidentRecord\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentRecordArn\": {\n      \"@id\": \"amzn:incidentRecordArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentRecordSource\": {\n      \"@id\": \"amzn:incidentRecordSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentRecordSummaries\": {\n      \"@id\": \"amzn:incidentRecordSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTags\": {\n      \"@id\": \"amzn:incidentTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplate\": {\n      \"@id\": \"amzn:incidentTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateDedupeString\": {\n      \"@id\": \"amzn:incidentTemplateDedupeString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateImpact\": {\n      \"@id\": \"amzn:incidentTemplateImpact\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateNotificationTargets\": {\n      \"@id\": \"amzn:incidentTemplateNotificationTargets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateSummary\": {\n      \"@id\": \"amzn:incidentTemplateSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateTags\": {\n      \"@id\": \"amzn:incidentTemplateTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incidentTemplateTitle\": {\n      \"@id\": \"amzn:incidentTemplateTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integerValues\": {\n      \"@id\": \"amzn:integerValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"integrations\": {\n      \"@id\": \"amzn:integrations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"invokedBy\": {\n      \"@id\": \"amzn:invokedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemToAdd\": {\n      \"@id\": \"amzn:itemToAdd\",\n      \"@type\": \"xsd:string\"\n    },\n    \"itemToRemove\": {\n\
  \      \"@id\": \"amzn:itemToRemove\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedBy\": {\n      \"@id\": \"amzn:lastModifiedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedTime\": {\n      \"@id\": \"amzn:lastModifiedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metricDefinition\": {\n      \"@id\": \"amzn:metricDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notificationTargets\": {\n      \"@id\": \"amzn:notificationTargets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagerDutyConfiguration\": {\n      \"@id\": \"amzn:pagerDutyConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagerDutyIncidentConfiguration\"\
  : {\n      \"@id\": \"amzn:pagerDutyIncidentConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pagerDutyIncidentDetail\": {\n      \"@id\": \"amzn:pagerDutyIncidentDetail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"amzn:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"amzn:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyDocument\": {\n      \"@id\": \"amzn:policyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyId\": {\n      \"@id\": \"amzn:policyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ramResourceShareRegion\": {\n      \"@id\": \"amzn:ramResourceShareRegion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rawData\": {\n      \"@id\": \"amzn:rawData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionMap\": {\n      \"@id\": \"amzn:regionMap\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionName\": {\n      \"@id\": \"amzn:regionName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"amzn:regions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedItemId\": {\n      \"@id\": \"amzn:relatedItemId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedItems\": {\n      \"@id\": \"amzn:relatedItems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedItemsUpdate\": {\n      \"@id\": \"amzn:relatedItemsUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replicationSet\": {\n      \"@id\": \"amzn:replicationSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"replicationSetArns\": {\n      \"@id\": \"amzn:replicationSetArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedTime\": {\n      \"@id\": \"amzn:resolvedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\": \"amzn:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"amzn:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"resourcePolicies\": {\n      \"@id\": \"amzn:resourcePolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responsePlanArn\": {\n      \"@id\": \"amzn:responsePlanArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responsePlanSummaries\": {\n      \"@id\": \"amzn:responsePlanSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretId\": {\n      \"@id\": \"amzn:secretId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceId\": {\n      \"@id\": \"amzn:serviceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snsTopicArn\": {\n      \"@id\": \"amzn:snsTopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortBy\": {\n      \"@id\": \"amzn:sortBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortOrder\": {\n      \"@id\": \"amzn:sortOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amzn:source\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"sseKmsKeyId\": {\n      \"@id\": \"amzn:sseKmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssmAutomation\": {\n      \"@id\": \"amzn:ssmAutomation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ssmExecutionArn\": {\n      \"@id\": \"amzn:ssmExecutionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"amzn:statusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusUpdateDateTime\": {\n      \"@id\": \"amzn:statusUpdateDateTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stringValues\": {\n      \"@id\": \"amzn:stringValues\",\n      \"@type\": \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"amzn:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAccount\": {\n      \"@id\": \"\
  amzn:targetAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timestamp\": {\n      \"@id\": \"amzn:timestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"amzn:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerArn\": {\n      \"@id\": \"amzn:triggerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerDetails\": {\n      \"@id\": \"amzn:triggerDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variable\": {\n      \"@id\": \"amzn:variable\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-incident-manager/refs/heads/main/json-ld/amazon-incident-manager-context.jsonld
tags:
- Automation
- DevOps
- Incident Management
- Operations
- JSON-LD
- Linked Data
- Semantic Web
---
