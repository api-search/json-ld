---
api_specs:
- filename: Benefits.json
  format: json
  label: Workday Benefits API
  slug: ''
  spec_type: OpenAPI
  url: https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/Benefits.json
class_count: 25
classes:
- BenefitPlan
- BenefitEnrollment
- BenefitEnrollmentRequest
- Dependent
- BenefitEvent
- TimeOffPlan
- EmployeeBenefits
- id
- name
- description
- status
- type
- currency
- carrier
- coverageLevel
- employeeId
- employeeName
- planId
- planName
- waiveReason
- firstName
- lastName
- relationship
- eventType
- accrualUnit
context_file: json-ld/workday-benefits-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/workday-benefits/refs/heads/main/json-ld/workday-benefits-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Workday Benefits from Workday Benefits.
layout: jsonld
name: Workday Benefits Context
namespaces:
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
- prefix: schema
  uri: https://schema.org/
- prefix: wdben
  uri: https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/schema/
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
  name: eventDate
  type: date
- container: ''
  name: dateOfBirth
  type: date
- container: ''
  name: employeePremium
  type: double
- container: ''
  name: employerContribution
  type: double
- container: ''
  name: totalEmployeePremium
  type: double
- container: list
  name: dependentIds
  type: ''
- container: list
  name: enrollments
  type: ''
- container: ''
  name: accrualRate
  type: double
- container: ''
  name: maxBalance
  type: double
- container: ''
  name: total
  type: integer
- container: list
  name: data
  type: ''
property_count: 14
provider_name: Workday Benefits
provider_slug: workday-benefits
slug: workday-benefits-context
source_filename: workday-benefits-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"schema\": \"https://schema.org/\",\n    \"wdben\": \"https://community.workday.com/sites/default/files/file-hosting/productionapi/Benefits/v40.2/schema/\",\n\n    \"BenefitPlan\": \"wdben:BenefitPlan\",\n    \"BenefitEnrollment\": \"wdben:BenefitEnrollment\",\n    \"BenefitEnrollmentRequest\": \"wdben:BenefitEnrollmentRequest\",\n    \"Dependent\": \"wdben:Dependent\",\n    \"BenefitEvent\": \"wdben:BenefitEvent\",\n    \"TimeOffPlan\": \"wdben:TimeOffPlan\",\n    \"EmployeeBenefits\": \"wdben:EmployeeBenefits\",\n\n    \"id\": \"@id\",\n    \"name\": \"schema:name\",\n    \"description\": \"schema:description\",\n    \"status\": \"wdben:status\",\n    \"type\": \"schema:additionalType\",\n    \"currency\": \"schema:currency\",\n\n    \"effectiveDate\": {\n      \"@id\": \"schema:validFrom\",\n      \"@type\": \"xsd:date\"\n    },\n    \"endDate\": {\n      \"@id\": \"schema:validThrough\"\
  ,\n      \"@type\": \"xsd:date\"\n    },\n    \"startDate\": {\n      \"@id\": \"schema:startDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"eventDate\": {\n      \"@id\": \"wdben:eventDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"dateOfBirth\": {\n      \"@id\": \"schema:birthDate\",\n      \"@type\": \"xsd:date\"\n    },\n\n    \"carrier\": \"wdben:carrier\",\n    \"coverageLevel\": \"wdben:coverageLevel\",\n\n    \"employeePremium\": {\n      \"@id\": \"wdben:employeePremium\",\n      \"@type\": \"xsd:double\"\n    },\n    \"employerContribution\": {\n      \"@id\": \"wdben:employerContribution\",\n      \"@type\": \"xsd:double\"\n    },\n    \"totalEmployeePremium\": {\n      \"@id\": \"wdben:totalEmployeePremium\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"employeeId\": \"schema:employee\",\n    \"employeeName\": \"schema:name\",\n    \"planId\": \"wdben:planId\",\n    \"planName\": \"schema:name\",\n    \"dependentIds\": {\n      \"@id\": \"wdben:dependentIds\"\
  ,\n      \"@container\": \"@list\"\n    },\n    \"waiveReason\": \"wdben:waiveReason\",\n    \"enrollments\": {\n      \"@id\": \"wdben:enrollments\",\n      \"@container\": \"@list\"\n    },\n\n    \"firstName\": \"schema:givenName\",\n    \"lastName\": \"schema:familyName\",\n    \"relationship\": \"schema:knowsAbout\",\n\n    \"eventType\": \"wdben:eventType\",\n\n    \"accrualRate\": {\n      \"@id\": \"wdben:accrualRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"accrualUnit\": \"wdben:accrualUnit\",\n    \"maxBalance\": {\n      \"@id\": \"wdben:maxBalance\",\n      \"@type\": \"xsd:double\"\n    },\n\n    \"total\": {\n      \"@id\": \"wdben:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"data\": {\n      \"@id\": \"wdben:data\",\n      \"@container\": \"@list\"\n    }\n  }\n}\n"
source_json_url: https://raw.githubusercontent.com/api-evangelist/workday-benefits/refs/heads/main/json-ld/workday-benefits-context.jsonld
tags:
- JSON-LD
- Linked Data
- Semantic Web
---
