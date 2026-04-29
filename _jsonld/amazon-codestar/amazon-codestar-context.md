---
api_specs:
- filename: amazon-codestar-openapi.yml
  format: yaml
  label: AWS CodeStar API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/openapi/amazon-codestar-openapi.yml
class_count: 53
classes:
- S3Location
- DeleteProjectResult
- ListProjectsRequest
- ListResourcesResult
- Toolchain
- CreateUserProfileResult
- GitHubCodeDestination
- DescribeUserProfileRequest
- TagProjectResult
- CreateProjectResult
- AssociateTeamMemberRequest
- UpdateTeamMemberResult
- Resource
- DeleteProjectRequest
- DeleteUserProfileResult
- CodeDestination
- DescribeUserProfileResult
- TagProjectRequest
- DisassociateTeamMemberRequest
- UserProfileSummary
- DeleteUserProfileRequest
- DisassociateTeamMemberResult
- UpdateUserProfileRequest
- DescribeProjectRequest
- ListTeamMembersRequest
- ListProjectsResult
- UpdateTeamMemberRequest
- CreateUserProfileRequest
- TeamMember
- ProjectStatus
- ListResourcesRequest
- UntagProjectRequest
- ListUserProfilesRequest
- ToolchainSource
- CreateProjectRequest
- UntagProjectResult
- AssociateTeamMemberResult
- ListTagsForProjectRequest
- Code
- TemplateParameterMap
- ProjectSummary
- ListTagsForProjectResult
- UpdateProjectResult
- ListUserProfilesResult
- Tags
- UpdateProjectRequest
- CodeSource
- ListTeamMembersResult
- DescribeProjectResult
- CodeCommitCodeDestination
- UpdateUserProfileResult
- name
- description
context_file: json-ld/amazon-codestar-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/json-ld/amazon-codestar-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codestar from Amazon CodeStar.
layout: jsonld
name: Amazon Codestar Context
namespaces:
- prefix: aws
  uri: https://aws.amazon.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: bucketName
  type: string
- container: ''
  name: bucketKey
  type: string
- container: ''
  name: stackId
  type: string
- container: ''
  name: projectArn
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: maxResults
  type: string
- container: ''
  name: resources
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: roleArn
  type: string
- container: ''
  name: stackParameters
  type: string
- container: ''
  name: userArn
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: emailAddress
  type: string
- container: ''
  name: sshPublicKey
  type: string
- container: ''
  name: createdTimestamp
  type: string
- container: ''
  name: lastModifiedTimestamp
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: owner
  type: string
- container: ''
  name: privateRepository
  type: string
- container: ''
  name: issuesEnabled
  type: string
- container: ''
  name: token
  type: string
- container: ''
  name: tags
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: clientRequestToken
  type: string
- container: ''
  name: projectTemplateId
  type: string
- container: ''
  name: projectId
  type: string
- container: ''
  name: projectRole
  type: string
- container: ''
  name: remoteAccessAllowed
  type: string
- container: ''
  name: deleteStack
  type: string
- container: ''
  name: codeCommit
  type: string
- container: ''
  name: gitHub
  type: string
- container: ''
  name: projects
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: s3
  type: string
- container: ''
  name: sourceCode
  type: string
- container: ''
  name: toolchain
  type: string
- container: ''
  name: destination
  type: string
- container: ''
  name: userProfiles
  type: string
- container: ''
  name: teamMembers
  type: string
- container: ''
  name: createdTimeStamp
  type: string
- container: ''
  name: status
  type: string
