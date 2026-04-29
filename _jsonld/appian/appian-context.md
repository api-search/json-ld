---
class_count: 20
classes:
- DeploymentRequest
- DeploymentResponse
- DeploymentStatus
- ImportDeploymentResult
- ExportDeploymentResult
- DatabaseScript
- ImportSummaryCount
- InspectionRequest
- InspectionResponse
- InspectionResult
- InspectionProblems
- InspectionError
- InspectionWarning
- ExportConfiguration
- ImportConfiguration
- PackageListResponse
- Package
- url
- name
- description
context_file: json-ld/appian-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/appian/refs/heads/main/json-ld/appian-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Appian from Appian.
layout: jsonld
name: Appian Context
namespaces:
- prefix: appian
  uri: https://appian.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: json
  type: string
- container: ''
  name: packageFileName
  type: string
- container: ''
  name: adminConsoleSettingsFileName
  type: string
- container: ''
  name: customizationFileName
  type: string
- container: ''
  name: pluginsFileName
  type: string
- container: ''
  name: uuid
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: summary
  type: string
- container: ''
  name: packageZip
  type: reference
- container: ''
  name: dataSource
  type: string
- container: set
  name: databaseScripts
  type: string
- container: ''
  name: pluginsZip
  type: reference
- container: ''
  name: customizationFile
  type: reference
- container: ''
  name: customizationFileTemplate
  type: reference
- container: ''
  name: deploymentLogUrl
  type: reference
- container: ''
  name: fileName
  type: string
- container: ''
  name: orderId
  type: integer
- container: ''
  name: total
  type: integer
- container: ''
  name: imported
  type: integer
- container: ''
  name: failed
  type: integer
- container: ''
  name: skipped
  type: integer
- container: ''
  name: totalErrors
  type: integer
- container: ''
  name: totalWarnings
  type: integer
- container: set
  name: errors
  type: string
- container: set
  name: warnings
  type: string
- container: ''
  name: errorMessage
  type: string
- container: ''
  name: objectName
  type: string
- container: ''
  name: objectUuid
  type: string
- container: ''
  name: warningMessage
  type: string
- container: ''
  name: exportType
  type: string
- container: set
  name: uuids
  type: string
- container: ''
  name: totalPackageCount
  type: integer
- container: set
  name: packages
  type: string
- container: ''
  name: objectCount
  type: integer
- container: ''
  name: databaseScriptCount
  type: integer
- container: ''
  name: pluginCount
  type: integer
- container: ''
  name: datasourceUuid
  type: string
- container: ''
  name: hasCustomizationFile
  type: boolean
- container: ''
  name: createdTimestamp
  type: dateTime
- container: ''
  name: lastModifiedTimestamp
  type: dateTime
- container: ''
  name: ticketLink
  type: string
