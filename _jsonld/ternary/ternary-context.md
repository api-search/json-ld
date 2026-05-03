---
api_specs:
- filename: ternary-openapi.yml
  format: yaml
  label: Ternary API
  slug: ternary-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ternary/refs/heads/main/openapi/ternary-openapi.yml
class_count: 5
classes:
- id
- name
- description
- Organization
- url
context_file: json-ld/ternary-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ternary/refs/heads/main/json-ld/ternary-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ternary from Ternary.
layout: jsonld
name: Ternary Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: finops
  uri: https://www.finops.org/framework/
- prefix: ternary
  uri: https://ternary.app/api/v1#
- prefix: owl
  uri: http://www.w3.org/2002/07/owl#
- prefix: rdfs
  uri: http://www.w3.org/2000/01/rdf-schema#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: CloudCostAnomaly
  type: reference
- container: ''
  name: CostAllocation
  type: reference
- container: ''
  name: CloudBudget
  type: reference
- container: ''
  name: CloudCommitment
  type: reference
- container: ''
  name: CostReport
  type: reference
- container: ''
  name: cloud_provider
  type: string
- container: ''
  name: service
  type: string
- container: ''
  name: severity
  type: '@vocab'
- container: ''
  name: status
  type: string
- container: ''
  name: expected_cost
  type: decimal
- container: ''
  name: actual_cost
  type: decimal
- container: ''
  name: cost_delta
  type: decimal
- container: ''
  name: amount
  type: decimal
- container: ''
  name: period
  type: string
- container: ''
  name: current_spend
  type: decimal
- container: ''
  name: forecasted_spend
  type: decimal
- container: list
  name: alert_thresholds
  type: ''
- container: ''
  name: detected_at
  type: dateTime
- container: ''
  name: acknowledged_at
  type: dateTime
- container: ''
  name: created_at
  type: dateTime
- container: ''
  name: updated_at
  type: dateTime
- container: ''
  name: commitment_type
  type: '@vocab'
- container: ''
  name: utilization
  type: decimal
- container: ''
  name: savings_vs_on_demand
  type: decimal
- container: list
  name: affected_resources
  type: ''
property_count: 25
provider_name: Ternary
provider_slug: ternary
slug: ternary-context
source_filename: ternary-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"finops\": \"https://www.finops.org/framework/\",\n    \"ternary\": \"https://ternary.app/api/v1#\",\n    \"owl\": \"http://www.w3.org/2002/07/owl#\",\n    \"rdfs\": \"http://www.w3.org/2000/01/rdf-schema#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"CloudCostAnomaly\": {\n      \"@id\": \"ternary:Anomaly\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A detected cloud cost anomaly\"\n    },\n    \"CostAllocation\": {\n      \"@id\": \"ternary:CostAllocation\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A rule for allocating shared cloud costs\"\n    },\n    \"CloudBudget\": {\n      \"@id\": \"ternary:Budget\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A cloud cost budget with thresholds\"\n    },\n    \"CloudCommitment\": {\n      \"@id\": \"ternary:Commitment\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A cloud commitment\
  \ purchase (RI, Savings Plan, CUD)\"\n    },\n    \"CostReport\": {\n      \"@id\": \"ternary:Report\",\n      \"@type\": \"@id\",\n      \"rdfs:comment\": \"A cloud cost analytics report\"\n    },\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"cloud_provider\": {\n      \"@id\": \"ternary:cloudProvider\",\n      \"@type\": \"xsd:string\"\n    },\n    \"service\": {\n      \"@id\": \"ternary:cloudService\",\n      \"@type\": \"xsd:string\"\n    },\n    \"severity\": {\n      \"@id\": \"ternary:severity\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"low\": \"ternary:LowSeverity\",\n        \"medium\": \"ternary:MediumSeverity\",\n        \"high\": \"ternary:HighSeverity\",\n        \"critical\": \"ternary:CriticalSeverity\"\n      }\n    },\n    \"status\": {\n      \"@id\": \"schema:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"expected_cost\": {\n      \"@id\": \"ternary:expectedCost\",\n   \
  \   \"@type\": \"xsd:decimal\"\n    },\n    \"actual_cost\": {\n      \"@id\": \"ternary:actualCost\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"cost_delta\": {\n      \"@id\": \"ternary:costDelta\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"amount\": {\n      \"@id\": \"schema:price\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"period\": {\n      \"@id\": \"ternary:budgetPeriod\",\n      \"@type\": \"xsd:string\"\n    },\n    \"current_spend\": {\n      \"@id\": \"ternary:currentSpend\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"forecasted_spend\": {\n      \"@id\": \"ternary:forecastedSpend\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"alert_thresholds\": {\n      \"@id\": \"ternary:alertThresholds\",\n      \"@container\": \"@list\"\n    },\n    \"detected_at\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"acknowledged_at\": {\n      \"@id\": \"ternary:acknowledgedAt\",\n      \"@type\": \"xsd:dateTime\"\n\
  \    },\n    \"created_at\": {\n      \"@id\": \"schema:dateCreated\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"updated_at\": {\n      \"@id\": \"schema:dateModified\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"commitment_type\": {\n      \"@id\": \"ternary:commitmentType\",\n      \"@type\": \"@vocab\",\n      \"@context\": {\n        \"reserved_instance\": \"ternary:ReservedInstance\",\n        \"savings_plan\": \"ternary:SavingsPlan\",\n        \"committed_use_discount\": \"ternary:CommittedUseDiscount\"\n      }\n    },\n    \"utilization\": {\n      \"@id\": \"ternary:commitmentUtilization\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"savings_vs_on_demand\": {\n      \"@id\": \"ternary:savingsVsOnDemand\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"affected_resources\": {\n      \"@id\": \"ternary:affectedResources\",\n      \"@container\": \"@list\"\n    },\n    \"Organization\": \"schema:Organization\",\n    \"url\": \"schema:url\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ternary/refs/heads/main/json-ld/ternary-context.jsonld
tags:
- Cloud Cost Management
- Cost Optimization
- FinOps
- Google Cloud
- Kubernetes
- Multi-Cloud
- JSON-LD
- Linked Data
- Semantic Web
---
