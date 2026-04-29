---
class_count: 0
classes: []
context_file: json-ld/checkmarx-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/json-ld/checkmarx-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Checkmarx from Checkmarx.
layout: jsonld
name: Checkmarx Context
namespaces:
- prefix: checkmarx
  uri: https://checkmarx.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Project
  type: ''
- container: ''
  name: Scan
  type: ''
- container: ''
  name: ScanResult
  type: ''
- container: ''
  name: Vulnerability
  type: ''
- container: ''
  name: Package
  type: ''
- container: ''
  name: Application
  type: ''
- container: ''
  name: Preset
  type: ''
- container: ''
  name: Team
  type: ''
- container: ''
  name: EngineServer
  type: ''
- container: ''
  name: RiskReport
  type: ''
property_count: 10
provider_name: Checkmarx
provider_slug: checkmarx
slug: checkmarx-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"checkmarx\": \"https://checkmarx.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Project\": {\n      \"@id\": \"checkmarx:Project\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"teamId\": \"checkmarx:teamId\",\n        \"isPublic\": {\n          \"@id\": \"checkmarx:isPublic\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"repoUrl\": {\n          \"@id\": \"schema:codeRepository\",\n          \"@type\": \"@id\"\n        },\n        \"mainBranch\": \"checkmarx:mainBranch\",\n        \"criticality\": {\n          \"@id\": \"checkmarx:criticality\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n  \
  \      \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Scan\": {\n      \"@id\": \"checkmarx:Scan\",\n      \"@context\": {\n        \"status\": \"checkmarx:scanStatus\",\n        \"scanType\": \"checkmarx:scanType\",\n        \"branch\": \"checkmarx:branch\",\n        \"engines\": \"checkmarx:engines\",\n        \"initiator\": \"checkmarx:initiator\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"ScanResult\": {\n      \"@id\": \"checkmarx:ScanResult\",\n      \"@context\": {\n        \"severity\": \"checkmarx:severity\",\n        \"status\": \"checkmarx:resultStatus\",\n        \"state\": \"checkmarx:triageState\",\n        \"type\": \"checkmarx:engineType\",\n        \"description\": \"\
  schema:description\",\n        \"queryName\": \"checkmarx:queryName\",\n        \"languageName\": \"checkmarx:languageName\",\n        \"firstFoundAt\": {\n          \"@id\": \"checkmarx:firstFoundAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"foundAt\": {\n          \"@id\": \"checkmarx:foundAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Vulnerability\": {\n      \"@id\": \"checkmarx:Vulnerability\",\n      \"@context\": {\n        \"cveName\": \"checkmarx:cveName\",\n        \"cweId\": {\n          \"@id\": \"checkmarx:cweId\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"description\": \"schema:description\",\n        \"severity\": \"checkmarx:severity\",\n        \"cvssScore\": {\n          \"@id\": \"checkmarx:cvssScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"publishDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hasExploit\"\
  : {\n          \"@id\": \"checkmarx:hasExploit\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Package\": {\n      \"@id\": \"checkmarx:Package\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"version\": \"schema:version\",\n        \"packageRepository\": \"checkmarx:packageRepository\",\n        \"isDirectDependency\": {\n          \"@id\": \"checkmarx:isDirectDependency\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"riskScore\": {\n          \"@id\": \"checkmarx:riskScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"outdated\": {\n          \"@id\": \"checkmarx:outdated\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"licenses\": \"checkmarx:licenses\"\n      }\n    },\n\n    \"Application\": {\n      \"@id\": \"checkmarx:Application\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"criticality\": {\n         \
  \ \"@id\": \"checkmarx:criticality\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Preset\": {\n      \"@id\": \"checkmarx:Preset\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"custom\": {\n          \"@id\": \"checkmarx:custom\",\n          \"@type\": \"xsd:boolean\"\n        }\n      }\n    },\n\n    \"Team\": {\n      \"@id\": \"checkmarx:Team\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"fullName\": \"checkmarx:fullName\",\n        \"parentId\": \"checkmarx:parentId\"\n      }\n    },\n\n    \"EngineServer\": {\n      \"@id\": \"checkmarx:EngineServer\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n    \
  \    \"uri\": {\n          \"@id\": \"schema:url\",\n          \"@type\": \"@id\"\n        },\n        \"isAlive\": {\n          \"@id\": \"checkmarx:isAlive\",\n          \"@type\": \"xsd:boolean\"\n        },\n        \"maxScans\": {\n          \"@id\": \"checkmarx:maxScans\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    },\n\n    \"RiskReport\": {\n      \"@id\": \"checkmarx:RiskReport\",\n      \"@context\": {\n        \"riskScore\": {\n          \"@id\": \"checkmarx:riskScore\",\n          \"@type\": \"xsd:float\"\n        },\n        \"totalPackages\": {\n          \"@id\": \"checkmarx:totalPackages\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"directPackages\": {\n          \"@id\": \"checkmarx:directPackages\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"totalOutdatedPackages\": {\n          \"@id\": \"checkmarx:totalOutdatedPackages\",\n          \"@type\": \"xsd:integer\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/checkmarx/refs/heads/main/json-ld/checkmarx-context.jsonld
tags:
- Application Security
- Code Analysis
- DevSecOps
- SAST
- Security Testing
- Vulnerability Scanning
- JSON-LD
- Linked Data
- Semantic Web
---
