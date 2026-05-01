---
api_specs:
- filename: amazon-robomaker-openapi.yml
  format: yaml
  label: AWS RoboMaker API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-robomaker/refs/heads/main/openapi/amazon-robomaker-openapi.yml
class_count: 167
classes:
- BatchDeleteWorldsRequest
- BatchDeleteWorldsResponse
- BatchDescribeSimulationJobRequest
- BatchDescribeSimulationJobResponse
- BatchPolicy
- CancelDeploymentJobRequest
- CancelDeploymentJobResponse
- CancelSimulationJobBatchRequest
- CancelSimulationJobBatchResponse
- CancelSimulationJobRequest
- CancelSimulationJobResponse
- CancelWorldExportJobRequest
- CancelWorldExportJobResponse
- CancelWorldGenerationJobRequest
- CancelWorldGenerationJobResponse
- ComputeResponse
- Compute
- CreateDeploymentJobRequest
- CreateDeploymentJobResponse
- CreateFleetRequest
- CreateFleetResponse
- CreateRobotApplicationRequest
- CreateRobotApplicationResponse
- CreateRobotApplicationVersionRequest
- CreateRobotApplicationVersionResponse
- CreateRobotRequest
- CreateRobotResponse
- CreateSimulationApplicationRequest
- CreateSimulationApplicationResponse
- CreateSimulationApplicationVersionRequest
- CreateSimulationApplicationVersionResponse
- CreateSimulationJobRequest
- CreateSimulationJobResponse
- CreateWorldExportJobRequest
- CreateWorldExportJobResponse
- CreateWorldGenerationJobRequest
- CreateWorldGenerationJobResponse
- CreateWorldTemplateRequest
- CreateWorldTemplateResponse
- DataSourceConfig
- DataSource
- DeleteFleetRequest
- DeleteFleetResponse
- DeleteRobotApplicationRequest
- DeleteRobotApplicationResponse
- DeleteRobotRequest
- DeleteRobotResponse
- DeleteSimulationApplicationRequest
- DeleteSimulationApplicationResponse
- DeleteWorldTemplateRequest
- DeleteWorldTemplateResponse
- DeploymentApplicationConfig
- DeploymentConfig
- DeploymentJob
- DeploymentLaunchConfig
- DeregisterRobotRequest
- DeregisterRobotResponse
- DescribeDeploymentJobRequest
- DescribeDeploymentJobResponse
- DescribeFleetRequest
- DescribeFleetResponse
- DescribeRobotApplicationRequest
- DescribeRobotApplicationResponse
- DescribeRobotRequest
- DescribeRobotResponse
- DescribeSimulationApplicationRequest
- DescribeSimulationApplicationResponse
- DescribeSimulationJobBatchRequest
- DescribeSimulationJobBatchResponse
- DescribeSimulationJobRequest
- DescribeSimulationJobResponse
- DescribeWorldExportJobRequest
- DescribeWorldExportJobResponse
- DescribeWorldGenerationJobRequest
- DescribeWorldGenerationJobResponse
- DescribeWorldRequest
- DescribeWorldResponse
- DescribeWorldTemplateRequest
- DescribeWorldTemplateResponse
- Environment
- EnvironmentVariableMap
- FailedCreateSimulationJobRequest
- FailureSummary
- Filter
- FinishedWorldsSummary
- Fleet
- GetWorldTemplateBodyRequest
- GetWorldTemplateBodyResponse
- LaunchConfig
- ListDeploymentJobsRequest
- ListDeploymentJobsResponse
- ListFleetsRequest
- ListFleetsResponse
- ListRobotApplicationsRequest
- ListRobotApplicationsResponse
- ListRobotsRequest
- ListRobotsResponse
- ListSimulationApplicationsRequest
- ListSimulationApplicationsResponse
- ListSimulationJobBatchesRequest
- ListSimulationJobBatchesResponse
- ListSimulationJobsRequest
- ListSimulationJobsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ListWorldExportJobsRequest
- ListWorldExportJobsResponse
- ListWorldGenerationJobsRequest
- ListWorldGenerationJobsResponse
- ListWorldTemplatesRequest
- ListWorldTemplatesResponse
- ListWorldsRequest
- ListWorldsResponse
- LoggingConfig
- NetworkInterface
- OutputLocation
- PortForwardingConfig
- PortMapping
- ProgressDetail
- RegisterRobotRequest
- RegisterRobotResponse
- RenderingEngine
- RestartSimulationJobRequest
- RestartSimulationJobResponse
- RobotApplicationConfig
- RobotApplicationSummary
- RobotDeployment
- Robot
- RobotSoftwareSuite
- S3KeyOutput
- S3Object
- SimulationApplicationConfig
- SimulationApplicationSummary
- SimulationJobBatchSummary
- SimulationJobRequest
- SimulationJob
- SimulationJobSummary
- SimulationSoftwareSuite
- SourceConfig
- Source
- StartSimulationJobBatchRequest
- StartSimulationJobBatchResponse
- SyncDeploymentJobRequest
- SyncDeploymentJobResponse
- TagMap
- TagResourceRequest
- TagResourceResponse
- TemplateLocation
- TemplateSummary
- Tool
- UntagResourceRequest
- UntagResourceResponse
- UpdateRobotApplicationRequest
- UpdateRobotApplicationResponse
- UpdateSimulationApplicationRequest
- UpdateSimulationApplicationResponse
- UpdateWorldTemplateRequest
- UpdateWorldTemplateResponse
- UploadConfiguration
- VPCConfigResponse
- VPCConfig
- WorldConfig
- WorldCount
- WorldExportJobSummary
- WorldFailure
- WorldGenerationJobSummary
- WorldSummary
context_file: json-ld/amazon-robomaker-context-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-robomaker/refs/heads/main/json-ld/amazon-robomaker-context-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Robomaker from Amazon RoboMaker.
layout: jsonld
name: Amazon Robomaker Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: worlds
  type: string
