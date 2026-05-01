---
api_specs:
- filename: amazon-connect-openapi.yml
  format: yaml
  label: Amazon Connect Service API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/openapi/amazon-connect-openapi.yml
class_count: 61
classes:
- HoursOfOperationSummary
- UserSummary
- InstanceSummary
- CreateContactFlowRequest
- GetCurrentMetricDataRequest
- MediaConcurrency
- Queue
- CreateQueueResponse
- ListAgentStatusesResponse
- HoursOfOperationConfig
- CreateUserResponse
- ContactFlowSummary
- ContactSummary
- DescribeContactFlowResponse
- StartTaskContactRequest
- ListContactFlowsResponse
- DescribeQueueResponse
- DescribeInstanceResponse
- QueueSummary
- StartOutboundVoiceContactRequest
- UserPhoneConfig
- Instance
- StartChatContactResponse
- ListRoutingProfilesResponse
- CreateHoursOfOperationRequest
- ContactFlow
- ListQueuesResponse
- SecurityProfileSummary
- SearchContactsRequest
- HoursOfOperationTimeSlice
- UpdateUserIdentityInfoRequest
- DescribeContactResponse
- GetCurrentMetricDataResponse
- DescribeRoutingProfileResponse
- Amazon Connect Instance
- ListInstancesResponse
- GetMetricDataResponse
- DescribeUserResponse
- CreateUserRequest
- CreateQueueRequest
- CreateHoursOfOperationResponse
- CreateInstanceRequest
- ListHoursOfOperationsResponse
- ListSecurityProfilesResponse
- RoutingProfile
- CreateRoutingProfileResponse
- GetMetricDataRequest
- UserIdentityInfo
- CreateContactFlowResponse
- CreateInstanceResponse
- User
- StartChatContactRequest
- Contact
- ListUsersResponse
- RoutingProfileSummary
- SearchContactsResponse
- CreateRoutingProfileRequest
- AgentStatusSummary
- description
- email
- name
context_file: json-ld/amazon-connect-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/json-ld/amazon-connect-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Connect from Amazon Connect.
layout: jsonld
name: Amazon Connect Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/connect/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: afterContactWorkTimeLimit
  type: integer
- container: set
  name: agentIds
  type: string
- container: ''
  name: agentInfo
  type: reference
- container: set
  name: agentStatusSummaryList
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: attributes
  type: reference
- container: ''
  name: autoAccept
  type: boolean
- container: ''
  name: channel
  type: string
- container: set
  name: channels
  type: string
- container: ''
  name: chatDurationInMinutes
  type: integer
- container: ''
  name: clientToken
  type: string
- container: set
  name: collections
  type: reference
- container: ''
  name: concurrency
  type: integer
- container: set
  name: config
  type: string
- container: ''
  name: connectedToAgentTimestamp
  type: dateTime
- container: ''
  name: contact
  type: string
- container: ''
  name: contactFlow
  type: string
- container: ''
  name: contactFlowArn
  type: string
- container: ''
  name: contactFlowId
  type: string
- container: ''
  name: contactFlowState
  type: string
- container: set
  name: contactFlowSummaryList
  type: string
- container: ''
  name: contactFlowType
  type: string
- container: ''
  name: contactId
  type: string
- container: set
  name: contacts
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: createdTime
  type: dateTime
- container: set
  name: currentMetrics
  type: reference
- container: ''
  name: dataSnapshotTime
  type: dateTime
- container: ''
  name: day
  type: string
- container: ''
  name: defaultOutboundQueueId
  type: string
- container: ''
  name: delay
  type: integer
- container: ''
  name: deskPhoneNumber
  type: string
- container: ''
  name: destinationPhoneNumber
  type: string
- container: ''
  name: dimensions
  type: reference
- container: ''
  name: directoryId
  type: string
- container: ''
  name: directoryUserId
  type: string
- container: ''
  name: disconnectTimestamp
  type: dateTime
- container: ''
  name: displayName
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: enqueueTimestamp
  type: dateTime
- container: ''
  name: fieldName
  type: string
- container: ''
  name: filters
  type: reference
- container: ''
  name: firstName
  type: string
- container: set
  name: groupings
  type: string
- container: ''
  name: hierarchyGroupId
  type: string
- container: set
  name: historicalMetrics
  type: reference
- container: ''
  name: hours
  type: integer
- container: ''
  name: hoursOfOperationArn
  type: string
- container: ''
  name: hoursOfOperationId
  type: string
- container: set
  name: hoursOfOperationSummaryList
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: identityInfo
  type: string
- container: ''
  name: identityManagementType
  type: string
