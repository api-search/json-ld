---
class_count: 146
classes:
- ChoiceAnswerSummary
- ProfileSummary
- ChoiceImprovementPlan
- BestPractice
- RiskCounts
- CheckDetail
- DisassociateProfilesInput
- DeleteLensShareInput
- GetProfileOutput
- Profile
- ProfileTemplateQuestion
- ListProfilesOutput
- AssociateLensesInput
- ListLensesInput
- ImprovementSummary
- WorkloadDiscoveryConfig
- ListProfileSharesInput
- CreateProfileShareOutput
- AnswerSummary
- GetLensReviewInput
- GetProfileTemplateOutput
- GetLensOutput
- Lens
- GetLensVersionDifferenceOutput
- LensMetric
- GetWorkloadInput
- UpdateLensReviewInput
- PillarNotes
- QuestionMetric
- ListTagsForResourceInput
- ListProfileSharesOutput
- TagResourceOutput
- NotificationSummary
- GetLensReviewOutput
- LensReview
- UntagResourceOutput
- GetConsolidatedReportInput
- ChoiceUpdate
- CheckSummary
- ProfileQuestionUpdate
- GetMilestoneOutput
- Milestone
- CreateLensVersionOutput
- UpdateAnswerOutput
- Answer
- ListAnswersOutput
- ProfileTemplateChoice
- UpdateWorkloadInput
- TagMap
- ListLensReviewImprovementsOutput
- ChoiceAnswer
- ListShareInvitationsOutput
- ListLensReviewsInput
- DeleteWorkloadShareInput
- CreateLensShareOutput
- ListCheckSummariesOutput
- PillarReviewSummary
- GetLensReviewReportOutput
- LensReviewReport
- ChoiceContent
- ListProfileNotificationsOutput
- UpdateGlobalSettingsInput
- CreateMilestoneInput
- ListLensReviewsOutput
- ListNotificationsOutput
- ShareInvitationSummary
- PillarMetric
- ListLensesOutput
- UpdateShareInvitationOutput
- ShareInvitation
- AssociateProfilesInput
- DeleteLensInput
- GetAnswerOutput
- ListNotificationsInput
- GetMilestoneInput
- ListLensSharesInput
- WorkloadShareSummary
- CreateWorkloadShareOutput
- ListProfileNotificationsInput
- UpdateWorkloadShareInput
- ListWorkloadSharesOutput
- UpdateProfileOutput
- ImportLensInput
- DeleteWorkloadInput
- GetProfileTemplateInput
- ListMilestonesOutput
- CreateWorkloadShareInput
- CreateProfileOutput
- ProfileQuestion
- DeleteProfileInput
- ProfileShareSummary
- ExportLensOutput
- Choice
- AdditionalResources
- GetLensReviewReportInput
- GetProfileInput
- ProfileChoice
- UpdateShareInvitationInput
- ExportLensInput
- ListCheckDetailsInput
- CreateProfileShareInput
- GetAnswerInput
- UntagResourceInput
- ListCheckDetailsOutput
- CreateWorkloadInput
- ListMilestonesInput
- ListShareInvitationsInput
- ListProfilesInput
- UpdateProfileInput
- UpdateWorkloadShareOutput
- WorkloadShare
- ListCheckSummariesInput
- UpgradeProfileVersionInput
- UpdateWorkloadOutput
- LensShareSummary
- LensSummary
- UpgradeLensReviewInput
- ConsolidatedReportMetric
- DeleteProfileShareInput
- ListWorkloadsOutput
- ListAnswersInput
- ProfileNotificationSummary
- GetLensInput
- ListTagsForResourceOutput
- GetLensVersionDifferenceInput
- LensReviewSummary
- CreateLensShareInput
- CreateMilestoneOutput
- ListLensReviewImprovementsInput
- PillarDifference
- DisassociateLensesInput
- TagResourceInput
- ListWorkloadSharesInput
- CreateLensVersionInput
- WorkloadProfile
- GetWorkloadOutput
- ImportLensOutput
- GetConsolidatedReportOutput
- MilestoneSummary
- ListLensSharesOutput
- UpdateAnswerInput
- ListWorkloadsInput
- CreateProfileInput
- QuestionDifference
- CreateWorkloadOutput
- UpdateLensReviewOutput
context_file: json-ld/amazon-well-architected-tool-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-well-architected-tool/refs/heads/main/json-ld/amazon-well-architected-tool-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Well Architected Tool from Amazon Well-Architected Tool.
layout: jsonld
name: Amazon Well Architected Tool Context
namespaces:
- prefix: amz
  uri: https://amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ChoiceId
  type: string
