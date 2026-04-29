---
api_specs:
- filename: amazon-inspector-openapi-original.yml
  format: yaml
  label: AWS Amazon Inspector API
  slug: aws-inspector-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-inspector/refs/heads/main/openapi/amazon-inspector-openapi-original.yml
class_count: 102
classes:
- Account
- AccountAggregation
- AccountAggregationResponse
- AccountState
- AggregationRequest
- AggregationResponse
- Amazon Inspector Finding Definition
- AmiAggregation
- AmiAggregationResponse
- AssociateMemberRequest
- AssociateMemberResponse
- AtigData
- AutoEnable
- AwsEc2InstanceDetails
- AwsEcrContainerAggregation
- AwsEcrContainerAggregationResponse
- AwsEcrContainerImageDetails
- AwsLambdaFunctionDetails
- BatchGetAccountStatusRequest
- BatchGetAccountStatusResponse
- BatchGetCodeSnippetRequest
- BatchGetCodeSnippetResponse
- BatchGetFindingDetailsRequest
- BatchGetFindingDetailsResponse
- BatchGetFreeTrialInfoRequest
- BatchGetFreeTrialInfoResponse
- BatchGetMemberEc2DeepInspectionStatusRequest
- BatchGetMemberEc2DeepInspectionStatusResponse
- BatchUpdateMemberEc2DeepInspectionStatusRequest
- BatchUpdateMemberEc2DeepInspectionStatusResponse
- CancelFindingsReportRequest
- CancelFindingsReportResponse
- CancelSbomExportRequest
- CancelSbomExportResponse
- CisaData
- CodeFilePath
- CodeLine
- CodeSnippetError
- CodeSnippetResult
- CodeVulnerabilityDetails
- Counts
- CoverageDateFilter
- CoverageFilterCriteria
- CoverageMapFilter
- CoverageStringFilter
- CoveredResource
- CreateFilterRequest
- CreateFilterResponse
- CreateFindingsReportRequest
- CreateFindingsReportResponse
- CreateSbomExportRequest
- CreateSbomExportResponse
- Cvss2
- Cvss3
- CvssScore
- CvssScoreAdjustment
- CvssScoreDetails
- DateFilter
- DelegatedAdmin
- DelegatedAdminAccount
- DeleteFilterRequest
- DeleteFilterResponse
- DescribeOrganizationConfigurationRequest
- DescribeOrganizationConfigurationResponse
- Destination
- DisableDelegatedAdminAccountRequest
- DisableDelegatedAdminAccountResponse
- DisableResponse
- DisassociateMemberResponse
- Ec2InstanceAggregation
- Ec2InstanceAggregationResponse
- EnableDelegatedAdminAccountResponse
- EnableResponse
- FilterCriteria
- FindingTypeAggregation
- FindingTypeAggregationResponse
- GetConfigurationResponse
- GetDelegatedAdminAccountResponse
- GetEc2DeepInspectionConfigurationResponse
- GetEncryptionKeyResponse
- GetFindingsReportStatusResponse
- GetMemberResponse
- GetSbomExportResponse
- ImageLayerAggregation
- ImageLayerAggregationResponse
- LambdaFunctionAggregation
- LambdaFunctionAggregationResponse
- LambdaLayerAggregation
- LambdaLayerAggregationResponse
- LambdaVpcConfig
- ListAccountPermissionsResponse
- ListCoverageResponse
- ListCoverageStatisticsResponse
- ListDelegatedAdminAccountsResponse
- ListFiltersResponse
- ListFindingAggregationsResponse
- ListFindingsResponse
- ListMembersResponse
- ListTagsForResourceResponse
- ListUsageTotalsResponse
- description
- name
context_file: json-ld/amazon-inspector-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-inspector/refs/heads/main/json-ld/amazon-inspector-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Inspector from Amazon Inspector.
layout: jsonld
name: Amazon Inspector Context
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
  name: accountAggregation
  type: string
- container: ''
  name: accountId
  type: string
- container: ''
  name: accountIds
  type: string
- container: ''
  name: accounts
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: activateDeepInspection
  type: string
- container: ''
  name: adjustments
  type: string
- container: ''
  name: affectedImages
  type: string
- container: ''
  name: affectedInstances
  type: string
- container: ''
  name: aggregationType
  type: string
- container: ''
  name: all
  type: string
- container: ''
  name: ami
  type: string
- container: ''
  name: amiAggregation
  type: string
- container: ''
  name: amis
  type: string
- container: ''
  name: architecture
  type: string
- container: ''
  name: architectures
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: author
  type: string
- container: ''
  name: autoEnable
  type: string
- container: ''
  name: awsAccountId
  type: string
- container: ''
  name: awsEcrContainerAggregation
  type: string
- container: ''
  name: baseScore
  type: string
- container: ''
  name: bucketName
  type: string
- container: ''
  name: codeSha256
  type: string
