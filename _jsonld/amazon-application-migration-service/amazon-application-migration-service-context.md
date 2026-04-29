---
class_count: 100
classes:
- ErrorResponse
- SourceServer
- LifeCycle
- LifeCycleLastTest
- LifeCycleLastCutover
- DataReplicationInfo
- DataReplicationInfoReplicatedDisk
- DataReplicationInitiation
- DataReplicationInitiationStep
- DataReplicationError
- SourceProperties
- IdentificationHints
- NetworkInterface
- Disk
- CPU
- OS
- LaunchedInstance
- ReplicationConfiguration
- ReplicationConfigurationReplicatedDisk
- ReplicationConfigurationTemplate
- LaunchConfiguration
- Licensing
- PostLaunchActions
- SsmDocument
- SsmParameterStoreParameter
- LaunchConfigurationTemplate
- Application
- ApplicationAggregatedStatus
- Wave
- WaveAggregatedStatus
- Job
- ParticipatingServer
- PostLaunchActionsStatus
- JobLogItem
- JobLogEventData
- VcenterClient
- ExportTaskError
- ExportTaskErrorData
- SourceServerAction
- DescribeSourceServersRequest
- DescribeSourceServersRequestFilters
- DescribeSourceServersResponse
- MarkAsArchivedRequest
- DeleteSourceServerRequest
- DisconnectFromServiceRequest
- RetryDataReplicationRequest
- GetReplicationConfigurationRequest
- UpdateReplicationConfigurationRequest
- DescribeReplicationConfigurationTemplatesRequest
- DescribeReplicationConfigurationTemplatesResponse
- CreateReplicationConfigurationTemplateRequest
- UpdateReplicationConfigurationTemplateRequest
- DeleteReplicationConfigurationTemplateRequest
- GetLaunchConfigurationRequest
- UpdateLaunchConfigurationRequest
- DescribeLaunchConfigurationTemplatesRequest
- DescribeLaunchConfigurationTemplatesResponse
- CreateLaunchConfigurationTemplateRequest
- UpdateLaunchConfigurationTemplateRequest
- DeleteLaunchConfigurationTemplateRequest
- StartTestRequest
- StartTestResponse
- StartCutoverRequest
- StartCutoverResponse
- FinalizeCutoverRequest
- TerminateTargetInstancesRequest
- TerminateTargetInstancesResponse
- DescribeJobsRequest
- DescribeJobsRequestFilters
- DescribeJobsResponse
- DescribeJobLogItemsRequest
- DescribeJobLogItemsResponse
- ListApplicationsRequest
- ListApplicationsRequestFilters
- ListApplicationsResponse
- CreateApplicationRequest
- UpdateApplicationRequest
- DeleteApplicationRequest
- ArchiveApplicationRequest
- UnarchiveApplicationRequest
- AssociateSourceServersRequest
- DisassociateSourceServersRequest
- ListWavesRequest
- ListWavesRequestFilters
- ListWavesResponse
- CreateWaveRequest
- UpdateWaveRequest
- DeleteWaveRequest
- AssociateApplicationsRequest
- ExportErrorsRequest
- ExportErrorsResponse
- ListExportErrorsRequest
- ListExportErrorsResponse
- ListSourceServerActionsRequest
- ListSourceServerActionsResponse
- ListTemplateActionsRequest
- ListTemplateActionsResponse
- DescribeVcenterClientsResponse
- ListTagsForResourceResponse
- TagResourceRequest
context_file: json-ld/amazon-application-migration-service-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-ld/amazon-application-migration-service-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Application Migration Service from Amazon Application Migration Service.
layout: jsonld
name: Amazon Application Migration Service Context
namespaces:
- prefix: mgn
  uri: https://api-evangelist.github.io/amazon-application-migration-service/vocabulary/
- prefix: aws
  uri: https://aws.amazon.com/vocabulary/