- container: ''
  name: Status
  type: string
- container: ''
  name: Reason
  type: string
- container: ''
  name: ProfileArn
  type: string
- container: ''
  name: ProfileVersion
  type: string
- container: ''
  name: ProfileName
  type: string
- container: ''
  name: ProfileDescription
  type: string
- container: ''
  name: Owner
  type: string
- container: ''
  name: CreatedAt
  type: string
- container: ''
  name: UpdatedAt
  type: string
- container: ''
  name: DisplayText
  type: string
- container: ''
  name: ImprovementPlanUrl
  type: string
- container: ''
  name: ChoiceTitle
  type: string
- container: ''
  name: WorkloadSummary
  type: string
- container: ''
  name: WorkloadId
  type: string
- container: ''
  name: WorkloadArn
  type: string
- container: ''
  name: WorkloadName
  type: string
- container: ''
  name: Lenses
  type: string
- container: ''
  name: ImprovementStatus
  type: string
- container: ''
  name: Profiles
  type: string
- container: ''
  name: PrioritizedRiskCounts
  type: string
- container: ''
  name: Id
  type: string
- container: ''
  name: Name
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: Provider
  type: string
- container: ''
  name: LensArn
  type: string
- container: ''
  name: PillarId
  type: string
- container: ''
  name: QuestionId
  type: string
- container: ''
  name: AccountId
  type: string
- container: ''
  name: FlaggedResources
  type: string
- container: ''
  name: ProfileArns
  type: string
- container: ''
  name: ProfileTemplate
  type: string
- container: ''
  name: TemplateName
  type: string
- container: ''
  name: TemplateQuestions
  type: string
- container: ''
  name: QuestionTitle
  type: string
- container: ''
  name: QuestionDescription
  type: string
- container: ''
  name: QuestionChoices
  type: string
- container: ''
  name: MinSelectedChoices
  type: string
- container: ''
  name: MaxSelectedChoices
  type: string
- container: ''
  name: ProfileSummaries
  type: string
- container: ''
  name: NextToken
  type: string
- container: ''
  name: LensAliases
  type: string
- container: ''
  name: Risk
  type: string
- container: ''
  name: ImprovementPlans
  type: string
- container: ''
  name: TrustedAdvisorIntegrationStatus
  type: string
- container: ''
  name: WorkloadResourceDefinition
  type: string
- container: ''
  name: AccountSummary
  type: string
- container: ''
  name: ShareId
  type: string
- container: ''
  name: LensUpgradeSummary
  type: string
- container: ''
  name: LensAlias
  type: string
- container: ''
  name: CurrentLensVersion
  type: string
- container: ''
  name: LatestLensVersion
  type: string
- container: ''
  name: VersionDifferences
  type: string
- container: ''
  name: PillarDifferences
  type: string
- container: ''
  name: Choices
  type: string
- container: ''
  name: SelectedChoices
  type: string
- container: ''
  name: ChoiceAnswerSummaries
  type: string
- container: ''
  name: IsApplicable
  type: string
- container: ''
  name: QuestionType
  type: string
- container: ''
  name: BaseLensVersion
  type: string
- container: ''
  name: TargetLensVersion
  type: string
- container: ''
  name: Pillars
  type: string
- container: ''
  name: LensNotes
  type: string
- container: ''
  name: BestPractices
  type: string
- container: ''
  name: ProfileShareSummaries
  type: string
- container: ''
  name: ChoiceUpdates
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: MilestoneNumber
  type: string
- container: ''
  name: Notes
  type: string
- container: ''
  name: SelectedChoiceIds
  type: string
- container: ''
  name: LensVersion
  type: string
- container: ''
  name: AnswerSummaries
  type: string
- container: ''
  name: ChoiceDescription
  type: string
- container: ''
  name: Environment
  type: string
- container: ''
  name: AccountIds
  type: string
- container: ''
  name: AwsRegions
  type: string
- container: ''
  name: NonAwsRegions
  type: string
- container: ''
  name: PillarPriorities
  type: string
- container: ''
  name: ArchitecturalDesign
  type: string
- container: ''
  name: ReviewOwner
  type: string
- container: ''
  name: IsReviewOwnerUpdateAcknowledged
  type: string
