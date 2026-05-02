---
api_specs:
- filename: openapi.yaml
  format: yaml
  label: Azure DevOps Services REST API
  slug: ''
  spec_type: OpenAPI
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/
- filename: azure-devops-work-items-api-openapi.yml
  format: yaml
  label: Azure DevOps Boards API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-work-items-api-openapi.yml
- filename: azure-devops-git-api-openapi.yml
  format: yaml
  label: Azure DevOps Repos API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-git-api-openapi.yml
- filename: azure-devops-pipelines-api-openapi.yml
  format: yaml
  label: Azure DevOps Pipelines API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-pipelines-api-openapi.yml
- filename: azure-devops-builds-api-openapi.yml
  format: yaml
  label: Azure DevOps Build API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-builds-api-openapi.yml
- filename: azure-devops-releases-api-openapi.yml
  format: yaml
  label: Azure DevOps Release API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-releases-api-openapi.yml
- filename: azure-devops-test-plans-api-openapi.yml
  format: yaml
  label: Azure DevOps Test Plans API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-test-plans-api-openapi.yml
- filename: azure-devops-artifacts-api-openapi.yml
  format: yaml
  label: Azure DevOps Artifacts API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-artifacts-api-openapi.yml
- filename: azure-devops-service-hooks-api-openapi.yml
  format: yaml
  label: Azure DevOps Service Hooks API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-service-hooks-api-openapi.yml
- filename: azure-devops-wiki-api-openapi.yml
  format: yaml
  label: Azure DevOps Wiki API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/openapi/azure-devops-wiki-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/azure-devops-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/json-ld/azure-devops-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Devops from Azure DevOps.
layout: jsonld
name: Azure Devops Context
namespaces:
- prefix: azdevops
  uri: https://learn.microsoft.com/en-us/rest/api/azure/devops/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: rdf
  uri: http://www.w3.org/1999/02/22-rdf-syntax-ns#
properties:
- container: ''
  name: WorkItem
  type: reference
- container: ''
  name: Repository
  type: reference
- container: ''
  name: PullRequest
  type: reference
- container: ''
  name: Build
  type: reference
- container: ''
  name: Pipeline
  type: reference
- container: ''
  name: PipelineRun
  type: reference
- container: ''
  name: ServiceHookEvent
  type: reference
- container: ''
  name: Feed
  type: reference
- container: ''
  name: Package
  type: reference
- container: ''
  name: TestPlan
  type: reference
- container: ''
  name: Wiki
  type: reference
- container: ''
  name: WikiPage
  type: reference
- container: ''
  name: Release
  type: reference
- container: ''
  name: IdentityRef
  type: reference
- container: ''
  name: TeamProject
  type: reference
