---
api_specs:
- filename: wtw-hr-portal-openapi.yml
  format: yaml
  label: WTW HR Portal
  slug: wtw-hr-portal
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/openapi/wtw-hr-portal-openapi.yml
class_count: 40
classes:
- Employee
- id
- employeeNumber
- firstName
- lastName
- email
- department
- jobTitle
- location
- status
- hireDate
- manager
- TotalRewards
- planYear
- baseSalary
- bonus
- equity
- totalCompensation
- currency
- BenefitEnrollment
- planType
- planName
- enrollmentStatus
- coverageLevel
- employeeContribution
- employerContribution
- effectiveDate
- HRContent
- title
- body
- audience
- publishedAt
- HRCase
- caseNumber
- category
- subject
- description
- priority
- assignedTo
- resolvedAt
context_file: json-ld/towers-watson-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/json-ld/towers-watson-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Towers Watson from Towers Watson.
layout: jsonld
name: Towers Watson Context
namespaces:
- prefix: schema
  uri: https://schema.org/
- prefix: wtw
  uri: https://api.wtwco.com/vocab#
- prefix: hr
  uri: https://www.wtwco.com/hr-ontology#
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties: []
property_count: 0
provider_name: Towers Watson
provider_slug: towers-watson
slug: towers-watson-context
source_filename: towers-watson-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"schema\": \"https://schema.org/\",\n    \"wtw\": \"https://api.wtwco.com/vocab#\",\n    \"hr\": \"https://www.wtwco.com/hr-ontology#\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n\n    \"Employee\": \"schema:Person\",\n    \"id\": \"@id\",\n    \"employeeNumber\": \"wtw:employeeNumber\",\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"email\": \"schema:workEmail\",\n    \"department\": \"schema:department\",\n    \"jobTitle\": \"schema:jobTitle\",\n    \"location\": \"schema:workLocation\",\n    \"status\": \"wtw:employmentStatus\",\n    \"hireDate\": \"schema:startDate\",\n    \"manager\": \"schema:reportsTo\",\n\n    \"TotalRewards\": \"wtw:TotalRewardsStatement\",\n    \"planYear\": \"wtw:planYear\",\n    \"baseSalary\": \"schema:baseSalary\",\n    \"bonus\": \"wtw:bonusCompensation\",\n    \"equity\": \"wtw:equityCompensation\",\n    \"totalCompensation\": \"wtw:totalCompensation\"\
  ,\n    \"currency\": \"schema:priceCurrency\",\n\n    \"BenefitEnrollment\": \"schema:Permit\",\n    \"planType\": \"wtw:benefitPlanType\",\n    \"planName\": \"schema:name\",\n    \"enrollmentStatus\": \"wtw:enrollmentStatus\",\n    \"coverageLevel\": \"wtw:coverageLevel\",\n    \"employeeContribution\": \"wtw:employeeContribution\",\n    \"employerContribution\": \"wtw:employerContribution\",\n    \"effectiveDate\": \"schema:validFrom\",\n\n    \"HRContent\": \"schema:CreativeWork\",\n    \"title\": \"schema:name\",\n    \"body\": \"schema:text\",\n    \"audience\": \"schema:audience\",\n    \"publishedAt\": \"schema:datePublished\",\n\n    \"HRCase\": \"schema:Action\",\n    \"caseNumber\": \"schema:identifier\",\n    \"category\": \"schema:additionalType\",\n    \"subject\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"priority\": \"wtw:casePriority\",\n    \"assignedTo\": \"schema:agent\",\n    \"resolvedAt\": \"schema:endTime\"\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/towers-watson/refs/heads/main/json-ld/towers-watson-context.jsonld
tags:
- Human Resources
- Risk Management
- Benefits
- Consulting
- Actuarial
- Insurance Brokerage
- Human Capital
- JSON-LD
- Linked Data
- Semantic Web
---