- container: ''
  name: unprocessedWorlds
  type: string
- container: ''
  name: jobs
  type: string
- container: ''
  name: unprocessedJobs
  type: string
- container: ''
  name: timeoutInSeconds
  type: string
- container: ''
  name: maxConcurrency
  type: string
- container: ''
  name: job
  type: string
- container: ''
  name: batch
  type: string
- container: ''
  name: simulationUnitLimit
  type: string
- container: ''
  name: computeType
  type: string
- container: ''
  name: gpuUnitLimit
  type: string
- container: ''
  name: deploymentConfig
  type: string
- container: ''
  name: clientRequestToken
  type: string
- container: ''
  name: fleet
  type: string
- container: ''
  name: deploymentApplicationConfigs
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: failureReason
  type: string
- container: ''
  name: failureCode
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: name
  type: ''
- container: ''
  name: sources
  type: string
- container: ''
  name: robotSoftwareSuite
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: version
  type: ''
- container: ''
  name: lastUpdatedAt
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: currentRevisionId
  type: string
- container: ''
  name: s3Etags
  type: string
- container: ''
  name: imageDigest
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: greengrassGroupId
  type: string
- container: ''
  name: simulationSoftwareSuite
  type: string
- container: ''
  name: renderingEngine
  type: string
- container: ''
  name: outputLocation
  type: string
- container: ''
  name: loggingConfig
  type: string
- container: ''
  name: maxJobDurationInSeconds
  type: string
- container: ''
  name: iamRole
  type: string
- container: ''
  name: failureBehavior
  type: string
- container: ''
  name: robotApplications
  type: string
- container: ''
  name: simulationApplications
  type: string
- container: ''
  name: dataSources
  type: string
- container: ''
  name: vpcConfig
  type: string
- container: ''
  name: compute
  type: string
- container: ''
  name: lastStartedAt
  type: string
- container: ''
  name: simulationTimeMillis
  type: string
- container: ''
  name: template
  type: string
- container: ''
  name: worldCount
  type: string
- container: ''
  name: worldTags
  type: string
- container: ''
  name: templateBody
  type: string
- container: ''
  name: templateLocation
  type: string
- container: ''
  name: s3Bucket
  type: string
- container: ''
  name: s3Keys
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: applicationVersion
  type: string
- container: ''
  name: robot
  type: string
- container: ''
  name: launchConfig
  type: string
- container: ''
  name: concurrentDeploymentPercentage
  type: string
- container: ''
  name: failureThresholdPercentage
  type: string
- container: ''
  name: robotDeploymentTimeoutInSeconds
  type: string
- container: ''
  name: downloadConditionFile
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: preLaunchFile
  type: string
- container: ''
  name: launchFile
  type: string
- container: ''
  name: postLaunchFile
  type: string
- container: ''
  name: environmentVariables
  type: string
- container: ''
  name: robotDeploymentSummary
  type: string
- container: ''
  name: robots
  type: string
- container: ''
  name: lastDeploymentStatus
  type: string
- container: ''
  name: lastDeploymentJob
  type: string
- container: ''
  name: lastDeploymentTime
  type: string
- container: ''
  name: fleetArn
  type: string
- container: ''
  name: batchPolicy
  type: string
- container: ''
  name: failedRequests
  type: string
- container: ''
  name: pendingRequests
  type: string
- container: ''
  name: createdRequests
  type: string
- container: ''
  name: networkInterface
  type: string
- container: ''
  name: finishedWorldsSummary
  type: string
- container: ''
  name: world
  type: string
- container: ''
  name: generationJob
  type: string
- container: ''
  name: worldDescriptionBody
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: request
  type: string
- container: ''
  name: failedAt
  type: string
- container: ''
  name: totalFailureCount
  type: string
- container: ''
  name: failures
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: finishedCount
  type: string
- container: ''
  name: succeededWorlds
  type: string
