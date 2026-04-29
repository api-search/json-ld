---
class_count: 0
classes: []
context_file: json-ld/alteryx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/json-ld/alteryx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Alteryx from Alteryx.
layout: jsonld
name: Alteryx Context
namespaces:
- prefix: alteryx
  uri: https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-v3-objects/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: foaf
  uri: http://xmlns.com/foaf/0.1/
properties:
- container: ''
  name: Workflow
  type: ''
- container: ''
  name: WorkflowVersion
  type: ''
- container: ''
  name: Schedule
  type: ''
- container: ''
  name: ScheduleIteration
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Job
  type: ''
- container: ''
  name: Credential
  type: ''
- container: ''
  name: Collection
  type: ''
property_count: 8
provider_name: Alteryx
provider_slug: alteryx
slug: alteryx-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"alteryx\": \"https://help.alteryx.com/current/en/server/api-overview/alteryx-server-api-v3/server-api-v3-objects/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"foaf\": \"http://xmlns.com/foaf/0.1/\",\n\n    \"Workflow\": {\n      \"@id\": \"alteryx:workflow-endpoints\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sourceAppId\": {\n          \"@id\": \"alteryx:sourceAppId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"alteryx:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n      \
  \    \"@type\": \"xsd:dateTime\"\n        },\n        \"publishedVersionNumber\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"publishedVersionId\": {\n          \"@id\": \"alteryx:publishedVersionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isAmp\": {\n          \"@id\": \"alteryx:isAmp\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"executionMode\": {\n          \"@id\": \"alteryx:executionMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runCount\": {\n          \"@id\": \"alteryx:runCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"workerTag\": {\n          \"@id\": \"alteryx:workerTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"districtTags\": {\n          \"@id\": \"alteryx:districtTags\",\n          \"@container\": \"@set\"\n        },\n        \"comments\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"isPublic\": {\n          \"@id\": \"alteryx:isPublic\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isReadyForMigration\": {\n          \"@id\": \"alteryx:isReadyForMigration\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"othersMayDownload\": {\n          \"@id\": \"alteryx:othersMayDownload\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"othersCanViewHistory\": {\n          \"@id\": \"alteryx:othersCanViewHistory\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"othersCanExecute\": {\n          \"@id\": \"alteryx:othersCanExecute\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hasPrivateDataExemption\": {\n          \"@id\": \"alteryx:hasPrivateDataExemption\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"workflowCredentialType\": {\n          \"@id\": \"alteryx:workflowCredentialType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"credentialId\": {\n\
  \          \"@id\": \"alteryx:credentialId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versions\": {\n          \"@id\": \"schema:hasPart\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"WorkflowVersion\": {\n      \"@id\": \"alteryx:workflow-endpoints#version\",\n      \"@context\": {\n        \"versionId\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versionNumber\": {\n          \"@id\": \"schema:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"uploadSource\": {\n          \"@id\": \"alteryx:uploadSource\",\n          \"@type\": \"xsd:string\"\n        },\n        \"uploadDate\": {\n          \"@id\": \"schema:datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"packageWorkflowType\"\
  : {\n          \"@id\": \"alteryx:packageWorkflowType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"published\": {\n          \"@id\": \"alteryx:published\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"comments\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runDisabled\": {\n          \"@id\": \"alteryx:runDisabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"executionMode\": {\n          \"@id\": \"alteryx:executionMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"author\": {\n          \"@id\": \"schema:author\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileName\": {\n          \"@id\": \"alteryx:fileName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"copyright\": {\n          \"@id\": \"schema:copyrightNotice\"\
  ,\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Schedule\": {\n      \"@id\": \"alteryx:schedules-endpoints\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workflowId\": {\n          \"@id\": \"alteryx:workflowId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"versionId\": {\n          \"@id\": \"alteryx:versionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"alteryx:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runDateTime\": {\n          \"@id\": \"alteryx:runDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"comment\": {\n          \"@id\": \"schema:comment\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enabled\": {\n     \
  \     \"@id\": \"alteryx:enabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"priority\": {\n          \"@id\": \"alteryx:priority\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workerTag\": {\n          \"@id\": \"alteryx:workerTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"alteryx:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"credentialId\": {\n          \"@id\": \"alteryx:credentialId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"creationTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastRunTime\": {\n          \"@id\": \"alteryx:lastRunTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"state\": {\n          \"@id\": \"alteryx:state\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runCount\": {\n          \"@id\": \"alteryx:runCount\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"frequency\": {\n          \"@id\": \"alteryx:frequency\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastError\": {\n          \"@id\": \"alteryx:lastError\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cpuName\": {\n          \"@id\": \"alteryx:cpuName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeZone\": {\n          \"@id\": \"alteryx:timeZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"iteration\": {\n          \"@id\": \"alteryx:iteration\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ScheduleIteration\": {\n      \"@id\": \"alteryx:schedules-endpoints#iteration\",\n      \"@context\": {\n        \"iterationType\": {\n          \"@id\": \"alteryx:iterationType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\"\
  : {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"cronExpression\": {\n          \"@id\": \"alteryx:cronExpression\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"alteryx:user-endpoints\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstName\": {\n          \"@id\": \"schema:givenName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"lastName\": {\n          \"@id\": \"schema:familyName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"email\": {\n          \"@id\": \"schema:email\",\n          \"@type\": \"xsd:string\"\n        },\n        \"role\": {\n          \"@id\": \"alteryx:role\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n\
  \        },\n        \"defaultWorkerTag\": {\n          \"@id\": \"alteryx:defaultWorkerTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"canScheduleJobs\": {\n          \"@id\": \"alteryx:canScheduleJobs\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canPrioritizeJobs\": {\n          \"@id\": \"alteryx:canPrioritizeJobs\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canAssignJobs\": {\n          \"@id\": \"alteryx:canAssignJobs\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"canCreateCollections\": {\n          \"@id\": \"alteryx:canCreateCollections\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isApiEnabled\": {\n          \"@id\": \"alteryx:isApiEnabled\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"defaultCredentialId\": {\n          \"@id\": \"alteryx:defaultCredentialId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isAccountLocked\": {\n          \"@id\": \"alteryx:isAccountLocked\"\
  ,\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isActive\": {\n          \"@id\": \"alteryx:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isValidated\": {\n          \"@id\": \"alteryx:isValidated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"timeZone\": {\n          \"@id\": \"alteryx:timeZone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"language\": {\n          \"@id\": \"schema:inLanguage\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Job\": {\n      \"@id\": \"alteryx:workflow-endpoints#job\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"appId\": {\n          \"@id\": \"alteryx:appId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createDateTime\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\"\
  : {\n          \"@id\": \"alteryx:status\",\n          \"@type\": \"xsd:string\"\n        },\n        \"disposition\": {\n          \"@id\": \"alteryx:disposition\",\n          \"@type\": \"xsd:string\"\n        },\n        \"priority\": {\n          \"@id\": \"alteryx:priority\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workerTag\": {\n          \"@id\": \"alteryx:workerTag\",\n          \"@type\": \"xsd:string\"\n        },\n        \"runWithE2\": {\n          \"@id\": \"alteryx:runWithE2\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"outputs\": {\n          \"@id\": \"alteryx:outputs\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        },\n        \"messages\": {\n          \"@id\": \"alteryx:messages\",\n          \"@type\": \"@id\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Credential\": {\n      \"@id\": \"alteryx:credential-endpoints\",\n      \"@context\": {\n        \"id\": {\n       \
  \   \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"username\": {\n          \"@id\": \"alteryx:username\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Collection\": {\n      \"@id\": \"alteryx:collection-endpoints\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"schema:identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ownerId\": {\n          \"@id\": \"alteryx:ownerId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateCreated\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/alteryx/refs/heads/main/json-ld/alteryx-context.jsonld
tags:
- Analytics
- Automation
- Data Engineering
- Data Preparation
- Data Science
- ETL
- Machine Learning
- Predictive Analytics
- JSON-LD
- Linked Data
- Semantic Web
---
