---
api_specs:
- filename: linkedin-marketing-audience-insights.yml
  format: yaml
  label: LinkedIn Marketing API
  slug: linkedin-marketing-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-marketing-audience-insights.yml
- filename: linkedin-learning-activity-reports.yml
  format: yaml
  label: LinkedIn Learning Solutions
  slug: linkedin-learning-solutions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-learning-activity-reports.yml
- filename: linkedin-talent-job-posting.yml
  format: yaml
  label: LinkedIn Talent Solutions
  slug: linkedin-talent-solutions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-talent-job-posting.yml
- filename: linkedin-compliance-events.yml
  format: yaml
  label: LinkedIn Compliance Solutions
  slug: linkedin-compliance-solutions
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-compliance-events.yml
- filename: linkedin-sales-navigator.yml
  format: yaml
  label: LinkedIn Sales Navigator API
  slug: linkedin-sales-navigator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-sales-navigator.yml
- filename: linkedin-regulations-data-portability.yml
  format: yaml
  label: LinkedIn Regulatory API
  slug: linkedin-regulatory-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/openapi/linkedin-regulations-data-portability.yml
class_count: 132
classes:
- AccessTokenRequest
- AccessTokenResponse
- AdAccount
- AdAccountCreateRequest
- AdAccountUser
- AdAccountUserCreateRequest
- AdAccountUserUpdateRequest
- AdAccountsResponse
- AdTargetingEntitiesResponse
- AdTargetingEntity
- AdTargetingFacet
- AdTargetingFacetsResponse
- AdditionalQuestions
- Address
- AdvertiserTransparencyRequest
- AdvertiserTransparencyResponse
- ApplicationCredentials
- ApplicationData
- ApplicationQuestions
- ApplicationRequest
- AtsIntegrationUpdateRequest
- AudienceCount
- AudienceInsight
- AudienceInsightsRequest
- AudienceInsightsResponse
- BatchGetOnAdministeredResponse200
- BatchGetOnNonadministeredResponse200
- BatchOrganizationResponse
- BatchProfileAssociationResponse
- Budget
- Campaign
- CampaignGroup
- CampaignUpdateRequest
- CandidateData
- CandidateRequest
- CompanyStreamElement
- CompanyStreamRequest
- ComplianceAuthorization
- ComplianceAuthorizationRequest
- ComplianceAuthorizationResponse
- ComplianceEvent
- ComplianceEventsResponse
- ConfigurationValue
- Contract
- ContractsResponse
- ConversionsByMemberCompanyResponse200
- CoverLetterQuestions
- CreateANewConversionResponse201
- Creative
- CreativeCreateRequest
- CrmDataValidationExportJob
- CrmDataValidationExportJobRequest
- CustomQuestion
- CustomQuestionSet
- DateInfo
- DmpSegment
- DmpSegmentCreateRequest
- DmpSegmentsResponse
- EducationQuestions
- ErrorResponse
- FetchActiveCampaignsResponse200
- FetchExistingConversionRulesResponse200
- FetchFullLeadDataResponse200
- FindAdministeredOrganizationBrandsResponse200
- FindNonadministeredOrganizationResponse200
- GetAListOfResponse200
- GetApplicationResponse
- GetBingGeoLocationsResponse200
- GetFormsForTheResponse200
- GetTheUsersSponsoredResponse200
- ImageAsset
- ImageReference
- InsightSegmentation
- IntegrationConfigurationRequest
- IntegrationPatch
- JobPostingElement
- JobPostingResponse
- LearnerDetails
- LearnerEntity
- LearningActivity
- LearningActivityReport
- LearningActivityReportResponse
- ListUploadRequest
- Locale
- LocalizedString
- LookupByOrganizationPrimaryResponse200
- MemberProfile
- MultipleChoiceQuestionDetails
- NoteData
- NoteRequest
- OnsiteApplyConfiguration
- OrganizationAcl
- OrganizationAclResponse
- OrganizationLocation
- OrganizationResponse
- Paging
- PagingLink
- PersonName
- PhoneNumber
- Post
- PostResponse
- ProvisionApplicationRequest
- ProvisionApplicationResponse
- QuestionChoice
- QuestionDetails
- ReactionResponse
- RequestMetaData
- ResumeQuestions
- RetrieveAnAdministeredOrganizationResponse200
- RetrieveAuthenticatedUsersSponsoredResponse200
- RetrieveOrganizationFollowerCountResponse200
- RunSchedule
- SalesAccessToken
- SalesAccessTokenResponse
- SalesAnalyticsExportJob
- SalesAnalyticsExportJobRequest
- SalesAnalyticsExportJobResponse
- SalesNavigatorProfileAssociation
- SalesNavigatorProfileAssociationKey
- SegmentDestination
- SimpleJobPostingRequest
- StreamMultipleConversionEventsResponse200
- StreamResponse
- StreamResultElement
- TargetingCriteria
- Timestamp
- UpdateCallbackUrlRequest
- UserId
- UserStreamElement
- UserStreamRequest
- ValidateTheUsersOrganizationResponse200
- WorkQuestions
context_file: json-ld/linkedin-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/json-ld/linkedin-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Linkedin Api from LinkedIn.
layout: jsonld
name: Linkedin Api Context
namespaces:
- prefix: li
  uri: https://learn.microsoft.com/en-us/linkedin/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessPolicy
  type: string
- container: ''
  name: access_token
  type: string
- container: ''
  name: account
  type: string
- container: ''
  name: accountUrn
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: activeCount
  type: integer
- container: set
  name: activities
  type: string
- container: ''
  name: activity
  type: string
- container: ''
  name: actor
  type: string
- container: ''
  name: additionalQuestions
  type: string
- container: ''
  name: address
  type: string
- container: set
  name: addresses
  type: string
- container: ''
  name: advertiserName
  type: string
- container: set
  name: alternativeNames
  type: string
- container: ''
  name: amount
  type: string
