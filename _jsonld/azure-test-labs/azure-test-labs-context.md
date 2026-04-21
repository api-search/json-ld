---
class_count: 22
classes:
- ApplicableSchedule
- ApplicableScheduleFragment
- ApplicableScheduleProperties
- ApplicableSchedulePropertiesFragment
- ApplyArtifactsRequest
- ArmTemplate
- ArmTemplateInfo
- ArmTemplateList
- ArmTemplateParameterProperties
- ArmTemplateParameterPropertiesFragment
- ArmTemplateProperties
- Artifact
- ArtifactDeploymentStatusProperties
- ArtifactDeploymentStatusPropertiesFragment
- ArtifactInstallProperties
- ArtifactInstallPropertiesFragment
- ArtifactList
- ArtifactParameterProperties
- ArtifactParameterPropertiesFragment
- ArtifactProperties
- name
- description
context_file: json-ld/azure-test-labs-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/json-ld/azure-test-labs-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Azure Test Labs from Azure DevTest Labs.
layout: jsonld
name: Azure Test Labs Context
namespaces:
- prefix: azuretestlabs
  uri: https://azure.microsoft.com/azure-test-labs/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: properties
  type: string
- container: ''
  name: labVmsShutdown
  type: string
- container: ''
  name: labVmsStartup
  type: string
- container: set
  name: artifacts
  type: string
- container: ''
  name: parameters
  type: reference
- container: ''
  name: template
  type: reference
- container: ''
  name: nextLink
  type: string
- container: set
  name: value
  type: string
- container: ''
  name: contents
  type: reference
- container: ''
  name: createdDate
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: icon
  type: string
- container: set
  name: parametersValueFilesInfo
  type: string
- container: ''
  name: publisher
  type: string
- container: ''
  name: artifactsApplied
  type: integer
- container: ''
  name: deploymentStatus
  type: string
- container: ''
  name: totalArtifacts
  type: integer
- container: ''
  name: artifactId
  type: string
- container: ''
  name: artifactTitle
  type: string
- container: ''
  name: deploymentStatusMessage
  type: string
- container: ''
  name: installTime
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: vmExtensionStatusMessage
  type: string
- container: ''
  name: filePath
  type: string
- container: ''
  name: targetOsType
  type: string
- container: ''
  name: title
  type: string
property_count: 27
provider_name: Azure DevTest Labs
provider_slug: azure-test-labs
slug: azure-test-labs-context
tags:
- Azure
- Development
- Infrastructure
- Labs
- Testing
- Virtual Machines
- JSON-LD
- Linked Data
- Semantic Web
---
