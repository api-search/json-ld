---
api_specs:
- filename: synopsys-polaris-openapi.yml
  format: yaml
  label: Synopsys Polaris API
  slug: polaris
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/openapi/synopsys-polaris-openapi.yml
- filename: synopsys-cloud-openlink-openapi.yml
  format: yaml
  label: Synopsys Cloud OpenLink API
  slug: cloud-openlink
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/openapi/synopsys-cloud-openlink-openapi.yml
class_count: 25
classes:
- SecurityIssue
- ScanRun
- Project
- Branch
- Entitlement
- LicenseFile
- issueId
- issueType
- severity
- cwe
- cve
- filePath
- lineNumber
- issueStatus
- projectId
- branchId
- scanId
- scanType
- scanStatus
- issueCount
- customerId
- entitlementId
- licenseId
- name
- description
context_file: json-ld/synopsys-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/json-ld/synopsys-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Synopsys from Synopsys.
layout: jsonld
name: Synopsys Context
namespaces:
- prefix: polaris
  uri: https://polaris.synopsys.com/vocab/
properties:
- container: ''
  name: startedAt
  type: schema:DateTime
- container: ''
  name: completedAt
  type: schema:DateTime
- container: ''
  name: expiresAt
  type: schema:DateTime
property_count: 3
provider_name: Synopsys
provider_slug: synopsys
slug: synopsys-context
source_filename: synopsys-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"polaris\": \"https://polaris.synopsys.com/vocab/\",\n    \"SecurityIssue\": \"polaris:SecurityIssue\",\n    \"ScanRun\": \"polaris:ScanRun\",\n    \"Project\": \"schema:SoftwareApplication\",\n    \"Branch\": \"polaris:Branch\",\n    \"Entitlement\": \"polaris:Entitlement\",\n    \"LicenseFile\": \"polaris:LicenseFile\",\n    \"issueId\": \"polaris:issueId\",\n    \"issueType\": \"polaris:issueType\",\n    \"severity\": \"polaris:severity\",\n    \"cwe\": \"polaris:cwe\",\n    \"cve\": \"polaris:cve\",\n    \"filePath\": \"polaris:filePath\",\n    \"lineNumber\": \"polaris:lineNumber\",\n    \"issueStatus\": \"polaris:issueStatus\",\n    \"projectId\": \"polaris:projectId\",\n    \"branchId\": \"polaris:branchId\",\n    \"scanId\": \"polaris:scanId\",\n    \"scanType\": \"polaris:scanType\",\n    \"scanStatus\": \"polaris:scanStatus\",\n    \"issueCount\": \"polaris:issueCount\",\n    \"customerId\": \"polaris:customerId\"\
  ,\n    \"entitlementId\": \"polaris:entitlementId\",\n    \"licenseId\": \"polaris:licenseId\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"startedAt\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"completedAt\": {\n      \"@id\": \"schema:endDate\",\n      \"@type\": \"schema:DateTime\"\n    },\n    \"expiresAt\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"schema:DateTime\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/synopsys/refs/heads/main/json-ld/synopsys-context.jsonld
tags:
- Software Security
- Application Security Testing
- Static Analysis
- Software Composition Analysis
- EDA Tools
- Semiconductor Design
- JSON-LD
- Linked Data
- Semantic Web
---
