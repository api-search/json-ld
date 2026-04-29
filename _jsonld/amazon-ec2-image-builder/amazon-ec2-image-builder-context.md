---
api_specs:
- filename: amazon-ec2-image-builder-openapi.yaml
  format: yaml
  label: Amazon EC2 Image Builder API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-image-builder/refs/heads/main/openapi/amazon-ec2-image-builder-openapi.yaml
class_count: 50
classes:
- AccountAggregation
- AdditionalInstanceConfiguration
- Ami
- AmiDistributionConfiguration
- CancelImageCreationRequest
- CancelImageCreationResponse
- Component
- ComponentConfiguration
- ComponentParameter
- ComponentParameterDetail
- ComponentState
- ComponentSummary
- ComponentVersion
- Container
- ContainerDistributionConfiguration
- ContainerRecipe
- ContainerRecipeSummary
- CreateComponentRequest
- CreateComponentResponse
- CreateContainerRecipeRequest
- CreateContainerRecipeResponse
- CreateDistributionConfigurationRequest
- CreateDistributionConfigurationResponse
- CreateImagePipelineRequest
- CreateImagePipelineResponse
- CreateImageRecipeRequest
- CreateImageRecipeResponse
- CreateImageRequest
- CreateImageResponse
- CreateInfrastructureConfigurationRequest
- CreateInfrastructureConfigurationResponse
- CvssScore
- CvssScoreAdjustment
- CvssScoreDetails
- DeleteComponentRequest
- DeleteComponentResponse
- DeleteContainerRecipeRequest
- DeleteContainerRecipeResponse
- DeleteDistributionConfigurationRequest
- DeleteDistributionConfigurationResponse
- DeleteImagePipelineRequest
- DeleteImagePipelineResponse
- DeleteImageRecipeRequest
- DeleteImageRecipeResponse
- DeleteImageRequest
- DeleteImageResponse
- DeleteInfrastructureConfigurationRequest
- DeleteInfrastructureConfigurationResponse
- Distribution
- DistributionConfiguration
context_file: json-ld/amazon-ec2-image-builder-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-image-builder/refs/heads/main/json-ld/amazon-ec2-image-builder-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Ec2 Image Builder from Amazon EC2 Image Builder.
layout: jsonld
name: Amazon Ec2 Image Builder Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: pan
  uri: https://aws.amazon.com/schema/
properties:
- container: ''
  name: filters
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: s3Logs
  type: string
- container: ''
  name: launchTemplateId
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: setDefaultVersion
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: imageRecipeArn
  type: string
- container: ''
  name: containerRecipeArn
  type: string
- container: ''
  name: distributionConfigurationArn
  type: string
- container: ''
  name: infrastructureConfigurationArn
  type: string
- container: ''
  name: imageTestsConfiguration
  type: string
- container: ''
  name: enhancedImageMetadataEnabled
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: imageScanningConfiguration
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: changeDescription
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: supportedOsVersions
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: encrypted
  type: string
- container: ''
  name: dateCreated
  type: string
- container: ''
  name: publisher
  type: string
- container: ''
  name: obfuscate
  type: string
- container: ''
  name: awsAccountId
  type: string
- container: ''
  name: imageBuildVersionArn
  type: string
- container: ''
  name: imagePipelineArn
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: remediation
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: firstObservedAt
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: inspectorScore
  type: string
- container: ''
  name: inspectorScoreDetails
  type: string
- container: ''
  name: packageVulnerabilityDetails
  type: string
- container: ''
  name: fixAvailable
  type: string
- container: ''
  name: vulnerabilityId
  type: string
- container: ''
  name: vulnerablePackages
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: cvss
  type: string
- container: ''
  name: relatedVulnerabilities
  type: string
- container: ''
  name: sourceUrl
  type: string
- container: ''
  name: vendorSeverity
  type: string
- container: ''
  name: vendorCreatedAt
  type: string
- container: ''
  name: vendorUpdatedAt
  type: string
- container: ''
  name: referenceUrls
  type: string
- container: ''
  name: scheduleExpression
  type: string
- container: ''
  name: timezone
  type: string
