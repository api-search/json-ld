---
api_specs:
- filename: microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml
  format: yaml
  label: Configuration Manager REST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-configmgr-rest-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml
  format: yaml
  label: Microsoft Intune Graph API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-graph-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml
  format: yaml
  label: Intune Data Warehouse API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-data-warehouse-api-openapi.yml
- filename: microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml
  format: yaml
  label: Intune Reporting Export API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/openapi/microsoft-endpoint-configuration-management-intune-reporting-export-api-openapi.yml
class_count: 0
classes: []
context_file: json-ld/microsoft-endpoint-configuration-management-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/json-ld/microsoft-endpoint-configuration-management-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Endpoint Configuration Management from Microsoft Endpoint Configuration Management.
layout: jsonld
name: Microsoft Endpoint Configuration Management Context
namespaces:
- prefix: microsoft
  uri: https://graph.microsoft.com/v1.0/$metadata#
- prefix: intune
  uri: https://graph.microsoft.com/v1.0/deviceManagement/
- prefix: configmgr
  uri: https://learn.microsoft.com/en-us/intune/configmgr/develop/reference/
- prefix: odata
  uri: http://docs.oasis-open.org/odata/ns/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: ManagedDevice
  type: ''
- container: ''
  name: DeviceCompliancePolicy
  type: ''
- container: ''
  name: MobileApp
  type: ''
- container: ''
  name: DeviceConfiguration
  type: ''
- container: ''
  name: ConfigMgrCollection
  type: ''
- container: ''
  name: ConfigMgrApplication
  type: ''
- container: ''
  name: DataWarehouseDevice
  type: ''
