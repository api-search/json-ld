---
class_count: 21
classes:
- AccountSasParameters
- ActiveDirectoryProperties
- AzureFilesIdentityBasedAuthentication
- BlobRestoreParameters
- BlobRestoreRange
- BlobRestoreStatus
- CheckNameAvailabilityResult
- CustomDomain
- DateAfterCreation
- DateAfterModification
- Dimension
- Encryption
- EncryptionService
- EncryptionServices
- Endpoints
- GeoReplicationStats
- IPRule
- Identity
- KeyVaultProperties
- ListAccountSasResponse
- name
context_file: json-ld/azure-storage-account-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/json-ld/azure-storage-account-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Storage Account from Azure Storage Account.
layout: jsonld
name: Azure Storage Account Context
namespaces:
- prefix: azurestorageaccount
  uri: https://azure.microsoft.com/azure-storage-account/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: keyToSign
  type: string
- container: ''
  name: signedExpiry
  type: string
- container: ''
  name: signedIp
  type: string
- container: ''
  name: signedPermission
  type: string
- container: ''
  name: signedProtocol
  type: string
- container: ''
  name: signedResourceTypes
  type: string
- container: ''
  name: signedServices
  type: string
- container: ''
  name: signedStart
  type: string
- container: ''
  name: azureStorageSid
  type: string
- container: ''
  name: domainGuid
  type: string
- container: ''
  name: domainName
  type: string
- container: ''
  name: domainSid
  type: string
- container: ''
  name: forestName
  type: string
- container: ''
  name: netBiosDomainName
  type: string
- container: ''
  name: activeDirectoryProperties
  type: string
- container: ''
  name: directoryServiceOptions
  type: string
- container: set
  name: blobRanges
  type: string
- container: ''
  name: timeToRestore
  type: string
- container: ''
  name: endRange
  type: string
- container: ''
  name: startRange
  type: string
- container: ''
  name: failureReason
  type: string
- container: ''
  name: parameters
  type: string
- container: ''
  name: restoreId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: message
  type: string
- container: ''
  name: nameAvailable
  type: boolean
- container: ''
  name: reason
  type: string
- container: ''
  name: useSubDomainName
  type: boolean
- container: ''
  name: daysAfterCreationGreaterThan
  type: decimal
- container: ''
  name: daysAfterModificationGreaterThan
  type: decimal
- container: ''
  name: displayName
  type: string
- container: ''
  name: keySource
  type: string
- container: ''
  name: keyvaultproperties
  type: string
- container: ''
  name: services
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: keyType
  type: string
- container: ''
  name: lastEnabledTime
  type: string
- container: ''
  name: blob
  type: string
- container: ''
  name: file
  type: string
- container: ''
  name: queue
  type: string
- container: ''
  name: table
  type: string
- container: ''
  name: dfs
  type: string
- container: ''
  name: internetEndpoints
  type: string
- container: ''
  name: microsoftEndpoints
  type: string
- container: ''
  name: web
  type: string
- container: ''
  name: canFailover
  type: boolean
- container: ''
  name: lastSyncTime
  type: string
- container: ''
  name: action
  type: string
- container: ''
  name: value
  type: string
- container: ''
  name: principalId
  type: string
- container: ''
  name: tenantId
  type: string
- container: ''
  name: type
  type: string
- container: ''
  name: keyname
  type: string
- container: ''
  name: keyvaulturi
  type: string
- container: ''
  name: keyversion
  type: string
- container: ''
  name: accountSasToken
  type: string
property_count: 56
provider_name: Azure Storage Account
provider_slug: azure-storage-account
slug: azure-storage-account-context
tags:
- Azure
- Blob Storage
- Cloud Storage
- File Storage
- Microsoft
- Storage
- JSON-LD
- Linked Data
- Semantic Web
---
