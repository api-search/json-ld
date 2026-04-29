---
api_specs:
- filename: salesforce-rest-api-openapi.json
  format: json
  label: Salesforce REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-rest-api-openapi.json
- filename: salesforce-bulk-api-openapi.json
  format: json
  label: Salesforce Bulk API 2.0
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-bulk-api-openapi.json
- filename: salesforce-streaming-api-openapi.json
  format: json
  label: Salesforce Streaming API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-streaming-api-openapi.json
- filename: salesforce-platform-events-api-openapi.json
  format: json
  label: Salesforce Platform Events API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-platform-events-api-openapi.json
- filename: salesforce-analytics-api-openapi.json
  format: json
  label: Salesforce Analytics API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-analytics-api-openapi.json
- filename: salesforce-tooling-api-openapi.json
  format: json
  label: Salesforce Tooling API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-tooling-api-openapi.json
- filename: salesforce-connect-rest-api-openapi.json
  format: json
  label: Salesforce Connect REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-connect-rest-api-openapi.json
- filename: salesforce-change-data-capture-api-openapi.json
  format: json
  label: Salesforce Change Data Capture API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-change-data-capture-api-openapi.json
- filename: salesforce-invocable-actions-api-openapi.json
  format: json
  label: Salesforce Invocable Actions API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-invocable-actions-api-openapi.json
- filename: salesforce-composite-api-openapi.json
  format: json
  label: Salesforce Composite API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-composite-api-openapi.json
- filename: salesforce-apex-rest-api-openapi.json
  format: json
  label: Salesforce Apex REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/openapi/salesforce-apex-rest-api-openapi.json
class_count: 0
classes: []
context_file: json-ld/salesforce-automation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/json-ld/salesforce-automation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salesforce Automation from Salesforce Automation.
layout: jsonld
name: Salesforce Automation Context
namespaces:
- prefix: sf
  uri: https://developer.salesforce.com/ns/
- prefix: sfauto
  uri: https://developer.salesforce.com/ns/automation/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: bpmn
  uri: http://www.omg.org/spec/BPMN/20100524/MODEL#
properties:
- container: ''
  name: Flow
  type: reference
- container: ''
  name: FlowDefinition
  type: reference
- container: ''
  name: FlowElement
  type: reference
- container: ''
  name: FlowVariable
  type: reference
- container: ''
  name: FlowDecision
  type: reference
- container: ''
  name: FlowActionCall
  type: reference
- container: ''
  name: WorkflowRule
  type: reference
- container: ''
  name: ApprovalProcess
  type: reference
- container: ''
  name: PlatformEvent
  type: reference
- container: ''
  name: ChangeDataCaptureEvent
  type: reference
- container: ''
  name: BulkJob
  type: reference
- container: ''
  name: InvocableAction
  type: reference
- container: ''
  name: PushTopic
  type: reference
- container: ''
  name: CompositeRequest
  type: reference
- container: ''
  name: AnalyticsDashboard
  type: reference
- container: ''
  name: AnalyticsDataset
  type: reference
