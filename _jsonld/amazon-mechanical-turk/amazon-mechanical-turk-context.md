---
api_specs:
- filename: amazon-mechanical-turk-openapi-original.yaml
  format: yaml
  label: Amazon Mechanical Turk API
  slug: amazon-mturk-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/openapi/amazon-mechanical-turk-openapi-original.yaml
class_count: 96
classes:
- AcceptQualificationRequestRequest
- AcceptQualificationRequestResponse
- ApproveAssignmentRequest
- ApproveAssignmentResponse
- Assignment
- AssociateQualificationWithWorkerRequest
- AssociateQualificationWithWorkerResponse
- BonusPayment
- CreateAdditionalAssignmentsForHITRequest
- CreateAdditionalAssignmentsForHITResponse
- CreateHITRequest
- CreateHITResponse
- CreateHITTypeRequest
- CreateHITTypeResponse
- CreateHITWithHITTypeRequest
- CreateHITWithHITTypeResponse
- CreateQualificationTypeRequest
- CreateQualificationTypeResponse
- CreateWorkerBlockRequest
- CreateWorkerBlockResponse
- DeleteHITRequest
- DeleteHITResponse
- DeleteQualificationTypeRequest
- DeleteQualificationTypeResponse
- DeleteWorkerBlockRequest
- DeleteWorkerBlockResponse
- DisassociateQualificationFromWorkerRequest
- DisassociateQualificationFromWorkerResponse
- GetAccountBalanceRequest
- GetAccountBalanceResponse
- GetAssignmentRequest
- GetAssignmentResponse
- GetFileUploadURLRequest
- GetFileUploadURLResponse
- GetHITRequest
- GetHITResponse
- GetQualificationScoreRequest
- GetQualificationScoreResponse
- GetQualificationTypeRequest
- GetQualificationTypeResponse
- HIT
- HITLayoutParameter
- ListAssignmentsForHITRequest
- ListAssignmentsForHITResponse
- ListBonusPaymentsRequest
- ListBonusPaymentsResponse
- ListHITsForQualificationTypeRequest
- ListHITsForQualificationTypeResponse
- ListHITsRequest
- ListHITsResponse
- ListQualificationRequestsRequest
- ListQualificationRequestsResponse
- ListQualificationTypesRequest
- ListQualificationTypesResponse
- ListReviewPolicyResultsForHITRequest
- ListReviewPolicyResultsForHITResponse
- ListReviewableHITsRequest
- ListReviewableHITsResponse
- ListWorkerBlocksRequest
- ListWorkerBlocksResponse
- ListWorkersWithQualificationTypeRequest
- ListWorkersWithQualificationTypeResponse
- Locale
- NotificationSpecification
- NotifyWorkersFailureStatus
- NotifyWorkersRequest
- NotifyWorkersResponse
- ParameterMapEntry
- PolicyParameter
- Qualification
- QualificationRequest
- QualificationRequirement
- QualificationType
- RejectAssignmentRequest
- RejectAssignmentResponse
- RejectQualificationRequestRequest
- RejectQualificationRequestResponse
- ReviewActionDetail
- ReviewPolicy
- ReviewReport
- ReviewResultDetail
- SendBonusRequest
- SendBonusResponse
- SendTestEventNotificationRequest
- SendTestEventNotificationResponse
- UpdateExpirationForHITRequest
- UpdateExpirationForHITResponse
- UpdateHITReviewStatusRequest
- UpdateHITReviewStatusResponse
- UpdateHITTypeOfHITRequest
- UpdateHITTypeOfHITResponse
- UpdateNotificationSettingsRequest
- UpdateNotificationSettingsResponse
- UpdateQualificationTypeRequest
- UpdateQualificationTypeResponse
- WorkerBlock
context_file: json-ld/amazon-mechanical-turk-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/json-ld/amazon-mechanical-turk-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Mechanical Turk from Amazon Mechanical Turk.
layout: jsonld
name: Amazon Mechanical Turk Context
namespaces:
- prefix: amtu
  uri: https://amtu.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: AcceptTime
  type: ''
- container: ''
  name: ActionId
  type: ''
- container: ''
  name: ActionName
  type: ''
