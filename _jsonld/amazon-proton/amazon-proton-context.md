---
class_count: 211
classes:
- CreateEnvironmentTemplateOutput
- CreateServiceSyncConfigOutput
- RepositorySyncDefinition
- DeleteEnvironmentAccountConnectionInput
- ServiceInstance
- name
- ServiceTemplateVersionSummary
- description
- GetEnvironmentTemplateInput
- ResourceCountsSummary
- ListEnvironmentTemplateVersionsInput
- RejectEnvironmentAccountConnectionOutput
- DeleteEnvironmentTemplateVersionInput
- ServicePipeline
- CreateRepositoryInput
- CancelServiceInstanceDeploymentInput
- ListServiceInstanceOutputsOutput
- DeleteEnvironmentOutput
- DeleteComponentOutput
- GetEnvironmentTemplateOutput
- Output
- ListServiceInstanceProvisionedResourcesInput
- UpdateComponentOutput
- GetComponentInput
- DeleteServiceInput
- ResourceSyncAttempt
- UpdateComponentInput
- ListServicePipelineOutputsOutput
- GetServiceSyncBlockerSummaryOutput
- ListEnvironmentOutputsInput
- CreateEnvironmentAccountConnectionInput
- GetServiceOutput
- EnvironmentTemplateSummary
- ListServicePipelineOutputsInput
- ListServiceInstanceProvisionedResourcesOutput
- RepositorySyncAttempt
- UpdateServiceSyncConfigInput
- ListServiceTemplateVersionsInput
- UntagResourceInput
- UpdateServiceInput
- Tag
- GetEnvironmentTemplateVersionOutput
- DeleteRepositoryOutput
- UpdateServiceOutput
- CreateServiceInstanceOutput
- ListEnvironmentProvisionedResourcesInput
- ListEnvironmentAccountConnectionsOutput
- UpdateServiceTemplateInput
- UpdateEnvironmentAccountConnectionInput
- CompatibleEnvironmentTemplate
- ListRepositorySyncDefinitionsInput
- CreateTemplateSyncConfigInput
- GetAccountSettingsOutput
- GetServiceTemplateOutput
- SyncBlocker
- UpdateEnvironmentTemplateVersionInput
- DeleteEnvironmentTemplateInput
- RejectEnvironmentAccountConnectionInput
- ServiceSyncConfig
- ListServiceInstancesInput
- ListEnvironmentProvisionedResourcesOutput
- UpdateServiceSyncBlockerOutput
- ServiceSummary
- DeleteEnvironmentInput
- ComponentSummary
- EnvironmentAccountConnection
- ListServicePipelineProvisionedResourcesOutput
- ResourceSyncEvent
- CreateComponentInput
- ListRepositoriesOutput
- ListServicesOutput
- ListRepositorySyncDefinitionsOutput
- UpdateServiceTemplateVersionInput
- ListComponentsOutput
- CreateServiceSyncConfigInput
- CreateEnvironmentOutput
- UpdateServiceTemplateOutput
- UpdateAccountSettingsOutput
- CreateEnvironmentAccountConnectionOutput
- GetRepositoryInput
- AcceptEnvironmentAccountConnectionOutput
- UpdateEnvironmentTemplateInput
- GetRepositorySyncStatusInput
- GetRepositorySyncStatusOutput
- CancelEnvironmentDeploymentOutput
- DeleteTemplateSyncConfigOutput
- UpdateEnvironmentInput
- Service
- CreateServiceInput
- ListTagsForResourceInput
- UpdateEnvironmentTemplateOutput
- UpdateEnvironmentTemplateVersionOutput
- ListEnvironmentTemplatesOutput
- ServiceTemplateSummary
- ServiceInstanceSummary
- CancelEnvironmentDeploymentInput
- UpdateServiceInstanceInput
- GetServiceSyncBlockerSummaryInput
- CancelServicePipelineDeploymentOutput
- ListServiceInstancesFilter
- UpdateEnvironmentOutput
- ListEnvironmentOutputsOutput
- GetServiceInstanceSyncStatusOutput
- CompatibleEnvironmentTemplateInput
- ProvisionedResource
- ListServiceTemplateVersionsOutput
- DeleteServiceTemplateVersionOutput
- CancelComponentDeploymentInput
- UpdateServiceSyncConfigOutput
- UpdateAccountSettingsInput
- GetServiceSyncConfigInput
- ListRepositoriesInput
- EnvironmentAccountConnectionSummary
- CreateRepositoryOutput
- GetRepositoryOutput
- GetServiceInstanceInput
- GetServiceInstanceOutput
- GetTemplateSyncStatusInput
- EnvironmentTemplateVersion
- ListEnvironmentsInput
- ListComponentOutputsInput
- UpdateServiceSyncBlockerInput
- ServiceTemplate
- CancelComponentDeploymentOutput
- CreateServiceTemplateOutput
- UpdateServicePipelineOutput
- DeleteTemplateSyncConfigInput
- GetEnvironmentAccountConnectionOutput
- EnvironmentTemplate
- CreateServiceTemplateInput
- DeleteEnvironmentTemplateOutput
- ListComponentsInput
- DeleteServiceSyncConfigOutput
- UpdateTemplateSyncConfigOutput
- GetComponentOutput
- AccountSettings
- EnvironmentTemplateFilter
- S3ObjectSource
- TemplateSyncConfig
- SyncBlockerContext
- GetEnvironmentOutput
- Component
- RepositorySyncEvent
- GetEnvironmentTemplateVersionInput
- ListServicePipelineProvisionedResourcesInput
- ListComponentProvisionedResourcesOutput
- UpdateServiceTemplateVersionOutput
- RepositorySummary
- CreateServiceTemplateVersionInput
- ListEnvironmentTemplateVersionsOutput
- ListEnvironmentAccountConnectionsInput
- DeleteServiceTemplateInput
- DeleteServiceTemplateVersionInput
- ListComponentOutputsOutput
- ListTagsForResourceOutput
- AcceptEnvironmentAccountConnectionInput
- UpdateTemplateSyncConfigInput
- TemplateVersionSourceInput
- ListServiceInstanceOutputsInput
- ListEnvironmentTemplatesInput
- CountsSummary
- CreateTemplateSyncConfigOutput
- CreateComponentOutput
- ServiceSyncBlockerSummary
- DeleteComponentInput
- GetServiceTemplateInput
- UpdateServicePipelineInput
- GetServiceTemplateVersionOutput
- EnvironmentTemplateVersionSummary
- ListEnvironmentsOutput
- GetEnvironmentAccountConnectionInput
- DeleteServiceTemplateOutput
- RepositoryBranchInput
- GetServiceInput
- DeleteRepositoryInput
- CreateEnvironmentTemplateVersionInput
- Environment
- UpdateEnvironmentAccountConnectionOutput
- Repository
- TagResourceInput
- ListServiceTemplatesOutput
- ListServiceInstancesOutput
- GetTemplateSyncConfigOutput
- GetTemplateSyncConfigInput
- GetServiceTemplateVersionInput
- NotifyResourceDeploymentStatusChangeInput
- CreateServiceOutput
- ServiceTemplateVersion
- GetServiceSyncConfigOutput
- CreateServiceInstanceInput
- Revision
- CreateEnvironmentTemplateInput
- DeleteServiceSyncConfigInput
- ListServicesInput
- CreateEnvironmentTemplateVersionOutput
- CancelServiceInstanceDeploymentOutput
- GetEnvironmentInput
- GetResourcesSummaryOutput
- UpdateServiceInstanceOutput
- GetServiceInstanceSyncStatusInput
- CreateServiceTemplateVersionOutput
- CreateEnvironmentInput
- ListComponentProvisionedResourcesInput
- CancelServicePipelineDeploymentInput
- DeleteEnvironmentTemplateVersionOutput
- ListServiceTemplatesInput
- DeleteEnvironmentAccountConnectionOutput
- DeleteServiceOutput
- EnvironmentSummary
- GetTemplateSyncStatusOutput
- RepositoryBranch
context_file: json-ld/amazon-proton-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-proton/refs/heads/main/json-ld/amazon-proton-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Proton from Amazon Proton.
layout: jsonld
name: Amazon Proton Context
namespaces:
- prefix: proton
  uri: https://proton.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: environmentTemplate
  type: string
