---
api_specs:
- filename: amazon-migration-hub-openapi-original.yml
  format: yaml
  label: Amazon Migration Hub API
  slug: migration-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-migration-hub/refs/heads/main/openapi/amazon-migration-hub-openapi-original.yml
class_count: 80
classes:
- Token
- DiscoveredResource
- CreatedArtifactDescription
- DisassociateCreatedArtifactRequest
- ListProgressUpdateStreamsResult
- ProgressUpdateStream
- ConfigurationId
- DescribeMigrationTaskResult
- ProgressUpdateStreamSummary
- Task
- ResourceAttributeType
- InvalidInputException
- DryRun
- DescribeApplicationStateResult
- NotifyMigrationTaskStateRequest
- ResourceAttributeValue
- CreatedArtifactList
- ImportMigrationTaskResult
- CreatedArtifactName
- ResourceAttributeList
- ResourceNotFoundException
- DescribeApplicationStateRequest
- ResourceAttribute
- ListMigrationTasksResult
- DryRunOperation
- ListProgressUpdateStreamsRequest
- MaxResultsCreatedArtifacts
- MigrationTaskName
- PutResourceAttributesRequest
- ImportMigrationTaskRequest
- CreateProgressUpdateStreamRequest
- ListCreatedArtifactsResult
- MaxResults
- DeleteProgressUpdateStreamRequest
- ResourceName
- DiscoveredResourceList
- CreatedArtifact
- ProgressPercent
- ListApplicationStatesRequest
- AssociateDiscoveredResourceResult
- CreateProgressUpdateStreamResult
- InternalServerError
- PolicyErrorException
- UnauthorizedOperation
- MigrationTaskSummary
- ApplicationId
- ListApplicationStatesResult
- ListMigrationTasksRequest
- ListDiscoveredResourcesResult
- MaxResultsResources
- UpdateDateTime
- HomeRegionNotSetException
- Status
- DiscoveredResourceDescription
- ListDiscoveredResourcesRequest
- ApplicationState
- NextUpdateSeconds
- NotifyApplicationStateResult
- DescribeMigrationTaskRequest
- StatusDetail
- ProgressUpdateStreamSummaryList
- ApplicationStateList
- NotifyApplicationStateRequest
- ApplicationIds
- PutResourceAttributesResult
- ApplicationStatus
- DeleteProgressUpdateStreamResult
- DisassociateDiscoveredResourceResult
- NotifyMigrationTaskStateResult
- DisassociateDiscoveredResourceRequest
- AssociateCreatedArtifactResult
- LatestResourceAttributeList
- AssociateDiscoveredResourceRequest
- ListCreatedArtifactsRequest
- MigrationTask
- AssociateCreatedArtifactRequest
- DisassociateCreatedArtifactResult
- MigrationTaskSummaryList
- description
- name
context_file: json-ld/amazon-migration-hub-migration-hub-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-migration-hub/refs/heads/main/json-ld/amazon-migration-hub-migration-hub-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Migration Hub Migration Hub Api from Amazon Migration Hub.
layout: jsonld
name: Amazon Migration Hub Migration Hub Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: configurationId
  type: string
- container: ''
  name: progressUpdateStream
  type: string
- container: ''
  name: migrationTaskName
  type: string
- container: ''
  name: createdArtifactName
  type: string
- container: ''
  name: dryRun
  type: string
- container: ''
  name: progressUpdateStreamSummaryList
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: migrationTask
  type: string
- container: ''
  name: progressUpdateStreamName
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusDetail
  type: string
- container: ''
  name: progressPercent
  type: string
- container: ''
  name: applicationStatus
  type: string
- container: ''
  name: lastUpdatedTime
  type: string
- container: ''
  name: task
  type: string
- container: ''
  name: updateDateTime
  type: string
- container: ''
  name: nextUpdateSeconds
  type: string
- container: ''
  name: applicationId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: migrationTaskSummaryList
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: resourceAttributeList
  type: string
- container: ''
  name: createdArtifactList
  type: string
- container: ''
  name: applicationIds
  type: string
- container: ''
  name: applicationStateList
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: discoveredResourceList
  type: string
- container: ''
  name: discoveredResource
  type: string
- container: ''
  name: createdArtifact
  type: string
