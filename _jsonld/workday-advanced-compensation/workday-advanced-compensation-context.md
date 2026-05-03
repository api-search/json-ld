---
api_specs:
- filename: Compensation.yaml
  format: yaml
  label: Workday Advanced Compensation API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/Compensation.yaml
class_count: 31
classes:
- CompensationPlan
- CompensationGrade
- MeritPlan
- BonusPlan
- StockPlan
- CompensationBudget
- CompensationReview
- EmployeeCompensation
- CompensationChangeRequest
- id
- name
- description
- status
- currency
- type
- code
- compensationPlanId
- budgetPercent
- minIncreasePercent
- maxIncreasePercent
- targetPercent
- maxPercent
- awardType
- vestingSchedule
- payFrequency
- compensationGradeId
- organizationId
- employeeId
- employeeName
- changeReason
- comments
context_file: json-ld/workday-advanced-compensation-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-advanced-compensation/refs/heads/main/json-ld/workday-advanced-compensation-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Advanced Compensation from Workday Advanced Compensation.
layout: jsonld
name: Workday Advanced Compensation Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wdcomp
  uri: https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/schema/
properties:
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: endDate
  type: date
- container: ''
  name: startDate
  type: date
- container: ''
  name: minimumPay
  type: double
- container: ''
  name: midpointPay
  type: double
- container: ''
  name: maximumPay
  type: double
- container: ''
  name: budgetAmount
  type: double
- container: ''
  name: allocatedAmount
  type: double
- container: ''
  name: remainingAmount
  type: double
- container: ''
  name: reviewerCount
  type: integer
- container: ''
  name: employeeCount
  type: integer
- container: ''
  name: basePay
  type: double
- container: ''
  name: totalCashCompensation
  type: double
- container: list
  name: payComponents
  type: ''
- container: ''
  name: newBasePay
  type: double
- container: ''
  name: total
  type: integer
- container: list
  name: data
  type: ''
property_count: 17
provider_name: Workday Advanced Compensation
provider_slug: workday-advanced-compensation
slug: workday-advanced-compensation-context
source_filename: workday-advanced-compensation-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wdcomp\": \"https://community.workday.com/sites/default/files/file-hosting/productionapi/Compensation/v41.1/schema/\",\n\n    \"CompensationPlan\": \"wdcomp:CompensationPlan\",\n    \"CompensationGrade\": \"wdcomp:CompensationGrade\",\n    \"MeritPlan\": \"wdcomp:MeritPlan\",\n    \"BonusPlan\": \"wdcomp:BonusPlan\",\n    \"StockPlan\": \"wdcomp:StockPlan\",\n    \"CompensationBudget\": \"wdcomp:CompensationBudget\",\n    \"CompensationReview\": \"wdcomp:CompensationReview\",\n    \"EmployeeCompensation\": \"wdcomp:EmployeeCompensation\",\n    \"CompensationChangeRequest\": \"wdcomp:CompensationChangeRequest\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"wdcomp:status\",\n    \"currency\": \"schema:currency\",\n    \"effectiveDate\": {\n      \"@id\": \"\
  schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:validThrough\",\n      \"@type\": \"xsd:date\"\n    },\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"type\": \"schema:additionalType\",\n    \"code\": \"schema:identifier\",\n\n    \"compensationPlanId\": \"wdcomp:compensationPlanId\",\n    \"budgetPercent\": \"wdcomp:budgetPercent\",\n    \"minIncreasePercent\": \"wdcomp:minIncreasePercent\",\n    \"maxIncreasePercent\": \"wdcomp:maxIncreasePercent\",\n    \"targetPercent\": \"wdcomp:targetPercent\",\n    \"maxPercent\": \"wdcomp:maxPercent\",\n    \"awardType\": \"wdcomp:awardType\",\n    \"vestingSchedule\": \"wdcomp:vestingSchedule\",\n\n    \"minimumPay\": {\n      \"@id\": \"schema:minValue\",\n      \"@type\": \"xsd:double\"\n    },\n    \"midpointPay\": {\n      \"@id\": \"wdcomp:midpointPay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"maximumPay\": {\n      \"\
  @id\": \"schema:maxValue\",\n      \"@type\": \"xsd:double\"\n    },\n    \"payFrequency\": \"wdcomp:payFrequency\",\n    \"compensationGradeId\": \"wdcomp:compensationGradeId\",\n\n    \"organizationId\": \"schema:memberOf\",\n    \"budgetAmount\": {\n      \"@id\": \"wdcomp:budgetAmount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"allocatedAmount\": {\n      \"@id\": \"wdcomp:allocatedAmount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"remainingAmount\": {\n      \"@id\": \"wdcomp:remainingAmount\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"reviewerCount\": {\n      \"@id\": \"wdcomp:reviewerCount\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"employeeCount\": {\n      \"@id\": \"wdcomp:employeeCount\",\n      \"@type\": \"xsd:integer\"\n    },\n\n    \"employeeId\": \"schema:employee\",\n    \"employeeName\": \"schema:name\",\n    \"basePay\": {\n      \"@id\": \"schema:baseSalary\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalCashCompensation\": {\n\
  \      \"@id\": \"wdcomp:totalCashCompensation\",\n      \"@type\": \"xsd:double\"\n    },\n    \"payComponents\": {\n      \"@id\": \"wdcomp:payComponents\",\n      \"@container\": \"@list\"\n    },\n\n    \"changeReason\": \"wdcomp:changeReason\",\n    \"newBasePay\": {\n      \"@id\": \"wdcomp:newBasePay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"comments\": \"schema:comment\",\n\n    \"total\": {\n      \"@id\": \"wdcomp:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"wdcomp:data\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-advanced-compensation/refs/heads/main/json-ld/workday-advanced-compensation-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