- container: ''
  name: serviceSyncConfig
  type: string
- container: ''
  name: branch
  type: string
- container: ''
  name: directory
  type: string
- container: ''
  name: parent
  type: string
- container: ''
  name: target
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: deploymentStatus
  type: string
- container: ''
  name: deploymentStatusMessage
  type: string
- container: ''
  name: environmentName
  type: string
- container: ''
  name: lastClientRequestToken
  type: string
- container: ''
  name: lastDeploymentAttemptedAt
  type: string
- container: ''
  name: lastDeploymentSucceededAt
  type: string
- container: ''
  name: serviceName
  type: string
- container: ''
  name: spec
  type: string
- container: ''
  name: templateMajorVersion
  type: string
- container: ''
  name: templateMinorVersion
  type: string
- container: ''
  name: templateName
  type: string
- container: ''
  name: lastModifiedAt
  type: string
- container: ''
  name: majorVersion
  type: string
- container: ''
  name: minorVersion
  type: string
- container: ''
  name: recommendedMinorVersion
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusMessage
  type: string
- container: ''
  name: behindMajor
  type: string
- container: ''
  name: behindMinor
  type: string
- container: ''
  name: failed
  type: string
- container: ''
  name: total
  type: string
- container: ''
  name: upToDate
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: environmentAccountConnection
  type: string
- container: ''
  name: connectionArn
  type: string
- container: ''
  name: encryptionKey
  type: string
- container: ''
  name: provider
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: serviceInstanceName
  type: string
- container: ''
  name: outputs
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: component
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: valueString
  type: string
- container: ''
  name: events
  type: string
- container: ''
  name: initialRevision
  type: string
- container: ''
  name: startedAt
  type: string
- container: ''
  name: targetRevision
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: deploymentType
  type: string
- container: ''
  name: serviceSpec
  type: string
- container: ''
  name: templateFile
  type: string
- container: ''
  name: serviceSyncBlockerSummary
  type: string
- container: ''
  name: codebuildRoleArn
  type: string
- container: ''
  name: componentRoleArn
  type: string
- container: ''
  name: managementAccountId
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: provisioning
  type: string
- container: ''
  name: recommendedVersion
  type: string
- container: ''
  name: provisionedResources
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: repositoryName
  type: string
- container: ''
  name: repositoryProvider
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: tagKeys
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: environmentTemplateVersion
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: serviceInstance
  type: string
- container: ''
  name: environmentAccountConnections
  type: string
- container: ''
  name: syncType
  type: string
- container: ''
  name: subdirectory
  type: string
- container: ''
  name: templateType
  type: string
- container: ''
  name: accountSettings
  type: string
- container: ''
  name: serviceTemplate
  type: string
- container: ''
  name: contexts
  type: string
