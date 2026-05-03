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
class_count: 27
classes:
- AddQueueItemRequest
- Asset
- Job
- ODataAlertCollection
- ODataAssetCollection
- ODataFolderCollection
- ODataJobCollection
- ODataMachineCollection
- ODataPackageCollection
- ODataProcessCollection
- ODataQueueDefinitionCollection
- ODataQueueItemCollection
- ODataRobotCollection
- ODataRoleCollection
- ODataScheduleCollection
- ODataStorageBucketCollection
- ODataUserCollection
- ODataWebhookCollection
- QueueDefinition
- QueueItemData
- QueueItem
- RobotRef
- StartInfo
- StartJobsRequest
- StopJobRequest
- WebhookEventType
- Webhook
context_file: json-ld/uipath-orchestrator-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-orchestrator-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Uipath Orchestrator from UiPath.
layout: jsonld
name: Uipath Orchestrator Context
namespaces:
- prefix: uipath
  uri: https://uipath.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: itemData
  type: string
- container: ''
  name: Id
  type: integer
- container: ''
  name: Name
  type: string
- container: ''
  name: ValueType
  type: string
- container: ''
  name: StringValue
  type: string
- container: ''
  name: IntValue
  type: integer
- container: ''
  name: BoolValue
  type: boolean
- container: ''
  name: CredentialUsername
  type: string
- container: ''
  name: CredentialPassword
  type: string
- container: ''
  name: Description
  type: string
- container: ''
  name: OrganizationUnitId
  type: integer
- container: ''
  name: Key
  type: string
- container: ''
  name: ReleaseName
  type: string
- container: ''
  name: ProcessVersion
  type: string
- container: ''
  name: State
  type: string
- container: ''
  name: Source
  type: string
- container: ''
  name: StartTime
  type: dateTime
- container: ''
  name: EndTime
  type: dateTime
- container: ''
  name: CreationTime
  type: dateTime
- container: ''
  name: Info
  type: string
- container: ''
  name: HostMachineName
  type: string
- container: ''
  name: Robot
  type: string
- container: ''
  name: InputArguments
  type: string
- container: ''
  name: OutputArguments
  type: string
- container: set
  name: value
  type: reference
- container: ''
  name: NotificationName
  type: string
- container: ''
  name: AlertSeverity
  type: string
- container: ''
  name: Message
  type: string
- container: ''
  name: Component
  type: string
- container: ''
  name: DisplayName
  type: string
- container: ''
  name: FullyQualifiedName
  type: string
- container: ''
  name: FolderType
  type: string
- container: ''
  name: Type
  type: string
- container: ''
  name: LicenseKey
  type: string
- container: ''
  name: Title
  type: string
- container: ''
  name: Version
  type: string
- container: ''
  name: Published
  type: dateTime
- container: ''
  name: MachineName
  type: string
- container: ''
  name: IsConnected
  type: boolean
- container: ''
  name: IsStatic
  type: boolean
- container: ''
  name: ReleaseId
  type: integer
- container: ''
  name: Enabled
  type: boolean
- container: ''
  name: StartProcessCron
  type: string
- container: ''
  name: StorageProvider
  type: string
- container: ''
  name: UserName
  type: string
- container: ''
  name: EmailAddress
  type: string
- container: ''
  name: IsActive
  type: boolean
- container: ''
  name: MaxNumberOfRetries
  type: integer
- container: ''
  name: AcceptAutomaticallyRetry
  type: boolean
- container: ''
  name: EnforceUniqueReference
  type: boolean
- container: ''
  name: Priority
  type: string
- container: ''
  name: SpecificContent
  type: reference
- container: ''
  name: Reference
  type: string
- container: ''
  name: DueDate
  type: dateTime
- container: ''
  name: PostponeDate
  type: dateTime
- container: ''
  name: QueueDefinitionId
  type: integer
- container: ''
  name: Status
  type: string
- container: ''
  name: ReviewStatus
  type: string
- container: ''
  name: Output
  type: reference
- container: ''
  name: StartProcessing
  type: dateTime
- container: ''
  name: EndProcessing
  type: dateTime
- container: ''
  name: RetryNumber
  type: integer
- container: ''
  name: MachineId
  type: integer
- container: ''
  name: ReleaseKey
  type: string
- container: ''
  name: Strategy
  type: string
- container: set
  name: RobotIds
  type: string
- container: ''
  name: NoOfRobots
  type: integer
- container: ''
  name: JobPriority
  type: string
- container: ''
  name: startInfo
  type: string
- container: ''
  name: jobId
  type: integer
- container: ''
  name: strategy
  type: string
