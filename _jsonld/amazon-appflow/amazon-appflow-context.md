---
api_specs:
- filename: amazon-appflow-openapi.yml
  format: yaml
  label: Amazon AppFlow API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/openapi/amazon-appflow-openapi.yml
class_count: 61
classes:
- DeleteFlowRequest
- ListConnectorsResponse
- DescribeFlowExecutionRecordsResponse
- UnregisterConnectorRequest
- RegisterConnectorResponse
- ConnectorProfile
- UpdateFlowRequest
- ExecutionDetails
- DeleteConnectorProfileRequest
- DescribeConnectorProfilesResponse
- DescribeConnectorRequest
- CreateFlowRequest
- DescribeFlowRequest
- TagResourceRequest
- ScheduledTriggerProperties
- ResetConnectorMetadataCacheRequest
- ListFlowsRequest
- FlowExecution
- CreateConnectorProfileResponse
- DescribeFlowResponse
- ListFlowsResponse
- ConnectorDetail
- RegisterConnectorRequest
- TriggerConfig
- UpdateConnectorRegistrationResponse
- Task
- StopFlowRequest
- Amazon AppFlow Flow Definition
- ListConnectorEntitiesRequest
- UpdateConnectorRegistrationRequest
- ConnectorEntityField
- DescribeConnectorsRequest
- CreateConnectorProfileRequest
- SourceFlowConfig
- ConnectorEntity
- ListConnectorsRequest
- StartFlowResponse
- ListTagsForResourceResponse
- StartFlowRequest
- UpdateFlowResponse
- CancelFlowExecutionsResponse
- FlowDefinition
- StopFlowResponse
- CancelFlowExecutionsRequest
- DescribeConnectorEntityRequest
- DestinationFlowConfig
- DescribeConnectorResponse
- ListConnectorEntitiesResponse
- UpdateConnectorProfileResponse
- DescribeConnectorEntityResponse
- MetadataCatalogConfig
- UpdateConnectorProfileRequest
- DescribeConnectorsResponse
- ExecutionResult
- DescribeFlowExecutionRecordsRequest
- CreateFlowResponse
- DescribeConnectorProfilesRequest
- createdAt
- lastUpdatedAt
- description
- name
context_file: json-ld/amazon-appflow-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/json-ld/amazon-appflow-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Appflow from Amazon AppFlow.
layout: jsonld
name: Amazon Appflow Context
namespaces:
- prefix: amzn
  uri: https://amazonaws.com/schema/appflow/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: flowName
  type: string
- container: ''
  name: forceDelete
  type: boolean
- container: set
  name: connectors
  type: string
- container: ''
  name: nextToken
  type: string
- container: set
  name: flowExecutions
  type: string
- container: ''
  name: connectorLabel
  type: string
- container: ''
  name: connectorArn
  type: string
- container: ''
  name: connectorProfileArn
  type: string
- container: ''
  name: connectorProfileName
  type: string
- container: ''
  name: connectorType
  type: string
- container: ''
  name: connectionMode
  type: string
- container: ''
  name: credentialsArn
  type: string
- container: ''
  name: connectorProfileProperties
  type: reference
- container: ''
  name: privateConnectionProvisioningState
  type: reference
- container: ''
  name: clientToken
  type: string
- container: ''
  name: triggerConfig
  type: reference
- container: ''
  name: triggerType
  type: string
- container: ''
  name: triggerProperties
  type: reference
- container: ''
  name: Scheduled
  type: string
- container: ''
  name: sourceFlowConfig
  type: reference
- container: ''
  name: apiVersion
  type: string
- container: ''
  name: sourceConnectorProperties
  type: reference
- container: ''
  name: incrementalPullConfig
  type: reference
- container: ''
  name: datetimeTypeFieldName
  type: string
- container: set
  name: destinationFlowConfigList
  type: string
- container: set
  name: tasks
  type: string
- container: ''
  name: metadataCatalogConfig
  type: reference
- container: ''
  name: glueDataCatalog
  type: reference
- container: ''
  name: roleArn
  type: string
- container: ''
  name: databaseName
  type: string
- container: ''
  name: tablePrefix
  type: string
- container: ''
  name: mostRecentExecutionMessage
  type: string
- container: ''
  name: mostRecentExecutionTime
  type: integer
