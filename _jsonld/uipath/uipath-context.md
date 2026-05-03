---
api_specs:
- filename: uipath-orchestrator-openapi.yml
  format: yaml
  label: UiPath Orchestrator API
  slug: uipath-orchestrator-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-orchestrator-openapi.yml
- filename: uipath-automation-hub-openapi.yml
  format: yaml
  label: UiPath Automation Hub API
  slug: uipath-automation-hub-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-automation-hub-openapi.yml
- filename: uipath-document-understanding-openapi.yml
  format: yaml
  label: UiPath Document Understanding API
  slug: uipath-document-understanding-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-document-understanding-openapi.yml
- filename: uipath-data-service-openapi.yml
  format: yaml
  label: UiPath Data Service API
  slug: uipath-data-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-data-service-openapi.yml
- filename: uipath-platform-management-openapi.yml
  format: yaml
  label: UiPath Platform Management API
  slug: uipath-platform-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-platform-management-openapi.yml
- filename: uipath-test-manager-openapi.yml
  format: yaml
  label: UiPath Test Manager API
  slug: uipath-test-manager-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/openapi/uipath-test-manager-openapi.yml
class_count: 0
classes: []
context_file: json-ld/uipath-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath from UiPath.
layout: jsonld
name: Uipath Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
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
  name: Job
  type: ''
- container: ''
  name: Robot
  type: ''
- container: ''
  name: Process
  type: ''
- container: ''
  name: QueueDefinition
  type: ''
- container: ''
  name: QueueItem
  type: ''
- container: ''
  name: Asset
  type: ''
- container: ''
  name: Folder
  type: ''
- container: ''
  name: Machine
  type: ''
- container: ''
  name: Webhook
  type: ''
- container: ''
  name: AutomationIdea
  type: ''
- container: ''
  name: TestProject
  type: ''
- container: ''
  name: TestCase
  type: ''
- container: ''
  name: Requirement
  type: ''
- container: ''
  name: DocumentUnderstandingProject
  type: ''
- container: ''
  name: ExtractedField
  type: ''
