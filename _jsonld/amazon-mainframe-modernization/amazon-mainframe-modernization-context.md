---
api_specs:
- filename: amazon-mainframe-modernization-openapi-original.yaml
  format: yaml
  label: AWS Mainframe Modernization API
  slug: aws-mainframe-modernization-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/openapi/amazon-mainframe-modernization-openapi-original.yaml
class_count: 108
classes:
- AlternateKey
- ApplicationSummary
- ApplicationVersionSummary
- BatchJobDefinition
- BatchJobExecutionSummary
- BatchJobIdentifier
- BatchJobParametersMap
- CancelBatchJobExecutionRequest
- CancelBatchJobExecutionResponse
- CreateApplicationRequest
- CreateApplicationResponse
- CreateDataSetImportTaskRequest
- CreateDataSetImportTaskResponse
- CreateDeploymentRequest
- CreateDeploymentResponse
- CreateEnvironmentRequest
- CreateEnvironmentResponse
- DataSet
- DataSetImportConfig
- DataSetImportItem
- DataSetImportSummary
- DataSetImportTask
- DataSetSummary
- DatasetDetailOrgAttributes
- DatasetOrgAttributes
- Definition
- DeleteApplicationFromEnvironmentRequest
- DeleteApplicationFromEnvironmentResponse
- DeleteApplicationRequest
- DeleteApplicationResponse
- DeleteEnvironmentRequest
- DeleteEnvironmentResponse
- DeployedVersionSummary
- DeploymentSummary
- EfsStorageConfiguration
- EngineVersionsSummary
- EnvironmentSummary
- ExternalLocation
- FileBatchJobDefinition
- FileBatchJobIdentifier
- FsxStorageConfiguration
- GdgAttributes
- GdgDetailAttributes
- GetApplicationRequest
- GetApplicationResponse
- GetApplicationVersionRequest
- GetApplicationVersionResponse
- GetBatchJobExecutionRequest
- GetBatchJobExecutionResponse
- GetDataSetDetailsRequest
- GetDataSetDetailsResponse
- GetDataSetImportTaskRequest
- GetDataSetImportTaskResponse
- GetDeploymentRequest
- GetDeploymentResponse
- GetEnvironmentRequest
- GetEnvironmentResponse
- GetSignedBluinsightsUrlResponse
- HighAvailabilityConfig
- ListApplicationVersionsRequest
- ListApplicationVersionsResponse
- ListApplicationsRequest
- ListApplicationsResponse
- ListBatchJobDefinitionsRequest
- ListBatchJobDefinitionsResponse
- ListBatchJobExecutionsRequest
- ListBatchJobExecutionsResponse
- ListDataSetImportHistoryRequest
- ListDataSetImportHistoryResponse
- ListDataSetsRequest
- ListDataSetsResponse
- ListDeploymentsRequest
- ListDeploymentsResponse
- ListEngineVersionsRequest
- ListEngineVersionsResponse
- ListEnvironmentsRequest
- ListEnvironmentsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- LogGroupSummary
- MaintenanceSchedule
- PendingMaintenance
- PoAttributes
- PoDetailAttributes
- PrimaryKey
- PsAttributes
- PsDetailAttributes
- RecordLength
- ScriptBatchJobDefinition
- ScriptBatchJobIdentifier
- StartApplicationRequest
- StartApplicationResponse
- StartBatchJobRequest
- StartBatchJobResponse
- StopApplicationRequest
- StopApplicationResponse
- StorageConfiguration
- TagMap
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- UpdateApplicationRequest
- UpdateApplicationResponse
- UpdateEnvironmentRequest
- UpdateEnvironmentResponse
- VsamAttributes
- VsamDetailAttributes
context_file: json-ld/amazon-mainframe-modernization-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/json-ld/amazon-mainframe-modernization-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mainframe Modernization from Amazon Mainframe Modernization.
layout: jsonld
name: Amazon Mainframe Modernization Context
namespaces:
- prefix: amm
  uri: https://amm.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: actualCapacity
  type: ''
