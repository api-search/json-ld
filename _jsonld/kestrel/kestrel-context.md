---
class_count: 0
classes: []
context_file: json-ld/kestrel-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/json-ld/kestrel-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Kestrel from Kestrel.
layout: jsonld
name: Kestrel Context
namespaces:
- prefix: kestrel
  uri: https://usekestrel.ai/ns/
- prefix: schema
  uri: https://schema.org/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: dcterms
  uri: http://purl.org/dc/terms/
properties:
- container: ''
  name: Incident
  type: ''
- container: ''
  name: Remediation
  type: ''
- container: ''
  name: Cluster
  type: ''
- container: ''
  name: Agent
  type: ''
- container: ''
  name: Integration
  type: ''
property_count: 5
provider_name: Kestrel
provider_slug: kestrel
slug: kestrel-context
source_filename: kestrel-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"kestrel\": \"https://usekestrel.ai/ns/\",\n    \"schema\": \"https://schema.org/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n\n    \"Incident\": {\n      \"@id\": \"kestrel:Incident\",\n      \"@context\": {\n        \"incidentId\": \"kestrel:incidentId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"severity\": \"kestrel:severity\",\n        \"status\": \"kestrel:incidentStatus\",\n        \"cluster\": \"kestrel:cluster\",\n        \"namespace\": \"kestrel:namespace\",\n        \"rootCause\": \"kestrel:rootCause\",\n        \"detectedAt\": {\n          \"@id\": \"dcterms:created\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"resolvedAt\": {\n          \"@id\": \"kestrel:resolvedAt\",\n          \"@type\": \"xsd:dateTime\"\n        },\n        \"tags\": {\n          \"@id\": \"schema:keywords\"\
  ,\n          \"@container\": \"@set\"\n        }\n      }\n    },\n\n    \"Remediation\": {\n      \"@id\": \"kestrel:Remediation\",\n      \"@context\": {\n        \"remediationId\": \"kestrel:remediationId\",\n        \"incidentId\": \"kestrel:incidentId\",\n        \"description\": \"schema:description\",\n        \"pullRequestUrl\": {\n          \"@id\": \"kestrel:pullRequestUrl\",\n          \"@type\": \"@id\"\n        },\n        \"status\": \"kestrel:remediationStatus\",\n        \"appliedAt\": {\n          \"@id\": \"kestrel:appliedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Cluster\": {\n      \"@id\": \"kestrel:Cluster\",\n      \"@context\": {\n        \"clusterId\": \"kestrel:clusterId\",\n        \"name\": \"schema:name\",\n        \"provider\": \"kestrel:cloudProvider\",\n        \"region\": \"kestrel:region\",\n        \"kubernetesVersion\": \"kestrel:kubernetesVersion\",\n        \"operatorVersion\": \"kestrel:operatorVersion\",\n \
  \       \"status\": \"kestrel:clusterStatus\",\n        \"connectedAt\": {\n          \"@id\": \"kestrel:connectedAt\",\n          \"@type\": \"xsd:dateTime\"\n        }\n      }\n    },\n\n    \"Agent\": {\n      \"@id\": \"kestrel:Agent\",\n      \"@context\": {\n        \"agentId\": \"kestrel:agentId\",\n        \"name\": \"schema:name\",\n        \"description\": \"schema:description\",\n        \"agentType\": \"kestrel:agentType\",\n        \"capabilities\": {\n          \"@id\": \"kestrel:capabilities\",\n          \"@container\": \"@set\"\n        },\n        \"status\": \"kestrel:agentStatus\"\n      }\n    },\n\n    \"Integration\": {\n      \"@id\": \"kestrel:Integration\",\n      \"@context\": {\n        \"integrationId\": \"kestrel:integrationId\",\n        \"name\": \"schema:name\",\n        \"integrationType\": \"kestrel:integrationType\",\n        \"status\": \"kestrel:integrationStatus\",\n        \"configuredAt\": {\n          \"@id\": \"kestrel:configuredAt\",\n     \
  \     \"@type\": \"xsd:dateTime\"\n        }\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/kestrel/refs/heads/main/json-ld/kestrel-context.jsonld
tags:
- AI Agents
- Cloud Security
- Incident Response
- Kubernetes
- Observability
- JSON-LD
- Linked Data
- Semantic Web
---
