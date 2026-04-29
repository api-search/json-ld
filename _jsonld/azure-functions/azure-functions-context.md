---
class_count: 21
classes:
- ApiKVReference
- ApplicationLogsConfig
- AzureBlobStorageApplicationLogsConfig
- AzureBlobStorageHttpLogsConfig
- AzureStorageInfoValue
- AzureStoragePropertyDictionaryResource
- AzureTableStorageApplicationLogsConfig
- BackupItem
- BackupItemCollection
- BackupRequest
- BackupSchedule
- ConnStringValueTypePair
- ConnectionStringDictionary
- ContainerCpuStatistics
- ContainerCpuUsage
- ContainerInfo
- ContainerMemoryStatistics
- ContainerNetworkInterfaceStatistics
- ContainerThrottlingData
- ContinuousWebJob
- name
context_file: json-ld/azure-functions-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/json-ld/azure-functions-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Functions from Azure Functions.
layout: jsonld
name: Azure Functions Context
namespaces:
- prefix: azurefunctions
  uri: https://azure.microsoft.com/azure-functions/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: details
  type: string
- container: ''
  name: identityType
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: reference
  type: string
- container: ''
  name: secretName
  type: string
- container: ''
  name: secretVersion
  type: string
- container: ''
  name: source
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: vaultName
  type: string
- container: ''
  name: azureBlobStorage
  type: string
- container: ''
  name: azureTableStorage
  type: string
- container: ''
  name: fileSystem
  type: string
- container: ''
  name: level
  type: string
- container: ''
  name: retentionInDays
  type: integer
- container: ''
  name: sasUrl
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: accessKey
  type: string
- container: ''
  name: accountName
  type: string
- container: ''
  name: mountPath
  type: string
- container: ''
  name: shareName
  type: string
- container: ''
  name: state
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: properties
  type: reference
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: frequencyInterval
  type: integer
- container: ''
  name: frequencyUnit
  type: string
- container: ''
  name: keepAtLeastOneBackup
  type: boolean
- container: ''
  name: lastExecutionTime
  type: string
- container: ''
  name: retentionPeriodInDays
  type: integer
- container: ''
  name: startTime
  type: string
- container: ''
  name: cpuUsage
  type: string
- container: ''
  name: onlineCpuCount
  type: integer
- container: ''
  name: systemCpuUsage
  type: integer
- container: ''
  name: throttlingData
  type: string
- container: ''
  name: kernelModeUsage
  type: integer
- container: set
  name: perCpuUsage
  type: string
- container: ''
  name: totalUsage
  type: integer
- container: ''
  name: userModeUsage
  type: integer
- container: ''
  name: currentCpuStats
  type: string
- container: ''
  name: currentTimeStamp
  type: string
- container: ''
  name: eth0
  type: string
- container: ''
  name: id
  type: string
- container: ''
  name: memoryStats
  type: string
- container: ''
  name: previousCpuStats
  type: string
- container: ''
  name: previousTimeStamp
  type: string
- container: ''
  name: limit
  type: integer
- container: ''
  name: maxUsage
  type: integer
- container: ''
  name: usage
  type: integer
- container: ''
  name: rxBytes
  type: integer
- container: ''
  name: rxDropped
  type: integer
- container: ''
  name: rxErrors
  type: integer
- container: ''
  name: rxPackets
  type: integer
- container: ''
  name: txBytes
  type: integer
- container: ''
  name: txDropped
  type: integer
- container: ''
  name: txErrors
  type: integer
- container: ''
  name: txPackets
  type: integer
- container: ''
  name: periods
  type: integer
- container: ''
  name: throttledPeriods
  type: integer
- container: ''
  name: throttledTime
  type: integer
