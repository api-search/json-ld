---
api_specs:
- filename: amazon-codebuild-openapi-original.yaml
  format: yaml
  label: Amazon CodeBuild API
  slug: amazon-codebuild-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/amazon-codebuild/refs/heads/main/openapi/amazon-codebuild-openapi-original.yaml
class_count: 11
classes:
- CreateProjectRequest
- CreateProjectResponse
- ListProjectsResponse
- Project
- StartBuildRequest
- StartBuildResponse
- StopBuildResponse
- BatchGetBuildsResponse
- Build
- name
- description
context_file: json-ld/amazon-codebuild-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/amazon-codebuild/refs/heads/main/json-ld/amazon-codebuild-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Amazon Codebuild from Amazon CodeBuild.
layout: jsonld
name: Amazon Codebuild Context
namespaces:
- prefix: amazon-code-build
  uri: https://amazon-code-build.amazonaws.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: source
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: buildspec
  type: string
- container: ''
  name: environment
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: computeType
  type: string
- container: set
  name: environmentVariables
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: serviceRole
  type: string
- container: ''
  name: timeoutInMinutes
  type: integer
- container: ''
  name: project
  type: string
- container: set
  name: projects
  type: string
- container: ''
  name: nextToken
  type: string
- container: ''
  name: arn
  type: string
- container: ''
  name: created
  type: dateTime
- container: ''
  name: lastModified
  type: dateTime
- container: ''
  name: projectName
  type: string
- container: ''
  name: sourceVersion
  type: string
- container: set
  name: environmentVariablesOverride
  type: string
- container: ''
  name: build
  type: string
- container: set
  name: builds
  type: string
- container: set
  name: buildsNotFound
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: buildNumber
  type: integer
- container: ''
  name: startTime
  type: dateTime
- container: ''
  name: endTime
  type: dateTime
- container: ''
  name: currentPhase
  type: string
- container: ''
  name: buildStatus
  type: string
property_count: 29
provider_name: Amazon CodeBuild
provider_slug: amazon-codebuild
slug: amazon-codebuild-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"amazon-code-build\": \"https://amazon-code-build.amazonaws.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CreateProjectRequest\": \"amazon-code-build:CreateProjectRequest\",\n    \"CreateProjectResponse\": \"amazon-code-build:CreateProjectResponse\",\n    \"ListProjectsResponse\": \"amazon-code-build:ListProjectsResponse\",\n    \"Project\": \"amazon-code-build:Project\",\n    \"StartBuildRequest\": \"amazon-code-build:StartBuildRequest\",\n    \"StartBuildResponse\": \"amazon-code-build:StartBuildResponse\",\n    \"StopBuildResponse\": \"amazon-code-build:StopBuildResponse\",\n    \"BatchGetBuildsResponse\": \"amazon-code-build:BatchGetBuildsResponse\",\n    \"Build\": \"amazon-code-build:Build\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"source\": {\n      \"@id\"\
  : \"amazon-code-build:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"amazon-code-build:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"amazon-code-build:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildspec\": {\n      \"@id\": \"amazon-code-build:buildspec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environment\": {\n      \"@id\": \"amazon-code-build:environment\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"amazon-code-build:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"computeType\": {\n      \"@id\": \"amazon-code-build:computeType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentVariables\": {\n      \"@id\": \"amazon-code-build:environmentVariables\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"amazon-code-build:value\",\n      \"@type\": \"xsd:string\"\n  \
  \  },\n    \"serviceRole\": {\n      \"@id\": \"amazon-code-build:serviceRole\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeoutInMinutes\": {\n      \"@id\": \"amazon-code-build:timeoutInMinutes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"project\": {\n      \"@id\": \"amazon-code-build:project\",\n      \"@type\": \"xsd:string\"\n    },\n    \"projects\": {\n      \"@id\": \"amazon-code-build:projects\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextToken\": {\n      \"@id\": \"amazon-code-build:nextToken\",\n      \"@type\": \"xsd:string\"\n    },\n    \"arn\": {\n      \"@id\": \"amazon-code-build:arn\",\n      \"@type\": \"xsd:string\"\n    },\n    \"created\": {\n      \"@id\": \"amazon-code-build:created\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModified\": {\n      \"@id\": \"amazon-code-build:lastModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"projectName\": {\n      \"@id\": \"amazon-code-build:projectName\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"sourceVersion\": {\n      \"@id\": \"amazon-code-build:sourceVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"environmentVariablesOverride\": {\n      \"@id\": \"amazon-code-build:environmentVariablesOverride\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"build\": {\n      \"@id\": \"amazon-code-build:build\",\n      \"@type\": \"xsd:string\"\n    },\n    \"builds\": {\n      \"@id\": \"amazon-code-build:builds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildsNotFound\": {\n      \"@id\": \"amazon-code-build:buildsNotFound\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"amazon-code-build:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildNumber\": {\n      \"@id\": \"amazon-code-build:buildNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"\
  amazon-code-build:startTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"endTime\": {\n      \"@id\": \"amazon-code-build:endTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"currentPhase\": {\n      \"@id\": \"amazon-code-build:currentPhase\",\n      \"@type\": \"xsd:string\"\n    },\n    \"buildStatus\": {\n      \"@id\": \"amazon-code-build:buildStatus\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/amazon-codebuild/refs/heads/main/json-ld/amazon-codebuild-context.jsonld
tags:
- Amazon
- AWS
- CI/CD
- Build
- Continuous Integration
- DevOps
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