- container: ''
  name: applicationUrn
  type: string
- container: ''
  name: assetType
  type: string
- container: set
  name: associatedCampaigns
  type: string
- container: ''
  name: associatedEntity
  type: string
- container: ''
  name: atsCandidateId
  type: string
- container: ''
  name: atsCreatedAt
  type: string
- container: ''
  name: atsJobPostingId
  type: string
- container: ''
  name: atsJobPostingName
  type: string
- container: ''
  name: atsLastModifiedAt
  type: string
- container: ''
  name: attributionType
  type: string
- container: ''
  name: audienceSize
  type: integer
- container: ''
  name: author
  type: string
- container: ''
  name: autoCreated
  type: boolean
- container: set
  name: availableEntityFinders
  type: string
- container: ''
  name: campaign
  type: string
- container: ''
  name: campaignGroup
  type: string
- container: set
  name: campaigns
  type: string
- container: ''
  name: candidateEmail
  type: string
- container: ''
  name: capturedAt
  type: string
- container: set
  name: choices
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: clientId
  type: string
- container: ''
  name: clientSecret
  type: string
- container: ''
  name: client_id
  type: string
- container: ''
  name: client_secret
  type: string
- container: ''
  name: code
  type: string
- container: ''
  name: commentary
  type: string
- container: ''
  name: companyApplyUrl
  type: reference
- container: ''
  name: companyDomain
  type: string
- container: ''
  name: companyName
  type: string
- container: ''
  name: companyPageUrl
  type: string
- container: ''
  name: configVersion
  type: string
- container: ''
  name: configurationValue
  type: string
- container: ''
  name: contentUrn
  type: string
- container: ''
  name: contract
  type: string
- container: ''
  name: conversionMethod
  type: string
- container: ''
  name: count
  type: integer
- container: ''
  name: country
  type: string
- container: ''
  name: coverLetterQuestionRequirement
  type: string
- container: ''
  name: coverLetterQuestions
  type: string
- container: ''
  name: coverPhotoV2
  type: string
- container: ''
  name: created
  type: integer
- container: ''
  name: createdAt
  type: string
- container: ''
  name: cropInfo
  type: string
- container: ''
  name: cropped
  type: string
- container: ''
  name: currency
  type: string
- container: ''
  name: currencyCode
  type: string
- container: ''
  name: currentCompanyName
  type: string
- container: ''
  name: currentJobTitle
  type: string
- container: set
  name: customQuestionSets
  type: string
- container: ''
  name: dailyBudget
  type: string
- container: ''
  name: day
  type: integer
- container: ''
  name: defaultLocale
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: destination
  type: string
- container: set
  name: destinations
  type: string
- container: ''
  name: developerApplication
  type: string
- container: ''
  name: displayValue
  type: string
- container: ''
  name: dispositionReason
  type: string
- container: ''
  name: downloadUrl
  type: reference
- container: ''
  name: downloadUrlExpiresAt
  type: string
- container: set
  name: downloadUrls
  type: string
- container: ''
  name: educationExperienceQuestionSet
  type: string
- container: ''
  name: educationQuestions
  type: string
- container: set
  name: elements
  type: string
- container: set
  name: emailAddresses
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: end
  type: string
- container: ''
  name: endAt
  type: integer
- container: ''
  name: engagementMetricQualifier
  type: string
- container: ''
  name: engagementType
  type: string
- container: ''
  name: engagementValue
  type: integer
- container: ''
  name: entities
  type: string
- container: ''
  name: entity
  type: string
- container: ''
  name: entityCount
  type: integer
- container: ''
  name: entityPercentage
  type: integer
- container: ''
  name: entityStatus
  type: string
- container: set
  name: entityTypes
  type: string
- container: ''
  name: errors
  type: string
- container: ''
  name: expireAt
  type: string
- container: ''
  name: expires_in
  type: integer
- container: ''
  name: expiryTime
  type: integer
- container: ''
  name: exportEndAt
  type: string
- container: ''
  name: exportStartAt
  type: string
- container: ''
  name: extension
  type: string
- container: ''
  name: externalJobPostingId
  type: string
- container: ''
  name: externalProfileUrl
  type: reference
- container: ''
  name: facetName
  type: string
- container: ''
  name: facetUrn
  type: string
- container: ''
  name: firstDegreeSize
  type: integer
- container: ''
  name: firstEngagedAt
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: formResponse
  type: string
- container: ''
  name: foundedOn
  type: string
- container: ''
  name: geoLocation
  type: string
- container: ''
  name: geographicArea
  type: string
- container: ''
  name: geographicAreaType
  type: string
- container: ''
  name: grant_type
  type: string
- container: ''
  name: groupUrn
  type: string
- container: ''
  name: groupedBy
  type: string
- container: set
  name: groups
  type: string
- container: ''
  name: hasReportingAccess
  type: boolean
- container: ''
  name: headline
  type: string
- container: ''
  name: href
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: idType
  type: string
- container: ''
  name: idValue
  type: string
- container: ''
  name: impressions
  type: integer
- container: ''
  name: include
  type: string
- container: set
  name: industries
  type: string
- container: set
  name: industriesV2
  type: string
- container: ''
  name: inputCount
  type: integer
- container: ''
  name: inputFile
  type: string
- container: ''
  name: instanceId
  type: string
- container: ''
  name: integrationContext
  type: string
- container: ''
  name: jobApplicationWebhookUrl
  type: reference
- container: ''
  name: jobId
  type: string
- container: ''
  name: jobPostingOperationType
  type: string
- container: ''
  name: language
  type: string
- container: ''
  name: lastEngagedAt
  type: string
- container: ''
  name: lastModified
  type: integer
- container: ''
  name: lastName
  type: string
- container: ''
  name: latestDataAt
  type: string
- container: ''
  name: leadMetadata
  type: string
- container: ''
  name: leadType
  type: string
- container: ''
  name: learnerDetails
  type: string
- container: ''
  name: learnerUrn
  type: string
