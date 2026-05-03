---
api_specs:
- filename: veracode-applications-openapi.yml
  format: yaml
  label: Veracode Applications REST API
  slug: veracode-applications-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-applications-openapi.yml
- filename: veracode-findings-openapi.yml
  format: yaml
  label: Veracode Findings REST API
  slug: veracode-findings-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-findings-openapi.yml
- filename: veracode-identity-openapi.yml
  format: yaml
  label: Veracode Identity REST API
  slug: veracode-identity-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-identity-openapi.yml
- filename: veracode-reporting-openapi.yml
  format: yaml
  label: Veracode Reporting REST API
  slug: veracode-reporting-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/openapi/veracode-reporting-openapi.yml
class_count: 28
classes:
- Application
- SecurityFinding
- Sandbox
- PolicyEvaluation
- SecurityReport
- User
- Team
- applicationGuid
- applicationName
- businessCriticality
- policyName
- policyComplianceStatus
- issueId
- scanType
- severity
- cweId
- cweName
- cvssScore
- violatesPolicy
- findingStatus
- userId
- emailAddress
- userType
- teamId
- teamName
- reportId
- reportType
- reportStatus
context_file: json-ld/veracode-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/json-ld/veracode-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Veracode from Veracode.
layout: jsonld
name: Veracode Context
namespaces:
- prefix: veracode
  uri: https://www.veracode.com/vocab/
- prefix: cwe
  uri: https://cwe.mitre.org/vocab/
- prefix: cvss
  uri: https://www.first.org/cvss/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: firstFoundDate
  type: dateTime
- container: ''
  name: lastSeenDate
  type: dateTime
- container: ''
  name: created
  type: dateTime
- container: ''
  name: modified
  type: dateTime
property_count: 4
provider_name: Veracode
provider_slug: veracode
slug: veracode-context
source_filename: veracode-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"veracode\": \"https://www.veracode.com/vocab/\",\n    \"cwe\": \"https://cwe.mitre.org/vocab/\",\n    \"cvss\": \"https://www.first.org/cvss/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Application\": \"veracode:Application\",\n    \"SecurityFinding\": \"veracode:SecurityFinding\",\n    \"Sandbox\": \"veracode:Sandbox\",\n    \"PolicyEvaluation\": \"veracode:PolicyEvaluation\",\n    \"SecurityReport\": \"veracode:SecurityReport\",\n    \"User\": \"schema:Person\",\n    \"Team\": \"schema:Organization\",\n\n    \"applicationGuid\": \"schema:identifier\",\n    \"applicationName\": \"schema:name\",\n    \"businessCriticality\": \"veracode:businessCriticality\",\n    \"policyName\": \"veracode:policyName\",\n    \"policyComplianceStatus\": \"veracode:policyComplianceStatus\",\n\n    \"issueId\": \"schema:identifier\",\n    \"scanType\": \"veracode:scanType\",\n    \"severity\": \"veracode:severity\"\
  ,\n    \"cweId\": \"cwe:identifier\",\n    \"cweName\": \"cwe:name\",\n    \"cvssScore\": \"cvss:score\",\n    \"violatesPolicy\": \"veracode:violatesPolicy\",\n    \"findingStatus\": \"veracode:findingStatus\",\n    \"firstFoundDate\": {\n      \"@id\": \"veracode:firstFoundDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastSeenDate\": {\n      \"@id\": \"veracode:lastSeenDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n\n    \"userId\": \"schema:identifier\",\n    \"emailAddress\": \"schema:email\",\n    \"userType\": \"veracode:userType\",\n    \"teamId\": \"schema:identifier\",\n    \"teamName\": \"schema:name\",\n\n    \"reportId\": \"schema:identifier\",\n    \"reportType\": \"veracode:reportType\",\n    \"reportStatus\": \"veracode:reportStatus\",\n\n    \"created\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"modified\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/veracode/refs/heads/main/json-ld/veracode-context.jsonld
tags:
- Application Security
- SAST
- DAST
- SCA
- Security Testing
- DevSecOps
- JSON-LD
- Linked Data
- Semantic Web
---