- container: ''
  name: mostRecentExecutionStatus
  type: string
- container: set
  name: connectorProfileDetails
  type: string
- container: ''
  name: kmsArn
  type: string
- container: ''
  name: tags
  type: reference
- container: ''
  name: scheduleExpression
  type: string
- container: ''
  name: dataPullMode
  type: string
- container: ''
  name: scheduleStartTime
  type: integer
- container: ''
  name: scheduleEndTime
  type: integer
- container: ''
  name: timezone
  type: string
- container: ''
  name: scheduleOffset
  type: integer
- container: ''
  name: firstExecutionFrom
  type: integer
- container: ''
  name: flowErrorDeactivationThreshold
  type: integer
- container: ''
  name: connectorEntityName
  type: string
- container: ''
  name: entitiesPath
  type: string
- container: ''
  name: maxResults
  type: integer
- container: ''
  name: executionId
  type: string
- container: ''
  name: executionStatus
  type: string
- container: ''
  name: executionResult
  type: reference
- container: ''
  name: errorInfo
  type: reference
- container: ''
  name: bytesProcessed
  type: integer
- container: ''
  name: bytesWritten
  type: integer
- container: ''
  name: recordsProcessed
  type: integer
- container: ''
  name: numParallelProcesses
  type: integer
- container: ''
  name: startedAt
  type: integer
- container: ''
  name: dataPullStartTime
  type: integer
- container: ''
  name: dataPullEndTime
  type: integer
- container: ''
  name: flowArn
  type: string
- container: ''
  name: flowStatus
  type: string
- container: ''
  name: flowStatusMessage
  type: string
- container: ''
  name: lastRunExecutionDetails
  type: reference
- container: ''
  name: createdBy
  type: string
- container: ''
  name: lastUpdatedBy
  type: string
- container: set
  name: lastRunMetadataCatalogDetails
  type: reference
- container: set
  name: flows
  type: string
- container: ''
  name: connectorDescription
  type: string
- container: ''
  name: connectorName
  type: string
- container: ''
  name: connectorOwner
  type: string
- container: ''
  name: connectorVersion
  type: string
- container: ''
  name: applicationType
  type: string
- container: ''
  name: registeredAt
  type: integer
- container: ''
  name: registeredBy
  type: string
- container: ''
  name: connectorProvisioningType
  type: string
- container: set
  name: connectorModes
  type: string
- container: set
  name: supportedDataTransferTypes
  type: string
- container: ''
  name: connectorProvisioningConfig
  type: reference
- container: ''
  name: lambda
  type: reference
- container: ''
  name: lambdaArn
  type: string
- container: set
  name: sourceFields
  type: string
- container: ''
  name: connectorOperator
  type: reference
- container: ''
  name: destinationField
  type: string
- container: ''
  name: taskType
  type: string
- container: ''
  name: taskProperties
  type: reference
- container: ''
  name: identifier
  type: string
- container: ''
  name: parentIdentifier
  type: string
- container: ''
  name: label
  type: string
- container: ''
  name: isPrimaryKey
  type: boolean
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: isDeprecated
  type: boolean
- container: ''
  name: supportedFieldTypeDetails
  type: reference
- container: ''
  name: sourceProperties
  type: reference
- container: ''
  name: isQueryable
  type: boolean
- container: ''
  name: isRetrievable
  type: boolean
- container: ''
  name: isPartitioningSupported
  type: boolean
- container: ''
  name: destinationProperties
  type: reference
- container: ''
  name: isCreatable
  type: boolean
- container: ''
  name: isNullable
  type: boolean
- container: ''
  name: isUpsertable
  type: boolean
- container: ''
  name: isUpdatable
  type: boolean
- container: ''
  name: isDefaultedOnCreate
  type: boolean
- container: set
  name: supportedWriteOperations
  type: string
- container: set
  name: connectorTypes
  type: string
- container: ''
  name: connectorProfileConfig
  type: reference
- container: ''
  name: hasNestedEntities
  type: boolean
- container: set
  name: invalidExecutions
  type: string
- container: ''
  name: sourceConnectorType
  type: string
- container: ''
  name: sourceConnectorLabel
  type: string
- container: ''
  name: destinationConnectorType
  type: string