- container: ''
  name: codeSnippet
  type: string
- container: ''
  name: codeSnippetResults
  type: string
- container: ''
  name: codeVulnerabilityDetectorName
  type: string
- container: ''
  name: codeVulnerabilityDetectorTags
  type: string
- container: ''
  name: codeVulnerabilityFilePath
  type: string
- container: ''
  name: comparison
  type: string
- container: ''
  name: componentId
  type: string
- container: ''
  name: componentType
  type: string
- container: ''
  name: content
  type: string
- container: ''
  name: count
  type: string
- container: ''
  name: countsByGroup
  type: string
- container: ''
  name: coveredResources
  type: string
- container: ''
  name: critical
  type: string
- container: ''
  name: cvssSource
  type: string
- container: ''
  name: cwes
  type: string
- container: ''
  name: dateAdded
  type: string
- container: ''
  name: dateDue
  type: string
- container: ''
  name: delegatedAdmin
  type: string
- container: ''
  name: delegatedAdminAccountId
  type: string
- container: ''
  name: delegatedAdminAccounts
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: detectorId
  type: string
- container: ''
  name: detectorName
  type: string
- container: ''
  name: detectorTags
  type: string
- container: ''
  name: ec2
  type: string
- container: ''
  name: ec2InstanceAggregation
  type: string
- container: ''
  name: ec2InstanceImageId
  type: string
- container: ''
  name: ec2InstanceSubnetId
  type: string
- container: ''
  name: ec2InstanceTags
  type: string
- container: ''
  name: ec2InstanceVpcId
  type: string
- container: ''
  name: ecr
  type: string
- container: ''
  name: ecrConfiguration
  type: string
- container: ''
  name: ecrImage
  type: string
- container: ''
  name: ecrImageArchitecture
  type: string
- container: ''
  name: ecrImageHash
  type: string
- container: ''
  name: ecrImagePushedAt
  type: string
- container: ''
  name: ecrImageRegistry
  type: string
- container: ''
  name: ecrImageRepositoryName
  type: string
- container: ''
  name: ecrImageTags
  type: string
- container: ''
  name: ecrRepository
  type: string
- container: ''
  name: ecrRepositoryName
  type: string
- container: ''
  name: endInclusive
  type: string
- container: ''
  name: endLine
  type: string
- container: ''
  name: epssScore
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: executionRoleArn
  type: string
- container: ''
  name: exploitAvailable
  type: string
- container: ''
  name: failedAccountIds
  type: string
- container: ''
  name: failedAccounts
  type: string
- container: ''
  name: fileName
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: filterCriteria
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: findingArn
  type: string
- container: ''
  name: findingArns
  type: string
- container: ''
  name: findingDetails
  type: string
- container: ''
  name: findingStatus
  type: string
- container: ''
  name: findingType
  type: string
- container: ''
  name: findingTypeAggregation
  type: string
- container: ''
  name: findings
  type: string
- container: ''
  name: firstObservedAt
  type: dateTime
- container: ''
  name: firstSeen
  type: string
- container: ''
  name: fixAvailable
  type: string
- container: ''
  name: format
  type: string
- container: ''
  name: functionName
  type: string
- container: ''
  name: functionNames
  type: string
- container: ''
  name: functionTags
  type: string
- container: ''
  name: groupKey
  type: string
- container: ''
  name: high
  type: string
- container: ''
  name: iamInstanceProfileArn
  type: string
- container: ''
  name: imageHash
  type: string
- container: ''
  name: imageId
  type: string
- container: ''
  name: imageLayerAggregation
  type: string
- container: ''
  name: imageSha
  type: string
- container: ''
  name: imageShas
  type: string
- container: ''
  name: imageTags
  type: string
- container: ''
  name: inspectorScore
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: instanceIds
  type: string
- container: ''
  name: instanceTags
  type: string
- container: ''
  name: ipV4Addresses
  type: string
- container: ''
  name: ipV6Addresses
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: keyName
  type: string
- container: ''
  name: keyPrefix
  type: string
- container: ''
  name: kmsKeyArn
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: lambda
  type: string
- container: ''
  name: lambdaCode
  type: string
- container: ''
  name: lambdaFunction
  type: string
- container: ''
  name: lambdaFunctionAggregation
  type: string
- container: ''
  name: lambdaFunctionExecutionRoleArn
  type: string
- container: ''
  name: lambdaFunctionLastModifiedAt
  type: string
- container: ''
  name: lambdaFunctionLayers
  type: string
- container: ''
  name: lambdaFunctionName
  type: string
- container: ''
  name: lambdaFunctionRuntime
  type: string
- container: ''
  name: lambdaFunctionTags
  type: string
- container: ''
  name: lambdaLayerAggregation
  type: string
- container: ''
  name: lambdaTags
  type: string
- container: ''
  name: lastModifiedAt
  type: string
- container: ''
  name: lastObservedAt
  type: dateTime