- container: ''
  name: createdReason
  type: string
- container: ''
  name: resolvedAt
  type: string
- container: ''
  name: resolvedReason
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: sortBy
  type: string
- container: ''
  name: sortOrder
  type: string
- container: ''
  name: serviceSyncBlocker
  type: string
- container: ''
  name: environmentAccountId
  type: string
- container: ''
  name: requestedAt
  type: string
- container: ''
  name: event
  type: string
- container: ''
  name: externalId
  type: string
- container: ''
  name: time
  type: string
- container: ''
  name: manifest
  type: string
- container: ''
  name: repositories
  type: string
- container: ''
  name: services
  type: string
- container: ''
  name: syncDefinitions
  type: string
- container: ''
  name: compatibleEnvironmentTemplates
  type: string
- container: ''
  name: supportedComponentSources
  type: string
- container: ''
  name: components
  type: string
- container: ''
  name: latestSync
  type: string
- container: ''
  name: templateSyncConfig
  type: string
- container: ''
  name: environmentAccountConnectionId
  type: string
- container: ''
  name: protonServiceRoleArn
  type: string
- container: ''
  name: provisioningRepository
  type: string
- container: ''
  name: branchName
  type: string
- container: ''
  name: pipeline
  type: string
- container: ''
  name: repositoryConnectionArn
  type: string
- container: ''
  name: repositoryId
  type: string
- container: ''
  name: templates
  type: string
- container: ''
  name: pipelineProvisioning
  type: string
- container: ''
  name: desiredState
  type: string
- container: ''
  name: latestSuccessfulSync
  type: string
- container: ''
  name: identifier
  type: string
- container: ''
  name: provisioningEngine
  type: string
- container: ''
  name: templateVersions
  type: string
- container: ''
  name: serviceTemplateVersion
  type: string
- container: ''
  name: componentName
  type: string
- container: ''
  name: deletePipelineProvisioningRepository
  type: string
- container: ''
  name: pipelineCodebuildRoleArn
  type: string
- container: ''
  name: pipelineProvisioningRepository
  type: string
- container: ''
  name: pipelineServiceRoleArn
  type: string
- container: ''
  name: templateVersion
  type: string
- container: ''
  name: environmentTemplates
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: requestedBy
  type: string
- container: ''
  name: statuses
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: environments
  type: string
- container: ''
  name: pipelines
  type: string
- container: ''
  name: serviceInstances
  type: string
- container: ''
  name: serviceTemplates
  type: string
- container: ''
  name: latestBlockers
  type: string
- container: ''
  name: deploymentId
  type: string
- container: ''
  name: sha
  type: string
- container: ''
  name: counts
  type: string
