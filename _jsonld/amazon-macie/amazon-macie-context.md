---
api_specs:
- filename: amazon-macie-openapi-original.yaml
  format: yaml
  label: Amazon Macie API
  slug: amazon-macie-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-macie/refs/heads/main/openapi/amazon-macie-openapi-original.yaml
class_count: 301
classes:
- AcceptInvitationRequest
- AcceptInvitationResponse
- AccessControlList
- AccountDetail
- AccountLevelPermissions
- AdminAccount
- AllowListCriteria
- AllowListStatus
- AllowListSummary
- ApiCallDetails
- AssumedRole
- AwsAccount
- AwsService
- BatchGetCustomDataIdentifierSummary
- BatchGetCustomDataIdentifiersRequest
- BatchGetCustomDataIdentifiersResponse
- BlockPublicAccess
- BucketCountByEffectivePermission
- BucketCountByEncryptionType
- BucketCountBySharedAccessType
- BucketCountPolicyAllowsUnencryptedObjectUploads
- BucketCriteria
- BucketCriteriaAdditionalProperties
- BucketLevelPermissions
- BucketMetadata
- BucketPermissionConfiguration
- BucketPolicy
- BucketPublicAccess
- BucketServerSideEncryption
- BucketSortCriteria
- BucketStatisticsBySensitivity
- Cell
- ClassificationDetails
- ClassificationExportConfiguration
- ClassificationResult
- ClassificationResultStatus
- ClassificationScopeSummary
- CreateAllowListRequest
- CreateAllowListResponse
- CreateClassificationJobRequest
- CreateClassificationJobResponse
- CreateCustomDataIdentifierRequest
- CreateCustomDataIdentifierResponse
- CreateFindingsFilterRequest
- CreateFindingsFilterResponse
- CreateInvitationsRequest
- CreateInvitationsResponse
- CreateMemberRequest
- CreateMemberResponse
- CreateSampleFindingsRequest
- CreateSampleFindingsResponse
- CriteriaBlockForJob
- CriteriaForJob
- Criterion
- CriterionAdditionalProperties
- CustomDataIdentifierSummary
- CustomDataIdentifiers
- CustomDetection
- DailySchedule
- DeclineInvitationsRequest
- DeclineInvitationsResponse
- DefaultDetection
- DeleteAllowListRequest
- DeleteAllowListResponse
- DeleteCustomDataIdentifierRequest
- DeleteCustomDataIdentifierResponse
- DeleteFindingsFilterRequest
- DeleteFindingsFilterResponse
- DeleteInvitationsRequest
- DeleteInvitationsResponse
- DeleteMemberRequest
- DeleteMemberResponse
- DescribeBucketsRequest
- DescribeBucketsResponse
- DescribeClassificationJobRequest
- DescribeClassificationJobResponse
- DescribeOrganizationConfigurationRequest
- DescribeOrganizationConfigurationResponse
- DetectedDataDetails
- Detection
- DisableMacieRequest
- DisableMacieResponse
- DisableOrganizationAdminAccountRequest
- DisableOrganizationAdminAccountResponse
- DisassociateFromAdministratorAccountRequest
- DisassociateFromAdministratorAccountResponse
- DisassociateFromMasterAccountRequest
- DisassociateFromMasterAccountResponse
- DisassociateMemberRequest
- DisassociateMemberResponse
- DomainDetails
- EnableMacieRequest
- EnableMacieResponse
- EnableOrganizationAdminAccountRequest
- EnableOrganizationAdminAccountResponse
- FederatedUser
- Finding
- FindingAction
- FindingActor
- FindingCriteria
- FindingStatisticsSortCriteria
- FindingsFilterListItem
- GetAdministratorAccountRequest
- GetAdministratorAccountResponse
- GetAllowListRequest
- GetAllowListResponse
- GetAutomatedDiscoveryConfigurationRequest
- GetAutomatedDiscoveryConfigurationResponse
- GetBucketStatisticsRequest
- GetBucketStatisticsResponse
- GetClassificationExportConfigurationRequest
- GetClassificationExportConfigurationResponse
- GetClassificationScopeRequest
- GetClassificationScopeResponse
- GetCustomDataIdentifierRequest
- GetCustomDataIdentifierResponse
- GetFindingStatisticsRequest
- GetFindingStatisticsResponse
- GetFindingsFilterRequest
- GetFindingsFilterResponse
- GetFindingsPublicationConfigurationRequest
- GetFindingsPublicationConfigurationResponse
- GetFindingsRequest
- GetFindingsResponse
- GetInvitationsCountRequest
- GetInvitationsCountResponse
- GetMacieSessionRequest
- GetMacieSessionResponse
- GetMasterAccountRequest
- GetMasterAccountResponse
- GetMemberRequest
- GetMemberResponse
- GetResourceProfileRequest
- GetResourceProfileResponse
- GetRevealConfigurationRequest
- GetRevealConfigurationResponse
- GetSensitiveDataOccurrencesAvailabilityRequest
- GetSensitiveDataOccurrencesAvailabilityResponse
- GetSensitiveDataOccurrencesRequest
- GetSensitiveDataOccurrencesResponse
- GetSensitivityInspectionTemplateRequest
- GetSensitivityInspectionTemplateResponse
- GetUsageStatisticsRequest
- GetUsageStatisticsResponse
- GetUsageTotalsRequest
- GetUsageTotalsResponse
- GroupCount
- IamUser
- Invitation
- IpAddressDetails
- IpCity
- IpCountry
- IpGeoLocation
- IpOwner
- JobDetails
- JobScheduleFrequency
- JobScopeTerm
- JobScopingBlock
- JobSummary
- KeyValuePair
- LastRunErrorStatus
- ListAllowListsRequest
- ListAllowListsResponse
- ListClassificationJobsRequest
- ListClassificationJobsResponse
- ListClassificationScopesRequest
- ListClassificationScopesResponse
- ListCustomDataIdentifiersRequest
- ListCustomDataIdentifiersResponse
- ListFindingsFiltersRequest
- ListFindingsFiltersResponse
- ListFindingsRequest
- ListFindingsResponse
- ListInvitationsRequest
- ListInvitationsResponse
- ListJobsFilterCriteria
- ListJobsFilterTerm
- ListJobsSortCriteria
- ListManagedDataIdentifiersRequest
- ListManagedDataIdentifiersResponse
- ListMembersRequest
- ListMembersResponse
- ListOrganizationAdminAccountsRequest
- ListOrganizationAdminAccountsResponse
- ListResourceProfileArtifactsRequest
- ListResourceProfileArtifactsResponse
- ListResourceProfileDetectionsRequest
- ListResourceProfileDetectionsResponse
- ListSensitivityInspectionTemplatesRequest
- ListSensitivityInspectionTemplatesResponse
- ListTagsForResourceRequest
- ListTagsForResourceResponse
- ManagedDataIdentifierSummary
- MatchingBucket
- MatchingResource
- Member
- MonthlySchedule
- ObjectCountByEncryptionType
- ObjectLevelStatistics
- Occurrences
- Page
- PolicyDetails
- PutClassificationExportConfigurationRequest
- PutClassificationExportConfigurationResponse
- PutFindingsPublicationConfigurationRequest
- PutFindingsPublicationConfigurationResponse
- Range
- Record
- ReplicationDetails
- ResourceProfileArtifact
- ResourceStatistics
- ResourcesAffected
- RevealConfiguration
- S3Bucket
- S3BucketCriteriaForJob
- S3BucketDefinitionForJob
- S3BucketOwner
- S3ClassificationScope
- S3ClassificationScopeExclusion
- S3ClassificationScopeExclusionUpdate
- S3ClassificationScopeUpdate
- S3Destination
- S3JobDefinition
- S3Object
- S3WordsList
- Scoping
- SearchResourcesBucketCriteria
- SearchResourcesCriteria
- SearchResourcesCriteriaBlock
- SearchResourcesRequest
- SearchResourcesResponse
- SearchResourcesSimpleCriterion
- SearchResourcesSortCriteria
- SearchResourcesTagCriterion
- SearchResourcesTagCriterionPair
- SecurityHubConfiguration
- SensitiveDataItem
- SensitiveDataOccurrences
- SensitivityAggregations
- SensitivityInspectionTemplateExcludes
- SensitivityInspectionTemplateIncludes
- SensitivityInspectionTemplatesEntry
- ServerSideEncryption
- ServiceLimit
- SessionContext
- SessionContextAttributes
- SessionIssuer
- Severity
- SeverityLevel
- SimpleCriterionForJob
- SimpleScopeTerm
- SortCriteria
- Statistics
- SuppressDataIdentifier
- TagCriterionForJob
- TagCriterionPairForJob
- TagMap
- TagResourceRequest
- TagResourceResponse
- TagScopeTerm
- TagValuePair
- TestCustomDataIdentifierRequest
- TestCustomDataIdentifierResponse
- UnprocessedAccount
- UntagResourceRequest
- UntagResourceResponse
- UpdateAllowListRequest
- UpdateAllowListResponse
- UpdateAutomatedDiscoveryConfigurationRequest
- UpdateAutomatedDiscoveryConfigurationResponse
- UpdateClassificationJobRequest
- UpdateClassificationJobResponse
- UpdateClassificationScopeRequest
- UpdateClassificationScopeResponse
- UpdateFindingsFilterRequest
- UpdateFindingsFilterResponse
- UpdateMacieSessionRequest
- UpdateMacieSessionResponse
- UpdateMemberSessionRequest
- UpdateMemberSessionResponse
- UpdateOrganizationConfigurationRequest
- UpdateOrganizationConfigurationResponse
- UpdateResourceProfileDetectionsRequest
- UpdateResourceProfileDetectionsResponse
- UpdateResourceProfileRequest
- UpdateResourceProfileResponse
- UpdateRevealConfigurationRequest
- UpdateRevealConfigurationResponse
- UpdateSensitivityInspectionTemplateRequest
- UpdateSensitivityInspectionTemplateResponse
- UsageByAccount
- UsageRecord
- UsageStatisticsFilter
- UsageStatisticsSortBy
- UsageTotal
- UserIdentity
- UserIdentityRoot
- UserPausedDetails
- WeeklySchedule
- description
- name
context_file: json-ld/amazon-macie-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-macie/refs/heads/main/json-ld/amazon-macie-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Macie from Amazon Macie.
layout: jsonld
name: Amazon Macie Context
namespaces:
- prefix: amcie
  uri: https://amcie.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: accessControlList
  type: ''