- container: ''
  name: inboundCallsEnabled
  type: boolean
- container: ''
  name: initialContactId
  type: string
- container: ''
  name: initialMessage
  type: reference
- container: ''
  name: initiationMethod
  type: string
- container: ''
  name: initiationTimestamp
  type: dateTime
- container: ''
  name: instance
  type: string
- container: ''
  name: instanceAlias
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: instanceStatus
  type: string
- container: set
  name: instanceSummaryList
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: lastUpdateTimestamp
  type: dateTime
- container: ''
  name: maxContacts
  type: integer
- container: ''
  name: maxResults
  type: integer
- container: set
  name: mediaConcurrencies
  type: string
- container: ''
  name: metric
  type: reference
- container: set
  name: metricResults
  type: reference
- container: ''
  name: minutes
  type: integer
- container: ''
  name: mobile
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: numberOfAssociatedQueues
  type: integer
- container: ''
  name: numberOfAssociatedUsers
  type: integer
- container: ''
  name: order
  type: string
- container: ''
  name: outboundCallerConfig
  type: reference
- container: ''
  name: outboundCallerIdName
  type: string
- container: ''
  name: outboundCallerIdNumberId
  type: string
- container: ''
  name: outboundCallsEnabled
  type: boolean
- container: ''
  name: outboundFlowId
  type: string
- container: ''
  name: participantDetails
  type: reference
- container: ''
  name: participantId
  type: string
- container: ''
  name: participantToken
  type: string
- container: ''
  name: password
  type: string
- container: ''
  name: phoneConfig
  type: string
- container: ''
  name: phoneType
  type: string
- container: ''
  name: previousContactId
  type: string
- container: ''
  name: priority
  type: integer
- container: ''
  name: queue
  type: string
- container: ''
  name: queueArn
  type: string
- container: set
  name: queueConfigs
  type: reference
- container: ''
  name: queueId
  type: string
- container: set
  name: queueIds
  type: string
- container: ''
  name: queueInfo
  type: reference
- container: ''
  name: queueReference
  type: reference
- container: set
  name: queueSummaryList
  type: string
- container: ''
  name: queueType
  type: string
- container: set
  name: queues
  type: string
- container: ''
  name: quickConnectId
  type: string
- container: ''
  name: references
  type: reference
- container: ''
  name: relatedContactId
  type: string
- container: ''
  name: routingProfile
  type: string
- container: ''
  name: routingProfileArn
  type: string
- container: ''
  name: routingProfileId
  type: string
- container: set
  name: routingProfileSummaryList
  type: string
- container: ''
  name: scheduledTime
  type: dateTime
- container: ''
  name: searchCriteria
  type: reference
- container: ''
  name: secondaryEmail
  type: string
- container: set
  name: securityProfileIds
  type: string
- container: set
  name: securityProfileSummaryList
  type: string
- container: ''
  name: serviceRole
  type: string
- container: ''
  name: sort
  type: reference
- container: ''
  name: sourcePhoneNumber
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: statistic
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: taskTemplateId
  type: string
- container: ''
  name: timeRange
  type: reference
- container: ''
  name: timeZone
  type: string
- container: ''
  name: totalCount
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: unit
  type: string
- container: ''
  name: user
  type: string
- container: ''
  name: userArn
  type: string
- container: ''
  name: userId
  type: string
- container: set
  name: userSummaryList
  type: string
- container: ''
  name: username
  type: string
- container: ''
  name: value
  type: decimal