- container: ''
  name: pipelineExecutionStartCondition
  type: string
- container: ''
  name: deviceName
  type: string
- container: ''
  name: ebs
  type: string
- container: ''
  name: virtualName
  type: string
- container: ''
  name: noDevice
  type: string
- container: ''
  name: launchTemplateName
  type: string
- container: ''
  name: launchTemplateVersion
  type: string
- container: ''
  name: components
  type: string
- container: ''
  name: parentImage
  type: string
- container: ''
  name: blockDeviceMappings
  type: string
- container: ''
  name: workingDirectory
  type: string
- container: ''
  name: additionalInstanceConfiguration
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: schedule
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: dateUpdated
  type: string
- container: ''
  name: dateLastRun
  type: string
- container: ''
  name: dateNextRun
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: imageVersionList
  type: string
- container: ''
  name: componentVersionArn
  type: string
- container: ''
  name: aggregationType
  type: string
- container: ''
  name: responses
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: targetResourceCount
  type: string
- container: ''
  name: imageScanningEnabled
  type: string
- container: ''
  name: ecrConfiguration
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: imagePackageList
  type: string
- container: ''
  name: defaultValue
  type: string
- container: ''
  name: distributions
  type: string
- container: ''
  name: timeoutMinutes
  type: string
- container: ''
  name: adjustedCvss
  type: string
- container: ''
  name: severityCounts
  type: string
- container: ''
  name: sourceLayerHash
  type: string
- container: ''
  name: epoch
  type: string
- container: ''
  name: release
  type: string
- container: ''
  name: arch
  type: string
- container: ''
  name: packageManager
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: fixedInVersion
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: accountAggregation
  type: string
- container: ''
  name: imageAggregation
  type: string
- container: ''
  name: imagePipelineAggregation
  type: string
- container: ''
  name: vulnerabilityIdAggregation
  type: string
- container: ''
  name: componentSummaryList
  type: string
- container: ''
  name: semanticVersion
  type: string
- container: ''
  name: workflowBuildVersionArn
  type: string
- container: ''
  name: workflowExecutionId
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: totalStepCount
  type: string
- container: ''
  name: totalStepsSucceeded
  type: string
- container: ''
  name: totalStepsFailed
  type: string
- container: ''
  name: totalStepsSkipped
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: s3BucketName
  type: string
- container: ''
  name: s3KeyPrefix
  type: string
- container: ''
  name: osVersion
  type: string
- container: ''
  name: buildType
  type: string
- container: ''
  name: imageSource
  type: string
- container: ''
  name: imageRecipeSummaryList
  type: string
- container: ''
  name: distributionConfiguration
  type: string
- container: ''
  name: targetAccountIds
  type: string
- container: ''
  name: amiTags
  type: string
- container: ''
  name: launchPermission
  type: string
- container: ''
  name: imageArn
  type: string
- container: ''
  name: instanceTypes
  type: string
- container: ''
  name: instanceProfileName
  type: string
- container: ''
  name: securityGroupIds
  type: string
- container: ''
  name: subnetId
  type: string
- container: ''
  name: logging
  type: string
- container: ''
  name: keyPair
  type: string
- container: ''
  name: terminateInstanceOnFailure
  type: string
- container: ''
  name: snsTopicArn
  type: string
- container: ''
  name: resourceTags
  type: string
- container: ''
  name: instanceMetadataOptions
  type: string
- container: ''
  name: workflowExecutions
  type: string
- container: ''
  name: region
  type: string
- container: ''
  name: amiDistributionConfiguration
  type: string
- container: ''
  name: containerDistributionConfiguration
  type: string
- container: ''
  name: licenseConfigurationArns
  type: string
- container: ''
  name: launchTemplateConfigurations
  type: string
- container: ''
  name: s3ExportConfiguration
  type: string
- container: ''
  name: fastLaunchConfigurations
  type: string
- container: ''
  name: containerRecipe
  type: string
- container: ''
  name: steps
  type: string
- container: ''
  name: httpTokens
  type: string
- container: ''
  name: httpPutResponseHopLimit
  type: string
- container: ''
  name: roleName
  type: string
