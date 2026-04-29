---
class_count: 7
classes:
- AttackCategory
- Scan
- ScanReport
- ScanRequest
- ScanTarget
- ScanTargetRequest
- VulnerabilityFinding
context_file: json-ld/palo-alto-prisma-airs-ai-red-teaming-api-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-airs-ai-red-teaming-api-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Palo Alto Prisma Airs Ai Red Teaming Api from Palo Alto Networks.
layout: jsonld
name: Palo Alto Prisma Airs Ai Red Teaming Api Context
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
- container: set
  name: attackCategories
  type: string
- container: ''
  name: attackCount
  type: integer
- container: ''
  name: attackPrompt
  type: string
- container: ''
  name: attacksExecuted
  type: integer
- container: ''
  name: authConfig
  type: reference
- container: ''
  name: categoryId
  type: string
- container: ''
  name: categoryName
  type: string
- container: set
  name: categorySummaries
  type: reference
- container: ''
  name: completedAt
  type: dateTime
- container: ''
  name: completedAttacks
  type: integer
- container: ''
  name: createdAt
  type: dateTime
- container: ''
  name: credential
  type: string
- container: set
  name: customPrompts
  type: string
- container: ''
  name: description
  type: string
- container: ''
  name: endpointUrl
  type: reference
- container: ''
  name: errorMessage
  type: string
- container: set
  name: examples
  type: string
- container: ''
  name: findingId
  type: string
- container: set
  name: findings
  type: reference
- container: ''
  name: generatedAt
  type: dateTime
- container: ''
  name: headerName
  type: string
- container: ''
  name: max
  type: string
- container: ''
  name: maxAttacksPerCategory
  type: integer
- container: ''
  name: min
  type: string
- container: ''
  name: model
  type: string
- container: ''
  name: modelResponse
  type: string
- container: ''
  name: name
  type: string
- container: ''
  name: overallRiskScore
  type: float
- container: ''
  name: progress
  type: float
- container: ''
  name: remediation
  type: string
- container: ''
  name: riskScore
  type: float
- container: ''
  name: scanId
  type: string
- container: ''
  name: severity
  type: string
- container: ''
  name: severityRange
  type: reference
- container: ''
  name: startedAt
  type: dateTime
- container: ''
  name: status
  type: string
- container: ''
  name: systemPrompt
  type: string
- container: ''
  name: targetId
  type: string
- container: ''
  name: targetName
  type: string
- container: ''
  name: title
  type: string
- container: ''
  name: totalAttacks
  type: integer
- container: ''
  name: totalAttacksExecuted
  type: integer
- container: ''
  name: type
  type: string
- container: ''
  name: updatedAt
  type: dateTime
- container: ''
  name: vulnerabilitiesFound
  type: integer
