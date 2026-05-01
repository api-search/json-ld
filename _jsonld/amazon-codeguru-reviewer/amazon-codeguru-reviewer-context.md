---
api_specs:
- filename: amazon-codeguru-reviewer-openapi-original.yaml
  format: yaml
  label: Amazon CodeGuru Reviewer API
  slug: amazon-codeguru-reviewer-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/openapi/amazon-codeguru-reviewer-openapi-original.yaml
class_count: 40
classes:
- AssociateRepositoryResponse
- CodeCommitRepository
- ThirdPartySourceRepository
- S3Repository
- CreateCodeReviewResponse
- DescribeCodeReviewResponse
- DescribeRecommendationFeedbackResponse
- DescribeRepositoryAssociationResponse
- DisassociateRepositoryResponse
- ListCodeReviewsResponse
- ListRecommendationFeedbackResponse
- ListRecommendationsResponse
- ListRepositoryAssociationsResponse
- ListTagsForResourceResponse
- PutRecommendationFeedbackResponse
- TagResourceResponse
- UntagResourceResponse
- TagMap
- AssociateRepositoryRequest
- BranchDiffSourceCodeType
- CodeReviewSummary
- CodeReviewType
- CommitDiffSourceCodeType
- CreateCodeReviewRequest
- DescribeCodeReviewRequest
- DescribeRecommendationFeedbackRequest
- DescribeRepositoryAssociationRequest
- DisassociateRepositoryRequest
- ListCodeReviewsRequest
- ListRecommendationFeedbackRequest
- ListRecommendationsRequest
- ListRepositoryAssociationsRequest
- ListTagsForResourceRequest
- PutRecommendationFeedbackRequest
- RecommendationFeedbackSummary
- RecommendationSummary
- RepositoryHeadSourceCodeType
- RepositoryAssociationSummary
- TagResourceRequest
- UntagResourceRequest
context_file: json-ld/amazon-codeguru-reviewer-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/json-ld/amazon-codeguru-reviewer-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codeguru Reviewer from Amazon CodeGuru Reviewer.
layout: jsonld
name: Amazon Codeguru Reviewer Context
namespaces:
- prefix: amazon-code-guru-reviewer
  uri: https://amazon-code-guru-reviewer.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: RepositoryAnalysis
  type: string
- container: ''
  name: Repository
  type: string
- container: ''
  name: KMSKeyDetails
  type: string
- container: ''
  name: RepositoryAssociation
  type: string
- container: ''
  name: CodeArtifacts
  type: string
- container: ''
  name: SourceCodeType
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: CodeReview
  type: string
- container: ''
  name: MetricsSummary
  type: string
- container: ''
  name: RecommendationFeedback
  type: string
- container: ''
  name: EventInfo
  type: string
- container: ''
  name: RuleMetadata
  type: string
- container: ''
  name: S3RepositoryDetails
  type: string
- container: ''
  name: RequestMetadata
  type: string
- container: ''
  name: S3BucketRepository
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: ConnectionArn
  type: string
- container: ''
  name: Owner
  type: string
- container: ''
  name: BucketName
  type: string
- container: ''
  name: RepositoryHead
  type: string
- container: ''
  name: CodeReviewSummaries
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: RecommendationFeedbackSummaries
  type: string
- container: ''
  name: RecommendationSummaries
  type: string
- container: ''
  name: RepositoryAssociationSummaries
  type: string
- container: ''
  name: CodeCommit
  type: string
- container: ''
  name: Bitbucket
  type: string
- container: ''
  name: GitHubEnterpriseServer
  type: string
- container: ''
  name: S3Bucket
  type: string
- container: ''
  name: KMSKeyId
  type: string
- container: ''
  name: EncryptionOption
  type: string
- container: ''
  name: ClientRequestToken
  type: string
- container: ''
  name: AssociationId
  type: string
- container: ''
  name: AssociationArn
  type: string
- container: ''
  name: ProviderType
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: StateReason
  type: string
- container: ''
  name: LastUpdatedTimeStamp
  type: string
- container: ''
  name: CreatedTimeStamp
  type: string
- container: ''
  name: SourceBranchName
  type: string
- container: ''
  name: DestinationBranchName
  type: string
- container: ''
  name: SourceCodeArtifactsObjectKey
  type: string
- container: ''
  name: BuildArtifactsObjectKey
  type: string
- container: ''
  name: CommitDiff
  type: string
- container: ''
  name: BranchDiff
  type: string
- container: ''
  name: MeteredLinesOfCodeCount
  type: string
- container: ''
  name: SuppressedLinesOfCodeCount
  type: string
- container: ''
  name: FindingsCount
  type: string
- container: ''
  name: CodeReviewArn
  type: string
- container: ''
  name: RepositoryName
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: PullRequestId
  type: string
