---
class_count: 116
classes:
- AccessPreview
- AccessPreviewFinding
- AccessPreviewStatusReason
- AccessPreviewSummary
- AclGrantee
- AnalyzedResource
- AnalyzedResourceSummary
- AnalyzerSummary
- ApplyArchiveRuleRequest
- ArchiveRuleSummary
- CancelPolicyGenerationRequest
- CancelPolicyGenerationResponse
- CloudTrailDetails
- CloudTrailProperties
- ConditionKeyMap
- Configuration
- ConfigurationsMap
- CreateAccessPreviewRequest
- CreateAccessPreviewResponse
- CreateAnalyzerRequest
- CreateAnalyzerResponse
- CreateArchiveRuleRequest
- Criterion
- DeleteAnalyzerRequest
- DeleteArchiveRuleRequest
- EbsSnapshotConfiguration
- EcrRepositoryConfiguration
- EfsFileSystemConfiguration
- FilterCriteriaMap
- Finding
- FindingSource
- FindingSourceDetail
- FindingSummary
- GeneratedPolicy
- GeneratedPolicyProperties
- GeneratedPolicyResult
- GetAccessPreviewRequest
- GetAccessPreviewResponse
- GetAnalyzedResourceRequest
- GetAnalyzedResourceResponse
- GetAnalyzerRequest
- GetAnalyzerResponse
- GetArchiveRuleRequest
- GetArchiveRuleResponse
- GetFindingRequest
- GetFindingResponse
- GetGeneratedPolicyRequest
- GetGeneratedPolicyResponse
- IamRoleConfiguration
- InlineArchiveRule
- InternetConfiguration
- JobDetails
- JobError
- KmsConstraintsMap
- KmsGrantConfiguration
- KmsGrantConstraints
- KmsKeyConfiguration
- KmsKeyPoliciesMap
- ListAccessPreviewFindingsRequest
- ListAccessPreviewFindingsResponse
- ListAccessPreviewsRequest
- ListAccessPreviewsResponse
- ListAnalyzedResourcesRequest
- ListAnalyzedResourcesResponse
- ListAnalyzersRequest
- ListAnalyzersResponse
- ListArchiveRulesRequest
- ListArchiveRulesResponse
- ListFindingsRequest
- ListFindingsResponse
- ListPolicyGenerationsRequest
- ListPolicyGenerationsResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- Location
- NetworkOriginConfiguration
- PathElement
- PolicyGeneration
- PolicyGenerationDetails
- Position
- PrincipalMap
- RdsDbClusterSnapshotAttributeValue
- RdsDbClusterSnapshotAttributesMap
- RdsDbClusterSnapshotConfiguration
- RdsDbSnapshotAttributeValue
- RdsDbSnapshotAttributesMap
- RdsDbSnapshotConfiguration
- S3AccessPointConfiguration
- S3AccessPointConfigurationsMap
- S3BucketAclGrantConfiguration
- S3BucketConfiguration
- S3PublicAccessBlockConfiguration
- SecretsManagerSecretConfiguration
- SnsTopicConfiguration
- SortCriteria
- Span
- SqsQueueConfiguration
- StartPolicyGenerationRequest
- StartPolicyGenerationResponse
- StartResourceScanRequest
- StatusReason
- Substring
- TagResourceRequest
- TagResourceResponse
- TagsMap
- Trail
- TrailProperties
- UntagResourceRequest
- UntagResourceResponse
- UpdateArchiveRuleRequest
- UpdateFindingsRequest
- ValidatePolicyFinding
- ValidatePolicyRequest
- ValidatePolicyResponse
- VpcConfiguration
- name
context_file: json-ld/amazon-iam-access-analyzer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-access-analyzer/refs/heads/main/json-ld/amazon-iam-access-analyzer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Iam Access Analyzer from Amazon IAM Access Analyzer.
layout: jsonld
name: Amazon Iam Access Analyzer Context
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
  name: accessPointAccount
  type: string
- container: ''
  name: accessPointArn
  type: string
- container: ''
  name: accessPointPolicy
  type: string
- container: ''
  name: accessPoints
  type: string
- container: ''
  name: accessPreview
  type: string
- container: ''
  name: accessPreviews
  type: string
- container: ''
  name: accessRole
  type: string
- container: ''
  name: accountIds
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: actions
  type: string
