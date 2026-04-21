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
