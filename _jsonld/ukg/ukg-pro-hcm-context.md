---
api_specs:
- filename: ukg-pro-hcm-openapi.yml
  format: yaml
  label: UKG Pro HCM API
  slug: ukg-pro-hcm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-hcm-openapi.yml
- filename: ukg-pro-wfm-openapi.yml
  format: yaml
  label: UKG Pro Workforce Management API
  slug: ukg-pro-wfm-api
  spec_type: OpenAPI
  url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/openapi/ukg-pro-wfm-openapi.yml
class_count: 13
classes:
- EmployeeIdList
- Employee
- email
- EmployeeList
- EmployeeJob
- PayRate
- BenefitsElection
- DirectDeposit
- PersonnelChangeRequest
- PersonnelChangeResponse
- Department
- Location
- PayStatement
context_file: json-ld/ukg-pro-hcm-context.jsonld
context_url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/json-ld/ukg-pro-hcm-context.jsonld
description: JSON-LD context defining the semantic vocabulary for Ukg Pro Hcm from UKG.
layout: jsonld
name: Ukg Pro Hcm Context
namespaces:
- prefix: ukg
  uri: https://ukg.com/vocab/
- prefix: schema
  uri: https://schema.org/
- prefix: dcterms
  uri: http://purl.org/dc/terms/
- prefix: xsd
  uri: http://www.w3.org/2001/XMLSchema#
properties:
- container: set
  name: employeeIds
  type: string
- container: ''
  name: total
  type: integer
- container: ''
  name: page
  type: integer
- container: ''
  name: employeeId
  type: string
- container: ''
  name: firstName
  type: string
- container: ''
  name: lastName
  type: string
- container: ''
  name: employmentStatus
  type: string
- container: ''
  name: hireDate
  type: date
- container: ''
  name: departmentId
  type: string
- container: ''
  name: locationId
  type: string
- container: ''
  name: jobTitle
  type: string
- container: ''
  name: managerId
  type: string
- container: set
  name: employees
  type: string
- container: ''
  name: jobCode
  type: string
- container: ''
  name: positionId
  type: string
- container: ''
  name: flsaStatus
  type: string
- container: ''
  name: employmentType
  type: string
- container: ''
  name: effectiveDate
  type: date
- container: ''
  name: payType
  type: string
- container: ''
  name: basePay
  type: double
- container: ''
  name: payCurrency
  type: string
- container: ''
  name: payFrequency
  type: string
- container: ''
  name: planId
  type: string
- container: ''
  name: planName
  type: string
- container: ''
  name: benefitType
  type: string
- container: ''
  name: enrollmentStatus
  type: string
- container: ''
  name: coverageTier
  type: string
- container: ''
  name: employeeContribution
  type: double
- container: ''
  name: accountId
  type: string
- container: ''
  name: bankName
  type: string
- container: ''
  name: accountType
  type: string
- container: ''
  name: depositType
  type: string
- container: ''
  name: depositAmount
  type: double
- container: ''
  name: priority
  type: integer
- container: ''
  name: actionType
  type: string
- container: ''
  name: reason
  type: string
- container: ''
  name: newDepartmentId
  type: string
- container: ''
  name: newJobTitle
  type: string
- container: ''
  name: newPayRate
  type: double
- container: ''
  name: requestId
  type: string
- container: ''
  name: status
  type: string
- container: ''
  name: submittedAt
  type: dateTime
- container: ''
  name: departmentName
  type: string
- container: ''
  name: parentDepartmentId
  type: string
- container: ''
  name: costCenterId
  type: string
- container: ''
  name: locationName
  type: string
- container: ''
  name: address
  type: string
- container: ''
  name: city
  type: string
- container: ''
  name: stateProvince
  type: string
- container: ''
  name: country
  type: string
- container: ''
  name: postalCode
  type: string
- container: ''
  name: statementId
  type: string
- container: ''
  name: payPeriodStart
  type: date
- container: ''
  name: payPeriodEnd
  type: date
- container: ''
  name: payDate
  type: date
- container: ''
  name: grossPay
  type: double
- container: ''
  name: netPay
  type: double
- container: ''
  name: federalTaxWithheld
  type: double
- container: ''
  name: stateTaxWithheld
  type: double
