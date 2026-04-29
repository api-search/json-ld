---
api_specs:
- filename: amazon-codedeploy-openapi-original.yaml
  format: yaml
  label: Amazon CodeDeploy API
  slug: amazon-codedeploy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/openapi/amazon-codedeploy-openapi-original.yaml
class_count: 16
classes:
- CreateApplicationRequest
- CreateApplicationResponse
- ListApplicationsResponse
- GetApplicationResponse
- CreateDeploymentRequest
- CreateDeploymentResponse
- ListDeploymentsResponse
- GetDeploymentResponse
- InvalidApplicationNameException
- ApplicationAlreadyExistsException
- ApplicationDoesNotExistException
- InvalidDeploymentGroupNameException
- InvalidDeploymentIdException
- DeploymentDoesNotExistException
- InvalidNextTokenException
- description
context_file: json-ld/amazon-codedeploy-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/json-ld/amazon-codedeploy-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codedeploy from Amazon CodeDeploy.
layout: jsonld
name: Amazon Codedeploy Context
namespaces:
- prefix: amazon-code-deploy
  uri: https://amazon-code-deploy.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: applicationName
  type: string
- container: ''
  name: computePlatform
  type: string
- container: ''
  name: applicationId
  type: string
- container: set
  name: applications
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: application
  type: string
- container: ''
  name: createTime
  type: dateTime
- container: ''
  name: linkedToGitHub
  type: boolean
- container: ''
  name: deploymentGroupName
  type: string
- container: ''
  name: revision
  type: string
- container: ''
  name: revisionType
  type: string
- container: ''
  name: s3Location
  type: string
- container: ''
  name: bucket
  type: string
- container: ''
  name: key
  type: string
- container: ''
  name: bundleType
  type: string
- container: ''
  name: gitHubLocation
  type: string
- container: ''
  name: repository
  type: string
- container: ''
  name: commitId
  type: string
- container: ''
  name: autoRollbackConfiguration
  type: string
- container: ''
  name: enabled
  type: boolean
- container: set
  name: events
  type: string
- container: ''
  name: deploymentId
  type: string
- container: set
  name: deployments
  type: string
- container: ''
  name: deploymentInfo
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: completeTime
  type: dateTime
- container: ''
  name: creator
  type: string
- container: ''
  name: message
  type: string
property_count: 29
provider_name: Amazon CodeDeploy
provider_slug: amazon-codedeploy
slug: amazon-codedeploy-context
source_filename: amazon-codedeploy-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-deploy\": \"https://amazon-code-deploy.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateApplicationRequest\": \"amazon-code-deploy:CreateApplicationRequest\",\n    \"CreateApplicationResponse\": \"amazon-code-deploy:CreateApplicationResponse\",\n    \"ListApplicationsResponse\": \"amazon-code-deploy:ListApplicationsResponse\",\n    \"GetApplicationResponse\": \"amazon-code-deploy:GetApplicationResponse\",\n    \"CreateDeploymentRequest\": \"amazon-code-deploy:CreateDeploymentRequest\",\n    \"CreateDeploymentResponse\": \"amazon-code-deploy:CreateDeploymentResponse\",\n    \"ListDeploymentsResponse\": \"amazon-code-deploy:ListDeploymentsResponse\",\n    \"GetDeploymentResponse\": \"amazon-code-deploy:GetDeploymentResponse\",\n    \"InvalidApplicationNameException\": \"amazon-code-deploy:InvalidApplicationNameException\"\
  ,\n    \"ApplicationAlreadyExistsException\": \"amazon-code-deploy:ApplicationAlreadyExistsException\",\n    \"ApplicationDoesNotExistException\": \"amazon-code-deploy:ApplicationDoesNotExistException\",\n    \"InvalidDeploymentGroupNameException\": \"amazon-code-deploy:InvalidDeploymentGroupNameException\",\n    \"InvalidDeploymentIdException\": \"amazon-code-deploy:InvalidDeploymentIdException\",\n    \"DeploymentDoesNotExistException\": \"amazon-code-deploy:DeploymentDoesNotExistException\",\n    \"InvalidNextTokenException\": \"amazon-code-deploy:InvalidNextTokenException\",\n    \"applicationName\": {\n      \"@id\": \"amazon-code-deploy:applicationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"computePlatform\": {\n      \"@id\": \"amazon-code-deploy:computePlatform\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applicationId\": {\n      \"@id\": \"amazon-code-deploy:applicationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"applications\": {\n      \"@id\": \"\
  amazon-code-deploy:applications\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-deploy:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"application\": {\n      \"@id\": \"amazon-code-deploy:application\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createTime\": {\n      \"@id\": \"amazon-code-deploy:createTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"linkedToGitHub\": {\n      \"@id\": \"amazon-code-deploy:linkedToGitHub\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"deploymentGroupName\": {\n      \"@id\": \"amazon-code-deploy:deploymentGroupName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revision\": {\n      \"@id\": \"amazon-code-deploy:revision\",\n      \"@type\": \"xsd:string\"\n    },\n    \"revisionType\": {\n      \"@id\": \"amazon-code-deploy:revisionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"s3Location\": {\n      \"@id\": \"amazon-code-deploy:s3Location\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"bucket\": {\n      \"@id\": \"amazon-code-deploy:bucket\",\n      \"@type\": \"xsd:string\"\n    },\n    \"key\": {\n      \"@id\": \"amazon-code-deploy:key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bundleType\": {\n      \"@id\": \"amazon-code-deploy:bundleType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"gitHubLocation\": {\n      \"@id\": \"amazon-code-deploy:gitHubLocation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"repository\": {\n      \"@id\": \"amazon-code-deploy:repository\",\n      \"@type\": \"xsd:string\"\n    },\n    \"commitId\": {\n      \"@id\": \"amazon-code-deploy:commitId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"autoRollbackConfiguration\": {\n      \"@id\": \"amazon-code-deploy:autoRollbackConfiguration\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"amazon-code-deploy:enabled\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n    \"events\": {\n      \"@id\": \"amazon-code-deploy:events\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentId\": {\n      \"@id\": \"amazon-code-deploy:deploymentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deployments\": {\n      \"@id\": \"amazon-code-deploy:deployments\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentInfo\": {\n      \"@id\": \"amazon-code-deploy:deploymentInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"amazon-code-deploy:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"amazon-code-deploy:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completeTime\": {\n      \"@id\": \"amazon-code-deploy:completeTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"creator\": {\n      \"@id\": \"amazon-code-deploy:creator\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  message\": {\n      \"@id\": \"amazon-code-deploy:message\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codedeploy/refs/heads/main/json-ld/amazon-codedeploy-context.jsonld
tags:
- Amazon
- AWS
- Deployment
- DevOps
- CI/CD
- Release Management
- Blue/Green Deployment
- JSON-LD
- Linked Data
- Semantic Web
---