property_count: 15
provider_name: UiPath
provider_slug: uipath
slug: uipath-context
source_filename: uipath-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rpa\": \"https://www.w3.org/ns/rpa#\",\n\n    \"Job\": {\n      \"@id\": \"uipath:Job\",\n      \"@context\": {\n        \"Id\": \"uipath:jobId\",\n        \"Key\": {\n          \"@id\": \"uipath:jobKey\",\n          \"@type\": \"@id\"\n        },\n        \"ReleaseName\": \"uipath:releaseName\",\n        \"ProcessVersion\": \"uipath:processVersion\",\n        \"State\": \"uipath:jobState\",\n        \"Source\": \"uipath:jobSource\",\n        \"StartTime\": {\n          \"@id\": \"schema:startDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"EndTime\": {\n          \"@id\": \"schema:endDate\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"CreationTime\": {\n          \"@id\": \"dcterms:created\",\n\
  \          \"@type\": \"xsd:dateTime\"\n        },\n        \"Info\": \"schema:description\",\n        \"HostMachineName\": \"uipath:hostMachineName\",\n        \"Robot\": {\n          \"@id\": \"uipath:executedByRobot\",\n          \"@type\": \"@id\"\n        },\n        \"OrganizationUnitId\": \"uipath:organizationUnitId\",\n        \"InputArguments\": \"uipath:inputArguments\",\n        \"OutputArguments\": \"uipath:outputArguments\"\n      }\n    },\n\n    \"Robot\": {\n      \"@id\": \"uipath:Robot\",\n      \"@context\": {\n        \"Id\": \"uipath:robotId\",\n        \"Name\": \"schema:name\",\n        \"MachineName\": \"uipath:machineName\",\n        \"MachineId\": \"uipath:machineId\",\n        \"Version\": \"schema:version\",\n        \"Type\": \"uipath:robotType\",\n        \"HostingType\": \"uipath:hostingType\",\n        \"UserName\": \"schema:accountId\",\n        \"IsConnected\": \"uipath:isConnected\",\n        \"OrganizationUnitId\": \"uipath:organizationUnitId\"\n   \
  \   }\n    },\n\n    \"Process\": {\n      \"@id\": \"uipath:Process\",\n      \"@context\": {\n        \"Id\": \"uipath:processId\",\n        \"Key\": {\n          \"@id\": \"uipath:processKey\",\n          \"@type\": \"@id\"\n        },\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"ProcessVersion\": \"schema:version\",\n        \"OrganizationUnitId\": \"uipath:organizationUnitId\"\n      }\n    },\n\n    \"QueueDefinition\": {\n      \"@id\": \"uipath:QueueDefinition\",\n      \"@context\": {\n        \"Id\": \"uipath:queueId\",\n        \"Name\": \"schema:name\",\n        \"Description\": \"schema:description\",\n        \"MaxNumberOfRetries\": \"uipath:maxRetries\",\n        \"AcceptAutomaticallyRetry\": \"uipath:acceptAutomaticallyRetry\",\n        \"EnforceUniqueReference\": \"uipath:enforceUniqueReference\",\n        \"OrganizationUnitId\": \"uipath:organizationUnitId\"\n      }\n    },\n\n    \"QueueItem\": {\n      \"@id\": \"\
  uipath:QueueItem\",\n      \"@context\": {\n        \"Id\": \"uipath:queueItemId\",\n        \"Key\": {\n          \"@id\": \"uipath:queueItemKey\",\n          \"@type\": \"@id\"\n        },\n        \"QueueDefinitionId\": \"uipath:belongsToQueue\",\n        \"Status\": \"uipath:transactionStatus\",\n        \"ReviewStatus\": \"uipath:reviewStatus\",\n        \"Priority\": \"uipath:priority\",\n        \"Reference\": \"uipath:reference\",\n        \"SpecificContent\": \"uipath:specificContent\",\n        \"Output\": \"uipath:transactionOutput\",\n        \"CreationTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"StartProcessing\": {\n          \"@id\": \"uipath:startProcessing\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"EndProcessing\": {\n          \"@id\": \"uipath:endProcessing\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"RetryNumber\": \"uipath:retryNumber\",\n        \"DueDate\"\
  : {\n          \"@id\": \"schema:expires\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"Robot\": {\n          \"@id\": \"uipath:processedByRobot\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"Asset\": {\n      \"@id\": \"uipath:Asset\",\n      \"@context\": {\n        \"Id\": \"uipath:assetId\",\n        \"Name\": \"schema:name\",\n        \"ValueType\": \"uipath:valueType\",\n        \"StringValue\": \"uipath:stringValue\",\n        \"IntValue\": \"uipath:intValue\",\n        \"BoolValue\": \"uipath:boolValue\",\n        \"CredentialUsername\": \"schema:accountId\",\n        \"Description\": \"schema:description\",\n        \"OrganizationUnitId\": \"uipath:organizationUnitId\"\n      }\n    },\n\n    \"Folder\": {\n      \"@id\": \"uipath:Folder\",\n      \"@context\": {\n        \"Id\": \"uipath:folderId\",\n        \"Key\": {\n          \"@id\": \"uipath:folderKey\",\n          \"@type\": \"@id\"\n        },\n        \"DisplayName\": \"schema:name\"\
  ,\n        \"FullyQualifiedName\": \"uipath:fullyQualifiedName\",\n        \"FolderType\": \"uipath:folderType\"\n      }\n    },\n\n    \"Machine\": {\n      \"@id\": \"uipath:Machine\",\n      \"@context\": {\n        \"Id\": \"uipath:machineId\",\n        \"Name\": \"schema:name\",\n        \"Type\": \"uipath:machineType\",\n        \"LicenseKey\": \"uipath:licenseKey\"\n      }\n    },\n\n    \"Webhook\": {\n      \"@id\": \"uipath:Webhook\",\n      \"@context\": {\n        \"Id\": \"uipath:webhookId\",\n        \"Url\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"Enabled\": \"uipath:isEnabled\",\n        \"Secret\": \"uipath:webhookSecret\",\n        \"SubscribeToAllEvents\": \"uipath:subscribeToAllEvents\",\n        \"AllowInsecureSsl\": \"uipath:allowInsecureSsl\",\n        \"Events\": {\n          \"@id\": \"uipath:subscribedEvents\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"AutomationIdea\": {\n   \
  \   \"@id\": \"uipath:AutomationIdea\",\n      \"@context\": {\n        \"id\": \"uipath:ideaId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"phase\": \"uipath:pipelinePhase\",\n        \"status\": \"schema:status\",\n        \"submittedBy\": \"dcterms:creator\",\n        \"submittedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModified\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"estimatedBenefit\": \"uipath:estimatedBenefit\",\n        \"tags\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"TestProject\": {\n      \"@id\": \"uipath:TestProject\",\n      \"@context\": {\n        \"id\": \"uipath:projectId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"createdBy\": \"dcterms:creator\"\
  ,\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"TestCase\": {\n      \"@id\": \"uipath:TestCase\",\n      \"@context\": {\n        \"id\": \"uipath:testCaseId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"schema:status\",\n        \"automationStatus\": \"uipath:automationStatus\",\n        \"labels\": {\n          \"@id\": \"schema:keywords\",\n          \"@container\": \"@set\"\n        },\n        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Requirement\": {\n      \"@id\": \"uipath:Requirement\",\n      \"@context\": {\n        \"id\": \"uipath:requirementId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"externalId\": \"dcterms:identifier\",\n        \"status\": \"schema:status\",\n\
  \        \"createdOn\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"DocumentUnderstandingProject\": {\n      \"@id\": \"uipath:DocumentUnderstandingProject\",\n      \"@context\": {\n        \"id\": \"uipath:projectId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"extractorsUrl\": {\n          \"@id\": \"uipath:extractorsUrl\",\n          \"@type\": \"@id\"\n        },\n        \"classifiersUrl\": {\n          \"@id\": \"uipath:classifiersUrl\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ExtractedField\": {\n      \"@id\": \"uipath:ExtractedField\",\n      \"@context\": {\n        \"FieldId\": \"uipath:fieldId\",\n        \"FieldName\": \"schema:name\",\n        \"IsMissing\": \"uipath:isMissing\",\n        \"Value\": \"schema:value\",\n        \"Confidence\": \"uipath:confidence\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-context.jsonld
tags:
- Automation
- Robotic Process Automation
- RPA
- Artificial Intelligence
- Document Processing
- Enterprise Automation
- Orchestration
- Testing
- JSON-LD
- Linked Data
- Semantic Web
---