- container: ''
  name: accessKeyId
  type: ''
- container: ''
  name: account
  type: ''
- container: ''
  name: accountId
  type: ''
- container: ''
  name: accountIds
  type: ''
- container: ''
  name: accountLevelPermissions
  type: ''
- container: ''
  name: action
  type: ''
- container: ''
  name: actionType
  type: ''
- container: ''
  name: actor
  type: ''
- container: ''
  name: additionalOccurrences
  type: ''
- container: ''
  name: adminAccountId
  type: ''
- container: ''
  name: adminAccounts
  type: ''
- container: ''
  name: administrator
  type: ''
- container: ''
  name: administratorAccountId
  type: ''
- container: ''
  name: allowListIds
  type: ''
- container: ''
  name: allowLists
  type: ''
- container: ''
  name: allowsPublicReadAccess
  type: ''
- container: ''
  name: allowsPublicWriteAccess
  type: ''
- container: ''
  name: allowsUnencryptedObjectUploads
  type: ''
- container: ''
  name: and
  type: ''
- container: ''
  name: api
  type: ''
- container: ''
  name: apiCallDetails
  type: ''
- container: ''
  name: apiServiceName
  type: ''
- container: ''
  name: approximateNumberOfObjectsToProcess
  type: ''
- container: ''
  name: archived
  type: ''
- container: ''
  name: arn
  type: ''
- container: ''
  name: artifacts
  type: ''
- container: ''
  name: asn
  type: ''
- container: ''
  name: asnOrg
  type: ''
- container: ''
  name: assumedRole
  type: ''
- container: ''
  name: attributeName
  type: ''
- container: ''
  name: attributes
  type: ''
- container: ''
  name: autoEnable
  type: ''
- container: ''
  name: automatedDiscoveryFreeTrialStartDate
  type: ''
- container: ''
  name: awsAccount
  type: ''
- container: ''
  name: awsService
  type: ''
- container: ''
  name: blockPublicAccess
  type: ''
- container: ''
  name: blockPublicAcls
  type: ''
- container: ''
  name: blockPublicPolicy
  type: ''
- container: ''
  name: bucketArn
  type: ''
- container: ''
  name: bucketCount
  type: ''
- container: ''
  name: bucketCountByEffectivePermission
  type: ''
- container: ''
  name: bucketCountByEncryptionType
  type: ''
- container: ''
  name: bucketCountByObjectEncryptionRequirement
  type: ''
- container: ''
  name: bucketCountBySharedAccessType
  type: ''
- container: ''
  name: bucketCreatedAt
  type: ''
- container: ''
  name: bucketCriteria
  type: ''
- container: ''
  name: bucketDefinitions
  type: ''
- container: ''
  name: bucketLevelPermissions
  type: ''
- container: ''
  name: bucketName
  type: ''
- container: ''
  name: bucketNames
  type: ''
- container: ''
  name: bucketPolicy
  type: ''
- container: ''
  name: bucketStatisticsBySensitivity
  type: ''
- container: ''
  name: buckets
  type: ''
- container: ''
  name: category
  type: ''
- container: ''
  name: cellReference
  type: ''
- container: ''
  name: cells
  type: ''
- container: ''
  name: classifiableObjectCount
  type: ''
- container: ''
  name: classifiableSizeInBytes
  type: ''
- container: ''
  name: classificationDetails
  type: ''
- container: ''
  name: classificationError
  type: ''
- container: ''
  name: classificationResultStatus
  type: ''
- container: ''
  name: classificationScopeId
  type: ''
- container: ''
  name: classificationScopes
  type: ''
- container: ''
  name: clientToken
  type: ''
- container: ''
  name: code
  type: ''
- container: ''
  name: column
  type: ''
- container: ''
  name: columnName
  type: ''
- container: ''
  name: comparator
  type: ''
- container: ''
  name: configuration
  type: ''
- container: ''
  name: count
  type: ''
- container: ''
  name: countsByGroup
  type: ''
- container: ''
  name: createdAt
  type: ''
- container: ''
  name: creationDate
  type: ''
- container: ''
  name: criteria
  type: ''
- container: ''
  name: criterion
  type: ''
- container: ''
  name: currency
  type: ''
- container: ''
  name: customDataIdentifierId
  type: ''
- container: ''
  name: customDataIdentifierIds
  type: ''
- container: ''
  name: customDataIdentifiers
  type: ''
- container: ''
  name: customerManaged
  type: ''
- container: ''
  name: dailySchedule
  type: ''
- container: ''
  name: dayOfMonth
  type: ''
- container: ''
  name: dayOfWeek
  type: ''
- container: ''
  name: defaultServerSideEncryption
  type: ''
- container: ''
  name: deleted
  type: ''
- container: ''
  name: deniesUnencryptedObjectUploads
  type: ''
- container: ''
  name: detailedResultsLocation
  type: ''
- container: ''
  name: detections
  type: ''
- container: ''
  name: disableEmailNotification
  type: ''
- container: ''
  name: disabledAt
  type: ''
- container: ''
  name: displayName
  type: ''
- container: ''
  name: domainDetails
  type: ''
- container: ''
  name: domainName
  type: ''
- container: ''
  name: eTag
  type: ''
- container: ''
  name: effectivePermission
  type: ''
- container: ''
  name: email
  type: ''
- container: ''
  name: encryptionType
  type: ''
- container: ''
  name: end
  type: ''
- container: ''
  name: eq
  type: ''
- container: ''
  name: eqExactMatch
  type: ''
- container: ''
  name: error
  type: ''
- container: ''
  name: errorCode
  type: ''
- container: ''
  name: errorMessage
  type: ''
- container: ''
  name: estimatedCost
  type: ''
- container: ''
  name: excludes
  type: ''
- container: ''
  name: extension
  type: ''
- container: ''
  name: external
  type: ''
- container: ''
  name: federatedUser
  type: ''
- container: ''
  name: fileType
  type: ''
- container: ''
  name: filterBy
  type: ''
- container: ''
  name: filterCriteria
  type: ''
- container: ''
  name: findingCriteria
  type: ''
- container: ''
  name: findingIds
  type: ''
- container: ''
  name: findingPublishingFrequency
  type: ''
- container: ''
  name: findingTypes
  type: ''
- container: ''
  name: findings
  type: ''
- container: ''
  name: findingsFilterListItems
  type: ''
- container: ''
  name: firstEnabledAt
  type: ''
- container: ''
  name: firstSeen
  type: ''
- container: ''
  name: freeTrialStartDate
  type: ''
- container: ''
  name: groupBy
  type: ''
- container: ''
  name: groupKey
  type: ''
- container: ''
  name: gt
  type: ''
- container: ''
  name: gte
  type: ''
- container: ''
  name: iamUser
  type: ''
- container: ''
  name: id
  type: ''
- container: ''
  name: ids
  type: ''
- container: ''
  name: ignorePublicAcls
  type: ''
- container: ''
  name: ignoreWords
  type: ''
- container: ''
  name: includes
  type: ''
- container: ''
  name: initialRun
  type: ''
- container: ''
  name: internal
  type: ''
- container: ''
  name: invitationId
  type: ''
- container: ''
  name: invitations
  type: ''
- container: ''
  name: invitationsCount
  type: ''
- container: ''
  name: invitedAt
  type: ''
- container: ''
  name: invokedBy
  type: ''
- container: ''
  name: ipAddressDetails
  type: ''
- container: ''
  name: ipAddressV4
  type: ''
- container: ''
  name: ipCity
  type: ''
- container: ''
  name: ipCountry
  type: ''
- container: ''
  name: ipGeoLocation
  type: ''
- container: ''
  name: ipOwner
  type: ''
- container: ''
  name: isDefinedInJob
  type: ''
- container: ''
  name: isMonitoredByJob
  type: ''
- container: ''
  name: isServiceLimited
  type: ''
- container: ''
  name: isp
  type: ''
- container: ''
  name: items
  type: ''
- container: ''
  name: jobArn
  type: ''
- container: ''
  name: jobDetails
  type: ''
- container: ''
  name: jobExpiresAt
  type: ''
- container: ''
  name: jobId
  type: ''
- container: ''
  name: jobImminentExpirationHealthEventArn
  type: ''
- container: ''
  name: jobPausedAt
  type: ''
- container: ''
  name: jobStatus
  type: ''
- container: ''
  name: jobType
  type: ''
- container: ''
  name: jsonPath
  type: ''
- container: ''
  name: key
  type: ''
- container: ''
  name: keyPrefix
  type: ''
- container: ''
  name: keywords
  type: ''
- container: ''
  name: kmsKeyArn
  type: ''