- container: ''
  name: diskImageFormat
  type: string
- container: ''
  name: s3Bucket
  type: string
- container: ''
  name: s3Prefix
  type: string
- container: ''
  name: byName
  type: string
- container: ''
  name: includeDeprecated
  type: string
- container: ''
  name: imageRecipe
  type: string
- container: ''
  name: sourcePipelineName
  type: string
- container: ''
  name: sourcePipelineArn
  type: string
- container: ''
  name: infrastructureConfiguration
  type: string
- container: ''
  name: outputResources
  type: string
- container: ''
  name: scanState
  type: string
- container: ''
  name: imageTestsEnabled
  type: string
- container: ''
  name: component
  type: string
- container: ''
  name: recommendation
  type: string
- container: ''
  name: containerTags
  type: string
- container: ''
  name: targetRepository
  type: string
- container: ''
  name: containerType
  type: string
- container: ''
  name: instanceConfiguration
  type: string
- container: ''
  name: dockerfileTemplateData
  type: string
- container: ''
  name: stepExecutionId
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: rollbackStatus
  type: string
- container: ''
  name: inputs
  type: string
- container: ''
  name: outputs
  type: string
- container: ''
  name: onFailure
  type: string
- container: ''
  name: timeoutSeconds
  type: string
- container: ''
  name: findings
  type: string
- container: ''
  name: componentBuildVersionArn
  type: string
- container: ''
  name: infrastructureConfigurationSummaryList
  type: string
- container: ''
  name: enabled
  type: string
- container: ''
  name: snapshotConfiguration
  type: string
- container: ''
  name: maxParallelLaunches
  type: string
- container: ''
  name: launchTemplate
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: imageVersionArn
  type: string
- container: ''
  name: amis
  type: string
- container: ''
  name: containers
  type: string
- container: ''
  name: userIds
  type: string
- container: ''
  name: userGroups
  type: string
- container: ''
  name: organizationArns
  type: string
- container: ''
  name: organizationalUnitArns
  type: string
- container: ''
  name: imagePipelineList
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: containerRecipeSummaryList
  type: string
- container: ''
  name: componentVersionList
  type: string
- container: ''
  name: uninstallAfterBuild
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: distributionConfigurationSummaryList
  type: string
- container: ''
  name: deleteOnTermination
  type: string
- container: ''
  name: iops
  type: string
- container: ''
  name: snapshotId
  type: string
- container: ''
  name: volumeSize
  type: string
