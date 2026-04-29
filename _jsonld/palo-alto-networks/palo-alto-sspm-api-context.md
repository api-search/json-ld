---
class_count: 6
classes:
- CatalogApp
- JiraIntegration
- JiraIntegrationRequest
- OnboardAppRequest
- OnboardedApp
- PostureCheck
context_file: json-ld/palo-alto-sspm-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sspm-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Sspm Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Sspm Api Context
namespaces:
- prefix: pan
  uri: https://pan.dev/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: apiToken
  type: string
- container: ''
  name: appId
  type: string
- container: ''
  name: appType
  type: string
- container: ''
  name: category
  type: string
- container: ''
  name: checkCount
  type: integer
- container: ''
  name: checkId
  type: string
- container: ''
  name: checkName
  type: string
- container: ''
  name: checkSummary
  type: reference
- container: ''
  name: checkType
  type: string
- container: set
  name: complianceFrameworks
  type: string
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: credentials
  type: reference
- container: ''
  name: critical
  type: integer
- container: ''
  name: description
  type: string
- container: ''
  name: displayName
  type: string
- container: ''
  name: email
  type: string
- container: ''
  name: enabled
  type: boolean
- container: ''
  name: high
  type: integer
- container: ''
  name: id
  type: string
- container: ''
  name: issueType
  type: string
- container: ''
  name: jiraUrl
  type: reference
- container: ''
  name: lastEvaluatedAt
  type: dateTime
- container: ''
  name: lastScannedAt
  type: dateTime
- container: ''
  name: logoUrl
  type: reference
- container: ''
  name: low
  type: integer
- container: ''
  name: medium
  type: integer
- container: ''
  name: name
  type: string
- container: ''
  name: onboardedAt
  type: dateTime
- container: ''
  name: pass
  type: integer
- container: ''
  name: projectKey
  type: string
- container: ''
  name: remediation
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: severityMapping
  type: reference
- container: ''
  name: status
  type: string
- container: ''
  name: suppressionJustification
  type: string
- container: ''
  name: tenantId
  type: string
property_count: 36
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-sspm-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"CatalogApp\": \"pan:CatalogApp\",\n    \"JiraIntegration\": \"pan:JiraIntegration\",\n    \"JiraIntegrationRequest\": \"pan:JiraIntegrationRequest\",\n    \"OnboardAppRequest\": \"pan:OnboardAppRequest\",\n    \"OnboardedApp\": \"pan:OnboardedApp\",\n    \"PostureCheck\": \"pan:PostureCheck\",\n    \"apiToken\": {\n      \"@id\": \"pan:api_token\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appId\": {\n      \"@id\": \"pan:app_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"appType\": {\n      \"@id\": \"pan:app_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"category\": {\n      \"@id\": \"pan:category\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkCount\": {\n      \"@id\": \"pan:check_count\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"checkId\": {\n      \"@id\": \"pan:check_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkName\": {\n      \"@id\": \"pan:check_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"checkSummary\": {\n      \"@id\": \"pan:check_summary\",\n      \"@type\": \"@id\"\n    },\n    \"checkType\": {\n      \"@id\": \"pan:check_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"complianceFrameworks\": {\n      \"@id\": \"pan:compliance_frameworks\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"credentials\": {\n      \"@id\": \"pan:credentials\",\n      \"@type\": \"@id\"\n    },\n    \"critical\": {\n      \"@id\": \"pan:critical\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"displayName\": {\n \
  \     \"@id\": \"pan:display_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": {\n      \"@id\": \"schema:email\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enabled\": {\n      \"@id\": \"pan:enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"high\": {\n      \"@id\": \"pan:high\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"id\": {\n      \"@id\": \"pan:id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"issueType\": {\n      \"@id\": \"pan:issue_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jiraUrl\": {\n      \"@id\": \"pan:jira_url\",\n      \"@type\": \"@id\"\n    },\n    \"lastEvaluatedAt\": {\n      \"@id\": \"pan:last_evaluated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"lastScannedAt\": {\n      \"@id\": \"pan:last_scanned_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"logoUrl\": {\n      \"@id\": \"pan:logo_url\",\n      \"@type\": \"@id\"\n    },\n    \"low\": {\n      \"@id\": \"pan:low\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"medium\": {\n      \"@id\": \"pan:medium\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"onboardedAt\": {\n      \"@id\": \"pan:onboarded_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"pass\": {\n      \"@id\": \"pan:pass\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"projectKey\": {\n      \"@id\": \"pan:project_key\",\n      \"@type\": \"xsd:string\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityMapping\": {\n      \"@id\": \"pan:severity_mapping\",\n      \"@type\": \"@id\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"suppressionJustification\": {\n      \"@id\": \"pan:suppression_justification\",\n      \"@type\"\
  : \"xsd:string\"\n    },\n    \"tenantId\": {\n      \"@id\": \"pan:tenant_id\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-sspm-api-context.jsonld
tags:
- Cloud Security
- Cybersecurity
- Firewall
- Network Security
- SASE
- SOAR
- Threat Intelligence
- XDR
- JSON-LD
- Linked Data
- Semantic Web
---
