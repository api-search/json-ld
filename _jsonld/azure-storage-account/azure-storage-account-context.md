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
source_filename: azure-storage-account-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurestorageaccount\": \"https://azure.microsoft.com/azure-storage-account/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountSasParameters\": \"azurestorageaccount:AccountSasParameters\",\n    \"ActiveDirectoryProperties\": \"azurestorageaccount:ActiveDirectoryProperties\",\n    \"AzureFilesIdentityBasedAuthentication\": \"azurestorageaccount:AzureFilesIdentityBasedAuthentication\",\n    \"BlobRestoreParameters\": \"azurestorageaccount:BlobRestoreParameters\",\n    \"BlobRestoreRange\": \"azurestorageaccount:BlobRestoreRange\",\n    \"BlobRestoreStatus\": \"azurestorageaccount:BlobRestoreStatus\",\n    \"CheckNameAvailabilityResult\": \"azurestorageaccount:CheckNameAvailabilityResult\",\n    \"CustomDomain\": \"azurestorageaccount:CustomDomain\",\n    \"DateAfterCreation\": \"azurestorageaccount:DateAfterCreation\"\
  ,\n    \"DateAfterModification\": \"azurestorageaccount:DateAfterModification\",\n    \"Dimension\": \"azurestorageaccount:Dimension\",\n    \"Encryption\": \"azurestorageaccount:Encryption\",\n    \"EncryptionService\": \"azurestorageaccount:EncryptionService\",\n    \"EncryptionServices\": \"azurestorageaccount:EncryptionServices\",\n    \"Endpoints\": \"azurestorageaccount:Endpoints\",\n    \"GeoReplicationStats\": \"azurestorageaccount:GeoReplicationStats\",\n    \"IPRule\": \"azurestorageaccount:IPRule\",\n    \"Identity\": \"azurestorageaccount:Identity\",\n    \"KeyVaultProperties\": \"azurestorageaccount:KeyVaultProperties\",\n    \"ListAccountSasResponse\": \"azurestorageaccount:ListAccountSasResponse\",\n    \"keyToSign\": {\n      \"@id\": \"azurestorageaccount:keyToSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedExpiry\": {\n      \"@id\": \"azurestorageaccount:signedExpiry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedIp\": {\n      \"@id\": \"azurestorageaccount:signedIp\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"signedPermission\": {\n      \"@id\": \"azurestorageaccount:signedPermission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedProtocol\": {\n      \"@id\": \"azurestorageaccount:signedProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedResourceTypes\": {\n      \"@id\": \"azurestorageaccount:signedResourceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedServices\": {\n      \"@id\": \"azurestorageaccount:signedServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedStart\": {\n      \"@id\": \"azurestorageaccount:signedStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureStorageSid\": {\n      \"@id\": \"azurestorageaccount:azureStorageSid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainGuid\": {\n      \"@id\": \"azurestorageaccount:domainGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainName\": {\n      \"@id\": \"azurestorageaccount:domainName\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"domainSid\": {\n      \"@id\": \"azurestorageaccount:domainSid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forestName\": {\n      \"@id\": \"azurestorageaccount:forestName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"netBiosDomainName\": {\n      \"@id\": \"azurestorageaccount:netBiosDomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeDirectoryProperties\": {\n      \"@id\": \"azurestorageaccount:activeDirectoryProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryServiceOptions\": {\n      \"@id\": \"azurestorageaccount:directoryServiceOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blobRanges\": {\n      \"@id\": \"azurestorageaccount:blobRanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeToRestore\": {\n      \"@id\": \"azurestorageaccount:timeToRestore\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endRange\": {\n      \"@id\": \"azurestorageaccount:endRange\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"startRange\": {\n      \"@id\": \"azurestorageaccount:startRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureReason\": {\n      \"@id\": \"azurestorageaccount:failureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"azurestorageaccount:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restoreId\": {\n      \"@id\": \"azurestorageaccount:restoreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azurestorageaccount:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"azurestorageaccount:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameAvailable\": {\n      \"@id\": \"azurestorageaccount:nameAvailable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"azurestorageaccount:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"\
  useSubDomainName\": {\n      \"@id\": \"azurestorageaccount:useSubDomainName\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"daysAfterCreationGreaterThan\": {\n      \"@id\": \"azurestorageaccount:daysAfterCreationGreaterThan\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"daysAfterModificationGreaterThan\": {\n      \"@id\": \"azurestorageaccount:daysAfterModificationGreaterThan\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"displayName\": {\n      \"@id\": \"azurestorageaccount:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keySource\": {\n      \"@id\": \"azurestorageaccount:keySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyvaultproperties\": {\n      \"@id\": \"azurestorageaccount:keyvaultproperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"azurestorageaccount:services\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"azurestorageaccount:enabled\",\n      \"@type\": \"\
  xsd:boolean\"\n    },\n    \"keyType\": {\n      \"@id\": \"azurestorageaccount:keyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEnabledTime\": {\n      \"@id\": \"azurestorageaccount:lastEnabledTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blob\": {\n      \"@id\": \"azurestorageaccount:blob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"azurestorageaccount:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queue\": {\n      \"@id\": \"azurestorageaccount:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table\": {\n      \"@id\": \"azurestorageaccount:table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dfs\": {\n      \"@id\": \"azurestorageaccount:dfs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internetEndpoints\": {\n      \"@id\": \"azurestorageaccount:internetEndpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"microsoftEndpoints\": {\n      \"@id\": \"azurestorageaccount:microsoftEndpoints\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"web\": {\n      \"@id\": \"azurestorageaccount:web\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canFailover\": {\n      \"@id\": \"azurestorageaccount:canFailover\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSyncTime\": {\n      \"@id\": \"azurestorageaccount:lastSyncTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"azurestorageaccount:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurestorageaccount:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\": {\n      \"@id\": \"azurestorageaccount:principalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"azurestorageaccount:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurestorageaccount:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyname\": {\n      \"@id\": \"azurestorageaccount:keyname\"\
  ,\n      \"@type\": \"xsd:string\"\n    },\n    \"keyvaulturi\": {\n      \"@id\": \"azurestorageaccount:keyvaulturi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyversion\": {\n      \"@id\": \"azurestorageaccount:keyversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountSasToken\": {\n      \"@id\": \"azurestorageaccount:accountSasToken\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-account/refs/heads/main/json-ld/azure-storage-account-context.jsonld
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