- container: ''
  name: allowDuplicates
  type: ''
- container: ''
  name: alternateKeys
  type: ''
- container: ''
  name: applicationArn
  type: ''
- container: ''
  name: applicationId
  type: ''
- container: ''
  name: applicationVersion
  type: ''
- container: ''
  name: applicationVersions
  type: ''
- container: ''
  name: applications
  type: ''
- container: ''
  name: applyDuringMaintenanceWindow
  type: ''
- container: ''
  name: batchJobDefinitions
  type: ''
- container: ''
  name: batchJobExecutions
  type: ''
- container: ''
  name: batchJobIdentifier
  type: ''
- container: ''
  name: blocksize
  type: ''
- container: ''
  name: cacheAtStartup
  type: ''
- container: ''
  name: clientToken
  type: ''
- container: ''
  name: compressed
  type: ''
- container: ''
  name: content
  type: ''
- container: ''
  name: creationTime
  type: ''
- container: ''
  name: currentApplicationVersion
  type: ''
- container: ''
  name: dataSet
  type: ''
- container: ''
  name: dataSetImportTasks
  type: ''
- container: ''
  name: dataSetName
  type: ''
- container: ''
  name: dataSetOrg
  type: ''
- container: ''
  name: dataSets
  type: ''
- container: ''
  name: datasetName
  type: ''
- container: ''
  name: datasetOrg
  type: ''
- container: ''
  name: definition
  type: ''
- container: ''
  name: definitionContent
  type: ''
- container: ''
  name: deployedVersion
  type: ''
- container: ''
  name: deploymentId
  type: ''
- container: ''
  name: deploymentStatus
  type: ''
- container: ''
  name: deployments
  type: ''
- container: ''
  name: description
  type: ''
- container: ''
  name: desiredCapacity
  type: ''
- container: ''
  name: efs
  type: ''
- container: ''
  name: encoding
  type: ''
- container: ''
  name: endTime
  type: ''
- container: ''
  name: engineType
  type: ''
- container: ''
  name: engineVersion
  type: ''
- container: ''
  name: engineVersions
  type: ''
- container: ''
  name: environmentArn
  type: ''
- container: ''
  name: environmentId
  type: ''
- container: ''
  name: environments
  type: ''
- container: ''
  name: executionId
  type: ''
- container: ''
  name: externalLocation
  type: ''
- container: ''
  name: failed
  type: ''
- container: ''
  name: fileBatchJobDefinition
  type: ''
- container: ''
  name: fileBatchJobIdentifier
  type: ''
- container: ''
  name: fileName
  type: ''
- container: ''
  name: fileSystemId
  type: ''
- container: ''
  name: folderPath
  type: ''
- container: ''
  name: forceStop
  type: ''
- container: ''
  name: format
  type: ''
- container: ''
  name: fsx
  type: ''
- container: ''
  name: gdg
  type: ''
- container: ''
  name: highAvailabilityConfig
  type: ''
- container: ''
  name: importConfig
  type: ''
- container: ''
  name: inProgress
  type: ''
- container: ''
  name: instanceType
  type: ''
- container: ''
  name: jobId
  type: ''
- container: ''
  name: jobName
  type: ''
- container: ''
  name: jobParams
  type: ''
- container: ''
  name: jobType
  type: ''
- container: ''
  name: jobUser
  type: ''
- container: ''
  name: kmsKeyId
  type: ''
- container: ''
  name: lastReferencedTime
  type: ''
- container: ''
  name: lastStartTime
  type: ''
- container: ''
  name: lastUpdatedTime
  type: ''
- container: ''
  name: latestVersion
  type: ''
- container: ''
  name: length
  type: ''
- container: ''
  name: limit
  type: ''
- container: ''
  name: listenerArns
  type: ''
- container: ''
  name: listenerPorts
  type: ''
- container: ''
  name: loadBalancerArn
  type: ''
