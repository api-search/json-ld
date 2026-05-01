---
api_specs:
- filename: blob.json
  format: json
  label: Azure Storage Blob Service API
  slug: azure-storage-blob-service-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/data-plane/Microsoft.BlobStorage/stable/2023-11-03/blob.json
- filename: storage.json
  format: json
  label: Azure Storage Management API
  slug: azure-storage-management-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/Azure/azure-rest-api-specs/main/specification/storage/resource-manager/Microsoft.Storage/stable/2023-01-01/storage.json
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
context_file: json-ld/azure-storage-accounts-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/json-ld/azure-storage-accounts-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Storage Accounts from Azure Storage Accounts.
layout: jsonld
name: Azure Storage Accounts Context
namespaces:
- prefix: azurestorageaccounts
  uri: https://azure.microsoft.com/azure-storage-accounts/schema/
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
provider_name: Azure Storage Accounts
provider_slug: azure-storage-accounts
slug: azure-storage-accounts-context
source_filename: azure-storage-accounts-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurestorageaccounts\": \"https://azure.microsoft.com/azure-storage-accounts/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AccountSasParameters\": \"azurestorageaccounts:AccountSasParameters\",\n    \"ActiveDirectoryProperties\": \"azurestorageaccounts:ActiveDirectoryProperties\",\n    \"AzureFilesIdentityBasedAuthentication\": \"azurestorageaccounts:AzureFilesIdentityBasedAuthentication\",\n    \"BlobRestoreParameters\": \"azurestorageaccounts:BlobRestoreParameters\",\n    \"BlobRestoreRange\": \"azurestorageaccounts:BlobRestoreRange\",\n    \"BlobRestoreStatus\": \"azurestorageaccounts:BlobRestoreStatus\",\n    \"CheckNameAvailabilityResult\": \"azurestorageaccounts:CheckNameAvailabilityResult\",\n    \"CustomDomain\": \"azurestorageaccounts:CustomDomain\",\n    \"DateAfterCreation\": \"azurestorageaccounts:DateAfterCreation\"\
  ,\n    \"DateAfterModification\": \"azurestorageaccounts:DateAfterModification\",\n    \"Dimension\": \"azurestorageaccounts:Dimension\",\n    \"Encryption\": \"azurestorageaccounts:Encryption\",\n    \"EncryptionService\": \"azurestorageaccounts:EncryptionService\",\n    \"EncryptionServices\": \"azurestorageaccounts:EncryptionServices\",\n    \"Endpoints\": \"azurestorageaccounts:Endpoints\",\n    \"GeoReplicationStats\": \"azurestorageaccounts:GeoReplicationStats\",\n    \"IPRule\": \"azurestorageaccounts:IPRule\",\n    \"Identity\": \"azurestorageaccounts:Identity\",\n    \"KeyVaultProperties\": \"azurestorageaccounts:KeyVaultProperties\",\n    \"ListAccountSasResponse\": \"azurestorageaccounts:ListAccountSasResponse\",\n    \"keyToSign\": {\n      \"@id\": \"azurestorageaccounts:keyToSign\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedExpiry\": {\n      \"@id\": \"azurestorageaccounts:signedExpiry\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedIp\": {\n      \"\
  @id\": \"azurestorageaccounts:signedIp\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedPermission\": {\n      \"@id\": \"azurestorageaccounts:signedPermission\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedProtocol\": {\n      \"@id\": \"azurestorageaccounts:signedProtocol\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedResourceTypes\": {\n      \"@id\": \"azurestorageaccounts:signedResourceTypes\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedServices\": {\n      \"@id\": \"azurestorageaccounts:signedServices\",\n      \"@type\": \"xsd:string\"\n    },\n    \"signedStart\": {\n      \"@id\": \"azurestorageaccounts:signedStart\",\n      \"@type\": \"xsd:string\"\n    },\n    \"azureStorageSid\": {\n      \"@id\": \"azurestorageaccounts:azureStorageSid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainGuid\": {\n      \"@id\": \"azurestorageaccounts:domainGuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainName\": {\n      \"@id\": \"\
  azurestorageaccounts:domainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"domainSid\": {\n      \"@id\": \"azurestorageaccounts:domainSid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"forestName\": {\n      \"@id\": \"azurestorageaccounts:forestName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"netBiosDomainName\": {\n      \"@id\": \"azurestorageaccounts:netBiosDomainName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"activeDirectoryProperties\": {\n      \"@id\": \"azurestorageaccounts:activeDirectoryProperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"directoryServiceOptions\": {\n      \"@id\": \"azurestorageaccounts:directoryServiceOptions\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blobRanges\": {\n      \"@id\": \"azurestorageaccounts:blobRanges\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"timeToRestore\": {\n      \"@id\": \"azurestorageaccounts:timeToRestore\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"endRange\": {\n      \"@id\": \"azurestorageaccounts:endRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startRange\": {\n      \"@id\": \"azurestorageaccounts:startRange\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureReason\": {\n      \"@id\": \"azurestorageaccounts:failureReason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"azurestorageaccounts:parameters\",\n      \"@type\": \"xsd:string\"\n    },\n    \"restoreId\": {\n      \"@id\": \"azurestorageaccounts:restoreId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azurestorageaccounts:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"message\": {\n      \"@id\": \"azurestorageaccounts:message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameAvailable\": {\n      \"@id\": \"azurestorageaccounts:nameAvailable\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"reason\": {\n      \"@id\": \"azurestorageaccounts:reason\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"useSubDomainName\": {\n      \"@id\": \"azurestorageaccounts:useSubDomainName\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"daysAfterCreationGreaterThan\": {\n      \"@id\": \"azurestorageaccounts:daysAfterCreationGreaterThan\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"daysAfterModificationGreaterThan\": {\n      \"@id\": \"azurestorageaccounts:daysAfterModificationGreaterThan\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"displayName\": {\n      \"@id\": \"azurestorageaccounts:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keySource\": {\n      \"@id\": \"azurestorageaccounts:keySource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyvaultproperties\": {\n      \"@id\": \"azurestorageaccounts:keyvaultproperties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"services\": {\n      \"@id\": \"azurestorageaccounts:services\",\n      \"@type\": \"xsd:string\"\n    },\n\
  \    \"enabled\": {\n      \"@id\": \"azurestorageaccounts:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"keyType\": {\n      \"@id\": \"azurestorageaccounts:keyType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastEnabledTime\": {\n      \"@id\": \"azurestorageaccounts:lastEnabledTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"blob\": {\n      \"@id\": \"azurestorageaccounts:blob\",\n      \"@type\": \"xsd:string\"\n    },\n    \"file\": {\n      \"@id\": \"azurestorageaccounts:file\",\n      \"@type\": \"xsd:string\"\n    },\n    \"queue\": {\n      \"@id\": \"azurestorageaccounts:queue\",\n      \"@type\": \"xsd:string\"\n    },\n    \"table\": {\n      \"@id\": \"azurestorageaccounts:table\",\n      \"@type\": \"xsd:string\"\n    },\n    \"dfs\": {\n      \"@id\": \"azurestorageaccounts:dfs\",\n      \"@type\": \"xsd:string\"\n    },\n    \"internetEndpoints\": {\n      \"@id\": \"azurestorageaccounts:internetEndpoints\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"microsoftEndpoints\": {\n      \"@id\": \"azurestorageaccounts:microsoftEndpoints\",\n      \"@type\": \"xsd:string\"\n    },\n    \"web\": {\n      \"@id\": \"azurestorageaccounts:web\",\n      \"@type\": \"xsd:string\"\n    },\n    \"canFailover\": {\n      \"@id\": \"azurestorageaccounts:canFailover\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"lastSyncTime\": {\n      \"@id\": \"azurestorageaccounts:lastSyncTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"action\": {\n      \"@id\": \"azurestorageaccounts:action\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurestorageaccounts:value\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\": {\n      \"@id\": \"azurestorageaccounts:principalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"azurestorageaccounts:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurestorageaccounts:type\",\n \
  \     \"@type\": \"xsd:string\"\n    },\n    \"keyname\": {\n      \"@id\": \"azurestorageaccounts:keyname\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyvaulturi\": {\n      \"@id\": \"azurestorageaccounts:keyvaulturi\",\n      \"@type\": \"xsd:string\"\n    },\n    \"keyversion\": {\n      \"@id\": \"azurestorageaccounts:keyversion\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountSasToken\": {\n      \"@id\": \"azurestorageaccounts:accountSasToken\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-storage-accounts/refs/heads/main/json-ld/azure-storage-accounts-context.jsonld
tags:
- Azure
- Blob Storage
- Cloud Storage
- File Storage
- Queue Storage
- Storage
- Table Storage
- JSON-LD
- Linked Data
- Semantic Web
---
