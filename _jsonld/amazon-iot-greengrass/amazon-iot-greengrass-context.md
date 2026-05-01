---
api_specs:
- filename: amazon-iot-greengrass-openapi-original.yml
  format: yaml
  label: AWS IoT Greengrass API
  slug: aws-iot-greengrass-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/openapi/amazon-iot-greengrass-openapi-original.yml
class_count: 102
classes:
- AssociateClientDeviceWithCoreDeviceEntry
- AssociateClientDeviceWithCoreDeviceErrorEntry
- AssociateServiceRoleToAccountRequest
- AssociateServiceRoleToAccountResponse
- AssociatedClientDevice
- BatchAssociateClientDeviceWithCoreDeviceRequest
- BatchAssociateClientDeviceWithCoreDeviceResponse
- BatchDisassociateClientDeviceFromCoreDeviceRequest
- BatchDisassociateClientDeviceFromCoreDeviceResponse
- CancelDeploymentRequest
- CancelDeploymentResponse
- CloudComponentStatus
- Component
- ComponentCandidate
- ComponentConfigurationUpdate
- ComponentDependencyMap
- ComponentDependencyRequirement
- ComponentDeploymentSpecification
- ComponentDeploymentSpecifications
- ComponentLatestVersion
- ComponentPlatform
- ComponentRunWith
- ComponentVersionListItem
- ComponentVersionRequirementMap
- ConnectivityInfo
- CoreDevice
- CreateComponentVersionRequest
- CreateComponentVersionResponse
- CreateDeploymentRequest
- CreateDeploymentResponse
- DeleteComponentRequest
- DeleteCoreDeviceRequest
- DeleteDeploymentRequest
- Deployment
- DeploymentComponentUpdatePolicy
- DeploymentConfigurationValidationPolicy
- DeploymentIoTJobConfiguration
- DeploymentPolicies
- DescribeComponentRequest
- DescribeComponentResponse
- DisassociateClientDeviceFromCoreDeviceEntry
- DisassociateClientDeviceFromCoreDeviceErrorEntry
- DisassociateServiceRoleFromAccountRequest
- DisassociateServiceRoleFromAccountResponse
- EffectiveDeployment
- EffectiveDeploymentStatusDetails
- GetComponentRequest
- GetComponentResponse
- GetComponentVersionArtifactRequest
- GetComponentVersionArtifactResponse
- GetConnectivityInfoRequest
- GetConnectivityInfoResponse
- GetCoreDeviceRequest
- GetCoreDeviceResponse
- GetDeploymentRequest
- GetDeploymentResponse
- GetServiceRoleForAccountRequest
- GetServiceRoleForAccountResponse
- InstalledComponent
- IoTJobAbortConfig
- IoTJobAbortCriteria
- IoTJobExecutionsRolloutConfig
- IoTJobExponentialRolloutRate
- IoTJobRateIncreaseCriteria
- IoTJobTimeoutConfig
- LambdaContainerParams
- LambdaDeviceMount
- LambdaEnvironmentVariables
- LambdaEventSource
- LambdaExecutionParameters
- LambdaFunctionRecipeSource
- LambdaLinuxProcessParams
- LambdaVolumeMount
- ListClientDevicesAssociatedWithCoreDeviceRequest
- ListClientDevicesAssociatedWithCoreDeviceResponse
- ListComponentVersionsRequest
- ListComponentVersionsResponse
- ListComponentsRequest
- ListComponentsResponse
- ListCoreDevicesRequest
- ListCoreDevicesResponse
- ListDeploymentsRequest
- ListDeploymentsResponse
- ListEffectiveDeploymentsRequest
- ListEffectiveDeploymentsResponse
- ListInstalledComponentsRequest
- ListInstalledComponentsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- PlatformAttributesMap
- ResolveComponentCandidatesRequest
- ResolveComponentCandidatesResponse
- ResolvedComponentVersion
- StringMap
- SystemResourceLimits
- TagMap
- TagResourceRequest
- TagResourceResponse
- UntagResourceRequest
- UntagResourceResponse
- description
- name
context_file: json-ld/amazon-iot-greengrass-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/json-ld/amazon-iot-greengrass-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iot Greengrass from Amazon IoT Greengrass.
layout: jsonld
name: Amazon Iot Greengrass Context
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
  name: abortConfig
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: addGroupOwner
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: associatedAt
  type: string
