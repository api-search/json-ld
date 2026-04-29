---
class_count: 92
classes:
- CreateAccessTokenResponse
- CreateDevEnvironmentResponse
- RepositoryInput
- IdeConfiguration
- CreateProjectResponse
- CreateSourceRepositoryResponse
- CreateSourceRepositoryBranchResponse
- DeleteAccessTokenResponse
- DeleteDevEnvironmentResponse
- DeleteProjectResponse
- DeleteSourceRepositoryResponse
- DeleteSpaceResponse
- GetDevEnvironmentResponse
- GetProjectResponse
- GetSourceRepositoryResponse
- GetSourceRepositoryCloneUrlsResponse
- GetSpaceResponse
- GetSubscriptionResponse
- GetUserDetailsResponse
- ListAccessTokensResponse
- ListDevEnvironmentSessionsResponse
- ListDevEnvironmentsResponse
- Filter
- ListEventLogsResponse
- ListProjectsResponse
- ProjectListFilter
- ListSourceRepositoriesResponse
- ListSourceRepositoryBranchesResponse
- ListSpacesResponse
- StartDevEnvironmentResponse
- StartDevEnvironmentSessionResponse
- ExecuteCommandSessionConfiguration
- StopDevEnvironmentResponse
- StopDevEnvironmentSessionResponse
- UpdateDevEnvironmentResponse
- UpdateProjectResponse
- UpdateSpaceResponse
- VerifySessionResponse
- AccessTokenSummary
- CreateAccessTokenRequest
- PersistentStorageConfiguration
- CreateDevEnvironmentRequest
- CreateProjectRequest
- CreateSourceRepositoryBranchRequest
- CreateSourceRepositoryRequest
- DeleteAccessTokenRequest
- DeleteDevEnvironmentRequest
- DeleteProjectRequest
- DeleteSourceRepositoryRequest
- DeleteSpaceRequest
- DevEnvironmentAccessDetails
- DevEnvironmentRepositorySummary
- DevEnvironmentSessionConfiguration
- DevEnvironmentSessionSummary
- PersistentStorage
- DevEnvironmentSummary
- EmailAddress
- EventLogEntry
- UserIdentity
- ProjectInformation
- EventPayload
- GetDevEnvironmentRequest
- GetProjectRequest
- GetSourceRepositoryCloneUrlsRequest
- GetSourceRepositoryRequest
- GetSpaceRequest
- GetSubscriptionRequest
- GetUserDetailsRequest
- Ide
- ListAccessTokensRequest
- ListDevEnvironmentSessionsRequest
- ListDevEnvironmentsRequest
- ListEventLogsRequest
- ListProjectsRequest
- ListSourceRepositoriesItem
- ListSourceRepositoriesRequest
- ListSourceRepositoryBranchesItem
- ListSourceRepositoryBranchesRequest
- ListSpacesRequest
- ProjectSummary
- SpaceSummary
- StartDevEnvironmentRequest
- StartDevEnvironmentSessionRequest
- StopDevEnvironmentRequest
- StopDevEnvironmentSessionRequest
- UpdateDevEnvironmentRequest
- UpdateProjectRequest
- UpdateSpaceRequest
- name
- description
- version
- email
context_file: json-ld/amazon-codecatalyst-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codecatalyst/refs/heads/main/json-ld/amazon-codecatalyst-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codecatalyst from Amazon CodeCatalyst.
layout: jsonld
name: Amazon Codecatalyst Context
namespaces:
- prefix: amazon-code-catalyst
  uri: https://amazon-code-catalyst.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: secret
  type: string
- container: ''
  name: expiresTime
  type: string
- container: ''
  name: accessTokenId
  type: string
- container: ''
  name: spaceName
  type: string
- container: ''
  name: projectName
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: repositoryName
  type: string
- container: ''
  name: branchName
  type: string
- container: ''
  name: runtime
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: ref
  type: string
- container: ''
  name: lastUpdatedTime
  type: string
