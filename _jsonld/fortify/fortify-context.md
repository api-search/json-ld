---
api_specs:
- filename: fortify-on-demand-openapi.yml
  format: yaml
  label: Fortify on Demand API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-on-demand-openapi.yml
- filename: fortify-software-security-center-openapi.yml
  format: yaml
  label: Fortify Software Security Center API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-software-security-center-openapi.yml
- filename: fortify-scancentral-dast-openapi.yml
  format: yaml
  label: Fortify ScanCentral DAST API
  slug: ''
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/openapi/fortify-scancentral-dast-openapi.yml
class_count: 0
classes: []
context_file: json-ld/fortify-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/json-ld/fortify-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Fortify from Fortify.
layout: jsonld
name: Fortify Context
namespaces:
- prefix: fortify
  uri: https://www.opentext.com/products/fortify/vocab#
- prefix: schema
  uri: https://schema.org/
- prefix: sec
  uri: https://w3id.org/security#
- prefix: sarif
  uri: https://docs.oasis-open.org/sarif/sarif/v2.1.0/vocab#
- prefix: cwe
  uri: https://cwe.mitre.org/data/definitions/
- prefix: cve
  uri: https://www.cve.org/
- prefix: spdx
  uri: https://spdx.org/rdf/terms#
properties:
- container: ''
  name: Application
  type: ''
- container: ''
  name: Release
  type: ''
- container: ''
  name: ProjectVersion
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: Scan
  type: ''
- container: ''
  name: DastScan
  type: ''
- container: ''
  name: Artifact
  type: ''
- container: ''
  name: OpenSourceComponent
  type: ''
- container: ''
  name: User
  type: ''
- container: ''
  name: Sensor
  type: ''
- container: ''
  name: ScanPolicy
  type: ''
