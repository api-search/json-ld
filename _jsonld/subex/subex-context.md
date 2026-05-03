---
api_specs:
- filename: subex-revenue-assurance-openapi.yml
  format: yaml
  label: Subex Revenue Assurance & Fraud Management API
  slug: subex-revenue-assurance-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/openapi/subex-revenue-assurance-openapi.yml
class_count: 30
classes:
- FraudCase
- LeakageAlert
- SubscriberRiskScore
- ReconciliationRun
- Subscriber
- caseId
- fraudType
- status
- riskScore
- subscriberMsisdn
- imsi
- currency
- indicators
- actions
- assignedTo
- leakageId
- leakageType
- severity
- serviceType
- affectedRecordCount
- controlName
- msisdn
- riskCategory
- contributingFactors
- runId
- runType
- matchRate
- totalRecordsProcessed
- matchedRecords
- unmatchedRecords
context_file: json-ld/subex-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/json-ld/subex-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Subex from Subex.
layout: jsonld
name: Subex Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: subex
  uri: https://www.subex.com/vocab/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: detectedAt
  type: dateTime
- container: ''
  name: estimatedFraudLoss
  type: decimal
- container: ''
  name: estimatedLoss
  type: decimal
property_count: 3
provider_name: Subex
provider_slug: subex
slug: subex-context
source_filename: subex-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"subex\": \"https://www.subex.com/vocab/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"FraudCase\": \"subex:FraudCase\",\n    \"LeakageAlert\": \"subex:RevenueLeakageAlert\",\n    \"SubscriberRiskScore\": \"subex:SubscriberRiskProfile\",\n    \"ReconciliationRun\": \"subex:ReconciliationRun\",\n    \"Subscriber\": \"schema:Person\",\n\n    \"caseId\": \"schema:identifier\",\n    \"fraudType\": \"subex:fraudType\",\n    \"status\": \"schema:status\",\n    \"riskScore\": \"subex:riskScore\",\n    \"detectedAt\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"subscriberMsisdn\": \"subex:msisdn\",\n    \"imsi\": \"subex:imsi\",\n    \"estimatedFraudLoss\": {\n      \"@id\": \"subex:estimatedLoss\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"currency\": \"schema:currency\",\n    \"indicators\": \"subex:fraudIndicators\"\
  ,\n    \"actions\": \"subex:caseActions\",\n    \"assignedTo\": \"schema:contributor\",\n\n    \"leakageId\": \"schema:identifier\",\n    \"leakageType\": \"subex:leakageType\",\n    \"severity\": \"schema:significance\",\n    \"estimatedLoss\": {\n      \"@id\": \"subex:estimatedRevenueLoss\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"serviceType\": \"subex:serviceType\",\n    \"affectedRecordCount\": \"subex:affectedRecords\",\n    \"controlName\": \"subex:controlName\",\n\n    \"msisdn\": \"subex:msisdn\",\n    \"riskCategory\": \"subex:riskCategory\",\n    \"contributingFactors\": \"subex:riskFactors\",\n\n    \"runId\": \"schema:identifier\",\n    \"runType\": \"subex:reconciliationType\",\n    \"matchRate\": \"subex:matchRate\",\n    \"totalRecordsProcessed\": \"subex:recordsProcessed\",\n    \"matchedRecords\": \"subex:matchedRecords\",\n    \"unmatchedRecords\": \"subex:unmatchedRecords\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/subex/refs/heads/main/json-ld/subex-context.jsonld
tags:
- Telecom
- Revenue Assurance
- Fraud Management
- Analytics
- BSS/OSS
- JSON-LD
- Linked Data
- Semantic Web
---