- container: ''
  name: loadBalancerDnsName
  type: ''
- container: ''
  name: location
  type: ''
- container: ''
  name: logGroupName
  type: ''
- container: ''
  name: logGroups
  type: ''
- container: ''
  name: logType
  type: ''
- container: ''
  name: max
  type: ''
- container: ''
  name: memberFileExtensions
  type: ''
- container: ''
  name: min
  type: ''
- container: ''
  name: mountPoint
  type: ''
- container: ''
  name: name
  type: ''
- container: ''
  name: nextToken
  type: ''
- container: ''
  name: offset
  type: ''
- container: ''
  name: pending
  type: ''
- container: ''
  name: pendingMaintenance
  type: ''
- container: ''
  name: po
  type: ''
- container: ''
  name: preferredMaintenanceWindow
  type: ''
- container: ''
  name: primaryKey
  type: ''
- container: ''
  name: ps
  type: ''
- container: ''
  name: publiclyAccessible
  type: ''
- container: ''
  name: recordFormat
  type: ''
- container: ''
  name: recordLength
  type: ''
- container: ''
  name: relativePath
  type: ''
- container: ''
  name: returnCode
  type: ''
- container: ''
  name: roleArn
  type: ''
- container: ''
  name: rollDisposition
  type: ''
- container: ''
  name: s3Location
  type: ''
- container: ''
  name: schedule
  type: ''
- container: ''
  name: scriptBatchJobDefinition
  type: ''
- container: ''
  name: scriptBatchJobIdentifier
  type: ''
- container: ''
  name: scriptName
  type: ''
- container: ''
  name: securityGroupIds
  type: ''
- container: ''
  name: signedBiUrl
  type: ''
- container: ''
  name: startTime
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: statusReason
  type: ''
- container: ''
  name: storageConfigurations
  type: ''
- container: ''
  name: storageType
  type: ''
- container: ''
  name: subnetIds
  type: ''
- container: ''
  name: succeeded
  type: ''
- container: ''
  name: summary
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: targetGroupArns
  type: ''
- container: ''
  name: taskId
  type: ''
- container: ''
  name: total
  type: ''
- container: ''
  name: versionStatus
  type: ''
- container: ''
  name: vpcId
  type: ''
- container: ''
  name: vsam
  type: ''