property_count: 15
provider_name: Azure DevOps
provider_slug: microsoft-azure-devops
slug: azure-devops-context
source_filename: azure-devops-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n\n    \"azdevops\": \"https://learn.microsoft.com/en-us/rest/api/azure/devops/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"rdf\": \"http://www.w3.org/1999/02/22-rdf-syntax-ns#\",\n\n    \"WorkItem\": {\n      \"@id\": \"azdevops:wit/WorkItem\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:wit/WorkItem/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"rev\": {\n          \"@id\": \"azdevops:wit/WorkItem/rev\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"fields\": {\n          \"@id\": \"azdevops:wit/WorkItem/fields\",\n          \"@container\": \"@index\"\n        },\n        \"relations\": {\n          \"@id\": \"azdevops:wit/WorkItem/relations\"\
  ,\n          \"@container\": \"@set\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"state\": {\n          \"@id\": \"azdevops:wit/WorkItem/state\"\n        },\n        \"workItemType\": {\n          \"@id\": \"azdevops:wit/WorkItem/type\"\n        },\n        \"assignedTo\": {\n          \"@id\": \"schema:accountablePerson\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"changedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"areaPath\": {\n          \"@id\": \"azdevops:wit/WorkItem/areaPath\"\n        },\n        \"iterationPath\": {\n          \"@id\": \"azdevops:wit/WorkItem/iterationPath\"\n        },\n        \"priority\"\
  : {\n          \"@id\": \"azdevops:wit/WorkItem/priority\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\"\n        }\n      }\n    },\n\n    \"Repository\": {\n      \"@id\": \"azdevops:git/Repository\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:git/Repository/id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"remoteUrl\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"sshUrl\": {\n          \"@id\": \"azdevops:git/Repository/sshUrl\"\n        },\n        \"webUrl\": {\n          \"@id\": \"schema:mainEntityOfPage\",\n          \"@type\": \"@id\"\n        },\n        \"defaultBranch\": {\n          \"@id\": \"azdevops:git/Repository/defaultBranch\"\n        },\n       \
  \ \"project\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n        \"size\": {\n          \"@id\": \"schema:contentSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"isFork\": {\n          \"@id\": \"azdevops:git/Repository/isFork\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isDisabled\": {\n          \"@id\": \"azdevops:git/Repository/isDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"parentRepository\": {\n          \"@id\": \"schema:isBasedOn\"\n        }\n      }\n    },\n\n    \"PullRequest\": {\n      \"@id\": \"azdevops:git/PullRequest\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"pullRequestId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"title\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\"\
  ,\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"azdevops:git/PullRequest/status\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\"\n        },\n        \"creationDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closedDate\": {\n          \"@id\": \"dcterms:dateAccepted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sourceRefName\": {\n          \"@id\": \"azdevops:git/PullRequest/sourceRefName\"\n        },\n        \"targetRefName\": {\n          \"@id\": \"azdevops:git/PullRequest/targetRefName\"\n        },\n        \"mergeStatus\": {\n          \"@id\": \"azdevops:git/PullRequest/mergeStatus\"\n        },\n        \"reviewers\": {\n          \"@id\": \"schema:contributor\",\n          \"@container\": \"@set\"\n        },\n        \"isDraft\": {\n          \"@id\": \"azdevops:git/PullRequest/isDraft\",\n          \"@type\": \"xsd:boolean\"\
  \n        },\n        \"repository\": {\n          \"@id\": \"azdevops:git/PullRequest/repository\"\n        },\n        \"workItemRefs\": {\n          \"@id\": \"schema:about\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Build\": {\n      \"@id\": \"azdevops:build/Build\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:build/Build/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"buildNumber\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"status\": {\n          \"@id\": \"azdevops:build/Build/status\"\n        },\n        \"result\": {\n          \"@id\": \"azdevops:build/Build/result\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"queueTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"startTime\": {\n          \"@id\": \"dcterms:date\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"finishTime\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"definition\": {\n          \"@id\": \"azdevops:build/Build/definition\"\n        },\n        \"project\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n        \"sourceBranch\": {\n          \"@id\": \"azdevops:build/Build/sourceBranch\"\n        },\n        \"sourceVersion\": {\n          \"@id\": \"schema:version\"\n        },\n        \"requestedBy\": {\n          \"@id\": \"schema:author\"\n        },\n        \"repository\": {\n          \"@id\": \"azdevops:build/Build/repository\"\n        }\n      }\n    },\n\n    \"Pipeline\": {\n      \"@id\": \"azdevops:pipelines/Pipeline\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:pipelines/Pipeline/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\"\
  : \"schema:name\"\n        },\n        \"folder\": {\n          \"@id\": \"azdevops:pipelines/Pipeline/folder\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"revision\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"configuration\": {\n          \"@id\": \"azdevops:pipelines/Pipeline/configuration\"\n        }\n      }\n    },\n\n    \"PipelineRun\": {\n      \"@id\": \"azdevops:pipelines/Run\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:pipelines/Run/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"state\": {\n          \"@id\": \"azdevops:pipelines/Run/state\"\n        },\n        \"result\": {\n          \"@id\": \"azdevops:pipelines/Run/result\"\n        },\n        \"createdDate\": {\n          \"@id\":\
  \ \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"finishedDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"pipeline\": {\n          \"@id\": \"azdevops:pipelines/Run/pipeline\"\n        },\n        \"resources\": {\n          \"@id\": \"azdevops:pipelines/Run/resources\"\n        },\n        \"variables\": {\n          \"@id\": \"azdevops:pipelines/Run/variables\"\n        },\n        \"templateParameters\": {\n          \"@id\": \"azdevops:pipelines/Run/templateParameters\"\n        }\n      }\n    },\n\n    \"ServiceHookEvent\": {\n      \"@id\": \"azdevops:hooks/ServiceHookEvent\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"@id\"\n        },\n        \"subscriptionId\": {\n          \"@id\": \"azdevops:hooks/ServiceHookEvent/subscriptionId\"\n\
  \        },\n        \"notificationId\": {\n          \"@id\": \"azdevops:hooks/ServiceHookEvent/notificationId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"eventType\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"publisherId\": {\n          \"@id\": \"azdevops:hooks/ServiceHookEvent/publisherId\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resource\": {\n          \"@id\": \"schema:object\"\n        },\n        \"resourceVersion\": {\n          \"@id\": \"schema:version\"\n        },\n        \"resourceContainers\": {\n          \"@id\": \"azdevops:hooks/ServiceHookEvent/resourceContainers\"\n        },\n        \"message\": {\n          \"@id\": \"schema:description\"\n        }\n      }\n    },\n\n    \"Feed\": {\n      \"@id\": \"azdevops:artifacts/Feed\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\"\
  : \"azdevops:artifacts/Feed/id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"project\": {\n          \"@id\": \"schema:isPartOf\"\n        },\n        \"upstreamEnabled\": {\n          \"@id\": \"azdevops:artifacts/Feed/upstreamEnabled\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"azdevops:artifacts/Package\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:artifacts/Package/id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"normalizedName\": {\n          \"@id\": \"azdevops:artifacts/Package/normalizedName\"\n        },\n        \"protocolType\": {\n          \"@id\": \"schema:encodingFormat\"\n     \
  \   },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"versions\": {\n          \"@id\": \"azdevops:artifacts/Package/versions\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TestPlan\": {\n      \"@id\": \"azdevops:testplan/TestPlan\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:testplan/TestPlan/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"startDate\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endDate\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"state\"\
  : {\n          \"@id\": \"azdevops:testplan/TestPlan/state\"\n        },\n        \"owner\": {\n          \"@id\": \"schema:author\"\n        },\n        \"areaPath\": {\n          \"@id\": \"azdevops:testplan/TestPlan/areaPath\"\n        },\n        \"iteration\": {\n          \"@id\": \"azdevops:testplan/TestPlan/iteration\"\n        },\n        \"project\": {\n          \"@id\": \"schema:isPartOf\"\n        }\n      }\n    },\n\n    \"Wiki\": {\n      \"@id\": \"azdevops:wiki/Wiki\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:wiki/Wiki/id\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"type\": {\n          \"@id\": \"schema:additionalType\"\n        },\n        \"repositoryId\": {\n          \"@id\": \"azdevops:wiki/Wiki/repositoryId\"\n        },\n        \"mappedPath\": {\n         \
  \ \"@id\": \"azdevops:wiki/Wiki/mappedPath\"\n        },\n        \"project\": {\n          \"@id\": \"schema:isPartOf\"\n        }\n      }\n    },\n\n    \"WikiPage\": {\n      \"@id\": \"azdevops:wiki/WikiPage\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:wiki/WikiPage/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"path\": {\n          \"@id\": \"azdevops:wiki/WikiPage/path\"\n        },\n        \"content\": {\n          \"@id\": \"schema:text\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"remoteUrl\": {\n          \"@id\": \"schema:mainEntityOfPage\",\n          \"@type\": \"@id\"\n        },\n        \"order\": {\n          \"@id\": \"schema:position\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"subPages\": {\n          \"@id\": \"schema:hasPart\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\
  \n    \"Release\": {\n      \"@id\": \"azdevops:release/Release\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"azdevops:release/Release/id\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"status\": {\n          \"@id\": \"azdevops:release/Release/status\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"modifiedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdBy\": {\n          \"@id\": \"dcterms:creator\"\n        },\n        \"releaseDefinition\": {\n          \"@id\": \"azdevops:release/Release/definition\"\n       \
  \ },\n        \"environments\": {\n          \"@id\": \"azdevops:release/Release/environments\",\n          \"@container\": \"@set\"\n        },\n        \"artifacts\": {\n          \"@id\": \"schema:result\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"IdentityRef\": {\n      \"@id\": \"schema:Person\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\n        },\n        \"displayName\": {\n          \"@id\": \"schema:name\"\n        },\n        \"uniqueName\": {\n          \"@id\": \"schema:email\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"imageUrl\": {\n          \"@id\": \"schema:image\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"TeamProject\": {\n      \"@id\": \"azdevops:core/Project\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\"\
  \n        },\n        \"name\": {\n          \"@id\": \"schema:name\"\n        },\n        \"description\": {\n          \"@id\": \"dcterms:description\"\n        },\n        \"url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"state\": {\n          \"@id\": \"azdevops:core/Project/state\"\n        },\n        \"visibility\": {\n          \"@id\": \"schema:accessMode\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-azure-devops/refs/heads/main/json-ld/azure-devops-context.jsonld
tags:
- Agile
- CI/CD
- DevOps
- Project Management
- Version Control
- JSON-LD
- Linked Data
- Semantic Web
---