- container: ''
  name: failureSummary
  type: string
- container: ''
  name: portForwardingConfig
  type: string
- container: ''
  name: streamUI
  type: string
- container: ''
  name: command
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: deploymentJobs
  type: string
- container: ''
  name: fleetDetails
  type: string
- container: ''
  name: versionQualifier
  type: string
- container: ''
  name: robotApplicationSummaries
  type: string
- container: ''
  name: simulationApplicationSummaries
  type: string
- container: ''
  name: simulationJobBatchSummaries
  type: string
- container: ''
  name: simulationJobSummaries
  type: string
- container: ''
  name: worldExportJobSummaries
  type: string
- container: ''
  name: worldGenerationJobSummaries
  type: string
- container: ''
  name: templateSummaries
  type: string
- container: ''
  name: worldSummaries
  type: string
- container: ''
  name: recordAllRosTopics
  type: string
- container: ''
  name: networkInterfaceId
  type: string
- container: ''
  name: privateIpAddress
  type: string
- container: ''
  name: publicIpAddress
  type: string
- container: ''
  name: s3Prefix
  type: string
- container: ''
  name: portMappings
  type: string
- container: ''
  name: jobPort
  type: string
- container: ''
  name: applicationPort
  type: string
- container: ''
  name: enableOnPublicIp
  type: string
- container: ''
  name: currentProgress
  type: string
- container: ''
  name: percentDone
  type: string
- container: ''
  name: estimatedTimeRemainingSeconds
  type: string
- container: ''
  name: targetResource
  type: string
- container: ''
  name: uploadConfigurations
  type: string
- container: ''
  name: useDefaultUploadConfigurations
  type: string
- container: ''
  name: tools
  type: string
- container: ''
  name: useDefaultTools
  type: string
- container: ''
  name: deploymentStartTime
  type: string
- container: ''
  name: deploymentFinishTime
  type: string
- container: ''
  name: progressDetail
  type: string
- container: ''
  name: greenGrassGroupId
  type: string
- container: ''
  name: s3Key
  type: string
- container: ''
  name: etag
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: worldConfigs
  type: string
- container: ''
  name: failedRequestCount
  type: string
- container: ''
  name: pendingRequestCount
  type: string
- container: ''
  name: createdRequestCount
  type: string
- container: ''
  name: useDefaultApplications
  type: string
- container: ''
  name: simulationApplicationNames
  type: string
- container: ''
  name: robotApplicationNames
  type: string
- container: ''
  name: dataSourceNames
  type: string
- container: ''
  name: createSimulationJobRequests
  type: string
- container: ''
  name: streamOutputToCloudWatch
  type: string
- container: ''
  name: exitBehavior
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: uploadBehavior
  type: string
- container: ''
  name: subnets
  type: string
- container: ''
  name: securityGroups
  type: string
- container: ''
  name: vpcId
  type: string
- container: ''
  name: assignPublicIp
  type: string
- container: ''
  name: floorplanCount
  type: string
- container: ''
  name: interiorCountPerFloorplan
  type: string
- container: ''
  name: sampleFailureReason
  type: string
- container: ''
  name: failureCount
  type: string
- container: ''
  name: succeededWorldCount
  type: string
- container: ''
  name: failedWorldCount
  type: string
