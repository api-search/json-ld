---
class_count: 20
classes:
- AzureFileVolume
- CachedImagesListResult
- Capabilities
- CapabilitiesListResult
- Container
- ContainerExec
- ContainerExecRequest
- ContainerExecResponse
- ContainerGroupDiagnostics
- ContainerGroupIdentity
- ContainerGroupListResult
- ContainerGroupNetworkProfile
- ContainerHttpGet
- ContainerPort
- ContainerProbe
- ContainerProperties
- ContainerState
- DnsConfiguration
- EmptyDirVolume
- name
context_file: json-ld/azure-container-instances-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/json-ld/azure-container-instances-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Container Instances from Azure Container Instances.
layout: jsonld
name: Azure Container Instances Context
namespaces:
- prefix: azurecontainerinstances
  uri: https://azure.microsoft.com/azure-container-instances/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: readOnly
  type: boolean
- container: ''
  name: shareName
  type: string
- container: ''
  name: storageAccountKey
  type: string
- container: ''
  name: storageAccountName
  type: string
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: capabilities
  type: reference
- container: ''
  name: gpu
  type: string
- container: ''
  name: ipAddressType
  type: string
- container: ''
  name: location
  type: string
- container: ''
  name: osType
  type: string
- container: ''
  name: resourceType
  type: string
- container: ''
  name: properties
  type: string
- container: set
  name: command
  type: string
- container: ''
  name: terminalSize
  type: reference
- container: ''
  name: password
  type: string
- container: ''
  name: webSocketUri
  type: string
- container: ''
  name: logAnalytics
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
  name: userAssignedIdentities
  type: reference
- container: ''
  name: id
  type: string
- container: ''
  name: path
  type: string
- container: ''
  name: port
  type: integer
- container: ''
  name: scheme
  type: string
- container: ''
  name: protocol
  type: string
- container: ''
  name: exec
  type: string
- container: ''
  name: failureThreshold
  type: integer
- container: ''
  name: httpGet
  type: string
- container: ''
  name: initialDelaySeconds
  type: integer
- container: ''
  name: periodSeconds
  type: integer
- container: ''
  name: successThreshold
  type: integer
- container: ''
  name: timeoutSeconds
  type: integer
- container: set
  name: environmentVariables
  type: string
- container: ''
  name: image
  type: string
- container: ''
  name: instanceView
  type: reference
- container: ''
  name: livenessProbe
  type: string
- container: set
  name: ports
  type: string
- container: ''
  name: readinessProbe
  type: string
- container: ''
  name: resources
  type: string
- container: set
  name: volumeMounts
  type: string
- container: ''
  name: detailStatus
  type: string
- container: ''
  name: exitCode
  type: integer
- container: ''
  name: finishTime
  type: string
- container: ''
  name: startTime
  type: string
- container: ''
  name: state
  type: string
- container: set
  name: nameServers
  type: string
- container: ''
  name: options
  type: string
- container: ''
  name: searchDomains
  type: string