- container: ''
  name: headCommitId
  type: string
- container: ''
  name: creatorId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: statusReason
  type: string
- container: ''
  name: repositories
  type: string
- container: ''
  name: alias
  type: string
- container: ''
  name: ides
  type: string
- container: ''
  name: instanceType
  type: string
- container: ''
  name: inactivityTimeoutMinutes
  type: string
- container: ''
  name: persistentStorage
  type: string
- container: ''
  name: createdTime
  type: string
- container: ''
  name: https
  type: string
- container: ''
  name: regionName
  type: string
- container: ''
  name: subscriptionType
  type: string
- container: ''
  name: awsAccountName
  type: string
- container: ''
  name: userId
  type: string
- container: ''
  name: userName
  type: string
- container: ''
  name: primaryEmail
  type: string
- container: ''
  name: items
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: values
  type: string
- container: ''
  name: comparisonOperator
  type: string
- container: ''
  name: accessDetails
  type: string
- container: ''
  name: sessionId
  type: string
- container: ''
  name: command
  type: string
- container: ''
  name: arguments
  type: string
- container: ''
  name: clientToken
  type: string
- container: ''
  name: identity
  type: string
- container: ''
  name: sizeInGiB
  type: string
- container: ''
  name: streamUrl
  type: string
- container: ''
  name: tokenValue
  type: string
- container: ''
  name: sessionType
  type: string
- container: ''
  name: executeCommandSessionConfiguration
  type: string
- container: ''
  name: devEnvironmentId
  type: string
- container: ''
  name: startedTime
  type: string
- container: ''
  name: verified
  type: string
- container: ''
  name: eventName
  type: string
- container: ''
  name: eventType
  type: string
- container: ''
  name: eventCategory
  type: string
- container: ''
  name: eventSource
  type: string
- container: ''
  name: eventTime
  type: string
- container: ''
  name: operationType
  type: string
- container: ''
  name: userIdentity
  type: string
- container: ''
  name: projectInformation
  type: string
- container: ''
  name: requestId
  type: string
- container: ''
  name: requestPayload
  type: string
- container: ''
  name: responsePayload
  type: string
- container: ''
  name: errorCode
  type: string
- container: ''
  name: sourceIpAddress
  type: string
- container: ''
  name: userAgent
  type: string
- container: ''
  name: userType
  type: string
- container: ''
  name: principalId
  type: string
- container: ''
  name: awsAccountId
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: contentType
  type: string
- container: ''
  name: data
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: filters
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: endTime
  type: string
- container: ''
  name: sessionConfiguration
  type: string