- container: ''
  name: kmsKeyId
  type: ''
- container: ''
  name: kmsManaged
  type: ''
- container: ''
  name: kmsMasterKeyId
  type: ''
- container: ''
  name: lastAutomatedDiscoveryTime
  type: ''
- container: ''
  name: lastJobId
  type: ''
- container: ''
  name: lastJobRunTime
  type: ''
- container: ''
  name: lastModified
  type: ''
- container: ''
  name: lastRunErrorStatus
  type: ''
- container: ''
  name: lastRunTime
  type: ''
- container: ''
  name: lastSeen
  type: ''
- container: ''
  name: lastUpdated
  type: ''
- container: ''
  name: lastUpdatedAt
  type: ''
- container: ''
  name: lat
  type: ''
- container: ''
  name: lineRange
  type: ''
- container: ''
  name: lineRanges
  type: ''
- container: ''
  name: lon
  type: ''
- container: ''
  name: lt
  type: ''
- container: ''
  name: lte
  type: ''
- container: ''
  name: managedDataIdentifierIds
  type: ''
- container: ''
  name: managedDataIdentifierSelector
  type: ''
- container: ''
  name: master
  type: ''
- container: ''
  name: masterAccount
  type: ''
- container: ''
  name: masterAccountId
  type: ''
- container: ''
  name: matchCount
  type: ''
- container: ''
  name: matchingBucket
  type: ''
- container: ''
  name: matchingResources
  type: ''
- container: ''
  name: maxAccountLimitReached
  type: ''
- container: ''
  name: maxResults
  type: ''
- container: ''
  name: maximumMatchDistance
  type: ''
- container: ''
  name: members
  type: ''
- container: ''
  name: message
  type: ''
- container: ''
  name: mfaAuthenticated
  type: ''
- container: ''
  name: mimeType
  type: ''
- container: ''
  name: monthlySchedule
  type: ''
- container: ''
  name: neq
  type: ''
- container: ''
  name: nextToken
  type: ''
- container: ''
  name: notClassified
  type: ''
- container: ''
  name: notFoundIdentifierIds
  type: ''
- container: ''
  name: notSensitive
  type: ''
- container: ''
  name: notShared
  type: ''
- container: ''
  name: numberOfRuns
  type: ''
- container: ''
  name: objectCount
  type: ''
- container: ''
  name: objectCountByEncryptionType
  type: ''
- container: ''
  name: objectKey
  type: ''
- container: ''
  name: occurrences
  type: ''
- container: ''
  name: occurrencesThreshold
  type: ''
- container: ''
  name: offsetRange
  type: ''
- container: ''
  name: offsetRanges
  type: ''
- container: ''
  name: operation
  type: ''
- container: ''
  name: orderBy
  type: ''
- container: ''
  name: org
  type: ''
- container: ''
  name: originType
  type: ''
- container: ''
  name: owner
  type: ''
- container: ''
  name: pageNumber
  type: ''
- container: ''
  name: pages
  type: ''
- container: ''
  name: partition
  type: ''
- container: ''
  name: path
  type: ''
- container: ''
  name: permissionConfiguration
  type: ''
- container: ''
  name: policyDetails
  type: ''
- container: ''
  name: position
  type: ''
- container: ''
  name: prefix
  type: ''
- container: ''
  name: principalId
  type: ''
- container: ''
  name: profileUpdatedAt
  type: ''
- container: ''
  name: publicAccess
  type: ''
- container: ''
  name: publiclyAccessible
  type: ''
- container: ''
  name: publiclyAccessibleCount
  type: ''
- container: ''
  name: publiclyReadable
  type: ''
- container: ''
  name: publiclyWritable
  type: ''
- container: ''
  name: publishClassificationFindings
  type: ''
- container: ''
  name: publishPolicyFindings
  type: ''
- container: ''
  name: reason
  type: ''
- container: ''
  name: reasons
  type: ''
- container: ''
  name: recordIndex
  type: ''
- container: ''
  name: records
  type: ''
- container: ''
  name: regex
  type: ''
- container: ''
  name: region
  type: ''
- container: ''
  name: relationshipStatus
  type: ''
- container: ''
  name: replicated
  type: ''
- container: ''
  name: replicatedExternally
  type: ''
- container: ''
  name: replicationAccounts
  type: ''
- container: ''
  name: replicationDetails
  type: ''
- container: ''
  name: resourcesAffected
  type: ''
- container: ''
  name: restrictPublicBuckets
  type: ''
- container: ''
  name: result
  type: ''
- container: ''
  name: root
  type: ''
- container: ''
  name: row
  type: ''
- container: ''
  name: s3
  type: ''
- container: ''
  name: s3Bucket
  type: ''
- container: ''
  name: s3Destination
  type: ''
- container: ''
  name: s3JobDefinition
  type: ''
- container: ''
  name: s3Managed
  type: ''
- container: ''
  name: s3Object
  type: ''
- container: ''
  name: s3WordsList
  type: ''
- container: ''
  name: sample
  type: ''
- container: ''
  name: sampleText
  type: ''
- container: ''
  name: samplingPercentage
  type: ''
- container: ''
  name: scheduleFrequency
  type: ''
- container: ''
  name: schemaVersion
  type: ''
- container: ''
  name: scoping
  type: ''
- container: ''
  name: score
  type: ''
- container: ''
  name: securityHubConfiguration
  type: ''
- container: ''
  name: sensitive
  type: ''
- container: ''
  name: sensitiveData
  type: ''
- container: ''
  name: sensitiveDataOccurrences
  type: ''
- container: ''
  name: sensitivityInspectionTemplateId
  type: ''
- container: ''
  name: sensitivityInspectionTemplates
  type: ''
- container: ''
  name: sensitivityScore
  type: ''
- container: ''
  name: sensitivityScoreOverridden
  type: ''
- container: ''
  name: sensitivityScoreOverride
  type: ''
- container: ''
  name: serverSideEncryption
  type: ''
- container: ''
  name: serviceLimit
  type: ''
- container: ''
  name: serviceRole
  type: ''
- container: ''
  name: sessionContext
  type: ''
- container: ''
  name: sessionIssuer
  type: ''
- container: ''
  name: severity
  type: ''
- container: ''
  name: severityLevels
  type: ''
- container: ''
  name: sharedAccess
  type: ''
- container: ''
  name: simpleCriterion
  type: ''
- container: ''
  name: simpleScopeTerm
  type: ''
- container: ''
  name: size
  type: ''
- container: ''
  name: sizeClassified
  type: ''
- container: ''
  name: sizeInBytes
  type: ''
- container: ''
  name: sizeInBytesCompressed
  type: ''
- container: ''
  name: sortBy
  type: ''
- container: ''
  name: sortCriteria
  type: ''
- container: ''
  name: start
  type: ''
- container: ''
  name: startColumn
  type: ''
- container: ''
  name: statistics
  type: ''
- container: ''
  name: status
  type: ''
- container: ''
  name: storageClass
  type: ''
- container: ''
  name: suppressDataIdentifiers
  type: ''
- container: ''
  name: suppressed
  type: ''
- container: ''
  name: tagCriterion
  type: ''
- container: ''
  name: tagScopeTerm
  type: ''
- container: ''
  name: tagValues
  type: ''
- container: ''
  name: tags
  type: ''
- container: ''
  name: target
  type: ''
- container: ''
  name: timeRange
  type: ''
- container: ''
  name: title
  type: ''
- container: ''
  name: total
  type: ''
- container: ''
  name: totalBytesClassified
  type: ''
- container: ''
  name: totalCount
  type: ''
- container: ''
  name: totalDetections
  type: ''
- container: ''
  name: totalDetectionsSuppressed
  type: ''
- container: ''
  name: totalItemsClassified
  type: ''
- container: ''
  name: totalItemsSensitive
  type: ''
- container: ''
  name: totalItemsSkipped
  type: ''
- container: ''
  name: totalItemsSkippedInvalidEncryption
  type: ''
- container: ''
  name: totalItemsSkippedInvalidKms
  type: ''
- container: ''
  name: totalItemsSkippedPermissionDenied
  type: ''
- container: ''
  name: totalSizeInBytes
  type: ''
- container: ''
  name: type
  type: ''
- container: ''
  name: unclassifiableObjectCount
  type: ''
- container: ''
  name: unclassifiableObjectSizeInBytes
  type: ''
- container: ''
  name: unencrypted
  type: ''
- container: ''
  name: unit
  type: ''
- container: ''
  name: unknown
  type: ''
- container: ''
  name: unprocessedAccounts
  type: ''
- container: ''
  name: updatedAt
  type: ''
- container: ''
  name: usage
  type: ''
- container: ''
  name: usageTotals
  type: ''
- container: ''
  name: userIdentity
  type: ''
- container: ''
  name: userName
  type: ''
- container: ''
  name: userPausedDetails
  type: ''
- container: ''
  name: value
  type: ''
- container: ''
  name: values
  type: ''
- container: ''
  name: versionId
  type: ''
- container: ''
  name: versioning
  type: ''
- container: ''
  name: weeklySchedule
  type: ''