- container: ''
  name: ActionsGuarded
  type: ''
- container: ''
  name: Active
  type: ''
- container: ''
  name: Answer
  type: ''
- container: ''
  name: AnswerKey
  type: ''
- container: ''
  name: ApprovalTime
  type: ''
- container: ''
  name: AssignmentDurationInSeconds
  type: ''
- container: ''
  name: AssignmentId
  type: ''
- container: ''
  name: AssignmentReviewPolicy
  type: ''
- container: ''
  name: AssignmentReviewReport
  type: ''
- container: ''
  name: AssignmentStatus
  type: ''
- container: ''
  name: AssignmentStatuses
  type: ''
- container: ''
  name: Assignments
  type: ''
- container: ''
  name: AutoApprovalDelayInSeconds
  type: ''
- container: ''
  name: AutoApprovalTime
  type: ''
- container: ''
  name: AutoGranted
  type: ''
- container: ''
  name: AutoGrantedValue
  type: ''
- container: ''
  name: AvailableBalance
  type: ''
- container: ''
  name: BonusAmount
  type: ''
- container: ''
  name: BonusPayments
  type: ''
- container: ''
  name: Comparator
  type: ''
- container: ''
  name: CompleteTime
  type: ''
- container: ''
  name: Country
  type: ''
- container: ''
  name: CreationTime
  type: ''
- container: ''
  name: Deadline
  type: ''
- container: ''
  name: Description
  type: ''
- container: ''
  name: Destination
  type: ''
- container: ''
  name: ErrorCode
  type: ''
- container: ''
  name: EventTypes
  type: ''
- container: ''
  name: Expiration
  type: ''
- container: ''
  name: ExpireAt
  type: ''
- container: ''
  name: FileUploadURL
  type: ''
- container: ''
  name: GrantTime
  type: ''
- container: ''
  name: HITGroupId
  type: ''
- container: ''
  name: HITId
  type: ''
- container: ''
  name: HITLayoutId
  type: ''
- container: ''
  name: HITLayoutParameters
  type: ''
- container: ''
  name: HITReviewPolicy
  type: ''
- container: ''
  name: HITReviewReport
  type: ''
- container: ''
  name: HITReviewStatus
  type: ''
- container: ''
  name: HITStatus
  type: ''
- container: ''
  name: HITTypeId
  type: ''
- container: ''
  name: HITs
  type: ''
- container: ''
  name: IntegerValue
  type: ''
- container: ''
  name: IntegerValues
  type: ''
- container: ''
  name: IsRequestable
  type: ''
- container: ''
  name: Key
  type: ''
- container: ''
  name: Keywords
  type: ''
- container: ''
  name: LifetimeInSeconds
  type: ''
- container: ''
  name: LocaleValue
  type: ''
- container: ''
  name: LocaleValues
  type: ''
- container: ''
  name: MapEntries
  type: ''
- container: ''
  name: MaxAssignments
  type: ''
- container: ''
  name: MaxResults
  type: ''
- container: ''
  name: MessageText
  type: ''
- container: ''
  name: MustBeOwnedByCaller
  type: ''
- container: ''
  name: MustBeRequestable
  type: ''
- container: ''
  name: Name
  type: ''
- container: ''
  name: NextToken
  type: ''
- container: ''
  name: Notification
  type: ''
- container: ''
  name: NotifyWorkersFailureCode
  type: ''
- container: ''
  name: NotifyWorkersFailureMessage
  type: ''
- container: ''
  name: NotifyWorkersFailureStatuses
  type: ''
- container: ''
  name: NumResults
  type: ''
- container: ''
  name: NumberOfAdditionalAssignments
  type: ''
- container: ''
  name: NumberOfAssignmentsAvailable
  type: ''
- container: ''
  name: NumberOfAssignmentsCompleted
  type: ''
- container: ''
  name: NumberOfAssignmentsPending
  type: ''
- container: ''
  name: OnHoldBalance
  type: ''
- container: ''
  name: OverrideRejection
  type: ''
- container: ''
  name: Parameters
  type: ''
- container: ''
  name: PolicyLevels
  type: ''
- container: ''
  name: PolicyName
  type: ''