property_count: 200
provider_name: Amazon EC2 Image Builder
provider_slug: amazon-ec2-image-builder
slug: amazon-ec2-image-builder-context
source_filename: amazon-ec2-image-builder-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"pan\": \"https://aws.amazon.com/schema/\",\n    \"AccountAggregation\": \"aws:AccountAggregation\",\n    \"AdditionalInstanceConfiguration\": \"aws:AdditionalInstanceConfiguration\",\n    \"Ami\": \"aws:Ami\",\n    \"AmiDistributionConfiguration\": \"aws:AmiDistributionConfiguration\",\n    \"CancelImageCreationRequest\": \"aws:CancelImageCreationRequest\",\n    \"CancelImageCreationResponse\": \"aws:CancelImageCreationResponse\",\n    \"Component\": \"aws:Component\",\n    \"ComponentConfiguration\": \"aws:ComponentConfiguration\",\n    \"ComponentParameter\": \"aws:ComponentParameter\",\n    \"ComponentParameterDetail\": \"aws:ComponentParameterDetail\",\n    \"ComponentState\": \"aws:ComponentState\",\n    \"ComponentSummary\": \"\
  aws:ComponentSummary\",\n    \"ComponentVersion\": \"aws:ComponentVersion\",\n    \"Container\": \"aws:Container\",\n    \"ContainerDistributionConfiguration\": \"aws:ContainerDistributionConfiguration\",\n    \"ContainerRecipe\": \"aws:ContainerRecipe\",\n    \"ContainerRecipeSummary\": \"aws:ContainerRecipeSummary\",\n    \"CreateComponentRequest\": \"aws:CreateComponentRequest\",\n    \"CreateComponentResponse\": \"aws:CreateComponentResponse\",\n    \"CreateContainerRecipeRequest\": \"aws:CreateContainerRecipeRequest\",\n    \"CreateContainerRecipeResponse\": \"aws:CreateContainerRecipeResponse\",\n    \"CreateDistributionConfigurationRequest\": \"aws:CreateDistributionConfigurationRequest\",\n    \"CreateDistributionConfigurationResponse\": \"aws:CreateDistributionConfigurationResponse\",\n    \"CreateImagePipelineRequest\": \"aws:CreateImagePipelineRequest\",\n    \"CreateImagePipelineResponse\": \"aws:CreateImagePipelineResponse\",\n    \"CreateImageRecipeRequest\": \"aws:CreateImageRecipeRequest\"\
  ,\n    \"CreateImageRecipeResponse\": \"aws:CreateImageRecipeResponse\",\n    \"CreateImageRequest\": \"aws:CreateImageRequest\",\n    \"CreateImageResponse\": \"aws:CreateImageResponse\",\n    \"CreateInfrastructureConfigurationRequest\": \"aws:CreateInfrastructureConfigurationRequest\",\n    \"CreateInfrastructureConfigurationResponse\": \"aws:CreateInfrastructureConfigurationResponse\",\n    \"CvssScore\": \"aws:CvssScore\",\n    \"CvssScoreAdjustment\": \"aws:CvssScoreAdjustment\",\n    \"CvssScoreDetails\": \"aws:CvssScoreDetails\",\n    \"DeleteComponentRequest\": \"aws:DeleteComponentRequest\",\n    \"DeleteComponentResponse\": \"aws:DeleteComponentResponse\",\n    \"DeleteContainerRecipeRequest\": \"aws:DeleteContainerRecipeRequest\",\n    \"DeleteContainerRecipeResponse\": \"aws:DeleteContainerRecipeResponse\",\n    \"DeleteDistributionConfigurationRequest\": \"aws:DeleteDistributionConfigurationRequest\",\n    \"DeleteDistributionConfigurationResponse\": \"aws:DeleteDistributionConfigurationResponse\"\
  ,\n    \"DeleteImagePipelineRequest\": \"aws:DeleteImagePipelineRequest\",\n    \"DeleteImagePipelineResponse\": \"aws:DeleteImagePipelineResponse\",\n    \"DeleteImageRecipeRequest\": \"aws:DeleteImageRecipeRequest\",\n    \"DeleteImageRecipeResponse\": \"aws:DeleteImageRecipeResponse\",\n    \"DeleteImageRequest\": \"aws:DeleteImageRequest\",\n    \"DeleteImageResponse\": \"aws:DeleteImageResponse\",\n    \"DeleteInfrastructureConfigurationRequest\": \"aws:DeleteInfrastructureConfigurationRequest\",\n    \"DeleteInfrastructureConfigurationResponse\": \"aws:DeleteInfrastructureConfigurationResponse\",\n    \"Distribution\": \"aws:Distribution\",\n    \"DistributionConfiguration\": \"aws:DistributionConfiguration\",\n    \"filters\": {\n      \"@id\": \"pan:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"pan:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"pan:nextToken\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"s3Logs\": {\n      \"@id\": \"pan:s3Logs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchTemplateId\": {\n      \"@id\": \"pan:launchTemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"pan:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"setDefaultVersion\": {\n      \"@id\": \"pan:setDefaultVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"pan:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageRecipeArn\": {\n      \"@id\": \"pan:imageRecipeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerRecipeArn\": {\n      \"@id\": \"pan:containerRecipeArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributionConfigurationArn\": {\n      \"@id\": \"pan:distributionConfigurationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"infrastructureConfigurationArn\": {\n      \"@id\": \"pan:infrastructureConfigurationArn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"imageTestsConfiguration\": {\n      \"@id\": \"pan:imageTestsConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enhancedImageMetadataEnabled\": {\n      \"@id\": \"pan:enhancedImageMetadataEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"pan:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"pan:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageScanningConfiguration\": {\n      \"@id\": \"pan:imageScanningConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"pan:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": {\n      \"@id\": \"schema:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeDescription\":\
  \ {\n      \"@id\": \"pan:changeDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"pan:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"supportedOsVersions\": {\n      \"@id\": \"pan:supportedOsVersions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"pan:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"pan:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"pan:data\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"pan:kmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encrypted\": {\n      \"@id\": \"pan:encrypted\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateCreated\": {\n      \"@id\": \"pan:dateCreated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\"\
  : \"pan:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"obfuscate\": {\n      \"@id\": \"pan:obfuscate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountId\": {\n      \"@id\": \"pan:awsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageBuildVersionArn\": {\n      \"@id\": \"pan:imageBuildVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imagePipelineArn\": {\n      \"@id\": \"pan:imagePipelineArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstObservedAt\": {\n      \"@id\": \"pan:firstObservedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"pan:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  inspectorScore\": {\n      \"@id\": \"pan:inspectorScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectorScoreDetails\": {\n      \"@id\": \"pan:inspectorScoreDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageVulnerabilityDetails\": {\n      \"@id\": \"pan:packageVulnerabilityDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixAvailable\": {\n      \"@id\": \"pan:fixAvailable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilityId\": {\n      \"@id\": \"pan:vulnerabilityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerablePackages\": {\n      \"@id\": \"pan:vulnerablePackages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"pan:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvss\": {\n      \"@id\": \"pan:cvss\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedVulnerabilities\": {\n      \"@id\": \"pan:relatedVulnerabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceUrl\"\
  : {\n      \"@id\": \"pan:sourceUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorSeverity\": {\n      \"@id\": \"pan:vendorSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorCreatedAt\": {\n      \"@id\": \"pan:vendorCreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorUpdatedAt\": {\n      \"@id\": \"pan:vendorUpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceUrls\": {\n      \"@id\": \"pan:referenceUrls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scheduleExpression\": {\n      \"@id\": \"pan:scheduleExpression\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timezone\": {\n      \"@id\": \"pan:timezone\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pipelineExecutionStartCondition\": {\n      \"@id\": \"pan:pipelineExecutionStartCondition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deviceName\": {\n      \"@id\": \"pan:deviceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ebs\": {\n      \"@id\":\
  \ \"pan:ebs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"virtualName\": {\n      \"@id\": \"pan:virtualName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"noDevice\": {\n      \"@id\": \"pan:noDevice\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchTemplateName\": {\n      \"@id\": \"pan:launchTemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchTemplateVersion\": {\n      \"@id\": \"pan:launchTemplateVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"components\": {\n      \"@id\": \"pan:components\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentImage\": {\n      \"@id\": \"pan:parentImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blockDeviceMappings\": {\n      \"@id\": \"pan:blockDeviceMappings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workingDirectory\": {\n      \"@id\": \"pan:workingDirectory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalInstanceConfiguration\": {\n      \"@id\": \"pan:additionalInstanceConfiguration\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"pan:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"schedule\": {\n      \"@id\": \"pan:schedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateUpdated\": {\n      \"@id\": \"pan:dateUpdated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateLastRun\": {\n      \"@id\": \"pan:dateLastRun\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateNextRun\": {\n      \"@id\": \"pan:dateNextRun\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"pan:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageVersionList\": {\n      \"@id\": \"pan:imageVersionList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentVersionArn\": {\n      \"@id\": \"pan:componentVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"aggregationType\": {\n      \"@id\"\
  : \"pan:aggregationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responses\": {\n      \"@id\": \"pan:responses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"pan:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetResourceCount\": {\n      \"@id\": \"pan:targetResourceCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageScanningEnabled\": {\n      \"@id\": \"pan:imageScanningEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrConfiguration\": {\n      \"@id\": \"pan:ecrConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"pan:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imagePackageList\": {\n      \"@id\": \"pan:imagePackageList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"defaultValue\": {\n      \"@id\": \"pan:defaultValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributions\": {\n      \"@id\": \"pan:distributions\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"timeoutMinutes\": {\n      \"@id\": \"pan:timeoutMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adjustedCvss\": {\n      \"@id\": \"pan:adjustedCvss\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityCounts\": {\n      \"@id\": \"pan:severityCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLayerHash\": {\n      \"@id\": \"pan:sourceLayerHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"epoch\": {\n      \"@id\": \"pan:epoch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"release\": {\n      \"@id\": \"pan:release\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arch\": {\n      \"@id\": \"pan:arch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageManager\": {\n      \"@id\": \"pan:packageManager\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"pan:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixedInVersion\": {\n      \"@id\": \"pan:fixedInVersion\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"pan:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountAggregation\": {\n      \"@id\": \"pan:accountAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageAggregation\": {\n      \"@id\": \"pan:imageAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imagePipelineAggregation\": {\n      \"@id\": \"pan:imagePipelineAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilityIdAggregation\": {\n      \"@id\": \"pan:vulnerabilityIdAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentSummaryList\": {\n      \"@id\": \"pan:componentSummaryList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"semanticVersion\": {\n      \"@id\": \"pan:semanticVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflowBuildVersionArn\": {\n      \"@id\": \"pan:workflowBuildVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflowExecutionId\"\
  : {\n      \"@id\": \"pan:workflowExecutionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"pan:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalStepCount\": {\n      \"@id\": \"pan:totalStepCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalStepsSucceeded\": {\n      \"@id\": \"pan:totalStepsSucceeded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalStepsFailed\": {\n      \"@id\": \"pan:totalStepsFailed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalStepsSkipped\": {\n      \"@id\": \"pan:totalStepsSkipped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"pan:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"pan:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3BucketName\": {\n      \"@id\": \"pan:s3BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3KeyPrefix\": {\n      \"@id\": \"pan:s3KeyPrefix\",\n     \
  \ \"@type\": \"xsd:string\"\n    },\n    \"osVersion\": {\n      \"@id\": \"pan:osVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildType\": {\n      \"@id\": \"pan:buildType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageSource\": {\n      \"@id\": \"pan:imageSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageRecipeSummaryList\": {\n      \"@id\": \"pan:imageRecipeSummaryList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributionConfiguration\": {\n      \"@id\": \"pan:distributionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetAccountIds\": {\n      \"@id\": \"pan:targetAccountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amiTags\": {\n      \"@id\": \"pan:amiTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchPermission\": {\n      \"@id\": \"pan:launchPermission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageArn\": {\n      \"@id\": \"pan:imageArn\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"instanceTypes\": {\n      \"@id\": \"pan:instanceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceProfileName\": {\n      \"@id\": \"pan:instanceProfileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"pan:securityGroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetId\": {\n      \"@id\": \"pan:subnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logging\": {\n      \"@id\": \"pan:logging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPair\": {\n      \"@id\": \"pan:keyPair\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminateInstanceOnFailure\": {\n      \"@id\": \"pan:terminateInstanceOnFailure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snsTopicArn\": {\n      \"@id\": \"pan:snsTopicArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceTags\": {\n      \"@id\": \"pan:resourceTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceMetadataOptions\": {\n    \
  \  \"@id\": \"pan:instanceMetadataOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workflowExecutions\": {\n      \"@id\": \"pan:workflowExecutions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"region\": {\n      \"@id\": \"pan:region\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amiDistributionConfiguration\": {\n      \"@id\": \"pan:amiDistributionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerDistributionConfiguration\": {\n      \"@id\": \"pan:containerDistributionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"licenseConfigurationArns\": {\n      \"@id\": \"pan:licenseConfigurationArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchTemplateConfigurations\": {\n      \"@id\": \"pan:launchTemplateConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3ExportConfiguration\": {\n      \"@id\": \"pan:s3ExportConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fastLaunchConfigurations\": {\n\
  \      \"@id\": \"pan:fastLaunchConfigurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerRecipe\": {\n      \"@id\": \"pan:containerRecipe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"steps\": {\n      \"@id\": \"pan:steps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpTokens\": {\n      \"@id\": \"pan:httpTokens\",\n      \"@type\": \"xsd:string\"\n    },\n    \"httpPutResponseHopLimit\": {\n      \"@id\": \"pan:httpPutResponseHopLimit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleName\": {\n      \"@id\": \"pan:roleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"diskImageFormat\": {\n      \"@id\": \"pan:diskImageFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Bucket\": {\n      \"@id\": \"pan:s3Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Prefix\": {\n      \"@id\": \"pan:s3Prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"byName\": {\n      \"@id\": \"pan:byName\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"includeDeprecated\": {\n      \"@id\": \"pan:includeDeprecated\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageRecipe\": {\n      \"@id\": \"pan:imageRecipe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePipelineName\": {\n      \"@id\": \"pan:sourcePipelineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePipelineArn\": {\n      \"@id\": \"pan:sourcePipelineArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"infrastructureConfiguration\": {\n      \"@id\": \"pan:infrastructureConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputResources\": {\n      \"@id\": \"pan:outputResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanState\": {\n      \"@id\": \"pan:scanState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageTestsEnabled\": {\n      \"@id\": \"pan:imageTestsEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"component\": {\n      \"@id\": \"pan:component\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"recommendation\": {\n      \"@id\": \"pan:recommendation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerTags\": {\n      \"@id\": \"pan:containerTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetRepository\": {\n      \"@id\": \"pan:targetRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerType\": {\n      \"@id\": \"pan:containerType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceConfiguration\": {\n      \"@id\": \"pan:instanceConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dockerfileTemplateData\": {\n      \"@id\": \"pan:dockerfileTemplateData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stepExecutionId\": {\n      \"@id\": \"pan:stepExecutionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"pan:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rollbackStatus\": {\n      \"@id\": \"pan:rollbackStatus\",\n      \"@type\": \"xsd:string\"\n    },\n  \
  \  \"inputs\": {\n      \"@id\": \"pan:inputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"outputs\": {\n      \"@id\": \"pan:outputs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onFailure\": {\n      \"@id\": \"pan:onFailure\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutSeconds\": {\n      \"@id\": \"pan:timeoutSeconds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"pan:findings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentBuildVersionArn\": {\n      \"@id\": \"pan:componentBuildVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"infrastructureConfigurationSummaryList\": {\n      \"@id\": \"pan:infrastructureConfigurationSummaryList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snapshotConfiguration\": {\n      \"@id\": \"pan:snapshotConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxParallelLaunches\"\
  : {\n      \"@id\": \"pan:maxParallelLaunches\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchTemplate\": {\n      \"@id\": \"pan:launchTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"pan:filter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageVersionArn\": {\n      \"@id\": \"pan:imageVersionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amis\": {\n      \"@id\": \"pan:amis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containers\": {\n      \"@id\": \"pan:containers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userIds\": {\n      \"@id\": \"pan:userIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userGroups\": {\n      \"@id\": \"pan:userGroups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationArns\": {\n      \"@id\": \"pan:organizationArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationalUnitArns\": {\n      \"@id\": \"pan:organizationalUnitArns\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"imagePipelineList\": {\n      \"@id\": \"pan:imagePipelineList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"pan:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"containerRecipeSummaryList\": {\n      \"@id\": \"pan:containerRecipeSummaryList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentVersionList\": {\n      \"@id\": \"pan:componentVersionList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uninstallAfterBuild\": {\n      \"@id\": \"pan:uninstallAfterBuild\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"pan:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"distributionConfigurationSummaryList\": {\n      \"@id\": \"pan:distributionConfigurationSummaryList\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteOnTermination\": {\n      \"@id\": \"pan:deleteOnTermination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iops\": {\n      \"@id\": \"pan:iops\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"snapshotId\": {\n      \"@id\": \"pan:snapshotId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeSize\": {\n      \"@id\": \"pan:volumeSize\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-ec2-image-builder/refs/heads/main/json-ld/amazon-ec2-image-builder-context.jsonld
tags:
- Amazon Web Services
- Automation
- AWS
- Container Images
- EC2
- Image Building
- Virtual Machine Images
- JSON-LD
- Linked Data
- Semantic Web
---