property_count: 11
provider_name: Fortify
provider_slug: fortify
slug: fortify-context
source_filename: fortify-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"fortify\": \"https://www.opentext.com/products/fortify/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"sec\": \"https://w3id.org/security#\",\n    \"sarif\": \"https://docs.oasis-open.org/sarif/sarif/v2.1.0/vocab#\",\n    \"cwe\": \"https://cwe.mitre.org/data/definitions/\",\n    \"cve\": \"https://www.cve.org/\",\n    \"spdx\": \"https://spdx.org/rdf/terms#\",\n\n    \"Application\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"applicationId\": \"schema:identifier\",\n        \"applicationName\": \"schema:name\",\n        \"applicationDescription\": \"schema:description\",\n        \"applicationCreatedDate\": \"schema:dateCreated\",\n        \"businessCriticalityType\": \"fortify:businessCriticality\",\n        \"sdlcStatusType\": \"fortify:sdlcStatus\",\n        \"emailList\": \"schema:email\",\n        \"hasMicroservices\": \"fortify:hasMicroservices\",\n        \"url\"\
  : \"schema:url\"\n      }\n    },\n\n    \"Release\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"releaseId\": \"schema:identifier\",\n        \"releaseName\": \"schema:name\",\n        \"releaseDescription\": \"schema:description\",\n        \"applicationId\": \"schema:isPartOf\",\n        \"sdlcStatusType\": \"fortify:sdlcStatus\",\n        \"rating\": \"schema:ratingValue\",\n        \"issueCount\": \"fortify:issueCount\",\n        \"isPassed\": \"fortify:passesSecurityPolicy\"\n      }\n    },\n\n    \"ProjectVersion\": {\n      \"@id\": \"schema:SoftwareApplication\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"active\": \"fortify:isActive\",\n        \"committed\": \"fortify:isCommitted\",\n        \"createdBy\": \"schema:creator\",\n        \"creationDate\": \"schema:dateCreated\",\n        \"issueTemplateId\": \"fortify:issueTemplateId\"\
  \n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"sec:Vulnerability\",\n      \"@context\": {\n        \"vulnId\": \"schema:identifier\",\n        \"issueInstanceId\": \"fortify:instanceId\",\n        \"category\": \"fortify:vulnerabilityCategory\",\n        \"kingdom\": \"fortify:vulnerabilityKingdom\",\n        \"severity\": \"sec:severity\",\n        \"severityString\": \"fortify:severityLabel\",\n        \"scanType\": \"fortify:scanType\",\n        \"status\": \"fortify:auditStatus\",\n        \"isSuppressed\": \"fortify:isSuppressed\",\n        \"assignedUser\": \"schema:assignee\",\n        \"primaryLocation\": \"sarif:physicalLocation\",\n        \"lineNumber\": \"sarif:startLine\",\n        \"fullFileName\": \"sarif:uri\",\n        \"introducedDate\": \"schema:dateCreated\",\n        \"removedDate\": \"fortify:dateRemoved\",\n        \"analyzer\": \"sarif:tool\",\n        \"confidence\": \"sarif:confidence\",\n        \"impact\": \"sec:impact\",\n        \"likelihood\"\
  : \"sec:likelihood\",\n        \"cweId\": \"cwe:id\"\n      }\n    },\n\n    \"Scan\": {\n      \"@id\": \"fortify:SecurityScan\",\n      \"@context\": {\n        \"scanId\": \"schema:identifier\",\n        \"scanType\": \"fortify:scanType\",\n        \"analysisStatusType\": \"fortify:analysisStatus\",\n        \"startedDateTime\": \"schema:startDate\",\n        \"completedDateTime\": \"schema:endDate\",\n        \"totalIssues\": \"fortify:totalIssues\",\n        \"issueCountCritical\": \"fortify:criticalIssueCount\",\n        \"issueCountHigh\": \"fortify:highIssueCount\",\n        \"issueCountMedium\": \"fortify:mediumIssueCount\",\n        \"issueCountLow\": \"fortify:lowIssueCount\",\n        \"passFailStatus\": \"fortify:passesSecurityPolicy\",\n        \"technologyStack\": \"schema:programmingLanguage\"\n      }\n    },\n\n    \"DastScan\": {\n      \"@id\": \"fortify:DastScan\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n\
  \        \"status\": \"fortify:scanStatus\",\n        \"startTime\": \"schema:startDate\",\n        \"endTime\": \"schema:endDate\",\n        \"totalVulnerabilities\": \"fortify:totalIssues\",\n        \"criticalCount\": \"fortify:criticalIssueCount\",\n        \"highCount\": \"fortify:highIssueCount\",\n        \"mediumCount\": \"fortify:mediumIssueCount\",\n        \"lowCount\": \"fortify:lowIssueCount\",\n        \"sensorId\": \"fortify:sensorId\",\n        \"sensorName\": \"fortify:sensorName\"\n      }\n    },\n\n    \"Artifact\": {\n      \"@id\": \"schema:DigitalDocument\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"fileName\": \"schema:name\",\n        \"fileSize\": \"schema:contentSize\",\n        \"status\": \"fortify:processingStatus\",\n        \"uploadDate\": \"schema:uploadDate\",\n        \"scanTypes\": \"fortify:scanTypes\"\n      }\n    },\n\n    \"OpenSourceComponent\": {\n      \"@id\": \"spdx:Package\",\n      \"@context\": {\n       \
  \ \"componentName\": \"spdx:name\",\n        \"componentVersion\": \"spdx:versionInfo\",\n        \"license\": \"spdx:licenseDeclared\",\n        \"vulnerabilityCount\": \"fortify:vulnerabilityCount\"\n      }\n    },\n\n    \"User\": {\n      \"@id\": \"schema:Person\",\n      \"@context\": {\n        \"userId\": \"schema:identifier\",\n        \"userName\": \"schema:alternateName\",\n        \"firstName\": \"schema:givenName\",\n        \"lastName\": \"schema:familyName\",\n        \"email\": \"schema:email\"\n      }\n    },\n\n    \"Sensor\": {\n      \"@id\": \"fortify:DastSensor\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"hostName\": \"schema:url\",\n        \"ipAddress\": \"fortify:ipAddress\",\n        \"status\": \"fortify:sensorStatus\",\n        \"webInspectVersion\": \"schema:softwareVersion\",\n        \"operatingSystem\": \"schema:operatingSystem\"\n      }\n    },\n\n    \"ScanPolicy\": {\n      \"@id\"\
  : \"fortify:ScanPolicy\",\n      \"@context\": {\n        \"id\": \"schema:identifier\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/fortify/refs/heads/main/json-ld/fortify-context.jsonld
tags:
- Application Security
- DAST
- DevSecOps
- SAST
- SCA
- Security Testing
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