property_count: 74
provider_name: Amazon CodeCatalyst
provider_slug: amazon-codecatalyst
slug: amazon-codecatalyst-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-catalyst\": \"https://amazon-code-catalyst.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateAccessTokenResponse\": \"amazon-code-catalyst:CreateAccessTokenResponse\",\n    \"CreateDevEnvironmentResponse\": \"amazon-code-catalyst:CreateDevEnvironmentResponse\",\n    \"RepositoryInput\": \"amazon-code-catalyst:RepositoryInput\",\n    \"IdeConfiguration\": \"amazon-code-catalyst:IdeConfiguration\",\n    \"CreateProjectResponse\": \"amazon-code-catalyst:CreateProjectResponse\",\n    \"CreateSourceRepositoryResponse\": \"amazon-code-catalyst:CreateSourceRepositoryResponse\",\n    \"CreateSourceRepositoryBranchResponse\": \"amazon-code-catalyst:CreateSourceRepositoryBranchResponse\",\n    \"DeleteAccessTokenResponse\": \"amazon-code-catalyst:DeleteAccessTokenResponse\",\n    \"DeleteDevEnvironmentResponse\"\
  : \"amazon-code-catalyst:DeleteDevEnvironmentResponse\",\n    \"DeleteProjectResponse\": \"amazon-code-catalyst:DeleteProjectResponse\",\n    \"DeleteSourceRepositoryResponse\": \"amazon-code-catalyst:DeleteSourceRepositoryResponse\",\n    \"DeleteSpaceResponse\": \"amazon-code-catalyst:DeleteSpaceResponse\",\n    \"GetDevEnvironmentResponse\": \"amazon-code-catalyst:GetDevEnvironmentResponse\",\n    \"GetProjectResponse\": \"amazon-code-catalyst:GetProjectResponse\",\n    \"GetSourceRepositoryResponse\": \"amazon-code-catalyst:GetSourceRepositoryResponse\",\n    \"GetSourceRepositoryCloneUrlsResponse\": \"amazon-code-catalyst:GetSourceRepositoryCloneUrlsResponse\",\n    \"GetSpaceResponse\": \"amazon-code-catalyst:GetSpaceResponse\",\n    \"GetSubscriptionResponse\": \"amazon-code-catalyst:GetSubscriptionResponse\",\n    \"GetUserDetailsResponse\": \"amazon-code-catalyst:GetUserDetailsResponse\",\n    \"ListAccessTokensResponse\": \"amazon-code-catalyst:ListAccessTokensResponse\",\n \
  \   \"ListDevEnvironmentSessionsResponse\": \"amazon-code-catalyst:ListDevEnvironmentSessionsResponse\",\n    \"ListDevEnvironmentsResponse\": \"amazon-code-catalyst:ListDevEnvironmentsResponse\",\n    \"Filter\": \"amazon-code-catalyst:Filter\",\n    \"ListEventLogsResponse\": \"amazon-code-catalyst:ListEventLogsResponse\",\n    \"ListProjectsResponse\": \"amazon-code-catalyst:ListProjectsResponse\",\n    \"ProjectListFilter\": \"amazon-code-catalyst:ProjectListFilter\",\n    \"ListSourceRepositoriesResponse\": \"amazon-code-catalyst:ListSourceRepositoriesResponse\",\n    \"ListSourceRepositoryBranchesResponse\": \"amazon-code-catalyst:ListSourceRepositoryBranchesResponse\",\n    \"ListSpacesResponse\": \"amazon-code-catalyst:ListSpacesResponse\",\n    \"StartDevEnvironmentResponse\": \"amazon-code-catalyst:StartDevEnvironmentResponse\",\n    \"StartDevEnvironmentSessionResponse\": \"amazon-code-catalyst:StartDevEnvironmentSessionResponse\",\n    \"ExecuteCommandSessionConfiguration\"\
  : \"amazon-code-catalyst:ExecuteCommandSessionConfiguration\",\n    \"StopDevEnvironmentResponse\": \"amazon-code-catalyst:StopDevEnvironmentResponse\",\n    \"StopDevEnvironmentSessionResponse\": \"amazon-code-catalyst:StopDevEnvironmentSessionResponse\",\n    \"UpdateDevEnvironmentResponse\": \"amazon-code-catalyst:UpdateDevEnvironmentResponse\",\n    \"UpdateProjectResponse\": \"amazon-code-catalyst:UpdateProjectResponse\",\n    \"UpdateSpaceResponse\": \"amazon-code-catalyst:UpdateSpaceResponse\",\n    \"VerifySessionResponse\": \"amazon-code-catalyst:VerifySessionResponse\",\n    \"AccessTokenSummary\": \"amazon-code-catalyst:AccessTokenSummary\",\n    \"CreateAccessTokenRequest\": \"amazon-code-catalyst:CreateAccessTokenRequest\",\n    \"PersistentStorageConfiguration\": \"amazon-code-catalyst:PersistentStorageConfiguration\",\n    \"CreateDevEnvironmentRequest\": \"amazon-code-catalyst:CreateDevEnvironmentRequest\",\n    \"CreateProjectRequest\": \"amazon-code-catalyst:CreateProjectRequest\"\
  ,\n    \"CreateSourceRepositoryBranchRequest\": \"amazon-code-catalyst:CreateSourceRepositoryBranchRequest\",\n    \"CreateSourceRepositoryRequest\": \"amazon-code-catalyst:CreateSourceRepositoryRequest\",\n    \"DeleteAccessTokenRequest\": \"amazon-code-catalyst:DeleteAccessTokenRequest\",\n    \"DeleteDevEnvironmentRequest\": \"amazon-code-catalyst:DeleteDevEnvironmentRequest\",\n    \"DeleteProjectRequest\": \"amazon-code-catalyst:DeleteProjectRequest\",\n    \"DeleteSourceRepositoryRequest\": \"amazon-code-catalyst:DeleteSourceRepositoryRequest\",\n    \"DeleteSpaceRequest\": \"amazon-code-catalyst:DeleteSpaceRequest\",\n    \"DevEnvironmentAccessDetails\": \"amazon-code-catalyst:DevEnvironmentAccessDetails\",\n    \"DevEnvironmentRepositorySummary\": \"amazon-code-catalyst:DevEnvironmentRepositorySummary\",\n    \"DevEnvironmentSessionConfiguration\": \"amazon-code-catalyst:DevEnvironmentSessionConfiguration\",\n    \"DevEnvironmentSessionSummary\": \"amazon-code-catalyst:DevEnvironmentSessionSummary\"\
  ,\n    \"PersistentStorage\": \"amazon-code-catalyst:PersistentStorage\",\n    \"DevEnvironmentSummary\": \"amazon-code-catalyst:DevEnvironmentSummary\",\n    \"EmailAddress\": \"amazon-code-catalyst:EmailAddress\",\n    \"EventLogEntry\": \"amazon-code-catalyst:EventLogEntry\",\n    \"UserIdentity\": \"amazon-code-catalyst:UserIdentity\",\n    \"ProjectInformation\": \"amazon-code-catalyst:ProjectInformation\",\n    \"EventPayload\": \"amazon-code-catalyst:EventPayload\",\n    \"GetDevEnvironmentRequest\": \"amazon-code-catalyst:GetDevEnvironmentRequest\",\n    \"GetProjectRequest\": \"amazon-code-catalyst:GetProjectRequest\",\n    \"GetSourceRepositoryCloneUrlsRequest\": \"amazon-code-catalyst:GetSourceRepositoryCloneUrlsRequest\",\n    \"GetSourceRepositoryRequest\": \"amazon-code-catalyst:GetSourceRepositoryRequest\",\n    \"GetSpaceRequest\": \"amazon-code-catalyst:GetSpaceRequest\",\n    \"GetSubscriptionRequest\": \"amazon-code-catalyst:GetSubscriptionRequest\",\n    \"GetUserDetailsRequest\"\
  : \"amazon-code-catalyst:GetUserDetailsRequest\",\n    \"Ide\": \"amazon-code-catalyst:Ide\",\n    \"ListAccessTokensRequest\": \"amazon-code-catalyst:ListAccessTokensRequest\",\n    \"ListDevEnvironmentSessionsRequest\": \"amazon-code-catalyst:ListDevEnvironmentSessionsRequest\",\n    \"ListDevEnvironmentsRequest\": \"amazon-code-catalyst:ListDevEnvironmentsRequest\",\n    \"ListEventLogsRequest\": \"amazon-code-catalyst:ListEventLogsRequest\",\n    \"ListProjectsRequest\": \"amazon-code-catalyst:ListProjectsRequest\",\n    \"ListSourceRepositoriesItem\": \"amazon-code-catalyst:ListSourceRepositoriesItem\",\n    \"ListSourceRepositoriesRequest\": \"amazon-code-catalyst:ListSourceRepositoriesRequest\",\n    \"ListSourceRepositoryBranchesItem\": \"amazon-code-catalyst:ListSourceRepositoryBranchesItem\",\n    \"ListSourceRepositoryBranchesRequest\": \"amazon-code-catalyst:ListSourceRepositoryBranchesRequest\",\n    \"ListSpacesRequest\": \"amazon-code-catalyst:ListSpacesRequest\",\n    \"\
  ProjectSummary\": \"amazon-code-catalyst:ProjectSummary\",\n    \"SpaceSummary\": \"amazon-code-catalyst:SpaceSummary\",\n    \"StartDevEnvironmentRequest\": \"amazon-code-catalyst:StartDevEnvironmentRequest\",\n    \"StartDevEnvironmentSessionRequest\": \"amazon-code-catalyst:StartDevEnvironmentSessionRequest\",\n    \"StopDevEnvironmentRequest\": \"amazon-code-catalyst:StopDevEnvironmentRequest\",\n    \"StopDevEnvironmentSessionRequest\": \"amazon-code-catalyst:StopDevEnvironmentSessionRequest\",\n    \"UpdateDevEnvironmentRequest\": \"amazon-code-catalyst:UpdateDevEnvironmentRequest\",\n    \"UpdateProjectRequest\": \"amazon-code-catalyst:UpdateProjectRequest\",\n    \"UpdateSpaceRequest\": \"amazon-code-catalyst:UpdateSpaceRequest\",\n    \"secret\": {\n      \"@id\": \"amazon-code-catalyst:secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"expiresTime\": {\n      \"@id\": \"amazon-code-catalyst:expiresTime\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"accessTokenId\": {\n      \"@id\": \"amazon-code-catalyst:accessTokenId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"spaceName\": {\n      \"@id\": \"amazon-code-catalyst:spaceName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectName\": {\n      \"@id\": \"amazon-code-catalyst:projectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amazon-code-catalyst:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositoryName\": {\n      \"@id\": \"amazon-code-catalyst:repositoryName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"branchName\": {\n      \"@id\": \"amazon-code-catalyst:branchName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"runtime\": {\n      \"@id\": \"amazon-code-catalyst:runtime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"amazon-code-catalyst:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"ref\": {\n\
  \      \"@id\": \"amazon-code-catalyst:ref\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastUpdatedTime\": {\n      \"@id\": \"amazon-code-catalyst:lastUpdatedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"headCommitId\": {\n      \"@id\": \"amazon-code-catalyst:headCommitId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"creatorId\": {\n      \"@id\": \"amazon-code-catalyst:creatorId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amazon-code-catalyst:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"statusReason\": {\n      \"@id\": \"amazon-code-catalyst:statusReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repositories\": {\n      \"@id\": \"amazon-code-catalyst:repositories\",\n      \"@type\": \"xsd:string\"\n    },\n    \"alias\": {\n      \"@id\": \"amazon-code-catalyst:alias\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ides\": {\n      \"@id\": \"amazon-code-catalyst:ides\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"instanceType\": {\n      \"@id\": \"amazon-code-catalyst:instanceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"inactivityTimeoutMinutes\": {\n      \"@id\": \"amazon-code-catalyst:inactivityTimeoutMinutes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"persistentStorage\": {\n      \"@id\": \"amazon-code-catalyst:persistentStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTime\": {\n      \"@id\": \"amazon-code-catalyst:createdTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"https\": {\n      \"@id\": \"amazon-code-catalyst:https\",\n      \"@type\": \"xsd:string\"\n    },\n    \"regionName\": {\n      \"@id\": \"amazon-code-catalyst:regionName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"subscriptionType\": {\n      \"@id\": \"amazon-code-catalyst:subscriptionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountName\": {\n      \"@id\": \"amazon-code-catalyst:awsAccountName\",\n      \"@type\": \"xsd:string\"\n   \
  \ },\n    \"userId\": {\n      \"@id\": \"amazon-code-catalyst:userId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userName\": {\n      \"@id\": \"amazon-code-catalyst:userName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"primaryEmail\": {\n      \"@id\": \"amazon-code-catalyst:primaryEmail\",\n      \"@type\": \"xsd:string\"\n    },\n    \"version\": \"schema:version\",\n    \"items\": {\n      \"@id\": \"amazon-code-catalyst:items\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-catalyst:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amazon-code-catalyst:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"values\": {\n      \"@id\": \"amazon-code-catalyst:values\",\n      \"@type\": \"xsd:string\"\n    },\n    \"comparisonOperator\": {\n      \"@id\": \"amazon-code-catalyst:comparisonOperator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accessDetails\": {\n      \"@id\": \"amazon-code-catalyst:accessDetails\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionId\": {\n      \"@id\": \"amazon-code-catalyst:sessionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"amazon-code-catalyst:command\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arguments\": {\n      \"@id\": \"amazon-code-catalyst:arguments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientToken\": {\n      \"@id\": \"amazon-code-catalyst:clientToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identity\": {\n      \"@id\": \"amazon-code-catalyst:identity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sizeInGiB\": {\n      \"@id\": \"amazon-code-catalyst:sizeInGiB\",\n      \"@type\": \"xsd:string\"\n    },\n    \"streamUrl\": {\n      \"@id\": \"amazon-code-catalyst:streamUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tokenValue\": {\n      \"@id\": \"amazon-code-catalyst:tokenValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionType\": {\n      \"@id\"\
  : \"amazon-code-catalyst:sessionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"executeCommandSessionConfiguration\": {\n      \"@id\": \"amazon-code-catalyst:executeCommandSessionConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"devEnvironmentId\": {\n      \"@id\": \"amazon-code-catalyst:devEnvironmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startedTime\": {\n      \"@id\": \"amazon-code-catalyst:startedTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"verified\": {\n      \"@id\": \"amazon-code-catalyst:verified\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventName\": {\n      \"@id\": \"amazon-code-catalyst:eventName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventType\": {\n      \"@id\": \"amazon-code-catalyst:eventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventCategory\": {\n      \"@id\": \"amazon-code-catalyst:eventCategory\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  eventSource\": {\n      \"@id\": \"amazon-code-catalyst:eventSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eventTime\": {\n      \"@id\": \"amazon-code-catalyst:eventTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"operationType\": {\n      \"@id\": \"amazon-code-catalyst:operationType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userIdentity\": {\n      \"@id\": \"amazon-code-catalyst:userIdentity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectInformation\": {\n      \"@id\": \"amazon-code-catalyst:projectInformation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestId\": {\n      \"@id\": \"amazon-code-catalyst:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"requestPayload\": {\n      \"@id\": \"amazon-code-catalyst:requestPayload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"responsePayload\": {\n      \"@id\": \"amazon-code-catalyst:responsePayload\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorCode\": {\n     \
  \ \"@id\": \"amazon-code-catalyst:errorCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceIpAddress\": {\n      \"@id\": \"amazon-code-catalyst:sourceIpAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAgent\": {\n      \"@id\": \"amazon-code-catalyst:userAgent\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userType\": {\n      \"@id\": \"amazon-code-catalyst:userType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\": {\n      \"@id\": \"amazon-code-catalyst:principalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"awsAccountId\": {\n      \"@id\": \"amazon-code-catalyst:awsAccountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\": \"amazon-code-catalyst:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"contentType\": {\n      \"@id\": \"amazon-code-catalyst:contentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"data\": {\n      \"@id\": \"amazon-code-catalyst:data\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"amazon-code-catalyst:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filters\": {\n      \"@id\": \"amazon-code-catalyst:filters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amazon-code-catalyst:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endTime\": {\n      \"@id\": \"amazon-code-catalyst:endTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sessionConfiguration\": {\n      \"@id\": \"amazon-code-catalyst:sessionConfiguration\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codecatalyst/refs/heads/main/json-ld/amazon-codecatalyst-context.jsonld
tags:
- Amazon
- AWS
- Developer Tools
- CI/CD
- Collaboration
- DevOps
- Source Control
- JSON-LD
- Linked Data
- Semantic Web
---