property_count: 41
provider_name: Appian
provider_slug: appian
slug: appian-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"appian\": \"https://appian.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"DeploymentRequest\": \"appian:DeploymentRequest\",\n    \"DeploymentResponse\": \"appian:DeploymentResponse\",\n    \"DeploymentStatus\": \"appian:DeploymentStatus\",\n    \"ImportDeploymentResult\": \"appian:ImportDeploymentResult\",\n    \"ExportDeploymentResult\": \"appian:ExportDeploymentResult\",\n    \"DatabaseScript\": \"appian:DatabaseScript\",\n    \"ImportSummaryCount\": \"appian:ImportSummaryCount\",\n    \"InspectionRequest\": \"appian:InspectionRequest\",\n    \"InspectionResponse\": \"appian:InspectionResponse\",\n    \"InspectionResult\": \"appian:InspectionResult\",\n    \"InspectionProblems\": \"appian:InspectionProblems\",\n    \"InspectionError\": \"appian:InspectionError\",\n    \"InspectionWarning\": \"appian:InspectionWarning\"\
  ,\n    \"ExportConfiguration\": \"appian:ExportConfiguration\",\n    \"ImportConfiguration\": \"appian:ImportConfiguration\",\n    \"PackageListResponse\": \"appian:PackageListResponse\",\n    \"Package\": \"appian:Package\",\n    \"json\": {\n      \"@id\": \"appian:json\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageFileName\": {\n      \"@id\": \"appian:packageFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"adminConsoleSettingsFileName\": {\n      \"@id\": \"appian:adminConsoleSettingsFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customizationFileName\": {\n      \"@id\": \"appian:customizationFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pluginsFileName\": {\n      \"@id\": \"appian:pluginsFileName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuid\": {\n      \"@id\": \"appian:uuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"url\": \"schema:url\",\n    \"status\": {\n      \"@id\": \"appian:status\",\n      \"@type\":\
  \ \"xsd:string\"\n    },\n    \"summary\": {\n      \"@id\": \"appian:summary\",\n      \"@type\": \"xsd:string\"\n    },\n    \"packageZip\": {\n      \"@id\": \"appian:packageZip\",\n      \"@type\": \"@id\"\n    },\n    \"dataSource\": {\n      \"@id\": \"appian:dataSource\",\n      \"@type\": \"xsd:string\"\n    },\n    \"databaseScripts\": {\n      \"@id\": \"appian:databaseScripts\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"pluginsZip\": {\n      \"@id\": \"appian:pluginsZip\",\n      \"@type\": \"@id\"\n    },\n    \"customizationFile\": {\n      \"@id\": \"appian:customizationFile\",\n      \"@type\": \"@id\"\n    },\n    \"customizationFileTemplate\": {\n      \"@id\": \"appian:customizationFileTemplate\",\n      \"@type\": \"@id\"\n    },\n    \"deploymentLogUrl\": {\n      \"@id\": \"appian:deploymentLogUrl\",\n      \"@type\": \"@id\"\n    },\n    \"fileName\": {\n      \"@id\": \"appian:fileName\",\n      \"@type\": \"xsd:string\"\n\
  \    },\n    \"orderId\": {\n      \"@id\": \"appian:orderId\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"total\": {\n      \"@id\": \"appian:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"imported\": {\n      \"@id\": \"appian:imported\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"failed\": {\n      \"@id\": \"appian:failed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"skipped\": {\n      \"@id\": \"appian:skipped\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalErrors\": {\n      \"@id\": \"appian:totalErrors\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalWarnings\": {\n      \"@id\": \"appian:totalWarnings\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"errors\": {\n      \"@id\": \"appian:errors\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warnings\": {\n      \"@id\": \"appian:warnings\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"errorMessage\": {\n   \
  \   \"@id\": \"appian:errorMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectName\": {\n      \"@id\": \"appian:objectName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectUuid\": {\n      \"@id\": \"appian:objectUuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"warningMessage\": {\n      \"@id\": \"appian:warningMessage\",\n      \"@type\": \"xsd:string\"\n    },\n    \"exportType\": {\n      \"@id\": \"appian:exportType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"uuids\": {\n      \"@id\": \"appian:uuids\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"totalPackageCount\": {\n      \"@id\": \"appian:totalPackageCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"packages\": {\n      \"@id\": \"appian:packages\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"objectCount\": {\n      \"@id\": \"appian:objectCount\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"databaseScriptCount\": {\n      \"@id\": \"appian:databaseScriptCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"pluginCount\": {\n      \"@id\": \"appian:pluginCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"datasourceUuid\": {\n      \"@id\": \"appian:datasourceUuid\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hasCustomizationFile\": {\n      \"@id\": \"appian:hasCustomizationFile\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"createdTimestamp\": {\n      \"@id\": \"appian:createdTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastModifiedTimestamp\": {\n      \"@id\": \"appian:lastModifiedTimestamp\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"ticketLink\": {\n      \"@id\": \"appian:ticketLink\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/appian/refs/heads/main/json-ld/appian-context.jsonld
tags:
- Automation
- BPM
- Business Process Management
- Enterprise Software
- Low-Code
- Process Automation
- RPA
- Workflow
- JSON-LD
- Linked Data
- Semantic Web
---