property_count: 16
provider_name: Salesforce Automation
provider_slug: salesforce-automation
slug: salesforce-automation-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"sf\": \"https://developer.salesforce.com/ns/\",\n    \"sfauto\": \"https://developer.salesforce.com/ns/automation/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"bpmn\": \"http://www.omg.org/spec/BPMN/20100524/MODEL#\",\n\n    \"Flow\": {\n      \"@id\": \"sfauto:Flow\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DefinitionId\": {\n          \"@id\": \"sfauto:definitionId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DeveloperName\": {\n          \"@id\": \"sfauto:developerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"MasterLabel\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n\
  \        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ProcessType\": {\n          \"@id\": \"sfauto:processType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TriggerType\": {\n          \"@id\": \"sfauto:triggerType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"TriggerObject\": {\n          \"@id\": \"sfauto:triggerObject\",\n          \"@type\": \"xsd:string\"\n        },\n        \"RecordTriggerType\": {\n          \"@id\": \"sfauto:recordTriggerType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Status\": {\n          \"@id\": \"sfauto:flowStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"VersionNumber\": {\n          \"@id\": \"sfauto:versionNumber\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"ApiVersion\": {\n          \"@id\": \"sf:apiVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"\
  RunInMode\": {\n          \"@id\": \"sfauto:runInMode\",\n          \"@type\": \"xsd:string\"\n        },\n        \"IsTemplate\": {\n          \"@id\": \"sfauto:isTemplate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"CreatedDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"LastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"CreatedById\": {\n          \"@id\": \"sfauto:createdBy\",\n          \"@type\": \"@id\"\n        },\n        \"LastModifiedById\": {\n          \"@id\": \"sfauto:lastModifiedBy\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FlowDefinition\": {\n      \"@id\": \"sfauto:FlowDefinition\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"Id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"DeveloperName\": {\n          \"@id\": \"sfauto:developerName\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"MasterLabel\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ActiveVersionId\": {\n          \"@id\": \"sfauto:activeVersion\",\n          \"@type\": \"@id\"\n        },\n        \"LatestVersionId\": {\n          \"@id\": \"sfauto:latestVersion\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FlowElement\": {\n      \"@id\": \"sfauto:FlowElement\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"sfauto:elementName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"elementType\": {\n          \"@id\": \"sfauto:elementType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"connector\": {\n          \"@id\": \"sfauto:connector\",\n          \"@type\": \"@id\"\n        },\n        \"faultConnector\": {\n          \"@id\": \"sfauto:faultConnector\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FlowVariable\": {\n      \"@id\": \"sfauto:FlowVariable\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"sfauto:variableName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dataType\": {\n          \"@id\": \"sfauto:dataType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isCollection\": {\n          \"@id\": \"sfauto:isCollection\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isInput\": {\n          \"@id\": \"sfauto:isInput\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isOutput\": {\n          \"@id\": \"\
  sfauto:isOutput\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"objectType\": {\n          \"@id\": \"sfauto:objectType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"FlowDecision\": {\n      \"@id\": \"sfauto:FlowDecision\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"sfauto:elementName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rules\": {\n          \"@id\": \"sfauto:rules\",\n          \"@type\": \"@id\"\n        },\n        \"defaultConnector\": {\n          \"@id\": \"sfauto:defaultConnector\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"FlowActionCall\": {\n      \"@id\": \"sfauto:FlowActionCall\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"sfauto:elementName\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionName\": {\n          \"@id\": \"sfauto:actionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actionType\": {\n          \"@id\": \"sfauto:actionType\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"WorkflowRule\": {\n      \"@id\": \"sfauto:WorkflowRule\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"sfauto:triggerObject\",\n          \"@type\": \"xsd:string\"\n        },\n        \"actions\": {\n          \"@id\": \"sfauto:actions\",\n\
  \          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ApprovalProcess\": {\n      \"@id\": \"sfauto:ApprovalProcess\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"sfauto:triggerObject\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sortOrder\": {\n          \"@id\": \"sfauto:sortOrder\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"PlatformEvent\": {\n      \"@id\": \"sfauto:PlatformEvent\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\"\
  : {\n          \"@id\": \"schema:name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fields\": {\n          \"@id\": \"sfauto:eventFields\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"ChangeDataCaptureEvent\": {\n      \"@id\": \"sfauto:ChangeDataCaptureEvent\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"entityName\": {\n          \"@id\": \"sfauto:entityName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"changeType\": {\n          \"@id\": \"sfauto:changeType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"recordIds\": {\n          \"@id\": \"sfauto:recordIds\"\n        },\n        \"commitTimestamp\": {\n          \"@id\": \"sfauto:commitTimestamp\",\n          \"@type\": \"xsd:long\"\n        },\n        \"commitUser\": {\n          \"@id\": \"sfauto:commitUser\",\n          \"\
  @type\": \"@id\"\n        },\n        \"changedFields\": {\n          \"@id\": \"sfauto:changedFields\"\n        },\n        \"transactionKey\": {\n          \"@id\": \"sfauto:transactionKey\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"BulkJob\": {\n      \"@id\": \"sf:BulkJob\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sf:jobId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"operation\": {\n          \"@id\": \"sf:operation\",\n          \"@type\": \"xsd:string\"\n        },\n        \"object\": {\n          \"@id\": \"sf:sobjectType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"state\": {\n          \"@id\": \"sf:jobState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"systemModstamp\": {\n          \"@id\": \"dcterms:modified\",\n       \
  \   \"@type\": \"xsd:dateTime\"\n        },\n        \"numberRecordsProcessed\": {\n          \"@id\": \"sf:numberRecordsProcessed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"numberRecordsFailed\": {\n          \"@id\": \"sf:numberRecordsFailed\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalProcessingTime\": {\n          \"@id\": \"sf:totalProcessingTime\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"InvocableAction\": {\n      \"@id\": \"sfauto:InvocableAction\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"name\": {\n          \"@id\": \"sfauto:actionName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"type\": {\n          \"@id\": \"sfauto:actionType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n \
  \         \"@type\": \"xsd:string\"\n        },\n        \"inputs\": {\n          \"@id\": \"sfauto:inputs\",\n          \"@type\": \"@id\"\n        },\n        \"outputs\": {\n          \"@id\": \"sfauto:outputs\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"PushTopic\": {\n      \"@id\": \"sfauto:PushTopic\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"Name\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"Query\": {\n          \"@id\": \"sfauto:pushTopicQuery\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ApiVersion\": {\n          \"@id\": \"sf:apiVersion\",\n          \"@type\": \"xsd:decimal\"\n        },\n        \"IsActive\": {\n          \"@id\": \"sfauto:isActive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"NotifyForFields\": {\n          \"@id\": \"sfauto:notifyForFields\",\n          \"@type\": \"xsd:string\"\n        },\n        \"NotifyForOperationCreate\"\
  : {\n          \"@id\": \"sfauto:notifyOnCreate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"NotifyForOperationUpdate\": {\n          \"@id\": \"sfauto:notifyOnUpdate\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"NotifyForOperationDelete\": {\n          \"@id\": \"sfauto:notifyOnDelete\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"CompositeRequest\": {\n      \"@id\": \"sfauto:CompositeRequest\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"allOrNone\": {\n          \"@id\": \"sfauto:allOrNone\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"compositeRequest\": {\n          \"@id\": \"sfauto:subrequests\",\n          \"@type\": \"@id\"\n        }\n      }\n    },\n\n    \"AnalyticsDashboard\": {\n      \"@id\": \"sfauto:AnalyticsDashboard\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n\
  \        \"name\": {\n          \"@id\": \"sfauto:developerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AnalyticsDataset\": {\n      \"@id\": \"sfauto:AnalyticsDataset\",\n      \"@type\": \"@id\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"sf:id\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"sfauto:developerName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"label\": {\n          \"@id\": \"rdfs:label\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"schema:description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"datasetType\": {\n          \"@id\": \"sfauto:datasetType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salesforce-automation/refs/heads/main/json-ld/salesforce-automation-context.jsonld
tags:
- Automation
- Cloud
- CRM
- Enterprise
- Sales
- JSON-LD
- Linked Data
- Semantic Web
---
