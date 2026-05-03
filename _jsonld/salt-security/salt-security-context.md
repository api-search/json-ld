---
class_count: 0
classes: []
context_file: json-ld/salt-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/salt-security/refs/heads/main/json-ld/salt-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Salt Security from Salt Security.
layout: jsonld
name: Salt Security Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: salt
  uri: https://api-evangelist.github.io/salt-security/vocab#
- prefix: sec
  uri: https://w3id.org/security#
properties:
- container: ''
  name: APIEndpoint
  type: ''
- container: ''
  name: APIAttack
  type: ''
- container: ''
  name: APIInventory
  type: ''
- container: ''
  name: SecurityPosture
  type: ''
property_count: 4
provider_name: Salt Security
provider_slug: salt-security
slug: salt-security-context
source_filename: salt-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"salt\": \"https://api-evangelist.github.io/salt-security/vocab#\",\n    \"sec\": \"https://w3id.org/security#\",\n\n    \"APIEndpoint\": {\n      \"@id\": \"salt:APIEndpoint\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"method\": \"salt:httpMethod\",\n        \"path\": \"salt:endpointPath\",\n        \"host\": \"salt:hostDomain\",\n        \"api_id\": \"salt:parentApi\",\n        \"api_name\": \"schema:name\",\n        \"status\": \"salt:endpointStatus\",\n        \"is_documented\": \"salt:isDocumented\",\n        \"is_shadow\": \"salt:isShadow\",\n        \"is_zombie\": \"salt:isZombie\",\n        \"sensitive_data\": \"salt:sensitiveData\",\n        \"risk_score\": \"salt:riskScore\",\n        \"vulnerabilities\": \"salt:vulnerabilities\",\n        \"authentication_required\": \"salt:authRequired\",\n        \"\
  first_seen\": {\n          \"@id\": \"schema:dateCreated\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"last_seen\": {\n          \"@id\": \"schema:dateModified\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"APIAttack\": {\n      \"@id\": \"salt:APIAttack\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"attack_type\": \"salt:attackType\",\n        \"severity\": \"salt:severity\",\n        \"status\": \"salt:incidentStatus\",\n        \"source_ip\": \"salt:sourceIP\",\n        \"target_endpoint\": \"salt:targetEndpoint\",\n        \"target_api_id\": \"salt:targetAPI\",\n        \"request_count\": \"salt:requestCount\",\n        \"data_exposed\": \"salt:dataExposed\",\n        \"remediation\": \"salt:remediation\",\n        \"detected_at\": {\n          \"@id\": \"salt:detectedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolved_at\": {\n          \"@id\": \"salt:resolvedAt\",\n          \"@type\": \"\
  xsd:dateTime\"\n        }\n      }\n    },\n\n    \"APIInventory\": {\n      \"@id\": \"salt:APIInventory\",\n      \"@context\": {\n        \"id\": \"@id\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"endpoints\": \"salt:hasEndpoints\",\n        \"risk_score\": \"salt:riskScore\"\n      }\n    },\n\n    \"SecurityPosture\": {\n      \"@id\": \"salt:SecurityPosture\",\n      \"@context\": {\n        \"api_id\": \"salt:forApi\",\n        \"score\": \"salt:postureScore\",\n        \"findings\": \"salt:postureFindings\",\n        \"last_assessed\": {\n          \"@id\": \"salt:lastAssessed\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/salt-security/refs/heads/main/json-ld/salt-security-context.jsonld
tags:
- API Security
- AI
- API Discovery
- Posture Governance
- Threat Protection
- Security
- JSON-LD
- Linked Data
- Semantic Web
---
