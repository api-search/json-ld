---
api_specs:
- filename: microsoft-defender-for-endpoint-api-openapi.yml
  format: yaml
  label: Microsoft Defender for Endpoint API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/openapi/microsoft-defender-for-endpoint-api-openapi.yml
- filename: graph-explorer
  format: yaml
  label: Microsoft Graph Security API
  slug: ''
  spec_type: OpenAPI
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
class_count: 0
classes: []
context_file: json-ld/microsoft-defender-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/json-ld/microsoft-defender-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Microsoft Defender from Microsoft Defender.
layout: jsonld
name: Microsoft Defender Context
namespaces:
- prefix: defender
  uri: https://learn.microsoft.com/en-us/defender-endpoint/api/
- prefix: security
  uri: https://schema.org/SecurityEvent/
- prefix: cve
  uri: https://cve.mitre.org/cgi-bin/cvename.cgi?name=
- prefix: mitre
  uri: https://attack.mitre.org/techniques/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: Alert
  type: ''
- container: ''
  name: Machine
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: AlertComment
  type: ''
- container: ''
  name: AlertEvidence
  type: ''
property_count: 5
provider_name: Microsoft Defender
provider_slug: microsoft-defender
slug: microsoft-defender-context
source_filename: microsoft-defender-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"@vocab\": \"https://schema.org/\",\n    \"defender\": \"https://learn.microsoft.com/en-us/defender-endpoint/api/\",\n    \"security\": \"https://schema.org/SecurityEvent/\",\n    \"cve\": \"https://cve.mitre.org/cgi-bin/cvename.cgi?name=\",\n    \"mitre\": \"https://attack.mitre.org/techniques/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Alert\": {\n      \"@id\": \"defender:alerts\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"title\": {\n          \"@id\": \"name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"alertCreationTime\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastEventTime\": {\n          \"@id\": \"defender:lastEventTime\"\
  ,\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"firstEventTime\": {\n          \"@id\": \"defender:firstEventTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastUpdateTime\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolvedTime\": {\n          \"@id\": \"defender:resolvedTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"incidentId\": {\n          \"@id\": \"defender:incidentId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"investigationId\": {\n          \"@id\": \"defender:investigationId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"investigationState\": {\n          \"@id\": \"defender:investigationState\",\n          \"@type\": \"xsd:string\"\n        },\n        \"assignedTo\": {\n          \"@id\": \"defender:assignedTo\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rbacGroupName\": {\n          \"@id\": \"defender:rbacGroupName\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"mitreTechniques\": {\n          \"@id\": \"defender:mitreTechniques\",\n          \"@container\": \"@set\"\n        },\n        \"severity\": {\n          \"@id\": \"security:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"status\": {\n          \"@id\": \"defender:alertStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"classification\": {\n          \"@id\": \"defender:classification\",\n          \"@type\": \"xsd:string\"\n        },\n        \"determination\": {\n          \"@id\": \"defender:determination\",\n          \"@type\": \"xsd:string\"\n        },\n        \"category\": {\n          \"@id\": \"category\",\n          \"@type\": \"xsd:string\"\n        },\n        \"detectionSource\": {\n          \"@id\": \"defender:detectionSource\",\n          \"@type\": \"xsd:string\"\n        },\n        \"threatFamilyName\": {\n          \"@id\": \"defender:threatFamilyName\",\n   \
  \       \"@type\": \"xsd:string\"\n        },\n        \"threatName\": {\n          \"@id\": \"defender:threatName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"machineId\": {\n          \"@id\": \"defender:machineId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"computerDnsName\": {\n          \"@id\": \"defender:computerDnsName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"aadTenantId\": {\n          \"@id\": \"defender:aadTenantId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"detectorId\": {\n          \"@id\": \"defender:detectorId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"comments\": {\n          \"@id\": \"comment\",\n          \"@container\": \"@set\"\n        },\n        \"evidence\": {\n          \"@id\": \"defender:evidence\",\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Machine\": {\n      \"@id\": \"defender:machine\",\n      \"@context\": {\n        \"id\": {\n\
  \          \"@id\": \"identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"computerDnsName\": {\n          \"@id\": \"defender:computerDnsName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"firstSeen\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"lastSeen\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"osPlatform\": {\n          \"@id\": \"operatingSystem\",\n          \"@type\": \"xsd:string\"\n        },\n        \"onboardingStatus\": {\n          \"@id\": \"defender:onboardingStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"version\": {\n          \"@id\": \"softwareVersion\",\n          \"@type\": \"xsd:string\"\n        },\n        \"osBuild\": {\n          \"@id\": \"defender:osBuild\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"lastIpAddress\": {\n          \"@id\": \"defender:lastIpAddress\"\
  ,\n          \"@type\": \"xsd:string\"\n        },\n        \"lastExternalIpAddress\": {\n          \"@id\": \"defender:lastExternalIpAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"healthStatus\": {\n          \"@id\": \"defender:healthStatus\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rbacGroupName\": {\n          \"@id\": \"defender:rbacGroupName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"rbacGroupId\": {\n          \"@id\": \"defender:rbacGroupId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"riskScore\": {\n          \"@id\": \"defender:riskScore\",\n          \"@type\": \"xsd:string\"\n        },\n        \"aadDeviceId\": {\n          \"@id\": \"defender:aadDeviceId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"machineTags\": {\n          \"@id\": \"keywords\",\n          \"@container\": \"@set\"\n        },\n        \"exposureLevel\": {\n          \"@id\": \"defender:exposureLevel\",\n\
  \          \"@type\": \"xsd:string\"\n        },\n        \"deviceValue\": {\n          \"@id\": \"defender:deviceValue\",\n          \"@type\": \"xsd:string\"\n        },\n        \"osArchitecture\": {\n          \"@id\": \"defender:osArchitecture\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"defender:vulnerability\",\n      \"@context\": {\n        \"id\": {\n          \"@id\": \"identifier\",\n          \"@type\": \"xsd:string\"\n        },\n        \"name\": {\n          \"@id\": \"name\",\n          \"@type\": \"xsd:string\"\n        },\n        \"description\": {\n          \"@id\": \"description\",\n          \"@type\": \"xsd:string\"\n        },\n        \"severity\": {\n          \"@id\": \"security:severity\",\n          \"@type\": \"xsd:string\"\n        },\n        \"cvssV3\": {\n          \"@id\": \"defender:cvssV3\",\n          \"@type\": \"xsd:double\"\n        },\n        \"cvssVector\": {\n          \"\
  @id\": \"defender:cvssVector\",\n          \"@type\": \"xsd:string\"\n        },\n        \"exposedMachines\": {\n          \"@id\": \"defender:exposedMachines\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"publishedOn\": {\n          \"@id\": \"datePublished\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedOn\": {\n          \"@id\": \"dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"publicExploit\": {\n          \"@id\": \"defender:publicExploit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"exploitVerified\": {\n          \"@id\": \"defender:exploitVerified\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"exploitInKit\": {\n          \"@id\": \"defender:exploitInKit\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"exploitTypes\": {\n          \"@id\": \"defender:exploitTypes\",\n          \"@container\": \"@set\"\n        },\n        \"exploitUris\": {\n          \"@id\"\
  : \"defender:exploitUris\",\n          \"@container\": \"@set\",\n          \"@type\": \"@id\"\n        },\n        \"cveSupportability\": {\n          \"@id\": \"defender:cveSupportability\",\n          \"@type\": \"xsd:string\"\n        },\n        \"epss\": {\n          \"@id\": \"defender:epss\",\n          \"@type\": \"xsd:double\"\n        },\n        \"status\": {\n          \"@id\": \"defender:vulnerabilityStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    },\n\n    \"AlertComment\": {\n      \"@id\": \"defender:alertComment\",\n      \"@context\": {\n        \"comment\": {\n          \"@id\": \"text\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdBy\": {\n          \"@id\": \"author\",\n          \"@type\": \"xsd:string\"\n        },\n        \"createdTime\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"AlertEvidence\": {\n      \"@id\": \"defender:alertEvidence\",\n\
  \      \"@context\": {\n        \"entityType\": {\n          \"@id\": \"additionalType\",\n          \"@type\": \"xsd:string\"\n        },\n        \"evidenceCreationTime\": {\n          \"@id\": \"dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sha1\": {\n          \"@id\": \"defender:sha1\",\n          \"@type\": \"xsd:string\"\n        },\n        \"sha256\": {\n          \"@id\": \"defender:sha256\",\n          \"@type\": \"xsd:string\"\n        },\n        \"fileName\": {\n          \"@id\": \"defender:fileName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"filePath\": {\n          \"@id\": \"defender:filePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processId\": {\n          \"@id\": \"defender:processId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"processCommandLine\": {\n          \"@id\": \"defender:processCommandLine\",\n          \"@type\": \"xsd:string\"\n        },\n        \"processCreationTime\"\
  : {\n          \"@id\": \"defender:processCreationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"parentProcessId\": {\n          \"@id\": \"defender:parentProcessId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"parentProcessCreationTime\": {\n          \"@id\": \"defender:parentProcessCreationTime\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"parentProcessFileName\": {\n          \"@id\": \"defender:parentProcessFileName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"parentProcessFilePath\": {\n          \"@id\": \"defender:parentProcessFilePath\",\n          \"@type\": \"xsd:string\"\n        },\n        \"ipAddress\": {\n          \"@id\": \"defender:ipAddress\",\n          \"@type\": \"xsd:string\"\n        },\n        \"url\": {\n          \"@id\": \"url\",\n          \"@type\": \"@id\"\n        },\n        \"accountName\": {\n          \"@id\": \"defender:accountName\",\n          \"@type\": \"xsd:string\"\
  \n        },\n        \"domainName\": {\n          \"@id\": \"defender:domainName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userSid\": {\n          \"@id\": \"defender:userSid\",\n          \"@type\": \"xsd:string\"\n        },\n        \"aadUserId\": {\n          \"@id\": \"defender:aadUserId\",\n          \"@type\": \"xsd:string\"\n        },\n        \"userPrincipalName\": {\n          \"@id\": \"defender:userPrincipalName\",\n          \"@type\": \"xsd:string\"\n        },\n        \"detectionStatus\": {\n          \"@id\": \"defender:detectionStatus\",\n          \"@type\": \"xsd:string\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/microsoft-defender/refs/heads/main/json-ld/microsoft-defender-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
