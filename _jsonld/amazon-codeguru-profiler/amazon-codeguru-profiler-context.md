---
api_specs:
- filename: amazon-codeguru-profiler-openapi-original.yaml
  format: yaml
  label: Amazon CodeGuru Profiler API
  slug: amazon-codeguru-profiler-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-profiler/refs/heads/main/openapi/amazon-codeguru-profiler-openapi-original.yaml
class_count: 71
classes:
- AddNotificationChannelsResponse
- Channel
- BatchGetFrameMetricDataResponse
- FrameMetric
- ConfigureAgentResponse
- CreateProfilingGroupResponse
- DeleteProfilingGroupResponse
- DescribeProfilingGroupResponse
- GetFindingsReportAccountSummaryResponse
- GetNotificationConfigurationResponse
- GetPolicyResponse
- GetProfileResponse
- GetRecommendationsResponse
- ListFindingsReportsResponse
- ListProfileTimesResponse
- ListProfilingGroupsResponse
- ListTagsForResourceResponse
- PostAgentProfileResponse
- PutPermissionResponse
- RemoveNotificationChannelResponse
- RemovePermissionResponse
- SubmitFeedbackResponse
- TagResourceResponse
- UntagResourceResponse
- UpdateProfilingGroupResponse
- AddNotificationChannelsRequest
- NotificationConfiguration
- AgentParameters
- AgentConfiguration
- AgentOrchestrationConfig
- AggregatedProfileTime
- Anomaly
- Metric
- UserFeedback
- AnomalyInstance
- BatchGetFrameMetricDataRequest
- UnprocessedEndTimeMap
- Metadata
- ConfigureAgentRequest
- TagsMap
- CreateProfilingGroupRequest
- ProfilingGroupDescription
- DeleteProfilingGroupRequest
- DescribeProfilingGroupRequest
- FindingsReportSummary
- FrameMetricDatum
- GetFindingsReportAccountSummaryRequest
- GetNotificationConfigurationRequest
- GetPolicyRequest
- GetProfileRequest
- GetRecommendationsRequest
- ListFindingsReportsRequest
- TimestampStructure
- ListProfileTimesRequest
- ListProfilingGroupsRequest
- ListTagsForResourceRequest
- Match
- Pattern
- PostAgentProfileRequest
- ProfileTime
- ProfilingStatus
- PutPermissionRequest
- Recommendation
- RemoveNotificationChannelRequest
- RemovePermissionRequest
- SubmitFeedbackRequest
- TagResourceRequest
- UntagResourceRequest
- UpdateProfilingGroupRequest
- name
- description
context_file: json-ld/amazon-codeguru-profiler-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-profiler/refs/heads/main/json-ld/amazon-codeguru-profiler-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codeguru Profiler from Amazon CodeGuru Profiler.
layout: jsonld
name: Amazon Codeguru Profiler Context
namespaces:
- prefix: amazon-code-guru-profiler
  uri: https://amazon-code-guru-profiler.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: notificationConfiguration
  type: string
- container: ''
  name: eventPublishers
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: endTimes
  type: string
- container: ''
  name: frameMetricData
  type: string
- container: ''
  name: resolution
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: unprocessedEndTimes
  type: string
- container: ''
  name: frameName
  type: string
- container: ''
  name: threadStates
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: configuration
  type: string
- container: ''
  name: profilingGroup
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: reportSummaries
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: profile
  type: string
- container: ''
  name: anomalies
  type: string
- container: ''
  name: profileEndTime
  type: string
- container: ''
  name: profileStartTime
  type: string
- container: ''
  name: profilingGroupName
  type: string
- container: ''
  name: recommendations
  type: string
- container: ''
  name: findingsReportSummaries
  type: string
- container: ''
  name: profileTimes
  type: string
- container: ''
  name: profilingGroupNames
  type: string
- container: ''
  name: profilingGroups
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: channels
  type: string
- container: ''
  name: agentParameters
  type: string
- container: ''
  name: periodInSeconds
  type: string
- container: ''
  name: shouldProfile
  type: string
- container: ''
  name: profilingEnabled
  type: string
- container: ''
  name: period
  type: string
- container: ''
  name: start
  type: string
- container: ''
  name: instances
  type: string
- container: ''
  name: metric
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: userFeedback
  type: string
- container: ''
  name: frameMetrics
  type: string
- container: ''
  name: fleetInstanceId
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: agentOrchestrationConfig
  type: string
- container: ''
  name: computePlatform
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: profilingStatus
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: totalNumberOfFindings
  type: string
- container: ''
  name: frameMetric
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: frameAddress
  type: string
- container: ''
  name: targetFramesIndex
  type: string
- container: ''
  name: thresholdBreachValue
  type: string
- container: ''
  name: countersToAggregate
  type: string
- container: ''
  name: resolutionSteps
  type: string
