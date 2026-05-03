---
api_specs:
- filename: secureworks-taegis-xdr-openapi.yml
  format: yaml
  label: Secureworks Taegis XDR API
  slug: secureworks-taegis-xdr-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/openapi/secureworks-taegis-xdr-openapi.yml
class_count: 25
classes:
- Alert
- Investigation
- EndpointAsset
- ThreatIntelligence
- id
- severity
- status
- message
- description
- createdAt
- updatedAt
- mitreTactic
- mitreTechnique
- title
- priority
- assignee
- hostname
- operatingSystem
- agentVersion
- type
- value
- confidence
- malicious
- firstSeen
- lastSeen
context_file: json-ld/secureworks-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/json-ld/secureworks-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Secureworks from Secureworks.
layout: jsonld
name: Secureworks Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: taegis
  uri: https://taegis.secureworks.com/vocab/
- prefix: security
  uri: https://w3id.org/security#
properties:
- container: set
  name: assets
  type: ''
- container: set
  name: alerts
  type: ''
- container: set
  name: ipAddresses
  type: ''
property_count: 3
provider_name: Secureworks
provider_slug: secureworks
slug: secureworks-context
source_filename: secureworks-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"taegis\": \"https://taegis.secureworks.com/vocab/\",\n    \"security\": \"https://w3id.org/security#\",\n    \"Alert\": \"taegis:Alert\",\n    \"Investigation\": \"taegis:Investigation\",\n    \"EndpointAsset\": \"taegis:EndpointAsset\",\n    \"ThreatIntelligence\": \"taegis:ThreatIntelligence\",\n    \"id\": \"@id\",\n    \"severity\": \"taegis:severity\",\n    \"status\": \"schema:status\",\n    \"message\": \"schema:description\",\n    \"description\": \"schema:description\",\n    \"createdAt\": \"schema:dateCreated\",\n    \"updatedAt\": \"schema:dateModified\",\n    \"mitreTactic\": \"taegis:mitreTactic\",\n    \"mitreTechnique\": \"taegis:mitreTechnique\",\n    \"assets\": {\n      \"@id\": \"taegis:affectedAssets\",\n      \"@container\": \"@set\"\n    },\n    \"title\": \"schema:name\",\n    \"priority\": \"taegis:priority\"\
  ,\n    \"assignee\": \"schema:agent\",\n    \"alerts\": {\n      \"@id\": \"taegis:associatedAlerts\",\n      \"@container\": \"@set\"\n    },\n    \"hostname\": \"taegis:hostname\",\n    \"ipAddresses\": {\n      \"@id\": \"schema:ipAddressOfSubject\",\n      \"@container\": \"@set\"\n    },\n    \"operatingSystem\": \"schema:operatingSystem\",\n    \"agentVersion\": \"taegis:agentVersion\",\n    \"type\": \"schema:additionalType\",\n    \"value\": \"schema:value\",\n    \"confidence\": \"taegis:confidence\",\n    \"malicious\": \"taegis:malicious\",\n    \"firstSeen\": \"schema:startDate\",\n    \"lastSeen\": \"schema:endDate\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/secureworks/refs/heads/main/json-ld/secureworks-context.jsonld
tags:
- Cybersecurity
- XDR
- Threat Detection
- Security Operations
- Incident Response
- MDR
- Threat Intelligence
- JSON-LD
- Linked Data
- Semantic Web
---