property_count: 45
provider_name: Palo Alto Networks
provider_slug: palo-alto-networks
slug: palo-alto-prisma-airs-ai-red-teaming-api-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"pan\": \"https://pan.dev/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"AttackCategory\": \"pan:AttackCategory\",\n    \"Scan\": \"pan:Scan\",\n    \"ScanReport\": \"pan:ScanReport\",\n    \"ScanRequest\": \"pan:ScanRequest\",\n    \"ScanTarget\": \"pan:ScanTarget\",\n    \"ScanTargetRequest\": \"pan:ScanTargetRequest\",\n    \"VulnerabilityFinding\": \"pan:VulnerabilityFinding\",\n    \"attackCategories\": {\n      \"@id\": \"pan:attack_categories\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attackCount\": {\n      \"@id\": \"pan:attack_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"attackPrompt\": {\n      \"@id\": \"pan:attack_prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"attacksExecuted\": {\n      \"@id\": \"pan:attacks_executed\",\n      \"@type\"\
  : \"xsd:integer\"\n    },\n    \"authConfig\": {\n      \"@id\": \"pan:auth_config\",\n      \"@type\": \"@id\"\n    },\n    \"categoryId\": {\n      \"@id\": \"pan:category_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categoryName\": {\n      \"@id\": \"pan:category_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"categorySummaries\": {\n      \"@id\": \"pan:category_summaries\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"completedAt\": {\n      \"@id\": \"pan:completed_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"completedAttacks\": {\n      \"@id\": \"pan:completed_attacks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"createdAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"credential\": {\n      \"@id\": \"pan:credential\",\n      \"@type\": \"xsd:string\"\n    },\n    \"customPrompts\": {\n      \"@id\": \"pan:custom_prompts\",\n      \"@container\": \"@set\",\n      \"\
  @type\": \"xsd:string\"\n    },\n    \"description\": {\n      \"@id\": \"schema:description\",\n      \"@type\": \"xsd:string\"\n    },\n    \"endpointUrl\": {\n      \"@id\": \"pan:endpoint_url\",\n      \"@type\": \"@id\"\n    },\n    \"errorMessage\": {\n      \"@id\": \"pan:error_message\",\n      \"@type\": \"xsd:string\"\n    },\n    \"examples\": {\n      \"@id\": \"pan:examples\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findingId\": {\n      \"@id\": \"pan:finding_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"findings\": {\n      \"@id\": \"pan:findings\",\n      \"@container\": \"@set\",\n      \"@type\": \"@id\"\n    },\n    \"generatedAt\": {\n      \"@id\": \"pan:generated_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"headerName\": {\n      \"@id\": \"pan:header_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"max\": {\n      \"@id\": \"pan:max\",\n      \"@type\": \"xsd:string\"\n    },\n    \"maxAttacksPerCategory\"\
  : {\n      \"@id\": \"pan:max_attacks_per_category\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"min\": {\n      \"@id\": \"pan:min\",\n      \"@type\": \"xsd:string\"\n    },\n    \"model\": {\n      \"@id\": \"pan:model\",\n      \"@type\": \"xsd:string\"\n    },\n    \"modelResponse\": {\n      \"@id\": \"pan:model_response\",\n      \"@type\": \"xsd:string\"\n    },\n    \"name\": {\n      \"@id\": \"schema:name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"overallRiskScore\": {\n      \"@id\": \"pan:overall_risk_score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"progress\": {\n      \"@id\": \"pan:progress\",\n      \"@type\": \"xsd:float\"\n    },\n    \"remediation\": {\n      \"@id\": \"pan:remediation\",\n      \"@type\": \"xsd:string\"\n    },\n    \"riskScore\": {\n      \"@id\": \"pan:risk_score\",\n      \"@type\": \"xsd:float\"\n    },\n    \"scanId\": {\n      \"@id\": \"pan:scan_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"\
  @id\": \"pan:severity\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severityRange\": {\n      \"@id\": \"pan:severity_range\",\n      \"@type\": \"@id\"\n    },\n    \"startedAt\": {\n      \"@id\": \"pan:started_at\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"status\": {\n      \"@id\": \"pan:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"systemPrompt\": {\n      \"@id\": \"pan:system_prompt\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetId\": {\n      \"@id\": \"pan:target_id\",\n      \"@type\": \"xsd:string\"\n    },\n    \"targetName\": {\n      \"@id\": \"pan:target_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"title\": {\n      \"@id\": \"pan:title\",\n      \"@type\": \"xsd:string\"\n    },\n    \"totalAttacks\": {\n      \"@id\": \"pan:total_attacks\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"totalAttacksExecuted\": {\n      \"@id\": \"pan:total_attacks_executed\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"type\": {\n\
  \      \"@id\": \"pan:type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"updatedAt\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"vulnerabilitiesFound\": {\n      \"@id\": \"pan:vulnerabilities_found\",\n      \"@type\": \"xsd:integer\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/palo-alto-networks/refs/heads/main/json-ld/palo-alto-prisma-airs-ai-red-teaming-api-context.jsonld
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