property_count: 121
provider_name: Amazon Mainframe Modernization
provider_slug: amazon-mainframe-modernization
slug: amazon-mainframe-modernization-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amm\": \"https://amm.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AlternateKey\": \"amm:AlternateKey\",\n    \"ApplicationSummary\": \"amm:ApplicationSummary\",\n    \"ApplicationVersionSummary\": \"amm:ApplicationVersionSummary\",\n    \"BatchJobDefinition\": \"amm:BatchJobDefinition\",\n    \"BatchJobExecutionSummary\": \"amm:BatchJobExecutionSummary\",\n    \"BatchJobIdentifier\": \"amm:BatchJobIdentifier\",\n    \"BatchJobParametersMap\": \"amm:BatchJobParametersMap\",\n    \"CancelBatchJobExecutionRequest\": \"amm:CancelBatchJobExecutionRequest\",\n    \"CancelBatchJobExecutionResponse\": \"amm:CancelBatchJobExecutionResponse\",\n    \"CreateApplicationRequest\": \"amm:CreateApplicationRequest\",\n    \"CreateApplicationResponse\": \"amm:CreateApplicationResponse\",\n    \"CreateDataSetImportTaskRequest\": \"amm:CreateDataSetImportTaskRequest\"\
  ,\n    \"CreateDataSetImportTaskResponse\": \"amm:CreateDataSetImportTaskResponse\",\n    \"CreateDeploymentRequest\": \"amm:CreateDeploymentRequest\",\n    \"CreateDeploymentResponse\": \"amm:CreateDeploymentResponse\",\n    \"CreateEnvironmentRequest\": \"amm:CreateEnvironmentRequest\",\n    \"CreateEnvironmentResponse\": \"amm:CreateEnvironmentResponse\",\n    \"DataSet\": \"amm:DataSet\",\n    \"DataSetImportConfig\": \"amm:DataSetImportConfig\",\n    \"DataSetImportItem\": \"amm:DataSetImportItem\",\n    \"DataSetImportSummary\": \"amm:DataSetImportSummary\",\n    \"DataSetImportTask\": \"amm:DataSetImportTask\",\n    \"DataSetSummary\": \"amm:DataSetSummary\",\n    \"DatasetDetailOrgAttributes\": \"amm:DatasetDetailOrgAttributes\",\n    \"DatasetOrgAttributes\": \"amm:DatasetOrgAttributes\",\n    \"Definition\": \"amm:Definition\",\n    \"DeleteApplicationFromEnvironmentRequest\": \"amm:DeleteApplicationFromEnvironmentRequest\",\n    \"DeleteApplicationFromEnvironmentResponse\":\
  \ \"amm:DeleteApplicationFromEnvironmentResponse\",\n    \"DeleteApplicationRequest\": \"amm:DeleteApplicationRequest\",\n    \"DeleteApplicationResponse\": \"amm:DeleteApplicationResponse\",\n    \"DeleteEnvironmentRequest\": \"amm:DeleteEnvironmentRequest\",\n    \"DeleteEnvironmentResponse\": \"amm:DeleteEnvironmentResponse\",\n    \"DeployedVersionSummary\": \"amm:DeployedVersionSummary\",\n    \"DeploymentSummary\": \"amm:DeploymentSummary\",\n    \"EfsStorageConfiguration\": \"amm:EfsStorageConfiguration\",\n    \"EngineVersionsSummary\": \"amm:EngineVersionsSummary\",\n    \"EnvironmentSummary\": \"amm:EnvironmentSummary\",\n    \"ExternalLocation\": \"amm:ExternalLocation\",\n    \"FileBatchJobDefinition\": \"amm:FileBatchJobDefinition\",\n    \"FileBatchJobIdentifier\": \"amm:FileBatchJobIdentifier\",\n    \"FsxStorageConfiguration\": \"amm:FsxStorageConfiguration\",\n    \"GdgAttributes\": \"amm:GdgAttributes\",\n    \"GdgDetailAttributes\": \"amm:GdgDetailAttributes\",\n   \
  \ \"GetApplicationRequest\": \"amm:GetApplicationRequest\",\n    \"GetApplicationResponse\": \"amm:GetApplicationResponse\",\n    \"GetApplicationVersionRequest\": \"amm:GetApplicationVersionRequest\",\n    \"GetApplicationVersionResponse\": \"amm:GetApplicationVersionResponse\",\n    \"GetBatchJobExecutionRequest\": \"amm:GetBatchJobExecutionRequest\",\n    \"GetBatchJobExecutionResponse\": \"amm:GetBatchJobExecutionResponse\",\n    \"GetDataSetDetailsRequest\": \"amm:GetDataSetDetailsRequest\",\n    \"GetDataSetDetailsResponse\": \"amm:GetDataSetDetailsResponse\",\n    \"GetDataSetImportTaskRequest\": \"amm:GetDataSetImportTaskRequest\",\n    \"GetDataSetImportTaskResponse\": \"amm:GetDataSetImportTaskResponse\",\n    \"GetDeploymentRequest\": \"amm:GetDeploymentRequest\",\n    \"GetDeploymentResponse\": \"amm:GetDeploymentResponse\",\n    \"GetEnvironmentRequest\": \"amm:GetEnvironmentRequest\",\n    \"GetEnvironmentResponse\": \"amm:GetEnvironmentResponse\",\n    \"GetSignedBluinsightsUrlResponse\"\
  : \"amm:GetSignedBluinsightsUrlResponse\",\n    \"HighAvailabilityConfig\": \"amm:HighAvailabilityConfig\",\n    \"ListApplicationVersionsRequest\": \"amm:ListApplicationVersionsRequest\",\n    \"ListApplicationVersionsResponse\": \"amm:ListApplicationVersionsResponse\",\n    \"ListApplicationsRequest\": \"amm:ListApplicationsRequest\",\n    \"ListApplicationsResponse\": \"amm:ListApplicationsResponse\",\n    \"ListBatchJobDefinitionsRequest\": \"amm:ListBatchJobDefinitionsRequest\",\n    \"ListBatchJobDefinitionsResponse\": \"amm:ListBatchJobDefinitionsResponse\",\n    \"ListBatchJobExecutionsRequest\": \"amm:ListBatchJobExecutionsRequest\",\n    \"ListBatchJobExecutionsResponse\": \"amm:ListBatchJobExecutionsResponse\",\n    \"ListDataSetImportHistoryRequest\": \"amm:ListDataSetImportHistoryRequest\",\n    \"ListDataSetImportHistoryResponse\": \"amm:ListDataSetImportHistoryResponse\",\n    \"ListDataSetsRequest\": \"amm:ListDataSetsRequest\",\n    \"ListDataSetsResponse\": \"amm:ListDataSetsResponse\"\
  ,\n    \"ListDeploymentsRequest\": \"amm:ListDeploymentsRequest\",\n    \"ListDeploymentsResponse\": \"amm:ListDeploymentsResponse\",\n    \"ListEngineVersionsRequest\": \"amm:ListEngineVersionsRequest\",\n    \"ListEngineVersionsResponse\": \"amm:ListEngineVersionsResponse\",\n    \"ListEnvironmentsRequest\": \"amm:ListEnvironmentsRequest\",\n    \"ListEnvironmentsResponse\": \"amm:ListEnvironmentsResponse\",\n    \"ListTagsForResourceRequest\": \"amm:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amm:ListTagsForResourceResponse\",\n    \"LogGroupSummary\": \"amm:LogGroupSummary\",\n    \"MaintenanceSchedule\": \"amm:MaintenanceSchedule\",\n    \"PendingMaintenance\": \"amm:PendingMaintenance\",\n    \"PoAttributes\": \"amm:PoAttributes\",\n    \"PoDetailAttributes\": \"amm:PoDetailAttributes\",\n    \"PrimaryKey\": \"amm:PrimaryKey\",\n    \"PsAttributes\": \"amm:PsAttributes\",\n    \"PsDetailAttributes\": \"amm:PsDetailAttributes\",\n    \"RecordLength\": \"\
  amm:RecordLength\",\n    \"ScriptBatchJobDefinition\": \"amm:ScriptBatchJobDefinition\",\n    \"ScriptBatchJobIdentifier\": \"amm:ScriptBatchJobIdentifier\",\n    \"StartApplicationRequest\": \"amm:StartApplicationRequest\",\n    \"StartApplicationResponse\": \"amm:StartApplicationResponse\",\n    \"StartBatchJobRequest\": \"amm:StartBatchJobRequest\",\n    \"StartBatchJobResponse\": \"amm:StartBatchJobResponse\",\n    \"StopApplicationRequest\": \"amm:StopApplicationRequest\",\n    \"StopApplicationResponse\": \"amm:StopApplicationResponse\",\n    \"StorageConfiguration\": \"amm:StorageConfiguration\",\n    \"TagMap\": \"amm:TagMap\",\n    \"TagResourceRequest\": \"amm:TagResourceRequest\",\n    \"TagResourceResponse\": \"amm:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amm:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amm:UntagResourceResponse\",\n    \"UpdateApplicationRequest\": \"amm:UpdateApplicationRequest\",\n    \"UpdateApplicationResponse\": \"amm:UpdateApplicationResponse\"\
  ,\n    \"UpdateEnvironmentRequest\": \"amm:UpdateEnvironmentRequest\",\n    \"UpdateEnvironmentResponse\": \"amm:UpdateEnvironmentResponse\",\n    \"VsamAttributes\": \"amm:VsamAttributes\",\n    \"VsamDetailAttributes\": \"amm:VsamDetailAttributes\",\n    \"actualCapacity\": {\n      \"@id\": \"amm:actualCapacity\"\n    },\n    \"allowDuplicates\": {\n      \"@id\": \"amm:allowDuplicates\"\n    },\n    \"alternateKeys\": {\n      \"@id\": \"amm:alternateKeys\"\n    },\n    \"applicationArn\": {\n      \"@id\": \"amm:applicationArn\"\n    },\n    \"applicationId\": {\n      \"@id\": \"amm:applicationId\"\n    },\n    \"applicationVersion\": {\n      \"@id\": \"amm:applicationVersion\"\n    },\n    \"applicationVersions\": {\n      \"@id\": \"amm:applicationVersions\"\n    },\n    \"applications\": {\n      \"@id\": \"amm:applications\"\n    },\n    \"applyDuringMaintenanceWindow\": {\n      \"@id\": \"amm:applyDuringMaintenanceWindow\"\n    },\n    \"batchJobDefinitions\": {\n      \"\
  @id\": \"amm:batchJobDefinitions\"\n    },\n    \"batchJobExecutions\": {\n      \"@id\": \"amm:batchJobExecutions\"\n    },\n    \"batchJobIdentifier\": {\n      \"@id\": \"amm:batchJobIdentifier\"\n    },\n    \"blocksize\": {\n      \"@id\": \"amm:blocksize\"\n    },\n    \"cacheAtStartup\": {\n      \"@id\": \"amm:cacheAtStartup\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amm:clientToken\"\n    },\n    \"compressed\": {\n      \"@id\": \"amm:compressed\"\n    },\n    \"content\": {\n      \"@id\": \"amm:content\"\n    },\n    \"creationTime\": {\n      \"@id\": \"amm:creationTime\"\n    },\n    \"currentApplicationVersion\": {\n      \"@id\": \"amm:currentApplicationVersion\"\n    },\n    \"dataSet\": {\n      \"@id\": \"amm:dataSet\"\n    },\n    \"dataSetImportTasks\": {\n      \"@id\": \"amm:dataSetImportTasks\"\n    },\n    \"dataSetName\": {\n      \"@id\": \"amm:dataSetName\"\n    },\n    \"dataSetOrg\": {\n      \"@id\": \"amm:dataSetOrg\"\n    },\n    \"dataSets\":\
  \ {\n      \"@id\": \"amm:dataSets\"\n    },\n    \"datasetName\": {\n      \"@id\": \"amm:datasetName\"\n    },\n    \"datasetOrg\": {\n      \"@id\": \"amm:datasetOrg\"\n    },\n    \"definition\": {\n      \"@id\": \"amm:definition\"\n    },\n    \"definitionContent\": {\n      \"@id\": \"amm:definitionContent\"\n    },\n    \"deployedVersion\": {\n      \"@id\": \"amm:deployedVersion\"\n    },\n    \"deploymentId\": {\n      \"@id\": \"amm:deploymentId\"\n    },\n    \"deploymentStatus\": {\n      \"@id\": \"amm:deploymentStatus\"\n    },\n    \"deployments\": {\n      \"@id\": \"amm:deployments\"\n    },\n    \"description\": {\n      \"@id\": \"amm:description\"\n    },\n    \"desiredCapacity\": {\n      \"@id\": \"amm:desiredCapacity\"\n    },\n    \"efs\": {\n      \"@id\": \"amm:efs\"\n    },\n    \"encoding\": {\n      \"@id\": \"amm:encoding\"\n    },\n    \"endTime\": {\n      \"@id\": \"amm:endTime\"\n    },\n    \"engineType\": {\n      \"@id\": \"amm:engineType\"\n    },\n\
  \    \"engineVersion\": {\n      \"@id\": \"amm:engineVersion\"\n    },\n    \"engineVersions\": {\n      \"@id\": \"amm:engineVersions\"\n    },\n    \"environmentArn\": {\n      \"@id\": \"amm:environmentArn\"\n    },\n    \"environmentId\": {\n      \"@id\": \"amm:environmentId\"\n    },\n    \"environments\": {\n      \"@id\": \"amm:environments\"\n    },\n    \"executionId\": {\n      \"@id\": \"amm:executionId\"\n    },\n    \"externalLocation\": {\n      \"@id\": \"amm:externalLocation\"\n    },\n    \"failed\": {\n      \"@id\": \"amm:failed\"\n    },\n    \"fileBatchJobDefinition\": {\n      \"@id\": \"amm:fileBatchJobDefinition\"\n    },\n    \"fileBatchJobIdentifier\": {\n      \"@id\": \"amm:fileBatchJobIdentifier\"\n    },\n    \"fileName\": {\n      \"@id\": \"amm:fileName\"\n    },\n    \"fileSystemId\": {\n      \"@id\": \"amm:fileSystemId\"\n    },\n    \"folderPath\": {\n      \"@id\": \"amm:folderPath\"\n    },\n    \"forceStop\": {\n      \"@id\": \"amm:forceStop\"\n\
  \    },\n    \"format\": {\n      \"@id\": \"amm:format\"\n    },\n    \"fsx\": {\n      \"@id\": \"amm:fsx\"\n    },\n    \"gdg\": {\n      \"@id\": \"amm:gdg\"\n    },\n    \"highAvailabilityConfig\": {\n      \"@id\": \"amm:highAvailabilityConfig\"\n    },\n    \"importConfig\": {\n      \"@id\": \"amm:importConfig\"\n    },\n    \"inProgress\": {\n      \"@id\": \"amm:inProgress\"\n    },\n    \"instanceType\": {\n      \"@id\": \"amm:instanceType\"\n    },\n    \"jobId\": {\n      \"@id\": \"amm:jobId\"\n    },\n    \"jobName\": {\n      \"@id\": \"amm:jobName\"\n    },\n    \"jobParams\": {\n      \"@id\": \"amm:jobParams\"\n    },\n    \"jobType\": {\n      \"@id\": \"amm:jobType\"\n    },\n    \"jobUser\": {\n      \"@id\": \"amm:jobUser\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"amm:kmsKeyId\"\n    },\n    \"lastReferencedTime\": {\n      \"@id\": \"amm:lastReferencedTime\"\n    },\n    \"lastStartTime\": {\n      \"@id\": \"amm:lastStartTime\"\n    },\n    \"lastUpdatedTime\"\
  : {\n      \"@id\": \"amm:lastUpdatedTime\"\n    },\n    \"latestVersion\": {\n      \"@id\": \"amm:latestVersion\"\n    },\n    \"length\": {\n      \"@id\": \"amm:length\"\n    },\n    \"limit\": {\n      \"@id\": \"amm:limit\"\n    },\n    \"listenerArns\": {\n      \"@id\": \"amm:listenerArns\"\n    },\n    \"listenerPorts\": {\n      \"@id\": \"amm:listenerPorts\"\n    },\n    \"loadBalancerArn\": {\n      \"@id\": \"amm:loadBalancerArn\"\n    },\n    \"loadBalancerDnsName\": {\n      \"@id\": \"amm:loadBalancerDnsName\"\n    },\n    \"location\": {\n      \"@id\": \"amm:location\"\n    },\n    \"logGroupName\": {\n      \"@id\": \"amm:logGroupName\"\n    },\n    \"logGroups\": {\n      \"@id\": \"amm:logGroups\"\n    },\n    \"logType\": {\n      \"@id\": \"amm:logType\"\n    },\n    \"max\": {\n      \"@id\": \"amm:max\"\n    },\n    \"memberFileExtensions\": {\n      \"@id\": \"amm:memberFileExtensions\"\n    },\n    \"min\": {\n      \"@id\": \"amm:min\"\n    },\n    \"mountPoint\"\
  : {\n      \"@id\": \"amm:mountPoint\"\n    },\n    \"name\": {\n      \"@id\": \"amm:name\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amm:nextToken\"\n    },\n    \"offset\": {\n      \"@id\": \"amm:offset\"\n    },\n    \"pending\": {\n      \"@id\": \"amm:pending\"\n    },\n    \"pendingMaintenance\": {\n      \"@id\": \"amm:pendingMaintenance\"\n    },\n    \"po\": {\n      \"@id\": \"amm:po\"\n    },\n    \"preferredMaintenanceWindow\": {\n      \"@id\": \"amm:preferredMaintenanceWindow\"\n    },\n    \"primaryKey\": {\n      \"@id\": \"amm:primaryKey\"\n    },\n    \"ps\": {\n      \"@id\": \"amm:ps\"\n    },\n    \"publiclyAccessible\": {\n      \"@id\": \"amm:publiclyAccessible\"\n    },\n    \"recordFormat\": {\n      \"@id\": \"amm:recordFormat\"\n    },\n    \"recordLength\": {\n      \"@id\": \"amm:recordLength\"\n    },\n    \"relativePath\": {\n      \"@id\": \"amm:relativePath\"\n    },\n    \"returnCode\": {\n      \"@id\": \"amm:returnCode\"\n    },\n    \"roleArn\"\
  : {\n      \"@id\": \"amm:roleArn\"\n    },\n    \"rollDisposition\": {\n      \"@id\": \"amm:rollDisposition\"\n    },\n    \"s3Location\": {\n      \"@id\": \"amm:s3Location\"\n    },\n    \"schedule\": {\n      \"@id\": \"amm:schedule\"\n    },\n    \"scriptBatchJobDefinition\": {\n      \"@id\": \"amm:scriptBatchJobDefinition\"\n    },\n    \"scriptBatchJobIdentifier\": {\n      \"@id\": \"amm:scriptBatchJobIdentifier\"\n    },\n    \"scriptName\": {\n      \"@id\": \"amm:scriptName\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"amm:securityGroupIds\"\n    },\n    \"signedBiUrl\": {\n      \"@id\": \"amm:signedBiUrl\"\n    },\n    \"startTime\": {\n      \"@id\": \"amm:startTime\"\n    },\n    \"status\": {\n      \"@id\": \"amm:status\"\n    },\n    \"statusReason\": {\n      \"@id\": \"amm:statusReason\"\n    },\n    \"storageConfigurations\": {\n      \"@id\": \"amm:storageConfigurations\"\n    },\n    \"storageType\": {\n      \"@id\": \"amm:storageType\"\n    },\n  \
  \  \"subnetIds\": {\n      \"@id\": \"amm:subnetIds\"\n    },\n    \"succeeded\": {\n      \"@id\": \"amm:succeeded\"\n    },\n    \"summary\": {\n      \"@id\": \"amm:summary\"\n    },\n    \"tags\": {\n      \"@id\": \"amm:tags\"\n    },\n    \"targetGroupArns\": {\n      \"@id\": \"amm:targetGroupArns\"\n    },\n    \"taskId\": {\n      \"@id\": \"amm:taskId\"\n    },\n    \"total\": {\n      \"@id\": \"amm:total\"\n    },\n    \"versionStatus\": {\n      \"@id\": \"amm:versionStatus\"\n    },\n    \"vpcId\": {\n      \"@id\": \"amm:vpcId\"\n    },\n    \"vsam\": {\n      \"@id\": \"amm:vsam\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mainframe-modernization/refs/heads/main/json-ld/amazon-mainframe-modernization-context.jsonld
tags:
- AWS
- COBOL
- Mainframe
- Migration
- Modernization
- Batch Processing
- JSON-LD
- Linked Data
- Semantic Web
---