property_count: 30
provider_name: Amazon Migration Hub
provider_slug: amazon-migration-hub
slug: amazon-migration-hub-migration-hub-api-context
source_filename: amazon-migration-hub-migration-hub-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Token\": \"pan:Token\",\n    \"DiscoveredResource\": \"pan:DiscoveredResource\",\n    \"CreatedArtifactDescription\": \"pan:CreatedArtifactDescription\",\n    \"DisassociateCreatedArtifactRequest\": \"pan:DisassociateCreatedArtifactRequest\",\n    \"ListProgressUpdateStreamsResult\": \"pan:ListProgressUpdateStreamsResult\",\n    \"ProgressUpdateStream\": \"pan:ProgressUpdateStream\",\n    \"ConfigurationId\": \"pan:ConfigurationId\",\n    \"DescribeMigrationTaskResult\": \"pan:DescribeMigrationTaskResult\",\n    \"ProgressUpdateStreamSummary\": \"pan:ProgressUpdateStreamSummary\",\n    \"Task\": \"pan:Task\",\n    \"ResourceAttributeType\": \"pan:ResourceAttributeType\",\n    \"InvalidInputException\": \"pan:InvalidInputException\",\n    \"\
  DryRun\": \"pan:DryRun\",\n    \"DescribeApplicationStateResult\": \"pan:DescribeApplicationStateResult\",\n    \"NotifyMigrationTaskStateRequest\": \"pan:NotifyMigrationTaskStateRequest\",\n    \"ResourceAttributeValue\": \"pan:ResourceAttributeValue\",\n    \"CreatedArtifactList\": \"pan:CreatedArtifactList\",\n    \"ImportMigrationTaskResult\": \"pan:ImportMigrationTaskResult\",\n    \"CreatedArtifactName\": \"pan:CreatedArtifactName\",\n    \"ResourceAttributeList\": \"pan:ResourceAttributeList\",\n    \"ResourceNotFoundException\": \"pan:ResourceNotFoundException\",\n    \"DescribeApplicationStateRequest\": \"pan:DescribeApplicationStateRequest\",\n    \"ResourceAttribute\": \"pan:ResourceAttribute\",\n    \"ListMigrationTasksResult\": \"pan:ListMigrationTasksResult\",\n    \"DryRunOperation\": \"pan:DryRunOperation\",\n    \"ListProgressUpdateStreamsRequest\": \"pan:ListProgressUpdateStreamsRequest\",\n    \"MaxResultsCreatedArtifacts\": \"pan:MaxResultsCreatedArtifacts\",\n    \"\
  MigrationTaskName\": \"pan:MigrationTaskName\",\n    \"PutResourceAttributesRequest\": \"pan:PutResourceAttributesRequest\",\n    \"ImportMigrationTaskRequest\": \"pan:ImportMigrationTaskRequest\",\n    \"CreateProgressUpdateStreamRequest\": \"pan:CreateProgressUpdateStreamRequest\",\n    \"ListCreatedArtifactsResult\": \"pan:ListCreatedArtifactsResult\",\n    \"MaxResults\": \"pan:MaxResults\",\n    \"DeleteProgressUpdateStreamRequest\": \"pan:DeleteProgressUpdateStreamRequest\",\n    \"ResourceName\": \"pan:ResourceName\",\n    \"DiscoveredResourceList\": \"pan:DiscoveredResourceList\",\n    \"CreatedArtifact\": \"pan:CreatedArtifact\",\n    \"ProgressPercent\": \"pan:ProgressPercent\",\n    \"ListApplicationStatesRequest\": \"pan:ListApplicationStatesRequest\",\n    \"AssociateDiscoveredResourceResult\": \"pan:AssociateDiscoveredResourceResult\",\n    \"CreateProgressUpdateStreamResult\": \"pan:CreateProgressUpdateStreamResult\",\n    \"InternalServerError\": \"pan:InternalServerError\"\
  ,\n    \"PolicyErrorException\": \"pan:PolicyErrorException\",\n    \"UnauthorizedOperation\": \"pan:UnauthorizedOperation\",\n    \"MigrationTaskSummary\": \"pan:MigrationTaskSummary\",\n    \"ApplicationId\": \"pan:ApplicationId\",\n    \"ListApplicationStatesResult\": \"pan:ListApplicationStatesResult\",\n    \"ListMigrationTasksRequest\": \"pan:ListMigrationTasksRequest\",\n    \"ListDiscoveredResourcesResult\": \"pan:ListDiscoveredResourcesResult\",\n    \"MaxResultsResources\": \"pan:MaxResultsResources\",\n    \"UpdateDateTime\": \"pan:UpdateDateTime\",\n    \"HomeRegionNotSetException\": \"pan:HomeRegionNotSetException\",\n    \"Status\": \"pan:Status\",\n    \"DiscoveredResourceDescription\": \"pan:DiscoveredResourceDescription\",\n    \"ListDiscoveredResourcesRequest\": \"pan:ListDiscoveredResourcesRequest\",\n    \"ApplicationState\": \"pan:ApplicationState\",\n    \"NextUpdateSeconds\": \"pan:NextUpdateSeconds\",\n    \"NotifyApplicationStateResult\": \"pan:NotifyApplicationStateResult\"\
  ,\n    \"DescribeMigrationTaskRequest\": \"pan:DescribeMigrationTaskRequest\",\n    \"StatusDetail\": \"pan:StatusDetail\",\n    \"ProgressUpdateStreamSummaryList\": \"pan:ProgressUpdateStreamSummaryList\",\n    \"ApplicationStateList\": \"pan:ApplicationStateList\",\n    \"NotifyApplicationStateRequest\": \"pan:NotifyApplicationStateRequest\",\n    \"ApplicationIds\": \"pan:ApplicationIds\",\n    \"PutResourceAttributesResult\": \"pan:PutResourceAttributesResult\",\n    \"ApplicationStatus\": \"pan:ApplicationStatus\",\n    \"DeleteProgressUpdateStreamResult\": \"pan:DeleteProgressUpdateStreamResult\",\n    \"DisassociateDiscoveredResourceResult\": \"pan:DisassociateDiscoveredResourceResult\",\n    \"NotifyMigrationTaskStateResult\": \"pan:NotifyMigrationTaskStateResult\",\n    \"DisassociateDiscoveredResourceRequest\": \"pan:DisassociateDiscoveredResourceRequest\",\n    \"AssociateCreatedArtifactResult\": \"pan:AssociateCreatedArtifactResult\",\n    \"LatestResourceAttributeList\": \"\
  pan:LatestResourceAttributeList\",\n    \"AssociateDiscoveredResourceRequest\": \"pan:AssociateDiscoveredResourceRequest\",\n    \"ListCreatedArtifactsRequest\": \"pan:ListCreatedArtifactsRequest\",\n    \"MigrationTask\": \"pan:MigrationTask\",\n    \"AssociateCreatedArtifactRequest\": \"pan:AssociateCreatedArtifactRequest\",\n    \"DisassociateCreatedArtifactResult\": \"pan:DisassociateCreatedArtifactResult\",\n    \"MigrationTaskSummaryList\": \"pan:MigrationTaskSummaryList\",\n    \"configurationId\": {\n      \"@id\": \"pan:configuration_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"progressUpdateStream\": {\n      \"@id\": \"pan:progress_update_stream\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationTaskName\": {\n      \"@id\": \"pan:migration_task_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdArtifactName\": {\n      \"@id\": \"pan:created_artifact_name\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"dryRun\": {\n      \"@id\": \"pan:dry_run\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressUpdateStreamSummaryList\": {\n      \"@id\": \"pan:progress_update_stream_summary_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:next_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationTask\": {\n      \"@id\": \"pan:migration_task\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressUpdateStreamName\": {\n      \"@id\": \"pan:progress_update_stream_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusDetail\": {\n      \"@id\": \"pan:status_detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressPercent\": {\n      \"@id\": \"pan:progress_percent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationStatus\": {\n      \"@id\": \"pan:application_status\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"lastUpdatedTime\": {\n      \"@id\": \"pan:last_updated_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"task\": {\n      \"@id\": \"pan:task\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updateDateTime\": {\n      \"@id\": \"pan:update_date_time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextUpdateSeconds\": {\n      \"@id\": \"pan:next_update_seconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationId\": {\n      \"@id\": \"pan:application_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"migrationTaskSummaryList\": {\n      \"@id\": \"pan:migration_task_summary_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"pan:max_results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceAttributeList\": {\n      \"@id\": \"pan:resource_attribute_list\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"createdArtifactList\": {\n      \"@id\": \"pan:created_artifact_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"applicationIds\": {\n      \"@id\": \"pan:application_ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationStateList\": {\n      \"@id\": \"pan:application_state_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"pan:resource_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveredResourceList\": {\n      \"@id\": \"pan:discovered_resource_list\",\n      \"@type\": \"xsd:string\"\n    },\n    \"discoveredResource\": {\n      \"@id\": \"pan:discovered_resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdArtifact\": {\n      \"@id\": \"pan:created_artifact\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-migration-hub/refs/heads/main/json-ld/amazon-migration-hub-migration-hub-api-context.jsonld
tags:
- AWS
- Broadcasting
- Media Processing
- Media
- JSON-LD
- Linked Data
- Semantic Web
---