property_count: 132
provider_name: Amazon Connect
provider_slug: amazon-connect
slug: amazon-connect-context
source_filename: amazon-connect-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/connect/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"HoursOfOperationSummary\": \"aws:HoursOfOperationSummary\",\n    \"UserSummary\": \"aws:UserSummary\",\n    \"InstanceSummary\": \"aws:InstanceSummary\",\n    \"CreateContactFlowRequest\": \"aws:CreateContactFlowRequest\",\n    \"GetCurrentMetricDataRequest\": \"aws:GetCurrentMetricDataRequest\",\n    \"MediaConcurrency\": \"aws:MediaConcurrency\",\n    \"Queue\": \"aws:Queue\",\n    \"CreateQueueResponse\": \"aws:CreateQueueResponse\",\n    \"ListAgentStatusesResponse\": \"aws:ListAgentStatusesResponse\",\n    \"HoursOfOperationConfig\": \"aws:HoursOfOperationConfig\",\n    \"CreateUserResponse\": \"aws:CreateUserResponse\",\n    \"ContactFlowSummary\": \"aws:ContactFlowSummary\",\n    \"ContactSummary\": \"aws:ContactSummary\"\
  ,\n    \"DescribeContactFlowResponse\": \"aws:DescribeContactFlowResponse\",\n    \"StartTaskContactRequest\": \"aws:StartTaskContactRequest\",\n    \"ListContactFlowsResponse\": \"aws:ListContactFlowsResponse\",\n    \"DescribeQueueResponse\": \"aws:DescribeQueueResponse\",\n    \"DescribeInstanceResponse\": \"aws:DescribeInstanceResponse\",\n    \"QueueSummary\": \"aws:QueueSummary\",\n    \"StartOutboundVoiceContactRequest\": \"aws:StartOutboundVoiceContactRequest\",\n    \"UserPhoneConfig\": \"aws:UserPhoneConfig\",\n    \"Instance\": \"aws:Instance\",\n    \"StartChatContactResponse\": \"aws:StartChatContactResponse\",\n    \"ListRoutingProfilesResponse\": \"aws:ListRoutingProfilesResponse\",\n    \"CreateHoursOfOperationRequest\": \"aws:CreateHoursOfOperationRequest\",\n    \"ContactFlow\": \"aws:ContactFlow\",\n    \"ListQueuesResponse\": \"aws:ListQueuesResponse\",\n    \"SecurityProfileSummary\": \"aws:SecurityProfileSummary\",\n    \"SearchContactsRequest\": \"aws:SearchContactsRequest\"\
  ,\n    \"HoursOfOperationTimeSlice\": \"aws:HoursOfOperationTimeSlice\",\n    \"UpdateUserIdentityInfoRequest\": \"aws:UpdateUserIdentityInfoRequest\",\n    \"DescribeContactResponse\": \"aws:DescribeContactResponse\",\n    \"GetCurrentMetricDataResponse\": \"aws:GetCurrentMetricDataResponse\",\n    \"DescribeRoutingProfileResponse\": \"aws:DescribeRoutingProfileResponse\",\n    \"Amazon Connect Instance\": \"aws:Amazon Connect Instance\",\n    \"ListInstancesResponse\": \"aws:ListInstancesResponse\",\n    \"GetMetricDataResponse\": \"aws:GetMetricDataResponse\",\n    \"DescribeUserResponse\": \"aws:DescribeUserResponse\",\n    \"CreateUserRequest\": \"aws:CreateUserRequest\",\n    \"CreateQueueRequest\": \"aws:CreateQueueRequest\",\n    \"CreateHoursOfOperationResponse\": \"aws:CreateHoursOfOperationResponse\",\n    \"CreateInstanceRequest\": \"aws:CreateInstanceRequest\",\n    \"ListHoursOfOperationsResponse\": \"aws:ListHoursOfOperationsResponse\",\n    \"ListSecurityProfilesResponse\"\
  : \"aws:ListSecurityProfilesResponse\",\n    \"RoutingProfile\": \"aws:RoutingProfile\",\n    \"CreateRoutingProfileResponse\": \"aws:CreateRoutingProfileResponse\",\n    \"GetMetricDataRequest\": \"aws:GetMetricDataRequest\",\n    \"UserIdentityInfo\": \"aws:UserIdentityInfo\",\n    \"CreateContactFlowResponse\": \"aws:CreateContactFlowResponse\",\n    \"CreateInstanceResponse\": \"aws:CreateInstanceResponse\",\n    \"User\": \"aws:User\",\n    \"StartChatContactRequest\": \"aws:StartChatContactRequest\",\n    \"Contact\": \"aws:Contact\",\n    \"ListUsersResponse\": \"aws:ListUsersResponse\",\n    \"RoutingProfileSummary\": \"aws:RoutingProfileSummary\",\n    \"SearchContactsResponse\": \"aws:SearchContactsResponse\",\n    \"CreateRoutingProfileRequest\": \"aws:CreateRoutingProfileRequest\",\n    \"AgentStatusSummary\": \"aws:AgentStatusSummary\",\n    \"afterContactWorkTimeLimit\": {\n      \"@id\": \"aws:after_contact_work_time_limit\",\n      \"@type\": \"xsd:integer\"\n    },\n \
  \   \"agentIds\": {\n      \"@id\": \"aws:agent_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentInfo\": {\n      \"@id\": \"aws:agent_info\",\n      \"@type\": \"@id\"\n    },\n    \"agentStatusSummaryList\": {\n      \"@id\": \"aws:agent_status_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"aws:attributes\",\n      \"@type\": \"@id\"\n    },\n    \"autoAccept\": {\n      \"@id\": \"aws:auto_accept\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"channel\": {\n      \"@id\": \"aws:channel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"channels\": {\n      \"@id\": \"aws:channels\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"chatDurationInMinutes\": {\n      \"@id\": \"aws:chat_duration_in_minutes\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"clientToken\": {\n      \"@id\": \"aws:client_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collections\": {\n      \"@id\": \"aws:collections\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"concurrency\": {\n      \"@id\": \"aws:concurrency\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"config\": {\n      \"@id\": \"aws:config\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectedToAgentTimestamp\": {\n      \"@id\": \"aws:connected_to_agent_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"contact\": {\n      \"@id\": \"aws:contact\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactFlow\": {\n      \"@id\": \"aws:contact_flow\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactFlowArn\": {\n      \"@id\": \"aws:contact_flow_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactFlowId\": {\n      \"@id\": \"aws:contact_flow_id\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"contactFlowState\": {\n      \"@id\": \"aws:contact_flow_state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactFlowSummaryList\": {\n      \"@id\": \"aws:contact_flow_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactFlowType\": {\n      \"@id\": \"aws:contact_flow_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contactId\": {\n      \"@id\": \"aws:contact_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contacts\": {\n      \"@id\": \"aws:contacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"aws:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"aws:content_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"aws:created_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currentMetrics\": {\n      \"@id\": \"aws:current_metrics\",\n     \
  \ \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"dataSnapshotTime\": {\n      \"@id\": \"aws:data_snapshot_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"day\": {\n      \"@id\": \"aws:day\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultOutboundQueueId\": {\n      \"@id\": \"aws:default_outbound_queue_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delay\": {\n      \"@id\": \"aws:delay\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": \"schema:description\",\n    \"deskPhoneNumber\": {\n      \"@id\": \"aws:desk_phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationPhoneNumber\": {\n      \"@id\": \"aws:destination_phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dimensions\": {\n      \"@id\": \"aws:dimensions\",\n      \"@type\": \"@id\"\n    },\n    \"directoryId\": {\n      \"@id\": \"aws:directory_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryUserId\": {\n      \"\
  @id\": \"aws:directory_user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disconnectTimestamp\": {\n      \"@id\": \"aws:disconnect_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"displayName\": {\n      \"@id\": \"aws:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"endTime\": {\n      \"@id\": \"aws:end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enqueueTimestamp\": {\n      \"@id\": \"aws:enqueue_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"fieldName\": {\n      \"@id\": \"aws:field_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"aws:filters\",\n      \"@type\": \"@id\"\n    },\n    \"firstName\": {\n      \"@id\": \"aws:first_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupings\": {\n      \"@id\": \"aws:groupings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hierarchyGroupId\": {\n      \"@id\"\
  : \"aws:hierarchy_group_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"historicalMetrics\": {\n      \"@id\": \"aws:historical_metrics\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"hours\": {\n      \"@id\": \"aws:hours\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"hoursOfOperationArn\": {\n      \"@id\": \"aws:hours_of_operation_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hoursOfOperationId\": {\n      \"@id\": \"aws:hours_of_operation_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hoursOfOperationSummaryList\": {\n      \"@id\": \"aws:hours_of_operation_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityInfo\": {\n      \"@id\": \"aws:identity_info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityManagementType\": {\n      \"@id\": \"aws:identity_management_type\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"inboundCallsEnabled\": {\n      \"@id\": \"aws:inbound_calls_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"initialContactId\": {\n      \"@id\": \"aws:initial_contact_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialMessage\": {\n      \"@id\": \"aws:initial_message\",\n      \"@type\": \"@id\"\n    },\n    \"initiationMethod\": {\n      \"@id\": \"aws:initiation_method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initiationTimestamp\": {\n      \"@id\": \"aws:initiation_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"instance\": {\n      \"@id\": \"aws:instance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceAlias\": {\n      \"@id\": \"aws:instance_alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"aws:instance_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceStatus\": {\n      \"@id\": \"aws:instance_status\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"instanceSummaryList\": {\n      \"@id\": \"aws:instance_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"aws:last_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdateTimestamp\": {\n      \"@id\": \"aws:last_update_timestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"maxContacts\": {\n      \"@id\": \"aws:max_contacts\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxResults\": {\n      \"@id\": \"aws:max_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mediaConcurrencies\": {\n      \"@id\": \"aws:media_concurrencies\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"aws:metric\",\n      \"@type\": \"@id\"\n    },\n    \"metricResults\": {\n      \"@id\": \"aws:metric_results\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"minutes\": {\n      \"@id\": \"aws:minutes\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"mobile\": {\n      \"@id\": \"aws:mobile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"aws:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfAssociatedQueues\": {\n      \"@id\": \"aws:number_of_associated_queues\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numberOfAssociatedUsers\": {\n      \"@id\": \"aws:number_of_associated_users\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"order\": {\n      \"@id\": \"aws:order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outboundCallerConfig\": {\n      \"@id\": \"aws:outbound_caller_config\",\n      \"@type\": \"@id\"\n    },\n    \"outboundCallerIdName\": {\n      \"@id\": \"aws:outbound_caller_id_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outboundCallerIdNumberId\": {\n      \"@id\": \"aws:outbound_caller_id_number_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outboundCallsEnabled\"\
  : {\n      \"@id\": \"aws:outbound_calls_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"outboundFlowId\": {\n      \"@id\": \"aws:outbound_flow_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"participantDetails\": {\n      \"@id\": \"aws:participant_details\",\n      \"@type\": \"@id\"\n    },\n    \"participantId\": {\n      \"@id\": \"aws:participant_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"participantToken\": {\n      \"@id\": \"aws:participant_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"password\": {\n      \"@id\": \"aws:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneConfig\": {\n      \"@id\": \"aws:phone_config\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneType\": {\n      \"@id\": \"aws:phone_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousContactId\": {\n      \"@id\": \"aws:previous_contact_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"priority\": {\n      \"@id\": \"aws:priority\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"queue\": {\n      \"@id\": \"aws:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueArn\": {\n      \"@id\": \"aws:queue_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueConfigs\": {\n      \"@id\": \"aws:queue_configs\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"queueId\": {\n      \"@id\": \"aws:queue_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueIds\": {\n      \"@id\": \"aws:queue_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueInfo\": {\n      \"@id\": \"aws:queue_info\",\n      \"@type\": \"@id\"\n    },\n    \"queueReference\": {\n      \"@id\": \"aws:queue_reference\",\n      \"@type\": \"@id\"\n    },\n    \"queueSummaryList\": {\n      \"@id\": \"aws:queue_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queueType\": {\n      \"@id\": \"aws:queue_type\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"queues\": {\n      \"@id\": \"aws:queues\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"quickConnectId\": {\n      \"@id\": \"aws:quick_connect_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"references\": {\n      \"@id\": \"aws:references\",\n      \"@type\": \"@id\"\n    },\n    \"relatedContactId\": {\n      \"@id\": \"aws:related_contact_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingProfile\": {\n      \"@id\": \"aws:routing_profile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingProfileArn\": {\n      \"@id\": \"aws:routing_profile_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingProfileId\": {\n      \"@id\": \"aws:routing_profile_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"routingProfileSummaryList\": {\n      \"@id\": \"aws:routing_profile_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduledTime\": {\n\
  \      \"@id\": \"aws:scheduled_time\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"searchCriteria\": {\n      \"@id\": \"aws:search_criteria\",\n      \"@type\": \"@id\"\n    },\n    \"secondaryEmail\": {\n      \"@id\": \"aws:secondary_email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileIds\": {\n      \"@id\": \"aws:security_profile_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityProfileSummaryList\": {\n      \"@id\": \"aws:security_profile_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceRole\": {\n      \"@id\": \"aws:service_role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sort\": {\n      \"@id\": \"aws:sort\",\n      \"@type\": \"@id\"\n    },\n    \"sourcePhoneNumber\": {\n      \"@id\": \"aws:source_phone_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"aws:start_time\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"state\": {\n      \"@id\": \"aws:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statistic\": {\n      \"@id\": \"aws:statistic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"@id\"\n    },\n    \"taskTemplateId\": {\n      \"@id\": \"aws:task_template_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeRange\": {\n      \"@id\": \"aws:time_range\",\n      \"@type\": \"@id\"\n    },\n    \"timeZone\": {\n      \"@id\": \"aws:time_zone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCount\": {\n      \"@id\": \"aws:total_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unit\": {\n      \"@id\": \"aws:unit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"aws:user\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"userArn\": {\n      \"@id\": \"aws:user_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userId\": {\n      \"@id\": \"aws:user_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userSummaryList\": {\n      \"@id\": \"aws:user_summary_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"username\": {\n      \"@id\": \"aws:username\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"aws:value\",\n      \"@type\": \"xsd:decimal\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-connect/refs/heads/main/json-ld/amazon-connect-context.jsonld
tags:
- Chat
- Contact Center
- Customer Service
- Voice
- AI
- Omnichannel
- JSON-LD
- Linked Data
- Semantic Web
---