- container: ''
  name: targetFrames
  type: string
- container: ''
  name: thresholdPercent
  type: string
- container: ''
  name: agentProfile
  type: string
- container: ''
  name: latestAgentOrchestratedAt
  type: string
- container: ''
  name: latestAgentProfileReportedAt
  type: string
- container: ''
  name: latestAggregatedProfile
  type: string
- container: ''
  name: principals
  type: string
- container: ''
  name: allMatchesCount
  type: string
- container: ''
  name: allMatchesSum
  type: string
- container: ''
  name: pattern
  type: string
- container: ''
  name: topMatches
  type: string
- container: ''
  name: comment
  type: string
property_count: 71
provider_name: Amazon CodeGuru Profiler
provider_slug: amazon-codeguru-profiler
slug: amazon-codeguru-profiler-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-guru-profiler\": \"https://amazon-code-guru-profiler.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddNotificationChannelsResponse\": \"amazon-code-guru-profiler:AddNotificationChannelsResponse\",\n    \"Channel\": \"amazon-code-guru-profiler:Channel\",\n    \"BatchGetFrameMetricDataResponse\": \"amazon-code-guru-profiler:BatchGetFrameMetricDataResponse\",\n    \"FrameMetric\": \"amazon-code-guru-profiler:FrameMetric\",\n    \"ConfigureAgentResponse\": \"amazon-code-guru-profiler:ConfigureAgentResponse\",\n    \"CreateProfilingGroupResponse\": \"amazon-code-guru-profiler:CreateProfilingGroupResponse\",\n    \"DeleteProfilingGroupResponse\": \"amazon-code-guru-profiler:DeleteProfilingGroupResponse\",\n    \"DescribeProfilingGroupResponse\": \"amazon-code-guru-profiler:DescribeProfilingGroupResponse\"\
  ,\n    \"GetFindingsReportAccountSummaryResponse\": \"amazon-code-guru-profiler:GetFindingsReportAccountSummaryResponse\",\n    \"GetNotificationConfigurationResponse\": \"amazon-code-guru-profiler:GetNotificationConfigurationResponse\",\n    \"GetPolicyResponse\": \"amazon-code-guru-profiler:GetPolicyResponse\",\n    \"GetProfileResponse\": \"amazon-code-guru-profiler:GetProfileResponse\",\n    \"GetRecommendationsResponse\": \"amazon-code-guru-profiler:GetRecommendationsResponse\",\n    \"ListFindingsReportsResponse\": \"amazon-code-guru-profiler:ListFindingsReportsResponse\",\n    \"ListProfileTimesResponse\": \"amazon-code-guru-profiler:ListProfileTimesResponse\",\n    \"ListProfilingGroupsResponse\": \"amazon-code-guru-profiler:ListProfilingGroupsResponse\",\n    \"ListTagsForResourceResponse\": \"amazon-code-guru-profiler:ListTagsForResourceResponse\",\n    \"PostAgentProfileResponse\": \"amazon-code-guru-profiler:PostAgentProfileResponse\",\n    \"PutPermissionResponse\": \"amazon-code-guru-profiler:PutPermissionResponse\"\
  ,\n    \"RemoveNotificationChannelResponse\": \"amazon-code-guru-profiler:RemoveNotificationChannelResponse\",\n    \"RemovePermissionResponse\": \"amazon-code-guru-profiler:RemovePermissionResponse\",\n    \"SubmitFeedbackResponse\": \"amazon-code-guru-profiler:SubmitFeedbackResponse\",\n    \"TagResourceResponse\": \"amazon-code-guru-profiler:TagResourceResponse\",\n    \"UntagResourceResponse\": \"amazon-code-guru-profiler:UntagResourceResponse\",\n    \"UpdateProfilingGroupResponse\": \"amazon-code-guru-profiler:UpdateProfilingGroupResponse\",\n    \"AddNotificationChannelsRequest\": \"amazon-code-guru-profiler:AddNotificationChannelsRequest\",\n    \"NotificationConfiguration\": \"amazon-code-guru-profiler:NotificationConfiguration\",\n    \"AgentParameters\": \"amazon-code-guru-profiler:AgentParameters\",\n    \"AgentConfiguration\": \"amazon-code-guru-profiler:AgentConfiguration\",\n    \"AgentOrchestrationConfig\": \"amazon-code-guru-profiler:AgentOrchestrationConfig\",\n    \"\
  AggregatedProfileTime\": \"amazon-code-guru-profiler:AggregatedProfileTime\",\n    \"Anomaly\": \"amazon-code-guru-profiler:Anomaly\",\n    \"Metric\": \"amazon-code-guru-profiler:Metric\",\n    \"UserFeedback\": \"amazon-code-guru-profiler:UserFeedback\",\n    \"AnomalyInstance\": \"amazon-code-guru-profiler:AnomalyInstance\",\n    \"BatchGetFrameMetricDataRequest\": \"amazon-code-guru-profiler:BatchGetFrameMetricDataRequest\",\n    \"UnprocessedEndTimeMap\": \"amazon-code-guru-profiler:UnprocessedEndTimeMap\",\n    \"Metadata\": \"amazon-code-guru-profiler:Metadata\",\n    \"ConfigureAgentRequest\": \"amazon-code-guru-profiler:ConfigureAgentRequest\",\n    \"TagsMap\": \"amazon-code-guru-profiler:TagsMap\",\n    \"CreateProfilingGroupRequest\": \"amazon-code-guru-profiler:CreateProfilingGroupRequest\",\n    \"ProfilingGroupDescription\": \"amazon-code-guru-profiler:ProfilingGroupDescription\",\n    \"DeleteProfilingGroupRequest\": \"amazon-code-guru-profiler:DeleteProfilingGroupRequest\"\
  ,\n    \"DescribeProfilingGroupRequest\": \"amazon-code-guru-profiler:DescribeProfilingGroupRequest\",\n    \"FindingsReportSummary\": \"amazon-code-guru-profiler:FindingsReportSummary\",\n    \"FrameMetricDatum\": \"amazon-code-guru-profiler:FrameMetricDatum\",\n    \"GetFindingsReportAccountSummaryRequest\": \"amazon-code-guru-profiler:GetFindingsReportAccountSummaryRequest\",\n    \"GetNotificationConfigurationRequest\": \"amazon-code-guru-profiler:GetNotificationConfigurationRequest\",\n    \"GetPolicyRequest\": \"amazon-code-guru-profiler:GetPolicyRequest\",\n    \"GetProfileRequest\": \"amazon-code-guru-profiler:GetProfileRequest\",\n    \"GetRecommendationsRequest\": \"amazon-code-guru-profiler:GetRecommendationsRequest\",\n    \"ListFindingsReportsRequest\": \"amazon-code-guru-profiler:ListFindingsReportsRequest\",\n    \"TimestampStructure\": \"amazon-code-guru-profiler:TimestampStructure\",\n    \"ListProfileTimesRequest\": \"amazon-code-guru-profiler:ListProfileTimesRequest\"\
  ,\n    \"ListProfilingGroupsRequest\": \"amazon-code-guru-profiler:ListProfilingGroupsRequest\",\n    \"ListTagsForResourceRequest\": \"amazon-code-guru-profiler:ListTagsForResourceRequest\",\n    \"Match\": \"amazon-code-guru-profiler:Match\",\n    \"Pattern\": \"amazon-code-guru-profiler:Pattern\",\n    \"PostAgentProfileRequest\": \"amazon-code-guru-profiler:PostAgentProfileRequest\",\n    \"ProfileTime\": \"amazon-code-guru-profiler:ProfileTime\",\n    \"ProfilingStatus\": \"amazon-code-guru-profiler:ProfilingStatus\",\n    \"PutPermissionRequest\": \"amazon-code-guru-profiler:PutPermissionRequest\",\n    \"Recommendation\": \"amazon-code-guru-profiler:Recommendation\",\n    \"RemoveNotificationChannelRequest\": \"amazon-code-guru-profiler:RemoveNotificationChannelRequest\",\n    \"RemovePermissionRequest\": \"amazon-code-guru-profiler:RemovePermissionRequest\",\n    \"SubmitFeedbackRequest\": \"amazon-code-guru-profiler:SubmitFeedbackRequest\",\n    \"TagResourceRequest\": \"amazon-code-guru-profiler:TagResourceRequest\"\
  ,\n    \"UntagResourceRequest\": \"amazon-code-guru-profiler:UntagResourceRequest\",\n    \"UpdateProfilingGroupRequest\": \"amazon-code-guru-profiler:UpdateProfilingGroupRequest\",\n    \"notificationConfiguration\": {\n      \"@id\": \"amazon-code-guru-profiler:notificationConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventPublishers\": {\n      \"@id\": \"amazon-code-guru-profiler:eventPublishers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amazon-code-guru-profiler:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"amazon-code-guru-profiler:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amazon-code-guru-profiler:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTimes\": {\n      \"@id\": \"amazon-code-guru-profiler:endTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frameMetricData\": {\n      \"@id\": \"amazon-code-guru-profiler:frameMetricData\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"resolution\": {\n      \"@id\": \"amazon-code-guru-profiler:resolution\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amazon-code-guru-profiler:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unprocessedEndTimes\": {\n      \"@id\": \"amazon-code-guru-profiler:unprocessedEndTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frameName\": {\n      \"@id\": \"amazon-code-guru-profiler:frameName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"threadStates\": {\n      \"@id\": \"amazon-code-guru-profiler:threadStates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amazon-code-guru-profiler:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configuration\": {\n      \"@id\": \"amazon-code-guru-profiler:configuration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profilingGroup\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingGroup\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-guru-profiler:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportSummaries\": {\n      \"@id\": \"amazon-code-guru-profiler:reportSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"amazon-code-guru-profiler:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"amazon-code-guru-profiler:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"amazon-code-guru-profiler:profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"anomalies\": {\n      \"@id\": \"amazon-code-guru-profiler:anomalies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileEndTime\": {\n      \"@id\": \"amazon-code-guru-profiler:profileEndTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileStartTime\": {\n      \"@id\": \"amazon-code-guru-profiler:profileStartTime\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"profilingGroupName\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendations\": {\n      \"@id\": \"amazon-code-guru-profiler:recommendations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingsReportSummaries\": {\n      \"@id\": \"amazon-code-guru-profiler:findingsReportSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profileTimes\": {\n      \"@id\": \"amazon-code-guru-profiler:profileTimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profilingGroupNames\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingGroupNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profilingGroups\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amazon-code-guru-profiler:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"amazon-code-guru-profiler:channels\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"agentParameters\": {\n      \"@id\": \"amazon-code-guru-profiler:agentParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"periodInSeconds\": {\n      \"@id\": \"amazon-code-guru-profiler:periodInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shouldProfile\": {\n      \"@id\": \"amazon-code-guru-profiler:shouldProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profilingEnabled\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"period\": {\n      \"@id\": \"amazon-code-guru-profiler:period\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"amazon-code-guru-profiler:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instances\": {\n      \"@id\": \"amazon-code-guru-profiler:instances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"amazon-code-guru-profiler:metric\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"amazon-code-guru-profiler:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userFeedback\": {\n      \"@id\": \"amazon-code-guru-profiler:userFeedback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frameMetrics\": {\n      \"@id\": \"amazon-code-guru-profiler:frameMetrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetInstanceId\": {\n      \"@id\": \"amazon-code-guru-profiler:fleetInstanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amazon-code-guru-profiler:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentOrchestrationConfig\": {\n      \"@id\": \"amazon-code-guru-profiler:agentOrchestrationConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"computePlatform\": {\n      \"@id\": \"amazon-code-guru-profiler:computePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amazon-code-guru-profiler:arn\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amazon-code-guru-profiler:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"profilingStatus\": {\n      \"@id\": \"amazon-code-guru-profiler:profilingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"amazon-code-guru-profiler:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalNumberOfFindings\": {\n      \"@id\": \"amazon-code-guru-profiler:totalNumberOfFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frameMetric\": {\n      \"@id\": \"amazon-code-guru-profiler:frameMetric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amazon-code-guru-profiler:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amazon-code-guru-profiler:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frameAddress\": {\n      \"@id\": \"amazon-code-guru-profiler:frameAddress\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"targetFramesIndex\": {\n      \"@id\": \"amazon-code-guru-profiler:targetFramesIndex\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thresholdBreachValue\": {\n      \"@id\": \"amazon-code-guru-profiler:thresholdBreachValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countersToAggregate\": {\n      \"@id\": \"amazon-code-guru-profiler:countersToAggregate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"resolutionSteps\": {\n      \"@id\": \"amazon-code-guru-profiler:resolutionSteps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetFrames\": {\n      \"@id\": \"amazon-code-guru-profiler:targetFrames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thresholdPercent\": {\n      \"@id\": \"amazon-code-guru-profiler:thresholdPercent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentProfile\": {\n      \"@id\": \"amazon-code-guru-profiler:agentProfile\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"latestAgentOrchestratedAt\": {\n      \"@id\": \"amazon-code-guru-profiler:latestAgentOrchestratedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestAgentProfileReportedAt\": {\n      \"@id\": \"amazon-code-guru-profiler:latestAgentProfileReportedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestAggregatedProfile\": {\n      \"@id\": \"amazon-code-guru-profiler:latestAggregatedProfile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principals\": {\n      \"@id\": \"amazon-code-guru-profiler:principals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allMatchesCount\": {\n      \"@id\": \"amazon-code-guru-profiler:allMatchesCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allMatchesSum\": {\n      \"@id\": \"amazon-code-guru-profiler:allMatchesSum\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pattern\": {\n      \"@id\": \"amazon-code-guru-profiler:pattern\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topMatches\"\
  : {\n      \"@id\": \"amazon-code-guru-profiler:topMatches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comment\": {\n      \"@id\": \"amazon-code-guru-profiler:comment\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-profiler/refs/heads/main/json-ld/amazon-codeguru-profiler-context.jsonld
tags:
- Amazon
- AWS
- Application Performance
- Profiling
- DevOps
- Machine Learning
- JSON-LD
- Linked Data
- Semantic Web
---
