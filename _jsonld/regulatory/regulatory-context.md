---
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/regulatory-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-ld/regulatory-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Regulatory from Regulatory.
layout: jsonld
name: Regulatory Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: reg
  uri: https://api-evangelist.github.io/regulatory/vocab#
properties:
- container: ''
  name: RegulatoryReport
  type: schema:Report
- container: ''
  name: ComplianceCheck
  type: schema:Action
- container: ''
  name: RegulatoryRequirement
  type: schema:Legislation
- container: ''
  name: SanctionsCheck
  type: schema:Action
- container: ''
  name: KYCRecord
  type: schema:Thing
- container: ''
  name: TradeReport
  type: schema:Report
property_count: 6
provider_name: Regulatory
provider_slug: regulatory
slug: regulatory-context
source_filename: regulatory-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"reg\": \"https://api-evangelist.github.io/regulatory/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"RegulatoryReport\": {\n      \"@id\": \"reg:RegulatoryReport\",\n      \"@type\": \"schema:Report\",\n      \"@context\": {\n        \"reportType\": \"reg:reportType\",\n        \"regulatoryAuthority\": \"reg:regulatoryAuthority\",\n        \"reportingPeriod\": \"reg:reportingPeriod\",\n        \"submissionDeadline\": \"reg:submissionDeadline\",\n        \"filingStatus\": \"reg:filingStatus\"\n      }\n    },\n    \"ComplianceCheck\": {\n      \"@id\": \"reg:ComplianceCheck\",\n      \"@type\": \"schema:Action\",\n      \"@context\": {\n        \"framework\": \"reg:framework\",\n        \"checkDate\": \"schema:startTime\",\n        \"result\": \"schema:result\",\n\
  \        \"findings\": \"reg:findings\",\n        \"remediationRequired\": \"reg:remediationRequired\"\n      }\n    },\n    \"RegulatoryRequirement\": {\n      \"@id\": \"reg:RegulatoryRequirement\",\n      \"@type\": \"schema:Legislation\",\n      \"@context\": {\n        \"requirementId\": \"reg:requirementId\",\n        \"regulation\": \"reg:sourceRegulation\",\n        \"applicableEntities\": \"reg:applicableEntities\",\n        \"industry\": \"schema:industry\",\n        \"jurisdiction\": \"schema:addressCountry\",\n        \"effectiveDate\": \"schema:legislationDate\"\n      }\n    },\n    \"SanctionsCheck\": {\n      \"@id\": \"reg:SanctionsCheck\",\n      \"@type\": \"schema:Action\",\n      \"@context\": {\n        \"entity\": \"schema:agent\",\n        \"listChecked\": \"reg:sanctionsList\",\n        \"checkDate\": \"schema:startTime\",\n        \"result\": \"schema:result\",\n        \"matchType\": \"reg:matchType\"\n      }\n    },\n    \"KYCRecord\": {\n      \"@id\": \"\
  reg:KYCRecord\",\n      \"@type\": \"schema:Thing\",\n      \"@context\": {\n        \"customer\": \"schema:customer\",\n        \"verificationDate\": \"schema:dateCreated\",\n        \"verificationStatus\": \"reg:verificationStatus\",\n        \"riskRating\": \"reg:riskRating\",\n        \"documentsVerified\": \"reg:documentsVerified\"\n      }\n    },\n    \"TradeReport\": {\n      \"@id\": \"reg:TradeReport\",\n      \"@type\": \"schema:Report\",\n      \"@context\": {\n        \"tradeId\": \"reg:tradeId\",\n        \"reportingFramework\": \"reg:reportingFramework\",\n        \"asset\": \"schema:financialProduct\",\n        \"notionalAmount\": \"schema:amount\",\n        \"currency\": \"schema:currency\",\n        \"reportedDate\": \"schema:dateCreated\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-ld/regulatory-context.jsonld
tags:
- Compliance
- Financial Services
- Governance
- Healthcare Regulation
- Regulatory Reporting
- Risk Management
- RegTech
- JSON-LD
- Linked Data
- Semantic Web
---