property_count: 331
provider_name: Amazon Macie
provider_slug: amazon-macie
slug: amazon-macie-context
source_filename: amazon-macie-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amcie\": \"https://amcie.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AcceptInvitationRequest\": \"amcie:AcceptInvitationRequest\",\n    \"AcceptInvitationResponse\": \"amcie:AcceptInvitationResponse\",\n    \"AccessControlList\": \"amcie:AccessControlList\",\n    \"AccountDetail\": \"amcie:AccountDetail\",\n    \"AccountLevelPermissions\": \"amcie:AccountLevelPermissions\",\n    \"AdminAccount\": \"amcie:AdminAccount\",\n    \"AllowListCriteria\": \"amcie:AllowListCriteria\",\n    \"AllowListStatus\": \"amcie:AllowListStatus\",\n    \"AllowListSummary\": \"amcie:AllowListSummary\",\n    \"ApiCallDetails\": \"amcie:ApiCallDetails\",\n    \"AssumedRole\": \"amcie:AssumedRole\",\n    \"AwsAccount\": \"amcie:AwsAccount\",\n    \"AwsService\": \"amcie:AwsService\",\n    \"BatchGetCustomDataIdentifierSummary\"\
  : \"amcie:BatchGetCustomDataIdentifierSummary\",\n    \"BatchGetCustomDataIdentifiersRequest\": \"amcie:BatchGetCustomDataIdentifiersRequest\",\n    \"BatchGetCustomDataIdentifiersResponse\": \"amcie:BatchGetCustomDataIdentifiersResponse\",\n    \"BlockPublicAccess\": \"amcie:BlockPublicAccess\",\n    \"BucketCountByEffectivePermission\": \"amcie:BucketCountByEffectivePermission\",\n    \"BucketCountByEncryptionType\": \"amcie:BucketCountByEncryptionType\",\n    \"BucketCountBySharedAccessType\": \"amcie:BucketCountBySharedAccessType\",\n    \"BucketCountPolicyAllowsUnencryptedObjectUploads\": \"amcie:BucketCountPolicyAllowsUnencryptedObjectUploads\",\n    \"BucketCriteria\": \"amcie:BucketCriteria\",\n    \"BucketCriteriaAdditionalProperties\": \"amcie:BucketCriteriaAdditionalProperties\",\n    \"BucketLevelPermissions\": \"amcie:BucketLevelPermissions\",\n    \"BucketMetadata\": \"amcie:BucketMetadata\",\n    \"BucketPermissionConfiguration\": \"amcie:BucketPermissionConfiguration\"\
  ,\n    \"BucketPolicy\": \"amcie:BucketPolicy\",\n    \"BucketPublicAccess\": \"amcie:BucketPublicAccess\",\n    \"BucketServerSideEncryption\": \"amcie:BucketServerSideEncryption\",\n    \"BucketSortCriteria\": \"amcie:BucketSortCriteria\",\n    \"BucketStatisticsBySensitivity\": \"amcie:BucketStatisticsBySensitivity\",\n    \"Cell\": \"amcie:Cell\",\n    \"ClassificationDetails\": \"amcie:ClassificationDetails\",\n    \"ClassificationExportConfiguration\": \"amcie:ClassificationExportConfiguration\",\n    \"ClassificationResult\": \"amcie:ClassificationResult\",\n    \"ClassificationResultStatus\": \"amcie:ClassificationResultStatus\",\n    \"ClassificationScopeSummary\": \"amcie:ClassificationScopeSummary\",\n    \"CreateAllowListRequest\": \"amcie:CreateAllowListRequest\",\n    \"CreateAllowListResponse\": \"amcie:CreateAllowListResponse\",\n    \"CreateClassificationJobRequest\": \"amcie:CreateClassificationJobRequest\",\n    \"CreateClassificationJobResponse\": \"amcie:CreateClassificationJobResponse\"\
  ,\n    \"CreateCustomDataIdentifierRequest\": \"amcie:CreateCustomDataIdentifierRequest\",\n    \"CreateCustomDataIdentifierResponse\": \"amcie:CreateCustomDataIdentifierResponse\",\n    \"CreateFindingsFilterRequest\": \"amcie:CreateFindingsFilterRequest\",\n    \"CreateFindingsFilterResponse\": \"amcie:CreateFindingsFilterResponse\",\n    \"CreateInvitationsRequest\": \"amcie:CreateInvitationsRequest\",\n    \"CreateInvitationsResponse\": \"amcie:CreateInvitationsResponse\",\n    \"CreateMemberRequest\": \"amcie:CreateMemberRequest\",\n    \"CreateMemberResponse\": \"amcie:CreateMemberResponse\",\n    \"CreateSampleFindingsRequest\": \"amcie:CreateSampleFindingsRequest\",\n    \"CreateSampleFindingsResponse\": \"amcie:CreateSampleFindingsResponse\",\n    \"CriteriaBlockForJob\": \"amcie:CriteriaBlockForJob\",\n    \"CriteriaForJob\": \"amcie:CriteriaForJob\",\n    \"Criterion\": \"amcie:Criterion\",\n    \"CriterionAdditionalProperties\": \"amcie:CriterionAdditionalProperties\",\n  \
  \  \"CustomDataIdentifierSummary\": \"amcie:CustomDataIdentifierSummary\",\n    \"CustomDataIdentifiers\": \"amcie:CustomDataIdentifiers\",\n    \"CustomDetection\": \"amcie:CustomDetection\",\n    \"DailySchedule\": \"amcie:DailySchedule\",\n    \"DeclineInvitationsRequest\": \"amcie:DeclineInvitationsRequest\",\n    \"DeclineInvitationsResponse\": \"amcie:DeclineInvitationsResponse\",\n    \"DefaultDetection\": \"amcie:DefaultDetection\",\n    \"DeleteAllowListRequest\": \"amcie:DeleteAllowListRequest\",\n    \"DeleteAllowListResponse\": \"amcie:DeleteAllowListResponse\",\n    \"DeleteCustomDataIdentifierRequest\": \"amcie:DeleteCustomDataIdentifierRequest\",\n    \"DeleteCustomDataIdentifierResponse\": \"amcie:DeleteCustomDataIdentifierResponse\",\n    \"DeleteFindingsFilterRequest\": \"amcie:DeleteFindingsFilterRequest\",\n    \"DeleteFindingsFilterResponse\": \"amcie:DeleteFindingsFilterResponse\",\n    \"DeleteInvitationsRequest\": \"amcie:DeleteInvitationsRequest\",\n    \"DeleteInvitationsResponse\"\
  : \"amcie:DeleteInvitationsResponse\",\n    \"DeleteMemberRequest\": \"amcie:DeleteMemberRequest\",\n    \"DeleteMemberResponse\": \"amcie:DeleteMemberResponse\",\n    \"DescribeBucketsRequest\": \"amcie:DescribeBucketsRequest\",\n    \"DescribeBucketsResponse\": \"amcie:DescribeBucketsResponse\",\n    \"DescribeClassificationJobRequest\": \"amcie:DescribeClassificationJobRequest\",\n    \"DescribeClassificationJobResponse\": \"amcie:DescribeClassificationJobResponse\",\n    \"DescribeOrganizationConfigurationRequest\": \"amcie:DescribeOrganizationConfigurationRequest\",\n    \"DescribeOrganizationConfigurationResponse\": \"amcie:DescribeOrganizationConfigurationResponse\",\n    \"DetectedDataDetails\": \"amcie:DetectedDataDetails\",\n    \"Detection\": \"amcie:Detection\",\n    \"DisableMacieRequest\": \"amcie:DisableMacieRequest\",\n    \"DisableMacieResponse\": \"amcie:DisableMacieResponse\",\n    \"DisableOrganizationAdminAccountRequest\": \"amcie:DisableOrganizationAdminAccountRequest\"\
  ,\n    \"DisableOrganizationAdminAccountResponse\": \"amcie:DisableOrganizationAdminAccountResponse\",\n    \"DisassociateFromAdministratorAccountRequest\": \"amcie:DisassociateFromAdministratorAccountRequest\",\n    \"DisassociateFromAdministratorAccountResponse\": \"amcie:DisassociateFromAdministratorAccountResponse\",\n    \"DisassociateFromMasterAccountRequest\": \"amcie:DisassociateFromMasterAccountRequest\",\n    \"DisassociateFromMasterAccountResponse\": \"amcie:DisassociateFromMasterAccountResponse\",\n    \"DisassociateMemberRequest\": \"amcie:DisassociateMemberRequest\",\n    \"DisassociateMemberResponse\": \"amcie:DisassociateMemberResponse\",\n    \"DomainDetails\": \"amcie:DomainDetails\",\n    \"EnableMacieRequest\": \"amcie:EnableMacieRequest\",\n    \"EnableMacieResponse\": \"amcie:EnableMacieResponse\",\n    \"EnableOrganizationAdminAccountRequest\": \"amcie:EnableOrganizationAdminAccountRequest\",\n    \"EnableOrganizationAdminAccountResponse\": \"amcie:EnableOrganizationAdminAccountResponse\"\
  ,\n    \"FederatedUser\": \"amcie:FederatedUser\",\n    \"Finding\": \"amcie:Finding\",\n    \"FindingAction\": \"amcie:FindingAction\",\n    \"FindingActor\": \"amcie:FindingActor\",\n    \"FindingCriteria\": \"amcie:FindingCriteria\",\n    \"FindingStatisticsSortCriteria\": \"amcie:FindingStatisticsSortCriteria\",\n    \"FindingsFilterListItem\": \"amcie:FindingsFilterListItem\",\n    \"GetAdministratorAccountRequest\": \"amcie:GetAdministratorAccountRequest\",\n    \"GetAdministratorAccountResponse\": \"amcie:GetAdministratorAccountResponse\",\n    \"GetAllowListRequest\": \"amcie:GetAllowListRequest\",\n    \"GetAllowListResponse\": \"amcie:GetAllowListResponse\",\n    \"GetAutomatedDiscoveryConfigurationRequest\": \"amcie:GetAutomatedDiscoveryConfigurationRequest\",\n    \"GetAutomatedDiscoveryConfigurationResponse\": \"amcie:GetAutomatedDiscoveryConfigurationResponse\",\n    \"GetBucketStatisticsRequest\": \"amcie:GetBucketStatisticsRequest\",\n    \"GetBucketStatisticsResponse\"\
  : \"amcie:GetBucketStatisticsResponse\",\n    \"GetClassificationExportConfigurationRequest\": \"amcie:GetClassificationExportConfigurationRequest\",\n    \"GetClassificationExportConfigurationResponse\": \"amcie:GetClassificationExportConfigurationResponse\",\n    \"GetClassificationScopeRequest\": \"amcie:GetClassificationScopeRequest\",\n    \"GetClassificationScopeResponse\": \"amcie:GetClassificationScopeResponse\",\n    \"GetCustomDataIdentifierRequest\": \"amcie:GetCustomDataIdentifierRequest\",\n    \"GetCustomDataIdentifierResponse\": \"amcie:GetCustomDataIdentifierResponse\",\n    \"GetFindingStatisticsRequest\": \"amcie:GetFindingStatisticsRequest\",\n    \"GetFindingStatisticsResponse\": \"amcie:GetFindingStatisticsResponse\",\n    \"GetFindingsFilterRequest\": \"amcie:GetFindingsFilterRequest\",\n    \"GetFindingsFilterResponse\": \"amcie:GetFindingsFilterResponse\",\n    \"GetFindingsPublicationConfigurationRequest\": \"amcie:GetFindingsPublicationConfigurationRequest\",\n\
  \    \"GetFindingsPublicationConfigurationResponse\": \"amcie:GetFindingsPublicationConfigurationResponse\",\n    \"GetFindingsRequest\": \"amcie:GetFindingsRequest\",\n    \"GetFindingsResponse\": \"amcie:GetFindingsResponse\",\n    \"GetInvitationsCountRequest\": \"amcie:GetInvitationsCountRequest\",\n    \"GetInvitationsCountResponse\": \"amcie:GetInvitationsCountResponse\",\n    \"GetMacieSessionRequest\": \"amcie:GetMacieSessionRequest\",\n    \"GetMacieSessionResponse\": \"amcie:GetMacieSessionResponse\",\n    \"GetMasterAccountRequest\": \"amcie:GetMasterAccountRequest\",\n    \"GetMasterAccountResponse\": \"amcie:GetMasterAccountResponse\",\n    \"GetMemberRequest\": \"amcie:GetMemberRequest\",\n    \"GetMemberResponse\": \"amcie:GetMemberResponse\",\n    \"GetResourceProfileRequest\": \"amcie:GetResourceProfileRequest\",\n    \"GetResourceProfileResponse\": \"amcie:GetResourceProfileResponse\",\n    \"GetRevealConfigurationRequest\": \"amcie:GetRevealConfigurationRequest\",\n\
  \    \"GetRevealConfigurationResponse\": \"amcie:GetRevealConfigurationResponse\",\n    \"GetSensitiveDataOccurrencesAvailabilityRequest\": \"amcie:GetSensitiveDataOccurrencesAvailabilityRequest\",\n    \"GetSensitiveDataOccurrencesAvailabilityResponse\": \"amcie:GetSensitiveDataOccurrencesAvailabilityResponse\",\n    \"GetSensitiveDataOccurrencesRequest\": \"amcie:GetSensitiveDataOccurrencesRequest\",\n    \"GetSensitiveDataOccurrencesResponse\": \"amcie:GetSensitiveDataOccurrencesResponse\",\n    \"GetSensitivityInspectionTemplateRequest\": \"amcie:GetSensitivityInspectionTemplateRequest\",\n    \"GetSensitivityInspectionTemplateResponse\": \"amcie:GetSensitivityInspectionTemplateResponse\",\n    \"GetUsageStatisticsRequest\": \"amcie:GetUsageStatisticsRequest\",\n    \"GetUsageStatisticsResponse\": \"amcie:GetUsageStatisticsResponse\",\n    \"GetUsageTotalsRequest\": \"amcie:GetUsageTotalsRequest\",\n    \"GetUsageTotalsResponse\": \"amcie:GetUsageTotalsResponse\",\n    \"GroupCount\"\
  : \"amcie:GroupCount\",\n    \"IamUser\": \"amcie:IamUser\",\n    \"Invitation\": \"amcie:Invitation\",\n    \"IpAddressDetails\": \"amcie:IpAddressDetails\",\n    \"IpCity\": \"amcie:IpCity\",\n    \"IpCountry\": \"amcie:IpCountry\",\n    \"IpGeoLocation\": \"amcie:IpGeoLocation\",\n    \"IpOwner\": \"amcie:IpOwner\",\n    \"JobDetails\": \"amcie:JobDetails\",\n    \"JobScheduleFrequency\": \"amcie:JobScheduleFrequency\",\n    \"JobScopeTerm\": \"amcie:JobScopeTerm\",\n    \"JobScopingBlock\": \"amcie:JobScopingBlock\",\n    \"JobSummary\": \"amcie:JobSummary\",\n    \"KeyValuePair\": \"amcie:KeyValuePair\",\n    \"LastRunErrorStatus\": \"amcie:LastRunErrorStatus\",\n    \"ListAllowListsRequest\": \"amcie:ListAllowListsRequest\",\n    \"ListAllowListsResponse\": \"amcie:ListAllowListsResponse\",\n    \"ListClassificationJobsRequest\": \"amcie:ListClassificationJobsRequest\",\n    \"ListClassificationJobsResponse\": \"amcie:ListClassificationJobsResponse\",\n    \"ListClassificationScopesRequest\"\
  : \"amcie:ListClassificationScopesRequest\",\n    \"ListClassificationScopesResponse\": \"amcie:ListClassificationScopesResponse\",\n    \"ListCustomDataIdentifiersRequest\": \"amcie:ListCustomDataIdentifiersRequest\",\n    \"ListCustomDataIdentifiersResponse\": \"amcie:ListCustomDataIdentifiersResponse\",\n    \"ListFindingsFiltersRequest\": \"amcie:ListFindingsFiltersRequest\",\n    \"ListFindingsFiltersResponse\": \"amcie:ListFindingsFiltersResponse\",\n    \"ListFindingsRequest\": \"amcie:ListFindingsRequest\",\n    \"ListFindingsResponse\": \"amcie:ListFindingsResponse\",\n    \"ListInvitationsRequest\": \"amcie:ListInvitationsRequest\",\n    \"ListInvitationsResponse\": \"amcie:ListInvitationsResponse\",\n    \"ListJobsFilterCriteria\": \"amcie:ListJobsFilterCriteria\",\n    \"ListJobsFilterTerm\": \"amcie:ListJobsFilterTerm\",\n    \"ListJobsSortCriteria\": \"amcie:ListJobsSortCriteria\",\n    \"ListManagedDataIdentifiersRequest\": \"amcie:ListManagedDataIdentifiersRequest\",\n\
  \    \"ListManagedDataIdentifiersResponse\": \"amcie:ListManagedDataIdentifiersResponse\",\n    \"ListMembersRequest\": \"amcie:ListMembersRequest\",\n    \"ListMembersResponse\": \"amcie:ListMembersResponse\",\n    \"ListOrganizationAdminAccountsRequest\": \"amcie:ListOrganizationAdminAccountsRequest\",\n    \"ListOrganizationAdminAccountsResponse\": \"amcie:ListOrganizationAdminAccountsResponse\",\n    \"ListResourceProfileArtifactsRequest\": \"amcie:ListResourceProfileArtifactsRequest\",\n    \"ListResourceProfileArtifactsResponse\": \"amcie:ListResourceProfileArtifactsResponse\",\n    \"ListResourceProfileDetectionsRequest\": \"amcie:ListResourceProfileDetectionsRequest\",\n    \"ListResourceProfileDetectionsResponse\": \"amcie:ListResourceProfileDetectionsResponse\",\n    \"ListSensitivityInspectionTemplatesRequest\": \"amcie:ListSensitivityInspectionTemplatesRequest\",\n    \"ListSensitivityInspectionTemplatesResponse\": \"amcie:ListSensitivityInspectionTemplatesResponse\",\n   \
  \ \"ListTagsForResourceRequest\": \"amcie:ListTagsForResourceRequest\",\n    \"ListTagsForResourceResponse\": \"amcie:ListTagsForResourceResponse\",\n    \"ManagedDataIdentifierSummary\": \"amcie:ManagedDataIdentifierSummary\",\n    \"MatchingBucket\": \"amcie:MatchingBucket\",\n    \"MatchingResource\": \"amcie:MatchingResource\",\n    \"Member\": \"amcie:Member\",\n    \"MonthlySchedule\": \"amcie:MonthlySchedule\",\n    \"ObjectCountByEncryptionType\": \"amcie:ObjectCountByEncryptionType\",\n    \"ObjectLevelStatistics\": \"amcie:ObjectLevelStatistics\",\n    \"Occurrences\": \"amcie:Occurrences\",\n    \"Page\": \"amcie:Page\",\n    \"PolicyDetails\": \"amcie:PolicyDetails\",\n    \"PutClassificationExportConfigurationRequest\": \"amcie:PutClassificationExportConfigurationRequest\",\n    \"PutClassificationExportConfigurationResponse\": \"amcie:PutClassificationExportConfigurationResponse\",\n    \"PutFindingsPublicationConfigurationRequest\": \"amcie:PutFindingsPublicationConfigurationRequest\"\
  ,\n    \"PutFindingsPublicationConfigurationResponse\": \"amcie:PutFindingsPublicationConfigurationResponse\",\n    \"Range\": \"amcie:Range\",\n    \"Record\": \"amcie:Record\",\n    \"ReplicationDetails\": \"amcie:ReplicationDetails\",\n    \"ResourceProfileArtifact\": \"amcie:ResourceProfileArtifact\",\n    \"ResourceStatistics\": \"amcie:ResourceStatistics\",\n    \"ResourcesAffected\": \"amcie:ResourcesAffected\",\n    \"RevealConfiguration\": \"amcie:RevealConfiguration\",\n    \"S3Bucket\": \"amcie:S3Bucket\",\n    \"S3BucketCriteriaForJob\": \"amcie:S3BucketCriteriaForJob\",\n    \"S3BucketDefinitionForJob\": \"amcie:S3BucketDefinitionForJob\",\n    \"S3BucketOwner\": \"amcie:S3BucketOwner\",\n    \"S3ClassificationScope\": \"amcie:S3ClassificationScope\",\n    \"S3ClassificationScopeExclusion\": \"amcie:S3ClassificationScopeExclusion\",\n    \"S3ClassificationScopeExclusionUpdate\": \"amcie:S3ClassificationScopeExclusionUpdate\",\n    \"S3ClassificationScopeUpdate\": \"amcie:S3ClassificationScopeUpdate\"\
  ,\n    \"S3Destination\": \"amcie:S3Destination\",\n    \"S3JobDefinition\": \"amcie:S3JobDefinition\",\n    \"S3Object\": \"amcie:S3Object\",\n    \"S3WordsList\": \"amcie:S3WordsList\",\n    \"Scoping\": \"amcie:Scoping\",\n    \"SearchResourcesBucketCriteria\": \"amcie:SearchResourcesBucketCriteria\",\n    \"SearchResourcesCriteria\": \"amcie:SearchResourcesCriteria\",\n    \"SearchResourcesCriteriaBlock\": \"amcie:SearchResourcesCriteriaBlock\",\n    \"SearchResourcesRequest\": \"amcie:SearchResourcesRequest\",\n    \"SearchResourcesResponse\": \"amcie:SearchResourcesResponse\",\n    \"SearchResourcesSimpleCriterion\": \"amcie:SearchResourcesSimpleCriterion\",\n    \"SearchResourcesSortCriteria\": \"amcie:SearchResourcesSortCriteria\",\n    \"SearchResourcesTagCriterion\": \"amcie:SearchResourcesTagCriterion\",\n    \"SearchResourcesTagCriterionPair\": \"amcie:SearchResourcesTagCriterionPair\",\n    \"SecurityHubConfiguration\": \"amcie:SecurityHubConfiguration\",\n    \"SensitiveDataItem\"\
  : \"amcie:SensitiveDataItem\",\n    \"SensitiveDataOccurrences\": \"amcie:SensitiveDataOccurrences\",\n    \"SensitivityAggregations\": \"amcie:SensitivityAggregations\",\n    \"SensitivityInspectionTemplateExcludes\": \"amcie:SensitivityInspectionTemplateExcludes\",\n    \"SensitivityInspectionTemplateIncludes\": \"amcie:SensitivityInspectionTemplateIncludes\",\n    \"SensitivityInspectionTemplatesEntry\": \"amcie:SensitivityInspectionTemplatesEntry\",\n    \"ServerSideEncryption\": \"amcie:ServerSideEncryption\",\n    \"ServiceLimit\": \"amcie:ServiceLimit\",\n    \"SessionContext\": \"amcie:SessionContext\",\n    \"SessionContextAttributes\": \"amcie:SessionContextAttributes\",\n    \"SessionIssuer\": \"amcie:SessionIssuer\",\n    \"Severity\": \"amcie:Severity\",\n    \"SeverityLevel\": \"amcie:SeverityLevel\",\n    \"SimpleCriterionForJob\": \"amcie:SimpleCriterionForJob\",\n    \"SimpleScopeTerm\": \"amcie:SimpleScopeTerm\",\n    \"SortCriteria\": \"amcie:SortCriteria\",\n    \"\
  Statistics\": \"amcie:Statistics\",\n    \"SuppressDataIdentifier\": \"amcie:SuppressDataIdentifier\",\n    \"TagCriterionForJob\": \"amcie:TagCriterionForJob\",\n    \"TagCriterionPairForJob\": \"amcie:TagCriterionPairForJob\",\n    \"TagMap\": \"amcie:TagMap\",\n    \"TagResourceRequest\": \"amcie:TagResourceRequest\",\n    \"TagResourceResponse\": \"amcie:TagResourceResponse\",\n    \"TagScopeTerm\": \"amcie:TagScopeTerm\",\n    \"TagValuePair\": \"amcie:TagValuePair\",\n    \"TestCustomDataIdentifierRequest\": \"amcie:TestCustomDataIdentifierRequest\",\n    \"TestCustomDataIdentifierResponse\": \"amcie:TestCustomDataIdentifierResponse\",\n    \"UnprocessedAccount\": \"amcie:UnprocessedAccount\",\n    \"UntagResourceRequest\": \"amcie:UntagResourceRequest\",\n    \"UntagResourceResponse\": \"amcie:UntagResourceResponse\",\n    \"UpdateAllowListRequest\": \"amcie:UpdateAllowListRequest\",\n    \"UpdateAllowListResponse\": \"amcie:UpdateAllowListResponse\",\n    \"UpdateAutomatedDiscoveryConfigurationRequest\"\
  : \"amcie:UpdateAutomatedDiscoveryConfigurationRequest\",\n    \"UpdateAutomatedDiscoveryConfigurationResponse\": \"amcie:UpdateAutomatedDiscoveryConfigurationResponse\",\n    \"UpdateClassificationJobRequest\": \"amcie:UpdateClassificationJobRequest\",\n    \"UpdateClassificationJobResponse\": \"amcie:UpdateClassificationJobResponse\",\n    \"UpdateClassificationScopeRequest\": \"amcie:UpdateClassificationScopeRequest\",\n    \"UpdateClassificationScopeResponse\": \"amcie:UpdateClassificationScopeResponse\",\n    \"UpdateFindingsFilterRequest\": \"amcie:UpdateFindingsFilterRequest\",\n    \"UpdateFindingsFilterResponse\": \"amcie:UpdateFindingsFilterResponse\",\n    \"UpdateMacieSessionRequest\": \"amcie:UpdateMacieSessionRequest\",\n    \"UpdateMacieSessionResponse\": \"amcie:UpdateMacieSessionResponse\",\n    \"UpdateMemberSessionRequest\": \"amcie:UpdateMemberSessionRequest\",\n    \"UpdateMemberSessionResponse\": \"amcie:UpdateMemberSessionResponse\",\n    \"UpdateOrganizationConfigurationRequest\"\
  : \"amcie:UpdateOrganizationConfigurationRequest\",\n    \"UpdateOrganizationConfigurationResponse\": \"amcie:UpdateOrganizationConfigurationResponse\",\n    \"UpdateResourceProfileDetectionsRequest\": \"amcie:UpdateResourceProfileDetectionsRequest\",\n    \"UpdateResourceProfileDetectionsResponse\": \"amcie:UpdateResourceProfileDetectionsResponse\",\n    \"UpdateResourceProfileRequest\": \"amcie:UpdateResourceProfileRequest\",\n    \"UpdateResourceProfileResponse\": \"amcie:UpdateResourceProfileResponse\",\n    \"UpdateRevealConfigurationRequest\": \"amcie:UpdateRevealConfigurationRequest\",\n    \"UpdateRevealConfigurationResponse\": \"amcie:UpdateRevealConfigurationResponse\",\n    \"UpdateSensitivityInspectionTemplateRequest\": \"amcie:UpdateSensitivityInspectionTemplateRequest\",\n    \"UpdateSensitivityInspectionTemplateResponse\": \"amcie:UpdateSensitivityInspectionTemplateResponse\",\n    \"UsageByAccount\": \"amcie:UsageByAccount\",\n    \"UsageRecord\": \"amcie:UsageRecord\"\
  ,\n    \"UsageStatisticsFilter\": \"amcie:UsageStatisticsFilter\",\n    \"UsageStatisticsSortBy\": \"amcie:UsageStatisticsSortBy\",\n    \"UsageTotal\": \"amcie:UsageTotal\",\n    \"UserIdentity\": \"amcie:UserIdentity\",\n    \"UserIdentityRoot\": \"amcie:UserIdentityRoot\",\n    \"UserPausedDetails\": \"amcie:UserPausedDetails\",\n    \"WeeklySchedule\": \"amcie:WeeklySchedule\",\n    \"accessControlList\": {\n      \"@id\": \"amcie:accessControlList\"\n    },\n    \"accessKeyId\": {\n      \"@id\": \"amcie:accessKeyId\"\n    },\n    \"account\": {\n      \"@id\": \"amcie:account\"\n    },\n    \"accountId\": {\n      \"@id\": \"amcie:accountId\"\n    },\n    \"accountIds\": {\n      \"@id\": \"amcie:accountIds\"\n    },\n    \"accountLevelPermissions\": {\n      \"@id\": \"amcie:accountLevelPermissions\"\n    },\n    \"action\": {\n      \"@id\": \"amcie:action\"\n    },\n    \"actionType\": {\n      \"@id\": \"amcie:actionType\"\n    },\n    \"actor\": {\n      \"@id\": \"amcie:actor\"\
  \n    },\n    \"additionalOccurrences\": {\n      \"@id\": \"amcie:additionalOccurrences\"\n    },\n    \"adminAccountId\": {\n      \"@id\": \"amcie:adminAccountId\"\n    },\n    \"adminAccounts\": {\n      \"@id\": \"amcie:adminAccounts\"\n    },\n    \"administrator\": {\n      \"@id\": \"amcie:administrator\"\n    },\n    \"administratorAccountId\": {\n      \"@id\": \"amcie:administratorAccountId\"\n    },\n    \"allowListIds\": {\n      \"@id\": \"amcie:allowListIds\"\n    },\n    \"allowLists\": {\n      \"@id\": \"amcie:allowLists\"\n    },\n    \"allowsPublicReadAccess\": {\n      \"@id\": \"amcie:allowsPublicReadAccess\"\n    },\n    \"allowsPublicWriteAccess\": {\n      \"@id\": \"amcie:allowsPublicWriteAccess\"\n    },\n    \"allowsUnencryptedObjectUploads\": {\n      \"@id\": \"amcie:allowsUnencryptedObjectUploads\"\n    },\n    \"and\": {\n      \"@id\": \"amcie:and\"\n    },\n    \"api\": {\n      \"@id\": \"amcie:api\"\n    },\n    \"apiCallDetails\": {\n      \"@id\":\
  \ \"amcie:apiCallDetails\"\n    },\n    \"apiServiceName\": {\n      \"@id\": \"amcie:apiServiceName\"\n    },\n    \"approximateNumberOfObjectsToProcess\": {\n      \"@id\": \"amcie:approximateNumberOfObjectsToProcess\"\n    },\n    \"archived\": {\n      \"@id\": \"amcie:archived\"\n    },\n    \"arn\": {\n      \"@id\": \"amcie:arn\"\n    },\n    \"artifacts\": {\n      \"@id\": \"amcie:artifacts\"\n    },\n    \"asn\": {\n      \"@id\": \"amcie:asn\"\n    },\n    \"asnOrg\": {\n      \"@id\": \"amcie:asnOrg\"\n    },\n    \"assumedRole\": {\n      \"@id\": \"amcie:assumedRole\"\n    },\n    \"attributeName\": {\n      \"@id\": \"amcie:attributeName\"\n    },\n    \"attributes\": {\n      \"@id\": \"amcie:attributes\"\n    },\n    \"autoEnable\": {\n      \"@id\": \"amcie:autoEnable\"\n    },\n    \"automatedDiscoveryFreeTrialStartDate\": {\n      \"@id\": \"amcie:automatedDiscoveryFreeTrialStartDate\"\n    },\n    \"awsAccount\": {\n      \"@id\": \"amcie:awsAccount\"\n    },\n   \
  \ \"awsService\": {\n      \"@id\": \"amcie:awsService\"\n    },\n    \"blockPublicAccess\": {\n      \"@id\": \"amcie:blockPublicAccess\"\n    },\n    \"blockPublicAcls\": {\n      \"@id\": \"amcie:blockPublicAcls\"\n    },\n    \"blockPublicPolicy\": {\n      \"@id\": \"amcie:blockPublicPolicy\"\n    },\n    \"bucketArn\": {\n      \"@id\": \"amcie:bucketArn\"\n    },\n    \"bucketCount\": {\n      \"@id\": \"amcie:bucketCount\"\n    },\n    \"bucketCountByEffectivePermission\": {\n      \"@id\": \"amcie:bucketCountByEffectivePermission\"\n    },\n    \"bucketCountByEncryptionType\": {\n      \"@id\": \"amcie:bucketCountByEncryptionType\"\n    },\n    \"bucketCountByObjectEncryptionRequirement\": {\n      \"@id\": \"amcie:bucketCountByObjectEncryptionRequirement\"\n    },\n    \"bucketCountBySharedAccessType\": {\n      \"@id\": \"amcie:bucketCountBySharedAccessType\"\n    },\n    \"bucketCreatedAt\": {\n      \"@id\": \"amcie:bucketCreatedAt\"\n    },\n    \"bucketCriteria\": {\n  \
  \    \"@id\": \"amcie:bucketCriteria\"\n    },\n    \"bucketDefinitions\": {\n      \"@id\": \"amcie:bucketDefinitions\"\n    },\n    \"bucketLevelPermissions\": {\n      \"@id\": \"amcie:bucketLevelPermissions\"\n    },\n    \"bucketName\": {\n      \"@id\": \"amcie:bucketName\"\n    },\n    \"bucketNames\": {\n      \"@id\": \"amcie:bucketNames\"\n    },\n    \"bucketPolicy\": {\n      \"@id\": \"amcie:bucketPolicy\"\n    },\n    \"bucketStatisticsBySensitivity\": {\n      \"@id\": \"amcie:bucketStatisticsBySensitivity\"\n    },\n    \"buckets\": {\n      \"@id\": \"amcie:buckets\"\n    },\n    \"category\": {\n      \"@id\": \"amcie:category\"\n    },\n    \"cellReference\": {\n      \"@id\": \"amcie:cellReference\"\n    },\n    \"cells\": {\n      \"@id\": \"amcie:cells\"\n    },\n    \"classifiableObjectCount\": {\n      \"@id\": \"amcie:classifiableObjectCount\"\n    },\n    \"classifiableSizeInBytes\": {\n      \"@id\": \"amcie:classifiableSizeInBytes\"\n    },\n    \"classificationDetails\"\
  : {\n      \"@id\": \"amcie:classificationDetails\"\n    },\n    \"classificationError\": {\n      \"@id\": \"amcie:classificationError\"\n    },\n    \"classificationResultStatus\": {\n      \"@id\": \"amcie:classificationResultStatus\"\n    },\n    \"classificationScopeId\": {\n      \"@id\": \"amcie:classificationScopeId\"\n    },\n    \"classificationScopes\": {\n      \"@id\": \"amcie:classificationScopes\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amcie:clientToken\"\n    },\n    \"code\": {\n      \"@id\": \"amcie:code\"\n    },\n    \"column\": {\n      \"@id\": \"amcie:column\"\n    },\n    \"columnName\": {\n      \"@id\": \"amcie:columnName\"\n    },\n    \"comparator\": {\n      \"@id\": \"amcie:comparator\"\n    },\n    \"configuration\": {\n      \"@id\": \"amcie:configuration\"\n    },\n    \"count\": {\n      \"@id\": \"amcie:count\"\n    },\n    \"countsByGroup\": {\n      \"@id\": \"amcie:countsByGroup\"\n    },\n    \"createdAt\": {\n      \"@id\": \"amcie:createdAt\"\
  \n    },\n    \"creationDate\": {\n      \"@id\": \"amcie:creationDate\"\n    },\n    \"criteria\": {\n      \"@id\": \"amcie:criteria\"\n    },\n    \"criterion\": {\n      \"@id\": \"amcie:criterion\"\n    },\n    \"currency\": {\n      \"@id\": \"amcie:currency\"\n    },\n    \"customDataIdentifierId\": {\n      \"@id\": \"amcie:customDataIdentifierId\"\n    },\n    \"customDataIdentifierIds\": {\n      \"@id\": \"amcie:customDataIdentifierIds\"\n    },\n    \"customDataIdentifiers\": {\n      \"@id\": \"amcie:customDataIdentifiers\"\n    },\n    \"customerManaged\": {\n      \"@id\": \"amcie:customerManaged\"\n    },\n    \"dailySchedule\": {\n      \"@id\": \"amcie:dailySchedule\"\n    },\n    \"dayOfMonth\": {\n      \"@id\": \"amcie:dayOfMonth\"\n    },\n    \"dayOfWeek\": {\n      \"@id\": \"amcie:dayOfWeek\"\n    },\n    \"defaultServerSideEncryption\": {\n      \"@id\": \"amcie:defaultServerSideEncryption\"\n    },\n    \"deleted\": {\n      \"@id\": \"amcie:deleted\"\n    },\n\
  \    \"deniesUnencryptedObjectUploads\": {\n      \"@id\": \"amcie:deniesUnencryptedObjectUploads\"\n    },\n    \"description\": \"schema:description\",\n    \"detailedResultsLocation\": {\n      \"@id\": \"amcie:detailedResultsLocation\"\n    },\n    \"detections\": {\n      \"@id\": \"amcie:detections\"\n    },\n    \"disableEmailNotification\": {\n      \"@id\": \"amcie:disableEmailNotification\"\n    },\n    \"disabledAt\": {\n      \"@id\": \"amcie:disabledAt\"\n    },\n    \"displayName\": {\n      \"@id\": \"amcie:displayName\"\n    },\n    \"domainDetails\": {\n      \"@id\": \"amcie:domainDetails\"\n    },\n    \"domainName\": {\n      \"@id\": \"amcie:domainName\"\n    },\n    \"eTag\": {\n      \"@id\": \"amcie:eTag\"\n    },\n    \"effectivePermission\": {\n      \"@id\": \"amcie:effectivePermission\"\n    },\n    \"email\": {\n      \"@id\": \"amcie:email\"\n    },\n    \"encryptionType\": {\n      \"@id\": \"amcie:encryptionType\"\n    },\n    \"end\": {\n      \"@id\":\
  \ \"amcie:end\"\n    },\n    \"eq\": {\n      \"@id\": \"amcie:eq\"\n    },\n    \"eqExactMatch\": {\n      \"@id\": \"amcie:eqExactMatch\"\n    },\n    \"error\": {\n      \"@id\": \"amcie:error\"\n    },\n    \"errorCode\": {\n      \"@id\": \"amcie:errorCode\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"amcie:errorMessage\"\n    },\n    \"estimatedCost\": {\n      \"@id\": \"amcie:estimatedCost\"\n    },\n    \"excludes\": {\n      \"@id\": \"amcie:excludes\"\n    },\n    \"extension\": {\n      \"@id\": \"amcie:extension\"\n    },\n    \"external\": {\n      \"@id\": \"amcie:external\"\n    },\n    \"federatedUser\": {\n      \"@id\": \"amcie:federatedUser\"\n    },\n    \"fileType\": {\n      \"@id\": \"amcie:fileType\"\n    },\n    \"filterBy\": {\n      \"@id\": \"amcie:filterBy\"\n    },\n    \"filterCriteria\": {\n      \"@id\": \"amcie:filterCriteria\"\n    },\n    \"findingCriteria\": {\n      \"@id\": \"amcie:findingCriteria\"\n    },\n    \"findingIds\": {\n      \"\
  @id\": \"amcie:findingIds\"\n    },\n    \"findingPublishingFrequency\": {\n      \"@id\": \"amcie:findingPublishingFrequency\"\n    },\n    \"findingTypes\": {\n      \"@id\": \"amcie:findingTypes\"\n    },\n    \"findings\": {\n      \"@id\": \"amcie:findings\"\n    },\n    \"findingsFilterListItems\": {\n      \"@id\": \"amcie:findingsFilterListItems\"\n    },\n    \"firstEnabledAt\": {\n      \"@id\": \"amcie:firstEnabledAt\"\n    },\n    \"firstSeen\": {\n      \"@id\": \"amcie:firstSeen\"\n    },\n    \"freeTrialStartDate\": {\n      \"@id\": \"amcie:freeTrialStartDate\"\n    },\n    \"groupBy\": {\n      \"@id\": \"amcie:groupBy\"\n    },\n    \"groupKey\": {\n      \"@id\": \"amcie:groupKey\"\n    },\n    \"gt\": {\n      \"@id\": \"amcie:gt\"\n    },\n    \"gte\": {\n      \"@id\": \"amcie:gte\"\n    },\n    \"iamUser\": {\n      \"@id\": \"amcie:iamUser\"\n    },\n    \"id\": {\n      \"@id\": \"amcie:id\"\n    },\n    \"ids\": {\n      \"@id\": \"amcie:ids\"\n    },\n    \"\
  ignorePublicAcls\": {\n      \"@id\": \"amcie:ignorePublicAcls\"\n    },\n    \"ignoreWords\": {\n      \"@id\": \"amcie:ignoreWords\"\n    },\n    \"includes\": {\n      \"@id\": \"amcie:includes\"\n    },\n    \"initialRun\": {\n      \"@id\": \"amcie:initialRun\"\n    },\n    \"internal\": {\n      \"@id\": \"amcie:internal\"\n    },\n    \"invitationId\": {\n      \"@id\": \"amcie:invitationId\"\n    },\n    \"invitations\": {\n      \"@id\": \"amcie:invitations\"\n    },\n    \"invitationsCount\": {\n      \"@id\": \"amcie:invitationsCount\"\n    },\n    \"invitedAt\": {\n      \"@id\": \"amcie:invitedAt\"\n    },\n    \"invokedBy\": {\n      \"@id\": \"amcie:invokedBy\"\n    },\n    \"ipAddressDetails\": {\n      \"@id\": \"amcie:ipAddressDetails\"\n    },\n    \"ipAddressV4\": {\n      \"@id\": \"amcie:ipAddressV4\"\n    },\n    \"ipCity\": {\n      \"@id\": \"amcie:ipCity\"\n    },\n    \"ipCountry\": {\n      \"@id\": \"amcie:ipCountry\"\n    },\n    \"ipGeoLocation\": {\n   \
  \   \"@id\": \"amcie:ipGeoLocation\"\n    },\n    \"ipOwner\": {\n      \"@id\": \"amcie:ipOwner\"\n    },\n    \"isDefinedInJob\": {\n      \"@id\": \"amcie:isDefinedInJob\"\n    },\n    \"isMonitoredByJob\": {\n      \"@id\": \"amcie:isMonitoredByJob\"\n    },\n    \"isServiceLimited\": {\n      \"@id\": \"amcie:isServiceLimited\"\n    },\n    \"isp\": {\n      \"@id\": \"amcie:isp\"\n    },\n    \"items\": {\n      \"@id\": \"amcie:items\"\n    },\n    \"jobArn\": {\n      \"@id\": \"amcie:jobArn\"\n    },\n    \"jobDetails\": {\n      \"@id\": \"amcie:jobDetails\"\n    },\n    \"jobExpiresAt\": {\n      \"@id\": \"amcie:jobExpiresAt\"\n    },\n    \"jobId\": {\n      \"@id\": \"amcie:jobId\"\n    },\n    \"jobImminentExpirationHealthEventArn\": {\n      \"@id\": \"amcie:jobImminentExpirationHealthEventArn\"\n    },\n    \"jobPausedAt\": {\n      \"@id\": \"amcie:jobPausedAt\"\n    },\n    \"jobStatus\": {\n      \"@id\": \"amcie:jobStatus\"\n    },\n    \"jobType\": {\n      \"@id\"\
  : \"amcie:jobType\"\n    },\n    \"jsonPath\": {\n      \"@id\": \"amcie:jsonPath\"\n    },\n    \"key\": {\n      \"@id\": \"amcie:key\"\n    },\n    \"keyPrefix\": {\n      \"@id\": \"amcie:keyPrefix\"\n    },\n    \"keywords\": {\n      \"@id\": \"amcie:keywords\"\n    },\n    \"kmsKeyArn\": {\n      \"@id\": \"amcie:kmsKeyArn\"\n    },\n    \"kmsKeyId\": {\n      \"@id\": \"amcie:kmsKeyId\"\n    },\n    \"kmsManaged\": {\n      \"@id\": \"amcie:kmsManaged\"\n    },\n    \"kmsMasterKeyId\": {\n      \"@id\": \"amcie:kmsMasterKeyId\"\n    },\n    \"lastAutomatedDiscoveryTime\": {\n      \"@id\": \"amcie:lastAutomatedDiscoveryTime\"\n    },\n    \"lastJobId\": {\n      \"@id\": \"amcie:lastJobId\"\n    },\n    \"lastJobRunTime\": {\n      \"@id\": \"amcie:lastJobRunTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"amcie:lastModified\"\n    },\n    \"lastRunErrorStatus\": {\n      \"@id\": \"amcie:lastRunErrorStatus\"\n    },\n    \"lastRunTime\": {\n      \"@id\": \"amcie:lastRunTime\"\
  \n    },\n    \"lastSeen\": {\n      \"@id\": \"amcie:lastSeen\"\n    },\n    \"lastUpdated\": {\n      \"@id\": \"amcie:lastUpdated\"\n    },\n    \"lastUpdatedAt\": {\n      \"@id\": \"amcie:lastUpdatedAt\"\n    },\n    \"lat\": {\n      \"@id\": \"amcie:lat\"\n    },\n    \"lineRange\": {\n      \"@id\": \"amcie:lineRange\"\n    },\n    \"lineRanges\": {\n      \"@id\": \"amcie:lineRanges\"\n    },\n    \"lon\": {\n      \"@id\": \"amcie:lon\"\n    },\n    \"lt\": {\n      \"@id\": \"amcie:lt\"\n    },\n    \"lte\": {\n      \"@id\": \"amcie:lte\"\n    },\n    \"managedDataIdentifierIds\": {\n      \"@id\": \"amcie:managedDataIdentifierIds\"\n    },\n    \"managedDataIdentifierSelector\": {\n      \"@id\": \"amcie:managedDataIdentifierSelector\"\n    },\n    \"master\": {\n      \"@id\": \"amcie:master\"\n    },\n    \"masterAccount\": {\n      \"@id\": \"amcie:masterAccount\"\n    },\n    \"masterAccountId\": {\n      \"@id\": \"amcie:masterAccountId\"\n    },\n    \"matchCount\":\
  \ {\n      \"@id\": \"amcie:matchCount\"\n    },\n    \"matchingBucket\": {\n      \"@id\": \"amcie:matchingBucket\"\n    },\n    \"matchingResources\": {\n      \"@id\": \"amcie:matchingResources\"\n    },\n    \"maxAccountLimitReached\": {\n      \"@id\": \"amcie:maxAccountLimitReached\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amcie:maxResults\"\n    },\n    \"maximumMatchDistance\": {\n      \"@id\": \"amcie:maximumMatchDistance\"\n    },\n    \"members\": {\n      \"@id\": \"amcie:members\"\n    },\n    \"message\": {\n      \"@id\": \"amcie:message\"\n    },\n    \"mfaAuthenticated\": {\n      \"@id\": \"amcie:mfaAuthenticated\"\n    },\n    \"mimeType\": {\n      \"@id\": \"amcie:mimeType\"\n    },\n    \"monthlySchedule\": {\n      \"@id\": \"amcie:monthlySchedule\"\n    },\n    \"name\": \"schema:name\",\n    \"neq\": {\n      \"@id\": \"amcie\n\n# --- truncated at 32 KB (40 KB total) ---\n# Full source: https://raw.githubusercontent.com/api-evangelist/amazon-macie/refs/heads/main/json-ld/amazon-macie-context.jsonld\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-macie/refs/heads/main/json-ld/amazon-macie-context.jsonld
tags:
- Data Security
- Sensitive Data
- Privacy
- Compliance
- Machine Learning
- S3
- JSON-LD
- Linked Data
- Semantic Web
---
