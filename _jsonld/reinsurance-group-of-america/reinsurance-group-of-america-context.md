---
class_count: 4
classes:
- name
- description
- url
- identifier
context_file: json-ld/reinsurance-group-of-america-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/reinsurance-group-of-america/refs/heads/main/json-ld/reinsurance-group-of-america-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Reinsurance Group Of America from Reinsurance Group of America.
layout: jsonld
name: Reinsurance Group Of America Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: rga
  uri: https://api-evangelist.github.io/reinsurance-group-of-america/vocab#
properties:
- container: ''
  name: UnderwritingDecision
  type: schema:Action
- container: ''
  name: InsuranceApplication
  type: schema:InsuranceProduct
- container: ''
  name: HealthDataScore
  type: schema:MedicalEntity
- container: ''
  name: ReinsuranceTreaty
  type: schema:Contract
- container: ''
  name: UnderwritingRule
  type: schema:Rule
- container: ''
  name: Claim
  type: schema:ClaimReview
property_count: 6
provider_name: Reinsurance Group of America
provider_slug: reinsurance-group-of-america
slug: reinsurance-group-of-america-context
source_filename: reinsurance-group-of-america-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"rga\": \"https://api-evangelist.github.io/reinsurance-group-of-america/vocab#\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"url\": \"schema:url\",\n    \"identifier\": \"schema:identifier\",\n    \"UnderwritingDecision\": {\n      \"@id\": \"rga:UnderwritingDecision\",\n      \"@type\": \"schema:Action\",\n      \"@context\": {\n        \"applicationId\": \"rga:applicationId\",\n        \"decisionDate\": \"schema:dateCreated\",\n        \"decision\": \"rga:decision\",\n        \"riskClass\": \"rga:riskClass\",\n        \"riskScore\": \"rga:riskScore\",\n        \"table\": \"rga:mortalityTable\",\n        \"automatedDecision\": \"rga:automatedDecision\"\n      }\n    },\n    \"InsuranceApplication\": {\n      \"@id\": \"rga:InsuranceApplication\",\n      \"@type\": \"schema:InsuranceProduct\",\n      \"@context\": {\n        \"applicantAge\"\
  : \"rga:applicantAge\",\n        \"applicantGender\": \"rga:applicantGender\",\n        \"faceAmount\": \"rga:faceAmount\",\n        \"productType\": \"rga:productType\",\n        \"carrier\": \"schema:provider\",\n        \"submissionDate\": \"schema:dateCreated\"\n      }\n    },\n    \"HealthDataScore\": {\n      \"@id\": \"rga:HealthDataScore\",\n      \"@type\": \"schema:MedicalEntity\",\n      \"@context\": {\n        \"applicationId\": \"rga:applicationId\",\n        \"scoreDate\": \"schema:dateCreated\",\n        \"riskScore\": \"rga:riskScore\",\n        \"scoreRange\": \"rga:scoreRange\",\n        \"dataSource\": \"rga:dataSource\",\n        \"diagnosisCodes\": \"rga:diagnosisCodes\",\n        \"claimsCodes\": \"rga:claimsCodes\"\n      }\n    },\n    \"ReinsuranceTreaty\": {\n      \"@id\": \"rga:ReinsuranceTreaty\",\n      \"@type\": \"schema:Contract\",\n      \"@context\": {\n        \"treatyNumber\": \"rga:treatyNumber\",\n        \"cedant\": \"schema:party\",\n        \"\
  reinsurer\": \"schema:party\",\n        \"effectiveDate\": \"schema:startDate\",\n        \"terminationDate\": \"schema:endDate\",\n        \"quota\": \"rga:quotaShare\",\n        \"retention\": \"rga:retention\",\n        \"jumboLimit\": \"rga:jumboLimit\"\n      }\n    },\n    \"UnderwritingRule\": {\n      \"@id\": \"rga:UnderwritingRule\",\n      \"@type\": \"schema:Rule\",\n      \"@context\": {\n        \"ruleId\": \"rga:ruleId\",\n        \"ruleSet\": \"rga:ruleSet\",\n        \"condition\": \"rga:condition\",\n        \"action\": \"rga:underwritingAction\",\n        \"priority\": \"rga:rulePriority\",\n        \"effectiveDate\": \"schema:startDate\"\n      }\n    },\n    \"Claim\": {\n      \"@id\": \"rga:Claim\",\n      \"@type\": \"schema:ClaimReview\",\n      \"@context\": {\n        \"claimId\": \"rga:claimId\",\n        \"policyNumber\": \"rga:policyNumber\",\n        \"claimType\": \"rga:claimType\",\n        \"claimDate\": \"schema:dateCreated\",\n        \"benefit\": \"\
  schema:amount\",\n        \"status\": \"rga:claimStatus\"\n      }\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/reinsurance-group-of-america/refs/heads/main/json-ld/reinsurance-group-of-america-context.jsonld
tags:
- Financial Services
- Health Insurance
- Insurance Technology
- Life Insurance
- Reinsurance
- Underwriting
- JSON-LD
- Linked Data
- Semantic Web
---
