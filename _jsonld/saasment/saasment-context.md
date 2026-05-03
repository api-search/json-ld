---
api_specs:
- filename: saasment-openapi.yml
  format: yaml
  label: Saasment API
  slug: saasment
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/openapi/saasment-openapi.yml
class_count: 26
classes:
- Misconfiguration
- SecurityPosture
- MonitoredApplication
- ComplianceAssessment
- CostRecommendation
- SecurityAlert
- id
- title
- description
- severity
- category
- status
- remediation
- detected_at
- updated_at
- app_name
- posture_score
- misconfiguration_count
- overall_score
- potential_savings
- estimated_annual_savings
- connected
- last_scanned
- compliance_score
- controls_passed
- controls_failed
context_file: json-ld/saasment-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/json-ld/saasment-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Saasment from Saasment.
layout: jsonld
name: Saasment Context
namespaces:
- prefix: saasment
  uri: https://api.saasment.com/vocab/
- prefix: security
  uri: https://w3id.org/security#
properties: []
property_count: 0
provider_name: Saasment
provider_slug: saasment
slug: saasment-context
source_filename: saasment-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@vocab\": \"https://schema.org/\",\n    \"saasment\": \"https://api.saasment.com/vocab/\",\n    \"security\": \"https://w3id.org/security#\",\n\n    \"Misconfiguration\": \"saasment:Misconfiguration\",\n    \"SecurityPosture\": \"saasment:SecurityPosture\",\n    \"MonitoredApplication\": \"saasment:MonitoredApplication\",\n    \"ComplianceAssessment\": \"saasment:ComplianceAssessment\",\n    \"CostRecommendation\": \"saasment:CostRecommendation\",\n    \"SecurityAlert\": \"saasment:SecurityAlert\",\n\n    \"id\": \"@id\",\n    \"title\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"severity\": \"saasment:severity\",\n    \"category\": \"schema:category\",\n    \"status\": \"schema:status\",\n    \"remediation\": \"saasment:remediation\",\n    \"detected_at\": \"schema:startDate\",\n    \"updated_at\": \"schema:dateModified\",\n    \"app_name\": \"schema:applicationName\",\n    \"posture_score\": \"saasment:postureScore\"\
  ,\n    \"misconfiguration_count\": \"saasment:misconfigurationCount\",\n    \"overall_score\": \"saasment:overallScore\",\n    \"potential_savings\": \"saasment:potentialSavings\",\n    \"estimated_annual_savings\": \"saasment:estimatedAnnualSavings\",\n    \"connected\": \"schema:isAccessibleForFree\",\n    \"last_scanned\": \"schema:dateModified\",\n    \"compliance_score\": \"saasment:complianceScore\",\n    \"controls_passed\": \"saasment:controlsPassed\",\n    \"controls_failed\": \"saasment:controlsFailed\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/saasment/refs/heads/main/json-ld/saasment-context.jsonld
tags:
- SaaS Security
- SSPM
- Cloud Security
- Cost Optimization
- Compliance
- Misconfigurations
- JSON-LD
- Linked Data
- Semantic Web
---