- container: ''
  name: lifecycleState
  type: string
- container: ''
  name: line1
  type: string
- container: set
  name: links
  type: string
- container: ''
  name: listedAt
  type: string
- container: ''
  name: listingType
  type: string
- container: ''
  name: localized
  type: string
- container: ''
  name: localizedDescription
  type: string
- container: ''
  name: localizedName
  type: string
- container: set
  name: localizedSpecialties
  type: string
- container: ''
  name: localizedTagline
  type: string
- container: ''
  name: localizedWebsite
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: locationType
  type: string
- container: set
  name: locations
  type: string
- container: ''
  name: logoV2
  type: string
- container: ''
  name: matchedCount
  type: integer
- container: ''
  name: member
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: method
  type: string
- container: ''
  name: middleInitial
  type: string
- container: ''
  name: month
  type: integer
- container: ''
  name: multipleChoiceQuestionDetails
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: nextExportStartAt
  type: string
- container: ''
  name: note
  type: string
- container: ''
  name: notifiedOnCampaignOptimization
  type: boolean
- container: ''
  name: notifiedOnCreativeApproval
  type: boolean
- container: ''
  name: notifiedOnCreativeRejection
  type: boolean
- container: ''
  name: notifiedOnEndOfCampaign
  type: boolean
- container: ''
  name: number
  type: string
- container: set
  name: oauth2AuthorizedCallbackUrls
  type: string
- container: ''
  name: objectiveType
  type: string
- container: ''
  name: onsiteApplyConfiguration
  type: string
- container: ''
  name: organization
  type: string
- container: ''
  name: organizationType
  type: string
- container: ''
  name: original
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: paging
  type: string
- container: ''
  name: parentActivity
  type: string
- container: ''
  name: parentRelationship
  type: string
- container: set
  name: parentSiblingActivities
  type: string
- container: ''
  name: partner
  type: string
- container: ''
  name: partnerQuestionIdentifier
  type: string
- container: ''
  name: patch
  type: string
- container: set
  name: phoneNumbers
  type: string
- container: ''
  name: postClickAttributionWindowSize
  type: integer
- container: ''
  name: postalCode
  type: string
- container: ''
  name: preferredFormComponent
  type: string
- container: ''
  name: preferredLocale
  type: string
- container: ''
  name: prefix
  type: string
- container: ''
  name: primaryOrganizationType
  type: string
- container: ''
  name: processedActivity
  type: string
- container: ''
  name: processedAt
  type: string
- container: ''
  name: profile
  type: reference
- container: ''
  name: profilePhoto
  type: reference
- container: ''
  name: questionDetails
  type: string
- container: ''
  name: questionSetId
  type: string
- container: ''
  name: questionText
  type: string
- container: set
  name: questions
  type: string
- container: ''
  name: recordId
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: rel
  type: string
- container: ''
  name: request
  type: string
- container: ''
  name: required
  type: boolean
- container: ''
  name: resourceId
  type: string
- container: ''
  name: resourceName
  type: string
- container: ''
  name: resourceUri
  type: string
- container: ''
  name: results
  type: string
- container: ''
  name: resumeQuestionRequirement
  type: string
- container: ''
  name: resumeQuestions
  type: string
- container: ''
  name: role
  type: string
- container: ''
  name: roleAssignee
  type: string
- container: ''
  name: rowCount
  type: integer
- container: ''
  name: runSchedule
  type: string
- container: set
  name: segmentations
  type: string
- container: ''
  name: selectMultiple
  type: boolean
- container: ''
  name: serviceErrorCode
  type: integer
- container: set
  name: siblingActivities
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: sourcePlatform
  type: string
- container: set
  name: specialties
  type: string
- container: ''
  name: sponsoredAccount
  type: string
- container: ''
  name: sponsoredAccountId
  type: string
- container: ''
  name: sponsoredAccountUrn
  type: string
- container: ''
  name: staffCountRange
  type: string
- container: ''
  name: start
  type: integer
- container: ''
  name: startAt
  type: integer
- container: ''
  name: state
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statuses
  type: string
- container: ''
  name: submittedAt
  type: integer
- container: ''
  name: submitter
  type: string
- container: ''
  name: suffix
  type: string
- container: ''
  name: symbolicName
  type: string
- container: ''
  name: tagline
  type: string
- container: ''
  name: test
  type: boolean
- container: ''
  name: testLead
  type: boolean
- container: ''
  name: time
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: token_type
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: totalBudget
  type: string
- container: ''
  name: totalSpend
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: uniqueForeignId
  type: string
- container: set
  name: urlRules
  type: string
- container: ''
  name: urn
  type: string
- container: ''
  name: user
  type: string
- container: set
  name: userIds
  type: string
- container: set
  name: validJsSdkDomains
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: vanityName
  type: string
- container: ''
  name: variables
  type: string
- container: ''
  name: versionTag
  type: string
- container: ''
  name: versionedLeadGenFormUrn
  type: string
- container: ''
  name: viewThroughAttributionWindowSize
  type: integer
- container: ''
  name: visibility
  type: string
- container: ''
  name: voluntarySelfIdentificationQuestions
  type: string
- container: ''
  name: website
  type: string
- container: ''
  name: workExperienceQuestionSet
  type: string
- container: ''
  name: workQuestions
  type: string
- container: ''
  name: year
  type: integer
