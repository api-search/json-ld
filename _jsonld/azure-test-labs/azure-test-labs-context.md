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
source_filename: azure-test-labs-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"azuretestlabs\": \"https://azure.microsoft.com/azure-test-labs/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"ApplicableSchedule\": \"azuretestlabs:ApplicableSchedule\",\n    \"ApplicableScheduleFragment\": \"azuretestlabs:ApplicableScheduleFragment\",\n    \"ApplicableScheduleProperties\": \"azuretestlabs:ApplicableScheduleProperties\",\n    \"ApplicableSchedulePropertiesFragment\": \"azuretestlabs:ApplicableSchedulePropertiesFragment\",\n    \"ApplyArtifactsRequest\": \"azuretestlabs:ApplyArtifactsRequest\",\n    \"ArmTemplate\": \"azuretestlabs:ArmTemplate\",\n    \"ArmTemplateInfo\": \"azuretestlabs:ArmTemplateInfo\",\n    \"ArmTemplateList\": \"azuretestlabs:ArmTemplateList\",\n    \"ArmTemplateParameterProperties\": \"azuretestlabs:ArmTemplateParameterProperties\",\n    \"ArmTemplateParameterPropertiesFragment\"\
  : \"azuretestlabs:ArmTemplateParameterPropertiesFragment\",\n    \"ArmTemplateProperties\": \"azuretestlabs:ArmTemplateProperties\",\n    \"Artifact\": \"azuretestlabs:Artifact\",\n    \"ArtifactDeploymentStatusProperties\": \"azuretestlabs:ArtifactDeploymentStatusProperties\",\n    \"ArtifactDeploymentStatusPropertiesFragment\": \"azuretestlabs:ArtifactDeploymentStatusPropertiesFragment\",\n    \"ArtifactInstallProperties\": \"azuretestlabs:ArtifactInstallProperties\",\n    \"ArtifactInstallPropertiesFragment\": \"azuretestlabs:ArtifactInstallPropertiesFragment\",\n    \"ArtifactList\": \"azuretestlabs:ArtifactList\",\n    \"ArtifactParameterProperties\": \"azuretestlabs:ArtifactParameterProperties\",\n    \"ArtifactParameterPropertiesFragment\": \"azuretestlabs:ArtifactParameterPropertiesFragment\",\n    \"ArtifactProperties\": \"azuretestlabs:ArtifactProperties\",\n    \"properties\": {\n      \"@id\": \"azuretestlabs:properties\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labVmsShutdown\"\
  : {\n      \"@id\": \"azuretestlabs:labVmsShutdown\",\n      \"@type\": \"xsd:string\"\n    },\n    \"labVmsStartup\": {\n      \"@id\": \"azuretestlabs:labVmsStartup\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artifacts\": {\n      \"@id\": \"azuretestlabs:artifacts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parameters\": {\n      \"@id\": \"azuretestlabs:parameters\",\n      \"@type\": \"@id\"\n    },\n    \"template\": {\n      \"@id\": \"azuretestlabs:template\",\n      \"@type\": \"@id\"\n    },\n    \"nextLink\": {\n      \"@id\": \"azuretestlabs:nextLink\",\n      \"@type\": \"xsd:string\"\n    },\n    \"value\": {\n      \"@id\": \"azuretestlabs:value\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"contents\": {\n      \"@id\": \"azuretestlabs:contents\",\n      \"@type\": \"@id\"\n    },\n    \"createdDate\": {\n      \"@id\": \"azuretestlabs:createdDate\",\n   \
  \   \"@type\": \"xsd:string\"\n    },\n    \"description\": \"schema:description\",\n    \"displayName\": {\n      \"@id\": \"azuretestlabs:displayName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"azuretestlabs:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"icon\": {\n      \"@id\": \"azuretestlabs:icon\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parametersValueFilesInfo\": {\n      \"@id\": \"azuretestlabs:parametersValueFilesInfo\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"publisher\": {\n      \"@id\": \"azuretestlabs:publisher\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artifactsApplied\": {\n      \"@id\": \"azuretestlabs:artifactsApplied\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"deploymentStatus\": {\n      \"@id\": \"azuretestlabs:deploymentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalArtifacts\": {\n      \"@id\": \"azuretestlabs:totalArtifacts\",\n\
  \      \"@type\": \"xsd:integer\"\n    },\n    \"artifactId\": {\n      \"@id\": \"azuretestlabs:artifactId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"artifactTitle\": {\n      \"@id\": \"azuretestlabs:artifactTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"deploymentStatusMessage\": {\n      \"@id\": \"azuretestlabs:deploymentStatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"installTime\": {\n      \"@id\": \"azuretestlabs:installTime\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"azuretestlabs:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"vmExtensionStatusMessage\": {\n      \"@id\": \"azuretestlabs:vmExtensionStatusMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"filePath\": {\n      \"@id\": \"azuretestlabs:filePath\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetOsType\": {\n      \"@id\": \"azuretestlabs:targetOsType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n    \
  \  \"@id\": \"azuretestlabs:title\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/azure-test-labs/refs/heads/main/json-ld/azure-test-labs-context.jsonld
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