- container: ''
  name: allRegions
  type: string
- container: ''
  name: analyzedAt
  type: string
- container: ''
  name: analyzedResources
  type: string
- container: ''
  name: analyzer
  type: string
- container: ''
  name: analyzerArn
  type: string
- container: ''
  name: analyzerName
  type: string
- container: ''
  name: analyzers
  type: string
- container: ''
  name: archiveRule
  type: reference
- container: ''
  name: archiveRules
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: attributeName
  type: string
- container: ''
  name: attributes
  type: string
- container: ''
  name: bucketAclGrants
  type: string
- container: ''
  name: bucketPolicy
  type: string
- container: ''
  name: bucketPublicAccessBlock
  type: string
- container: ''
  name: changeType
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: cloudTrailArn
  type: string
- container: ''
  name: cloudTrailDetails
  type: string
- container: ''
  name: cloudTrailProperties
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: column
  type: string
- container: ''
  name: completedOn
  type: string
- container: ''
  name: condition
  type: string
- container: ''
  name: configurations
  type: string
- container: ''
  name: constraints
  type: string
- container: ''
  name: contains
  type: string
- container: ''
  name: createdAt
  type: string
- container: ''
  name: detail
  type: string
- container: ''
  name: ebsSnapshot
  type: string
- container: ''
  name: ecrRepository
  type: string
- container: ''
  name: efsFileSystem
  type: string
- container: ''
  name: encryptionContextEquals
  type: string
- container: ''
  name: encryptionContextSubset
  type: string
- container: ''
  name: end
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: eq
  type: string
- container: ''
  name: error
  type: string
- container: ''
  name: existingFindingId
  type: string
- container: ''
  name: existingFindingStatus
  type: string
- container: ''
  name: exists
  type: string
- container: ''
  name: fileSystemPolicy
  type: string
- container: ''
  name: filter
  type: string
- container: ''
  name: finding
  type: string
- container: ''
  name: findingDetails
  type: string
- container: ''
  name: findingType
  type: string
- container: ''
  name: findings
  type: string
- container: ''
  name: generatedPolicies
  type: string
- container: ''
  name: generatedPolicyResult
  type: string
- container: ''
  name: grantee
  type: string
- container: ''
  name: granteePrincipal
  type: string
- container: ''
  name: grants
  type: string
- container: ''
  name: groups
  type: string
- container: ''
  name: iamRole
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: ids
  type: string
- container: ''
  name: ignorePublicAcls
  type: string
- container: ''
  name: index
  type: string
- container: ''
  name: internetConfiguration
  type: string
- container: ''
  name: isComplete
  type: string
- container: ''
  name: isPublic
  type: string
- container: ''
  name: issueCode
  type: string
- container: ''
  name: issuingAccount
  type: string
- container: ''
  name: jobDetails
  type: string
- container: ''
  name: jobError
  type: string
- container: ''
  name: jobId
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: keyPolicies
  type: string
- container: ''
  name: kmsKey
  type: string
- container: ''
  name: kmsKeyId
  type: string
- container: ''
  name: lastResourceAnalyzed
  type: string
- container: ''
  name: lastResourceAnalyzedAt
  type: string
- container: ''
  name: learnMoreLink
  type: string
- container: ''
  name: length
  type: string
- container: ''
  name: line
  type: string
- container: ''
  name: locale
  type: string
- container: ''
  name: locations
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: neq
  type: string
- container: ''
  name: networkOrigin
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: offset
  type: string
- container: ''
  name: operations
  type: string
- container: ''
  name: orderBy
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: permission
  type: string
- container: ''
  name: policy
  type: string
- container: ''
  name: policyDocument
  type: string
- container: ''
  name: policyGenerationDetails
  type: string
- container: ''
  name: policyGenerations
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: principal
  type: string
- container: ''
  name: principalArn
  type: string
- container: ''
  name: properties
  type: string
- container: ''
  name: publicAccessBlock
  type: string
- container: ''
  name: queuePolicy
  type: string
- container: ''
  name: rdsDbClusterSnapshot
  type: string
- container: ''
  name: rdsDbSnapshot
  type: string
- container: ''
  name: regions
  type: string
- container: ''
  name: repositoryPolicy
  type: string
- container: ''
  name: resource
  type: string
- container: ''
  name: resourceArn
  type: string
