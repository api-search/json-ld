---
api_specs:
- filename: vanta-openapi.yml
  format: yaml
  label: Vanta API
  slug: vanta-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml
- filename: vanta-auditor-openapi.yml
  format: yaml
  label: Vanta Auditor API
  slug: vanta-auditor-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml
class_count: 15
classes:
- id
- title
- description
- name
- severity
- status
- cvssScore
- cveId
- riskLevel
- residualRiskLevel
- reviewStatus
- employmentStatus
- hostname
- osName
- osVersion
context_file: json-ld/vanta-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/json-ld/vanta-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Vanta from Vanta.
layout: jsonld
name: Vanta Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: vanta
  uri: https://api.vanta.com/v1/
properties:
- container: ''
  name: Vulnerability
  type: reference
- container: ''
  name: Control
  type: reference
- container: ''
  name: Framework
  type: reference
- container: ''
  name: Vendor
  type: reference
- container: ''
  name: Person
  type: reference
- container: ''
  name: Computer
  type: reference
- container: ''
  name: url
  type: reference
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: discoveredAt
  type: dateTime
- container: ''
  name: remediatedAt
  type: dateTime
- container: ''
  name: nextReviewDate
  type: date
- container: ''
  name: remediationSlaDate
  type: dateTime
- container: list
  name: affectedResources
  type: ''
- container: ''
  name: hasContract
  type: boolean
- container: ''
  name: hasDpa
  type: boolean
- container: ''
  name: frameworkId
  type: reference
- container: ''
  name: ownerId
  type: reference
- container: ''
  name: testCount
  type: integer
- container: ''
  name: passingTestCount
  type: integer
- container: ''
  name: securityTasksOverdue
  type: integer
- container: ''
  name: trainingCompleted
  type: boolean
- container: ''
  name: backgroundCheckCompleted
  type: boolean
- container: ''
  name: screenlockEnabled
  type: boolean
- container: ''
  name: diskEncryptionEnabled
  type: boolean
- container: ''
  name: antivirusInstalled
  type: boolean
- container: ''
  name: passwordManagerInstalled
  type: boolean
- container: ''
  name: isCompliant
  type: boolean
property_count: 27
provider_name: Vanta
provider_slug: vanta
slug: vanta-context
source_filename: vanta-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"vanta\": \"https://api.vanta.com/v1/\",\n\n    \"Vulnerability\": {\n      \"@id\": \"vanta:Vulnerability\",\n      \"@type\": \"@id\"\n    },\n    \"Control\": {\n      \"@id\": \"vanta:Control\",\n      \"@type\": \"@id\"\n    },\n    \"Framework\": {\n      \"@id\": \"vanta:Framework\",\n      \"@type\": \"@id\"\n    },\n    \"Vendor\": {\n      \"@id\": \"vanta:Vendor\",\n      \"@type\": \"@id\"\n    },\n    \"Person\": {\n      \"@id\": \"vanta:Person\",\n      \"@type\": \"@id\",\n      \"@context\": \"https://schema.org/Person\"\n    },\n    \"Computer\": {\n      \"@id\": \"vanta:Computer\",\n      \"@type\": \"@id\"\n    },\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"name\": \"schema:name\",\n    \"url\": {\n      \"@id\": \"schema:url\",\n      \"@type\"\
  : \"@id\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"discoveredAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"remediatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"nextReviewDate\": {\n      \"@id\": \"schema:expires\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"severity\": \"vanta:severity\",\n    \"status\": \"vanta:status\",\n    \"cvssScore\": \"vanta:cvssScore\",\n    \"cveId\": \"vanta:cveId\",\n    \"remediationSlaDate\": {\n      \"@id\": \"vanta:remediationSlaDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"affectedResources\": {\n      \"@id\": \"vanta:affectedResources\",\n      \"@container\": \"@list\"\n    },\n\n    \"riskLevel\": \"vanta:riskLevel\",\n    \"residualRiskLevel\": \"vanta:residualRiskLevel\",\n    \"reviewStatus\": \"vanta:reviewStatus\",\n    \"hasContract\": {\n\
  \      \"@id\": \"vanta:hasContract\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"hasDpa\": {\n      \"@id\": \"vanta:hasDpa\",\n      \"@type\": \"xsd:boolean\"\n    },\n\n    \"frameworkId\": {\n      \"@id\": \"vanta:framework\",\n      \"@type\": \"@id\"\n    },\n    \"ownerId\": {\n      \"@id\": \"schema:accountablePerson\",\n      \"@type\": \"@id\"\n    },\n    \"testCount\": {\n      \"@id\": \"vanta:testCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"passingTestCount\": {\n      \"@id\": \"vanta:passingTestCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"employmentStatus\": \"vanta:employmentStatus\",\n    \"securityTasksOverdue\": {\n      \"@id\": \"vanta:securityTasksOverdue\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"trainingCompleted\": {\n      \"@id\": \"vanta:trainingCompleted\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"backgroundCheckCompleted\": {\n      \"@id\": \"vanta:backgroundCheckCompleted\",\n      \"@type\": \"xsd:boolean\"\
  \n    },\n\n    \"hostname\": \"vanta:hostname\",\n    \"osName\": \"vanta:osName\",\n    \"osVersion\": \"vanta:osVersion\",\n    \"screenlockEnabled\": {\n      \"@id\": \"vanta:screenlockEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"diskEncryptionEnabled\": {\n      \"@id\": \"vanta:diskEncryptionEnabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"antivirusInstalled\": {\n      \"@id\": \"vanta:antivirusInstalled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"passwordManagerInstalled\": {\n      \"@id\": \"vanta:passwordManagerInstalled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"isCompliant\": {\n      \"@id\": \"vanta:isCompliant\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/json-ld/vanta-context.jsonld
tags:
- Cybersecurity
- Compliance
- Security
- Governance
- Risk Management
- JSON-LD
- Linked Data
- Semantic Web
---
