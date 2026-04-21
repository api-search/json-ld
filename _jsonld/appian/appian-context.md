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
