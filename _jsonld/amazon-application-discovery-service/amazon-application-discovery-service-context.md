---
class_count: 69
classes:
- CustomerAgentInfo
- DescribeTagsResponse
- DescribeBatchDeleteConfigurationTaskRequest
- DescribeImportTasksRequest
- CreateApplicationResponse
- StartBatchDeleteConfigurationTaskRequest
- DeleteAgent
- AgentNetworkInfo
- GetDiscoverySummaryResponse
- StartExportTaskRequest
- DescribeAgentsRequest
- BatchDeleteImportDataRequest
- DisassociateConfigurationItemsRequest
- BatchDeleteAgentsRequest
- UpdateApplicationRequest
- BatchDeleteAgentsResponse
- ImportTask
- OrderByElement
- StartDataCollectionByAgentIdsResponse
- DescribeExportTasksRequest
- ListConfigurationsResponse
- FailedConfiguration
- AgentConfigurationStatus
- StartImportTaskRequest
- DescribeContinuousExportsRequest
- DeletionWarning
- DescribeAgentsResponse
- Tag
- DescribeBatchDeleteConfigurationTaskResponse
- ExportFilter
- DescribeConfigurationsRequest
- CustomerConnectorInfo
- DescribeConfigurationsResponse
- BatchDeleteImportDataError
- Filter
- DescribeImportTasksResponse
- DeleteApplicationsRequest
- ConfigurationTag
- BatchDeleteImportDataResponse
- TagFilter
- StartExportTaskResponse
- StartDataCollectionByAgentIdsRequest
- CreateTagsRequest
- DescribeTagsRequest
- DescribeExportTasksResponse
- AssociateConfigurationItemsRequest
- NeighborConnectionDetail
- DeleteTagsRequest
- ImportTaskFilter
- DescribeContinuousExportsResponse
- StopDataCollectionByAgentIdsResponse
- ListConfigurationsRequest
- ExportInfo
- BatchDeleteConfigurationTask
- StartBatchDeleteConfigurationTaskResponse
- StopContinuousExportResponse
- StartImportTaskResponse
- ContinuousExportDescription
- CreateApplicationRequest
- ListServerNeighborsResponse
- StopDataCollectionByAgentIdsRequest
- StopContinuousExportRequest
- BatchDeleteAgentError
- ListServerNeighborsRequest
- StartContinuousExportResponse
- AgentInfo
- name
- description
- version
context_file: json-ld/amazon-application-discovery-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-ld/amazon-application-discovery-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Application Discovery Service from Amazon Application Discovery Service.
layout: jsonld
name: Amazon Application Discovery Service Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/application-discovery/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: activeAgents
  type: integer
- container: ''
  name: healthyAgents
  type: integer
- container: ''
  name: blackListedAgents
  type: integer
- container: ''
  name: shutdownAgents
  type: integer
- container: ''
  name: unhealthyAgents
  type: integer
- container: ''
  name: totalAgents
  type: integer
- container: ''
  name: unknownAgents
  type: integer
- container: set
  name: tags
  type: reference
- container: ''
  name: nextToken
  type: string
- container: ''
  name: taskId
  type: string
- container: set
  name: filters
  type: reference
- container: ''
  name: maxResults
  type: integer
- container: ''
  name: configurationId
  type: string
- container: ''
  name: configurationType
  type: string
- container: set
  name: configurationIds
  type: string
- container: ''
  name: agentId
  type: string
- container: ''
  name: force
  type: boolean
- container: ''
  name: ipAddress
  type: string
- container: ''
  name: macAddress
  type: string
- container: ''
  name: servers
  type: integer
- container: ''
  name: applications
  type: integer
- container: ''
  name: serversMappedToApplications
  type: integer
- container: ''
  name: serversMappedtoTags
  type: integer
- container: ''
  name: mappedServerCount
  type: integer
- container: ''
  name: unmappedServerCount
  type: integer
- container: ''
  name: agentSummary
  type: reference
- container: ''
  name: connectorSummary
  type: reference
- container: ''
  name: activeConnectors
  type: integer
- container: ''
  name: healthyConnectors
  type: integer
- container: ''
  name: blackListedConnectors
  type: integer
- container: ''
  name: shutdownConnectors
  type: integer
- container: ''
  name: unhealthyConnectors
  type: integer
- container: ''
  name: totalConnectors
  type: integer
- container: ''
  name: unknownConnectors
  type: integer
- container: set
  name: exportDataFormat
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: preferences
  type: reference
- container: set
  name: agentIds
  type: string
- container: set
  name: importTaskIds
  type: string