- container: ''
  name: IndustryType
  type: string
- container: ''
  name: Industry
  type: string
- container: ''
  name: DiscoveryConfig
  type: string
- container: ''
  name: Applications
  type: string
- container: ''
  name: ImprovementSummaries
  type: string
- container: ''
  name: ShareInvitationSummaries
  type: string
- container: ''
  name: CheckSummaries
  type: string
- container: ''
  name: PillarName
  type: string
- container: ''
  name: Url
  type: string
- container: ''
  name: NotificationSummaries
  type: string
- container: ''
  name: OrganizationSharingStatus
  type: string
- container: ''
  name: DiscoveryIntegrationStatus
  type: string
- container: ''
  name: MilestoneName
  type: string
- container: ''
  name: ClientRequestToken
  type: string
- container: ''
  name: LensReviewSummaries
  type: string
- container: ''
  name: ShareInvitationId
  type: string
- container: ''
  name: SharedBy
  type: string
- container: ''
  name: SharedWith
  type: string
- container: ''
  name: PermissionType
  type: string
- container: ''
  name: ShareResourceType
  type: string
- container: ''
  name: LensName
  type: string
- container: ''
  name: Questions
  type: string
- container: ''
  name: LensSummaries
  type: string
- container: ''
  name: MaxResults
  type: string
- container: ''
  name: StatusMessage
  type: string
- container: ''
  name: WorkloadShareSummaries
  type: string
- container: ''
  name: Tags
  type: string
- container: ''
  name: Workload
  type: string
- container: ''
  name: ReviewRestrictionDate
  type: string
- container: ''
  name: JSONString
  type: string
- container: ''
  name: MilestoneSummaries
  type: string
- container: ''
  name: LensJSON
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: HelpfulResource
  type: string
- container: ''
  name: ImprovementPlan
  type: string
- container: ''
  name: RecordedAt
  type: string
- container: ''
  name: ShareInvitationAction
  type: string
- container: ''
  name: CheckDetails
  type: string
- container: ''
  name: ProfileQuestions
  type: string
- container: ''
  name: HelpfulResourceUrl
  type: string
- container: ''
  name: HelpfulResourceDisplayText
  type: string
- container: ''
  name: ChoiceAnswers
  type: string
- container: ''
  name: LensType
  type: string
- container: ''
  name: LensStatus
  type: string
- container: ''
  name: MetricType
  type: string
- container: ''
  name: LensesAppliedCount
  type: string
- container: ''
  name: PillarReviewSummaries
  type: string
- container: ''
  name: WorkloadSummaries
  type: string
- container: ''
  name: Base64String
  type: string
- container: ''
  name: CurrentProfileVersion
  type: string
- container: ''
  name: LatestProfileVersion
  type: string
- container: ''
  name: Content
  type: string
- container: ''
  name: DifferenceStatus
  type: string
- container: ''
  name: QuestionDifferences
  type: string
- container: ''
  name: IsMajorVersion
  type: string
- container: ''
  name: Metrics
  type: string
- container: ''
  name: LensShareSummaries
  type: string
- container: ''
  name: WorkloadNamePrefix
  type: string
