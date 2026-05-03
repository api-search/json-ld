---
class_count: 16
classes:
- Alert
- Integration
- id
- type
- severity
- status
- title
- description
- application
- risk_score
- compliance_frameworks
- remediation
- created_at
- updated_at
- permissions
- last_scanned
context_file: json-ld/valence-security-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-ld/valence-security-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Valence Security from Valence Security.
layout: jsonld
name: Valence Security Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: security
  uri: https://www.w3.org/ns/ssn/
properties: []
property_count: 0
provider_name: Valence Security
provider_slug: valence-security
slug: valence-security-context
source_filename: valence-security-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://valencesecurity.com/vocab#\",\n    \"schema\": \"https://schema.org/\",\n    \"security\": \"https://www.w3.org/ns/ssn/\",\n    \"Alert\": \"schema:Alert\",\n    \"Integration\": \"schema:SoftwareApplication\",\n    \"id\": \"@id\",\n    \"type\": \"@type\",\n    \"severity\": \"schema:additionalProperty\",\n    \"status\": \"schema:status\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"application\": \"schema:applicationCategory\",\n    \"risk_score\": \"schema:ratingValue\",\n    \"compliance_frameworks\": \"schema:additionalType\",\n    \"remediation\": \"schema:actionOption\",\n    \"created_at\": \"schema:dateCreated\",\n    \"updated_at\": \"schema:dateModified\",\n    \"permissions\": \"schema:permissions\",\n    \"last_scanned\": \"schema:dateModified\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/valence-security/refs/heads/main/json-ld/valence-security-context.jsonld
tags:
- SaaS Security
- SSPM
- AI Security
- Identity Security
- ITDR
- Posture Management
- Risk Remediation
- JSON-LD
- Linked Data
- Semantic Web
---