property_count: 7
provider_name: Microsoft Endpoint Configuration Management
provider_slug: microsoft-endpoint-configuration-management
slug: microsoft-endpoint-configuration-management-context
source_filename: microsoft-endpoint-configuration-management-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"microsoft\": \"https://graph.microsoft.com/v1.0/$metadata#\",\n    \"intune\": \"https://graph.microsoft.com/v1.0/deviceManagement/\",\n    \"configmgr\": \"https://learn.microsoft.com/en-us/intune/configmgr/develop/reference/\",\n    \"odata\": \"http://docs.oasis-open.org/odata/ns/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"ManagedDevice\": {\n      \"@id\": \"microsoft:managedDevice\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"deviceName\": \"name\",\n        \"operatingSystem\": \"operatingSystem\",\n        \"osVersion\": \"microsoft:osVersion\",\n        \"manufacturer\": \"manufacturer\",\n        \"model\": \"model\",\n        \"serialNumber\": \"serialNumber\",\n        \"userId\": {\n          \"@id\": \"microsoft:userId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"managedDeviceOwnerType\": {\n          \"@id\": \"microsoft:managedDeviceOwnerType\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"enrolledDateTime\": {\n          \"@id\": \"microsoft:enrolledDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSyncDateTime\": {\n          \"@id\": \"microsoft:lastSyncDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"complianceState\": {\n          \"@id\": \"microsoft:complianceState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"managementAgent\": {\n          \"@id\": \"microsoft:managementAgent\",\n          \"@type\": \"xsd:string\"\n        },\n        \"deviceEnrollmentType\": {\n          \"@id\": \"microsoft:deviceEnrollmentType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"emailAddress\": {\n          \"@id\": \"microsoft:emailAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"azureADDeviceId\": {\n          \"@id\": \"microsoft:azureADDeviceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"isSupervised\"\
  : {\n          \"@id\": \"microsoft:isSupervised\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"isEncrypted\": {\n          \"@id\": \"microsoft:isEncrypted\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"userPrincipalName\": {\n          \"@id\": \"microsoft:userPrincipalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"imei\": {\n          \"@id\": \"microsoft:imei\",\n          \"@type\": \"xsd:string\"\n        },\n        \"phoneNumber\": {\n          \"@id\": \"telephone\",\n          \"@type\": \"xsd:string\"\n        },\n        \"wiFiMacAddress\": {\n          \"@id\": \"microsoft:wiFiMacAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"totalStorageSpaceInBytes\": {\n          \"@id\": \"microsoft:totalStorageSpaceInBytes\",\n          \"@type\": \"xsd:long\"\n        },\n        \"freeStorageSpaceInBytes\": {\n          \"@id\": \"microsoft:freeStorageSpaceInBytes\",\n          \"@type\": \"xsd:long\"\n \
  \       },\n        \"physicalMemoryInBytes\": {\n          \"@id\": \"microsoft:physicalMemoryInBytes\",\n          \"@type\": \"xsd:long\"\n        }\n      }\n    },\n\n    \"DeviceCompliancePolicy\": {\n      \"@id\": \"microsoft:deviceCompliancePolicy\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"name\",\n        \"description\": \"description\",\n        \"createdDateTime\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"version\": {\n          \"@id\": \"version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assignments\": {\n          \"@id\": \"microsoft:assignments\",\n          \"@container\": \"@set\"\n        },\n        \"scheduledActionsForRule\": {\n          \"@id\": \"microsoft:scheduledActionsForRule\",\n          \"@container\": \"@set\"\n\
  \        },\n        \"deviceStatuses\": {\n          \"@id\": \"microsoft:deviceStatuses\",\n          \"@container\": \"@set\"\n        },\n        \"userStatuses\": {\n          \"@id\": \"microsoft:userStatuses\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"MobileApp\": {\n      \"@id\": \"microsoft:mobileApp\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"name\",\n        \"description\": \"description\",\n        \"publisher\": \"publisher\",\n        \"developer\": \"microsoft:developer\",\n        \"owner\": \"microsoft:owner\",\n        \"createdDateTime\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"isFeatured\": {\n          \"@id\": \"microsoft:isFeatured\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"privacyInformationUrl\"\
  : {\n          \"@id\": \"microsoft:privacyInformationUrl\",\n          \"@type\": \"@id\"\n        },\n        \"informationUrl\": {\n          \"@id\": \"url\",\n          \"@type\": \"@id\"\n        },\n        \"notes\": {\n          \"@id\": \"microsoft:notes\",\n          \"@type\": \"xsd:string\"\n        },\n        \"publishingState\": {\n          \"@id\": \"microsoft:publishingState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"categories\": {\n          \"@id\": \"microsoft:categories\",\n          \"@container\": \"@set\"\n        },\n        \"assignments\": {\n          \"@id\": \"microsoft:assignments\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"DeviceConfiguration\": {\n      \"@id\": \"microsoft:deviceConfiguration\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"displayName\": \"name\",\n        \"description\": \"description\",\n        \"createdDateTime\": {\n          \"@id\": \"dateCreated\",\n       \
  \   \"@type\": \"xsd:dateTime\"\n        },\n        \"lastModifiedDateTime\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"version\": {\n          \"@id\": \"version\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assignments\": {\n          \"@id\": \"microsoft:assignments\",\n          \"@container\": \"@set\"\n        },\n        \"deviceStatuses\": {\n          \"@id\": \"microsoft:deviceStatuses\",\n          \"@container\": \"@set\"\n        },\n        \"userStatuses\": {\n          \"@id\": \"microsoft:userStatuses\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"ConfigMgrCollection\": {\n      \"@id\": \"configmgr:SMS_Collection\",\n      \"@context\": {\n        \"CollectionID\": \"@id\",\n        \"Name\": \"name\",\n        \"Comment\": \"description\",\n        \"CollectionType\": {\n          \"@id\": \"configmgr:CollectionType\",\n          \"@type\": \"xsd:integer\"\n  \
  \      },\n        \"MemberCount\": {\n          \"@id\": \"configmgr:MemberCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"LimitToCollectionID\": {\n          \"@id\": \"configmgr:LimitToCollectionID\",\n          \"@type\": \"xsd:string\"\n        },\n        \"LastRefreshTime\": {\n          \"@id\": \"configmgr:LastRefreshTime\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ConfigMgrApplication\": {\n      \"@id\": \"configmgr:SMS_Application\",\n      \"@context\": {\n        \"CI_ID\": \"@id\",\n        \"LocalizedDisplayName\": \"name\",\n        \"LocalizedDescription\": \"description\",\n        \"Manufacturer\": \"manufacturer\",\n        \"SoftwareVersion\": \"softwareVersion\",\n        \"DateCreated\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"DateLastModified\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"\
  IsDeployed\": {\n          \"@id\": \"configmgr:IsDeployed\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"IsSuperseded\": {\n          \"@id\": \"configmgr:IsSuperseded\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"DataWarehouseDevice\": {\n      \"@id\": \"intune:dataWarehouseDevice\",\n      \"@context\": {\n        \"deviceKey\": \"@id\",\n        \"deviceName\": \"name\",\n        \"operatingSystem\": \"operatingSystem\",\n        \"manufacturer\": \"manufacturer\",\n        \"model\": \"model\",\n        \"serialNumber\": \"serialNumber\",\n        \"osVersion\": {\n          \"@id\": \"microsoft:osVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"enrolledDateTime\": {\n          \"@id\": \"microsoft:enrolledDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSyncDateTime\": {\n          \"@id\": \"microsoft:lastSyncDateTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n      \
  \  \"complianceState\": {\n          \"@id\": \"microsoft:complianceState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"dateKey\": {\n          \"@id\": \"intune:dateKey\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-endpoint-configuration-management/refs/heads/main/json-ld/microsoft-endpoint-configuration-management-context.jsonld
tags:
- Compliance
- Configuration Management
- Device Management
- Endpoint Management
- Mobile Device Management
- Patch Management
- Software Deployment
- JSON-LD
- Linked Data
- Semantic Web
---