property_count: 265
provider_name: LinkedIn
provider_slug: linkedin
slug: linkedin-api-context
source_filename: linkedin-api-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"li\": \"https://learn.microsoft.com/en-us/linkedin/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccessTokenRequest\": \"li:AccessTokenRequest\",\n    \"AccessTokenResponse\": \"li:AccessTokenResponse\",\n    \"AdAccount\": \"li:AdAccount\",\n    \"AdAccountCreateRequest\": \"li:AdAccountCreateRequest\",\n    \"AdAccountUser\": \"li:AdAccountUser\",\n    \"AdAccountUserCreateRequest\": \"li:AdAccountUserCreateRequest\",\n    \"AdAccountUserUpdateRequest\": \"li:AdAccountUserUpdateRequest\",\n    \"AdAccountsResponse\": \"li:AdAccountsResponse\",\n    \"AdTargetingEntitiesResponse\": \"li:AdTargetingEntitiesResponse\",\n    \"AdTargetingEntity\": \"li:AdTargetingEntity\",\n    \"AdTargetingFacet\": \"li:AdTargetingFacet\",\n    \"AdTargetingFacetsResponse\": \"li:AdTargetingFacetsResponse\",\n    \"AdditionalQuestions\": \"li:AdditionalQuestions\",\n    \"Address\"\
  : \"li:Address\",\n    \"AdvertiserTransparencyRequest\": \"li:AdvertiserTransparencyRequest\",\n    \"AdvertiserTransparencyResponse\": \"li:AdvertiserTransparencyResponse\",\n    \"ApplicationCredentials\": \"li:ApplicationCredentials\",\n    \"ApplicationData\": \"li:ApplicationData\",\n    \"ApplicationQuestions\": \"li:ApplicationQuestions\",\n    \"ApplicationRequest\": \"li:ApplicationRequest\",\n    \"AtsIntegrationUpdateRequest\": \"li:AtsIntegrationUpdateRequest\",\n    \"AudienceCount\": \"li:AudienceCount\",\n    \"AudienceInsight\": \"li:AudienceInsight\",\n    \"AudienceInsightsRequest\": \"li:AudienceInsightsRequest\",\n    \"AudienceInsightsResponse\": \"li:AudienceInsightsResponse\",\n    \"BatchGetOnAdministeredResponse200\": \"li:BatchGetOnAdministeredResponse200\",\n    \"BatchGetOnNonadministeredResponse200\": \"li:BatchGetOnNonadministeredResponse200\",\n    \"BatchOrganizationResponse\": \"li:BatchOrganizationResponse\",\n    \"BatchProfileAssociationResponse\":\
  \ \"li:BatchProfileAssociationResponse\",\n    \"Budget\": \"li:Budget\",\n    \"Campaign\": \"li:Campaign\",\n    \"CampaignGroup\": \"li:CampaignGroup\",\n    \"CampaignUpdateRequest\": \"li:CampaignUpdateRequest\",\n    \"CandidateData\": \"li:CandidateData\",\n    \"CandidateRequest\": \"li:CandidateRequest\",\n    \"CompanyStreamElement\": \"li:CompanyStreamElement\",\n    \"CompanyStreamRequest\": \"li:CompanyStreamRequest\",\n    \"ComplianceAuthorization\": \"li:ComplianceAuthorization\",\n    \"ComplianceAuthorizationRequest\": \"li:ComplianceAuthorizationRequest\",\n    \"ComplianceAuthorizationResponse\": \"li:ComplianceAuthorizationResponse\",\n    \"ComplianceEvent\": \"li:ComplianceEvent\",\n    \"ComplianceEventsResponse\": \"li:ComplianceEventsResponse\",\n    \"ConfigurationValue\": \"li:ConfigurationValue\",\n    \"Contract\": \"li:Contract\",\n    \"ContractsResponse\": \"li:ContractsResponse\",\n    \"ConversionsByMemberCompanyResponse200\": \"li:ConversionsByMemberCompanyResponse200\"\
  ,\n    \"CoverLetterQuestions\": \"li:CoverLetterQuestions\",\n    \"CreateANewConversionResponse201\": \"li:CreateANewConversionResponse201\",\n    \"Creative\": \"li:Creative\",\n    \"CreativeCreateRequest\": \"li:CreativeCreateRequest\",\n    \"CrmDataValidationExportJob\": \"li:CrmDataValidationExportJob\",\n    \"CrmDataValidationExportJobRequest\": \"li:CrmDataValidationExportJobRequest\",\n    \"CustomQuestion\": \"li:CustomQuestion\",\n    \"CustomQuestionSet\": \"li:CustomQuestionSet\",\n    \"DateInfo\": \"li:DateInfo\",\n    \"DmpSegment\": \"li:DmpSegment\",\n    \"DmpSegmentCreateRequest\": \"li:DmpSegmentCreateRequest\",\n    \"DmpSegmentsResponse\": \"li:DmpSegmentsResponse\",\n    \"EducationQuestions\": \"li:EducationQuestions\",\n    \"ErrorResponse\": \"li:ErrorResponse\",\n    \"FetchActiveCampaignsResponse200\": \"li:FetchActiveCampaignsResponse200\",\n    \"FetchExistingConversionRulesResponse200\": \"li:FetchExistingConversionRulesResponse200\",\n    \"FetchFullLeadDataResponse200\"\
  : \"li:FetchFullLeadDataResponse200\",\n    \"FindAdministeredOrganizationBrandsResponse200\": \"li:FindAdministeredOrganizationBrandsResponse200\",\n    \"FindNonadministeredOrganizationResponse200\": \"li:FindNonadministeredOrganizationResponse200\",\n    \"GetAListOfResponse200\": \"li:GetAListOfResponse200\",\n    \"GetApplicationResponse\": \"li:GetApplicationResponse\",\n    \"GetBingGeoLocationsResponse200\": \"li:GetBingGeoLocationsResponse200\",\n    \"GetFormsForTheResponse200\": \"li:GetFormsForTheResponse200\",\n    \"GetTheUsersSponsoredResponse200\": \"li:GetTheUsersSponsoredResponse200\",\n    \"ImageAsset\": \"li:ImageAsset\",\n    \"ImageReference\": \"li:ImageReference\",\n    \"InsightSegmentation\": \"li:InsightSegmentation\",\n    \"IntegrationConfigurationRequest\": \"li:IntegrationConfigurationRequest\",\n    \"IntegrationPatch\": \"li:IntegrationPatch\",\n    \"JobPostingElement\": \"li:JobPostingElement\",\n    \"JobPostingResponse\": \"li:JobPostingResponse\"\
  ,\n    \"LearnerDetails\": \"li:LearnerDetails\",\n    \"LearnerEntity\": \"li:LearnerEntity\",\n    \"LearningActivity\": \"li:LearningActivity\",\n    \"LearningActivityReport\": \"li:LearningActivityReport\",\n    \"LearningActivityReportResponse\": \"li:LearningActivityReportResponse\",\n    \"ListUploadRequest\": \"li:ListUploadRequest\",\n    \"Locale\": \"li:Locale\",\n    \"LocalizedString\": \"li:LocalizedString\",\n    \"LookupByOrganizationPrimaryResponse200\": \"li:LookupByOrganizationPrimaryResponse200\",\n    \"MemberProfile\": \"li:MemberProfile\",\n    \"MultipleChoiceQuestionDetails\": \"li:MultipleChoiceQuestionDetails\",\n    \"NoteData\": \"li:NoteData\",\n    \"NoteRequest\": \"li:NoteRequest\",\n    \"OnsiteApplyConfiguration\": \"li:OnsiteApplyConfiguration\",\n    \"OrganizationAcl\": \"li:OrganizationAcl\",\n    \"OrganizationAclResponse\": \"li:OrganizationAclResponse\",\n    \"OrganizationLocation\": \"li:OrganizationLocation\",\n    \"OrganizationResponse\"\
  : \"li:OrganizationResponse\",\n    \"Paging\": \"li:Paging\",\n    \"PagingLink\": \"li:PagingLink\",\n    \"PersonName\": \"li:PersonName\",\n    \"PhoneNumber\": \"li:PhoneNumber\",\n    \"Post\": \"li:Post\",\n    \"PostResponse\": \"li:PostResponse\",\n    \"ProvisionApplicationRequest\": \"li:ProvisionApplicationRequest\",\n    \"ProvisionApplicationResponse\": \"li:ProvisionApplicationResponse\",\n    \"QuestionChoice\": \"li:QuestionChoice\",\n    \"QuestionDetails\": \"li:QuestionDetails\",\n    \"ReactionResponse\": \"li:ReactionResponse\",\n    \"RequestMetaData\": \"li:RequestMetaData\",\n    \"ResumeQuestions\": \"li:ResumeQuestions\",\n    \"RetrieveAnAdministeredOrganizationResponse200\": \"li:RetrieveAnAdministeredOrganizationResponse200\",\n    \"RetrieveAuthenticatedUsersSponsoredResponse200\": \"li:RetrieveAuthenticatedUsersSponsoredResponse200\",\n    \"RetrieveOrganizationFollowerCountResponse200\": \"li:RetrieveOrganizationFollowerCountResponse200\",\n    \"RunSchedule\"\
  : \"li:RunSchedule\",\n    \"SalesAccessToken\": \"li:SalesAccessToken\",\n    \"SalesAccessTokenResponse\": \"li:SalesAccessTokenResponse\",\n    \"SalesAnalyticsExportJob\": \"li:SalesAnalyticsExportJob\",\n    \"SalesAnalyticsExportJobRequest\": \"li:SalesAnalyticsExportJobRequest\",\n    \"SalesAnalyticsExportJobResponse\": \"li:SalesAnalyticsExportJobResponse\",\n    \"SalesNavigatorProfileAssociation\": \"li:SalesNavigatorProfileAssociation\",\n    \"SalesNavigatorProfileAssociationKey\": \"li:SalesNavigatorProfileAssociationKey\",\n    \"SegmentDestination\": \"li:SegmentDestination\",\n    \"SimpleJobPostingRequest\": \"li:SimpleJobPostingRequest\",\n    \"StreamMultipleConversionEventsResponse200\": \"li:StreamMultipleConversionEventsResponse200\",\n    \"StreamResponse\": \"li:StreamResponse\",\n    \"StreamResultElement\": \"li:StreamResultElement\",\n    \"TargetingCriteria\": \"li:TargetingCriteria\",\n    \"Timestamp\": \"li:Timestamp\",\n    \"UpdateCallbackUrlRequest\"\
  : \"li:UpdateCallbackUrlRequest\",\n    \"UserId\": \"li:UserId\",\n    \"UserStreamElement\": \"li:UserStreamElement\",\n    \"UserStreamRequest\": \"li:UserStreamRequest\",\n    \"ValidateTheUsersOrganizationResponse200\": \"li:ValidateTheUsersOrganizationResponse200\",\n    \"WorkQuestions\": \"li:WorkQuestions\",\n    \"accessPolicy\": {\n      \"@id\": \"li:accessPolicy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"access_token\": {\n      \"@id\": \"li:access_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"account\": {\n      \"@id\": \"li:account\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountUrn\": {\n      \"@id\": \"li:accountUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"li:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeCount\": {\n      \"@id\": \"li:activeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"activities\": {\n      \"@id\": \"li:activities\",\n      \"@container\": \"@set\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"activity\": {\n      \"@id\": \"li:activity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"actor\": {\n      \"@id\": \"li:actor\",\n      \"@type\": \"xsd:string\"\n    },\n    \"additionalQuestions\": {\n      \"@id\": \"li:additionalQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"li:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"addresses\": {\n      \"@id\": \"li:addresses\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"advertiserName\": {\n      \"@id\": \"li:advertiserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alternativeNames\": {\n      \"@id\": \"li:alternativeNames\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"amount\": {\n      \"@id\": \"li:amount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationUrn\": {\n      \"@id\": \"li:applicationUrn\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"assetType\": {\n      \"@id\": \"li:assetType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedCampaigns\": {\n      \"@id\": \"li:associatedCampaigns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"associatedEntity\": {\n      \"@id\": \"li:associatedEntity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsCandidateId\": {\n      \"@id\": \"li:atsCandidateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsCreatedAt\": {\n      \"@id\": \"li:atsCreatedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsJobPostingId\": {\n      \"@id\": \"li:atsJobPostingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsJobPostingName\": {\n      \"@id\": \"li:atsJobPostingName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"atsLastModifiedAt\": {\n      \"@id\": \"li:atsLastModifiedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attributionType\": {\n      \"@id\": \"li:attributionType\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"audienceSize\": {\n      \"@id\": \"li:audienceSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"author\": {\n      \"@id\": \"li:author\",\n      \"@type\": \"xsd:string\"\n    },\n    \"autoCreated\": {\n      \"@id\": \"li:autoCreated\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"availableEntityFinders\": {\n      \"@id\": \"li:availableEntityFinders\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaign\": {\n      \"@id\": \"li:campaign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaignGroup\": {\n      \"@id\": \"li:campaignGroup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"campaigns\": {\n      \"@id\": \"li:campaigns\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"candidateEmail\": {\n      \"@id\": \"li:candidateEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capturedAt\": {\n      \"@id\": \"li:capturedAt\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"choices\": {\n      \"@id\": \"li:choices\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"li:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientId\": {\n      \"@id\": \"li:clientId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientSecret\": {\n      \"@id\": \"li:clientSecret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_id\": {\n      \"@id\": \"li:client_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"client_secret\": {\n      \"@id\": \"li:client_secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"code\": {\n      \"@id\": \"li:code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commentary\": {\n      \"@id\": \"li:commentary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyApplyUrl\": {\n      \"@id\": \"li:companyApplyUrl\",\n      \"@type\": \"@id\"\n    },\n    \"companyDomain\": {\n      \"@id\": \"li:companyDomain\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"companyName\": {\n      \"@id\": \"li:companyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"companyPageUrl\": {\n      \"@id\": \"li:companyPageUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configVersion\": {\n      \"@id\": \"li:configVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"configurationValue\": {\n      \"@id\": \"li:configurationValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentUrn\": {\n      \"@id\": \"li:contentUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contract\": {\n      \"@id\": \"li:contract\",\n      \"@type\": \"xsd:string\"\n    },\n    \"conversionMethod\": {\n      \"@id\": \"li:conversionMethod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"count\": {\n      \"@id\": \"li:count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"country\": {\n      \"@id\": \"li:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverLetterQuestionRequirement\": {\n      \"@id\": \"li:coverLetterQuestionRequirement\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"coverLetterQuestions\": {\n      \"@id\": \"li:coverLetterQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverPhotoV2\": {\n      \"@id\": \"li:coverPhotoV2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"li:created\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"li:createdAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cropInfo\": {\n      \"@id\": \"li:cropInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cropped\": {\n      \"@id\": \"li:cropped\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currency\": {\n      \"@id\": \"li:currency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currencyCode\": {\n      \"@id\": \"li:currencyCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentCompanyName\": {\n      \"@id\": \"li:currentCompanyName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentJobTitle\": {\n      \"@id\"\
  : \"li:currentJobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customQuestionSets\": {\n      \"@id\": \"li:customQuestionSets\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dailyBudget\": {\n      \"@id\": \"li:dailyBudget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"day\": {\n      \"@id\": \"li:day\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"defaultLocale\": {\n      \"@id\": \"li:defaultLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"li:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destinations\": {\n      \"@id\": \"li:destinations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"developerApplication\": {\n      \"@id\": \"li:developerApplication\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayValue\": {\n     \
  \ \"@id\": \"li:displayValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dispositionReason\": {\n      \"@id\": \"li:dispositionReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrl\": {\n      \"@id\": \"li:downloadUrl\",\n      \"@type\": \"@id\"\n    },\n    \"downloadUrlExpiresAt\": {\n      \"@id\": \"li:downloadUrlExpiresAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"downloadUrls\": {\n      \"@id\": \"li:downloadUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"educationExperienceQuestionSet\": {\n      \"@id\": \"li:educationExperienceQuestionSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"educationQuestions\": {\n      \"@id\": \"li:educationQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"elements\": {\n      \"@id\": \"li:elements\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailAddresses\": {\n      \"@id\": \"li:emailAddresses\",\n      \"@container\"\
  : \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"li:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"end\": {\n      \"@id\": \"li:end\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endAt\": {\n      \"@id\": \"li:endAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"engagementMetricQualifier\": {\n      \"@id\": \"li:engagementMetricQualifier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engagementType\": {\n      \"@id\": \"li:engagementType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"engagementValue\": {\n      \"@id\": \"li:engagementValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entities\": {\n      \"@id\": \"li:entities\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entity\": {\n      \"@id\": \"li:entity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityCount\": {\n      \"@id\": \"li:entityCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityPercentage\": {\n      \"@id\"\
  : \"li:entityPercentage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"entityStatus\": {\n      \"@id\": \"li:entityStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"entityTypes\": {\n      \"@id\": \"li:entityTypes\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errors\": {\n      \"@id\": \"li:errors\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expireAt\": {\n      \"@id\": \"li:expireAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expires_in\": {\n      \"@id\": \"li:expires_in\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"expiryTime\": {\n      \"@id\": \"li:expiryTime\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"exportEndAt\": {\n      \"@id\": \"li:exportEndAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportStartAt\": {\n      \"@id\": \"li:exportStartAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"extension\": {\n      \"@id\": \"li:extension\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"externalJobPostingId\": {\n      \"@id\": \"li:externalJobPostingId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"externalProfileUrl\": {\n      \"@id\": \"li:externalProfileUrl\",\n      \"@type\": \"@id\"\n    },\n    \"facetName\": {\n      \"@id\": \"li:facetName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"facetUrn\": {\n      \"@id\": \"li:facetUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstDegreeSize\": {\n      \"@id\": \"li:firstDegreeSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"firstEngagedAt\": {\n      \"@id\": \"li:firstEngagedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"li:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"formResponse\": {\n      \"@id\": \"li:formResponse\",\n      \"@type\": \"xsd:string\"\n    },\n    \"foundedOn\": {\n      \"@id\": \"li:foundedOn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geoLocation\": {\n      \"@id\": \"li:geoLocation\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"geographicArea\": {\n      \"@id\": \"li:geographicArea\",\n      \"@type\": \"xsd:string\"\n    },\n    \"geographicAreaType\": {\n      \"@id\": \"li:geographicAreaType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"grant_type\": {\n      \"@id\": \"li:grant_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupUrn\": {\n      \"@id\": \"li:groupUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groupedBy\": {\n      \"@id\": \"li:groupedBy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"groups\": {\n      \"@id\": \"li:groups\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasReportingAccess\": {\n      \"@id\": \"li:hasReportingAccess\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"headline\": {\n      \"@id\": \"li:headline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"href\": {\n      \"@id\": \"li:href\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"\
  li:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idType\": {\n      \"@id\": \"li:idType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"idValue\": {\n      \"@id\": \"li:idValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"impressions\": {\n      \"@id\": \"li:impressions\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"include\": {\n      \"@id\": \"li:include\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industries\": {\n      \"@id\": \"li:industries\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"industriesV2\": {\n      \"@id\": \"li:industriesV2\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inputCount\": {\n      \"@id\": \"li:inputCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"inputFile\": {\n      \"@id\": \"li:inputFile\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceId\": {\n      \"@id\": \"li:instanceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  integrationContext\": {\n      \"@id\": \"li:integrationContext\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobApplicationWebhookUrl\": {\n      \"@id\": \"li:jobApplicationWebhookUrl\",\n      \"@type\": \"@id\"\n    },\n    \"jobId\": {\n      \"@id\": \"li:jobId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobPostingOperationType\": {\n      \"@id\": \"li:jobPostingOperationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"language\": {\n      \"@id\": \"li:language\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEngagedAt\": {\n      \"@id\": \"li:lastEngagedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModified\": {\n      \"@id\": \"li:lastModified\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"lastName\": {\n      \"@id\": \"li:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"latestDataAt\": {\n      \"@id\": \"li:latestDataAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"leadMetadata\": {\n      \"@id\": \"li:leadMetadata\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"leadType\": {\n      \"@id\": \"li:leadType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"learnerDetails\": {\n      \"@id\": \"li:learnerDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"learnerUrn\": {\n      \"@id\": \"li:learnerUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lifecycleState\": {\n      \"@id\": \"li:lifecycleState\",\n      \"@type\": \"xsd:string\"\n    },\n    \"line1\": {\n      \"@id\": \"li:line1\",\n      \"@type\": \"xsd:string\"\n    },\n    \"links\": {\n      \"@id\": \"li:links\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listedAt\": {\n      \"@id\": \"li:listedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"listingType\": {\n      \"@id\": \"li:listingType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localized\": {\n      \"@id\": \"li:localized\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedDescription\": {\n      \"@id\"\
  : \"li:localizedDescription\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedName\": {\n      \"@id\": \"li:localizedName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedSpecialties\": {\n      \"@id\": \"li:localizedSpecialties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedTagline\": {\n      \"@id\": \"li:localizedTagline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"localizedWebsite\": {\n      \"@id\": \"li:localizedWebsite\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"li:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationType\": {\n      \"@id\": \"li:locationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locations\": {\n      \"@id\": \"li:locations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logoV2\": {\n      \"@id\": \"li:logoV2\",\n      \"@type\": \"xsd:string\"\n    },\n    \"matchedCount\": {\n   \
  \   \"@id\": \"li:matchedCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"member\": {\n      \"@id\": \"li:member\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"li:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"method\": {\n      \"@id\": \"li:method\",\n      \"@type\": \"xsd:string\"\n    },\n    \"middleInitial\": {\n      \"@id\": \"li:middleInitial\",\n      \"@type\": \"xsd:string\"\n    },\n    \"month\": {\n      \"@id\": \"li:month\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"multipleChoiceQuestionDetails\": {\n      \"@id\": \"li:multipleChoiceQuestionDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextExportStartAt\": {\n      \"@id\": \"li:nextExportStartAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"note\": {\n      \"@id\": \"li:note\",\n      \"@type\": \"xsd:string\"\n    },\n    \"notifiedOnCampaignOptimization\"\
  : {\n      \"@id\": \"li:notifiedOnCampaignOptimization\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notifiedOnCreativeApproval\": {\n      \"@id\": \"li:notifiedOnCreativeApproval\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notifiedOnCreativeRejection\": {\n      \"@id\": \"li:notifiedOnCreativeRejection\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"notifiedOnEndOfCampaign\": {\n      \"@id\": \"li:notifiedOnEndOfCampaign\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"number\": {\n      \"@id\": \"li:number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"oauth2AuthorizedCallbackUrls\": {\n      \"@id\": \"li:oauth2AuthorizedCallbackUrls\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectiveType\": {\n      \"@id\": \"li:objectiveType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onsiteApplyConfiguration\": {\n      \"@id\": \"li:onsiteApplyConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organization\"\
  : {\n      \"@id\": \"li:organization\",\n      \"@type\": \"xsd:string\"\n    },\n    \"organizationType\": {\n      \"@id\": \"li:organizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"original\": {\n      \"@id\": \"li:original\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"li:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"paging\": {\n      \"@id\": \"li:paging\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentActivity\": {\n      \"@id\": \"li:parentActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentRelationship\": {\n      \"@id\": \"li:parentRelationship\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentSiblingActivities\": {\n      \"@id\": \"li:parentSiblingActivities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partner\": {\n      \"@id\": \"li:partner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"partnerQuestionIdentifier\": {\n      \"@id\": \"li:partnerQuestionIdentifier\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"patch\": {\n      \"@id\": \"li:patch\",\n      \"@type\": \"xsd:string\"\n    },\n    \"phoneNumbers\": {\n      \"@id\": \"li:phoneNumbers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postClickAttributionWindowSize\": {\n      \"@id\": \"li:postClickAttributionWindowSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"postalCode\": {\n      \"@id\": \"li:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferredFormComponent\": {\n      \"@id\": \"li:preferredFormComponent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"preferredLocale\": {\n      \"@id\": \"li:preferredLocale\",\n      \"@type\": \"xsd:string\"\n    },\n    \"prefix\": {\n      \"@id\": \"li:prefix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryOrganizationType\": {\n      \"@id\": \"li:primaryOrganizationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedActivity\": {\n      \"@id\"\
  : \"li:processedActivity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"processedAt\": {\n      \"@id\": \"li:processedAt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"profile\": {\n      \"@id\": \"li:profile\",\n      \"@type\": \"@id\"\n    },\n    \"profilePhoto\": {\n      \"@id\": \"li:profilePhoto\",\n      \"@type\": \"@id\"\n    },\n    \"questionDetails\": {\n      \"@id\": \"li:questionDetails\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questionSetId\": {\n      \"@id\": \"li:questionSetId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questionText\": {\n      \"@id\": \"li:questionText\",\n      \"@type\": \"xsd:string\"\n    },\n    \"questions\": {\n      \"@id\": \"li:questions\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"recordId\": {\n      \"@id\": \"li:recordId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"li:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rel\"\
  : {\n      \"@id\": \"li:rel\",\n      \"@type\": \"xsd:string\"\n    },\n    \"request\": {\n      \"@id\": \"li:request\",\n      \"@type\": \"xsd:string\"\n    },\n    \"required\": {\n      \"@id\": \"li:required\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"resourceId\": {\n      \"@id\": \"li:resourceId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceName\": {\n      \"@id\": \"li:resourceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceUri\": {\n      \"@id\": \"li:resourceUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"results\": {\n      \"@id\": \"li:results\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resumeQuestionRequirement\": {\n      \"@id\": \"li:resumeQuestionRequirement\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resumeQuestions\": {\n      \"@id\": \"li:resumeQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"role\": {\n      \"@id\": \"li:role\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleAssignee\"\
  : {\n      \"@id\": \"li:roleAssignee\",\n      \"@type\": \"xsd:string\"\n    },\n    \"rowCount\": {\n      \"@id\": \"li:rowCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"runSchedule\": {\n      \"@id\": \"li:runSchedule\",\n      \"@type\": \"xsd:string\"\n    },\n    \"segmentations\": {\n      \"@id\": \"li:segmentations\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"selectMultiple\": {\n      \"@id\": \"li:selectMultiple\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"serviceErrorCode\": {\n      \"@id\": \"li:serviceErrorCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"siblingActivities\": {\n      \"@id\": \"li:siblingActivities\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"li:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourcePlatform\": {\n      \"@id\": \"li:sourcePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"specialties\"\
  : {\n      \"@id\": \"li:specialties\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sponsoredAccount\": {\n      \"@id\": \"li:sponsoredAccount\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sponsoredAccountId\": {\n      \"@id\": \"li:sponsoredAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sponsoredAccountUrn\": {\n      \"@id\": \"li:sponsoredAccountUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"staffCountRange\": {\n      \"@id\": \"li:staffCountRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"start\": {\n      \"@id\": \"li:start\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startAt\": {\n      \"@id\": \"li:startAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"state\": {\n      \"@id\": \"li:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"li:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statuses\": {\n      \"@id\": \"li:statuses\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"li:submittedAt\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"submitter\": {\n      \"@id\": \"li:submitter\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suffix\": {\n      \"@id\": \"li:suffix\",\n      \"@type\": \"xsd:string\"\n    },\n    \"symbolicName\": {\n      \"@id\": \"li:symbolicName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tagline\": {\n      \"@id\": \"li:tagline\",\n      \"@type\": \"xsd:string\"\n    },\n    \"test\": {\n      \"@id\": \"li:test\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"testLead\": {\n      \"@id\": \"li:testLead\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"time\": {\n      \"@id\": \"li:time\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"li:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"li:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token_type\": {\n      \"@id\": \"\
  li:token_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"li:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalBudget\": {\n      \"@id\": \"li:totalBudget\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalSpend\": {\n      \"@id\": \"li:totalSpend\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"li:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uniqueForeignId\": {\n      \"@id\": \"li:uniqueForeignId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urlRules\": {\n      \"@id\": \"li:urlRules\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"urn\": {\n      \"@id\": \"li:urn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"user\": {\n      \"@id\": \"li:user\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userIds\": {\n      \"@id\": \"li:userIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"validJsSdkDomains\": {\n\
  \      \"@id\": \"li:validJsSdkDomains\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"li:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vanityName\": {\n      \"@id\": \"li:vanityName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"variables\": {\n      \"@id\": \"li:variables\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionTag\": {\n      \"@id\": \"li:versionTag\",\n      \"@type\": \"xsd:string\"\n    },\n    \"versionedLeadGenFormUrn\": {\n      \"@id\": \"li:versionedLeadGenFormUrn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"viewThroughAttributionWindowSize\": {\n      \"@id\": \"li:viewThroughAttributionWindowSize\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"visibility\": {\n      \"@id\": \"li:visibility\",\n      \"@type\": \"xsd:string\"\n    },\n    \"voluntarySelfIdentificationQuestions\": {\n      \"@id\": \"li:voluntarySelfIdentificationQuestions\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"website\": {\n      \"@id\": \"li:website\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workExperienceQuestionSet\": {\n      \"@id\": \"li:workExperienceQuestionSet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"workQuestions\": {\n      \"@id\": \"li:workQuestions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"year\": {\n      \"@id\": \"li:year\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/linkedin/refs/heads/main/json-ld/linkedin-api-context.jsonld
tags:
- Business
- Careers
- Marketing
- Professional Networking
- Recruiting
- Social Media
- JSON-LD
- Linked Data
- Semantic Web
---