- container: ''
  name: lastScannedAt
  type: string
- container: ''
  name: lastSeen
  type: string
- container: ''
  name: launchedAt
  type: string
- container: ''
  name: layerArn
  type: string
- container: ''
  name: layerArns
  type: string
- container: ''
  name: layerHash
  type: string
- container: ''
  name: layerHashes
  type: string
- container: ''
  name: layers
  type: string
- container: ''
  name: lineNumber
  type: string
- container: ''
  name: maxAccountLimitReached
  type: string
- container: ''
  name: medium
  type: string
- container: ''
  name: member
  type: string
- container: ''
  name: members
  type: string
- container: ''
  name: metric
  type: string
- container: ''
  name: networkFindings
  type: string
- container: ''
  name: networkProtocol
  type: string
- container: ''
  name: networkReachabilityDetails
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: operatingSystem
  type: string
- container: ''
  name: operatingSystems
  type: string
- container: ''
  name: orgPackagePaths
  type: string
- container: ''
  name: packageAggregation
  type: string
- container: ''
  name: packageName
  type: string
- container: ''
  name: packageNames
  type: string
- container: ''
  name: packagePaths
  type: string
- container: ''
  name: packageType
  type: string
- container: ''
  name: packageVulnerabilityDetails
  type: string
- container: ''
  name: permissions
  type: string
- container: ''
  name: platform
  type: string
- container: ''
  name: portRange
  type: string
- container: ''
  name: pushedAt
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: referenceUrls
  type: string
- container: ''
  name: registry
  type: string
- container: ''
  name: relatedVulnerabilities
  type: string
- container: ''
  name: relationshipStatus
  type: string
- container: ''
  name: remediation
  type: string
- container: ''
  name: reportFormat
  type: string
- container: ''
  name: reportId
  type: string
- container: ''
  name: repositories
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: repositoryAggregation
  type: string
- container: ''
  name: repositoryName
  type: string
- container: ''
  name: resourceFilterCriteria
  type: string
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceIds
  type: string
- container: ''
  name: resourceMetadata
  type: string
- container: ''
  name: resourceState
  type: string
- container: ''
  name: resourceStatus
  type: string
- container: ''
  name: resourceTags
  type: string
- container: ''
  name: resourceType
  type: string
- container: set
  name: resources
  type: string
- container: ''
  name: responses
  type: string
- container: ''
  name: ruleId
  type: string
- container: ''
  name: runtime
  type: string
- container: ''
  name: runtimes
  type: string
- container: ''
  name: s3Destination
  type: string
- container: ''
  name: scanStatus
  type: string
- container: ''
  name: scanStatusCode
  type: string
- container: ''
  name: scanStatusReason
  type: string
- container: ''
  name: scanType
  type: string
- container: ''
  name: score
  type: string
- container: ''
  name: scoreSource
  type: string
- container: ''
  name: scoringVector
  type: string
- container: ''
  name: securityGroupIds
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: severityCounts
  type: string
- container: ''
  name: sortBy
  type: string
- container: ''
  name: sortOrder
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourceLambdaLayerArn
  type: string
- container: ''
  name: startInclusive
  type: string
- container: ''
  name: startLine
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusCode
  type: string
- container: ''
  name: subnetId
  type: string
- container: ''
  name: subnetIds
  type: string
- container: ''
  name: suggestedFixes
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: targets
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: titleAggregation
  type: string
- container: ''
  name: titles
  type: string
- container: ''
  name: totalCounts
  type: string
- container: ''
  name: totals
  type: string
- container: ''
  name: ttps
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: value
  type: string
- container: ''
  name: vendorSeverity
  type: string
- container: ''
  name: version
  type: string
- container: ''
  name: vpcConfig
  type: string
- container: ''
  name: vpcId
  type: string
- container: ''
  name: vulnerabilities
  type: string
- container: ''
  name: vulnerabilityId
  type: string
- container: ''
  name: vulnerabilityIds
  type: string
- container: ''
  name: vulnerabilitySource
  type: string
- container: ''
  name: vulnerablePackages
  type: string