- container: ''
  name: deleteHistory
  type: boolean
- container: ''
  name: applicationConfigurationId
  type: string
- container: set
  name: deleteAgents
  type: reference
- container: set
  name: errors
  type: reference
- container: ''
  name: importTaskId
  type: string
- container: ''
  name: clientRequestToken
  type: string
- container: ''
  name: importUrl
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: importRequestTime
  type: string
- container: ''
  name: importCompletionTime
  type: string
- container: ''
  name: importDeletedTime
  type: string
- container: ''
  name: serverImportSuccess
  type: integer
- container: ''
  name: serverImportFailure
  type: integer
- container: ''
  name: applicationImportSuccess
  type: integer
- container: ''
  name: applicationImportFailure
  type: integer
- container: ''
  name: errorsAndFailedEntriesZip
  type: string
- container: ''
  name: fieldName
  type: string
- container: ''
  name: sortOrder
  type: string
- container: set
  name: agentsConfigurationStatus
  type: reference
- container: set
  name: exportIds
  type: string
- container: set
  name: configurations
  type: reference
- container: ''
  name: errorStatusCode
  type: integer
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: operationSucceeded
  type: boolean
- container: ''
  name: warningCode
  type: integer
- container: ''
  name: warningText
  type: string
- container: set
  name: agentsInfo
  type: reference
- container: ''
  name: key
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: task
  type: reference
- container: set
  name: requestedConfigurations
  type: string
- container: set
  name: deletedConfigurations
  type: string
- container: set
  name: failedConfigurations
  type: reference
- container: set
  name: deletionWarnings
  type: reference
- container: set
  name: values
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorDescription
  type: string
- container: set
  name: tasks
  type: reference
- container: ''
  name: timeOfCreation
  type: string
- container: ''
  name: exportId
  type: string
- container: set
  name: exportsInfo
  type: reference
- container: ''
  name: sourceServerId
  type: string
- container: ''
  name: destinationServerId
  type: string
- container: ''
  name: destinationPort
  type: integer
- container: ''
  name: transportProtocol
  type: string
- container: ''
  name: connectionsCount
  type: integer
- container: set
  name: descriptions
  type: reference
- container: set
  name: orderBy
  type: reference
- container: ''
  name: exportStatus
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: configurationsDownloadUrl
  type: string
- container: ''
  name: exportRequestTime
  type: string
- container: ''
  name: isTruncated
  type: boolean
- container: ''
  name: requestedStartTime
  type: string
- container: ''
  name: requestedEndTime
  type: string
- container: ''
  name: stopTime
  type: string
- container: ''
  name: statusDetail
  type: string
- container: ''
  name: s3Bucket
  type: string
- container: ''
  name: dataSource
  type: string
- container: ''
  name: schemaStorageConfig
  type: reference
- container: set
  name: neighbors
  type: reference
- container: ''
  name: knownDependencyCount
  type: integer
- container: ''
  name: portInformationNeeded
  type: boolean
- container: set
  name: neighborConfigurationIds
  type: string
- container: ''
  name: hostName
  type: string
- container: set
  name: agentNetworkInfoList
  type: reference
- container: ''
  name: connectorId
  type: string
- container: ''
  name: health
  type: string
- container: ''
  name: lastHealthPingTime
  type: string
- container: ''
  name: collectionStatus
  type: string
- container: ''
  name: agentType
  type: string
- container: ''
  name: registeredTime
  type: string