- container: ''
  name: resourceOwnerAccount
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: restrictPublicBuckets
  type: string
- container: ''
  name: retiringPrincipal
  type: string
- container: ''
  name: ruleName
  type: string
- container: ''
  name: s3Bucket
  type: string
- container: ''
  name: secretPolicy
  type: string
- container: ''
  name: secretsManagerSecret
  type: string
- container: ''
  name: sharedVia
  type: string
- container: ''
  name: snsTopic
  type: string
- container: ''
  name: sort
  type: string
- container: ''
  name: sources
  type: string
- container: ''
  name: span
  type: string
- container: ''
  name: sqsQueue
  type: string
- container: ''
  name: start
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: startedOn
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: reference
- container: ''
  name: substring
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: topicPolicy
  type: string
- container: ''
  name: trailProperties
  type: string
- container: ''
  name: trails
  type: string
- container: ''
  name: trustPolicy
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: string
- container: ''
  name: uri
  type: string
- container: ''
  name: userIds
  type: string
- container: ''
  name: validatePolicyResourceType
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: vpcConfiguration
  type: reference
- container: ''
  name: vpcId
  type: string
property_count: 146
provider_name: Amazon IAM Access Analyzer
provider_slug: amazon-iam-access-analyzer
slug: amazon-iam-access-analyzer-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amzn\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessPreview\": \"amzn:AccessPreview\",\n    \"AccessPreviewFinding\": \"amzn:AccessPreviewFinding\",\n    \"AccessPreviewStatusReason\": \"amzn:AccessPreviewStatusReason\",\n    \"AccessPreviewSummary\": \"amzn:AccessPreviewSummary\",\n    \"AclGrantee\": \"amzn:AclGrantee\",\n    \"AnalyzedResource\": \"amzn:AnalyzedResource\",\n    \"AnalyzedResourceSummary\": \"amzn:AnalyzedResourceSummary\",\n    \"AnalyzerSummary\": \"amzn:AnalyzerSummary\",\n    \"ApplyArchiveRuleRequest\": \"amzn:ApplyArchiveRuleRequest\",\n    \"ArchiveRuleSummary\": \"amzn:ArchiveRuleSummary\",\n    \"CancelPolicyGenerationRequest\": \"amzn:CancelPolicyGenerationRequest\",\n    \"CancelPolicyGenerationResponse\": \"amzn:CancelPolicyGenerationResponse\",\n\
  \    \"CloudTrailDetails\": \"amzn:CloudTrailDetails\",\n    \"CloudTrailProperties\": \"amzn:CloudTrailProperties\",\n    \"ConditionKeyMap\": \"amzn:ConditionKeyMap\",\n    \"Configuration\": \"amzn:Configuration\",\n    \"ConfigurationsMap\": \"amzn:ConfigurationsMap\",\n    \"CreateAccessPreviewRequest\": \"amzn:CreateAccessPreviewRequest\",\n    \"CreateAccessPreviewResponse\": \"amzn:CreateAccessPreviewResponse\",\n    \"CreateAnalyzerRequest\": \"amzn:CreateAnalyzerRequest\",\n    \"CreateAnalyzerResponse\": \"amzn:CreateAnalyzerResponse\",\n    \"CreateArchiveRuleRequest\": \"amzn:CreateArchiveRuleRequest\",\n    \"Criterion\": \"amzn:Criterion\",\n    \"DeleteAnalyzerRequest\": \"amzn:DeleteAnalyzerRequest\",\n    \"DeleteArchiveRuleRequest\": \"amzn:DeleteArchiveRuleRequest\",\n    \"EbsSnapshotConfiguration\": \"amzn:EbsSnapshotConfiguration\",\n    \"EcrRepositoryConfiguration\": \"amzn:EcrRepositoryConfiguration\",\n    \"EfsFileSystemConfiguration\": \"amzn:EfsFileSystemConfiguration\"\
  ,\n    \"FilterCriteriaMap\": \"amzn:FilterCriteriaMap\",\n    \"Finding\": \"amzn:Finding\",\n    \"FindingSource\": \"amzn:FindingSource\",\n    \"FindingSourceDetail\": \"amzn:FindingSourceDetail\",\n    \"FindingSummary\": \"amzn:FindingSummary\",\n    \"GeneratedPolicy\": \"amzn:GeneratedPolicy\",\n    \"GeneratedPolicyProperties\": \"amzn:GeneratedPolicyProperties\",\n    \"GeneratedPolicyResult\": \"amzn:GeneratedPolicyResult\",\n    \"GetAccessPreviewRequest\": \"amzn:GetAccessPreviewRequest\",\n    \"GetAccessPreviewResponse\": \"amzn:GetAccessPreviewResponse\",\n    \"GetAnalyzedResourceRequest\": \"amzn:GetAnalyzedResourceRequest\",\n    \"GetAnalyzedResourceResponse\": \"amzn:GetAnalyzedResourceResponse\",\n    \"GetAnalyzerRequest\": \"amzn:GetAnalyzerRequest\",\n    \"GetAnalyzerResponse\": \"amzn:GetAnalyzerResponse\",\n    \"GetArchiveRuleRequest\": \"amzn:GetArchiveRuleRequest\",\n    \"GetArchiveRuleResponse\": \"amzn:GetArchiveRuleResponse\",\n    \"GetFindingRequest\"\
  : \"amzn:GetFindingRequest\",\n    \"GetFindingResponse\": \"amzn:GetFindingResponse\",\n    \"GetGeneratedPolicyRequest\": \"amzn:GetGeneratedPolicyRequest\",\n    \"GetGeneratedPolicyResponse\": \"amzn:GetGeneratedPolicyResponse\",\n    \"IamRoleConfiguration\": \"amzn:IamRoleConfiguration\",\n    \"InlineArchiveRule\": \"amzn:InlineArchiveRule\",\n    \"InternetConfiguration\": \"amzn:InternetConfiguration\",\n    \"JobDetails\": \"amzn:JobDetails\",\n    \"JobError\": \"amzn:JobError\",\n    \"KmsConstraintsMap\": \"amzn:KmsConstraintsMap\",\n    \"KmsGrantConfiguration\": \"amzn:KmsGrantConfiguration\",\n    \"KmsGrantConstraints\": \"amzn:KmsGrantConstraints\",\n    \"KmsKeyConfiguration\": \"amzn:KmsKeyConfiguration\",\n    \"KmsKeyPoliciesMap\": \"amzn:KmsKeyPoliciesMap\",\n    \"ListAccessPreviewFindingsRequest\": \"amzn:ListAccessPreviewFindingsRequest\",\n    \"ListAccessPreviewFindingsResponse\": \"amzn:ListAccessPreviewFindingsResponse\",\n    \"ListAccessPreviewsRequest\"\
  : \"amzn:ListAccessPreviewsRequest\",\n    \"ListAccessPreviewsResponse\": \"amzn:ListAccessPreviewsResponse\",\n    \"ListAnalyzedResourcesRequest\": \"amzn:ListAnalyzedResourcesRequest\",\n    \"ListAnalyzedResourcesResponse\": \"amzn:ListAnalyzedResourcesResponse\",\n    \"ListAnalyzersRequest\": \"amzn:ListAnalyzersRequest\",\n    \"ListAnalyzersResponse\": \"amzn:ListAnalyzersResponse\",\n    \"ListArchiveRulesRequest\": \"amzn:ListArchiveRulesRequest\",\n    \"ListArchiveRulesResponse\": \"amzn:ListArchiveRulesResponse\",\n    \"ListFindingsRequest\": \"amzn:ListFindingsRequest\",\n    \"ListFindingsResponse\": \"amzn:ListFindingsResponse\",\n    \"ListPolicyGenerationsRequest\": \"amzn:ListPolicyGenerationsRequest\",\n    \"ListPolicyGenerationsResponse\": \"amzn:ListPolicyGenerationsResponse\",\n    \"ListTagsForResourceRequest\": \"amzn:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amzn:ListTagsForResourceResponse\",\n    \"Location\": \"amzn:Location\"\
  ,\n    \"NetworkOriginConfiguration\": \"amzn:NetworkOriginConfiguration\",\n    \"PathElement\": \"amzn:PathElement\",\n    \"PolicyGeneration\": \"amzn:PolicyGeneration\",\n    \"PolicyGenerationDetails\": \"amzn:PolicyGenerationDetails\",\n    \"Position\": \"amzn:Position\",\n    \"PrincipalMap\": \"amzn:PrincipalMap\",\n    \"RdsDbClusterSnapshotAttributeValue\": \"amzn:RdsDbClusterSnapshotAttributeValue\",\n    \"RdsDbClusterSnapshotAttributesMap\": \"amzn:RdsDbClusterSnapshotAttributesMap\",\n    \"RdsDbClusterSnapshotConfiguration\": \"amzn:RdsDbClusterSnapshotConfiguration\",\n    \"RdsDbSnapshotAttributeValue\": \"amzn:RdsDbSnapshotAttributeValue\",\n    \"RdsDbSnapshotAttributesMap\": \"amzn:RdsDbSnapshotAttributesMap\",\n    \"RdsDbSnapshotConfiguration\": \"amzn:RdsDbSnapshotConfiguration\",\n    \"S3AccessPointConfiguration\": \"amzn:S3AccessPointConfiguration\",\n    \"S3AccessPointConfigurationsMap\": \"amzn:S3AccessPointConfigurationsMap\",\n    \"S3BucketAclGrantConfiguration\"\
  : \"amzn:S3BucketAclGrantConfiguration\",\n    \"S3BucketConfiguration\": \"amzn:S3BucketConfiguration\",\n    \"S3PublicAccessBlockConfiguration\": \"amzn:S3PublicAccessBlockConfiguration\",\n    \"SecretsManagerSecretConfiguration\": \"amzn:SecretsManagerSecretConfiguration\",\n    \"SnsTopicConfiguration\": \"amzn:SnsTopicConfiguration\",\n    \"SortCriteria\": \"amzn:SortCriteria\",\n    \"Span\": \"amzn:Span\",\n    \"SqsQueueConfiguration\": \"amzn:SqsQueueConfiguration\",\n    \"StartPolicyGenerationRequest\": \"amzn:StartPolicyGenerationRequest\",\n    \"StartPolicyGenerationResponse\": \"amzn:StartPolicyGenerationResponse\",\n    \"StartResourceScanRequest\": \"amzn:StartResourceScanRequest\",\n    \"StatusReason\": \"amzn:StatusReason\",\n    \"Substring\": \"amzn:Substring\",\n    \"TagResourceRequest\": \"amzn:TagResourceRequest\",\n    \"TagResourceResponse\": \"amzn:TagResourceResponse\",\n    \"TagsMap\": \"amzn:TagsMap\",\n    \"Trail\": \"amzn:Trail\",\n    \"TrailProperties\"\
  : \"amzn:TrailProperties\",\n    \"UntagResourceRequest\": \"amzn:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amzn:UntagResourceResponse\",\n    \"UpdateArchiveRuleRequest\": \"amzn:UpdateArchiveRuleRequest\",\n    \"UpdateFindingsRequest\": \"amzn:UpdateFindingsRequest\",\n    \"ValidatePolicyFinding\": \"amzn:ValidatePolicyFinding\",\n    \"ValidatePolicyRequest\": \"amzn:ValidatePolicyRequest\",\n    \"ValidatePolicyResponse\": \"amzn:ValidatePolicyResponse\",\n    \"VpcConfiguration\": \"amzn:VpcConfiguration\",\n    \"accessPointAccount\": {\n      \"@id\": \"amzn:accessPointAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPointArn\": {\n      \"@id\": \"amzn:accessPointArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPointPolicy\": {\n      \"@id\": \"amzn:accessPointPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPoints\": {\n      \"@id\": \"amzn:accessPoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPreview\"\
  : {\n      \"@id\": \"amzn:accessPreview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessPreviews\": {\n      \"@id\": \"amzn:accessPreviews\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessRole\": {\n      \"@id\": \"amzn:accessRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountIds\": {\n      \"@id\": \"amzn:accountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"amzn:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actions\": {\n      \"@id\": \"amzn:actions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"allRegions\": {\n      \"@id\": \"amzn:allRegions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analyzedAt\": {\n      \"@id\": \"amzn:analyzedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analyzedResources\": {\n      \"@id\": \"amzn:analyzedResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analyzer\": {\n      \"@id\": \"amzn:analyzer\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"analyzerArn\": {\n      \"@id\": \"amzn:analyzerArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analyzerName\": {\n      \"@id\": \"amzn:analyzerName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"analyzers\": {\n      \"@id\": \"amzn:analyzers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"archiveRule\": {\n      \"@id\": \"amzn:archiveRule\",\n      \"@type\": \"@id\"\n    },\n    \"archiveRules\": {\n      \"@id\": \"amzn:archiveRules\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amzn:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributeName\": {\n      \"@id\": \"amzn:attributeName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributes\": {\n      \"@id\": \"amzn:attributes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketAclGrants\": {\n      \"@id\": \"amzn:bucketAclGrants\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketPolicy\": {\n      \"@id\": \"amzn:bucketPolicy\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"bucketPublicAccessBlock\": {\n      \"@id\": \"amzn:bucketPublicAccessBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"changeType\": {\n      \"@id\": \"amzn:changeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amzn:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudTrailArn\": {\n      \"@id\": \"amzn:cloudTrailArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudTrailDetails\": {\n      \"@id\": \"amzn:cloudTrailDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cloudTrailProperties\": {\n      \"@id\": \"amzn:cloudTrailProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"amzn:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"column\": {\n      \"@id\": \"amzn:column\",\n      \"@type\": \"xsd:string\"\n    },\n    \"completedOn\": {\n      \"@id\": \"amzn:completedOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"condition\": {\n      \"\
  @id\": \"amzn:condition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurations\": {\n      \"@id\": \"amzn:configurations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"constraints\": {\n      \"@id\": \"amzn:constraints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contains\": {\n      \"@id\": \"amzn:contains\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amzn:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detail\": {\n      \"@id\": \"amzn:detail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ebsSnapshot\": {\n      \"@id\": \"amzn:ebsSnapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ecrRepository\": {\n      \"@id\": \"amzn:ecrRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"efsFileSystem\": {\n      \"@id\": \"amzn:efsFileSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"encryptionContextEquals\": {\n      \"@id\": \"amzn:encryptionContextEquals\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"encryptionContextSubset\": {\n      \"@id\": \"amzn:encryptionContextSubset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"end\": {\n      \"@id\": \"amzn:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amzn:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eq\": {\n      \"@id\": \"amzn:eq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"error\": {\n      \"@id\": \"amzn:error\",\n      \"@type\": \"xsd:string\"\n    },\n    \"existingFindingId\": {\n      \"@id\": \"amzn:existingFindingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"existingFindingStatus\": {\n      \"@id\": \"amzn:existingFindingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exists\": {\n      \"@id\": \"amzn:exists\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSystemPolicy\": {\n      \"@id\": \"amzn:fileSystemPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filter\": {\n      \"@id\": \"amzn:filter\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"finding\": {\n      \"@id\": \"amzn:finding\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingDetails\": {\n      \"@id\": \"amzn:findingDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingType\": {\n      \"@id\": \"amzn:findingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"amzn:findings\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatedPolicies\": {\n      \"@id\": \"amzn:generatedPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"generatedPolicyResult\": {\n      \"@id\": \"amzn:generatedPolicyResult\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grantee\": {\n      \"@id\": \"amzn:grantee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"granteePrincipal\": {\n      \"@id\": \"amzn:granteePrincipal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grants\": {\n      \"@id\": \"amzn:grants\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n    \
  \  \"@id\": \"amzn:groups\",\n      \"@type\": \"xsd:string\"\n    },\n    \"iamRole\": {\n      \"@id\": \"amzn:iamRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amzn:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ids\": {\n      \"@id\": \"amzn:ids\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ignorePublicAcls\": {\n      \"@id\": \"amzn:ignorePublicAcls\",\n      \"@type\": \"xsd:string\"\n    },\n    \"index\": {\n      \"@id\": \"amzn:index\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internetConfiguration\": {\n      \"@id\": \"amzn:internetConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isComplete\": {\n      \"@id\": \"amzn:isComplete\",\n      \"@type\": \"xsd:string\"\n    },\n    \"isPublic\": {\n      \"@id\": \"amzn:isPublic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issueCode\": {\n      \"@id\": \"amzn:issueCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuingAccount\": {\n      \"@id\"\
  : \"amzn:issuingAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobDetails\": {\n      \"@id\": \"amzn:jobDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobError\": {\n      \"@id\": \"amzn:jobError\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"amzn:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amzn:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyPolicies\": {\n      \"@id\": \"amzn:keyPolicies\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKey\": {\n      \"@id\": \"amzn:kmsKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"amzn:kmsKeyId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastResourceAnalyzed\": {\n      \"@id\": \"amzn:lastResourceAnalyzed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastResourceAnalyzedAt\": {\n      \"@id\": \"amzn:lastResourceAnalyzedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"learnMoreLink\"\
  : {\n      \"@id\": \"amzn:learnMoreLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"length\": {\n      \"@id\": \"amzn:length\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line\": {\n      \"@id\": \"amzn:line\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locale\": {\n      \"@id\": \"amzn:locale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"amzn:locations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amzn:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"amzn:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"neq\": {\n      \"@id\": \"amzn:neq\",\n      \"@type\": \"xsd:string\"\n    },\n    \"networkOrigin\": {\n      \"@id\": \"amzn:networkOrigin\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amzn:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"offset\": {\n\
  \      \"@id\": \"amzn:offset\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operations\": {\n      \"@id\": \"amzn:operations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"orderBy\": {\n      \"@id\": \"amzn:orderBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"amzn:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"permission\": {\n      \"@id\": \"amzn:permission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policy\": {\n      \"@id\": \"amzn:policy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyDocument\": {\n      \"@id\": \"amzn:policyDocument\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyGenerationDetails\": {\n      \"@id\": \"amzn:policyGenerationDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyGenerations\": {\n      \"@id\": \"amzn:policyGenerations\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"amzn:policyType\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"principal\": {\n      \"@id\": \"amzn:principal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalArn\": {\n      \"@id\": \"amzn:principalArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"amzn:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publicAccessBlock\": {\n      \"@id\": \"amzn:publicAccessBlock\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queuePolicy\": {\n      \"@id\": \"amzn:queuePolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rdsDbClusterSnapshot\": {\n      \"@id\": \"amzn:rdsDbClusterSnapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rdsDbSnapshot\": {\n      \"@id\": \"amzn:rdsDbSnapshot\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regions\": {\n      \"@id\": \"amzn:regions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryPolicy\": {\n      \"@id\": \"amzn:repositoryPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resource\": {\n      \"@id\"\
  : \"amzn:resource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceArn\": {\n      \"@id\": \"amzn:resourceArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceOwnerAccount\": {\n      \"@id\": \"amzn:resourceOwnerAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"amzn:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restrictPublicBuckets\": {\n      \"@id\": \"amzn:restrictPublicBuckets\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retiringPrincipal\": {\n      \"@id\": \"amzn:retiringPrincipal\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ruleName\": {\n      \"@id\": \"amzn:ruleName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Bucket\": {\n      \"@id\": \"amzn:s3Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretPolicy\": {\n      \"@id\": \"amzn:secretPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretsManagerSecret\": {\n      \"@id\": \"amzn:secretsManagerSecret\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sharedVia\": {\n      \"@id\": \"amzn:sharedVia\",\n      \"@type\": \"xsd:string\"\n    },\n    \"snsTopic\": {\n      \"@id\": \"amzn:snsTopic\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sort\": {\n      \"@id\": \"amzn:sort\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sources\": {\n      \"@id\": \"amzn:sources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"span\": {\n      \"@id\": \"amzn:span\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sqsQueue\": {\n      \"@id\": \"amzn:sqsQueue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"amzn:start\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amzn:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedOn\": {\n      \"@id\": \"amzn:startedOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amzn:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\"\
  : {\n      \"@id\": \"amzn:statusReason\",\n      \"@type\": \"@id\"\n    },\n    \"substring\": {\n      \"@id\": \"amzn:substring\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"amzn:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"topicPolicy\": {\n      \"@id\": \"amzn:topicPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trailProperties\": {\n      \"@id\": \"amzn:trailProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trails\": {\n      \"@id\": \"amzn:trails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"trustPolicy\": {\n      \"@id\": \"amzn:trustPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amzn:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"amzn:updatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uri\": {\n      \"@id\": \"amzn:uri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userIds\": {\n      \"@id\": \"amzn:userIds\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"validatePolicyResourceType\": {\n      \"@id\": \"amzn:validatePolicyResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amzn:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vpcConfiguration\": {\n      \"@id\": \"amzn:vpcConfiguration\",\n      \"@type\": \"@id\"\n    },\n    \"vpcId\": {\n      \"@id\": \"amzn:vpcId\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-iam-access-analyzer/refs/heads/main/json-ld/amazon-iam-access-analyzer-context.jsonld
tags:
- Access Control
- AWS
- Compliance
- IAM
- Policy Management
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