- container: ''
  name: associatedClientDevices
  type: string
- container: ''
  name: associationTimestamp
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: baseRatePerMinute
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: componentCandidates
  type: string
- container: ''
  name: componentDependencies
  type: string
- container: ''
  name: componentLambdaParameters
  type: string
- container: ''
  name: componentName
  type: string
- container: ''
  name: componentPlatforms
  type: string
- container: ''
  name: componentState
  type: string
- container: ''
  name: componentUpdatePolicy
  type: string
- container: ''
  name: componentVersion
  type: string
- container: ''
  name: componentVersions
  type: string
- container: ''
  name: components
  type: string
- container: ''
  name: configurationUpdate
  type: string
- container: ''
  name: configurationValidationPolicy
  type: string
- container: ''
  name: connectivityInfo
  type: string
- container: ''
  name: containerParams
  type: string
- container: ''
  name: coreDeviceExecutionStatus
  type: string
- container: ''
  name: coreDeviceThingName
  type: string
- container: ''
  name: coreDevices
  type: string
- container: ''
  name: coreVersion
  type: string
- container: ''
  name: cpus
  type: string
- container: ''
  name: creationTimestamp
  type: string
- container: ''
  name: criteriaList
  type: string
- container: ''
  name: dependencyType
  type: string
- container: ''
  name: deploymentId
  type: string
- container: ''
  name: deploymentName
  type: string
- container: ''
  name: deploymentPolicies
  type: string
- container: ''
  name: deploymentStatus
  type: string
- container: ''
  name: deployments
  type: string
- container: ''
  name: destinationPath
  type: string
- container: ''
  name: devices
  type: string
- container: ''
  name: disassociatedAt
  type: string
- container: ''
  name: effectiveDeployments
  type: string
- container: ''
  name: entries
  type: string
- container: ''
  name: environmentVariables
  type: string
- container: ''
  name: errorEntries
  type: string
- container: ''
  name: errorStack
  type: string
- container: ''
  name: errorTypes
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: eventSources
  type: string
- container: ''
  name: execArgs
  type: string
- container: ''
  name: exponentialRate
  type: string
- container: ''
  name: failureHandlingPolicy
  type: string
- container: ''
  name: failureType
  type: string
- container: ''
  name: hostAddress
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: inProgressTimeoutInMinutes
  type: string
- container: ''
  name: incrementFactor
  type: string
- container: ''
  name: inlineRecipe
  type: string
- container: ''
  name: inputPayloadEncodingType
  type: string
- container: ''
  name: installedComponents
  type: string
- container: ''
  name: iotJobArn
  type: string
- container: ''
  name: iotJobConfiguration
  type: string
- container: ''
  name: iotJobId
  type: string
- container: ''
  name: isLatestForTarget
  type: string
- container: ''
  name: isRoot
  type: string
- container: ''
  name: isolationMode
  type: string
- container: ''
  name: jobExecutionsRolloutConfig
  type: string
- container: ''
  name: lambdaArn
  type: string
- container: ''
  name: lambdaFunction
  type: string
- container: ''
  name: lastInstallationSource
  type: string
- container: ''
  name: lastReportedTimestamp
  type: string
- container: ''
  name: lastStatusChangeTimestamp
  type: string
- container: ''
  name: lastStatusUpdateTimestamp
  type: string
- container: ''
  name: latestVersion
  type: string
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: lifecycleStateDetails
  type: string
- container: ''
  name: lifecycleStatusCodes
  type: string
- container: ''
  name: linuxProcessParams
  type: string
- container: ''
  name: maxIdleTimeInSeconds
  type: string
- container: ''
  name: maxInstancesCount
  type: string
- container: ''
  name: maxQueueSize
  type: string
- container: ''
  name: maximumPerMinute
  type: string
- container: ''
  name: memory
  type: string
- container: ''
  name: memorySizeInKB
  type: string
- container: ''
  name: merge
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: metadata
  type: string
- container: ''
  name: minNumberOfExecutedThings
  type: string
- container: ''
  name: modifiedTimestamp
  type: string