property_count: 139
provider_name: Amazon Well-Architected Tool
provider_slug: amazon-well-architected-tool
slug: amazon-well-architected-tool-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amz\": \"https://amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ChoiceAnswerSummary\": \"amz:ChoiceAnswerSummary\",\n    \"ChoiceId\": {\n      \"@id\": \"amz:ChoiceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Status\": {\n      \"@id\": \"amz:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Reason\": {\n      \"@id\": \"amz:Reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileSummary\": \"amz:ProfileSummary\",\n    \"ProfileArn\": {\n      \"@id\": \"amz:ProfileArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileVersion\": {\n      \"@id\": \"amz:ProfileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileName\": {\n      \"@id\": \"amz:ProfileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileDescription\": {\n      \"@id\": \"amz:ProfileDescription\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"Owner\": {\n      \"@id\": \"amz:Owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreatedAt\": {\n      \"@id\": \"amz:CreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdatedAt\": {\n      \"@id\": \"amz:UpdatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChoiceImprovementPlan\": \"amz:ChoiceImprovementPlan\",\n    \"DisplayText\": {\n      \"@id\": \"amz:DisplayText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImprovementPlanUrl\": {\n      \"@id\": \"amz:ImprovementPlanUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BestPractice\": \"amz:BestPractice\",\n    \"ChoiceTitle\": {\n      \"@id\": \"amz:ChoiceTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadSummary\": {\n      \"@id\": \"amz:WorkloadSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadId\": {\n      \"@id\": \"amz:WorkloadId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadArn\": {\n      \"\
  @id\": \"amz:WorkloadArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadName\": {\n      \"@id\": \"amz:WorkloadName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Lenses\": {\n      \"@id\": \"amz:Lenses\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RiskCounts\": \"amz:RiskCounts\",\n    \"ImprovementStatus\": {\n      \"@id\": \"amz:ImprovementStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Profiles\": {\n      \"@id\": \"amz:Profiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PrioritizedRiskCounts\": {\n      \"@id\": \"amz:PrioritizedRiskCounts\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckDetail\": \"amz:CheckDetail\",\n    \"Id\": {\n      \"@id\": \"amz:Id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Name\": {\n      \"@id\": \"amz:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"amz:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Provider\": {\n      \"@id\": \"amz:Provider\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"LensArn\": {\n      \"@id\": \"amz:LensArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarId\": {\n      \"@id\": \"amz:PillarId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuestionId\": {\n      \"@id\": \"amz:QuestionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountId\": {\n      \"@id\": \"amz:AccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FlaggedResources\": {\n      \"@id\": \"amz:FlaggedResources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisassociateProfilesInput\": \"amz:DisassociateProfilesInput\",\n    \"ProfileArns\": {\n      \"@id\": \"amz:ProfileArns\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteLensShareInput\": \"amz:DeleteLensShareInput\",\n    \"ProfileTemplate\": {\n      \"@id\": \"amz:ProfileTemplate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateName\": {\n      \"@id\": \"amz:TemplateName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TemplateQuestions\"\
  : {\n      \"@id\": \"amz:TemplateQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetProfileOutput\": \"amz:GetProfileOutput\",\n    \"Profile\": \"amz:Profile\",\n    \"ProfileTemplateQuestion\": \"amz:ProfileTemplateQuestion\",\n    \"QuestionTitle\": {\n      \"@id\": \"amz:QuestionTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuestionDescription\": {\n      \"@id\": \"amz:QuestionDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuestionChoices\": {\n      \"@id\": \"amz:QuestionChoices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MinSelectedChoices\": {\n      \"@id\": \"amz:MinSelectedChoices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MaxSelectedChoices\": {\n      \"@id\": \"amz:MaxSelectedChoices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListProfilesOutput\": \"amz:ListProfilesOutput\",\n    \"ProfileSummaries\": {\n      \"@id\": \"amz:ProfileSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NextToken\": {\n\
  \      \"@id\": \"amz:NextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AssociateLensesInput\": \"amz:AssociateLensesInput\",\n    \"LensAliases\": {\n      \"@id\": \"amz:LensAliases\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListLensesInput\": \"amz:ListLensesInput\",\n    \"ImprovementSummary\": \"amz:ImprovementSummary\",\n    \"Risk\": {\n      \"@id\": \"amz:Risk\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImprovementPlans\": {\n      \"@id\": \"amz:ImprovementPlans\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadDiscoveryConfig\": \"amz:WorkloadDiscoveryConfig\",\n    \"TrustedAdvisorIntegrationStatus\": {\n      \"@id\": \"amz:TrustedAdvisorIntegrationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadResourceDefinition\": {\n      \"@id\": \"amz:WorkloadResourceDefinition\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListProfileSharesInput\": \"amz:ListProfileSharesInput\",\n    \"AccountSummary\": {\n      \"@id\": \"amz:AccountSummary\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateProfileShareOutput\": \"amz:CreateProfileShareOutput\",\n    \"ShareId\": {\n      \"@id\": \"amz:ShareId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensUpgradeSummary\": {\n      \"@id\": \"amz:LensUpgradeSummary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensAlias\": {\n      \"@id\": \"amz:LensAlias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CurrentLensVersion\": {\n      \"@id\": \"amz:CurrentLensVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LatestLensVersion\": {\n      \"@id\": \"amz:LatestLensVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"VersionDifferences\": {\n      \"@id\": \"amz:VersionDifferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarDifferences\": {\n      \"@id\": \"amz:PillarDifferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AnswerSummary\": \"amz:AnswerSummary\",\n    \"Choices\": {\n      \"@id\": \"amz:Choices\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"SelectedChoices\": {\n      \"@id\": \"amz:SelectedChoices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChoiceAnswerSummaries\": {\n      \"@id\": \"amz:ChoiceAnswerSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsApplicable\": {\n      \"@id\": \"amz:IsApplicable\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuestionType\": {\n      \"@id\": \"amz:QuestionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetLensReviewInput\": \"amz:GetLensReviewInput\",\n    \"GetProfileTemplateOutput\": \"amz:GetProfileTemplateOutput\",\n    \"GetLensOutput\": \"amz:GetLensOutput\",\n    \"Lens\": \"amz:Lens\",\n    \"GetLensVersionDifferenceOutput\": \"amz:GetLensVersionDifferenceOutput\",\n    \"BaseLensVersion\": {\n      \"@id\": \"amz:BaseLensVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TargetLensVersion\": {\n      \"@id\": \"amz:TargetLensVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensMetric\": \"amz:LensMetric\"\
  ,\n    \"Pillars\": {\n      \"@id\": \"amz:Pillars\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetWorkloadInput\": \"amz:GetWorkloadInput\",\n    \"UpdateLensReviewInput\": \"amz:UpdateLensReviewInput\",\n    \"LensNotes\": {\n      \"@id\": \"amz:LensNotes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarNotes\": \"amz:PillarNotes\",\n    \"QuestionMetric\": \"amz:QuestionMetric\",\n    \"BestPractices\": {\n      \"@id\": \"amz:BestPractices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListTagsForResourceInput\": \"amz:ListTagsForResourceInput\",\n    \"ListProfileSharesOutput\": \"amz:ListProfileSharesOutput\",\n    \"ProfileShareSummaries\": {\n      \"@id\": \"amz:ProfileShareSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChoiceUpdates\": {\n      \"@id\": \"amz:ChoiceUpdates\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagResourceOutput\": \"amz:TagResourceOutput\",\n    \"NotificationSummary\": \"amz:NotificationSummary\",\n    \"Type\"\
  : {\n      \"@id\": \"amz:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetLensReviewOutput\": \"amz:GetLensReviewOutput\",\n    \"MilestoneNumber\": {\n      \"@id\": \"amz:MilestoneNumber\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensReview\": \"amz:LensReview\",\n    \"UntagResourceOutput\": \"amz:UntagResourceOutput\",\n    \"GetConsolidatedReportInput\": \"amz:GetConsolidatedReportInput\",\n    \"ChoiceUpdate\": \"amz:ChoiceUpdate\",\n    \"Notes\": {\n      \"@id\": \"amz:Notes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CheckSummary\": \"amz:CheckSummary\",\n    \"ProfileQuestionUpdate\": \"amz:ProfileQuestionUpdate\",\n    \"SelectedChoiceIds\": {\n      \"@id\": \"amz:SelectedChoiceIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMilestoneOutput\": \"amz:GetMilestoneOutput\",\n    \"Milestone\": \"amz:Milestone\",\n    \"CreateLensVersionOutput\": \"amz:CreateLensVersionOutput\",\n    \"LensVersion\": {\n      \"@id\": \"amz:LensVersion\",\n\
  \      \"@type\": \"xsd:string\"\n    },\n    \"UpdateAnswerOutput\": \"amz:UpdateAnswerOutput\",\n    \"Answer\": \"amz:Answer\",\n    \"ListAnswersOutput\": \"amz:ListAnswersOutput\",\n    \"AnswerSummaries\": {\n      \"@id\": \"amz:AnswerSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProfileTemplateChoice\": \"amz:ProfileTemplateChoice\",\n    \"ChoiceDescription\": {\n      \"@id\": \"amz:ChoiceDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateWorkloadInput\": \"amz:UpdateWorkloadInput\",\n    \"Environment\": {\n      \"@id\": \"amz:Environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AccountIds\": {\n      \"@id\": \"amz:AccountIds\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AwsRegions\": {\n      \"@id\": \"amz:AwsRegions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NonAwsRegions\": {\n      \"@id\": \"amz:NonAwsRegions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarPriorities\": {\n      \"@id\": \"amz:PillarPriorities\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ArchitecturalDesign\": {\n      \"@id\": \"amz:ArchitecturalDesign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReviewOwner\": {\n      \"@id\": \"amz:ReviewOwner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsReviewOwnerUpdateAcknowledged\": {\n      \"@id\": \"amz:IsReviewOwnerUpdateAcknowledged\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IndustryType\": {\n      \"@id\": \"amz:IndustryType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Industry\": {\n      \"@id\": \"amz:Industry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DiscoveryConfig\": {\n      \"@id\": \"amz:DiscoveryConfig\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Applications\": {\n      \"@id\": \"amz:Applications\",\n      \"@type\": \"xsd:string\"\n    },\n    \"TagMap\": \"amz:TagMap\",\n    \"ListLensReviewImprovementsOutput\": \"amz:ListLensReviewImprovementsOutput\",\n    \"ImprovementSummaries\": {\n      \"@id\": \"amz:ImprovementSummaries\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ChoiceAnswer\": \"amz:ChoiceAnswer\",\n    \"ListShareInvitationsOutput\": \"amz:ListShareInvitationsOutput\",\n    \"ShareInvitationSummaries\": {\n      \"@id\": \"amz:ShareInvitationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListLensReviewsInput\": \"amz:ListLensReviewsInput\",\n    \"DeleteWorkloadShareInput\": \"amz:DeleteWorkloadShareInput\",\n    \"CreateLensShareOutput\": \"amz:CreateLensShareOutput\",\n    \"ListCheckSummariesOutput\": \"amz:ListCheckSummariesOutput\",\n    \"CheckSummaries\": {\n      \"@id\": \"amz:CheckSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarReviewSummary\": \"amz:PillarReviewSummary\",\n    \"PillarName\": {\n      \"@id\": \"amz:PillarName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetLensReviewReportOutput\": \"amz:GetLensReviewReportOutput\",\n    \"LensReviewReport\": \"amz:LensReviewReport\",\n    \"ChoiceContent\": \"amz:ChoiceContent\",\n    \"Url\"\
  : {\n      \"@id\": \"amz:Url\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListProfileNotificationsOutput\": \"amz:ListProfileNotificationsOutput\",\n    \"NotificationSummaries\": {\n      \"@id\": \"amz:NotificationSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateGlobalSettingsInput\": \"amz:UpdateGlobalSettingsInput\",\n    \"OrganizationSharingStatus\": {\n      \"@id\": \"amz:OrganizationSharingStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DiscoveryIntegrationStatus\": {\n      \"@id\": \"amz:DiscoveryIntegrationStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMilestoneInput\": \"amz:CreateMilestoneInput\",\n    \"MilestoneName\": {\n      \"@id\": \"amz:MilestoneName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ClientRequestToken\": {\n      \"@id\": \"amz:ClientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListLensReviewsOutput\": \"amz:ListLensReviewsOutput\",\n    \"LensReviewSummaries\": {\n      \"@id\"\
  : \"amz:LensReviewSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListNotificationsOutput\": \"amz:ListNotificationsOutput\",\n    \"ShareInvitationSummary\": \"amz:ShareInvitationSummary\",\n    \"ShareInvitationId\": {\n      \"@id\": \"amz:ShareInvitationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedBy\": {\n      \"@id\": \"amz:SharedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SharedWith\": {\n      \"@id\": \"amz:SharedWith\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PermissionType\": {\n      \"@id\": \"amz:PermissionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ShareResourceType\": {\n      \"@id\": \"amz:ShareResourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensName\": {\n      \"@id\": \"amz:LensName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarMetric\": \"amz:PillarMetric\",\n    \"Questions\": {\n      \"@id\": \"amz:Questions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ListLensesOutput\"\
  : \"amz:ListLensesOutput\",\n    \"LensSummaries\": {\n      \"@id\": \"amz:LensSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateShareInvitationOutput\": \"amz:UpdateShareInvitationOutput\",\n    \"ShareInvitation\": \"amz:ShareInvitation\",\n    \"AssociateProfilesInput\": \"amz:AssociateProfilesInput\",\n    \"DeleteLensInput\": \"amz:DeleteLensInput\",\n    \"GetAnswerOutput\": \"amz:GetAnswerOutput\",\n    \"ListNotificationsInput\": \"amz:ListNotificationsInput\",\n    \"MaxResults\": {\n      \"@id\": \"amz:MaxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetMilestoneInput\": \"amz:GetMilestoneInput\",\n    \"ListLensSharesInput\": \"amz:ListLensSharesInput\",\n    \"WorkloadShareSummary\": \"amz:WorkloadShareSummary\",\n    \"StatusMessage\": {\n      \"@id\": \"amz:StatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateWorkloadShareOutput\": \"amz:CreateWorkloadShareOutput\",\n    \"ListProfileNotificationsInput\": \"amz:ListProfileNotificationsInput\"\
  ,\n    \"UpdateWorkloadShareInput\": \"amz:UpdateWorkloadShareInput\",\n    \"ListWorkloadSharesOutput\": \"amz:ListWorkloadSharesOutput\",\n    \"WorkloadShareSummaries\": {\n      \"@id\": \"amz:WorkloadShareSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateProfileOutput\": \"amz:UpdateProfileOutput\",\n    \"Tags\": {\n      \"@id\": \"amz:Tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Workload\": {\n      \"@id\": \"amz:Workload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReviewRestrictionDate\": {\n      \"@id\": \"amz:ReviewRestrictionDate\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImportLensInput\": \"amz:ImportLensInput\",\n    \"JSONString\": {\n      \"@id\": \"amz:JSONString\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteWorkloadInput\": \"amz:DeleteWorkloadInput\",\n    \"GetProfileTemplateInput\": \"amz:GetProfileTemplateInput\",\n    \"ListMilestonesOutput\": \"amz:ListMilestonesOutput\",\n    \"MilestoneSummaries\": {\n\
  \      \"@id\": \"amz:MilestoneSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateWorkloadShareInput\": \"amz:CreateWorkloadShareInput\",\n    \"CreateProfileOutput\": \"amz:CreateProfileOutput\",\n    \"ProfileQuestion\": \"amz:ProfileQuestion\",\n    \"DeleteProfileInput\": \"amz:DeleteProfileInput\",\n    \"ProfileShareSummary\": \"amz:ProfileShareSummary\",\n    \"ExportLensOutput\": \"amz:ExportLensOutput\",\n    \"LensJSON\": {\n      \"@id\": \"amz:LensJSON\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Choice\": \"amz:Choice\",\n    \"Title\": {\n      \"@id\": \"amz:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HelpfulResource\": {\n      \"@id\": \"amz:HelpfulResource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ImprovementPlan\": {\n      \"@id\": \"amz:ImprovementPlan\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AdditionalResources\": \"amz:AdditionalResources\",\n    \"GetLensReviewReportInput\": \"amz:GetLensReviewReportInput\",\n\
  \    \"GetProfileInput\": \"amz:GetProfileInput\",\n    \"ProfileChoice\": \"amz:ProfileChoice\",\n    \"RecordedAt\": {\n      \"@id\": \"amz:RecordedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateShareInvitationInput\": \"amz:UpdateShareInvitationInput\",\n    \"ShareInvitationAction\": {\n      \"@id\": \"amz:ShareInvitationAction\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ExportLensInput\": \"amz:ExportLensInput\",\n    \"ListCheckDetailsInput\": \"amz:ListCheckDetailsInput\",\n    \"CreateProfileShareInput\": \"amz:CreateProfileShareInput\",\n    \"GetAnswerInput\": \"amz:GetAnswerInput\",\n    \"UntagResourceInput\": \"amz:UntagResourceInput\",\n    \"ListCheckDetailsOutput\": \"amz:ListCheckDetailsOutput\",\n    \"CheckDetails\": {\n      \"@id\": \"amz:CheckDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateWorkloadInput\": \"amz:CreateWorkloadInput\",\n    \"ListMilestonesInput\": \"amz:ListMilestonesInput\",\n    \"ListShareInvitationsInput\"\
  : \"amz:ListShareInvitationsInput\",\n    \"ListProfilesInput\": \"amz:ListProfilesInput\",\n    \"UpdateProfileInput\": \"amz:UpdateProfileInput\",\n    \"ProfileQuestions\": {\n      \"@id\": \"amz:ProfileQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateWorkloadShareOutput\": \"amz:UpdateWorkloadShareOutput\",\n    \"WorkloadShare\": \"amz:WorkloadShare\",\n    \"ListCheckSummariesInput\": \"amz:ListCheckSummariesInput\",\n    \"UpgradeProfileVersionInput\": \"amz:UpgradeProfileVersionInput\",\n    \"HelpfulResourceUrl\": {\n      \"@id\": \"amz:HelpfulResourceUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HelpfulResourceDisplayText\": {\n      \"@id\": \"amz:HelpfulResourceDisplayText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ChoiceAnswers\": {\n      \"@id\": \"amz:ChoiceAnswers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateWorkloadOutput\": \"amz:UpdateWorkloadOutput\",\n    \"LensShareSummary\": \"amz:LensShareSummary\",\n    \"LensSummary\"\
  : \"amz:LensSummary\",\n    \"LensType\": {\n      \"@id\": \"amz:LensType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensStatus\": {\n      \"@id\": \"amz:LensStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpgradeLensReviewInput\": \"amz:UpgradeLensReviewInput\",\n    \"ConsolidatedReportMetric\": \"amz:ConsolidatedReportMetric\",\n    \"MetricType\": {\n      \"@id\": \"amz:MetricType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LensesAppliedCount\": {\n      \"@id\": \"amz:LensesAppliedCount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PillarReviewSummaries\": {\n      \"@id\": \"amz:PillarReviewSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DeleteProfileShareInput\": \"amz:DeleteProfileShareInput\",\n    \"ListWorkloadsOutput\": \"amz:ListWorkloadsOutput\",\n    \"WorkloadSummaries\": {\n      \"@id\": \"amz:WorkloadSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Base64String\": {\n      \"@id\": \"amz:Base64String\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"ListAnswersInput\": \"amz:ListAnswersInput\",\n    \"ProfileNotificationSummary\": \"amz:ProfileNotificationSummary\",\n    \"CurrentProfileVersion\": {\n      \"@id\": \"amz:CurrentProfileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LatestProfileVersion\": {\n      \"@id\": \"amz:LatestProfileVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"GetLensInput\": \"amz:GetLensInput\",\n    \"ListTagsForResourceOutput\": \"amz:ListTagsForResourceOutput\",\n    \"GetLensVersionDifferenceInput\": \"amz:GetLensVersionDifferenceInput\",\n    \"LensReviewSummary\": \"amz:LensReviewSummary\",\n    \"CreateLensShareInput\": \"amz:CreateLensShareInput\",\n    \"Content\": {\n      \"@id\": \"amz:Content\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateMilestoneOutput\": \"amz:CreateMilestoneOutput\",\n    \"ListLensReviewImprovementsInput\": \"amz:ListLensReviewImprovementsInput\",\n    \"PillarDifference\": \"amz:PillarDifference\"\
  ,\n    \"DifferenceStatus\": {\n      \"@id\": \"amz:DifferenceStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"QuestionDifferences\": {\n      \"@id\": \"amz:QuestionDifferences\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisassociateLensesInput\": \"amz:DisassociateLensesInput\",\n    \"TagResourceInput\": \"amz:TagResourceInput\",\n    \"ListWorkloadSharesInput\": \"amz:ListWorkloadSharesInput\",\n    \"CreateLensVersionInput\": \"amz:CreateLensVersionInput\",\n    \"IsMajorVersion\": {\n      \"@id\": \"amz:IsMajorVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"WorkloadProfile\": \"amz:WorkloadProfile\",\n    \"GetWorkloadOutput\": \"amz:GetWorkloadOutput\",\n    \"ImportLensOutput\": \"amz:ImportLensOutput\",\n    \"GetConsolidatedReportOutput\": \"amz:GetConsolidatedReportOutput\",\n    \"Metrics\": {\n      \"@id\": \"amz:Metrics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"MilestoneSummary\": \"amz:MilestoneSummary\",\n    \"ListLensSharesOutput\"\
  : \"amz:ListLensSharesOutput\",\n    \"LensShareSummaries\": {\n      \"@id\": \"amz:LensShareSummaries\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UpdateAnswerInput\": \"amz:UpdateAnswerInput\",\n    \"ListWorkloadsInput\": \"amz:ListWorkloadsInput\",\n    \"WorkloadNamePrefix\": {\n      \"@id\": \"amz:WorkloadNamePrefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CreateProfileInput\": \"amz:CreateProfileInput\",\n    \"QuestionDifference\": \"amz:QuestionDifference\",\n    \"CreateWorkloadOutput\": \"amz:CreateWorkloadOutput\",\n    \"UpdateLensReviewOutput\": \"amz:UpdateLensReviewOutput\"\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-well-architected-tool/refs/heads/main/json-ld/amazon-well-architected-tool-context.jsonld
tags:
- Architecture
- AWS
- Best Practices
- Cloud Governance
- Well-Architected
- Workloads
- JSON-LD
- Linked Data
- Semantic Web
---
