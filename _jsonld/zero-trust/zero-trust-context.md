---
class_count: 21
classes:
- AccessDecision
- Subject
- Device
- Resource
- Signal
- Obligation
- Pdp
- Pep
- Pap
- id
- decision
- ttl_seconds
- evaluated_at
- subject
- device
- resource
- context
- signals
- obligations
- risk_score
- spiffe_id
context_file: json-ld/zero-trust-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/zero-trust/refs/heads/main/json-ld/zero-trust-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Zero Trust from Zero Trust.
layout: jsonld
name: Zero Trust Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: zt
  uri: https://api-evangelist.com/zero-trust/vocab#
properties: []
property_count: 0
provider_name: Zero Trust
provider_slug: zero-trust
slug: zero-trust-context
source_filename: zero-trust-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"zt\": \"https://api-evangelist.com/zero-trust/vocab#\",\n    \"AccessDecision\": \"zt:AccessDecision\",\n    \"Subject\": \"zt:Subject\",\n    \"Device\": \"zt:Device\",\n    \"Resource\": \"zt:Resource\",\n    \"Signal\": \"zt:Signal\",\n    \"Obligation\": \"zt:Obligation\",\n    \"Pdp\": \"zt:PolicyDecisionPoint\",\n    \"Pep\": \"zt:PolicyEnforcementPoint\",\n    \"Pap\": \"zt:PolicyAdministrationPoint\",\n    \"id\": \"@id\",\n    \"decision\": \"zt:decision\",\n    \"ttl_seconds\": \"zt:decisionTtl\",\n    \"evaluated_at\": \"schema:dateCreated\",\n    \"subject\": \"zt:subject\",\n    \"device\": \"zt:device\",\n    \"resource\": \"zt:resource\",\n    \"context\": \"zt:context\",\n    \"signals\": \"zt:signals\",\n    \"obligations\": \"zt:obligations\",\n    \"risk_score\": \"zt:riskScore\",\n    \"spiffe_id\": \"zt:spiffeId\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/zero-trust/refs/heads/main/json-ld/zero-trust-context.jsonld
tags:
- Access Control
- Cloud Security
- Cybersecurity
- Federal
- Identity and Access Management
- Network Security
- Security
- Zero Trust
- JSON-LD
- Linked Data
- Semantic Web
---