property_count: 135
provider_name: Amazon Proton
provider_slug: amazon-proton
slug: amazon-proton-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"proton\": \"https://proton.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateEnvironmentTemplateOutput\": \"proton:CreateEnvironmentTemplateOutput\",\n    \"environmentTemplate\": {\n      \"@id\": \"proton:environmentTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceSyncConfigOutput\": \"proton:CreateServiceSyncConfigOutput\",\n    \"serviceSyncConfig\": {\n      \"@id\": \"proton:serviceSyncConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositorySyncDefinition\": \"proton:RepositorySyncDefinition\",\n    \"branch\": {\n      \"@id\": \"proton:branch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directory\": {\n      \"@id\": \"proton:directory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parent\": {\n      \"@id\": \"proton:parent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"target\": {\n\
  \      \"@id\": \"proton:target\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEnvironmentAccountConnectionInput\": \"proton:DeleteEnvironmentAccountConnectionInput\",\n    \"id\": {\n      \"@id\": \"proton:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceInstance\": \"proton:ServiceInstance\",\n    \"arn\": {\n      \"@id\": \"proton:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"proton:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentStatus\": {\n      \"@id\": \"proton:deploymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentStatusMessage\": {\n      \"@id\": \"proton:deploymentStatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentName\": {\n      \"@id\": \"proton:environmentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastClientRequestToken\": {\n      \"@id\": \"proton:lastClientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  lastDeploymentAttemptedAt\": {\n      \"@id\": \"proton:lastDeploymentAttemptedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastDeploymentSucceededAt\": {\n      \"@id\": \"proton:lastDeploymentSucceededAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"serviceName\": {\n      \"@id\": \"proton:serviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spec\": {\n      \"@id\": \"proton:spec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateMajorVersion\": {\n      \"@id\": \"proton:templateMajorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateMinorVersion\": {\n      \"@id\": \"proton:templateMinorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateName\": {\n      \"@id\": \"proton:templateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceTemplateVersionSummary\": \"proton:ServiceTemplateVersionSummary\",\n    \"description\": \"schema:description\",\n    \"lastModifiedAt\": {\n   \
  \   \"@id\": \"proton:lastModifiedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"majorVersion\": {\n      \"@id\": \"proton:majorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minorVersion\": {\n      \"@id\": \"proton:minorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedMinorVersion\": {\n      \"@id\": \"proton:recommendedMinorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"proton:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusMessage\": {\n      \"@id\": \"proton:statusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEnvironmentTemplateInput\": \"proton:GetEnvironmentTemplateInput\",\n    \"ResourceCountsSummary\": \"proton:ResourceCountsSummary\",\n    \"behindMajor\": {\n      \"@id\": \"proton:behindMajor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"behindMinor\": {\n      \"@id\": \"proton:behindMinor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failed\": {\n\
  \      \"@id\": \"proton:failed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"proton:total\",\n      \"@type\": \"xsd:string\"\n    },\n    \"upToDate\": {\n      \"@id\": \"proton:upToDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListEnvironmentTemplateVersionsInput\": \"proton:ListEnvironmentTemplateVersionsInput\",\n    \"maxResults\": {\n      \"@id\": \"proton:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"proton:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RejectEnvironmentAccountConnectionOutput\": \"proton:RejectEnvironmentAccountConnectionOutput\",\n    \"environmentAccountConnection\": {\n      \"@id\": \"proton:environmentAccountConnection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEnvironmentTemplateVersionInput\": \"proton:DeleteEnvironmentTemplateVersionInput\",\n    \"ServicePipeline\": \"proton:ServicePipeline\",\n    \"CreateRepositoryInput\": \"proton:CreateRepositoryInput\"\
  ,\n    \"connectionArn\": {\n      \"@id\": \"proton:connectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionKey\": {\n      \"@id\": \"proton:encryptionKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provider\": {\n      \"@id\": \"proton:provider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"proton:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelServiceInstanceDeploymentInput\": \"proton:CancelServiceInstanceDeploymentInput\",\n    \"serviceInstanceName\": {\n      \"@id\": \"proton:serviceInstanceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServiceInstanceOutputsOutput\": \"proton:ListServiceInstanceOutputsOutput\",\n    \"outputs\": {\n      \"@id\": \"proton:outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteEnvironmentOutput\": \"proton:DeleteEnvironmentOutput\",\n    \"environment\": {\n      \"@id\": \"proton:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteComponentOutput\"\
  : \"proton:DeleteComponentOutput\",\n    \"component\": {\n      \"@id\": \"proton:component\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEnvironmentTemplateOutput\": \"proton:GetEnvironmentTemplateOutput\",\n    \"Output\": \"proton:Output\",\n    \"key\": {\n      \"@id\": \"proton:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"valueString\": {\n      \"@id\": \"proton:valueString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServiceInstanceProvisionedResourcesInput\": \"proton:ListServiceInstanceProvisionedResourcesInput\",\n    \"UpdateComponentOutput\": \"proton:UpdateComponentOutput\",\n    \"GetComponentInput\": \"proton:GetComponentInput\",\n    \"DeleteServiceInput\": \"proton:DeleteServiceInput\",\n    \"ResourceSyncAttempt\": \"proton:ResourceSyncAttempt\",\n    \"events\": {\n      \"@id\": \"proton:events\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialRevision\": {\n      \"@id\": \"proton:initialRevision\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"startedAt\": {\n      \"@id\": \"proton:startedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetRevision\": {\n      \"@id\": \"proton:targetRevision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateComponentInput\": \"proton:UpdateComponentInput\",\n    \"clientToken\": {\n      \"@id\": \"proton:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentType\": {\n      \"@id\": \"proton:deploymentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceSpec\": {\n      \"@id\": \"proton:serviceSpec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateFile\": {\n      \"@id\": \"proton:templateFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServicePipelineOutputsOutput\": \"proton:ListServicePipelineOutputsOutput\",\n    \"GetServiceSyncBlockerSummaryOutput\": \"proton:GetServiceSyncBlockerSummaryOutput\",\n    \"serviceSyncBlockerSummary\": {\n      \"@id\": \"proton:serviceSyncBlockerSummary\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"ListEnvironmentOutputsInput\": \"proton:ListEnvironmentOutputsInput\",\n    \"CreateEnvironmentAccountConnectionInput\": \"proton:CreateEnvironmentAccountConnectionInput\",\n    \"codebuildRoleArn\": {\n      \"@id\": \"proton:codebuildRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentRoleArn\": {\n      \"@id\": \"proton:componentRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managementAccountId\": {\n      \"@id\": \"proton:managementAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"proton:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetServiceOutput\": \"proton:GetServiceOutput\",\n    \"service\": {\n      \"@id\": \"proton:service\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnvironmentTemplateSummary\": \"proton:EnvironmentTemplateSummary\",\n    \"displayName\": {\n      \"@id\": \"proton:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioning\"\
  : {\n      \"@id\": \"proton:provisioning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recommendedVersion\": {\n      \"@id\": \"proton:recommendedVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServicePipelineOutputsInput\": \"proton:ListServicePipelineOutputsInput\",\n    \"ListServiceInstanceProvisionedResourcesOutput\": \"proton:ListServiceInstanceProvisionedResourcesOutput\",\n    \"provisionedResources\": {\n      \"@id\": \"proton:provisionedResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositorySyncAttempt\": \"proton:RepositorySyncAttempt\",\n    \"UpdateServiceSyncConfigInput\": \"proton:UpdateServiceSyncConfigInput\",\n    \"filePath\": {\n      \"@id\": \"proton:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryName\": {\n      \"@id\": \"proton:repositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryProvider\": {\n      \"@id\": \"proton:repositoryProvider\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"ListServiceTemplateVersionsInput\": \"proton:ListServiceTemplateVersionsInput\",\n    \"UntagResourceInput\": \"proton:UntagResourceInput\",\n    \"resourceArn\": {\n      \"@id\": \"proton:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagKeys\": {\n      \"@id\": \"proton:tagKeys\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateServiceInput\": \"proton:UpdateServiceInput\",\n    \"Tag\": \"proton:Tag\",\n    \"value\": {\n      \"@id\": \"proton:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetEnvironmentTemplateVersionOutput\": \"proton:GetEnvironmentTemplateVersionOutput\",\n    \"environmentTemplateVersion\": {\n      \"@id\": \"proton:environmentTemplateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteRepositoryOutput\": \"proton:DeleteRepositoryOutput\",\n    \"repository\": {\n      \"@id\": \"proton:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateServiceOutput\": \"proton:UpdateServiceOutput\",\n\
  \    \"CreateServiceInstanceOutput\": \"proton:CreateServiceInstanceOutput\",\n    \"serviceInstance\": {\n      \"@id\": \"proton:serviceInstance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListEnvironmentProvisionedResourcesInput\": \"proton:ListEnvironmentProvisionedResourcesInput\",\n    \"ListEnvironmentAccountConnectionsOutput\": \"proton:ListEnvironmentAccountConnectionsOutput\",\n    \"environmentAccountConnections\": {\n      \"@id\": \"proton:environmentAccountConnections\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateServiceTemplateInput\": \"proton:UpdateServiceTemplateInput\",\n    \"UpdateEnvironmentAccountConnectionInput\": \"proton:UpdateEnvironmentAccountConnectionInput\",\n    \"CompatibleEnvironmentTemplate\": \"proton:CompatibleEnvironmentTemplate\",\n    \"ListRepositorySyncDefinitionsInput\": \"proton:ListRepositorySyncDefinitionsInput\",\n    \"syncType\": {\n      \"@id\": \"proton:syncType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTemplateSyncConfigInput\"\
  : \"proton:CreateTemplateSyncConfigInput\",\n    \"subdirectory\": {\n      \"@id\": \"proton:subdirectory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"templateType\": {\n      \"@id\": \"proton:templateType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetAccountSettingsOutput\": \"proton:GetAccountSettingsOutput\",\n    \"accountSettings\": {\n      \"@id\": \"proton:accountSettings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetServiceTemplateOutput\": \"proton:GetServiceTemplateOutput\",\n    \"serviceTemplate\": {\n      \"@id\": \"proton:serviceTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SyncBlocker\": \"proton:SyncBlocker\",\n    \"contexts\": {\n      \"@id\": \"proton:contexts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdReason\": {\n      \"@id\": \"proton:createdReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedAt\": {\n      \"@id\": \"proton:resolvedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedReason\"\
  : {\n      \"@id\": \"proton:resolvedReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"proton:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateEnvironmentTemplateVersionInput\": \"proton:UpdateEnvironmentTemplateVersionInput\",\n    \"DeleteEnvironmentTemplateInput\": \"proton:DeleteEnvironmentTemplateInput\",\n    \"RejectEnvironmentAccountConnectionInput\": \"proton:RejectEnvironmentAccountConnectionInput\",\n    \"ServiceSyncConfig\": \"proton:ServiceSyncConfig\",\n    \"ListServiceInstancesInput\": \"proton:ListServiceInstancesInput\",\n    \"filters\": {\n      \"@id\": \"proton:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortBy\": {\n      \"@id\": \"proton:sortBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortOrder\": {\n      \"@id\": \"proton:sortOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListEnvironmentProvisionedResourcesOutput\": \"proton:ListEnvironmentProvisionedResourcesOutput\",\n    \"\
  UpdateServiceSyncBlockerOutput\": \"proton:UpdateServiceSyncBlockerOutput\",\n    \"serviceSyncBlocker\": {\n      \"@id\": \"proton:serviceSyncBlocker\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceSummary\": \"proton:ServiceSummary\",\n    \"DeleteEnvironmentInput\": \"proton:DeleteEnvironmentInput\",\n    \"ComponentSummary\": \"proton:ComponentSummary\",\n    \"EnvironmentAccountConnection\": \"proton:EnvironmentAccountConnection\",\n    \"environmentAccountId\": {\n      \"@id\": \"proton:environmentAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestedAt\": {\n      \"@id\": \"proton:requestedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServicePipelineProvisionedResourcesOutput\": \"proton:ListServicePipelineProvisionedResourcesOutput\",\n    \"ResourceSyncEvent\": \"proton:ResourceSyncEvent\",\n    \"event\": {\n      \"@id\": \"proton:event\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalId\": {\n      \"@id\": \"proton:externalId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"time\": {\n      \"@id\": \"proton:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateComponentInput\": \"proton:CreateComponentInput\",\n    \"manifest\": {\n      \"@id\": \"proton:manifest\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListRepositoriesOutput\": \"proton:ListRepositoriesOutput\",\n    \"repositories\": {\n      \"@id\": \"proton:repositories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServicesOutput\": \"proton:ListServicesOutput\",\n    \"services\": {\n      \"@id\": \"proton:services\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListRepositorySyncDefinitionsOutput\": \"proton:ListRepositorySyncDefinitionsOutput\",\n    \"syncDefinitions\": {\n      \"@id\": \"proton:syncDefinitions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateServiceTemplateVersionInput\": \"proton:UpdateServiceTemplateVersionInput\",\n    \"compatibleEnvironmentTemplates\": {\n      \"@id\": \"proton:compatibleEnvironmentTemplates\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedComponentSources\": {\n      \"@id\": \"proton:supportedComponentSources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListComponentsOutput\": \"proton:ListComponentsOutput\",\n    \"components\": {\n      \"@id\": \"proton:components\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceSyncConfigInput\": \"proton:CreateServiceSyncConfigInput\",\n    \"CreateEnvironmentOutput\": \"proton:CreateEnvironmentOutput\",\n    \"UpdateServiceTemplateOutput\": \"proton:UpdateServiceTemplateOutput\",\n    \"UpdateAccountSettingsOutput\": \"proton:UpdateAccountSettingsOutput\",\n    \"CreateEnvironmentAccountConnectionOutput\": \"proton:CreateEnvironmentAccountConnectionOutput\",\n    \"GetRepositoryInput\": \"proton:GetRepositoryInput\",\n    \"AcceptEnvironmentAccountConnectionOutput\": \"proton:AcceptEnvironmentAccountConnectionOutput\",\n    \"UpdateEnvironmentTemplateInput\": \"proton:UpdateEnvironmentTemplateInput\"\
  ,\n    \"GetRepositorySyncStatusInput\": \"proton:GetRepositorySyncStatusInput\",\n    \"GetRepositorySyncStatusOutput\": \"proton:GetRepositorySyncStatusOutput\",\n    \"latestSync\": {\n      \"@id\": \"proton:latestSync\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelEnvironmentDeploymentOutput\": \"proton:CancelEnvironmentDeploymentOutput\",\n    \"DeleteTemplateSyncConfigOutput\": \"proton:DeleteTemplateSyncConfigOutput\",\n    \"templateSyncConfig\": {\n      \"@id\": \"proton:templateSyncConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateEnvironmentInput\": \"proton:UpdateEnvironmentInput\",\n    \"environmentAccountConnectionId\": {\n      \"@id\": \"proton:environmentAccountConnectionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protonServiceRoleArn\": {\n      \"@id\": \"proton:protonServiceRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioningRepository\": {\n      \"@id\": \"proton:provisioningRepository\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"Service\": \"proton:Service\",\n    \"branchName\": {\n      \"@id\": \"proton:branchName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipeline\": {\n      \"@id\": \"proton:pipeline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryConnectionArn\": {\n      \"@id\": \"proton:repositoryConnectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryId\": {\n      \"@id\": \"proton:repositoryId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceInput\": \"proton:CreateServiceInput\",\n    \"ListTagsForResourceInput\": \"proton:ListTagsForResourceInput\",\n    \"UpdateEnvironmentTemplateOutput\": \"proton:UpdateEnvironmentTemplateOutput\",\n    \"UpdateEnvironmentTemplateVersionOutput\": \"proton:UpdateEnvironmentTemplateVersionOutput\",\n    \"ListEnvironmentTemplatesOutput\": \"proton:ListEnvironmentTemplatesOutput\",\n    \"templates\": {\n      \"@id\": \"proton:templates\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"ServiceTemplateSummary\": \"proton:ServiceTemplateSummary\",\n    \"pipelineProvisioning\": {\n      \"@id\": \"proton:pipelineProvisioning\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ServiceInstanceSummary\": \"proton:ServiceInstanceSummary\",\n    \"CancelEnvironmentDeploymentInput\": \"proton:CancelEnvironmentDeploymentInput\",\n    \"UpdateServiceInstanceInput\": \"proton:UpdateServiceInstanceInput\",\n    \"GetServiceSyncBlockerSummaryInput\": \"proton:GetServiceSyncBlockerSummaryInput\",\n    \"CancelServicePipelineDeploymentOutput\": \"proton:CancelServicePipelineDeploymentOutput\",\n    \"ListServiceInstancesFilter\": \"proton:ListServiceInstancesFilter\",\n    \"UpdateEnvironmentOutput\": \"proton:UpdateEnvironmentOutput\",\n    \"ListEnvironmentOutputsOutput\": \"proton:ListEnvironmentOutputsOutput\",\n    \"GetServiceInstanceSyncStatusOutput\": \"proton:GetServiceInstanceSyncStatusOutput\",\n    \"desiredState\": {\n      \"@id\": \"proton:desiredState\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"latestSuccessfulSync\": {\n      \"@id\": \"proton:latestSuccessfulSync\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CompatibleEnvironmentTemplateInput\": \"proton:CompatibleEnvironmentTemplateInput\",\n    \"ProvisionedResource\": \"proton:ProvisionedResource\",\n    \"identifier\": {\n      \"@id\": \"proton:identifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"provisioningEngine\": {\n      \"@id\": \"proton:provisioningEngine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServiceTemplateVersionsOutput\": \"proton:ListServiceTemplateVersionsOutput\",\n    \"templateVersions\": {\n      \"@id\": \"proton:templateVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteServiceTemplateVersionOutput\": \"proton:DeleteServiceTemplateVersionOutput\",\n    \"serviceTemplateVersion\": {\n      \"@id\": \"proton:serviceTemplateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CancelComponentDeploymentInput\"\
  : \"proton:CancelComponentDeploymentInput\",\n    \"componentName\": {\n      \"@id\": \"proton:componentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateServiceSyncConfigOutput\": \"proton:UpdateServiceSyncConfigOutput\",\n    \"UpdateAccountSettingsInput\": \"proton:UpdateAccountSettingsInput\",\n    \"deletePipelineProvisioningRepository\": {\n      \"@id\": \"proton:deletePipelineProvisioningRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineCodebuildRoleArn\": {\n      \"@id\": \"proton:pipelineCodebuildRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineProvisioningRepository\": {\n      \"@id\": \"proton:pipelineProvisioningRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineServiceRoleArn\": {\n      \"@id\": \"proton:pipelineServiceRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetServiceSyncConfigInput\": \"proton:GetServiceSyncConfigInput\",\n    \"ListRepositoriesInput\": \"proton:ListRepositoriesInput\"\
  ,\n    \"EnvironmentAccountConnectionSummary\": \"proton:EnvironmentAccountConnectionSummary\",\n    \"CreateRepositoryOutput\": \"proton:CreateRepositoryOutput\",\n    \"GetRepositoryOutput\": \"proton:GetRepositoryOutput\",\n    \"GetServiceInstanceInput\": \"proton:GetServiceInstanceInput\",\n    \"GetServiceInstanceOutput\": \"proton:GetServiceInstanceOutput\",\n    \"GetTemplateSyncStatusInput\": \"proton:GetTemplateSyncStatusInput\",\n    \"templateVersion\": {\n      \"@id\": \"proton:templateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EnvironmentTemplateVersion\": \"proton:EnvironmentTemplateVersion\",\n    \"ListEnvironmentsInput\": \"proton:ListEnvironmentsInput\",\n    \"environmentTemplates\": {\n      \"@id\": \"proton:environmentTemplates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListComponentOutputsInput\": \"proton:ListComponentOutputsInput\",\n    \"UpdateServiceSyncBlockerInput\": \"proton:UpdateServiceSyncBlockerInput\",\n    \"ServiceTemplate\"\
  : \"proton:ServiceTemplate\",\n    \"CancelComponentDeploymentOutput\": \"proton:CancelComponentDeploymentOutput\",\n    \"CreateServiceTemplateOutput\": \"proton:CreateServiceTemplateOutput\",\n    \"UpdateServicePipelineOutput\": \"proton:UpdateServicePipelineOutput\",\n    \"DeleteTemplateSyncConfigInput\": \"proton:DeleteTemplateSyncConfigInput\",\n    \"GetEnvironmentAccountConnectionOutput\": \"proton:GetEnvironmentAccountConnectionOutput\",\n    \"EnvironmentTemplate\": \"proton:EnvironmentTemplate\",\n    \"CreateServiceTemplateInput\": \"proton:CreateServiceTemplateInput\",\n    \"DeleteEnvironmentTemplateOutput\": \"proton:DeleteEnvironmentTemplateOutput\",\n    \"ListComponentsInput\": \"proton:ListComponentsInput\",\n    \"DeleteServiceSyncConfigOutput\": \"proton:DeleteServiceSyncConfigOutput\",\n    \"UpdateTemplateSyncConfigOutput\": \"proton:UpdateTemplateSyncConfigOutput\",\n    \"GetComponentOutput\": \"proton:GetComponentOutput\",\n    \"AccountSettings\": \"proton:AccountSettings\"\
  ,\n    \"EnvironmentTemplateFilter\": \"proton:EnvironmentTemplateFilter\",\n    \"S3ObjectSource\": \"proton:S3ObjectSource\",\n    \"bucket\": {\n      \"@id\": \"proton:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateSyncConfig\": \"proton:TemplateSyncConfig\",\n    \"SyncBlockerContext\": \"proton:SyncBlockerContext\",\n    \"GetEnvironmentOutput\": \"proton:GetEnvironmentOutput\",\n    \"Component\": \"proton:Component\",\n    \"RepositorySyncEvent\": \"proton:RepositorySyncEvent\",\n    \"GetEnvironmentTemplateVersionInput\": \"proton:GetEnvironmentTemplateVersionInput\",\n    \"ListServicePipelineProvisionedResourcesInput\": \"proton:ListServicePipelineProvisionedResourcesInput\",\n    \"ListComponentProvisionedResourcesOutput\": \"proton:ListComponentProvisionedResourcesOutput\",\n    \"UpdateServiceTemplateVersionOutput\": \"proton:UpdateServiceTemplateVersionOutput\",\n    \"RepositorySummary\": \"proton:RepositorySummary\",\n    \"CreateServiceTemplateVersionInput\"\
  : \"proton:CreateServiceTemplateVersionInput\",\n    \"source\": {\n      \"@id\": \"proton:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListEnvironmentTemplateVersionsOutput\": \"proton:ListEnvironmentTemplateVersionsOutput\",\n    \"ListEnvironmentAccountConnectionsInput\": \"proton:ListEnvironmentAccountConnectionsInput\",\n    \"requestedBy\": {\n      \"@id\": \"proton:requestedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statuses\": {\n      \"@id\": \"proton:statuses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteServiceTemplateInput\": \"proton:DeleteServiceTemplateInput\",\n    \"DeleteServiceTemplateVersionInput\": \"proton:DeleteServiceTemplateVersionInput\",\n    \"ListComponentOutputsOutput\": \"proton:ListComponentOutputsOutput\",\n    \"ListTagsForResourceOutput\": \"proton:ListTagsForResourceOutput\",\n    \"AcceptEnvironmentAccountConnectionInput\": \"proton:AcceptEnvironmentAccountConnectionInput\",\n    \"UpdateTemplateSyncConfigInput\"\
  : \"proton:UpdateTemplateSyncConfigInput\",\n    \"TemplateVersionSourceInput\": \"proton:TemplateVersionSourceInput\",\n    \"s3\": {\n      \"@id\": \"proton:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListServiceInstanceOutputsInput\": \"proton:ListServiceInstanceOutputsInput\",\n    \"ListEnvironmentTemplatesInput\": \"proton:ListEnvironmentTemplatesInput\",\n    \"CountsSummary\": \"proton:CountsSummary\",\n    \"environments\": {\n      \"@id\": \"proton:environments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelines\": {\n      \"@id\": \"proton:pipelines\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceInstances\": {\n      \"@id\": \"proton:serviceInstances\",\n      \"@type\": \"xsd:string\"\n    },\n    \"serviceTemplates\": {\n      \"@id\": \"proton:serviceTemplates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateTemplateSyncConfigOutput\": \"proton:CreateTemplateSyncConfigOutput\",\n    \"CreateComponentOutput\": \"proton:CreateComponentOutput\"\
  ,\n    \"ServiceSyncBlockerSummary\": \"proton:ServiceSyncBlockerSummary\",\n    \"latestBlockers\": {\n      \"@id\": \"proton:latestBlockers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteComponentInput\": \"proton:DeleteComponentInput\",\n    \"GetServiceTemplateInput\": \"proton:GetServiceTemplateInput\",\n    \"UpdateServicePipelineInput\": \"proton:UpdateServicePipelineInput\",\n    \"GetServiceTemplateVersionOutput\": \"proton:GetServiceTemplateVersionOutput\",\n    \"EnvironmentTemplateVersionSummary\": \"proton:EnvironmentTemplateVersionSummary\",\n    \"ListEnvironmentsOutput\": \"proton:ListEnvironmentsOutput\",\n    \"GetEnvironmentAccountConnectionInput\": \"proton:GetEnvironmentAccountConnectionInput\",\n    \"DeleteServiceTemplateOutput\": \"proton:DeleteServiceTemplateOutput\",\n    \"RepositoryBranchInput\": \"proton:RepositoryBranchInput\",\n    \"GetServiceInput\": \"proton:GetServiceInput\",\n    \"DeleteRepositoryInput\": \"proton:DeleteRepositoryInput\"\
  ,\n    \"CreateEnvironmentTemplateVersionInput\": \"proton:CreateEnvironmentTemplateVersionInput\",\n    \"Environment\": \"proton:Environment\",\n    \"UpdateEnvironmentAccountConnectionOutput\": \"proton:UpdateEnvironmentAccountConnectionOutput\",\n    \"Repository\": \"proton:Repository\",\n    \"TagResourceInput\": \"proton:TagResourceInput\",\n    \"ListServiceTemplatesOutput\": \"proton:ListServiceTemplatesOutput\",\n    \"ListServiceInstancesOutput\": \"proton:ListServiceInstancesOutput\",\n    \"GetTemplateSyncConfigOutput\": \"proton:GetTemplateSyncConfigOutput\",\n    \"GetTemplateSyncConfigInput\": \"proton:GetTemplateSyncConfigInput\",\n    \"GetServiceTemplateVersionInput\": \"proton:GetServiceTemplateVersionInput\",\n    \"NotifyResourceDeploymentStatusChangeInput\": \"proton:NotifyResourceDeploymentStatusChangeInput\",\n    \"deploymentId\": {\n      \"@id\": \"proton:deploymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateServiceOutput\": \"proton:CreateServiceOutput\"\
  ,\n    \"ServiceTemplateVersion\": \"proton:ServiceTemplateVersion\",\n    \"GetServiceSyncConfigOutput\": \"proton:GetServiceSyncConfigOutput\",\n    \"CreateServiceInstanceInput\": \"proton:CreateServiceInstanceInput\",\n    \"Revision\": \"proton:Revision\",\n    \"sha\": {\n      \"@id\": \"proton:sha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateEnvironmentTemplateInput\": \"proton:CreateEnvironmentTemplateInput\",\n    \"DeleteServiceSyncConfigInput\": \"proton:DeleteServiceSyncConfigInput\",\n    \"ListServicesInput\": \"proton:ListServicesInput\",\n    \"CreateEnvironmentTemplateVersionOutput\": \"proton:CreateEnvironmentTemplateVersionOutput\",\n    \"CancelServiceInstanceDeploymentOutput\": \"proton:CancelServiceInstanceDeploymentOutput\",\n    \"GetEnvironmentInput\": \"proton:GetEnvironmentInput\",\n    \"GetResourcesSummaryOutput\": \"proton:GetResourcesSummaryOutput\",\n    \"counts\": {\n      \"@id\": \"proton:counts\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"UpdateServiceInstanceOutput\": \"proton:UpdateServiceInstanceOutput\",\n    \"GetServiceInstanceSyncStatusInput\": \"proton:GetServiceInstanceSyncStatusInput\",\n    \"CreateServiceTemplateVersionOutput\": \"proton:CreateServiceTemplateVersionOutput\",\n    \"CreateEnvironmentInput\": \"proton:CreateEnvironmentInput\",\n    \"ListComponentProvisionedResourcesInput\": \"proton:ListComponentProvisionedResourcesInput\",\n    \"CancelServicePipelineDeploymentInput\": \"proton:CancelServicePipelineDeploymentInput\",\n    \"DeleteEnvironmentTemplateVersionOutput\": \"proton:DeleteEnvironmentTemplateVersionOutput\",\n    \"ListServiceTemplatesInput\": \"proton:ListServiceTemplatesInput\",\n    \"DeleteEnvironmentAccountConnectionOutput\": \"proton:DeleteEnvironmentAccountConnectionOutput\",\n    \"DeleteServiceOutput\": \"proton:DeleteServiceOutput\",\n    \"EnvironmentSummary\": \"proton:EnvironmentSummary\",\n    \"GetTemplateSyncStatusOutput\": \"proton:GetTemplateSyncStatusOutput\"\
  ,\n    \"RepositoryBranch\": \"proton:RepositoryBranch\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-proton/refs/heads/main/json-ld/amazon-proton-context.jsonld
tags:
- AWS
- DevOps
- Infrastructure as Code
- Platform Engineering
- Serverless
- Templates
- Self-Service
- CI/CD
- JSON-LD
- Linked Data
- Semantic Web
---