- container: ''
  name: socialSecurityTax
  type: double
- container: ''
  name: medicareTax
  type: double
- container: ''
  name: currency
  type: string
property_count: 62
provider_name: UKG
provider_slug: ukg
slug: ukg-pro-hcm-context
source_filename: ukg-pro-hcm-context.jsonld
source_heading: JSON-LD Document
source_json: "{\n  \"@context\": {\n    \"@version\": 1.1,\n    \"ukg\": \"https://ukg.com/vocab/\",\n    \"schema\": \"https://schema.org/\",\n    \"dcterms\": \"http://purl.org/dc/terms/\",\n    \"xsd\": \"http://www.w3.org/2001/XMLSchema#\",\n    \"EmployeeIdList\": \"ukg:EmployeeIdList\",\n    \"employeeIds\": {\n      \"@id\": \"ukg:employeeIds\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"total\": {\n      \"@id\": \"ukg:total\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"page\": {\n      \"@id\": \"ukg:page\",\n      \"@type\": \"xsd:integer\"\n    },\n    \"Employee\": \"ukg:Employee\",\n    \"employeeId\": {\n      \"@id\": \"ukg:employeeId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"firstName\": {\n      \"@id\": \"ukg:firstName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"lastName\": {\n      \"@id\": \"ukg:lastName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"email\": \"schema:email\",\n    \"employmentStatus\": {\n\
  \      \"@id\": \"ukg:employmentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"hireDate\": {\n      \"@id\": \"ukg:hireDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"departmentId\": {\n      \"@id\": \"ukg:departmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"locationId\": {\n      \"@id\": \"ukg:locationId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"jobTitle\": {\n      \"@id\": \"ukg:jobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"managerId\": {\n      \"@id\": \"ukg:managerId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmployeeList\": \"ukg:EmployeeList\",\n    \"employees\": {\n      \"@id\": \"ukg:employees\",\n      \"@container\": \"@set\",\n      \"@type\": \"xsd:string\"\n    },\n    \"EmployeeJob\": \"ukg:EmployeeJob\",\n    \"jobCode\": {\n      \"@id\": \"ukg:jobCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"positionId\": {\n      \"@id\": \"ukg:positionId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"flsaStatus\"\
  : {\n      \"@id\": \"ukg:flsaStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employmentType\": {\n      \"@id\": \"ukg:employmentType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"effectiveDate\": {\n      \"@id\": \"ukg:effectiveDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"PayRate\": \"ukg:PayRate\",\n    \"payType\": {\n      \"@id\": \"ukg:payType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"basePay\": {\n      \"@id\": \"ukg:basePay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"payCurrency\": {\n      \"@id\": \"ukg:payCurrency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payFrequency\": {\n      \"@id\": \"ukg:payFrequency\",\n      \"@type\": \"xsd:string\"\n    },\n    \"BenefitsElection\": \"ukg:BenefitsElection\",\n    \"planId\": {\n      \"@id\": \"ukg:planId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"planName\": {\n      \"@id\": \"ukg:planName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"benefitType\": {\n      \"@id\"\
  : \"ukg:benefitType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"enrollmentStatus\": {\n      \"@id\": \"ukg:enrollmentStatus\",\n      \"@type\": \"xsd:string\"\n    },\n    \"coverageTier\": {\n      \"@id\": \"ukg:coverageTier\",\n      \"@type\": \"xsd:string\"\n    },\n    \"employeeContribution\": {\n      \"@id\": \"ukg:employeeContribution\",\n      \"@type\": \"xsd:double\"\n    },\n    \"DirectDeposit\": \"ukg:DirectDeposit\",\n    \"accountId\": {\n      \"@id\": \"ukg:accountId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"bankName\": {\n      \"@id\": \"ukg:bankName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"accountType\": {\n      \"@id\": \"ukg:accountType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"depositType\": {\n      \"@id\": \"ukg:depositType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"depositAmount\": {\n      \"@id\": \"ukg:depositAmount\",\n      \"@type\": \"xsd:double\"\n    },\n    \"priority\": {\n      \"@id\": \"ukg:priority\"\
  ,\n      \"@type\": \"xsd:integer\"\n    },\n    \"PersonnelChangeRequest\": \"ukg:PersonnelChangeRequest\",\n    \"actionType\": {\n      \"@id\": \"ukg:actionType\",\n      \"@type\": \"xsd:string\"\n    },\n    \"reason\": {\n      \"@id\": \"ukg:reason\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newDepartmentId\": {\n      \"@id\": \"ukg:newDepartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newJobTitle\": {\n      \"@id\": \"ukg:newJobTitle\",\n      \"@type\": \"xsd:string\"\n    },\n    \"newPayRate\": {\n      \"@id\": \"ukg:newPayRate\",\n      \"@type\": \"xsd:double\"\n    },\n    \"PersonnelChangeResponse\": \"ukg:PersonnelChangeResponse\",\n    \"requestId\": {\n      \"@id\": \"ukg:requestId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"status\": {\n      \"@id\": \"ukg:status\",\n      \"@type\": \"xsd:string\"\n    },\n    \"submittedAt\": {\n      \"@id\": \"ukg:submittedAt\",\n      \"@type\": \"xsd:dateTime\"\n    },\n    \"Department\": \"ukg:Department\"\
  ,\n    \"departmentName\": {\n      \"@id\": \"ukg:departmentName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"parentDepartmentId\": {\n      \"@id\": \"ukg:parentDepartmentId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"costCenterId\": {\n      \"@id\": \"ukg:costCenterId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"Location\": \"ukg:Location\",\n    \"locationName\": {\n      \"@id\": \"ukg:locationName\",\n      \"@type\": \"xsd:string\"\n    },\n    \"address\": {\n      \"@id\": \"ukg:address\",\n      \"@type\": \"xsd:string\"\n    },\n    \"city\": {\n      \"@id\": \"ukg:city\",\n      \"@type\": \"xsd:string\"\n    },\n    \"stateProvince\": {\n      \"@id\": \"ukg:stateProvince\",\n      \"@type\": \"xsd:string\"\n    },\n    \"country\": {\n      \"@id\": \"ukg:country\",\n      \"@type\": \"xsd:string\"\n    },\n    \"postalCode\": {\n      \"@id\": \"ukg:postalCode\",\n      \"@type\": \"xsd:string\"\n    },\n    \"PayStatement\": \"ukg:PayStatement\",\n\
  \    \"statementId\": {\n      \"@id\": \"ukg:statementId\",\n      \"@type\": \"xsd:string\"\n    },\n    \"payPeriodStart\": {\n      \"@id\": \"ukg:payPeriodStart\",\n      \"@type\": \"xsd:date\"\n    },\n    \"payPeriodEnd\": {\n      \"@id\": \"ukg:payPeriodEnd\",\n      \"@type\": \"xsd:date\"\n    },\n    \"payDate\": {\n      \"@id\": \"ukg:payDate\",\n      \"@type\": \"xsd:date\"\n    },\n    \"grossPay\": {\n      \"@id\": \"ukg:grossPay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"netPay\": {\n      \"@id\": \"ukg:netPay\",\n      \"@type\": \"xsd:double\"\n    },\n    \"federalTaxWithheld\": {\n      \"@id\": \"ukg:federalTaxWithheld\",\n      \"@type\": \"xsd:double\"\n    },\n    \"stateTaxWithheld\": {\n      \"@id\": \"ukg:stateTaxWithheld\",\n      \"@type\": \"xsd:double\"\n    },\n    \"socialSecurityTax\": {\n      \"@id\": \"ukg:socialSecurityTax\",\n      \"@type\": \"xsd:double\"\n    },\n    \"medicareTax\": {\n      \"@id\": \"ukg:medicareTax\",\n     \
  \ \"@type\": \"xsd:double\"\n    },\n    \"currency\": {\n      \"@id\": \"ukg:currency\",\n      \"@type\": \"xsd:string\"\n    }\n  }\n}"
source_json_url: https://raw.githubusercontent.com/api-evangelist/ukg/refs/heads/main/json-ld/ukg-pro-hcm-context.jsonld
tags:
- Human Capital Management
- HCM
- Workforce Management
- HR
- Payroll
- Time and Attendance
- Benefits
- Scheduling
- JSON-LD
- Linked Data
- Semantic Web
---
