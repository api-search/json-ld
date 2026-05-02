---
api_specs:
- filename: mcafee-epo-openapi.yml
  format: yaml
  label: McAfee ePO API
  slug: mcafee-epo-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-epo-openapi.yml
- filename: mcafee-mvision-openapi.yml
  format: yaml
  label: McAfee MVISION API
  slug: mcafee-mvision-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-mvision-openapi.yml
- filename: mcafee-web-gateway-openapi.yml
  format: yaml
  label: McAfee Web Gateway API
  slug: mcafee-web-gateway-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-web-gateway-openapi.yml
- filename: mcafee-esm-openapi.yml
  format: yaml
  label: McAfee ESM API
  slug: mcafee-esm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/openapi/mcafee-esm-openapi.yml
class_count: 0
classes: []
context_file: json-ld/mcafee-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/json-ld/mcafee-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Mcafee from McAfee (Trellix).
layout: jsonld
name: Mcafee Context
namespaces:
- prefix: mcafee
  uri: https://www.mcafee.com/schemas/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: ThreatEvent
  type: ''
- container: ''
  name: Endpoint
  type: ''
- container: ''
  name: Policy
  type: ''
- container: ''
  name: Threat
  type: ''
- container: ''
  name: Detection
  type: ''
- container: ''
  name: Device
  type: ''
- container: ''
  name: Alarm
  type: ''
- container: ''
  name: Case
  type: ''
- container: ''
  name: Investigation
  type: ''
- container: ''
  name: Watchlist
  type: ''
property_count: 10
provider_name: McAfee (Trellix)
provider_slug: mcafee
slug: mcafee-context
source_filename: mcafee-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"mcafee\": \"https://www.mcafee.com/schemas/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"ThreatEvent\": {\n      \"@id\": \"mcafee:ThreatEvent\",\n      \"@context\": {\n        \"threatName\": \"mcafee:threatName\",\n        \"threatType\": \"mcafee:threatType\",\n        \"threatSeverity\": {\n          \"@id\": \"mcafee:threatSeverity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"threatActionTaken\": \"mcafee:threatActionTaken\",\n        \"detectedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"receivedAt\": {\n          \"@id\": \"dcterms:dateSubmitted\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"sourceHostName\": \"mcafee:sourceHostName\",\n        \"sourceIPv4\": \"mcafee:sourceIPv4\",\n        \"targetFileName\"\
  : \"mcafee:targetFileName\",\n        \"analyzerName\": \"mcafee:analyzerName\",\n        \"analyzerVersion\": \"mcafee:analyzerVersion\"\n      }\n    },\n\n    \"Endpoint\": {\n      \"@id\": \"mcafee:Endpoint\",\n      \"@context\": {\n        \"computerName\": \"schema:name\",\n        \"ipAddress\": \"mcafee:ipAddress\",\n        \"agentGuid\": \"mcafee:agentGuid\",\n        \"agentVersion\": \"mcafee:agentVersion\",\n        \"agentStatus\": \"mcafee:agentStatus\",\n        \"domainName\": \"mcafee:domainName\",\n        \"userName\": \"schema:name\",\n        \"operatingSystem\": \"mcafee:operatingSystem\",\n        \"lastCommunication\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"systemGroupPath\": \"mcafee:systemGroupPath\",\n        \"complianceStatus\": \"mcafee:complianceStatus\",\n        \"datVersion\": \"mcafee:datVersion\"\n      }\n    },\n\n    \"Policy\": {\n      \"@id\": \"mcafee:Policy\",\n      \"@context\"\
  : {\n        \"objectName\": \"schema:name\",\n        \"productId\": \"mcafee:productId\",\n        \"typeId\": \"mcafee:typeId\",\n        \"productName\": \"mcafee:productName\"\n      }\n    },\n\n    \"Threat\": {\n      \"@id\": \"mcafee:Threat\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"severity\": \"mcafee:severity\",\n        \"status\": \"mcafee:status\",\n        \"detectedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hostName\": \"mcafee:hostName\",\n        \"processName\": \"mcafee:processName\",\n        \"filePath\": \"mcafee:filePath\",\n        \"sha256\": \"mcafee:sha256\",\n        \"mitreAttackTechnique\": \"mcafee:mitreAttackTechnique\"\n      }\n    },\n\n    \"Detection\": {\n      \"@id\": \"mcafee:Detection\",\n      \"@context\": {\n        \"ruleName\": \"mcafee:ruleName\",\n        \"ruleId\": \"mcafee:ruleId\",\n        \"severity\": \"mcafee:severity\",\n       \
  \ \"detectedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"hostName\": \"mcafee:hostName\",\n        \"processName\": \"mcafee:processName\",\n        \"commandLine\": \"mcafee:commandLine\",\n        \"sha256\": \"mcafee:sha256\",\n        \"mitreAttackTactic\": \"mcafee:mitreAttackTactic\",\n        \"mitreAttackTechnique\": \"mcafee:mitreAttackTechnique\"\n      }\n    },\n\n    \"Device\": {\n      \"@id\": \"mcafee:Device\",\n      \"@context\": {\n        \"hostName\": \"schema:name\",\n        \"ipAddress\": \"mcafee:ipAddress\",\n        \"os\": \"mcafee:os\",\n        \"osVersion\": \"mcafee:osVersion\",\n        \"agentVersion\": \"mcafee:agentVersion\",\n        \"healthStatus\": \"mcafee:healthStatus\",\n        \"lastCheckIn\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Alarm\": {\n      \"@id\": \"mcafee:Alarm\",\n      \"@context\"\
  : {\n        \"alarmName\": \"schema:name\",\n        \"triggeredDate\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"severity\": {\n          \"@id\": \"mcafee:severity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"summary\": \"schema:description\",\n        \"assignee\": \"mcafee:assignee\",\n        \"acknowledgedDate\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Case\": {\n      \"@id\": \"mcafee:Case\",\n      \"@context\": {\n        \"summary\": \"schema:description\",\n        \"status\": \"mcafee:status\",\n        \"severity\": {\n          \"@id\": \"mcafee:severity\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"assignee\": \"mcafee:assignee\",\n        \"openTime\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"closeTime\": {\n          \"@id\": \"\
  dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Investigation\": {\n      \"@id\": \"mcafee:Investigation\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"status\": \"mcafee:status\",\n        \"priority\": \"mcafee:priority\",\n        \"createdAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"updatedAt\": {\n          \"@id\": \"dcterms:modified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Watchlist\": {\n      \"@id\": \"mcafee:Watchlist\",\n      \"@context\": {\n        \"name\": \"schema:name\",\n        \"type\": \"mcafee:watchlistType\",\n        \"valueCount\": {\n          \"@id\": \"mcafee:valueCount\",\n          \"@type\": \"xsd:integer\"\n        },\n        \"dynamic\": {\n          \"@id\": \"mcafee:dynamic\",\n          \"@type\": \"xsd:boolean\"\n       \
  \ }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/json-ld/mcafee-context.jsonld
tags:
- Antivirus
- Cybersecurity
- Endpoint Protection
- Security
- Threat Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