- container: ''
  name: destinationConnectorLabel
  type: string
- container: set
  name: executionIds
  type: string
- container: ''
  name: destinationConnectorProperties
  type: reference
- container: ''
  name: connectorConfiguration
  type: reference
- container: ''
  name: canUseAsSource
  type: boolean
- container: ''
  name: canUseAsDestination
  type: boolean
- container: ''
  name: connectorEntityMap
  type: reference
- container: set
  name: connectorEntityFields
  type: string
- container: ''
  name: connectorConfigurations
  type: reference
- container: set
  name: connectorProfileNames
  type: string
property_count: 120
provider_name: Amazon AppFlow
provider_slug: amazon-appflow
slug: amazon-appflow-context
source_filename: amazon-appflow-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/appflow/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeleteFlowRequest\": \"amzn:DeleteFlowRequest\",\n    \"ListConnectorsResponse\": \"amzn:ListConnectorsResponse\",\n    \"DescribeFlowExecutionRecordsResponse\": \"amzn:DescribeFlowExecutionRecordsResponse\",\n    \"UnregisterConnectorRequest\": \"amzn:UnregisterConnectorRequest\",\n    \"RegisterConnectorResponse\": \"amzn:RegisterConnectorResponse\",\n    \"ConnectorProfile\": \"amzn:ConnectorProfile\",\n    \"UpdateFlowRequest\": \"amzn:UpdateFlowRequest\",\n    \"ExecutionDetails\": \"amzn:ExecutionDetails\",\n    \"DeleteConnectorProfileRequest\": \"amzn:DeleteConnectorProfileRequest\",\n    \"DescribeConnectorProfilesResponse\": \"amzn:DescribeConnectorProfilesResponse\",\n    \"DescribeConnectorRequest\": \"amzn:DescribeConnectorRequest\"\
  ,\n    \"CreateFlowRequest\": \"amzn:CreateFlowRequest\",\n    \"DescribeFlowRequest\": \"amzn:DescribeFlowRequest\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"ScheduledTriggerProperties\": \"amzn:ScheduledTriggerProperties\",\n    \"ResetConnectorMetadataCacheRequest\": \"amzn:ResetConnectorMetadataCacheRequest\",\n    \"ListFlowsRequest\": \"amzn:ListFlowsRequest\",\n    \"FlowExecution\": \"amzn:FlowExecution\",\n    \"CreateConnectorProfileResponse\": \"amzn:CreateConnectorProfileResponse\",\n    \"DescribeFlowResponse\": \"amzn:DescribeFlowResponse\",\n    \"ListFlowsResponse\": \"amzn:ListFlowsResponse\",\n    \"ConnectorDetail\": \"amzn:ConnectorDetail\",\n    \"RegisterConnectorRequest\": \"amzn:RegisterConnectorRequest\",\n    \"TriggerConfig\": \"amzn:TriggerConfig\",\n    \"UpdateConnectorRegistrationResponse\": \"amzn:UpdateConnectorRegistrationResponse\",\n    \"Task\": \"amzn:Task\",\n    \"StopFlowRequest\": \"amzn:StopFlowRequest\",\n    \"Amazon\
  \ AppFlow Flow Definition\": \"amzn:Amazon AppFlow Flow Definition\",\n    \"ListConnectorEntitiesRequest\": \"amzn:ListConnectorEntitiesRequest\",\n    \"UpdateConnectorRegistrationRequest\": \"amzn:UpdateConnectorRegistrationRequest\",\n    \"ConnectorEntityField\": \"amzn:ConnectorEntityField\",\n    \"DescribeConnectorsRequest\": \"amzn:DescribeConnectorsRequest\",\n    \"CreateConnectorProfileRequest\": \"amzn:CreateConnectorProfileRequest\",\n    \"SourceFlowConfig\": \"amzn:SourceFlowConfig\",\n    \"ConnectorEntity\": \"amzn:ConnectorEntity\",\n    \"ListConnectorsRequest\": \"amzn:ListConnectorsRequest\",\n    \"StartFlowResponse\": \"amzn:StartFlowResponse\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"StartFlowRequest\": \"amzn:StartFlowRequest\",\n    \"UpdateFlowResponse\": \"amzn:UpdateFlowResponse\",\n    \"CancelFlowExecutionsResponse\": \"amzn:CancelFlowExecutionsResponse\",\n    \"FlowDefinition\": \"amzn:FlowDefinition\",\n    \"\
  StopFlowResponse\": \"amzn:StopFlowResponse\",\n    \"CancelFlowExecutionsRequest\": \"amzn:CancelFlowExecutionsRequest\",\n    \"DescribeConnectorEntityRequest\": \"amzn:DescribeConnectorEntityRequest\",\n    \"DestinationFlowConfig\": \"amzn:DestinationFlowConfig\",\n    \"DescribeConnectorResponse\": \"amzn:DescribeConnectorResponse\",\n    \"ListConnectorEntitiesResponse\": \"amzn:ListConnectorEntitiesResponse\",\n    \"UpdateConnectorProfileResponse\": \"amzn:UpdateConnectorProfileResponse\",\n    \"DescribeConnectorEntityResponse\": \"amzn:DescribeConnectorEntityResponse\",\n    \"MetadataCatalogConfig\": \"amzn:MetadataCatalogConfig\",\n    \"UpdateConnectorProfileRequest\": \"amzn:UpdateConnectorProfileRequest\",\n    \"DescribeConnectorsResponse\": \"amzn:DescribeConnectorsResponse\",\n    \"ExecutionResult\": \"amzn:ExecutionResult\",\n    \"DescribeFlowExecutionRecordsRequest\": \"amzn:DescribeFlowExecutionRecordsRequest\",\n    \"CreateFlowResponse\": \"amzn:CreateFlowResponse\"\
  ,\n    \"DescribeConnectorProfilesRequest\": \"amzn:DescribeConnectorProfilesRequest\",\n    \"flowName\": {\n      \"@id\": \"amzn:flow_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forceDelete\": {\n      \"@id\": \"amzn:force_delete\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"connectors\": {\n      \"@id\": \"amzn:connectors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flowExecutions\": {\n      \"@id\": \"amzn:flow_executions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorLabel\": {\n      \"@id\": \"amzn:connector_label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorArn\": {\n      \"@id\": \"amzn:connector_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProfileArn\": {\n      \"@id\": \"amzn:connector_profile_arn\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"connectorProfileName\": {\n      \"@id\": \"amzn:connector_profile_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorType\": {\n      \"@id\": \"amzn:connector_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectionMode\": {\n      \"@id\": \"amzn:connection_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"credentialsArn\": {\n      \"@id\": \"amzn:credentials_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProfileProperties\": {\n      \"@id\": \"amzn:connector_profile_properties\",\n      \"@type\": \"@id\"\n    },\n    \"createdAt\": \"schema:dateCreated\",\n    \"lastUpdatedAt\": \"schema:dateModified\",\n    \"privateConnectionProvisioningState\": {\n      \"@id\": \"amzn:private_connection_provisioning_state\",\n      \"@type\": \"@id\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amzn:client_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"triggerConfig\": {\n\
  \      \"@id\": \"amzn:trigger_config\",\n      \"@type\": \"@id\"\n    },\n    \"triggerType\": {\n      \"@id\": \"amzn:trigger_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"triggerProperties\": {\n      \"@id\": \"amzn:trigger_properties\",\n      \"@type\": \"@id\"\n    },\n    \"Scheduled\": {\n      \"@id\": \"amzn:scheduled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceFlowConfig\": {\n      \"@id\": \"amzn:source_flow_config\",\n      \"@type\": \"@id\"\n    },\n    \"apiVersion\": {\n      \"@id\": \"amzn:api_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceConnectorProperties\": {\n      \"@id\": \"amzn:source_connector_properties\",\n      \"@type\": \"@id\"\n    },\n    \"incrementalPullConfig\": {\n      \"@id\": \"amzn:incremental_pull_config\",\n      \"@type\": \"@id\"\n    },\n    \"datetimeTypeFieldName\": {\n      \"@id\": \"amzn:datetime_type_field_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationFlowConfigList\"\
  : {\n      \"@id\": \"amzn:destination_flow_config_list\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tasks\": {\n      \"@id\": \"amzn:tasks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadataCatalogConfig\": {\n      \"@id\": \"amzn:metadata_catalog_config\",\n      \"@type\": \"@id\"\n    },\n    \"glueDataCatalog\": {\n      \"@id\": \"amzn:glue_data_catalog\",\n      \"@type\": \"@id\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:role_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseName\": {\n      \"@id\": \"amzn:database_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tablePrefix\": {\n      \"@id\": \"amzn:table_prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mostRecentExecutionMessage\": {\n      \"@id\": \"amzn:most_recent_execution_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mostRecentExecutionTime\": {\n      \"@id\": \"amzn:most_recent_execution_time\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"mostRecentExecutionStatus\": {\n      \"@id\": \"amzn:most_recent_execution_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProfileDetails\": {\n      \"@id\": \"amzn:connector_profile_details\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsArn\": {\n      \"@id\": \"amzn:kms_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"@id\"\n    },\n    \"scheduleExpression\": {\n      \"@id\": \"amzn:schedule_expression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataPullMode\": {\n      \"@id\": \"amzn:data_pull_mode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleStartTime\": {\n      \"@id\": \"amzn:schedule_start_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scheduleEndTime\": {\n      \"@id\": \"amzn:schedule_end_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timezone\": {\n    \
  \  \"@id\": \"amzn:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleOffset\": {\n      \"@id\": \"amzn:schedule_offset\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"firstExecutionFrom\": {\n      \"@id\": \"amzn:first_execution_from\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flowErrorDeactivationThreshold\": {\n      \"@id\": \"amzn:flow_error_deactivation_threshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"connectorEntityName\": {\n      \"@id\": \"amzn:connector_entity_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entitiesPath\": {\n      \"@id\": \"amzn:entities_path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:max_results\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"executionId\": {\n      \"@id\": \"amzn:execution_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionStatus\": {\n      \"@id\": \"amzn:execution_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  executionResult\": {\n      \"@id\": \"amzn:execution_result\",\n      \"@type\": \"@id\"\n    },\n    \"errorInfo\": {\n      \"@id\": \"amzn:error_info\",\n      \"@type\": \"@id\"\n    },\n    \"bytesProcessed\": {\n      \"@id\": \"amzn:bytes_processed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"bytesWritten\": {\n      \"@id\": \"amzn:bytes_written\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"recordsProcessed\": {\n      \"@id\": \"amzn:records_processed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"numParallelProcesses\": {\n      \"@id\": \"amzn:num_parallel_processes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startedAt\": {\n      \"@id\": \"amzn:started_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataPullStartTime\": {\n      \"@id\": \"amzn:data_pull_start_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"dataPullEndTime\": {\n      \"@id\": \"amzn:data_pull_end_time\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"flowArn\"\
  : {\n      \"@id\": \"amzn:flow_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flowStatus\": {\n      \"@id\": \"amzn:flow_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flowStatusMessage\": {\n      \"@id\": \"amzn:flow_status_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRunExecutionDetails\": {\n      \"@id\": \"amzn:last_run_execution_details\",\n      \"@type\": \"@id\"\n    },\n    \"createdBy\": {\n      \"@id\": \"amzn:created_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedBy\": {\n      \"@id\": \"amzn:last_updated_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastRunMetadataCatalogDetails\": {\n      \"@id\": \"amzn:last_run_metadata_catalog_details\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"flows\": {\n      \"@id\": \"amzn:flows\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorDescription\": {\n      \"@id\": \"amzn:connector_description\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorName\": {\n      \"@id\": \"amzn:connector_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorOwner\": {\n      \"@id\": \"amzn:connector_owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorVersion\": {\n      \"@id\": \"amzn:connector_version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationType\": {\n      \"@id\": \"amzn:application_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"registeredAt\": {\n      \"@id\": \"amzn:registered_at\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"registeredBy\": {\n      \"@id\": \"amzn:registered_by\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProvisioningType\": {\n      \"@id\": \"amzn:connector_provisioning_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorModes\": {\n      \"@id\": \"amzn:connector_modes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedDataTransferTypes\"\
  : {\n      \"@id\": \"amzn:supported_data_transfer_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProvisioningConfig\": {\n      \"@id\": \"amzn:connector_provisioning_config\",\n      \"@type\": \"@id\"\n    },\n    \"lambda\": {\n      \"@id\": \"amzn:lambda\",\n      \"@type\": \"@id\"\n    },\n    \"lambdaArn\": {\n      \"@id\": \"amzn:lambda_arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceFields\": {\n      \"@id\": \"amzn:source_fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorOperator\": {\n      \"@id\": \"amzn:connector_operator\",\n      \"@type\": \"@id\"\n    },\n    \"destinationField\": {\n      \"@id\": \"amzn:destination_field\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskType\": {\n      \"@id\": \"amzn:task_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"taskProperties\": {\n      \"@id\": \"amzn:task_properties\",\n      \"@type\": \"\
  @id\"\n    },\n    \"identifier\": {\n      \"@id\": \"amzn:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentIdentifier\": {\n      \"@id\": \"amzn:parent_identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"label\": {\n      \"@id\": \"amzn:label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPrimaryKey\": {\n      \"@id\": \"amzn:is_primary_key\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"amzn:default_value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isDeprecated\": {\n      \"@id\": \"amzn:is_deprecated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportedFieldTypeDetails\": {\n      \"@id\": \"amzn:supported_field_type_details\",\n      \"@type\": \"@id\"\n    },\n    \"sourceProperties\": {\n      \"@id\": \"amzn:source_properties\",\n      \"@type\": \"@id\"\n    },\n    \"isQueryable\": {\n      \"@id\": \"amzn:is_queryable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isRetrievable\"\
  : {\n      \"@id\": \"amzn:is_retrievable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isPartitioningSupported\": {\n      \"@id\": \"amzn:is_partitioning_supported\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"destinationProperties\": {\n      \"@id\": \"amzn:destination_properties\",\n      \"@type\": \"@id\"\n    },\n    \"isCreatable\": {\n      \"@id\": \"amzn:is_creatable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isNullable\": {\n      \"@id\": \"amzn:is_nullable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUpsertable\": {\n      \"@id\": \"amzn:is_upsertable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isUpdatable\": {\n      \"@id\": \"amzn:is_updatable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isDefaultedOnCreate\": {\n      \"@id\": \"amzn:is_defaulted_on_create\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"supportedWriteOperations\": {\n      \"@id\": \"amzn:supported_write_operations\",\n      \"@container\": \"@set\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"connectorTypes\": {\n      \"@id\": \"amzn:connector_types\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectorProfileConfig\": {\n      \"@id\": \"amzn:connector_profile_config\",\n      \"@type\": \"@id\"\n    },\n    \"name\": \"schema:name\",\n    \"hasNestedEntities\": {\n      \"@id\": \"amzn:has_nested_entities\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"invalidExecutions\": {\n      \"@id\": \"amzn:invalid_executions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceConnectorType\": {\n      \"@id\": \"amzn:source_connector_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceConnectorLabel\": {\n      \"@id\": \"amzn:source_connector_label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationConnectorType\": {\n      \"@id\": \"amzn:destination_connector_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationConnectorLabel\"\
  : {\n      \"@id\": \"amzn:destination_connector_label\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionIds\": {\n      \"@id\": \"amzn:execution_ids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinationConnectorProperties\": {\n      \"@id\": \"amzn:destination_connector_properties\",\n      \"@type\": \"@id\"\n    },\n    \"connectorConfiguration\": {\n      \"@id\": \"amzn:connector_configuration\",\n      \"@type\": \"@id\"\n    },\n    \"canUseAsSource\": {\n      \"@id\": \"amzn:can_use_as_source\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"canUseAsDestination\": {\n      \"@id\": \"amzn:can_use_as_destination\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"connectorEntityMap\": {\n      \"@id\": \"amzn:connector_entity_map\",\n      \"@type\": \"@id\"\n    },\n    \"connectorEntityFields\": {\n      \"@id\": \"amzn:connector_entity_fields\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"connectorConfigurations\": {\n      \"@id\": \"amzn:connector_configurations\",\n      \"@type\": \"@id\"\n    },\n    \"connectorProfileNames\": {\n      \"@id\": \"amzn:connector_profile_names\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-appflow/refs/heads/main/json-ld/amazon-appflow-context.jsonld
tags:
- AWS
- Connectors
- Data Flow
- Data Integration
- ETL
- Integration
- SaaS
- Data Transfer
- JSON-LD
- Linked Data
- Semantic Web
---