- container: ''
  name: EventType
  type: string
- container: ''
  name: Url
  type: reference
- container: ''
  name: Secret
  type: string
- container: ''
  name: SubscribeToAllEvents
  type: boolean
- container: ''
  name: AllowInsecureSsl
  type: boolean
- container: set
  name: Events
  type: string
property_count: 77
provider_name: UiPath
provider_slug: uipath
slug: uipath-orchestrator-context
source_filename: uipath-orchestrator-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"uipath\": \"https://uipath.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AddQueueItemRequest\": \"uipath:AddQueueItemRequest\",\n    \"Asset\": \"uipath:Asset\",\n    \"Job\": \"uipath:Job\",\n    \"ODataAlertCollection\": \"uipath:ODataAlertCollection\",\n    \"ODataAssetCollection\": \"uipath:ODataAssetCollection\",\n    \"ODataFolderCollection\": \"uipath:ODataFolderCollection\",\n    \"ODataJobCollection\": \"uipath:ODataJobCollection\",\n    \"ODataMachineCollection\": \"uipath:ODataMachineCollection\",\n    \"ODataPackageCollection\": \"uipath:ODataPackageCollection\",\n    \"ODataProcessCollection\": \"uipath:ODataProcessCollection\",\n    \"ODataQueueDefinitionCollection\": \"uipath:ODataQueueDefinitionCollection\",\n    \"ODataQueueItemCollection\": \"uipath:ODataQueueItemCollection\",\n    \"ODataRobotCollection\"\
  : \"uipath:ODataRobotCollection\",\n    \"ODataRoleCollection\": \"uipath:ODataRoleCollection\",\n    \"ODataScheduleCollection\": \"uipath:ODataScheduleCollection\",\n    \"ODataStorageBucketCollection\": \"uipath:ODataStorageBucketCollection\",\n    \"ODataUserCollection\": \"uipath:ODataUserCollection\",\n    \"ODataWebhookCollection\": \"uipath:ODataWebhookCollection\",\n    \"QueueDefinition\": \"uipath:QueueDefinition\",\n    \"QueueItemData\": \"uipath:QueueItemData\",\n    \"QueueItem\": \"uipath:QueueItem\",\n    \"RobotRef\": \"uipath:RobotRef\",\n    \"StartInfo\": \"uipath:StartInfo\",\n    \"StartJobsRequest\": \"uipath:StartJobsRequest\",\n    \"StopJobRequest\": \"uipath:StopJobRequest\",\n    \"WebhookEventType\": \"uipath:WebhookEventType\",\n    \"Webhook\": \"uipath:Webhook\",\n    \"itemData\": {\n      \"@id\": \"uipath:itemData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Id\": {\n      \"@id\": \"uipath:Id\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"\
  Name\": {\n      \"@id\": \"uipath:Name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ValueType\": {\n      \"@id\": \"uipath:ValueType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StringValue\": {\n      \"@id\": \"uipath:StringValue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IntValue\": {\n      \"@id\": \"uipath:IntValue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"BoolValue\": {\n      \"@id\": \"uipath:BoolValue\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"CredentialUsername\": {\n      \"@id\": \"uipath:CredentialUsername\",\n      \"@type\": \"xsd:string\"\n    },\n    \"CredentialPassword\": {\n      \"@id\": \"uipath:CredentialPassword\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Description\": {\n      \"@id\": \"uipath:Description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OrganizationUnitId\": {\n      \"@id\": \"uipath:OrganizationUnitId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Key\": {\n      \"@id\": \"uipath:Key\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"ReleaseName\": {\n      \"@id\": \"uipath:ReleaseName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ProcessVersion\": {\n      \"@id\": \"uipath:ProcessVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"State\": {\n      \"@id\": \"uipath:State\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Source\": {\n      \"@id\": \"uipath:Source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StartTime\": {\n      \"@id\": \"uipath:StartTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndTime\": {\n      \"@id\": \"uipath:EndTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"CreationTime\": {\n      \"@id\": \"uipath:CreationTime\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Info\": {\n      \"@id\": \"uipath:Info\",\n      \"@type\": \"xsd:string\"\n    },\n    \"HostMachineName\": {\n      \"@id\": \"uipath:HostMachineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Robot\": {\n      \"@id\": \"uipath:Robot\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"InputArguments\": {\n      \"@id\": \"uipath:InputArguments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"OutputArguments\": {\n      \"@id\": \"uipath:OutputArguments\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"uipath:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"NotificationName\": {\n      \"@id\": \"uipath:NotificationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"AlertSeverity\": {\n      \"@id\": \"uipath:AlertSeverity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Message\": {\n      \"@id\": \"uipath:Message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Component\": {\n      \"@id\": \"uipath:Component\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DisplayName\": {\n      \"@id\": \"uipath:DisplayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"FullyQualifiedName\": {\n      \"@id\": \"uipath:FullyQualifiedName\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"FolderType\": {\n      \"@id\": \"uipath:FolderType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@odata.context\": {\n      \"@id\": \"uipath:@odata.context\",\n      \"@type\": \"xsd:string\"\n    },\n    \"@odata.count\": {\n      \"@id\": \"uipath:@odata.count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Type\": {\n      \"@id\": \"uipath:Type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"LicenseKey\": {\n      \"@id\": \"uipath:LicenseKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Title\": {\n      \"@id\": \"uipath:Title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Version\": {\n      \"@id\": \"uipath:Version\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Published\": {\n      \"@id\": \"uipath:Published\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"MachineName\": {\n      \"@id\": \"uipath:MachineName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsConnected\": {\n      \"@id\": \"uipath:IsConnected\"\
  ,\n      \"@type\": \"xsd:boolean\"\n    },\n    \"IsStatic\": {\n      \"@id\": \"uipath:IsStatic\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"ReleaseId\": {\n      \"@id\": \"uipath:ReleaseId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Enabled\": {\n      \"@id\": \"uipath:Enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"StartProcessCron\": {\n      \"@id\": \"uipath:StartProcessCron\",\n      \"@type\": \"xsd:string\"\n    },\n    \"StorageProvider\": {\n      \"@id\": \"uipath:StorageProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"UserName\": {\n      \"@id\": \"uipath:UserName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmailAddress\": {\n      \"@id\": \"uipath:EmailAddress\",\n      \"@type\": \"xsd:string\"\n    },\n    \"IsActive\": {\n      \"@id\": \"uipath:IsActive\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"MaxNumberOfRetries\": {\n      \"@id\": \"uipath:MaxNumberOfRetries\",\n      \"@type\": \"xsd:integer\"\n    },\n\
  \    \"AcceptAutomaticallyRetry\": {\n      \"@id\": \"uipath:AcceptAutomaticallyRetry\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"EnforceUniqueReference\": {\n      \"@id\": \"uipath:EnforceUniqueReference\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Priority\": {\n      \"@id\": \"uipath:Priority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SpecificContent\": {\n      \"@id\": \"uipath:SpecificContent\",\n      \"@type\": \"@id\"\n    },\n    \"Reference\": {\n      \"@id\": \"uipath:Reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"DueDate\": {\n      \"@id\": \"uipath:DueDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"PostponeDate\": {\n      \"@id\": \"uipath:PostponeDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"QueueDefinitionId\": {\n      \"@id\": \"uipath:QueueDefinitionId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Status\": {\n      \"@id\": \"uipath:Status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ReviewStatus\"\
  : {\n      \"@id\": \"uipath:ReviewStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Output\": {\n      \"@id\": \"uipath:Output\",\n      \"@type\": \"@id\"\n    },\n    \"StartProcessing\": {\n      \"@id\": \"uipath:StartProcessing\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"EndProcessing\": {\n      \"@id\": \"uipath:EndProcessing\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"RetryNumber\": {\n      \"@id\": \"uipath:RetryNumber\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"MachineId\": {\n      \"@id\": \"uipath:MachineId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"ReleaseKey\": {\n      \"@id\": \"uipath:ReleaseKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Strategy\": {\n      \"@id\": \"uipath:Strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"RobotIds\": {\n      \"@id\": \"uipath:RobotIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"NoOfRobots\": {\n      \"@id\": \"uipath:NoOfRobots\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"JobPriority\": {\n      \"@id\": \"uipath:JobPriority\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startInfo\": {\n      \"@id\": \"uipath:startInfo\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobId\": {\n      \"@id\": \"uipath:jobId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"strategy\": {\n      \"@id\": \"uipath:strategy\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EventType\": {\n      \"@id\": \"uipath:EventType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Url\": {\n      \"@id\": \"uipath:Url\",\n      \"@type\": \"@id\"\n    },\n    \"Secret\": {\n      \"@id\": \"uipath:Secret\",\n      \"@type\": \"xsd:string\"\n    },\n    \"SubscribeToAllEvents\": {\n      \"@id\": \"uipath:SubscribeToAllEvents\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"AllowInsecureSsl\": {\n      \"@id\": \"uipath:AllowInsecureSsl\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"Events\": {\n      \"@id\": \"uipath:Events\"\
  ,\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/uipath/refs/heads/main/json-ld/uipath-orchestrator-context.jsonld
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