- container: ''
  name: AnalysisTypes
  type: string
- container: ''
  name: ConfigFileState
  type: string
- container: ''
  name: SourceCommit
  type: string
- container: ''
  name: DestinationCommit
  type: string
- container: ''
  name: MergeBaseCommit
  type: string
- container: ''
  name: RepositoryAssociationArn
  type: string
- container: ''
  name: RecommendationId
  type: string
- container: ''
  name: Reactions
  type: string
- container: ''
  name: UserId
  type: string
- container: ''
  name: FilePath
  type: string
- container: ''
  name: StartLine
  type: string
- container: ''
  name: EndLine
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: RecommendationCategory
  type: string
- container: ''
  name: Severity
  type: string
- container: ''
  name: RuleId
  type: string
- container: ''
  name: RuleName
  type: string
- container: ''
  name: ShortDescription
  type: string
- container: ''
  name: LongDescription
  type: string
- container: ''
  name: RuleTags
  type: string
- container: ''
  name: BranchName
  type: string
- container: ''
  name: RequestId
  type: string
- container: ''
  name: Requester
  type: string
- container: ''
  name: VendorName
  type: string
- container: ''
  name: Details
  type: string
property_count: 78
provider_name: Amazon CodeGuru Reviewer
provider_slug: amazon-codeguru-reviewer
slug: amazon-codeguru-reviewer-context
source_filename: amazon-codeguru-reviewer-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-guru-reviewer\": \"https://amazon-code-guru-reviewer.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AssociateRepositoryResponse\": \"amazon-code-guru-reviewer:AssociateRepositoryResponse\",\n    \"CodeCommitRepository\": \"amazon-code-guru-reviewer:CodeCommitRepository\",\n    \"ThirdPartySourceRepository\": \"amazon-code-guru-reviewer:ThirdPartySourceRepository\",\n    \"S3Repository\": \"amazon-code-guru-reviewer:S3Repository\",\n    \"CreateCodeReviewResponse\": \"amazon-code-guru-reviewer:CreateCodeReviewResponse\",\n    \"RepositoryAnalysis\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryAnalysis\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeCodeReviewResponse\": \"amazon-code-guru-reviewer:DescribeCodeReviewResponse\",\n    \"DescribeRecommendationFeedbackResponse\"\
  : \"amazon-code-guru-reviewer:DescribeRecommendationFeedbackResponse\",\n    \"DescribeRepositoryAssociationResponse\": \"amazon-code-guru-reviewer:DescribeRepositoryAssociationResponse\",\n    \"DisassociateRepositoryResponse\": \"amazon-code-guru-reviewer:DisassociateRepositoryResponse\",\n    \"ListCodeReviewsResponse\": \"amazon-code-guru-reviewer:ListCodeReviewsResponse\",\n    \"ListRecommendationFeedbackResponse\": \"amazon-code-guru-reviewer:ListRecommendationFeedbackResponse\",\n    \"ListRecommendationsResponse\": \"amazon-code-guru-reviewer:ListRecommendationsResponse\",\n    \"ListRepositoryAssociationsResponse\": \"amazon-code-guru-reviewer:ListRepositoryAssociationsResponse\",\n    \"ListTagsForResourceResponse\": \"amazon-code-guru-reviewer:ListTagsForResourceResponse\",\n    \"PutRecommendationFeedbackResponse\": \"amazon-code-guru-reviewer:PutRecommendationFeedbackResponse\",\n    \"TagResourceResponse\": \"amazon-code-guru-reviewer:TagResourceResponse\",\n    \"UntagResourceResponse\"\
  : \"amazon-code-guru-reviewer:UntagResourceResponse\",\n    \"Repository\": {\n      \"@id\": \"amazon-code-guru-reviewer:Repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagMap\": \"amazon-code-guru-reviewer:TagMap\",\n    \"KMSKeyDetails\": {\n      \"@id\": \"amazon-code-guru-reviewer:KMSKeyDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateRepositoryRequest\": \"amazon-code-guru-reviewer:AssociateRepositoryRequest\",\n    \"RepositoryAssociation\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryAssociation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BranchDiffSourceCodeType\": \"amazon-code-guru-reviewer:BranchDiffSourceCodeType\",\n    \"CodeArtifacts\": {\n      \"@id\": \"amazon-code-guru-reviewer:CodeArtifacts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceCodeType\": {\n      \"@id\": \"amazon-code-guru-reviewer:SourceCodeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Metrics\": {\n      \"@id\": \"amazon-code-guru-reviewer:Metrics\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeReview\": {\n      \"@id\": \"amazon-code-guru-reviewer:CodeReview\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeReviewSummary\": \"amazon-code-guru-reviewer:CodeReviewSummary\",\n    \"MetricsSummary\": {\n      \"@id\": \"amazon-code-guru-reviewer:MetricsSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeReviewType\": \"amazon-code-guru-reviewer:CodeReviewType\",\n    \"CommitDiffSourceCodeType\": \"amazon-code-guru-reviewer:CommitDiffSourceCodeType\",\n    \"CreateCodeReviewRequest\": \"amazon-code-guru-reviewer:CreateCodeReviewRequest\",\n    \"DescribeCodeReviewRequest\": \"amazon-code-guru-reviewer:DescribeCodeReviewRequest\",\n    \"DescribeRecommendationFeedbackRequest\": \"amazon-code-guru-reviewer:DescribeRecommendationFeedbackRequest\",\n    \"RecommendationFeedback\": {\n      \"@id\": \"amazon-code-guru-reviewer:RecommendationFeedback\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DescribeRepositoryAssociationRequest\"\
  : \"amazon-code-guru-reviewer:DescribeRepositoryAssociationRequest\",\n    \"DisassociateRepositoryRequest\": \"amazon-code-guru-reviewer:DisassociateRepositoryRequest\",\n    \"EventInfo\": {\n      \"@id\": \"amazon-code-guru-reviewer:EventInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListCodeReviewsRequest\": \"amazon-code-guru-reviewer:ListCodeReviewsRequest\",\n    \"ListRecommendationFeedbackRequest\": \"amazon-code-guru-reviewer:ListRecommendationFeedbackRequest\",\n    \"ListRecommendationsRequest\": \"amazon-code-guru-reviewer:ListRecommendationsRequest\",\n    \"ListRepositoryAssociationsRequest\": \"amazon-code-guru-reviewer:ListRepositoryAssociationsRequest\",\n    \"ListTagsForResourceRequest\": \"amazon-code-guru-reviewer:ListTagsForResourceRequest\",\n    \"PutRecommendationFeedbackRequest\": \"amazon-code-guru-reviewer:PutRecommendationFeedbackRequest\",\n    \"RecommendationFeedbackSummary\": \"amazon-code-guru-reviewer:RecommendationFeedbackSummary\",\n    \"\
  RecommendationSummary\": \"amazon-code-guru-reviewer:RecommendationSummary\",\n    \"RuleMetadata\": {\n      \"@id\": \"amazon-code-guru-reviewer:RuleMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryHeadSourceCodeType\": \"amazon-code-guru-reviewer:RepositoryHeadSourceCodeType\",\n    \"S3RepositoryDetails\": {\n      \"@id\": \"amazon-code-guru-reviewer:S3RepositoryDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryAssociationSummary\": \"amazon-code-guru-reviewer:RepositoryAssociationSummary\",\n    \"RequestMetadata\": {\n      \"@id\": \"amazon-code-guru-reviewer:RequestMetadata\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3BucketRepository\": {\n      \"@id\": \"amazon-code-guru-reviewer:S3BucketRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceRequest\": \"amazon-code-guru-reviewer:TagResourceRequest\",\n    \"UntagResourceRequest\": \"amazon-code-guru-reviewer:UntagResourceRequest\",\n    \"Tags\": {\n      \"\
  @id\": \"amazon-code-guru-reviewer:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"amazon-code-guru-reviewer:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ConnectionArn\": {\n      \"@id\": \"amazon-code-guru-reviewer:ConnectionArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Owner\": {\n      \"@id\": \"amazon-code-guru-reviewer:Owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BucketName\": {\n      \"@id\": \"amazon-code-guru-reviewer:BucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryHead\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryHead\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeReviewSummaries\": {\n      \"@id\": \"amazon-code-guru-reviewer:CodeReviewSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amazon-code-guru-reviewer:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationFeedbackSummaries\": {\n      \"\
  @id\": \"amazon-code-guru-reviewer:RecommendationFeedbackSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationSummaries\": {\n      \"@id\": \"amazon-code-guru-reviewer:RecommendationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryAssociationSummaries\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryAssociationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeCommit\": {\n      \"@id\": \"amazon-code-guru-reviewer:CodeCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Bitbucket\": {\n      \"@id\": \"amazon-code-guru-reviewer:Bitbucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GitHubEnterpriseServer\": {\n      \"@id\": \"amazon-code-guru-reviewer:GitHubEnterpriseServer\",\n      \"@type\": \"xsd:string\"\n    },\n    \"S3Bucket\": {\n      \"@id\": \"amazon-code-guru-reviewer:S3Bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"KMSKeyId\": {\n      \"@id\": \"amazon-code-guru-reviewer:KMSKeyId\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"EncryptionOption\": {\n      \"@id\": \"amazon-code-guru-reviewer:EncryptionOption\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"amazon-code-guru-reviewer:ClientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationId\": {\n      \"@id\": \"amazon-code-guru-reviewer:AssociationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociationArn\": {\n      \"@id\": \"amazon-code-guru-reviewer:AssociationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProviderType\": {\n      \"@id\": \"amazon-code-guru-reviewer:ProviderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"amazon-code-guru-reviewer:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StateReason\": {\n      \"@id\": \"amazon-code-guru-reviewer:StateReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LastUpdatedTimeStamp\": {\n      \"@id\": \"amazon-code-guru-reviewer:LastUpdatedTimeStamp\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedTimeStamp\": {\n      \"@id\": \"amazon-code-guru-reviewer:CreatedTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceBranchName\": {\n      \"@id\": \"amazon-code-guru-reviewer:SourceBranchName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DestinationBranchName\": {\n      \"@id\": \"amazon-code-guru-reviewer:DestinationBranchName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceCodeArtifactsObjectKey\": {\n      \"@id\": \"amazon-code-guru-reviewer:SourceCodeArtifactsObjectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BuildArtifactsObjectKey\": {\n      \"@id\": \"amazon-code-guru-reviewer:BuildArtifactsObjectKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CommitDiff\": {\n      \"@id\": \"amazon-code-guru-reviewer:CommitDiff\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BranchDiff\": {\n      \"@id\": \"amazon-code-guru-reviewer:BranchDiff\",\n      \"@type\": \"xsd:string\"\n \
  \   },\n    \"MeteredLinesOfCodeCount\": {\n      \"@id\": \"amazon-code-guru-reviewer:MeteredLinesOfCodeCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SuppressedLinesOfCodeCount\": {\n      \"@id\": \"amazon-code-guru-reviewer:SuppressedLinesOfCodeCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FindingsCount\": {\n      \"@id\": \"amazon-code-guru-reviewer:FindingsCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CodeReviewArn\": {\n      \"@id\": \"amazon-code-guru-reviewer:CodeReviewArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryName\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Type\": {\n      \"@id\": \"amazon-code-guru-reviewer:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PullRequestId\": {\n      \"@id\": \"amazon-code-guru-reviewer:PullRequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnalysisTypes\": {\n      \"@id\": \"amazon-code-guru-reviewer:AnalysisTypes\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ConfigFileState\": {\n      \"@id\": \"amazon-code-guru-reviewer:ConfigFileState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SourceCommit\": {\n      \"@id\": \"amazon-code-guru-reviewer:SourceCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DestinationCommit\": {\n      \"@id\": \"amazon-code-guru-reviewer:DestinationCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MergeBaseCommit\": {\n      \"@id\": \"amazon-code-guru-reviewer:MergeBaseCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RepositoryAssociationArn\": {\n      \"@id\": \"amazon-code-guru-reviewer:RepositoryAssociationArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationId\": {\n      \"@id\": \"amazon-code-guru-reviewer:RecommendationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reactions\": {\n      \"@id\": \"amazon-code-guru-reviewer:Reactions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserId\": {\n      \"\
  @id\": \"amazon-code-guru-reviewer:UserId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FilePath\": {\n      \"@id\": \"amazon-code-guru-reviewer:FilePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartLine\": {\n      \"@id\": \"amazon-code-guru-reviewer:StartLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EndLine\": {\n      \"@id\": \"amazon-code-guru-reviewer:EndLine\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"amazon-code-guru-reviewer:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RecommendationCategory\": {\n      \"@id\": \"amazon-code-guru-reviewer:RecommendationCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Severity\": {\n      \"@id\": \"amazon-code-guru-reviewer:Severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleId\": {\n      \"@id\": \"amazon-code-guru-reviewer:RuleId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleName\": {\n      \"@id\": \"amazon-code-guru-reviewer:RuleName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ShortDescription\": {\n      \"@id\": \"amazon-code-guru-reviewer:ShortDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LongDescription\": {\n      \"@id\": \"amazon-code-guru-reviewer:LongDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RuleTags\": {\n      \"@id\": \"amazon-code-guru-reviewer:RuleTags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BranchName\": {\n      \"@id\": \"amazon-code-guru-reviewer:BranchName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RequestId\": {\n      \"@id\": \"amazon-code-guru-reviewer:RequestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Requester\": {\n      \"@id\": \"amazon-code-guru-reviewer:Requester\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VendorName\": {\n      \"@id\": \"amazon-code-guru-reviewer:VendorName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Details\": {\n      \"@id\": \"amazon-code-guru-reviewer:Details\",\n      \"@type\"\
  : \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/json-ld/amazon-codeguru-reviewer-context.jsonld
tags:
- Amazon
- Code Review
- Security
- DevOps
- Machine Learning
- Developer Tools
- JSON-LD
- Linked Data
- Semantic Web
---