properties: []
property_count: 0
provider_name: Amazon Application Migration Service
provider_slug: amazon-application-migration-service
slug: amazon-application-migration-service-context
source_filename: amazon-application-migration-service-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"mgn\": \"https://api-evangelist.github.io/amazon-application-migration-service/vocabulary/\",\n    \"aws\": \"https://aws.amazon.com/vocabulary/\",\n    \"ErrorResponse\": \"mgn:ErrorResponse\",\n    \"SourceServer\": \"mgn:SourceServer\",\n    \"LifeCycle\": \"mgn:LifeCycle\",\n    \"LifeCycleLastTest\": \"mgn:LifeCycleLastTest\",\n    \"LifeCycleLastCutover\": \"mgn:LifeCycleLastCutover\",\n    \"DataReplicationInfo\": \"mgn:DataReplicationInfo\",\n    \"DataReplicationInfoReplicatedDisk\": \"mgn:DataReplicationInfoReplicatedDisk\",\n    \"DataReplicationInitiation\": \"mgn:DataReplicationInitiation\",\n    \"DataReplicationInitiationStep\": \"mgn:DataReplicationInitiationStep\",\n    \"DataReplicationError\": \"mgn:DataReplicationError\",\n    \"SourceProperties\": \"mgn:SourceProperties\",\n    \"IdentificationHints\": \"mgn:IdentificationHints\",\n    \"NetworkInterface\": \"mgn:NetworkInterface\",\n\
  \    \"Disk\": \"mgn:Disk\",\n    \"CPU\": \"mgn:CPU\",\n    \"OS\": \"mgn:OS\",\n    \"LaunchedInstance\": \"mgn:LaunchedInstance\",\n    \"ReplicationConfiguration\": \"mgn:ReplicationConfiguration\",\n    \"ReplicationConfigurationReplicatedDisk\": \"mgn:ReplicationConfigurationReplicatedDisk\",\n    \"ReplicationConfigurationTemplate\": \"mgn:ReplicationConfigurationTemplate\",\n    \"LaunchConfiguration\": \"mgn:LaunchConfiguration\",\n    \"Licensing\": \"mgn:Licensing\",\n    \"PostLaunchActions\": \"mgn:PostLaunchActions\",\n    \"SsmDocument\": \"mgn:SsmDocument\",\n    \"SsmParameterStoreParameter\": \"mgn:SsmParameterStoreParameter\",\n    \"LaunchConfigurationTemplate\": \"mgn:LaunchConfigurationTemplate\",\n    \"Application\": \"mgn:Application\",\n    \"ApplicationAggregatedStatus\": \"mgn:ApplicationAggregatedStatus\",\n    \"Wave\": \"mgn:Wave\",\n    \"WaveAggregatedStatus\": \"mgn:WaveAggregatedStatus\",\n    \"Job\": \"mgn:Job\",\n    \"ParticipatingServer\": \"mgn:ParticipatingServer\"\
  ,\n    \"PostLaunchActionsStatus\": \"mgn:PostLaunchActionsStatus\",\n    \"JobLogItem\": \"mgn:JobLogItem\",\n    \"JobLogEventData\": \"mgn:JobLogEventData\",\n    \"VcenterClient\": \"mgn:VcenterClient\",\n    \"ExportTaskError\": \"mgn:ExportTaskError\",\n    \"ExportTaskErrorData\": \"mgn:ExportTaskErrorData\",\n    \"SourceServerAction\": \"mgn:SourceServerAction\",\n    \"DescribeSourceServersRequest\": \"mgn:DescribeSourceServersRequest\",\n    \"DescribeSourceServersRequestFilters\": \"mgn:DescribeSourceServersRequestFilters\",\n    \"DescribeSourceServersResponse\": \"mgn:DescribeSourceServersResponse\",\n    \"MarkAsArchivedRequest\": \"mgn:MarkAsArchivedRequest\",\n    \"DeleteSourceServerRequest\": \"mgn:DeleteSourceServerRequest\",\n    \"DisconnectFromServiceRequest\": \"mgn:DisconnectFromServiceRequest\",\n    \"RetryDataReplicationRequest\": \"mgn:RetryDataReplicationRequest\",\n    \"GetReplicationConfigurationRequest\": \"mgn:GetReplicationConfigurationRequest\",\n \
  \   \"UpdateReplicationConfigurationRequest\": \"mgn:UpdateReplicationConfigurationRequest\",\n    \"DescribeReplicationConfigurationTemplatesRequest\": \"mgn:DescribeReplicationConfigurationTemplatesRequest\",\n    \"DescribeReplicationConfigurationTemplatesResponse\": \"mgn:DescribeReplicationConfigurationTemplatesResponse\",\n    \"CreateReplicationConfigurationTemplateRequest\": \"mgn:CreateReplicationConfigurationTemplateRequest\",\n    \"UpdateReplicationConfigurationTemplateRequest\": \"mgn:UpdateReplicationConfigurationTemplateRequest\",\n    \"DeleteReplicationConfigurationTemplateRequest\": \"mgn:DeleteReplicationConfigurationTemplateRequest\",\n    \"GetLaunchConfigurationRequest\": \"mgn:GetLaunchConfigurationRequest\",\n    \"UpdateLaunchConfigurationRequest\": \"mgn:UpdateLaunchConfigurationRequest\",\n    \"DescribeLaunchConfigurationTemplatesRequest\": \"mgn:DescribeLaunchConfigurationTemplatesRequest\",\n    \"DescribeLaunchConfigurationTemplatesResponse\": \"mgn:DescribeLaunchConfigurationTemplatesResponse\"\
  ,\n    \"CreateLaunchConfigurationTemplateRequest\": \"mgn:CreateLaunchConfigurationTemplateRequest\",\n    \"UpdateLaunchConfigurationTemplateRequest\": \"mgn:UpdateLaunchConfigurationTemplateRequest\",\n    \"DeleteLaunchConfigurationTemplateRequest\": \"mgn:DeleteLaunchConfigurationTemplateRequest\",\n    \"StartTestRequest\": \"mgn:StartTestRequest\",\n    \"StartTestResponse\": \"mgn:StartTestResponse\",\n    \"StartCutoverRequest\": \"mgn:StartCutoverRequest\",\n    \"StartCutoverResponse\": \"mgn:StartCutoverResponse\",\n    \"FinalizeCutoverRequest\": \"mgn:FinalizeCutoverRequest\",\n    \"TerminateTargetInstancesRequest\": \"mgn:TerminateTargetInstancesRequest\",\n    \"TerminateTargetInstancesResponse\": \"mgn:TerminateTargetInstancesResponse\",\n    \"DescribeJobsRequest\": \"mgn:DescribeJobsRequest\",\n    \"DescribeJobsRequestFilters\": \"mgn:DescribeJobsRequestFilters\",\n    \"DescribeJobsResponse\": \"mgn:DescribeJobsResponse\",\n    \"DescribeJobLogItemsRequest\": \"mgn:DescribeJobLogItemsRequest\"\
  ,\n    \"DescribeJobLogItemsResponse\": \"mgn:DescribeJobLogItemsResponse\",\n    \"ListApplicationsRequest\": \"mgn:ListApplicationsRequest\",\n    \"ListApplicationsRequestFilters\": \"mgn:ListApplicationsRequestFilters\",\n    \"ListApplicationsResponse\": \"mgn:ListApplicationsResponse\",\n    \"CreateApplicationRequest\": \"mgn:CreateApplicationRequest\",\n    \"UpdateApplicationRequest\": \"mgn:UpdateApplicationRequest\",\n    \"DeleteApplicationRequest\": \"mgn:DeleteApplicationRequest\",\n    \"ArchiveApplicationRequest\": \"mgn:ArchiveApplicationRequest\",\n    \"UnarchiveApplicationRequest\": \"mgn:UnarchiveApplicationRequest\",\n    \"AssociateSourceServersRequest\": \"mgn:AssociateSourceServersRequest\",\n    \"DisassociateSourceServersRequest\": \"mgn:DisassociateSourceServersRequest\",\n    \"ListWavesRequest\": \"mgn:ListWavesRequest\",\n    \"ListWavesRequestFilters\": \"mgn:ListWavesRequestFilters\",\n    \"ListWavesResponse\": \"mgn:ListWavesResponse\",\n    \"CreateWaveRequest\"\
  : \"mgn:CreateWaveRequest\",\n    \"UpdateWaveRequest\": \"mgn:UpdateWaveRequest\",\n    \"DeleteWaveRequest\": \"mgn:DeleteWaveRequest\",\n    \"AssociateApplicationsRequest\": \"mgn:AssociateApplicationsRequest\",\n    \"ExportErrorsRequest\": \"mgn:ExportErrorsRequest\",\n    \"ExportErrorsResponse\": \"mgn:ExportErrorsResponse\",\n    \"ListExportErrorsRequest\": \"mgn:ListExportErrorsRequest\",\n    \"ListExportErrorsResponse\": \"mgn:ListExportErrorsResponse\",\n    \"ListSourceServerActionsRequest\": \"mgn:ListSourceServerActionsRequest\",\n    \"ListSourceServerActionsResponse\": \"mgn:ListSourceServerActionsResponse\",\n    \"ListTemplateActionsRequest\": \"mgn:ListTemplateActionsRequest\",\n    \"ListTemplateActionsResponse\": \"mgn:ListTemplateActionsResponse\",\n    \"DescribeVcenterClientsResponse\": \"mgn:DescribeVcenterClientsResponse\",\n    \"ListTagsForResourceResponse\": \"mgn:ListTagsForResourceResponse\",\n    \"TagResourceRequest\": \"mgn:TagResourceRequest\"\n  }\n\
  }"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-application-migration-service/refs/heads/main/json-ld/amazon-application-migration-service-context.jsonld
tags:
- Amazon Application Migration Service
- Migration
- Lift And Shift
- AWS
- Cloud Migration
- JSON-LD
- Linked Data
- Semantic Web
---