property_count: 60
provider_name: Azure Functions
provider_slug: azure-functions
slug: azure-functions-context
source_filename: azure-functions-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurefunctions\": \"https://azure.microsoft.com/azure-functions/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiKVReference\": \"azurefunctions:ApiKVReference\",\n    \"ApplicationLogsConfig\": \"azurefunctions:ApplicationLogsConfig\",\n    \"AzureBlobStorageApplicationLogsConfig\": \"azurefunctions:AzureBlobStorageApplicationLogsConfig\",\n    \"AzureBlobStorageHttpLogsConfig\": \"azurefunctions:AzureBlobStorageHttpLogsConfig\",\n    \"AzureStorageInfoValue\": \"azurefunctions:AzureStorageInfoValue\",\n    \"AzureStoragePropertyDictionaryResource\": \"azurefunctions:AzureStoragePropertyDictionaryResource\",\n    \"AzureTableStorageApplicationLogsConfig\": \"azurefunctions:AzureTableStorageApplicationLogsConfig\",\n    \"BackupItem\": \"azurefunctions:BackupItem\",\n    \"BackupItemCollection\": \"azurefunctions:BackupItemCollection\"\
  ,\n    \"BackupRequest\": \"azurefunctions:BackupRequest\",\n    \"BackupSchedule\": \"azurefunctions:BackupSchedule\",\n    \"ConnStringValueTypePair\": \"azurefunctions:ConnStringValueTypePair\",\n    \"ConnectionStringDictionary\": \"azurefunctions:ConnectionStringDictionary\",\n    \"ContainerCpuStatistics\": \"azurefunctions:ContainerCpuStatistics\",\n    \"ContainerCpuUsage\": \"azurefunctions:ContainerCpuUsage\",\n    \"ContainerInfo\": \"azurefunctions:ContainerInfo\",\n    \"ContainerMemoryStatistics\": \"azurefunctions:ContainerMemoryStatistics\",\n    \"ContainerNetworkInterfaceStatistics\": \"azurefunctions:ContainerNetworkInterfaceStatistics\",\n    \"ContainerThrottlingData\": \"azurefunctions:ContainerThrottlingData\",\n    \"ContinuousWebJob\": \"azurefunctions:ContinuousWebJob\",\n    \"details\": {\n      \"@id\": \"azurefunctions:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"identityType\": {\n      \"@id\": \"azurefunctions:identityType\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azurefunctions:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"azurefunctions:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\": {\n      \"@id\": \"azurefunctions:secretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretVersion\": {\n      \"@id\": \"azurefunctions:secretVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"azurefunctions:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azurefunctions:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vaultName\": {\n      \"@id\": \"azurefunctions:vaultName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureBlobStorage\": {\n      \"@id\": \"azurefunctions:azureBlobStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureTableStorage\": {\n      \"@id\": \"azurefunctions:azureTableStorage\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"fileSystem\": {\n      \"@id\": \"azurefunctions:fileSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"azurefunctions:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionInDays\": {\n      \"@id\": \"azurefunctions:retentionInDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sasUrl\": {\n      \"@id\": \"azurefunctions:sasUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"azurefunctions:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"accessKey\": {\n      \"@id\": \"azurefunctions:accessKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"azurefunctions:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mountPath\": {\n      \"@id\": \"azurefunctions:mountPath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"shareName\": {\n      \"@id\": \"azurefunctions:shareName\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"state\": {\n      \"@id\": \"azurefunctions:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurefunctions:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"azurefunctions:properties\",\n      \"@type\": \"@id\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurefunctions:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurefunctions:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequencyInterval\": {\n      \"@id\": \"azurefunctions:frequencyInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"frequencyUnit\": {\n      \"@id\": \"azurefunctions:frequencyUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keepAtLeastOneBackup\": {\n      \"@id\": \"azurefunctions:keepAtLeastOneBackup\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastExecutionTime\": {\n      \"@id\": \"azurefunctions:lastExecutionTime\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionPeriodInDays\": {\n      \"@id\": \"azurefunctions:retentionPeriodInDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"azurefunctions:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuUsage\": {\n      \"@id\": \"azurefunctions:cpuUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onlineCpuCount\": {\n      \"@id\": \"azurefunctions:onlineCpuCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"systemCpuUsage\": {\n      \"@id\": \"azurefunctions:systemCpuUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttlingData\": {\n      \"@id\": \"azurefunctions:throttlingData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kernelModeUsage\": {\n      \"@id\": \"azurefunctions:kernelModeUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"perCpuUsage\": {\n      \"@id\": \"azurefunctions:perCpuUsage\",\n      \"@container\": \"@set\",\n      \"@type\": \"\
  xsd:string\"\n    },\n    \"totalUsage\": {\n      \"@id\": \"azurefunctions:totalUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userModeUsage\": {\n      \"@id\": \"azurefunctions:userModeUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentCpuStats\": {\n      \"@id\": \"azurefunctions:currentCpuStats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentTimeStamp\": {\n      \"@id\": \"azurefunctions:currentTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eth0\": {\n      \"@id\": \"azurefunctions:eth0\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"azurefunctions:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryStats\": {\n      \"@id\": \"azurefunctions:memoryStats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"previousCpuStats\": {\n      \"@id\": \"azurefunctions:previousCpuStats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousTimeStamp\": {\n      \"@id\"\
  : \"azurefunctions:previousTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"azurefunctions:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxUsage\": {\n      \"@id\": \"azurefunctions:maxUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usage\": {\n      \"@id\": \"azurefunctions:usage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxBytes\": {\n      \"@id\": \"azurefunctions:rxBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxDropped\": {\n      \"@id\": \"azurefunctions:rxDropped\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxErrors\": {\n      \"@id\": \"azurefunctions:rxErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxPackets\": {\n      \"@id\": \"azurefunctions:rxPackets\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txBytes\": {\n      \"@id\": \"azurefunctions:txBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txDropped\": {\n      \"@id\": \"azurefunctions:txDropped\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"txErrors\": {\n      \"@id\": \"azurefunctions:txErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txPackets\": {\n      \"@id\": \"azurefunctions:txPackets\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"periods\": {\n      \"@id\": \"azurefunctions:periods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttledPeriods\": {\n      \"@id\": \"azurefunctions:throttledPeriods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttledTime\": {\n      \"@id\": \"azurefunctions:throttledTime\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-functions/refs/heads/main/json-ld/azure-functions-context.jsonld
tags:
- Cloud
- Compute
- Event-Driven
- Functions
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