property_count: 226
provider_name: Amazon Inspector
provider_slug: amazon-inspector
slug: amazon-inspector-context
source_filename: amazon-inspector-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"Account\": \"amzn:Account\",\n    \"AccountAggregation\": \"amzn:AccountAggregation\",\n    \"AccountAggregationResponse\": \"amzn:AccountAggregationResponse\",\n    \"AccountState\": \"amzn:AccountState\",\n    \"AggregationRequest\": \"amzn:AggregationRequest\",\n    \"AggregationResponse\": \"amzn:AggregationResponse\",\n    \"Amazon Inspector Finding Definition\": \"amzn:Amazon Inspector Finding Definition\",\n    \"AmiAggregation\": \"amzn:AmiAggregation\",\n    \"AmiAggregationResponse\": \"amzn:AmiAggregationResponse\",\n    \"AssociateMemberRequest\": \"amzn:AssociateMemberRequest\",\n    \"AssociateMemberResponse\": \"amzn:AssociateMemberResponse\",\n    \"AtigData\": \"amzn:AtigData\",\n    \"AutoEnable\": \"amzn:AutoEnable\"\
  ,\n    \"AwsEc2InstanceDetails\": \"amzn:AwsEc2InstanceDetails\",\n    \"AwsEcrContainerAggregation\": \"amzn:AwsEcrContainerAggregation\",\n    \"AwsEcrContainerAggregationResponse\": \"amzn:AwsEcrContainerAggregationResponse\",\n    \"AwsEcrContainerImageDetails\": \"amzn:AwsEcrContainerImageDetails\",\n    \"AwsLambdaFunctionDetails\": \"amzn:AwsLambdaFunctionDetails\",\n    \"BatchGetAccountStatusRequest\": \"amzn:BatchGetAccountStatusRequest\",\n    \"BatchGetAccountStatusResponse\": \"amzn:BatchGetAccountStatusResponse\",\n    \"BatchGetCodeSnippetRequest\": \"amzn:BatchGetCodeSnippetRequest\",\n    \"BatchGetCodeSnippetResponse\": \"amzn:BatchGetCodeSnippetResponse\",\n    \"BatchGetFindingDetailsRequest\": \"amzn:BatchGetFindingDetailsRequest\",\n    \"BatchGetFindingDetailsResponse\": \"amzn:BatchGetFindingDetailsResponse\",\n    \"BatchGetFreeTrialInfoRequest\": \"amzn:BatchGetFreeTrialInfoRequest\",\n    \"BatchGetFreeTrialInfoResponse\": \"amzn:BatchGetFreeTrialInfoResponse\"\
  ,\n    \"BatchGetMemberEc2DeepInspectionStatusRequest\": \"amzn:BatchGetMemberEc2DeepInspectionStatusRequest\",\n    \"BatchGetMemberEc2DeepInspectionStatusResponse\": \"amzn:BatchGetMemberEc2DeepInspectionStatusResponse\",\n    \"BatchUpdateMemberEc2DeepInspectionStatusRequest\": \"amzn:BatchUpdateMemberEc2DeepInspectionStatusRequest\",\n    \"BatchUpdateMemberEc2DeepInspectionStatusResponse\": \"amzn:BatchUpdateMemberEc2DeepInspectionStatusResponse\",\n    \"CancelFindingsReportRequest\": \"amzn:CancelFindingsReportRequest\",\n    \"CancelFindingsReportResponse\": \"amzn:CancelFindingsReportResponse\",\n    \"CancelSbomExportRequest\": \"amzn:CancelSbomExportRequest\",\n    \"CancelSbomExportResponse\": \"amzn:CancelSbomExportResponse\",\n    \"CisaData\": \"amzn:CisaData\",\n    \"CodeFilePath\": \"amzn:CodeFilePath\",\n    \"CodeLine\": \"amzn:CodeLine\",\n    \"CodeSnippetError\": \"amzn:CodeSnippetError\",\n    \"CodeSnippetResult\": \"amzn:CodeSnippetResult\",\n    \"CodeVulnerabilityDetails\"\
  : \"amzn:CodeVulnerabilityDetails\",\n    \"Counts\": \"amzn:Counts\",\n    \"CoverageDateFilter\": \"amzn:CoverageDateFilter\",\n    \"CoverageFilterCriteria\": \"amzn:CoverageFilterCriteria\",\n    \"CoverageMapFilter\": \"amzn:CoverageMapFilter\",\n    \"CoverageStringFilter\": \"amzn:CoverageStringFilter\",\n    \"CoveredResource\": \"amzn:CoveredResource\",\n    \"CreateFilterRequest\": \"amzn:CreateFilterRequest\",\n    \"CreateFilterResponse\": \"amzn:CreateFilterResponse\",\n    \"CreateFindingsReportRequest\": \"amzn:CreateFindingsReportRequest\",\n    \"CreateFindingsReportResponse\": \"amzn:CreateFindingsReportResponse\",\n    \"CreateSbomExportRequest\": \"amzn:CreateSbomExportRequest\",\n    \"CreateSbomExportResponse\": \"amzn:CreateSbomExportResponse\",\n    \"Cvss2\": \"amzn:Cvss2\",\n    \"Cvss3\": \"amzn:Cvss3\",\n    \"CvssScore\": \"amzn:CvssScore\",\n    \"CvssScoreAdjustment\": \"amzn:CvssScoreAdjustment\",\n    \"CvssScoreDetails\": \"amzn:CvssScoreDetails\",\n \
  \   \"DateFilter\": \"amzn:DateFilter\",\n    \"DelegatedAdmin\": \"amzn:DelegatedAdmin\",\n    \"DelegatedAdminAccount\": \"amzn:DelegatedAdminAccount\",\n    \"DeleteFilterRequest\": \"amzn:DeleteFilterRequest\",\n    \"DeleteFilterResponse\": \"amzn:DeleteFilterResponse\",\n    \"DescribeOrganizationConfigurationRequest\": \"amzn:DescribeOrganizationConfigurationRequest\",\n    \"DescribeOrganizationConfigurationResponse\": \"amzn:DescribeOrganizationConfigurationResponse\",\n    \"Destination\": \"amzn:Destination\",\n    \"DisableDelegatedAdminAccountRequest\": \"amzn:DisableDelegatedAdminAccountRequest\",\n    \"DisableDelegatedAdminAccountResponse\": \"amzn:DisableDelegatedAdminAccountResponse\",\n    \"DisableResponse\": \"amzn:DisableResponse\",\n    \"DisassociateMemberResponse\": \"amzn:DisassociateMemberResponse\",\n    \"Ec2InstanceAggregation\": \"amzn:Ec2InstanceAggregation\",\n    \"Ec2InstanceAggregationResponse\": \"amzn:Ec2InstanceAggregationResponse\",\n    \"EnableDelegatedAdminAccountResponse\"\
  : \"amzn:EnableDelegatedAdminAccountResponse\",\n    \"EnableResponse\": \"amzn:EnableResponse\",\n    \"FilterCriteria\": \"amzn:FilterCriteria\",\n    \"FindingTypeAggregation\": \"amzn:FindingTypeAggregation\",\n    \"FindingTypeAggregationResponse\": \"amzn:FindingTypeAggregationResponse\",\n    \"GetConfigurationResponse\": \"amzn:GetConfigurationResponse\",\n    \"GetDelegatedAdminAccountResponse\": \"amzn:GetDelegatedAdminAccountResponse\",\n    \"GetEc2DeepInspectionConfigurationResponse\": \"amzn:GetEc2DeepInspectionConfigurationResponse\",\n    \"GetEncryptionKeyResponse\": \"amzn:GetEncryptionKeyResponse\",\n    \"GetFindingsReportStatusResponse\": \"amzn:GetFindingsReportStatusResponse\",\n    \"GetMemberResponse\": \"amzn:GetMemberResponse\",\n    \"GetSbomExportResponse\": \"amzn:GetSbomExportResponse\",\n    \"ImageLayerAggregation\": \"amzn:ImageLayerAggregation\",\n    \"ImageLayerAggregationResponse\": \"amzn:ImageLayerAggregationResponse\",\n    \"LambdaFunctionAggregation\"\
  : \"amzn:LambdaFunctionAggregation\",\n    \"LambdaFunctionAggregationResponse\": \"amzn:LambdaFunctionAggregationResponse\",\n    \"LambdaLayerAggregation\": \"amzn:LambdaLayerAggregation\",\n    \"LambdaLayerAggregationResponse\": \"amzn:LambdaLayerAggregationResponse\",\n    \"LambdaVpcConfig\": \"amzn:LambdaVpcConfig\",\n    \"ListAccountPermissionsResponse\": \"amzn:ListAccountPermissionsResponse\",\n    \"ListCoverageResponse\": \"amzn:ListCoverageResponse\",\n    \"ListCoverageStatisticsResponse\": \"amzn:ListCoverageStatisticsResponse\",\n    \"ListDelegatedAdminAccountsResponse\": \"amzn:ListDelegatedAdminAccountsResponse\",\n    \"ListFiltersResponse\": \"amzn:ListFiltersResponse\",\n    \"ListFindingAggregationsResponse\": \"amzn:ListFindingAggregationsResponse\",\n    \"ListFindingsResponse\": \"amzn:ListFindingsResponse\",\n    \"ListMembersResponse\": \"amzn:ListMembersResponse\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"ListUsageTotalsResponse\"\
  : \"amzn:ListUsageTotalsResponse\",\n    \"accountAggregation\": {\n      \"@id\": \"amzn:accountAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountId\": {\n      \"@id\": \"amzn:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIds\": {\n      \"@id\": \"amzn:accountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accounts\": {\n      \"@id\": \"amzn:accounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activateDeepInspection\": {\n      \"@id\": \"amzn:activateDeepInspection\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adjustments\": {\n      \"@id\": \"amzn:adjustments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedImages\": {\n      \"@id\": \"amzn:affectedImages\",\n      \"@type\": \"xsd:string\"\n    },\n    \"affectedInstances\": {\n      \"@id\": \"amzn:affectedInstances\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"aggregationType\": {\n      \"@id\": \"amzn:aggregationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"all\": {\n      \"@id\": \"amzn:all\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ami\": {\n      \"@id\": \"amzn:ami\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amiAggregation\": {\n      \"@id\": \"amzn:amiAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amis\": {\n      \"@id\": \"amzn:amis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architecture\": {\n      \"@id\": \"amzn:architecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"architectures\": {\n      \"@id\": \"amzn:architectures\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"author\": {\n      \"@id\": \"amzn:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoEnable\": {\n      \"@id\": \"amzn:autoEnable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountId\": {\n\
  \      \"@id\": \"amzn:awsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsEcrContainerAggregation\": {\n      \"@id\": \"amzn:awsEcrContainerAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"baseScore\": {\n      \"@id\": \"amzn:baseScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketName\": {\n      \"@id\": \"amzn:bucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeSha256\": {\n      \"@id\": \"amzn:codeSha256\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeSnippet\": {\n      \"@id\": \"amzn:codeSnippet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeSnippetResults\": {\n      \"@id\": \"amzn:codeSnippetResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeVulnerabilityDetectorName\": {\n      \"@id\": \"amzn:codeVulnerabilityDetectorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeVulnerabilityDetectorTags\": {\n      \"@id\": \"amzn:codeVulnerabilityDetectorTags\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"codeVulnerabilityFilePath\": {\n      \"@id\": \"amzn:codeVulnerabilityFilePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comparison\": {\n      \"@id\": \"amzn:comparison\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentId\": {\n      \"@id\": \"amzn:componentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"componentType\": {\n      \"@id\": \"amzn:componentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"content\": {\n      \"@id\": \"amzn:content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"amzn:count\",\n      \"@type\": \"xsd:string\"\n    },\n    \"countsByGroup\": {\n      \"@id\": \"amzn:countsByGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coveredResources\": {\n      \"@id\": \"amzn:coveredResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"critical\": {\n      \"@id\": \"amzn:critical\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cvssSource\": {\n      \"@id\": \"amzn:cvssSource\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"cwes\": {\n      \"@id\": \"amzn:cwes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateAdded\": {\n      \"@id\": \"amzn:dateAdded\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dateDue\": {\n      \"@id\": \"amzn:dateDue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delegatedAdmin\": {\n      \"@id\": \"amzn:delegatedAdmin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delegatedAdminAccountId\": {\n      \"@id\": \"amzn:delegatedAdminAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"delegatedAdminAccounts\": {\n      \"@id\": \"amzn:delegatedAdminAccounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"destination\": {\n      \"@id\": \"amzn:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorId\": {\n      \"@id\": \"amzn:detectorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorName\": {\n      \"@id\": \"amzn:detectorName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"detectorTags\": {\n      \"@id\": \"amzn:detectorTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2\": {\n      \"@id\": \"amzn:ec2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2InstanceAggregation\": {\n      \"@id\": \"amzn:ec2InstanceAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2InstanceImageId\": {\n      \"@id\": \"amzn:ec2InstanceImageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2InstanceSubnetId\": {\n      \"@id\": \"amzn:ec2InstanceSubnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2InstanceTags\": {\n      \"@id\": \"amzn:ec2InstanceTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ec2InstanceVpcId\": {\n      \"@id\": \"amzn:ec2InstanceVpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecr\": {\n      \"@id\": \"amzn:ecr\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrConfiguration\": {\n      \"@id\": \"amzn:ecrConfiguration\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"ecrImage\": {\n      \"@id\": \"amzn:ecrImage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImageArchitecture\": {\n      \"@id\": \"amzn:ecrImageArchitecture\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImageHash\": {\n      \"@id\": \"amzn:ecrImageHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImagePushedAt\": {\n      \"@id\": \"amzn:ecrImagePushedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImageRegistry\": {\n      \"@id\": \"amzn:ecrImageRegistry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImageRepositoryName\": {\n      \"@id\": \"amzn:ecrImageRepositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrImageTags\": {\n      \"@id\": \"amzn:ecrImageTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrRepository\": {\n      \"@id\": \"amzn:ecrRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrRepositoryName\": {\n      \"@id\": \"amzn:ecrRepositoryName\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"endInclusive\": {\n      \"@id\": \"amzn:endInclusive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endLine\": {\n      \"@id\": \"amzn:endLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"epssScore\": {\n      \"@id\": \"amzn:epssScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amzn:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amzn:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"amzn:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executionRoleArn\": {\n      \"@id\": \"amzn:executionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exploitAvailable\": {\n      \"@id\": \"amzn:exploitAvailable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedAccountIds\": {\n      \"@id\": \"amzn:failedAccountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failedAccounts\": {\n      \"@id\": \"\
  amzn:failedAccounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileName\": {\n      \"@id\": \"amzn:fileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"amzn:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filterCriteria\": {\n      \"@id\": \"amzn:filterCriteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"amzn:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingArn\": {\n      \"@id\": \"amzn:findingArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingArns\": {\n      \"@id\": \"amzn:findingArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingDetails\": {\n      \"@id\": \"amzn:findingDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingStatus\": {\n      \"@id\": \"amzn:findingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingType\": {\n      \"@id\": \"amzn:findingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingTypeAggregation\"\
  : {\n      \"@id\": \"amzn:findingTypeAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"amzn:findings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstObservedAt\": {\n      \"@id\": \"amzn:firstObservedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"amzn:firstSeen\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fixAvailable\": {\n      \"@id\": \"amzn:fixAvailable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"format\": {\n      \"@id\": \"amzn:format\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionName\": {\n      \"@id\": \"amzn:functionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionNames\": {\n      \"@id\": \"amzn:functionNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"functionTags\": {\n      \"@id\": \"amzn:functionTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupKey\": {\n      \"@id\": \"amzn:groupKey\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"high\": {\n      \"@id\": \"amzn:high\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamInstanceProfileArn\": {\n      \"@id\": \"amzn:iamInstanceProfileArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageHash\": {\n      \"@id\": \"amzn:imageHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageId\": {\n      \"@id\": \"amzn:imageId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageLayerAggregation\": {\n      \"@id\": \"amzn:imageLayerAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageSha\": {\n      \"@id\": \"amzn:imageSha\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageShas\": {\n      \"@id\": \"amzn:imageShas\",\n      \"@type\": \"xsd:string\"\n    },\n    \"imageTags\": {\n      \"@id\": \"amzn:imageTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inspectorScore\": {\n      \"@id\": \"amzn:inspectorScore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"amzn:instanceId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceIds\": {\n      \"@id\": \"amzn:instanceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceTags\": {\n      \"@id\": \"amzn:instanceTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipV4Addresses\": {\n      \"@id\": \"amzn:ipV4Addresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipV6Addresses\": {\n      \"@id\": \"amzn:ipV6Addresses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyName\": {\n      \"@id\": \"amzn:keyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPrefix\": {\n      \"@id\": \"amzn:keyPrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"amzn:kmsKeyArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"amzn:kmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambda\": {\n      \"@id\": \"amzn:lambda\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"lambdaCode\": {\n      \"@id\": \"amzn:lambdaCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunction\": {\n      \"@id\": \"amzn:lambdaFunction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionAggregation\": {\n      \"@id\": \"amzn:lambdaFunctionAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionExecutionRoleArn\": {\n      \"@id\": \"amzn:lambdaFunctionExecutionRoleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionLastModifiedAt\": {\n      \"@id\": \"amzn:lambdaFunctionLastModifiedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionLayers\": {\n      \"@id\": \"amzn:lambdaFunctionLayers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionName\": {\n      \"@id\": \"amzn:lambdaFunctionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaFunctionRuntime\": {\n      \"@id\": \"amzn:lambdaFunctionRuntime\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"lambdaFunctionTags\": {\n      \"@id\": \"amzn:lambdaFunctionTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaLayerAggregation\": {\n      \"@id\": \"amzn:lambdaLayerAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lambdaTags\": {\n      \"@id\": \"amzn:lambdaTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedAt\": {\n      \"@id\": \"amzn:lastModifiedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastObservedAt\": {\n      \"@id\": \"amzn:lastObservedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScannedAt\": {\n      \"@id\": \"amzn:lastScannedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastSeen\": {\n      \"@id\": \"amzn:lastSeen\",\n      \"@type\": \"xsd:string\"\n    },\n    \"launchedAt\": {\n      \"@id\": \"amzn:launchedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layerArn\": {\n      \"@id\": \"amzn:layerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layerArns\": {\n  \
  \    \"@id\": \"amzn:layerArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layerHash\": {\n      \"@id\": \"amzn:layerHash\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layerHashes\": {\n      \"@id\": \"amzn:layerHashes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"layers\": {\n      \"@id\": \"amzn:layers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lineNumber\": {\n      \"@id\": \"amzn:lineNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAccountLimitReached\": {\n      \"@id\": \"amzn:maxAccountLimitReached\",\n      \"@type\": \"xsd:string\"\n    },\n    \"medium\": {\n      \"@id\": \"amzn:medium\",\n      \"@type\": \"xsd:string\"\n    },\n    \"member\": {\n      \"@id\": \"amzn:member\",\n      \"@type\": \"xsd:string\"\n    },\n    \"members\": {\n      \"@id\": \"amzn:members\",\n      \"@type\": \"xsd:string\"\n    },\n    \"metric\": {\n      \"@id\": \"amzn:metric\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\"\
  ,\n    \"networkFindings\": {\n      \"@id\": \"amzn:networkFindings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkProtocol\": {\n      \"@id\": \"amzn:networkProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkReachabilityDetails\": {\n      \"@id\": \"amzn:networkReachabilityDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystem\": {\n      \"@id\": \"amzn:operatingSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operatingSystems\": {\n      \"@id\": \"amzn:operatingSystems\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orgPackagePaths\": {\n      \"@id\": \"amzn:orgPackagePaths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageAggregation\": {\n      \"@id\": \"amzn:packageAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageName\": {\n      \"@id\": \"amzn:packageName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"packageNames\": {\n      \"@id\": \"amzn:packageNames\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packagePaths\": {\n      \"@id\": \"amzn:packagePaths\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageType\": {\n      \"@id\": \"amzn:packageType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageVulnerabilityDetails\": {\n      \"@id\": \"amzn:packageVulnerabilityDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permissions\": {\n      \"@id\": \"amzn:permissions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"platform\": {\n      \"@id\": \"amzn:platform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"portRange\": {\n      \"@id\": \"amzn:portRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pushedAt\": {\n      \"@id\": \"amzn:pushedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"amzn:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"referenceUrls\": {\n      \"@id\": \"amzn:referenceUrls\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"registry\": {\n      \"@id\": \"amzn:registry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relatedVulnerabilities\": {\n      \"@id\": \"amzn:relatedVulnerabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"relationshipStatus\": {\n      \"@id\": \"amzn:relationshipStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"amzn:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportFormat\": {\n      \"@id\": \"amzn:reportFormat\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reportId\": {\n      \"@id\": \"amzn:reportId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"amzn:repositories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"amzn:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryAggregation\": {\n      \"@id\": \"amzn:repositoryAggregation\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"repositoryName\": {\n      \"@id\": \"amzn:repositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceFilterCriteria\": {\n      \"@id\": \"amzn:resourceFilterCriteria\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceId\": {\n      \"@id\": \"amzn:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceIds\": {\n      \"@id\": \"amzn:resourceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceMetadata\": {\n      \"@id\": \"amzn:resourceMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceState\": {\n      \"@id\": \"amzn:resourceState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceStatus\": {\n      \"@id\": \"amzn:resourceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceTags\": {\n      \"@id\": \"amzn:resourceTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"amzn:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\"\
  : {\n      \"@id\": \"amzn:resources\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responses\": {\n      \"@id\": \"amzn:responses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleId\": {\n      \"@id\": \"amzn:ruleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runtime\": {\n      \"@id\": \"amzn:runtime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runtimes\": {\n      \"@id\": \"amzn:runtimes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Destination\": {\n      \"@id\": \"amzn:s3Destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanStatus\": {\n      \"@id\": \"amzn:scanStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanStatusCode\": {\n      \"@id\": \"amzn:scanStatusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanStatusReason\": {\n      \"@id\": \"amzn:scanStatusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scanType\": {\n      \"@id\": \"amzn:scanType\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"score\": {\n      \"@id\": \"amzn:score\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scoreSource\": {\n      \"@id\": \"amzn:scoreSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"scoringVector\": {\n      \"@id\": \"amzn:scoringVector\",\n      \"@type\": \"xsd:string\"\n    },\n    \"securityGroupIds\": {\n      \"@id\": \"amzn:securityGroupIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"amzn:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityCounts\": {\n      \"@id\": \"amzn:severityCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortBy\": {\n      \"@id\": \"amzn:sortBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sortOrder\": {\n      \"@id\": \"amzn:sortOrder\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"amzn:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceLambdaLayerArn\": {\n      \"@id\": \"amzn:sourceLambdaLayerArn\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"startInclusive\": {\n      \"@id\": \"amzn:startInclusive\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startLine\": {\n      \"@id\": \"amzn:startLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"amzn:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusCode\": {\n      \"@id\": \"amzn:statusCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetId\": {\n      \"@id\": \"amzn:subnetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subnetIds\": {\n      \"@id\": \"amzn:subnetIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suggestedFixes\": {\n      \"@id\": \"amzn:suggestedFixes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targets\": {\n      \"@id\": \"amzn:targets\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"amzn:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"titleAggregation\": {\n      \"@id\": \"amzn:titleAggregation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"titles\": {\n      \"@id\": \"amzn:titles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalCounts\": {\n      \"@id\": \"amzn:totalCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totals\": {\n      \"@id\": \"amzn:totals\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ttps\": {\n      \"@id\": \"amzn:ttps\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"amzn:updatedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vendorSeverity\": {\n      \"@id\": \"amzn:vendorSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n \
  \   \"version\": {\n      \"@id\": \"amzn:version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcConfig\": {\n      \"@id\": \"amzn:vpcConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcId\": {\n      \"@id\": \"amzn:vpcId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilities\": {\n      \"@id\": \"amzn:vulnerabilities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilityId\": {\n      \"@id\": \"amzn:vulnerabilityId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilityIds\": {\n      \"@id\": \"amzn:vulnerabilityIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerabilitySource\": {\n      \"@id\": \"amzn:vulnerabilitySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vulnerablePackages\": {\n      \"@id\": \"amzn:vulnerablePackages\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-inspector/refs/heads/main/json-ld/amazon-inspector-context.jsonld
tags:
- AWS
- Compliance
- Container Security
- EC2
- Lambda
- Security
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