- container: ''
  name: QualificationRequestId
  type: ''
- container: ''
  name: QualificationRequests
  type: ''
- container: ''
  name: QualificationRequirements
  type: ''
- container: ''
  name: QualificationTypeId
  type: ''
- container: ''
  name: QualificationTypeStatus
  type: ''
- container: ''
  name: QualificationTypes
  type: ''
- container: ''
  name: Qualifications
  type: ''
- container: ''
  name: Query
  type: ''
- container: ''
  name: Question
  type: ''
- container: ''
  name: QuestionId
  type: ''
- container: ''
  name: QuestionIdentifier
  type: ''
- container: ''
  name: Reason
  type: ''
- container: ''
  name: RejectionTime
  type: ''
- container: ''
  name: RequesterAnnotation
  type: ''
- container: ''
  name: RequesterFeedback
  type: ''
- container: ''
  name: RequiredToPreview
  type: ''
- container: ''
  name: Result
  type: ''
- container: ''
  name: RetrieveActions
  type: ''
- container: ''
  name: RetrieveResults
  type: ''
- container: ''
  name: RetryDelayInSeconds
  type: ''
- container: ''
  name: Revert
  type: ''
- container: ''
  name: ReviewActions
  type: ''
- container: ''
  name: ReviewResults
  type: ''
- container: ''
  name: Reward
  type: ''
- container: ''
  name: SendNotification
  type: ''
- container: ''
  name: Status
  type: ''
- container: ''
  name: Subdivision
  type: ''
- container: ''
  name: Subject
  type: ''
- container: ''
  name: SubjectId
  type: ''
- container: ''
  name: SubjectType
  type: ''
- container: ''
  name: SubmitTime
  type: ''
- container: ''
  name: TargetId
  type: ''
- container: ''
  name: TargetType
  type: ''
- container: ''
  name: Test
  type: ''
- container: ''
  name: TestDurationInSeconds
  type: ''
- container: ''
  name: TestEventType
  type: ''
- container: ''
  name: Title
  type: ''
- container: ''
  name: Transport
  type: ''
- container: ''
  name: UniqueRequestToken
  type: ''
- container: ''
  name: Value
  type: ''
- container: ''
  name: Values
  type: ''
- container: ''
  name: Version
  type: ''
- container: ''
  name: WorkerBlocks
  type: ''
- container: ''
  name: WorkerId
  type: ''
- container: ''
  name: WorkerIds
  type: ''