property_count: 158
provider_name: Amazon RoboMaker
provider_slug: amazon-robomaker
slug: amazon-robomaker-context-context
source_filename: amazon-robomaker-context-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"BatchDeleteWorldsRequest\": \"aws:BatchDeleteWorldsRequest\",\n    \"BatchDeleteWorldsResponse\": \"aws:BatchDeleteWorldsResponse\",\n    \"BatchDescribeSimulationJobRequest\": \"aws:BatchDescribeSimulationJobRequest\",\n    \"BatchDescribeSimulationJobResponse\": \"aws:BatchDescribeSimulationJobResponse\",\n    \"BatchPolicy\": \"aws:BatchPolicy\",\n    \"CancelDeploymentJobRequest\": \"aws:CancelDeploymentJobRequest\",\n    \"CancelDeploymentJobResponse\": \"aws:CancelDeploymentJobResponse\",\n    \"CancelSimulationJobBatchRequest\": \"aws:CancelSimulationJobBatchRequest\",\n    \"CancelSimulationJobBatchResponse\": \"aws:CancelSimulationJobBatchResponse\",\n    \"CancelSimulationJobRequest\": \"aws:CancelSimulationJobRequest\",\n\
  \    \"CancelSimulationJobResponse\": \"aws:CancelSimulationJobResponse\",\n    \"CancelWorldExportJobRequest\": \"aws:CancelWorldExportJobRequest\",\n    \"CancelWorldExportJobResponse\": \"aws:CancelWorldExportJobResponse\",\n    \"CancelWorldGenerationJobRequest\": \"aws:CancelWorldGenerationJobRequest\",\n    \"CancelWorldGenerationJobResponse\": \"aws:CancelWorldGenerationJobResponse\",\n    \"ComputeResponse\": \"aws:ComputeResponse\",\n    \"Compute\": \"aws:Compute\",\n    \"CreateDeploymentJobRequest\": \"aws:CreateDeploymentJobRequest\",\n    \"CreateDeploymentJobResponse\": \"aws:CreateDeploymentJobResponse\",\n    \"CreateFleetRequest\": \"aws:CreateFleetRequest\",\n    \"CreateFleetResponse\": \"aws:CreateFleetResponse\",\n    \"CreateRobotApplicationRequest\": \"aws:CreateRobotApplicationRequest\",\n    \"CreateRobotApplicationResponse\": \"aws:CreateRobotApplicationResponse\",\n    \"CreateRobotApplicationVersionRequest\": \"aws:CreateRobotApplicationVersionRequest\",\n\
  \    \"CreateRobotApplicationVersionResponse\": \"aws:CreateRobotApplicationVersionResponse\",\n    \"CreateRobotRequest\": \"aws:CreateRobotRequest\",\n    \"CreateRobotResponse\": \"aws:CreateRobotResponse\",\n    \"CreateSimulationApplicationRequest\": \"aws:CreateSimulationApplicationRequest\",\n    \"CreateSimulationApplicationResponse\": \"aws:CreateSimulationApplicationResponse\",\n    \"CreateSimulationApplicationVersionRequest\": \"aws:CreateSimulationApplicationVersionRequest\",\n    \"CreateSimulationApplicationVersionResponse\": \"aws:CreateSimulationApplicationVersionResponse\",\n    \"CreateSimulationJobRequest\": \"aws:CreateSimulationJobRequest\",\n    \"CreateSimulationJobResponse\": \"aws:CreateSimulationJobResponse\",\n    \"CreateWorldExportJobRequest\": \"aws:CreateWorldExportJobRequest\",\n    \"CreateWorldExportJobResponse\": \"aws:CreateWorldExportJobResponse\",\n    \"CreateWorldGenerationJobRequest\": \"aws:CreateWorldGenerationJobRequest\",\n    \"CreateWorldGenerationJobResponse\"\
  : \"aws:CreateWorldGenerationJobResponse\",\n    \"CreateWorldTemplateRequest\": \"aws:CreateWorldTemplateRequest\",\n    \"CreateWorldTemplateResponse\": \"aws:CreateWorldTemplateResponse\",\n    \"DataSourceConfig\": \"aws:DataSourceConfig\",\n    \"DataSource\": \"aws:DataSource\",\n    \"DeleteFleetRequest\": \"aws:DeleteFleetRequest\",\n    \"DeleteFleetResponse\": \"aws:DeleteFleetResponse\",\n    \"DeleteRobotApplicationRequest\": \"aws:DeleteRobotApplicationRequest\",\n    \"DeleteRobotApplicationResponse\": \"aws:DeleteRobotApplicationResponse\",\n    \"DeleteRobotRequest\": \"aws:DeleteRobotRequest\",\n    \"DeleteRobotResponse\": \"aws:DeleteRobotResponse\",\n    \"DeleteSimulationApplicationRequest\": \"aws:DeleteSimulationApplicationRequest\",\n    \"DeleteSimulationApplicationResponse\": \"aws:DeleteSimulationApplicationResponse\",\n    \"DeleteWorldTemplateRequest\": \"aws:DeleteWorldTemplateRequest\",\n    \"DeleteWorldTemplateResponse\": \"aws:DeleteWorldTemplateResponse\"\
  ,\n    \"DeploymentApplicationConfig\": \"aws:DeploymentApplicationConfig\",\n    \"DeploymentConfig\": \"aws:DeploymentConfig\",\n    \"DeploymentJob\": \"aws:DeploymentJob\",\n    \"DeploymentLaunchConfig\": \"aws:DeploymentLaunchConfig\",\n    \"DeregisterRobotRequest\": \"aws:DeregisterRobotRequest\",\n    \"DeregisterRobotResponse\": \"aws:DeregisterRobotResponse\",\n    \"DescribeDeploymentJobRequest\": \"aws:DescribeDeploymentJobRequest\",\n    \"DescribeDeploymentJobResponse\": \"aws:DescribeDeploymentJobResponse\",\n    \"DescribeFleetRequest\": \"aws:DescribeFleetRequest\",\n    \"DescribeFleetResponse\": \"aws:DescribeFleetResponse\",\n    \"DescribeRobotApplicationRequest\": \"aws:DescribeRobotApplicationRequest\",\n    \"DescribeRobotApplicationResponse\": \"aws:DescribeRobotApplicationResponse\",\n    \"DescribeRobotRequest\": \"aws:DescribeRobotRequest\",\n    \"DescribeRobotResponse\": \"aws:DescribeRobotResponse\",\n    \"DescribeSimulationApplicationRequest\": \"aws:DescribeSimulationApplicationRequest\"\
  ,\n    \"DescribeSimulationApplicationResponse\": \"aws:DescribeSimulationApplicationResponse\",\n    \"DescribeSimulationJobBatchRequest\": \"aws:DescribeSimulationJobBatchRequest\",\n    \"DescribeSimulationJobBatchResponse\": \"aws:DescribeSimulationJobBatchResponse\",\n    \"DescribeSimulationJobRequest\": \"aws:DescribeSimulationJobRequest\",\n    \"DescribeSimulationJobResponse\": \"aws:DescribeSimulationJobResponse\",\n    \"DescribeWorldExportJobRequest\": \"aws:DescribeWorldExportJobRequest\",\n    \"DescribeWorldExportJobResponse\": \"aws:DescribeWorldExportJobResponse\",\n    \"DescribeWorldGenerationJobRequest\": \"aws:DescribeWorldGenerationJobRequest\",\n    \"DescribeWorldGenerationJobResponse\": \"aws:DescribeWorldGenerationJobResponse\",\n    \"DescribeWorldRequest\": \"aws:DescribeWorldRequest\",\n    \"DescribeWorldResponse\": \"aws:DescribeWorldResponse\",\n    \"DescribeWorldTemplateRequest\": \"aws:DescribeWorldTemplateRequest\",\n    \"DescribeWorldTemplateResponse\"\
  : \"aws:DescribeWorldTemplateResponse\",\n    \"Environment\": \"aws:Environment\",\n    \"EnvironmentVariableMap\": \"aws:EnvironmentVariableMap\",\n    \"FailedCreateSimulationJobRequest\": \"aws:FailedCreateSimulationJobRequest\",\n    \"FailureSummary\": \"aws:FailureSummary\",\n    \"Filter\": \"aws:Filter\",\n    \"FinishedWorldsSummary\": \"aws:FinishedWorldsSummary\",\n    \"Fleet\": \"aws:Fleet\",\n    \"GetWorldTemplateBodyRequest\": \"aws:GetWorldTemplateBodyRequest\",\n    \"GetWorldTemplateBodyResponse\": \"aws:GetWorldTemplateBodyResponse\",\n    \"LaunchConfig\": \"aws:LaunchConfig\",\n    \"ListDeploymentJobsRequest\": \"aws:ListDeploymentJobsRequest\",\n    \"ListDeploymentJobsResponse\": \"aws:ListDeploymentJobsResponse\",\n    \"ListFleetsRequest\": \"aws:ListFleetsRequest\",\n    \"ListFleetsResponse\": \"aws:ListFleetsResponse\",\n    \"ListRobotApplicationsRequest\": \"aws:ListRobotApplicationsRequest\",\n    \"ListRobotApplicationsResponse\": \"aws:ListRobotApplicationsResponse\"\
  ,\n    \"ListRobotsRequest\": \"aws:ListRobotsRequest\",\n    \"ListRobotsResponse\": \"aws:ListRobotsResponse\",\n    \"ListSimulationApplicationsRequest\": \"aws:ListSimulationApplicationsRequest\",\n    \"ListSimulationApplicationsResponse\": \"aws:ListSimulationApplicationsResponse\",\n    \"ListSimulationJobBatchesRequest\": \"aws:ListSimulationJobBatchesRequest\",\n    \"ListSimulationJobBatchesResponse\": \"aws:ListSimulationJobBatchesResponse\",\n    \"ListSimulationJobsRequest\": \"aws:ListSimulationJobsRequest\",\n    \"ListSimulationJobsResponse\": \"aws:ListSimulationJobsResponse\",\n    \"ListTagsForResourceRequest\": \"aws:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"aws:ListTagsForResourceResponse\",\n    \"ListWorldExportJobsRequest\": \"aws:ListWorldExportJobsRequest\",\n    \"ListWorldExportJobsResponse\": \"aws:ListWorldExportJobsResponse\",\n    \"ListWorldGenerationJobsRequest\": \"aws:ListWorldGenerationJobsRequest\",\n    \"ListWorldGenerationJobsResponse\"\
  : \"aws:ListWorldGenerationJobsResponse\",\n    \"ListWorldTemplatesRequest\": \"aws:ListWorldTemplatesRequest\",\n    \"ListWorldTemplatesResponse\": \"aws:ListWorldTemplatesResponse\",\n    \"ListWorldsRequest\": \"aws:ListWorldsRequest\",\n    \"ListWorldsResponse\": \"aws:ListWorldsResponse\",\n    \"LoggingConfig\": \"aws:LoggingConfig\",\n    \"NetworkInterface\": \"aws:NetworkInterface\",\n    \"OutputLocation\": \"aws:OutputLocation\",\n    \"PortForwardingConfig\": \"aws:PortForwardingConfig\",\n    \"PortMapping\": \"aws:PortMapping\",\n    \"ProgressDetail\": \"aws:ProgressDetail\",\n    \"RegisterRobotRequest\": \"aws:RegisterRobotRequest\",\n    \"RegisterRobotResponse\": \"aws:RegisterRobotResponse\",\n    \"RenderingEngine\": \"aws:RenderingEngine\",\n    \"RestartSimulationJobRequest\": \"aws:RestartSimulationJobRequest\",\n    \"RestartSimulationJobResponse\": \"aws:RestartSimulationJobResponse\",\n    \"RobotApplicationConfig\": \"aws:RobotApplicationConfig\",\n    \"\
  RobotApplicationSummary\": \"aws:RobotApplicationSummary\",\n    \"RobotDeployment\": \"aws:RobotDeployment\",\n    \"Robot\": \"aws:Robot\",\n    \"RobotSoftwareSuite\": \"aws:RobotSoftwareSuite\",\n    \"S3KeyOutput\": \"aws:S3KeyOutput\",\n    \"S3Object\": \"aws:S3Object\",\n    \"SimulationApplicationConfig\": \"aws:SimulationApplicationConfig\",\n    \"SimulationApplicationSummary\": \"aws:SimulationApplicationSummary\",\n    \"SimulationJobBatchSummary\": \"aws:SimulationJobBatchSummary\",\n    \"SimulationJobRequest\": \"aws:SimulationJobRequest\",\n    \"SimulationJob\": \"aws:SimulationJob\",\n    \"SimulationJobSummary\": \"aws:SimulationJobSummary\",\n    \"SimulationSoftwareSuite\": \"aws:SimulationSoftwareSuite\",\n    \"SourceConfig\": \"aws:SourceConfig\",\n    \"Source\": \"aws:Source\",\n    \"StartSimulationJobBatchRequest\": \"aws:StartSimulationJobBatchRequest\",\n    \"StartSimulationJobBatchResponse\": \"aws:StartSimulationJobBatchResponse\",\n    \"SyncDeploymentJobRequest\"\
  : \"aws:SyncDeploymentJobRequest\",\n    \"SyncDeploymentJobResponse\": \"aws:SyncDeploymentJobResponse\",\n    \"TagMap\": \"aws:TagMap\",\n    \"TagResourceRequest\": \"aws:TagResourceRequest\",\n    \"TagResourceResponse\": \"aws:TagResourceResponse\",\n    \"TemplateLocation\": \"aws:TemplateLocation\",\n    \"TemplateSummary\": \"aws:TemplateSummary\",\n    \"Tool\": \"aws:Tool\",\n    \"UntagResourceRequest\": \"aws:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"aws:UntagResourceResponse\",\n    \"UpdateRobotApplicationRequest\": \"aws:UpdateRobotApplicationRequest\",\n    \"UpdateRobotApplicationResponse\": \"aws:UpdateRobotApplicationResponse\",\n    \"UpdateSimulationApplicationRequest\": \"aws:UpdateSimulationApplicationRequest\",\n    \"UpdateSimulationApplicationResponse\": \"aws:UpdateSimulationApplicationResponse\",\n    \"UpdateWorldTemplateRequest\": \"aws:UpdateWorldTemplateRequest\",\n    \"UpdateWorldTemplateResponse\": \"aws:UpdateWorldTemplateResponse\"\
  ,\n    \"UploadConfiguration\": \"aws:UploadConfiguration\",\n    \"VPCConfigResponse\": \"aws:VPCConfigResponse\",\n    \"VPCConfig\": \"aws:VPCConfig\",\n    \"WorldConfig\": \"aws:WorldConfig\",\n    \"WorldCount\": \"aws:WorldCount\",\n    \"WorldExportJobSummary\": \"aws:WorldExportJobSummary\",\n    \"WorldFailure\": \"aws:WorldFailure\",\n    \"WorldGenerationJobSummary\": \"aws:WorldGenerationJobSummary\",\n    \"WorldSummary\": \"aws:WorldSummary\",\n    \"worlds\": {\n      \"@id\": \"aws:worlds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unprocessedWorlds\": {\n      \"@id\": \"aws:unprocessedWorlds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobs\": {\n      \"@id\": \"aws:jobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"unprocessedJobs\": {\n      \"@id\": \"aws:unprocessedJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutInSeconds\": {\n      \"@id\": \"aws:timeoutInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxConcurrency\"\
  : {\n      \"@id\": \"aws:maxConcurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"job\": {\n      \"@id\": \"aws:job\",\n      \"@type\": \"xsd:string\"\n    },\n    \"batch\": {\n      \"@id\": \"aws:batch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationUnitLimit\": {\n      \"@id\": \"aws:simulationUnitLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"computeType\": {\n      \"@id\": \"aws:computeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gpuUnitLimit\": {\n      \"@id\": \"aws:gpuUnitLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentConfig\": {\n      \"@id\": \"aws:deploymentConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientRequestToken\": {\n      \"@id\": \"aws:clientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleet\": {\n      \"@id\": \"aws:fleet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentApplicationConfigs\": {\n      \"@id\": \"aws:deploymentApplicationConfigs\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureReason\": {\n      \"@id\": \"aws:failureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureCode\": {\n      \"@id\": \"aws:failureCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"aws:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\"\n    },\n    \"sources\": {\n      \"@id\": \"aws:sources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotSoftwareSuite\": {\n      \"@id\": \"aws:robotSoftwareSuite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"aws:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\":\
  \ {\n      \"@id\": \"schema:version\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"aws:lastUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"aws:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"aws:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentRevisionId\": {\n      \"@id\": \"aws:currentRevisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Etags\": {\n      \"@id\": \"aws:s3Etags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageDigest\": {\n      \"@id\": \"aws:imageDigest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\": \"aws:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"greengrassGroupId\": {\n      \"@id\": \"aws:greengrassGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationSoftwareSuite\": {\n      \"@id\": \"aws:simulationSoftwareSuite\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"renderingEngine\": {\n      \"@id\": \"aws:renderingEngine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputLocation\": {\n      \"@id\": \"aws:outputLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"loggingConfig\": {\n      \"@id\": \"aws:loggingConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxJobDurationInSeconds\": {\n      \"@id\": \"aws:maxJobDurationInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamRole\": {\n      \"@id\": \"aws:iamRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureBehavior\": {\n      \"@id\": \"aws:failureBehavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotApplications\": {\n      \"@id\": \"aws:robotApplications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationApplications\": {\n      \"@id\": \"aws:simulationApplications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataSources\": {\n      \"@id\": \"aws:dataSources\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"vpcConfig\": {\n      \"@id\": \"aws:vpcConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"compute\": {\n      \"@id\": \"aws:compute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastStartedAt\": {\n      \"@id\": \"aws:lastStartedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationTimeMillis\": {\n      \"@id\": \"aws:simulationTimeMillis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"template\": {\n      \"@id\": \"aws:template\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldCount\": {\n      \"@id\": \"aws:worldCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldTags\": {\n      \"@id\": \"aws:worldTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateBody\": {\n      \"@id\": \"aws:templateBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateLocation\": {\n      \"@id\": \"aws:templateLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Bucket\": {\n      \"@id\": \"aws:s3Bucket\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"s3Keys\": {\n      \"@id\": \"aws:s3Keys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"aws:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationVersion\": {\n      \"@id\": \"aws:applicationVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robot\": {\n      \"@id\": \"aws:robot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchConfig\": {\n      \"@id\": \"aws:launchConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"concurrentDeploymentPercentage\": {\n      \"@id\": \"aws:concurrentDeploymentPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureThresholdPercentage\": {\n      \"@id\": \"aws:failureThresholdPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotDeploymentTimeoutInSeconds\": {\n      \"@id\": \"aws:robotDeploymentTimeoutInSeconds\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"downloadConditionFile\": {\n      \"@id\": \"aws:downloadConditionFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"aws:packageName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preLaunchFile\": {\n      \"@id\": \"aws:preLaunchFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchFile\": {\n      \"@id\": \"aws:launchFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postLaunchFile\": {\n      \"@id\": \"aws:postLaunchFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentVariables\": {\n      \"@id\": \"aws:environmentVariables\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotDeploymentSummary\": {\n      \"@id\": \"aws:robotDeploymentSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robots\": {\n      \"@id\": \"aws:robots\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastDeploymentStatus\": {\n      \"@id\": \"aws:lastDeploymentStatus\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"lastDeploymentJob\": {\n      \"@id\": \"aws:lastDeploymentJob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastDeploymentTime\": {\n      \"@id\": \"aws:lastDeploymentTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetArn\": {\n      \"@id\": \"aws:fleetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"batchPolicy\": {\n      \"@id\": \"aws:batchPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedRequests\": {\n      \"@id\": \"aws:failedRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingRequests\": {\n      \"@id\": \"aws:pendingRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdRequests\": {\n      \"@id\": \"aws:createdRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterface\": {\n      \"@id\": \"aws:networkInterface\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finishedWorldsSummary\": {\n      \"@id\": \"aws:finishedWorldsSummary\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"world\": {\n      \"@id\": \"aws:world\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generationJob\": {\n      \"@id\": \"aws:generationJob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldDescriptionBody\": {\n      \"@id\": \"aws:worldDescriptionBody\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"aws:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request\": {\n      \"@id\": \"aws:request\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedAt\": {\n      \"@id\": \"aws:failedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalFailureCount\": {\n      \"@id\": \"aws:totalFailureCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failures\": {\n      \"@id\": \"aws:failures\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"aws:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"finishedCount\": {\n      \"@id\": \"aws:finishedCount\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"succeededWorlds\": {\n      \"@id\": \"aws:succeededWorlds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureSummary\": {\n      \"@id\": \"aws:failureSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portForwardingConfig\": {\n      \"@id\": \"aws:portForwardingConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamUI\": {\n      \"@id\": \"aws:streamUI\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"aws:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"aws:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"aws:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentJobs\": {\n      \"@id\": \"aws:deploymentJobs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fleetDetails\": {\n      \"@id\": \"aws:fleetDetails\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"versionQualifier\": {\n      \"@id\": \"aws:versionQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotApplicationSummaries\": {\n      \"@id\": \"aws:robotApplicationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationApplicationSummaries\": {\n      \"@id\": \"aws:simulationApplicationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationJobBatchSummaries\": {\n      \"@id\": \"aws:simulationJobBatchSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationJobSummaries\": {\n      \"@id\": \"aws:simulationJobSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldExportJobSummaries\": {\n      \"@id\": \"aws:worldExportJobSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldGenerationJobSummaries\": {\n      \"@id\": \"aws:worldGenerationJobSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateSummaries\": {\n      \"@id\": \"aws:templateSummaries\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"worldSummaries\": {\n      \"@id\": \"aws:worldSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordAllRosTopics\": {\n      \"@id\": \"aws:recordAllRosTopics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkInterfaceId\": {\n      \"@id\": \"aws:networkInterfaceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateIpAddress\": {\n      \"@id\": \"aws:privateIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicIpAddress\": {\n      \"@id\": \"aws:publicIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Prefix\": {\n      \"@id\": \"aws:s3Prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portMappings\": {\n      \"@id\": \"aws:portMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobPort\": {\n      \"@id\": \"aws:jobPort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationPort\": {\n      \"@id\": \"aws:applicationPort\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"enableOnPublicIp\": {\n      \"@id\": \"aws:enableOnPublicIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentProgress\": {\n      \"@id\": \"aws:currentProgress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"percentDone\": {\n      \"@id\": \"aws:percentDone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"estimatedTimeRemainingSeconds\": {\n      \"@id\": \"aws:estimatedTimeRemainingSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetResource\": {\n      \"@id\": \"aws:targetResource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadConfigurations\": {\n      \"@id\": \"aws:uploadConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useDefaultUploadConfigurations\": {\n      \"@id\": \"aws:useDefaultUploadConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tools\": {\n      \"@id\": \"aws:tools\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useDefaultTools\": {\n      \"@id\": \"aws:useDefaultTools\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"deploymentStartTime\": {\n      \"@id\": \"aws:deploymentStartTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentFinishTime\": {\n      \"@id\": \"aws:deploymentFinishTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"progressDetail\": {\n      \"@id\": \"aws:progressDetail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"greenGrassGroupId\": {\n      \"@id\": \"aws:greenGrassGroupId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Key\": {\n      \"@id\": \"aws:s3Key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"etag\": {\n      \"@id\": \"aws:etag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"aws:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"aws:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"worldConfigs\": {\n      \"@id\": \"aws:worldConfigs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedRequestCount\": {\n      \"\
  @id\": \"aws:failedRequestCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pendingRequestCount\": {\n      \"@id\": \"aws:pendingRequestCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdRequestCount\": {\n      \"@id\": \"aws:createdRequestCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"useDefaultApplications\": {\n      \"@id\": \"aws:useDefaultApplications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"simulationApplicationNames\": {\n      \"@id\": \"aws:simulationApplicationNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"robotApplicationNames\": {\n      \"@id\": \"aws:robotApplicationNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dataSourceNames\": {\n      \"@id\": \"aws:dataSourceNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createSimulationJobRequests\": {\n      \"@id\": \"aws:createSimulationJobRequests\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamOutputToCloudWatch\": {\n      \"@id\": \"aws:streamOutputToCloudWatch\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"exitBehavior\": {\n      \"@id\": \"aws:exitBehavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"aws:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uploadBehavior\": {\n      \"@id\": \"aws:uploadBehavior\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnets\": {\n      \"@id\": \"aws:subnets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroups\": {\n      \"@id\": \"aws:securityGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"aws:vpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"assignPublicIp\": {\n      \"@id\": \"aws:assignPublicIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"floorplanCount\": {\n      \"@id\": \"aws:floorplanCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"interiorCountPerFloorplan\": {\n      \"@id\": \"aws:interiorCountPerFloorplan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sampleFailureReason\"\
  : {\n      \"@id\": \"aws:sampleFailureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureCount\": {\n      \"@id\": \"aws:failureCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"succeededWorldCount\": {\n      \"@id\": \"aws:succeededWorldCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedWorldCount\": {\n      \"@id\": \"aws:failedWorldCount\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-robomaker/refs/heads/main/json-ld/amazon-robomaker-context-context.jsonld
tags:
- Robotics
- Simulation
- JSON-LD
- Linked Data
- Semantic Web
---
