---
class_count: 5
classes:
- name
- description
- url
- dateCreated
- dateModified
context_file: json-ld/regulatory-templates-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/json-ld/regulatory-templates-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Regulatory Templates from Regulatory Templates.
layout: jsonld
name: Regulatory Templates Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rt
  uri: https://api-evangelist.github.io/regulatory-templates/vocab#
properties:
- container: ''
  name: ComplianceFramework
  type: schema:CreativeWork
- container: ''
  name: PolicyTemplate
  type: schema:CreativeWork
- container: ''
  name: ComplianceControl
  type: schema:Thing
- container: ''
  name: EvidenceItem
  type: schema:CreativeWork
- container: ''
  name: AuditReport
  type: schema:Report
- container: ''
  name: RiskAssessment
  type: schema:Report
property_count: 6
provider_name: Regulatory Templates
provider_slug: regulatory-templates
slug: regulatory-templates-context
source_filename: regulatory-templates-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rt\": \"https://api-evangelist.github.io/regulatory-templates/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"dateCreated\": \"schema:dateCreated\",\n    \"dateModified\": \"schema:dateModified\",\n    \"ComplianceFramework\": {\n      \"@id\": \"rt:ComplianceFramework\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"frameworkId\": \"rt:frameworkId\",\n        \"version\": \"schema:version\",\n        \"issuingBody\": \"schema:publisher\",\n        \"industry\": \"schema:industry\",\n        \"jurisdiction\": \"rt:jurisdiction\",\n        \"controls\": \"rt:controls\",\n        \"certificationRequired\": \"rt:certificationRequired\"\n      }\n    },\n    \"PolicyTemplate\": {\n      \"@id\": \"rt:PolicyTemplate\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\"\
  : {\n        \"templateId\": \"rt:templateId\",\n        \"framework\": \"rt:ComplianceFramework\",\n        \"policyType\": \"rt:policyType\",\n        \"lastReviewDate\": \"schema:dateModified\",\n        \"requiredControls\": \"rt:requiredControls\"\n      }\n    },\n    \"ComplianceControl\": {\n      \"@id\": \"rt:ComplianceControl\",\n      \"@type\": \"schema:Thing\",\n      \"@context\": {\n        \"controlId\": \"rt:controlId\",\n        \"domain\": \"rt:controlDomain\",\n        \"framework\": \"rt:ComplianceFramework\",\n        \"implementationGuidance\": \"rt:implementationGuidance\",\n        \"evidenceRequired\": \"rt:evidenceRequired\",\n        \"automatable\": \"rt:automatable\"\n      }\n    },\n    \"EvidenceItem\": {\n      \"@id\": \"rt:EvidenceItem\",\n      \"@type\": \"schema:CreativeWork\",\n      \"@context\": {\n        \"control\": \"rt:ComplianceControl\",\n        \"collectedDate\": \"schema:dateCreated\",\n        \"source\": \"schema:source\",\n      \
  \  \"evidenceType\": \"rt:evidenceType\",\n        \"status\": \"rt:evidenceStatus\"\n      }\n    },\n    \"AuditReport\": {\n      \"@id\": \"rt:AuditReport\",\n      \"@type\": \"schema:Report\",\n      \"@context\": {\n        \"framework\": \"rt:ComplianceFramework\",\n        \"auditPeriod\": \"rt:auditPeriod\",\n        \"auditor\": \"schema:author\",\n        \"findings\": \"rt:findings\",\n        \"overallStatus\": \"rt:overallStatus\"\n      }\n    },\n    \"RiskAssessment\": {\n      \"@id\": \"rt:RiskAssessment\",\n      \"@type\": \"schema:Report\",\n      \"@context\": {\n        \"scope\": \"rt:assessmentScope\",\n        \"riskLevel\": \"rt:riskLevel\",\n        \"likelihood\": \"rt:likelihood\",\n        \"impact\": \"rt:impact\",\n        \"mitigations\": \"rt:mitigations\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/json-ld/regulatory-templates-context.jsonld
tags:
- Compliance
- Governance
- GDPR
- HIPAA
- ISO 27001
- PCI DSS
- Policy Templates
- Regulatory
- SOC 2
- Templates
- JSON-LD
- Linked Data
- Semantic Web
---
