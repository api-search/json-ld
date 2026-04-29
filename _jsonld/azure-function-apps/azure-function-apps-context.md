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
context_file: json-ld/azure-function-apps-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/json-ld/azure-function-apps-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Function Apps from Azure Function Apps.
layout: jsonld
name: Azure Function Apps Context
namespaces:
- prefix: azurefunctionapps
  uri: https://azure.microsoft.com/azure-function-apps/schema/
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
provider_name: Azure Function Apps
provider_slug: azure-function-apps
slug: azure-function-apps-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurefunctionapps\": \"https://azure.microsoft.com/azure-function-apps/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApiKVReference\": \"azurefunctionapps:ApiKVReference\",\n    \"ApplicationLogsConfig\": \"azurefunctionapps:ApplicationLogsConfig\",\n    \"AzureBlobStorageApplicationLogsConfig\": \"azurefunctionapps:AzureBlobStorageApplicationLogsConfig\",\n    \"AzureBlobStorageHttpLogsConfig\": \"azurefunctionapps:AzureBlobStorageHttpLogsConfig\",\n    \"AzureStorageInfoValue\": \"azurefunctionapps:AzureStorageInfoValue\",\n    \"AzureStoragePropertyDictionaryResource\": \"azurefunctionapps:AzureStoragePropertyDictionaryResource\",\n    \"AzureTableStorageApplicationLogsConfig\": \"azurefunctionapps:AzureTableStorageApplicationLogsConfig\",\n    \"BackupItem\": \"azurefunctionapps:BackupItem\",\n    \"BackupItemCollection\"\
  : \"azurefunctionapps:BackupItemCollection\",\n    \"BackupRequest\": \"azurefunctionapps:BackupRequest\",\n    \"BackupSchedule\": \"azurefunctionapps:BackupSchedule\",\n    \"ConnStringValueTypePair\": \"azurefunctionapps:ConnStringValueTypePair\",\n    \"ConnectionStringDictionary\": \"azurefunctionapps:ConnectionStringDictionary\",\n    \"ContainerCpuStatistics\": \"azurefunctionapps:ContainerCpuStatistics\",\n    \"ContainerCpuUsage\": \"azurefunctionapps:ContainerCpuUsage\",\n    \"ContainerInfo\": \"azurefunctionapps:ContainerInfo\",\n    \"ContainerMemoryStatistics\": \"azurefunctionapps:ContainerMemoryStatistics\",\n    \"ContainerNetworkInterfaceStatistics\": \"azurefunctionapps:ContainerNetworkInterfaceStatistics\",\n    \"ContainerThrottlingData\": \"azurefunctionapps:ContainerThrottlingData\",\n    \"ContinuousWebJob\": \"azurefunctionapps:ContinuousWebJob\",\n    \"details\": {\n      \"@id\": \"azurefunctionapps:details\",\n      \"@type\": \"xsd:string\"\n    },\n    \"\
  identityType\": {\n      \"@id\": \"azurefunctionapps:identityType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azurefunctionapps:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reference\": {\n      \"@id\": \"azurefunctionapps:reference\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretName\": {\n      \"@id\": \"azurefunctionapps:secretName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"secretVersion\": {\n      \"@id\": \"azurefunctionapps:secretVersion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"source\": {\n      \"@id\": \"azurefunctionapps:source\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azurefunctionapps:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vaultName\": {\n      \"@id\": \"azurefunctionapps:vaultName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureBlobStorage\": {\n      \"@id\": \"azurefunctionapps:azureBlobStorage\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"azureTableStorage\": {\n      \"@id\": \"azurefunctionapps:azureTableStorage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"fileSystem\": {\n      \"@id\": \"azurefunctionapps:fileSystem\",\n      \"@type\": \"xsd:string\"\n    },\n    \"level\": {\n      \"@id\": \"azurefunctionapps:level\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionInDays\": {\n      \"@id\": \"azurefunctionapps:retentionInDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"sasUrl\": {\n      \"@id\": \"azurefunctionapps:sasUrl\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"azurefunctionapps:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"accessKey\": {\n      \"@id\": \"azurefunctionapps:accessKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountName\": {\n      \"@id\": \"azurefunctionapps:accountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"mountPath\": {\n      \"@id\": \"azurefunctionapps:mountPath\",\n    \
  \  \"@type\": \"xsd:string\"\n    },\n    \"shareName\": {\n      \"@id\": \"azurefunctionapps:shareName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"azurefunctionapps:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurefunctionapps:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"properties\": {\n      \"@id\": \"azurefunctionapps:properties\",\n      \"@type\": \"@id\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurefunctionapps:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurefunctionapps:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"frequencyInterval\": {\n      \"@id\": \"azurefunctionapps:frequencyInterval\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"frequencyUnit\": {\n      \"@id\": \"azurefunctionapps:frequencyUnit\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keepAtLeastOneBackup\": {\n      \"\
  @id\": \"azurefunctionapps:keepAtLeastOneBackup\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastExecutionTime\": {\n      \"@id\": \"azurefunctionapps:lastExecutionTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"retentionPeriodInDays\": {\n      \"@id\": \"azurefunctionapps:retentionPeriodInDays\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"startTime\": {\n      \"@id\": \"azurefunctionapps:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"cpuUsage\": {\n      \"@id\": \"azurefunctionapps:cpuUsage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onlineCpuCount\": {\n      \"@id\": \"azurefunctionapps:onlineCpuCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"systemCpuUsage\": {\n      \"@id\": \"azurefunctionapps:systemCpuUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttlingData\": {\n      \"@id\": \"azurefunctionapps:throttlingData\",\n      \"@type\": \"xsd:string\"\n    },\n    \"kernelModeUsage\": {\n      \"@id\": \"azurefunctionapps:kernelModeUsage\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"perCpuUsage\": {\n      \"@id\": \"azurefunctionapps:perCpuUsage\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalUsage\": {\n      \"@id\": \"azurefunctionapps:totalUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"userModeUsage\": {\n      \"@id\": \"azurefunctionapps:userModeUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"currentCpuStats\": {\n      \"@id\": \"azurefunctionapps:currentCpuStats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"currentTimeStamp\": {\n      \"@id\": \"azurefunctionapps:currentTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"eth0\": {\n      \"@id\": \"azurefunctionapps:eth0\",\n      \"@type\": \"xsd:string\"\n    },\n    \"id\": {\n      \"@id\": \"azurefunctionapps:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"memoryStats\": {\n      \"@id\": \"azurefunctionapps:memoryStats\",\n      \"@type\": \"xsd:string\"\n    },\n   \
  \ \"name\": \"schema:name\",\n    \"previousCpuStats\": {\n      \"@id\": \"azurefunctionapps:previousCpuStats\",\n      \"@type\": \"xsd:string\"\n    },\n    \"previousTimeStamp\": {\n      \"@id\": \"azurefunctionapps:previousTimeStamp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"limit\": {\n      \"@id\": \"azurefunctionapps:limit\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"maxUsage\": {\n      \"@id\": \"azurefunctionapps:maxUsage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"usage\": {\n      \"@id\": \"azurefunctionapps:usage\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxBytes\": {\n      \"@id\": \"azurefunctionapps:rxBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxDropped\": {\n      \"@id\": \"azurefunctionapps:rxDropped\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxErrors\": {\n      \"@id\": \"azurefunctionapps:rxErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"rxPackets\": {\n      \"@id\": \"azurefunctionapps:rxPackets\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"txBytes\": {\n      \"@id\": \"azurefunctionapps:txBytes\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txDropped\": {\n      \"@id\": \"azurefunctionapps:txDropped\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txErrors\": {\n      \"@id\": \"azurefunctionapps:txErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"txPackets\": {\n      \"@id\": \"azurefunctionapps:txPackets\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"periods\": {\n      \"@id\": \"azurefunctionapps:periods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttledPeriods\": {\n      \"@id\": \"azurefunctionapps:throttledPeriods\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"throttledTime\": {\n      \"@id\": \"azurefunctionapps:throttledTime\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-function-apps/refs/heads/main/json-ld/azure-function-apps-context.jsonld
tags:
- Azure
- Compute
- FaaS
- Functions
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