property_count: 43
provider_name: Amazon CodeStar
provider_slug: amazon-codestar
slug: amazon-codestar-context
source_filename: amazon-codestar-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aws\": \"https://aws.amazon.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"S3Location\": \"aws:S3Location\",\n    \"DeleteProjectResult\": \"aws:DeleteProjectResult\",\n    \"ListProjectsRequest\": \"aws:ListProjectsRequest\",\n    \"ListResourcesResult\": \"aws:ListResourcesResult\",\n    \"Toolchain\": \"aws:Toolchain\",\n    \"CreateUserProfileResult\": \"aws:CreateUserProfileResult\",\n    \"GitHubCodeDestination\": \"aws:GitHubCodeDestination\",\n    \"DescribeUserProfileRequest\": \"aws:DescribeUserProfileRequest\",\n    \"TagProjectResult\": \"aws:TagProjectResult\",\n    \"CreateProjectResult\": \"aws:CreateProjectResult\",\n    \"AssociateTeamMemberRequest\": \"aws:AssociateTeamMemberRequest\",\n    \"UpdateTeamMemberResult\": \"aws:UpdateTeamMemberResult\",\n    \"Resource\": \"aws:Resource\",\n\
  \    \"DeleteProjectRequest\": \"aws:DeleteProjectRequest\",\n    \"DeleteUserProfileResult\": \"aws:DeleteUserProfileResult\",\n    \"CodeDestination\": \"aws:CodeDestination\",\n    \"DescribeUserProfileResult\": \"aws:DescribeUserProfileResult\",\n    \"TagProjectRequest\": \"aws:TagProjectRequest\",\n    \"DisassociateTeamMemberRequest\": \"aws:DisassociateTeamMemberRequest\",\n    \"UserProfileSummary\": \"aws:UserProfileSummary\",\n    \"DeleteUserProfileRequest\": \"aws:DeleteUserProfileRequest\",\n    \"DisassociateTeamMemberResult\": \"aws:DisassociateTeamMemberResult\",\n    \"UpdateUserProfileRequest\": \"aws:UpdateUserProfileRequest\",\n    \"DescribeProjectRequest\": \"aws:DescribeProjectRequest\",\n    \"ListTeamMembersRequest\": \"aws:ListTeamMembersRequest\",\n    \"ListProjectsResult\": \"aws:ListProjectsResult\",\n    \"UpdateTeamMemberRequest\": \"aws:UpdateTeamMemberRequest\",\n    \"CreateUserProfileRequest\": \"aws:CreateUserProfileRequest\",\n    \"TeamMember\":\
  \ \"aws:TeamMember\",\n    \"ProjectStatus\": \"aws:ProjectStatus\",\n    \"ListResourcesRequest\": \"aws:ListResourcesRequest\",\n    \"UntagProjectRequest\": \"aws:UntagProjectRequest\",\n    \"ListUserProfilesRequest\": \"aws:ListUserProfilesRequest\",\n    \"ToolchainSource\": \"aws:ToolchainSource\",\n    \"CreateProjectRequest\": \"aws:CreateProjectRequest\",\n    \"UntagProjectResult\": \"aws:UntagProjectResult\",\n    \"AssociateTeamMemberResult\": \"aws:AssociateTeamMemberResult\",\n    \"ListTagsForProjectRequest\": \"aws:ListTagsForProjectRequest\",\n    \"Code\": \"aws:Code\",\n    \"TemplateParameterMap\": \"aws:TemplateParameterMap\",\n    \"ProjectSummary\": \"aws:ProjectSummary\",\n    \"ListTagsForProjectResult\": \"aws:ListTagsForProjectResult\",\n    \"UpdateProjectResult\": \"aws:UpdateProjectResult\",\n    \"ListUserProfilesResult\": \"aws:ListUserProfilesResult\",\n    \"Tags\": \"aws:Tags\",\n    \"UpdateProjectRequest\": \"aws:UpdateProjectRequest\",\n    \"CodeSource\"\
  : \"aws:CodeSource\",\n    \"ListTeamMembersResult\": \"aws:ListTeamMembersResult\",\n    \"DescribeProjectResult\": \"aws:DescribeProjectResult\",\n    \"CodeCommitCodeDestination\": \"aws:CodeCommitCodeDestination\",\n    \"UpdateUserProfileResult\": \"aws:UpdateUserProfileResult\",\n    \"bucketName\": {\n      \"@id\": \"aws:bucketName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bucketKey\": {\n      \"@id\": \"aws:bucketKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stackId\": {\n      \"@id\": \"aws:stackId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectArn\": {\n      \"@id\": \"aws:projectArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"aws:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxResults\": {\n      \"@id\": \"aws:maxResults\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\": {\n      \"@id\": \"aws:resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n     \
  \ \"@id\": \"aws:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"roleArn\": {\n      \"@id\": \"aws:roleArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stackParameters\": {\n      \"@id\": \"aws:stackParameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userArn\": {\n      \"@id\": \"aws:userArn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n      \"@id\": \"aws:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"emailAddress\": {\n      \"@id\": \"aws:emailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sshPublicKey\": {\n      \"@id\": \"aws:sshPublicKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTimestamp\": {\n      \"@id\": \"aws:createdTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastModifiedTimestamp\": {\n      \"@id\": \"aws:lastModifiedTimestamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"type\"\
  : {\n      \"@id\": \"aws:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"owner\": {\n      \"@id\": \"aws:owner\",\n      \"@type\": \"xsd:string\"\n    },\n    \"privateRepository\": {\n      \"@id\": \"aws:privateRepository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issuesEnabled\": {\n      \"@id\": \"aws:issuesEnabled\",\n      \"@type\": \"xsd:string\"\n    },\n    \"token\": {\n      \"@id\": \"aws:token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tags\": {\n      \"@id\": \"aws:tags\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"aws:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"aws:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"clientRequestToken\": {\n      \"@id\": \"aws:clientRequestToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectTemplateId\": {\n      \"@id\": \"aws:projectTemplateId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectId\": {\n      \"@id\"\
  : \"aws:projectId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projectRole\": {\n      \"@id\": \"aws:projectRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remoteAccessAllowed\": {\n      \"@id\": \"aws:remoteAccessAllowed\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deleteStack\": {\n      \"@id\": \"aws:deleteStack\",\n      \"@type\": \"xsd:string\"\n    },\n    \"codeCommit\": {\n      \"@id\": \"aws:codeCommit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitHub\": {\n      \"@id\": \"aws:gitHub\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projects\": {\n      \"@id\": \"aws:projects\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"aws:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"aws:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3\": {\n      \"@id\": \"aws:s3\",\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceCode\": {\n      \"@id\": \"aws:sourceCode\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"toolchain\": {\n      \"@id\": \"aws:toolchain\",\n      \"@type\": \"xsd:string\"\n    },\n    \"destination\": {\n      \"@id\": \"aws:destination\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userProfiles\": {\n      \"@id\": \"aws:userProfiles\",\n      \"@type\": \"xsd:string\"\n    },\n    \"teamMembers\": {\n      \"@id\": \"aws:teamMembers\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdTimeStamp\": {\n      \"@id\": \"aws:createdTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"aws:status\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codestar/refs/heads/main/json-ld/amazon-codestar-context.jsonld
tags:
- AWS
- Developer Tools
- DevOps
- Project Management
- Team Collaboration
- JSON-LD
- Linked Data
- Semantic Web
---
