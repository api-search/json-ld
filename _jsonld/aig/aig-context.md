---
class_count: 4
classes:
- InsurancePolicy
- InsuranceClaim
- RiskProfile
- CyberRiskProfile
context_file: json-ld/aig-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/aig/refs/heads/main/json-ld/aig-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Aig from AIG.
layout: jsonld
name: Aig Context
namespaces:
- prefix: aig
  uri: https://aig.com/schema/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: ''
  name: policyNumber
  type: string
- container: ''
  name: policyType
  type: string
- container: ''
  name: insuredName
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: expirationDate
  type: date
- container: ''
  name: premium
  type: decimal
- container: ''
  name: coverageLimit
  type: decimal
- container: ''
  name: deductible
  type: decimal
- container: ''
  name: claimNumber
  type: string
- container: ''
  name: lossDate
  type: date
- container: ''
  name: lossAmount
  type: decimal
- container: ''
  name: claimStatus
  type: string
- container: ''
  name: naicsCode
  type: string
- container: ''
  name: annualRevenue
  type: decimal
- container: ''
  name: employeeCount
  type: integer
- container: ''
  name: mfaEnabled
  type: boolean
- container: ''
  name: incidentResponsePlan
  type: boolean
property_count: 17
provider_name: AIG
provider_slug: aig
slug: aig-context
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"aig\": \"https://aig.com/schema/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"InsurancePolicy\": \"aig:InsurancePolicy\",\n    \"InsuranceClaim\": \"aig:InsuranceClaim\",\n    \"RiskProfile\": \"aig:RiskProfile\",\n    \"CyberRiskProfile\": \"aig:CyberRiskProfile\",\n    \"policyNumber\": {\n      \"@id\": \"aig:policy_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"policyType\": {\n      \"@id\": \"aig:policy_type\",\n      \"@type\": \"xsd:string\"\n    },\n    \"insuredName\": {\n      \"@id\": \"aig:insured_name\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"aig:effective_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"expirationDate\": {\n      \"@id\": \"aig:expiration_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"premium\": {\n      \"@id\": \"\
  aig:premium\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"coverageLimit\": {\n      \"@id\": \"aig:coverage_limit\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"deductible\": {\n      \"@id\": \"aig:deductible\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"claimNumber\": {\n      \"@id\": \"aig:claim_number\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lossDate\": {\n      \"@id\": \"aig:loss_date\",\n      \"@type\": \"xsd:date\"\n    },\n    \"lossAmount\": {\n      \"@id\": \"aig:loss_amount\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"claimStatus\": {\n      \"@id\": \"aig:claim_status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"naicsCode\": {\n      \"@id\": \"aig:naics_code\",\n      \"@type\": \"xsd:string\"\n    },\n    \"annualRevenue\": {\n      \"@id\": \"aig:annual_revenue\",\n      \"@type\": \"xsd:decimal\"\n    },\n    \"employeeCount\": {\n      \"@id\": \"aig:employee_count\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"mfaEnabled\"\
  : {\n      \"@id\": \"aig:mfa_enabled\",\n      \"@type\": \"xsd:boolean\"\n    },\n    \"incidentResponsePlan\": {\n      \"@id\": \"aig:incident_response_plan\",\n      \"@type\": \"xsd:boolean\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/aig/refs/heads/main/json-ld/aig-context.jsonld
tags:
- Insurance
- Financial Services
- Property Casualty
- Cyber Insurance
- Enterprise
- JSON-LD
- Linked Data
- Semantic Web
---
