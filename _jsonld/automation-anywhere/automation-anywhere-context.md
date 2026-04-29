---
api_specs:
- filename: automation-anywhere-control-room-openapi.yml
  format: yaml
  label: Automation Anywhere Control Room API
  slug: control-room-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-control-room-openapi.yml
- filename: automation-anywhere-bot-deploy-openapi.yml
  format: yaml
  label: Automation Anywhere Bot Deploy API
  slug: bot-deploy-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-bot-deploy-openapi.yml
- filename: automation-anywhere-workload-management-openapi.yml
  format: yaml
  label: Automation Anywhere Workload Management API
  slug: workload-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-workload-management-openapi.yml
- filename: automation-anywhere-bot-insight-openapi.yml
  format: yaml
  label: Automation Anywhere Bot Insight API
  slug: bot-insight-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-bot-insight-openapi.yml
- filename: automation-anywhere-api-task-execution-openapi.yml
  format: yaml
  label: Automation Anywhere API Task Execution API
  slug: api-task-execution-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-api-task-execution-openapi.yml
- filename: automation-anywhere-credential-vault-openapi.yml
  format: yaml
  label: Automation Anywhere Credential Vault API
  slug: credential-vault-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-credential-vault-openapi.yml
- filename: automation-anywhere-repository-management-openapi.yml
  format: yaml
  label: Automation Anywhere Repository Management API
  slug: repository-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/openapi/automation-anywhere-repository-management-openapi.yml
class_count: 0
classes: []
context_file: json-ld/automation-anywhere-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/json-ld/automation-anywhere-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Automation Anywhere from automation-anywhere.
layout: jsonld
name: Automation Anywhere Context
namespaces:
- prefix: aa
  uri: https://automationanywhere.com/ontology/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rpa
  uri: https://www.w3.org/ns/rpa#
properties:
- container: ''
  name: Bot
  type: ''
- container: ''
  name: Deployment
  type: ''
- container: ''
  name: WorkItem
  type: ''
- container: ''
  name: Queue
  type: ''
- container: ''
  name: Credential
  type: ''
- container: ''
  name: Locker
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Role
  type: ''
- container: ''
  name: ApiTaskAllocation
  type: ''
- container: ''
  name: BotRunRecord
  type: ''
property_count: 10
provider_name: automation-anywhere
provider_slug: automation-anywhere
slug: automation-anywhere-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aa\": \"https://automationanywhere.com/ontology/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rpa\": \"https://www.w3.org/ns/rpa#\",\n\n    \"Bot\": {\n      \"@id\": \"aa:Bot\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"path\": \"aa:repositoryPath\",\n        \"type\": {\n          \"@id\": \"aa:botType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"aa:version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"workspaceType\": {\n          \"@id\": \"aa:workspaceType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"size\": {\n          \"@id\": \"schema:fileSize\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdBy\"\
  : \"dcterms:creator\",\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedBy\": \"dcterms:contributor\",\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"dependencies\": {\n          \"@id\": \"aa:hasDependency\",\n          \"@container\": \"@set\"\n        },\n        \"permission\": \"aa:hasPermission\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Deployment\": {\n      \"@id\": \"aa:Deployment\",\n      \"@context\": {\n        \"deploymentId\": {\n          \"@id\": \"aa:deploymentId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"botId\": {\n          \"@id\": \"aa:deployedBot\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"automationName\": \"schema:name\",\n        \"description\": \"schema:description\"\
  ,\n        \"automationPriority\": \"aa:priority\",\n        \"runElevated\": {\n          \"@id\": \"aa:runElevated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"hideBotAgentUi\": {\n          \"@id\": \"aa:hideBotAgentUi\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"botInput\": \"aa:hasInput\",\n        \"callbackInfo\": \"aa:hasCallback\",\n        \"unattendedRequest\": \"aa:unattendedConfig\",\n        \"attendedRequest\": \"aa:attendedConfig\",\n        \"headlessRequest\": \"aa:headlessConfig\"\n      }\n    },\n\n    \"WorkItem\": {\n      \"@id\": \"aa:WorkItem\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"queueId\": {\n          \"@id\": \"aa:belongsToQueue\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"json\": \"aa:payload\",\n        \"status\": {\n          \"@id\": \"aa:workItemStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"result\": {\n          \"@id\": \"aa:workItemResult\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"col1\": \"aa:displayColumn1\",\n        \"col2\": \"aa:displayColumn2\",\n        \"col3\": \"aa:displayColumn3\",\n        \"comment\": \"schema:comment\",\n        \"error\": \"aa:errorMessage\",\n        \"retryCount\": {\n          \"@id\": \"aa:retryCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"startTime\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"endTime\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"deferredUntil\": {\n          \"@id\": \"aa:deferredUntil\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Queue\"\
  : {\n      \"@id\": \"aa:Queue\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": {\n          \"@id\": \"aa:queueStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"workItemModelId\": {\n          \"@id\": \"aa:hasWorkItemModel\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"reactivationThreshold\": {\n          \"@id\": \"aa:reactivationThreshold\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"disallowDuplicate\": {\n          \"@id\": \"aa:disallowDuplicate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"autoRetryLimit\": {\n          \"@id\": \"aa:autoRetryLimit\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"\
  @type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Credential\": {\n      \"@id\": \"aa:Credential\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"ownerId\": {\n          \"@id\": \"schema:owner\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"attributes\": {\n          \"@id\": \"aa:hasAttribute\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Locker\": {\n      \"@id\": \"aa:Locker\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"ownerId\": {\n          \"@id\": \"schema:owner\",\n          \"@type\"\
  : \"xsd:integer\"\n        },\n        \"credentials\": {\n          \"@id\": \"aa:containsCredential\",\n          \"@container\": \"@set\"\n        },\n        \"consumers\": {\n          \"@id\": \"aa:hasConsumer\",\n          \"@container\": \"@set\"\n        },\n        \"members\": {\n          \"@id\": \"aa:hasMember\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"username\": \"schema:identifier\",\n        \"email\": \"schema:email\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"enabled\": {\n          \"@id\": \"aa:accountEnabled\",\n          \"@type\": \"\
  xsd:boolean\"\n        },\n        \"roles\": {\n          \"@id\": \"aa:hasRole\",\n          \"@container\": \"@set\"\n        },\n        \"licenseFeatures\": {\n          \"@id\": \"aa:licenseFeature\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Role\": {\n      \"@id\": \"schema:Role\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"permissions\": {\n          \"@id\": \"aa:hasPermission\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dcterms:modified\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ApiTaskAllocation\": {\n      \"@id\": \"aa:ApiTaskAllocation\",\n      \"@context\": {\n        \"fileId\": {\n          \"@id\": \"aa:allocatedFileId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"filePath\": \"aa:repositoryPath\",\n        \"fileName\": \"schema:name\",\n        \"concurrencyLimit\": {\n          \"@id\": \"aa:concurrencyLimit\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"BotRunRecord\": {\n      \"@id\": \"aa:BotRunRecord\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"userName\": \"schema:identifier\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\",\n        \"hostName\": \"schema:serverName\",\n        \"fileName\": \"schema:name\",\n        \"startTime\": {\n          \"@id\": \"schema:startTime\",\n          \"@type\": \"xsd:dateTime\"\n     \
  \   },\n        \"endTime\": {\n          \"@id\": \"schema:endTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"status\": {\n          \"@id\": \"aa:executionStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"timeTaken\": {\n          \"@id\": \"schema:duration\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"successIndicator\": {\n          \"@id\": \"aa:successIndicator\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/automation-anywhere/refs/heads/main/json-ld/automation-anywhere-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