property_count: 113
provider_name: Amazon Application Discovery Service
provider_slug: amazon-application-discovery-service
slug: amazon-application-discovery-service-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/application-discovery/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CustomerAgentInfo\": \"amzn:CustomerAgentInfo\",\n    \"DescribeTagsResponse\": \"amzn:DescribeTagsResponse\",\n    \"DescribeBatchDeleteConfigurationTaskRequest\": \"amzn:DescribeBatchDeleteConfigurationTaskRequest\",\n    \"DescribeImportTasksRequest\": \"amzn:DescribeImportTasksRequest\",\n    \"CreateApplicationResponse\": \"amzn:CreateApplicationResponse\",\n    \"StartBatchDeleteConfigurationTaskRequest\": \"amzn:StartBatchDeleteConfigurationTaskRequest\",\n    \"DeleteAgent\": \"amzn:DeleteAgent\",\n    \"AgentNetworkInfo\": \"amzn:AgentNetworkInfo\",\n    \"GetDiscoverySummaryResponse\": \"amzn:GetDiscoverySummaryResponse\",\n    \"StartExportTaskRequest\": \"amzn:StartExportTaskRequest\",\n    \"DescribeAgentsRequest\"\
  : \"amzn:DescribeAgentsRequest\",\n    \"BatchDeleteImportDataRequest\": \"amzn:BatchDeleteImportDataRequest\",\n    \"DisassociateConfigurationItemsRequest\": \"amzn:DisassociateConfigurationItemsRequest\",\n    \"BatchDeleteAgentsRequest\": \"amzn:BatchDeleteAgentsRequest\",\n    \"UpdateApplicationRequest\": \"amzn:UpdateApplicationRequest\",\n    \"BatchDeleteAgentsResponse\": \"amzn:BatchDeleteAgentsResponse\",\n    \"ImportTask\": \"amzn:ImportTask\",\n    \"OrderByElement\": \"amzn:OrderByElement\",\n    \"StartDataCollectionByAgentIdsResponse\": \"amzn:StartDataCollectionByAgentIdsResponse\",\n    \"DescribeExportTasksRequest\": \"amzn:DescribeExportTasksRequest\",\n    \"ListConfigurationsResponse\": \"amzn:ListConfigurationsResponse\",\n    \"FailedConfiguration\": \"amzn:FailedConfiguration\",\n    \"AgentConfigurationStatus\": \"amzn:AgentConfigurationStatus\",\n    \"StartImportTaskRequest\": \"amzn:StartImportTaskRequest\",\n    \"DescribeContinuousExportsRequest\": \"amzn:DescribeContinuousExportsRequest\"\
  ,\n    \"DeletionWarning\": \"amzn:DeletionWarning\",\n    \"DescribeAgentsResponse\": \"amzn:DescribeAgentsResponse\",\n    \"Tag\": \"amzn:Tag\",\n    \"DescribeBatchDeleteConfigurationTaskResponse\": \"amzn:DescribeBatchDeleteConfigurationTaskResponse\",\n    \"ExportFilter\": \"amzn:ExportFilter\",\n    \"DescribeConfigurationsRequest\": \"amzn:DescribeConfigurationsRequest\",\n    \"CustomerConnectorInfo\": \"amzn:CustomerConnectorInfo\",\n    \"DescribeConfigurationsResponse\": \"amzn:DescribeConfigurationsResponse\",\n    \"BatchDeleteImportDataError\": \"amzn:BatchDeleteImportDataError\",\n    \"Filter\": \"amzn:Filter\",\n    \"DescribeImportTasksResponse\": \"amzn:DescribeImportTasksResponse\",\n    \"DeleteApplicationsRequest\": \"amzn:DeleteApplicationsRequest\",\n    \"ConfigurationTag\": \"amzn:ConfigurationTag\",\n    \"BatchDeleteImportDataResponse\": \"amzn:BatchDeleteImportDataResponse\",\n    \"TagFilter\": \"amzn:TagFilter\",\n    \"StartExportTaskResponse\": \"amzn:StartExportTaskResponse\"\
  ,\n    \"StartDataCollectionByAgentIdsRequest\": \"amzn:StartDataCollectionByAgentIdsRequest\",\n    \"CreateTagsRequest\": \"amzn:CreateTagsRequest\",\n    \"DescribeTagsRequest\": \"amzn:DescribeTagsRequest\",\n    \"DescribeExportTasksResponse\": \"amzn:DescribeExportTasksResponse\",\n    \"AssociateConfigurationItemsRequest\": \"amzn:AssociateConfigurationItemsRequest\",\n    \"NeighborConnectionDetail\": \"amzn:NeighborConnectionDetail\",\n    \"DeleteTagsRequest\": \"amzn:DeleteTagsRequest\",\n    \"ImportTaskFilter\": \"amzn:ImportTaskFilter\",\n    \"DescribeContinuousExportsResponse\": \"amzn:DescribeContinuousExportsResponse\",\n    \"StopDataCollectionByAgentIdsResponse\": \"amzn:StopDataCollectionByAgentIdsResponse\",\n    \"ListConfigurationsRequest\": \"amzn:ListConfigurationsRequest\",\n    \"ExportInfo\": \"amzn:ExportInfo\",\n    \"BatchDeleteConfigurationTask\": \"amzn:BatchDeleteConfigurationTask\",\n    \"StartBatchDeleteConfigurationTaskResponse\": \"amzn:StartBatchDeleteConfigurationTaskResponse\"\
  ,\n    \"StopContinuousExportResponse\": \"amzn:StopContinuousExportResponse\",\n    \"StartImportTaskResponse\": \"amzn:StartImportTaskResponse\",\n    \"ContinuousExportDescription\": \"amzn:ContinuousExportDescription\",\n    \"CreateApplicationRequest\": \"amzn:CreateApplicationRequest\",\n    \"ListServerNeighborsResponse\": \"amzn:ListServerNeighborsResponse\",\n    \"StopDataCollectionByAgentIdsRequest\": \"amzn:StopDataCollectionByAgentIdsRequest\",\n    \"StopContinuousExportRequest\": \"amzn:StopContinuousExportRequest\",\n    \"BatchDeleteAgentError\": \"amzn:BatchDeleteAgentError\",\n    \"ListServerNeighborsRequest\": \"amzn:ListServerNeighborsRequest\",\n    \"StartContinuousExportResponse\": \"amzn:StartContinuousExportResponse\",\n    \"AgentInfo\": \"amzn:AgentInfo\",\n    \"activeAgents\": {\n      \"@id\": \"amzn:active_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"healthyAgents\": {\n      \"@id\": \"amzn:healthy_agents\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"blackListedAgents\": {\n      \"@id\": \"amzn:black_listed_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shutdownAgents\": {\n      \"@id\": \"amzn:shutdown_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unhealthyAgents\": {\n      \"@id\": \"amzn:unhealthy_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalAgents\": {\n      \"@id\": \"amzn:total_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unknownAgents\": {\n      \"@id\": \"amzn:unknown_agents\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskId\": {\n      \"@id\": \"amzn:task_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"amzn:filters\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n   \
  \ \"maxResults\": {\n      \"@id\": \"amzn:max_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"configurationId\": {\n      \"@id\": \"amzn:configuration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationType\": {\n      \"@id\": \"amzn:configuration_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationIds\": {\n      \"@id\": \"amzn:configuration_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentId\": {\n      \"@id\": \"amzn:agent_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"force\": {\n      \"@id\": \"amzn:force\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ipAddress\": {\n      \"@id\": \"amzn:ip_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"macAddress\": {\n      \"@id\": \"amzn:mac_address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"servers\": {\n      \"@id\": \"amzn:servers\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"applications\": {\n      \"@id\"\
  : \"amzn:applications\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serversMappedToApplications\": {\n      \"@id\": \"amzn:servers_mapped_to_applications\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serversMappedtoTags\": {\n      \"@id\": \"amzn:servers_mappedto_tags\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mappedServerCount\": {\n      \"@id\": \"amzn:mapped_server_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unmappedServerCount\": {\n      \"@id\": \"amzn:unmapped_server_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"agentSummary\": {\n      \"@id\": \"amzn:agent_summary\",\n      \"@type\": \"@id\"\n    },\n    \"connectorSummary\": {\n      \"@id\": \"amzn:connector_summary\",\n      \"@type\": \"@id\"\n    },\n    \"activeConnectors\": {\n      \"@id\": \"amzn:active_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"healthyConnectors\": {\n      \"@id\": \"amzn:healthy_connectors\",\n      \"@type\": \"xsd:integer\"\n\
  \    },\n    \"blackListedConnectors\": {\n      \"@id\": \"amzn:black_listed_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"shutdownConnectors\": {\n      \"@id\": \"amzn:shutdown_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unhealthyConnectors\": {\n      \"@id\": \"amzn:unhealthy_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalConnectors\": {\n      \"@id\": \"amzn:total_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"unknownConnectors\": {\n      \"@id\": \"amzn:unknown_connectors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exportDataFormat\": {\n      \"@id\": \"amzn:export_data_format\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amzn:end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferences\": {\n      \"@id\": \"amzn:preferences\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"agentIds\": {\n      \"@id\": \"amzn:agent_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importTaskIds\": {\n      \"@id\": \"amzn:import_task_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteHistory\": {\n      \"@id\": \"amzn:delete_history\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"applicationConfigurationId\": {\n      \"@id\": \"amzn:application_configuration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteAgents\": {\n      \"@id\": \"amzn:delete_agents\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"importTaskId\": {\n      \"@id\": \"amzn:import_task_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientRequestToken\"\
  : {\n      \"@id\": \"amzn:client_request_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importUrl\": {\n      \"@id\": \"amzn:import_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importRequestTime\": {\n      \"@id\": \"amzn:import_request_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importCompletionTime\": {\n      \"@id\": \"amzn:import_completion_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"importDeletedTime\": {\n      \"@id\": \"amzn:import_deleted_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serverImportSuccess\": {\n      \"@id\": \"amzn:server_import_success\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"serverImportFailure\": {\n      \"@id\": \"amzn:server_import_failure\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"applicationImportSuccess\": {\n      \"@id\": \"amzn:application_import_success\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"applicationImportFailure\": {\n      \"@id\": \"amzn:application_import_failure\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errorsAndFailedEntriesZip\": {\n      \"@id\": \"amzn:errors_and_failed_entries_zip\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fieldName\": {\n      \"@id\": \"amzn:field_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortOrder\": {\n      \"@id\": \"amzn:sort_order\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentsConfigurationStatus\": {\n      \"@id\": \"amzn:agents_configuration_status\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"exportIds\": {\n      \"@id\": \"amzn:export_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurations\": {\n      \"@id\": \"amzn:configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"errorStatusCode\": {\n      \"@id\": \"amzn:error_status_code\",\n      \"@type\": \"xsd:integer\"\
  \n    },\n    \"errorMessage\": {\n      \"@id\": \"amzn:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationSucceeded\": {\n      \"@id\": \"amzn:operation_succeeded\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"warningCode\": {\n      \"@id\": \"amzn:warning_code\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"warningText\": {\n      \"@id\": \"amzn:warning_text\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentsInfo\": {\n      \"@id\": \"amzn:agents_info\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"task\": {\n      \"@id\": \"amzn:task\",\n      \"@type\": \"@id\"\n    },\n    \"requestedConfigurations\": {\n      \"@id\": \"amzn:requested_configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  deletedConfigurations\": {\n      \"@id\": \"amzn:deleted_configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedConfigurations\": {\n      \"@id\": \"amzn:failed_configurations\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"deletionWarnings\": {\n      \"@id\": \"amzn:deletion_warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"values\": {\n      \"@id\": \"amzn:values\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"@id\": \"amzn:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amzn:error_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorDescription\": {\n      \"@id\": \"amzn:error_description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"amzn:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"\
  timeOfCreation\": {\n      \"@id\": \"amzn:time_of_creation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportId\": {\n      \"@id\": \"amzn:export_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportsInfo\": {\n      \"@id\": \"amzn:exports_info\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"sourceServerId\": {\n      \"@id\": \"amzn:source_server_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationServerId\": {\n      \"@id\": \"amzn:destination_server_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationPort\": {\n      \"@id\": \"amzn:destination_port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"transportProtocol\": {\n      \"@id\": \"amzn:transport_protocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionsCount\": {\n      \"@id\": \"amzn:connections_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"descriptions\": {\n      \"@id\": \"amzn:descriptions\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"@id\"\n    },\n    \"orderBy\": {\n      \"@id\": \"amzn:order_by\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"exportStatus\": {\n      \"@id\": \"amzn:export_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"amzn:status_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationsDownloadUrl\": {\n      \"@id\": \"amzn:configurations_download_url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportRequestTime\": {\n      \"@id\": \"amzn:export_request_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isTruncated\": {\n      \"@id\": \"amzn:is_truncated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"requestedStartTime\": {\n      \"@id\": \"amzn:requested_start_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedEndTime\": {\n      \"@id\": \"amzn:requested_end_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stopTime\": {\n      \"@id\": \"\
  amzn:stop_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusDetail\": {\n      \"@id\": \"amzn:status_detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Bucket\": {\n      \"@id\": \"amzn:s3_bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataSource\": {\n      \"@id\": \"amzn:data_source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schemaStorageConfig\": {\n      \"@id\": \"amzn:schema_storage_config\",\n      \"@type\": \"@id\"\n    },\n    \"neighbors\": {\n      \"@id\": \"amzn:neighbors\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"knownDependencyCount\": {\n      \"@id\": \"amzn:known_dependency_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"portInformationNeeded\": {\n      \"@id\": \"amzn:port_information_needed\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"neighborConfigurationIds\": {\n      \"@id\": \"amzn:neighbor_configuration_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"hostName\": {\n      \"@id\": \"amzn:host_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentNetworkInfoList\": {\n      \"@id\": \"amzn:agent_network_info_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"connectorId\": {\n      \"@id\": \"amzn:connector_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"health\": {\n      \"@id\": \"amzn:health\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastHealthPingTime\": {\n      \"@id\": \"amzn:last_health_ping_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"collectionStatus\": {\n      \"@id\": \"amzn:collection_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"agentType\": {\n      \"@id\": \"amzn:agent_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registeredTime\": {\n      \"@id\": \"amzn:registered_time\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-discovery-service/refs/heads/main/json-ld/amazon-application-discovery-service-context.jsonld
tags:
- Amazon Application Discovery Service
- Migration
- Discovery
- Infrastructure
- AWS
- JSON-LD
- Linked Data
- Semantic Web
---
