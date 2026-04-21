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