property_count: 50
provider_name: Azure Container Instances
provider_slug: azure-container-instances
slug: azure-container-instances-context
source_filename: azure-container-instances-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azurecontainerinstances\": \"https://azure.microsoft.com/azure-container-instances/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AzureFileVolume\": \"azurecontainerinstances:AzureFileVolume\",\n    \"CachedImagesListResult\": \"azurecontainerinstances:CachedImagesListResult\",\n    \"Capabilities\": \"azurecontainerinstances:Capabilities\",\n    \"CapabilitiesListResult\": \"azurecontainerinstances:CapabilitiesListResult\",\n    \"Container\": \"azurecontainerinstances:Container\",\n    \"ContainerExec\": \"azurecontainerinstances:ContainerExec\",\n    \"ContainerExecRequest\": \"azurecontainerinstances:ContainerExecRequest\",\n    \"ContainerExecResponse\": \"azurecontainerinstances:ContainerExecResponse\",\n    \"ContainerGroupDiagnostics\": \"azurecontainerinstances:ContainerGroupDiagnostics\",\n    \"ContainerGroupIdentity\"\
  : \"azurecontainerinstances:ContainerGroupIdentity\",\n    \"ContainerGroupListResult\": \"azurecontainerinstances:ContainerGroupListResult\",\n    \"ContainerGroupNetworkProfile\": \"azurecontainerinstances:ContainerGroupNetworkProfile\",\n    \"ContainerHttpGet\": \"azurecontainerinstances:ContainerHttpGet\",\n    \"ContainerPort\": \"azurecontainerinstances:ContainerPort\",\n    \"ContainerProbe\": \"azurecontainerinstances:ContainerProbe\",\n    \"ContainerProperties\": \"azurecontainerinstances:ContainerProperties\",\n    \"ContainerState\": \"azurecontainerinstances:ContainerState\",\n    \"DnsConfiguration\": \"azurecontainerinstances:DnsConfiguration\",\n    \"EmptyDirVolume\": \"azurecontainerinstances:EmptyDirVolume\",\n    \"readOnly\": {\n      \"@id\": \"azurecontainerinstances:readOnly\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"shareName\": {\n      \"@id\": \"azurecontainerinstances:shareName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageAccountKey\"\
  : {\n      \"@id\": \"azurecontainerinstances:storageAccountKey\",\n      \"@type\": \"xsd:string\"\n    },\n    \"storageAccountName\": {\n      \"@id\": \"azurecontainerinstances:storageAccountName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azurecontainerinstances:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azurecontainerinstances:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"capabilities\": {\n      \"@id\": \"azurecontainerinstances:capabilities\",\n      \"@type\": \"@id\"\n    },\n    \"gpu\": {\n      \"@id\": \"azurecontainerinstances:gpu\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ipAddressType\": {\n      \"@id\": \"azurecontainerinstances:ipAddressType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"location\": {\n      \"@id\": \"azurecontainerinstances:location\",\n      \"@type\": \"xsd:string\"\n    },\n    \"osType\": {\n      \"@id\"\
  : \"azurecontainerinstances:osType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resourceType\": {\n      \"@id\": \"azurecontainerinstances:resourceType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"properties\": {\n      \"@id\": \"azurecontainerinstances:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"command\": {\n      \"@id\": \"azurecontainerinstances:command\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"terminalSize\": {\n      \"@id\": \"azurecontainerinstances:terminalSize\",\n      \"@type\": \"@id\"\n    },\n    \"password\": {\n      \"@id\": \"azurecontainerinstances:password\",\n      \"@type\": \"xsd:string\"\n    },\n    \"webSocketUri\": {\n      \"@id\": \"azurecontainerinstances:webSocketUri\",\n      \"@type\": \"xsd:string\"\n    },\n    \"logAnalytics\": {\n      \"@id\": \"azurecontainerinstances:logAnalytics\",\n      \"@type\": \"xsd:string\"\n    },\n    \"principalId\"\
  : {\n      \"@id\": \"azurecontainerinstances:principalId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"azurecontainerinstances:tenantId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"type\": {\n      \"@id\": \"azurecontainerinstances:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"userAssignedIdentities\": {\n      \"@id\": \"azurecontainerinstances:userAssignedIdentities\",\n      \"@type\": \"@id\"\n    },\n    \"id\": {\n      \"@id\": \"azurecontainerinstances:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"path\": {\n      \"@id\": \"azurecontainerinstances:path\",\n      \"@type\": \"xsd:string\"\n    },\n    \"port\": {\n      \"@id\": \"azurecontainerinstances:port\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"scheme\": {\n      \"@id\": \"azurecontainerinstances:scheme\",\n      \"@type\": \"xsd:string\"\n    },\n    \"protocol\": {\n      \"@id\": \"azurecontainerinstances:protocol\",\n      \"@type\": \"xsd:string\"\
  \n    },\n    \"exec\": {\n      \"@id\": \"azurecontainerinstances:exec\",\n      \"@type\": \"xsd:string\"\n    },\n    \"failureThreshold\": {\n      \"@id\": \"azurecontainerinstances:failureThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"httpGet\": {\n      \"@id\": \"azurecontainerinstances:httpGet\",\n      \"@type\": \"xsd:string\"\n    },\n    \"initialDelaySeconds\": {\n      \"@id\": \"azurecontainerinstances:initialDelaySeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"periodSeconds\": {\n      \"@id\": \"azurecontainerinstances:periodSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"successThreshold\": {\n      \"@id\": \"azurecontainerinstances:successThreshold\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"timeoutSeconds\": {\n      \"@id\": \"azurecontainerinstances:timeoutSeconds\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"environmentVariables\": {\n      \"@id\": \"azurecontainerinstances:environmentVariables\",\n      \"\
  @container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"image\": {\n      \"@id\": \"azurecontainerinstances:image\",\n      \"@type\": \"xsd:string\"\n    },\n    \"instanceView\": {\n      \"@id\": \"azurecontainerinstances:instanceView\",\n      \"@type\": \"@id\"\n    },\n    \"livenessProbe\": {\n      \"@id\": \"azurecontainerinstances:livenessProbe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"ports\": {\n      \"@id\": \"azurecontainerinstances:ports\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"readinessProbe\": {\n      \"@id\": \"azurecontainerinstances:readinessProbe\",\n      \"@type\": \"xsd:string\"\n    },\n    \"resources\": {\n      \"@id\": \"azurecontainerinstances:resources\",\n      \"@type\": \"xsd:string\"\n    },\n    \"volumeMounts\": {\n      \"@id\": \"azurecontainerinstances:volumeMounts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"detailStatus\": {\n      \"@id\"\
  : \"azurecontainerinstances:detailStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exitCode\": {\n      \"@id\": \"azurecontainerinstances:exitCode\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"finishTime\": {\n      \"@id\": \"azurecontainerinstances:finishTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"startTime\": {\n      \"@id\": \"azurecontainerinstances:startTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"state\": {\n      \"@id\": \"azurecontainerinstances:state\",\n      \"@type\": \"xsd:string\"\n    },\n    \"nameServers\": {\n      \"@id\": \"azurecontainerinstances:nameServers\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"options\": {\n      \"@id\": \"azurecontainerinstances:options\",\n      \"@type\": \"xsd:string\"\n    },\n    \"searchDomains\": {\n      \"@id\": \"azurecontainerinstances:searchDomains\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-container-instances/refs/heads/main/json-ld/azure-container-instances-context.jsonld
tags:
- Azure
- Cloud
- Container Instances
- Containers
- Microsoft
- Serverless
- JSON-LD
- Linked Data
- Semantic Web
---