property_count: 120
provider_name: Amazon Mechanical Turk
provider_slug: amazon-mechanical-turk
slug: amazon-mechanical-turk-context
source_filename: amazon-mechanical-turk-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amtu\": \"https://amtu.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcceptQualificationRequestRequest\": \"amtu:AcceptQualificationRequestRequest\",\n    \"AcceptQualificationRequestResponse\": \"amtu:AcceptQualificationRequestResponse\",\n    \"ApproveAssignmentRequest\": \"amtu:ApproveAssignmentRequest\",\n    \"ApproveAssignmentResponse\": \"amtu:ApproveAssignmentResponse\",\n    \"Assignment\": \"amtu:Assignment\",\n    \"AssociateQualificationWithWorkerRequest\": \"amtu:AssociateQualificationWithWorkerRequest\",\n    \"AssociateQualificationWithWorkerResponse\": \"amtu:AssociateQualificationWithWorkerResponse\",\n    \"BonusPayment\": \"amtu:BonusPayment\",\n    \"CreateAdditionalAssignmentsForHITRequest\": \"amtu:CreateAdditionalAssignmentsForHITRequest\",\n    \"CreateAdditionalAssignmentsForHITResponse\": \"amtu:CreateAdditionalAssignmentsForHITResponse\"\
  ,\n    \"CreateHITRequest\": \"amtu:CreateHITRequest\",\n    \"CreateHITResponse\": \"amtu:CreateHITResponse\",\n    \"CreateHITTypeRequest\": \"amtu:CreateHITTypeRequest\",\n    \"CreateHITTypeResponse\": \"amtu:CreateHITTypeResponse\",\n    \"CreateHITWithHITTypeRequest\": \"amtu:CreateHITWithHITTypeRequest\",\n    \"CreateHITWithHITTypeResponse\": \"amtu:CreateHITWithHITTypeResponse\",\n    \"CreateQualificationTypeRequest\": \"amtu:CreateQualificationTypeRequest\",\n    \"CreateQualificationTypeResponse\": \"amtu:CreateQualificationTypeResponse\",\n    \"CreateWorkerBlockRequest\": \"amtu:CreateWorkerBlockRequest\",\n    \"CreateWorkerBlockResponse\": \"amtu:CreateWorkerBlockResponse\",\n    \"DeleteHITRequest\": \"amtu:DeleteHITRequest\",\n    \"DeleteHITResponse\": \"amtu:DeleteHITResponse\",\n    \"DeleteQualificationTypeRequest\": \"amtu:DeleteQualificationTypeRequest\",\n    \"DeleteQualificationTypeResponse\": \"amtu:DeleteQualificationTypeResponse\",\n    \"DeleteWorkerBlockRequest\"\
  : \"amtu:DeleteWorkerBlockRequest\",\n    \"DeleteWorkerBlockResponse\": \"amtu:DeleteWorkerBlockResponse\",\n    \"DisassociateQualificationFromWorkerRequest\": \"amtu:DisassociateQualificationFromWorkerRequest\",\n    \"DisassociateQualificationFromWorkerResponse\": \"amtu:DisassociateQualificationFromWorkerResponse\",\n    \"GetAccountBalanceRequest\": \"amtu:GetAccountBalanceRequest\",\n    \"GetAccountBalanceResponse\": \"amtu:GetAccountBalanceResponse\",\n    \"GetAssignmentRequest\": \"amtu:GetAssignmentRequest\",\n    \"GetAssignmentResponse\": \"amtu:GetAssignmentResponse\",\n    \"GetFileUploadURLRequest\": \"amtu:GetFileUploadURLRequest\",\n    \"GetFileUploadURLResponse\": \"amtu:GetFileUploadURLResponse\",\n    \"GetHITRequest\": \"amtu:GetHITRequest\",\n    \"GetHITResponse\": \"amtu:GetHITResponse\",\n    \"GetQualificationScoreRequest\": \"amtu:GetQualificationScoreRequest\",\n    \"GetQualificationScoreResponse\": \"amtu:GetQualificationScoreResponse\",\n    \"GetQualificationTypeRequest\"\
  : \"amtu:GetQualificationTypeRequest\",\n    \"GetQualificationTypeResponse\": \"amtu:GetQualificationTypeResponse\",\n    \"HIT\": \"amtu:HIT\",\n    \"HITLayoutParameter\": \"amtu:HITLayoutParameter\",\n    \"ListAssignmentsForHITRequest\": \"amtu:ListAssignmentsForHITRequest\",\n    \"ListAssignmentsForHITResponse\": \"amtu:ListAssignmentsForHITResponse\",\n    \"ListBonusPaymentsRequest\": \"amtu:ListBonusPaymentsRequest\",\n    \"ListBonusPaymentsResponse\": \"amtu:ListBonusPaymentsResponse\",\n    \"ListHITsForQualificationTypeRequest\": \"amtu:ListHITsForQualificationTypeRequest\",\n    \"ListHITsForQualificationTypeResponse\": \"amtu:ListHITsForQualificationTypeResponse\",\n    \"ListHITsRequest\": \"amtu:ListHITsRequest\",\n    \"ListHITsResponse\": \"amtu:ListHITsResponse\",\n    \"ListQualificationRequestsRequest\": \"amtu:ListQualificationRequestsRequest\",\n    \"ListQualificationRequestsResponse\": \"amtu:ListQualificationRequestsResponse\",\n    \"ListQualificationTypesRequest\"\
  : \"amtu:ListQualificationTypesRequest\",\n    \"ListQualificationTypesResponse\": \"amtu:ListQualificationTypesResponse\",\n    \"ListReviewPolicyResultsForHITRequest\": \"amtu:ListReviewPolicyResultsForHITRequest\",\n    \"ListReviewPolicyResultsForHITResponse\": \"amtu:ListReviewPolicyResultsForHITResponse\",\n    \"ListReviewableHITsRequest\": \"amtu:ListReviewableHITsRequest\",\n    \"ListReviewableHITsResponse\": \"amtu:ListReviewableHITsResponse\",\n    \"ListWorkerBlocksRequest\": \"amtu:ListWorkerBlocksRequest\",\n    \"ListWorkerBlocksResponse\": \"amtu:ListWorkerBlocksResponse\",\n    \"ListWorkersWithQualificationTypeRequest\": \"amtu:ListWorkersWithQualificationTypeRequest\",\n    \"ListWorkersWithQualificationTypeResponse\": \"amtu:ListWorkersWithQualificationTypeResponse\",\n    \"Locale\": \"amtu:Locale\",\n    \"NotificationSpecification\": \"amtu:NotificationSpecification\",\n    \"NotifyWorkersFailureStatus\": \"amtu:NotifyWorkersFailureStatus\",\n    \"NotifyWorkersRequest\"\
  : \"amtu:NotifyWorkersRequest\",\n    \"NotifyWorkersResponse\": \"amtu:NotifyWorkersResponse\",\n    \"ParameterMapEntry\": \"amtu:ParameterMapEntry\",\n    \"PolicyParameter\": \"amtu:PolicyParameter\",\n    \"Qualification\": \"amtu:Qualification\",\n    \"QualificationRequest\": \"amtu:QualificationRequest\",\n    \"QualificationRequirement\": \"amtu:QualificationRequirement\",\n    \"QualificationType\": \"amtu:QualificationType\",\n    \"RejectAssignmentRequest\": \"amtu:RejectAssignmentRequest\",\n    \"RejectAssignmentResponse\": \"amtu:RejectAssignmentResponse\",\n    \"RejectQualificationRequestRequest\": \"amtu:RejectQualificationRequestRequest\",\n    \"RejectQualificationRequestResponse\": \"amtu:RejectQualificationRequestResponse\",\n    \"ReviewActionDetail\": \"amtu:ReviewActionDetail\",\n    \"ReviewPolicy\": \"amtu:ReviewPolicy\",\n    \"ReviewReport\": \"amtu:ReviewReport\",\n    \"ReviewResultDetail\": \"amtu:ReviewResultDetail\",\n    \"SendBonusRequest\": \"amtu:SendBonusRequest\"\
  ,\n    \"SendBonusResponse\": \"amtu:SendBonusResponse\",\n    \"SendTestEventNotificationRequest\": \"amtu:SendTestEventNotificationRequest\",\n    \"SendTestEventNotificationResponse\": \"amtu:SendTestEventNotificationResponse\",\n    \"UpdateExpirationForHITRequest\": \"amtu:UpdateExpirationForHITRequest\",\n    \"UpdateExpirationForHITResponse\": \"amtu:UpdateExpirationForHITResponse\",\n    \"UpdateHITReviewStatusRequest\": \"amtu:UpdateHITReviewStatusRequest\",\n    \"UpdateHITReviewStatusResponse\": \"amtu:UpdateHITReviewStatusResponse\",\n    \"UpdateHITTypeOfHITRequest\": \"amtu:UpdateHITTypeOfHITRequest\",\n    \"UpdateHITTypeOfHITResponse\": \"amtu:UpdateHITTypeOfHITResponse\",\n    \"UpdateNotificationSettingsRequest\": \"amtu:UpdateNotificationSettingsRequest\",\n    \"UpdateNotificationSettingsResponse\": \"amtu:UpdateNotificationSettingsResponse\",\n    \"UpdateQualificationTypeRequest\": \"amtu:UpdateQualificationTypeRequest\",\n    \"UpdateQualificationTypeResponse\":\
  \ \"amtu:UpdateQualificationTypeResponse\",\n    \"WorkerBlock\": \"amtu:WorkerBlock\",\n    \"AcceptTime\": {\n      \"@id\": \"amtu:AcceptTime\"\n    },\n    \"ActionId\": {\n      \"@id\": \"amtu:ActionId\"\n    },\n    \"ActionName\": {\n      \"@id\": \"amtu:ActionName\"\n    },\n    \"ActionsGuarded\": {\n      \"@id\": \"amtu:ActionsGuarded\"\n    },\n    \"Active\": {\n      \"@id\": \"amtu:Active\"\n    },\n    \"Answer\": {\n      \"@id\": \"amtu:Answer\"\n    },\n    \"AnswerKey\": {\n      \"@id\": \"amtu:AnswerKey\"\n    },\n    \"ApprovalTime\": {\n      \"@id\": \"amtu:ApprovalTime\"\n    },\n    \"AssignmentDurationInSeconds\": {\n      \"@id\": \"amtu:AssignmentDurationInSeconds\"\n    },\n    \"AssignmentId\": {\n      \"@id\": \"amtu:AssignmentId\"\n    },\n    \"AssignmentReviewPolicy\": {\n      \"@id\": \"amtu:AssignmentReviewPolicy\"\n    },\n    \"AssignmentReviewReport\": {\n      \"@id\": \"amtu:AssignmentReviewReport\"\n    },\n    \"AssignmentStatus\": {\n \
  \     \"@id\": \"amtu:AssignmentStatus\"\n    },\n    \"AssignmentStatuses\": {\n      \"@id\": \"amtu:AssignmentStatuses\"\n    },\n    \"Assignments\": {\n      \"@id\": \"amtu:Assignments\"\n    },\n    \"AutoApprovalDelayInSeconds\": {\n      \"@id\": \"amtu:AutoApprovalDelayInSeconds\"\n    },\n    \"AutoApprovalTime\": {\n      \"@id\": \"amtu:AutoApprovalTime\"\n    },\n    \"AutoGranted\": {\n      \"@id\": \"amtu:AutoGranted\"\n    },\n    \"AutoGrantedValue\": {\n      \"@id\": \"amtu:AutoGrantedValue\"\n    },\n    \"AvailableBalance\": {\n      \"@id\": \"amtu:AvailableBalance\"\n    },\n    \"BonusAmount\": {\n      \"@id\": \"amtu:BonusAmount\"\n    },\n    \"BonusPayments\": {\n      \"@id\": \"amtu:BonusPayments\"\n    },\n    \"Comparator\": {\n      \"@id\": \"amtu:Comparator\"\n    },\n    \"CompleteTime\": {\n      \"@id\": \"amtu:CompleteTime\"\n    },\n    \"Country\": {\n      \"@id\": \"amtu:Country\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"amtu:CreationTime\"\
  \n    },\n    \"Deadline\": {\n      \"@id\": \"amtu:Deadline\"\n    },\n    \"Description\": {\n      \"@id\": \"amtu:Description\"\n    },\n    \"Destination\": {\n      \"@id\": \"amtu:Destination\"\n    },\n    \"ErrorCode\": {\n      \"@id\": \"amtu:ErrorCode\"\n    },\n    \"EventTypes\": {\n      \"@id\": \"amtu:EventTypes\"\n    },\n    \"Expiration\": {\n      \"@id\": \"amtu:Expiration\"\n    },\n    \"ExpireAt\": {\n      \"@id\": \"amtu:ExpireAt\"\n    },\n    \"FileUploadURL\": {\n      \"@id\": \"amtu:FileUploadURL\"\n    },\n    \"GrantTime\": {\n      \"@id\": \"amtu:GrantTime\"\n    },\n    \"HITGroupId\": {\n      \"@id\": \"amtu:HITGroupId\"\n    },\n    \"HITId\": {\n      \"@id\": \"amtu:HITId\"\n    },\n    \"HITLayoutId\": {\n      \"@id\": \"amtu:HITLayoutId\"\n    },\n    \"HITLayoutParameters\": {\n      \"@id\": \"amtu:HITLayoutParameters\"\n    },\n    \"HITReviewPolicy\": {\n      \"@id\": \"amtu:HITReviewPolicy\"\n    },\n    \"HITReviewReport\": {\n     \
  \ \"@id\": \"amtu:HITReviewReport\"\n    },\n    \"HITReviewStatus\": {\n      \"@id\": \"amtu:HITReviewStatus\"\n    },\n    \"HITStatus\": {\n      \"@id\": \"amtu:HITStatus\"\n    },\n    \"HITTypeId\": {\n      \"@id\": \"amtu:HITTypeId\"\n    },\n    \"HITs\": {\n      \"@id\": \"amtu:HITs\"\n    },\n    \"IntegerValue\": {\n      \"@id\": \"amtu:IntegerValue\"\n    },\n    \"IntegerValues\": {\n      \"@id\": \"amtu:IntegerValues\"\n    },\n    \"IsRequestable\": {\n      \"@id\": \"amtu:IsRequestable\"\n    },\n    \"Key\": {\n      \"@id\": \"amtu:Key\"\n    },\n    \"Keywords\": {\n      \"@id\": \"amtu:Keywords\"\n    },\n    \"LifetimeInSeconds\": {\n      \"@id\": \"amtu:LifetimeInSeconds\"\n    },\n    \"LocaleValue\": {\n      \"@id\": \"amtu:LocaleValue\"\n    },\n    \"LocaleValues\": {\n      \"@id\": \"amtu:LocaleValues\"\n    },\n    \"MapEntries\": {\n      \"@id\": \"amtu:MapEntries\"\n    },\n    \"MaxAssignments\": {\n      \"@id\": \"amtu:MaxAssignments\"\n    },\n\
  \    \"MaxResults\": {\n      \"@id\": \"amtu:MaxResults\"\n    },\n    \"MessageText\": {\n      \"@id\": \"amtu:MessageText\"\n    },\n    \"MustBeOwnedByCaller\": {\n      \"@id\": \"amtu:MustBeOwnedByCaller\"\n    },\n    \"MustBeRequestable\": {\n      \"@id\": \"amtu:MustBeRequestable\"\n    },\n    \"Name\": {\n      \"@id\": \"amtu:Name\"\n    },\n    \"NextToken\": {\n      \"@id\": \"amtu:NextToken\"\n    },\n    \"Notification\": {\n      \"@id\": \"amtu:Notification\"\n    },\n    \"NotifyWorkersFailureCode\": {\n      \"@id\": \"amtu:NotifyWorkersFailureCode\"\n    },\n    \"NotifyWorkersFailureMessage\": {\n      \"@id\": \"amtu:NotifyWorkersFailureMessage\"\n    },\n    \"NotifyWorkersFailureStatuses\": {\n      \"@id\": \"amtu:NotifyWorkersFailureStatuses\"\n    },\n    \"NumResults\": {\n      \"@id\": \"amtu:NumResults\"\n    },\n    \"NumberOfAdditionalAssignments\": {\n      \"@id\": \"amtu:NumberOfAdditionalAssignments\"\n    },\n    \"NumberOfAssignmentsAvailable\"\
  : {\n      \"@id\": \"amtu:NumberOfAssignmentsAvailable\"\n    },\n    \"NumberOfAssignmentsCompleted\": {\n      \"@id\": \"amtu:NumberOfAssignmentsCompleted\"\n    },\n    \"NumberOfAssignmentsPending\": {\n      \"@id\": \"amtu:NumberOfAssignmentsPending\"\n    },\n    \"OnHoldBalance\": {\n      \"@id\": \"amtu:OnHoldBalance\"\n    },\n    \"OverrideRejection\": {\n      \"@id\": \"amtu:OverrideRejection\"\n    },\n    \"Parameters\": {\n      \"@id\": \"amtu:Parameters\"\n    },\n    \"PolicyLevels\": {\n      \"@id\": \"amtu:PolicyLevels\"\n    },\n    \"PolicyName\": {\n      \"@id\": \"amtu:PolicyName\"\n    },\n    \"QualificationRequestId\": {\n      \"@id\": \"amtu:QualificationRequestId\"\n    },\n    \"QualificationRequests\": {\n      \"@id\": \"amtu:QualificationRequests\"\n    },\n    \"QualificationRequirements\": {\n      \"@id\": \"amtu:QualificationRequirements\"\n    },\n    \"QualificationTypeId\": {\n      \"@id\": \"amtu:QualificationTypeId\"\n    },\n    \"QualificationTypeStatus\"\
  : {\n      \"@id\": \"amtu:QualificationTypeStatus\"\n    },\n    \"QualificationTypes\": {\n      \"@id\": \"amtu:QualificationTypes\"\n    },\n    \"Qualifications\": {\n      \"@id\": \"amtu:Qualifications\"\n    },\n    \"Query\": {\n      \"@id\": \"amtu:Query\"\n    },\n    \"Question\": {\n      \"@id\": \"amtu:Question\"\n    },\n    \"QuestionId\": {\n      \"@id\": \"amtu:QuestionId\"\n    },\n    \"QuestionIdentifier\": {\n      \"@id\": \"amtu:QuestionIdentifier\"\n    },\n    \"Reason\": {\n      \"@id\": \"amtu:Reason\"\n    },\n    \"RejectionTime\": {\n      \"@id\": \"amtu:RejectionTime\"\n    },\n    \"RequesterAnnotation\": {\n      \"@id\": \"amtu:RequesterAnnotation\"\n    },\n    \"RequesterFeedback\": {\n      \"@id\": \"amtu:RequesterFeedback\"\n    },\n    \"RequiredToPreview\": {\n      \"@id\": \"amtu:RequiredToPreview\"\n    },\n    \"Result\": {\n      \"@id\": \"amtu:Result\"\n    },\n    \"RetrieveActions\": {\n      \"@id\": \"amtu:RetrieveActions\"\n  \
  \  },\n    \"RetrieveResults\": {\n      \"@id\": \"amtu:RetrieveResults\"\n    },\n    \"RetryDelayInSeconds\": {\n      \"@id\": \"amtu:RetryDelayInSeconds\"\n    },\n    \"Revert\": {\n      \"@id\": \"amtu:Revert\"\n    },\n    \"ReviewActions\": {\n      \"@id\": \"amtu:ReviewActions\"\n    },\n    \"ReviewResults\": {\n      \"@id\": \"amtu:ReviewResults\"\n    },\n    \"Reward\": {\n      \"@id\": \"amtu:Reward\"\n    },\n    \"SendNotification\": {\n      \"@id\": \"amtu:SendNotification\"\n    },\n    \"Status\": {\n      \"@id\": \"amtu:Status\"\n    },\n    \"Subdivision\": {\n      \"@id\": \"amtu:Subdivision\"\n    },\n    \"Subject\": {\n      \"@id\": \"amtu:Subject\"\n    },\n    \"SubjectId\": {\n      \"@id\": \"amtu:SubjectId\"\n    },\n    \"SubjectType\": {\n      \"@id\": \"amtu:SubjectType\"\n    },\n    \"SubmitTime\": {\n      \"@id\": \"amtu:SubmitTime\"\n    },\n    \"TargetId\": {\n      \"@id\": \"amtu:TargetId\"\n    },\n    \"TargetType\": {\n      \"@id\"\
  : \"amtu:TargetType\"\n    },\n    \"Test\": {\n      \"@id\": \"amtu:Test\"\n    },\n    \"TestDurationInSeconds\": {\n      \"@id\": \"amtu:TestDurationInSeconds\"\n    },\n    \"TestEventType\": {\n      \"@id\": \"amtu:TestEventType\"\n    },\n    \"Title\": {\n      \"@id\": \"amtu:Title\"\n    },\n    \"Transport\": {\n      \"@id\": \"amtu:Transport\"\n    },\n    \"UniqueRequestToken\": {\n      \"@id\": \"amtu:UniqueRequestToken\"\n    },\n    \"Value\": {\n      \"@id\": \"amtu:Value\"\n    },\n    \"Values\": {\n      \"@id\": \"amtu:Values\"\n    },\n    \"Version\": {\n      \"@id\": \"amtu:Version\"\n    },\n    \"WorkerBlocks\": {\n      \"@id\": \"amtu:WorkerBlocks\"\n    },\n    \"WorkerId\": {\n      \"@id\": \"amtu:WorkerId\"\n    },\n    \"WorkerIds\": {\n      \"@id\": \"amtu:WorkerIds\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-mechanical-turk/refs/heads/main/json-ld/amazon-mechanical-turk-context.jsonld
tags:
- Crowdsourcing
- Human Intelligence
- Labor
- Machine Learning
- Tasks
- JSON-LD
- Linked Data
- Semantic Web
---