- container: ''
  name: mountROSysfs
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: numberOfNotifiedThings
  type: string
- container: ''
  name: numberOfSucceededThings
  type: string
- container: ''
  name: parentTargetArn
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: permission
  type: string
- container: ''
  name: pinned
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: platforms
  type: string
- container: ''
  name: portNumber
  type: string
- container: ''
  name: posixUser
  type: string
- container: ''
  name: preSignedUrl
  type: string
- container: ''
  name: publisher
  type: string
- container: ''
  name: rateIncreaseCriteria
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: recipe
  type: string
- container: ''
  name: recipeOutputFormat
  type: string
- container: ''
  name: reset
  type: string
- container: ''
  name: resolvedComponentVersions
  type: string
- container: ''
  name: revisionId
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: runWith
  type: string
- container: ''
  name: sourcePath
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusDetails
  type: string
- container: ''
  name: statusTimeoutInSeconds
  type: string
- container: ''
  name: systemResourceLimits
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targetArn
  type: string
- container: ''
  name: thingName
  type: string
- container: ''
  name: thresholdPercentage
  type: string
- container: ''
  name: timeoutConfig
  type: string
- container: ''
  name: timeoutInSeconds
  type: string
- container: ''
  name: topic
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: vendorGuidance
  type: string
- container: ''
  name: vendorGuidanceMessage
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: versionRequirement
  type: string
- container: ''
  name: versionRequirements
  type: string
- container: ''
  name: volumes
  type: string
- container: ''
  name: windowsUser
  type: string
property_count: 133
provider_name: Amazon IoT Greengrass
provider_slug: amazon-iot-greengrass
slug: amazon-iot-greengrass-context
source_filename: amazon-iot-greengrass-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociateClientDeviceWithCoreDeviceEntry\": \"amzn:AssociateClientDeviceWithCoreDeviceEntry\",\n    \"AssociateClientDeviceWithCoreDeviceErrorEntry\": \"amzn:AssociateClientDeviceWithCoreDeviceErrorEntry\",\n    \"AssociateServiceRoleToAccountRequest\": \"amzn:AssociateServiceRoleToAccountRequest\",\n    \"AssociateServiceRoleToAccountResponse\": \"amzn:AssociateServiceRoleToAccountResponse\",\n    \"AssociatedClientDevice\": \"amzn:AssociatedClientDevice\",\n    \"BatchAssociateClientDeviceWithCoreDeviceRequest\": \"amzn:BatchAssociateClientDeviceWithCoreDeviceRequest\",\n    \"BatchAssociateClientDeviceWithCoreDeviceResponse\": \"amzn:BatchAssociateClientDeviceWithCoreDeviceResponse\",\n    \"BatchDisassociateClientDeviceFromCoreDeviceRequest\"\
  : \"amzn:BatchDisassociateClientDeviceFromCoreDeviceRequest\",\n    \"BatchDisassociateClientDeviceFromCoreDeviceResponse\": \"amzn:BatchDisassociateClientDeviceFromCoreDeviceResponse\",\n    \"CancelDeploymentRequest\": \"amzn:CancelDeploymentRequest\",\n    \"CancelDeploymentResponse\": \"amzn:CancelDeploymentResponse\",\n    \"CloudComponentStatus\": \"amzn:CloudComponentStatus\",\n    \"Component\": \"amzn:Component\",\n    \"ComponentCandidate\": \"amzn:ComponentCandidate\",\n    \"ComponentConfigurationUpdate\": \"amzn:ComponentConfigurationUpdate\",\n    \"ComponentDependencyMap\": \"amzn:ComponentDependencyMap\",\n    \"ComponentDependencyRequirement\": \"amzn:ComponentDependencyRequirement\",\n    \"ComponentDeploymentSpecification\": \"amzn:ComponentDeploymentSpecification\",\n    \"ComponentDeploymentSpecifications\": \"amzn:ComponentDeploymentSpecifications\",\n    \"ComponentLatestVersion\": \"amzn:ComponentLatestVersion\",\n    \"ComponentPlatform\": \"amzn:ComponentPlatform\"\
  ,\n    \"ComponentRunWith\": \"amzn:ComponentRunWith\",\n    \"ComponentVersionListItem\": \"amzn:ComponentVersionListItem\",\n    \"ComponentVersionRequirementMap\": \"amzn:ComponentVersionRequirementMap\",\n    \"ConnectivityInfo\": \"amzn:ConnectivityInfo\",\n    \"CoreDevice\": \"amzn:CoreDevice\",\n    \"CreateComponentVersionRequest\": \"amzn:CreateComponentVersionRequest\",\n    \"CreateComponentVersionResponse\": \"amzn:CreateComponentVersionResponse\",\n    \"CreateDeploymentRequest\": \"amzn:CreateDeploymentRequest\",\n    \"CreateDeploymentResponse\": \"amzn:CreateDeploymentResponse\",\n    \"DeleteComponentRequest\": \"amzn:DeleteComponentRequest\",\n    \"DeleteCoreDeviceRequest\": \"amzn:DeleteCoreDeviceRequest\",\n    \"DeleteDeploymentRequest\": \"amzn:DeleteDeploymentRequest\",\n    \"Deployment\": \"amzn:Deployment\",\n    \"DeploymentComponentUpdatePolicy\": \"amzn:DeploymentComponentUpdatePolicy\",\n    \"DeploymentConfigurationValidationPolicy\": \"amzn:DeploymentConfigurationValidationPolicy\"\
  ,\n    \"DeploymentIoTJobConfiguration\": \"amzn:DeploymentIoTJobConfiguration\",\n    \"DeploymentPolicies\": \"amzn:DeploymentPolicies\",\n    \"DescribeComponentRequest\": \"amzn:DescribeComponentRequest\",\n    \"DescribeComponentResponse\": \"amzn:DescribeComponentResponse\",\n    \"DisassociateClientDeviceFromCoreDeviceEntry\": \"amzn:DisassociateClientDeviceFromCoreDeviceEntry\",\n    \"DisassociateClientDeviceFromCoreDeviceErrorEntry\": \"amzn:DisassociateClientDeviceFromCoreDeviceErrorEntry\",\n    \"DisassociateServiceRoleFromAccountRequest\": \"amzn:DisassociateServiceRoleFromAccountRequest\",\n    \"DisassociateServiceRoleFromAccountResponse\": \"amzn:DisassociateServiceRoleFromAccountResponse\",\n    \"EffectiveDeployment\": \"amzn:EffectiveDeployment\",\n    \"EffectiveDeploymentStatusDetails\": \"amzn:EffectiveDeploymentStatusDetails\",\n    \"GetComponentRequest\": \"amzn:GetComponentRequest\",\n    \"GetComponentResponse\": \"amzn:GetComponentResponse\",\n    \"GetComponentVersionArtifactRequest\"\
  : \"amzn:GetComponentVersionArtifactRequest\",\n    \"GetComponentVersionArtifactResponse\": \"amzn:GetComponentVersionArtifactResponse\",\n    \"GetConnectivityInfoRequest\": \"amzn:GetConnectivityInfoRequest\",\n    \"GetConnectivityInfoResponse\": \"amzn:GetConnectivityInfoResponse\",\n    \"GetCoreDeviceRequest\": \"amzn:GetCoreDeviceRequest\",\n    \"GetCoreDeviceResponse\": \"amzn:GetCoreDeviceResponse\",\n    \"GetDeploymentRequest\": \"amzn:GetDeploymentRequest\",\n    \"GetDeploymentResponse\": \"amzn:GetDeploymentResponse\",\n    \"GetServiceRoleForAccountRequest\": \"amzn:GetServiceRoleForAccountRequest\",\n    \"GetServiceRoleForAccountResponse\": \"amzn:GetServiceRoleForAccountResponse\",\n    \"InstalledComponent\": \"amzn:InstalledComponent\",\n    \"IoTJobAbortConfig\": \"amzn:IoTJobAbortConfig\",\n    \"IoTJobAbortCriteria\": \"amzn:IoTJobAbortCriteria\",\n    \"IoTJobExecutionsRolloutConfig\": \"amzn:IoTJobExecutionsRolloutConfig\",\n    \"IoTJobExponentialRolloutRate\"\
  : \"amzn:IoTJobExponentialRolloutRate\",\n    \"IoTJobRateIncreaseCriteria\": \"amzn:IoTJobRateIncreaseCriteria\",\n    \"IoTJobTimeoutConfig\": \"amzn:IoTJobTimeoutConfig\",\n    \"LambdaContainerParams\": \"amzn:LambdaContainerParams\",\n    \"LambdaDeviceMount\": \"amzn:LambdaDeviceMount\",\n    \"LambdaEnvironmentVariables\": \"amzn:LambdaEnvironmentVariables\",\n    \"LambdaEventSource\": \"amzn:LambdaEventSource\",\n    \"LambdaExecutionParameters\": \"amzn:LambdaExecutionParameters\",\n    \"LambdaFunctionRecipeSource\": \"amzn:LambdaFunctionRecipeSource\",\n    \"LambdaLinuxProcessParams\": \"amzn:LambdaLinuxProcessParams\",\n    \"LambdaVolumeMount\": \"amzn:LambdaVolumeMount\",\n    \"ListClientDevicesAssociatedWithCoreDeviceRequest\": \"amzn:ListClientDevicesAssociatedWithCoreDeviceRequest\",\n    \"ListClientDevicesAssociatedWithCoreDeviceResponse\": \"amzn:ListClientDevicesAssociatedWithCoreDeviceResponse\",\n    \"ListComponentVersionsRequest\": \"amzn:ListComponentVersionsRequest\"\
  ,\n    \"ListComponentVersionsResponse\": \"amzn:ListComponentVersionsResponse\",\n    \"ListComponentsRequest\": \"amzn:ListComponentsRequest\",\n    \"ListComponentsResponse\": \"amzn:ListComponentsResponse\",\n    \"ListCoreDevicesRequest\": \"amzn:ListCoreDevicesRequest\",\n    \"ListCoreDevicesResponse\": \"amzn:ListCoreDevicesResponse\",\n    \"ListDeploymentsRequest\": \"amzn:ListDeploymentsRequest\",\n    \"ListDeploymentsResponse\": \"amzn:ListDeploymentsResponse\",\n    \"ListEffectiveDeploymentsRequest\": \"amzn:ListEffectiveDeploymentsRequest\",\n    \"ListEffectiveDeploymentsResponse\": \"amzn:ListEffectiveDeploymentsResponse\",\n    \"ListInstalledComponentsRequest\": \"amzn:ListInstalledComponentsRequest\",\n    \"ListInstalledComponentsResponse\": \"amzn:ListInstalledComponentsResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"PlatformAttributesMap\": \"\
  amzn:PlatformAttributesMap\",\n    \"ResolveComponentCandidatesRequest\": \"amzn:ResolveComponentCandidatesRequest\",\n    \"ResolveComponentCandidatesResponse\": \"amzn:ResolveComponentCandidatesResponse\",\n    \"ResolvedComponentVersion\": \"amzn:ResolvedComponentVersion\",\n    \"StringMap\": \"amzn:StringMap\",\n    \"SystemResourceLimits\": \"amzn:SystemResourceLimits\",\n    \"TagMap\": \"amzn:TagMap\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"TagResourceResponse\": \"amzn:TagResourceResponse\",\n    \"UntagResourceRequest\": \"amzn:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amzn:UntagResourceResponse\",\n    \"abortConfig\": {\n      \"@id\": \"amzn:abortConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addGroupOwner\": {\n      \"@id\": \"amzn:addGroupOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\"\
  : \"amzn:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedAt\": {\n      \"@id\": \"amzn:associatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedClientDevices\": {\n      \"@id\": \"amzn:associatedClientDevices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associationTimestamp\": {\n      \"@id\": \"amzn:associationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amzn:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseRatePerMinute\": {\n      \"@id\": \"amzn:baseRatePerMinute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amzn:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amzn:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentCandidates\": {\n      \"@id\": \"amzn:componentCandidates\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"componentDependencies\": {\n      \"@id\": \"amzn:componentDependencies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentLambdaParameters\": {\n      \"@id\": \"amzn:componentLambdaParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentName\": {\n      \"@id\": \"amzn:componentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentPlatforms\": {\n      \"@id\": \"amzn:componentPlatforms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentState\": {\n      \"@id\": \"amzn:componentState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentUpdatePolicy\": {\n      \"@id\": \"amzn:componentUpdatePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentVersion\": {\n      \"@id\": \"amzn:componentVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentVersions\": {\n      \"@id\": \"amzn:componentVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"components\": {\n     \
  \ \"@id\": \"amzn:components\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationUpdate\": {\n      \"@id\": \"amzn:configurationUpdate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationValidationPolicy\": {\n      \"@id\": \"amzn:configurationValidationPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"connectivityInfo\": {\n      \"@id\": \"amzn:connectivityInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerParams\": {\n      \"@id\": \"amzn:containerParams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreDeviceExecutionStatus\": {\n      \"@id\": \"amzn:coreDeviceExecutionStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreDeviceThingName\": {\n      \"@id\": \"amzn:coreDeviceThingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreDevices\": {\n      \"@id\": \"amzn:coreDevices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coreVersion\": {\n      \"@id\": \"amzn:coreVersion\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"cpus\": {\n      \"@id\": \"amzn:cpus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creationTimestamp\": {\n      \"@id\": \"amzn:creationTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"criteriaList\": {\n      \"@id\": \"amzn:criteriaList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dependencyType\": {\n      \"@id\": \"amzn:dependencyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentId\": {\n      \"@id\": \"amzn:deploymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentName\": {\n      \"@id\": \"amzn:deploymentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentPolicies\": {\n      \"@id\": \"amzn:deploymentPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentStatus\": {\n      \"@id\": \"amzn:deploymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deployments\": {\n      \"@id\": \"amzn:deployments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\"\
  ,\n    \"destinationPath\": {\n      \"@id\": \"amzn:destinationPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"devices\": {\n      \"@id\": \"amzn:devices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"disassociatedAt\": {\n      \"@id\": \"amzn:disassociatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDeployments\": {\n      \"@id\": \"amzn:effectiveDeployments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entries\": {\n      \"@id\": \"amzn:entries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentVariables\": {\n      \"@id\": \"amzn:environmentVariables\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorEntries\": {\n      \"@id\": \"amzn:errorEntries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorStack\": {\n      \"@id\": \"amzn:errorStack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorTypes\": {\n      \"@id\": \"amzn:errorTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"\
  amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventSources\": {\n      \"@id\": \"amzn:eventSources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"execArgs\": {\n      \"@id\": \"amzn:execArgs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exponentialRate\": {\n      \"@id\": \"amzn:exponentialRate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureHandlingPolicy\": {\n      \"@id\": \"amzn:failureHandlingPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureType\": {\n      \"@id\": \"amzn:failureType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hostAddress\": {\n      \"@id\": \"amzn:hostAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amzn:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inProgressTimeoutInMinutes\": {\n      \"@id\": \"amzn:inProgressTimeoutInMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"incrementFactor\": {\n      \"@id\": \"amzn:incrementFactor\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"inlineRecipe\": {\n      \"@id\": \"amzn:inlineRecipe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputPayloadEncodingType\": {\n      \"@id\": \"amzn:inputPayloadEncodingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"installedComponents\": {\n      \"@id\": \"amzn:installedComponents\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotJobArn\": {\n      \"@id\": \"amzn:iotJobArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotJobConfiguration\": {\n      \"@id\": \"amzn:iotJobConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iotJobId\": {\n      \"@id\": \"amzn:iotJobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isLatestForTarget\": {\n      \"@id\": \"amzn:isLatestForTarget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isRoot\": {\n      \"@id\": \"amzn:isRoot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isolationMode\": {\n      \"@id\": \"amzn:isolationMode\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"jobExecutionsRolloutConfig\": {\n      \"@id\": \"amzn:jobExecutionsRolloutConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaArn\": {\n      \"@id\": \"amzn:lambdaArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunction\": {\n      \"@id\": \"amzn:lambdaFunction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastInstallationSource\": {\n      \"@id\": \"amzn:lastInstallationSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastReportedTimestamp\": {\n      \"@id\": \"amzn:lastReportedTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastStatusChangeTimestamp\": {\n      \"@id\": \"amzn:lastStatusChangeTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastStatusUpdateTimestamp\": {\n      \"@id\": \"amzn:lastStatusUpdateTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestVersion\": {\n      \"@id\": \"amzn:latestVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleState\": {\n     \
  \ \"@id\": \"amzn:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleStateDetails\": {\n      \"@id\": \"amzn:lifecycleStateDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleStatusCodes\": {\n      \"@id\": \"amzn:lifecycleStatusCodes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"linuxProcessParams\": {\n      \"@id\": \"amzn:linuxProcessParams\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxIdleTimeInSeconds\": {\n      \"@id\": \"amzn:maxIdleTimeInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxInstancesCount\": {\n      \"@id\": \"amzn:maxInstancesCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxQueueSize\": {\n      \"@id\": \"amzn:maxQueueSize\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maximumPerMinute\": {\n      \"@id\": \"amzn:maximumPerMinute\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memory\": {\n      \"@id\": \"amzn:memory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memorySizeInKB\"\
  : {\n      \"@id\": \"amzn:memorySizeInKB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"merge\": {\n      \"@id\": \"amzn:merge\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metadata\": {\n      \"@id\": \"amzn:metadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"minNumberOfExecutedThings\": {\n      \"@id\": \"amzn:minNumberOfExecutedThings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modifiedTimestamp\": {\n      \"@id\": \"amzn:modifiedTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mountROSysfs\": {\n      \"@id\": \"amzn:mountROSysfs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfNotifiedThings\": {\n      \"@id\": \"amzn:numberOfNotifiedThings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"numberOfSucceededThings\"\
  : {\n      \"@id\": \"amzn:numberOfSucceededThings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentTargetArn\": {\n      \"@id\": \"amzn:parentTargetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"amzn:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permission\": {\n      \"@id\": \"amzn:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pinned\": {\n      \"@id\": \"amzn:pinned\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"amzn:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platforms\": {\n      \"@id\": \"amzn:platforms\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portNumber\": {\n      \"@id\": \"amzn:portNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"posixUser\": {\n      \"@id\": \"amzn:posixUser\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preSignedUrl\": {\n      \"@id\": \"amzn:preSignedUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\"\
  : {\n      \"@id\": \"amzn:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rateIncreaseCriteria\": {\n      \"@id\": \"amzn:rateIncreaseCriteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"amzn:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipe\": {\n      \"@id\": \"amzn:recipe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recipeOutputFormat\": {\n      \"@id\": \"amzn:recipeOutputFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reset\": {\n      \"@id\": \"amzn:reset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resolvedComponentVersions\": {\n      \"@id\": \"amzn:resolvedComponentVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionId\": {\n      \"@id\": \"amzn:revisionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"amzn:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runWith\": {\n      \"@id\": \"amzn:runWith\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"sourcePath\": {\n      \"@id\": \"amzn:sourcePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusDetails\": {\n      \"@id\": \"amzn:statusDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusTimeoutInSeconds\": {\n      \"@id\": \"amzn:statusTimeoutInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemResourceLimits\": {\n      \"@id\": \"amzn:systemResourceLimits\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetArn\": {\n      \"@id\": \"amzn:targetArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thingName\": {\n      \"@id\": \"amzn:thingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"thresholdPercentage\": {\n      \"@id\": \"amzn:thresholdPercentage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutConfig\": {\n      \"@id\"\
  : \"amzn:timeoutConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutInSeconds\": {\n      \"@id\": \"amzn:timeoutInSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topic\": {\n      \"@id\": \"amzn:topic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorGuidance\": {\n      \"@id\": \"amzn:vendorGuidance\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorGuidanceMessage\": {\n      \"@id\": \"amzn:vendorGuidanceMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"amzn:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionRequirement\": {\n      \"@id\": \"amzn:versionRequirement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionRequirements\": {\n      \"@id\": \"amzn:versionRequirements\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumes\": {\n      \"@id\": \"amzn:volumes\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"windowsUser\": {\n      \"@id\": \"amzn:windowsUser\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iot-greengrass/refs/heads/main/json-ld/amazon-iot-greengrass-context.jsonld
tags:
- Edge Computing
- IoT
- Lambda
- Machine Learning
- Real-Time Processing
- JSON-LD
- Linked Data
- Semantic Web
---
